#### Test 79426650616b042_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-05 15:17:00.085  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
08-05 15:17:00.094  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 15:17:00.094  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-05 15:17:00.096  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-05 15:17:00.098  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 15:17:06.103  6858  6858 D AndroidRuntime: 
08-05 15:17:06.103  6858  6858 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-05 15:17:06.106  6858  6858 D AndroidRuntime: CheckJNI is OFF
08-05 15:17:06.226  6858  6858 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-05 15:17:06.231  1035  2048 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 15:17:06.255  1941  1957 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-05 15:17:06.263  1035  2048 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-05 15:17:06.264  1035  2048 D ActivityManager: setTaskToReturnTo : TaskRecord{3615f601 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 15:17:06.264  1035  2048 D ActivityManager: setTaskToReturnTo : TaskRecord{3615f601 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 15:17:06.265  1035  2048 D WindowStateEx: AppWindowTokenEx init.. 
08-05 15:17:06.266   344   365 E GBMv2   : DFP En is all cleared set to be enabled
08-05 15:17:06.290  1035  2048 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6877 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-05 15:17:06.293  6858  6858 D AndroidRuntime: Shutting down VM
08-05 15:17:06.345  1941  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-05 15:17:06.345  1941  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{d12ad59 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 15:17:06.345  1941  2538 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-05 15:17:06.346  1941  2538 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2d9b1d1e co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 15:17:06.444  6877  6877 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-05 15:17:06.547  6877  6877 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-05 15:17:06.558  6877  6877 I LibraryLoader: Loading: webviewchromium
08-05 15:17:06.562  6877  6877 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 9835-9840)
,08-05 15:17:06.563  6877  6877 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 15:17:06.581  6877  6877 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2a9df96f}
,08-05 15:17:06.583  6877  6877 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 15:17:06.584  6877  6877 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 15:17:06.596  6877  6877 I BrowserStartupController: Initializing chromium process, renderers=0
,08-05 15:17:06.597  6877  6877 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 15:17:06.609  6877  6877 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-05 15:17:06.610  6877  6877 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-05 15:17:06.610  6877  6877 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-05 15:17:06.621   323  2160 V AudioPolicyService: registerClient() client 0xb1025da0, uid 10118
08-05 15:17:06.632  6877  6877 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 15:17:06.632  6877  6877 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 15:17:06.632  6877  6877 I Adreno-EGL: Build Date: 12/12/14 금
08-05 15:17:06.632  6877  6877 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 15:17:06.632  6877  6877 I Adreno-EGL: Remote Branch: 
08-05 15:17:06.632  6877  6877 I Adreno-EGL: Local Patches: 
08-05 15:17:06.632  6877  6877 I Adreno-EGL: Reconstruct Branch: 
,08-05 15:17:06.637  1035  1111 D BluetoothManagerService: Message: 20
08-05 15:17:06.637  1035  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ff1ba83:true
08-05 15:17:06.728  6877  6914 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-05 15:17:06.735  6877  6877 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-05 15:17:06.752  6877  6877 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 15:17:06.757  6877  6877 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-05 15:17:06.761  6877  6877 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-05 15:17:06.763  6877  6877 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-05 15:17:06.763  6877  6877 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-05 15:17:06.777  6877  6877 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-05 15:17:06.786  6877  6877 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 15:17:06.786  6877  6877 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 15:17:06.819  6877  6926 D OpenGLRenderer: Render dirty regions requested: true
08-05 15:17:06.819  6877  6926 I OpenGLRenderer: Initialized EGL, version 1.4
08-05 15:17:06.825  6877  6926 D OpenGLRenderer: Enabling debug mode 0
08-05 15:17:06.832  6877  6877 D Atlas   : Validating map...
,08-05 15:17:06.837  1035  1914 D SplitWindow: check instance of lgWin Window{2dde9b65 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 15:17:06.844  1035  1092 W ActivityManager: Activity pause timeout for ActivityRecord{3e143ca6 u0 com.test.thalitest/.MainActivity t40}
,08-05 15:17:06.915  6877  6924 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 15:17:06.915  6877  6924 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 15:17:06.946  1035  1112 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +602ms (total +679ms)
08-05 15:17:06.946  1035  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3e143ca6 u0 com.test.thalitest/.MainActivity t40} time:320224
,08-05 15:17:06.948  6877  6877 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2c2efb0a time:320225
08-05 15:17:07.128  6877  6877 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 15:17:07.218  6877  6924 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-05 15:17:07.218  6877  6924 I chromium: 
,08-05 15:17:07.388  6877  6940 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435139584
,08-05 15:17:07.405  6877  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 15:17:07.405  6877  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 15:17:07.405  6877  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 15:17:07.405  6877  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 15:17:07.405  6877  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-05 15:17:07.405  6877  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bab1ae added. We now have 1 listener(s)
08-05 15:17:07.407  6877  6877 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-05 15:17:07.407  6877  6877 I chromium: 
,08-05 15:17:07.413  1035  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:07.416  6877  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-05 15:17:07.421  6877  6940 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-05 15:17:07.423  6877  6940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 15:17:07.424  6877  6940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 15:17:07.433  6877  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 15:17:07.433  6877  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 15:17:07.433  6877  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 15:17:07.433  6877  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-05 15:17:07.433  6877  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 15:17:07.433  6877  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 15:17:07.433  6877  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 15:17:07.433  6877  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 15:17:07.433  6877  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 15:17:07.433  6877  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 15:17:07.433  6877  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 15:17:07.433  6877  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 15:17:07.433  6877  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 15:17:07.433  6877  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-05 15:17:07.433  6877  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7758fe5 added. We now have 1 listener(s)
08-05 15:17:07.434  6877  6940 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 15:17:07.439  1035  1545 D WifiService: New client listening to asynchronous messages
08-05 15:17:07.443  6877  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 15:17:07.444  6877  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-05 15:17:07.445  6877  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 15:17:07.445  6877  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-05 15:17:07.446  6877  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-05 15:17:07.454  6877  6940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 15:17:07.457  1035  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 15:17:07.459  6877  6940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-05 15:17:07.470  6877  6940 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-05 15:17:07.473  6877  6940 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 15:17:07.473  6877  6940 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:07.473  6877  6940 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:07.473  6877  6940 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:07.473  6877  6940 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:07.473  6877  6940 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:07.473  6877  6940 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 15:17:07.473  6877  6940 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 15:17:07.473  6877  6940 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 15:17:07.473  6877  6940 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 15:17:07.477  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:07.479  6877  6940 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 15:17:07.480  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:07.488   344   367 E GBMv2   : DFP En is all cleared set to be enabled
08-05 15:17:07.488   344   367 E GBMv2   : Set value is all cleared set the max
08-05 15:17:07.488   344   367 I GBMv2   : DFP Enabled. Ignore VFP set
,08-05 15:17:07.533  6877  6877 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 15:17:08.502  6877  6943 W jxcore-log: Initializing JXcore engine
08-05 15:17:08.502  6877  6943 W jxcore-log: JXcore engine is ready
,08-05 15:17:08.532  6943  6943 W Thread-817: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8428]" dev="sockfs" ino=8428 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-05 15:17:08.532  6943  6943 W Thread-817: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-05 15:17:08.532  6943  6943 W Thread-817: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7628]" dev="sockfs" ino=7628 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-05 15:17:08.532  6943  6943 W Thread-817: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-05 15:17:08.532  6943  6943 W Thread-817: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33222]" dev="sockfs" ino=33222 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-05 15:17:08.568  6877  6943 W jxcore-log: Starting JXcore engine
,08-05 15:17:08.674  6877  6943 W jxcore-log: Platform android
08-05 15:17:08.674  6877  6943 W jxcore-log: 
08-05 15:17:08.674  6877  6943 W jxcore-log: Process ARCH arm
08-05 15:17:08.674  6877  6943 W jxcore-log: 
,08-05 15:17:08.910  6877  6943 I jxcore-log: JXcore Cordova bridge is ready!
08-05 15:17:08.910  6877  6943 I jxcore-log: 
08-05 15:17:08.910  6877  6943 W jxcore-log: JXcore engine is started
,08-05 15:17:08.923  6877  6940 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-05 15:17:08.926  6877  6877 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 15:17:21.170  1035  3520 I LocationManagerService: remove 2c24385f
08-05 15:17:21.170  1035  3520 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-05 15:17:21.171  1035  3520 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 15:17:21.171  1035  3520 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-05 15:17:21.178  1035  3520 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-05 15:17:21.178  1035  3520 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-05 15:17:24.673  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 15:17:24.673  6877  6943 I jxcore-log: 
,08-05 15:17:24.676  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 15:17:24.676  6877  6943 I jxcore-log: 
08-05 15:17:24.683  6877  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 15:17:24.683  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:24.683  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:24.683  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:24.683  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:24.683  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:24.683  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 15:17:24.683  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 15:17:24.685  6877  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:24.687  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 15:17:24.687  6877  6943 I jxcore-log: 
08-05 15:17:24.689  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 15:17:24.689  6877  6943 I jxcore-log: 
,08-05 15:17:25.025  6877  6943 D ExecuteNativeTests: Running unit tests
,08-05 15:17:25.107  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,08-05 15:17:25.107  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e added. We now have 2 listener(s),
08-05 15:17:25.108  1035  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 15:17:25.110  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-05 15:17:25.110  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 15:17:25.110  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
,08-05 15:17:25.110  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:25.110  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f added. We now have 2 listener(s)
,08-05 15:17:25.110  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-05 15:17:25.111  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 15:17:25.113  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 15:17:25.115  6877  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-05 15:17:25.115  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:25.115  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:25.115  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-05 15:17:25.115  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:25.115  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,08-05 15:17:25.115  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 15:17:25.115  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 15:17:25.116  6877  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:25.116  6877  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 15:17:25.118  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:25.119  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 15:17:25.121  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 15:17:25.123  6877  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 15:17:25.123  6877  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 15:17:25.125  6877  6943 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-05 15:17:25.126  6877  6943 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 15:17:25.126  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 15:17:25.126  6877  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 15:17:25.126  6877  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 15:17:25.127  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.127  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.127  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.128  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.128  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.128  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 15:17:25.128  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 15:17:25.128  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e removed from the list
08-05 15:17:25.128  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.128  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f removed from the list
08-05 15:17:25.128  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.128  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.129  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.129  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.129  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.129  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.129  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.129  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.131  6877  6943 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-05 15:17:25.131  6877  6943 I io.jxcore.node.Connec,tionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.131  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.131  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.131  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.131  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.131  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.131  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.131  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.131  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.131  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.132  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.132  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.132  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.132  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.134  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.134  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.134  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.134  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 15:17:25.138  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 15:17:25.139  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 15:17:25.139  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 15:17:25.139  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 15:17:25.139  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 15:17:25.139  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.139  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.139  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.139  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.139  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.139  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.139  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.139  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.139  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.139  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.139  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.139  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.139  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.139  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.141  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.141  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.141  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.141  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.141  6877  6943 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 15:17:25.142  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 15:17:25.144  6877  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 15:17:25.144  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:25.144  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:25.144  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:25.144  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:25.144  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:25.144  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 15:17:25.144  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 15:17:25.146  6877  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:25.146  6877  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 15:17:25.147  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:25.148  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:25.148  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 15:17:25.148  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 15:17:25.148  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 15:17:25.148  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 15:17:25.148  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 15:17:25.151  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 15:17:25.151  1035  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:25.155  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 15:17:25.158  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 15:17:25.160  6877  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 15:17:25.160  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 15:17:25.161  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 15:17:25.162  6877  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 15:17:25.162  6877  6943 I io.jxcore.node.ConnectionHelper: start: OK
08-05 15:17:25.164  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.164  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.164  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.164  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.164  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.164  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 15:17:25.165  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.165  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.165  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.165  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.165  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.165  6877  6943 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 15:17:25.166  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 15:17:25.168  6877  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 15:17:25.168  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:25.168  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:25.168  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:25.168  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:25.168  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:25.168  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 15:17:25.168  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 15:17:25.169  6877  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:25.169  6877  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 15:17:25.170  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:25.171  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:25.171  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 15:17:25.171  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 15:17:25.171  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 15:17:25.171  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 15:17:25.171  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 15:17:25.174  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 15:17:25.174  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 15:17:25.175  6877  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 15:17:25.175  6877  6943 I io.jxcore.node.ConnectionHelper: start: OK
08-05 15:17:25.176  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.177  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.177  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.177  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.177  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.177  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 15:17:25.177  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.177  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.177  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.177  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.177  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.177  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.177  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.178  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.178  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.179  6877  6943 D BluetoothLeScanner: could not find callback wrapper
08-05 15:17:25.179  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 15:17:25.179  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.179  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.179  6877  6943 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 15:17:25.181  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 15:17:25.183  6877  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 15:17:25.183  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:25.183  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:25.183  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:25.183  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:25.183  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:25.183  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 15:17:25.183  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 15:17:25.184  6877  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:25.184  6877  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 15:17:25.185  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:25.186  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:25.186  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 15:17:25.186  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 15:17:25.186  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 15:17:25.186  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 15:17:25.186  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 15:17:25.189  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 15:17:25.189  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 15:17:25.190  6877  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 15:17:25.190  6877  6943 I io.jxcore.node.ConnectionHelper: start: OK
08-05 15:17:25.190  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.190  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.190  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.191  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.191  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.191  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.191  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.191  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.191  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 15:17:25.191  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.191  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.191  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.191  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.191  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.192  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.192  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.192  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.192  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.193  6877  6943 D BluetoothLeScanner: could not find callback wrapper
08-05 15:17:25.193  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 15:17:25.193  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.193  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.193  6877  6943 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-05 15:17:25.193  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.193  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.193  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.194  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.194  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.194  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.194  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.194  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.194  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.194  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.194  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothMana,ger: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.194  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.194  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.194  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.195  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.195  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.195  6877  6943 D BluetoothLeScanner: could not find callback wrapper
08-05 15:17:25.195  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 15:17:25.195  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.195  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.196  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 15:17:25.196  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.196  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.196  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.196  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.196  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.196  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.196  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.196  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.196  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.196  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.196  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.196  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.196  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.196  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.197  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.197  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.198  6877  6943 D BluetoothLeScanner: could not find callback wrapper
08-05 15:17:25.198  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-05 15:17:25.198  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.198  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.198  6877  6943 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-05 15:17:25.199  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.199  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.199  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.199  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 15:17:25.199  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.199  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.199  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.199  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.199  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.199  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 15:17:25.199  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.199  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.199  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.199  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-05 15:17:25.200  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.200  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.200  6877  6943 D BluetoothLeScanner: could not find callback wrapper
08-05 15:17:25.200  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 15:17:25.200  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 15:17:25.200  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.201  6877  6943 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-05 15:17:25.201  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 15:17:25.201  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.201  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 15:17:25.201  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.201  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.201  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.201  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.201  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.201  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.201  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.201  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.201  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.201  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.201  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.202  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.202  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.202  6877  6943 D BluetoothLeScanner: could not find callback wrapper
08-05 15:17:25.203  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 15:17:25.203  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.203  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.203  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 15:17:25.203  6877  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 15:17:25.203  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 15:17:25.203  6877  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-05 15:17:25.203  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 15:17:25.203  6877  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 15:17:25.203  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.203  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.203  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.204  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.204  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.204  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.204  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.204  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.204  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.204  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 15:17:25.204  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.204  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.204  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.204  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.205  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.205  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.205  6877  6943 D BluetoothLeScanner: could not find callback wrapper
08-05 15:17:25.205  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 15:17:25.205  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.205  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.206  6877  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-05 15:17:25.206  6877  6943 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 15:17:25.206  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 15:17:25.208  6877  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 15:17:25.208  6877  6943 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 15:17:25.208  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 15:17:25.209  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 15:17:25.209  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 15:17:25.209  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 15:17:25.209  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-05 15:17:25.209  6877  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-05 15:17:25.209  6877  6943 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 15:17:25.209  6877  6943 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-05 15:17:25.209  6877  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 15:17:25.209  6877  6943 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 15:17:25.209  6877  6943 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-05 15:17:25.209  6877  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 15:17:25.209  6877  6943 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 15:17:25.209  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-05 15:17:25.211  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-05 15:17:25.212  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-05 15:17:25.212  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-05 15:17:25.213  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-05 15:17:25.213  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-05 15:17:25.213  6877  6943 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-05 15:17:25.213  6877  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 15:17:25.213  6877  6943 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-05 15:17:25.214  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.214  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.214  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.214  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.214  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-05 15:17:25.214  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.214  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-05 15:17:25.214  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.214  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.215  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.215  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.215  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 15:17:25.215  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.215  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.215  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.215  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.215  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.216  6877  6943 D BluetoothLeScanner: could not find callback wrapper
08-05 15:17:25.216  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 15:17:25.216  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.216  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.216  6877  6943 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-05 15:17:25.217  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.217  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.217  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.218  6877  6946 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 881
08-05 15:17:25.218  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 15:17:25.218  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.218  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.218  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.218  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.218  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.218  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.218  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.218  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.218  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.218  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.219  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 15:17:25.219  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.219  6877  6943 D BluetoothLeScanner: could not find callback wrapper
08-05 15:17:25.219  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 15:17:25.219  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.219  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.220  6877  6943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-05 15:17:25.221  6877  6945 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 881)
08-05 15:17:25.221  6877  6945 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 881)
08-05 15:17:25.225  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.225  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.225  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 15:17:25.225  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.225  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.225  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.225  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.225  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.225  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.225  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.225  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.227  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.227  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.227  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 15:17:25.228  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.228  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.229  6877  6943 D BluetoothLeScanner: could not find callback wrapper
08-05 15:17:25.229  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 15:17:25.229  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.229  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.231  6877  6943 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-05 15:17:25.231  6877  6943 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-05 15:17:25.232  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 15:17:25.232  6877  6943 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,08-05 15:17:25.232  6877  6943 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 15:17:25.233  6877  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-05 15:17:25.233  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 15:17:25.233  6877  6943 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-05 15:17:25.234  6877  6943 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 15:17:25.234  6877  6943 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 15:17:25.234  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 15:17:25.234  6877  6943 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-05 15:17:25.234  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.234  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.234  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.234  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.234  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.234  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.234  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.235  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.235  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
,08-05 15:17:25.235  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.235  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.235  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.235  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.235  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.236  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.236  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 15:17:25.236  6877  6943 D BluetoothLeScanner: could not find callback wrapper
08-05 15:17:25.236  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 15:17:25.236  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.236  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.236  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.236  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.236  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.236  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.236  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.237  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.237  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.237  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 15:17:25.237  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.237  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.237  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.237  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.237  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.237  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.237  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.237  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.237  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.237  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.237  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.237  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 15:17:25.237  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.237  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.237  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.237  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.237  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.237  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.237  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.237  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.237  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.238  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.238  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 15:17:25.239  6877  6943 D BluetoothLeScanner: could not find callback wrapper
08-05 15:17:25.239  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 15:17:25.239  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.239  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.240  6877  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-05 15:17:25.240  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 15:17:25.241  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-05 15:17:25.241  6877  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-05 15:17:25.241  6877  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-05 15:17:25.242  6877  6877 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-05 15:17:25.242  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-05 15:17:25.242  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 15:17:25.243  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.243  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-05 15:17:25.243  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-05 15:17:25.243  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-05 15:17:25.243  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.243  6877  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-05 15:17:25.243  6877  6877 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-05 15:17:25.243  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.243  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.243  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 15:17:25.243  6877  6943 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 15:17:25.244  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 15:17:25.246  1035  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 15:17:25.246  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 15:17:25.246  6877  6943 D BluetoothLeScanner: could not find callback wrapper
,08-05 15:17:25.246  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-05 15:17:25.246  6877  6943 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 15:17:25.246  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.246  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.247  6877  6952 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 15:17:25.247  6877  6943 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 15:17:25.247  6877  6877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 15:17:25.247  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.247  6877  6877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 15:17:25.247  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.247  6877  6877 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 15:17:25.247  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.247  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.247  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.247  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.247  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.248  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.248  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.248  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.248  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.248  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 15:17:25.248  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.248  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.248  4299  4325 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-05 15:17:25.248  6877  6952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-05 15:17:25.248  6877  6952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-05 15:17:25.248  6877  6952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-05 15:17:25.249  6877  6877 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-05 15:17:25.248  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.250  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.250  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.250  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.250  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.250  6877  6943 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-05 15:17:25.251  6877  6943 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 15:17:25.251  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 15:17:25.252  6877  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 15:17:25.252  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 15:17:25.252  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.252  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.252  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.252  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.252  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.252  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.252  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.252  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.252  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.252  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.252  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.252  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.252  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.253  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.253  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 15:17:25.253  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.253  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.254  1035  1644 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:25.254  1035  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:25.255  1035  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:25.255  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.255  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.255  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.255  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:25.255  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.255  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 15:17:25.255  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.255  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.255  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.255  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.255  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.256  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.256  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.256  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.257  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.257  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.257  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 15:17:25.257  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.257  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:25.257  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:25.257  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:25.258  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 15:17:25.258  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 15:17:25.258  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.258  6877  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75c76e not in the list
08-05 15:17:25.258  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.258  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.258  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:25.258  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.258  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 15:17:25.258  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:25.258  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:25.258  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:25.258  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:25.258  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:25.258  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10fd9e0f not in the list
08-05 15:17:25.259  6877  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-05 15:17:25.259  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-05 15:17:25.260  6877  6943 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-05 15:17:25.260  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 15:17:25.260  6877  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-05 15:17:25.260  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 15:17:25.261  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 15:17:25.261  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-05 15:17:25.262  6877  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-05 15:17:25.262  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-05 15:17:25.262  6877  6943 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-05 15:17:25.262  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 15:17:25.262  6877  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-05 15:17:25.262  6877  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-05 15:17:25.263  6877  6943 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-05 15:17:25.263  6877  6943 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-05 15:17:25.263  6877  6943 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-05 15:17:25.263  6877  6943 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-05 15:17:25.263  6877  6943 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-05 15:17:25.263  6877  6943 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-05 15:17:25.264  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:25.264  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24249534 added. We now have 2 listener(s)
08-05 15:17:25.264  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 15:17:25.265  6877  6943 D BluetoothAdapter: enable(): BT is already enabled..!
08-05 15:17:25.265  1035  1977 D WifiServiceImplEx: setWifiEnabled: true pid=6877, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 15:17:25.266  1035  1977 D WifiService: setWifiEnabled: true pid=6877, uid=10118
,08-05 15:17:25.266  1035  1977 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 15:17:25.267  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:25.267  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23418f5d added. We now have 3 listener(s)
08-05 15:17:25.267  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 15:17:25.269  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:25.269  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b8690d2 added. We now have 4 listener(s)
08-05 15:17:25.269  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 15:17:25.270  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:25.270  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2cd7d5a3 added. We now have 5 listener(s)
08-05 15:17:25.270  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 15:17:25.272  1035  1977 D WifiServiceImplEx: setWifiEnabled: false pid=6877, uid=10118, package= com.test.thalitest, App Lable : ThaliTest,
08-05 15:17:25.272  1035  1977 D WifiService: setWifiEnabled: false pid=6877, uid=10118
08-05 15:17:25.272  1035  1977 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 15:17:25.280  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 15:17:25.281  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 15:17:25.281  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-05 15:17:25.282  1035  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 15:17:25.282  1035  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 15:17:25.282  1035  2014 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@38ee88bc mBinding = false
08-05 15:17:25.282  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 15:17:25.283  1035  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-05 15:17:25.283  1035  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-05 15:17:25.284  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-05 15:17:25.284  1035  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-05 15:17:25.284  1035  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 15:17:25.284  1035  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-05 15:17:25.285  1035  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 15:17:25.285  1035  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 15:17:25.288  1035  1111 D BluetoothManagerService: Message: 2
08-05 15:17:25.288  1035  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 15:17:25.289  1035  1111 D BluetoothManagerService: Sending off request.
08-05 15:17:25.289  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:25.289  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:25.289  4299  4325 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-05 15:17:25.289  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 15:17:25.289  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 15:17:25.289  2733  2733 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 15:17:25.289  4299  4415 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-05 15:17:25.289  4299  4415 D BluetoothAdapterProperties: Setting state to 13
08-05 15:17:25.289  4299  4415 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 15:17:25.290  1035  1111 D BluetoothManagerService: Message: 60
08-05 15:17:25.290  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-05 15:17:25.290  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-05 15:17:25.290  4299  4415 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 15:17:25.290  1035  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 15:17:25.290  1035  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 15:17:25.290  4299  4415 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-05 15:17:25.290  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 15:17:25.290  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-05 15:17:25.291  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 15:17:25.291  1035  1539 D WifiNative-wlan0: SET ps 1: returned true
08-05 15:17:25.292  1035  2864 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:25.293  4299  4419 D BluetoothAdapterProperties: Scan Mode:20
08-05 15:17:25.293  4299  4415 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 15:17:25.294  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 15:17:25.295  4299  4299 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:25.295  4299  4299 D BluetoothMapService: STATE_TURNING_OFF
08-05 15:17:25.295  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:25.295  4299  4415 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 15:17:25.296  4299  4733 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 15:17:25.296  4299  4677 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-05 15:17:25.296  4299  4677 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 15:17:25.296  4299  4677 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-05 15:17:25.296  4299  4677 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(Blue,toothSocket.java:563)
08-05 15:17:25.296  4299  4677 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-05 15:17:25.296  4299  4677 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-05 15:17:25.296  4299  4677 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-05 15:17:25.296  4299  4677 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-05 15:17:25.297  4299  4736 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 15:17:25.297  4299  4678 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 15:17:25.297  4299  4734 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 15:17:25.297  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-05 15:17:25.297  4299  4299 V BtOppService: Receiver DISABLED_ACTION 
08-05 15:17:25.297  4299  4299 V BluetoothMapService: Handler(): got msg=4
08-05 15:17:25.297  4299  4299 D BluetoothMapService: MAP Service closeService in
08-05 15:17:25.297  4299  4299 D BluetoothMapMasInstance: MAP Service shutdown
08-05 15:17:25.297  4299  4522 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-05 15:17:25.298  4299  4299 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 15:17:25.298  4299  4299 V BluetoothMapService: MAP Service closeService out
08-05 15:17:25.299  4299  4299 I BtOppRfcommListener: stopping Accept Thread
08-05 15:17:25.299  4299  4299 V BtOppRfcommListener: close mBtServerSocket
08-05 15:17:25.299  4299  4299 V BtOppRfcommListener: waiting for thread to terminate
08-05 15:17:25.299  4299  4733 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-05 15:17:25.299  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 15:17:25.299  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 15:17:25.299  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 15:17:25.299  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 15:17:25.299  4299  4522 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 15:17:25.299  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 15:17:25.299  4299  4522 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 15:17:25.299  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 15:17:25.299  4299  4522 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 15:17:25.299  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-05 15:17:25.299  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-05 15:17:25.299  4299  4522 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-05 15:17:25.300  4299  4299 V BtOppRfcommListener: done waiting for thread to terminate
08-05 15:17:25.302   318   894 D CommandListener: Clearing all IP addresses on wlan0
,08-05 15:17:25.325  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:25.325  6877  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 15:17:25.325  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:25.325  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:25.325  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:25.325  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 15:17:25.325  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:25.325  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 15:17:25.325  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 15:17:25.326  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:25.326  6877  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:25.326  6877  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 15:17:25.327  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:25.328  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:25.329  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:25.329  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:25.329  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:25.329  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:25.329  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:25.329  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 15:17:25.329  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:25.329  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 15:17:25.329  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 15:17:25.330  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:25.330  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:25.331  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 15:17:25.340  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-05 15:17:25.341  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-05 15:17:25.341  1035  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6961 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 15:17:25.344  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:25.344  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:25.344  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:25.344  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:25.344  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:25.344  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 15:17:25.344  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 15:17:25.344  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 15:17:25.344  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 15:17:25.345  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:25.345  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 15:17:25.347  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:25.347  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:25.347  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:25.347  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:25.347  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:25.347  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 15:17:25.347  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 15:17:25.347  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 15:17:25.347  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 15:17:25.347  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:25.347  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 15:17:25.350  1035  1781 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-05 15:17:25.350  1035  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:25.350  1035  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=,com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:25.350  1035  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-05 15:17:25.350  1035  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:25.351  1035  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,08-05 15:17:25.385  1035  1546 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-05 15:17:25.385  1035  1546 D DSQN    : disableDataServiceNotify
08-05 15:17:25.385  1035  1546 D DSQN    : stop dsqn bin
,08-05 15:17:25.386   318  6985 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 15:17:25.386  1035  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 15:17:25.386  1035  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-05 15:17:25.390  1035  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6984 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-05 15:17:25.390  4299  4299 V BtOppService: onDestroy
08-05 15:17:25.391  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-05 15:17:25.392  1035  1546 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-05 15:17:25.392  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:25.392  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:25.393  1035  1546 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:25.393  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-05 15:17:25.393  1035  1546 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-05 15:17:25.393  1035  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:25.393  1035  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:25.393  1035  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-05 15:17:25.393  1604  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-05 15:17:25.393  1035  1546 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-05 15:17:25.393  1035  1546 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-05 15:17:25.394  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 15:17:25.394  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:25.394  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:25.394  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 15:17:25.397  1035  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 15:17:25.397  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 15:17:25.397  1035  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:25.397  1035  1546 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:25.398  1035  1546 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 15:17:25.398  4299  4299 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-05 15:17:25.399  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-05 15:17:25.399  1035  1546 D NetworkManagementService: Removing idletimer
08-05 15:17:25.399  1035  1546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:25.399  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:25.400  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 15:17:25.400  1035  1546 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-05 15:17:25.401  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:25.401  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:25.401  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 15:17:25.402  1035  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 15:17:25.402  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 15:17:25.402  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 15:17:25.402  1035  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 15:17:25.403  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 15:17:25.403  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 15:17:25.403  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:25.403  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:25.404  1035  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@21699fa5
08-05 15:17:25.404  1035  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:25.404  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:25.404  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:25.404  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:25.404  1035  1538 D LGWifiP2pService: P2pDisablingState
08-05 15:17:25.404  1035  1538 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:25.404  1035  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:25.404  1035  1538 D LGWifiP2pService: p2p socket connection lost
08-05 15:17:25.404  1035  1538 D LGWifiP2pService: P2pDisabledState
08-05 15:17:25.405  1035  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:25.405  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:25.405  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:25.405  1035  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPRO,PERTIES 0 0
08-05 15:17:25.406  1035  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-05 15:17:25.406  1035  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:25.406  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:25.406  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:25.406  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:25.407  1035  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:25.407  1035  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:25.407  1035  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 15:17:25.407  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:25.407  1035  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-05 15:17:25.407  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 15:17:25.407  2733  2733 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 15:17:25.408  1035  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:25.408  1035  1538 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:25.408  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 15:17:25.408  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 15:17:25.408  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 15:17:25.408  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-05 15:17:25.409  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-05 15:17:25.409  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-05 15:17:25.409  1035  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:25.409  1035  1558 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:25.409  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 15:17:25.410  1941  1941 D WfdsService: WifiP2pState is changed : false
08-05 15:17:25.410  1941  2352 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-05 15:17:25.410  1941  2352 D WfdsService: Set the WFDS Monitor: false
08-05 15:17:25.410  1941  2352 D WfdsMonitor: WFDS Monitor is stopped
08-05 15:17:25.410  1941  2352 D WfdsService: STATE : WfdsDisabledState - enter
08-05 15:17:25.411  1941  2800 D CtrlSupplicant: Received on exit socket, terminate
08-05 15:17:25.411  1941  2800 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-05 15:17:25.411  1941  2800 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-05 15:17:25.411  1941  2800 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-05 15:17:25.411  1035  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 15:17:25.411  1035  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 15:17:25.411  1941  2356 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-05 15:17:25.411  1941  2352 W WfdsService: DefaultState - msg [9445378] is not handled
08-05 15:17:25.411  1035  1539 D WifiNative-wlan0: SET ps 1: returned true
08-05 15:17:25.412   318   894 D CommandListener: Clearing all IP addresses on wlan0
08-05 15:17:25.414  1035  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-05 15:17:25.414  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-05 15:17:25.415  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:25.415  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:25.415  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 15:17:25.416  1035  1539 D WifiNative-p2p0: TERMINATE: returned true
08-05 15:17:25.416  1035  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 15:17:25.416  1035  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 15:17:25.416  1035  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-05 15:17:25.426  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-05 15:17:25.426  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-05 15:17:25.426  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 15:17:25.426  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-05 15:17:25.428  6961  6961 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 15:17:25.428  6961  6961 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-05 15:17:25.428  6961  6961 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 15:17:25.428  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:25.428  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:25.428  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:25.428  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:25.428  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 15:17:25.428  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 15:17:25.428  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 15:17:25.428  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 15:17:25.428  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 15:17:25.428  6961  6961 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-05 15:17:25.429  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:25.429  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 15:17:25.430  6961  6961 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 15:17:25.430  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:25.430  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:25.430  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:25.430  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:25.430  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 15:17:25.430  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 15:17:25.430  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 15:17:25.430  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 15:17:25.430  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 15:17:25.431  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:25.431  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NO,T_CARE, BSSID name: null
08-05 15:17:25.432  6961  6961 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 15:17:25.446  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 15:17:25.446  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:25.447  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 15:17:25.461  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 15:17:25.462  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:25.462  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:25.466  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 15:17:25.466  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:25.472  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 15:17:25.488  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 15:17:25.489  6984  6984 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 15:17:25.489  6984  6984 W LG Account v2.2: No ProfileInfo entries
08-05 15:17:25.489  6984  6984 I LG Account v2.2: isEnabled: false
08-05 15:17:25.490  6984  6984 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 15:17:25.490  6984  6984 I Feature : [Lifetracker]Country: EU
08-05 15:17:25.490  6984  6984 I Feature : [Lifetracker]Operator: OPEN
08-05 15:17:25.490  6984  6984 I Feature : [Lifetracker]Ranking support: false
08-05 15:17:25.490  6984  6984 I Feature : [Lifetracker]Comfort support: false
08-05 15:17:25.490  6984  6984 I Feature : [Lifetracker]Accessory: true
08-05 15:17:25.490  6984  6984 I Feature : [Lifetracker]Health device: true
08-05 15:17:25.490  6984  6984 I Feature : [Lifetracker]Extra Pedometer: false
08-05 15:17:25.490  6984  6984 I Feature : [Lifetracker]Blood glucose device: false
08-05 15:17:25.490  6984  6984 I Feature : [Lifetracker]Device Number: 3
08-05 15:17:25.495  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:25.513  2733  2733 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-05 15:17:25.513  2733  2733 I wpa_supplicant: monitor socket send errors count : 1
08-05 15:17:25.513  2733  2733 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
08-05 15:17:25.514  1035  2780 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-05 15:17:25.514  1035  2864 D DhcpStateMachine: StoppedState
08-05 15:17:25.514  1035  2780 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 15:17:25.514  1035  2864 D DhcpStateMachine: StoppedState{ when=-103ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 15:17:25.529  1035  1914 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7005 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 15:17:25.530  1035  1914 I ActivityManager: Killing 2129:com.lge.music/u0a34 (adj 15): empty #17
08-05 15:17:25.537  6961  6961 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 15:17:25.541   323  2159 V AudioFlinger: 2129 died, releasing its sessions
08-05 15:17:25.541   323  2159 V AudioFlinger:  pid 1852 @ 0
08-05 15:17:25.541   323  2159 V AudioFlinger:  pid 3356 @ 1
08-05 15:17:25.541   323  2159 V AudioFlinger:  pid 3356 @ 2
,08-05 15:17:25.550  2733  2733 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 15:17:25.550  1035  2780 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,08-05 15:17:25.550  1035  2780 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 15:17:25.551  1035  2780 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 15:17:25.551  1035  2780 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-05 15:17:25.551  2733  2733 W wpa_supplicant: USIM:  scard_deinit function
08-05 15:17:25.551  1035  2780 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 15:17:25.551  1035  2780 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 15:17:25.552  1035  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=338816
08-05 15:17:25.552  1035  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=338817
08-05 15:17:25.553  1035  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=338817  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 15:17:25.553  1035  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=338818  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 15:17:25.553  1035  1111 D Tethering: InitialState.processMessage what=4
,08-05 15:17:25.563  1035  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-05 15:17:25.564  1035  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-05 15:17:25.564  1035  2051 W libprocessgroup: failed to open /acct/uid_10034/pid_2129/cgroup.procs: No such file or directory
,08-05 15:17:25.569  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 15:17:25.570  4299  4299 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 15:17:25.570  4299  4299 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:25.570  4299  4299 V BluetoothPbapReceiver: ***********state = 13
08-05 15:17:25.571  1035  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:25.571  1035  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:25.572  4299  4299 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-05 15:17:25.573  4299  4299 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-05 15:17:25.573  4299  4299 V BluetoothPbapService: state: 13
08-05 15:17:25.573  4299  4299 V BluetoothPbapService: Pbap Service closeService in
08-05 15:17:25.573  1035  1111 D BluetoothManagerService: Message: 20
08-05 15:17:25.573  1035  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@149702a7:true
08-05 15:17:25.575  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 15:17:25.577  4299  4299 V BluetoothPbapService: successfully stopped pbap service
08-05 15:17:25.577  4299  4299 V BluetoothPbapService: Pbap Service closeService out
08-05 15:17:25.577  4299  4299 V BluetoothPbapService: Pbap Service onDestroy
,08-05 15:17:25.577  4299  4299 V BluetoothPbapService: Pbap Service closeService in
08-05 15:17:25.577  4299  4299 V BluetoothPbapService: Pbap Service closeService out
08-05 15:17:25.577  4299  4299 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-05 15:17:25.585  1035  1111 D BluetoothManagerService: Message: 30
08-05 15:17:25.588  1035  1111 D BluetoothManagerService: Message: 30
08-05 15:17:25.589  6961  6961 D LocalBluetoothProfileManager: Adding local MAP profile
,08-05 15:17:25.590  6961  6961 D BluetoothMap: Create BluetoothMap proxy object
08-05 15:17:25.591  1035  1111 D BluetoothManagerService: Message: 30
08-05 15:17:25.595  1035  1111 D BluetoothManagerService: Message: 30
08-05 15:17:25.596  6961  6961 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-05 15:17:25.597  6961  6961 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-05 15:17:25.607  6961  6961 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-05 15:17:25.607  7005  7005 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 15:17:25.609  6961  6961 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-05 15:17:25.610  7005  7005 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 15:17:25.610  7005  7005 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 15:17:25.612  1035  1940 I ActivityManager: Killing 6318:com.android.defcontainer/u0a4 (adj 15): empty #17
08-05 15:17:25.633  2733  2733 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-05 15:17:25.634  1035  2780 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,08-05 15:17:25.634  1035  2780 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-05 15:17:25.634  1035  2780 D WifiMonitor: Disconnecting from the supplicant, no more events
08-05 15:17:25.634  1035  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-05 15:17:25.644  1035  2051 W libprocessgroup: failed to open /acct/uid_10004/pid_6318/cgroup.procs: No such file or directory
08-05 15:17:25.646  6961  6961 D DockEventReceiver: finishStartingService: stopping service
,08-05 15:17:25.654  6961  6961 D BluetoothInputDevice: Proxy object connected
08-05 15:17:25.655  6961  6961 D HidProfile: Bluetooth service connected
08-05 15:17:25.656  6961  6961 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 15:17:25.656  6961  6961 D PanProfile: Bluetooth service connected
08-05 15:17:25.657  6961  6961 D BluetoothMap: Proxy object connected
,08-05 15:17:25.657  6961  6961 D MapProfile: Bluetooth service connected
,08-05 15:17:25.657  6961  6961 D BluetoothMap: getConnectedDevices()
08-05 15:17:25.658  6961  6961 D BluetoothMap: Bluetooth is Not enabled
08-05 15:17:25.666  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 15:17:25.711  6961  6961 D LgDataFeature: LgDataFeature() Constructor: none
08-05 15:17:25.711  6961  6961 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 15:17:25.722  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 15:17:25.724  6961  6961 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-05 15:17:25.727  6961  6961 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-05 15:17:25.736  1035  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-05 15:17:25.736  1035  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 15:17:25.736  1035  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 15:17:25.736  1035  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 15:17:25.737  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-05 15:17:25.737  6961  6961 D BluetoothPermissionRequest: onReceive
08-05 15:17:25.737  1941  2352 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-05 15:17:25.737  1941  2352 D WfdsService: Set the WFDS Monitor: false
08-05 15:17:25.737  1941  2352 D WfdsMonitor: WFDS Monitor is stopped
08-05 15:17:25.738  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 15:17:25.742  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-05 15:17:25.743  6961  6961 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-05 15:17:25.743  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 15:17:25.743  1035  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-05 15:17:25.744  1035  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-05 15:17:25.746  2502  2502 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:25.746  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:25.748  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:25.748  6877  6877 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-05 15:17:25.758  6961  6961 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 15:17:25.759  1035  2051 I ActivityManager: Killing 6419:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-05 15:17:25.796  1035  1886 W libprocessgroup: failed to open /acct/uid_10008/pid_6419/cgroup.procs: No such file or directory
08-05 15:17:25.797  4299  4299 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-05 15:17:25.797  4299  4299 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-05 15:17:25.798  4299  4299 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-05 15:17:25.885  1035  2051 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7036 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-05 15:17:25.889  4299  4299 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:25.889  4299  4299 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 15:17:25.891  4299  4299 V BluetoothFtpService: Ftp Service onStartCommand
08-05 15:17:25.891  4299  4299 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:25.892  4299  4299 V BluetoothFtpService: Ftp Service closeService
08-05 15:17:25.892  4299  4299 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-05 15:17:25.895  4299  4299 V BluetoothFtpService: successfully stopped ftp service
08-05 15:17:25.895  4299  4299 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 15:17:25.896  4299  4299 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 15:17:25.896  4299  4299 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 15:17:25.896  4299  4299 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:25.896  4299  4299 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-05 15:17:25.896  4299  4299 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 15:17:25.898  4299  4299 V BluetoothFtpService: Ftp Service onDestroy
08-05 15:17:25.898  4299  4299 V BluetoothFtpService: Ftp Service closeService
,08-05 15:17:25.960  1035  1051 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7053 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 15:17:25.966  4299  4299 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:25.966  4299  4299 V BluetoothSapService: state: 13
08-05 15:17:25.966  4299  4299 V BluetoothSapService: Stopping SAP server process
08-05 15:17:25.967  4299  4299 V BluetoothSapService: Sap Service closeSapService in
08-05 15:17:25.967  4299  4299 V BluetoothSapService: Close listen Socket : 
08-05 15:17:25.967  4299  4299 V BluetoothSapService: Close rfcomm Socket : 
08-05 15:17:25.967  4299  4299 V BluetoothSapService: Close sapd  Socket : 
08-05 15:17:25.968  4299  4299 V BluetoothSapService: Sap Service closeSapService out
08-05 15:17:25.969  4299  4299 V BluetoothSapService: Sap Service onDestroy
08-05 15:17:25.969  4299  4299 V BluetoothSapService: Sap Service closeSapService in
08-05 15:17:25.969  4299  4299 V BluetoothSapService: Close listen Socket : 
08-05 15:17:25.969  4299  4299 V BluetoothSapService: Close rfcomm Socket : 
08-05 15:17:25.969  4299  4299 V BluetoothSapService: Close sapd  Socket : 
08-05 15:17:25.969  4299  4299 V BluetoothSapService: Sap Service closeSapService out
,08-05 15:17:26.004  7036  7036 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 15:17:26.018  7053  7053 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 15:17:26.029  7036  7036 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-05 15:17:26.032  1035  1959 I ActivityManager: Killing 6465:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-05 15:17:26.121  1035  2013 W libprocessgroup: failed to open /acct/uid_10011/pid_6465/cgroup.procs: No such file or directory
,08-05 15:17:26.168  7036  7036 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-05 15:17:26.169  7036  7036 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-05 15:17:26.169  7036  7036 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-05 15:17:26.170  7036  7036 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-05 15:17:26.170  7036  7036 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-05 15:17:26.172  7036  7036 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-05 15:17:26.179  7036  7036 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-05 15:17:26.188  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 15:17:26.194  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 15:17:26.227  7036  7036 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 15:17:26.234  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:26.235  7036  7036 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-05 15:17:26.238  7036  7036 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-05 15:17:26.241  7005  7005 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 15:17:26.241  7005  7005 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 15:17:26.241  7005  7005 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 15:17:26.253  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:26.263  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:26.274  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 15:17:26.275  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:26.278  7036  7036 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 15:17:26.284  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:26.290  7005  7005 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-05 15:17:26.290  7005  7005 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 15:17:26.290  7005  7005 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 15:17:26.296  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 15:17:26.303  4299  4524 I bt_lpm  : LPM is already off!!!
08-05 15:17:26.303  4299  4419 D bt_hci_bdroid: cleanup
,08-05 15:17:26.303  4299  4667 I bt_userial_mct: exiting userial_read_thread
08-05 15:17:26.303  4299  4667 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-05 15:17:26.303  4299  4522 W bt-btif : ag scb idx 1 not allocated
08-05 15:17:26.303  4299  4522 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 15:17:26.303  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 15:17:26.303  4299  4522 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 15:17:26.304  4299  4522 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 15:17:26.304  4299  4522 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 15:17:26.305  4299  4419 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-05 15:17:26.305  4299  4524 I bt_vendor: hw_epilog_process
08-05 15:17:26.305  4299  4419 D bt_hci_bdroid: cleanup Finalizing cleanup
08-05 15:17:26.305  4299  4419 D bt_userial_mct: userial_close
08-05 15:17:26.305  4299  4419 E bt_userial_mct: pthread_join() FAILED result:3
08-05 15:17:26.305  4299  4419 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-05 15:17:26.309  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:26.324  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:26.325  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:26.328  7036  7036 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 15:17:26.382  4299  4419 D bt_hci_bdroid: set_power 0
08-05 15:17:26.382  4299  4419 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-05 15:17:26.382  4299  4419 I bt_vendor: bluetooth satus is on
08-05 15:17:26.382  4299  4419 I bt_vendor: bt-vendor : resetting BT status
08-05 15:17:26.382  4299  4419 I bt_vendor: Starting hciattach daemon
08-05 15:17:26.382  4299  4419 I bt_vendor: try to set false
,08-05 15:17:26.386  4299  4419 I bt_vendor: Starting hciattach daemon
08-05 15:17:26.386  4299  4419 I bt_vendor: try to set false
08-05 15:17:26.387  4299  4419 I bt_vendor: cleanup
08-05 15:17:26.388  4299  4522 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-05 15:17:26.389  4299  4419 I GKI_LINUX: GKI_exit_task 0 done
08-05 15:17:26.389  4299  4419 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-05 15:17:26.390  4299  4415 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 15:17:26.406  1035  1050 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7077 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-05 15:17:26.412  4299  4299 D HeadsetService: Received stop request...Stopping profile...
08-05 15:17:26.413  4299  4299 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 15:17:26.413  4299  4299 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 15:17:26.413  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@221d367c
08-05 15:17:26.414  4299  4453 D HeadsetStateMachine: Exit Disconnected: -1
08-05 15:17:26.420  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-05 15:17:26.420  1852  1852 D BluetoothHeadset: Proxy object disconnected
,08-05 15:17:26.420  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-05 15:17:26.425  4299  4299 D A2dpService: Received stop request...Stopping profile...
08-05 15:17:26.425  4299  4502 D A2dpStateMachine: Exit Disconnected: -1
08-05 15:17:26.426  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-05 15:17:26.426  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-05 15:17:26.426  4299  4299 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-05 15:17:26.429  4299  4299 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-05 15:17:26.429  4299  4299 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 15:17:26.430  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@221d367c
08-05 15:17:26.430  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-05 15:17:26.430  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-05 15:17:26.432  4299  4299 D HeadsetStateMachine: Unbinding service...
08-05 15:17:26.433  4299  4299 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 15:17:26.433  4299  4299 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 15:17:26.433  4299  4299 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 15:17:26.433  4299  4299 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 15:17:26.433  4299  4299 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 15:17:26.433  4299  4299 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 15:17:26.433  4299  4299 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-05 15:17:26.436  4299  4299 D HidService: Received stop request...Stopping profile...
08-05 15:17:26.436  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@221d367c
08-05 15:17:26.437  4299  4415 D BluetoothAdapterState: Stopping profile services that were post enabled
08-05 15:17:26.439  6961  6961 D BluetoothInputDevice: Proxy object disconnected
08-05 15:17:26.439  6961  6961 D HidProfile: Bluetooth service disconnected
08-05 15:17:26.440  4299  4299 D HealthService: Received stop request...Stopping profile...
08-05 15:17:26.440  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@221d367c
08-05 15:17:26.441  4299  4299 I BluetoothA2dpServiceJni: cleanupNative
08-05 15:17:26.441  4299  4503 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 15:17:26.441  4299  4299 I GKI_LINUX: GKI_exit_task 2 done
08-05 15:17:26.441  4299  4299 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-05 15:17:26.442  4299  4299 D PanService: Received stop request...Stopping profile...
08-05 15:17:26.442  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@221d367c
08-05 15:17:26.443  4299  4299 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 15:17:26.444  4299  4299 D BtGatt.GattService: Received stop request...Stopping profile...
08-05 15:17:26.444  4299  4299 D BtGatt.GattService: stop()
08-05 15:17:26.444  4299  4299 D BtGatt.AdvertiseManager: advertise clients cleared
08-05 15:17:26.445  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@221d367c
,08-05 15:17:26.446  4299  4299 D BluetoothMapService: Received stop request...Stopping profile...
,08-05 15:17:26.446  4299  4299 D BluetoothMapService: stop()
08-05 15:17:26.447  4299  4299 D BluetoothMapEmailAppObserver: deinitObservers()
08-05 15:17:26.447  4299  4299 D BluetoothMapEmailAppObserver: removeReceiver()
08-05 15:17:26.448  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@221d367c
08-05 15:17:26.448  6961  6961 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 15:17:26.448  6961  6961 D PanProfile: Bluetooth service disconnected
08-05 15:17:26.449  4299  4299 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 15:17:26.449  4299  4299 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-05 15:17:26.449  6961  6961 D BluetoothMap: Proxy object disconnected
08-05 15:17:26.449  6961  6961 D MapProfile: Bluetooth service disconnected
08-05 15:17:26.449   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 36.823ms
08-05 15:17:26.449  4299  4299 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 15:17:26.449  4299  4299 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 15:17:26.449  4299  4299 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 15:17:26.450  4299  4299 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 15:17:26.450  4299  4299 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 15:17:26.451  4299  4299 V BluetoothMapService: Handler(): got msg=4
08-05 15:17:26.451  4299  4299 D BluetoothMapService: MAP Service closeService in
08-05 15:17:26.451  4299  4299 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 15:17:26.451  4299  4299 V BluetoothMapService: MAP Service closeService out
08-05 15:17:26.451  4299  4299 D BluetoothMapService: cleanup()
08-05 15:17:26.451  4299  4299 D BluetoothMapService: MAP Service closeService in
08-05 15:17:26.452  4299  4299 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 15:17:26.452  4299  4299 V BluetoothMapService: MAP Service closeService out
08-05 15:17:26.452  4299  4415 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-05 15:17:26.452  4299  4415 D BluetoothAdapterProperties: Setting state to 10
08-05 15:17:26.452  4299  4415 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-05 15:17:26.452  1035  1111 D BluetoothManagerService: Message: 60
08-05 15:17:26.452  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-05 15:17:26.452  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-05 15:17:26.453  4299  4415 I BluetoothAdapterState: Entering OffState
08-05 15:17:26.453  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 15:17:26.453  6961  7032 D BluetoothMap: onBluetoothStateChange: up=false
08-05 15:17:26.454  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 15:17:26.455  1852  4454 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 15:17:26.455  6961  6982 D BluetoothPan: onBluetoothStateChange on: false
08-05 15:17:26.456  6961  6979 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 15:17:26.456  1035  1111 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 15:17:26.456  6961  7032 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-05 15:17:26.457  1035  1111 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 15:17:26.458  1035  1111 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-05 15:17:26.458  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-05 15:17:26.460  1035  1111 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-05 15:17:26.460  1035  1111 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-05 15:17:26.460  1035  1111 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@38ee88bc mBinding = false
08-05 15:17:26.461  1035  1111 D BluetoothManagerService: Sending unbind request.
,08-05 15:17:26.469  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-05 15:17:26.471   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 619us total 21.557ms
08-05 15:17:26.472  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:26.472  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 15:17:26.475  4299  4419 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-05 15:17:26.475  4299  4299 I GKI_LINUX: GKI_exit_task 1 done
08-05 15:17:26.475  4299  4299 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-05 15:17:26.476  4299  4299 I BluetoothServiceJni: cleanupNative: return from cleanup
08-05 15:17:26.476  4299  4299 I art     : --- WEIRD: removing null entry 246
08-05 15:17:26.476  4299  4299 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-05 15:17:26.476  4299  4299 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-05 15:17:26.477  1604  1604 D BluetoothAdapter: 697982356: getState() :  mService = null. Returning STATE_OFF
08-05 15:17:26.477  1604  1604 D BluetoothAdapter: 697982356: getState() :  mService = null. Returning STATE_OFF
08-05 15:17:26.478  1941  2139 D LGBluetoothAPIService: Message: 2
08-05 15:17:26.478  1941  2139 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@111eb9ff mBinding = false
08-05 15:17:26.478  1941  2139 D LGBluetoothAPIService: Sending unbind request.
,08-05 15:17:26.484  4299  4299 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-05 15:17:26.485  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:26.486  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:26.489  6961  6961 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 15:17:26.489  6961  6961 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-05 15:17:26.489  6961  6961 D LGBluetoothEventManager: [BTUI] clear device connection state
08-05 15:17:26.493  4299  4299 I art     : System.exit called, status: 0
08-05 15:17:26.493  4299  4299 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-05 15:17:26.497  6961  6961 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 15:17:26.504  6961  6961 D DockEventReceiver: finishStartingService: stopping service
08-05 15:17:26.505   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.343ms total 32.747ms
08-05 15:17:26.513   323   323 V AudioFlinger: 4299 died, releasing its sessions
08-05 15:17:26.513   323   323 V AudioFlinger:  pid 1852 @ 0
08-05 15:17:26.513   323   323 V AudioFlinger:  pid 3356 @ 1
08-05 15:17:26.513   323   323 V AudioFlinger:  pid 3356 @ 2
08-05 15:17:26.514  6961  6961 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-05 15:17:26.542  1035  2014 I ActivityManager: Process com.android.bluetooth (pid 4299) has died
,08-05 15:17:26.542  1035  2014 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-05 15:17:26.548  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 15:17:26.554  7005  7005 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 15:17:26.561  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 15:17:26.569  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 15:17:26.573  6961  6961 D BluetoothPermissionRequest: onReceive
08-05 15:17:26.576  6961  6961 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 15:17:26.576  6961  6961 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-05 15:17:26.578  6961  6961 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-05 15:17:26.641  1035  2013 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7106 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-05 15:17:26.652  7077  7103 W FormManager: Network not available. Please check & try again.
08-05 15:17:26.666  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 15:17:26.667  6961  6961 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 15:17:26.667  6961  6961 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 15:17:26.667  6961  6961 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 15:17:26.669  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 15:17:26.669  7077  7105 V FormManager: Network unavailable.
,08-05 15:17:26.672  7077  7105 V FormManager: Network unavailable.
,08-05 15:17:26.679  6961  6961 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 15:17:26.680  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 15:17:26.680  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 15:17:26.680  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 15:17:26.680  6961  6961 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,08-05 15:17:26.680  6961  6961 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-05 15:17:26.685  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 15:17:26.686  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 15:17:26.688  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 15:17:26.689  1035  2013 I ActivityManager: Killing 5985:com.android.contacts/u0a19 (adj 15): empty #17
,08-05 15:17:26.800  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 15:17:26.802  1035  1051 W libprocessgroup: failed to open /acct/uid_10019/pid_5985/cgroup.procs: No such file or directory
08-05 15:17:26.836  4785  7125 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 15:17:26.838  7005  7005 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-05 15:17:26.838  7005  7005 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 15:17:26.838  7005  7005 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 15:17:26.844  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 15:17:26.846  7106  7106 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-05 15:17:26.847  4785  7127 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 15:17:26.848  4785  7127 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 15:17:26.848  7106  7106 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 15:17:26.849  7106  7106 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-05 15:17:26.850  7106  7106 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-05 15:17:26.854  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:26.862  7077  7129 W FormManager: Network not available. Please check & try again.
08-05 15:17:26.870  7077  7130 V FormManager: Network unavailable.
,08-05 15:17:26.874  7036  7036 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 15:17:26.874  7077  7130 V FormManager: Network unavailable.
08-05 15:17:26.875  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 15:17:26.875  7036  7036 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-05 15:17:26.881  7106  7106 D BluetoothAdapterApp: Loading JNI Library
,08-05 15:17:26.910  7036  7036 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 15:17:26.911  7036  7036 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 15:17:26.915  7106  7106 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@31eb5f4d Instance Count = 1
08-05 15:17:26.917  7036  7036 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-05 15:17:26.918  7036  7036 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-05 15:17:26.918  7036  7036 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-05 15:17:26.918  7036  7036 V SoundPool: doLoad: loading sample sampleID=1
08-05 15:17:26.919  7036  7036 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 15:17:26.919  7036  7133 V SoundPool: Start decode
08-05 15:17:26.919  7036  7133 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-05 15:17:26.920   323  1383 V MediaPlayerService: decode(23, 10857164, 17813)
08-05 15:17:26.920   323  1383 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-05 15:17:26.920   323  1383 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-05 15:17:26.920   323  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-05 15:17:26.920   323  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-05 15:17:26.920   323  1383 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-05 15:17:26.920   323  1383 V MediaPlayerService: player type = 3
08-05 15:17:26.920   323  1383 V AwesomePlayer: AwesomePlayer create()
08-05 15:17:26.921   323  1383 V AwesomePlayer: reset_l() 
08-05 15:17:26.921   323  1383 V AwesomePlayer: cancelPlayerEvents
08-05 15:17:26.921   323  1383 V AwesomePlayer: setAudioSink() 
08-05 15:17:26.921   323  1383 V AwesomePlayer: reset_l() 
08-05 15:17:26.921   323  1383 V AudioCache: notify(0xb14323c0, 8, 0, 0)
08-05 15:17:26.921   323  1383 V AudioCache: ignored
08-05 15:17:26.921   323  1383 V AwesomePlayer: cancelPlayerEvents
08-05 15:17:26.921   323  1383 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-05 15:17:26.921   323  1383 V AwesomePlayer: setDataSource_l dataSource
08-05 15:17:26.921   323  1383 V LGParserOSAL: SniffLGParser start
08-05 15:17:26.921   323  1383 V LGParserOSAL: MainType:5, SubType=0
08-05 15:17:26.921   323  1383 V LGParserOSAL: #### check Mime : application/ogg
08-05 15:17:26.921   323  1383 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-05 15:17:26.921   323  1383 E MediaExtractor: Use LGExtractor :application/ogg 
,08-05 15:17:26.925  7106  7106 D BluetoothAdapterApp: onCreate
08-05 15:17:26.925  6749  6749 D UEI.SmartControl: QS Service created
08-05 15:17:26.933  7036  7036 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-05 15:17:26.942  7036  7036 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 15:17:26.943  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-05 15:17:26.954  7106  7106 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-05 15:17:26.955  7106  7106 D ProfileConfigQcom: Adding HeadsetService
08-05 15:17:26.955  7106  7106 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-05 15:17:26.955  7106  7106 D ProfileConfigQcom: Adding A2dpService
08-05 15:17:26.955  7106  7106 D ProfileConfigQcom: [BTUI] HidService is supported
08-05 15:17:26.955  7106  7106 D ProfileConfigQcom: Adding HidService
08-05 15:17:26.956  7106  7106 D ProfileConfigQcom: [BTUI] HealthService is supported
08-05 15:17:26.956  7106  7106 D ProfileConfigQcom: Adding HealthService
08-05 15:17:26.956  7106  7106 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-05 15:17:26.957  7036  7036 V LGMDMManager: Create singleton instance
08-05 15:17:26.957   323  1383 V LGParserOSAL: supported mime: application/ogg
08-05 15:17:26.957   323  1383 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-05 15:17:26.957   323  1383 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-05 15:17:26.957   323  1383 V AwesomePlayer: mBitrate = -1 bits/sec
08-05 15:17:26.957   323  1383 V AwesomePlayer: AudioTrack Setting
08-05 15:17:26.957   323  1383 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-05 15:17:26.957   323  1383 V AwesomePlayer: setAudioSource() 
08-05 15:17:26.957   323  1383 V MediaPlayerService: prepare
08-05 15:17:26.957   323  1383 V AwesomePlayer: prepareAsync_l() 
08-05 15:17:26.958   323  1383 V MediaPlayerService: wait for prepare
08-05 15:17:26.958  7106  7106 D ProfileConfigQcom: [BTUI] PanService is supported
08-05 15:17:26.958  7106  7106 D ProfileConfigQcom: Adding PanService
08-05 15:17:26.958   323  7135 V AwesomePlayer: onPrepareAsyncEvent() 
08-05 15:17:26.958  7106  7106 D ProfileConfigQcom: [BTUI] GattService is supported
08-05 15:17:26.958   323  7135 V AwesomePlayer: initAudioDecoder() 
08-05 15:17:26.958   323  7135 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 15:17:26.958  7106  7106 D ProfileConfigQcom: Adding GattService
08-05 15:17:26.958   323  7135 V AudioSystem: isOffloadSupported()
08-05 15:17:26.958  7106  7106 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-05 15:17:26.958   323  7135 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 15:17:26.958   323  7135 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 15:17:26.958  7106  7106 D ProfileConfigQcom: Adding BluetoothMapService
08-05 15:17:26.958   323  7135 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 15:17:26.958   323  7135 V AwesomePlayer: getUseOffload() = 0 
08-05 15:17:26.958   323  7135 V OMXCodec: OMXCodec::Create
08-05 15:17:26.958   323  7135 V OMXCodec: findMatchingCodecs()
08-05 15:17:26.959  7106  7106 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-05 15:17:26.959   323  7135 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-05 15:17:26.959   323  7135 V OMXCodec: matchingCodecs.size()=1
08-05 15:17:26.959   323  7135 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-05 15:17:26.960  7106  7106 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-05 15:17:26.964  6961  6961 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-05 15:17:26.965   323  7135 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-05 15:17:26.965  7106  7106 V LGMDMManagerInternal: Create singleton instance
08-05 15:17:26.965   323  7135 V LGCodecAdapter: LG Codec Adapter start
08-05 15:17:26.965   323  7135 V OMXCodec: OMXCodec Createtor
08-05 15:17:26.965   323  7135 V OMXCodec: setComponentRole
08-05 15:17:26.965   323  7135 V OMXCodec: configureCodec protected=0
08-05 15:17:26.965   323  7135 V, LGCodecAdapter: called getLGCodecSpecificData
08-05 15:17:26.965   323  7135 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-05 15:17:26.965   323  7135 V LGCodecOSAL: Called LGconfigureCodecMETA
08-05 15:17:26.966   323  7135 V LGCodecOSAL: Called LGconfigureCodecMSG
08-05 15:17:26.966   323  7135 V LGCodecOSAL: Not support LGCodec
08-05 15:17:26.966   323  7135 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 15:17:26.966   323  7135 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-05 15:17:26.966   323  7135 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-05 15:17:26.966   323  7135 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-05 15:17:26.966  6749  6749 I UEI.SmartControl: Service initServices...
08-05 15:17:26.966   323  7135 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 15:17:26.966   323  7135 V AudioSystem: isOffloadSupported()
08-05 15:17:26.966  6749  6749 D UEI.SmartControl: QS start get config
08-05 15:17:26.966   323  7135 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 15:17:26.966   323  7135 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 15:17:26.966   323  7135 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-05 15:17:26.967   323  7135 V OMXCodec: init()
08-05 15:17:26.967   323  7135 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-05 15:17:26.967   323  7135 V OMXCodec: allocateBuffers
08-05 15:17:26.967   323  7135 V OMXCodec: allocateBuffersOnPort portIndex=0
08-05 15:17:26.967   323  7135 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-05 15:17:26.967   323  7135 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76a0 on input port
08-05 15:17:26.967   323  7135 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
08-05 15:17:26.968   323  7135 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
08-05 15:17:26.968   323  7135 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-05 15:17:26.968   323  7135 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 15:17:26.968   323  7135 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 15:17:26.968   323  7135 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on output port
08-05 15:17:26.968   323  7135 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
08-05 15:17:26.968   323  7135 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
08-05 15:17:26.968   323  7135 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-05 15:17:26.968   323  7135 V OMXCodec: init() mAsyncCompletion wait!!! 
08-05 15:17:26.969   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 15:17:26.969   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 15:17:26.969   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-05 15:17:26.970   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-05 15:17:26.970   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
,08-05 15:17:26.970   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-05 15:17:26.970   323  7135 V OMXCodec: init() mAsyncCompletion wait free! 
08-05 15:17:26.970   323  7135 V AwesomePlayer: finishAsyncPrepare_l() 
08-05 15:17:26.970   323  7135 V AudioCache: notify(0xb14323c0, 5, 0, 0)
08-05 15:17:26.970   323  7135 V AudioCache: ignored
08-05 15:17:26.970   323  7135 V AudioCache: notify(0xb14323c0, 1, 0, 0)
08-05 15:17:26.970   323  7135 V AudioCache: prepared
08-05 15:17:26.970   323  1383 V AudioCache: wait - success
08-05 15:17:26.970   323  1383 V MediaPlayerService: start,
08-05 15:17:26.970   323  1383 V AwesomePlayer: play_l() 
08-05 15:17:26.970   323  1383 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-05 15:17:26.970   323  1383 V AwesomePlayer: createAudioPlayer_l
08-05 15:17:26.970   323  1383 V AwesomePlayer: seekAudioIfNecessary_l() 
08-05 15:17:26.970   323  1383 V AwesomePlayer: startAudioPlayer_l() 
,08-05 15:17:26.970   323  1383 D AudioPlayer: start of Playback, useOffload 0
08-05 15:17:26.970   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 15:17:26.970   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 15:17:26.972   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-05 15:17:26.972   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-05 15:17:26.972   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-05 15:17:26.972   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-05 15:17:26.972   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-05 15:17:26.972   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,08-05 15:17:26.972   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884288
08-05 15:17:26.972   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884448
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884528
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-05 15:17:26.973   323  7137 V OMXCodec: allocateBuffersOnPort portIndex=1
,08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port,
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on output port
,08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-05 15:17:26.973   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-05 15:17:26.974   323  1383 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-05 15:17:26.975   323  1383 V AudioCache: notify(0xb14323c0, 6, 0, 0)
08-05 15:17:26.975   323  1383 V AudioCache: ignored
08-05 15:17:26.975   323  1383 V MediaPlayerService: wait for playback complete
08-05 15:17:26.975   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.975   323  7138 V AudioCache: memcpy(0xaf004000, 0xb16ec000, 4096)
08-05 15:17:26.976   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.976   323  7138 V AudioCache: memcpy(0xaf005000, 0xb16ec000, 4096)
08-05 15:17:26.976   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.976   323  7138 V AudioCache: memcpy(0xaf006000, 0xb16ec000, 4096)
08-05 15:17:26.978   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.978   323  7138 V AudioCache: memcpy(0xaf007000, 0xb16ec000, 4096)
08-05 15:17:26.978   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.978   323  7138 V AudioCache: memcpy(0xaf008000, 0xb16ec000, 4096)
08-05 15:17:26.978   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.978   323  7138 V AudioCache: memcpy(0xaf009000, 0xb16ec000, 4096)
08-05 15:17:26.978   323  7138 V AudioCache: write(0xb16ec000, 4096)
,08-05 15:17:26.978   323  7138 V AudioCache: memcpy(0xaf00a000, 0xb16ec000, 4096)
08-05 15:17:26.979   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.979   323  7138 V AudioCache: memcpy(0xaf00b000, 0xb16ec000, 4096)
08-05 15:17:26.979   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.980   323  7138 V AudioCache: memcpy(0xaf00c000, 0xb16ec000, 4096)
08-05 15:17:26.980   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.980   323  7138 V AudioCache: memcpy(0xaf00d000, 0xb16ec000, 4096)
08-05 15:17:26.980   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.980   323  7138 V AudioCache: memcpy(0xaf00e000, 0xb16ec000, 4096)
08-05 15:17:26.980   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.980   323  7138 V AudioCache: memcpy(0xaf00f000, 0xb16ec000, 4096)
08-05 15:17:26.981   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.981   323  7138 V AudioCache: memcpy(0xaf010000, 0xb16ec000, 4096)
08-05 15:17:26.981   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.981   323  7138 V AudioCache: memcpy(0xaf011000, 0xb16ec000, 4096)
,08-05 15:17:26.981   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.981   323  7138 V AudioCache: memcpy(0xaf012000, 0xb16ec000, 4096)
08-05 15:17:26.981   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.981   323  7138 V AudioCache: memcpy(0xaf013000, 0xb16ec000, 4096)
08-05 15:17:26.983   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.983   323  7138 V AudioCache: memcpy(0xaf014000, 0xb16ec000, 4096)
08-05 15:17:26.983   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.983   323  7138 V AudioCache: memcpy(0xaf015000, 0xb16ec000, 4096)
08-05 15:17:26.983   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.983   323  7138 V AudioCache: memcpy(0xaf016000, 0xb16ec000, 4096)
08-05 15:17:26.984   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.984   323  7138 V AudioCache: memcpy(0xaf017000, 0xb16ec000, 4096)
08-05 15:17:26.985   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.985   323  7138 V AudioCache: memcpy(0xaf018000, 0xb16ec000, 4096)
08-05 15:17:26.985   323  7138 V AudioCache: write(0xb16ec000, 4096)
,08-05 15:17:26.985   323  7138 V AudioCache: memcpy(0xaf019000, 0xb16ec000, 4096)
08-05 15:17:26.985   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.985   323  7138 V AudioCache: memcpy(0xaf01a000, 0xb16ec000, 4096)
08-05 15:17:26.986   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.986   323  7138 V AudioCache: memcpy(0xaf01b000, 0xb16ec000, 4096)
08-05 15:17:26.986   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.987   323  7138 V AudioCache: memcpy(0xaf01c000, 0xb16ec000, 4096)
08-05 15:17:26.987   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.987   323  7138 V AudioCache: memcpy(0xaf01d000, 0xb16ec000, 4096)
08-05 15:17:26.988   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.988   323  7138 V AudioCache: memcpy(0xaf01e000, 0xb16ec000, 4096)
,08-05 15:17:26.988   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.989   323  7138 V AudioCache: memcpy(0xaf01f000, 0xb16ec000, 4096)
08-05 15:17:26.989   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.989   323  7138 V AudioCache: memcpy(0xaf020000, 0xb16ec000, 4096)
08-05 15:17:26.989   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.989   323  7138 V AudioCache: memcpy(0xaf021000, 0xb16ec000, 4096)
08-05 15:17:26.990   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.990   323  7138 V AudioCache: memcpy(0xaf022000, 0xb16ec000, 4096)
08-05 15:17:26.990   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.990   323  7138 V AudioCache: memcpy(0xaf023000, 0xb16ec000, 4096)
08-05 15:17:26.991   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.991   323  7138 V AudioCache: memcpy(0xaf024000, 0xb16ec000, 4096)
08-05 15:17:26.991   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.991   323  7138 V AudioCache: memcpy(0xaf025000, 0xb16ec000, 4096)
08-05 15:17:26.992   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.992   323  7138 V AudioCache: memcpy(0xaf026000, 0xb16ec000, 4096)
08-05 15:17:26.992   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.992   323  7138 V AudioCache: memcpy(0xaf027000, 0xb16ec000, 4096)
08-05 15:17:26.993   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.993   323  7138 V AudioCache: memcpy(0xaf028000, 0xb16ec000, 4096)
08-05 15:17:26.994   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.994   323  7138 V AudioCache: memcpy(0xaf029000, 0xb16ec000, 4096)
08-05 15:17:26.995   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.995   323  7138 V AudioCache: memcpy(0xaf02a000, 0xb16ec000, 4096)
08-05 15:17:26.995   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.995   323  7138 V AudioCache: memcpy(0xaf02b000, 0xb16ec000, 4096)
08-05 15:17:26.996   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.996   323  7138 V AudioCache: memcpy(0xaf02c000, 0xb16ec000, 4096)
08-05 15:17:26.996   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.996   323  7138 V AudioCache: memcpy(0xaf02d000, 0xb16ec000, 4096)
08-05 15:17:26.997   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.997   323  7138 V AudioCache: memcpy(0xaf02e000, 0xb16ec000, 4096)
08-05 15:17:26.997   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.997   323  7138 V AudioCache: memcpy(0xaf02f000, 0xb16ec000, 4096)
08-05 15:17:26.998   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.998   323  7138 V AudioCache: memcpy(0xaf030000, 0xb16ec000, 4096)
08-05 15:17:26.998   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.998   323  7138 V AudioCache: memcpy(0xaf031000, 0xb16ec000, 4096)
08-05 15:17:26.999   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.999   323  7138 V AudioCache: memcpy(0xaf032000, 0xb16ec000, 4096)
08-05 15:17:26.999   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:26.999   323  7138 V AudioCache: memcpy(0xaf033000, 0xb16ec000, 4096)
08-05 15:17:27.000   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:27.000   323  7138 V AudioCache: memcpy(0xaf034000, 0xb16ec000, 4096)
08-05 15:17:27.000   323  7138 V AudioCache: write(0xb16ec000, 4096)
08-05 15:17:27.000   323  7138 V AudioCache: memcpy(0xaf035000, 0xb16ec000, 4096)
,08-05 15:17:27.000   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-05 15:17:27.000   323  7138 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-05 15:17:27.000   323  7138 V AwesomePlayer: postAudioEOS() 
08-05 15:17:27.000   323  7138 V AudioCache: write(0xb16ec000, 280)
08-05 15:17:27.000   323  7138 V AudioCache: memcpy(0xaf036000, 0xb16ec000, 280)
08-05 15:17:27.002   323  7135 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-05 15:17:27.002   323  7135 V AwesomePlayer: onStreamDone
08-05 15:17:27.002   323  7135 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-05 15:17:27.002   323  7135 V AudioCache: notify(0xb14323c0, 2, 0, 0)
08-05 15:17:27.002   323  7135 V AudioCache: playback complete
08-05 15:17:27.002   323  7135 V AwesomePlayer: pause_l() 
08-05 15:17:27.002   323  7135 V AudioCache: notify(0xb14323c0, 7, 0, 0)
08-05 15:17:27.002   323  7135 V AudioCache: ignored
08-05 15:17:27.002   323  7135 V AwesomePlayer: cancelPlayerEvents
08-05 15:17:27.002   323  1383 V AudioCache: wait - success
08-05 15:17:27.002   323  1383 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-05 15:17:27.002   323  7135 D AudioPlayer: Pause Playback at 1068125
08-05 15:17:27.002   323  1383 V AwesomePlayer: reset_l() 
08-05 15:17:27.002   323  1383 V AudioCache: notify(0xb14323c0, 8, 0, 0)
08-05 15:17:27.002   323  1383 V AudioCache: ignored
08-05 15:17:27.002   323  1383 V AwesomePlayer: cancelPlayerEvents
08-05 15:17:27.002   323  1383 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-05 15:17:27.002   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-05 15:17:27.003   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-05 15:17:27.003   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-05 15:17:27.003   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76a0 on port 0
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 1
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 1
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 1
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google,.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-05 15:17:27.003   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 15:17:27.003   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-05 15:17:27.003   323  7137 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-05 15:17:27.003   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 15:17:27.003   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-05 15:17:27.004   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-05 15:17:27.004   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-05 15:17:27.004   323  1383 D AudioPlayer: AudioPlayer releasing audio source
08-05 15:17:27.004   323  1383 D AudioPlayer: AudioPlayer done releasing audio source
08-05 15:17:27.004   323  1383 V AwesomePlayer: reset_l() 
08-05 15:17:27.004   323  1383 V AwesomePlayer: cancelPlayerEvents
08-05 15:17:27.004   323  1383 V AwesomePlayer: ~AwesomePlayer call
08-05 15:17:27.004   323  1383 V AwesomePlayer: reset_l() 
08-05 15:17:27.004   323  1383 V AwesomePlayer: cancelPlayerEvents
08-05 15:17:27.005  7036  7133 V SoundPool: close(31)
08-05 15:17:27.005  7036  7133 V SoundPool: pointer = 0xa0000000, size = 205080, sampleRate = 48000, numChannels = 2
08-05 15:17:27.019  7106  7106 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-05 15:17:27.022  7106  7106 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 15:17:27.023  7106  7106 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 15:17:27.023  7106  7106 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 15:17:27.024  7106  7106 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:27.024  7106  7106 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-05 15:17:27.030  7053  7053 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-05 15:17:27.030  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 15:17:27.031  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-05 15:17:27.033  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6042
,08-05 15:17:27.246  6749  6749 I UEI.SmartControl: Supports setup maps: true
,08-05 15:17:27.248  6749  6749 D UEI.SmartControl: QS start statue = true Error code = 0
,08-05 15:17:27.248  6749  6749 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-05 15:17:27.248  6749  6749 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 15:17:27.248  6749  6749 I UEI.SmartControl: ### init IR Blaster...
,08-05 15:17:27.251  6749  6749 D serial_port: Configuring serial port
08-05 15:17:27.251  6749  6749 E UEI.SmartControl: UEIBLaster setting for 616
08-05 15:17:27.251  6749  6749 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 15:17:27.251  6749  6749 I UEI.SmartControl: configuring settings for MAXQ616
08-05 15:17:27.251  6749  6749 I UEI.SmartControl: Get version...
08-05 15:17:27.270  6749  7140 D UEI.SmartControl: serial port data available: 21
,08-05 15:17:27.297  6749  6749 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-05 15:17:27.297  6749  6749 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 15:17:27.297  6749  6749 I UEI.SmartControl: QS saving settings...
08-05 15:17:27.300  6749  6749 D UEI.SmartControl: IR Blaster version: 25672567
,08-05 15:17:27.317  6749  7140 D UEI.SmartControl: serial port data available: 4
,08-05 15:17:27.349  6749  7146 I UEI.SmartControl: Device manager: loading config....
,08-05 15:17:27.363  6749  6749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-05 15:17:27.366  6749  7146 D UEI.SmartControl: ----------- loading internal config...
08-05 15:17:27.371  6749  6749 E UEI.SmartControl: Services init done
08-05 15:17:27.371  6749  6749 D UEI.SmartControl: QS Service init finished
08-05 15:17:27.373  6749  6749 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 15:17:27.373  6749  6749 D UEI.SmartControl: QS Service version code: 201091
08-05 15:17:27.376  6749  6749 D UEI.SmartControl: Service requested: Control
08-05 15:17:27.380  6749  7146 E UEI.SmartControl: Loading SETTINGS...
08-05 15:17:27.381  6749  6749 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-05 15:17:27.385  6749  6749 D UEI.SmartControl: Internal service binding...
08-05 15:17:27.386  7036  7036 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-05 15:17:27.388  6749  6765 I UEI.SmartControl: ------ IControl API: 11
08-05 15:17:27.388  6749  6765 D UEI.SmartControl: File observer start...
08-05 15:17:27.389  6749  6765 E UEI.SmartControl: IR Port is disabled: false
08-05 15:17:27.390  6749  6765 D UEI.SmartControl: Starting file observer...
08-05 15:17:27.392  6749  6765 I UEI.SmartControl: Registering callback...
08-05 15:17:27.394  6749  6764 I UEI.SmartControl: ------ IControl API: 19
08-05 15:17:27.395  6749  6764 I UEI.SmartControl: Registering Services Ready callback...
,08-05 15:17:27.399  6749  7146 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 15:17:27.407  6749  7145 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-05 15:17:27.407  6749  7145 D UEI.SmartControl: -----service ready thread exits
08-05 15:17:27.408  7036  7051 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-05 15:17:27.409  7036  7131 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-05 15:17:27.409  7036  7131 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-05 15:17:27.409  7036  7036 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-05 15:17:27.410  7036  7036 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-05 15:17:27.410  6749  6765 I UEI.SmartControl: ------ IControl API: 8
08-05 15:17:27.412  7036  7036 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-05 15:17:27.412  7036  7036 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-05 15:17:27.412  7036  7036 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-05 15:17:27.413  7036  7036 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-05 15:17:27.414  7036  7036 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-05 15:17:27.414  7036  7036 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-05 15:17:27.416  7036  7036 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-05 15:17:27.418  7036  7036 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 15:17:27.418  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-05 15:17:27.419  7036  7036 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 15:17:27.419  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 15:17:27.420  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 15:17:27.422  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-05 15:17:27.422  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-05 15:17:27.423  7036  7036 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470403047423]
08-05 15:17:27.425  7036  7036 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-05 15:17:27.427  1035  1959 I ActivityManager: Killing 6520:com.android.gallery3d/u0a27 (adj 15): empty #17
08-05 15:17:27.447  7036  7151 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-05 15:17:27.472  1035  1959 I ActivityManager: Killing 6490:com.lge.email/u0a23 (adj 15): empty #18
,08-05 15:17:27.503  1035  1914 W libprocessgroup: failed to open /acct/uid_10027/pid_6520/cgroup.procs: No such file or directory
,08-05 15:17:27.509  1035  1050 W libprocessgroup: failed to open /acct/uid_10023/pid_6490/cgroup.procs: No such file or directory
08-05 15:17:27.513  7036  7036 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-05 15:17:27.514  7036  7036 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 15:17:27.515  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-05 15:17:27.515  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-05 15:17:27.515  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-05 15:17:27.516  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-05 15:17:27.516  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-05 15:17:27.526  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-05 15:17:28.331  1035  2013 D WifiServiceImplEx: setWifiEnabled: true pid=6877, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-05 15:17:28.340  1035  2013 D WifiService: setWifiEnabled: true pid=6877, uid=10118
08-05 15:17:28.340  1035  2013 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 15:17:28.361  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 15:17:28.361  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 15:17:28.361  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-05 15:17:28.363  1035  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-05 15:17:28.363  1035  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-05 15:17:28.365  1035  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-05 15:17:28.365  1035  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 15:17:28.365  1035  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-05 15:17:28.365  1035  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 15:17:28.365  1035  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-05 15:17:28.366  1035  1539 E WifiHW  : unknown target_country: EU , set to default
08-05 15:17:28.366  1035  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-05 15:17:28.366  1035  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-05 15:17:28.366  1035  1539 I WifiUtil: gEnableBmps=1
08-05 15:17:28.398  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 15:17:28.411  1035  1111 D Tethering: MasterInitialState.processMessage what=3
08-05 15:17:28.415  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 15:17:28.435  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 15:17:28.439  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:28.444  1035  1111 D Tethering: MasterInitialState.processMessage what=3
08-05 15:17:28.453  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 15:17:28.458  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:28.458  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:28.460  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 15:17:28.464  6379  7004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 15:17:28.475  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 15:17:28.491  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-05 15:17:28.508  2232  2232 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 15:17:28.566  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-05 15:17:28.599  1035  1644 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7156 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-05 15:17:28.604  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:28.604  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 15:17:28.714  7156  7156 I AppUp4:AppBoxCP: onCreate
,08-05 15:17:28.715  7156  7156 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-05 15:17:28.725  7156  7156 I AppUp4:DB:  setFingerPrint start
08-05 15:17:28.726  7156  7156 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-05 15:17:28.735  7156  7156 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-05 15:17:28.735  7156  7156 I AppUp4:DB:  SDK version = 21
08-05 15:17:28.735  7156  7156 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-05 15:17:28.737  7156  7156 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-05 15:17:28.738  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-05 15:17:28.739  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:28.741  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 15:17:28.741  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 15:17:28.750  7156  7156 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 15:17:28.807  7156  7156 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 15:17:28.807  7156  7156 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 15:17:28.817  7156  7156 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2a9df96f
08-05 15:17:28.818  7156  7156 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-05 15:17:28.818  7156  7156 D AppUp4:CustFacade: isPhone : true
08-05 15:17:28.819  7156  7156 D AppUp4:CustModeStarterReceiver: begin check event
08-05 15:17:28.820  7156  7156 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-05 15:17:28.821  7156  7156 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,08-05 15:17:28.822  7156  7191 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-05 15:17:28.822  7156  7191 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-05 15:17:28.822  7156  7191 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-05 15:17:28.829  1035  1781 I ActivityManager: Killing 6579:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-05 15:17:28.901  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-05 15:17:28.902  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 15:17:28.904  1035  1051 W libprocessgroup: failed to open /acct/uid_10061/pid_6579/cgroup.procs: No such file or directory
08-05 15:17:28.907  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 15:17:28.916  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 15:17:28.935  4785  7201 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 15:17:28.938  4785  7202 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:28.938  4785  7202 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-05 15:17:28.981  1035  2048 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7204 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-05 15:17:29.042  7204  7204 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 15:17:29.043  7204  7204 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 15:17:29.044  7204  7204 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 15:17:29.045  7204  7204 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 15:17:29.110   318   894 D SoftapController: Softap fwReload - Ok
08-05 15:17:29.111  1035  1539 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (741ms)
,08-05 15:17:29.114  1035  1111 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 15:17:29.116   318   894 D CommandListener: Setting iface cfg
08-05 15:17:29.116   318   894 D CommandListener: Trying to bring down wlan0
08-05 15:17:29.117   318   894 D CommandListener: Clearing all IP addresses on wlan0
08-05 15:17:29.117  1035  1111 D Tethering: InitialState.processMessage what=4
08-05 15:17:29.118  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 15:17:29.119  1035  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-05 15:17:29.121  1035  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 15:17:29.121  1035  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 15:17:29.121  1035  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 15:17:29.124  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 15:17:29.127  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-05 15:17:29.112  7222  7222 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:29.112  7222  7222 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:29.133  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-05 15:17:29.134  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:29.134  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:29.134  1035  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-05 15:17:29.134  1035  1539 D WifiMonitor: connecting to supplicant
,08-05 15:17:29.151  7222  7222 I wpa_supplicant: Successfully initialized wpa_supplicant
08-05 15:17:29.177  7204  7204 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 15:17:29.180  7222  7222 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-05 15:17:29.180  7222  7222 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-05 15:17:29.195  7204  7204 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-05 15:17:29.244  7204  7204 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 15:17:29.280  7222  7222 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 15:17:29.283  7204  7204 D LgDataFeature: LgDataFeature() Constructor: none
08-05 15:17:29.283  7204  7204 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 15:17:29.325  7222  7222 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-05 15:17:29.332  7222  7222 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-05 15:17:29.333  7222  7222 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-05 15:17:29.334  1035  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-05 15:17:29.334  1035  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-05 15:17:29.335  1035  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-05 15:17:29.335  1035  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-05 15:17:29.336  1035  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:29.337  1035  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:29.339  1035  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:29.340  1035  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:29.341  1035  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-05 15:17:29.341  1035  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,08-05 15:17:29.343  1035  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-05 15:17:29.343  1035  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-05 15:17:29.343  1035  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-05 15:17:29.344  1035  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 15:17:29.344  1035  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 15:17:29.344  1035  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 15:17:29.344  1035  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-05 15:17:29.344  1035  7233 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 15:17:29.344  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:29.344  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-05 15:17:29.344  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-05 15:17:29.344  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:29.344  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:29.345  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 15:17:29.345  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 15:17:29.345  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-05 15:17:29.345  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-05 15:17:29.347  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:29.350  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-05 15:17:29.350  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-05 15:17:29.351  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:29.351  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:29.351  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:29.351  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:29.351  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:29.351  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 15:17:29.351  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 15:17:29.351  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 15:17:29.351  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 15:17:29.351  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:29.351  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 15:17:29.352  1035  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-05 15:17:29.352  1035  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-05 15:17:29.353  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:29.353  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:29.353  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:29.353  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:29.353  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:29.353  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 15:17:29.353  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 15:17:29.353  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 15:17:29.353  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 15:17:29.353  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:29.353  1035  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-05 15:17:29.353  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 15:17:29.353  1035  1539 D WifiConfigStore: Loading config and enabling all networks 
08-05 15:17:29.353  1035  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-05 15:17:29.354  1035  1539 D Wif,iNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-05 15:17:29.363  1035  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-05 15:17:29.373  1035  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-05 15:17:29.373  1035  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-05 15:17:29.374  1035  1539 D WifiStateMachine: enableVerboseLogging : level 2
08-05 15:17:29.374  1035  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-05 15:17:29.375  1035  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-05 15:17:29.375  1035  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-05 15:17:29.375  1035  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-05 15:17:29.375  1035  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-05 15:17:29.376  1035  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-05 15:17:29.376  1035  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-05 15:17:29.377  1035  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-05 15:17:29.377  1035  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-05 15:17:29.377  1035  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-05 15:17:29.377  1035  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-05 15:17:29.378  1035  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-05 15:17:29.378  1035  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-05 15:17:29.378  1035  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-05 15:17:29.379  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-05 15:17:29.380  1941  2352 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-05 15:17:29.380  1941  2352 D WfdsService: Set the WFDS Monitor: true
08-05 15:17:29.380  1941  2352 D WfdsMonitor: WfdsMonitorThread create
08-05 15:17:29.380  1035  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 15:17:29.380  1035  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-05 15:17:29.380  1941  2352 D WfdsMonitor: WFDS Monitor is created and started
08-05 15:17:29.380  1941  2352 D WfdsService: WiFi: Supplicant connection re-established
08-05 15:17:29.380  1035  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-05 15:17:29.380  1035  1539 D WifiNative-HAL: Setting external_sim to 1
08-05 15:17:29.380  1035  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-05 15:17:29.381  1035  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-05 15:17:29.381  1035  1539 I WifiNative-HAL: startHal
08-05 15:17:29.381  1035  1539 D wifi    : setting scan oui 0xaf73e1a0
08-05 15:17:29.381  1035  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 15:17:29.381  1035  1539 I WifiNative-HAL: startHal
08-05 15:17:29.381  1035  1539 D wifi    : setting scan oui 0xaf73e1a0
08-05 15:17:29.381  1035  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-05 15:17:29.382  1941  7234 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-05 15:17:29.382  1035  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-05 15:17:29.382  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-05 15:17:29.382  7222  7222 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-05 15:17:29.383  1035  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-05 15:17:29.383  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,08-05 15:17:29.383  1941  7234 E CtrlSupplicant: Succeed to open control connection
08-05 15:17:29.383  7222  7222 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 15:17:29.383  1035  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 15:17:29.383  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-05 15:17:29.384  1941  7234 E CtrlSupplicant: Succeed to open monitor connection
08-05 15:17:29.384  7222  7222 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-05 15:17:29.384  1941  7234 D WfdsMonitor: Supplicant connection established
08-05 15:17:29.384  1035  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-05 15:17:29.384  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 15:17:29.384  7222  7222 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 15:17:29.384  1941  2352 D WfdsService: Connected to the supplicant for wfds
08-05 15:17:29.384  1035  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 15:17:29.384  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,08-05 15:17:29.385  7222  7222 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 15:17:29.385  1035  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 15:17:29.385  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-05 15:17:29.385  7222  7222 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-05 15:17:29.385  1035  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-05 15:17:29.385  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 15:17:29.386  7222  7222 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 15:17:29.386  1035  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 15:17:29.387  1035  1539 E WifiNative: : [342,651,012 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-05 15:17:29.387  1035  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-05 15:17:29.387  1035  1539 D WifiNative-wlan0: RECONNECT: returned true
08-05 15:17:29.387  1035  1539 D WifiNative-wlan0: doString: [STATUS]
08-05 15:17:29.388  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 15:17:29.388  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 15:17:29.388  1035  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 15:17:29.388  1035  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 15:17:29.389  1035  1539 D WifiNative-wlan0: SET ps 1: returned true
08-05 15:17:29.390  1035  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.392   318   894 D CommandListener: Setting iface cfg
08-05 15:17:29.392   318   894 D CommandListener: Trying to bring up p2p0
08-05 15:17:29.392  1035  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 15:17:29.392  1035  1538 D LGWifiP2pService: P2pEnablingState
08-05 15:17:29.392  1035  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.392  1035  1538 D LGWifiP2pService: P2p socket connection successful
08-05 15:17:29.392  1035  1538 D LGWifiP2pService: P2pEnabledState
08-05 15:17:29.393  1035  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-05 15:17:29.394  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-05 15:17:29.394  1941  1941 D WfdsService: WifiP2pState is changed : true
08-05 15:17:29.395  1941  2352 D WfdsService: Receive the WFDS_ENABLE Method
08-05 15:17:29.395  1941  2352 D WfdsService: Set the WFDS Monitor: true
08-05 15:17:29.395  1941  2352 D WfdsService: Connected to the supplicant for wfds
08-05 15:17:29.395  1941  2352 D WfdsJNI : doCommand: WFDS_SET TRUE
08-05 15:17:29.395  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 15:17:29.395  7222  7222 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-05 15:17:29.395  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-05 15:17:29.395  1035  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.396  1035  1557 I WifiNative-HAL: startHal
08-05 15:17:29.396  1035  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf73e1a0
08-05 15:17:29.396  1035  1557 D wifi    : failed to get capabilities : -3
08-05 15:17:29.396  1035  1557 E WifiScanningService: could not get scan capabilities
08-05 15:17:29.396  1941  2352 D WfdsService: selectPreferredScanChannel [36]
08-05 15:17:29.396  1941  2352 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,08-05 15:17:29.398  1035  1558 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.399  1035  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-05 15:17:29.400  1035  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-05 15:17:29.400  1035  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-05 15:17:29.400  1035  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-05 15:17:29.401  1035  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-05 15:17:29.401  1035  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-05 15:17:29.401  1035  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-05 15:17:29.401  1035  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-05 15:17:29.401  1035  1538 D LGWifiP2pService: before postfix = G3
08-05 15:17:29.401  1035  1538 D WifiServerServiceExt: postfix byte check : 2
08-05 15:17:29.401  1035  1538 D LGWifiP2pService: after postfix = G3
08-05 15:17:29.401  1035  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-05 15:17:29.401  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-05 15:17:29.401  1035  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-05 15:17:29.402  1035  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-05 15:17:29.402  1035  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-05 15:17:29.402  1035  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-05 15:17:29.403  1035  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-05 15:17:29.403  1035  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-05 15:17:29.403  1941  1941 D WfdsService: isConnected: false
08-05 15:17:29.403  1035  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-05 15:17:29.403  1035  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-05 15:17:29.403  1035  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-05 15:17:29.403  1035  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-05 15:17:29.404  1035  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-05 15:17:29.404  1035  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-05 15:17:29.404  1035  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-05 15:17:29.404  1035  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-05 15:17:29.404  7222  7222 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-05 15:17:29.405  1035  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-05 15:17:29.406  1035  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-05 15:17:29.406  1035  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-05 15:17:29.406  1035  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-05 15:17:29.406  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-05 15:17:29.406  1035  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-05 15:17:29.406  1035  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-05 15:17:29.406  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-05 15:17:29.406  1035  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
08-05 15:17:29.406  1035  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-05 15:17:29.406  7222  7222 E wpa_supplicant: disconnect_rssi_lvl: -100
08-05 15:17:29.407  1941  1941 D WfdsService: Update P2p Interface State: 3
08-05 15:17:29.407  1035  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-05 15:17:29.407  1035  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-05 15:17:29.407  1035  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-05 15:17:29.408  1035  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-05 15:17:29.408  1035  1539 E WifiStateMac,hine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 15:17:29.408  1035  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 15:17:29.409  1035  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 15:17:29.409  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-05 15:17:29.418  1035  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-05 15:17:29.418  1035  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-05 15:17:29.418  1035  1538 D LGWifiP2pService: InactiveState
,08-05 15:17:29.418  1035  1538 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.418  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.418  1035  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-05 15:17:29.419  7222  7222 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 15:17:29.419  7222  7222 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:29.420  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 15:17:29.420  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:29.420  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:29.420  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:29.420  7222  7222 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 15:17:29.420  7222  7222 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.420  1035  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 15:17:29.420  1035  7233 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.420  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.420  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.421  7222  7222 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.421  1035  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-05 15:17:29.421  1035  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 15:17:29.421  1035  7233 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.421  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.421  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.421  1941  7234 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 15:17:29.422  1941  7234 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 15:17:29.422  7222  7222 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 15:17:29.422  7222  7222 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:29.423  1035  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-05 15:17:29.423  1035  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-05 15:17:29.423  7222  7222 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 15:17:29.423  7222  7222 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.423  1035  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-05 15:17:29.423  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-05 15:17:29.424  1035  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-05 15:17:29.424  1035  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 15:17:29.424  1035  7233 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:29.424  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:29.424  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:29.424  1035  7233 D WifiMonitor: Even,t [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 15:17:29.424  1035  7233 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.424  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.424  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.424  7222  7222 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.425  1035  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 15:17:29.425  1035  7233 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.425  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.425  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:29.425  1035  1538 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.425  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.425  7222  7222 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-05 15:17:29.425  1035  1538 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.425  7222  7222 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 15:17:29.425  1035  1538 D LGWifiP2pService: InactiveState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.425  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.426  1035  1538 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.426  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-05 15:17:29.426  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 15:17:29.426  1035  7233 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 15:17:29.426  1035  7233 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 15:17:29.426  1941  7234 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 15:17:29.426  1941  7234 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-05 15:17:29.426  1035  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-05 15:17:29.426  1941  7234 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 15:17:29.426  1035  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-05 15:17:29.426  1035  1538 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.426  1941  2352 W WfdsService: DefaultState - msg [9441285] is not handled
08-05 15:17:29.426  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.426  1035  1538 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.426  1035  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-05 15:17:29.426  1035  1539 D WifiNative-wlan0: doBoolean: SCAN
08-05 15:17:29.427  1035  1538 D LGWifiP2pService: InactiveState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.427  1035  1539 D WifiNative-wlan0: SCAN: returned false
,08-05 15:17:29.427  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.427  1035  1538 D LGWifiP2pService: DefaultState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.427  1035  1035 E WifiServerServiceExt: No p2p device connected
08-05 15:17:29.427  1035  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=342692  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 15:17:29.427  1035  1538 D LGWifiP2pService: InactiveState{ when=-6ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.427  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:29.430  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:29.430  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 15:17:29.430  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 15:17:29.430  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:29.430  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:29.431  1035  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=342696  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 15:17:29.431  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:29.432  1035  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 15:17:29.432  1035  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-05 15:17:29.433  1035  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 15:17:29.433  1035  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 15:17:29.434  1035  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-05 15:17:29.434  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 15:17:29.435  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-05 15:17:29.436  7204  7204 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-05 15:17:29.470  3356  3356 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-05 15:17:29.470  3356  3356 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:29.470  3356  3356 I LgeMiscReceiver: networkInfo.isConnected() = false
08-05 15:17:29.472  7204  7204 I HubEmail: JNI_OnLoad()
08-05 15:17:29.472  7204  7204 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 15:17:29.472  7204  7204 I HubEmail: registerNatives()
08-05 15:17:29.472  7204  7204 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 15:17:29.472  7204  7204 I HubEmail: registerNativeMethods()
08-05 15:17:29.472  7204  7204 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 15:17:29.473  7204  7204 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-05 15:17:29.526  1035  2051 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7240 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-05 15:17:29.536  7077  7237 W FormManager: Network not available. Please check & try again.
08-05 15:17:29.537  7204  7239 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:29.544  7077  7238 V FormManager: Network unavailable.
,08-05 15:17:29.553  7077  7238 V FormManager: Network unavailable.
08-05 15:17:29.560  1035  1887 I ActivityManager: Killing 6635:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-05 15:17:29.614  1035  1978 W libprocessgroup: failed to open /acct/uid_10080/pid_6635/cgroup.procs: No such file or directory
,08-05 15:17:29.813  1035  1576 I art     : Explicit concurrent mark sweep GC freed 79987(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.620ms total 180.655ms
,08-05 15:17:29.855  7222  7222 E wpa_supplicant: USIM:  scard_init function
08-05 15:17:29.855  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-05 15:17:29.856  1035  7233 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-05 15:17:29.856  7222  7222 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-05 15:17:29.856  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-05 15:17:29.856  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-05 15:17:29.856  1035  7233 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-05 15:17:29.856  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-05 15:17:29.856  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-05 15:17:29.861  1035  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-05 15:17:29.862  1035  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
,08-05 15:17:29.864  1035  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-05 15:17:29.865  1035  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-05 15:17:29.865  1035  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-05 15:17:29.869  1035  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=343134  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-05 15:17:29.875  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:29.875  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:29.877  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:29.879  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:29.879  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:29.879  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 15:17:29.879  1035  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=343144  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-05 15:17:29.879  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:29.879  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:29.879  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 15:17:29.880  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 15:17:29.880  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-05 15:17:29.881  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:29.881  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:29.882  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:29.914  7240  7240 D LgDataFeature: LgDataFeature() Constructor: none
08-05 15:17:29.915  7240  7240 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 15:17:29.918  7240  7240 D PhoneMonitor: Register our PhoneStateListener
,08-05 15:17:29.936  7240  7240 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-05 15:17:29.941  7240  7240 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-05 15:17:29.963  7240  7240 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-05 15:17:29.964  7240  7240 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-05 15:17:29.964  7240  7240 D TelephonyAutoProfiling: [parse] Load xml
,08-05 15:17:29.966  7222  7222 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-05 15:17:29.967  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-05 15:17:29.967  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-05 15:17:29.967  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-05 15:17:29.967  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-05 15:17:29.970  1035  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=343234  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 15:17:29.970  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 15:17:29.970  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 15:17:29.971  1035  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=343236  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 15:17:29.972  1035  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=343236
08-05 15:17:29.973  1035  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=343238
08-05 15:17:29.974  1035  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=343239
08-05 15:17:29.974  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=343239
08-05 15:17:29.975  1035  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=343239
08-05 15:17:29.976  1035  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=343240  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 15:17:29.979  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-05 15:17:29.979  7222  7222 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 15:17:29.979  7222  7222 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 15:17:29.981  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 15:17:29.981  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-05 15:17:29.981  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 15:17:29.981  1035  7233 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 15:17:29.982  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-05 15:17:29.982  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 15:17:29.982  1035  7233 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 15:17:29.982  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 15:17:29.982  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 15:17:29.983  7240  7240 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-05 15:17:29.983  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-05 15:17:29.983  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-05 15:17:29.984  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-05 15:17:29.984  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-05 15:17:29.984  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-05 15:17:29.984  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-05 15:17:29.984  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-05 15:17:29.984  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-05 15:17:29.984  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-05 15:17:29.984  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-05 15:17:29.984  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-05 15:17:29.984  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-05 15:17:29.984  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-05 15:17:29.984  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-05 15:17:29.984  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-05 15:17:29.984  7240  7240 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-05 15:17:29.996  7240  7240 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-05 15:17:30.000  1035  2013 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7264 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 15:17:30.002  1035  2013 I ActivityManager: Killing 6653:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-05 15:17:30.053  1035  1111 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-05 15:17:30.054  1035  1886 W libprocessgroup: failed to open /acct/uid_10097/pid_6653/cgroup.procs: No such file or directory
08-05 15:17:30.064  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.064  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.064  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 15:17:30.065  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:30.065  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:30.066  1035  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=343330  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 15:17:30.067  1035  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=343331  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 15:17:30.067  1035  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=343332  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 15:17:30.068  1035  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=343333
08-05 15:17:30.068  1035  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=343333
08-05 15:17:30.069  1035  1539 D WifiNative-wlan0: doString: [STATUS]
08-05 15:17:30.070  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 15:17:30.070  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 15:17:30.071  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 15:17:30.073  1035  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 15:17:30.075  1035  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-05 15:17:30.076  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.076  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.076  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-05 15:17:30.077  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 15:17:30.077  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-05 15:17:30.084  1035  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-05 15:17:30.084  1035  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-05 15:17:30.089  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.089  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.089  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 15:17:30.091  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:30.092  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:30.093  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:30.095  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.095  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.095  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 15:17:30.100  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:30.100  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 15:17:30.101  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:30.104  1035  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-05 15:17:30.104  1035  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 15:17:30.104  1035  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 15:17:30.104  1035  1546 D ConnectivityService: Got NetworkAgent Messenger
08-05 15:17:30.104  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-05 15:17:30.104  1035  1546 D ConnectivityService: NetworkAgent connected
08-05 15:17:30.105  1035  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 15:17:30.105  1035  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 15:17:30.107  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:30.107  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:30.109  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:30.112  1035  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 15:17:30.112  1035  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 15:17:30.112  1035  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 15:17:30.112  1035  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 15:17:30.112  1035  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 15:17:30.116  1035  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-05 15:17:30.118   318   894 D CommandListener: Setting iface cfg
08-05 15:17:30.121  1035  1539 E WifiStateMachine: Start Dhcp Watchdog 2
08-05 15:17:30.121  1035  7282 D DhcpStateMachine: StoppedState
08-05 15:17:30.122  1035  7282 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:30.122  1035  7282 D DhcpStateMachine: WaitBeforeStartState
08-05 15:17:30.122  1035  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=343387  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 15:17:30.123  1035  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=343388  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 15:17:30.124  1035  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=343388  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 15:17:30.124  1035  1539 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:30.125  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:30.125  1035  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:30.125  1035  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:30.126  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:30.126  1035  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:30.128  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 15:17:30.128  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-05 15:17:30.131  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-05 15:17:30.131  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-05 15:17:30.131  1035  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=343396  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-05 15:17:30.132  1035  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=343396  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 15:17:30.133  1035  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=343397  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 15:17:30.134  1035  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:297415] from screen [on:0 period:1524234902] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 15:17:30.135  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1524234903] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 15:17:30.135  1035  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 15:17:30.140  1035  1546 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-05 15:17:30.140  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:30.141  1035  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:30.141  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:30.142  1035  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:30.142  1035  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:30.142  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:30.143  1035  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-05 15:17:30.143  1035  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 15:17:30.144  1035  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=103,0,0
08-05 15:17:30.144  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=103,0,0
,08-05 15:17:30.145  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-05 15:17:30.145  7222  7222 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-05 15:17:30.145  1035  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-05 15:17:30.145  1035  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-05 15:17:30.146  1035  1539 D WifiNative-wlan0: SET ps 0: returned true
08-05 15:17:30.146  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-05 15:17:30.146  7222  7222 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-05 15:17:30.147  1035  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-05 15:17:30.147  1035  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-05 15:17:30.147  1035  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 15:17:30.147  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@6afd60c target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:30.147  1035  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 15:17:30.147  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@6afd60c target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:30.147  1035  7282 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:30.147  1035  7282 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-05 15:17:30.148   318   894 D CommandListener: Setting iface cfg
08-05 15:17:30.148   318   894 D CommandListener: Trying to bring up wlan0
08-05 15:17:30.149  1035  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-05 15:17:30.150  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 15:17:30.150  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 15:17:30.151  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 15:17:30.151  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 15:17:30.153  1035  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-05 15:17:30.153  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-05 15:17:30.153  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 15:17:30.153  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:30.153  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:30.153  7222  7222 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 15:17:30.154  1035  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 15:17:30.154  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
,08-05 15:17:30.154  7222  7222 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-05 15:17:30.155  1035  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-05 15:17:30.155  1035  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 15:17:30.172  1035  1539 D WifiNative-wlan0: SET ps 1: returned true
,08-05 15:17:30.173  1035  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-05 15:17:30.174  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:30.174  1035  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:30.174  1035  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 15:17:30.176  1035  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:30.177  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:30.177  1035  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:30.178  1035  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 15:17:30.179  1035  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 15:17:30.179  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 15:17:30.179  1035  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-05 15:17:30.180  1035  1546 D ConnectivityService: ignoring duplicate network state non-change
08-05 15:17:30.182  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:30.182  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:30.184  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.184  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.184  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-05 15:17:30.191  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:30.191  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.191  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.191  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-05 15:17:30.193  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-05 15:17:30.194  1035  1546 D ConnectivityService: Adding iface wlan0 to network 101
08-05 15:17:30.201  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 15:17:30.201  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.201  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.201  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 15:17:30.202  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:30.203  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:30.203  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-05 15:17:30.205  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 15:17:30.208  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 15:17:30.211  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.211  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:30.211  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 15:17:30.212  1035  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-05 15:17:30.225  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:30.225  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 15:17:30.226  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:30.226  1035  1546 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-05 15:17:30.226  1035  1546 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-05 15:17:30.227  1035  1546 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-05 15:17:30.228   318   894 E Netd    : netlink response contains error (File exists)
08-05 15:17:30.228  1035  1546 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-05 15:17:30.229  1035  1546 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-05 15:17:30.229  1035  1546 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-05 15:17:30.229  1035  1546 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-05 15:17:30.232  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:30.232  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 15:17:30.233  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 15:17:30.265  1035  1959 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7292 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-05 15:17:30.266  1035  1959 I ActivityManager: Killing 6703:com.lge.eula/1000 (adj 15): empty #17
08-05 15:17:30.303  1035  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 15:17:30.303  1035  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-05 15:17:30.303  1035  1546 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-05 15:17:30.303  1035  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 15:17:30.304  1035  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 15:17:30.304  1035  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:30.304  1035  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 15:17:30.304  1035  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:30.304  1035  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-05 15:17:30.304  1035  1546 D ConnectivityService: currentScore = 0, newScore = 20
08-05 15:17:30.304  1035  1546 D ConnectivityService:    accepting network in place of null
08-05 15:17:30.304  1035  1546 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:30.305  1035  7281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:30.305  1035  7281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-05 15:17:30.305  1035  7281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:30.305  1035  7281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 15:17:30.308  1035  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:30.308  1035  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 15:17:30.309  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:30.309  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 15:17:30.309  1035  1546 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{,20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-05 15:17:30.310  1035  1546 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-05 15:17:30.310   318  7310 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-05 15:17:30.310  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 15:17:30.310  1035  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:30.310  1035  1546 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-05 15:17:30.310  1035  1546 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-05 15:17:30.312  1035  1546 D ConnectivityService: validation of new default Network = false
08-05 15:17:30.312  1035  1546 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-05 15:17:30.312  1035  1546 D DSQN    : enableDataServiceNotify 
08-05 15:17:30.312  1035  1546 D DSQN    : start dsqn bin
08-05 15:17:30.315  1035  1576 W libprocessgroup: failed to open /acct/uid_1000/pid_6703/cgroup.procs: No such file or directory
08-05 15:17:30.324  1035  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 15:17:30.324  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:30.325  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:30.325  1035  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:30.312  7311  7311 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:30.312  7311  7311 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:30.326  1604  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-05 15:17:30.312  7311  7311 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:30.312  7311  7311 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:30.344  7311  7311 E DSQN    : DSQN ssw
,08-05 15:17:30.349  1035  7282 D DhcpStateMachine: DHCPV4 request on wlan0
08-05 15:17:30.349  1035  7282 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-05 15:17:30.349  1035  7282 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-05 15:17:30.342  7315  7315 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:30.342  7315  7315 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 15:17:30.361  7315  7315 I dhcpcd  : version 5.5.6 starting
08-05 15:17:30.363  7315  7315 E dhcpcd  : get_duid: m
08-05 15:17:30.363  7315  7315 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-05 15:17:30.363  7315  7315 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-05 15:17:30.366  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-05 15:17:30.366  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 15:17:30.366  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 15:17:30.367  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 15:17:30.367   318  7310 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-05 15:17:30.401   318  7310 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-05 15:17:30.407  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:30.407  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:30.407  1035  1538 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:30.416  1035  1978 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7321 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 15:17:30.417  1035  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 15:17:30.417  1035  1978 I ActivityManager: Killing 6727:com.lge.bnr/1000 (adj 15): empty #17
08-05 15:17:30.417  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 15:17:30.418  1035  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-05 15:17:30.418  1035  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 15:17:30.420  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-05 15:17:30.420  1035  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 15:17:30.434  7315  7315 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 15:17:30.434  7315  7315 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 15:17:30.434  7315  7315 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 15:17:30.435  7315  7315 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-05 15:17:30.435  7315  7315 D dhcpcd  : wlan0: sending REQUEST (xid 0x460d01dd), next in 4.99 seconds
,08-05 15:17:30.445   318   893 D LGDataListener: argv[0]=dsqncommand
08-05 15:17:30.445   318   893 D LGDataListener: argv[1]=wlan0
08-05 15:17:30.445   318   893 D LGDataListener: argv[2]=1
08-05 15:17:30.445   318   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-05 15:17:30.445  1035  1108 D DSQN    : DSQM DsqnNotification wlan0  1
08-05 15:17:30.445  1035  1108 D DSQN    : start to monitor internet connection
08-05 15:17:30.464  7315  7315 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-05 15:17:30.472  7315  7315 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-05 15:17:30.472  7315  7315 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-05 15:17:30.472  7315  7315 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-05 15:17:30.472  7315  7315 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-05 15:17:30.473  7315  7315 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 15:17:30.473  7315  7315 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 15:17:30.473  7315  7315 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 15:17:30.473  7315  7315 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-05 15:17:30.478  1035  1092 W ActivityManager: Failed to clear dns cache for: com.lge.bnr
,08-05 15:17:30.483  1035  1887 W libprocessgroup: failed to open /acct/uid_1000/pid_6727/cgroup.procs: No such file or directory
08-05 15:17:30.487  1035  7281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 13:17:30 GMT], X-Android-Received-Millis=[1470403050486], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470403050444]}
08-05 15:17:30.487  1035  7281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-05 15:17:30.487  1035  7281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-05 15:17:30.487  1035  1546 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-05 15:17:30.487  1035  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 15:17:30.487  1035  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 15:17:30.487  1035  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:30.488  1035  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 15:17:30.488  1035  1546 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-05 15:17:30.488  1035  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 15:17:30.488  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:30.488  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:30.488  1035  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:30.488  1035  1546 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:30.489  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-05 15:17:30.489  1035  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:30.489  1035  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 15:17:30.490  1604  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 15:17:30.490  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:30.490  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 15:17:30.495  1035  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-05 15:17:30.519  7321  7321 I art     : Almond Protected OAT
08-05 15:17:30.520  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 15:17:30.520  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:30.521  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 15:17:30.527  1816  7345 I CheckinService: active receiver: enabled
,08-05 15:17:30.538  1816  7345 I CheckinService: Preparing to send checkin request
08-05 15:17:30.538  1816  7345 I EventLogService: Accumulating logs since 1470402751505
,08-05 15:17:30.561  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 15:17:30.562  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:30.563  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:30.574  7321  7321 D WeatherApplication: removeAccount
,08-05 15:17:30.574  7321  7321 D WeatherApplication: Account.length = 0
08-05 15:17:30.575  7321  7321 E WeatherApplication: OPERATOR:OPEN
08-05 15:17:30.578  7321  7321 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:30
08-05 15:17:30.580  7321  7321 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 15:17:30.580  7321  7321 D Weather.Utils: 2 : All the weather widget is gone.
08-05 15:17:30.581  7321  7321 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 15:17:30.584  7321  7321 D WeatherAncestor: connectivity changed - connection : true
08-05 15:17:30.585  7321  7321 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-05 15:17:30.592  1816  7345 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-05 15:17:30.594  7321  7321 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 15:17:30.594  7321  7321 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 15:17:30.594  7321  7321 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-05 15:17:30.614  7321  7321 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 15:17:30.614  7321  7321 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:30
,08-05 15:17:30.660  1035  1886 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7363 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 15:17:30.661  1035  1886 I ActivityManager: Killing 6540:com.android.vending/u0a44 (adj 15): empty #17
08-05 15:17:30.704  1035  1940 W libprocessgroup: failed to open /acct/uid_10044/pid_6540/cgroup.procs: No such file or directory
,08-05 15:17:30.753  1035  7282 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-05 15:17:30.755  1035  7282 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-05 15:17:30.756  1035  7282 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 15:17:30.756  1035  7282 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-05 15:17:30.756  1035  7282 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-05 15:17:30.756  1035  7282 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 15:17:30.756  1035  7282 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-05 15:17:30.756  1035  7282 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-05 15:17:30.757  1035  7282 D DhcpStateMachine: RunningState
08-05 15:17:30.804  1035  1050 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7381 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-05 15:17:30.866   278   381 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 15:17:30.866   278   381 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 15:17:30.866   278   381 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 15:17:30.868  7363  7399 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-05 15:17:30.871   278   381 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 15:17:30.871   278   381 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 15:17:30.871   278   381 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 15:17:30.872  7363  7399 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 15:17:30.878   278   381 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 15:17:30.878   278   381 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 15:17:30.878   278   381 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 15:17:30.878  7363  7402 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-05 15:17:30.881   278   381 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 15:17:30.881   278   381 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 15:17:30.881   278   381 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 15:17:30.882  7363  7402 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-05 15:17:30.893  7381  7381 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-05 15:17:30.894  7381  7381 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-05 15:17:30.923  7381  7381 I MultiDex: VM with version 2.1.0 has multidex support
08-05 15:17:30.923  7381  7381 I MultiDex: install
08-05 15:17:30.924  7381  7381 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-05 15:17:30.938  7381  7381 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-05 15:17:31.137  7363  7363 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-05 15:17:31.173  7363  7363 I LibraryLoader: Loading: webviewchromium
08-05 15:17:31.177  7363  7363 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 4447-4454)
08-05 15:17:31.177  7363  7363 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-05 15:17:31.186  7363  7363 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {249bdd6}
,08-05 15:17:31.190  7363  7363 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 15:17:31.191  7363  7363 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 15:17:31.216  7363  7363 I BrowserStartupController: Initializing chromium process, renderers=0
,08-05 15:17:31.217  7363  7363 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 15:17:31.234  7363  7363 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-05 15:17:31.240  7363  7363 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-05 15:17:31.241  7363  7363 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-05 15:17:31.245   323  2159 V AudioPolicyService: registerClient() client 0xb04104e0, uid 10093
08-05 15:17:31.247  7363  7425 W AudioManagerAndroid: Requires BLUETOOTH permission
08-05 15:17:31.271  7363  7363 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 15:17:31.271  7363  7363 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 15:17:31.271  7363  7363 I Adreno-EGL: Build Date: 12/12/14 금
08-05 15:17:31.271  7363  7363 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 15:17:31.271  7363  7363 I Adreno-EGL: Remote Branch: 
08-05 15:17:31.271  7363  7363 I Adreno-EGL: Local Patches: 
08-05 15:17:31.271  7363  7363 I Adreno-EGL: Reconstruct Branch: 
,08-05 15:17:31.326  1035  1546 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-05 15:17:31.335  7381  7396 D LgDataFeature: LgDataFeature() Constructor: none
08-05 15:17:31.335  7381  7396 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 15:17:31.364  7363  7363 I NSApplication: Starting up...
08-05 15:17:31.366  1035  1914 D WifiServiceImplEx: setWifiEnabled: false pid=6877, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 15:17:31.366  1035  1914 D WifiService: setWifiEnabled: false pid=6877, uid=10118
08-05 15:17:31.366  1035  1914 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 15:17:31.374  1035  1539 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:31.374  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:31.374  1035  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:31.375  1035  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:31.375  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:31.376  1035  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:31.376  1035  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-05 15:17:31.376  1035  1546 D ConnectivityService: identical MTU - not setting
08-05 15:17:31.376  1035  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 15:17:31.376  1035  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-05 15:17:31.376  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:31.376  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:31.377  1035  1546 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:31.377  1604  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-05 15:17:31.377  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 15:17:31.378  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 15:17:31.378  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-05 15:17:31.381  1035  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 15:17:31.381  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 15:17:31.381  1035  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-05 15:17:31.382  1035  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-05 15:17:31.382  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-05 15:17:31.382  1035  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-05 15:17:31.382  1035  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 15:17:31.382  1035  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-05 15:17:31.383  1035  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,08-05 15:17:31.383  1035  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 15:17:31.398  1035  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 15:17:31.400  1035  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:31.400  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:31.400  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 15:17:31.400  7222  7222 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-05 15:17:31.401  1035  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 15:17:31.401  1035  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 15:17:31.401  1035  1539 D WifiNative-wlan0: SET ps 1: returned true
08-05 15:17:31.402   318   894 D CommandListener: Clearing all IP addresses on wlan0
08-05 15:17:31.403  1035  7282 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:31.429  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-05 15:17:31.429  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-05 15:17:31.444  1035  1576 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7440 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-05 15:17:31.445  1035  1576 I ActivityManager: Killing 6810:com.lge.clock/u0a10 (adj 15): empty #17
,08-05 15:17:31.483  1035  1546 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-05 15:17:31.483  1035  1546 D DSQN    : disableDataServiceNotify
08-05 15:17:31.483  1035  1546 D DSQN    : stop dsqn bin
,08-05 15:17:31.489  1035  1546 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-05 15:17:31.489  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:31.489  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:31.489  1035  1546 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:31.490  1035  1546 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-05 15:17:31.490  1035  7281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:31.490  1035  1546 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-05 15:17:31.490  1035  7281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:31.490  1035  7281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-05 15:17:31.490  1035  1546 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-05 15:17:31.490  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 15:17:31.490  1604  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-05 15:17:31.504  1035  1978 W libprocessgroup: failed to open /acct/uid_10010/pid_6810/cgroup.procs: No such file or directory
,08-05 15:17:31.504  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:31.504  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:31.504  1035  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@21699fa5
08-05 15:17:31.504  1035  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:31.505  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:31.505  1035  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:31.506  1035  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:31.507  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:31.507  1035  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:31.507  1035  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-05 15:17:31.508  1035  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:31.508  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:31.508  1035  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:31.511  1035  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:31.511  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 15:17:31.511  1035  1538 D LGWifiP2pService: P2pDisablingState
08-05 15:17:31.511  1035  1538 D LGWifiP2pService: P2pDisablingState{ when=-8ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:31.511  1035  1538 D LGWifiP2pService: p2p socket connection lost
08-05 15:17:31.511  1035  1538 D LGWifiP2pService: P2pDisabledState
08-05 15:17:31.512  1035  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-05 15:17:31.512  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 15:17:31.512  1035  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:31.512  1035  1538 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:31.513  7222  7222 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 15:17:31.514  1035  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 15:17:31.514  1035  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 15:17:31.514  1035  1539 D WifiNative-wlan0: SET ps 1: returned true
08-05 15:17:31.515  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-05 15:17:31.515   318   894 D CommandListener: Clearing all IP addresses on wlan0
08-05 15:17:31.516  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:31.516  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 15:17:31.518  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-05 15:17:31.518  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:31.518  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:31.518  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 15:17:31.518  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:31.519  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-05 15:17:31.522  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:31.522  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:31.522  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 15:17:31.523  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-05 15:17:31.523  1035  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:31.523  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-05 15:17:31.523  1035  1558 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:31.523  1035  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 15:17:31.525  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 15:17:31.525  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 15:17:31.525  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 15:17:31.525  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 15:17:31.525  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 15:17:31.526  1941  1941 D WfdsService: WifiP2pState is changed : false
08-05 15:17:31.526  1941  2352 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-05 15:17:31.526  1941  2352 D WfdsService: Set the WFDS Monitor: false
08-05 15:17:31.528  1941  2352 D WfdsMonitor: WFDS Monitor is stopped
08-05 15:17:31.528  1941  7234 D CtrlSupplicant: Received on exit socket, terminate
08-05 15:17:31.528  1941  7234 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-05 15:17:31.528  1941  2352 D WfdsService: STATE : WfdsDisabledState - enter
08-05 15:17:31.528  1941  7234 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-05 15:17:31.528  1941  7234 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-05 15:17:31.528  1941  2352 W WfdsService: DefaultState - msg [9445378] is not handled
08-05 15:17:31.528  1941  2356 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
,08-05 15:17:31.537  1035  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:31.537  1035  1546 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:31.537  1035  1546 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:31.537  1035  1546 D NetworkManagementService: Removing idletimer
08-05 15:17:31.537  1035  1546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:31.537  1035  1546 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-05 15:17:31.538  1035  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,08-05 15:17:31.538  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 15:17:31.538  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 15:17:31.539  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 15:17:31.539  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 15:17:31.539  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:31.539  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 15:17:31.540  1035  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-05 15:17:31.541  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-05 15:17:31.541  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:31.542  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:31.542  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 15:17:31.542  1035  1539 D WifiNative-p2p0: TERMINATE: returned true
08-05 15:17:31.542  1035  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 15:17:31.542  1035  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 15:17:31.542  1035  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 15:17:31.543  1035  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:31.543  1035  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-05 15:17:31.546  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-05 15:17:31.546  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:31.546  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:31.546  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:31.546  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:31.546  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 15:17:31.546  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 15:17:31.546  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 15:17:31.546  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 15:17:31.546  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 15:17:31.546  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:31.546  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 15:17:31.547  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-05 15:17:31.547  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-05 15:17:31.547  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-05 15:17:31.548  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:31.548  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:31.548  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:31.548  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:31.548  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 15:17:31.548  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 15:17:31.548  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 15:17:31.548  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 15:17:31.548  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 15:17:31.548  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:31.548  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 15:17:31.549  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:31.549  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:31.551  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 15:17:31.573  7440  7440 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 15:17:31.577  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 15:17:31.579  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:31.579  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:31.597  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 15:17:31.598  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:31.598  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 15:17:31.599  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 15:17:31.599  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:31.599  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:31.601  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:31.608  1035  7282 D DhcpStateMachine: StoppedState
08-05 15:17:31.608  1035  7282 D DhcpStateMachine: StoppedState{ when=-94ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:31.609  1035  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-05 15:17:31.609  1035  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-05 15:17:31.615  7460  7460 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-05 15:17:31.634  7222  7222 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-05 15:17:31.634  7222  7222 I wpa_supplicant: monitor socket send errors count : 1
08-05 15:17:31.634  7222  7222 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
08-05 15:17:31.640  1035  7233 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-05 15:17:31.640  1035  7233 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-05 15:17:31.678  7222  7222 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 15:17:31.679  7222  7222 W wpa_supplicant: USIM:  scard_deinit function
,08-05 15:17:31.680  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-05 15:17:31.680  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 15:17:31.680  1035  7233 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 15:17:31.680  1035  7233 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-05 15:17:31.680  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 15:17:31.680  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 15:17:31.681  1035  1111 D Tethering: InitialState.processMessage what=4
08-05 15:17:31.681  1035  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=344946
08-05 15:17:31.681  1035  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=344946
08-05 15:17:31.682  1035  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=344946  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 15:17:31.682  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 15:17:31.682  1035  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=344947  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 15:17:31.683  1035  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:31.683  1035  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:31.687  7460  7460 I dex2oat : dex2oat took 71.524ms (threads: 4)
08-05 15:17:31.702  7381  7396 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 15:17:31.702  7381  7396 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 15:17:31.702  7381  7396 I Adreno-EGL: Build Date: 12/12/14 금
08-05 15:17:31.702  7381  7396 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 15:17:31.702  7381  7396 I Adreno-EGL: Remote Branch: 
08-05 15:17:31.702  7381  7396 I Adreno-EGL: Local Patches: 
08-05 15:17:31.702  7381  7396 I Adreno-EGL: Reconstruct Branch: 
,08-05 15:17:31.803  7222  7222 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-05 15:17:31.803  1035  7233 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-05 15:17:31.803  1035  7233 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-05 15:17:31.803  1035  7233 D WifiMonitor: Disconnecting from the supplicant, no more events
08-05 15:17:31.806  1035  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,08-05 15:17:31.811  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-05 15:17:31.811  1941  2352 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-05 15:17:31.811  1941  2352 D WfdsService: Set the WFDS Monitor: false
08-05 15:17:31.811  1941  2352 D WfdsMonitor: WFDS Monitor is stopped
08-05 15:17:31.811  1035  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-05 15:17:31.811  7381  7396 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 15:17:31.811  7381  7396 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 15:17:31.811  7381  7396 I Adreno-EGL: Build Date: 12/12/14 금
08-05 15:17:31.811  7381  7396 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 15:17:31.811  7381  7396 I Adreno-EGL: Remote Branch: 
08-05 15:17:31.811  7381  7396 I Adreno-EGL: Local Patches: 
08-05 15:17:31.811  7381  7396 I Adreno-EGL: Reconstruct Branch: 
08-05 15:17:31.811  1035  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 15:17:31.811  1035  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 15:17:31.811  1035  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 15:17:31.814  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 15:17:31.814  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:31.815  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-05 15:17:31.815  1035  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-05 15:17:31.815  1035  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-05 15:17:31.815  2502  2502 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:31.817  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:31.818  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:31.835  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-05 15:17:31.836  6379  7004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 15:17:31.850  2232  2232 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 15:17:31.856  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 15:17:31.856  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:31.856  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 15:17:31.856  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 15:17:31.857  7156  7156 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 15:17:31.865  7156  7156 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2a9df96f
08-05 15:17:31.865  7156  7156 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 15:17:31.865  7156  7156 D AppUp4:CustFacade: isPhone : true
08-05 15:17:31.865  7156  7156 D AppUp4:CustModeStarterReceiver: begin check event
08-05 15:17:31.865  7156  7156 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 15:17:31.867  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:31.868  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 15:17:31.868  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 15:17:31.870  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 15:17:31.873  4785  7478 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 15:17:31.875  4785  7479 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:31.875  4785  7479 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-05 15:17:31.878  7204  7204 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-05 15:17:31.885  7381  7396 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 15:17:31.885  7381  7396 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 15:17:31.885  7381  7396 I Adreno-EGL: Build Date: 12/12/14 금
08-05 15:17:31.885  7381  7396 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 15:17:31.885  7381  7396 I Adreno-EGL: Remote Branch: 
08-05 15:17:31.885  7381  7396 I Adreno-EGL: Local Patches: 
08-05 15:17:31.885  7381  7396 I Adreno-EGL: Reconstruct Branch: 
08-05 15:17:31.895  3356  3356 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 15:17:31.896  3356  3356 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:31.896  3356  3356 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-05 15:17:31.902  7240  7240 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 15:17:31.902  7240  7240 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 15:17:31.913  7204  7482 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 15:17:31.914  7077  7484 W FormManager: Network not available. Please check & try again.
08-05 15:17:31.920  7077  7485 V FormManager: Network unavailable.
08-05 15:17:31.925  7321  7321 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:31
08-05 15:17:31.927  7077  7485 V FormManager: Network unavailable.
,08-05 15:17:31.929  7321  7321 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 15:17:31.929  7321  7321 D Weather.Utils: 2 : All the weather widget is gone.
08-05 15:17:31.929  7321  7321 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 15:17:31.929  7321  7321 D WeatherAncestor: connectivity changed - connection : true
08-05 15:17:31.930  7321  7321 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@cf22b05
08-05 15:17:31.931  7321  7321 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 15:17:31.933  7321  7321 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 15:17:31.933  7321  7321 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 15:17:31.933  7321  7321 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 15:17:31.933  7321  7321 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:31
08-05 15:17:31.958  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 15:17:31.958  6961  6961 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 15:17:31.958  6961  6961 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 15:17:31.958  6961  6961 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 15:17:31.959  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 15:17:31.959  6961  6961 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 15:17:31.960  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 15:17:31.960  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 15:17:31.960  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 15:17:31.960  6961  6961 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 15:17:31.960  6961  6961 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-05 15:17:31.966  7005  7005 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 15:17:31.969  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 15:17:31.972  7077  7487 W FormManager: Network not available. Please check & try again.
08-05 15:17:31.973   318  7490 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 15:17:31.974  1035  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 15:17:31.975  7077  7488 V FormManager: Network unavailable.
08-05 15:17:31.975  1816  7345 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-05 15:17:31.977  7077  7488 V FormManager: Network unavailable.
08-05 15:17:31.979  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:31.982  1816  7345 I CheckinService: active receiver: disabled
,08-05 15:17:32.005  7005  7005 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 15:17:32.007  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 15:17:32.010  7077  7492 W FormManager: Network not available. Please check & try again.
08-05 15:17:32.014  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:32.014  7077  7493 V FormManager: Network unavailable.
08-05 15:17:32.019  7077  7493 V FormManager: Network unavailable.
,08-05 15:17:32.027  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-05 15:17:32.027  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 15:17:32.028  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 15:17:32.029  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 15:17:32.034  4785  7494 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 15:17:32.036  4785  7495 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 15:17:32.036  4785  7495 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-05 15:17:32.078  1035  2048 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7496 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-05 15:17:32.078  1035  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=619433655, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
08-05 15:17:32.108   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 458us total 28.465ms
08-05 15:17:32.112  2580  2580 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 15:17:32.131   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 423us total 20.423ms
,08-05 15:17:32.150   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 366us total 18.609ms
,08-05 15:17:32.183  7496  7496 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-05 15:17:32.183  7496  7496 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-05 15:17:32.191  7496  7496 V [BNRBootReceiver]: Boot Receiver Return
,08-05 15:17:32.192  7496  7496 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-05 15:17:32.195  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:32.203  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:32.214  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:32.227  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 15:17:32.227  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:32.229  7036  7036 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 15:17:32.232  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-05 15:17:32.238  6961  6961 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-05 15:17:32.245  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 15:17:32.259  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:32.268  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 15:17:32.276  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:32.276  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:32.278  7036  7036 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 15:17:32.282  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:32.298  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:32.307  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:32.317  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:32.317  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 15:17:32.318  7036  7036 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 15:17:32.326  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 15:17:32.339  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:32.351  6749  7147 D UEI.SmartControl: Internal timer expired: 2
08-05 15:17:32.351  6749  7147 D UEI.SmartControl: unbind internal service
,08-05 15:17:32.356  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:32.371  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:32.372  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:32.373  7036  7036 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 15:17:32.380  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:32.392  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:32.403  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:32.415  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:32.416  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:32.417  7036  7036 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 15:17:32.425  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:32.439  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:32.448  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:32.459  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:32.459  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:32.460  7036  7036 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 15:17:32.469  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:32.480  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:32.487  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:32.493  6749  7144 D serial_port: close(fd = 24)
08-05 15:17:32.497  6749  7144 I UEI.SmartControl: Serial port is closed.
,08-05 15:17:32.500  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:32.501  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 15:17:32.502  7036  7036 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 15:17:32.517  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 15:17:32.543  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:32.554  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:32.569  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:32.570  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 15:17:32.578  7036  7036 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 15:17:32.586  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:32.600  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:32.612  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:32.623  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 15:17:32.624  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:32.625  7036  7036 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 15:17:32.634  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:32.639  7005  7005 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 15:17:32.651  1035  1545 D WifiService: New client listening to asynchronous messages
08-05 15:17:32.653  7005  7005 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 15:17:32.657  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 15:17:32.665  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:32.674  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:32.674  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:32.676  7036  7036 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 15:17:32.677  7036  7036 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 15:17:32.677  7036  7036 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-05 15:17:32.683  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:32.689  7005  7005 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 15:17:32.691  7005  7005 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 15:17:32.698  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE,
,08-05 15:17:32.706  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:32.717  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 15:17:32.718  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:32.720  7036  7036 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 15:17:32.722  7036  7036 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 15:17:32.723  7036  7036 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 15:17:32.730  1035  2014 I ActivityManager: Killing 6984:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-05 15:17:32.764  1035  1051 W libprocessgroup: failed to open /acct/uid_10037/pid_6984/cgroup.procs: No such file or directory
,08-05 15:17:32.771  2232  2232 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-05 15:17:32.784  2232  2232 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-05 15:17:32.784  2232  2232 D c       : Getting all permits...
08-05 15:17:32.784  2232  2232 D a       : Opening database...
08-05 15:17:32.791  2232  2232 D a       : Opening database auth.proximity.permit_store...
08-05 15:17:32.792  2232  2232 D a       : Closing database...
08-05 15:17:32.810  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 15:17:32.819  7005  7005 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 15:17:32.819  7005  7005 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 15:17:32.820  7005  7005 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 15:17:32.826  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:32.837  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:32.851  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:32.852  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:32.855  7036  7036 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 15:17:32.861  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:32.869  7005  7005 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-05 15:17:32.870  7005  7005 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 15:17:32.870  7005  7005 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 15:17:32.879  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:32.887  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:32.898  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:32.898  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 15:17:32.900  7036  7036 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 15:17:32.903  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:32.907  7005  7005 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 15:17:32.907  7005  7005 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 15:17:32.908  7005  7005 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 15:17:32.912  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:32.918  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:32.925  7036  7036 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:32.926  7036  7036 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:32.927  7036  7036 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 15:17:32.935  7005  7005 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 15:17:32.939  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 15:17:32.948  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 15:17:32.958  7077  7521 W FormManager: Network not available. Please check & try again.
,08-05 15:17:32.962  7077  7522 V FormManager: Network unavailable.
08-05 15:17:32.967  7077  7522 V FormManager: Network unavailable.
08-05 15:17:32.975  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-05 15:17:32.975  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 15:17:32.977  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 15:17:32.981  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 15:17:32.986  4785  7523 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 15:17:32.991  4785  7524 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 15:17:32.991  4785  7524 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-05 15:17:33.000  7005  7005 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-05 15:17:33.000  7005  7005 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 15:17:33.000  7005  7005 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 15:17:33.004  7077  7526 W FormManager: Network not available. Please check & try again.
08-05 15:17:33.009  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 15:17:33.017  7077  7527 V FormManager: Network unavailable.
08-05 15:17:33.020  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:33.020  7077  7527 V FormManager: Network unavailable.
,08-05 15:17:33.038  2232  2232 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-05 15:17:33.056  7036  7036 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-05 15:17:33.056  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6042
08-05 15:17:33.057  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=619433655 [*alarm*], flags=0x0
,08-05 15:17:33.142  1035  1539 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1524237910] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 15:17:33.145  1035  1539 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1524237912] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 15:17:33.312  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 15:17:33.319  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:33.321  1035  1111 D Tethering: MasterInitialState.processMessage what=3
,08-05 15:17:33.323  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:33.324  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:33.328  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-05 15:17:33.333  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 15:17:33.339  6379  7004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 15:17:33.343  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 15:17:33.362  2232  2232 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 15:17:33.373  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 15:17:33.373  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:33.373  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 15:17:33.373  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 15:17:33.375  7156  7156 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 15:17:33.380  7156  7156 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2a9df96f
,08-05 15:17:33.380  7156  7156 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 15:17:33.380  7156  7156 D AppUp4:CustFacade: isPhone : true
08-05 15:17:33.380  7156  7156 D AppUp4:CustModeStarterReceiver: begin check event
08-05 15:17:33.380  7156  7156 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 15:17:33.384  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:33.385  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 15:17:33.386  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 15:17:33.388  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 15:17:33.403  4785  7535 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 15:17:33.405  7204  7204 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-05 15:17:33.411  4785  7537 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:33.411  4785  7537 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 15:17:33.426  7204  7538 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:33.430  3356  3356 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-05 15:17:33.430  3356  3356 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:33.431  3356  3356 I LgeMiscReceiver: networkInfo.isConnected() = true
08-05 15:17:33.431  3356  3356 D PhoneState: setPdpRejectCasuse : false
08-05 15:17:33.435  7240  7240 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 15:17:33.435  7240  7240 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 15:17:33.449  7321  7321 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:33
,08-05 15:17:33.451  7321  7321 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 15:17:33.451  7321  7321 D Weather.Utils: 2 : All the weather widget is gone.
08-05 15:17:33.452  7321  7321 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 15:17:33.452  7321  7321 D WeatherAncestor: connectivity changed - connection : true
08-05 15:17:33.452  7321  7321 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@cf22b05
08-05 15:17:33.453  7077  7541 W FormManager: Network not available. Please check & try again.
08-05 15:17:33.454  7321  7321 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 15:17:33.454  7321  7321 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 15:17:33.454  7321  7321 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 15:17:33.454  7321  7321 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 15:17:33.454  7321  7321 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:33
08-05 15:17:33.458  7077  7542 V FormManager: Network unavailable.
08-05 15:17:33.467  7077  7542 V FormManager: Network unavailable.
,08-05 15:17:34.381  1035  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 15:17:34.382  1035  1978 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-05 15:17:34.418  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 15:17:34.419  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 15:17:34.419  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-05 15:17:34.420  1035  1111 D BluetoothManagerService: Message: 1
08-05 15:17:34.420  1035  1111 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-05 15:17:34.447  1035  1111 D BluetoothManagerService: Message: 20
08-05 15:17:34.447  1035  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18a98515:true
,08-05 15:17:34.452  7106  7106 D BluetoothAdapterState: make
08-05 15:17:34.458  7106  7106 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-05 15:17:34.458  7106  7106 I bluedroid-qcom: init
08-05 15:17:34.459  7106  7550 I BluetoothAdapterState: Entering OffState
08-05 15:17:34.460  7106  7106 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 15:17:34.460  7106  7106 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 15:17:34.460  7106  7106 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 15:17:34.460  7106  7106 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 15:17:34.460  7106  7106 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-05 15:17:34.462  7106  7106 I bluedroid-qcom: get_profile_interface socket
08-05 15:17:34.462  7106  7106 I bluedroid-qcom: get_profile_interface map_client
,08-05 15:17:34.468  7106  7554 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-05 15:17:34.452  7553  7553 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:34.462  7553  7553 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:34.484  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-05 15:17:34.487  1035  1111 D BluetoothManagerService: Message: 40
08-05 15:17:34.487  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-05 15:17:34.488  7106  7123 I bluedroid-qcom: config_hci_snoop_log
08-05 15:17:34.489  1035  1111 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-05 15:17:34.489  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-05 15:17:34.492  7553  7553 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-05 15:17:34.492  7553  7553 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-05 15:17:34.492  7553  7553 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-05 15:17:34.497  7106  7550 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-05 15:17:34.500  7553  7553 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-05 15:17:34.502  7106  7554 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-05 15:17:34.504  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 15:17:34.505  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 15:17:34.505  7106  7554 D BluetoothAdapterProperties: Name is: G3
08-05 15:17:34.505  7106  7550 D BluetoothAdapterProperties: Setting state to 11
08-05 15:17:34.505  7106  7550 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-05 15:17:34.506  1035  1111 D BluetoothManagerService: Message: 60
08-05 15:17:34.506  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-05 15:17:34.506  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-05 15:17:34.508  7553  7553 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-05 15:17:34.508  7553  7553 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-05 15:17:34.510  7106  7550 I LGBluetoothServiceJni: classInitNative: succeeds
,08-05 15:17:34.515  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:34.520  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:34.520  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 15:17:34.525  6961  6961 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-05 15:17:34.530  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:34.536  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:34.537  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:34.549  1035  1111 D Tethering: MasterInitialState.processMessage what=3
,08-05 15:17:34.559  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:34.561  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:34.565  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 15:17:34.567  6379  7004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-05 15:17:34.572  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:34.577  7106  7106 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 15:17:34.578  7106  7106 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:34.578  7106  7106 V BluetoothPbapReceiver: ***********state = 11
08-05 15:17:34.587  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 15:17:34.590  1035  1111 D Tethering: MasterInitialState.processMessage what=3
08-05 15:17:34.594  7106  7550 D BluetoothBondStateMachine: make
08-05 15:17:34.598  7106  7550 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:34.598  7106  7550 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-05 15:17:34.598  7106  7550 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:34.598  7106  7550 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-05 15:17:34.598  7106  7550 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-05 15:17:34.599  7106  7569 I BluetoothBondStateMachine: StableState(): Entering Off State
08-05 15:17:34.604  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 15:17:34.605  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:34.608  7106  7550 E BluetoothAdapterService: File transfer profiles supported!!
08-05 15:17:34.609  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-05 15:17:34.611  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:34.615  7106  7550 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 15:17:34.617  7106  7106 D HeadsetService: Received start request. Starting profile...
08-05 15:17:34.617  7106  7106 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 15:17:34.617  7106  7106 D LGBluetoothHfpAdapter: Version 1.6
08-05 15:17:34.621  7106  7106 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 15:17:34.622  7106  7106 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 15:17:34.622  7106  7106 D HeadsetStateMachine: make
08-05 15:17:34.623  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 15:17:34.626  7106  7550 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 15:17:34.654  1035  1886 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7573 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-05 15:17:34.661  7106  7106 D LgDataFeature: LgDataFeature() Constructor: none
08-05 15:17:34.661  7106  7106 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 15:17:34.661  7106  7550 E BluetoothAdapterService: File transfer profiles supported!!
08-05 15:17:34.662  2232  2232 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:34.664  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:34.664  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:34.668  7106  7106 D HeadsetStateMachine: max_hf_connections = 1
08-05 15:17:34.668  7106  7106 I bluedroid-qcom: get_profile_interface handsfree
,08-05 15:17:34.668  7106  7550 E BluetoothAdapterService: File transfer profiles supported!!
08-05 15:17:34.670  7106  7106 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-05 15:17:34.671   323   323 V AudioPolicyService: registerClient() client 0xb558a5e0, uid 1002
08-05 15:17:34.671   323  1383 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-05 15:17:34.671   323  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 15:17:34.672   323  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 15:17:34.672  7106  7106 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 15:17:34.674  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 15:17:34.674  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:34.674   323  1384 V AudioFlinger: registerClient() client 0xb55815c8, pid 7106
08-05 15:17:34.674  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 15:17:34.674   323  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 15:17:34.674   323  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 15:17:34.674   323  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 15:17:34.674   323  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 15:17:34.675  7106  7106 V ToneGenerator: Create Track: 0xb4928a80
08-05 15:17:34.675  7106  7122 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 15:17:34.675  7106  7106 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-05 15:17:34.675  7106  7122 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-05 15:17:34.675  7106  7106 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-05 15:17:34.675  7106  7123 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 15:17:34.675  3356  3371 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 15:17:34.675  3356  3371 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 15:17:34.675  7106  7123 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-05 15:17:34.675  3356  3371 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 15:17:34.675  3356  3371 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 15:17:34.675   323   323 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 15:17:34.675   323   323 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-05 15:17:34.675   323   323 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 15:17:34.675   323   323 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 15:17:34.675  1852  4454 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 15:17:34.675  1852  4454 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 15:17:34.675  1852  4454 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 15:17:34.675  1852  4454 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 15:17:34.675  1604  1623 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 15:17:34.675  1604  1623 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 15:17:34.675  1035  1050 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 15:17:34.675   323  2159 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 15:17:34.675  1035  1050 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 15:17:34.675  1604  1623 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 15:17:34.675  16,04  1623 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 15:17:34.675   323  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 15:17:34.675   323  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-05 15:17:34.675  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 15:17:34.675   323  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 15:17:34.675   323  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 15:17:34.676  7106  7106 V AudioSystem: getLatency() output 2, latency 50
08-05 15:17:34.676  7106  7106 V AudioSystem: getFrameCount() output 2, frameCount 960
08-05 15:17:34.676  7106  7106 V AudioTrack: createTrack_l() output 2 afLatency 50
08-05 15:17:34.676  1035  1050 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 15:17:34.676  1035  1050 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 15:17:34.676   323  2160 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 15:17:34.676   323  2160 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 15:17:34.676   323  2160 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 15:17:34.676   323  2160 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 15:17:34.676   323  2160 V AudioFlinger: createTrack() lSessionId: 22
08-05 15:17:34.677  7156  7156 I AppUp4:CustModeStarterReceiver: onReceive
08-05 15:17:34.678  7106  7106 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-05 15:17:34.678  7106  7550 E BluetoothAdapterService: File transfer profiles supported!!
08-05 15:17:34.679   323  2159 V AudioFlinger: acquiring 22 from 7106, for 7106
08-05 15:17:34.679   323  2159 V AudioFlinger:  added new entry for 22
08-05 15:17:34.680  7106  7106 V ToneGenerator: ToneGenerator INIT OK, time: 347958
08-05 15:17:34.680  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:34.681  7106  7572 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-05 15:17:34.681  7106  7572 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 15:17:34.681  7106  7572 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 15:17:34.681  7106  7572 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-05 15:17:34.681  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:34.682   323  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7106
08-05 15:17:34.682   323  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-05 15:17:34.682   323  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-05 15:17:34.682   323  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-05 15:17:34.682   323  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 15:17:34.682   323  1383 V voice   : voice_set_parameters: exit with code(0)
08-05 15:17:34.682   323  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-05 15:17:34.682   323  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-05 15:17:34.682   323  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 15:17:34.682   323  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 15:17:34.682   323  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 15:17:34.682   323  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-05 15:17:34.683  7106  7572 V ToneGenerator: ToneGenerator destructor
08-05 ,15:17:34.683  7106  7572 V ToneGenerator: stopTone
08-05 15:17:34.683  7106  7572 V ToneGenerator: Delete Track: 0xb4928a80
08-05 15:17:34.684  7106  7106 D A2dpService: Received start request. Starting profile...
08-05 15:17:34.684  7106  7572 V AudioTrack: ~AudioTrack, releasing session id from 7106 on behalf of 7106
08-05 15:17:34.684   323   323 V AudioFlinger: releasing 22 from 7106 for 7106
08-05 15:17:34.684   323   323 V AudioFlinger:  decremented refcount to 0
08-05 15:17:34.684   323   323 V AudioFlinger: purging stale effects
08-05 15:17:34.685   323   323 V AudioPolicyService: AudioCommandThread() adding release output 2
08-05 15:17:34.685   323   323 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-05 15:17:34.685   323  1258 V AudioPolicyService: AudioCommandThread() waking up
08-05 15:17:34.685   323  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-05 15:17:34.685   323  1258 V AudioPolicyManager: releaseOutput() 2
08-05 15:17:34.685   323  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 15:17:34.685   323   323 V AudioFlinger: PlaybackThread::Track destructor
08-05 15:17:34.685  7106  7106 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 15:17:34.685   323   323 V AudioFlinger: removeClient_l() pid 7106, calling pid 323
08-05 15:17:34.685  1035  1914 W Process : Unable to open /proc/7587/status
08-05 15:17:34.686  7106  7106 V Avrcp   : make
08-05 15:17:34.686  7106  7106 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-05 15:17:34.686  7106  7106 I bluedroid-qcom: get_profile_interface avrcp
08-05 15:17:34.694  7106  7106 V AudioManager: registerRemoteController: size of Media player list: 0
08-05 15:17:34.696  7106  7106 E AudioManager: No RCC entry present to update
08-05 15:17:34.696  7106  7106 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-05 15:17:34.699  7106  7106 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-05 15:17:34.699  7106  7550 E BluetoothAdapterService: File transfer profiles supported!!
08-05 15:17:34.700  7106  7106 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-05 15:17:34.700  7106  7106 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-05 15:17:34.704  7156  7156 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2a9df96f
08-05 15:17:34.704  7156  7156 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 15:17:34.704  7156  7156 D AppUp4:CustFacade: isPhone : true
08-05 15:17:34.704  7156  7156 D AppUp4:CustModeStarterReceiver: begin check event
08-05 15:17:34.704  7156  7156 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 15:17:34.710  7106  7550 V LGMDMManager: Create singleton instance
,08-05 15:17:34.712  7106  7550 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-05 15:17:34.714  7106  7106 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-05 15:17:34.716  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:34.716  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 15:17:34.721  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 15:17:34.750  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 15:17:34.758  4785  7595 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 15:17:34.761  4785  7596 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:34.761  4785  7596 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-05 15:17:34.763  7204  7204 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-05 15:17:34.780  3356  3356 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 15:17:34.780  3356  3356 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:34.780  3356  3356 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-05 15:17:34.788  7240  7240 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 15:17:34.788  7240  7240 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 15:17:34.792  7077  7600 W FormManager: Network not available. Please check & try again.
,08-05 15:17:34.792  7204  7598 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:34.796  1035  1977 V SIM_STK : Menu title from STK is T-Mobile
08-05 15:17:34.796  1035  1977 V SIM_STK : Menu title from STK is T-Mobile
08-05 15:17:34.805  7077  7601 V FormManager: Network unavailable.
,08-05 15:17:34.809  7077  7601 V FormManager: Network unavailable.
08-05 15:17:34.854  1035  2048 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-05 15:17:34.859  7106  7106 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 15:17:34.862  7106  7106 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 15:17:34.863  7106  7106 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 15:17:34.863  7106  7106 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 15:17:34.863  7106  7106 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 15:17:34.863  7106  7106 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 15:17:34.863  7106  7106 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 15:17:34.863  7106  7106 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 15:17:34.863  7106  7106 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 15:17:34.863  7106  7106 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 15:17:34.863  7106  7106 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 15:17:34.864  7106  7106 I BluetoothA2dpServiceJni: classInitNative
08-05 15:17:34.864  7106  7106 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 15:17:34.864  7106  7106 D A2dpStateMachine: make
08-05 15:17:34.865  7106  7106 I bluedroid-qcom: get_profile_interface a2dp
08-05 15:17:34.865  7106  7605 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-05 15:17:34.867  7106  7106 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-05 15:17:34.867  7106  7106 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-05 15:17:34.868  7106  7604 D A2dpStateMachine: Enter Disconnected: -2
08-05 15:17:34.868  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:34.869  7106  7106 I BluetoothHidServiceJni: classInitNative: succeeds
08-05 15:17:34.869  1035  1940 I art     : Explicit concurrent mark sweep GC freed 120715(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.040ms total 81.732ms
08-05 15:17:34.869  1035  1048 I art     : WaitForGcToComplete blocked for 57.174ms for cause HeapTrim
08-05 15:17:34.870  7106  7106 D HidService: Received start request. Starting profile...
08-05 15:17:34.870  7106  7106 I bluedroid-qcom: get_profile_interface hidhost
08-05 15:17:34.870  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:34.870  7106  7106 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 15:17:34.871  7106  7106 D HealthService: Received start request. Starting profile...
08-05 15:17:34.872  7106  7106 I bluedroid-qcom: get_profile_interface health
08-05 15:17:34.872  7106  7106 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-05 15:17:34.872  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:34.872  7106  7106 D HeadsetStateMachine: Proxy object connected
08-05 15:17:34.873  7106  7106 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-05 15:17:34.873  7106  7106 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-05 15:17:34.874  7106  7106 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-05 15:17:34.877  7106  7106 D PanService: Received start request. Starting profile...
08-05 15:17:34.877  7106  7106 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 15:17:34.877  7106  7106 I bluedroid-qcom: get_profile_interface pan
08-05 15:17:34.877  7573  7573 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 15:17:34.877  7573  7573 W LG Account v2.2: No ProfileInfo entries
08-05 15:17:34.878  7573  7573 I LG Account v2.2: isEnabled: false
08-05 15:17:34.878  7573  7573 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 15:17:34.878  7573  7573 I Feature : [Lifetracker]Country: EU
08-05 15:17:34.878  7573  7573 I Feature : [Lifetracker]Operator: OPEN
08-05 15:17:34.878  7573  7573 I Feature : [Lifetracker]Ranking support: false
08-05 15:17:34.878  7573  7573 I Feature : [Lifetracker]Comfort support: false
08-05 15:17:34.878  7573  7573 I Feature : [Lifetracker]Accessory: true
08-05 15:17:34.878  7573  7573 I Feature : [Lifetracker]Health device: true
08-05 15:17:34.878  7573  7573 I Feature : [Lifetracker]Extra Pedometer: false
08-05 15:17:34.878  7573  7573 I Feature : [Lifetracker]Blood glucose device: false
08-05 15:17:34.878  7573  7573 I Feature : [Lifetracker]Device Number: 3
,08-05 15:17:34.883  7106  7106 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-05 15:17:34.884  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:34.884  7106  7572 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 15:17:34.885  7106  7572 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 15:17:34.885  7106  7572 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-05 15:17:34.885  7321  7321 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:34
08-05 15:17:34.886  7106  7106 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 15:17:34.886  7321  7321 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 15:17:34.886  7321  7321 D Weather.Utils: 2 : All the weather widget is gone.
08-05 15:17:34.886  7106  7106 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-05 15:17:34.886  7321  7321 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 15:17:34.886  7321  7321 D WeatherAncestor: connectivity changed - connection : true
08-05 15:17:34.887  7321  7321 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@cf22b05
08-05 15:17:34.888  6961  6961 D BluetoothPermissionRequest: onReceive
08-05 15:17:34.890  7106  7106 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 15:17:34.890  7106  7106 D BtGatt.GattService: Received start request. Starting profile...
08-05 15:17:34.890  7106  7106 D BtGatt.GattService: start()
08-05 15:17:34.890  7106  7106 I bluedroid-qcom: get_profile_interface gatt
08-05 15:17:34.890  6961  6961 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 15:17:34.891  7106  7106 D BtGatt.AdvertiseManager: advertise manager created
08-05 15:17:34.891  7321  7321 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 15:17:34.891  7321  7321 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 15:17:34.891  7321  7321 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 15:17:34.891  7321  7321 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 15:17:34.891  7321  7321 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:34
,08-05 15:17:34.895  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:34.896  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:34.896  7106  7106 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-05 15:17:34.897  7106  7106 V BluetoothMapService: BluetoothMapBinder()
08-05 15:17:34.897  7106  7106 D BluetoothMapService: Received start request. Starting profile...
08-05 15:17:34.897  7106  7106 D BluetoothMapService: start()
08-05 15:17:34.899  7106  7106 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-05 15:17:34.899  7106  7106 D BluetoothMapEmailAppObserver: createReceiver()
08-05 15:17:34.901  7106  7106 D BluetoothMapEmailAppObserver: initObservers()
08-05 15:17:34.901  7106  7106 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-05 15:17:34.906  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
,08-05 15:17:34.907  7106  7106 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 15:17:34.909  7106  7106 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 15:17:34.911  7106  7106 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 15:17:34.911  7106  7106 V PanService: [BTUI] SIM Extra State :ABSENT
08-05 15:17:34.913  7106  7106 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 15:17:34.913  6379  6379 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 15:17:34.914  6379  7004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 15:17:34.916  7106  7106 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-05 15:17:34.916  7106  7106 V BluetoothMapService: Handler(): got msg=1
08-05 15:17:34.917  7106  7550 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-05 15:17:34.917  7106  7550 I bluedroid-qcom: enable
08-05 15:17:34.917  7106  7612 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-05 15:17:34.918  7106  7612 I bt-btu  : btu_task pending for preload complete event
08-05 15:17:34.918  7106  7550 I bt_hci_bdroid: init
08-05 15:17:34.919  7106  7550 I bt_vendor: bt-vendor : init
08-05 15:17:34.919  7106  7550 I bt_vendor: bt-vendor : get_bt_soc_type
08-05 15:17:34.919  7106  7550 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-05 15:17:34.919  7106  7550 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-05 15:17:34.919  7106  7550 D bt_userial_mct: userial_init
08-05 15:17:34.919  7106  7550 D bt_hci_bdroid: set_power 1
08-05 15:17:34.919  7106  7550 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-05 15:17:34.919  7106  7550 I bt_vendor: Starting hciattach daemon
08-05 15:17:34.919  7106  7550 I bt_vendor: try to set true
08-05 15:17:34.921  7106  7106 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:34.902  7615  7615 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:34.902  7615  7615 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:34.922  7106  7106 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 15:17:34.922  7106  7106 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 15:17:34.922  7106  7106 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 15:17:34.922  7106  7106 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:34.922  7106  7106 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-05 15:17:34.928  2232  2232 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 15:17:34.935  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 15:17:34.935  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:34.935  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 15:17:34.935  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 15:17:34.936  7156  7156 I AppUp4:CustModeStarterReceiver: onReceive
08-05 15:17:34.939  7156  7156 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2a9df96f
08-05 15:17:34.939  7156  7156 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 15:17:34.939  7156  7156 D AppUp4:CustFacade: isPhone : true
08-05 15:17:34.940  7616  7616 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-05 15:17:34.940  7156  7156 D AppUp4:CustModeStarterReceiver: begin check event
08-05 15:17:34.940  7156  7156 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 15:17:34.948  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:34.948  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 15:17:34.950  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 15:17:34.951  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 15:17:34.955  4785  7620 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 15:17:34.956  7204  7204 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-05 15:17:34.959  4785  7621 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:34.959  4785  7621 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 15:17:34.972  7204  7623 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 15:17:34.976  7628  7628 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
08-05 15:17:34.978  3356  3356 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 15:17:34.978  3356  3356 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:34.978  3356  3356 I LgeMiscReceiver: networkInfo.isConnected() = false
08-05 15:17:34.981  7240  7240 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 15:17:34.981  7240  7240 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 15:17:34.982  7630  7630 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-05 15:17:34.983  7077  7626 W FormManager: Network not available. Please check & try again.
08-05 15:17:34.984  7077  7627 V FormManager: Network unavailable.
,08-05 15:17:34.989  7321  7321 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:34
,08-05 15:17:34.990  7077  7627 V FormManager: Network unavailable.
08-05 15:17:34.991  7321  7321 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 15:17:34.991  7321  7321 D Weather.Utils: 2 : All the weather widget is gone.
08-05 15:17:34.991  7321  7321 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 15:17:34.991  7321  7321 D WeatherAncestor: connectivity changed - connection : true
08-05 15:17:34.991  7321  7321 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@cf22b05
08-05 15:17:34.992  7321  7321 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 15:17:34.992  7321  7321 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 15:17:34.992  7321  7321 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 15:17:34.992  7321  7321 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 15:17:34.992  7321  7321 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:34
08-05 15:17:34.998  7632  7632 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 15:17:35.005  7633  7633 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-05 15:17:35.011  7634  7634 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 15:17:35.017  7635  7635 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-05 15:17:35.029  7637  7637 I libmdmdetect: ESOC framework not supported
08-05 15:17:35.029  7637  7637 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-05 15:17:35.036  7637  7637 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-05 15:17:35.036  7637  7637 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-05 15:17:35.036  7637  7637 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-05 15:17:35.036  7637  7637 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-05 15:17:35.036  7637  7637 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-05 15:17:35.036  7637  7637 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-05 15:17:35.036  7637  7637 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-05 15:17:35.073  7637  7638 E QC-QMI  : qmi_client [7637] 14: failed to locate client data
08-05 15:17:35.073   493   493 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-05 15:17:35.074   493   493 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-05 15:17:35.143  7639  7639 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 ,
,08-05 15:17:35.168  7640  7640 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 15:17:35.221  7106  7550 I bt_vendor: bluetooth satus is on
,08-05 15:17:35.221  7106  7550 D bt_hci_bdroid: preload
08-05 15:17:35.221  7106  7614 D bt_userial_mct: userial_open(port:0)
,08-05 15:17:35.221  7106  7614 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-05 15:17:35.225  7106  7614 I bt_vendor: Done intiailizing UART
,08-05 15:17:35.229  7106  7614 I bt_vendor: Done intiailizing UART
08-05 15:17:35.229  7106  7614 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-05 15:17:35.229  7106  7614 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-05 15:17:35.229  7106  7612 I bt-btu  : btu_task received preload complete event
08-05 15:17:35.229  7106  7642 D bt_userial_mct: Entering userial_read_thread()
08-05 15:17:35.231  7106  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-05 15:17:35.231  7106  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-05 15:17:35.238  7106  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-05 15:17:35.250  7106  7612 I         : BTE_InitTraceLevels -- TRC_HCI
,08-05 15:17:35.251  7106  7612 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-05 15:17:35.251  7106  7612 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 15:17:35.251  7106  7612 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 15:17:35.251  7106  7612 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-05 15:17:35.251  7106  7612 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 15:17:35.251  7106  7612 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 15:17:35.251  7106  7612 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 15:17:35.251  7106  7612 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-05 15:17:35.251  7106  7612 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 15:17:35.251  7106  7612 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 15:17:35.251  7106  7612 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 15:17:35.251  7106  7612 I         : BTE_InitTraceLevels -- TRC_GATT
,08-05 15:17:35.251  7106  7612 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 15:17:35.251  7106  7612 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 15:17:35.251  7106  7612 I         : BTE_InitTraceLevels -- TRC_BTIF
08-05 15:17:35.341  7106  7612 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-05 15:17:35.342  7106  7612 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa020e061 
08-05 15:17:35.342  7106  7612 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa020e061 ,
,08-05 15:17:35.365  7106  7554 E bt-btif : Calling BTA_HhEnable
08-05 15:17:35.365  7106  7554 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-05 15:17:35.366  7106  7554 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 15:17:35.367  7106  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-05 15:17:35.367  7106  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-05 15:17:35.367  7106  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-05 15:17:35.367  7106  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-05 15:17:35.367  7106  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-05 15:17:35.370  7106  7554 D BluetoothAdapterProperties: Name is: G3
08-05 15:17:35.371  7106  7554 D BluetoothAdapterProperties: Scan Mode:20
08-05 15:17:35.371  7106  7554 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 15:17:35.371  7106  7554 D bt_hci_bdroid: postload
08-05 15:17:35.371  7106  7614 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 15:17:35.372  7106  7614 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 15:17:35.372  7106  7554 D bte_conf: Device ID record 1 : primary
08-05 15:17:35.372  7106  7554 D bte_conf:   vendorId            = 00c4
08-05 15:17:35.372  7106  7554 D bte_conf:   vendorIdSource      = 0001
08-05 15:17:35.372  7106  7554 D bte_conf:   product             = 13a1
08-05 15:17:35.373  7106  7554 D bte_conf:   version             = 1000
08-05 15:17:35.373  7106  7554 D bte_conf:   clientExecutableURL = 
08-05 15:17:35.373  7106  7554 D bte_conf:   serviceDescription  = 
08-05 15:17:35.373  7106  7554 D bte_conf:   documentationURL    = 
08-05 15:17:35.373  7106  7554 D bte_conf: bte_load_did_conf no section named DID2.
08-05 15:17:35.373  7106  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-05 15:17:35.375  7106  7614 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 15:17:35.362  7650  7650 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:35.362  7650  7650 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:35.383  7106  7614 D bt_hci_bdroid: Used up Tx Cmd credits
,08-05 15:17:35.388  7106  7642 E bt_mct  : hci lib postload completed
08-05 15:17:35.388  7106  7550 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-05 15:17:35.389  7106  7550 D BluetoothAdapterProperties: ScanMode =  20
08-05 15:17:35.389  7106  7550 D BluetoothAdapterProperties: State =  11
08-05 15:17:35.389  7106  7550 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-05 15:17:35.389  7106  7550 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-05 15:17:35.389  7106  7550 D BluetoothAdapterProperties: Setting state to 12
08-05 15:17:35.389  7106  7550 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 15:17:35.390  1035  1111 D BluetoothManagerService: Message: 60
08-05 15:17:35.390  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-05 15:17:35.390  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-05 15:17:35.390  7106  7554 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-05 15:17:35.390  7106  7554 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 15:17:35.390  7106  7550 I BluetoothAdapterState: Entering On State
08-05 15:17:35.391  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 15:17:35.397  7106  7612 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 15:17:35.398  7106  7612 W bt-smp  : Plain text(LSB ~ MSB) = 31 91 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 15:17:35.398  7106  7612 W bt-smp  : Encrypted text(LSB ~ MSB) = 8b 85 62 09 65 1f 1b 73 34 75 4e 43 b4 d3 55 91 
08-05 15:17:35.398  7106  7612 W bt-btm  : Stopping oneshot timer
,08-05 15:17:35.400  7106  7550 D LGBluetoothServiceAdapter: [BTUI] OnState
08-05 15:17:35.400  7106  7550 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-05 15:17:35.400  7106  7550 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-05 15:17:35.403  7106  7550 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-05 15:17:35.410  1852  1852 D BluetoothHeadset: Proxy object connected
08-05 15:17:35.411  6961  7032 D BluetoothMap: onBluetoothStateChange: up=true
08-05 15:17:35.412  7106  7554 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 15:17:35.412  7106  7554 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-05 15:17:35.425  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7562
08-05 15:17:35.426  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7563
08-05 15:17:35.426  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7571
08-05 15:17:35.427  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7589
08-05 15:17:35.427  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7646
08-05 15:17:35.429  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 15:17:35.429  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 15:17:35.436  6961  6961 D BluetoothMap: Proxy object connected
08-05 15:17:35.436  6961  6961 D MapProfile: Bluetooth service connected
08-05 15:17:35.436  6961  6961 D BluetoothMap: getConnectedDevices()
,08-05 15:17:35.437  7106  7123 V BluetoothMapService: getConnectedDevices()
08-05 15:17:35.438  1852  4454 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 15:17:35.439  7106  7612 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 15:17:35.439  7106  7612 W bt-smp  : Plain text(LSB ~ MSB) = 62 30 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 15:17:35.439  7106  7612 W bt-smp  : Encrypted text(LSB ~ MSB) = 5f 32 55 06 6e c5 c1 6e 79 ca 28 15 d1 28 6f fc 
08-05 15:17:35.439  7106  7612 W bt-btm  : Stopping oneshot timer
08-05 15:17:35.440  7106  7550 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-05 15:17:35.443  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:35.443  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:35.443  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:35.443  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 15:17:35.443  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:35.443  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 15:17:35.443  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 15:17:35.443  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 15:17:35.446  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 15:17:35.450  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:35.450  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:35.450  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:35.450  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 15:17:35.450  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:35.450  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 15:17:35.450  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 15:17:35.450  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 15:17:35.453  7106  7612 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 15:17:35.453  7106  7612 W bt-smp  : Plain text(LSB ~ MSB) = 2d 9b 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 15:17:35.453  7106  7612 W bt-smp  : Encrypted text(LSB ~ MSB) = b6 bc ad 95 76 58 0a df ad 74 07 05 e3 7d e5 89 
08-05 15:17:35.453  7106  7612 W bt-btm  : Stopping oneshot timer
08-05 15:17:35.455  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 15:17:35.456  1852  1852 D BluetoothHeadset: Proxy object connected
08-05 15:17:35.459  1852  2379 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 15:17:35.465  1852  1852 D BluetoothHeadset: Proxy object connected
,08-05 15:17:35.469  7106  7612 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 15:17:35.469  7106  7612 W bt-smp  : Plain text(LSB ~ MSB) = 6b c8 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 15:17:35.469  7106  7612 W bt-smp  : Encrypted text(LSB ~ MSB) = 1f bb 9c 9b 5a 03 7d 1a e3 e3 86 f5 52 88 1e c3 
08-05 15:17:35.469  7106  7612 W bt-btm  : Stopping oneshot timer
08-05 15:17:35.469  7655  7655 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-05 15:17:35.472  6961  6979 D BluetoothPan: onBluetoothStateChange on: true
08-05 15:17:35.472  6961  6979 D BluetoothPan: onBluetoothStateChange call bindService
08-05 15:17:35.477  6961  6982 D BluetoothPbap: onBluetoothStateChange: up=true
,08-05 15:17:35.480  6961  6961 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 15:17:35.480  6961  6961 D PanProfile: Bluetooth service connected
08-05 15:17:35.483  1035  1111 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 15:17:35.485  6961  6979 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 15:17:35.486  1035  1035 D BluetoothA2dp: Proxy object connected
08-05 15:17:35.486  7106  7612 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 15:17:35.486  7106  7612 W bt-smp  : Plain text(LSB ~ MSB) = 11 14 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 15:17:35.486  7106  7612 W bt-smp  : Encrypted text(LSB ~ MSB) = 83 1a 88 52 dc 0d 5a 78 0f a5 d5 05 58 e8 60 67 
08-05 15:17:35.487  7106  7612 W bt-btm  : Stopping oneshot timer
08-05 15:17:35.489  1035  1111 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 15:17:35.490  1035  1035 D BluetoothHeadset: Proxy object connected
,08-05 15:17:35.491  6961  6961 D BluetoothInputDevice: Proxy object connected
08-05 15:17:35.493  1035  1111 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-05 15:17:35.493  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-05 15:17:35.495  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:35.495  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-05 15:17:35.495  6961  6961 D HidProfile: Bluetooth service connected
08-05 15:17:35.496  1941  2139 D LGBluetoothAPIService: Message: 1
08-05 15:17:35.496  1941  2139 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-05 15:17:35.497  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 15:17:35.497  1035  1111 D BluetoothManagerService: Message: 40
08-05 15:17:35.497  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-05 15:17:35.511  6877  6877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 15:17:35.513  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 15:17:35.514  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:35.519  1941  2139 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-05 15:17:35.521  7106  7106 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:35.521  7106  7106 D BluetoothMapService: STATE_ON
08-05 15:17:35.522  6961  6961 D LocalBluetoothProfileManager: Adding local A2DP profile
08-05 15:17:35.524  7106  7106 D LGBluetoothAPIServer: [BTUI] onCreate()
08-05 15:17:35.524  7106  7106 D LGBluetoothAPIServer: [BTUI] onBind()
08-05 15:17:35.526  1035  1111 D BluetoothManagerService: Message: 30
,08-05 15:17:35.528  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-05 15:17:35.529  1941  2139 D LGBluetoothAPIService: Message: 100
08-05 15:17:35.529  1941  2139 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-05 15:17:35.531  6961  6961 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-05 15:17:35.533  1035  1111 D BluetoothManagerService: Message: 30
08-05 15:17:35.537  6961  6961 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-05 15:17:35.538  6961  6961 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 15:17:35.541  6961  6961 D BluetoothA2dp: Proxy object connected
08-05 15:17:35.541  6961  6961 D A2dpProfile: Bluetooth service connected
08-05 15:17:35.543  6961  6961 D BluetoothHeadset: Proxy object connected
08-05 15:17:35.543  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:35.543  7106  7106 V BluetoothPbapService: Pbap Service onCreate
08-05 15:17:35.543  7106  7106 V BluetoothPbapService: Starting PBAP service
08-05 15:17:35.544  6961  6961 D HeadsetProfile: Bluetooth service connected
08-05 15:17:35.544  7106  7106 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-05 15:17:35.544  7106  7106 V BluetoothPbapService: Pbap Service onBind
08-05 15:17:35.545  7106  7106 V BluetoothMapService: Handler(): got msg=1
08-05 15:17:35.548  7106  7106 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-05 15:17:35.548  7106  7106 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:35.548  7106  7106 V BluetoothPbapService: state: 12
,08-05 15:17:35.549  7106  7670 D BluetoothMapMasInstance: MAS initSocket()
08-05 15:17:35.549  7106  7670 D BluetoothMapMasInstance:   masId = 00
08-05 15:17:35.549  7106  7670 D BluetoothMapMasInstance:   msgTypes = 0e
08-05 15:17:35.549  7106  7670 D BluetoothMapMasInstance:   masName = SMS/MMS
08-05 15:17:35.549  7106  7670 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-05 15:17:35.549  7106  7106 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 15:17:35.550  7106  7106 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:35.550  7106  7106 V BluetoothPbapReceiver: ***********state = 12
08-05 15:17:35.551  1035  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:35.551  6961  6961 D DockEventReceiver: finishStartingService: stopping service
08-05 15:17:35.551  7106  7106 V BluetoothPbapService: Handler(): got msg=1
08-05 15:17:35.551  7106  7106 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-05 15:17:35.552  6961  6961 D BluetoothPbap: Proxy object connected
08-05 15:17:35.552  6961  6961 D PbapServerProfile: Bluetooth service connected
08-05 15:17:35.552  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 15:17:35.553  7106  7671 V BluetoothPbapService: Pbap Service initSocket
08-05 15:17:35.553  2232  2232 D c       : Getting all permits...
08-05 15:17:35.553  2232  2232 D a       : Opening database...
08-05 15:17:35.553  7106  7670 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 15:17:35.553  1035  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:35.555  7106  7671 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 15:17:35.555  7106  7670 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-05 15:17:35.555  7106  7670 V BluetoothMapMasInstance: Succeed to create listening socket 
08-05 15:17:35.555  7106  7670 D BluetoothMapMasInstance: Accepting socket connection...
08-05 15:17:35.555  7106  7671 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-05 15:17:35.555  7106  7671 V BluetoothPbapService: Succeed to create listening socket 
08-05 15:17:35.555  7106  7671 V BluetoothPbapService: Accepting socket connection...
08-05 15:17:35.556  2232  2232 D a       : Opening database auth.proximity.permit_store...
08-05 15:17:35.557  2232  2232 D a       : Closing database...
08-05 15:17:35.558  7106  7554 D BluetoothAdapterProperties: Scan Mode:21
08-05 15:17:35.558  7106  7554 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-05 15:17:35.562  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:35.563  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 15:17:35.570  6961  6961 D BluetoothPermissionRequest: onReceive
08-05 15:17:35.571  6961  6961 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 15:17:35.572  6961  6961 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 15:17:35.575  7106  7106 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-05 15:17:35.576  7106  7106 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-05 15:17:35.582  7106  7106 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-05 15:17:35.607  7106  7106 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 15:17:35.608  7106  7106 V BtOppService: onCreate
,08-05 15:17:35.613  7106  7106 V BluetoothOppNotification: send message
08-05 15:17:35.616  7106  7106 V BtOppService: Starting RfcommListener
08-05 15:17:35.623  7106  7106 D BluetoothOppPreference: Dumping Names:  
08-05 15:17:35.624  7106  7106 D BluetoothOppPreference: {}
,08-05 15:17:35.624  7106  7106 D BluetoothOppPreference: Dumping Channels:  
08-05 15:17:35.624  7106  7106 D BluetoothOppPreference: {}
,08-05 15:17:35.625  7106  7106 V BtOppService: onStartCommand
08-05 15:17:35.629  7106  7106 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:35.629  7106  7106 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 15:17:35.632  7106  7675 V BtOppService: Deleted complete outbound shares, number =  0
08-05 15:17:35.632  7106  7106 V BluetoothOppNotification: new notify threadi!
08-05 15:17:35.633  7106  7106 V BluetoothOppNotification: send delay message
08-05 15:17:35.634  7106  7106 V BtOppService: start RfcommListener
08-05 15:17:35.635  7106  7675 V BtOppService: Deleted complete inbound failed shares, number = 0
08-05 15:17:35.635  7106  7678 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-05 15:17:35.638  7106  7106 V BtOppService: RfcommListener started
08-05 15:17:35.638  7106  7675 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-05 15:17:35.639  7106  7679 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-05 15:17:35.640  7106  7106 V BtOppService: ContentObserver received notification
08-05 15:17:35.640  7106  7680 V BtOppRfcommListener: Starting RFCOMM listener....
08-05 15:17:35.640  7106  7675 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c9cdf36 on behalf of 
08-05 15:17:35.641  7106  7678 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 15:17:35.641  1035  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:35.644  7106  7680 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 15:17:35.644  7106  7679 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1491ae37 on behalf of 
08-05 15:17:35.645  7106  7680 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-05 15:17:35.646  7106  7680 V BtOppRfcommListener: Started RFCOMM listener....
08-05 15:17:35.646  7106  7680 I BtOppRfcommListener: Accept thread started.
08-05 15:17:35.646  7106  7680 V BtOppRfcommListener: Accepting connection...
08-05 15:17:35.646  7106  7679 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 15:17:35.648  7106  7679 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 15:17:35.649  7106  7679 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1aa61fa4 on behalf of 
08-05 15:17:35.650  7106  7679 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 15:17:35.650  7106  7678 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1337a10d on behalf of 
08-05 15:17:35.651  7106  7679 V BluetoothOppNotification: outbound notification was removed.
08-05 15:17:35.652  7106  7679 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-05 15:17:35.655  7106  7678 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 15:17:35.655  7106  7678 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 15:17:35.657  7106  7678 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ecfb8c2 on behalf of 
,08-05 15:17:35.659  7106  7679 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30c8f6d3 on behalf of 
08-05 15:17:35.660  7106  7679 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 15:17:35.660  7106  7678 V BluetoothOppNotification: update too frequent, put in queue
08-05 15:17:35.662  7106  7679 V BluetoothOppNotification: inbound notification was removed.
08-05 15:17:35.662  7106  7679 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 15:17:35.663  7106  7678 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 15:17:35.663  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:35.664  7106  7106 V BluetoothFtpService: Ftp Service onCreate
08-05 15:17:35.664  7106  7106 I BluetoothFtpService: Ftp Service onCreate
08-05 15:17:35.664  7106  7679 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@124a4109 on behalf of 
,08-05 15:17:35.664  7106  7106 V BluetoothFtpService: Ftp Service onStartCommand
08-05 15:17:35.664  7106  7106 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:35.665  7106  7106 V BluetoothFtpService: Starting Listening on sockets
08-05 15:17:35.665  7106  7106 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 15:17:35.665  7106  7106 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 15:17:35.665  7106  7106 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 15:17:35.666  7106  7106 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:35.666  7106  7106 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-05 15:17:35.666  7106  7106 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-05 15:17:35.671  7106  7106 V BtOppService: ContentObserver received notification
08-05 15:17:35.672  7106  7106 V BluetoothFtpService: Handler(): got msg=1
08-05 15:17:35.672  7106  7106 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-05 15:17:35.672  7106  7106 V BluetoothFtpService: Ftp Service initSocket
08-05 15:17:35.676  7106  7681 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 15:17:35.676  7106  7681 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-05 15:17:35.676  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:35.677  7106  7681 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f649f0e on behalf of 
08-05 15:17:35.678  7106  7681 V BluetoothOppNotification: update too frequent, put in queue
08-05 15:17:35.679  7106  7681 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 15:17:35.679  7106  7106 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 15:17:35.684  7106  7106 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-05 15:17:35.684  7106  7106 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-05 15:17:35.686  7106  7682 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-05 15:17:35.713  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:35.713  7106  7106 V BluetoothSapService: Sap Service onCreate
,08-05 15:17:35.716  7106  7106 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:35.716  7106  7106 V BluetoothSapService: state: 12
08-05 15:17:35.717  7106  7106 V BluetoothSapService: Starting SAP server process
08-05 15:17:35.721  7106  7106 V BluetoothSapService: SAP Service startRfcommListenerThread
08-05 15:17:35.702  7683  7683 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:35.702  7683  7683 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:35.726  7106  7684 V BluetoothSapService: Sap Service initRfcommSocket
08-05 15:17:35.727  1035  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 15:17:35.733  7106  7684 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 15:17:35.734  7683  7683 V BT_SAP  : Event pipe created
08-05 15:17:35.734  7683  7683 V BT_SAP  : create_server_socket qcom.sap.server
08-05 15:17:35.734  7683  7683 V BT_SAP  : created socket fd 6
08-05 15:17:35.736  7106  7684 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-05 15:17:35.736  7106  7684 V BluetoothSapService: Succeed to create listening socket 
08-05 15:17:35.736  7106  7684 V BluetoothSapService: Accepting socket connection...
08-05 15:17:35.897  7363  7401 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-05 15:17:36.514  1035  1538 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 15:17:36.514  1035  1538 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 15:17:36.544  1035  1539 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-05 15:17:36.544  1035  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-05 15:17:36.635  7106  7106 V BluetoothOppNotification: new notify threadi!
,08-05 15:17:36.635  7106  7106 V BluetoothOppNotification: send delay message
,08-05 15:17:36.648  7106  7696 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-05 15:17:36.654  7106  7696 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@354f9e1a on behalf of 
,08-05 15:17:36.661  7106  7696 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 15:17:36.664  7106  7696 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 15:17:36.666  7106  7696 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@172e6d4b on behalf of 
08-05 15:17:36.667  7106  7696 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 15:17:36.669  7106  7696 V BluetoothOppNotification: outbound notification was removed.
,08-05 15:17:36.671  7106  7696 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 15:17:36.673  7106  7696 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17139328 on behalf of 
08-05 15:17:36.673  7106  7696 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 15:17:36.675  7106  7696 V BluetoothOppNotification: inbound notification was removed.
08-05 15:17:36.675  7106  7696 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 15:17:36.676  7106  7696 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31c0841 on behalf of 
08-05 15:17:36.844  1035  2051 I ActivityManager: Killing 7496:com.lge.bnr/1000 (adj 15): empty #17
,08-05 15:17:36.877  1035  1940 W libprocessgroup: failed to open /acct/uid_1000/pid_7496/cgroup.procs: No such file or directory
,08-05 15:17:36.958  1035  1977 I ActivityManager: Killing 7005:com.lge.sync/1000 (adj 15): empty #17
,08-05 15:17:36.985  1035  1545 D WifiService: Client connection lost with reason: 4
,08-05 15:17:37.043  1035  1887 W libprocessgroup: failed to open /acct/uid_1000/pid_7005/cgroup.procs: No such file or directory
,08-05 15:17:37.436  1035  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 15:17:37.436  1035  2014 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@28fdfe31 mBinding = false
,08-05 15:17:37.466  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 15:17:37.466  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 15:17:37.466  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-05 15:17:37.470  1035  1111 D BluetoothManagerService: Message: 2
08-05 15:17:37.470  1035  1111 D BluetoothManagerService: Sending off request.
08-05 15:17:37.471  7106  7122 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-05 15:17:37.472  7106  7550 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-05 15:17:37.472  7106  7550 D BluetoothAdapterProperties: Setting state to 13
08-05 15:17:37.472  7106  7550 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 15:17:37.473  7106  7550 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 15:17:37.473  7106  7550 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-05 15:17:37.475  7106  7554 D BluetoothAdapterProperties: Scan Mode:20
08-05 15:17:37.476  7106  7550 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 15:17:37.478  7106  7670 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-05 15:17:37.478  7106  7670 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 15:17:37.478  7106  7670 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-05 15:17:37.478  7106  7670 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-05 15:17:37.478  7106  7670 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-05 15:17:37.478  7106  7670 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-05 15:17:37.478  7106  7670 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-05 15:17:37.478  7106  7670 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-05 15:17:37.480  7106  7671 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-05 15:17:37.483  7106  7680 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 15:17:37.484  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-05 15:17:37.484  7106  7612 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-05 15:17:37.485  7106  7684 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 15:17:37.485  7106  7682 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 15:17:37.487  7106  7550 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 15:17:37.491  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 15:17:37.491  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 15:17:37.491  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 15:17:37.491  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 15:17:37.491  7106  7612 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 15:17:37.495  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 15:17:37.495  7106  7612 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 15:17:37.495  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 15:17:37.495  7106  7612 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 15:17:37.495  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-05 15:17:37.495  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-05 15:17:37.495  7106  7612 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-05 15:17:37.505  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:37.505  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:37.505  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:37.505  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:37.505  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 15:17:37.505  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 15:17:37.505  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 15:17:37.505  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 15:17:37.505  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 15:17:37.507  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:37.507  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 15:17:37.513  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:37.513  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:37.513  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:37.513  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:37.513  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 15:17:37.513  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 15:17:37.513  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 15:17:37.513  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 15:17:37.513  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 15:17:37.517  6877  6877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 15:17:37.517  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 15:17:37.519  1035  1111 D BluetoothManagerService: Message: 60
08-05 15:17:37.519  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-05 15:17:37.519  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-05 15:17:37.521  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:37.522  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 15:17:37.527  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 15:17:37.531  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:37.533  7106  7106 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:37.533  7106  7106 D BluetoothMapService: STATE_TURNING_OFF
08-05 15:17:37.533  7106  7106 V BluetoothMapService: Handler(): got msg=4
08-05 15:17:37.533  7106  7106 D BluetoothMapService: MAP Service closeService in
08-05 15:17:37.534  7106  7106 D BluetoothMapMasInstance: MAP Service shutdown
08-05 15:17:37.534  7106  7106 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 15:17:37.534  7106  7106 V BluetoothMapService: MAP Service closeService out
08-05 15:17:37.535  7106  7106 V BtOppService: Receiver DISABLED_ACTION 
08-05 15:17:37.535  7106  7106 I BtOppRfcommListener: stopping Accept Thread
08-05 15:17:37.535  7106  7106 V BtOppRfcommListener: close mBtServerSocket
08-05 15:17:37.536  7106  7680 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-05 15:17:37.536  7106  7106 V BtOppRfcommListener: waiting for thread to terminate
08-05 15:17:37.536  7106  7106 V BtOppRfcommListener: done waiting for thread to terminate
08-05 15:17:37.540  6961  6961 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-05 15:17:37.552  6961  6961 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 15:17:37.556  7106  7106 V BtOppService: onDestroy
08-05 15:17:37.557  7106  7106 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-05 15:17:37.562  7106  7106 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 15:17:37.562  7106  7106 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:37.562  7106  7106 V BluetoothPbapReceiver: ***********state = 13
08-05 15:17:37.564  7106  7106 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-05 15:17:37.565  7106  7106 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:37.565  7106  7106 V BluetoothPbapService: state: 13
08-05 15:17:37.565  7106  7106 V BluetoothPbapService: Pbap Service closeService in
,08-05 15:17:37.571  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 15:17:37.572  7106  7106 V BluetoothPbapService: successfully stopped pbap service
08-05 15:17:37.572  7106  7106 V BluetoothPbapService: Pbap Service closeService out
08-05 15:17:37.573  7106  7106 V BluetoothPbapService: Pbap Service onDestroy
08-05 15:17:37.573  7106  7106 V BluetoothPbapService: Pbap Service closeService in
08-05 15:17:37.573  7106  7106 V BluetoothPbapService: Pbap Service closeService out
08-05 15:17:37.573  7106  7106 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-05 15:17:37.602  6961  6961 D DockEventReceiver: finishStartingService: stopping service
,08-05 15:17:37.605  6961  6961 D BluetoothPbap: Proxy object disconnected
08-05 15:17:37.605  6961  6961 D PbapServerProfile: Bluetooth service disconnected
08-05 15:17:37.610  6961  6961 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-05 15:17:37.616  6961  6961 D BluetoothPermissionRequest: onReceive
08-05 15:17:37.616  6961  6961 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-05 15:17:37.624  6961  6961 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 15:17:37.627  7106  7106 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-05 15:17:37.627  7106  7106 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-05 15:17:37.628  7106  7106 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-05 15:17:37.633  7106  7106 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:37.633  7106  7106 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 15:17:37.634  7106  7106 V BluetoothFtpService: Ftp Service onStartCommand
08-05 15:17:37.634  7106  7106 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:37.634  7106  7106 V BluetoothFtpService: Ftp Service closeService
08-05 15:17:37.635  7106  7106 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-05 15:17:37.636  7106  7106 V BluetoothFtpService: successfully stopped ftp service
08-05 15:17:37.637  7106  7106 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 15:17:37.637  7106  7106 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 15:17:37.637  7106  7106 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 15:17:37.637  7106  7106 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:37.637  7106  7106 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-05 15:17:37.637  7106  7106 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 15:17:37.639  7106  7106 V BluetoothFtpService: Ftp Service onDestroy
08-05 15:17:37.639  7106  7106 V BluetoothFtpService: Ftp Service closeService
,08-05 15:17:37.645  7106  7106 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-05 15:17:37.645  7106  7106 V BluetoothSapService: state: 13
08-05 15:17:37.645  7106  7106 V BluetoothSapService: Stopping SAP server process
08-05 15:17:37.648  7106  7106 V BluetoothSapService: Sap Service closeSapService in
08-05 15:17:37.648  7106  7106 V BluetoothSapService: Close listen Socket : 
08-05 15:17:37.648  7106  7106 V BluetoothSapService: Close rfcomm Socket : 
08-05 15:17:37.649  7106  7106 V BluetoothSapService: Close sapd  Socket : 
08-05 15:17:37.650  7106  7106 V BluetoothSapService: Sap Service closeSapService out
08-05 15:17:37.650  7106  7106 V BluetoothSapService: Sap Service onDestroy
08-05 15:17:37.650  7106  7106 V BluetoothSapService: Sap Service closeSapService in
08-05 15:17:37.651  7106  7106 V BluetoothSapService: Close listen Socket : 
08-05 15:17:37.651  7106  7106 V BluetoothSapService: Close rfcomm Socket : 
08-05 15:17:37.651  7106  7106 V BluetoothSapService: Close sapd  Socket : 
08-05 15:17:37.651  7106  7106 V BluetoothSapService: Sap Service closeSapService out
,08-05 15:17:38.395  7106  7554 D bt_hci_bdroid: cleanup
,08-05 15:17:38.402  7106  7614 I bt_lpm  : LPM is already off!!!
08-05 15:17:38.404  7106  7642 I bt_userial_mct: exiting userial_read_thread
08-05 15:17:38.404  7106  7642 D bt_userial_mct: Leaving userial_evt_read_thread()
08-05 15:17:38.405  7106  7612 W bt-btif : ag scb idx 1 not allocated
08-05 15:17:38.405  7106  7612 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 15:17:38.405  7106  7612 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 15:17:38.405  7106  7612 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 15:17:38.406  7106  7554 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-05 15:17:38.406  7106  7614 I bt_vendor: hw_epilog_process
08-05 15:17:38.406  7106  7554 D bt_hci_bdroid: cleanup Finalizing cleanup
08-05 15:17:38.407  7106  7554 D bt_userial_mct: userial_close
08-05 15:17:38.407  7106  7554 E bt_userial_mct: pthread_join() FAILED result:3
08-05 15:17:38.407  7106  7554 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-05 15:17:38.413  7106  7554 D bt_hci_bdroid: set_power 0
08-05 15:17:38.413  7106  7554 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-05 15:17:38.413  7106  7554 I bt_vendor: bluetooth satus is on
08-05 15:17:38.413  7106  7554 I bt_vendor: bt-vendor : resetting BT status
08-05 15:17:38.413  7106  7554 I bt_vendor: Starting hciattach daemon
08-05 15:17:38.413  7106  7554 I bt_vendor: try to set false
,08-05 15:17:38.420  7106  7554 I bt_vendor: Starting hciattach daemon
08-05 15:17:38.420  7106  7554 I bt_vendor: try to set false
08-05 15:17:38.421  7106  7554 I bt_vendor: cleanup
08-05 15:17:38.422  7106  7612 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-05 15:17:38.422  7106  7554 I GKI_LINUX: GKI_exit_task 0 done
08-05 15:17:38.422  7106  7554 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-05 15:17:38.424  7106  7550 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 15:17:38.431  7106  7550 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-05 15:17:38.434  7106  7106 D HeadsetService: Received stop request...Stopping profile...
08-05 15:17:38.436  7106  7106 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 15:17:38.436  7106  7106 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 15:17:38.436  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:38.437  7106  7572 D HeadsetStateMachine: Exit Disconnected: -1
08-05 15:17:38.439  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-05 15:17:38.439  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-05 15:17:38.440  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-05 15:17:38.441  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-05 15:17:38.441  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-05 15:17:38.441  7106  7106 D A2dpService: Received stop request...Stopping profile...
08-05 15:17:38.441  7106  7604 D A2dpStateMachine: Exit Disconnected: -1
08-05 15:17:38.443  7106  7106 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-05 15:17:38.449  7106  7106 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-05 15:17:38.449  7106  7106 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 15:17:38.449  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:38.451  7106  7106 D HidService: Received stop request...Stopping profile...
08-05 15:17:38.451  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:38.451  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-05 15:17:38.451  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-05 15:17:38.453  7106  7106 D HealthService: Received stop request...Stopping profile...
08-05 15:17:38.453  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:38.456  7106  7106 D PanService: Received stop request...Stopping profile...
,08-05 15:17:38.460  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:38.461  7106  7106 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 15:17:38.461  7106  7106 D BtGatt.GattService: Received stop request...Stopping profile...
08-05 15:17:38.462  7106  7106 D BtGatt.GattService: stop()
08-05 15:17:38.462  7106  7106 D BtGatt.AdvertiseManager: advertise clients cleared
08-05 15:17:38.463  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:38.464  7106  7106 D BluetoothMapService: Received stop request...Stopping profile...
08-05 15:17:38.465  7106  7106 D BluetoothMapService: stop()
08-05 15:17:38.465  7106  7106 D BluetoothMapEmailAppObserver: deinitObservers()
08-05 15:17:38.465  7106  7106 D BluetoothMapEmailAppObserver: removeReceiver()
08-05 15:17:38.466  7106  7106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf22b05
08-05 15:17:38.467  7106  7106 D HeadsetStateMachine: Unbinding service...
08-05 15:17:38.470  7106  7106 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 15:17:38.470  7106  7106 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 15:17:38.470  7106  7106 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 15:17:38.470  7106  7106 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 15:17:38.470  7106  7106 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 15:17:38.470  7106  7106 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 15:17:38.470  7106  7106 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 15:17:38.470  7106  7106 I BluetoothA2dpServiceJni: cleanupNative
,08-05 15:17:38.473  7106  7605 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 15:17:38.474  7106  7106 I GKI_LINUX: GKI_exit_task 2 done
08-05 15:17:38.474  7106  7106 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-05 15:17:38.474  7106  7106 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 15:17:38.474  7106  7106 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 15:17:38.474  7106  7106 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 15:17:38.475  7106  7106 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 15:17:38.475  7106  7106 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 15:17:38.475  7106  7106 V BluetoothMapService: Handler(): got msg=4
08-05 15:17:38.475  7106  7106 D BluetoothMapService: MAP Service closeService in
08-05 15:17:38.475  7106  7106 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 15:17:38.475  7106  7106 V BluetoothMapService: MAP Service closeService out
08-05 15:17:38.476  7106  7550 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-05 15:17:38.476  7106  7550 D BluetoothAdapterProperties: Setting state to 10
08-05 15:17:38.476  7106  7550 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-05 15:17:38.478  1035  1111 D BluetoothManagerService: Message: 60
08-05 15:17:38.478  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-05 15:17:38.478  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-05 15:17:38.479  7106  7106 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 15:17:38.479  7106  7106 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 15:17:38.482  7106  7550 I BluetoothAdapterState: Entering OffState
08-05 15:17:38.483  7106  7106 D BluetoothMapService: cleanup()
08-05 15:17:38.483  7106  7106 D BluetoothMapService: MAP Service closeService in
08-05 15:17:38.483  7106  7106 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 15:17:38.483  7106  7106 V BluetoothMapService: MAP Service closeService out
,08-05 15:17:38.486  6961  7032 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 15:17:38.487  1852  4468 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 15:17:38.488  6961  7032 D BluetoothMap: onBluetoothStateChange: up=false
08-05 15:17:38.488  1852  2379 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 15:17:38.489  1852  4455 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 15:17:38.490  6961  7032 D BluetoothPan: onBluetoothStateChange on: false
08-05 15:17:38.490  6961  7032 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 15:17:38.491  1035  1111 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 15:17:38.495  6961  7032 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-05 15:17:38.497  6961  6979 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-05 15:17:38.498  1035  1111 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 15:17:38.499  1035  1111 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-05 15:17:38.499  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-05 15:17:38.501  1035  1111 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-05 15:17:38.501  1035  1111 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-05 15:17:38.501  1035  1111 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@28fdfe31 mBinding = false
08-05 15:17:38.501  1035  1111 D BluetoothManagerService: Sending unbind request.
08-05 15:17:38.507  7106  7554 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-05 15:17:38.510  7106  7106 I GKI_LINUX: GKI_exit_task 1 done
08-05 15:17:38.510  7106  7106 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-05 15:17:38.510  7106  7106 I BluetoothServiceJni: cleanupNative: return from cleanup
08-05 15:17:38.510  7106  7106 I art     : --- WEIRD: removing null entry 248
08-05 15:17:38.510  7106  7106 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-05 15:17:38.510  7106  7106 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-05 15:17:38.512  7106  7106 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-05 15:17:38.513  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-05 15:17:38.515  7106  7106 I art     : System.exit called, status: 0
08-05 15:17:38.515  7106  7106 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-05 15:17:38.534   323  1383 V AudioFlinger: 7106 died, releasing its sessions
08-05 15:17:38.534   323  1383 V AudioFlinger:  pid 1852 @ 0
08-05 15:17:38.534   323  1383 V AudioFlinger:  pid 3356 @ 1
08-05 15:17:38.534   323  1383 V AudioFlinger:  pid 3356 @ 2
,08-05 15:17:38.538  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-05 15:17:38.538  1941  2139 D LGBluetoothAPIService: Message: 101
08-05 15:17:38.538  1941  2139 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-05 15:17:38.539  1941  2139 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-05 15:17:38.539  1941  2139 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-05 15:17:38.540  6961  6961 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-05 15:17:38.582  1035  1576 I ActivityManager: Process com.android.bluetooth (pid 7106) has died
,08-05 15:17:38.583  1035  1576 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-05 15:17:38.583  1035  1576 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,08-05 15:17:38.604  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 15:17:38.601  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:38.607  1941  2139 D LGBluetoothAPIService: Message: 2
08-05 15:17:38.607  1941  2139 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-05 15:17:38.607  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:38.608  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:38.613  6961  6961 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-05 15:17:38.614  6961  6961 D LGBluetoothEventManager: [BTUI] clear device connection state
08-05 15:17:38.615  1604  1604 D BluetoothAdapter: 697982356: getState() :  mService = null. Returning STATE_OFF
08-05 15:17:38.615  1604  1604 D BluetoothAdapter: 697982356: getState() :  mService = null. Returning STATE_OFF
08-05 15:17:38.616  6961  6961 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 15:17:38.663  1035  1887 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7738 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-05 15:17:38.665  6961  6961 D DockEventReceiver: finishStartingService: stopping service
,08-05 15:17:38.724  7738  7738 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-05 15:17:38.725  7738  7738 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 15:17:38.725  7738  7738 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-05 15:17:38.726  7738  7738 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 15:17:38.747  7738  7738 D BluetoothAdapterApp: Loading JNI Library
,08-05 15:17:38.785  7738  7738 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@31eb5f4d Instance Count = 1
,08-05 15:17:38.791  7738  7738 D BluetoothAdapterApp: onCreate
08-05 15:17:38.817  7738  7738 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-05 15:17:38.818  7738  7738 D ProfileConfigQcom: Adding HeadsetService
08-05 15:17:38.818  7738  7738 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-05 15:17:38.818  7738  7738 D ProfileConfigQcom: Adding A2dpService
,08-05 15:17:38.818  7738  7738 D ProfileConfigQcom: [BTUI] HidService is supported
,08-05 15:17:38.818  7738  7738 D ProfileConfigQcom: Adding HidService
08-05 15:17:38.819  7738  7738 D ProfileConfigQcom: [BTUI] HealthService is supported
08-05 15:17:38.819  7738  7738 D ProfileConfigQcom: Adding HealthService
08-05 15:17:38.819  7738  7738 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-05 15:17:38.821  7738  7738 D ProfileConfigQcom: [BTUI] PanService is supported
08-05 15:17:38.821  7738  7738 D ProfileConfigQcom: Adding PanService
08-05 15:17:38.821  7738  7738 D ProfileConfigQcom: [BTUI] GattService is supported
08-05 15:17:38.821  7738  7738 D ProfileConfigQcom: Adding GattService
08-05 15:17:38.821  7738  7738 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-05 15:17:38.822  7738  7738 D ProfileConfigQcom: Adding BluetoothMapService
08-05 15:17:38.823  7738  7738 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-05 15:17:38.824  7738  7738 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 15:17:38.825  7738  7738 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:38.826  7738  7738 V BluetoothPbapReceiver: ***********state = 10
08-05 15:17:38.828  7738  7738 V LGMDMManagerInternal: Create singleton instance
08-05 15:17:38.934  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 15:17:38.935  7738  7738 D LGBluetoothAPIServer: [BTUI] onCreate()
08-05 15:17:38.935  7738  7738 D LGBluetoothAPIServer: [BTUI] onBind()
,08-05 15:17:38.941  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-05 15:17:38.941  1941  2139 D LGBluetoothAPIService: Message: 100
08-05 15:17:38.941  1941  2139 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-05 15:17:38.946  6961  6961 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-05 15:17:38.950  6961  6961 D BluetoothPermissionRequest: onReceive
08-05 15:17:38.952  6961  6961 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 15:17:38.952  6961  6961 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-05 15:17:38.957  6961  6961 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 15:17:38.962  7738  7738 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-05 15:17:38.967  7738  7738 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-05 15:17:38.971  7738  7738 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-05 15:17:38.971  7738  7738 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-05 15:17:38.971  7738  7738 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 15:17:38.973  7738  7738 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:38.973  7738  7738 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-05 15:17:38.976  7053  7053 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-05 15:17:40.550  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:40.551  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 15:17:40.619  1035  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 15:17:40.629  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
08-05 15:17:40.709  1035  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7762 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-05 15:17:40.715  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-05 15:17:40.716  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-05 15:17:40.720  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-05 15:17:40.743  1035  1035 D administrator: Handling package changes for user 0
,08-05 15:17:40.765  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 15:17:40.775  7762  7762 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 15:17:40.840  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-05 15:17:40.840  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-05 15:17:40.854  7762  7762 D LgDataFeature: LgDataFeature() Constructor: none
08-05 15:17:40.855  7762  7762 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 15:17:40.888  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 15:17:40.902  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-05 15:17:40.933  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-05 15:17:40.935  2502  2502 V GmsNetworkLocationProvi: DISABLE
,08-05 15:17:40.977  7762  7807 I Babel   : MmsConfig: mnc/mcc: 0/0
08-05 15:17:40.977  7762  7807 I Babel   : MmsConfig.loadMmsSettings
08-05 15:17:40.983  1035  1091 D LocationProviderProxy: applying state to connected service
08-05 15:17:40.984  2502  2502 E GCoreFlp: Bound FusedProviderService with LocationManager
08-05 15:17:40.992  7762  7807 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 15:17:40.992  7762  7807 I Babel   : MmsConfig.loadFromDatabase
,08-05 15:17:41.006  7762  7807 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-05 15:17:41.006  7762  7807 I Babel   : MmsConfig.loadFromResources
08-05 15:17:41.009  7762  7807 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-05 15:17:41.010  7762  7807 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 15:17:41.016  7762  7762 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 15:17:41.027  7762  7805 W AudioCapabilities: Unsupported mime audio/evrc
08-05 15:17:41.028  7762  7805 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 15:17:41.031  7762  7805 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 15:17:41.038  1816  7810 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-05 15:17:41.038  1816  7810 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-05 15:17:41.043  7156  7156 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 15:17:41.048  7156  7156 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2a9df96f
08-05 15:17:41.048  7156  7156 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 15:17:41.048  7156  7156 D AppUp4:CustFacade: isPhone : true
08-05 15:17:41.048  7156  7156 D AppUp4:CustModeStarterReceiver: begin check event
08-05 15:17:41.048  7156  7156 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-05 15:17:41.054  1816  5210 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-05 15:17:41.054  7762  7805 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-05 15:17:41.057  7762  7805 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 15:17:41.059  7762  7805 W AudioCapabilities: Unsupported mime audio/evrc
08-05 15:17:41.081  7762  7805 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-05 15:17:41.083  7762  7805 W VideoCapabilities: Unsupported mime video/divx
08-05 15:17:41.085  7762  7805 W VideoCapabilities: Unsupported mime video/divx311
08-05 15:17:41.086  7762  7805 W VideoCapabilities: Unsupported mime video/divx4
08-05 15:17:41.094  7762  7805 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-05 15:17:41.095  1035  1051 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7813 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-05 15:17:41.101  1035  1644 I ActivityManager: Killing 6749:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-05 15:17:41.115  7036  7036 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-05 15:17:41.115  7762  7805 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-05 15:17:41.115  7036  7036 W System.err: android.os.DeadObjectException
08-05 15:17:41.115  7036  7036 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 15:17:41.115  7036  7036 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 15:17:41.115  7036  7036 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,08-05 15:17:41.115  7036  7036 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-05 15:17:41.115  7036  7036 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 15:17:41.115  7036  7036 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 15:17:41.115  7036  7036 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 15:17:41.116  7036  7036 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 15:17:41.116  7036  7036 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 15:17:41.116  7036  7036 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 15:17:41.116  7036  7036 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 15:17:41.116  7036  7036 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 15:17:41.116  7036  7036 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 15:17:41.116  7036  7036 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 15:17:41.116  7036  7036 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-05 15:17:41.116  7036  7036 W System.err: android.os.DeadObjectException
08-05 15:17:41.116  7036  7036 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 15:17:41.116  7036  7036 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 15:17:41.116  7036  7036 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-05 15:17:41.116  7036  7036 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-05 15:17:41.116  7036  7036 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 15:17:41.117  7036  7036 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 15:17:41.117  7036  7036 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 15:17:41.118  7036  7036 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 15:17:41.118  7036  7036 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 15:17:41.118  7036  7036 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 15:17:41.118  7036  7036 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 15:17:41.118  7036  7036 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 15:17:41.118  7036  7036 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 15:17:41.118  7036  7036 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 15:17:41.118  7036  7036 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-05 15:17:41.118  7036  7036 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-05 15:17:41.119  7762  7805 W AudioCapabilities: Unsupported mime audio/eac3
08-05 15:17:41.120  7762  7805 W AudioCapabilities: Unsupported mime audio/ac3
08-05 15:17:41.121  7762  7805 W AudioCapabilities: Unsupported mime audio/g726
08-05 15:17:41.122  7762  7805 W AudioCapabilities: Unsupported mime audio/wma-voice
08-05 15:17:41.124  7762  7805 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-05 15:17:41.125  7762  7805 W AudioCapabilities: Unsupported mime audio/adpcm
08-05 15:17:41.127  7762  7805 W VideoCapabilities: Unsupported mime video/theora
08-05 15:17:41.129  7762  7805 W VideoCapabilities: Unsupported mime video/mjpg
,08-05 15:17:41.345  1035  1887 W libprocessgroup: failed to open /acct/uid_1000/pid_6749/cgroup.procs: No such file or directory
,08-05 15:17:41.345  1035  1887 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-05 15:17:41.348  7036  7036 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-05 15:17:41.348  7036  7036 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 15:17:41.361  1035  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1429cd5b type 2 when 354517 com.google.android.gms} when 354517
,08-05 15:17:41.380  7813  7813 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 15:17:41.380  7813  7813 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 15:17:41.380  7813  7813 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-05 15:17:41.381  7813  7813 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-05 15:17:41.381  7813  7813 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-05 15:17:41.431  1035  1051 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7831 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 15:17:41.431  7036  7036 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-05 15:17:41.456  7813  7813 I SystemConfig: BUILD Country: EU
08-05 15:17:41.457  7813  7813 I SystemConfig: BUILD Operator: OPEN
,08-05 15:17:41.484  7831  7831 D UEI.SmartControl: Quickset Services start...
08-05 15:17:41.485  7831  7831 I UEI.SmartControl: Manufacture = LGE
,08-05 15:17:41.486  7831  7831 D UEI.SmartControl: Id = LGNevo
,08-05 15:17:41.487  7831  7831 D UEI.SmartControl: File observer start...
08-05 15:17:41.488  7831  7831 E UEI.SmartControl: IR Port is disabled: false
08-05 15:17:41.488  7831  7831 D UEI.SmartControl: Starting file observer...
08-05 15:17:41.488  7831  7831 D UEI.SmartControl: Extracting JNI libs...
08-05 15:17:41.488  7831  7831 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-05 15:17:41.517  1035  1886 I ActivityManager: Killing 7036:com.lge.qremote/u0a112 (adj 15): empty #17
,08-05 15:17:41.543  1035  1546 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-05 15:17:41.544  7831  7831 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-05 15:17:41.544  7831  7831 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-05 15:17:41.544  7831  7831 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-05 15:17:41.565  7831  7831 I UEI.SmartControl: --- Selecting new region: 6
,08-05 15:17:41.566  7831  7831 I UEI.SmartControl: Model = LG-D855
08-05 15:17:41.567  7831  7831 D UEI.SmartControl: QS Service created
08-05 15:17:41.576  1035  1050 W libprocessgroup: failed to open /acct/uid_10112/pid_7036/cgroup.procs: No such file or directory
08-05 15:17:41.586  7831  7831 I UEI.SmartControl: Service initServices...
,08-05 15:17:41.590  7831  7831 D UEI.SmartControl: QS start get config
08-05 15:17:41.625  1035  1886 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7852 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-05 15:17:41.631  7831  7831 D UEI.SmartControl: Loading JNI Libs...
08-05 15:17:41.632  7813  7850 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-05 15:17:41.632  7813  7850 I SystemConfig: existFile = false
08-05 15:17:41.632  7813  7850 I SystemConfig: canReadFile = false
08-05 15:17:41.632  7813  7850 I SystemConfig: systemFeature RCS result false
08-05 15:17:41.633  7813  7850 D SystemConfig: refreshRcsSupport() :false
,08-05 15:17:41.701  7852  7852 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 15:17:41.701  7852  7852 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 15:17:41.702  7852  7852 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-05 15:17:41.702  7852  7852 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-05 15:17:41.780  7852  7852 I AppConfig: Total System Memory = 2995761152
,08-05 15:17:41.787  7852  7852 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-05 15:17:41.854  1035  2051 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7871 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 15:17:41.859  1035  2051 I ActivityManager: Killing 7204:com.lge.email/u0a23 (adj 15): empty #17
,08-05 15:17:41.864  7831  7831 I UEI.SmartControl: Supports setup maps: true
08-05 15:17:41.867  7831  7831 D UEI.SmartControl: QS start statue = true Error code = 0
08-05 15:17:41.867  7831  7831 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 15:17:41.867  7831  7831 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 15:17:41.868  7831  7831 I UEI.SmartControl: ### init IR Blaster...
08-05 15:17:41.873  7831  7831 D serial_port: Configuring serial port
,08-05 15:17:41.885  7831  7831 E UEI.SmartControl: UEIBLaster setting for 616
08-05 15:17:41.885  7831  7831 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 15:17:41.885  7831  7831 I UEI.SmartControl: configuring settings for MAXQ616
08-05 15:17:41.885  7831  7831 I UEI.SmartControl: Get version...
08-05 15:17:41.901  7831  7884 D UEI.SmartControl: serial port data available: 21
,08-05 15:17:41.931  7831  7831 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-05 15:17:41.931  7831  7831 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-05 15:17:41.931  7831  7831 I UEI.SmartControl: QS saving settings...
08-05 15:17:41.934  7831  7831 D UEI.SmartControl: IR Blaster version: 25672567
08-05 15:17:41.950  7831  7884 D UEI.SmartControl: serial port data available: 4
,08-05 15:17:41.953  1035  1977 W libprocessgroup: failed to open /acct/uid_10023/pid_7204/cgroup.procs: No such file or directory
08-05 15:17:41.984  7831  7831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-05 15:17:41.988  7831  7891 I UEI.SmartControl: Device manager: loading config....
08-05 15:17:41.988  7831  7831 E UEI.SmartControl: Services init done
08-05 15:17:41.989  7831  7831 D UEI.SmartControl: QS Service init finished
08-05 15:17:41.989  7831  7891 D UEI.SmartControl: ----------- loading internal config...
08-05 15:17:41.990  7831  7831 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 15:17:41.990  7831  7831 D UEI.SmartControl: QS Service version code: 201091
08-05 15:17:41.991  7831  7831 D UEI.SmartControl: Service requested: Control
08-05 15:17:42.001  7831  7891 E UEI.SmartControl: Loading SETTINGS...
,08-05 15:17:42.003  7831  7831 D UEI.SmartControl: Request IControl service: devices are loaded...
08-05 15:17:42.005  7831  7831 D UEI.SmartControl: Service.onUnbind: IControl
08-05 15:17:42.005  7831  7831 D UEI.SmartControl: Service.onDestroy
08-05 15:17:42.005  7831  7831 D UEI.SmartControl: Lock is in USE false
08-05 15:17:42.006  7831  7831 D UEI.SmartControl: unbind internal service
08-05 15:17:42.006  7831  7831 D serial_port: close(fd = 25)
08-05 15:17:42.011  7831  7831 I UEI.SmartControl: Serial port is closed.
08-05 15:17:42.011  7831  7831 I UEI.SmartControl: Serial port is closed.
08-05 15:17:42.012  7831  7831 D UEI.SmartControl: Blaster closed
08-05 15:17:42.012  7831  7831 D UEI.SmartControl: Shut down QS...
08-05 15:17:42.012  7831  7831 D UEI.SmartControl: Stopping QS lib
08-05 15:17:42.012  7831  7831 D UEI.SmartControl: QS lib stop result = true
08-05 15:17:42.013  7831  7831 D UEI.SmartControl: Stopped QS lib
08-05 15:17:42.013  7831  7831 D UEI.SmartControl: Stopped file observer...
08-05 15:17:42.013  7831  7831 D UEI.SmartControl: QS shutdown complete
08-05 15:17:42.014  7831  7831 D UEI.SmartControl: QS Service created
08-05 15:17:42.015  7831  7891 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-05 15:17:42.021  7831  7890 I UEI.SmartControl: Notify AllClients services are ready: 11
08-05 15:17:42.021  7831  7890 D UEI.SmartControl: -----service ready thread exits
08-05 15:17:42.029  7831  7831 I UEI.SmartControl: Service initServices...
08-05 15:17:42.029  7831  7831 D UEI.SmartControl: QS start get config
,08-05 15:17:42.153  7871  7871 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-05 15:17:42.238  7871  7871 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 15:17:42.238  7871  7871 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 15:17:42.283  7871  7871 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-05 15:17:42.304  7871  7871 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-05 15:17:42.304  7871  7871 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-05 15:17:42.315  7831  7831 I UEI.SmartControl: Supports setup maps: true
08-05 15:17:42.318  7831  7831 D UEI.SmartControl: QS start statue = true Error code = 0
08-05 15:17:42.318  7831  7831 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 15:17:42.318  7831  7831 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 15:17:42.318  7831  7831 I UEI.SmartControl: ### init IR Blaster...
08-05 15:17:42.318  7871  7871 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-05 15:17:42.318  7871  7871 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-05 15:17:42.321  7831  7831 D serial_port: Configuring serial port
08-05 15:17:42.321  7831  7831 E UEI.SmartControl: UEIBLaster setting for 616
08-05 15:17:42.321  7831  7831 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 15:17:42.321  7831  7831 I UEI.SmartControl: configuring settings for MAXQ616
08-05 15:17:42.321  7831  7831 I UEI.SmartControl: Get version...
08-05 15:17:42.334  1035  1051 I ActivityManager: Killing 7077:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-05 15:17:42.340  7831  7916 D UEI.SmartControl: serial port data available: 21
08-05 15:17:42.366  7831  7831 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-05 15:17:42.366  7831  7831 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 15:17:42.366  1035  1644 W libprocessgroup: failed to open /acct/uid_10026/pid_7077/cgroup.procs: No such file or directory
08-05 15:17:42.366  7831  7831 I UEI.SmartControl: QS saving settings...
08-05 15:17:42.366  7831  7831 D UEI.SmartControl: IR Blaster version: 25672567
,08-05 15:17:42.373  5050  7919 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-05 15:17:42.386  7831  7916 D UEI.SmartControl: serial port data available: 4
,08-05 15:17:42.414  7831  7921 I UEI.SmartControl: Device manager: loading config....
,08-05 15:17:42.416  7831  7831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-05 15:17:42.417  7831  7921 D UEI.SmartControl: ----------- loading internal config...
08-05 15:17:42.421  7831  7921 E UEI.SmartControl: Loading SETTINGS...
08-05 15:17:42.426  7831  7921 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 15:17:42.427  1035  2051 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7923 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-05 15:17:42.434  7831  7831 E UEI.SmartControl: Services init done
08-05 15:17:42.434  7831  7831 D UEI.SmartControl: QS Service init finished
,08-05 15:17:42.434  7831  7920 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 15:17:42.434  7831  7920 D UEI.SmartControl: -----service ready thread exits
08-05 15:17:42.435  7831  7831 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 15:17:42.435  7831  7831 D UEI.SmartControl: QS Service version code: 201091
08-05 15:17:42.435  7831  7831 D UEI.SmartControl: Service requested: Control
08-05 15:17:42.438  1035  1886 I ActivityManager: Killing 6379:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-05 15:17:42.444  3473  3488 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-05 15:17:42.446  3473  3488 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2a0630e0 on behalf of 7871
,08-05 15:17:42.524  7831  7831 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@143abd8b that was originally bound here
08-05 15:17:42.524  7831  7831 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@143abd8b that was originally bound here
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 15:17:42.524  7831  7831 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 15:17:42.530  1035  1887 W libprocessgroup: failed to open /acct/uid_1000/pid_6379/cgroup.procs: No such file or directory
08-05 15:17:42.538  7831  7831 D UEI.SmartControl: Internal service binding...
,08-05 15:17:42.548  7871  7871 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-05 15:17:42.573  7871  7871 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-05 15:17:42.578  7923  7923 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-05 15:17:42.601  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-05 15:17:42.601  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-05 15:17:42.601  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-05 15:17:42.601  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-05 15:17:42.601  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-05 15:17:42.601  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-05 15:17:42.759  1035  2048 I art     : Explicit concurrent mark sweep GC freed 40353(1903KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 3.012ms total 144.224ms
,08-05 15:17:42.766   318  7950 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 15:17:42.767  1035  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-05 15:17:42.794  1035  1886 I ActivityManager: Killing 7240:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-05 15:17:42.824  1035  1644 W libprocessgroup: failed to open /acct/uid_10046/pid_7240/cgroup.procs: No such file or directory
,08-05 15:17:43.007  7831  7893 D UEI.SmartControl: Internal timer expired: 2
,08-05 15:17:43.045  1035  2013 V SIM_STK : Menu title from STK is T-Mobile
,08-05 15:17:43.059  5050  7919 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 685 ms] updated apps [took 685 ms] 
,08-05 15:17:43.565  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 15:17:43.565  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60cc459 added. We now have 6 listener(s)
08-05 15:17:43.565  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-05 15:17:43.578  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:43.578  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d18e81e added. We now have 7 listener(s)
08-05 15:17:43.578  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 15:17:43.578  6877  6943 I System.out: IsBluetoothEnabled
08-05 15:17:43.580  1035  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:43.580  1035  1886 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-05 15:17:43.581  1035  1111 D BluetoothManagerService: Message: 2
08-05 15:17:43.584  6877  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:43.584  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:43.585  1035  1050 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-05 15:17:43.602  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 15:17:43.602  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 15:17:43.602  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-05 15:17:43.603  1035  1111 D BluetoothManagerService: Message: 1
08-05 15:17:43.603  1035  1111 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-05 15:17:43.627  1035  1111 D BluetoothManagerService: Message: 20
08-05 15:17:43.628  1035  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38653670:true
,08-05 15:17:43.632  7738  7738 D BluetoothAdapterState: make
08-05 15:17:43.637  7738  7738 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-05 15:17:43.637  7738  7738 I bluedroid-qcom: init
08-05 15:17:43.638  7738  7969 I BluetoothAdapterState: Entering OffState
08-05 15:17:43.639  7738  7738 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 15:17:43.639  7738  7738 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 15:17:43.639  7738  7738 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 15:17:43.639  7738  7738 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 15:17:43.639  7738  7738 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-05 15:17:43.641  7738  7738 I bluedroid-qcom: get_profile_interface socket
08-05 15:17:43.641  7738  7738 I bluedroid-qcom: get_profile_interface map_client
,08-05 15:17:43.646  7738  7973 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-05 15:17:43.648  7738  7973 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-05 15:17:43.632  7972  7972 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:43.632  7972  7972 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:43.657  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 15:17:43.658  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,08-05 15:17:43.665  7972  7972 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-05 15:17:43.665  7972  7972 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-05 15:17:43.665  7972  7972 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-05 15:17:43.666  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-05 15:17:43.667  1035  1111 D BluetoothManagerService: Message: 40
08-05 15:17:43.667  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-05 15:17:43.668  7738  7753 I bluedroid-qcom: config_hci_snoop_log
08-05 15:17:43.669  1035  1111 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-05 15:17:43.669  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-05 15:17:43.670  7972  7972 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-05 15:17:43.679  7972  7972 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-05 15:17:43.679  7972  7972 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-05 15:17:43.681  7738  7969 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-05 15:17:43.683  7738  7973 D BluetoothAdapterProperties: Name is: G3
,08-05 15:17:43.685  7738  7969 D BluetoothAdapterProperties: Setting state to 11
08-05 15:17:43.685  7738  7969 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-05 15:17:43.686  1035  1111 D BluetoothManagerService: Message: 60
08-05 15:17:43.686  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-05 15:17:43.686  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-05 15:17:43.688  7738  7969 I LGBluetoothServiceJni: classInitNative: succeeds
08-05 15:17:43.694  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-05 15:17:43.697  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 15:17:43.699  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:43.703  6961  6961 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-05 15:17:43.710  7738  7738 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 15:17:43.710  7738  7738 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:43.710  7738  7738 V BluetoothPbapReceiver: ***********state = 11
,08-05 15:17:43.724  7738  7969 D BluetoothBondStateMachine: make
,08-05 15:17:43.729  7738  7969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1716075a
08-05 15:17:43.729  7738  7969 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-05 15:17:43.729  7738  7969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1716075a
08-05 15:17:43.729  7738  7969 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-05 15:17:43.730  7738  7986 I BluetoothBondStateMachine: StableState(): Entering Off State
08-05 15:17:43.731  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 15:17:43.733  7738  7969 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-05 15:17:43.736  7738  7969 E BluetoothAdapterService: File transfer profiles supported!!
08-05 15:17:43.743  7738  7969 E BluetoothAdapterService: File transfer profiles supported!!
08-05 15:17:43.745  6961  6961 D BluetoothPermissionRequest: onReceive
08-05 15:17:43.745  7738  7738 D HeadsetService: Received start request. Starting profile...
,08-05 15:17:43.745  7738  7738 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 15:17:43.745  7738  7738 D LGBluetoothHfpAdapter: Version 1.6
08-05 15:17:43.748  7738  7738 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 15:17:43.748  6961  6961 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 15:17:43.748  7738  7969 E BluetoothAdapterService: File transfer profiles supported!!
08-05 15:17:43.749  7738  7738 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 15:17:43.750  7738  7738 D HeadsetStateMachine: make
08-05 15:17:43.754  7738  7969 E BluetoothAdapterService: File transfer profiles supported!!
08-05 15:17:43.758  7738  7969 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 15:17:43.762  7738  7969 E BluetoothAdapterService: File transfer profiles supported!!
08-05 15:17:43.765  7738  7969 E BluetoothAdapterService: File transfer profiles supported!!
08-05 15:17:43.773  7738  7969 V LGMDMManager: Create singleton instance
,08-05 15:17:43.780  7738  7969 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-05 15:17:43.782  7738  7738 D LgDataFeature: LgDataFeature() Constructor: none
08-05 15:17:43.782  7738  7738 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 15:17:43.786  7738  7738 D HeadsetStateMachine: max_hf_connections = 1
08-05 15:17:43.786  7738  7738 I bluedroid-qcom: get_profile_interface handsfree
,08-05 15:17:43.788  7738  7738 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-05 15:17:43.788   323  1384 V AudioPolicyService: registerClient() client 0xb1427160, uid 1002
08-05 15:17:43.788   323  2159 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-05 15:17:43.788   323  2159 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 15:17:43.788   323  2159 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 15:17:43.788  7738  7738 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 15:17:43.789   323  1383 V AudioFlinger: registerClient() client 0xb14338e0, pid 7738
08-05 15:17:43.789   323  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 15:17:43.789   323  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 15:17:43.789  1604  2544 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 15:17:43.789  1604  2544 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 15:17:43.789   323  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 15:17:43.789   323  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 15:17:43.789  1604  2544 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 15:17:43.789  1604  2544 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 15:17:43.789  1035  1978 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 15:17:43.789  1035  1978 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 15:17:43.789  1035  1978 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 15:17:43.789  7738  7738 V ToneGenerator: Create Track: 0xb4928a80
,08-05 15:17:43.789  1035  1978 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 15:17:43.789  7738  7738 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-05 15:17:43.789  7738  7738 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-05 15:17:43.789  7738  7753 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 15:17:43.789   323   323 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 15:17:43.789  7738  7753 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-05 15:17:43.790   323   323 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-05 15:17:43.790   323   323 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 15:17:43.790   323   323 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 15:17:43.790  7738  7753 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 15:17:43.790  7738  7753 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-05 15:17:43.790   323  2159 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 15:17:43.790   323  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 15:17:43.790   323  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-05 15:17:43.790   323  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 15:17:43.790   323  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 15:17:43.790  7738  7738 V AudioSystem: getLatency() output 2, latency 50
08-05 15:17:43.790  7738  7738 V AudioSystem: getFrameCount() output 2, frameCount 960
08-05 15:17:43.790  7738  7738 V AudioTrack: createTrack_l() output 2 afLatency 50
08-05 15:17:43.790   323  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 15:17:43.790   323  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 15:17:43.790   323  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 15:17:43.790   323  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 15:17:43.790   323  1383 V AudioFlinger: createTrack() lSessionId: 23
08-05 15:17:43.791  3356  3375 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 15:17:43.791  3356  3375 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 15:17:43.791  3356  3375 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 15:17:43.791  3356  3375 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 15:17:43.791  1852  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 15:17:43.791  1852  1868 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 15:17:43.791  1852  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 15:17:43.791  1852  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 15:17:43.791  7738  7738 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-05 15:17:43.791   323   323 V AudioFlinger: acquiring 23 from 7738, for 7738
08-05 15:17:43.791   323   323 V AudioFlinger:  added new entry for 23
08-05 15:17:43.791  7738  7738 V ToneGenerator: ToneGenerator INIT OK, time: 357069
08-05 15:17:43.791  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1716075a
08-05 15:17:43.792  7738  7990 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-05 15:17:43.792  7738  7990 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 15:17:43.793  7738  7990 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = ,false
08-05 15:17:43.793  7738  7990 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-05 15:17:43.793   323  2159 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7738
08-05 15:17:43.793  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1716075a
08-05 15:17:43.797   323  2159 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-05 15:17:43.797   323  2159 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-05 15:17:43.797   323  2159 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-05 15:17:43.797   323  2159 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 15:17:43.797   323  2159 V voice   : voice_set_parameters: exit with code(0)
08-05 15:17:43.797   323  2159 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-05 15:17:43.797   323  2159 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-05 15:17:43.797   323  2159 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 15:17:43.797   323  2159 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 15:17:43.797  7738  7738 D A2dpService: Received start request. Starting profile...
08-05 15:17:43.797   323  2159 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 15:17:43.797   323  2159 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-05 15:17:43.798  7738  7738 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 15:17:43.798  7738  7990 V ToneGenerator: ToneGenerator destructor
08-05 15:17:43.798  7738  7990 V ToneGenerator: stopTone
08-05 15:17:43.798  7738  7990 V ToneGenerator: Delete Track: 0xb4928a80
08-05 15:17:43.798   323  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
08-05 15:17:43.798   323  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-05 15:17:43.798  7738  7738 V Avrcp   : make
08-05 15:17:43.798   323  1258 V AudioPolicyService: AudioCommandThread() waking up
08-05 15:17:43.798   323  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-05 15:17:43.798   323  1258 V AudioPolicyManager: releaseOutput() 2
08-05 15:17:43.798   323  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 15:17:43.798   323  1384 V AudioFlinger: PlaybackThread::Track destructor
08-05 15:17:43.798   323  1384 V AudioFlinger: removeClient_l() pid 7738, calling pid 323
08-05 15:17:43.798  7738  7990 V AudioTrack: ~AudioTrack, releasing session id from 7738 on behalf of 7738
08-05 15:17:43.799   323   323 V AudioFlinger: releasing 23 from 7738 for 7738
08-05 15:17:43.799   323   323 V AudioFlinger:  decremented refcount to 0
08-05 15:17:43.799   323   323 V AudioFlinger: purging stale effects
08-05 15:17:43.799  7738  7738 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-05 15:17:43.799  7738  7738 I bluedroid-qcom: get_profile_interface avrcp
08-05 15:17:43.800  1035  1887 W Process : Unable to open /proc/7992/status
08-05 15:17:43.807  7738  7738 V AudioManager: registerRemoteController: size of Media player list: 0
08-05 15:17:43.809  7738  7738 E AudioManager: No RCC entry present to update
08-05 15:17:43.809  7738  7738 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-05 15:17:43.811  7738  7738 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-05 15:17:43.812  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-05 15:17:43.812  7738  7738 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-05 15:17:43.815  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-05 15:17:43.905  1035  1886 V SIM_STK : Menu title from STK is T-Mobile
,08-05 15:17:43.905  1035  1886 V SIM_STK : Menu title from STK is T-Mobile
,08-05 15:17:43.978  1035  2013 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-05 15:17:43.987  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 15:17:43.991  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 15:17:43.992  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 15:17:43.992  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 15:17:43.992  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 15:17:43.992  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 15:17:43.992  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 15:17:43.992  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 15:17:43.992  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 15:17:43.992  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 15:17:43.992  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 15:17:43.992  7738  7738 I BluetoothA2dpServiceJni: classInitNative
08-05 15:17:43.993  7738  7738 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-05 15:17:43.993  7738  7738 D A2dpStateMachine: make
08-05 15:17:43.995  7738  7738 I bluedroid-qcom: get_profile_interface a2dp
08-05 15:17:43.996  7738  7997 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-05 15:17:43.998  7738  7738 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-05 15:17:43.998  7738  7738 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-05 15:17:43.999  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1716075a
08-05 15:17:43.999  7738  7996 D A2dpStateMachine: Enter Disconnected: -2
08-05 15:17:44.000  7738  7738 I BluetoothHidServiceJni: classInitNative: succeeds
08-05 15:17:44.001  7738  7738 D HidService: Received start request. Starting profile...
08-05 15:17:44.001  7738  7738 I bluedroid-qcom: get_profile_interface hidhost
08-05 15:17:44.001  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1716075a
08-05 15:17:44.001  7738  7738 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 15:17:44.003  7738  7738 D HealthService: Received start request. Starting profile...
08-05 15:17:44.006  7738  7738 I bluedroid-qcom: get_profile_interface health
08-05 15:17:44.006  7738  7738 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-05 15:17:44.006  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1716075a
08-05 15:17:44.007  7738  7738 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-05 15:17:44.009  7738  7738 D PanService: Received start request. Starting profile...
08-05 15:17:44.009  7738  7738 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 15:17:44.009  7738  7738 I bluedroid-qcom: get_profile_interface pan
08-05 15:17:44.016  7738  7738 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-05 15:17:44.016  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1716075a
08-05 15:17:44.017  7738  7738 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-05 15:17:44.020  7738  7738 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 15:17:44.020  7738  7738 D BtGatt.GattService: Received start request. Starting profile...
08-05 15:17:44.021  7738  7738 D BtGatt.GattService: start()
08-05 15:17:44.021  7738  7738 I bluedroid-qcom: get_profile_interface gatt
,08-05 15:17:44.021  7738  7738 D BtGatt.AdvertiseManager: advertise manager created
,08-05 15:17:44.029  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1716075a
08-05 15:17:44.030  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1716075a
08-05 15:17:44.031  7738  7738 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-05 15:17:44.031  7738  7738 V BluetoothMapService: BluetoothMapBinder()
08-05 15:17:44.032  7738  7738 D BluetoothMapService: Received start request. Starting profile...
,08-05 15:17:44.032  7738  7738 D BluetoothMapService: start()
,08-05 15:17:44.035  7738  7738 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-05 15:17:44.035  7738  7738 D BluetoothMapEmailAppObserver: createReceiver()
08-05 15:17:44.036  7738  7738 D BluetoothMapEmailAppObserver: initObservers()
08-05 15:17:44.036  7738  7738 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-05 15:17:44.042  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1716075a
08-05 15:17:44.042  7738  7738 D HeadsetStateMachine: Proxy object connected
08-05 15:17:44.043  7738  7738 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-05 15:17:44.043  7738  7738 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-05 15:17:44.044  7738  7990 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-05 15:17:44.048  7738  7990 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 15:17:44.048  7738  7990 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-05 15:17:44.049  7738  7738 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 15:17:44.053  7738  7738 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 15:17:44.056  7738  7738 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 15:17:44.058  7738  7738 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-05 15:17:44.063  7738  7738 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 15:17:44.064  7738  7738 V PanService: [BTUI] SIM Extra State :ABSENT
08-05 15:17:44.068  7738  7738 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 15:17:44.077  7738  7738 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-05 15:17:44.078  7738  7738 V BluetoothMapService: Handler(): got msg=1
08-05 15:17:44.081  7738  7738 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 15:17:44.081  7738  7738 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 15:17:44.081  7738  7738 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 15:17:44.081  7738  7738 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:44.081  7738  7738 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-05 15:17:44.084  7738  7969 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-05 15:17:44.084  7738  7969 I bluedroid-qcom: enable
08-05 15:17:44.086  7738  7969 I bt_hci_bdroid: init
08-05 15:17:44.087  7738  8008 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-05 15:17:44.087  7738  8008 I bt-btu  : btu_task pending for preload complete event
08-05 15:17:44.093  7738  7969 I bt_vendor: bt-vendor : init
08-05 15:17:44.093  7738  7969 I bt_vendor: bt-vendor : get_bt_soc_type
08-05 15:17:44.093  7738  7969 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-05 15:17:44.093  7738  7969 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-05 15:17:44.093  7738  7969 D bt_userial_mct: userial_init
08-05 15:17:44.095  7738  7969 D bt_hci_bdroid: set_power 1
,08-05 15:17:44.096  7738  7969 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-05 15:17:44.096  7738  7969 I bt_vendor: Starting hciattach daemon
08-05 15:17:44.096  7738  7969 I bt_vendor: try to set true
08-05 15:17:44.082  8011  8011 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:44.082  8011  8011 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:44.133  8012  8012 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-05 15:17:44.237  8018  8018 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-05 15:17:44.248  8019  8019 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-05 15:17:44.275  8021  8021 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 15:17:44.287  8022  8022 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-05 15:17:44.316  8023  8023 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 15:17:44.341  8024  8024 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-05 15:17:44.368  8026  8026 I libmdmdetect: ESOC framework not supported
,08-05 15:17:44.369  8026  8026 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-05 15:17:44.378  8026  8026 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-05 15:17:44.378  8026  8026 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-05 15:17:44.378  8026  8026 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-05 15:17:44.378  8026  8026 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-05 15:17:44.378  8026  8026 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-05 15:17:44.378  8026  8026 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-05 15:17:44.378  8026  8026 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-05 15:17:44.422  8026  8027 E QC-QMI  : qmi_client [8026] 15: failed to locate client data
,08-05 15:17:44.424   493   493 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-05 15:17:44.426   493   493 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-05 15:17:44.484  8028  8028 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-05 15:17:44.514  8029  8029 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 15:17:44.549  7738  7969 I bt_vendor: bluetooth satus is on
08-05 15:17:44.549  7738  7969 D bt_hci_bdroid: preload
08-05 15:17:44.549  7738  8010 D bt_userial_mct: userial_open(port:0)
08-05 15:17:44.549  7738  8010 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-05 15:17:44.555  7738  8010 I bt_vendor: Done intiailizing UART
,08-05 15:17:44.560  7738  8010 I bt_vendor: Done intiailizing UART
,08-05 15:17:44.560  7738  8010 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-05 15:17:44.561  7738  8010 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-05 15:17:44.561  7738  8008 I bt-btu  : btu_task received preload complete event
08-05 15:17:44.562  7738  8034 D bt_userial_mct: Entering userial_read_thread()
08-05 15:17:44.563  7738  8008 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-05 15:17:44.563  7738  8008 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-05 15:17:44.569  7738  8008 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-05 15:17:44.576  7738  8008 I         : BTE_InitTraceLevels -- TRC_HCI
08-05 15:17:44.576  7738  8008 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 15:17:44.576  7738  8008 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 15:17:44.576  7738  8008 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 15:17:44.576  7738  8008 I         : BTE_InitTraceLevels -- TRC_AVRC
08-05 15:17:44.576  7738  8008 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 15:17:44.576  7738  8008 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 15:17:44.577  7738  8008 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 15:17:44.577  7738  8008 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-05 15:17:44.577  7738  8008 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 15:17:44.577  7738  8008 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 15:17:44.577  7738  8008 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 15:17:44.578  7738  8008 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 15:17:44.578  7738  8008 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 15:17:44.578  7738  8008 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 15:17:44.578  7738  8008 I         : BTE_InitTraceLevels -- TRC_BTIF
08-05 15:17:44.666  7738  8008 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-05 15:17:44.666  7738  8008 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa020e061 
,08-05 15:17:44.666  7738  8008 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa020e061 
08-05 15:17:44.685  7738  7973 E bt-btif : Calling BTA_HhEnable
08-05 15:17:44.685  7738  7973 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-05 15:17:44.685  7738  7973 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 15:17:44.688  7738  8008 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-05 15:17:44.688  7738  8008 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-05 15:17:44.688  7738  8008 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-05 15:17:44.688  7738  8008 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-05 15:17:44.688  7738  8008 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-05 15:17:44.690  7738  7973 D BluetoothAdapterProperties: Name is: G3
08-05 15:17:44.691  7738  7973 D BluetoothAdapterProperties: Scan Mode:20
08-05 15:17:44.692  7738  7973 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 15:17:44.692  7738  7973 D bt_hci_bdroid: postload
08-05 15:17:44.692  7738  8010 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 15:17:44.694  7738  8010 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 15:17:44.694  7738  8008 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-05 15:17:44.694  7738  7973 D bte_conf: Device ID record 1 : primary
08-05 15:17:44.695  7738  7973 D bte_conf:   vendorId            = 00c4
08-05 15:17:44.695  7738  7973 D bte_conf:   vendorIdSource      = 0001
08-05 15:17:44.695  7738  7973 D bte_conf:   product             = 13a1
08-05 15:17:44.695  7738  7973 D bte_conf:   version             = 1000
08-05 15:17:44.695  7738  7973 D bte_conf:   clientExecutableURL = 
08-05 15:17:44.695  7738  7973 D bte_conf:   serviceDescription  = 
08-05 15:17:44.695  7738  7973 D bte_conf:   documentationURL    = 
08-05 15:17:44.695  7738  7973 D bte_conf: bte_load_did_conf no section named DID2.
08-05 15:17:44.689  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 15:17:44.699  7738  8010 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 15:17:44.699  7738  8010 D bt_hci_bdroid: Used up Tx Cmd credits
,08-05 15:17:44.704  7738  8010 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 15:17:44.692  8040  8040 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:44.709  7738  8034 E bt_mct  : hci lib postload completed
08-05 15:17:44.712  7738  7969 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-05 15:17:44.715  7738  7969 D BluetoothAdapterProperties: ScanMode =  20
08-05 15:17:44.715  7738  7969 D BluetoothAdapterProperties: State =  11
08-05 15:17:44.716  7738  7969 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-05 15:17:44.717  7738  7969 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-05 15:17:44.717  7738  7969 D BluetoothAdapterProperties: Setting state to 12
08-05 15:17:44.717  7738  7969 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 15:17:44.702  8040  8040 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:44.723  7738  8008 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 15:17:44.723  7738  8008 W bt-smp  : Plain text(LSB ~ MSB) = c5 99 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 15:17:44.723  7738  8008 W bt-smp  : Encrypted text(LSB ~ MSB) = 05 6e 4e 7d 4f 34 60 8e f2 8d e6 16 45 9f ed d7 
08-05 15:17:44.725  7738  8008 W bt-btm  : Stopping oneshot timer
,08-05 15:17:44.727  7738  7973 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-05 15:17:44.727  7738  7973 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 15:17:44.745  1035  1111 D BluetoothManagerService: Message: 60
08-05 15:17:44.745  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-05 15:17:44.745  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-05 15:17:44.763  7738  8008 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 15:17:44.763  7738  8008 W bt-smp  : Plain text(LSB ~ MSB) = fa a6 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 15:17:44.763  7738  8008 W bt-smp  : Encrypted text(LSB ~ MSB) = 87 dc cb 11 15 c6 fa 1f 99 76 16 ec 22 e1 37 96 
,08-05 15:17:44.767  7738  8008 W bt-btm  : Stopping oneshot timer
08-05 15:17:44.776  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:44.776  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:44.776  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:44.776  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 15:17:44.776  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:44.776  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 15:17:44.776  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 15:17:44.776  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 15:17:44.785  7738  7973 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 15:17:44.786  7738  7973 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-05 15:17:44.786  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 15:17:44.786  7738  7969 I BluetoothAdapterState: Entering On State
08-05 15:17:44.790  7738  8008 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 15:17:44.790  7738  8008 W bt-smp  : Plain text(LSB ~ MSB) = 76 97 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 15:17:44.790  7738  8008 W bt-smp  : Encrypted text(LSB ~ MSB) = 1c cc 79 d3 02 53 e8 a6 79 d7 e0 84 c4 99 97 8f 
,08-05 15:17:44.793  7738  8008 W bt-btm  : Stopping oneshot timer
08-05 15:17:44.798  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 15:17:44.807  7738  8008 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 15:17:44.807  7738  8008 W bt-smp  : Plain text(LSB ~ MSB) = 9b 86 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 15:17:44.807  7738  8008 W bt-smp  : Encrypted text(LSB ~ MSB) = 12 19 8a d9 f2 92 ba 86 50 95 ab 2a ad 1f 75 46 
,08-05 15:17:44.809  7738  8008 W bt-btm  : Stopping oneshot timer
08-05 15:17:44.811  7738  7969 D LGBluetoothServiceAdapter: [BTUI] OnState
,08-05 15:17:44.812  7738  7969 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-05 15:17:44.812  7738  7969 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-05 15:17:44.816  7738  7969 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-05 15:17:44.816  6961  6979 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 15:17:44.829  1852  4468 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 15:17:44.835  7738  8008 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 15:17:44.835  7738  8008 W bt-smp  : Plain text(LSB ~ MSB) = 10 91 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 15:17:44.835  7738  8008 W bt-smp  : Encrypted text(LSB ~ MSB) = a5 aa b5 66 9c c9 d4 7a ed 14 bb 9f be e9 ef 15 
08-05 15:17:44.835  7738  8008 W bt-btm  : Stopping oneshot timer
08-05 15:17:44.837  7738  7969 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-05 15:17:44.842  6961  6961 D BluetoothA2dp: Proxy object connected
08-05 15:17:44.843  6961  6961 D A2dpProfile: Bluetooth service connected
08-05 15:17:44.848  1852  1852 D BluetoothHeadset: Proxy object connected
,08-05 15:17:44.850  6961  7032 D BluetoothMap: onBluetoothStateChange: up=true
08-05 15:17:44.861  8055  8055 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-05 15:17:44.864  6961  6961 D BluetoothMap: Proxy object connected
08-05 15:17:44.864  1852  4455 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 15:17:44.864  6961  6961 D MapProfile: Bluetooth service connected
08-05 15:17:44.864  6961  6961 D BluetoothMap: getConnectedDevices()
08-05 15:17:44.866  7738  7754 V BluetoothMapService: getConnectedDevices()
,08-05 15:17:44.867  1852  1852 D BluetoothHeadset: Proxy object connected
08-05 15:17:44.867  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 15:17:44.869  1852  1852 D BluetoothHeadset: Proxy object connected
08-05 15:17:44.869  6961  6982 D BluetoothPan: onBluetoothStateChange on: true
08-05 15:17:44.869  6961  6982 D BluetoothPan: onBluetoothStateChange call bindService
08-05 15:17:44.872  6961  6961 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 15:17:44.872  6961  6961 D PanProfile: Bluetooth service connected
08-05 15:17:44.873  6961  7032 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 15:17:44.875  1035  1111 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 15:17:44.876  1035  1035 D BluetoothA2dp: Proxy object connected
,08-05 15:17:44.878  6961  6982 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 15:17:44.880  6961  6961 D BluetoothHeadset: Proxy object connected
08-05 15:17:44.880  6961  6961 D HeadsetProfile: Bluetooth service connected
08-05 15:17:44.880  6961  7032 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 15:17:44.882  1035  1111 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 15:17:44.883  6961  6961 D BluetoothInputDevice: Proxy object connected
08-05 15:17:44.883  6961  6961 D HidProfile: Bluetooth service connected
08-05 15:17:44.883  1035  1035 D BluetoothHeadset: Proxy object connected
08-05 15:17:44.883  1035  1111 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-05 15:17:44.883  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-05 15:17:44.885  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-05 15:17:44.885  1035  1111 D BluetoothManagerService: Message: 40
08-05 15:17:44.885  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-05 15:17:44.886  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 15:17:44.888  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-05 15:17:44.888  1941  2139 D LGBluetoothAPIService: Message: 1
08-05 15:17:44.888  1941  2139 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-05 15:17:44.888  1941  2139 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-05 15:17:44.888  1941  2139 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-05 15:17:44.890  7738  7738 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:44.890  7738  7738 D BluetoothMapService: STATE_ON
08-05 15:17:44.892  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:44.894  6961  6961 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-05 15:17:44.895  6961  6961 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 15:17:44.900  6961  6961 D DockEventReceiver: finishStartingService: stopping service
,08-05 15:17:44.906  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1716075a
08-05 15:17:44.906  7738  7738 V BluetoothPbapService: Pbap Service onCreate
08-05 15:17:44.906  7738  7738 V BluetoothPbapService: Starting PBAP service
08-05 15:17:44.907  7738  7738 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-05 15:17:44.907  7738  7738 V BluetoothPbapService: Pbap Service onBind
08-05 15:17:44.908  7738  7738 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:44.908  6961  6961 D BluetoothPbap: Proxy object connected
08-05 15:17:44.908  6961  6961 D PbapServerProfile: Bluetooth service connected
08-05 15:17:44.908  7738  7738 V BluetoothPbapService: state: 12
08-05 15:17:44.908  7738  7738 V BluetoothMapService: Handler(): got msg=1
08-05 15:17:44.908  7738  7738 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-05 15:17:44.909  7738  7738 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 15:17:44.909  7738  7738 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:44.909  7738  7738 V BluetoothPbapReceiver: ***********state = 12
08-05 15:17:44.909  7738  8064 D BluetoothMapMasInstance: MAS initSocket()
08-05 15:17:44.910  7738  8064 D BluetoothMapMasInstance:   masId = 00
08-05 15:17:44.910  7738  8064 D BluetoothMapMasInstance:   msgTypes = 0e
08-05 15:17:44.910  7738  8064 D BluetoothMapMasInstance:   masName = SMS/MMS
08-05 15:17:44.910  7738  8064 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-05 15:17:44.910  7738  7738 V BluetoothPbapService: Handler(): got msg=1
08-05 15:17:44.910  7738  7738 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-05 15:17:44.911  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 15:17:44.911  1035  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:44.912  2232  2232 D c       : Getting all permits...
08-05 15:17:44.912  2232  2232 D a       : Opening database...
08-05 15:17:44.913  7738  8064 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 15:17:44.913  7738  8065 V BluetoothPbapService: Pbap Service initSocket
08-05 15:17:44.914  1035  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:44.915  7738  8064 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-05 15:17:44.915  7738  8064 V BluetoothMapMasInstance: Succeed to create listening socket 
08-05 15:17:44.915  7738  8064 D BluetoothMapMasInstance: Accepting socket connection...
08-05 15:17:44.918  2232  2232 D a       : Opening database auth.proximity.permit_store...
08-05 15:17:44.919  2232  2232 D a       : Closing database...
,08-05 15:17:44.920  7738  7973 D BluetoothAdapterProperties: Scan Mode:21
08-05 15:17:44.921  7738  7973 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-05 15:17:44.922  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:44.923  7738  8065 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 15:17:44.925  7738  8065 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-05 15:17:44.925  7738  8065 V BluetoothPbapService: Succeed to create listening socket 
08-05 15:17:44.925  7738  8065 V BluetoothPbapService: Accepting socket connection...
08-05 15:17:44.929  6961  6961 D BluetoothPermissionRequest: onReceive
08-05 15:17:44.931  6961  6961 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-05 15:17:44.933  6961  6961 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 15:17:44.936  7738  7738 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-05 15:17:44.938  7738  7738 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-05 15:17:44.944  7738  7738 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-05 15:17:44.976  7738  7738 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-05 15:17:44.976  7738  7738 V BtOppService: onCreate
,08-05 15:17:44.981  7738  7738 V BluetoothOppNotification: send message
08-05 15:17:44.985  7738  7738 V BtOppService: Starting RfcommListener
08-05 15:17:44.991  7738  7738 D BluetoothOppPreference: Dumping Names:  
08-05 15:17:44.991  7738  7738 D BluetoothOppPreference: {}
08-05 15:17:44.991  7738  7738 D BluetoothOppPreference: Dumping Channels:  
08-05 15:17:44.991  7738  7738 D BluetoothOppPreference: {}
08-05 15:17:44.992  7738  7738 V BtOppService: onStartCommand
,08-05 15:17:44.999  7738  7738 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:45.000  7738  7738 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 15:17:45.002  7738  8072 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 15:17:45.005  7738  8069 V BtOppService: Deleted complete outbound shares, number =  0
08-05 15:17:45.008  7738  8072 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-05 15:17:45.009  7738  7738 V BluetoothOppNotification: new notify threadi!
08-05 15:17:45.010  7738  8072 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c9cdf36 on behalf of 
08-05 15:17:45.010  7738  8069 V BtOppService: Deleted complete inbound failed shares, number = 0
08-05 15:17:45.012  7738  8069 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-05 15:17:45.013  7738  7738 V BluetoothOppNotification: send delay message
08-05 15:17:45.014  7738  8069 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1491ae37 on behalf of 
08-05 15:17:45.014  7738  7738 V BtOppService: start RfcommListener
08-05 15:17:45.015  7738  8072 V BluetoothOppNotification: update too frequent, put in queue
08-05 15:17:45.015  7738  8073 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 15:17:45.017  7738  8072 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 15:17:45.019  7738  8073 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1aa61fa4 on behalf of 
08-05 15:17:45.021  7738  7738 V BtOppService: RfcommListener started
08-05 15:17:45.022  7738  8074 V BtOppRfcommListener: Starting RFCOMM listener....
,08-05 15:17:45.023  1035  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:45.022  7738  8073 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 15:17:45.025  7738  8074 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 15:17:45.026  7738  8074 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
,08-05 15:17:45.026  7738  8074 V BtOppRfcommListener: Started RFCOMM listener....
08-05 15:17:45.026  7738  8074 I BtOppRfcommListener: Accept thread started.
08-05 15:17:45.026  7738  8074 V BtOppRfcommListener: Accepting connection...
08-05 15:17:45.027  7738  8073 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 15:17:45.030  7738  8073 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1337a10d on behalf of 
08-05 15:17:45.032  7738  8073 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 15:17:45.034  7738  8073 V BluetoothOppNotification: outbound notification was removed.
08-05 15:17:45.035  7738  8073 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-05 15:17:45.038  7738  8073 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ecfb8c2 on behalf of 
08-05 15:17:45.039  7738  8073 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 15:17:45.042  7738  8073 V BluetoothOppNotification: inbound notification was removed.
08-05 15:17:45.042  7738  8073 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 15:17:45.044  7738  8073 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30c8f6d3 on behalf of 
08-05 15:17:45.045  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1716075a
08-05 15:17:45.045  7738  7738 V BluetoothFtpService: Ftp Service onCreate
08-05 15:17:45.045  7738  7738 I BluetoothFtpService: Ftp Service onCreate
08-05 15:17:45.045  7738  7738 V BtOppService: ContentObserver received notification
08-05 15:17:45.046  7738  7738 V BluetoothFtpService: Ftp Service onStartCommand
08-05 15:17:45.046  7738  7738 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:45.046  7738  7738 V BluetoothFtpService: Starting Listening on sockets
08-05 15:17:45.047  7738  7738 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 15:17:45.047  7738  7738 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 15:17:45.047  7738  7738 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 15:17:45.047  7738  7738 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:45.047  7738  7738 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-05 15:17:45.047  7738  7738 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 15:17:45.048  7738  8075 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 15:17:45.048  7738  8075 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 15:17:45.050  7738  8075 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@124a4109 on behalf of 
08-05 15:17:45.050  7738  7738 V BtOppService: ContentObserver received notification
08-05 15:17:45.050  7738  7738 V BluetoothFtpService: Handler(): got msg=1
08-05 15:17:45.050  7738  7738 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-05 15:17:45.051  7738  7738 V BluetoothFtpService: Ftp Service initSocket
,08-05 15:17:45.055  7738  8075 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 15:17:45.055  7738  8075 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 15:17:45.056  1035  1644 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:45.057  7738  8075 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f649f0e on behalf of 
08-05 15:17:45.057  7738  7738 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 15:17:45.058  7738  8075 V BluetoothOppNotification: update too frequent, put in queue
08-05 15:17:45.059  7738  8075 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 15:17:45.060  7738  7738 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-05 15:17:45.061  7738  7738 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-05 15:17:45.063  7738  8076 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-05 15:17:45.078  7738  7738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1716075a
,08-05 15:17:45.078  7738  7738 V BluetoothSapService: Sap Service onCreate
08-05 15:17:45.081  7738  7738 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 15:17:45.081  7738  7738 V BluetoothSapService: state: 12
08-05 15:17:45.081  7738  7738 V BluetoothSapService: Starting SAP server process
08-05 15:17:45.083  7738  7738 V BluetoothSapService: SAP Service startRfcommListenerThread
08-05 15:17:45.084  7738  8078 V BluetoothSapService: Sap Service initRfcommSocket
08-05 15:17:45.085  1035  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:45.072  8077  8077 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:45.072  8077  8077 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:45.087  7738  8078 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 15:17:45.088  7738  8078 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-05 15:17:45.089  7738  8078 V BluetoothSapService: Succeed to create listening socket 
08-05 15:17:45.089  7738  8078 V BluetoothSapService: Accepting socket connection...
08-05 15:17:45.114  8077  8077 V BT_SAP  : Event pipe created
08-05 15:17:45.114  8077  8077 V BT_SAP  : create_server_socket qcom.sap.server
08-05 15:17:45.114  8077  8077 V BT_SAP  : created socket fd 6
,08-05 15:17:45.630  6877  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:45.630  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:45.630  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:45.630  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 15:17:45.630  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:45.630  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 15:17:45.630  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 15:17:45.630  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 15:17:45.643  6877  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 15:17:45.650  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:45.651  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f8828ff added. We now have 8 listener(s)
08-05 15:17:45.651  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 15:17:45.658  1035  1576 D WifiServiceImplEx: setWifiEnabled: false pid=6877, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 15:17:45.658  1035  1576 D WifiService: setWifiEnabled: false pid=6877, uid=10118
08-05 15:17:45.658  1035  1576 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 15:17:45.664  6877  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:45.665  1035  1959 D WifiServiceImplEx: setWifiEnabled: true pid=6877, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 15:17:45.666  1035  1959 D WifiService: setWifiEnabled: true pid=6877, uid=10118
08-05 15:17:45.666  1035  1959 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 15:17:45.685  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 15:17:45.685  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 15:17:45.685  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-05 15:17:45.687  1035  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-05 15:17:45.687  1035  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-05 15:17:45.689  1035  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-05 15:17:45.689  1035  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 15:17:45.689  1035  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-05 15:17:45.689  1035  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 15:17:45.689  1035  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-05 15:17:45.690  1035  1539 E WifiHW  : unknown target_country: EU , set to default
08-05 15:17:45.690  1035  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-05 15:17:45.690  1035  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-05 15:17:45.690  1035  1539 I WifiUtil: gEnableBmps=1
08-05 15:17:46.015  7738  7738 V BluetoothOppNotification: new notify threadi!
08-05 15:17:46.015  7738  7738 V BluetoothOppNotification: send delay message
,08-05 15:17:46.030  7738  8092 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-05 15:17:46.049  7738  8092 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@354f9e1a on behalf of 
,08-05 15:17:46.052  7738  8092 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 15:17:46.053  7738  8092 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 15:17:46.055  7738  8092 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@172e6d4b on behalf of 
08-05 15:17:46.055  7738  8092 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 15:17:46.057  7738  8092 V BluetoothOppNotification: outbound notification was removed.
08-05 15:17:46.057  7738  8092 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 15:17:46.058  7738  8092 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17139328 on behalf of 
08-05 15:17:46.058  7738  8092 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 15:17:46.060  7738  8092 V BluetoothOppNotification: inbound notification was removed.
08-05 15:17:46.060  7738  8092 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 15:17:46.061  7738  8092 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31c0841 on behalf of 
08-05 15:17:46.381   318   894 D SoftapController: Softap fwReload - Ok
,08-05 15:17:46.403  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 15:17:46.403  1035  1111 D Tethering: InitialState.processMessage what=4
08-05 15:17:46.404  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-05 15:17:46.428  1035  1539 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (734ms)
,08-05 15:17:46.493   318   894 D CommandListener: Setting iface cfg
08-05 15:17:46.493   318   894 D CommandListener: Trying to bring down wlan0
,08-05 15:17:46.495  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 15:17:46.495  6961  6961 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 15:17:46.496  6961  6961 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 15:17:46.496  6961  6961 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 15:17:46.497   318   894 D CommandListener: Clearing all IP addresses on wlan0
08-05 15:17:46.501  1035  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-05 15:17:46.502  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 15:17:46.492  8108  8108 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:46.492  8108  8108 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 15:17:46.530  8108  8108 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-05 15:17:46.559  7831  7842 E UEI.SmartControl: file observer is disposed!
08-05 15:17:46.561  6961  6961 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 15:17:46.561  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 15:17:46.561  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 15:17:46.562  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 15:17:46.562  6961  6961 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 15:17:46.563  8108  8108 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-05 15:17:46.564  8108  8108 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-05 15:17:46.570  6961  6961 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-05 15:17:46.578  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 15:17:46.578  6961  6961 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 15:17:46.578  6961  6961 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 15:17:46.578  6961  6961 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 15:17:46.579  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 15:17:46.580  6961  6961 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 15:17:46.580  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 15:17:46.580  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 15:17:46.580  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 15:17:46.581  6961  6961 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 15:17:46.581  6961  6961 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 15:17:46.602  1035  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 15:17:46.602  1035  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 15:17:46.602  1035  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-05 15:17:46.602  1035  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-05 15:17:46.602  1035  1539 D WifiMonitor: connecting to supplicant
08-05 15:17:46.608  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-05 15:17:46.609  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:46.609  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:46.646  8108  8108 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 15:17:46.676  1035  1092 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8117 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-05 15:17:46.677  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-05 15:17:46.695  8108  8108 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-05 15:17:46.701  8108  8108 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-05 15:17:46.702  1035  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-05 15:17:46.703  1035  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-05 15:17:46.704  1035  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-05 15:17:46.704  1035  8134 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-05 15:17:46.704  1035  8134 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 15:17:46.704  1035  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-05 15:17:46.705  1035  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:46.705  1035  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:46.705  1035  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-05 15:17:46.705  1035  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-05 15:17:46.707  1035  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 15:17:46.707  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 15:17:46.707  8108  8108 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-05 15:17:46.708  1035  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-05 15:17:46.708  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-05 15:17:46.708  1035  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-05 15:17:46.708  1035  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-05 15:17:46.708  1035  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-05 15:17:46.708  1035  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-05 15:17:46.708  1035  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-05 15:17:46.708  1035  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 15:17:46.708  1035  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 15:17:46.708  1035  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 15:17:46.709  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:46.709  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:46.709  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:46.709  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:46.709  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 15:17:46.712  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-05 15:17:46.712  1035  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-05 15:17:46.712  1035  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-05 15:17:46.713  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:46.713  1035  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-05 15:17:46.713  1035  1539 D WifiConfigStore: Loading config and enabling all networks 
08-05 15:17:46.714  1035  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-05 15:17:46.714  1941  1941 D WfdService: Waiting for WifiP2p enabling
,08-05 15:17:46.718  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:46.718  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:46.718  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:46.718  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:46.718  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:46.718  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 15:17:46.718  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 15:17:46.718  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 15:17:46.721  1035  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-05 15:17:46.722  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 15:17:46.728  1035  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-05 15:17:46.736  1035  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-05 15:17:46.736  1035  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-05 15:17:46.736  1035  1539 D WifiStateMachine: enableVerboseLogging : level 2
08-05 15:17:46.736  1035  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-05 15:17:46.737  1035  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-05 15:17:46.737  1035  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-05 15:17:46.737  1035  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-05 15:17:46.737  1035  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-05 15:17:46.737  1035  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
,08-05 15:17:46.738  1035  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-05 15:17:46.738  1035  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-05 15:17:46.738  1035  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-05 15:17:46.738  1035  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-05 15:17:46.738  1035  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-05 15:17:46.738  1035  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-05 15:17:46.738  1035  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-05 15:17:46.739  1035  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-05 15:17:46.739  1035  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 15:17:46.739  1035  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-05 15:17:46.740  1035  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-05 15:17:46.740  1035  1539 D WifiNative-HAL: Setting external_sim to 1
08-05 15:17:46.740  1035  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-05 15:17:46.740  1035  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-05 15:17:46.740  1035  1539 I WifiNative-HAL: startHal
08-05 15:17:46.740  1035  1539 D wifi    : setting scan oui 0xaf73e1a0
08-05 15:17:46.740  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-05 15:17:46.740  1941  2352 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-05 15:17:46.740  1941  2352 D WfdsService: Set the WFDS Monitor: true
08-05 15:17:46.740  1941  2352 D WfdsMonitor: WfdsMonitorThread create
08-05 15:17:46.740  1035  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 15:17:46.740  1035  1539 I WifiNative-HAL: startHal
,08-05 15:17:46.740  1035  1539 D wifi    : setting scan oui 0xaf73e1a0
08-05 15:17:46.741  1941  2352 D WfdsMonitor: WFDS Monitor is created and started
08-05 15:17:46.741  1941  2352 D WfdsService: WiFi: Supplicant connection re-established
08-05 15:17:46.741  1035  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-05 15:17:46.741  7762  7762 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:46.741  1035  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-05 15:17:46.741  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-05 15:17:46.741  8108  8108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-05 15:17:46.741  1941  8137 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-05 15:17:46.741  1035  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-05 15:17:46.742  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 15:17:46.742  1941  8137 E CtrlSupplicant: Succeed to open control connection
08-05 15:17:46.742  8108  8108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 15:17:46.742  1035  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 15:17:46.742  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-05 15:17:46.743  8108  8108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-05 15:17:46.743  1035  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-05 15:17:46.743  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 15:17:46.743  8108  8108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 15:17:46.744  1035  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 15:17:46.744  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 15:17:46.744  8108  8108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 15:17:46.744  1035  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 15:17:46.744  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-05 15:17:46.744  8108  8108 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-05 15:17:46.744  1941  8137 E CtrlSupplicant: Succeed to open monitor connection
08-05 15:17:46.745  1035  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-05 15:17:46.745  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 15:17:46.745  8108  8108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-05 15:17:46.745  1941  8137 D WfdsMonitor: Supplicant connection established
08-05 15:17:46.745  1035  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,08-05 15:17:46.746  1941  2352 D WfdsService: Connected to the supplicant for wfds
08-05 15:17:46.746  1035  1539 E WifiNative: : [360,010,338 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-05 15:17:46.746  1035  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-05 15:17:46.746  1035  1539 D WifiNative-wlan0: RECONNECT: returned true
08-05 15:17:46.746  1035  1539 D WifiNative-wlan0: doString: [STATUS]
08-05 15:17:46.747  1035  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 15:17:46.747  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 15:17:46.747  1035  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 15:17:46.747  1035  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 15:17:46.748  1035  1539 D WifiNative-wlan0: SET ps 1: returned true
08-05 15:17:46.748  1035  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.749  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 15:17:46.749  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-05 15:17:46.749  1035  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.749  1035  1557 I WifiNative-HAL: startHal
08-05 15:17:46.749  1035  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf73e1a0
08-05 15:17:46.749  1035  1557 D wifi    : failed to get capabilities : -3
08-05 15:17:46.749  1035  1557 E WifiScanningService: could not get scan capabilities
08-05 15:17:46.749  1035  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.749   318   894 D CommandListener: Setting iface cfg
08-05 15:17:46.749   318   894 D CommandListener: Trying to bring up p2p0
08-05 15:17:46.750  1035  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 15:17:46.750  1035  1538 D LGWifiP2pService: P2pEnablingState
08-05 15:17:46.750  1035  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.750  1035  1538 D LGWifiP2pService: P2p socket connection successful
08-05 15:17:46.750  1035  1538 D LGWifiP2pService: P2pEnabledState
08-05 15:17:46.750  1035  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-05 15:17:46.750  1035  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-05 15:17:46.750  1035  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-05 15:17:46.751  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-05 15:17:46.751  1941  1941 D WfdsService: WifiP2pState is changed : true
08-05 15:17:46.751  1941  2352 D WfdsService: Receive the WFDS_ENABLE Method
08-05 15:17:46.751  1941  2352 D WfdsService: Set the WFDS Monitor: true
08-05 15:17:46.751  1941  2352 D WfdsService: Connected to the supplicant for wfds
08-05 15:17:46.751  1035  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-05 15:17:46.751  1941  2352 D WfdsJNI : doCommand: WFDS_SET TRUE
08-05 15:17:46.751  1035  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-05 15:17:46.751  8108  8108 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-05 15:17:46.751  1035  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-05 15:17:46.752  1941  2352 D WfdsService: selectPreferredScanChannel [36]
08-05 15:17:46.752  1941  2352 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-05 15:17:46.752  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-05 15:17:46.752  1035  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-05 15:17:46.752,  1035  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-05 15:17:46.752  1035  1538 D LGWifiP2pService: before postfix = G3
08-05 15:17:46.752  1035  1538 D WifiServerServiceExt: postfix byte check : 2
08-05 15:17:46.752  1035  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-05 15:17:46.753  1941  1941 D WfdsService: isConnected: false
08-05 15:17:46.753  1035  1538 D LGWifiP2pService: after postfix = G3
08-05 15:17:46.753  1035  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-05 15:17:46.753  1035  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-05 15:17:46.753  1035  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-05 15:17:46.753  1035  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-05 15:17:46.754  1035  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-05 15:17:46.754  1035  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-05 15:17:46.754  1035  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-05 15:17:46.754  1035  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-05 15:17:46.754  1035  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-05 15:17:46.754  1035  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-05 15:17:46.755  1035  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-05 15:17:46.755  1035  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-05 15:17:46.755  1035  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-05 15:17:46.756  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-05 15:17:46.756  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-05 15:17:46.756  1941  1941 D WfdsService: Update P2p Interface State: 3
08-05 15:17:46.756  1035  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
08-05 15:17:46.756  1035  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-05 15:17:46.756  1035  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-05 15:17:46.756  1035  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-05 15:17:46.757  1035  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-05 15:17:46.757  1035  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-05 15:17:46.758  1035  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=360023  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 15:17:46.762  1035  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=360027  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 15:17:46.762  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:46.762  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:46.763  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:46.763  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:46.763  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 15:17:46.763  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:46.764  1035  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-05 15:17:46.764  1035  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-05 15:17:46.765  1035  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-05 15:17:46.765  1035  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-05 15:17:46.765  8108  8108 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-05 15:17:46.765  1035  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-05 15:17:46.765  1035  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-05 15:17:46.765  1035  1538 D LGWifiP2pService: InactiveState
08-05 15:17:46.765  1035  1538 D LGWifiP2pService: InactiveState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.765  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.765  1035  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-05 15:17:46.766  8108  8108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 15:17:46.766  1035  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-05 15:17:46.766  1035  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-05 15:17:46.766  1035  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-05 15:17:46.767  1035  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-05 15:17:46.767  8108  8108 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:46.767  1941  8137 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 15:17:46.767  1035  8134 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 15:17:46.767  1035  8134 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:46.767  1035  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:46.767  1035  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:46.767  8108  8108 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 15:17:46.767  8108  8108 E wpa_supplicant: disconnect_rssi_lvl: -100
,08-05 15:17:46.767  1035  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-05 15:17:46.767  8108  8108 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.768  1035  1538 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.768  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.768  1035  1538 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.768  1035  1538 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.768  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.768  1035  1538 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.768  1035  1538 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.768  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.768  1035  1538 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.768  1941  8137 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 15:17:46.768  1035  1538 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.768  1035  8134 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 15:17:46.768  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.768  1035  8134 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.768  1035  1538 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.768  1035  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.768  1035  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.768  8108  8108 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.768  1941  8137 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 15:17:46.768  1035  8134 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 15:17:46.768  1035  8134 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.768  1035  1035 E WifiServerServiceExt: No p2p device connected
08-05 15:17:46.768  1035  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.768  1035  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.769  1941  2352 W WfdsService: DefaultState - msg [9441285] is not handled
08-05 15:17:46.769  1035  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 15:17:46.769  1035  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 15:17:46.769  1035  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 15:17:46.769  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-05 15:17:46.770  8108  8108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 15:17:46.771  8108  8108 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:46.771  1035  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 15:17:46.771  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:46.771  1035  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:46.771  1035  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 15:17:46.772  8108  8108 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 15:17:46.773  8108  8108 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.773  1035  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-05 15:17:46.773  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.773  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:46.773  1035  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-05 15:17:46.774  1035  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-05 15:17:46.774  8108  8108 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.774  1035  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-05 15:17:46.774  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-05 15:17:46.774  1941  8137 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 15:17:46.774  1941  8137 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 15:17:46.774  1035  8134 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 15:17:46.774  1035  8134 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.774  1035  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.774  1035  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.774  1035  8134 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 15:17:46.774  8108  8108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-05 15:17:46.774  1035  8134 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.774  8108  8108 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 15:17:46.774  1035  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.775  1035  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 15:17:46.775  1035  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-05 15:17:46.775  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 15:17:46.775  1035  8134 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 15:17:46.775  1035  8134 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 15:17:46.775  1035  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-05 15:17:46.775  1035  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-05 15:17:46.776  1035  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-05 15:17:46.776  1035  1539 D WifiNative-wlan0: doBoolean: SCAN
08-05 15:17:46.776  1035  1539 D WifiNative-wlan0: SCAN: returned false
08-05 15:17:46.777  1035  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=360041  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 15:17:46.805  1035  2014 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8142 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 15:17:46.807  1035  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=360071  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 15:17:46.807  1035  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 15:17:46.808  1035  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 15:17:46.808  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:46.808  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:46.808  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 15:17:46.809  1035  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 15:17:46.810  1035  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 15:17:46.810  1035  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 15:17:46.811  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 15:17:46.811  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-05 15:17:46.812  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 15:17:46.812  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-05 15:17:46.813  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:46.813  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:46.814  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:46.820  8117  8140 W FormManager: Network not available. Please check & try again.
,08-05 15:17:46.823  8117  8141 V FormManager: Network unavailable.
08-05 15:17:46.826  8117  8141 V FormManager: Network unavailable.
08-05 15:17:46.843  1035  1977 I ActivityManager: Killing 7264:com.android.chrome/u0a57 (adj 15): empty #17
,08-05 15:17:46.893  1035  1051 W libprocessgroup: failed to open /acct/uid_10057/pid_7264/cgroup.procs: No such file or directory
08-05 15:17:46.949  8142  8142 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 15:17:46.954  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 15:17:46.961  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:46.963  1035  1781 I ActivityManager: Killing 7292:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-05 15:17:47.025  1035  1940 W libprocessgroup: failed to open /acct/uid_10062/pid_7292/cgroup.procs: No such file or directory
,08-05 15:17:47.052  8142  8142 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 15:17:47.058  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 15:17:47.061  8117  8163 W FormManager: Network not available. Please check & try again.
,08-05 15:17:47.067  8117  8164 V FormManager: Network unavailable.
08-05 15:17:47.069  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:47.070  8117  8164 V FormManager: Network unavailable.
08-05 15:17:47.098  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 15:17:47.098  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 15:17:47.100  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 15:17:47.105  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 15:17:47.114  4785  8165 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 15:17:47.118  4785  8166 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 15:17:47.118  4785  8166 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 15:17:47.174  1035  1886 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8167 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-05 15:17:47.198   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 21.750ms
,08-05 15:17:47.220   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 370us total 18.776ms
,08-05 15:17:47.237   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 298us total 16.718ms
,08-05 15:17:47.295  8167  8167 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-05 15:17:47.295  8167  8167 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-05 15:17:47.304  8167  8167 V [BNRBootReceiver]: Boot Receiver Return
,08-05 15:17:47.304  8167  8167 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-05 15:17:47.319  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-05 15:17:47.319  1035  8134 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-05 15:17:47.319  1035  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-05 15:17:47.319  1035  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-05 15:17:47.320  8108  8108 E wpa_supplicant: USIM:  scard_init function
08-05 15:17:47.320  1035  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-05 15:17:47.320  1035  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-05 15:17:47.320  1035  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-05 15:17:47.320  1035  8134 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-05 15:17:47.320  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-05 15:17:47.320  1035  8134 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-05 15:17:47.320  8108  8108 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-05 15:17:47.322  1035  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-05 15:17:47.323  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-05 15:17:47.384  1035  1959 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8185 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 15:17:47.386  1035  1959 I ActivityManager: Killing 7321:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-05 15:17:47.415  7831  7922 D UEI.SmartControl: Internal timer expired: 3
08-05 15:17:47.415  7831  7922 D UEI.SmartControl: unbind internal service
,08-05 15:17:47.444  8108  8108 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 15:17:47.446  1035  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-05 15:17:47.447  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-05 15:17:47.447  1035  8134 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-05 15:17:47.447  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-05 15:17:47.448  1035  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 15:17:47.448  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 15:17:47.453  1035  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 15:17:47.453  8108  8108 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 15:17:47.453  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 15:17:47.453  8108  8108 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 15:17:47.453  1035  8134 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-05 15:17:47.453  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 15:17:47.453  1035  8134 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 15:17:47.453  1035  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-05 15:17:47.453  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 15:17:47.453  1035  8134 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 15:17:47.454  1035  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 15:17:47.454  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 15:17:47.455  1035  1781 W libprocessgroup: failed to open /acct/uid_10085/pid_7321/cgroup.procs: No such file or directory
08-05 15:17:47.457  1035  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=360721  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-05 15:17:47.459  1035  1111 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 15:17:47.460  7831  7831 D UEI.SmartControl: Service.onUnbind: IControl
08-05 15:17:47.462  7831  7831 D UEI.SmartControl: Service.onDestroy
08-05 15:17:47.462  7831  7831 D UEI.SmartControl: Lock is in USE false
08-05 15:17:47.462  7831  7831 D UEI.SmartControl: unbind internal service
08-05 15:17:47.463  7831  7831 D serial_port: close(fd = 24)
08-05 15:17:47.468  1035  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=360733  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-05 15:17:47.469  1035  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=360734  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 15:17:47.470  1035  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=360734  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-05 15:17:47.470  1035  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=360735
08-05 15:17:47.471  1035  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=360735
08-05 15:17:47.471  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:47.471  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:47.474  7831  7831 I UEI.SmartControl: Serial port is closed.
08-05 15:17:47.474  7831  7831 I UEI.SmartControl: Serial port is closed.
08-05 15:17:47.474  7831  7831 D UEI.SmartControl: Blaster closed
08-05 15:17:47.474  7831  7831 D UEI.SmartControl: Shut down QS...
08-05 15:17:47.474  7831  7831 D UEI.SmartControl: Stopping QS lib
08-05 15:17:47.474  7831  7831 D UEI.SmartControl: QS lib stop result = true
08-05 15:17:47.474  7831  7831 D UEI.SmartControl: Stopped QS lib
08-05 15:17:47.474  7831  7831 D UEI.SmartControl: QS shutdown complete
08-05 15:17:47.475  1035  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=360740
08-05 15:17:47.476  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=360740
08-05 15:17:47.476  1035  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=360741
08-05 15:17:47.477  1035  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=360741  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 15:17:47.477  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:47.478  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.478  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.478  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 15:17:47.481  1035  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=360745  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 15:17:47.481  1035  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=360746  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 15:17:47.482  1035  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=360747  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-05 15:17:47.483  1035  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=360747
08-05 15:17:47.483  1035  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=360748
08-05 15:17:47.484  1035  1539 D WifiNative-wlan0: doString: [STATUS]
08-05 15:17:47.485  1035  8134 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 15:17:47.485  1035  8134 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 15:17:47.486  1035  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 15:17:47.487  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.487  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.487  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 15:17:47.487  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.487  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.487  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-05 15:17:47.487  1035  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-05 15:17:47.494  1035  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,08-05 15:17:47.494  1035  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-05 15:17:47.497  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.497  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.497  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 15:17:47.499  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:47.499  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:47.500  8185  8185 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 15:17:47.503  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:47.504  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.504  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.504  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 15:17:47.505  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:47.505  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:47.506  1035  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-05 15:17:47.506  1035  1546 D ConnectivityService: Got NetworkAgent Messenger
08-05 15:17:47.506  1035  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 15:17:47.506  1035  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-05 15:17:47.506  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-05 15:17:47.506  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:47.506  1035  1546 D ConnectivityService: NetworkAgent connected
08-05 15:17:47.506  1035  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 15:17:47.506  1035  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-05 15:17:47.508  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:47.508  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:47.509  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:47.511  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:47.511  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:47.511  1035  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 15:17:47.512  1035  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 15:17:47.512  1035  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 15:17:47.512  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:47.512  1035  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 15:17:47.512  1035  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 15:17:47.515  1035  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 15:17:47.517   318   894 D CommandListener: Setting iface cfg
08-05 15:17:47.519  1035  1539 E WifiStateMachine: Start Dhcp Watchdog 3
,08-05 15:17:47.520  1035  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=360784  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 15:17:47.520  1035  8203 D DhcpStateMachine: StoppedState
08-05 15:17:47.520  1035  8203 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:47.520  1035  8203 D DhcpStateMachine: WaitBeforeStartState
08-05 15:17:47.521  1035  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=360785  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 15:17:47.521  1035  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=360786  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 15:17:47.522  1035  1539 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:47.522  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:47.522  1035  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:47.523  1035  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:47.523  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:47.523  1035  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 15:17:47.524  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 15:17:47.524  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-05 15:17:47.524  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 15:17:47.524  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-05 15:17:47.530  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 15:17:47.530  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-05 15:17:47.532  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 15:17:47.532  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-05 15:17:47.533  1035  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=360797  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 15:17:47.533  1035  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=360798  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 15:17:47.534  1035  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=360798  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 15:17:47.534  8185  8185 D PluginManager: init()
08-05 15:17:47.535  1035  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14389] from screen [on:0 period:1524252302] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 15:17:47.535  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1524252303] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 15:17:47.535  1035  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 15:17:47.539  1035  1546 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-05 15:17:47.540  1035  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:47.540  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:47.540  1035  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:47.541  1035  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:47.541  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:47.541  1035  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:47.542  1035  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-05 15:17:47.542  1035  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=113,0,0
08-05 15:17:47.543  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=113,0,0
08-05 15:17:47.543  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-05 15:17:47.543  8108  8108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-05 15:17:47.543  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:47.543  1035  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-05 15:17:47.543  1035  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-05 15:17:47.544  1035  1539 D WifiNative-wlan0: SET ps 0: returned true
08-05 15:17:47.544  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-05 15:17:47.544  8108  8108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-05 15:17:47.544  1035  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-05 15:17:47.544  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@22839531 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:47.544  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@22839531 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:47.545  1035  8203 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:47.545  1035  8203 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-05 15:17:47.545  1035  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_,DHCP_ACTION[ConnectingState]
08-05 15:17:47.545  1035  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 15:17:47.547  1035  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 15:17:47.548   318   894 D CommandListener: Setting iface cfg
08-05 15:17:47.548   318   894 D CommandListener: Trying to bring up wlan0
08-05 15:17:47.549  1035  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-05 15:17:47.550  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 15:17:47.550  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-05 15:17:47.552  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 15:17:47.552  1035  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:47.552  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 15:17:47.553  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:47.553  1035  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:47.553  1035  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:47.554  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:47.554  1035  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 15:17:47.554  1035  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-05 15:17:47.554  1035  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-05 15:17:47.555  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-05 15:17:47.555  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 15:17:47.555  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:47.555  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:47.555  8108  8108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 15:17:47.555  1035  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 15:17:47.555  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-05 15:17:47.556  8108  8108 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-05 15:17:47.556  1035  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-05 15:17:47.556  1035  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 15:17:47.572  1035  1539 D WifiNative-wlan0: SET ps 1: returned true
,08-05 15:17:47.572  1035  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-05 15:17:47.573  1035  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 15:17:47.573  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 15:17:47.573  1035  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-05 15:17:47.573  1035  1546 D ConnectivityService: ignoring duplicate network state non-change
08-05 15:17:47.576  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.576  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.576  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-05 15:17:47.579  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:47.579  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-05 15:17:47.579  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 15:17:47.579  1035  1546 D ConnectivityService: Adding iface wlan0 to network 102
08-05 15:17:47.580  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.580  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.580  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-05 15:17:47.581  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:47.583  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:47.583  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 15:17:47.584  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:47.586  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 15:17:47.588  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-05 15:17:47.590  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.590  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.590  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 15:17:47.590  1035  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-05 15:17:47.591  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 15:17:47.594  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.594  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:47.594  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 15:17:47.598  1035  1546 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-05 15:17:47.598  1035  1546 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-05 15:17:47.601  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:47.601  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 15:17:47.601  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:47.603  1035  1546 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-05 15:17:47.603   318   894 E Netd    : netlink response contains error (File exists)
08-05 15:17:47.604  1035  1546 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-05 15:17:47.604  1035  1546 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-05 15:17:47.604  1035  1546 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-05 15:17:47.604  1035  1546 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-05 15:17:47.605  1035  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 15:17:47.605  1035  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-05 15:17:47.605  1035  1546 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-05 15:17:47.606  1035  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-05 15:17:47.606  1035  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 15:17:47.606  1035  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:47.606  1035  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 15:17:47.606  1035  8202 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:47.606  1035  8202 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-05 15:17:47.606  1035  8202 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 15:17:47.606  1035  8202 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 15:17:47.608  1035  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:47.608  1035  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-05 15:17:47.608  1035  1546 D ConnectivityService: currentScore = 0, newScore = 20
08-05 15:17:47.608  1035  1546 D ConnectivityService:    accepting network in place of null
08-05 15:17:47.608  1035  1546 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:47.609   318  8207 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-05 15:17:47.609  1035  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 15:17:47.609  1035  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 15:17:47.610  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:47.610  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:47.610  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 15:17:47.610  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 15:17:47.610  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:47.611  1035  1546 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-05 15:17:47.611  1035  1546 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-05 15:17:47.612  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 15:17:47.612  1035  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:47.612  1035  1546 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-05 15:17:47.613  1035  1546 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-05 15:17:47.613  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-05 15:17:47.613  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 15:17:47.614  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 15:17:47.614  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 15:17:47.614  1035  1546 D ConnectivityService: validation of new default Network = false
08-05 15:17:47.614  1035  1546 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-05 15:17:47.614  1035  1546 D DSQN    : enableDataServiceNotify 
08-05 15:17:47.614  1035  1546 D DSQN    : start dsqn bin
08-05 15:17:47,.619  1035  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-05 15:17:47.619  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:47.619  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:47.619  1035  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:47.619  1604  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-05 15:17:47.602  8208  8208 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:47.602  8208  8208 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:47.629  1035  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-05 15:17:47.634  8208  8208 E DSQN    : DSQN ssw
,08-05 15:17:47.640  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 15:17:47.641  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:47.642  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:47.654   318  8207 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-05 15:17:47.690   318  8207 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-05 15:17:47.709  6877  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:47.709  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:47.709  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:47.709  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:47.709  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:47.709  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:47.709  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 15:17:47.709  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 15:17:47.711  6877  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 15:17:47.724  6877  6943 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-05 15:17:47.725  6877  6943 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-05 15:17:47.730  6877  6943 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@616f0b9 Bundle[{}]
08-05 15:17:47.733  6877  6943 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 15:17:47.734  6877  6943 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-05 15:17:47.735   318   893 D LGDataListener: argv[0]=dsqncommand
08-05 15:17:47.735   318   893 D LGDataListener: argv[1]=wlan0
08-05 15:17:47.736   318   893 D LGDataListener: argv[2]=1
08-05 15:17:47.736   318   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-05 15:17:47.736  1035  1108 D DSQN    : DSQM DsqnNotification wlan0  1
08-05 15:17:47.736  1035  1108 D DSQN    : start to monitor internet connection
08-05 15:17:47.738  6877  6943 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-05 15:17:47.740  6877  6943 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-05 15:17:47.742  6877  6943 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-05 15:17:47.744  6877  6943 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-05 15:17:47.746  1035  8203 D DhcpStateMachine: DHCPV4 request on wlan0
08-05 15:17:47.732  8214  8214 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:47.732  8214  8214 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 15:17:47.746  1035  8203 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-05 15:17:47.746  1035  8203 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-05 15:17:47.754  8214  8214 I dhcpcd  : version 5.5.6 starting
08-05 15:17:47.755  8214  8214 E dhcpcd  : get_duid: m
08-05 15:17:47.756  8214  8214 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-05 15:17:47.756  8214  8214 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-05 15:17:47.758  6877  6943 I System.out: Running OutgoingSocketThread
,08-05 15:17:47.760  6877  8216 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 912)
08-05 15:17:47.761  6877  8216 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 36750
08-05 15:17:47.761  6877  8216 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-05 15:17:47.780  1035  8202 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 13:17:47 GMT], X-Android-Received-Millis=[1470403067780], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470403067735]}
08-05 15:17:47.781  1035  8202 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-05 15:17:47.781  1035  8202 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-05 15:17:47.781  1035  1546 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-05 15:17:47.781  1035  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-05 15:17:47.781  1035  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 15:17:47.781  1035  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:47.781  1035  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 15:17:47.781  1035  1546 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-05 15:17:47.781  1035  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-05 15:17:47.781  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:47.781  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-05 15:17:47.781  1035  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:47.781  1035  1546 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:47.782  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-05 15:17:47.782  1035  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:47.782  1035  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 15:17:47.782  1604  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 15:17:47.783  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:47.784  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 15:17:47.801  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-05 15:17:47.802  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 15:17:47.803  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 15:17:47.811  8214  8214 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 15:17:47.811  8214  8214 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 15:17:47.811  8214  8214 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 15:17:47.811  8214  8214 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-05 15:17:47.811  8214  8214 D dhcpcd  : wlan0: sending REQUEST (xid 0xf4e7a556), next in 3.45 seconds
08-05 15:17:47.841  8214  8214 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-05 15:17:47.882  8214  8214 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,08-05 15:17:47.882  8214  8214 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-05 15:17:47.883  8214  8214 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-05 15:17:47.884  8214  8214 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-05 15:17:47.884  8214  8214 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 15:17:47.885  8214  8214 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 15:17:47.885  8214  8214 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 15:17:47.885  8214  8214 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-05 15:17:47.940  8185  8185 W ExternalStrings: load override strings
08-05 15:17:47.940  8185  8185 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 15:17:47.940  8185  8185 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 15:17:47.944  8185  8185 D StatusProvider: onCreate
,08-05 15:17:47.984  8185  8185 V Signer  : override build config not found
08-05 15:17:47.984  8185  8185 D Signer  : value of property debug is false
,08-05 15:17:48.006  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-05 15:17:48.007  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-05 15:17:48.007  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-05 15:17:48.007  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,08-05 15:17:48.007  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-05 15:17:48.007  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-05 15:17:48.007  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-05 15:17:48.008  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-05 15:17:48.008  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-05 15:17:48.008  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-05 15:17:48.008  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-05 15:17:48.008  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-05 15:17:48.008  8185  8185 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-05 15:17:48.015  8185  8185 V LGMDMManager: Create singleton instance
08-05 15:17:48.053  8185  8185 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-05 15:17:48.094  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 15:17:48.095  8185  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 15:17:48.115  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:48.120  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:48.174  1035  1959 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8250 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-05 15:17:48.176  1035  1959 I ActivityManager: Killing 7363:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-05 15:17:48.274  8185  8239 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-05 15:17:48.351  1035  8203 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-05 15:17:48.353  1035  8203 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-05 15:17:48.353  1035  8203 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 15:17:48.354  1035  8203 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-05 15:17:48.354  1035  8203 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-05 15:17:48.354  1035  8203 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 15:17:48.354  1035  8203 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-05 15:17:48.354  1035  8203 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-05 15:17:48.354  1035  8203 D DhcpStateMachine: RunningState
08-05 15:17:48.387  1035  1914 W libprocessgroup: failed to open /acct/uid_10093/pid_7363/cgroup.procs: No such file or directory
,08-05 15:17:48.432  8250  8250 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 15:17:48.462  8250  8250 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-05 15:17:48.503  8250  8250 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-05 15:17:48.504  8250  8250 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-05 15:17:48.504  8250  8250 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-05 15:17:48.505  8250  8250 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,08-05 15:17:48.505  8250  8250 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-05 15:17:48.507  8250  8250 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-05 15:17:48.513  8250  8250 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-05 15:17:48.520  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:48.525  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 15:17:48.527  8185  8239 D LgDataFeature: LgDataFeature() Constructor: none
08-05 15:17:48.528  8185  8239 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 15:17:48.548  8250  8250 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 15:17:48.552  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 15:17:48.552  8185  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 15:17:48.553  8250  8250 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-05 15:17:48.561  8250  8250 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-05 15:17:48.566  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:48.573  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:48.579  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:48.579  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:48.581  8250  8250 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 15:17:48.584  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-05 15:17:48.593  6961  6961 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-05 15:17:48.596  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-05 15:17:48.597  6961  6961 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 15:17:48.597  6961  6961 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 15:17:48.597  6961  6961 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 15:17:48.597  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 15:17:48.598  6961  6961 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 15:17:48.598  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-05 15:17:48.598  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 15:17:48.598  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 15:17:48.598  6961  6961 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 15:17:48.598  6961  6961 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-05 15:17:48.598  6961  6961 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 15:17:48.602  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:48.602  8185  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 15:17:48.613  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:48.626  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:48.634  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:48.634  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:48.635  8250  8250 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 15:17:48.638  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:48.638  8185  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 15:17:48.645  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:48.658  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:48.664  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:48.665  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:48.665  8250  8250 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 15:17:48.668  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:48.669  8185  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 15:17:48.671  8185  8239 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-05 15:17:48.677  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 15:17:48.683  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:48.690  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 15:17:48.690  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:48.691  8250  8250 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 15:17:48.694  8185  8239 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-05 15:17:48.694  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:48.695  8185  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 15:17:48.704  8185  8239 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-05 15:17:48.704  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 15:17:48.705  8185  8239 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-05 15:17:48.706  8185  8239 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-05 15:17:48.707  8185  8239 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-05 15:17:48.707  8185  8239 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-05 15:17:48.711  8185  8239 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-05 15:17:48.714  8185  8239 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-05 15:17:48.714  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 15:17:48.723  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:48.724  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:48.724  8250  8250 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 15:17:48.727  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:48.728  8185  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 15:17:48.733  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:48.751  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:48.759  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:48.759  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:48.760  8250  8250 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 15:17:48.760  6877  6943 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 913)
08-05 15:17:48.760  6877  6943 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 913)
08-05 15:17:48.766  6877  6943 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 918)
08-05 15:17:48.768  6877  6943 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-05 15:17:48.768  6877  6943 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 919)
,08-05 15:17:48.775  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 15:17:48.775  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2db156cc added. We now have 2 listener(s)
08-05 15:17:48.776  1035  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:48.779  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 15:17:48.779  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 15:17:48.779  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 15:17:48.779  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:48.779  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2abc4d15 added. We now have 9 listener(s)
08-05 15:17:48.779  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 15:17:48.780  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 15:17:48.783  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 15:17:48.789  6877  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 15:17:48.789  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:48.789  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:48.789  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:48.789  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:48.789  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:48.789  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 15:17:48.789  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 15:17:48.790  6877  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:48.790  6877  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 15:17:48.790  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 15:17:48.791  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c0561b added. We now have 3 listener(s)
08-05 15:17:48.791  1035  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:48.792  8185  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 15:17:48.794  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 15:17:48.794  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:48.794  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 15:17:48.794  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 15:17:48.794  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:48.794  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0313b8 added. We now have 10 listener(s)
08-05 15:17:48.794  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 15:17:48.794  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:48.794  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:48.794  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:48.794  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:48.794  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.795  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.b,luetooth.BluetoothManager: release: 2 listener(s) left
08-05 15:17:48.795  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 15:17:48.795  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2db156cc removed from the list
08-05 15:17:48.795  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:48.795  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2abc4d15 removed from the list
08-05 15:17:48.797  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 15:17:48.797  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:48.797  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.802  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.802  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.804  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:48.804  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 15:17:48.804  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:48.804  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:48.804  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2abc4d15 not in the list
08-05 15:17:48.804  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.804  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.805  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:48.805  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:48.805  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:48.805  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0313b8 removed from the list
08-05 15:17:48.805  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:48.805  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.805  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.805  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 15:17:48.805  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c0561b removed from the list
08-05 15:17:48.806  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 15:17:48.806  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ba1a591 added. We now have 2 listener(s)
08-05 15:17:48.806  1035  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:48.809  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 15:17:48.810  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 15:17:48.810  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 15:17:48.810  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:48.810  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336bdcf6 added. We now have 9 listener(s)
08-05 15:17:48.810  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 15:17:48.811  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 15:17:48.813  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 15:17:48.817  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 15:17:48.820  6877  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 15:17:48.820  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:48.820  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:48.820  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:48.820  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:48.820  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:48.820  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 15:17:48.820  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 15:17:48.822  6877  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:48.822  6877  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 15:17:48.822  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 15:17:48.823  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db1b364 added. We now have 3 listener(s)
,08-05 15:17:48.823  1035  2048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:48.825  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:48.826  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:48.827  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 15:17:48.827  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 15:17:48.827  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 15:17:48.827  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:48.828  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1caa09cd added. We now have 10 listener(s)
08-05 15:17:48.828  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 15:17:48.828  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 15:17:48.828  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 15:17:48.828  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 15:17:48.828  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 15:17:48.828  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 15:17:48.830  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:48.833  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 15:17:48.833  1035  2048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:48.838  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:48.839  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 15:17:48.839  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:48.839  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 15:17:48.841  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 15:17:48.841  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 15:17:48.843  6877  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 15:17:48.844  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:48.844  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:48.846  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:48.846  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:48.846  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:48.846  8250  8250 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 15:17:48.846  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:48.846  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.846  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 15:17:48.846  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 15:17:48.846  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ba1a591 removed from the list
08-05 15:17:48.846  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:48.846  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336bdcf6 removed from the list
08-05 15:17:48.846  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:48.847  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.849  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.849  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.849  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:48.849  8185  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 15:17:48.850  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:48.851  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:48.851  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:48.851  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336bdcf6 not in the list
08-05 15:17:48.851  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.851  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.854  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:48.858  6877  6943 D BluetoothLeScanner: could not find callback wrapper
08-05 15:17:48.858  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 15:17:48.858  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:48.858  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:48.858  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1caa09cd removed from the list
08-05 15:17:48.858  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:48.858  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 15:17:48.858  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.858  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blueto,othManager: release: 1 listener(s) left
08-05 15:17:48.858  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 15:17:48.858  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db1b364 removed from the list
08-05 15:17:48.859  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 15:17:48.859  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1388a1d0 added. We now have 2 listener(s)
08-05 15:17:48.860  1035  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 15:17:48.866  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 15:17:48.866  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 15:17:48.866  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 15:17:48.866  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:48.866  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@295a75c9 added. We now have 9 listener(s)
08-05 15:17:48.866  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 15:17:48.867  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 15:17:48.872  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 15:17:48.875  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:48.878  6877  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 15:17:48.878  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:48.878  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:48.878  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:48.878  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:48.878  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:48.878  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 15:17:48.878  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 15:17:48.879  6877  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:48.879  6877  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 15:17:48.879  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 15:17:48.880  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10034fef added. We now have 3 listener(s)
08-05 15:17:48.881  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:48.883  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:48.884  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:48.884  1035  1914 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:48.885  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:48.886  8250  8250 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 15:17:48.887  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 15:17:48.887  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 15:17:48.887  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 15:17:48.887  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:48.887  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@159e0afc added. We now have 10 listener(s)
08-05 15:17:48.887  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 15:17:48.887  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 15:17:48.888  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 15:17:48.888  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening ,to advertisements only
08-05 15:17:48.888  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 15:17:48.888  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 15:17:48.888  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 15:17:48.889  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:48.891  8185  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-05 15:17:48.892  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 15:17:48.894  1035  2048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:48.895  8142  8142 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 15:17:48.898  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 15:17:48.899  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 15:17:48.900  8142  8142 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-05 15:17:48.901  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 15:17:48.903  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 15:17:48.904  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 15:17:48.905  6877  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 15:17:48.906  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:48.906  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:48.906  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:48.906  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:48.906  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.906  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 15:17:48.906  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 15:17:48.906  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1388a1d0 removed from the list
08-05 15:17:48.906  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:48.906  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@295a75c9 removed from the list
08-05 15:17:48.906  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:48.906  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.907  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.907  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.909  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:48.909  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 15:17:48.909  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:48.909  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@295a75c9 not in the list
08-05 15:17:48.909  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.909  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.910  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:48.910  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:48.910  6877  6943 D BluetoothLeScanner: could not find callback wrapper
08-05 15:17:48.910  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 15:17:48.910  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:48.910  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 15:17:48.911  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@159e0afc removed from the list
08-05 15:17:48.911  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:48.911  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.911  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.911  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 15:17:48.911  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10034fef removed from the list
08-05 15:17:48.912  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 15:17:48.912  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cdefc0b added. We now have 2 listener(s)
08-05 15:17:48.912  1035  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:48.915  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 15:17:48.915  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 15:17:48.915  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 15:17:48.915  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:48.915  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@373edae8 added. We now have 9 listener(s)
08-05 15:17:48.915  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 15:17:48.915  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 15:17:48.918  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 15:17:48.921  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:48.921  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:48.922  8250  8250 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 15:17:48.923  6877  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 15:17:48.923  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:48.923  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:48.923  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:48.923  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:48.923  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:48.923  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 15:17:48.923  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 15:17:48.924  8250  8250 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 15:17:48.924  8250  8250 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 15:17:48.924  6877  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:48.924  6877  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 15:17:48.925  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 15:17:48.925  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23236fa6 added. We now have 3 listener(s)
08-05 15:17:48.925  1035  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:48.926  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:48.928  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 15:17:48.928  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 15:17:48.928  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 15:17:48.928  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:48.928  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27f4de7 added. We now have 10 listener(s)
08-05 15:17:48.928  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 15:17:48.928  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 15:17:48.928  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 15:17:48.928  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 15:17:48.928  6877  6943 I org.th,aliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 15:17:48.928  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 15:17:48.930  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:48.931  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:48.932  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 15:17:48.932  1035  2048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 15:17:48.936  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 15:17:48.937  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 15:17:48.938  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 15:17:48.939  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 15:17:48.940  6877  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 15:17:48.942  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:48.942  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:48.942  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:48.942  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:48.942  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.942  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 15:17:48.942  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-05 15:17:48.942  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cdefc0b removed from the list
08-05 15:17:48.942  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:48.942  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@373edae8 removed from the list
08-05 15:17:48.942  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:48.942  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.943  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.943  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.944  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:48.944  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:48.944  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:48.944  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@373edae8 not in the list
08-05 15:17:48.944  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.944  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.945  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 15:17:48.945  6877  6943 D BluetoothLeScanner: could not find callback wrapper
08-05 15:17:48.946  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 15:17:48.946  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:48.946  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:48.946  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27f4de7 removed from the list
08-05 15:17:48.946  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:48.946  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.946  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.946  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 15:17:48.946  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23236fa6 removed from the list
08-05 15:17:48.947  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 15:17:48.947  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3206e032 added. We now have 2 listener(s)
08-05 15:17:48.947  1035  1781 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:48.950  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 15:17:48.950  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 15:17:48.950  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 15:17:48.951  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:48.951  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3de8e183 added. We now have 9 listener(s)
08-05 15:17:48.951  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 15:17:48.951  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 15:17:48.953  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 15:17:48.957  6877  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 15:17:48.957  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:48.957  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:48.957  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:48.957  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:48.957  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:48.957  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 15:17:48.957  6877  6943 V io.jxcore.node.ConnectivityMonitor:     - active network t,ype is Wi-Fi: true
,08-05 15:17:48.961  6877  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 15:17:48.961  6877  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 15:17:48.961  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 15:17:48.961  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aef6339 added. We now have 3 listener(s)
08-05 15:17:48.961  1035  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 15:17:48.963  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:48.964  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 15:17:48.965  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 15:17:48.965  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 15:17:48.965  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 15:17:48.965  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3ecd7e added. We now have 10 listener(s)
08-05 15:17:48.965  6877  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 15:17:48.966  6877  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 15:17:48.966  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:48.966  6877  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 15:17:48.966  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:48.966  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 15:17:48.966  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 15:17:48.966  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 15:17:48.966  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3206e032 removed from the list
08-05 15:17:48.966  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:48.966  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3de8e183 removed from the list
08-05 15:17:48.967  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 15:17:48.967  6877  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-05 15:17:48.967  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.970  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.970  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.970  8142  8142 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 15:17:48.971  8142  8142 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-05 15:17:48.971  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:48.971  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:48.971  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:48.971  6877  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3de8e183 not in the list
08-05 15:17:48.971  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.971  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 15:17:48.972  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 15:17:48.972  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 15:17:48.973  6877  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 15:17:48.973  6877  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3ecd7e removed from the list
08-05 15:17:48.973  6877  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 15:17:48.973  6877  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 15:17:48.973  6877  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 15:17:48.973  6877  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 15:17:48.973  6877  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aef6339 removed from the list
08-05 15:17:48.974  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-05 15:17:48.974  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-05 15:17:48.975  6961  6961 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 15:17:48.975  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-05 15:17:48.975  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 15:17:48.975  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 15:17:48.975  6877  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-05 15:17:48.981  6961  6961 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 15:17:48.989  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 15:17:48.989  6877  8290 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 926, name: My test thread name)
08-05 15:17:48.989  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 15:17:48.989  6877  8290 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 926, thread name: My test thread name)
08-05 15:17:48.990  6877  8290 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 926, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 15:17:48.990  8250  8250 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-05 15:17:48.991  8250  8250 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-05 15:17:48.991  8250  8250 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 15:17:48.993  6877  8291 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 928, name: My test thread name)
08-05 15:17:48.993  6877  8291 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 928, thread name: My test thread name)
08-05 15:17:48.993  6877  8291 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 928, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 15:17:48.997  6877  6943 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-05 15:17:48.997  6877  6943 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-05 15:17:48.997  6877  6943 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-05 15:17:48.997  6877  6943 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-05 15:17:48.997  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:48.997  6877  6943 D com.test.thalitest.ThaliTestRunner: Total duration: 23892 ms
08-05 15:17:48.998  6877  6943 I jxcore-log: Total number of executed tests:  80
08-05 15:17:48.998  6877  6943 I jxcore-log: 
08-05 15:17:48.999  6877  6943 I jxcore-log: Number of passed tests:  80
08-05 15:17:48.999  6877  6943 I jxcore-log: 
08-05 15:17:48.999  6877  6943 I jxcore-log: Number of failed tests:  0
08-05 15:17:48.999  6877  6943 I jxcore-log: 
08-05 15:17:48.999  6877  6943 I jxcore-log: Number of ignored tests:  0
08-05 15:17:48.999  6877  6943 I jxcore-log: 
08-05 15:17:48.999  6877  6943 I jxcore-log: Total duration:  23892
08-05 15:17:48.999  6877  6943 I jxcore-log: 
08-05 15:17:49.004  6877  6943 I jxcore-log: Unit Test app is loaded
08-05 15:17:49.004  6877  6943 I jxcore-log: 
08-05 15:17:49.005  8250  8250 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 15:17:49.007  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 15:17:49.008  8250  8250 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-05 15:17:49.014  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 15:17:49.014  6877  6943 I jxcore-log: 
08-05 15:17:49.020  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 15:17:49.020  6877  6943 I jxcore-log: 
,08-05 15:17:49.022  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 15:17:49.022  6877  6943 I jxcore-log: 
08-05 15:17:49.024  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 15:17:49.024  6877  6943 I jxcore-log: 
08-05 15:17:49.025  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 15:17:49.025  6877  6943 I jxcore-log: 
08-05 15:17:49.025  6877  6877 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-05 15:17:49.027  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 15:17:49.027  6877  6943 I jxcore-log: 
08-05 15:17:49.031  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 15:17:49.031  6877  6943 I jxcore-log: 
08-05 15:17:49.034  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 15:17:49.034  6877  6943 I jxcore-log: 
,08-05 15:17:49.035  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 15:17:49.035  6877  6943 I jxcore-log: 
08-05 15:17:49.036  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 15:17:49.036  6877  6943 I jxcore-log: 
08-05 15:17:49.037  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 15:17:49.037  6877  6943 I jxcore-log: 
08-05 15:17:49.039  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 15:17:49.039  6877  6943 I jxcore-log: 
08-05 15:17:49.041  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 15:17:49.041  6877  6943 I jxcore-log: 
08-05 15:17:49.042  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 15:17:49.042  6877  6943 I jxcore-log: 
08-05 15:17:49.043  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 15:17:49.043  6877  6943 I jxcore-log: 
08-05 15:17:49.044  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 15:17:49.044  6877  6943 I jxcore-log: 
08-05 15:17:49.044  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 15:17:49.044  6877  6943 I jxcore-log: 
08-05 15:17:49.045  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 15:17:49.045  6877  6943 I jxcore-log: 
08-05 15:17:49.046  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 15:17:49.046  6877  6943 I jxcore-log: 
,08-05 15:17:49.047  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 15:17:49.047  6877  6943 I jxcore-log: 
,08-05 15:17:49.048  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 15:17:49.048  6877  6943 I jxcore-log: 
08-05 15:17:49.049  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 15:17:49.049  6877  6943 I jxcore-log: 
08-05 15:17:49.050  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 15:17:49.050  6877  6943 I jxcore-log: 
08-05 15:17:49.051  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 15:17:49.051  6877  6943 I jxcore-log: 
,08-05 15:17:49.052  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 15:17:49.052  6877  6943 I jxcore-log: 
08-05 15:17:49.053  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 15:17:49.053  6877  6943 I jxcore-log: 
,08-05 15:17:49.054  8250  8250 D LgDataFeature: LgDataFeature() Constructor: none
08-05 15:17:49.054  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 15:17:49.054  6877  6943 I jxcore-log: 
08-05 15:17:49.054  8250  8250 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 15:17:49.055  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 15:17:49.055  6877  6943 I jxcore-log: 
08-05 15:17:49.056  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 15:17:49.056  6877  6943 I jxcore-log: 
,08-05 15:17:49.059  6877  6943 I jxcore-log: My device name is: LGE-LG-D855
08-05 15:17:49.059  6877  6943 I jxcore-log: 
08-05 15:17:49.060  6877  6943 I jxcore-log: WARN testUtils: myNameCallback not set!
08-05 15:17:49.060  6877  6943 I jxcore-log: 
08-05 15:17:49.061  8250  8250 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-05 15:17:49.062  8250  8250 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-05 15:17:49.062  8250  8250 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-05 15:17:49.062  8250  8250 V SoundPool: doLoad: loading sample sampleID=1
08-05 15:17:49.063  8250  8250 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-05 15:17:49.067  7831  7831 D UEI.SmartControl: QS Service created
08-05 15:17:49.071  8250  8294 V SoundPool: Start decode
08-05 15:17:49.071  8250  8294 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-05 15:17:49.072  8250  8250 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-05 15:17:49.073   323  2160 V MediaPlayerService: decode(23, 10857164, 17813)
08-05 15:17:49.073   323  2160 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-05 15:17:49.073   323  2160 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-05 15:17:49.073   323  2160 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-05 15:17:49.073   323  2160 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-05 15:17:49.073   323  2160 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-05 15:17:49.073   323  2160 V MediaPlayerService: player type = 3
08-05 15:17:49.073   323  2160 V AwesomePlayer: AwesomePlayer create()
08-05 15:17:49.074   323  2160 V AwesomePlayer: reset_l() 
08-05 15:17:49.075   323  2160 V AwesomePlayer: cancelPlayerEvents
08-05 15:17:49.075   323  2160 V AwesomePlayer: setAudioSink() 
08-05 15:17:49.075   323  2160 V AwesomePlayer: reset_l() 
08-05 15:17:49.075   323  2160 V AudioCache: notify(0xb1432300, 8, 0, 0)
08-05 15:17:49.075   323  2160 V AudioCache: ignored
08-05 15:17:49.075   323  2160 V AwesomePlayer: cancelPlayerEvents
08-05 15:17:49.075  8250  8250 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 15:17:49.075   323  2160 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-05 15:17:49.075  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 15:17:49.075   323  2160 V AwesomePlayer: setDataSource_l dataSource
08-05 15:17:49.075   323  2160 V LGParserOSAL: SniffLGParser start
08-05 15:17:49.075   323  2160 V LGParserOSAL: MainType:5, SubType=0
08-05 15:17:49.076   323  2160 V LGParserOSAL: #### check Mime : application/ogg
08-05 15:17:49.076   323  2160 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-05 15:17:49.076   323  2160 E MediaExtractor: Use LGExtractor :application/ogg 
08-05 15:17:49.081  7831  7831 I UEI.SmartControl: Service initServices...
08-05 15:17:49.081  7831  7831 D UEI.SmartControl: QS start get config
08-05 15:17:49.095  8250  8250 V LGMDMManager: Create singleton instance
,08-05 15:17:49.120   323  2160 V LGParserOSAL: supported mime: application/ogg
08-05 15:17:49.120   323  2160 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-05 15:17:49.120   323  2160 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-05 15:17:49.120   323  2160 V AwesomePlayer: mBitrate = -1 bits/sec
08-05 15:17:49.120   323  2160 V AwesomePlayer: AudioTrack Setting
08-05 15:17:49.120   323  2160 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-05 15:17:49.120   323  2160 V AwesomePlayer: setAudioSource() 
08-05 15:17:49.120   323  2160 V MediaPlayerService: prepare
08-05 15:17:49.120   323  2160 V AwesomePlayer: prepareAsync_l() 
08-05 15:17:49.120   323  2160 V MediaPlayerService: wait for prepare
08-05 15:17:49.120   323  8295 V AwesomePlayer: onPrepareAsyncEvent() 
08-05 15:17:49.120   323  8295 V AwesomePlayer: initAudioDecoder() 
08-05 15:17:49.120   323  8295 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 15:17:49.120   323  8295 V AudioSystem: isOffloadSupported()
08-05 15:17:49.120   323  8295 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 15:17:49.120   323  8295 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 15:17:49.120   323  8295 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 15:17:49.120   323  8295 V AwesomePlayer: getUseOffload() = 0 
08-05 15:17:49.120   323  8295 V OMXCodec: OMXCodec::Create
08-05 15:17:49.120   323  8295 V OMXCodec: findMatchingCodecs()
08-05 15:17:49.120   323  8295 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-05 15:17:49.120   323  8295 V OMXCodec: matchingCodecs.size()=1
08-05 15:17:49.120   323  8295 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-05 15:17:49.121   323  8295 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-05 15:17:49.121   323  8295 V LGCodecAdapter: LG Codec Adapter start
08-05 15:17:49.121   323  8295 V OMXCodec: OMXCodec Createtor
08-05 15:17:49.121   323  8295 V OMXCodec: setComponentRole
08-05 15:17:49.121   323  8295 V OMXCodec: configureCodec protected=0
08-05 15:17:49.122   323  8295 V LGCodecAdapter: called getLGCodecSpecificData
08-05 15:17:49.122   323  8295 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-05 15:17:49.122   323  8295 V LGCodecOSAL: Called LGconfigureCodecMETA
08-05 15:17:49.122   323  8295 V LGCodecOSAL: Called LGconfigureCodecMSG
08-05 15:17:49.122   323  8295 V LGCodecOSAL: Not support LGCodec
08-05 15:17:49.122   323  8295 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 15:17:49.122   323  8295 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-05 15:17:49.122   323  8295 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-05 15:17:49.122   323  8295 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-05 15:17:49.122   323  8295 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 15:17:49.122   323  8295 V AudioSystem: isOffloadSupported()
08-05 15:17:49.122   323  8295 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 15:17:49.122   323  8295 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 15:17:49.122   323  8295 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-05 15:17:49.122   323  8295 V OMXCodec: init()
08-05 15:17:49.122   323  8295 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-05 15:17:49.122   323  8295 V OMXCodec: allocateBuffers
08-05 15:17:49.122   323  8295 V OMXCodec: allocateBuffersOnPort portIndex=0
08-05 15:17:49.122   323  8295 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-05 15:17:49.122   323  8295 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76a0 on input port
08-05 15:17:49.122   323  8295 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
08-05 15:17:49.122   323  8295 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
08-05 15:17:49.122   323  8295 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-05 15:17:49.122   323  8295 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 15:17:49.122   323  8295 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 15:17:49.122   323  8295 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on output port
08-05 15:17:49.122   323  8295 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
08-05 15:17:49.122   323  8295 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
08-05 15:17:49.122   323  8295 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-05 15:17:49.122   323  8295 V OMXCodec: init() mAsyncCompletion wait!!! 
08-05 15:17:49.131   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 15:17:49.131   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 15:17:49.131   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-05 15:17:49.131   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-05 15:17:49.131   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-05 15:17:49.131   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-05 15:17:49.131   323  8295 V OMXCodec: init() mAsyncCompletion wait free! 
08-05 15:17:49.131   323  8295 V AwesomePlayer: finishAsyncPrepare_l() 
08-05 15:17:49.132   323  8295 V AudioCache: notify(0xb1432300, 5, 0, 0)
08-05 15:17:49.132   323  8295 V AudioCache: ignored
08-05 15:17:49.132   323  8295 V AudioCache: notify(0xb1432300, 1, 0, 0)
08-05 15:17:49.132   323  8295 V AudioCache: prepared
08-05 15:17:49.132   323  2160 V AudioCache: wait - success
08-05 15:17:49.132   323  2160 V MediaPlayerService: start
08-05 15:17:49.132   323  2160 V AwesomePlayer: play_l() 
08-05 15:17:49.132   323  2160 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-05 15:17:49.132   323  2160 V AwesomePlayer: createAudioPlayer_l
08-05 15:17:49.132   323  2160 V AwesomePlayer: seekAudioIfNecessary_l() 
,08-05 15:17:49.132   323  2160 V AwesomePlayer: startAudioPlayer_l() 
08-05 15:17:49.132   323  2160 D AudioPlayer: start of Playback, useOffload 0
08-05 15:17:49.132   323  2160 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 15:17:49.132   323  2160 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 15:17:49.134   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-05 15:17:49.134   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-05 15:17:49.134   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-05 15:17:49.134   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-05 15:17:49.134   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-05 15:17:49.134   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,08-05 15:17:49.142   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884288
,08-05 15:17:49.142   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 15:17:49.142   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884448
08-05 15:17:49.142   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 15:17:49.142   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884528
08-05 15:17:49.142   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 15:17:49.142   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-05 15:17:49.142   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 15:17:49.142   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-05 15:17:49.142   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 15:17:49.143   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-05 15:17:49.143   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-05 15:17:49.143   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-05 15:17:49.143   323  8297 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 15:17:49.143   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 15:17:49.143   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
08-05 15:17:49.143   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
08-05 15:17:49.143   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on output port
08-05 15:17:49.143   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c11a0 on output port
08-05 15:17:49.143   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-05 15:17:49.143   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-05 15:17:49.143   323  2160 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-05 15:17:49.143   323  2160 V AudioCache: notify(0xb1432300, 6, 0, 0)
08-05 15:17:49.143   323  2160 V AudioCache: ignored
08-05 15:17:49.144   323  2160 V MediaPlayerService: wait for playback complete
08-05 15:17:49.144   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.144   323  8298 V AudioCache: memcpy(0xac200000, 0xb0409000, 4096)
08-05 15:17:49.145   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.145   323  8298 V AudioCache: memcpy(0xac201000, 0xb0409000, 4096)
08-05 15:17:49.145   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.145   323  8298 V AudioCache: memcpy(0xac202000, 0xb0409000, 4096)
08-05 15:17:49.145   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.146   323  8298 V AudioCache: memcpy(0xac203000, 0xb0409000, 4096)
,08-05 15:17:49.146   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.146   323  8298 V AudioCache: memcpy(0xac204000, 0xb0409000, 4096)
08-05 15:17:49.147   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.147   323  8298 V AudioCache: memcpy(0xac205000, 0xb0409000, 4096)
08-05 15:17:49.147   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.147   323  8298 V AudioCache: memcpy(0xac206000, 0xb0409000, 4096)
08-05 15:17:49.147   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.147   323  8298 V AudioCache: memcpy(0xac207000, 0xb0409000, 4096)
08-05 15:17:49.147   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.147   323  8298 V AudioCache: memcpy(0xac208000, 0xb0409000, 4096)
,08-05 15:17:49.148   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.148   323  8298 V AudioCache: memcpy(0xac209000, 0xb0409000, 4096)
08-05 15:17:49.148   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.148   323  8298 V AudioCache: memcpy(0xac20a000, 0xb0409000, 4096)
08-05 15:17:49.148   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.148   323  8298 V AudioCache: memcpy(0xac20b000, 0xb0409000, 4096)
08-05 15:17:49.148   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.148   323  8298 V AudioCache: memcpy(0xac20c000, 0xb0409000, 4096)
08-05 15:17:49.149   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.149   323  8298 V AudioCache: memcpy(0xac20d000, 0xb0409000, 4096)
08-05 15:17:49.149   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.149   323  8298 V AudioCache: memcpy(0xac20e000, 0xb0409000, 4096)
08-05 15:17:49.149   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.149   323  8298 V AudioCache: memcpy(0xac20f000, 0xb0409000, 4096)
08-05 15:17:49.150   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.150   323  8298 V AudioCache: memcpy(0xac210000, 0xb0409000, 4096)
08-05 15:17:49.150   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.150   323  8298 V AudioCache: memcpy(0xac211000, 0xb0409000, 4096)
08-05 15:17:49.151   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.151   323  8298 V AudioCache: memcpy(0xac212000, 0xb0409000, 4096)
08-05 15:17:49.151   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.151   323  8298 V AudioCache: memcpy(0xac213000, 0xb0409000, 4096)
08-05 15:17:49.152   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.152   323  8298 V AudioCache: memcpy(0xac214000, 0xb0409000, 4096)
08-05 15:17:49.152   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.152   323  8298 V AudioCache: memcpy(0xac215000, 0xb0409000, 4096)
08-05 15:17:49.153   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.153   323  8298 V AudioCache: memcpy(0xac216000, 0xb0409000, 4096)
08-05 15:17:49.153   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.153   323  8298 V AudioCache: memcpy(0xac217000, 0xb0409000, 4096)
08-05 15:17:49.154   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.154   323  8298 V AudioCache: memcpy(0xac218000, 0xb0409000, 4096)
08-05 15:17:49.154   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.154   323  8298 V AudioCache: memcpy(0xac219000, 0xb0409000, 4096)
08-05 15:17:49.154   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.154   323  8298 V AudioCache: memcpy(0xac21a000, 0xb0409000, 4096)
08-05 15:17:49.155   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.155   323  8298 V AudioCache: memcpy(0xac21b000, 0xb0409000, 4096)
08-05 15:17:49.155   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.155   323  8298 V AudioCache: memcpy(0xac21c000, 0xb0409000, 4096)
08-05 15:17:49.156   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.156   323  8298 V AudioCache: memcpy(0xac21d000, 0xb0409000, 4096)
08-05 15:17:49.156   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.156   323  8298 V AudioCache: memcpy(0xac21e000, 0xb0409000, 4096)
08-05 15:17:49.157   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.157   323  8298 V AudioCache: memcpy(0xac21f000, 0xb0409000, 4096)
08-05 15:17:49.157   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.157   323  8298 V AudioCache: memcpy(0xac220000, 0xb0409000, 4096)
08-05 15:17:49.158   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.158   323  8298 V AudioCache: memcpy(0xac221000, 0xb0409000, 4096)
08-05 15:17:49.158   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.158   323  8298 V AudioCache: memcpy(0xac222000, 0xb0409000, 4096)
08-05 15:17:49.158   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.158   323  8298 V AudioCache: mem,cpy(0xac223000, 0xb0409000, 4096)
08-05 15:17:49.159   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.159   323  8298 V AudioCache: memcpy(0xac224000, 0xb0409000, 4096)
08-05 15:17:49.159   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.159   323  8298 V AudioCache: memcpy(0xac225000, 0xb0409000, 4096)
08-05 15:17:49.160   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.160   323  8298 V AudioCache: memcpy(0xac226000, 0xb0409000, 4096)
08-05 15:17:49.160   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.160   323  8298 V AudioCache: memcpy(0xac227000, 0xb0409000, 4096)
08-05 15:17:49.161   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.161   323  8298 V AudioCache: memcpy(0xac228000, 0xb0409000, 4096)
08-05 15:17:49.161   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.161   323  8298 V AudioCache: memcpy(0xac229000, 0xb0409000, 4096)
08-05 15:17:49.162   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.162   323  8298 V AudioCache: memcpy(0xac22a000, 0xb0409000, 4096)
08-05 15:17:49.162   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.162   323  8298 V AudioCache: memcpy(0xac22b000, 0xb0409000, 4096)
,08-05 15:17:49.163   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.163   323  8298 V AudioCache: memcpy(0xac22c000, 0xb0409000, 4096)
08-05 15:17:49.163   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.163   323  8298 V AudioCache: memcpy(0xac22d000, 0xb0409000, 4096)
08-05 15:17:49.163   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.163   323  8298 V AudioCache: memcpy(0xac22e000, 0xb0409000, 4096)
08-05 15:17:49.164   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.164   323  8298 V AudioCache: memcpy(0xac22f000, 0xb0409000, 4096)
08-05 15:17:49.164   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.164   323  8298 V AudioCache: memcpy(0xac230000, 0xb0409000, 4096)
08-05 15:17:49.164   323  8298 V AudioCache: write(0xb0409000, 4096)
08-05 15:17:49.164   323  8298 V AudioCache: memcpy(0xac231000, 0xb0409000, 4096)
08-05 15:17:49.164   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-05 15:17:49.164   323  8298 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-05 15:17:49.164   323  8298 V AwesomePlayer: postAudioEOS() 
08-05 15:17:49.164   323  8298 V AudioCache: write(0xb0409000, 280)
08-05 15:17:49.164   323  8298 V AudioCache: memcpy(0xac232000, 0xb0409000, 280)
08-05 15:17:49.166   323  8295 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-05 15:17:49.166   323  8295 V AwesomePlayer: onStreamDone
08-05 15:17:49.166   323  8295 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-05 15:17:49.166   323  8295 V AudioCache: notify(0xb1432300, 2, 0, 0)
08-05 15:17:49.166   323  8295 V AudioCache: playback complete
08-05 15:17:49.166   323  8295 V AwesomePlayer: pause_l() 
08-05 15:17:49.166   323  8295 V AudioCache: notify(0xb1432300, 7, 0, 0)
08-05 15:17:49.166   323  8295 V AudioCache: ignored
08-05 15:17:49.166   323  8295 V AwesomePlayer: cancelPlayerEvents
08-05 15:17:49.166   323  8295 D AudioPlayer: Pause Playback at 1068125
08-05 15:17:49.166   323  2160 V AudioCache: wait - success
08-05 15:17:49.166   323  2160 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-05 15:17:49.166   323  2160 V AwesomePlayer: reset_l() 
08-05 15:17:49.166   323  2160 V AudioCache: notify(0xb1432300, 8, 0, 0)
08-05 15:17:49.166   323  2160 V AudioCache: ignored
08-05 15:17:49.166   323  2160 V AwesomePlayer: cancelPlayerEvents
08-05 15:17:49.166   323  2160 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-05 15:17:49.166   323  2160 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-05 15:17:49.166   323  2160 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-05 15:17:49.166   323  2160 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-05 15:17:49.166   323  2160 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76a0 on port 0
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,,bufIndex=0
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c11a0 on port 1
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 1
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 1
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-05 15:17:49.172   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 1
08-05 15:17:49.173   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 15:17:49.173   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-05 15:17:49.173   323  2160 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 15:17:49.173   323  2160 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 15:17:49.173   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-05 15:17:49.173   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-05 15:17:49.173   323  8297 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-05 15:17:49.173   323  2160 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 15:17:49.173   323  2160 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-05 15:17:49.173   323  2160 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-05 15:17:49.173  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 15:17:49.173   323  2160 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-05 15:17:49.174   323  2160 D AudioPlayer: AudioPlayer releasing audio source
08-05 15:17:49.174   323  2160 D AudioPlayer: AudioPlayer done releasing audio source
08-05 15:17:49.174   323  2160 V AwesomePlayer: reset_l() 
08-05 15:17:49.174   323  2160 V AwesomePlayer: cancelPlayerEvents
,08-05 15:17:49.174   323  2160 V AwesomePlayer: ~AwesomePlayer call
08-05 15:17:49.174   323  2160 V AwesomePlayer: reset_l() 
08-05 15:17:49.174   323  2160 V AwesomePlayer: cancelPlayerEvents
08-05 15:17:49.174  8250  8294 V SoundPool: close(31)
08-05 15:17:49.174  8250  8294 V SoundPool: pointer = 0xa0000000, size = 205080, sampleRate = 48000, numChannels = 2
08-05 15:17:49.174  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-05 15:17:49.176  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8013
08-05 15:17:49.178  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:49.179  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:49.184  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:49.185  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:49.186  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:49.188  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:49.190  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:49.191  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 15:17:49.193  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 15:17:49.333  7831  7831 I UEI.SmartControl: Supports setup maps: true
,08-05 15:17:49.335  7831  7831 D UEI.SmartControl: QS start statue = true Error code = 0
,08-05 15:17:49.335  7831  7831 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 15:17:49.336  7831  7831 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 15:17:49.336  7831  7831 I UEI.SmartControl: ### init IR Blaster...
,08-05 15:17:49.339  7831  7831 D serial_port: Configuring serial port
08-05 15:17:49.339  7831  7831 E UEI.SmartControl: UEIBLaster setting for 616
08-05 15:17:49.340  7831  7831 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 15:17:49.340  7831  7831 I UEI.SmartControl: configuring settings for MAXQ616
,08-05 15:17:49.340  7831  7831 I UEI.SmartControl: Get version...
08-05 15:17:49.358  7831  8299 D UEI.SmartControl: serial port data available: 21
,08-05 15:17:49.384  7831  7831 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-05 15:17:49.384  7831  7831 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 15:17:49.385  7831  7831 I UEI.SmartControl: QS saving settings...
08-05 15:17:49.386  7831  7831 D UEI.SmartControl: IR Blaster version: 25672567
,08-05 15:17:49.403  7831  8299 D UEI.SmartControl: serial port data available: 4
,08-05 15:17:49.434  7831  8302 I UEI.SmartControl: Device manager: loading config....
,08-05 15:17:49.435  7831  8302 D UEI.SmartControl: ----------- loading internal config...
08-05 15:17:49.435  7831  7831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-05 15:17:49.438  7831  7831 E UEI.SmartControl: Services init done
08-05 15:17:49.438  7831  7831 D UEI.SmartControl: QS Service init finished
08-05 15:17:49.444  7831  7831 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 15:17:49.444  7831  7831 D UEI.SmartControl: QS Service version code: 201091
08-05 15:17:49.445  7831  7831 D UEI.SmartControl: Service requested: Control
08-05 15:17:49.448  7831  8302 E UEI.SmartControl: Loading SETTINGS...
,08-05 15:17:49.450  7831  7831 D UEI.SmartControl: Request IControl service: devices are loaded...
08-05 15:17:49.459  8250  8250 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-05 15:17:49.461  7831  7831 D UEI.SmartControl: Internal service binding...
08-05 15:17:49.461  7831  7847 I UEI.SmartControl: ------ IControl API: 11
08-05 15:17:49.461  7831  7847 D UEI.SmartControl: File observer start...
08-05 15:17:49.463  7831  7847 E UEI.SmartControl: IR Port is disabled: false
08-05 15:17:49.463  7831  7847 D UEI.SmartControl: Starting file observer...
08-05 15:17:49.465  7831  7847 I UEI.SmartControl: Registering callback...
08-05 15:17:49.467  7831  7846 I UEI.SmartControl: ------ IControl API: 19
08-05 15:17:49.468  7831  8302 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 15:17:49.469  7831  7846 I UEI.SmartControl: Registering Services Ready callback...
,08-05 15:17:49.475  1035  1539 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:49.476  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:49.476  1035  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:49.477  1035  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:49.477  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:49.478  1035  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 15:17:49.478  1035  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-05 15:17:49.478  1035  1546 D ConnectivityService: identical MTU - not setting
08-05 15:17:49.478  1035  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 15:17:49.478  1035  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-05 15:17:49.478  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 15:17:49.479  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:49.479  1035  1546 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 15:17:49.480  1604  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-05 15:17:49.494  7831  8301 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-05 15:17:49.495  8250  8265 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-05 15:17:49.495  7831  8301 D UEI.SmartControl: -----service ready thread exits
08-05 15:17:49.496  8250  8292 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-05 15:17:49.496  8250  8292 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-05 15:17:49.498  8250  8250 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-05 15:17:49.498  8250  8250 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-05 15:17:49.498  7831  7847 I UEI.SmartControl: ------ IControl API: 8
08-05 15:17:49.500  8250  8250 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-05 15:17:49.501  8250  8250 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-05 15:17:49.501  8250  8250 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-05 15:17:49.501  8250  8250 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-05 15:17:49.502  8250  8250 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-05 15:17:49.503  8250  8250 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-05 15:17:49.504  8250  8250 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-05 15:17:49.507  8250  8250 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 15:17:49.508  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-05 15:17:49.509  8250  8250 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 15:17:49.509  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 15:17:49.510  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 15:17:49.511  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-05 15:17:49.511  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-05 15:17:49.512  8250  8250 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470403069512]
08-05 15:17:49.514  8250  8250 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-05 15:17:49.516  1035  1576 I ActivityManager: Killing 7381:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-05 15:17:49.541  8250  8307 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-05 15:17:49.615  1035  1644 W libprocessgroup: failed to open /acct/uid_10005/pid_7381/cgroup.procs: No such file or directory
,08-05 15:17:49.631  8250  8250 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-05 15:17:49.635  8250  8250 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 15:17:49.635  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-05 15:17:49.636  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-05 15:17:49.637  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-05 15:17:49.638  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-05 15:17:49.638  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-05 15:17:49.657  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-05 15:17:50.541  1035  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=56.5, 0.0, 0.0  rx=50.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1524255309] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 15:17:50.542  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=56.5, 0.0, 0.0  rx=50.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1524255310] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 15:17:50.542  1035  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 15:17:50.563  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 15:17:50.589  1035  1541 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-05 15:17:50.612  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 15:17:50.618  1035  1111 D Tethering: MasterInitialState.processMessage what=3
,08-05 15:17:50.626  6877  6877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 15:17:50.626  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 15:17:50.626  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 15:17:50.626  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 15:17:50.626  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 15:17:50.626  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:50.626  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 15:17:50.626  6877  6877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 15:17:50.628  6877  6877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 15:17:50.630  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:50.631  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-05 15:17:50.634  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 15:17:50.640  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 15:17:50.646  8185  8239 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-05 15:17:50.652  2232  2232 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:50.663  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 15:17:50.663  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:50.663  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 15:17:50.663  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 15:17:50.664  7156  7156 I AppUp4:CustModeStarterReceiver: onReceive
08-05 15:17:50.666  7156  7156 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2a9df96f
08-05 15:17:50.667  7156  7156 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 15:17:50.667  7156  7156 D AppUp4:CustFacade: isPhone : true
08-05 15:17:50.667  7156  7156 D AppUp4:CustModeStarterReceiver: begin check event
08-05 15:17:50.667  7156  7156 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 15:17:50.670  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:50.670  4785  4785 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 15:17:50.671  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 15:17:50.676  4785  4785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 15:17:50.678  3473  3473 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:50.681  3473  3473 V DownloadManager: DownloadService onCreate
08-05 15:17:50.682  3473  8323 I DownloadManager: in removeSpuriousFiles
08-05 15:17:50.682  3473  8323 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-05 15:17:50.683  3473  8323 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@34c73f99 on behalf of 3473
08-05 15:17:50.683  3473  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-05 15:17:50.683  3473  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-05 15:17:50.683  3473  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-05 15:17:50.683  3473  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-05 15:17:50.683  3473  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-05 15:17:50.683  3473  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-05 15:17:50.683  3473  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-05 15:17:50.683  3473  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-05 15:17:50.683  3473  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-05 15:17:50.683  3473  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-05 15:17:50.683  3473  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,08-05 15:17:50.684  3473  8323 I DownloadManager: in trimDatabase
08-05 15:17:50.684  3473  8323 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-05 15:17:50.686  3473  8323 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@378ce25e on behalf of 3473
08-05 15:17:50.686  4785  8325 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 15:17:50.688  4785  8325 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-05 15:17:50.691  4785  8327 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:50.691  4785  8327 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 15:17:50.708  1035  1887 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8329 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-05 15:17:50.712  3473  3473 V DownloadManager: DownloadService onStartCommand
,08-05 15:17:50.713  3473  8324 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-05 15:17:50.715  3473  8324 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2bc33c55 on behalf of 3473
08-05 15:17:50.719  4785  8325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-05 15:17:50.720  3473  8324 V DownloadManager: processing inserted download 1
08-05 15:17:50.721  3473  8324 V DownloadManager: processing inserted download 4
08-05 15:17:50.721  4785  4785 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-05 15:17:50.722  4785  4785 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-05 15:17:50.722  4785  4785 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-05 15:17:50.722  3473  8324 V DownloadManager: processing inserted download 7
08-05 15:17:50.723  4785  4785 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-05 15:17:50.723  3473  8324 V DownloadManager: processing inserted download 8
08-05 15:17:50.724  3473  8324 V DownloadManager: processing inserted download 9
08-05 15:17:50.726  4785  4785 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-05 15:17:50.726  3473  8324 V DownloadManager: processing inserted download 10
08-05 15:17:50.727  3473  8324 V DownloadManager: processing inserted download 11
08-05 15:17:50.728  3473  8324 V DownloadManager: processing inserted download 12
08-05 15:17:50.729  3473  8324 V DownloadManager: processing inserted download 13
08-05 15:17:50.730  3473  8324 V DownloadManager: processing inserted download 14
08-05 15:17:50.731  3473  8324 V DownloadManager: processing inserted download 16
,08-05 15:17:50.737  3473  3473 V DownloadManager: DownloadService onDestroy
08-05 15:17:50.755  8329  8329 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 15:17:50.755  8329  8329 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 15:17:50.756  8329  8329 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 15:17:50.756  8329  8329 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-05 15:17:50.787  1035  2014 I art     : Explicit concurrent mark sweep GC freed 75805(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.774ms total 132.473ms
,08-05 15:17:50.790   318  8347 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 15:17:50.790   318  8347 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-05 15:17:50.804  8329  8329 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 15:17:50.811  8329  8329 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-05 15:17:50.830  8329  8329 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 15:17:50.838   318  8347 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-05 15:17:50.850  8329  8329 D LgDataFeature: LgDataFeature() Constructor: none
08-05 15:17:50.850  8329  8329 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 15:17:50.980  8329  8329 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 15:17:51.022  8329  8329 I HubEmail: JNI_OnLoad()
08-05 15:17:51.023  8329  8329 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 15:17:51.023  8329  8329 I HubEmail: registerNatives()
08-05 15:17:51.023  8329  8329 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 15:17:51.023  8329  8329 I HubEmail: registerNativeMethods()
08-05 15:17:51.023  8329  8329 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 15:17:51.023  8329  8329 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-05 15:17:51.035  8329  8357 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 15:17:51.050  3356  3356 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-05 15:17:51.050  3356  3356 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 15:17:51.050  3356  3356 I LgeMiscReceiver: networkInfo.isConnected() = true
08-05 15:17:51.050  3356  3356 D PhoneState: setPdpRejectCasuse : false
08-05 15:17:51.059   318  8360 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 15:17:51.059   318  8360 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-05 15:17:51.099  1035  1644 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8361 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-05 15:17:51.100   318  8360 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-05 15:17:51.179  8361  8361 D LgDataFeature: LgDataFeature() Constructor: none
08-05 15:17:51.179  8361  8361 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 15:17:51.182  8361  8361 D PhoneMonitor: Register our PhoneStateListener
08-05 15:17:51.187  2232  8355 D GCM     : Connected
08-05 15:17:51.188  8117  8356 V FormManager: There are no updated forms. The schedule will be deleted.
08-05 15:17:51.192  8361  8361 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 15:17:51.192  8117  8356 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,08-05 15:17:51.197  8361  8361 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-05 15:17:51.208  8361  8361 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-05 15:17:51.209  8361  8361 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-05 15:17:51.209  8361  8361 D TelephonyAutoProfiling: [parse] Load xml
08-05 15:17:51.211  8361  8361 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-05 15:17:51.211  8361  8361 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-05 15:17:51.211  8361  8361 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-05 15:17:51.211  8361  8361 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-05 15:17:51.211  8361  8361 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-05 15:17:51.211  8361  8361 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-05 15:17:51.211  8361  8361 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-05 15:17:51.211  8361  8361 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-05 15:17:51.211  8361  8361 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-05 15:17:51.211  8361  8361 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-05 15:17:51.211  8361  8361 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-05 15:17:51.211  8361  8361 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-05 15:17:51.211  8361  8361 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-05 15:17:51.211  8361  8361 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-05 15:17:51.211  8361  8361 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-05 15:17:51.211  8361  8361 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-05 15:17:51.211  8361  8361 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-05 15:17:51.215  8361  8361 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-05 15:17:51.236  1035  1050 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8380 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 15:17:51.237  1035  1050 I ActivityManager: Killing 7762:com.google.android.talk/u0a72 (adj 15): empty #17
,08-05 15:17:51.336  1035  1781 W libprocessgroup: failed to open /acct/uid_10072/pid_7762/cgroup.procs: No such file or directory
,08-05 15:17:51.354  1035  1959 I ActivityManager: Killing 7813:com.android.contacts/u0a19 (adj 15): empty #17
08-05 15:17:51.359  2232  8355 D GCM     : Message class com.google.e.a.a.q
,08-05 15:17:51.578  1035  1886 W libprocessgroup: failed to open /acct/uid_10019/pid_7813/cgroup.procs: No such file or directory
,08-05 15:17:51.662  1035  1978 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8399 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-05 15:17:51.663  1035  1978 I ActivityManager: Killing 7852:com.android.gallery3d/u0a27 (adj 15): empty #17
08-05 15:17:51.734  1816  8398 I CheckinService: active receiver: enabled
,08-05 15:17:51.762  1035  2013 W libprocessgroup: failed to open /acct/uid_10027/pid_7852/cgroup.procs: No such file or directory
08-05 15:17:51.765  1816  8398 I CheckinService: Preparing to send checkin request
08-05 15:17:51.765  1816  8398 I EventLogService: Accumulating logs since 1470403050538
08-05 15:17:51.801   318  8418 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 15:17:51.803   318  8418 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-05 15:17:51.832  1035  1940 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8419 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 15:17:51.833  1035  1940 I ActivityManager: Killing 7923:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-05 15:17:51.834   318  8418 D libc-netbsd: res_queryN name = www.google.com succeed
08-05 15:17:51.838   318  8430 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 15:17:51.839   318  8430 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-05 15:17:51.839   318  8430 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-05 15:17:51.841  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-05 15:17:51.841  6877  6943 I jxcore-log: 
08-05 15:17:51.924  1035  1542 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-05 15:17:51.935  1816  8398 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-05 15:17:51.939  1035  2013 W libprocessgroup: failed to open /acct/uid_10080/pid_7923/cgroup.procs: No such file or directory
,08-05 15:17:51.975  8419  8419 I art     : Almond Protected OAT
,08-05 15:17:52.036  8419  8419 D WeatherApplication: removeAccount
,08-05 15:17:52.037  8419  8419 D WeatherApplication: Account.length = 0
08-05 15:17:52.038  8419  8419 E WeatherApplication: OPERATOR:OPEN
08-05 15:17:52.042  8419  8419 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:52
08-05 15:17:52.045  8419  8419 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 15:17:52.045  8419  8419 D Weather.Utils: 2 : All the weather widget is gone.
08-05 15:17:52.046  8419  8419 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 15:17:52.049  8419  8419 D WeatherAncestor: connectivity changed - connection : true
,08-05 15:17:52.050  8419  8419 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-05 15:17:52.057  8419  8419 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 15:17:52.057  8419  8419 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 15:17:52.057  8419  8419 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-05 15:17:52.073  8419  8419 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 15:17:52.073  8419  8419 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:52
,08-05 15:17:52.084  1035  1978 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8439 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-05 15:17:52.147  1035  1977 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8456 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 15:17:52.148  1035  1977 I ActivityManager: Killing 7871:com.android.vending/u0a44 (adj 15): empty #17
,08-05 15:17:52.300  1035  1887 W libprocessgroup: failed to open /acct/uid_10044/pid_7871/cgroup.procs: No such file or directory
,08-05 15:17:52.329  8439  8439 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-05 15:17:52.330  8439  8439 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-05 15:17:52.356  8439  8439 I MultiDex: VM with version 2.1.0 has multidex support
08-05 15:17:52.356  8439  8439 I MultiDex: install
08-05 15:17:52.356  8439  8439 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-05 15:17:52.366  8439  8439 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-05 15:17:52.420   278   381 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 15:17:52.420   278   381 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-05 15:17:52.420   278   381 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 15:17:52.421  8456  8475 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-05 15:17:52.426   278   381 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 15:17:52.426   278   381 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 15:17:52.426   278   381 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 15:17:52.426  8456  8475 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 15:17:52.458   278   381 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 15:17:52.458   278   381 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 15:17:52.458   278   381 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 15:17:52.459  8456  8477 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-05 15:17:52.483   278   381 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 15:17:52.483   278   381 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 15:17:52.483   278   381 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 15:17:52.485  8456  8477 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 15:17:52.498  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-05 15:17:52.498  6877  6943 I jxcore-log: 
,08-05 15:17:52.522  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-05 15:17:52.522  6877  6943 I jxcore-log: 
,08-05 15:17:52.632  8456  8456 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-05 15:17:52.638  8456  8456 I LibraryLoader: Loading: webviewchromium
08-05 15:17:52.641  8456  8456 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5915-5918)
08-05 15:17:52.641  8456  8456 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 15:17:52.648  8456  8456 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {249bdd6}
,08-05 15:17:52.651  8456  8456 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 15:17:52.652  8456  8456 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 15:17:52.669  8456  8456 I BrowserStartupController: Initializing chromium process, renderers=0
08-05 15:17:52.670  8456  8456 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 15:17:52.685  8456  8456 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-05 15:17:52.686  8456  8456 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-05 15:17:52.686  8456  8456 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-05 15:17:52.694   323  2159 V AudioPolicyService: registerClient() client 0xb558a380, uid 10093
08-05 15:17:52.695  8439  8454 D LgDataFeature: LgDataFeature() Constructor: none
08-05 15:17:52.695  8439  8454 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 15:17:52.695  8456  8499 W AudioManagerAndroid: Requires BLUETOOTH permission
08-05 15:17:52.706  8456  8456 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 15:17:52.706  8456  8456 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 15:17:52.706  8456  8456 I Adreno-EGL: Build Date: 12/12/14 금
08-05 15:17:52.706  8456  8456 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 15:17:52.706  8456  8456 I Adreno-EGL: Remote Branch: 
08-05 15:17:52.706  8456  8456 I Adreno-EGL: Local Patches: 
08-05 15:17:52.706  8456  8456 I Adreno-EGL: Reconstruct Branch: 
,08-05 15:17:52.785  8456  8456 I NSApplication: Starting up...
,08-05 15:17:52.816  1035  2051 I ActivityManager: Killing 7573:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-05 15:17:53.067  1035  1959 W libprocessgroup: failed to open /acct/uid_10037/pid_7573/cgroup.procs: No such file or directory
,08-05 15:17:53.103  2232  2232 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-05 15:17:53.114  2232  2232 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-05 15:17:53.114  2232  2232 D c       : Getting all permits...
08-05 15:17:53.114  2232  2232 D a       : Opening database...
08-05 15:17:53.118  2232  2232 D a       : Opening database auth.proximity.permit_store...
08-05 15:17:53.119  2232  2232 D a       : Closing database...
,08-05 15:17:53.165  8518  8518 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-05 15:17:53.246  8518  8518 I dex2oat : dex2oat took 80.584ms (threads: 4)
,08-05 15:17:53.262  8439  8454 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 15:17:53.262  8439  8454 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 15:17:53.262  8439  8454 I Adreno-EGL: Build Date: 12/12/14 금
08-05 15:17:53.262  8439  8454 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 15:17:53.262  8439  8454 I Adreno-EGL: Remote Branch: 
08-05 15:17:53.262  8439  8454 I Adreno-EGL: Local Patches: 
08-05 15:17:53.262  8439  8454 I Adreno-EGL: Reconstruct Branch: 
,08-05 15:17:53.379  8439  8454 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 15:17:53.379  8439  8454 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 15:17:53.379  8439  8454 I Adreno-EGL: Build Date: 12/12/14 금,
08-05 15:17:53.379  8439  8454 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 15:17:53.379  8439  8454 I Adreno-EGL: Remote Branch: 
08-05 15:17:53.379  8439  8454 I Adreno-EGL: Local Patches: 
08-05 15:17:53.379  8439  8454 I Adreno-EGL: Reconstruct Branch: 
,08-05 15:17:53.446  8439  8454 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 15:17:53.446  8439  8454 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 15:17:53.446  8439  8454 I Adreno-EGL: Build Date: 12/12/14 금
08-05 15:17:53.446  8439  8454 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 15:17:53.446  8439  8454 I Adreno-EGL: Remote Branch: 
08-05 15:17:53.446  8439  8454 I Adreno-EGL: Local Patches: 
08-05 15:17:53.446  8439  8454 I Adreno-EGL: Reconstruct Branch: 
,08-05 15:17:53.510   318  8526 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 15:17:53.511   318  8526 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-05 15:17:53.544   318  8526 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-05 15:17:53.562  1035  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=32.8, 0.0, 0.0  rx=28.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1524258330] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 15:17:53.569  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=32.8, 0.0, 0.0  rx=28.2 bcn=0 [on:0 tx:0 rx:0 period:7] from screen [on:0 period:1524258337] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 15:17:53.570  1035  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 15:17:53.699  1816  8398 I CheckinTask: Sending checkin request (7786 bytes)
,08-05 15:17:53.956  1816  8398 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
08-05 15:17:53.961  1816  8398 I CheckinService: active receiver: disabled
,08-05 15:17:53.988  2232  2232 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-05 15:17:54.007  2232  2232 I GCM     : GCM config loaded
,08-05 15:17:54.059  2232  2247 I art     : Explicit concurrent mark sweep GC freed 6664(431KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 1.258ms total 36.758ms
,08-05 15:17:54.067  8361  8361 V SetupWizard: Connected to Gservices successfully
,08-05 15:17:54.159  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-05 15:17:54.159  6877  6943 I jxcore-log: 
,08-05 15:17:54.434  7831  8303 D UEI.SmartControl: Internal timer expired: 4
08-05 15:17:54.434  7831  8303 D UEI.SmartControl: unbind internal service
,08-05 15:17:54.476  7831  8300 D serial_port: close(fd = 24)
,08-05 15:17:54.487  7831  8300 I UEI.SmartControl: Serial port is closed.
,08-05 15:17:54.528  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-05 15:17:54.528  6877  6943 I jxcore-log: 
,08-05 15:17:54.537  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-05 15:17:54.537  6877  6943 I jxcore-log: 
,08-05 15:17:54.561  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-05 15:17:54.561  6877  6943 I jxcore-log: 
,08-05 15:17:54.568  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-05 15:17:54.568  6877  6943 I jxcore-log: 
,08-05 15:17:55.259  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-05 15:17:55.259  6877  6943 I jxcore-log: 
,08-05 15:17:55.274  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-05 15:17:55.274  6877  6943 I jxcore-log: 
,08-05 15:17:55.286  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-05 15:17:55.286  6877  6943 I jxcore-log: 
,08-05 15:17:55.294  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-05 15:17:55.294  6877  6943 I jxcore-log: 
,08-05 15:17:55.342  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-05 15:17:55.342  6877  6943 I jxcore-log: 
,08-05 15:17:55.397  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-05 15:17:55.397  6877  6943 I jxcore-log: 
,08-05 15:17:55.404  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-05 15:17:55.404  6877  6943 I jxcore-log: 
08-05 15:17:55.550  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-05 15:17:55.551  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-05 15:17:55.562  1941  2123 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-05 15:17:55.562  1941  2123 D LEDHandler: Battery Level Remaining: 100%
08-05 15:17:55.562  1941  2123 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
08-05 15:17:55.563  1035  1545 D WifiController: battery changed pluggedType: 2
08-05 15:17:55.563  1604  1604 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
08-05 15:17:55.563  1604  1604 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-05 15:17:55.568  7738  7990 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 15:17:55.569  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-05 15:17:55.570  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:55.570  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 15:17:55.572  8167  8167 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-05 15:17:55.583  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-05 15:17:55.583  6877  6943 I jxcore-log: 
,08-05 15:17:55.608  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-05 15:17:55.608  6877  6943 I jxcore-log: 
,08-05 15:17:55.613  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-05 15:17:55.613  6877  6943 I jxcore-log: 
08-05 15:17:55.618  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-05 15:17:55.618  6877  6943 I jxcore-log: 
08-05 15:17:55.635  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-05 15:17:55.635  6877  6943 I jxcore-log: 
,08-05 15:17:55.715  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-05 15:17:55.715  6877  6943 I jxcore-log: 
,08-05 15:17:55.727  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-05 15:17:55.727  6877  6943 I jxcore-log: 
08-05 15:17:55.757  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-05 15:17:55.757  6877  6943 I jxcore-log: 
08-05 15:17:55.770  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-05 15:17:55.770  6877  6943 I jxcore-log: 
,08-05 15:17:55.791  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-05 15:17:55.791  6877  6943 I jxcore-log: 
,08-05 15:17:55.825  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-05 15:17:55.825  6877  6943 I jxcore-log: 
08-05 15:17:55.830  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-05 15:17:55.830  6877  6943 I jxcore-log: 
,08-05 15:17:56.032  6877  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-05 15:17:56.032  6877  6943 I jxcore-log: 
,08-05 15:17:56.040  6877  6943 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-05 15:17:56.041  6877  6943 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-05 15:17:56.041  6877  6943 I jxcore-log: 
08-05 15:17:56.087  6877  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 15:17:56.087  6877  6943 I jxcore-log: 
,08-05 15:17:56.580  1035  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=28.9, 0.0, 0.0  rx=23.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1524261348] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 15:17:56.591  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=28.9, 0.0, 0.0  rx=23.6 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1524261359] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 15:17:56.591  1035  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 15:17:57.470  8456  8478 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-05 15:17:58.521  1035  2013 I ActivityManager: Killing 7053:com.lge.settings.easy/1000 (adj 15): empty #17
,08-05 15:17:58.555  1035  1914 W libprocessgroup: failed to open /acct/uid_1000/pid_7053/cgroup.procs: No such file or directory
,08-05 15:17:59.604  1035  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=24.4, 0.0, 0.0  rx=19.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1524264372] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 15:17:59.607  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=24.4, 0.0, 0.0  rx=19.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1524264375] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 15:17:59.607  1035  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 15:18:00.004  1035  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=619433655, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-05 15:18:00.012  8250  8250 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-05 15:18:00.016  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8013
08-05 15:18:00.045  2580  2580 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 15:18:00.060  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 15:18:00.060  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 15:18:00.061  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 15:18:00.061  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-05 15:18:00.066  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 15:18:00.066  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-05 15:18:00.067  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-05 15:18:00.069  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 15:18:00.116  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=619433655 [*alarm*], flags=0x0
,08-05 15:18:01.790  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-05 15:18:01.872  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-05 15:18:01.886  1035  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8569 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-05 15:18:01.949  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-05 15:18:01.950  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-05 15:18:01.957  1035  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-05 15:18:01.960  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 15:18:01.961  8569  8569 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 15:18:01.982  1035  1035 D administrator: Handling package changes for user 0
,08-05 15:18:02.014  8569  8569 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 15:18:02.015  8569  8569 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 15:18:02.059  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-05 15:18:02.059  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-05 15:18:02.099  8569  8613 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-05 15:18:02.099  8569  8613 I Babel   : MmsConfig.loadMmsSettings
08-05 15:18:02.101  8569  8613 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 15:18:02.101  8569  8613 I Babel   : MmsConfig.loadFromDatabase
08-05 15:18:02.116  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 15:18:02.124  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-05 15:18:02.125  8569  8613 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-05 15:18:02.125  8569  8613 I Babel   : MmsConfig.loadFromResources
08-05 15:18:02.128  8569  8613 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-05 15:18:02.128  8569  8613 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-05 15:18:02.136  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-05 15:18:02.138  2502  2502 V GmsNetworkLocationProvi: DISABLE
08-05 15:18:02.147  8569  8569 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 15:18:02.152  8569  8610 W AudioCapabilities: Unsupported mime audio/evrc
08-05 15:18:02.154  8569  8610 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 15:18:02.155  8569  8610 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 15:18:02.164  8569  8610 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-05 15:18:02.165  8569  8610 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 15:18:02.166  8569  8610 W AudioCapabilities: Unsupported mime audio/evrc
08-05 15:18:02.178  1816  8616 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-05 15:18:02.178  1816  8616 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-05 15:18:02.181  2502  2502 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-05 15:18:02.185  7156  7156 I AppUp4:CustModeStarterReceiver: onReceive
08-05 15:18:02.193  7156  7156 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2a9df96f
08-05 15:18:02.193  7156  7156 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 15:18:02.193  7156  7156 D AppUp4:CustFacade: isPhone : true
08-05 15:18:02.193  7156  7156 D AppUp4:CustModeStarterReceiver: begin check event
08-05 15:18:02.193  7156  7156 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-05 15:18:02.194  1816  5210 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-05 15:18:02.197  8569  8610 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-05 15:18:02.202  8569  8610 W VideoCapabilities: Unsupported mime video/divx
08-05 15:18:02.204  8569  8610 W VideoCapabilities: Unsupported mime video/divx311
08-05 15:18:02.206  8569  8610 W VideoCapabilities: Unsupported mime video/divx4
,08-05 15:18:02.214  8569  8610 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-05 15:18:02.219  1035  1051 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8620 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-05 15:18:02.222  1035  2014 I ActivityManager: Killing 8167:com.lge.bnr/1000 (adj 15): empty #17
08-05 15:18:02.232   354   354 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 244us total 11.766ms
,08-05 15:18:02.244   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 195us total 11.331ms
,08-05 15:18:02.249  8569  8610 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-05 15:18:02.252  8569  8610 W AudioCapabilities: Unsupported mime audio/eac3
08-05 15:18:02.253  8569  8610 W AudioCapabilities: Unsupported mime audio/ac3
08-05 15:18:02.254  8569  8610 W AudioCapabilities: Unsupported mime audio/g726
08-05 15:18:02.254   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 197us total 9.677ms
08-05 15:18:02.255  8569  8610 W AudioCapabilities: Unsupported mime audio/wma-voice
08-05 15:18:02.256  8569  8610 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-05 15:18:02.258  8569  8610 W AudioCapabilities: Unsupported mime audio/adpcm
08-05 15:18:02.260  8569  8610 W VideoCapabilities: Unsupported mime video/theora
08-05 15:18:02.261  8569  8610 W VideoCapabilities: Unsupported mime video/mjpg
08-05 15:18:02.303  1035  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_8167/cgroup.procs: No such file or directory
,08-05 15:18:02.312  1035  1091 D LocationProviderProxy: applying state to connected service
08-05 15:18:02.333  8620  8620 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 15:18:02.334  8620  8620 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 15:18:02.334  8620  8620 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-05 15:18:02.337  8620  8620 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-05 15:18:02.337  8620  8620 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 15:18:02.390  8620  8620 I SystemConfig: BUILD Country: EU
08-05 15:18:02.390  8620  8620 I SystemConfig: BUILD Operator: OPEN
,08-05 15:18:02.427  1035  1051 I ActivityManager: Killing 8142:com.lge.sync/1000 (adj 15): empty #17
,08-05 15:18:02.544  1035  1914 W libprocessgroup: failed to open /acct/uid_1000/pid_8142/cgroup.procs: No such file or directory
,08-05 15:18:02.584  1035  1051 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8643 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-05 15:18:02.592  8620  8638 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-05 15:18:02.592  8620  8638 I SystemConfig: existFile = false
08-05 15:18:02.592  8620  8638 I SystemConfig: canReadFile = false
08-05 15:18:02.592  8620  8638 I SystemConfig: systemFeature RCS result false
08-05 15:18:02.592  8620  8638 D SystemConfig: refreshRcsSupport() :false
08-05 15:18:02.633  1035  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=12.7, 0.0, 0.0  rx=9.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1524267401] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 15:18:02.633  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=12.7, 0.0, 0.0  rx=9.9 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:1524267401] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 15:18:02.633  1035  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 15:18:02.647  8643  8643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 15:18:02.647  8643  8643 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 15:18:02.648  8643  8643 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-05 15:18:02.648  8643  8643 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-05 15:18:02.734  8643  8643 I AppConfig: Total System Memory = 2995761152
,08-05 15:18:02.745  8643  8643 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-05 15:18:02.850  1035  1940 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8662 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 15:18:02.852  1035  1940 I ActivityManager: Killing 6961:com.android.settings/1000 (adj 15): empty #17
,08-05 15:18:02.923  1035  2051 W libprocessgroup: failed to open /acct/uid_1000/pid_6961/cgroup.procs: No such file or directory
,08-05 15:18:03.140  8662  8662 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-05 15:18:03.281  8662  8662 D LgDataFeature: LgDataFeature() Constructor: none
08-05 15:18:03.282  8662  8662 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 15:18:03.336  8662  8662 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-05 15:18:03.357  8662  8662 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-05 15:18:03.358  8662  8662 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-05 15:18:03.375  8662  8662 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-05 15:18:03.375  8662  8662 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-05 15:18:03.396  1035  1887 I ActivityManager: Killing 8329:com.lge.email/u0a23 (adj 15): empty #17
,08-05 15:18:03.454  1035  2013 W libprocessgroup: failed to open /acct/uid_10023/pid_8329/cgroup.procs: No such file or directory
,08-05 15:18:03.460  3473  4222 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-05 15:18:03.466  3473  4222 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1104f75b on behalf of 8662
08-05 15:18:03.471  5050  8702 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-05 15:18:03.520  1035  2048 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8703 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-05 15:18:03.569  8662  8662 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-05 15:18:03.690  1035  1978 I art     : Explicit concurrent mark sweep GC freed 38126(1957KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.937ms total 113.005ms
,08-05 15:18:03.713  8662  8662 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-05 15:18:03.728  8703  8703 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-05 15:18:03.749  8703  8703 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-05 15:18:03.749  8703  8703 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-05 15:18:03.749  8703  8703 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-05 15:18:03.749  8703  8703 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-05 15:18:03.749  8703  8703 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-05 15:18:03.749  8703  8703 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-05 15:18:03.758  1035  1644 I ActivityManager: Killing 8117:com.lge.formmanager/u0a26 (adj 15): empty #17
08-05 15:18:03.783  1035  1051 W libprocessgroup: failed to open /acct/uid_10026/pid_8117/cgroup.procs: No such file or directory
,08-05 15:18:03.975  1035  1781 V SIM_STK : Menu title from STK is T-Mobile
,08-05 15:18:03.991  5050  8702 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 520 ms] updated apps [took 520 ms] 
,08-05 15:18:05.648  1035  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=6.4, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1524270416] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 15:18:05.651  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=6.4, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1524270419] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 15:18:05.651  1035  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 15:18:08.674  1035  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1524273441] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 15:18:08.677  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1524273444] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 15:18:08.677  1035  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 15:18:10.124  1035  1539 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-05 15:18:10.125  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 15:18:10.127  1035  1539 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 15:18:10.128  1035  1539 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-05 15:18:10.140  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 15:18:10.142  1035  1539 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 15:18:10.862  6877  6943 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-05 15:18:10.862  6877  6943 I jxcore-log: 
,08-05 15:18:11.198  8744  8744 D AndroidRuntime: 
08-05 15:18:11.198  8744  8744 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-05 15:18:11.203  8744  8744 D AndroidRuntime: CheckJNI is OFF
08-05 15:18:11.324  8744  8744 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 15:18:11.335  1035  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-05 15:18:11.335  1035  1092 I ActivityManager: Killing 6877:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-05 15:18:11.400  1035  1886 I WindowState: WIN DEATH: Window{2dde9b65 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-05 15:18:11.401  1035  1545 D WifiService: Client connection lost with reason: 4
,08-05 15:18:11.407  1035  1886 D InputDispatcher: Window went away: Window{2dde9b65 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-05 15:18:11.562  1035  1092 I ActivityManager:   Force finishing activity ActivityRecord{3e143ca6 u0 com.test.thalitest/.MainActivity t40}
,08-05 15:18:11.628   344   365 E GBMv2   : DFP En is all cleared set to be enabled
,08-05 15:18:11.640  1035  1576 W ActivityManager: Spurious death for ProcessRecord{3a88e545 6877:com.test.thalitest/u0a118}, curProc for 6877: null
08-05 15:18:11.641  1035  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-05 15:18:11.647  1035  1124 I ActivityManager:   Force finishing activity ActivityRecord{3e143ca6 u0 com.test.thalitest/.MainActivity t40 f}
08-05 15:18:11.647  1035  1124 W ActivityManager: Duplicate finish request for ActivityRecord{3e143ca6 u0 com.test.thalitest/.MainActivity t40 f}
,08-05 15:18:11.683  2033  2033 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-05 15:18:11.684  2033  2033 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-05 15:18:11.687  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-05 15:18:11.687  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{14aba0b8 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-05 15:18:11.688  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-05 15:18:11.690  2033  2127 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-05 15:18:11.691  1941  2538 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-05 15:18:11.692  1941  2538 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1e5bae91 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
,08-05 15:18:11.713  1035  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1524276481] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 15:18:11.715  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1524276483] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 15:18:11.715  1035  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 15:18:11.718  1905  1905 D ActionManagerService: notifyUserLog: 1000003
,08-05 15:18:11.721  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-05 15:18:11.721  5050  5050 I art     : Explicit concurrent mark sweep GC freed 15440(886KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 516us total 59.256ms
08-05 15:18:11.722  3711  4937 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-05 15:18:11.724  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-05 15:18:11.730  1035  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 15:18:11.741  1996  1996 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-05 15:18:11.741  2502  2683 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-05 15:18:11.741  3711  3711 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-05 15:18:11.751  7738  7738 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-05 15:18:11.751  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-05 15:18:11.755  4946  4946 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-05 15:18:11.756  4946  4946 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-05 15:18:11.756  4946  4946 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-05 15:18:11.756  4946  4946 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-05 15:18:11.756  4946  4946 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 15:18:11.756  4946  4946 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 15:18:11.756  4946  4946 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 15:18:11.756  4946  4946 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 15:18:11.756  4946  4946 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 15:18:11.756  4946  4946 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 15:18:11.756  4946  4946 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 15:18:11.756  4946  4946 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-05 15:18:11.759  1035  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-05 15:18:11.774  1035  1887 V SIM_STK : Menu title from STK is T-Mobile
,08-05 15:18:11.802  2033  2033 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-05 15:18:11.803  8185  8185 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-05 15:18:11.822  2033  2033 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-05 15:18:11.828  1816  1816 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-05 15:18:11.828  2033  2033 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-05 15:18:11.834  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-05 15:18:11.835  1905  1905 D ActionManagerService: notifyUserLog: 1000004
08-05 15:18:11.835  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-05 15:18:11.835  3711  4937 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-05 15:18:11.836  1604  1654 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 15:18:11.836  1604  1654 D KeyguardModel: createShortcutInfo...
08-05 15:18:11.840  1035  1035 I art     : Explicit concurrent mark sweep GC freed 16680(1085KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.565ms total 164.745ms
08-05 15:18:11.843  3711  3730 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262123
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , display: false
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , animation: false }
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262287
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , display: false
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , animation: false }
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , create_time: 1470393743569
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , display: false
08-05 15:18:11.845  2033  2033 I GBoardWebViewUtils: , animation: false }
,08-05 15:18:11.851  1604  1654 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
,08-05 15:18:11.851  1604  1654 D KeyguardModel: createShortcutInfo...
08-05 15:18:11.853  2232  2232 I ConfigService: onCreate
08-05 15:18:11.853  2232  2232 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-05 15:18:11.856  1604  1654 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-05 15:18:11.856  1604  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 15:18:11.856  1604  1654 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-05 15:18:11.857  1604  1654 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 15:18:11.858  1604  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 15:18:11.858  1604  1654 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-05 15:18:11.859  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-05 15:18:11.859  1869  1869 D SplitUIService: removed split : 
08-05 15:18:11.861  1604  1654 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 15:18:11.861  1604  1654 D KeyguardModel: createShortcutInfo...
,08-05 15:18:11.863  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-05 15:18:11.863  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-05 15:18:11.864  1604  1654 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-05 15:18:11.864  1604  1654 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 15:18:11.866  2232  2232 I ConfigService: onBind returning update interface
08-05 15:18:11.867  2033  8776 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-05 15:18:11.871  1604  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 15:18:11.872  1604  1654 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-05 15:18:11.875  1816  1816 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-05 15:18:11.880  1035  1644 V SIM_STK : Menu title from STK is T-Mobile
08-05 15:18:11.880  1035  1644 V SIM_STK : Menu title from STK is T-Mobile
08-05 15:18:11.884  2232  2232 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-05 15:18:11.884  2232  2232 I ConfigService: onBind returning config service
,08-05 15:18:11.897  1816  1816 I ConfigFetchService: service connected
,08-05 15:18:11.897  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-05 15:18:11.901  1604  1654 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 15:18:11.901  1604  1654 D KeyguardModel: createShortcutInfo...
08-05 15:18:11.902  2232  2232 I ConfigService: onDestroy
08-05 15:18:11.907  1604  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 15:18:11.907  1604  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 15:18:11.907  1604  1654 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-05 15:18:11.907  1604  1654 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 15:18:11.912  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-05 15:18:11.912  1869  1869 I SplitUIService: split app #11
08-05 15:18:11.913  1604  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 15:18:11.913  1604  1654 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 15:18:11.914  1604  1654 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 15:18:11.914  1604  1654 D KeyguardModel: createShortcutInfo...
,08-05 15:18:11.920  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-05 15:18:11.920  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-05 15:18:11.931  1035  1035 D administrator: Handling package changes for user 0
,08-05 15:18:11.931  1604  1654 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 15:18:11.931  1604  1654 D KeyguardModel: createShortcutInfo...
08-05 15:18:11.934  1035  2014 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-05 15:18:11.934  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 15:18:11.934  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 15:18:11.934  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 15:18:11.934  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 15:18:11.934  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 15:18:11.934  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 15:18:11.934  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 15:18:11.934  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 15:18:11.934  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 15:18:11.934  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 15:18:11.934  7738  7738 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 15:18:11.940  1816  8780 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-05 15:18:11.945  1604  1654 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 15:18:11.945  1604  1654 D KeyguardModel: createShortcutInfo...
08-05 15:18:11.946  1604  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 15:18:11.946  1604  1654 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-05 15:18:11.949  1604  1654 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 15:18:11.949  1604  1654 D KeyguardModel: createShortcutInfo...
08-05 15:18:11.951  1604  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 15:18:11.951  1604  1654 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-05 15:18:11.953  1604  1654 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 15:18:11.953  1604  1654 D KeyguardModel: createShortcutInfo...
08-05 15:18:11.954  1604  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 15:18:11.955  1604  1654 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 15:18:11.955  1035  1576 V SIM_STK : Menu title from STK is T-Mobile
08-05 15:18:11.966  1604  1654 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 15:18:11.966  1604  1654 D KeyguardModel: createShortcutInfo...
,08-05 15:18:11.974  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 15:18:11.975  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-05 15:18:11.975  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-05 15:18:11.978  5810  8785 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-05 15:18:11.979  2033  2033 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-05 15:18:12.002  1816  8787 I PeopleContactsSync: CP2 sync disabled
,08-05 15:18:12.011  1816  5210 I Icing   : doRemovePackageData com.test.thalitest
08-05 15:18:12.014  1816  8786 W GmsApplication: Using Auth Proxy for data requests.
,08-05 15:18:12.016   338   437 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-05 15:18:12.017  3267  8789 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-05 15:18:12.020  1816  8786 W GmsApplication: Using Auth Proxy for data requests.
08-05 15:18:12.030  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-05 15:18:12.030  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 15:18:12.030  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-05 15:18:12.031  1035  1578 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
,08-05 15:18:12.040  7156  7156 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-05 15:18:12.068  2331  8791 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-05 15:18:12.074  1035  2051 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8792 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-05 15:18:12.086  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-05 15:18:12.091  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 15:18:12.092  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-05 15:18:12.094  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-05 15:18:12.095  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-05 15:18:12.096  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-05 15:18:12.117  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-05 15:18:12.117  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 15:18:12.117  2033  2175 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-05 15:18:12.117  2033  2175 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-05 15:18:12.123  1035  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f20e5df u0 com.lge.launcher2/.Launcher t39} time:385400
08-05 15:18:12.134  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-05 15:18:12.135  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,08-05 15:18:12.135  8792  8792 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 15:18:12.135  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 15:18:12.140  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 15:18:12.140  8792  8792 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 15:18:12.141  8792  8792 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 15:18:12.141  8792  8792 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 15:18:12.144  2033  2033 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-05 15:18:12.144  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-05 15:18:12.145  2580  2580 D [Concierge]Service: onStartCommand(). Type : 8
08-05 15:18:12.145  2580  2580 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-05 15:18:12.146  2580  2580 D [Concierge]Service: Update widget ID : 11
08-05 15:18:12.147  2033  2033 D [Concierge]WidgetView: change position of spinner
08-05 15:18:12.148  2033  2033 I [Concierge]WidgetView: initWebView(). Time : 1470403092148
08-05 15:18:12.148  2580  2580 D [Concierge]Service: onStartCommand(). Type : 0
,08-05 15:18:12.160  2033  2033 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 767407362
08-05 15:18:12.161  2033  2033 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-05 15:18:12.161  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-05 15:18:12.162  1816  8810 I art     : Explicit concurrent mark sweep GC freed 36532(2MB) AllocSpace objects, 26(416KB) LOS objects, 51% free, 30MB/62MB, paused 783us total 34.841ms
,08-05 15:18:12.166  2033  2033 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@192d8d93
08-05 15:18:12.166  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-05 15:18:12.167  1816  1828 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-05 15:18:12.167  1816  1828 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-05 15:18:12.167  1816  1828 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-05 15:18:12.169  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-05 15:18:12.169  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 15:18:12.174  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-05 15:18:12.174  2033  2033 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-05 15:18:12.174  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-05 15:18:12.176  2033  2033 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-05 15:18:12.176  2033  2033 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470402734968, New one : 1470403092148
08-05 15:18:12.176  2033  2033 D [Concierge]WidgetView: Unregister all receivers
08-05 15:18:12.176  2033  2033 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-05 15:18:12.177  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 15:18:12.178  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-05 15:18:12.180  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-05 15:18:12.181  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-05 15:18:12.182  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-05 15:18:12.183  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-05 15:18:12.183  1035  1124 I art     : Explicit concurrent mark sweep GC freed 13433(871KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.132ms total 318.284ms
08-05 15:18:12.185  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 15:18:12.186  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 15:18:12.206  8792  8792 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 15:18:12.218  8792  8792 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-05 15:18:12.226  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-05 15:18:12.234  2033  2033 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-05 15:18:12.234  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-05 15:18:12.243  8792  8792 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 15:18:12.243  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 15:18:12.253  8744  8744 D AndroidRuntime: Shutting down VM
,08-05 15:18:12.262  2033  2033 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2bfec01f time:385539
08-05 15:18:12.267  8792  8792 D LgDataFeature: LgDataFeature() Constructor: none
08-05 15:18:12.267  8792  8792 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 15:18:12.282  1035  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8814 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-05 15:18:12.318  8792  8792 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-05 15:18:12.325  1035  1959 I ActivityManager: Killing 8380:com.android.chrome/u0a57 (adj 15): empty #17
,08-05 15:18:12.368  2033  2033 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-05 15:18:12.403  2033  2873 I GBoardtInterface: onReloaded()
,08-05 15:18:12.405  2033  2033 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-05 15:18:12.413  1035  1959 I ActivityManager: Killing 8399:com.lge.drmservice/u0a62 (adj 15): empty #17
08-05 15:18:12.433  1996  1996 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-05 15:18:12.433  1996  1996 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-05 15:18:12.434  1035  1914 W libprocessgroup: failed to open /acct/uid_10062/pid_8399/cgroup.procs: No such file or directory
08-05 15:18:12.435  3711  3730 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 15:18:12.436  1035  1781 W libprocessgroup: failed to open /acct/uid_10057/pid_8380/cgroup.procs: No such file or directory
08-05 15:18:12.437  1996  1996 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-05 15:18:12.440  3711  4938 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 15:18:12.441  8185  8185 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-05 15:18:12.472  1035  2014 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8835 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-05 15:18:12.473  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-05 15:18:12.474  3711  4937 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-05 15:18:12.475  3711  4937 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-05 15:18:12.477  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-05 15:18:12.478  3711  4937 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-05 15:18:12.478  3711  4937 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-05 15:18:12.478  3711  4937 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-05 15:18:12.478  3711  4937 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-05 15:18:12.478  3711  3730 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 15:18:12.480  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-05 15:18:12.481  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-05 15:18:12.482  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-05 15:18:12.482  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 15:18:12.484  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-05 15:18:12.484  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-05 15:18:12.538  8835  8835 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-05 15:18:12.538  8835  8835 W LG Account v2.2: No ProfileInfo entries
08-05 15:18:12.538  8835  8835 I LG Account v2.2: isEnabled: false
08-05 15:18:12.538  8835  8835 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 15:18:12.538  8835  8835 I Feature : [Lifetracker]Country: EU
08-05 15:18:12.539  8835  8835 I Feature : [Lifetracker]Operator: OPEN
08-05 15:18:12.539  8835  8835 I Feature : [Lifetracker]Ranking support: false
08-05 15:18:12.539  8835  8835 I Feature : [Lifetracker]Comfort support: false
08-05 15:18:12.539  8835  8835 I Feature : [Lifetracker]Accessory: true
08-05 15:18:12.539  8835  8835 I Feature : [Lifetracker]Health device: true
08-05 15:18:12.539  8835  8835 I Feature : [Lifetracker]Extra Pedometer: false
08-05 15:18:12.539  8835  8835 I Feature : [Lifetracker]Blood glucose device: false
08-05 15:18:12.539  8835  8835 I Feature : [Lifetracker]Device Number: 3
08-05 15:18:12.539  8835  8835 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-05 15:18:12.568  1035  1886 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8857 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 15:18:12.569  1035  1886 I ActivityManager: Killing 8419:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17

```
