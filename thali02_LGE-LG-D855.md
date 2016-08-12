#### Test 80912877c1aacde_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-12 11:12:00.084  1580  1580 I [SystemUI]Clock: called onTimeUpdated()
08-12 11:12:00.093  1580  1580 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 11:12:00.094  1580  1580 I [SystemUI]DateView: called onTimeUpdated()
08-12 11:12:00.097  1580  1580 I [SystemUI]DateView: called onTimeUpdated()
08-12 11:12:00.098  1580  1580 D KeyguardUpdateMonitor: handleTimeUpdate
,08-12 11:12:35.096  6751  6751 D AndroidRuntime: 
08-12 11:12:35.096  6751  6751 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 11:12:35.099  6751  6751 D AndroidRuntime: CheckJNI is OFF
08-12 11:12:35.218  6751  6751 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 11:12:35.223  1031  2015 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 11:12:35.232  1944  2563 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-12 11:12:35.245  1031  2015 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-12 11:12:35.248  1031  2015 D ActivityManager: setTaskToReturnTo : TaskRecord{16a984f5 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 11:12:35.248  1031  2015 D ActivityManager: setTaskToReturnTo : TaskRecord{16a984f5 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 11:12:35.251  1031  2015 D WindowStateEx: AppWindowTokenEx init.. 
08-12 11:12:35.253   369   397 E GBMv2   : DFP En is all cleared set to be enabled
08-12 11:12:35.300  1031  2015 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6771 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 11:12:35.304  6751  6751 D AndroidRuntime: Shutting down VM
08-12 11:12:35.350  1944  2563 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-12 11:12:35.350  1944  2563 D SplitWindowPolicy: topRunningActivity=ActivityInfo{d1893f7 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 11:12:35.351  1944  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-12 11:12:35.351  1944  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{38967264 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 11:12:35.414  6771  6771 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-12 11:12:35.488  6771  6771 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-12 11:12:35.494  6771  6771 I LibraryLoader: Loading: webviewchromium
08-12 11:12:35.497  6771  6771 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7179-7182)
08-12 11:12:35.497  6771  6771 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 11:12:35.516  6771  6771 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1b33efbd}
08-12 11:12:35.518  6771  6771 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 11:12:35.519  6771  6771 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-12 11:12:35.533  6771  6771 I BrowserStartupController: Initializing chromium process, renderers=0
08-12 11:12:35.534  6771  6771 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 11:12:35.552  6771  6771 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-12 11:12:35.553  6771  6771 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-12 11:12:35.553  6771  6771 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-12 11:12:35.555   315  1384 V AudioPolicyService: registerClient() client 0xb57f97e0, uid 10118
08-12 11:12:35.568  1031  1093 D BluetoothManagerService: Message: 20
,08-12 11:12:35.569  1031  1093 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1abcb1d7:true
08-12 11:12:35.570  6771  6771 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 11:12:35.570  6771  6771 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 11:12:35.570  6771  6771 I Adreno-EGL: Build Date: 12/12/14 금
08-12 11:12:35.570  6771  6771 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-12 11:12:35.570  6771  6771 I Adreno-EGL: Remote Branch: 
08-12 11:12:35.570  6771  6771 I Adreno-EGL: Local Patches: 
08-12 11:12:35.570  6771  6771 I Adreno-EGL: Reconstruct Branch: 
08-12 11:12:35.659  6771  6807 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-12 11:12:35.666  6771  6771 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-12 11:12:35.686  6771  6771 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 11:12:35.692  6771  6771 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 11:12:35.696  6771  6771 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-12 11:12:35.699  6771  6771 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 11:12:35.700  6771  6771 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-12 11:12:35.717  6771  6771 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 11:12:35.724  6771  6771 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 11:12:35.724  6771  6771 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 11:12:35.776  6771  6819 D OpenGLRenderer: Render dirty regions requested: true
08-12 11:12:35.776  6771  6819 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 11:12:35.783  6771  6819 D OpenGLRenderer: Enabling debug mode 0
08-12 11:12:35.797  6771  6771 D Atlas   : Validating map...
,08-12 11:12:35.805  1031  1976 D SplitWindow: check instance of lgWin Window{5b14d19 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 11:12:35.845  6771  6817 D LgDataFeature: LgDataFeature() Constructor: none
,08-12 11:12:35.845  6771  6817 D LgDataFeature: LgDataFeature() Constructor Done, null
08-12 11:12:35.956  1031  1094 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +605ms (total +701ms)
,08-12 11:12:35.959  1031  1094 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{172e728a u0 com.test.thalitest/.MainActivity t6} time:187644
08-12 11:12:35.964  6771  6771 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d6dfdb0 time:187649
08-12 11:12:36.075  6771  6771 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-12 11:12:36.075  6771  6771 I chromium: 
,08-12 11:12:36.152  6771  6771 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 11:12:36.236  6771  6817 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-12 11:12:36.236  6771  6817 I chromium: 
,08-12 11:12:36.386  6771  6833 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435177984
,08-12 11:12:36.402  6771  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 11:12:36.402  6771  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 11:12:36.402  6771  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 11:12:36.402  6771  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 11:12:36.402  6771  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 11:12:36.402  6771  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55b5374 added. We now have 1 listener(s)
,08-12 11:12:36.408  1031  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 11:12:36.411  6771  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-12 11:12:36.412  6771  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-12 11:12:36.414  6771  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 11:12:36.414  6771  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 11:12:36.422  6771  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 11:12:36.422  6771  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 11:12:36.422  6771  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 11:12:36.422  6771  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-12 11:12:36.422  6771  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 11:12:36.422  6771  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 11:12:36.422  6771  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 11:12:36.422  6771  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 11:12:36.422  6771  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 11:12:36.422  6771  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 11:12:36.422  6771  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 11:12:36.422  6771  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 11:12:36.422  6771  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 11:12:36.422  6771  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-12 11:12:36.422  6771  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18358e3 added. We now have 1 listener(s)
08-12 11:12:36.423  6771  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 11:12:36.427  1031  1544 D WifiService: New client listening to asynchronous messages
08-12 11:12:36.431  6771  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 11:12:36.432  6771  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 11:12:36.433  6771  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 11:12:36.434  6771  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 11:12:36.434  6771  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 11:12:36.438  6771  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 11:12:36.439  1031  2046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 11:12:36.441  6771  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-12 11:12:36.449  6771  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 11:12:36.450  6771  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 11:12:36.450  6771  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 11:12:36.450  6771  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 11:12:36.450  6771  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 11:12:36.450  6771  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 11:12:36.450  6771  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 11:12:36.450  6771  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 11:12:36.450  6771  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 11:12:36.450  6771  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 11:12:36.450  6771  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 11:12:36.451  6771  6833 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 11:12:36.452  6771  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 11:12:36.454  6771  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 11:12:36.485  6771  6771 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 11:12:36.662  1580  1580 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-12 11:12:36.663  1580  1580 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-12 11:12:36.673  1580  1580 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
,08-12 11:12:36.674  1580  1580 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-12 11:12:36.674  1031  1544 D WifiController: battery changed pluggedType: 2
08-12 11:12:36.677  1944  2102 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-12 11:12:36.677  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 11:12:36.677  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 11:12:36.678  3875  3988 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 11:12:36.682  1944  2102 D LEDHandler: Battery Level Remaining: 100%
08-12 11:12:36.682  1944  2102 D LEDHandler: Battery Temp: 283, mChargingStatus=5, mChargingStop=false
08-12 11:12:36.684  1580  1580 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-12 11:12:36.686  6640  6640 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-12 11:12:37.110  6771  6836 W jxcore-log: Initializing JXcore engine
08-12 11:12:37.110  6771  6836 W jxcore-log: JXcore engine is ready
,08-12 11:12:37.134  6836  6836 W Thread-766: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9691]" dev="sockfs" ino=9691 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-12 11:12:37.134  6836  6836 W Thread-766: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-12 11:12:37.134  6836  6836 W Thread-766: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8631]" dev="sockfs" ino=8631 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-12 11:12:37.134  6836  6836 W Thread-766: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-12 11:12:37.134  6836  6836 W Thread-766: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31553]" dev="sockfs" ino=31553 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket,
,08-12 11:12:37.160  6771  6836 W jxcore-log: Starting JXcore engine
08-12 11:12:37.191   369   399 E GBMv2   : DFP En is all cleared set to be enabled
08-12 11:12:37.191   369   399 E GBMv2   : Set value is all cleared set the max
,08-12 11:12:37.191   369   399 I GBMv2   : DFP Enabled. Ignore VFP set
,08-12 11:12:37.238  6771  6836 W jxcore-log: Platform android
08-12 11:12:37.238  6771  6836 W jxcore-log: 
,08-12 11:12:37.238  6771  6836 W jxcore-log: Process ARCH arm
08-12 11:12:37.238  6771  6836 W jxcore-log: 
,08-12 11:12:37.402  6771  6836 I jxcore-log: JXcore Cordova bridge is ready!
08-12 11:12:37.402  6771  6836 I jxcore-log: 
08-12 11:12:37.402  6771  6836 W jxcore-log: JXcore engine is started
,08-12 11:12:37.408  6771  6833 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 11:12:37.414  6771  6771 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 11:12:47.526  6771  6836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 11:12:47.526  6771  6836 I jxcore-log: 
,08-12 11:12:47.528  6771  6836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 11:12:47.528  6771  6836 I jxcore-log: 
,08-12 11:12:47.531  6771  6836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 11:12:47.531  6771  6836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 11:12:47.531  6771  6836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 11:12:47.531  6771  6836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 11:12:47.531  6771  6836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 11:12:47.531  6771  6836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 11:12:47.531  6771  6836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 11:12:47.531  6771  6836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 11:12:47.533  6771  6836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 11:12:47.536  6771  6836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 11:12:47.536  6771  6836 I jxcore-log: 
08-12 11:12:47.537  6771  6836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 11:12:47.537  6771  6836 I jxcore-log: 
08-12 11:12:47.862  6771  6836 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-12 11:12:47.862  6771  6836 I jxcore-log: Failed to execute UT.
08-12 11:12:47.862  6771  6836 I jxcore-log: 
08-12 11:12:47.862  6771  6836 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 11:12:47.862  6771  6836 I jxcore-log: 
,08-12 11:12:47.871  6771  6836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 11:12:47.871  6771  6836 I jxcore-log: 
08-12 11:12:47.872  6771  6771 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-12 11:12:48.211  6847  6847 D AndroidRuntime: 
08-12 11:12:48.211  6847  6847 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 11:12:48.217  6847  6847 D AndroidRuntime: CheckJNI is OFF
08-12 11:12:48.337  6847  6847 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 11:12:48.353  1031  1089 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-12 11:12:48.353  1031  1089 I ActivityManager: Killing 6771:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-12 11:12:48.410  1031  2054 I WindowState: WIN DEATH: Window{5b14d19 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 11:12:48.411  1031  1544 D WifiService: Client connection lost with reason: 4
08-12 11:12:48.415  1031  2054 D InputDispatcher: Window went away: Window{5b14d19 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 11:12:48.578  1031  1089 I ActivityManager:   Force finishing activity ActivityRecord{172e728a u0 com.test.thalitest/.MainActivity t6}
,08-12 11:12:48.619   369   397 E GBMv2   : DFP En is all cleared set to be enabled
08-12 11:12:48.620  1031  1101 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-12 11:12:48.631  1031  1101 I ActivityManager:   Force finishing activity ActivityRecord{172e728a u0 com.test.thalitest/.MainActivity t6 f}
08-12 11:12:48.631  1031  1101 W ActivityManager: Duplicate finish request for ActivityRecord{172e728a u0 com.test.thalitest/.MainActivity t6 f}
,08-12 11:12:48.677  4579  4579 I art     : Explicit concurrent mark sweep GC freed 496(32KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 585us total 37.934ms
,08-12 11:12:48.679  1031  1640 W ActivityManager: Spurious death for ProcessRecord{cc7e7b7 6771:com.test.thalitest/u0a118}, curProc for 6771: null
08-12 11:12:48.680  1944  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-12 11:12:48.680  2035  2035 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-12 11:12:48.681  1944  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c415ccd co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 11:12:48.682  2035  2035 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-12 11:12:48.683  1944  2563 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-12 11:12:48.684  1944  2563 D SplitWindowPolicy: topRunningActivity=ActivityInfo{35a92982 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 11:12:48.685  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-12 11:12:48.687  2035  2127 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-12 11:12:48.694  1907  1907 D ActionManagerService: notifyUserLog: 1000003
,08-12 11:12:48.701  3821  4467 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-12 11:12:48.701  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-12 11:12:48.702  2035  2035 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-12 11:12:48.705  2035  2035 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-12 11:12:48.707  1580  1580 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 11:12:48.709  1031  1088 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-12 11:12:48.720  1031  1439 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 11:12:48.729  2450  2608 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 11:12:48.736  3875  3875 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-12 11:12:48.736  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-12 11:12:48.745  1998  1998 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 11:12:48.745  3821  3821 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-12 11:12:48.773  2035  2035 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-12 11:12:48.774  6463  6463 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-12 11:12:48.775  4473  4473 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 11:12:48.776  4473  4473 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 11:12:48.776  4473  4473 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 11:12:48.776  4473  4473 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-12 11:12:48.776  4473  4473 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 11:12:48.776  4473  4473 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 11:12:48.776  4473  4473 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 11:12:48.776  4473  4473 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 11:12:48.776  4473  4473 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 11:12:48.776  4473  4473 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 11:12:48.776  4473  4473 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 11:12:48.776  4473  4473 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-12 11:12:48.786  1819  1819 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-12 11:12:48.799  1580  1580 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-12 11:12:48.811  1872  1872 D SplitUIManager: split_name #11 / not available #0
08-12 11:12:48.812  1872  1872 D SplitUIService: removed split : 
08-12 11:12:48.815  1031  1031 I art     : Explicit concurrent mark sweep GC freed 40129(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.695ms total 162.324ms
,08-12 11:12:48.817  1031  1046 I art     : WaitForGcToComplete blocked for 15.596ms for cause Explicit
08-12 11:12:48.842  1031  2054 V SIM_STK : Menu title from STK is T-Mobile
,08-12 11:12:48.872  1031  1031 D administrator: Handling package changes for user 0
,08-12 11:12:48.878  1872  1872 D SplitUIManager: split_name #11 / not available #0
08-12 11:12:48.878  1872  1872 I SplitUIService: split app #11
08-12 11:12:48.965  1031  1046 I art     : Explicit concurrent mark sweep GC freed 4370(299KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.717ms total 147.195ms
08-12 11:12:48.966  1031  1101 I art     : WaitForGcToComplete blocked for 282.795ms for cause Explicit
,08-12 11:12:48.979  1031  1640 V SIM_STK : Menu title from STK is T-Mobile
08-12 11:12:48.979  1031  1640 V SIM_STK : Menu title from STK is T-Mobile
,08-12 11:12:48.986  1907  1907 D ActionManagerService: notifyUserLog: 1000004
08-12 11:12:48.986  3821  4467 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-12 11:12:48.990  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-12 11:12:48.995  1580  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 11:12:48.995  1580  1652 D KeyguardModel: createShortcutInfo...
,08-12 11:12:49.001  1580  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 11:12:49.001  1580  1652 D KeyguardModel: createShortcutInfo...
08-12 11:12:49.007  1580  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-12 11:12:49.007  1580  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 11:12:49.008  1580  1652 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-12 11:12:49.009  1580  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 11:12:49.009  1580  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 11:12:49.009  1580  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 11:12:49.011  1580  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 11:12:49.011  1580  1652 D KeyguardModel: createShortcutInfo...
08-12 11:12:49.015  1580  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 11:12:49.015  1580  1580 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 11:12:49.015  1580  1652 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 11:12:49.015  1580  1580 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-12 11:12:49.015  1580  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-12 11:12:49.016  1580  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 11:12:49.018  1580  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 11:12:49.018  1580  1652 D KeyguardModel: createShortcutInfo...
08-12 11:12:49.025  3821  4463 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 11:12:49.030  1580  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 11:12:49.030  1580  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-12 11:12:49.030  1580  1652 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-12 11:12:49.030  1580  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-12 11:12:49.031  1580  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 11:12:49.031  1580  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 11:12:49.033  1580  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 11:12:49.033  1580  1652 D KeyguardModel: createShortcutInfo...
08-12 11:12:49.037  2205  2205 I ConfigService: onCreate
08-12 11:12:49.037  2205  2205 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-12 11:12:49.040  1031  1940 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262123
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , display: false
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , animation: false }
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262287
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , display: false
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , animation: false }
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , create_time: 1470393743569
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , display: false
08-12 11:12:49.040  2035  2035 I GBoardWebViewUtils: , animation: false }
08-12 11:12:49.041  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-12 11:12:49.041  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-12 11:12:49.041  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-12 11:12:49.041  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-12 11:12:49.041  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-12 11:12:49.041  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 11:12:49.041  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-12 11:12:49.041  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-12 11:12:49.041  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-12 11:12:49.041  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 11:12,:49.041  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-12 11:12:49.041  1819  1819 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-12 11:12:49.048  2205  2205 I ConfigService: onBind returning update interface
08-12 11:12:49.048  2035  6885 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-12 11:12:49.049  1580  1580 D KeyguardModel: handleShortcutListChanged...
08-12 11:12:49.049  1580  1580 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 11:12:49.054  2205  2205 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-12 11:12:49.054  2205  2205 I ConfigService: onBind returning config service
08-12 11:12:49.059  1031  1976 V SIM_STK : Menu title from STK is T-Mobile
08-12 11:12:49.062  2205  2205 I ConfigService: onDestroy
08-12 11:12:49.067  1580  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 11:12:49.067  1580  1652 D KeyguardModel: createShortcutInfo...
08-12 11:12:49.069  1580  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 11:12:49.069  1580  1652 D KeyguardModel: createShortcutInfo...
08-12 11:12:49.070  1819  6886 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-12 11:12:49.071  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-12 11:12:49.075  1580  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 11:12:49.075  1580  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 11:12:49.076  1580  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 11:12:49.076  1580  1652 D KeyguardModel: createShortcutInfo...
08-12 11:12:49.078  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 11:12:49.078  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 11:12:49.078  1580  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 11:12:49.078  1031  1031 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 11:12:49.078  1580  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 11:12:49.080  1580  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 11:12:49.080  1580  1652 D KeyguardModel: createShortcutInfo...
08-12 11:12:49.080  1031  1579 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-12 11:12:49.084  1580  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 11:12:49.084  1580  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-12 11:12:49.091  1580  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 11:12:49.091  1580  1652 D KeyguardModel: createShortcutInfo...
08-12 11:12:49.092  5964  6890 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-12 11:12:49.106  6030  6030 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-12 11:12:49.108  1580  1580 D KeyguardModel: handleShortcutListChanged...
08-12 11:12:49.108  1580  1580 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 11:12:49.123  1819  6894 I PeopleContactsSync: CP2 sync disabled
,08-12 11:12:49.140  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-12 11:12:49.141  1819  6893 W GmsApplication: Using Auth Proxy for data requests.
08-12 11:12:49.141  1819  4772 I Icing   : doRemovePackageData com.test.thalitest
08-12 11:12:49.146  2035  2035 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-12 11:12:49.152  1819  6893 W GmsApplication: Using Auth Proxy for data requests.
,08-12 11:12:49.155  6551  6551 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-12 11:12:49.169  2349  6896 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-12 11:12:49.178  1998  1998 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 11:12:49.178  1998  1998 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-12 11:12:49.179  1998  1998 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-12 11:12:49.183  6463  6463 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-12 11:12:49.204   324   389 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-12 11:12:49.205  1031  1046 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6899 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-12 11:12:49.206  3216  6901 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-12 11:12:49.249  1031  1101 I art     : Explicit concurrent mark sweep GC freed 8337(433KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.465ms total 281.653ms
,08-12 11:12:49.265  1031  1088 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 11:12:49.271  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-12 11:12:49.273  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 11:12:49.275  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-12 11:12:49.276  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-12 11:12:49.277  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-12 11:12:49.277  1031  1088 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-12 11:12:49.278  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-12 11:12:49.289  6899  6899 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-12 11:12:49.289  6899  6899 W LG Account v2.2: No ProfileInfo entries
08-12 11:12:49.290  6899  6899 I LG Account v2.2: isEnabled: false
08-12 11:12:49.290  6899  6899 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-12 11:12:49.290  6899  6899 I Feature : [Lifetracker]Country: EU
08-12 11:12:49.290  6899  6899 I Feature : [Lifetracker]Operator: OPEN
08-12 11:12:49.290  6899  6899 I Feature : [Lifetracker]Ranking support: false
08-12 11:12:49.290  6899  6899 I Feature : [Lifetracker]Comfort support: false
08-12 11:12:49.290  6899  6899 I Feature : [Lifetracker]Accessory: true
08-12 11:12:49.290  6899  6899 I Feature : [Lifetracker]Health device: true
08-12 11:12:49.290  6899  6899 I Feature : [Lifetracker]Extra Pedometer: false
08-12 11:12:49.290  6899  6899 I Feature : [Lifetracker]Blood glucose device: false
08-12 11:12:49.290  6899  6899 I Feature : [Lifetracker]Device Number: 3
08-12 11:12:49.291  6899  6899 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-12 11:12:49.294  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-12 11:12:49.294  2035  2187 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-12 11:12:49.294  2035  2187 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-12 11:12:49.295  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-12 11:12:49.295  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 11:12:49.309  1031  1940 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6921 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-12 11:12:49.309  1031  1940 I ActivityManager: Killing 6233:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-12 11:12:49.310  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-12 11:12:49.311  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 11:12:49.311  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 11:12:49.318  2035  2035 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-12 11:12:49.327  6847  6847 D AndroidRuntime: Shutting down VM
,08-12 11:12:49.345  1031  1094 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{101c17ad u0 com.lge.launcher2/.Launcher t5} time:201030
,08-12 11:12:49.346  2609  2609 D [Concierge]Service: onStartCommand(). Type : 8
08-12 11:12:49.346  2609  2609 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-12 11:12:49.348  2035  2035 D [Concierge]WidgetView: change position of spinner
08-12 11:12:49.348  1031  1983 W libprocessgroup: failed to open /acct/uid_10014/pid_6233/cgroup.procs: No such file or directory
08-12 11:12:49.349  2609  2609 D [Concierge]Service: Update widget ID : 11
08-12 11:12:49.351  2609  2609 D [Concierge]Service: onStartCommand(). Type : 0
08-12 11:12:49.351  2035  2035 I [Concierge]WidgetView: initWebView(). Time : 1470993169351
08-12 11:12:49.362  6921  6921 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 11:12:49.362  6921  6921 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-12 11:12:49.362  6921  6921 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 11:12:49.362  6921  6921 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,08-12 11:12:49.363  6921  6921 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 11:12:49.363  6921  6921 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-12 11:12:49.365  2035  2035 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 694539112
08-12 11:12:49.365  2035  2035 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-12 11:12:49.366  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-12 11:12:49.368  2035  2035 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@6bc4cfc
08-12 11:12:49.368  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-12 11:12:49.369  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 11:12:49.369  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 11:12:49.373  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-12 11:12:49.374  2035  2035 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
,08-12 11:12:49.374  2035  2035 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 11:12:49.375  2035  2035 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470992996994, New one : 1470993169351
08-12 11:12:49.375  2035  2035 D [Concierge]WidgetView: Unregister all receivers
08-12 11:12:49.375  2035  2035 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 11:12:49.375  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 11:12:49.377  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-12 11:12:49.378  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-12 11:12:49.378  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-12 11:12:49.379  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-12 11:12:49.380  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-12 11:12:49.386  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 11:12:49.386  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 11:12:49.421  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-12 11:12:49.430  2035  2035 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-12 11:12:49.430  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-12 11:12:49.432  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 11:12:49.446  6921  6921 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-12 11:12:49.451  2035  2035 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@10ff63ed time:201136
08-12 11:12:49.453  6921  6921 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-12 11:12:49.453  6921  6921 D HideNavigationAppsReceiver: replacing : false
08-12 11:12:49.455  6921  6921 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-12 11:12:49.456  6921  6921 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-12 11:12:49.456  6921  6921 D ButtonCombinationReceiver: replacing : false
,08-12 11:12:49.461  1031  1772 I ActivityManager: Killing 6327:com.android.defcontainer/u0a4 (adj 15): empty #17
08-12 11:12:49.546  1031  1983 W libprocessgroup: failed to open /acct/uid_10004/pid_6327/cgroup.procs: No such file or directory
,08-12 11:12:49.561  2035  2035 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-12 11:12:49.576  1031  1101 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6939 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-12 11:12:49.582  4579  6948 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-12 11:12:49.604  1031  1576 V SIM_STK : Menu title from STK is T-Mobile
,08-12 11:12:49.607  2035  2973 I GBoardtInterface: onReloaded()
08-12 11:12:49.609  2035  2035 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-12 11:12:49.610  1031  2046 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6958 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-12 11:12:49.615  3821  4463 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 11:12:49.619  4579  6948 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-12 11:12:49.620  3821  3837 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
--------- beginning of crash
08-12 11:12:49.622  4579  6948 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-12 11:12:49.622  4579  6948 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4579
08-12 11:12:49.622  4579  6948 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at csx.d(PG:186)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at cun.g(PG:594)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at cuw.Tg(PG:368)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at cuy.ub(PG:301)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-12 11:12:49.622  4579  6948 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 11:12:49.625  1907  1907 D ActionManagerService: notifyUserLog: 1000001
08-12 11:12:49.626  3821  4467 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 11:12:49.626  3821  4467 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 11:12:49.629  1907  1907 D ActionManagerService: notifyUserLog: 1000001
,08-12 11:12:49.632  3821  3837 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 11:12:49.633  4579  6948 I Process : Sending signal. PID: 4579 SIG: 9
08-12 11:12:49.634  3821  4467 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 11:12:49.634  3821  4467 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 11:12:49.634  3821  4467 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-12 11:12:49.634  3821  4467 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-12 11:12:49.636  1031  6976 E DropBoxManagerService: Can't write: system_app_crash
08-12 11:12:49.636  1031  6976 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-12 11:12:49.636  1031  6976 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-12 11:12:49.636  1031  6976 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:12:49.636  1031  6976 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:12:49.636  1031  6976 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:12:49.636  1031  6976 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-12 11:12:49.636  1031  6976 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-12 11:12:49.636  1031  6976 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:12:49.636  1031  6976 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:12:49.636  1031  6976 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:12:49.636  1031  6976 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-12 11:12:49.636  1031  6976 E DropBoxManagerService: 	... 5 more
08-12 11:12:49.637  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-12 11:12:49.637  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-12 11:12:49.639  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-12 11:12:49.639  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 11:12:49.641  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-12 11:12:49.641  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-12 11:12:49.646  1031  1544 D WifiService: Client connection lost with reason: 4
08-12 11:12:49.661  6958  6958 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2586 

```
