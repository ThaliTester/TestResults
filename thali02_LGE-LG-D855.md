#### Test 81738796795e45d_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-24 21:37:11.912  1940  2121 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
--------- beginning of main
08-24 21:37:11.914  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:37:11.914  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:37:11.916  3890  4002 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 21:37:11.917  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 21:37:11.922  6735  6735 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-24 21:37:54.573  6867  6867 D AndroidRuntime: 
08-24 21:37:54.573  6867  6867 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 21:37:54.579  6867  6867 D AndroidRuntime: CheckJNI is OFF
08-24 21:37:54.706  6867  6867 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-24 21:37:54.711  1037  1958 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 21:37:54.721  1940  1956 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-24 21:37:54.725  1037  1958 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-24 21:37:54.726  1037  1958 D ActivityManager: setTaskToReturnTo : TaskRecord{a28c0b9 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 21:37:54.726  1037  1958 D ActivityManager: setTaskToReturnTo : TaskRecord{a28c0b9 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 21:37:54.727  1037  1958 D WindowStateEx: AppWindowTokenEx init.. 
08-24 21:37:54.728   351   365 E GBMv2   : DFP En is all cleared set to be enabled
08-24 21:37:54.767  1037  1958 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6886 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 21:37:54.769  6867  6867 D AndroidRuntime: Shutting down VM
08-24 21:37:54.807  1940  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-24 21:37:54.808  1940  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{27d1e945 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-24 21:37:54.808  1940  3987 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-24 21:37:54.809  1940  3987 D SplitWindowPolicy: topRunningActivity=ActivityInfo{19d1889a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-24 21:37:54.854  6886  6886 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-24 21:37:54.957  6886  6886 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-24 21:37:54.966  6886  6886 I LibraryLoader: Loading: webviewchromium
08-24 21:37:54.969  6886  6886 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1769-1773)
,08-24 21:37:54.970  6886  6886 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 21:37:54.994  6886  6886 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1ab2b83b}
,08-24 21:37:54.997  6886  6886 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 21:37:54.997  6886  6886 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 21:37:55.005  6886  6886 I BrowserStartupController: Initializing chromium process, renderers=0
,08-24 21:37:55.006  6886  6886 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 21:37:55.016  6886  6886 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-24 21:37:55.017  6886  6886 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-24 21:37:55.018  6886  6886 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-24 21:37:55.020   332  2178 V AudioPolicyService: registerClient() client 0xb558a8e0, uid 10118
08-24 21:37:55.024  1037  1112 D BluetoothManagerService: Message: 20
08-24 21:37:55.024  1037  1112 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@173d6f7b:true
08-24 21:37:55.033  6886  6886 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 21:37:55.033  6886  6886 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 21:37:55.033  6886  6886 I Adreno-EGL: Build Date: 12/12/14 금
08-24 21:37:55.033  6886  6886 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 21:37:55.033  6886  6886 I Adreno-EGL: Remote Branch: 
08-24 21:37:55.033  6886  6886 I Adreno-EGL: Local Patches: 
08-24 21:37:55.033  6886  6886 I Adreno-EGL: Reconstruct Branch: 
08-24 21:37:55.104  6886  6917 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-24 21:37:55.111  6886  6886 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-24 21:37:55.127  6886  6886 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 21:37:55.132  6886  6886 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-24 21:37:55.135  6886  6886 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-24 21:37:55.138  6886  6886 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-24 21:37:55.138  6886  6886 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-24 21:37:55.150  6886  6886 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-24 21:37:55.156  6886  6886 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 21:37:55.156  6886  6886 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 21:37:55.195  6886  6929 D OpenGLRenderer: Render dirty regions requested: true
,08-24 21:37:55.195  6886  6929 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 21:37:55.202  6886  6929 D OpenGLRenderer: Enabling debug mode 0
,08-24 21:37:55.213  6886  6886 D Atlas   : Validating map...
08-24 21:37:55.220  1037  2050 D SplitWindow: check instance of lgWin Window{318ba69d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 21:37:55.266  6886  6927 D LgDataFeature: LgDataFeature() Constructor: none
,08-24 21:37:55.266  6886  6927 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 21:37:55.365  1037  1113 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +559ms (total +637ms)
,08-24 21:37:55.366  6886  6886 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@257bb846 time:292170
08-24 21:37:55.368  1037  1113 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6289cfe u0 com.test.thalitest/.MainActivity t6} time:292172
08-24 21:37:55.498  6886  6886 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-24 21:37:55.498  6886  6886 I chromium: 
,08-24 21:37:55.543  6886  6886 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 21:37:55.605  6886  6927 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-24 21:37:55.605  6886  6927 I chromium: 
,08-24 21:37:55.774  6886  6940 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435060736
,08-24 21:37:55.798  6886  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 21:37:55.798  6886  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 21:37:55.798  6886  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 21:37:55.798  6886  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 21:37:55.798  6886  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 21:37:55.798  6886  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2eda2a2a added. We now have 1 listener(s)
08-24 21:37:55.805  1037  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:37:55.808  6886  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-24 21:37:55.809  6886  6940 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 21:37:55.813  6886  6940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 21:37:55.814  6886  6940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 21:37:55.828  6886  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 21:37:55.828  6886  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 21:37:55.828  6886  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 21:37:55.828  6886  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-24 21:37:55.828  6886  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 21:37:55.828  6886  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 21:37:55.828  6886  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 21:37:55.828  6886  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 21:37:55.828  6886  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 21:37:55.828  6886  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 21:37:55.828  6886  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 21:37:55.828  6886  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 21:37:55.828  6886  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 21:37:55.828  6886  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 21:37:55.828  6886  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14bccf91 added. We now have 1 listener(s)
08-24 21:37:55.828  6886  6940 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 21:37:55.833  1037  1545 D WifiService: New client listening to asynchronous messages
08-24 21:37:55.843  6886  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 21:37:55.843  6886  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-24 21:37:55.848  6886  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 21:37:55.848  6886  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 21:37:55.848  6886  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-24 21:37:55.852  6886  6940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:37:55.853  1037  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:37:55.856  6886  6940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-24 21:37:55.866  6886  6940 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-24 21:37:55.867  6886  6940 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 21:37:55.867  6886  6940 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:37:55.867  6886  6940 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:37:55.867  6886  6940 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:37:55.867  6886  6940 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:37:55.867  6886  6940 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:37:55.867  6886  6940 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:37:55.867  6886  6940 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:37:55.867  6886  6940 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 21:37:55.867  6886  6940 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 21:37:55.868  6886  6940 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 21:37:55.872  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 21:37:55.876  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:37:55.912  6886  6886 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 21:37:56.117   351   368 E GBMv2   : DFP En is all cleared set to be enabled
08-24 21:37:56.117   351   368 E GBMv2   : Set value is all cleared set the max
08-24 21:37:56.117   351   368 I GBMv2   : DFP Enabled. Ignore VFP set
,08-24 21:37:56.784  6886  6943 W jxcore-log: Initializing JXcore engine
08-24 21:37:56.784  6886  6943 W jxcore-log: JXcore engine is ready
,08-24 21:37:56.814  6943  6943 W Thread-781: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7309]" dev="sockfs" ino=7309 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-24 21:37:56.814  6943  6943 W Thread-781: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-24 21:37:56.814  6943  6943 W Thread-781: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7537]" dev="sockfs" ino=7537 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-24 21:37:56.814  6943  6943 W Thread-781: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-24 21:37:56.814  6943  6943 W Thread-781: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33295]" dev="sockfs" ino=33295 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-24 21:37:56.831  6886  6943 W jxcore-log: Starting JXcore engine
08-24 21:37:56.905  6886  6943 W jxcore-log: Platform android
08-24 21:37:56.905  6886  6943 W jxcore-log: 
08-24 21:37:56.906  6886  6943 W jxcore-log: Process ARCH arm
08-24 21:37:56.906  6886  6943 W jxcore-log: 
,08-24 21:37:57.122  6886  6943 I jxcore-log: JXcore Cordova bridge is ready!
08-24 21:37:57.122  6886  6943 I jxcore-log: 
08-24 21:37:57.122  6886  6943 W jxcore-log: JXcore engine is started
,08-24 21:37:57.131  6886  6940 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-24 21:37:57.134  6886  6886 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-24 21:38:00.053  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 21:38:00.053  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-24 21:38:00.053  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 21:38:00.053  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-24 21:38:00.062  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 21:38:00.063  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-24 21:38:00.064  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-24 21:38:00.066  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 21:38:12.032  1604  1604 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
08-24 21:38:12.032  1604  1604 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 21:38:12.033  3890  4002 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 21:38:12.033  1940  2121 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 21:38:12.033  1940  2121 D LEDHandler: Battery Level Remaining: 100%
08-24 21:38:12.033  1940  2121 D LEDHandler: Battery Temp: 286, mChargingStatus=5, mChargingStop=false
08-24 21:38:12.033  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:12.033  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:12.034  1037  1545 D WifiController: battery changed pluggedType: 2
,08-24 21:38:12.034  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 21:38:12.035  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 21:38:12.035  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 21:38:12.047  6735  6735 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 21:38:12.996  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 21:38:12.996  6886  6943 I jxcore-log: 
,08-24 21:38:12.999  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 21:38:12.999  6886  6943 I jxcore-log: 
08-24 21:38:13.003  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 21:38:13.003  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:13.003  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:13.003  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:13.003  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:38:13.003  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:13.003  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:38:13.003  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:38:13.006  6886  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:13.008  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 21:38:13.008  6886  6943 I jxcore-log: 
08-24 21:38:13.010  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 21:38:13.010  6886  6943 I jxcore-log: 
,08-24 21:38:13.348  6886  6943 I jxcore-log: Running unit tests
08-24 21:38:13.348  6886  6943 I jxcore-log: 
,08-24 21:38:13.349  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 21:38:13.349  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e99f319 added. We now have 2 listener(s)
08-24 21:38:13.350  1037  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 21:38:13.352  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 21:38:13.352  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 21:38:13.352  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 21:38:13.352  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 21:38:13.352  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1df44fde added. We now have 2 listener(s)
08-24 21:38:13.352  6886  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 21:38:13.352  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 21:38:13.355  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:38:13.358  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 21:38:13.358  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:13.358  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:13.358  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:13.358  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:38:13.358  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:13.358  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:38:13.358  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:38:13.359  6886  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:13.359  6886  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 21:38:13.361  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:13.362  6886  6943 D ExecuteNativeTests: Running unit tests
08-24 21:38:13.362  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 21:38:13.523  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 21:38:13.523  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc added. We now have 3 listener(s)
08-24 21:38:13.524  1037  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:38:13.527  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 21:38:13.527  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 21:38:13.527  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 21:38:13.527  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 21:38:13.527  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 added. We now have 3 listener(s)
08-24 21:38:13.527  6886  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 21:38:13.528  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 21:38:13.531  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:38:13.536  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 21:38:13.536  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:13.536  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:13.536  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:13.536  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:38:13.536  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:13.536  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:38:13.536  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:38:13.537  6886  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:13.538  6886  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 21:38:13.542  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:13.542  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 21:38:13.544  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:13.544  6886  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 21:38:13.545  6886  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 21:38:13.545  6886  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 21:38:13.547  6886  6943 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-24 21:38:13.548  6886  6943 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 21:38:13.548  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 21:38:13.548  6886  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 21:38:13.548  6886  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 21:38:13.548  6886  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 21:38:13.551  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:13.552  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:13.552  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:38:13.553  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 21:38:13.553  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:13.553  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:38:13.553  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 21:38:13.553  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc removed from the list
08-24 21:38:13.553  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:13.553  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 removed from the list
08-24 21:38:13.553  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:13.553  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:13.554  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:13.554  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:13.556  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:13.556  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:38:13.556  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:13.556  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:13.558  6886  6943 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-24 21:38:13.559  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:13.559  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:13.559  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:38:13.559  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:13.559  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:13.559  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:13.559  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:13.559  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:13.559  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:13.559  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:13.559  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:13.559  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:13.559  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothMana,ger: release: The given listener does not exist in the list - probably already removed
08-24 21:38:13.559  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:13.560  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 21:38:13.560  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:38:13.560  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:13.560  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:13.569  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 21:38:13.569  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 21:38:13.569  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 21:38:13.569  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 21:38:13.569  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 21:38:13.569  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 21:38:13.569  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 21:38:13.569  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 21:38:13.569  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 21:38:13.569  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 21:38:13.570  6886  6943 D io.jxc,ore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 21:38:13.570  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 21:38:13.570  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:13.571  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:13.571  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:38:13.571  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:13.571  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:13.571  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:13.571  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:13.571  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:13.571  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:13.571  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:13.571  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:13.571  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:13.571  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:13.571  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 21:38:13.572  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:13.572  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:38:13.572  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:13.572  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:13.573  6886  6943 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 21:38:13.575  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:38:13.578  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 21:38:13.578  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:13.578  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:13.578  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:13.578  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:38:13.578  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:13.578  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:38:13.578  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 21:38:13.579  6886  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:13.579  6886  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 21:38:13.581  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:13.583  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:13.583  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 21:38:13.583  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 21:38:13.584  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-24 21:38:13.584  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:38:13.584  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 21:38:13.588  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 21:38:13.588  1037  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:38:13.594  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 21:38:13.601  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 21:38:13.604  6886  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-24 21:38:13.605  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 21:38:13.606  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:38:13.608  6886  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 21:38:13.608  6886  6943 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 21:38:18.620  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:18.620  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:18.620  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 21:38:18.627  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:18.627  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:18.628  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:38:18.628  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:18.628  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:18.628  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:18.628  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:18.628  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:23.630  6886  6943 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-24 21:38:23.644  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:38:23.651  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 21:38:23.651  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:23.651  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:23.651  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:23.651  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:38:23.651  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:23.651  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:38:23.651  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 21:38:23.653  6886  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:23.654  6886  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 21:38:23.656  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:23.657  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:23.658  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 21:38:23.658  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 21:38:23.658  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 21:38:23.658  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:38:23.658  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 21:38:23.664  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 21:38:23.666  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:38:23.668  6886  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 21:38:23.668  6886  6943 I io.jxcore.node.ConnectionHelper: start: OK
08-24 21:38:23.671  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:23.671  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:23.671  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:38:23.671  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:23.671  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:23.671  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:38:23.672  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
,08-24 21:38:23.672  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:23.672  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:23.672  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:23.672  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:23.672  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:23.672  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:23.673  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:23.673  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:38:23.676  6886  6943 D BluetoothLeScanner: could not find callback wrapper
,08-24 21:38:23.677  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:38:23.681  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:23.681  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:23.683  6886  6943 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 21:38:23.685  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:38:23.689  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 21:38:23.689  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:23.689  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:23.689  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:23.689  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:38:23.689  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:23.689  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:38:23.689  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 21:38:23.693  6886  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:23.693  6886  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 21:38:23.696  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:23.698  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:23.698  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 21:38:23.698  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 21:38:23.698  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 21:38:23.698  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:38:23.698  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 21:38:23.703  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 21:38:23.706  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:38:23.708  6886  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 21:38:23.709  6886  6943 I io.jxcore.node.ConnectionHelper: start: OK
08-24 21:38:28.709  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:28.709  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:28.710  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 21:38:33.720  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:33.720  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:33.720  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 21:38:33.728  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:33.728  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.728  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:38:33.728  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:33.728  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.728  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.728  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:33.729  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.731  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.731  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.734  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:33.734  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 21:38:33.739  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:38:33.739  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:38:33.739  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.739  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.740  6886  6943 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-24 21:38:33.741  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:33.741  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:33.741  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:38:33.742  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:33.742  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.742  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.742  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:33.742  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.742  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
,08-24 21:38:33.742  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:33.742  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.742  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.742  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.742  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.743  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:33.743  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:38:33.744  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:38:33.744  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:38:33.744  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.744  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.746  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 21:38:33.746  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:33.746  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:33.746  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:38:33.747  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:33.747  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.747  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.747  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:33.747  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.747  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.747  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:33.747  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.747  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.747  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.747  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.748  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:33.748  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 21:38:33.755  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:38:33.755  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:38:33.755  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.755  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.756  6886  6943 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-24 21:38:33.757  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:33.757  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:33.757  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:38:33.757  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:33.757  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.757  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.757  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:33.757  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.758  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.758  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:33.758  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.758  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.758  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.758  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.759  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:33.759  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:38:33.760  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:38:33.760  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:38:33.760  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.760  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.761  6886  6943 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-24 21:38:33.761  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:33.761  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:33.761  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:38:33.762  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:33.762  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.762  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.762  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:33.762  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.762  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.762  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:33.762  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.762  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.762  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.762  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.764  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:33.764  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 21:38:33.769  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:38:33.770  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:38:33.770  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.770  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.770  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 21:38:33.773  6886  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 21:38:33.773  6886  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 21:38:33.773  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 21:38:33.774  6886  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 21:38:33.774  6886  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 21:38:33.777  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 21:38:33.777  6886  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 21:38:33.777  6886  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 21:38:33.777  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:33.777  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:33.777  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 21:38:33.781  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:33.781  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.781  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.781  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:33.781  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.781  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.781  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:33.781  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.781  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.781  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.781  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.783  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:33.783  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:38:33.784  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:38:33.784  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:38:33.784  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.784  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.785  6886  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 21:38:33.785  6886  6943 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 21:38:33.785  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 21:38:33.792  6886  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-24 21:38:33.799  6886  6943 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-24 21:38:33.799  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 21:38:33.799  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 21:38:33.799  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 21:38:33.799  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 21:38:33.799  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 21:38:33.799  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 21:38:33.800  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 21:38:33.801  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 21:38:33.801  6886  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-24 21:38:33.802  6886  6943 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 21:38:33.802  6886  6943 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-24 21:38:33.803  6886  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 21:38:33.803  6886  6943 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 21:38:33.803  6886  6943 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-24 21:38:33.804  6886  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 21:38:33.804  6886  6943 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-24 21:38:33.804  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-24 21:38:33.806  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-24 21:38:33.808  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-24 21:38:33.808  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-24 21:38:33.809  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-24 21:38:33.809  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-24 21:38:33.809  6886  6943 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-24 21:38:33.809  6886  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 21:38:33.809  6886  6943 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-24 21:38:33.810  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:33.810  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:33.810  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 21:38:33.818  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:33.818  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.818  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.818  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-24 21:38:33.820  6886  6956 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 845)
08-24 21:38:33.827  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:33.827  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.827  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.827  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:33.827  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.827  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.827  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.827  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 21:38:33.831  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:33.831  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:38:33.832  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:38:33.832  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:38:33.832  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.832  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.833  6886  6943 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-24 21:38:33.833  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:33.833  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:33.833  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:38:33.836  6886  6957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 845
08-24 21:38:33.836  6886  6957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 845)
08-24 21:38:33.837  6886  6957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 845)
08-24 21:38:33.837  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:33.837  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.837  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.837  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:33.837  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.837  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.837  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:33.837  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.837  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.837  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.837  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.838  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:33.838  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:38:33.840  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:38:33.840  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:38:33.840  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.840  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSetti,ngs: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.841  6886  6943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-24 21:38:33.841  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:33.842  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:33.842  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 21:38:33.845  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:33.845  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.845  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.845  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:33.845  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.845  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.845  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:33.845  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.845  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.845  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.845  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.848  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:33.848  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:38:33.850  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:38:33.850  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:38:33.850  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.850  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.851  6886  6943 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-24 21:38:33.851  6886  6943 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-24 21:38:33.852  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 21:38:33.852  6886  6943 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-24 21:38:33.852  6886  6943 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 21:38:33.852  6886  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-24 21:38:33.852  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 21:38:33.852  6886  6943 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-24 21:38:33.852  6886  6943 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 21:38:33.852  6886  6943 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 21:38:33.852  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 21:38:33.85,2  6886  6943 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-24 21:38:33.853  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:33.853  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:33.853  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:38:33.856  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:33.856  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.856  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.856  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:33.857  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.857  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.857  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:33.857  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.857  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.857  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.857  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 21:38:33.862  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:33.862  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:38:33.863  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:38:33.863  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:38:33.863  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.863  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.864  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:33.864  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.864  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.864  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:33.864  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:33.864  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:33.864  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:33.864  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:33.864  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:33.932  6886  6956 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-24 21:38:33.936  6886  6956 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 845)
08-24 21:38:37.913  1037  3516 I LocationManagerService: remove 6ac60b1
08-24 21:38:37.914  1037  3516 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-24 21:38:37.914  1037  3516 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-24 21:38:37.922  1037  3516 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-24 21:38:37.925  1037  3516 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-24 21:38:37.927  1037  3516 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-24 21:38:38.865  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 21:38:38.871  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:38.871  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:38.872  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.872  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.872  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:38.872  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:38.872  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:38.873  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:38:38.874  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:38.874  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.874  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.875  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:38.875  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:38.875  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:38.875  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:38.875  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.875  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.875  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.875  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.880  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:38.880  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 21:38:38.883  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:38:38.883  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:38:38.883  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:38.884  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:38.886  6886  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-24 21:38:38.887  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:38:38.887  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-24 21:38:38.888  6886  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-24 21:38:38.889  6886  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-24 21:38:38.889  6886  6886 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-24 21:38:38.889  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-24 21:38:38.890  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 21:38:38.891  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:38.891  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-24 21:38:38.891  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-24 21:38:38.891  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-24 21:38:38.891  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.891  6886  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-24 21:38:38.893  6886  6973 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-24 21:38:38.893  6886  6973 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-24 21:38:38.897  6886  6886 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-24 21:38:38.898  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:38.898  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:38.898  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 21:38:38.898  6886  6943 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 21:38:38.898  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 21:38:38.900  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 21:38:38.901  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:38:38.901  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:38:38.902  6886  6943 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 21:38:38.902  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.902  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.903  6886  6943 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 21:38:38.903  6886  6886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 21:38:38.903  6886  6886 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-24 21:38:38.904  6886  6886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 21:38:38.904  6886  6886 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 21:38:38.904  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:38.904  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:38.904  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:38.904  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:38:38.905  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:38.905  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.905  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.905  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:38.905  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:38.905  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:38.905  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:38.905  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.905  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.905  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.905  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.906  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:38.907  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:38:38.907  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:38.907  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:38.908  6886  6943 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-24 21:38:38.913  6886  6943 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 21:38:38.913  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 21:38:38.915  6886  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 21:38:38.915  6886  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 21:38:38.916  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:38.916  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:38.916  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:38:38.917  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:38.917  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.919  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.919  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:38.919  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:38.919  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:38.919  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:38.919  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.919  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.919  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.919  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.922  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:38.923  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:38:38.923  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:38.923  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
,08-24 21:38:38.927  1037  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:38:38.928  1037  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:38:38.929  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:38:38.929  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:38.930  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:38.930  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:38:38.930  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:38.930  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.930  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.930  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:38.930  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:38.930  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:38.930  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:38.930  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.931  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.931  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.931  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.932  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:38.932  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:38:38.932  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:38.932  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:38.933  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:38:38.933  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:38:38.933  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:38:38.935  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:38:38.935  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.935  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.935  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4408bc not in the list
08-24 21:38:38.935  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:38.935  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:38.935  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:38.935  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.935  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.935  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:38.935  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:38.937  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:38:38.937  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:38:38.937  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:38.937  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e093045 not in the list
08-24 21:38:38.938  6886  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-24 21:38:38.938  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 21:38:38.939  6886  6943 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-24 21:38:38.939  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 21:38:38.939  6886  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-24 21:38:38.939  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 21:38:38.941  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 21:38:38.941  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-24 21:38:38.942  6886  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-24 21:38:38.943  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 21:38:38.943  6886  6943 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-24 21:38:38.943  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 21:38:38.943  6886  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-24 21:38:38.943  6886  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-24 21:38:38.944  6886  6943 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-24 21:38:38.944  6886  6943 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-24 21:38:38.945  6886  6943 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-24 21:38:38.945  6886  6943 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-24 21:38:38.945  6886  6943 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-24 21:38:38.945  6886  6943 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-24 21:38:38.956  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 21:38:38.956  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e082bf2 added. We now have 3 listener(s)
08-24 21:38:38.956  6886  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 21:38:38.959  6886  6943 D BluetoothAdapter: enable(): BT is already enabled..!
,08-24 21:38:38.961  1037  1884 D WifiServiceImplEx: setWifiEnabled: true pid=6886, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 21:38:38.962  1037  1884 D WifiService: setWifiEnabled: true pid=6886, uid=10118
08-24 21:38:38.962  1037  1884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 21:38:39.405  6886  6886 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 21:38:40.482  1037  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=440719139, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,08-24 21:38:40.497  1037  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3d068ac3 type 2 when 337269 com.google.android.gms} when 337269
,08-24 21:38:40.535  2600  2600 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 21:38:40.563  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=440719139 [*alarm*], flags=0x0
,08-24 21:38:40.604  1815  1815 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-24 21:38:40.609  2196  2196 I ConfigService: onCreate
08-24 21:38:40.610  2196  2196 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-24 21:38:40.612  1815  6975 I ConfigFetchService: running network task: configservice_periodic
08-24 21:38:40.617  1815  6975 I ConfigFetchService: launchTask
,08-24 21:38:40.623  2196  2196 I ConfigService: onBind returning update interface
08-24 21:38:40.624  1815  1815 I ConfigFetchService: service connected
08-24 21:38:40.625  2196  2196 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-24 21:38:40.625  2196  2196 I ConfigService: onBind returning config service
08-24 21:38:40.626  1815  1815 I ConfigClient: service connected
08-24 21:38:43.970  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 21:38:43.971  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60aa243 added. We now have 4 listener(s)
08-24 21:38:43.971  6886  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 21:38:43.983  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:43.983  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60aa243 removed from the list
08-24 21:38:43.983  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:43.983  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:43.983  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:43.984  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 21:38:43.984  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12c9b0c0 added. We now have 4 listener(s)
08-24 21:38:43.984  6886  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 21:38:43.986  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:38:43.986  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12c9b0c0 removed from the list
08-24 21:38:43.986  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:38:43.986  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:38:43.986  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:38:43.987  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 21:38:43.987  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@283af1f9 added. We now have 4 listener(s)
08-24 21:38:43.987  6886  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 21:38:43.991  1037  1977 D WifiServiceImplEx: setWifiEnabled: false pid=6886, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-24 21:38:43.994  1037  1977 D WifiService: setWifiEnabled: false pid=6886, uid=10118
08-24 21:38:43.994  1037  1977 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 21:38:44.013  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 21:38:44.013  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 21:38:44.014  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-24 21:38:44.015  1037  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-24 21:38:44.016  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-24 21:38:44.016  1037  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-24 21:38:44.017  1037  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-24 21:38:44.017  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-24 21:38:44.017  1037  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-24 21:38:44.017  1037  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 21:38:44.017  1037  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 21:38:44.018  1037  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 21:38:44.019  1037  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 21:38:44.020  1037  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:38:44.021  1037  1995 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2aa253b1 mBinding = false
,08-24 21:38:44.028  1037  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 21:38:44.028  1037  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:44.028  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:44.029  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 21:38:44.029  2736  2736 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 21:38:44.030  1037  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 21:38:44.030  1037  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 21:38:44.031  1037  1539 D WifiNative-wlan0: SET ps 1: returned true
08-24 21:38:44.032  1037  2846 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:44.037   328   895 D CommandListener: Clearing all IP addresses on wlan0
,08-24 21:38:44.051  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 21:38:44.051  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 21:38:44.051  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-24 21:38:44.052  1037  1112 D BluetoothManagerService: Message: 2
08-24 21:38:44.053  1037  1112 D BluetoothManagerService: Sending off request.
08-24 21:38:44.053  3890  4457 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-24 21:38:44.056  3890  3971 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-24 21:38:44.056  3890  3971 D BluetoothAdapterProperties: Setting state to 13
08-24 21:38:44.056  3890  3971 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 21:38:44.066  3890  3971 D BluetoothAdapterProperties: onBluetoothDisable()
08-24 21:38:44.066  3890  3971 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-24 21:38:44.073  3890  3975 D BluetoothAdapterProperties: Scan Mode:20
08-24 21:38:44.074  3890  3971 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-24 21:38:44.074  3890  3971 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 21:38:44.077  3890  4208 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 21:38:44.077  3890  4203 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-24 21:38:44.077  3890  4203 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 21:38:44.077  3890  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-24 21:38:44.077  3890  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-24 21:38:44.077  3890  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-24 21:38:44.077  3890  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-24 21:38:44.077  3890  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-24 21:38:44.077  3890  4203 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-24 21:38:44.079  3890  4230 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-24 21:38:44.080  3890  4250 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 21:38:44.086  3890  4252 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 21:38:44.087  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-24 21:38:44.088  3890  4081 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-24 21:38:44.089  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 21:38:44.089  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 21:38:44.089  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 21:38:44.089  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 21:38:44.089  3890  4081 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 21:38:44.089  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 21:38:44.089  3890  4081 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 21:38:44.089  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 21:38:44.089  3890  4081 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 21:38:44.089  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-24 21:38:44.089  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-24 21:38:44.089  3890  4081 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 21:38:44.103  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:44.103  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:44.103  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:44.103  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:44.103  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:44.103  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:44.103  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:44.103  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:38:44.103  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 21:38:44.115  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:44.115  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 21:38:44.123  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:44.123  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:44.123  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:44.123  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:44.123  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:44.123  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:44.123  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:44.123  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:38:44.123  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:38:44.125  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:44.125  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:44.125  1037  1112 D BluetoothManagerService: Message: 60
08-24 21:38:44.129  1037  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,08-24 21:38:44.136  1037  1112 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-24 21:38:44.154  1037  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-24 21:38:44.155  1037  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-24 21:38:44.176  1037  1885 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-24 21:38:44.176  1037  1097 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7020 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-24 21:38:44.178  1037  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:44.178  1037  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:44.178  1037  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-24 21:38:44.178  1037  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:44.178  1037  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-24 21:38:44.181  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:38:44.181  1037  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:44.181  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:44.181  1037  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2b3f4b51
,08-24 21:38:44.181  1037  1538 D LGWifiP2pService: P2pDisablingState
08-24 21:38:44.182  1037  1538 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:44.182  1037  1538 D LGWifiP2pService: p2p socket connection lost
08-24 21:38:44.182  1037  1538 D LGWifiP2pService: P2pDisabledState
08-24 21:38:44.183  1037  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:44.183  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:44.184  1037  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:44.184  1037  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:44.185  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:44.185  1037  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:44.186  1037  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 21:38:44.187  1037  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:44.187  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:44.187  1037  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:44.188  1037  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-24 21:38:44.188  1037  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:44.188  1037  1538 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:44.188  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 21:38:44.189  2736  2736 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 21:38:44.189  1037  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 21:38:44.189  1037  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 21:38:44.189  1037  1539 D WifiNative-wlan0: SET ps 1: returned true
,08-24 21:38:44.203  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:38:44.204  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-24 21:38:44.206  3890  3890 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:38:44.206  3890  3890 D BluetoothMapService: STATE_TURNING_OFF
08-24 21:38:44.206  3890  3890 V BluetoothMapService: Handler(): got msg=4
08-24 21:38:44.206  3890  3890 D BluetoothMapService: MAP Service closeService in
08-24 21:38:44.206  3890  3890 D BluetoothMapMasInstance: MAP Service shutdown
08-24 21:38:44.206  3890  3890 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 21:38:44.206  3890  3890 V BluetoothMapService: MAP Service closeService out
08-24 21:38:44.207  3890  3890 V BtOppService: Receiver DISABLED_ACTION 
08-24 21:38:44.207  3890  3890 I BtOppRfcommListener: stopping Accept Thread
08-24 21:38:44.207  3890  3890 V BtOppRfcommListener: close mBtServerSocket
08-24 21:38:44.207  3890  3890 V BtOppRfcommListener: waiting for thread to terminate
08-24 21:38:44.208  3890  4230 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 21:38:44.208  3890  3890 V BtOppRfcommListener: done waiting for thread to terminate
08-24 21:38:44.208  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:44.209  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 21:38:44.209  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:44.209  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:44.209  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:44.209  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:44.209  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:38:44.209  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:38:44.209  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:38:44.211  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:44.212  6886  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:38:44.212  6886  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 21:38:44.213  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 21:38:44.213  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:44.213  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:44.213  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:44.213  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:44.213  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:44.213  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:38:44.213  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:38:44.213  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:38:44.213  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:44.213  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:38:44.215  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:44.215  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:44.215  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:44.215  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:44.215  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:44.215  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:44.215  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:38:44.215  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:38:44.215  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:38:44.216  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:44.216  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:38:44.217   328   895 D CommandListener: Clearing all IP addresses on wlan0
08-24 21:38:44.217  1037  1546 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-24 21:38:44.217  1037  1546 D DSQN    : disableDataServiceNotify
08-24 21:38:44.218  1037  1546 D DSQN    : stop dsqn bin
08-24 21:38:44.218   328  7042 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-24 21:38:44.219  1037  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-24 21:38:44.219  1037  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-24 21:38:44.219  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:44.226  1037  1546 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-24 21:38:44.226  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:44.226  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:38:44.226  1037  15,46 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:38:44.227  1037  1546 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-24 21:38:44.227  1037  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:44.227  1037  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:44.227  1037  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-24 21:38:44.227  1037  1546 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-24 21:38:44.227  1037  1546 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-24 21:38:44.227  1037  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 21:38:44.227  1604  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-24 21:38:44.248  1037  1097 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7043 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-24 21:38:44.249  3890  3890 V BtOppService: onDestroy
08-24 21:38:44.249  1037  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-24 21:38:44.249  1037  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:44.250  1037  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 21:38:44.250  1037  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:44.250  1037  1546 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:44.250  1037  1546 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:44.250  1037  1539 D WifiNative-p2p0: TERMINATE: returned true
08-24 21:38:44.251  1037  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 21:38:44.251  1037  1539 E WifiStateMachine: useWiFiOffloading() : false
08-24 21:38:44.251  1037  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 21:38:44.251  1037  1546 D NetworkManagementService: Removing idletimer
08-24 21:38:44.251  1037  1546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:44.252  1037  1546 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-24 21:38:44.252  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:44.252  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 21:38:44.255  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-24 21:38:44.256  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:44.256  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:44.256  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 21:38:44.257  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-24 21:38:44.258  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-24 21:38:44.258  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:44.258  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:44.258  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 21:38:44.258  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
08-24 21:38:44.258  1037  1037 D RttService: SCAN_AVAILABLE : 1
08-24 21:38:44.258  1037  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:44.258  1037  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:44.258  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:44.259  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:44.259  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:44.259  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:44.259  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:38:44.259  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:44.259  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:38:44.259  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:38:44.259  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 21:38:44.260  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-24 21:38:44.260  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 21:38:44.260  1940  1940 D WfdsService: WifiP2pState is changed : false
08-24 21:38:44.260  1940  2383 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-24 21:38:44.260  1940  2383 D WfdsService: Set the WFDS Monitor: false
08-24 21:38:44.261  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:44.261  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:44.261  1940  2383 D WfdsMonitor: WFDS Monitor is stopped
08-24 21:38:44.261  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 21:38:44.261  1940  2383 D WfdsService: STATE : WfdsDisabledState - enter
08-24 21:38:44.261  1940  2778 D CtrlSupplicant: Received on exit socket, terminate
08-24 21:38:44.261  1940  2778 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-24 21:38:44.261  1940  2778 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-24 21:38:44.261  1940  2778 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-24 21:38:44.261  1940  2383 W WfdsService: DefaultState - msg [9445378] is not handled
08-24 21:38:44.261  1940  2386 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-24 21:38:44.262  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:44.262  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:38:44.263  1037  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 21:38:44.264   355   355 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 750us total 15.854ms
08-24 21:38:44.266  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:44.267  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-24 21:38:44.267  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 21:38:44.267  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 21:38:44.267  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 21:38:44.268  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:44.268  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:38:44.269  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:44.270  1037  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:44.270  1037  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 21:38:44.270  1037  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 21:38:44.270  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-24 21:38:44.270  3890  3890 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-24 21:38:44.274  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-24 21:38:44.274  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-24 21:38:44.274  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:38:44.274  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-24 21:38:44.275  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 21:38:44.275  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 21:38:44.275  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-24 21:38:44.277   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 272us total 13.255ms
08-24 21:38:44.281  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:44.281  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:44.281  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:44.281  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:44.281  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:38:44.281  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:44.281  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:38:44.281  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:38:44.281  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 21:38:44.281  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:44.282  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:38:44.284  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:44.284  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:44.284  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:44.284  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:44.284  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:38:44.284  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:44.284  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:38:44.284  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:38:44.284  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 21:38:44.285  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:44.285  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:38:44.286  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:44.289   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 254us total 11.587ms
08-24 21:38:44.302  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:44.302  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:38:44.306  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:44.307  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-24 21:38:44.307  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:38:44.307  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:44.320  7043  7043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 21:38:44.320  7043  7043 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-24 21:38:44.321  7043  7043 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 21:38:44.321  7043  7043 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,08-24 21:38:44.322  7043  7043 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 21:38:44.323  7043  7043 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-24 21:38:44.323  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 21:38:44.324  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:44.324  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:44.332  2736  2736 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-24 21:38:44.332  2736  2736 I wpa_supplicant: monitor socket send errors count : 1
08-24 21:38:44.332  2736  2736 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-2\x00 that cannot receive messages
,08-24 21:38:44.333  1037  2774 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-24 21:38:44.333  1037  2774 D WifiMonitor: Dropping event because (p2p0) is stopped
08-24 21:38:44.337  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 21:38:44.338  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:44.338  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:44.339  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:44.347  7020  7020 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-24 21:38:44.347  7020  7020 W LG Account v2.2: No ProfileInfo entries
08-24 21:38:44.347  7020  7020 I LG Account v2.2: isEnabled: false
08-24 21:38:44.347  7020  7020 I Feature : [Lifetracker]ver: 4.21.112(40211120)
,08-24 21:38:44.347  7020  7020 I Feature : [Lifetracker]Country: EU
08-24 21:38:44.347  7020  7020 I Feature : [Lifetracker]Operator: OPEN
08-24 21:38:44.347  7020  7020 I Feature : [Lifetracker]Ranking support: false
08-24 21:38:44.348  7020  7020 I Feature : [Lifetracker]Comfort support: false
08-24 21:38:44.348  7020  7020 I Feature : [Lifetracker]Accessory: true
08-24 21:38:44.348  7020  7020 I Feature : [Lifetracker]Health device: true
08-24 21:38:44.348  7020  7020 I Feature : [Lifetracker]Extra Pedometer: false
08-24 21:38:44.348  7020  7020 I Feature : [Lifetracker]Blood glucose device: false
08-24 21:38:44.348  7020  7020 I Feature : [Lifetracker]Device Number: 3
08-24 21:38:44.355  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:38:44.358  1037  2846 D DhcpStateMachine: StoppedState
08-24 21:38:44.358  1037  2846 D DhcpStateMachine: StoppedState{ when=-169ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 21:38:44.370  2736  2736 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 21:38:44.370  1037  2774 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-24 21:38:44.370  1037  2774 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 21:38:44.370  1037  2774 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 21:38:44.371  1037  2774 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-24 21:38:44.371  2736  2736 W wpa_supplicant: USIM:  scard_deinit function
,08-24 21:38:44.371  1037  2774 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 21:38:44.371  1037  2774 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 21:38:44.371  1037  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=341161
08-24 21:38:44.372  1037  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=341162
08-24 21:38:44.373  1037  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=341162  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-24 21:38:44.373  1037  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=341163  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-24 21:38:44.373  1037  1112 D Tethering: InitialState.processMessage what=4
08-24 21:38:44.403  1037  1977 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7065 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-24 21:38:44.405  1037  1977 I ActivityManager: Killing 6310:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-24 21:38:44.438  1037  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-24 21:38:44.440  1037  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-24 21:38:44.441  1037  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-24 21:38:44.441  1037  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:38:44.441  1037  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:38:44.443  1037  1885 W libprocessgroup: failed to open /acct/uid_10014/pid_6310/cgroup.procs: No such file or directory
08-24 21:38:44.467  2736  2736 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-24 21:38:44.468  1037  2774 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,08-24 21:38:44.468  1037  2774 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-24 21:38:44.468  1037  2774 D WifiMonitor: Disconnecting from the supplicant, no more events
08-24 21:38:44.469  1037  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-24 21:38:44.491  7065  7065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-24 21:38:44.495  7065  7065 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 21:38:44.495  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 21:38:44.497  1037  1052 I ActivityManager: Killing 6475:com.android.defcontainer/u0a4 (adj 15): empty #17
08-24 21:38:44.520  7043  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-24 21:38:44.572  1037  1885 W libprocessgroup: failed to open /acct/uid_10004/pid_6475/cgroup.procs: No such file or directory
,08-24 21:38:44.584  3890  3890 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 21:38:44.584  3890  3890 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:38:44.584  3890  3890 V BluetoothPbapReceiver: ***********state = 13
08-24 21:38:44.585  1037  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{338faab3 type 2 when 341363 com.google.android.gms} when 341363
08-24 21:38:44.586  3890  3890 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-24 21:38:44.590  3890  3890 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:38:44.590  3890  3890 V BluetoothPbapService: state: 13
08-24 21:38:44.590  1940  1940 D WfdsService: Supplicant Connection state is changed : false
08-24 21:38:44.590  1037  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-24 21:38:44.590  3890  3890 V BluetoothPbapService: Pbap Service closeService in
08-24 21:38:44.590  1037  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 21:38:44.590  1037  1539 E WifiStateMachine: useWiFiOffloading() : false
08-24 21:38:44.590  1037  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 21:38:44.590  1940  2383 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-24 21:38:44.590  1940  2383 D WfdsService: Set the WFDS Monitor: false
08-24 21:38:44.590  1940  2383 D WfdsMonitor: WFDS Monitor is stopped
08-24 21:38:44.593  3890  3890 V BluetoothPbapService: successfully stopped pbap service
08-24 21:38:44.593  3890  3890 V BluetoothPbapService: Pbap Service closeService out
08-24 21:38:44.593  3890  3890 V BluetoothPbapService: Pbap Service onDestroy
,08-24 21:38:44.593  3890  3890 V BluetoothPbapService: Pbap Service closeService in
08-24 21:38:44.593  3890  3890 V BluetoothPbapService: Pbap Service closeService out
08-24 21:38:44.593  3890  3890 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-24 21:38:44.594  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 21:38:44.595  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:44.601  2504  2504 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:44.601  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 21:38:44.602  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 21:38:44.604  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 21:38:44.604  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-24 21:38:44.605  1037  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-24 21:38:44.605  1037  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-24 21:38:44.608  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:44.617  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:38:44.643  7043  7043 D LgDataFeature: LgDataFeature() Constructor: none
08-24 21:38:44.644  7043  7043 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 21:38:44.652  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:44.660  1037  1112 D BluetoothManagerService: Message: 20
08-24 21:38:44.660  1037  1112 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11bec7e9:true
,08-24 21:38:44.670  1037  1112 D BluetoothManagerService: Message: 30
,08-24 21:38:44.680  1037  1112 D BluetoothManagerService: Message: 30
,08-24 21:38:44.685  7043  7043 D LocalBluetoothProfileManager: Adding local MAP profile
08-24 21:38:44.686  7043  7043 D BluetoothMap: Create BluetoothMap proxy object
08-24 21:38:44.687  1037  1112 D BluetoothManagerService: Message: 30
08-24 21:38:44.699  1037  1112 D BluetoothManagerService: Message: 30
,08-24 21:38:44.703  7043  7043 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-24 21:38:44.705  7043  7043 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-24 21:38:44.731  7043  7043 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-24 21:38:44.737  7043  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-24 21:38:44.753  7043  7043 D DockEventReceiver: finishStartingService: stopping service
,08-24 21:38:44.772  7043  7043 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-24 21:38:44.777  7043  7043 D BluetoothInputDevice: Proxy object connected
08-24 21:38:44.779  7043  7043 D HidProfile: Bluetooth service connected
08-24 21:38:44.780  7043  7043 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 21:38:44.780  7043  7043 D PanProfile: Bluetooth service connected
08-24 21:38:44.782  7043  7043 D BluetoothMap: Proxy object connected
08-24 21:38:44.782  7043  7043 D MapProfile: Bluetooth service connected
08-24 21:38:44.782  7043  7043 D BluetoothMap: getConnectedDevices()
08-24 21:38:44.783  7043  7043 D BluetoothMap: Bluetooth is Not enabled
08-24 21:38:44.783  7043  7043 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-24 21:38:44.785  7043  7043 D BluetoothPermissionRequest: onReceive
,08-24 21:38:44.790  7043  7043 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-24 21:38:44.800  1037  1957 I ActivityManager: Killing 6602:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-24 21:38:44.804  7043  7043 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 21:38:44.830  1037  1885 W libprocessgroup: failed to open /acct/uid_10008/pid_6602/cgroup.procs: No such file or directory
08-24 21:38:44.831  3890  3890 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-24 21:38:44.831  3890  3890 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-24 21:38:44.833  3890  3890 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-24 21:38:44.841  3890  3890 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:38:44.841  3890  3890 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-24 21:38:44.843  3890  3890 V BluetoothFtpService: Ftp Service onStartCommand
08-24 21:38:44.843  3890  3890 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-24 21:38:44.843  3890  3890 V BluetoothFtpService: Ftp Service closeService
08-24 21:38:44.844  3890  3890 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-24 21:38:44.903  1037  1995 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7096 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-24 21:38:44.907  3890  3890 V BluetoothFtpService: successfully stopped ftp service
08-24 21:38:44.908  3890  3890 V BluetoothFtpService: Ftp Service onDestroy
,08-24 21:38:44.908  3890  3890 V BluetoothFtpService: Ftp Service closeService
,08-24 21:38:44.914  3890  3890 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 21:38:44.914  3890  3890 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 21:38:44.914  3890  3890 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 21:38:44.914  3890  3890 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:38:44.914  3890  3890 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-24 21:38:44.915  3890  3890 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-24 21:38:44.916  3890  3890 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:38:44.916  3890  3890 V BluetoothSapService: state: 13
08-24 21:38:44.917  3890  3890 V BluetoothSapService: Stopping SAP server process
08-24 21:38:44.918  3890  3890 V BluetoothSapService: Sap Service closeSapService in
08-24 21:38:44.918  3890  3890 V BluetoothSapService: Close listen Socket : 
08-24 21:38:44.918  3890  3890 V BluetoothSapService: Close rfcomm Socket : 
08-24 21:38:44.918  3890  3890 V BluetoothSapService: Close sapd  Socket : 
08-24 21:38:44.971  1037  1995 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7113 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-24 21:38:44.977  3890  3890 V BluetoothSapService: Sap Service closeSapService out
08-24 21:38:44.978  3890  3890 V BluetoothSapService: Sap Service onDestroy
08-24 21:38:44.978  3890  3890 V BluetoothSapService: Sap Service closeSapService in
08-24 21:38:44.978  3890  3890 V BluetoothSapService: Close listen Socket : 
08-24 21:38:44.978  3890  3890 V BluetoothSapService: Close rfcomm Socket : 
08-24 21:38:44.978  3890  3890 V BluetoothSapService: Close sapd  Socket : 
08-24 21:38:44.979  3890  3890 V BluetoothSapService: Sap Service closeSapService out
08-24 21:38:45.002  7096  7096 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-24 21:38:45.028  7096  7096 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-24 21:38:45.053  7113  7113 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-24 21:38:45.072  1037  1922 I ActivityManager: Killing 6107:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-24 21:38:45.074  7096  7096 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-24 21:38:45.074  7096  7096 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-24 21:38:45.075  7096  7096 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-24 21:38:45.075  7096  7096 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-24 21:38:45.076  7096  7096 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-24 21:38:45.078  7096  7096 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-24 21:38:45.087  7096  7096 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-24 21:38:45.094  3890  4081 W bt-btif : ag scb idx 1 not allocated
08-24 21:38:45.094  3890  3975 D bt_hci_bdroid: cleanup
08-24 21:38:45.094  3890  4081 E bt-btif : BTA AG is already disabled, ignoring ...
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 21:38:45.094  3890  4193 I bt_userial_mct: exiting userial_read_thread
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 21:38:45.094  3890  4193 D bt_userial_mct: Leaving userial_evt_read_thread()
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 21:38:45.094  3890  4081 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 21:38:45.094  3890  4081 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 21:38:45.094  3890  3975 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-24 21:38:45.095  3890  4084 I bt_lpm  : LPM is already off!!!
08-24 21:38:45.095  3890  4084 I bt_vendor: hw_epilog_process
08-24 21:38:45.095  3890  3975 D bt_hci_bdroid: cleanup Finalizing cleanup
08-24 21:38:45.095  3890  3975 D bt_userial_mct: userial_close
08-24 21:38:45.095  3890  3975 E bt_userial_mct: pthread_join() FAILED result:3
08-24 21:38:45.095  3890  3975 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-24 21:38:45.119  1037  1886 W libprocessgroup: failed to open /acct/uid_10011/pid_6107/cgroup.procs: No such file or directory
,08-24 21:38:45.126  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:38:45.131  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:38:45.131  3890  3975 D bt_hci_bdroid: set_power 0
08-24 21:38:45.131  3890  3975 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-24 21:38:45.132  3890  3975 I bt_vendor: bluetooth satus is on
08-24 21:38:45.132  3890  3975 I bt_vendor: bt-vendor : resetting BT status
08-24 21:38:45.132  3890  3975 I bt_vendor: Starting hciattach daemon
08-24 21:38:45.132  3890  3975 I bt_vendor: try to set false
08-24 21:38:45.134  3890  3975 I bt_vendor: Starting hciattach daemon
08-24 21:38:45.134  3890  3975 I bt_vendor: try to set false
08-24 21:38:45.136  3890  3975 I bt_vendor: cleanup
,08-24 21:38:45.137  3890  4081 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-24 21:38:45.137  3890  3975 I GKI_LINUX: GKI_exit_task 0 done
08-24 21:38:45.137  3890  3975 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-24 21:38:45.140  3890  3971 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-24 21:38:45.142  3890  3890 D HeadsetService: Received stop request...Stopping profile...
08-24 21:38:45.143  3890  3890 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-24 21:38:45.143  3890  3890 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 21:38:45.143  3890  3890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adc9b58
08-24 21:38:45.143  3890  4002 D HeadsetStateMachine: Exit Disconnected: -1
08-24 21:38:45.144  1037  1037 D BluetoothHeadset: Proxy object disconnected
08-24 21:38:45.144  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-24 21:38:45.145  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-24 21:38:45.145  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-24 21:38:45.145  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-24 21:38:45.145  3890  3890 D A2dpService: Received stop request...Stopping profile...
08-24 21:38:45.146  3890  3890 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-24 21:38:45.146  3890  4064 D A2dpStateMachine: Exit Disconnected: -1
08-24 21:38:45.149  3890  3890 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-24 21:38:45.149  3890  3890 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 21:38:45.149  3890  3890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adc9b58
,08-24 21:38:45.152  1037  1037 D BluetoothA2dp: Proxy object disconnected
08-24 21:38:45.152  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-24 21:38:45.152  3890  3890 D HidService: Received stop request...Stopping profile...
08-24 21:38:45.152  3890  3890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adc9b58
08-24 21:38:45.152  3890  3971 D BluetoothAdapterState: Stopping profile services that were post enabled
08-24 21:38:45.153  7043  7043 D BluetoothInputDevice: Proxy object disconnected
08-24 21:38:45.154  7043  7043 D HidProfile: Bluetooth service disconnected
08-24 21:38:45.154  3890  3890 D HeadsetStateMachine: Unbinding service...
08-24 21:38:45.154  3890  3890 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 21:38:45.154  3890  3890 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 21:38:45.155  3890  3890 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 21:38:45.155  3890  3890 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 21:38:45.155  3890  3890 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-24 21:38:45.155  3890  3890 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 21:38:45.155  3890  3890 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-24 21:38:45.155  3890  3890 D HealthService: Received stop request...Stopping profile...
08-24 21:38:45.156  3890  3890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adc9b58
08-24 21:38:45.157  3890  3890 D PanService: Received stop request...Stopping profile...
08-24 21:38:45.157  3890  3890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adc9b58
08-24 21:38:45.158  3890  3890 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 21:38:45.158  7043  7043 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 21:38:45.158  7043  7043 D PanProfile: Bluetooth service disconnected
08-24 21:38:45.159  3890  3890 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 21:38:45.159  3890  3890 D BtGatt.GattService: stop()
08-24 21:38:45.159  3890  3890 D BtGatt.AdvertiseManager: advertise clients cleared
08-24 21:38:45.160  3890  3890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adc9b58
08-24 21:38:45.161  3890  3890 D BluetoothMapService: Received stop request...Stopping profile...
08-24 21:38:45.161  3890  3890 D BluetoothMapService: stop()
08-24 21:38:45.162  3890  3890 D BluetoothMapEmailAppObserver: deinitObservers()
08-24 21:38:45.162  3890  3890 D BluetoothMapEmailAppObserver: removeReceiver()
08-24 21:38:45.163  3890  3890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adc9b58
,08-24 21:38:45.166  3890  3890 I BluetoothA2dpServiceJni: cleanupNative
08-24 21:38:45.166  3890  4065 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-24 21:38:45.166  7043  7043 D BluetoothMap: Proxy object disconnected
08-24 21:38:45.166  7043  7043 D MapProfile: Bluetooth service disconnected
08-24 21:38:45.167  3890  3890 I GKI_LINUX: GKI_exit_task 2 done
08-24 21:38:45.167  3890  3890 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-24 21:38:45.167  3890  3890 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 21:38:45.167  3890  3890 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 21:38:45.167  3890  3890 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 21:38:45.167  3890  3890 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 21:38:45.167  3890  3890 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 21:38:45.168  3890  3890 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 21:38:45.168  3890  3890 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 21:38:45.169  3890  3890 V BluetoothMapService: Handler(): got msg=4
08-24 21:38:45.169  3890  3890 D BluetoothMapService: MAP Service closeService in
08-24 21:38:45.169  3890  3890 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 21:38:45.169  3890  3890 V BluetoothMapService: MAP Service closeService out
08-24 21:38:45.170  3890  3890 D BluetoothMapService: cleanup()
08-24 21:38:45.170  3890  3890 D BluetoothMapService: MAP Service closeService in
08-24 21:38:45.170  3890  3890 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 21:38:45.170  3890  3890 V BluetoothMapService: MAP Service closeService out
08-24 21:38:45.170  3890  3971 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-24 21:38:45.170  7096  7096 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 21:38:45.170  3890  3971 D BluetoothAdapterProperties: Setting state to 10
08-24 21:38:45.170  3890  3971 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-24 21:38:45.170  1037  1112 D BluetoothManagerService: Message: 60
08-24 21:38:45.170  1037  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-24 21:38:45.170  1037  1112 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-24 21:38:45.170  3890  3971 I BluetoothAdapterState: Entering OffState
08-24 21:38:45.171  7043  7060 D BluetoothPan: onBluetoothStateChange on: false
08-24 21:38:45.171  1850  3512 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 21:38:45.172  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 21:38:45.173  1037  1112 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 21:38:45.173  1850  2468 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 21:38:45.173  7096  7096 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-24 21:38:45.176  7096  7096 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-24 21:38:45.176  7043  7059 D BluetoothMap: onBluetoothStateChange: up=false
08-24 21:38:45.177  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:38:45.177  7043  7060 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-24 21:38:45.177  7043  7059 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 21:38:45.178  1037  1112 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 21:38:45.179  1037  1112 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-24 21:38:45.179  1037  1112 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-24 21:38:45.182  1037  1112 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-24 21:38:45.182  1037  1112 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-24 21:38:45.182  1037  1112 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2aa253b1 mBinding = false
08-24 21:38:45.183  1037  1112 D BluetoothManagerService: Sending unbind request.
08-24 21:38:45.184  7065  7065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 21:38:45.184  7065  7065 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 21:38:45.185  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 21:38:45.187  1037  1112 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-24 21:38:45.188  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:38:45.188  1940  2251 D LGBluetoothAPIService: Message: 2
08-24 21:38:45.188  1940  2251 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@16f245cb mBinding = false
08-24 21:38:45.189  1940  2251 D LGBluetoothAPIService: Sending unbind request.
,08-24 21:38:45.189  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 21:38:45.192  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:45.193  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:45.194  1604  1604 D BluetoothAdapter: 321677808: getState() :  mService = null. Returning STATE_OFF
08-24 21:38:45.194  1604  1604 D BluetoothAdapter: 321677808: getState() :  mService = null. Returning STATE_OFF
08-24 21:38:45.194  7043  7043 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-24 21:38:45.195  7043  7043 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-24 21:38:45.195  7043  7043 D LGBluetoothEventManager: [BTUI] clear device connection state
08-24 21:38:45.195  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:45.205  7043  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-24 21:38:45.209  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 21:38:45.211  3890  3975 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-24 21:38:45.211  3890  3890 I GKI_LINUX: GKI_exit_task 1 done
08-24 21:38:45.211  3890  3890 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-24 21:38:45.211  3890  3890 I BluetoothServiceJni: cleanupNative: return from cleanup
08-24 21:38:45.211  3890  3890 I art     : --- WEIRD: removing null entry 246
08-24 21:38:45.212  3890  3890 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-24 21:38:45.212  3890  3890 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-24 21:38:45.213  3890  3890 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-24 21:38:45.216  3890  3890 I art     : System.exit called, status: 0
08-24 21:38:45.216  3890  3890 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 21:38:45.217  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:45.223  7043  7043 D DockEventReceiver: finishStartingService: stopping service
08-24 21:38:45.228  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:38:45.229  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 21:38:45.232  7096  7096 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 21:38:45.236   332   332 V AudioFlinger: 3890 died, releasing its sessions
08-24 21:38:45.236   332   332 V AudioFlinger:  pid 1850 @ 0
08-24 21:38:45.236   332   332 V AudioFlinger:  pid 3433 @ 1
08-24 21:38:45.236   332   332 V AudioFlinger:  pid 3433 @ 2
08-24 21:38:45.236  7043  7043 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-24 21:38:45.306  1037  2013 I ActivityManager: Process com.android.bluetooth (pid 3890) has died
08-24 21:38:45.306  1037  2013 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-24 21:38:45.321  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:38:45.328  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 21:38:45.333  7065  7065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 21:38:45.333  7065  7065 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 21:38:45.333  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 21:38:45.348  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:38:45.357  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:45.364  7043  7043 D BluetoothPermissionRequest: onReceive
,08-24 21:38:45.367  7043  7043 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-24 21:38:45.368  7043  7043 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-24 21:38:45.370  7043  7043 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 21:38:45.443  1037  1958 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7142 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-24 21:38:45.457  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:38:45.458  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 21:38:45.462  7096  7096 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 21:38:45.527  1037  1885 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7159 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-24 21:38:45.558  7142  7142 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-24 21:38:45.558  7142  7142 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 21:38:45.559  7142  7142 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-24 21:38:45.559  7142  7142 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 21:38:45.583  7142  7142 D BluetoothAdapterApp: Loading JNI Library
08-24 21:38:45.620  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 21:38:45.620  7142  7142 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2d75ff79 Instance Count = 1
,08-24 21:38:45.623  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 21:38:45.625  7142  7142 D BluetoothAdapterApp: onCreate
08-24 21:38:45.630  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:45.641  7159  7178 W FormManager: Network not available. Please check & try again.
08-24 21:38:45.647  7142  7142 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-24 21:38:45.647  7142  7142 D ProfileConfigQcom: Adding HeadsetService
08-24 21:38:45.647  7142  7142 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-24 21:38:45.648  7142  7142 D ProfileConfigQcom: Adding A2dpService
08-24 21:38:45.648  7142  7142 D ProfileConfigQcom: [BTUI] HidService is supported
08-24 21:38:45.648  7142  7142 D ProfileConfigQcom: Adding HidService
08-24 21:38:45.648  7142  7142 D ProfileConfigQcom: [BTUI] HealthService is supported
08-24 21:38:45.649  7142  7142 D ProfileConfigQcom: Adding HealthService
08-24 21:38:45.649  7142  7142 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-24 21:38:45.650  7142  7142 D ProfileConfigQcom: [BTUI] PanService is supported
08-24 21:38:45.650  7142  7142 D ProfileConfigQcom: Adding PanService
08-24 21:38:45.650  7142  7142 D ProfileConfigQcom: [BTUI] GattService is supported
08-24 21:38:45.650  7142  7142 D ProfileConfigQcom: Adding GattService
08-24 21:38:45.651  7142  7142 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-24 21:38:45.651  7142  7142 D ProfileConfigQcom: Adding BluetoothMapService
08-24 21:38:45.651  7142  7142 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-24 21:38:45.653  7159  7180 V FormManager: Network unavailable.
08-24 21:38:45.653  7142  7142 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-24 21:38:45.654  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 21:38:45.654  7043  7043 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 21:38:45.655  7043  7043 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 21:38:45.655  7043  7043 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 21:38:45.658  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-24 21:38:45.660  7142  7142 V LGMDMManagerInternal: Create singleton instance
08-24 21:38:45.662  7159  7180 V FormManager: Network unavailable.
08-24 21:38:45.672  7043  7043 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 21:38:45.672  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-24 21:38:45.672  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 21:38:45.673  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 21:38:45.673  7043  7043 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 21:38:45.673  7043  7043 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-24 21:38:45.677  7043  7043 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-24 21:38:45.678  1037  1995 I ActivityManager: Killing 6128:com.android.contacts/u0a19 (adj 15): empty #17
08-24 21:38:45.680   328  7184 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-24 21:38:45.680  1037  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-24 21:38:45.789  1037  2050 W libprocessgroup: failed to open /acct/uid_10019/pid_6128/cgroup.procs: No such file or directory
,08-24 21:38:45.797  7142  7142 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-24 21:38:45.804  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 21:38:45.805  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-24 21:38:45.808  7142  7142 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 21:38:45.809  7142  7142 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 21:38:45.810  7142  7142 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 21:38:45.813  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 21:38:45.813  7142  7142 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:38:45.813  7142  7142 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-24 21:38:45.819  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 21:38:45.836  4325  7186 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 21:38:45.836  7113  7113 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-24 21:38:45.840  4325  7187 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 21:38:45.840  4325  7187 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 21:38:45.851  7065  7065 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-24 21:38:45.851  7065  7065 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 21:38:45.852  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 21:38:45.857  7159  7189 W FormManager: Network not available. Please check & try again.
08-24 21:38:45.863  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-24 21:38:45.870  7159  7190 V FormManager: Network unavailable.
08-24 21:38:45.874  7159  7190 V FormManager: Network unavailable.
,08-24 21:38:45.879  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:45.886  1037  1922 I ActivityManager: Killing 6647:com.lge.email/u0a23 (adj 15): empty #17
08-24 21:38:45.933  1037  1052 W libprocessgroup: failed to open /acct/uid_10023/pid_6647/cgroup.procs: No such file or directory
,08-24 21:38:45.967  7096  7096 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-24 21:38:45.969  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-24 21:38:45.970  7096  7096 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-24 21:38:46.025  7096  7096 D LgDataFeature: LgDataFeature() Constructor: none
08-24 21:38:46.025  7096  7096 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 21:38:46.034  7096  7096 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-24 21:38:46.035  7096  7096 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-24 21:38:46.035  7096  7096 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-24 21:38:46.035  7096  7096 V SoundPool: doLoad: loading sample sampleID=1
08-24 21:38:46.036  7096  7096 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-24 21:38:46.046  6760  6760 D UEI.SmartControl: QS Service created
08-24 21:38:46.047  7096  7200 V SoundPool: Start decode
08-24 21:38:46.047  7096  7200 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-24 21:38:46.048   332  1386 V MediaPlayerService: decode(23, 10857164, 17813)
08-24 21:38:46.048   332  1386 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-24 21:38:46.048   332  1386 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-24 21:38:46.048   332  1386 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-24 21:38:46.048   332  1386 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-24 21:38:46.048   332  1386 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-24 21:38:46.048   332  1386 V MediaPlayerService: player type = 3
08-24 21:38:46.048   332  1386 V AwesomePlayer: AwesomePlayer create()
08-24 21:38:46.048   332  1386 V AwesomePlayer: reset_l() 
08-24 21:38:46.048   332  1386 V AwesomePlayer: cancelPlayerEvents
08-24 21:38:46.048   332  1386 V AwesomePlayer: setAudioSink() 
08-24 21:38:46.048   332  1386 V AwesomePlayer: reset_l() 
08-24 21:38:46.048   332  1386 V AudioCache: notify(0xb1432500, 8, 0, 0)
08-24 21:38:46.049   332  1386 V AudioCache: ignored
08-24 21:38:46.049   332  1386 V AwesomePlayer: cancelPlayerEvents
08-24 21:38:46.049   332  1386 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-24 21:38:46.049   332  1386 V AwesomePlayer: setDataSource_l dataSource
08-24 21:38:46.049   332  1386 V LGParserOSAL: SniffLGParser start
08-24 21:38:46.049   332  1386 V LGParserOSAL: MainType:5, SubType=0
08-24 21:38:46.049   332  1386 V LGParserOSAL: #### check Mime : application/ogg
08-24 21:38:46.049   332  1386 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-24 21:38:46.049   332  1386 E MediaExtractor: Use LGExtractor :application/ogg 
,08-24 21:38:46.057  7096  7096 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-24 21:38:46.064  6760  6760 I UEI.SmartControl: Service initServices...
08-24 21:38:46.064  6760  6760 D UEI.SmartControl: QS start get config
08-24 21:38:46.067  7096  7096 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-24 21:38:46.068  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-24 21:38:46.103   332  1386 V LGParserOSAL: supported mime: application/ogg
08-24 21:38:46.103   332  1386 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-24 21:38:46.103   332  1386 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-24 21:38:46.103   332  1386 V AwesomePlayer: mBitrate = -1 bits/sec
,08-24 21:38:46.103   332  1386 V AwesomePlayer: AudioTrack Setting
08-24 21:38:46.103   332  1386 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-24 21:38:46.103   332  1386 V AwesomePlayer: setAudioSource() 
08-24 21:38:46.103   332  1386 V MediaPlayerService: prepare
08-24 21:38:46.103   332  1386 V AwesomePlayer: prepareAsync_l() 
08-24 21:38:46.103   332  1386 V MediaPlayerService: wait for prepare
08-24 21:38:46.104   332  7201 V AwesomePlayer: onPrepareAsyncEvent() 
08-24 21:38:46.104   332  7201 V AwesomePlayer: initAudioDecoder() 
08-24 21:38:46.104   332  7201 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-24 21:38:46.104   332  7201 V AudioSystem: isOffloadSupported()
08-24 21:38:46.104   332  7201 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-24 21:38:46.104   332  7201 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-24 21:38:46.105   332  7201 I AudioFlinger: isAudioPlaybackHookOn() false
08-24 21:38:46.105   332  7201 V AwesomePlayer: getUseOffload() = 0 
08-24 21:38:46.105   332  7201 V OMXCodec: OMXCodec::Create
08-24 21:38:46.105   332  7201 V OMXCodec: findMatchingCodecs()
08-24 21:38:46.105   332  7201 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-24 21:38:46.105   332  7201 V OMXCodec: matchingCodecs.size()=1
08-24 21:38:46.105   332  7201 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-24 21:38:46.107   332  7201 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-24 21:38:46.107   332  7201 V LGCodecAdapter: LG Codec Adapter start
08-24 21:38:46.107   332  7201 V OMXCodec: OMXCodec Createtor
08-24 21:38:46.107   332  7201 V OMXCodec: setComponentRole
08-24 21:38:46.107   332  7201 V OMXCodec: configureCodec protected=0
08-24 21:38:46.107   332  7201 V LGCodecAdapter: called getLGCodecSpecificData
08-24 21:38:46.107   332  7201 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-24 21:38:46.108  7096  7096 V LGMDMManager: Create singleton instance
08-24 21:38:46.108   332  7201 V LGCodecOSAL: Called LGconfigureCodecMETA
08-24 21:38:46.108   332  7201 V LGCodecOSAL: Called LGconfigureCodecMSG
08-24 21:38:46.108   332  7201 V LGCodecOSAL: Not support LGCodec
08-24 21:38:46.108   332  7201 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-24 21:38:46.108   332  7201 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-24 21:38:46.108   332  7201 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-24 21:38:46.108   332  7201 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-24 21:38:46.108   332  7201 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-24 21:38:46.108   332  7201 V AudioSystem: isOffloadSupported()
08-24 21:38:46.108   332  7201 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-24 21:38:46.108   332  7201 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-24 21:38:46.108   332  7201 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-24 21:38:46.108   332  7201 V OMXCodec: init()
08-24 21:38:46.108   332  7201 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-24 21:38:46.108   332  7201 V OMXCodec: allocateBuffers
08-24 21:38:46.108   332  7201 V OMXCodec: allocateBuffersOnPort portIndex=0
08-24 21:38:46.108   332  7201 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 ,on input port
08-24 21:38:46.109   332  7201 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1012100 on input port
08-24 21:38:46.109   332  7201 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1012150 on input port
08-24 21:38:46.109   332  7201 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb10121f0 on input port
08-24 21:38:46.109   332  7201 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb10122e0 on input port
08-24 21:38:46.109   332  7201 V OMXCodec: allocateBuffersOnPort portIndex=1
08-24 21:38:46.109   332  7201 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-24 21:38:46.109   332  7201 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1012330 on output port
08-24 21:38:46.109   332  7201 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb10123d0 on output port
08-24 21:38:46.109   332  7201 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1012880 on output port
08-24 21:38:46.109   332  7201 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1012b50 on output port
08-24 21:38:46.109   332  7201 V OMXCodec: init() mAsyncCompletion wait!!! 
08-24 21:38:46.112   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-24 21:38:46.112   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-24 21:38:46.112   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-24 21:38:46.112   332  7201 V OMXCodec: init() mAsyncCompletion wait!!! 
08-24 21:38:46.113   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-24 21:38:46.113   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-24 21:38:46.113   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-24 21:38:46.113   332  7201 V OMXCodec: init() mAsyncCompletion wait free! 
08-24 21:38:46.113   332  7201 V AwesomePlayer: finishAsyncPrepare_l() 
08-24 21:38:46.113   332  7201 V AudioCache: notify(0xb1432500, 5, 0, 0)
08-24 21:38:46.114   332  7201 V AudioCache: ignored
08-24 21:38:46.114   332  7201 V AudioCache: notify(0xb1432500, 1, 0, 0)
08-24 21:38:46.114   332  7201 V AudioCache: prepared
08-24 21:38:46.114   332  1386 V AudioCache: wait - success
08-24 21:38:46.114   332  1386 V MediaPlayerService: start
08-24 21:38:46.114   332  1386 V AwesomePlayer: play_l() 
08-24 21:38:46.114   332  1386 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-24 21:38:46.114   332  1386 V AwesomePlayer: createAudioPlayer_l
08-24 21:38:46.114   332  1386 V AwesomePlayer: seekAudioIfNecessary_l() 
08-24 21:38:46.114   332  1386 V AwesomePlayer: startAudioPlayer_l() 
08-24 21:38:46.114   332  1386 D AudioPlayer: start of Playback, useOffload 0
08-24 21:38:46.115   332  1386 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-24 21:38:46.115   332  1386 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,08-24 21:38:46.118   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-24 21:38:46.118   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-24 21:38:46.118   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-24 21:38:46.118   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-24 21:38:46.118   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-24 21:38:46.119   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-24 21:38:46.120   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969641776
08-24 21:38:46.120   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 21:38:46.120   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969641936
08-24 21:38:46.120   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 21:38:46.120   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969643136
08-24 21:38:46.120   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 21:38:46.120   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969643856
08-24 21:38:46.120   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 21:38:46.120   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-24 21:38:46.120   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-24 21:38:46.120   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-24 21:38:46.120   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-24 21:38:46.120   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-24 21:38:46.121   332  7203 V OMXCodec: allocateBuffersOnPort portIndex=1
08-24 21:38:46.121   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-24 21:38:46.122   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1012880 on output port
08-24 21:38:46.122   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb10123d0 on output port
08-24 21:38:46.122   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1012330 on output port
08-24 21:38:46.122   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1012d30 on output port
08-24 21:38:46.122   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-24 21:38:46.122   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-24 21:38:46.124   332  1386 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-24 21:38:46.125   332  1386 V AudioCache: notify(0xb1432500, 6, 0, 0)
08-24 21:38:46.125   332  1386 V AudioCache: ignored
08-24 21:38:46.125   332  1386 V MediaPlayerService: wait for playback complete
08-24 21:38:46.126   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.126   332  7213 V AudioCache: memcpy(0xaf006000, 0xb16ad000, 4096)
08-24 21:38:46.128   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.128   332  7213 V AudioCache: memcpy(0xaf007000, 0xb16ad000, 4096)
08-24 21:38:46.128   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.128   332  7213 V AudioCache: memcpy(0xaf008000, 0xb16ad000, 4096)
08-24 21:38:46.128   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.128   332  7213 V AudioCache: memcpy(0xaf009000, 0xb16ad000, 4096)
08-24 21:38:46.130   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.130   332  7213 V AudioCache: memcpy(0xaf00a000, 0xb16ad000, 4096)
08-24 21:38:46.130   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.130   332  7213 V AudioCache: memcpy(0xaf00b000, 0xb16ad000, 4096)
08-24 21:38:46.130   3,32  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.130   332  7213 V AudioCache: memcpy(0xaf00c000, 0xb16ad000, 4096)
08-24 21:38:46.130   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.130   332  7213 V AudioCache: memcpy(0xaf00d000, 0xb16ad000, 4096)
08-24 21:38:46.132   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.132   332  7213 V AudioCache: memcpy(0xaf00e000, 0xb16ad000, 4096)
08-24 21:38:46.133   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.133   332  7213 V AudioCache: memcpy(0xaf00f000, 0xb16ad000, 4096)
08-24 21:38:46.136   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.136   332  7213 V AudioCache: memcpy(0xaf010000, 0xb16ad000, 4096)
,08-24 21:38:46.137   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.137   332  7213 V AudioCache: memcpy(0xaf011000, 0xb16ad000, 4096)
08-24 21:38:46.138   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.138   332  7213 V AudioCache: memcpy(0xaf012000, 0xb16ad000, 4096)
08-24 21:38:46.138   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.138   332  7213 V AudioCache: memcpy(0xaf013000, 0xb16ad000, 4096)
08-24 21:38:46.139   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.139   332  7213 V AudioCache: memcpy(0xaf014000, 0xb16ad000, 4096)
08-24 21:38:46.140   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.140   332  7213 V AudioCache: memcpy(0xaf015000, 0xb16ad000, 4096)
08-24 21:38:46.140   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.140   332  7213 V AudioCache: memcpy(0xaf016000, 0xb16ad000, 4096)
08-24 21:38:46.141   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.141   332  7213 V AudioCache: memcpy(0xaf017000, 0xb16ad000, 4096)
08-24 21:38:46.142   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.142   332  7213 V AudioCache: memcpy(0xaf018000, 0xb16ad000, 4096)
08-24 21:38:46.142   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.142   332  7213 V AudioCache: memcpy(0xaf019000, 0xb16ad000, 4096)
08-24 21:38:46.143   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.143   332  7213 V AudioCache: memcpy(0xaf01a000, 0xb16ad000, 4096)
08-24 21:38:46.143   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.143   332  7213 V AudioCache: memcpy(0xaf01b000, 0xb16ad000, 4096)
08-24 21:38:46.143   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.143   332  7213 V AudioCache: memcpy(0xaf01c000, 0xb16ad000, 4096)
08-24 21:38:46.145   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.145   332  7213 V AudioCache: memcpy(0xaf01d000, 0xb16ad000, 4096)
08-24 21:38:46.145   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.145   332  7213 V AudioCache: memcpy(0xaf01e000, 0xb16ad000, 4096)
08-24 21:38:46.145   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.145   332  7213 V AudioCache: memcpy(0xaf01f000, 0xb16ad000, 4096)
08-24 21:38:46.146   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.146   332  7213 V AudioCache: memcpy(0xaf020000, 0xb16ad000, 4096)
08-24 21:38:46.147   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.148   332  7213 V AudioCache: memcpy(0xaf021000, 0xb16ad000, 4096)
,08-24 21:38:46.150   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.150   332  7213 V AudioCache: memcpy(0xaf022000, 0xb16ad000, 4096)
08-24 21:38:46.151   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.151   332  7213 V AudioCache: memcpy(0xaf023000, 0xb16ad000, 4096)
08-24 21:38:46.151   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.151   332  7213 V AudioCache: memcpy(0xaf024000, 0xb16ad000, 4096)
08-24 21:38:46.151   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.151   332  7213 V AudioCache: memcpy(0xaf025000, 0xb16ad000, 4096)
08-24 21:38:46.152   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.152   332  7213 V AudioCache: memcpy(0xaf026000, 0xb16ad000, 4096)
08-24 21:38:46.152   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.152   332  7213 V AudioCache: memcpy(0xaf027000, 0xb16ad000, 4096)
08-24 21:38:46.152   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.152   332  7213 V AudioCache: memcpy(0xaf028000, 0xb16ad000, 4096)
08-24 21:38:46.153   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.153   332  7213 V AudioCache: memcpy(0xaf029000, 0xb16ad000, 4096)
08-24 21:38:46.153   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.153   332  7213 V AudioCache: memcpy(0xaf02a000, 0xb16ad000, 4096)
08-24 21:38:46.153   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.153   332  7213 V AudioCache: memcpy(0xaf02b000, 0xb16ad000, 4096)
08-24 21:38:46.154   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.154   332  7213 V AudioCache: memcpy(0xaf02c000, 0xb16ad000, 4096)
08-24 21:38:46.154   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.154   332  7213 V AudioCache: memcpy(0xaf02d000, 0xb16ad000, 4096)
08-24 21:38:46.154   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.154   332  7213 V AudioCache: memcpy(0xaf02e000, 0xb16ad000, 4096)
08-24 21:38:46.155   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.155   332  7213 V AudioCache: memcpy(0xaf02f000, 0xb16ad000, 4096)
08-24 21:38:46.155   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.155   332  7213 V AudioCache: memcpy(0xaf030000, 0xb16ad000, 4096)
08-24 21:38:46.155   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.155   332  7213 V AudioCache: memcpy(0xaf031000, 0xb16ad000, 4096)
08-24 21:38:46.156   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.156   332  7213 V AudioCache: memcpy(0xaf032000, 0xb16ad000, 4096)
08-24 21:38:46.156   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.156   332  7213 V AudioCache: memcpy(0xaf033000, 0xb16ad000, 4096)
08-24 21:38:46.156   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.157   332  7213 V AudioCache: memcpy(0xaf034000, 0xb16ad000, 4096)
08-24 21:38:46.157   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.157   332  7213 V AudioCache: memcpy(0xaf035000, 0xb16ad000, 4096)
08-24 21:38:46.157   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.157   332  7213 V AudioCache: memcpy(0xaf036000, 0xb16ad000, 4096)
08-24 21:38:46.158   332  7213 V AudioCache: write(0xb16ad000, 4096)
08-24 21:38:46.158   332  7213 V AudioCache: memcpy(0xaf037000, 0xb16ad000, 4096)
08-24 21:38:46.159   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
,08-24 21:38:46.162   332  7213 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-24 21:38:46.162   332  7213 V AwesomePlayer: postAudioEOS() 
08-24 21:38:46.162   332  7213 V AudioCache: write(0xb16ad000, 280)
08-24 21:38:46.162   332  7213 V AudioCache: memcpy(0xaf038000, 0xb16ad000, 280)
08-24 21:38:46.164   332  7201 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-24 21:38:46.164   332  7201 V AwesomePlayer: onStreamDone
08-24 21:38:46.164   332  7201 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-24 21:38:46.164   332  7201 V AudioCache: notify(0xb1432500, 2, 0, 0)
08-24 21:38:46.164   332  7201 V AudioCache: playback complete
08-24 21:38:46.164   332  7201 V AwesomePlayer: pause_l() 
08-24 21:38:46.164   332  1386 V AudioCache: wait - success
08-24 21:38:46.164   332  7201 V AudioCache: notify(0xb1432500, 7, 0, 0)
08-24 21:38:46.164   332  7201 V AudioCache: ignored
08-24 21:38:46.164   332  1386 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-24 21:38:46.164   332  7201 V AwesomePlayer: cancelPlayerEvents
08-24 21:38:46.164   332  7201 D AudioPlayer: Pause Playback at 1068125
08-24 21:38:46.164   332  1386 V AwesomePlayer: reset_l() 
08-24 21:38:46.164   332  1386 V AudioCache: notify(0xb1432500, 8, 0, 0)
08-24 21:38:46.164   332  1386 V AudioCache: ignored
08-24 21:38:46.164   332  1386 V AwesomePlayer: cancelPlayerEvents
08-24 21:38:46.164   332  1386 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-24 21:38:46.164   332  1386 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-24 21:38:46.165   332  1386 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-24 21:38:46.165   332  1386 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-24 21:38:46.165   332  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-24 21:38:46.165   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-24 21:38:46.165   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-24 21:38:46.165   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-24 21:38:46.165   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb10122e0 on port 0
08-24 21:38:46.165   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-24 21:38:46.165   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb10121f0 on port 0
08-24 21:38:46.165   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-24 21:38:46.165   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1012150 on port 0
08-24 21:38:46.166   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-24 21:38:46.166   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1012100 on port 0
08-24 21:38:46.166   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-24 21:38:46.166   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-24 21:38:46.166   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1012d30 on port 1
08-24 21:38:46.166   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-24 21:38:46.166   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1012330 on port 1
08-24 21:38:46.166   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-24 21:38:46.166   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb10123d0 on port 1
08-24 21:38:46.166   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-24 21:38:46.166   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1012880 on port 1
08-24 21:38:46.166   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 21:38:46.167   332  7203 V OMXCodec,: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-24 21:38:46.167   332  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-24 21:38:46.167   332  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-24 21:38:46.176   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-24 21:38:46.176   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-24 21:38:46.176   332  7203 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-24 21:38:46.176   332  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-24 21:38:46.176   332  1386 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-24 21:38:46.176   332  1386 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-24 21:38:46.178   332  1386 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-24 21:38:46.178   332  1386 D AudioPlayer: AudioPlayer releasing audio source
08-24 21:38:46.178   332  1386 D AudioPlayer: AudioPlayer done releasing audio source
08-24 21:38:46.178   332  1386 V AwesomePlayer: reset_l() 
08-24 21:38:46.178   332  1386 V AwesomePlayer: cancelPlayerEvents
08-24 21:38:46.178   332  1386 V AwesomePlayer: ~AwesomePlayer call
08-24 21:38:46.178   332  1386 V AwesomePlayer: reset_l() 
08-24 21:38:46.178   332  1386 V AwesomePlayer: cancelPlayerEvents
08-24 21:38:46.179  7096  7200 V SoundPool: close(31)
08-24 21:38:46.179  7096  7200 V SoundPool: pointer = 0xa002f000, size = 205080, sampleRate = 48000, numChannels = 2
,08-24 21:38:46.202  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-24 21:38:46.203  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-24 21:38:46.207  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:98
,08-24 21:38:46.420  6760  6760 I UEI.SmartControl: Supports setup maps: true
08-24 21:38:46.423  6760  6760 D UEI.SmartControl: QS start statue = true Error code = 0
,08-24 21:38:46.423  6760  6760 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-24 21:38:46.423  6760  6760 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart,
,08-24 21:38:46.423  6760  6760 I UEI.SmartControl: ### init IR Blaster...
08-24 21:38:46.427  6760  6760 D serial_port: Configuring serial port
08-24 21:38:46.427  6760  6760 E UEI.SmartControl: UEIBLaster setting for 616
08-24 21:38:46.427  6760  6760 I UEI.SmartControl: Setting serial record hearder size = 2
08-24 21:38:46.427  6760  6760 I UEI.SmartControl: configuring settings for MAXQ616
08-24 21:38:46.427  6760  6760 I UEI.SmartControl: Get version...
08-24 21:38:46.441  1037  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{5672d0b type 2 when 343229 com.google.android.gms} when 343229
08-24 21:38:46.442  6760  7217 D UEI.SmartControl: serial port data available: 21
,08-24 21:38:46.472  6760  6760 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-24 21:38:46.472  6760  6760 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-24 21:38:46.472  6760  6760 I UEI.SmartControl: QS saving settings...
08-24 21:38:46.473  6760  6760 D UEI.SmartControl: IR Blaster version: 25672567
,08-24 21:38:46.491  6760  7217 D UEI.SmartControl: serial port data available: 4
,08-24 21:38:46.523  6760  7224 I UEI.SmartControl: Device manager: loading config....
,08-24 21:38:46.524  6760  7224 D UEI.SmartControl: ----------- loading internal config...
08-24 21:38:46.525  6760  6760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-24 21:38:46.540  6760  6760 E UEI.SmartControl: Services init done
08-24 21:38:46.541  6760  6760 D UEI.SmartControl: QS Service init finished
08-24 21:38:46.542  6760  7224 E UEI.SmartControl: Loading SETTINGS...
,08-24 21:38:46.546  6760  6760 D UEI.SmartControl: QS Service version name: 2.1.91
08-24 21:38:46.546  6760  6760 D UEI.SmartControl: QS Service version code: 201091
08-24 21:38:46.546  6760  6760 D UEI.SmartControl: Service requested: Control
08-24 21:38:46.550  6760  6760 D UEI.SmartControl: Internal service binding...
08-24 21:38:46.553  6760  7224 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-24 21:38:46.555  7096  7096 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-24 21:38:46.558  6760  6775 I UEI.SmartControl: ------ IControl API: 11
08-24 21:38:46.558  6760  6775 D UEI.SmartControl: File observer start...
08-24 21:38:46.559  6760  6775 E UEI.SmartControl: IR Port is disabled: false
08-24 21:38:46.559  6760  6775 D UEI.SmartControl: Starting file observer...
08-24 21:38:46.560  6760  6775 I UEI.SmartControl: Registering callback...
08-24 21:38:46.560  6760  6776 I UEI.SmartControl: ------ IControl API: 19
08-24 21:38:46.561  6760  6776 I UEI.SmartControl: Registering Services Ready callback...
08-24 21:38:46.561  6760  6776 I UEI.SmartControl: Notify client services are ready...
08-24 21:38:46.562  6760  7223 I UEI.SmartControl: Notify AllClients services are ready: 0
08-24 21:38:46.562  7096  7111 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-24 21:38:46.562  6760  7223 D UEI.SmartControl: -----service ready thread exits
08-24 21:38:46.562  7096  7111 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-24 21:38:46.563  7096  7198 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-24 21:38:46.563  7096  7198 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-24 21:38:46.563  7096  7096 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-24 21:38:46.563  7096  7096 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-24 21:38:46.564  6760  6775 I UEI.SmartControl: ------ IControl API: 8
08-24 21:38:46.565  7096  7096 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-24 21:38:46.567  7096  7096 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-24 21:38:46.568  7096  7096 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-24 21:38:46.568  7096  7096 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-24 21:38:46.569  7096  7096 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-24 21:38:46.569  7096  7096 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-24 21:38:46.570  7096  7096 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-24 21:38:46.573  7096  7096 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-24 21:38:46.574  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-24 21:38:46.574  7096  7096 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-24 21:38:46.575  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-24 21:38:46.575  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-24 21:38:46.576  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-24 21:38:46.577  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-24 21:38:46.578  7096  7096 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472067526578]
08-24 21:38:46.582  7096  7096 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-24 21:38:46.587  1037  2013 I ActivityManager: Killing 6154:com.android.gallery3d/u0a27 (adj 15): empty #17
08-24 21:38:46.600  7096  7229 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-24 21:38:46.628  1037  1576 W libprocessgroup: failed to open /acct/uid_10027/pid_6154/cgroup.procs: No such file or directory
,08-24 21:38:46.636  7096  7096 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-24 21:38:46.638  7096  7096 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-24 21:38:46.639  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-24 21:38:46.639  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,08-24 21:38:46.640  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,08-24 21:38:46.640  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-24 21:38:46.641  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-24 21:38:46.656  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-24 21:38:47.253  1037  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:38:47.267  1037  1112 D Tethering: MasterInitialState.processMessage what=3
08-24 21:38:47.281  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 21:38:47.285  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:47.287  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:47.289  1037  1095 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:47.290  1037  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:47.292  1037  1112 D Tethering: MasterInitialState.processMessage what=3
08-24 21:38:47.302  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 21:38:47.305  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:47.307  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:47.309  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 21:38:47.312  6556  7063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-24 21:38:47.324  5762  5762 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-24 21:38:47.333  5762  5762 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-24 21:38:47.356  2196  2196 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:38:47.398  1037  1095 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:38:47.416  1037  1958 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7233 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-24 21:38:47.433  1037  1095 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:47.433  1037  1095 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-24 21:38:47.518  7233  7233 I AppUp4:AppBoxCP: onCreate
08-24 21:38:47.520  7233  7233 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-24 21:38:47.532  7233  7233 I AppUp4:DB:  setFingerPrint start
,08-24 21:38:47.532  7233  7233 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-24 21:38:47.542  7233  7233 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-24 21:38:47.542  7233  7233 I AppUp4:DB:  SDK version = 21
,08-24 21:38:47.542  7233  7233 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-24 21:38:47.544  7233  7233 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-24 21:38:47.546  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 21:38:47.546  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:47.548  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 21:38:47.549  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-24 21:38:47.556  7233  7233 I AppUp4:CustModeStarterReceiver: onReceive
08-24 21:38:47.600  7233  7233 D LgDataFeature: LgDataFeature() Constructor: none
08-24 21:38:47.600  7233  7233 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 21:38:47.612  7233  7233 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1ab2b83b
08-24 21:38:47.613  7233  7233 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 21:38:47.613  7233  7233 D AppUp4:CustFacade: isPhone : true
08-24 21:38:47.614  7233  7233 D AppUp4:CustModeStarterReceiver: begin check event
08-24 21:38:47.614  7233  7233 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-24 21:38:47.615  7233  7233 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-24 21:38:47.615  7233  7266 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-24 21:38:47.616  7233  7266 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-24 21:38:47.616  7233  7266 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-24 21:38:47.618  1037  1886 I ActivityManager: Killing 2123:com.lge.music/u0a34 (adj 15): empty #17
,08-24 21:38:47.643   332  1387 V AudioFlinger: 2123 died, releasing its sessions
,08-24 21:38:47.643   332  1387 V AudioFlinger:  pid 1850 @ 0
,08-24 21:38:47.643   332  1387 V AudioFlinger:  pid 3433 @ 1
,08-24 21:38:47.643   332  1387 V AudioFlinger:  pid 3433 @ 2
08-24 21:38:47.669  1037  1958 W libprocessgroup: failed to open /acct/uid_10034/pid_2123/cgroup.procs: No such file or directory
,08-24 21:38:47.669  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:47.669  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-24 21:38:47.672  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 21:38:47.678  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 21:38:47.688  4325  7269 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-24 21:38:47.693  4325  7270 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:47.693  4325  7270 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 21:38:47.748  1037  1957 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7274 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-24 21:38:47.800  7274  7274 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 21:38:47.801  7274  7274 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-24 21:38:47.802  7274  7274 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 21:38:47.802  7274  7274 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 21:38:47.901  7274  7274 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-24 21:38:47.916  7274  7274 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-24 21:38:47.969  7274  7274 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-24 21:38:48.007  7274  7274 D LgDataFeature: LgDataFeature() Constructor: none
08-24 21:38:48.008  7274  7274 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 21:38:48.171  7274  7274 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-24 21:38:48.221  3433  3433 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 21:38:48.221  3433  3433 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:48.221  3433  3433 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-24 21:38:48.224  7274  7274 I HubEmail: JNI_OnLoad()
08-24 21:38:48.224  7274  7274 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-24 21:38:48.224  7274  7274 I HubEmail: registerNatives()
08-24 21:38:48.224  7274  7274 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-24 21:38:48.224  7274  7274 I HubEmail: registerNativeMethods()
08-24 21:38:48.224  7274  7274 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-24 21:38:48.225  7274  7274 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-24 21:38:48.275  1037  1053 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7305 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-24 21:38:48.287  7274  7304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:48.289  7159  7301 W FormManager: Network not available. Please check & try again.
,08-24 21:38:48.296  7159  7302 V FormManager: Network unavailable.
08-24 21:38:48.305  7159  7302 V FormManager: Network unavailable.
,08-24 21:38:48.313  1037  1886 I ActivityManager: Killing 6242:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-24 21:38:48.348  1037  1884 W libprocessgroup: failed to open /acct/uid_10080/pid_6242/cgroup.procs: No such file or directory
08-24 21:38:48.417  7305  7305 D LgDataFeature: LgDataFeature() Constructor: none
08-24 21:38:48.417  7305  7305 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 21:38:48.420  7305  7305 D PhoneMonitor: Register our PhoneStateListener
08-24 21:38:48.444  7305  7305 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-24 21:38:48.448  7305  7305 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-24 21:38:48.462  7305  7305 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-24 21:38:48.466  7305  7305 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-24 21:38:48.467  7305  7305 D TelephonyAutoProfiling: [parse] Load xml
08-24 21:38:48.472  7305  7305 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-24 21:38:48.472  7305  7305 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-24 21:38:48.472  7305  7305 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-24 21:38:48.472  7305  7305 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-24 21:38:48.472  7305  7305 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-24 21:38:48.472  7305  7305 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
,08-24 21:38:48.472  7305  7305 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-24 21:38:48.472  7305  7305 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-24 21:38:48.472  7305  7305 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-24 21:38:48.472  7305  7305 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-24 21:38:48.472  7305  7305 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-24 21:38:48.472  7305  7305 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-24 21:38:48.472  7305  7305 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-24 21:38:48.473  7305  7305 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-24 21:38:48.473  7305  7305 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-24 21:38:48.473  7305  7305 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-24 21:38:48.473  7305  7305 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-24 21:38:48.480  7305  7305 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-24 21:38:48.511  1037  2032 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7331 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 21:38:48.513  1037  2032 I ActivityManager: Killing 6680:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-24 21:38:48.558  1037  2050 W libprocessgroup: failed to open /acct/uid_10061/pid_6680/cgroup.procs: No such file or directory
,08-24 21:38:48.882  1037  1958 I art     : Explicit concurrent mark sweep GC freed 59062(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.480ms total 182.512ms
,08-24 21:38:48.968  1037  2032 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7353 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-24 21:38:48.973  1037  2032 I ActivityManager: Killing 6001:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-24 21:38:49.027  1037  1922 W libprocessgroup: failed to open /acct/uid_10097/pid_6001/cgroup.procs: No such file or directory
,08-24 21:38:49.141  1037  1053 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7370 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 21:38:49.146  1037  1053 I ActivityManager: Killing 6717:com.lge.eula/1000 (adj 15): empty #17
08-24 21:38:49.169   355   355 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 474us total 27.933ms
,08-24 21:38:49.186  1037  1538 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:49.186  1037  1538 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 21:38:49.192   355   355 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 21.532ms
08-24 21:38:49.214   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 443us total 20.498ms
,08-24 21:38:49.234  1037  1957 W libprocessgroup: failed to open /acct/uid_1000/pid_6717/cgroup.procs: No such file or directory
08-24 21:38:49.238  1037  1052 D WifiServiceImplEx: setWifiEnabled: true pid=6886, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-24 21:38:49.238  1037  1052 D WifiService: setWifiEnabled: true pid=6886, uid=10118
08-24 21:38:49.238  1037  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 21:38:49.253  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 21:38:49.254  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 21:38:49.254  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-24 21:38:49.257  1037  1539 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 21:38:49.257  1037  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 21:38:49.258  1037  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-24 21:38:49.258  1037  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-24 21:38:49.261  1037  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-24 21:38:49.261  1037  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-24 21:38:49.261  1037  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-24 21:38:49.261  1037  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-24 21:38:49.261  1037  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-24 21:38:49.261  1037  1539 E WifiHW  : unknown target_country: EU , set to default
08-24 21:38:49.262  1037  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-24 21:38:49.262  1037  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-24 21:38:49.262  1037  1539 I WifiUtil: gEnableBmps=1
,08-24 21:38:49.274  7370  7370 I art     : Almond Protected OAT
,08-24 21:38:49.333  7370  7370 D WeatherApplication: removeAccount
08-24 21:38:49.334  7370  7370 D WeatherApplication: Account.length = 0
08-24 21:38:49.335  7370  7370 E WeatherApplication: OPERATOR:OPEN
08-24 21:38:49.342  7370  7370 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:38:49
,08-24 21:38:49.346  7370  7370 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 21:38:49.347  7370  7370 D Weather.Utils: 2 : All the weather widget is gone.
08-24 21:38:49.349  7370  7370 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 21:38:49.352  7370  7370 D WeatherAncestor: connectivity changed - connection : true
08-24 21:38:49.353  7370  7370 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-24 21:38:49.362  7370  7370 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-24 21:38:49.362  7370  7370 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 21:38:49.362  7370  7370 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-24 21:38:49.384  7370  7370 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-24 21:38:49.384  7370  7370 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:38:49
08-24 21:38:49.445  1037  2032 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7389 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 21:38:49.448  1037  2032 I ActivityManager: Killing 6735:com.lge.bnr/1000 (adj 15): empty #17
08-24 21:38:49.507  1037  1922 W libprocessgroup: failed to open /acct/uid_1000/pid_6735/cgroup.procs: No such file or directory
,08-24 21:38:49.622   281   361 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 21:38:49.622   281   361 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-24 21:38:49.622   281   361 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 21:38:49.627  7389  7407 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-24 21:38:49.630   281   361 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 21:38:49.630   281   361 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-24 21:38:49.630   281   361 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 21:38:49.631  7389  7407 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-24 21:38:49.648   281   361 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 21:38:49.648   281   361 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-24 21:38:49.648   281   361 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 21:38:49.648  7389  7409 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-24 21:38:49.653   281   361 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-24 21:38:49.653   281   361 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-24 21:38:49.653   281   361 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 21:38:49.654  7389  7409 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-24 21:38:49.900  7389  7389 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-24 21:38:49.921  7389  7389 I LibraryLoader: Loading: webviewchromium
08-24 21:38:49.925  7389  7389 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 6724-6729)
08-24 21:38:49.925  7389  7389 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-24 21:38:49.933  7389  7389 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8c0c734}
08-24 21:38:49.934  7389  7389 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 21:38:49.935  7389  7389 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 21:38:49.945   328   895 D SoftapController: Softap fwReload - Ok
,08-24 21:38:49.959  7389  7389 I BrowserStartupController: Initializing chromium process, renderers=0
08-24 21:38:49.960  7389  7389 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 21:38:49.966  1037  1539 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (683ms)
,08-24 21:38:49.967  1037  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 21:38:49.967  1037  1112 D Tethering: InitialState.processMessage what=4
08-24 21:38:49.968  1037  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 21:38:49.971   328   895 D CommandListener: Setting iface cfg
08-24 21:38:49.971   328   895 D CommandListener: Trying to bring down wlan0
08-24 21:38:49.973   328   895 D CommandListener: Clearing all IP addresses on wlan0
08-24 21:38:49.975  1037  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-24 21:38:49.980  1037  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 21:38:49.980  1037  1539 E WifiStateMachine: useWiFiOffloading() : false
08-24 21:38:49.980  1037  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 21:38:49.983  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-24 21:38:49.985  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 21:38:49.984  7436  7436 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:38:49.989  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-24 21:38:49.984  7436  7436 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:38:49.991  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:49.992  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:49.992  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:49.994  1037  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-24 21:38:49.994  1037  1539 D WifiMonitor: connecting to supplicant
08-24 21:38:50.015  7436  7436 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-24 21:38:50.021  7389  7389 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-24 21:38:50.022  7389  7389 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-24 21:38:50.022  7389  7389 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-24 21:38:50.028   332  2178 V AudioPolicyService: registerClient() client 0xb558a500, uid 10093
08-24 21:38:50.029  7389  7447 W AudioManagerAndroid: Requires BLUETOOTH permission
08-24 21:38:50.043  7389  7389 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 21:38:50.043  7389  7389 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 21:38:50.043  7389  7389 I Adreno-EGL: Build Date: 12/12/14 금
08-24 21:38:50.043  7389  7389 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 21:38:50.043  7389  7389 I Adreno-EGL: Remote Branch: 
08-24 21:38:50.043  7389  7389 I Adreno-EGL: Local Patches: 
08-24 21:38:50.043  7389  7389 I Adreno-EGL: Reconstruct Branch: 
,08-24 21:38:50.050  7436  7436 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-24 21:38:50.051  7436  7436 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-24 21:38:50.122  7436  7436 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-24 21:38:50.133  7389  7389 I NSApplication: Starting up...
08-24 21:38:50.194  1037  2050 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7463 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-24 21:38:50.195  7436  7436 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-24 21:38:50.200  1037  2050 I ActivityManager: Killing 6179:com.android.vending/u0a44 (adj 15): empty #17
08-24 21:38:50.213  7436  7436 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-24 21:38:50.214  7436  7436 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-24 21:38:50.216  1037  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-24 21:38:50.217  1037  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-24 21:38:50.217  1037  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-24 21:38:50.218  1037  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-24 21:38:50.218  1037  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:38:50.219  1037  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:38:50.219  1037  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:38:50.220  1037  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:38:50.221  1037  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-24 21:38:50.221  1037  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-24 21:38:50.223  1037  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-24 21:38:50.223  1037  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-24 21:38:50.223  1037  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-24 21:38:50.223  1037  7478 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-24 21:38:50.223  1037  7478 D WifiMonitor: Dropping event because (p2p0) is stopped
08-24 21:38:50.223  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-24 21:38:50.224  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-24 21:38:50.224  1037  7478 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-24 21:38:50.224  1037  7478 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-24 21:38:50.270  1037  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 21:38:50.270  1037  1539 E WifiStateMachine: useWiFiOffloading() : false
08-24 21:38:50.270  1037  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 21:38:50.270  1037  1886 W libprocessgroup: failed to open /acct/uid_10044/pid_6179/cgroup.procs: No such file or directory
,08-24 21:38:50.280  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.280  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.280  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.280  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 21:38:50.281  1037  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-24 21:38:50.281  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 21:38:50.282  1037  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-24 21:38:50.282  1037  1539 D WifiConfigStore: Loading config and enabling all networks 
08-24 21:38:50.282  1037  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-24 21:38:50.284  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:50.286  1940  1940 D WfdService: Waiting for WifiP2p enabling
08-24 21:38:50.286  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-24 21:38:50.287  1037  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-24 21:38:50.287  1037  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-24 21:38:50.288  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:50.288  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:50.288  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:50.288  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:50.288  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:50.288  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:50.288  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:38:50.288  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:38:50.288  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 21:38:50.288  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:50.288  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 21:38:50.291  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 21:38:50.291  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:50.291  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:50.291  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:50.291  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:50.291  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:50.291  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:38:50.291  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:38:50.291  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 21:38:50.291  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:50.291  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:38:50.292  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:50.292  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:50.292  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:50.292  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:50.292  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:50.292  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:50.292  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:38:50.292  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:38:50.292  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 21:38:50.292  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:50.292  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:38:50.299  1037  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-24 21:38:50.314  1037  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-24 21:38:50.314  1037  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-24 21:38:50.315  1037  1539 D WifiStateMachine: enableVerboseLogging : level 2
,08-24 21:38:50.317  1037  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-24 21:38:50.318  1037  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-24 21:38:50.318  1037  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,08-24 21:38:50.318  7463  7463 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 21:38:50.319  1037  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-24 21:38:50.320  1037  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-24 21:38:50.320  1037  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-24 21:38:50.321  1037  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-24 21:38:50.322  1037  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-24 21:38:50.322  1037  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-24 21:38:50.323  1037  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-24 21:38:50.323  1037  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-24 21:38:50.323  1037  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-24 21:38:50.323  1037  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-24 21:38:50.324  1037  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-24 21:38:50.325  1940  1940 D WfdsService: Supplicant Connection state is changed : true
08-24 21:38:50.325  1037  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 21:38:50.325  1037  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-24 21:38:50.325  1940  2383 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-24 21:38:50.325  1940  2383 D WfdsService: Set the WFDS Monitor: true
08-24 21:38:50.325  1940  2383 D WfdsMonitor: WfdsMonitorThread create
08-24 21:38:50.325  1037  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-24 21:38:50.325  1037  1539 D WifiNative-HAL: Setting external_sim to 1
08-24 21:38:50.326  1037  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-24 21:38:50.326  1940  2383 D WfdsMonitor: WFDS Monitor is created and started
08-24 21:38:50.326  1940  2383 D WfdsService: WiFi: Supplicant connection re-established
08-24 21:38:50.326  1037  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-24 21:38:50.326  1037  1539 I WifiNative-HAL: startHal
08-24 21:38:50.326  1037  1539 D wifi    : setting scan oui 0xaf614100
08-24 21:38:50.327  1037  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 21:38:50.327  1037  1539 I WifiNative-HAL: startHal
08-24 21:38:50.327  1940  7482 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-24 21:38:50.327  1037  1539 D wifi    : setting scan oui 0xaf614100
08-24 21:38:50.327  1037  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-24 21:38:50.327  1940  7482 E CtrlSupplicant: Succeed to open control connection
08-24 21:38:50.328  1940  7482 E CtrlSupplicant: Succeed to open monitor connection
08-24 21:38:50.328  1940  7482 D WfdsMonitor: Supplicant connection established
08-24 21:38:50.328  1037  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-24 21:38:50.328  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-24 21:38:50.328  1940  2383 D WfdsService: Connected to the supplicant for wfds
08-24 21:38:50.328  7436  7436 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
,08-24 21:38:50.330  1037  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-24 21:38:50.330  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-24 21:38:50.330  7436  7436 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 21:38:50.332  1037  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 21:38:50.332  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-24 21:38:50.332  7436  7436 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-24 21:38:50.332  1037  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-24 21:38:50.332  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 21:38:50.332  7436  7436 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-24 21:38:50.333  1037  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-24 21:38:50.333  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-24 21:38:50.333  7436  7436 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 21:38:50.333  1037  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 21:38:50.333  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-24 21:38:50.334  7436  7436 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-24 21:38:50.334  1037  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
,08-24 21:38:50.334  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 21:38:50.334  7436  7436 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-24 21:38:50.335  1037  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true,
08-24 21:38:50.336  1037  1539 E WifiNative: : [347,124,980 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-24 21:38:50.336  1037  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-24 21:38:50.336  1037  1539 D WifiNative-wlan0: RECONNECT: returned true,
08-24 21:38:50.336  1037  1539 D WifiNative-wlan0: doString: [STATUS]
08-24 21:38:50.337  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-24 21:38:50.337  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-24 21:38:50.337  1037  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-24 21:38:50.338  1037  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 21:38:50.338  1037  1539 D WifiNative-wlan0: SET ps 1: returned true
,08-24 21:38:50.339  1037  1538 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.340   328   895 D CommandListener: Setting iface cfg
08-24 21:38:50.340   328   895 D CommandListener: Trying to bring up p2p0
,08-24 21:38:50.341  1037  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-24 21:38:50.341  1037  1538 D LGWifiP2pService: P2pEnablingState
08-24 21:38:50.341  1037  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 21:38:50.341  1037  1538 D LGWifiP2pService: P2p socket connection successful
08-24 21:38:50.341  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
08-24 21:38:50.341  1037  1538 D LGWifiP2pService: P2pEnabledState
08-24 21:38:50.341  1037  1037 D RttService: SCAN_AVAILABLE : 3
,08-24 21:38:50.341  1037  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.341  1037  1557 I WifiNative-HAL: startHal
08-24 21:38:50.341  1037  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf614100
,08-24 21:38:50.341  1037  1557 D wifi    : failed to get capabilities : -3
08-24 21:38:50.341  1037  1557 E WifiScanningService: could not get scan capabilities
08-24 21:38:50.342  1037  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 21:38:50.343  1037  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-24 21:38:50.343  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-24 21:38:50.343  1940  1940 D WfdsService: WifiP2pState is changed : true
08-24 21:38:50.343  1037  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-24 21:38:50.344  1037  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-24 21:38:50.344  1037  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-24 21:38:50.345  1037  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-24 21:38:50.345  1037  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-24 21:38:50.345  1037  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-24 21:38:50.345  1037  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-24 21:38:50.346  1940  2383 D WfdsService: Receive the WFDS_ENABLE Method
08-24 21:38:50.346  1940  2383 D WfdsService: Set the WFDS Monitor: true
08-24 21:38:50.346  1940  2383 D WfdsService: Connected to the supplicant for wfds
08-24 21:38:50.346  1940  2383 D WfdsJNI : doCommand: WFDS_SET TRUE
08-24 21:38:50.346  7436  7436 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-24 21:38:50.346  7436  7436 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-24 21:38:50.346  1940  2383 D WfdsService: selectPreferredScanChannel [36]
08-24 21:38:50.347  1940  2383 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-24 21:38:50.347  1037  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-24 21:38:50.347  1037  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-24 21:38:50.347  1037  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-24 21:38:50.348  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
,08-24 21:38:50.349  1940  1940 D WfdsService: isConnected: false
08-24 21:38:50.349  1037  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-24 21:38:50.349  1037  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-24 21:38:50.349  1037  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-24 21:38:50.349  1037  1538 D LGWifiP2pService: before postfix = G3
08-24 21:38:50.349  1037  1538 D WifiServerServiceExt: postfix byte check : 2
08-24 21:38:50.349  1037  1538 D LGWifiP2pService: after postfix = G3
08-24 21:38:50.349  1037  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-24 21:38:50.350  1037  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-24 21:38:50.350  1037  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-24 21:38:50.350  1037  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-24 21:38:50.350  1037  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
,08-24 21:38:50.351  1037  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-24 21:38:50.351  1037  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-24 21:38:50.351  1037  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-24 21:38:50.351  1037  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-24 21:38:50.351  1037  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-24 21:38:50.352  1037  1538 D LGWifiP2pService: DeviceAddress: 
08-24 21:38:50.352  1037  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-24 21:38:50.352  1940  1940 I WfdStateTracker: handleP2pThisDeviceChanged
08-24 21:38:50.353  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-24 21:38:50.353  1940  1940 D WfdsService: Update P2p Interface State: 3
,08-24 21:38:50.353  1037  1538 D WifiNative-p2p0: P2P_FLUSH: returned false
08-24 21:38:50.353  1037  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-24 21:38:50.354  1037  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-24 21:38:50.354  1037  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-24 21:38:50.354  1037  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-24 21:38:50.354  1037  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-24 21:38:50.355  7436  7436 E wpa_supplicant: disconnect_rssi_lvl: -100
08-24 21:38:50.355  1037  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-24 21:38:50.355  1037  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-24 21:38:50.355  1037  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
,08-24 21:38:50.356  1037  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-24 21:38:50.356  1037  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-24 21:38:50.356  1037  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-24 21:38:50.357  1037  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-24 21:38:50.357  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-24 21:38:50.369  1037  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-24 21:38:50.369  1037  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-24 21:38:50.369  1037  1538 D LGWifiP2pService: InactiveState
08-24 21:38:50.369  1037  1538 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.369  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.370  1037  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-24 21:38:50.371  7436  7436 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-24 21:38:50.372  7436  7436 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:38:50.372  1037  7478 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 21:38:50.372  1037  7478 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:38:50.372  1037  7478 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:38:50.372  1037  7478 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:38:50.373  1940  7482 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 21:38:50.373  7436  7436 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-24 21:38:50.373  7436  7436 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.373  1940  7482 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:38:50.373  1037  7478 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:38:50.373  1037  7478 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.373  1037  7478 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.373  1037  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-24 21:38:50.373  1037  7478 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.373  1037  1538 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.373  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.374  1037  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.374  7436  7436 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.374  1037  7478 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:38:50.374  1037  7478 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.374  1037  7478 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.374  1037  7478 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.374  1037  1538 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.374  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.374  1037  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.374  1940  7482 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:38:50.375  7436  7436 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-24 21:38:50.375  7436  7436 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:38:50.375  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 21:38:50.375  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:38:50.375  1037  7478 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:38:50.375  1037  7478 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:38:50.376  7436  7436 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-24 21:38:50.376  7436  7436 I wpa_supplicant: p2p0: CTRL-E,VENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.376  1037  7478 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:38:50.376  1037  7478 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.376  1037  7478 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.376  1037  7478 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.376  1940  2383 W WfdsService: DefaultState - msg [9441285] is not handled
08-24 21:38:50.376  7436  7436 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.377  1037  7478 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:38:50.377  1037  1538 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.377  1037  7478 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.377  1037  7478 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.377  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.377  1037  7478 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:38:50.377  1037  1538 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.377  1940  7482 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:38:50.377  1037  1538 D LGWifiP2pService: InactiveState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.377  1940  7482 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:38:50.377  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.377  1037  1538 D LGWifiP2pService: DefaultState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.377  1037  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-24 21:38:50.378  1037  1037 E WifiServerServiceExt: No p2p device connected
08-24 21:38:50.378  1037  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.378  1037  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-24 21:38:50.378  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:50.378  1037  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-24 21:38:50.379  1037  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-24 21:38:50.379  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-24 21:38:50.379  7436  7436 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-24 21:38:50.379  7436  7436 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 21:38:50.379  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-24 21:38:50.380  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 21:38:50.380  1037  7478 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 21:38:50.380  1037  7478 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 21:38:50.380  1037  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-24 21:38:50.380  1037  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-24 21:38:50.380  1037  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1f2b9b9a type 2 when 347170 com.google.android.gms} when 347170
,08-24 21:38:50.380  1037  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-24 21:38:50.380  1037  1539 D WifiNative-wlan0: doBoolean: SCAN
08-24 21:38:50.381  1037  1539 D WifiNative-wlan0: SCAN: returned false
08-24 21:38:50.381  1037  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=347171  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 21:38:50.382  1037  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=347172  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 21:38:50.383  1037  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 21:38:50.383  1037  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 21:38:50.383  1037  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 21:38:50.384  1037  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-24 21:38:50.384  1037  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-24 21:38:50.387  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:50.388  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:38:50.390  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:50.391  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.391  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.391  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-24 21:38:50.392  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:38:50.392  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-24 21:38:50.604  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 21:38:50.605  6556  7063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-24 21:38:50.661  2196  2196 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:38:50.683  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 21:38:50.683  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:50.683  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 21:38:50.683  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-24 21:38:50.685  7233  7233 I AppUp4:CustModeStarterReceiver: onReceive
,08-24 21:38:50.690  7233  7233 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1ab2b83b
08-24 21:38:50.690  7233  7233 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 21:38:50.690  7233  7233 D AppUp4:CustFacade: isPhone : true
08-24 21:38:50.691  7233  7233 D AppUp4:CustModeStarterReceiver: begin check event
08-24 21:38:50.691  7233  7233 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-24 21:38:50.694  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:50.694  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 21:38:50.696  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 21:38:50.701  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 21:38:50.711  4325  7498 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 21:38:50.716  7274  7274 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-24 21:38:50.724  4325  7499 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:50.724  4325  7499 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 21:38:50.736  1037  1958 V SIM_STK : Menu title from STK is T-Mobile
,08-24 21:38:50.741  7274  7501 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.746  3433  3433 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 21:38:50.747  3433  3433 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:50.747  3433  3433 I LgeMiscReceiver: networkInfo.isConnected() = false
08-24 21:38:50.750  7305  7305 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 21:38:50.750  7305  7305 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-24 21:38:50.764  7159  7502 W FormManager: Network not available. Please check & try again.
,08-24 21:38:50.767  7436  7436 E wpa_supplicant: USIM:  scard_init function
08-24 21:38:50.767  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-24 21:38:50.767  1037  7478 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-24 21:38:50.767  7436  7436 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-24 21:38:50.768  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-24 21:38:50.768  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-24 21:38:50.768  1037  7478 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-24 21:38:50.769  1037  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 21:38:50.770  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-24 21:38:50.770  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-24 21:38:50.770  1815  4027 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-24 21:38:50.770  1037  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 21:38:50.771  1037  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 21:38:50.771  1037  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 21:38:50.771  1037  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-24 21:38:50.772  7370  7370 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:38:50
08-24 21:38:50.775  7159  7504 V FormManager: Network unavailable.
08-24 21:38:50.776   328  7510 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-24 21:38:50.777  1037  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=347567  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-24 21:38:50.779  1037  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-24 21:38:50.780  1815  4027 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-24 21:38:50.780  1037  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=347570  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-24 21:38:50.781  1815  1815 I ConfigFetchService: fetch service done; releasing wakelock
08-24 21:38:50.782  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:50.782  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:38:50.784  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:50.785  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.786  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.786  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-24 21:38:50.787  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.787  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.787  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-24 21:38:50.788  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:38:50.788  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-24 21:38:50.790  1815  1815 I ConfigFetchService: stopping self
08-24 21:38:50.794  7159  7504 V FormManager: Network unavailable.
08-24 21:38:50.796  7370  7370 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 21:38:50.796  7370  7370 D Weather.Utils: 2 : All the weather widget is gone.
08-24 21:38:50.798  7370  7370 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 21:38:50.798  7370  7370 D WeatherAncestor: connectivity changed - connection : true
08-24 21:38:50.799  7370  7370 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@155324b1
08-24 21:38:50.801  7370  7370 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-24 21:38:50.803  7370  7370 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 21:38:50.803  7370  7370 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-24 21:38:50.803  7370  7370 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 21:38:50.803  7370  7370 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:38:50
08-24 21:38:50.804  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:50.804  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:38:50.809  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:50.821  2196  2196 I ConfigService: onDestroy
,08-24 21:38:50.826  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 21:38:50.826  7043  7043 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 21:38:50.826  7043  7043 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 21:38:50.826  7043  7043 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 21:38:50.828  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 21:38:50.828  7043  7043 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 21:38:50.829  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-24 21:38:50.829  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 21:38:50.829  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 21:38:50.829  7043  7043 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 21:38:50.829  7043  7043 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-24 21:38:50.834  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 21:38:50.838  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 21:38:50.840  7159  7514 W FormManager: Network not available. Please check & try again.
08-24 21:38:50.843  7159  7515 V FormManager: Network unavailable.
08-24 21:38:50.844  7159  7515 V FormManager: Network unavailable.
08-24 21:38:50.845  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:50.861  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 21:38:50.864  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-24 21:38:50.869  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:50.878  7436  7436 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-24 21:38:50.878  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-24 21:38:50.878  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-24 21:38:50.879  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-24 21:38:50.879  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-24 21:38:50.879  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 21:38:50.879  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 21:38:50.882  1037  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=347671  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-24 21:38:50.882  1037  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-24 21:38:50.882  1037  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=347672  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-24 21:38:50.883  1037  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=347673
08-24 21:38:50.883  7159  7517 W FormManager: Network not available. Please check & try again.
08-24 21:38:50.883  1037  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=347673
08-24 21:38:50.884  1037  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=347674
,08-24 21:38:50.884  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=347674
08-24 21:38:50.886  1037  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=347675
08-24 21:38:50.886  1037  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=347676  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-24 21:38:50.889  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:50.889  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:38:50.890  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.890  7436  7436 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 21:38:50.890  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.890  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 21:38:50.890  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-24 21:38:50.890  7436  7436 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 21:38:50.892  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 21:38:50.892  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 21:38:50.892  1037  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=347682  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-24 21:38:50.892  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-24 21:38:50.892  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 21:38:50.892  1037  7478 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 21:38:50.892  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-24 21:38:50.892  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 21:38:50.893  1037  7478 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 21:38:50.893  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 21:38:50.893  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 21:38:50.896  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.896  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.896  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-24 21:38:50.899  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:38:50.899  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-24 21:38:50.899  1037  1539 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:38:50.900  1037  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:38:50.900  1037  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:38:50.900  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 21:38:50.900  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:38:50.901  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 21:38:50.901  1037  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:38:50.901  1037  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=347691  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-24 21:38:50.902  7159  7518 V FormManager: Network unavailable.
08-24 21:38:50.902  1037  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=347692  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-24 21:38:50.903  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:38:50.903  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-24 21:38:50.903  1037  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=347693
08-24 21:38:50.903  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 21:38:50.903  1037  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=347693
08-24 21:38:50.904  1037  1539 D WifiNative-wlan0: doString: [STATUS]
08-24 21:38:50.904  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 21:38:50.904  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 21:38:50.905  1037  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-24 21:38:50.906  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 21:38:50.908  1037  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-24 21:38:50.910  7159  7518 V FormManager: Network unavailable.
08-24 21:38:50.912  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:50.912  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-24 21:38:50.914  1037  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,08-24 21:38:50.914  1037  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-24 21:38:50.915  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:50.920  4325  7519 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 21:38:50.925  4325  7520 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 21:38:50.925  4325  7520 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-24 21:38:50.972  1037  1052 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7521 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-24 21:38:50.978  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.978  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.979  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-24 21:38:50.979  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:50.979  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:38:50.981  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:50.986  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.986  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:50.986  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-24 21:38:50.991  1037  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-24 21:38:50.991  1037  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 21:38:50.991  1037  1546 D ConnectivityService: Got NetworkAgent Messenger
08-24 21:38:50.991  1037  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 21:38:50.992  1037  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-24 21:38:50.992  1037  1546 D ConnectivityService: NetworkAgent connected
08-24 21:38:50.993  1037  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 21:38:50.993  1037  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-24 21:38:51.000  1037  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 21:38:51.001  1037  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 21:38:51.001  1037  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 21:38:51.001  1037  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 21:38:51.001  1037  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 21:38:51.003  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:51.003  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:38:51.004  1037  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 21:38:51.005  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 21:38:51.007   328   895 D CommandListener: Setting iface cfg
08-24 21:38:51.010  1037  1539 E WifiStateMachine: Start Dhcp Watchdog 2
08-24 21:38:51.011  1037  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=347800  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 21:38:51.011  1037  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=347801  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 21:38:51.012  1037  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=347801  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 21:38:51.013  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:38:51.013  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-24 21:38:51.013  1037  7539 D DhcpStateMachine: StoppedState
08-24 21:38:51.013  1037  7539 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:51.013  1037  7539 D DhcpStateMachine: WaitBeforeStartState
08-24 21:38:51.014  1037  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=347803  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 21:38:51.014  1037  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=347804  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 21:38:51.015  1037  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=347804  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 21:38:51.016  1037  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:302126] from screen [on:0 period:-1106251512] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:38:51.017  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1106251511] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:38:51.017  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-24 21:38:51.021  1037  1546 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-24 21:38:51.021  1037  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:51.022  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:51.023  1037  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:51.023  1037  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:51.024  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:51.024  1037  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:51.024  1037  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-24 21:38:51.026  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:38:51.026  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-24 21:38:51.026  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:51.026  1037  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=180,0,0
08-24 21:38:51.027  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=180,0,0
08-24 21:38:51.027  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-24 21:38:51.027  7436  7436 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-24 21:38:51.028  1037  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-24 21:38:51.028  1037  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-24 21:38:51.028  1037  1539 D WifiNative-wlan0: SET ps 0: returned true
08-24 21:38:51.028  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-24 21:38:51.029  7436  7436 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-24 21:38:51.029  1037  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-24 21:38:51.029  1037  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@30eb0aaa target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:51.029  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@30eb0aaa target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:51.029  1037  7539 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:51.029  1037  7539 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-24 21:38:51.030  1037  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-24 21:38:51.030  1037  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 21:38:51.030  1037  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-24 21:38:51.031   328   895 D CommandListener: Setting iface cfg
08-24 21:38:51.031   328   895 D CommandListener: Trying to bring up wlan0
08-24 21:38:51.032  1037  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-24 21:38:51.033  1037  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:51.033  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:38:51.033  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-24 21:38:51.033  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:51.033  1037  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:51.034  1037  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:51.034  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:51.035  1037  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LI,NKPROPERTIES 0 0
08-24 21:38:51.035  1037  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-24 21:38:51.036  1037  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-24 21:38:51.036  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-24 21:38:51.036  1037  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:51.036  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:51.036  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 21:38:51.037  7436  7436 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 21:38:51.037  1037  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 21:38:51.037  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-24 21:38:51.037  7436  7436 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,08-24 21:38:51.038  1037  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-24 21:38:51.038  1037  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 21:38:51.054  1037  1539 D WifiNative-wlan0: SET ps 1: returned true
08-24 21:38:51.055  1037  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-24 21:38:51.055  1037  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-24 21:38:51.056  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-24 21:38:51.056  1037  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-24 21:38:51.057  1037  1546 D ConnectivityService: ignoring duplicate network state non-change
,08-24 21:38:51.061  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:51.061  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:38:51.063  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:51.063  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:51.063  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-24 21:38:51.066  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:51.066  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:51.066  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:51.066  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-24 21:38:51.067  1037  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-24 21:38:51.068  1037  1546 D ConnectivityService: Adding iface wlan0 to network 101
08-24 21:38:51.068  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-24 21:38:51.073  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:51.073  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:51.073  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-24 21:38:51.075  1037  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-24 21:38:51.076  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:51.076  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:38:51.077  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-24 21:38:51.077  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-24 21:38:51.077  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:51.083  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:51.083  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:51.083  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-24 21:38:51.089  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:51.090  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 21:38:51.090  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:51.096  1037  1546 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-24 21:38:51.096  1037  1546 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-24 21:38:51.097  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:51.097  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 21:38:51.097  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:51.097  1037  1546 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-24 21:38:51.098   328   895 E Netd    : netlink response contains error (File exists)
08-24 21:38:51.099  1037  1546 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-24 21:38:51.100  1037  1546 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-24 21:38:51.100  1037  1546 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-24 21:38:51.100  1037  1546 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-24 21:38:51.101  1037  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-24 21:38:51.101  1037  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-24 21:38:51.101  1037  1546 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-24 21:38:51.103  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:51.103  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-24 21:38:51.103  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:51.103  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-24 21:38:51.104  1037  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-24 21:38:51.105  1037  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 21:38:51.105  1037  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:38:51.105  1037  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 21:38:51.105  1037  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:51.105  1037  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-24 21:38:51.105  1037  1546 D ConnectivityService: currentScore = 0, newScore = 20
08-24 21:38:51.105  1037  1546 D ConnectivityService:    accepting network in place of null
08-24 21:38:51.105  1037  1546 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:51.106  1037  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:51.106  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:51.106  1037  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 21:38:51.107   328  7543 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-24 21:,38:51.106  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 21:38:51.108  1037  1546 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-24 21:38:51.108  1037  1546 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-24 21:38:51.108  1037  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-24 21:38:51.109  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-24 21:38:51.109  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 21:38:51.109  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 21:38:51.109  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 21:38:51.110  1037  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:51.111  1037  1546 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-24 21:38:51.111  1037  1546 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-24 21:38:51.112  1037  1546 D ConnectivityService: validation of new default Network = false
08-24 21:38:51.112  1037  1546 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-24 21:38:51.112  1037  1546 D DSQN    : enableDataServiceNotify 
08-24 21:38:51.112  1037  1546 D DSQN    : start dsqn bin
08-24 21:38:51.117  7521  7521 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-24 21:38:51.117  1037  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-24 21:38:51.117  7521  7521 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-24 21:38:51.117  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:51.117  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:38:51.117  1037  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:38:51.118  1604  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 21:38:51.114  7545  7545 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:38:51.114  7545  7545 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 21:38:51.127  1037  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-24 21:38:51.133  7545  7545 E DSQN    : DSQN ssw
,08-24 21:38:51.135  7521  7521 V [BNRBootReceiver]: Boot Receiver Return
08-24 21:38:51.139  1037  1995 I ActivityManager: Killing 7020:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-24 21:38:51.141   328  7551 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-24 21:38:51.141  7521  7521 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 21:38:51.141   328  7551 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-24 21:38:51.166  1037  1623 W libprocessgroup: failed to open /acct/uid_10037/pid_7020/cgroup.procs: No such file or directory
,08-24 21:38:51.172  1815  7552 I CheckinService: active receiver: enabled
08-24 21:38:51.173  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:38:51.173   328  7543 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-24 21:38:51.182   328  7551 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-24 21:38:51.215   328  7543 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-24 21:38:51.229   328   894 D LGDataListener: argv[0]=dsqncommand
08-24 21:38:51.229   328   894 D LGDataListener: argv[1]=wlan0
08-24 21:38:51.229   328   894 D LGDataListener: argv[2]=1
08-24 21:38:51.229   328   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-24 21:38:51.232  1037  7539 D DhcpStateMachine: DHCPV4 request on wlan0
08-24 21:38:51.233  1037  7539 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-24 21:38:51.234  1037  7539 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-24 21:38:51.234  1037  1110 D DSQN    : DSQM DsqnNotification wlan0  1
08-24 21:38:51.234  1037  1110 D DSQN    : start to monitor internet connection
08-24 21:38:51.234  7556  7556 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:38:51.234  7556  7556 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:38:51.259  7556  7556 I dhcpcd  : version 5.5.6 starting
08-24 21:38:51.261  7556  7556 E dhcpcd  : get_duid: m
08-24 21:38:51.261  7556  7556 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-24 21:38:51.261  7556  7556 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-24 21:38:51.280  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 19:38:51 GMT], X-Android-Received-Millis=[1472067531280], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472067531246]}
08-24 21:38:51.280  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-24 21:38:51.280  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-24 21:38:51.281  1037  1546 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-24 21:38:51.281  1037  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-24 21:38:51.281  1037  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 21:38:51.281  1037  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:38:51.281  1037  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 21:38:51.281  1037  1546 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-24 21:38:51.281  1037  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-24 21:38:51.281  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:51.281  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:38:51.281  1037  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:38:51.282  1037  1546 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:51.282  1037  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-24 21:38:51.282  1604  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 21:38:51.282  1037  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 21:38:51.282  1037  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 21:38:51.283  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:51.283  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 21:38:51.309  1815  7552 I CheckinService: Preparing to send checkin request
08-24 21:38:51.309  1815  7552 I EventLogService: Accumulating logs since 1472067241442
,08-24 21:38:51.315  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:38:51.325  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 21:38:51.326  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:51.327  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:51.329  1815  7552 W EventLogAggregator: Unknown tag: snet_gcore
08-24 21:38:51.329  7556  7556 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-24 21:38:51.329  7556  7556 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-24 21:38:51.329  7556  7556 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-24 21:38:51.330  7556  7556 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-24 21:38:51.330  7556  7556 D dhcpcd  : wlan0: sending REQUEST (xid 0x1376cb59), next in 4.64 seconds
08-24 21:38:51.330  1815  7552 W EventLogAggregator: Unknown tag: snet_launch_service
08-24 21:38:51.335  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:51.346  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 21:38:51.348  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:51.348  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 21:38:51.350  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:38:51.351  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:38:51.351  7096  7096 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 21:38:51.354  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-24 21:38:51.357  7043  7043 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-24 21:38:51.360  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 21:38:51.364  7556  7556 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-24 21:38:51.368  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:38:51.373  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:51.376  7556  7556 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-24 21:38:51.376  7556  7556 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-24 21:38:51.376  7556  7556 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-24 21:38:51.376  7556  7556 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-24 21:38:51.376  7556  7556 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-24 21:38:51.377  7556  7556 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-24 21:38:51.377  7556  7556 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-24 21:38:51.377  7556  7556 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-24 21:38:51.380  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:38:51.380  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:38:51.381  7096  7096 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 21:38:51.384  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 21:38:51.392  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:38:51.398  1815  7552 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-24 21:38:51.399  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:51.405  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:38:51.405  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:38:51.406  7096  7096 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-24 21:38:51.416  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 21:38:51.416  7043  7043 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 21:38:51.416  7043  7043 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 21:38:51.416  7043  7043 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 21:38:51.418  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 21:38:51.422  7043  7043 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 21:38:51.422  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-24 21:38:51.422  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 21:38:51.422  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 21:38:51.422  7043  7043 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 21:38:51.422  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-24 21:38:51.422  7043  7043 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-24 21:38:51.425  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:38:51.430  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:38:51.437  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:51.442  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:38:51.442  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:38:51.443  7096  7096 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 21:38:51.446  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:38:51.449  2196  7564 D GCM     : Connected
,08-24 21:38:51.453  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 21:38:51.460  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:51.464  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:38:51.465  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:38:51.465  7096  7096 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-24 21:38:51.467  2196  7564 D GCM     : Message class com.google.e.a.a.q
08-24 21:38:51.468  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:38:51.472  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:38:51.479  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:51.484  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:38:51.484  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:38:51.485  7096  7096 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 21:38:51.488  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 21:38:51.495  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:38:51.506  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:51.524  6760  7225 D UEI.SmartControl: Internal timer expired: 2
08-24 21:38:51.524  6760  7225 D UEI.SmartControl: unbind internal service
,08-24 21:38:51.532  1037  1922 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7589 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-24 21:38:51.538  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:38:51.539  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:38:51.539  7096  7096 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-24 21:38:51.543  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:38:51.555  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:38:51.562  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:51.569  7589  7589 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-24 21:38:51.569  7589  7589 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-24 21:38:51.569  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 21:38:51.569  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:38:51.571  7096  7096 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 21:38:51.576  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:38:51.583  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:38:51.586  7589  7589 I MultiDex: VM with version 2.1.0 has multidex support
08-24 21:38:51.586  7589  7589 I MultiDex: install
08-24 21:38:51.586  7589  7589 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-24 21:38:51.589  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:51.594  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 21:38:51.594  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:38:51.594  7096  7096 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 21:38:51.597  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:38:51.602  7065  7065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-24 21:38:51.602  7589  7589 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-24 21:38:51.606  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 21:38:51.608  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 21:38:51.618  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 21:38:51.622  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:38:51.622  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:38:51.623  7096  7096 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-24 21:38:51.623  7096  7096 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-24 21:38:51.623  7096  7096 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-24 21:38:51.627  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:38:51.634  7065  7065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-24 21:38:51.635  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-24 21:38:51.639  1037  7539 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-24 21:38:51.642  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 21:38:51.643  1037  7539 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-24 21:38:51.644  1037  7539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-24 21:38:51.644  1037  7539 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-24 21:38:51.644  1037  7539 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-24 21:38:51.644  1037  7539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 21:38:51.644  1037  7539 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-24 21:38:51.644  1037  7539 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-24 21:38:51.645  1037  7539 D DhcpStateMachine: RunningState
08-24 21:38:51.648  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 21:38:51.653  6760  7222 D serial_port: close(fd = 24)
08-24 21:38:51.654  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:38:51.654  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:38:51.655  7096  7096 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-24 21:38:51.655  7096  7096 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-24 21:38:51.655  7096  7096 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-24 21:38:51.660  2196  2196 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-24 21:38:51.660  6760  7222 I UEI.SmartControl: Serial port is closed.
,08-24 21:38:51.668  2196  2196 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-24 21:38:51.668  2196  2196 D c       : Getting all permits...
08-24 21:38:51.668  2196  2196 D a       : Opening database...
08-24 21:38:51.673  2196  2196 D a       : Opening database auth.proximity.permit_store...
08-24 21:38:51.674  2196  2196 D a       : Closing database...
,08-24 21:38:51.954  7613  7613 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-24 21:38:52.069  7613  7613 I dex2oat : dex2oat took 114.180ms (threads: 4)
,08-24 21:38:52.087  7589  7605 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 21:38:52.087  7589  7605 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 21:38:52.087  7589  7605 I Adreno-EGL: Build Date: 12/12/14 금
08-24 21:38:52.087  7589  7605 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 21:38:52.087  7589  7605 I Adreno-EGL: Remote Branch: 
08-24 21:38:52.087  7589  7605 I Adreno-EGL: Local Patches: 
08-24 21:38:52.087  7589  7605 I Adreno-EGL: Reconstruct Branch: 
,08-24 21:38:52.119  1037  1546 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-24 21:38:52.219  7589  7605 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 21:38:52.219  7589  7605 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 21:38:52.219  7589  7605 I Adreno-EGL: Build Date: 12/12/14 금
08-24 21:38:52.219  7589  7605 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 21:38:52.219  7589  7605 I Adreno-EGL: Remote Branch: 
08-24 21:38:52.219  7589  7605 I Adreno-EGL: Local Patches: 
08-24 21:38:52.219  7589  7605 I Adreno-EGL: Reconstruct Branch: 
,08-24 21:38:52.432  7589  7605 D LgDataFeature: LgDataFeature() Constructor: none
,08-24 21:38:52.432  7589  7605 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 21:38:52.469  7589  7605 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 21:38:52.469  7589  7605 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 21:38:52.469  7589  7605 I Adreno-EGL: Build Date: 12/12/14 금
08-24 21:38:52.469  7589  7605 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 21:38:52.469  7589  7605 I Adreno-EGL: Remote Branch: 
08-24 21:38:52.469  7589  7605 I Adreno-EGL: Local Patches: 
08-24 21:38:52.469  7589  7605 I Adreno-EGL: Reconstruct Branch: 
,08-24 21:38:52.898  1037  1539 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-24 21:38:52.901  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 21:38:52.902  1037  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 21:38:52.902  1037  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 21:38:52.903  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 21:38:52.903  1037  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 21:38:52.904  1037  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-24 21:38:52.904  1037  1546 D ConnectivityService: identical MTU - not setting
08-24 21:38:52.904  1037  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-24 21:38:52.904  1037  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-24 21:38:52.904  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:52.904  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:38:52.904  1037  1546 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:38:52.905  1604  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-24 21:38:52.914   328  7627 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-24 21:38:52.917   328  7627 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-24 21:38:52.957   328  7627 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-24 21:38:53.187  1815  7552 I CheckinTask: Sending checkin request (7911 bytes)
,08-24 21:38:53.542  1815  7552 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-24 21:38:53.562  1815  7552 I CheckinService: active receiver: disabled
,08-24 21:38:53.603  2196  2196 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-24 21:38:53.622  2196  2196 I GCM     : GCM config loaded
,08-24 21:38:53.642  7305  7305 V SetupWizard: Connected to Gservices successfully
,08-24 21:38:54.024  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2412 sc=60 link=72 tx=90.0, 0.0, 0.0  rx=89.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1106248504] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 21:38:54.037  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2412 sc=60 link=72 tx=90.0, 0.0, 0.0  rx=89.5 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1106248491] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-24 21:38:54.037  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-24 21:38:54.060  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 21:38:54.071  1037  1541 V WifiInternetCheck: Single check msg out of sync, ignoring.
08-24 21:38:54.112  1037  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:38:54.124  1037  1112 D Tethering: MasterInitialState.processMessage what=3
08-24 21:38:54.133  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:54.133  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:54.133  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:54.133  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:54.133  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:54.133  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:54.133  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:54.133  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:38:54.133  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:38:54.133  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:54.133  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 21:38:54.140  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:54.140  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:54.140  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:54.140  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:54.140  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:54.140  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:54.140  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:54.140  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:38:54.140  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:38:54.140  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:54.140  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:54.142  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:54.143  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:54.143  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:54.143  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:54.143  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:38:54.143  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:54.143  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:54.143  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:38:54.143  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:38:54.143  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:54.143  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:38:54.155  1037  1095 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:38:54.161  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 21:38:54.162  6556  7063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-24 21:38:54.172  5762  5762 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-24 21:38:54.195  2196  2196 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:38:54.212  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 21:38:54.212  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:54.212  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 21:38:54.212  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-24 21:38:54.217  7233  7233 I AppUp4:CustModeStarterReceiver: onReceive
08-24 21:38:54.221  7233  7233 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1ab2b83b
08-24 21:38:54.221  7233  7233 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 21:38:54.221  7233  7233 D AppUp4:CustFacade: isPhone : true
08-24 21:38:54.221  7233  7233 D AppUp4:CustModeStarterReceiver: begin check event
08-24 21:38:54.221  7233  7233 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-24 21:38:54.226  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:54.226  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 21:38:54.228  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 21:38:54.234  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 21:38:54.249  2848  2848 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:38:54.255  7274  7274 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
08-24 21:38:54.256  2848  2848 V DownloadManager: DownloadService onCreate
08-24 21:38:54.261  1037  2032 D WifiServiceImplEx: setWifiEnabled: false pid=6886, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 21:38:54.261  1037  2032 D WifiService: setWifiEnabled: false pid=6886, uid=10118
08-24 21:38:54.261  1037  2032 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 21:38:54.273  1037  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-24 21:38:54.275  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-24 21:38:54.275  1037  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-24 21:38:54.279  1037  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-24 21:38:54.280  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-24 21:38:54.280  1037  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-24 21:38:54.280  1037  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 21:38:54.280  1037  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 21:38:54.282  1037  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 21:38:54.282  1037  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 21:38:54.292  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 21:38:54.292  1037  1095 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-24 21:38:54.292  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 21:38:54.293  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-24 21:38:54.295  1037  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 21:38:54.296  1037  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.296  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.296  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 21:38:54.296  7436  7436 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 21:38:54.296  1037  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 21:38:54.296  1037  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 21:38:54.297  1037  1539 D WifiNative-wlan0: SET ps 1: returned true
08-24 21:38:54.297  1037  7539 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.297   328   895 D CommandListener: Clearing all IP addresses on wlan0
08-24 21:38:54.304  3433  3433 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 21:38:54.304  3433  3433 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:54.304  3433  3433 I LgeMiscReceiver: networkInfo.isConnected() = true
08-24 21:38:54.304  3433  3433 D PhoneState: setPdpRejectCasuse : false
08-24 21:38:54.310  1037  1957 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-24 21:38:54.310  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.310  7305  7305 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 21:38:54.310  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.310  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-24 21:38:54.310  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.310  7305  7305 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-24 21:38:54.310  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-24 21:38:54.314   328  7671 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-24 21:38:54.314  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-24 21:38:54.315  1037  1110 D DSQN    : Dns fail occured do internet check.
08-24 21:38:54.315  1037  1037 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-24 21:38:54.315  1037  1037 D DSQN    : try Internet connection check
08-24 21:38:54.319  2848  7647 I DownloadManager: in removeSpuriousFiles
08-24 21:38:54.320  2848  7647 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-24 21:38:54.321  2848  7647 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@20f8c9ef on behalf of 2848
08-24 21:38:54.321  2848  7647 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-24 21:38:54.321  2848  7647 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-24 21:38:54.321  2848  7647 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-24 21:38:54.322  2848  7647 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-24 21:38:54.322  2848  7647 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-24 21:38:54.322  2848  7647 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-24 21:38:54.322  2848  7647 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-24 21:38:54.322  2848  7647 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-24 21:38:54.322  2848  7647 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-24 21:38:54.322  2848  7647 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-24 21:38:54.322  2848  7647 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-24 21:38:54.324  2848  7647 I DownloadManager: in trimDatabase
08-24 21:38:54.324  2848  7647 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-24 21:38:54.324  2848  7647 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@354efcfc on behalf of 2848
08-24 21:38:54.331   328  7678 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-24 21:38:54.331  1037  7674 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-24 21:38:54.332  1037  7672 D DSQN    : ThreadInternetCheck internet check NOK 
08-24 21:38:54.332  1037  7672 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
08-24 21:38:54.332  1037  7672 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
08-24 21:38:54.334  1037  1037 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
08-24 21:38:54.334  4325  7668 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 21:38:54.336  1037  1110 D DSQN    : Dns timeout INTERNET_CHECK already in progress ignore!
08-24 21:38:54.338  1037  1538 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.338  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.338  1037  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2b3f4b51
08-24 21:38:54.338  1037  1538 D LGWifiP2pService: P2pDisablingState
08-24 21:38:54.338  1037  1538 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.338  1037  1538 D LGWifiP2pService: p2p socket connection lost
08-24 21:38:54.338  1037  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:54.338  1037  1538 D LGWifiP2pService: P2pDisabledState
08-24 21:38:54.338  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:54.339  1037  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:54.339  1037  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:54.339  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:54.340  1037  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:38:54.340  1037  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-24 21:38:54.340  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 21:38:54.340  1037  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.341  7436  7436 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 21:38:54.341  1037  1538 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.341  1037  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 21:38:54.341  1037  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 21:38:54.341  1037  1539 D WifiNative-wlan0: SET ps 1: returned true
08-24 21:38:54.341  1037  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-24 21:38:54.341   328   895 D CommandListener: Clearing all IP addresses on wlan0
08-24 21:38:54.341  1037  1546 D ConnectivityService: ignoring duplicate network state non-change
08-24 21:38:54.341  1037  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-24 21:38:54.345  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-24 21:38:54.345  1940  1955 D WifiServiceExtension: isInternetCheckAvailable return false
08-24 21:38:54.346  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-24 21:38:54.346  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:54.346  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:54.346  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 21:38:54.347  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-24 21:38:54.347  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:54.347  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:54.347  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 21:38:54.347  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
08-24 21:38:54.347  1037  1037 D RttService: SCAN_AVAILABLE : 1
08-24 21:38:54.347  1037  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.347  1037  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.347  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:54.347  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:38:54.348  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:54.350  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 21:38:54.351  1940  1940 D WfdsService: WifiP2pState is changed : false
08-24 21:38:54.351  1037  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-24 21:38:54.352  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:54.352  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:38:54.353  1037  1037 D WifiHS20: hidePasspointNotification off =false
,08-24 21:38:54.355  1037  1539 D WifiNative-p2p0: TERMINATE: returned true
08-24 21:38:54.355  1037  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 21:38:54.355  1037  1539 E WifiStateMachine: useWiFiOffloading() : false
08-24 21:38:54.355  1037  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 21:38:54.356  1940  2383 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-24 21:38:54.356  1940  2383 D WfdsService: Set the WFDS Monitor: false
08-24 21:38:54.356  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:54.357  1940  2383 D WfdsMonitor: WFDS Monitor is stopped
08-24 21:38:54.357  1940  2383 D WfdsService: STATE : WfdsDisabledState - enter
08-24 21:38:54.357  1940  7482 D CtrlSupplicant: Received on exit socket, terminate
08-24 21:38:54.357  1940  7482 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-24 21:38:54.357  1940  7482 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-24 21:38:54.357  1940  7482 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-24 21:38:54.357  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:54.357  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:54.357  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 21:38:54.359  1037  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 21:38:54.363  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-24 21:38:54.363  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:38:54.363  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-24 21:38:54.363  7274  7673 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:54.366  1940  2386 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-24 21:38:54.366  1940  2383 W WfdsService: DefaultState - msg [9445378] is not handled
,08-24 21:38:54.368  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-24 21:38:54.369  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:54.370  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:54.370  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:54.370  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:54.370  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:38:54.370  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:54.370  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:38:54.370  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:38:54.370  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:38:54.370  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:54.370  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:38:54.370  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:38:54.371  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:54.371  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:38:54.371  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor:  ,   - is connected/connecting to active network: false
08-24 21:38:54.371  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:38:54.371  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:54.371  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:38:54.373  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-24 21:38:54.373  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:38:54.373  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:54.374  4325  7677 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:54.374  4325  7677 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 21:38:54.375  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:54.376  2848  2848 V DownloadManager: DownloadService onStartCommand
08-24 21:38:54.376  2848  7648 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-24 21:38:54.385  1037  1546 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-24 21:38:54.385  1037  1546 D DSQN    : disableDataServiceNotify
08-24 21:38:54.385  1037  1546 D DSQN    : stop dsqn bin
08-24 21:38:54.385   328  7685 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-24 21:38:54.386  1037  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-24 21:38:54.387  7159  7670 I FormManager: Network unavailable (Unable to resolve host "static-avc.lglime.com": No address associated with hostname, URL : http://static-avc.lglime.com/avc/list/FORMMANAGER_lastUpdatedTime.json)
08-24 21:38:54.388  7159  7670 V FormManager: Network unavailable.
08-24 21:38:54.389  7370  7370 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:38:54
08-24 21:38:54.391  7159  7670 V FormManager: Network unavailable.
08-24 21:38:54.391  7370  7370 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 21:38:54.391  7370  7370 D Weather.Utils: 2 : All the weather widget is gone.
08-24 21:38:54.392  7370  7370 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 21:38:54.392  7370  7370 D WeatherAncestor: connectivity changed - connection : true
08-24 21:38:54.392  7370  7370 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@155324b1
08-24 21:38:54.393  7159  7670 V FormManager: Network unavailable.
08-24 21:38:54.393  7370  7370 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 21:38:54.393  7370  7370 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 21:38:54.393  7370  7370 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-24 21:38:54.393  7370  7370 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 21:38:54.393  1037  1546 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-24 21:38:54.393  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:54.393  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:38:54.394  7370  7370 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:38:54
08-24 21:38:54.394  1037  1546 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:38:54.394  1037  1546 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-24 21:38:54.395  1037  1546 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-24 21:38:54.395  1037  1546 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-24 21:38:54.395  1037  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 21:38:54.396  1604  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-24 21:38:54.396  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.396  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.396  1037  7533 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-24 21:38:54.396,  1037  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:54.396  1037  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 21:38:54.396  1037  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:54.397  1037  1546 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:54.397  1037  1546 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:54.397  1037  1546 D NetworkManagementService: Removing idletimer
08-24 21:38:54.397  1037  1546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:54.397  1037  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:54.397  1037  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 21:38:54.398  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:38:54.398  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-24 21:38:54.402  1037  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 21:38:54.402  1037  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 21:38:54.403  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-24 21:38:54.404  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
,08-24 21:38:54.404  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 21:38:54.404  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 21:38:54.404  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 21:38:54.404  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 21:38:54.404  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 21:38:54.404  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 21:38:54.424  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 21:38:54.427  7065  7065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 21:38:54.427  7065  7065 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 21:38:54.427  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 21:38:54.429  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 21:38:54.435  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:54.437  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 21:38:54.437  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:54.438  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 21:38:54.445  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:38:54.445  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:38:54.446  7096  7096 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 21:38:54.449  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:38:54.451  7065  7065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 21:38:54.452  7065  7065 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 21:38:54.452  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 21:38:54.455  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 21:38:54.456  7436  7436 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-24 21:38:54.456  7436  7436 I wpa_supplicant: monitor socket send errors count : 1
08-24 21:38:54.456  7436  7436 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-4\x00 that cannot receive messages
08-24 21:38:54.457  1037  7478 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-24 21:38:54.457  1037  7478 D WifiMonitor: Dropping event because (p2p0) is stopped
08-24 21:38:54.460  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 21:38:54.461  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:54.462  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:54.462  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:54.467  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 21:38:54.468  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:38:54.469  7096  7096 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 21:38:54.471  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:38:54.473  7065  7065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 21:38:54.473  7065  7065 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 21:38:54.473  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 21:38:54.476  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:38:54.480  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:54.485  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:38:54.486  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:38:54.487  7096  7096 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 21:38:54.491  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 21:38:54.493  7436  7436 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 21:38:54.494  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-24 21:38:54.494  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 21:38:54.494  1037  7478 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 21:38:54.494  1037  7478 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-24 21:38:54.494  7436  7436 W wpa_supplicant: USIM:  scard_deinit function
08-24 21:38:54.494  1037  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=351284
08-24 21:38:54.495  1037  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=351284
08-24 21:38:54.495  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 21:38:54.495  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 21:38:54.495  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 21:38:54.496  1037  1112 D Tethering: InitialState.processMessage what=4
08-24 21:38:54.496  1037  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=351286  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-24 21:38:54.496  1037  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=351286  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-24 21:38:54.496  1037  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 21:38:54.497  1037  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:38:54.497  1037  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:38:54.499  7159  7687 W FormManager: Network not available. Please check & try again.
08-24 21:38:54.501  1037  7539 D DhcpStateMachine: StoppedState
08-24 21:38:54.501  1037  7539 D DhcpStateMachine: StoppedState{ when=-160ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:54.501  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:54.502  1037  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-24 21:38:54.502  1037  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-24 21:38:54.504  1037  1884 I art     : Explicit concurrent mark sweep GC freed 112387(5MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.458ms total 127.460ms
08-24 21:38:54.505  2848  7648 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@20b2160b on behalf of 2848
,08-24 21:38:54.508  2848  7648 V DownloadManager: processing inserted download 1
08-24 21:38:54.509  2848  7648 V DownloadManager: processing inserted download 4
08-24 21:38:54.510  2848  7648 V DownloadManager: processing inserted download 7
08-24 21:38:54.510  2848  7648 V DownloadManager: processing inserted download 8
08-24 21:38:54.511  7159  7688 V FormManager: Network unavailable.
08-24 21:38:54.512  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 21:38:54.512  7043  7043 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 21:38:54.513  7043  7043 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 21:38:54.513  7043  7043 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 21:38:54.513  2848  7648 V DownloadManager: processing inserted download 9
08-24 21:38:54.514  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 21:38:54.514  2848  7648 V DownloadManager: processing inserted download 10
08-24 21:38:54.515  2848  7648 V DownloadManager: processing inserted download 11
08-24 21:38:54.516  7043  7043 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 21:38:54.516  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-24 21:38:54.516  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 21:38:54.516  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 21:38:54.516  7043  7043 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 21:38:54.516  7043  7043 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-24 21:38:54.516  2848  7648 V DownloadManager: processing inserted download 12
08-24 21:38:54.519  2848  7648 V DownloadManager: processing inserted download 13
,08-24 21:38:54.519  2848  7648 V DownloadManager: processing inserted download 14
08-24 21:38:54.521  2848  7648 V DownloadManager: processing inserted download 16
08-24 21:38:54.522  7159  7688 V FormManager: Network unavailable.
08-24 21:38:54.524  2848  2848 V DownloadManager: DownloadService onDestroy
08-24 21:38:54.556  7436  7436 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-24 21:38:54.556  1037  7478 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-24 21:38:54.556  1037  7478 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-24 21:38:54.556  1037  7478 D WifiMonitor: Disconnecting from the supplicant, no more events
08-24 21:38:54.557  1037  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,08-24 21:38:54.660  1940  1940 D WfdsService: Supplicant Connection state is changed : false
08-24 21:38:54.660  1940  2383 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-24 21:38:54.660  1940  2383 D WfdsService: Set the WFDS Monitor: false
,08-24 21:38:54.660  1940  2383 D WfdsMonitor: WFDS Monitor is stopped
08-24 21:38:54.661  1037  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-24 21:38:54.661  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 21:38:54.661  1037  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 21:38:54.661  1037  1539 E WifiStateMachine: useWiFiOffloading() : false
08-24 21:38:54.661  1037  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 21:38:54.661  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-24 21:38:54.665  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 21:38:54.665  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:38:54.665  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-24 21:38:54.666  1037  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-24 21:38:54.666  1037  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-24 21:38:54.668  2504  2504 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:54.668  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:54.668  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:54.668  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:54.668  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:54.668  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:38:54.668  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:54.668  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:38:54.668  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:38:54.668  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 21:38:54.670  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:54.670  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:54.670  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:54.670  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:54.670  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:38:54.670  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:54.670  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:38:54.670  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:38:54.670  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 21:38:54.671  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:38:54.671  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:38:54.671  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:38:54.671  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:38:54.671  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:38:54.671  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:38:54.671  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:38:54.671  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:38:54.671  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 21:38:54.671  4325  43,25 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 21:38:54.673  7389  7410 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-24 21:38:54.676  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 21:38:54.687  4325  7691 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 21:38:54.689  4325  7692 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 21:38:54.689  4325  7692 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-24 21:38:54.696  7065  7065 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-24 21:38:54.696  7065  7065 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 21:38:54.696  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 21:38:54.696  7159  7694 W FormManager: Network not available. Please check & try again.
08-24 21:38:54.705  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-24 21:38:54.708  7159  7695 V FormManager: Network unavailable.
,08-24 21:38:54.711  7159  7695 V FormManager: Network unavailable.
08-24 21:38:54.712  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:38:55.606  1037  1921 I ActivityManager: Killing 7113:com.lge.settings.easy/1000 (adj 15): empty #17
,08-24 21:38:55.645  1037  1884 W libprocessgroup: failed to open /acct/uid_1000/pid_7113/cgroup.procs: No such file or directory
,08-24 21:38:57.063  1037  1539 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1106245465] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 21:38:57.065  1037  1539 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1106245463] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 21:38:57.399  1037  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:38:57.413  1037  1112 D Tethering: MasterInitialState.processMessage what=3
08-24 21:38:57.428  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 21:38:57.433  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:57.434  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:57.436  1037  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:57.439  1037  1095 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:57.442  1037  1112 D Tethering: MasterInitialState.processMessage what=3
,08-24 21:38:57.453  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:57.454  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 21:38:57.458  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:57.461  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 21:38:57.463  6556  7063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-24 21:38:57.474  5762  5762 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-24 21:38:57.483  5762  5762 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-24 21:38:57.502  2196  2196 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:38:57.520  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 21:38:57.520  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:57.520  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 21:38:57.520  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-24 21:38:57.525  7233  7233 I AppUp4:CustModeStarterReceiver: onReceive
08-24 21:38:57.529  7233  7233 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1ab2b83b
08-24 21:38:57.529  7233  7233 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 21:38:57.529  7233  7233 D AppUp4:CustFacade: isPhone : true
08-24 21:38:57.529  7233  7233 D AppUp4:CustModeStarterReceiver: begin check event
08-24 21:38:57.529  7233  7233 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-24 21:38:57.534  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:57.534  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-24 21:38:57.539  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 21:38:57.541  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 21:38:57.549  7274  7274 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-24 21:38:57.573  4325  7717 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-24 21:38:57.581  4325  7719 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:57.581  4325  7719 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 21:38:57.591  7274  7718 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:57.592  7159  7723 W FormManager: Network not available. Please check & try again.
,08-24 21:38:57.600  7159  7724 V FormManager: Network unavailable.
08-24 21:38:57.602  7159  7724 V FormManager: Network unavailable.
,08-24 21:38:57.613  3433  3433 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 21:38:57.613  3433  3433 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:57.614  3433  3433 I LgeMiscReceiver: networkInfo.isConnected() = false
08-24 21:38:57.619  7305  7305 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-24 21:38:57.619  7305  7305 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-24 21:38:57.627  7370  7370 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:38:57
08-24 21:38:57.629  7370  7370 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 21:38:57.629  7370  7370 D Weather.Utils: 2 : All the weather widget is gone.
08-24 21:38:57.630  7370  7370 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 21:38:57.630  7370  7370 D WeatherAncestor: connectivity changed - connection : true
08-24 21:38:57.630  7370  7370 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@155324b1
,08-24 21:38:57.631  7370  7370 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 21:38:57.631  7370  7370 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 21:38:57.631  7370  7370 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-24 21:38:57.631  7370  7370 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 21:38:57.631  7370  7370 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:38:57
08-24 21:38:57.638  1037  1095 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:57.640  1037  1095 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:57.640  1037  1095 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:38:57.651  6556  6556 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-24 21:38:57.652  6556  7063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-24 21:38:57.664  2196  2196 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:38:57.674  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 21:38:57.674  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:57.674  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 21:38:57.674  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-24 21:38:57.676  7233  7233 I AppUp4:CustModeStarterReceiver: onReceive
,08-24 21:38:57.678  7233  7233 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1ab2b83b
08-24 21:38:57.678  7233  7233 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 21:38:57.678  7233  7233 D AppUp4:CustFacade: isPhone : true
08-24 21:38:57.679  7233  7233 D AppUp4:CustModeStarterReceiver: begin check event
08-24 21:38:57.679  7233  7233 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-24 21:38:57.681  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 21:38:57.681  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 21:38:57.683  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 21:38:57.685  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 21:38:57.691  7274  7274 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-24 21:38:57.695  4325  7729 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 21:38:57.703  4325  7730 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:38:57.705  4325  7730 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 21:38:57.708  7274  7731 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:38:57.715  7159  7734 W FormManager: Network not available. Please check & try again.
08-24 21:38:57.716  3433  3433 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 21:38:57.716  3433  3433 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:38:57.716  3433  3433 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-24 21:38:57.719  7305  7305 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 21:38:57.720  7305  7305 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-24 21:38:57.731  7159  7735 V FormManager: Network unavailable.
,08-24 21:38:57.731  7370  7370 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:38:57
08-24 21:38:57.733  7159  7735 V FormManager: Network unavailable.
08-24 21:38:57.734  7370  7370 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 21:38:57.734  7370  7370 D Weather.Utils: 2 : All the weather widget is gone.
08-24 21:38:57.735  7370  7370 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 21:38:57.735  7370  7370 D WeatherAncestor: connectivity changed - connection : true
08-24 21:38:57.735  7370  7370 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@155324b1
08-24 21:38:57.737  7370  7370 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 21:38:57.737  7370  7370 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 21:38:57.737  7370  7370 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-24 21:38:57.737  7370  7370 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 21:38:57.737  7370  7370 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:38:57
08-24 21:38:57.873  1037  1884 I ActivityManager: Killing 7521:com.lge.bnr/1000 (adj 15): empty #17
,08-24 21:38:57.930  1037  1922 W libprocessgroup: failed to open /acct/uid_1000/pid_7521/cgroup.procs: No such file or directory
,08-24 21:38:59.275  1037  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 21:38:59.275  1037  1921 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-24 21:38:59.300  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 21:38:59.300  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 21:38:59.301  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-24 21:38:59.301  1037  1112 D BluetoothManagerService: Message: 1
08-24 21:38:59.301  1037  1112 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-24 21:38:59.327  1037  1112 D BluetoothManagerService: Message: 20
08-24 21:38:59.327  1037  1112 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@253c73c8:true
,08-24 21:38:59.331  7142  7142 D BluetoothAdapterState: make
08-24 21:38:59.336  7142  7142 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-24 21:38:59.336  7142  7142 I bluedroid-qcom: init
08-24 21:38:59.337  7142  7747 I BluetoothAdapterState: Entering OffState
08-24 21:38:59.337  7142  7142 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-24 21:38:59.338  7142  7142 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-24 21:38:59.338  7142  7142 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 21:38:59.338  7142  7142 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 21:38:59.338  7142  7142 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-24 21:38:59.340  1037  1538 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:38:59.340  1037  1538 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 21:38:59.343  7142  7142 I bluedroid-qcom: get_profile_interface socket
08-24 21:38:59.343  7142  7142 I bluedroid-qcom: get_profile_interface map_client
08-24 21:38:59.344  7750  7750 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:38:59.347  7142  7751 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-24 21:38:59.349  7142  7751 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-24 21:38:59.344  7750  7750 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:38:59.356  1037  1539 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-24 21:38:59.357  1037  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-24 21:38:59.362  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 21:38:59.363  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-24 21:38:59.366  7750  7750 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-24 21:38:59.366  7750  7750 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-24 21:38:59.366  7750  7750 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-24 21:38:59.367  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-24 21:38:59.367  1037  1112 D BluetoothManagerService: Message: 40
08-24 21:38:59.368  1037  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-24 21:38:59.368  7142  7157 I bluedroid-qcom: config_hci_snoop_log
08-24 21:38:59.371  7750  7750 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-24 21:38:59.374  1037  1112 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-24 21:38:59.374  1037  1112 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-24 21:38:59.378  7750  7750 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-24 21:38:59.378  7750  7750 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-24 21:38:59.383  7142  7747 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-24 21:38:59.386  7142  7751 D BluetoothAdapterProperties: Name is: G3
08-24 21:38:59.386  7142  7747 D BluetoothAdapterProperties: Setting state to 11
08-24 21:38:59.387  7142  7747 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-24 21:38:59.387  1037  1112 D BluetoothManagerService: Message: 60
08-24 21:38:59.387  1037  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-24 21:38:59.388  1037  1112 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-24 21:38:59.389  7142  7747 I LGBluetoothServiceJni: classInitNative: succeeds
08-24 21:38:59.396  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-24 21:38:59.398  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 21:38:59.401  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:59.402  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:59.403  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:38:59.406  7043  7043 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-24 21:38:59.413  7142  7142 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 21:38:59.414  7142  7142 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:38:59.414  7142  7142 V BluetoothPbapReceiver: ***********state = 11
,08-24 21:38:59.421  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 21:38:59.437  7142  7747 D BluetoothBondStateMachine: make
,08-24 21:38:59.444  7142  7747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:38:59.444  7142  7747 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-24 21:38:59.445  7142  7747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:38:59.445  7142  7747 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-24 21:38:59.447  7142  7747 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-24 21:38:59.448  7142  7765 I BluetoothBondStateMachine: StableState(): Entering Off State
08-24 21:38:59.451  7142  7747 E BluetoothAdapterService: File transfer profiles supported!!
08-24 21:38:59.478  1037  1885 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7770 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-24 21:38:59.484  7142  7747 E BluetoothAdapterService: File transfer profiles supported!!
08-24 21:38:59.487  7142  7142 D HeadsetService: Received start request. Starting profile...
08-24 21:38:59.487  7142  7142 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 21:38:59.488  7142  7142 D LGBluetoothHfpAdapter: Version 1.6
08-24 21:38:59.491  7142  7142 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-24 21:38:59.492  7142  7142 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 21:38:59.492  7142  7142 D HeadsetStateMachine: make
,08-24 21:38:59.494  7142  7747 E BluetoothAdapterService: File transfer profiles supported!!
08-24 21:38:59.502  7142  7747 E BluetoothAdapterService: File transfer profiles supported!!
08-24 21:38:59.508  7142  7747 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 21:38:59.519  7142  7747 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 21:38:59.526  7142  7747 E BluetoothAdapterService: File transfer profiles supported!!
08-24 21:38:59.532  7142  7142 D LgDataFeature: LgDataFeature() Constructor: none
08-24 21:38:59.532  7142  7142 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 21:38:59.536  7142  7142 D HeadsetStateMachine: max_hf_connections = 1
08-24 21:38:59.536  7142  7142 I bluedroid-qcom: get_profile_interface handsfree
,08-24 21:38:59.538  7142  7142 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-24 21:38:59.539  7142  7747 V LGMDMManager: Create singleton instance
08-24 21:38:59.539   332  1386 V AudioPolicyService: registerClient() client 0xb558a6a0, uid 1002
08-24 21:38:59.539   332  1387 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-24 21:38:59.539   332  1387 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-24 21:38:59.539   332  1387 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 21:38:59.539  7142  7142 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-24 21:38:59.540   332  2178 V AudioFlinger: registerClient() client 0xb14331f0, pid 7142
08-24 21:38:59.540   332  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 21:38:59.540   332  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 21:38:59.540  1037  1977 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 21:38:59.540  1037  1977 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 21:38:59.540   332  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 21:38:59.540  1604  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 21:38:59.540  1604  1620 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 21:38:59.540   332  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 21:38:59.540  7142  7158 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 21:38:59.540  7142  7158 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-24 21:38:59.540  7142  7158 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 21:38:59.540  1850  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 21:38:59.540  7142  7158 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-24 21:38:59.540  1604  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 21:38:59.541  1850  1865 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 21:38:59.541  1604  1622 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 21:38:59.541  1850  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-24 21:38:59.541  1850  1865 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 21:38:59.541  7142  7142 V ToneGenerator: Create Track: 0xb4928a80
08-24 21:38:59.541  1037  1052 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 21:38:59.541  1037  1052 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 21:38:59.541  7142  7142 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-24 21:38:59.541  7142  7142 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-24 21:38:59.541   332  2175 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 21:38:59.541   332  2175 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-24 21:38:59.541   332  2175 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 21:38:59.541   332  2175 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 21:38:59.541  3433  3448 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 21:38:59.541   332  1387 I AudioFlinger: isAudioPlaybackHookOn() false
08-24 21:38:59.541  3433  3448 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 21:38:59.541  3433  3448 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-24 21:38:59.541  3433  3448 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 21:38:59.541   332  2178 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 21:38:59.541   332  2178 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-24 21:38:59.541   332  2178 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 21:38:59.541   332  2178 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 21:38:59.541  7142  7747 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-24 21:38:59.541  7142  7142 V AudioSystem: getLatency() output 2, latency 50
08-24 21:38:59.541  7142  7142 V AudioSystem: getFrameCount() output 2, frameCount 960
08-24 21:38:59.541  7142  7142 V AudioTrack: createTrack_l() output 2 afLatency 50
08-24 21:38:59.542   332  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 21:38:59.542   332  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 21:38:59.542   332  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 21:38:59.542   332  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 21:38:59.542   332  1386 V AudioFlinger: createTrack() lSessionId: 22
08-24 21:38:59.543  7142  7142 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-24 21:38:59.543   332  1386 V AudioFlinger: acquiring 22 from 7142, for 7142
08-24 21:38:59.543   332  1386 V AudioFlinger:  added new entry for 22
08-24 21:38:59.543  7142  7142 V ToneGenerator: ToneGenerator INIT OK, time: 356347
08-24 21:38:59.543  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:38:59.544  7142  7782 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-24 21:38:59.544  7142  7782 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 21:38:59.545  7142  7782 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 21:38:59.545  7142  7782 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-24 21:38:59.545   332  2175 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7142
08-24 21:38:59.545   332  2175 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-24 21:38:59.545   332  2175 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-24 21:38:59.545   332  2175 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-24 21:38:59.545   332  2175 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-24 21:38:59.545   332  2175 V voice   : voice_set_parameters: exit with code(0)
08-24 21:38:59.545   332  2175 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-24 21:38:59.545   332  2175 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-24 21:38:59.545  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:38:59.545   332  2175 V msm8974_platform: platform_set_parameters: exit with code(0)
,08-24 21:38:59.545   332  2175 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-24 21:38:59.546   332  2175 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-24 21:38:59.546   332  2175 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-24 21:38:59.546  7142  7782 V ToneGenerator: ToneGenerator destructor
08-24 21:38:59.546  7142  7782 V ToneGenerator: stopTone
08-24 21:38:59.546  7142  7782 V ToneGenerator: Delete Track: 0xb4928a80
08-24 21:38:59.546  7142  7782 V AudioTrack: ~AudioTrack, releasing session id from 7142 on behalf of 7142
08-24 21:38:59.546   332  2178 V AudioFlinger: releasing 22 from 7142 for 7142
08-24 21:38:59.546   332  2178 V AudioFlinger:  decremented refcount to 0
08-24 21:38:59.546   332  2178 V AudioFlinger: purging stale effects
08-24 21:38:59.546   332  2178 V AudioPolicyService: AudioCommandThread() adding release output 2
08-24 21:38:59.546   332  2178 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-24 21:38:59.546   332  2178 V AudioFlinger: PlaybackThread::Track destructor
08-24 21:38:59.546   332  1275 V AudioPolicyService: AudioCommandThread() waking up
08-24 21:38:59.546   332  2178 V AudioFlinger: removeClient_l() pid 7142, calling pid 332
08-24 21:38:59.546   332  1275 V AudioPolicyService: AudioCommandThread() processing release output 2
08-24 21:38:59.546   332  1275 V AudioPolicyManager: releaseOutput() 2
08-24 21:38:59.546   332  1275 V AudioPolicyService: AudioCommandThread() going to sleep
08-24 21:38:59.548  7142  7142 D A2dpService: Received start request. Starting profile...,
08-24 21:38:59.549  7142  7142 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-24 21:38:59.549  7142  7142 V Avrcp   : make
08-24 21:38:59.550  7142  7142 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-24 21:38:59.550  7142  7142 I bluedroid-qcom: get_profile_interface avrcp
08-24 21:38:59.551  1037  1885 W Process : Unable to open /proc/7789/status
08-24 21:38:59.559  7142  7142 V AudioManager: registerRemoteController: size of Media player list: 0
08-24 21:38:59.561  7142  7142 E AudioManager: No RCC entry present to update
08-24 21:38:59.561  7142  7142 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 21:38:59.564  7142  7142 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-24 21:38:59.565  7142  7142 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-24 21:38:59.565  7142  7142 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-24 21:38:59.569  7142  7142 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-24 21:38:59.612  7770  7770 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-24 21:38:59.612  7770  7770 W LG Account v2.2: No ProfileInfo entries
,08-24 21:38:59.613  7770  7770 I LG Account v2.2: isEnabled: false
,08-24 21:38:59.613  7770  7770 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-24 21:38:59.613  7770  7770 I Feature : [Lifetracker]Country: EU
08-24 21:38:59.613  7770  7770 I Feature : [Lifetracker]Operator: OPEN
08-24 21:38:59.613  7770  7770 I Feature : [Lifetracker]Ranking support: false
08-24 21:38:59.613  7770  7770 I Feature : [Lifetracker]Comfort support: false
08-24 21:38:59.613  7770  7770 I Feature : [Lifetracker]Accessory: true
08-24 21:38:59.613  7770  7770 I Feature : [Lifetracker]Health device: true
08-24 21:38:59.613  7770  7770 I Feature : [Lifetracker]Extra Pedometer: false
,08-24 21:38:59.613  7770  7770 I Feature : [Lifetracker]Blood glucose device: false
08-24 21:38:59.613  7770  7770 I Feature : [Lifetracker]Device Number: 3
08-24 21:38:59.624  7043  7043 D BluetoothPermissionRequest: onReceive
08-24 21:38:59.629  7043  7043 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-24 21:38:59.675  1037  2032 V SIM_STK : Menu title from STK is T-Mobile
08-24 21:38:59.675  1037  2032 V SIM_STK : Menu title from STK is T-Mobile
,08-24 21:38:59.792  1037  1957 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-24 21:38:59.802  7142  7142 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-24 21:38:59.807  7142  7142 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-24 21:38:59.808  7142  7142 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-24 21:38:59.808  7142  7142 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-24 21:38:59.808  7142  7142 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-24 21:38:59.808  7142  7142 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 21:38:59.808  7142  7142 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-24 21:38:59.808  7142  7142 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-24 21:38:59.808  7142  7142 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-24 21:38:59.808  7142  7142 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 21:38:59.809  7142  7142 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-24 21:38:59.809  7142  7142 I BluetoothA2dpServiceJni: classInitNative
08-24 21:38:59.810  7142  7142 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 21:38:59.810  7142  7142 D A2dpStateMachine: make
,08-24 21:38:59.814  7142  7142 I bluedroid-qcom: get_profile_interface a2dp
08-24 21:38:59.814  7142  7795 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-24 21:38:59.820  7142  7142 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-24 21:38:59.820  7142  7142 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-24 21:38:59.823  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:38:59.823  7142  7794 D A2dpStateMachine: Enter Disconnected: -2
,08-24 21:38:59.826  7142  7142 I BluetoothHidServiceJni: classInitNative: succeeds
08-24 21:38:59.832  7142  7142 D HidService: Received start request. Starting profile...
08-24 21:38:59.833  7142  7142 I bluedroid-qcom: get_profile_interface hidhost
08-24 21:38:59.833  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:38:59.834  7142  7142 I BluetoothHealthServiceJni: classInitNative: succeeds
08-24 21:38:59.837  7142  7142 D HealthService: Received start request. Starting profile...
,08-24 21:38:59.839  7142  7142 I bluedroid-qcom: get_profile_interface health
08-24 21:38:59.839  7142  7142 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-24 21:38:59.839  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:38:59.840  7142  7142 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-24 21:38:59.842  7142  7142 D PanService: Received start request. Starting profile...
08-24 21:38:59.842  7142  7142 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 21:38:59.842  7142  7142 I bluedroid-qcom: get_profile_interface pan
08-24 21:38:59.851  7142  7142 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-24 21:38:59.851  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
,08-24 21:38:59.852  7142  7142 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-24 21:38:59.858  7142  7142 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 21:38:59.859  7142  7142 D BtGatt.GattService: Received start request. Starting profile...
08-24 21:38:59.859  7142  7142 D BtGatt.GattService: start()
08-24 21:38:59.859  7142  7142 I bluedroid-qcom: get_profile_interface gatt
08-24 21:38:59.859  7142  7142 D BtGatt.AdvertiseManager: advertise manager created
08-24 21:38:59.864  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
,08-24 21:38:59.867  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:38:59.868  7142  7142 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-24 21:38:59.869  7142  7142 V BluetoothMapService: BluetoothMapBinder()
,08-24 21:38:59.870  7142  7142 D BluetoothMapService: Received start request. Starting profile...
08-24 21:38:59.870  7142  7142 D BluetoothMapService: start()
08-24 21:38:59.873  7142  7142 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-24 21:38:59.873  7142  7142 D BluetoothMapEmailAppObserver: createReceiver()
08-24 21:38:59.875  7142  7142 D BluetoothMapEmailAppObserver: initObservers()
,08-24 21:38:59.875  7142  7142 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-24 21:38:59.885  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
,08-24 21:38:59.886  7142  7142 D HeadsetStateMachine: Proxy object connected
08-24 21:38:59.887  7142  7142 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-24 21:38:59.887  7142  7142 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-24 21:38:59.889  7142  7782 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 21:38:59.889  7142  7782 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 21:38:59.890  7142  7782 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-24 21:38:59.893  7142  7142 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 21:38:59.898  7142  7142 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-24 21:38:59.902  7142  7142 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 21:38:59.905  7142  7142 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 21:38:59.906  7142  7142 V PanService: [BTUI] SIM Extra State :ABSENT
08-24 21:38:59.909  7142  7142 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 21:38:59.912  7142  7142 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-24 21:38:59.912  7142  7142 V BluetoothMapService: Handler(): got msg=1
,08-24 21:38:59.914  7142  7747 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-24 21:38:59.914  7142  7747 I bluedroid-qcom: enable
08-24 21:38:59.915  7142  7747 I bt_hci_bdroid: init
08-24 21:38:59.915  7142  7142 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:38:59.917  7142  7805 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-24 21:38:59.918  7142  7805 I bt-btu  : btu_task pending for preload complete event
08-24 21:38:59.918  7142  7747 I bt_vendor: bt-vendor : init
08-24 21:38:59.918  7142  7747 I bt_vendor: bt-vendor : get_bt_soc_type
08-24 21:38:59.918  7142  7142 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 21:38:59.918  7142  7747 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-24 21:38:59.918  7142  7747 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-24 21:38:59.918  7142  7142 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 21:38:59.918  7142  7142 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 21:38:59.918  7142  7747 D bt_userial_mct: userial_init
08-24 21:38:59.918  7142  7142 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:38:59.918  7142  7142 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-24 21:38:59.919  7142  7747 D bt_hci_bdroid: set_power 1
08-24 21:38:59.919  7142  7747 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-24 21:38:59.919  7142  7747 I bt_vendor: Starting hciattach daemon
08-24 21:38:59.919  7142  7747 I bt_vendor: try to set true
08-24 21:38:59.914  7808  7808 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:38:59.914  7808  7808 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:38:59.954  7809  7809 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-24 21:38:59.976  1037  1053 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7811 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-24 21:39:00.000  1037  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=440719139, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,08-24 21:39:00.004  7096  7096 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-24 21:39:00.004  7096  7096 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:98
,08-24 21:39:00.032  7832  7832 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
08-24 21:39:00.042  7833  7833 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-24 21:39:00.050  7811  7811 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 21:39:00.050  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 21:39:00.050  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 21:39:00.050  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 21:39:00.050  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
08-24 21:39:00.052  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 21:39:00.052  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-24 21:39:00.052  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-24 21:39:00.053  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 21:39:00.066  7835  7835 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-24 21:39:00.067  1037  2013 I ActivityManager: Killing 7065:com.lge.sync/1000 (adj 15): empty #17
,08-24 21:39:00.078  7836  7836 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-24 21:39:00.092  7837  7837 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-24 21:39:00.104  7838  7838 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-24 21:39:00.125  7840  7840 I libmdmdetect: ESOC framework not supported
08-24 21:39:00.127  7840  7840 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-24 21:39:00.136  7840  7840 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-24 21:39:00.136  7840  7840 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-24 21:39:00.136  7840  7840 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-24 21:39:00.136  7840  7840 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-24 21:39:00.136  7840  7840 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-24 21:39:00.136  7840  7840 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-24 21:39:00.136  7840  7840 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-24 21:39:00.139  1037  1884 W libprocessgroup: failed to open /acct/uid_1000/pid_7065/cgroup.procs: No such file or directory
,08-24 21:39:00.173  7840  7841 E QC-QMI  : qmi_client [7840] 14: failed to locate client data
,08-24 21:39:00.175   490   490 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-24 21:39:00.175   490   490 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-24 21:39:00.179  2600  2600 D [Concierge]Service: onStartCommand(). Type : 9
08-24 21:39:00.206  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=440719139 [*alarm*], flags=0x0
,08-24 21:39:00.238  7842  7842 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-24 21:39:00.250  7843  7843 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-24 21:39:00.270  7142  7747 I bt_vendor: bluetooth satus is on
08-24 21:39:00.271  7142  7747 D bt_hci_bdroid: preload
,08-24 21:39:00.271  7142  7807 D bt_userial_mct: userial_open(port:0)
08-24 21:39:00.271  7142  7807 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-24 21:39:00.274  7142  7807 I bt_vendor: Done intiailizing UART
08-24 21:39:00.275  7142  7807 I bt_vendor: Done intiailizing UART
08-24 21:39:00.275  7142  7807 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-24 21:39:00.275  7142  7807 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-24 21:39:00.276  7142  7845 D bt_userial_mct: Entering userial_read_thread()
08-24 21:39:00.276  7142  7805 I bt-btu  : btu_task received preload complete event
08-24 21:39:00.277  7142  7805 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-24 21:39:00.277  7142  7805 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-24 21:39:00.282  7142  7805 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_HCI
08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_AVDT
08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_AVRC
08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_BTM
,08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_PAN
,08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_SMP
,08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 21:39:00.287  7142  7805 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 21:39:00.395  7142  7805 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-24 21:39:00.396  7142  7805 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa023d061 
08-24 21:39:00.396  7142  7805 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa023d061 
,08-24 21:39:00.444  7142  7751 E bt-btif : Calling BTA_HhEnable
08-24 21:39:00.445  7142  7751 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-24 21:39:00.446  7142  7805 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-24 21:39:00.446  7142  7805 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-24 21:39:00.446  7142  7805 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-24 21:39:00.447  7142  7805 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,08-24 21:39:00.447  7142  7805 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-24 21:39:00.448  7142  7751 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-24 21:39:00.463  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 21:39:00.464  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
,08-24 21:39:00.473  7142  7751 D BluetoothAdapterProperties: Name is: G3
08-24 21:39:00.478  7142  7751 D BluetoothAdapterProperties: Scan Mode:20
08-24 21:39:00.478  7142  7751 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 21:39:00.479  7142  7751 D bt_hci_bdroid: postload
08-24 21:39:00.479  7142  7807 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 21:39:00.480  7142  7751 D bte_conf: Device ID record 1 : primary
08-24 21:39:00.480  7142  7751 D bte_conf:   vendorId            = 00c4
08-24 21:39:00.480  7142  7751 D bte_conf:   vendorIdSource      = 0001
08-24 21:39:00.480  7142  7751 D bte_conf:   product             = 13a1
08-24 21:39:00.480  7142  7751 D bte_conf:   version             = 1000
08-24 21:39:00.480  7142  7751 D bte_conf:   clientExecutableURL = 
08-24 21:39:00.480  7142  7751 D bte_conf:   serviceDescription  = 
08-24 21:39:00.480  7142  7751 D bte_conf:   documentationURL    = 
08-24 21:39:00.480  7142  7751 D bte_conf: bte_load_did_conf no section named DID2.
08-24 21:39:00.484  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 21:39:00.490  7142  7747 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-24 21:39:00.490  7142  7747 D BluetoothAdapterProperties: ScanMode =  20
08-24 21:39:00.491  7142  7747 D BluetoothAdapterProperties: State =  11
08-24 21:39:00.491  7142  7747 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-24 21:39:00.491  7142  7747 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-24 21:39:00.491  7142  7747 D BluetoothAdapterProperties: Setting state to 12
08-24 21:39:00.491  7142  7747 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 21:39:00.492  7142  7751 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 21:39:00.494  7853  7853 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 21:39:00.494  7853  7853 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:39:00.502  1037  1112 D BluetoothManagerService: Message: 60
08-24 21:39:00.502  1037  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-24 21:39:00.502  1037  1112 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-24 21:39:00.503  7142  7845 E bt_mct  : hci lib postload completed
08-24 21:39:00.520  7142  7747 I BluetoothAdapterState: Entering On State
,08-24 21:39:00.513  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:39:00.513  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:00.513  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:00.513  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:39:00.513  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:00.513  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:39:00.513  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:39:00.513  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 21:39:00.526  7142  7751 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 21:39:00.526  7142  7751 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-24 21:39:00.534  7142  7805 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-24 21:39:00.537  7142  7751 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-24 21:39:00.538  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:39:00.542  7142  7805 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 21:39:00.542  7142  7805 W bt-smp  : Plain text(LSB ~ MSB) = 51 90 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 21:39:00.542  7142  7805 W bt-smp  : Encrypted text(LSB ~ MSB) = ac 5d 87 01 31 7d 46 13 bb a5 3b e9 cd 1a f5 2a 
08-24 21:39:00.543  7142  7805 W bt-btm  : Stopping oneshot timer
08-24 21:39:00.549  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:39:00.549  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:00.549  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:00.549  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:39:00.549  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:00.549  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:39:00.549  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:39:00.549  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 21:39:00.566  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 21:39:00.574  7142  7747 D LGBluetoothServiceAdapter: [BTUI] OnState
08-24 21:39:00.574  7142  7747 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-24 21:39:00.574  7142  7747 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-24 21:39:00.577  7142  7747 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-24 21:39:00.577  7142  7747 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-24 21:39:00.577  7142  7805 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 21:39:00.577  7142  7805 W bt-smp  : Plain text(LSB ~ MSB) = a4 6e 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 21:39:00.577  7142  7805 W bt-smp  : Encrypted text(LSB ~ MSB) = a9 5a 34 e2 20 81 0d 82 ff 5e df 6c ae 86 3c ca 
08-24 21:39:00.578  7142  7805 W bt-btm  : Stopping oneshot timer
08-24 21:39:00.579  7043  7059 D BluetoothPan: onBluetoothStateChange on: true
08-24 21:39:00.579  7043  7059 D BluetoothPan: onBluetoothStateChange call bindService
,08-24 21:39:00.595  1850  2468 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 21:39:00.609  1850  1850 D BluetoothHeadset: Proxy object connected
,08-24 21:39:00.611  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 21:39:00.614  7142  7805 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 21:39:00.614  7142  7805 W bt-smp  : Plain text(LSB ~ MSB) = 4c d9 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 21:39:00.614  7142  7805 W bt-smp  : Encrypted text(LSB ~ MSB) = d4 75 fa 28 6f ad a4 58 68 3f 77 0e 71 05 92 b6 
08-24 21:39:00.615  7142  7805 W bt-btm  : Stopping oneshot timer
08-24 21:39:00.623  7858  7858 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-24 21:39:00.630  1850  1850 D BluetoothHeadset: Proxy object connected
,08-24 21:39:00.630  1037  1112 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 21:39:00.632  7043  7043 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 21:39:00.632  7043  7043 D PanProfile: Bluetooth service connected
08-24 21:39:00.632  1850  3512 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 21:39:00.635  1850  1850 D BluetoothHeadset: Proxy object connected
08-24 21:39:00.638  1037  1037 D BluetoothA2dp: Proxy object connected
,08-24 21:39:00.643  7142  7805 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-24 21:39:00.643  7142  7805 W bt-smp  : Plain text(LSB ~ MSB) = a8 4b 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 21:39:00.643  7142  7805 W bt-smp  : Encrypted text(LSB ~ MSB) = f5 9e 53 25 7d a3 75 d4 03 5e 76 c3 c9 8c 74 35 
08-24 21:39:00.643  7142  7805 W bt-btm  : Stopping oneshot timer
08-24 21:39:00.647  7043  7059 D BluetoothMap: onBluetoothStateChange: up=true
08-24 21:39:00.655  7043  7352 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 21:39:00.661  7043  7059 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 21:39:00.664  1037  1112 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 21:39:00.664  7142  7805 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 21:39:00.664  7142  7805 W bt-smp  : Plain text(LSB ~ MSB) = 14 9e 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 21:39:00.664  7142  7805 W bt-smp  : Encrypted text(LSB ~ MSB) = ac e9 51 cd 4c f5 b5 c6 95 a2 7c 3e 07 26 ff 3a 
08-24 21:39:00.664  7142  7805 W bt-btm  : Stopping oneshot timer
08-24 21:39:00.664  1037  1037 D BluetoothHeadset: Proxy object connected
08-24 21:39:00.666  1037  1112 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-24 21:39:00.667  1037  1112 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-24 21:39:00.672  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:00.672  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 21:39:00.676  1940  2251 D LGBluetoothAPIService: Message: 1
08-24 21:39:00.676  1940  2251 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-24 21:39:00.680  7043  7043 D BluetoothInputDevice: Proxy object connected
08-24 21:39:00.680  7043  7043 D HidProfile: Bluetooth service connected
08-24 21:39:00.682  6886  6886 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-24 21:39:00.691  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-24 21:39:00.691  1037  1112 D BluetoothManagerService: Message: 40
08-24 21:39:00.692  1037  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-24 21:39:00.694  1940  2251 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-24 21:39:00.694  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:39:00.694  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:00.694  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:00.694  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:39:00.694  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:00.694  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:39:00.694  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:39:00.694  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 21:39:00.698  7043  7043 D BluetoothMap: Proxy object connected
08-24 21:39:00.698  7043  7043 D MapProfile: Bluetooth service connected
08-24 21:39:00.698  7043  7043 D BluetoothMap: getConnectedDevices()
08-24 21:39:00.700  7142  7142 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:00.700  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:39:00.700  7142  7142 D BluetoothMapService: STATE_ON
08-24 21:39:00.702  7142  7142 D LGBluetoothAPIServer: [BTUI] onCreate()
08-24 21:39:00.702  7142  7871 V BluetoothMapService: getConnectedDevices()
08-24 21:39:00.702  7142  7142 D LGBluetoothAPIServer: [BTUI] onBind()
08-24 21:39:00.702  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:00.707  7043  7043 D LocalBluetoothProfileManager: Adding local A2DP profile
08-24 21:39:00.707  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-24 21:39:00.707  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:00.707  1940  2251 D LGBluetoothAPIService: Message: 100
08-24 21:39:00.707  1940  2251 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-24 21:39:00.709  1037  1112 D BluetoothManagerService: Message: 30
08-24 21:39:00.711  7043  7043 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-24 21:39:00.714  1037  1112 D BluetoothManagerService: Message: 30
08-24 21:39:00.719  7043  7043 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-24 21:39:00.720  7043  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 21:39:00.721  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:39:00.722  7142  7142 V BluetoothPbapService: Pbap Service onCreate
08-24 21:39:00.722  7142  7142 V BluetoothPbapService: Starting PBAP service
08-24 21:39:00.723  7142  7142 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-24 21:39:00.723  7043  7043 D BluetoothA2dp: Proxy object connected
08-24 21:39:00.723  7142  7142 V BluetoothPbapService: Pbap Service onBind
08-24 21:39:00.724  7142  7142 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:00.724  7043  7043 D A2dpProfile: Bluetooth service connected
08-24 21:39:00.724  7142  7142 V BluetoothPbapService: state: 12
08-24 21:39:00.724  7142  7142 V BluetoothMapService: Handler(): got msg=1
08-24 21:39:00.725  7142  7142 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-24 21:39:00.725  7142  7142 V BluetoothPbapService: Handler(): got msg=1
08-24 21:39:00.726  7142  7142 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-24 21:39:00.726  7043  7043 D BluetoothHeadset: Proxy object connected
08-24 21:39:00.726  7142  7142 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 21:39:00.726  7142  7142 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:00.727  7142  7142 V BluetoothPbapReceiver: ***********state = 12
08-24 21:39:00.727  7043  7043 D HeadsetProfile: Bluetooth service connected
08-24 21:39:00.727  7142  7878 D BluetoothMapMasInstance: MAS initSocket()
08-24 21:39:00.727  7142  7879 V BluetoothPbapService: Pbap Service initSocket
08-24 21:39:00.728  7142  7878 D BluetoothMapMasInstance:   masId = 00
08-24 21:39:00.728  7142  7878 D BluetoothMapMasInstance:   msgTypes = 0e
08-24 21:39:00.728  7142  7878 D BluetoothMapMasInstance:   masName = SMS/MMS
08-24 21:39:00.728  7142  7878 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-24 21:39:00.730  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 21:39:00.730  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 21:39:00.731  1037  1623 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:00.731  2196  2196 D c       : Getting all permits...
08-24 21:39:00.731  2196  2196 D a       : Opening database...
08-24 21:39:00.732  7142  7878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 21:39:00.732  7142  7879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 21:39:00.735  7142  7879 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-24 21:39:00.735  7142  7751 D BluetoothAdapterProperties: Scan Mode:21
08-24 21:39:00.735  7142  7879 V BluetoothPbapService: Succeed to create listening socket 
08-24 21:39:00.735  7142  7879 V BluetoothPbapService: Accepting socket connection...
08-24 21:39:00.735  7142  7751 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-24 21:39:00.736  7142  7878 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-24 21:39:00.736  7142  7878 V BluetoothMapMasInstance: Succeed to create listening socket 
08-24 21:39:00.736  7142  7878 D BluetoothMapMasInstance: Accepting socket connection...
08-24 21:39:00.737  7043  7043 D DockEventReceiver: finishStartingService: stopping service
08-24 21:39:00.737  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:00.738  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:00.739  2196  2196 D a       : Opening database auth.proximity.permit_store...
08-24 21:39:00.740  7043  7043 D BluetoothPbap: Proxy object connected
08-24 21:39:00.740  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:00.740  7043  7043 D PbapServerProfile: Bluetooth service connected
08-24 21:39:00.741  2196  2196 D a       : Closing database...
08-24 21:39:00.755  7043  7043 D BluetoothPermissionRequest: onReceive
,08-24 21:39:00.758  7043  7043 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-24 21:39:00.760  7043  7043 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 21:39:00.765  7142  7142 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-24 21:39:00.766  7142  7142 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-24 21:39:00.774  7142  7142 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-24 21:39:00.798  7142  7142 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-24 21:39:00.798  7142  7142 V BtOppService: onCreate
,08-24 21:39:00.803  7142  7142 V BluetoothOppNotification: send message
08-24 21:39:00.806  7142  7142 V BtOppService: Starting RfcommListener
08-24 21:39:00.812  7142  7142 D BluetoothOppPreference: Dumping Names:  
08-24 21:39:00.812  7142  7142 D BluetoothOppPreference: {}
08-24 21:39:00.812  7142  7142 D BluetoothOppPreference: Dumping Channels:  
08-24 21:39:00.812  7142  7142 D BluetoothOppPreference: {}
08-24 21:39:00.814  7142  7142 V BtOppService: onStartCommand
,08-24 21:39:00.822  7142  7142 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:00.823  7142  7142 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-24 21:39:00.823  7142  7888 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 21:39:00.826  7142  7142 V BluetoothOppNotification: new notify threadi!
08-24 21:39:00.828  7142  7142 V BluetoothOppNotification: send delay message
,08-24 21:39:00.829  7142  7142 V BtOppService: start RfcommListener
08-24 21:39:00.831  7142  7889 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-24 21:39:00.832  7142  7142 V BtOppService: RfcommListener started
08-24 21:39:00.833  7142  7885 V BtOppService: Deleted complete outbound shares, number =  0
08-24 21:39:00.834  7142  7889 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18946232 on behalf of 
08-24 21:39:00.835  7142  7888 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 21:39:00.837  7142  7885 V BtOppService: Deleted complete inbound failed shares, number = 0
08-24 21:39:00.837  7142  7885 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-24 21:39:00.840  7142  7889 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-24 21:39:00.840  7142  7890 V BtOppRfcommListener: Starting RFCOMM listener....
,08-24 21:39:00.844  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:00.844  7142  7885 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11c53b83 on behalf of 
08-24 21:39:00.845  7142  7890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 21:39:00.846  7142  7888 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@336e7100 on behalf of 
08-24 21:39:00.847  7142  7888 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-24 21:39:00.849  7142  7889 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-24 21:39:00.851  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:39:00.851  7142  7889 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32744d39 on behalf of 
08-24 21:39:00.851  7142  7142 V BluetoothFtpService: Ftp Service onCreate
08-24 21:39:00.851  7142  7142 I BluetoothFtpService: Ftp Service onCreate
08-24 21:39:00.851  7142  7142 V BluetoothFtpService: Ftp Service onStartCommand
08-24 21:39:00.852  7142  7142 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:00.852  7142  7142 V BluetoothFtpService: Starting Listening on sockets
08-24 21:39:00.852  7142  7889 V BluetoothOppNotification: outbound: succ-0  fail-0
08-24 21:39:00.852  7142  7142 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 21:39:00.852  7142  7142 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 21:39:00.852  7142  7142 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 21:39:00.853  7142  7142 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:00.853  7142  7142 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-24 21:39:00.853  7142  7142 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-24 21:39:00.854  7142  7890 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-24 21:39:00.854  7142  7890 V BtOppRfcommListener: Started RFCOMM listener....
08-24 21:39:00.854  7142  7890 I BtOppRfcommListener: Accept thread started.
08-24 21:39:00.854  7142  7890 V BtOppRfcommListener: Accepting connection...
,08-24 21:39:00.857  7142  7142 V BtOppService: ContentObserver received notification
08-24 21:39:00.857  7142  7142 V BtOppService: ContentObserver received notification
08-24 21:39:00.857  7142  7142 V BluetoothFtpService: Handler(): got msg=1
08-24 21:39:00.858  7142  7889 V BluetoothOppNotification: outbound notification was removed.
08-24 21:39:00.858  7142  7142 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-24 21:39:00.858  7142  7142 V BluetoothFtpService: Ftp Service initSocket
08-24 21:39:00.858  7142  7889 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-24 21:39:00.858  7142  7891 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 21:39:00.859  7142  7891 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 21:39:00.861  7142  7891 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c160cdf on behalf of 
08-24 21:39:00.861  7142  7889 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30c99d2c on behalf of 
08-24 21:39:00.862  1037  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:00.863  7142  7891 V BluetoothOppNotification: update too frequent, put in queue
08-24 21:39:00.863  7142  7142 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 21:39:00.864  7142  7889 V BluetoothOppNotification: inbound: succ-0  fail-0
08-24 21:39:00.866  7142  7889 V BluetoothOppNotification: inbound notification was removed.
08-24 21:39:00.866  7142  7889 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-24 21:39:00.866  7142  7891 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-24 21:39:00.867  7142  7142 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-24 21:39:00.867  7142  7142 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-24 21:39:00.869  7142  7892 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-24 21:39:00.872  7142  7889 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2fc383f5 on behalf of 
08-24 21:39:00.883  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:39:00.884  7142  7142 V BluetoothSapService: Sap Service onCreate
,08-24 21:39:00.886  7142  7142 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-24 21:39:00.886  7142  7142 V BluetoothSapService: state: 12
08-24 21:39:00.886  7142  7142 V BluetoothSapService: Starting SAP server process
08-24 21:39:00.888  7142  7142 V BluetoothSapService: SAP Service startRfcommListenerThread
08-24 21:39:00.884  7893  7893 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:39:00.884  7893  7893 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:39:00.890  7142  7894 V BluetoothSapService: Sap Service initRfcommSocket
08-24 21:39:00.891  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:00.892  7142  7894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 21:39:00.893  7142  7894 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-24 21:39:00.893  7142  7894 V BluetoothSapService: Succeed to create listening socket 
08-24 21:39:00.893  7142  7894 V BluetoothSapService: Accepting socket connection...
08-24 21:39:00.908  7893  7893 V BT_SAP  : Event pipe created
08-24 21:39:00.908  7893  7893 V BT_SAP  : create_server_socket qcom.sap.server
08-24 21:39:00.908  7893  7893 V BT_SAP  : created socket fd 6
,08-24 21:39:01.375  1037  1409 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 21:39:01.399  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-24 21:39:01.482  1037  1097 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7904 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-24 21:39:01.492  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-24 21:39:01.492  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-24 21:39:01.518  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-24 21:39:01.532  1037  1037 D administrator: Handling package changes for user 0
,08-24 21:39:01.555  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-24 21:39:01.585  7904  7904 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-24 21:39:01.656  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-24 21:39:01.656  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-24 21:39:01.681  7904  7904 D LgDataFeature: LgDataFeature() Constructor: none
08-24 21:39:01.681  7904  7904 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 21:39:01.726  1037  1095 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 21:39:01.733  1037  1095 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-24 21:39:01.741  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-24 21:39:01.742  2504  2504 V GmsNetworkLocationProvi: DISABLE
,08-24 21:39:01.764  1037  1095 D LocationProviderProxy: applying state to connected service
,08-24 21:39:01.766  2504  2504 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-24 21:39:01.800  7904  7948 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-24 21:39:01.800  7904  7948 I Babel   : MmsConfig.loadMmsSettings
08-24 21:39:01.805  7904  7948 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-24 21:39:01.806  7904  7948 I Babel   : MmsConfig.loadFromDatabase
,08-24 21:39:01.821  7904  7948 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-24 21:39:01.821  7904  7948 I Babel   : MmsConfig.loadFromResources
08-24 21:39:01.823  7904  7948 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-24 21:39:01.824  7904  7948 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-24 21:39:01.829  7142  7142 V BluetoothOppNotification: new notify threadi!
08-24 21:39:01.829  7142  7142 V BluetoothOppNotification: send delay message
,08-24 21:39:01.830  7142  7951 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-24 21:39:01.831  7142  7951 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e956a71 on behalf of 
08-24 21:39:01.832  7142  7951 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-24 21:39:01.833  7142  7951 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-24 21:39:01.834  7142  7951 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1072f056 on behalf of 
08-24 21:39:01.834  7142  7951 V BluetoothOppNotification: outbound: succ-0  fail-0
08-24 21:39:01.836  7142  7951 V BluetoothOppNotification: outbound notification was removed.
08-24 21:39:01.836  7142  7951 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-24 21:39:01.837  7142  7951 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3eaeb8d7 on behalf of 
08-24 21:39:01.838  7142  7951 V BluetoothOppNotification: inbound: succ-0  fail-0
08-24 21:39:01.838  7142  7951 V BluetoothOppNotification: inbound notification was removed.
08-24 21:39:01.839  7142  7951 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-24 21:39:01.840  7142  7951 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a0065c4 on behalf of 
08-24 21:39:01.840  7904  7904 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 21:39:01.855  7904  7947 W AudioCapabilities: Unsupported mime audio/evrc
,08-24 21:39:01.857  7904  7947 W AudioCapabilities: Unsupported mime audio/qcelp
08-24 21:39:01.858  7904  7947 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 21:39:01.871  7904  7947 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-24 21:39:01.873  7904  7947 W AudioCapabilities: Unsupported mime audio/qcelp
08-24 21:39:01.874  7904  7947 W AudioCapabilities: Unsupported mime audio/evrc
08-24 21:39:01.890  1815  7952 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-24 21:39:01.890  1815  7952 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-24 21:39:01.901  7233  7233 I AppUp4:CustModeStarterReceiver: onReceive
,08-24 21:39:01.907  7233  7233 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1ab2b83b
08-24 21:39:01.907  7233  7233 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 21:39:01.907  1815  4760 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-24 21:39:01.907  7233  7233 D AppUp4:CustFacade: isPhone : true
08-24 21:39:01.907  7233  7233 D AppUp4:CustModeStarterReceiver: begin check event
08-24 21:39:01.907  7233  7233 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-24 21:39:01.924  7904  7947 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-24 21:39:01.927  7904  7947 W VideoCapabilities: Unsupported mime video/divx
08-24 21:39:01.937  7904  7947 W VideoCapabilities: Unsupported mime video/divx311
,08-24 21:39:01.940  7904  7947 W VideoCapabilities: Unsupported mime video/divx4
08-24 21:39:01.953  7904  7947 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-24 21:39:01.957  1037  1884 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7956 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-24 21:39:01.963  1037  1576 I ActivityManager: Killing 7274:com.lge.email/u0a23 (adj 15): empty #17
,08-24 21:39:01.981  7904  7947 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-24 21:39:01.987  7904  7947 W AudioCapabilities: Unsupported mime audio/eac3
08-24 21:39:01.988  7904  7947 W AudioCapabilities: Unsupported mime audio/ac3
08-24 21:39:01.989  7904  7947 W AudioCapabilities: Unsupported mime audio/g726
08-24 21:39:01.990  7904  7947 W AudioCapabilities: Unsupported mime audio/wma-voice
08-24 21:39:01.991  7904  7947 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-24 21:39:01.992  7904  7947 W AudioCapabilities: Unsupported mime audio/adpcm
08-24 21:39:01.995  7904  7947 W VideoCapabilities: Unsupported mime video/theora
,08-24 21:39:02.006  7904  7947 W VideoCapabilities: Unsupported mime video/mjpg
08-24 21:39:02.017  1037  2032 W libprocessgroup: failed to open /acct/uid_10023/pid_7274/cgroup.procs: No such file or directory
,08-24 21:39:02.038  7956  7956 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 21:39:02.038  7956  7956 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-24 21:39:02.038  7956  7956 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-24 21:39:02.040  7956  7956 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-24 21:39:02.040  7956  7956 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 21:39:02.126  7956  7956 I SystemConfig: BUILD Country: EU
08-24 21:39:02.126  7956  7956 I SystemConfig: BUILD Operator: OPEN
,08-24 21:39:02.188  1037  1885 I ActivityManager: Killing 7159:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-24 21:39:02.417  1037  1623 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7979 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-24 21:39:02.426  1037  1921 W libprocessgroup: failed to open /acct/uid_10026/pid_7159/cgroup.procs: No such file or directory
08-24 21:39:02.427  7956  7974 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-24 21:39:02.427  7956  7974 I SystemConfig: existFile = false
08-24 21:39:02.427  7956  7974 I SystemConfig: canReadFile = false
08-24 21:39:02.428  7956  7974 I SystemConfig: systemFeature RCS result false
08-24 21:39:02.428  7956  7974 D SystemConfig: refreshRcsSupport() :false
,08-24 21:39:02.485  7979  7979 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 21:39:02.485  7979  7979 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-24 21:39:02.486  7979  7979 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-24 21:39:02.486  7979  7979 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 21:39:02.584  7979  7979 I AppConfig: Total System Memory = 2995761152
,08-24 21:39:02.594  7979  7979 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-24 21:39:02.680  1037  2050 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8001 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 21:39:02.684  1037  2050 I ActivityManager: Killing 6556:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-24 21:39:02.736  1037  1053 W libprocessgroup: failed to open /acct/uid_1000/pid_6556/cgroup.procs: No such file or directory
,08-24 21:39:02.920  8001  8001 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-24 21:39:03.023  8001  8001 D LgDataFeature: LgDataFeature() Constructor: none
08-24 21:39:03.023  8001  8001 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 21:39:03.077  8001  8001 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-24 21:39:03.097  8001  8001 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-24 21:39:03.098  8001  8001 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-24 21:39:03.114  8001  8001 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 21:39:03.114  8001  8001 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-24 21:39:03.143  1037  1053 I ActivityManager: Killing 7305:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-24 21:39:03.176  1037  2013 W libprocessgroup: failed to open /acct/uid_10046/pid_7305/cgroup.procs: No such file or directory
,08-24 21:39:03.188  2848  2864 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-24 21:39:03.192  4615  8038 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-24 21:39:03.336  1037  1958 I art     : Explicit concurrent mark sweep GC freed 58198(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.218ms total 146.796ms
,08-24 21:39:03.339  2848  2864 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@271fbf01 on behalf of 8001
08-24 21:39:03.386  1037  1886 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8040 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-24 21:39:03.412   355   355 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 464us total 26.640ms
,08-24 21:39:03.433   355   355 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 414us total 19.362ms
,08-24 21:39:03.441  8001  8001 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-24 21:39:03.453   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 400us total 18.925ms
,08-24 21:39:03.459  8001  8001 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-24 21:39:03.472  8040  8040 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-24 21:39:03.490  8040  8040 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-24 21:39:03.490  8040  8040 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-24 21:39:03.490  8040  8040 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-24 21:39:03.490  8040  8040 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-24 21:39:03.490  8040  8040 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-24 21:39:03.490  8040  8040 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-24 21:39:03.506  1037  1921 I ActivityManager: Killing 7331:com.android.chrome/u0a57 (adj 15): empty #17
,08-24 21:39:03.600  1037  1053 W libprocessgroup: failed to open /acct/uid_10057/pid_7331/cgroup.procs: No such file or directory
,08-24 21:39:03.855  1037  1886 V SIM_STK : Menu title from STK is T-Mobile
,08-24 21:39:03.880  4615  8038 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 688 ms] updated apps [took 688 ms] 
,08-24 21:39:04.320  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 21:39:04.320  1037  1052 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1cfcfd9 mBinding = false
,08-24 21:39:04.357  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 21:39:04.357  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 21:39:04.357  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,08-24 21:39:04.360  1037  1112 D BluetoothManagerService: Message: 2
08-24 21:39:04.361  1037  1112 D BluetoothManagerService: Sending off request.
08-24 21:39:04.362  7142  7871 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-24 21:39:04.363  7142  7747 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-24 21:39:04.363  7142  7747 D BluetoothAdapterProperties: Setting state to 13
08-24 21:39:04.363  7142  7747 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 21:39:04.364  7142  7747 D BluetoothAdapterProperties: onBluetoothDisable()
08-24 21:39:04.364  7142  7747 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-24 21:39:04.366  7142  7751 D BluetoothAdapterProperties: Scan Mode:20
08-24 21:39:04.367  7142  7747 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-24 21:39:04.368  7142  7879 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 21:39:04.370  7142  7878 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-24 21:39:04.370  7142  7878 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 21:39:04.370  7142  7878 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-24 21:39:04.370  7142  7878 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-24 21:39:04.370  7142  7878 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-24 21:39:04.370  7142  7878 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-24 21:39:04.370  7142  7878 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-24 21:39:04.370  7142  7878 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-24 21:39:04.374  7142  7890 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 21:39:04.374  7142  7892 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 21:39:04.375  7142  7894 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 21:39:04.376  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-24 21:39:04.376  7142  7805 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-24 21:39:04.378  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 21:39:04.378  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 21:39:04.378  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 21:39:04.378  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 21:39:04.378  7142  7805 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 21:39:04.378  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 21:39:04.378  7142  7805 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 21:39:04.378  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 21:39:04.378  7142  7805 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 21:39:04.378  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-24 21:39:04.378  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-24 21:39:04.378  7142  7805 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 21:39:04.379  7142  7747 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 21:39:04.384  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:39:04.384  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:39:04.384  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:04.384  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:04.384  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:39:04.384  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:39:04.384  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:39:04.384  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:39:04.384  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 21:39:04.399  1037  1546 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-24 21:39:04.403  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:39:04.404  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:39:04.409  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:39:04.409  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:39:04.409  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:04.409  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:04.409  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:39:04.409  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:39:04.409  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:39:04.409  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:39:04.409  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 21:39:04.410  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:39:04.410  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:39:04.413  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:39:04.413  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:39:04.413  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:04.413  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:04.413  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:39:04.413  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 21:39:04.413  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:39:04.413  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:39:04.413  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 21:39:04.416  6886  6886 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 21:39:04.416  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:39:04.417  1037  1112 D BluetoothManagerService: Message: 60
08-24 21:39:04.417  1037  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-24 21:39:04.417  1037  1112 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-24 21:39:04.419  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:04.421  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 21:39:04.425  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 21:39:04.429  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:04.431  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:04.432  7142  7142 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:04.432  7142  7142 D BluetoothMapService: STATE_TURNING_OFF
08-24 21:39:04.432  7142  7142 V BluetoothMapService: Handler(): got msg=4
08-24 21:39:04.432  7142  7142 D BluetoothMapService: MAP Service closeService in
08-24 21:39:04.433  7142  7142 D BluetoothMapMasInstance: MAP Service shutdown
08-24 21:39:04.433  7142  7142 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 21:39:04.433  7142  7142 V BluetoothMapService: MAP Service closeService out
08-24 21:39:04.434  7142  7142 V BtOppService: Receiver DISABLED_ACTION 
08-24 21:39:04.434  7142  7142 I BtOppRfcommListener: stopping Accept Thread
08-24 21:39:04.434  7142  7142 V BtOppRfcommListener: close mBtServerSocket
08-24 21:39:04.435  7142  7890 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 21:39:04.435  7142  7142 V BtOppRfcommListener: waiting for thread to terminate
08-24 21:39:04.435  7142  7142 V BtOppRfcommListener: done waiting for thread to terminate
08-24 21:39:04.440  7043  7043 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-24 21:39:04.445  7043  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 21:39:04.451  7142  7142 V BtOppService: onDestroy
,08-24 21:39:04.454  7142  7142 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-24 21:39:04.459  7142  7142 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 21:39:04.460  7142  7142 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:04.460  7142  7142 V BluetoothPbapReceiver: ***********state = 13
08-24 21:39:04.461  7142  7142 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-24 21:39:04.462  7142  7142 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:04.462  7142  7142 V BluetoothPbapService: state: 13
08-24 21:39:04.462  7142  7142 V BluetoothPbapService: Pbap Service closeService in
08-24 21:39:04.466  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 21:39:04.470  7142  7142 V BluetoothPbapService: successfully stopped pbap service
08-24 21:39:04.470  7142  7142 V BluetoothPbapService: Pbap Service closeService out
08-24 21:39:04.471  7142  7142 V BluetoothPbapService: Pbap Service onDestroy
08-24 21:39:04.471  7142  7142 V BluetoothPbapService: Pbap Service closeService in
08-24 21:39:04.471  7142  7142 V BluetoothPbapService: Pbap Service closeService out
08-24 21:39:04.471  7142  7142 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-24 21:39:04.488  7043  7043 D DockEventReceiver: finishStartingService: stopping service
,08-24 21:39:04.493  7043  7043 D BluetoothPbap: Proxy object disconnected
08-24 21:39:04.493  7043  7043 D PbapServerProfile: Bluetooth service disconnected
08-24 21:39:04.500  7043  7043 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-24 21:39:04.507  7043  7043 D BluetoothPermissionRequest: onReceive
08-24 21:39:04.507  7043  7043 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-24 21:39:04.513  7043  7043 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-24 21:39:04.520  7142  7142 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-24 21:39:04.520  7142  7142 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-24 21:39:04.520  7142  7142 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-24 21:39:04.523  7142  7142 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:04.523  7142  7142 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-24 21:39:04.525  7142  7142 V BluetoothFtpService: Ftp Service onStartCommand
08-24 21:39:04.525  7142  7142 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-24 21:39:04.530  7142  7142 V BluetoothFtpService: Ftp Service closeService
,08-24 21:39:04.530  7142  7142 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-24 21:39:04.532  7142  7142 V BluetoothFtpService: successfully stopped ftp service
08-24 21:39:04.539  7142  7142 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 21:39:04.539  7142  7142 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 21:39:04.540  7142  7142 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 21:39:04.540  7142  7142 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:04.540  7142  7142 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-24 21:39:04.540  7142  7142 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-24 21:39:04.548  7142  7142 V BluetoothFtpService: Ftp Service onDestroy
,08-24 21:39:04.548  7142  7142 V BluetoothFtpService: Ftp Service closeService
08-24 21:39:04.549  7142  7142 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:04.549  7142  7142 V BluetoothSapService: state: 13
,08-24 21:39:04.549  7142  7142 V BluetoothSapService: Stopping SAP server process
08-24 21:39:04.551  7142  7142 V BluetoothSapService: Sap Service closeSapService in
08-24 21:39:04.552  7142  7142 V BluetoothSapService: Close listen Socket : 
08-24 21:39:04.552  7142  7142 V BluetoothSapService: Close rfcomm Socket : 
08-24 21:39:04.552  7142  7142 V BluetoothSapService: Close sapd  Socket : 
08-24 21:39:04.553  7142  7142 V BluetoothSapService: Sap Service closeSapService out
08-24 21:39:04.553  7142  7142 V BluetoothSapService: Sap Service onDestroy
08-24 21:39:04.553  7142  7142 V BluetoothSapService: Sap Service closeSapService in
,08-24 21:39:04.553  7142  7142 V BluetoothSapService: Close listen Socket : 
08-24 21:39:04.553  7142  7142 V BluetoothSapService: Close rfcomm Socket : 
08-24 21:39:04.553  7142  7142 V BluetoothSapService: Close sapd  Socket : 
08-24 21:39:04.554  7142  7142 V BluetoothSapService: Sap Service closeSapService out
08-24 21:39:05.298  7142  7751 D bt_hci_bdroid: cleanup
,08-24 21:39:05.309  7142  7807 I bt_lpm  : LPM is already off!!!
08-24 21:39:05.310  7142  7845 I bt_userial_mct: exiting userial_read_thread
08-24 21:39:05.310  7142  7845 D bt_userial_mct: Leaving userial_evt_read_thread()
08-24 21:39:05.310  7142  7805 W bt-btif : ag scb idx 1 not allocated
08-24 21:39:05.310  7142  7805 E bt-btif : BTA AG is already disabled, ignoring ...
08-24 21:39:05.310  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 21:39:05.310  7142  7805 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 21:39:05.310  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 21:39:05.310  7142  7805 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 21:39:05.310  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 21:39:05.310  7142  7805 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 21:39:05.310  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 21:39:05.310  7142  7805 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 21:39:05.310  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 21:39:05.311  7142  7805 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 21:39:05.311  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 21:39:05.311  7142  7805 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 21:39:05.311  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 21:39:05.311  7142  7805 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 21:39:05.311  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 21:39:05.311  7142  7805 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 21:39:05.311  7142  7805 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 21:39:05.311  7142  7805 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 21:39:05.311  7142  7805 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 21:39:05.312  7142  7751 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-24 21:39:05.312  7142  7807 I bt_vendor: hw_epilog_process
08-24 21:39:05.313  7142  7751 D bt_hci_bdroid: cleanup Finalizing cleanup
08-24 21:39:05.313  7142  7751 D bt_userial_mct: userial_close
08-24 21:39:05.313  7142  7751 E bt_userial_mct: pthread_join() FAILED result:3
08-24 21:39:05.313  7142  7751 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-24 21:39:05.316  7142  7751 D bt_hci_bdroid: set_power 0
08-24 21:39:05.316  7142  7751 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-24 21:39:05.316  7142  7751 I bt_vendor: bluetooth satus is on
08-24 21:39:05.316  7142  7751 I bt_vendor: bt-vendor : resetting BT status
08-24 21:39:05.316  7142  7751 I bt_vendor: Starting hciattach daemon
08-24 21:39:05.316  7142  7751 I bt_vendor: try to set false
08-24 21:39:05.318  7142  7751 I bt_vendor: Starting hciattach daemon
08-24 21:39:05.318  7142  7751 I bt_vendor: try to set false
,08-24 21:39:05.324  7142  7751 I bt_vendor: cleanup
08-24 21:39:05.325  7142  7805 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-24 21:39:05.326  7142  7751 I GKI_LINUX: GKI_exit_task 0 done
08-24 21:39:05.326  7142  7751 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-24 21:39:05.328  7142  7747 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-24 21:39:05.333  1037  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{e72e07f type 2 when 362122 com.google.android.gms} when 362122
,08-24 21:39:05.336  7142  7142 D HeadsetService: Received stop request...Stopping profile...
08-24 21:39:05.339  7142  7142 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-24 21:39:05.340  7142  7142 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 21:39:05.340  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:39:05.340  7142  7782 D HeadsetStateMachine: Exit Disconnected: -1
08-24 21:39:05.344  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-24 21:39:05.344  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-24 21:39:05.344  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-24 21:39:05.345  1037  1037 D BluetoothHeadset: Proxy object disconnected
08-24 21:39:05.345  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-24 21:39:05.350  7142  7142 D A2dpService: Received stop request...Stopping profile...
08-24 21:39:05.351  7142  7794 D A2dpStateMachine: Exit Disconnected: -1
08-24 21:39:05.354  7142  7142 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-24 21:39:05.355  7142  7142 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-24 21:39:05.355  7142  7142 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 21:39:05.355  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:39:05.359  7142  7142 D HidService: Received stop request...Stopping profile...
08-24 21:39:05.359  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
,08-24 21:39:05.361  1037  1037 D BluetoothA2dp: Proxy object disconnected
08-24 21:39:05.361  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-24 21:39:05.363  7142  7747 D BluetoothAdapterState: Stopping profile services that were post enabled
08-24 21:39:05.365  7142  7142 D HealthService: Received stop request...Stopping profile...
08-24 21:39:05.365  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:39:05.367  7142  7142 D HeadsetStateMachine: Unbinding service...
08-24 21:39:05.368  7142  7142 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 21:39:05.368  7142  7142 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 21:39:05.368  7142  7142 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 21:39:05.368  7142  7142 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 21:39:05.368  7142  7142 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-24 21:39:05.368  7142  7142 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 21:39:05.368  7142  7142 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-24 21:39:05.369  7142  7142 D PanService: Received stop request...Stopping profile...
08-24 21:39:05.370  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:39:05.371  7142  7142 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 21:39:05.374  7142  7142 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 21:39:05.375  7142  7142 D BtGatt.GattService: stop()
08-24 21:39:05.376  7142  7142 D BtGatt.AdvertiseManager: advertise clients cleared
08-24 21:39:05.377  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:39:05.377  7142  7142 I BluetoothA2dpServiceJni: cleanupNative
08-24 21:39:05.378  7142  7795 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-24 21:39:05.378  7142  7142 I GKI_LINUX: GKI_exit_task 2 done
08-24 21:39:05.378  7142  7142 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-24 21:39:05.380  7142  7142 D BluetoothMapService: Received stop request...Stopping profile...
08-24 21:39:05.380  7142  7142 D BluetoothMapService: stop()
08-24 21:39:05.380  7142  7142 D BluetoothMapEmailAppObserver: deinitObservers()
08-24 21:39:05.380  7142  7142 D BluetoothMapEmailAppObserver: removeReceiver()
08-24 21:39:05.381  7142  7142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@155324b1
08-24 21:39:05.382  7142  7142 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 21:39:05.382  7142  7142 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 21:39:05.383  7142  7142 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 21:39:05.383  7142  7142 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 21:39:05.383  7142  7142 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 21:39:05.383  7142  7142 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 21:39:05.384  7142  7142 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-24 21:39:05.388  7142  7142 V BluetoothMapService: Handler(): got msg=4
08-24 21:39:05.388  7142  7142 D BluetoothMapService: MAP Service closeService in
08-24 21:39:05.388  7142  7142 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 21:39:05.388  7142  7142 V BluetoothMapService: MAP Service closeService out
08-24 21:39:05.390  7142  7747 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-24 21:39:05.390  7142  7747 D BluetoothAdapterProperties: Setting state to 10
08-24 21:39:05.390  7142  7747 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-24 21:39:05.390  1037  1112 D BluetoothManagerService: Message: 60
08-24 21:39:05.391  1037  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-24 21:39:05.391  1037  1112 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-24 21:39:05.391  7142  7747 I BluetoothAdapterState: Entering OffState
08-24 21:39:05.391  7043  7059 D BluetoothPan: onBluetoothStateChange on: false
08-24 21:39:05.394  7142  7142 D BluetoothMapService: cleanup()
08-24 21:39:05.394  7142  7142 D BluetoothMapService: MAP Service closeService in
08-24 21:39:05.394  7142  7142 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 21:39:05.394  7142  7142 V BluetoothMapService: MAP Service closeService out
08-24 21:39:05.397  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-24 21:39:05.400  1850  3512 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 21:39:05.401  1037  1112 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 21:39:05.402  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 21:39:05.402  7043  7059 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 21:39:05.403  7043  7059 D BluetoothMap: onBluetoothStateChange: up=false
08-24 21:39:05.403  7043  7059 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 21:39:05.404  7043  7059 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 21:39:05.404  7043  7059 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 21:39:05.405  1037  1112 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 21:39:05.406  1037  1112 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-24 21:39:05.406  1037  1112 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-24 21:39:05.408  1037  1112 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-24 21:39:05.408  1037  1112 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-24 21:39:05.408  1037  1112 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1cfcfd9 mBinding = false
08-24 21:39:05.408  1037  1112 D BluetoothManagerService: Sending unbind request.
08-24 21:39:05.413  7142  7751 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-24 21:39:05.416  7142  7142 I GKI_LINUX: GKI_exit_task 1 done
08-24 21:39:05.416  7142  7142 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-24 21:39:05.416  7142  7142 I BluetoothServiceJni: cleanupNative: return from cleanup
08-24 21:39:05.417  7142  7142 I art     : --- WEIRD: removing null entry 248
08-24 21:39:05.417  7142  7142 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-24 21:39:05.417  7142  7142 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-24 21:39:05.418  7142  7142 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-24 21:39:05.419  1037  1112 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-24 21:39:05.421  7142  7142 I art     : System.exit called, status: 0
08-24 21:39:05.421  7142  7142 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-24 21:39:05.440   332  1386 V AudioFlinger: 7142 died, releasing its sessions
08-24 21:39:05.440   332  1386 V AudioFlinger:  pid 1850 @ 0
08-24 21:39:05.440   332  1386 V AudioFlinger:  pid 3433 @ 1
08-24 21:39:05.440   332  1386 V AudioFlinger:  pid 3433 @ 2
,08-24 21:39:05.444  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-24 21:39:05.444  1940  2251 D LGBluetoothAPIService: Message: 101
08-24 21:39:05.444  1940  2251 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-24 21:39:05.444  1940  2251 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-24 21:39:05.444  1940  2251 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-24 21:39:05.448  7043  7043 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-24 21:39:05.464   328  8122 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-24 21:39:05.465  1037  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-24 21:39:05.486  1037  1958 I ActivityManager: Process com.android.bluetooth (pid 7142) has died
08-24 21:39:05.486  1037  1958 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-24 21:39:05.487  1037  1958 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 10999ms
,08-24 21:39:05.493  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-24 21:39:05.494  1940  2251 D LGBluetoothAPIService: Message: 2
08-24 21:39:05.494  1940  2251 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-24 21:39:05.494  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 21:39:05.495  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:05.496  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:05.497  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:05.497  7043  7043 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-24 21:39:05.497  7043  7043 D LGBluetoothEventManager: [BTUI] clear device connection state
08-24 21:39:05.499  1604  1604 D BluetoothAdapter: 321677808: getState() :  mService = null. Returning STATE_OFF
08-24 21:39:05.499  1604  1604 D BluetoothAdapter: 321677808: getState() :  mService = null. Returning STATE_OFF
,08-24 21:39:05.505  7043  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 21:39:05.568  1037  1958 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=8128 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-24 21:39:05.571  7043  7043 D DockEventReceiver: finishStartingService: stopping service
,08-24 21:39:05.649  8128  8128 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-24 21:39:05.649  8128  8128 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 21:39:05.650  8128  8128 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-24 21:39:05.651  8128  8128 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 21:39:05.671  8128  8128 D BluetoothAdapterApp: Loading JNI Library
,08-24 21:39:05.708  8128  8128 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2d75ff79 Instance Count = 1
,08-24 21:39:05.715  8128  8128 D BluetoothAdapterApp: onCreate
08-24 21:39:05.741  8128  8128 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-24 21:39:05.742  8128  8128 D ProfileConfigQcom: Adding HeadsetService
08-24 21:39:05.742  8128  8128 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-24 21:39:05.742  8128  8128 D ProfileConfigQcom: Adding A2dpService
08-24 21:39:05.742  8128  8128 D ProfileConfigQcom: [BTUI] HidService is supported
08-24 21:39:05.742  8128  8128 D ProfileConfigQcom: Adding HidService
08-24 21:39:05.743  8128  8128 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-24 21:39:05.743  8128  8128 D ProfileConfigQcom: Adding HealthService
08-24 21:39:05.743  8128  8128 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-24 21:39:05.744  8128  8128 D ProfileConfigQcom: [BTUI] PanService is supported
08-24 21:39:05.745  8128  8128 D ProfileConfigQcom: Adding PanService
,08-24 21:39:05.745  8128  8128 D ProfileConfigQcom: [BTUI] GattService is supported
08-24 21:39:05.745  8128  8128 D ProfileConfigQcom: Adding GattService
08-24 21:39:05.745  8128  8128 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-24 21:39:05.745  8128  8128 D ProfileConfigQcom: Adding BluetoothMapService
08-24 21:39:05.746  8128  8128 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-24 21:39:05.747  8128  8128 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 21:39:05.749  8128  8128 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:05.749  8128  8128 V BluetoothPbapReceiver: ***********state = 10
,08-24 21:39:05.757  8128  8128 V LGMDMManagerInternal: Create singleton instance
08-24 21:39:05.865  8128  8128 D LGBluetoothAPIServer: [BTUI] onCreate()
08-24 21:39:05.865  8128  8128 D LGBluetoothAPIServer: [BTUI] onBind()
,08-24 21:39:05.870  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 21:39:05.871  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-24 21:39:05.872  1940  2251 D LGBluetoothAPIService: Message: 100
08-24 21:39:05.872  1940  2251 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-24 21:39:05.886  7043  7043 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-24 21:39:05.892  7043  7043 D BluetoothPermissionRequest: onReceive
08-24 21:39:05.895  7043  7043 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-24 21:39:05.895  7043  7043 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-24 21:39:05.900  7043  7043 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-24 21:39:05.912  8128  8128 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-24 21:39:05.921  8128  8128 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-24 21:39:05.930  8128  8128 V BluetoothSapReceiver: [BTUI] checkServiceStart,
08-24 21:39:05.931  8128  8128 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 21:39:05.931  8128  8128 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 21:39:05.932  8128  8128 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:05.933  8128  8128 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-24 21:39:05.944  7811  7811 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-24 21:39:09.432  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 21:39:09.432  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 21:39:09.444  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 21:39:09.444  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@283af1f9 removed from the list
08-24 21:39:09.444  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:39:09.444  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 21:39:09.444  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:09.448  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 21:39:09.448  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b2b1f9f added. We now have 4 listener(s)
08-24 21:39:09.449  6886  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 21:39:09.449  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:09.449  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b2b1f9f removed from the list
08-24 21:39:09.449  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:39:09.449  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:09.450  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:09.450  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 21:39:09.450  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f918ec added. We now have 4 listener(s)
08-24 21:39:09.450  6886  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 21:39:09.451  1037  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:09.451  1037  1977 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,08-24 21:39:09.457  1037  1112 D BluetoothManagerService: Message: 2
,08-24 21:39:14.464  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 21:39:14.473  1037  2050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:14.474  1037  2050 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-24 21:39:14.498  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 21:39:14.499  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 21:39:14.499  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-24 21:39:14.500  1037  1112 D BluetoothManagerService: Message: 1
08-24 21:39:14.500  1037  1112 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-24 21:39:14.526  1037  1112 D BluetoothManagerService: Message: 20
08-24 21:39:14.526  1037  1112 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@344aa111:true
,08-24 21:39:14.530  8128  8128 D BluetoothAdapterState: make
08-24 21:39:14.535  8128  8128 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-24 21:39:14.535  8128  8128 I bluedroid-qcom: init
08-24 21:39:14.536  8128  8161 I BluetoothAdapterState: Entering OffState
08-24 21:39:14.537  8128  8128 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-24 21:39:14.537  8128  8128 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-24 21:39:14.537  8128  8128 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 21:39:14.537  8128  8128 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 21:39:14.537  8128  8128 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-24 21:39:14.539  8128  8128 I bluedroid-qcom: get_profile_interface socket
08-24 21:39:14.539  8128  8128 I bluedroid-qcom: get_profile_interface map_client
,08-24 21:39:14.544  8128  8165 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-24 21:39:14.534  8164  8164 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:39:14.544  8164  8164 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:39:14.557  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-24 21:39:14.559  1037  1112 D BluetoothManagerService: Message: 40
08-24 21:39:14.559  1037  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-24 21:39:14.560  8128  8145 I bluedroid-qcom: config_hci_snoop_log
08-24 21:39:14.562  1037  1112 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-24 21:39:14.562  1037  1112 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-24 21:39:14.567  8164  8164 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-24 21:39:14.567  8164  8164 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-24 21:39:14.567  8164  8164 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-24 21:39:14.569  8164  8164 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-24 21:39:14.573  8128  8161 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-24 21:39:14.574  8128  8161 D BluetoothAdapterProperties: Setting state to 11
08-24 21:39:14.574  8128  8161 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-24 21:39:14.576  1037  1112 D BluetoothManagerService: Message: 60
08-24 21:39:14.576  1037  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-24 21:39:14.576  1037  1112 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-24 21:39:14.577  8164  8164 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-24 21:39:14.577  8164  8164 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-24 21:39:14.583  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-24 21:39:14.586  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 21:39:14.589  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:14.592  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:14.595  7043  7043 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-24 21:39:14.603  8128  8165 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-24 21:39:14.605  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 21:39:14.605  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-24 21:39:14.609  8128  8128 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 21:39:14.609  8128  8128 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:14.609  8128  8128 V BluetoothPbapReceiver: ***********state = 11
,08-24 21:39:14.620  8128  8165 D BluetoothAdapterProperties: Name is: G3
08-24 21:39:14.623  8128  8161 I LGBluetoothServiceJni: classInitNative: succeeds
,08-24 21:39:14.630  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 21:39:14.637  8128  8161 D BluetoothBondStateMachine: make
08-24 21:39:14.640  8128  8180 I BluetoothBondStateMachine: StableState(): Entering Off State
08-24 21:39:14.640  8128  8161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b7abd96
,08-24 21:39:14.641  8128  8161 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-24 21:39:14.641  8128  8161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b7abd96
08-24 21:39:14.641  8128  8161 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-24 21:39:14.641  8128  8161 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-24 21:39:14.647  8128  8161 E BluetoothAdapterService: File transfer profiles supported!!
08-24 21:39:14.652  7043  7043 D BluetoothPermissionRequest: onReceive
08-24 21:39:14.657  8128  8161 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 21:39:14.661  8128  8128 D HeadsetService: Received start request. Starting profile...
08-24 21:39:14.661  8128  8128 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 21:39:14.661  8128  8128 D LGBluetoothHfpAdapter: Version 1.6
08-24 21:39:14.665  8128  8128 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-24 21:39:14.666  8128  8128 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 21:39:14.667  8128  8128 D HeadsetStateMachine: make
08-24 21:39:14.669  7043  7043 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 21:39:14.670  8128  8161 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 21:39:14.683  8128  8161 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 21:39:14.687  8128  8161 E BluetoothAdapterService: File transfer profiles supported!!
08-24 21:39:14.692  8128  8161 E BluetoothAdapterService: File transfer profiles supported!!
08-24 21:39:14.697  8128  8161 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 21:39:14.704  8128  8128 D LgDataFeature: LgDataFeature() Constructor: none
08-24 21:39:14.704  8128  8128 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 21:39:14.709  8128  8128 D HeadsetStateMachine: max_hf_connections = 1
08-24 21:39:14.709  8128  8128 I bluedroid-qcom: get_profile_interface handsfree
08-24 21:39:14.711  8128  8128 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-24 21:39:14.712   332  1387 V AudioPolicyService: registerClient() client 0xb558a780, uid 1002
08-24 21:39:14.712   332  1386 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-24 21:39:14.712   332  1386 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 21:39:14.712   332  1386 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 21:39:14.712  8128  8128 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-24 21:39:14.712   332  2175 V AudioFlinger: registerClient() client 0xb5581808, pid 8128
08-24 21:39:14.713   332  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 21:39:14.713   332  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 21:39:14.713  1037  1958 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 21:39:14.713  1037  1958 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-24 21:39:14.713  1604  2716 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 21:39:14.713  1604  2716 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 21:39:14.713   332  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 21:39:14.713   332  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 21:39:14.713  1850  2468 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 21:39:14.713  1850  2468 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 21:39:14.713  1850  2468 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 21:39:14.713  8128  8128 V ToneGenerator: Create Track: 0xb4928080
08-24 21:39:14.713  1850  2468 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 21:39:14.713  8128  8128 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-24 21:39:14.713  8128  8128 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-24 21:39:14.713  3433  3450 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 21:39:14.713  3433  3450 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 21:39:14.713   332  1387 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 21:39:14.713   332  1387 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-24 21:39:14.714   332  1387 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 21:39:14.714   332  1387 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 21:39:14.714  3433  3450 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 21:39:14.714  3433  3450 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 21:39:14.714  8128  8128 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-24 21:39:14.714  1037  1977 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 21:39:14.714  1037  1977 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 21:39:14.714  1604  2095 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 21:39:14.714  1604  2095 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 21:39:14.714   332  2175 I AudioFlinger: isAudioPlaybackHookOn() false
08-24 21:39:14.714  8128  8144 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 21:39:14.714  8128  8144 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-24 21:39:14.714   332  2178 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 21:39:14.714   332  2178 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-24 21:39:14.714   332  2178 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 21:39:14.714   332  2178 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 21:39:14.714  8128  8144 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 21:39:14.714  8128  8144 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-24 21:39:14.714  8128  8128 V AudioSystem: getLatency() output 2, latency 50
08-24 21:39:14.714  8128  8128 V AudioSystem: getFrameCount() output 2, frameCount 960
08-24 21:39:14.714  8128  8128 V AudioTrack: createTrack_l() output 2 afLatency 50
08-24 21:39:14.714  8128  8161 V LGMDMManager: Create singleton instance
08-24 21:39:14.715   332   332 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 21:39:14.715   332   332 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 21:39:14.715   332   332 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 21:39:14.715   332   332 V AudioFlinger: [MABL,_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 21:39:14.715   332   332 V AudioFlinger: createTrack() lSessionId: 23
08-24 21:39:14.715  8128  8128 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-24 21:39:14.716   332   332 V AudioFlinger: acquiring 23 from 8128, for 8128
08-24 21:39:14.716   332   332 V AudioFlinger:  added new entry for 23
08-24 21:39:14.716  8128  8128 V ToneGenerator: ToneGenerator INIT OK, time: 371520
08-24 21:39:14.716  8128  8128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b7abd96
08-24 21:39:14.716  8128  8182 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-24 21:39:14.717  8128  8182 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 21:39:14.717  8128  8182 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 21:39:14.717  8128  8182 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-24 21:39:14.718   332  1387 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 8128
08-24 21:39:14.718   332  1387 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-24 21:39:14.718   332  1387 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-24 21:39:14.718   332  1387 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-24 21:39:14.718   332  1387 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-24 21:39:14.718   332  1387 V voice   : voice_set_parameters: exit with code(0)
08-24 21:39:14.718   332  1387 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-24 21:39:14.718   332  1387 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-24 21:39:14.718   332  1387 V msm8974_platform: platform_set_parameters: exit with code(0)
08-24 21:39:14.718   332  1387 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-24 21:39:14.718   332  1387 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-24 21:39:14.718   332  1387 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-24 21:39:14.718  8128  8128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b7abd96
08-24 21:39:14.720  8128  8182 V ToneGenerator: ToneGenerator destructor
08-24 21:39:14.720  8128  8182 V ToneGenerator: stopTone
08-24 21:39:14.720  8128  8182 V ToneGenerator: Delete Track: 0xb4928080
08-24 21:39:14.721  8128  8128 D A2dpService: Received start request. Starting profile...
08-24 21:39:14.721  8128  8161 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-24 21:39:14.721  8128  8128 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-24 21:39:14.722  8128  8128 V Avrcp   : make
08-24 21:39:14.723  8128  8128 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-24 21:39:14.723  8128  8128 I bluedroid-qcom: get_profile_interface avrcp
,08-24 21:39:14.724  1037  1958 W Process : Unable to open /proc/8186/status
08-24 21:39:14.724  8128  8182 V AudioTrack: ~AudioTrack, releasing session id from 8128 on behalf of 8128
08-24 21:39:14.724   332  1386 V AudioFlinger: releasing 23 from 8128 for 8128
08-24 21:39:14.724   332  1386 V AudioFlinger:  decremented refcount to 0
08-24 21:39:14.724   332  1386 V AudioFlinger: purging stale effects
08-24 21:39:14.724   332  1386 V AudioPolicyService: AudioCommandThread() adding release output 2
08-24 21:39:14.724   332  1386 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-24 21:39:14.724   332  1275 V AudioPolicyService: AudioCommandThread() waking up
08-24 21:39:14.724   332  1275 V AudioPolicyService: AudioCommandThread() processing release output 2
08-24 21:39:14.724   332  1275 V AudioPolicyManager: releaseOutput() 2
08-24 21:39:14.724   332  1275 V AudioPolicyService: AudioCommandThread() going to sleep
08-24 21:39:14.724   332  1386 V AudioFlinger: PlaybackThread::Track destructor
08-24 21:39:14.724   332  1386 V AudioFlinger: removeClient_l() pid 8128, calling pid 332
,08-24 21:39:14.732  8128  8128 V AudioManager: registerRemoteController: size of Media player list: 0
08-24 21:39:14.733  8128  8128 E AudioManager: No RCC entry present to update
08-24 21:39:14.733  8128  8128 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-24 21:39:14.736  8128  8128 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-24 21:39:14.737  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-24 21:39:14.737  8128  8128 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-24 21:39:14.741  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-24 21:39:14.869  1037  1053 V SIM_STK : Menu title from STK is T-Mobile
,08-24 21:39:14.869  1037  1053 V SIM_STK : Menu title from STK is T-Mobile
,08-24 21:39:15.021  1037  1052 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-24 21:39:15.037  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-24 21:39:15.043  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-24 21:39:15.044  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-24 21:39:15.044  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-24 21:39:15.044  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-24 21:39:15.044  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 21:39:15.044  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-24 21:39:15.045  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-24 21:39:15.045  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-24 21:39:15.045  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 21:39:15.045  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-24 21:39:15.045  8128  8128 I BluetoothA2dpServiceJni: classInitNative
08-24 21:39:15.046  8128  8128 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 21:39:15.046  8128  8128 D A2dpStateMachine: make
,08-24 21:39:15.052  8128  8128 I bluedroid-qcom: get_profile_interface a2dp
08-24 21:39:15.052  8128  8196 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-24 21:39:15.057  8128  8128 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-24 21:39:15.057  8128  8128 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-24 21:39:15.059  8128  8128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b7abd96
08-24 21:39:15.059  8128  8195 D A2dpStateMachine: Enter Disconnected: -2
08-24 21:39:15.060  8128  8128 I BluetoothHidServiceJni: classInitNative: succeeds
08-24 21:39:15.062  8128  8128 D HidService: Received start request. Starting profile...
08-24 21:39:15.062  8128  8128 I bluedroid-qcom: get_profile_interface hidhost
08-24 21:39:15.062  8128  8128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b7abd96
08-24 21:39:15.063  8128  8128 I BluetoothHealthServiceJni: classInitNative: succeeds
08-24 21:39:15.065  8128  8128 D HealthService: Received start request. Starting profile...
08-24 21:39:15.067  8128  8128 I bluedroid-qcom: get_profile_interface health
08-24 21:39:15.068  8128  8128 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-24 21:39:15.068  8128  8128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b7abd96
08-24 21:39:15.069  8128  8128 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-24 21:39:15.071  8128  8128 D PanService: Received start request. Starting profile...
08-24 21:39:15.071  8128  8128 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 21:39:15.071  8128  8128 I bluedroid-qcom: get_profile_interface pan
,08-24 21:39:15.079  8128  8128 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-24 21:39:15.079  8128  8128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b7abd96
08-24 21:39:15.080  8128  8128 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-24 21:39:15.086  8128  8128 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 21:39:15.088  8128  8128 D BtGatt.GattService: Received start request. Starting profile...
08-24 21:39:15.088  8128  8128 D BtGatt.GattService: start()
08-24 21:39:15.088  8128  8128 I bluedroid-qcom: get_profile_interface gatt
08-24 21:39:15.088  8128  8128 D BtGatt.AdvertiseManager: advertise manager created
08-24 21:39:15.094  8128  8128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b7abd96
08-24 21:39:15.096  8128  8128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b7abd96
08-24 21:39:15.096  8128  8128 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-24 21:39:15.097  8128  8128 V BluetoothMapService: BluetoothMapBinder()
,08-24 21:39:15.098  8128  8128 D BluetoothMapService: Received start request. Starting profile...
08-24 21:39:15.098  8128  8128 D BluetoothMapService: start()
08-24 21:39:15.102  8128  8128 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-24 21:39:15.102  8128  8128 D BluetoothMapEmailAppObserver: createReceiver()
08-24 21:39:15.103  8128  8128 D BluetoothMapEmailAppObserver: initObservers()
08-24 21:39:15.103  8128  8128 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-24 21:39:15.113  8128  8128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b7abd96
08-24 21:39:15.113  8128  8128 D HeadsetStateMachine: Proxy object connected
08-24 21:39:15.114  8128  8128 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-24 21:39:15.114  8128  8128 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-24 21:39:15.116  8128  8182 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 21:39:15.117  8128  8182 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 21:39:15.117  8128  8182 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-24 21:39:15.119  8128  8128 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 21:39:15.122  8128  8128 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 21:39:15.124  8128  8128 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:15.128  8128  8128 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-24 21:39:15.133  8128  8128 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 21:39:15.133  8128  8128 V PanService: [BTUI] SIM Extra State :ABSENT
08-24 21:39:15.136  8128  8128 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 21:39:15.139  8128  8128 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-24 21:39:15.139  8128  8128 V BluetoothMapService: Handler(): got msg=1
08-24 21:39:15.140  8128  8161 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,08-24 21:39:15.140  8128  8128 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 21:39:15.140  8128  8161 I bluedroid-qcom: enable
08-24 21:39:15.140  8128  8128 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 21:39:15.140  8128  8128 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 21:39:15.140  8128  8128 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:15.140  8128  8128 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-24 21:39:15.140  8128  8161 I bt_hci_bdroid: init
08-24 21:39:15.142  8128  8161 I bt_vendor: bt-vendor : init
08-24 21:39:15.142  8128  8161 I bt_vendor: bt-vendor : get_bt_soc_type
08-24 21:39:15.142  8128  8161 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-24 21:39:15.142  8128  8161 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-24 21:39:15.142  8128  8161 D bt_userial_mct: userial_init
08-24 21:39:15.142  8128  8161 D bt_hci_bdroid: set_power 1
08-24 21:39:15.142  8128  8161 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-24 21:39:15.143  8128  8161 I bt_vendor: Starting hciattach daemon
08-24 21:39:15.143  8128  8161 I bt_vendor: try to set true
,08-24 21:39:15.147  8128  8203 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-24 21:39:15.147  8128  8203 I bt-btu  : btu_task pending for preload complete event
08-24 21:39:15.144  8206  8206 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:39:15.144  8206  8206 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:39:15.172  8207  8207 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-24 21:39:15.255  8213  8213 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-24 21:39:15.271  8214  8214 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-24 21:39:15.311  8216  8216 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-24 21:39:15.337  8217  8217 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-24 21:39:15.359  8218  8218 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-24 21:39:15.387  8219  8219 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-24 21:39:15.410  8221  8221 I libmdmdetect: ESOC framework not supported
08-24 21:39:15.411  8221  8221 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-24 21:39:15.421  8221  8221 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-24 21:39:15.421  8221  8221 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-24 21:39:15.421  8221  8221 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-24 21:39:15.421  8221  8221 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-24 21:39:15.421  8221  8221 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-24 21:39:15.421  8221  8221 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-24 21:39:15.421  8221  8221 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-24 21:39:15.458  8221  8222 E QC-QMI  : qmi_client [8221] 15: failed to locate client data
,08-24 21:39:15.462   490   490 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-24 21:39:15.462   490   490 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-24 21:39:15.495  8223  8223 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-24 21:39:15.513  8224  8224 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-24 21:39:15.549  8128  8161 I bt_vendor: bluetooth satus is on
,08-24 21:39:15.549  8128  8161 D bt_hci_bdroid: preload
08-24 21:39:15.551  8128  8205 D bt_userial_mct: userial_open(port:0)
08-24 21:39:15.551  8128  8205 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-24 21:39:15.555  8128  8205 I bt_vendor: Done intiailizing UART
08-24 21:39:15.556  8128  8205 I bt_vendor: Done intiailizing UART
08-24 21:39:15.556  8128  8205 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-24 21:39:15.556  8128  8205 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-24 21:39:15.556  8128  8226 D bt_userial_mct: Entering userial_read_thread()
08-24 21:39:15.556  8128  8203 I bt-btu  : btu_task received preload complete event
08-24 21:39:15.557  8128  8203 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-24 21:39:15.557  8128  8203 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-24 21:39:15.559  8128  8203 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_HCI
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_AVDT
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_AVRC
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_BTM
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 21:39:15.563  8128  8203 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 21:39:15.646  8128  8203 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
08-24 21:39:15.646  8128  8203 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa023d061 
,08-24 21:39:15.646  8128  8203 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa023d061 
,08-24 21:39:15.687  8128  8165 E bt-btif : Calling BTA_HhEnable
,08-24 21:39:15.691  8128  8165 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-24 21:39:15.692  8128  8165 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-24 21:39:15.695  8128  8203 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-24 21:39:15.695  8128  8203 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-24 21:39:15.695  8128  8203 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-24 21:39:15.697  8128  8203 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-24 21:39:15.697  8128  8203 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-24 21:39:15.697  8128  8165 D BluetoothAdapterProperties: Name is: G3
08-24 21:39:15.699  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 21:39:15.700  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-24 21:39:15.702  8128  8165 D BluetoothAdapterProperties: Scan Mode:20
08-24 21:39:15.703  8128  8165 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 21:39:15.703  8128  8165 D bt_hci_bdroid: postload
,08-24 21:39:15.709  8128  8205 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 21:39:15.710  8128  8165 D bte_conf: Device ID record 1 : primary
08-24 21:39:15.710  8128  8165 D bte_conf:   vendorId            = 00c4
08-24 21:39:15.710  8128  8165 D bte_conf:   vendorIdSource      = 0001
08-24 21:39:15.710  8128  8165 D bte_conf:   product             = 13a1
08-24 21:39:15.710  8128  8165 D bte_conf:   version             = 1000
08-24 21:39:15.710  8128  8165 D bte_conf:   clientExecutableURL = 
08-24 21:39:15.710  8128  8165 D bte_conf:   serviceDescription  = 
08-24 21:39:15.710  8128  8165 D bte_conf:   documentationURL    = 
08-24 21:39:15.710  8128  8165 D bte_conf: bte_load_did_conf no section named DID2.
08-24 21:39:15.711  8128  8203 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-24 21:39:15.711  8128  8205 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 21:39:15.714  8128  8161 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-24 21:39:15.714  8128  8161 D BluetoothAdapterProperties: ScanMode =  20
08-24 21:39:15.714  8128  8161 D BluetoothAdapterProperties: State =  11
08-24 21:39:15.715  8128  8161 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-24 21:39:15.715  8128  8161 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-24 21:39:15.716  8128  8161 D BluetoothAdapterProperties: Setting state to 12
08-24 21:39:15.716  8128  8161 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 21:39:15.716  8128  8165 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-24 21:39:15.716  8128  8165 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 21:39:15.714  8231  8231 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 21:39:15.714  8231  8231 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:39:15.727  1037  1112 D BluetoothManagerService: Message: 60
08-24 21:39:15.727  1037  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-24 21:39:15.727  1037  1112 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-24 21:39:15.727  8128  8161 I BluetoothAdapterState: Entering On State
08-24 21:39:15.737  8128  8205 D bt_hci_bdroid: Used up Tx Cmd credits
,08-24 21:39:15.745  8128  8161 D LGBluetoothServiceAdapter: [BTUI] OnState
08-24 21:39:15.745  8128  8161 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-24 21:39:15.745  8128  8161 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-24 21:39:15.747  8128  8161 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-24 21:39:15.748  8128  8203 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 21:39:15.748  8128  8203 W bt-smp  : Plain text(LSB ~ MSB) = 9e 81 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 21:39:15.748  8128  8203 W bt-smp  : Encrypted text(LSB ~ MSB) = ae f3 18 45 dd b7 53 a6 e3 c2 6c e9 2a c1 cf 90 
08-24 21:39:15.748  8128  8205 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 21:39:15.748  8128  8203 W bt-btm  : Stopping oneshot timer
08-24 21:39:15.751  8128  8226 E bt_mct  : hci lib postload completed
,08-24 21:39:15.757  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:39:15.757  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:15.757  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:15.757  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:39:15.757  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:15.757  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:39:15.757  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:39:15.757  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 21:39:15.766  8128  8165 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 21:39:15.766  8128  8165 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-24 21:39:15.776  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:39:15.777  8128  8161 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-24 21:39:15.779  8128  8203 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 21:39:15.779  8128  8203 W bt-smp  : Plain text(LSB ~ MSB) = 8d fd 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 21:39:15.779  8128  8203 W bt-smp  : Encrypted text(LSB ~ MSB) = ad b3 35 cc 66 f6 ba 19 20 c3 ac 1c ee 38 df ef 
,08-24 21:39:15.781  8128  8203 W bt-btm  : Stopping oneshot timer
08-24 21:39:15.785  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:39:15.785  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:15.785  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:15.785  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:39:15.785  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:15.785  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:39:15.785  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:39:15.785  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 21:39:15.791  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 21:39:15.799  8128  8203 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 21:39:15.799  8128  8203 W bt-smp  : Plain text(LSB ~ MSB) = 7b 3d 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 21:39:15.799  8128  8203 W bt-smp  : Encrypted text(LSB ~ MSB) = 3d 4a 69 5b e8 6a 5f 09 91 42 b2 69 c8 b5 06 04 
08-24 21:39:15.799  8128  8203 W bt-btm  : Stopping oneshot timer
08-24 21:39:15.833  8236  8236 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-24 21:39:15.842  7043  7352 D BluetoothPan: onBluetoothStateChange on: true
,08-24 21:39:15.842  7043  7352 D BluetoothPan: onBluetoothStateChange call bindService
08-24 21:39:15.848  7043  7043 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 21:39:15.848  7043  7043 D PanProfile: Bluetooth service connected
08-24 21:39:15.852  8128  8203 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 21:39:15.852  8128  8203 W bt-smp  : Plain text(LSB ~ MSB) = b0 30 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 21:39:15.852  8128  8203 W bt-smp  : Encrypted text(LSB ~ MSB) = 2b 37 01 db 4f f8 c3 a0 5f 84 0c 16 c7 38 01 74 
08-24 21:39:15.852  8128  8203 W bt-btm  : Stopping oneshot timer
,08-24 21:39:15.855  1850  3512 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 21:39:15.866  1850  1850 D BluetoothHeadset: Proxy object connected
08-24 21:39:15.868  8128  8203 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 21:39:15.868  8128  8203 W bt-smp  : Plain text(LSB ~ MSB) = 11 d1 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 21:39:15.868  8128  8203 W bt-smp  : Encrypted text(LSB ~ MSB) = a9 a4 10 1c 33 37 a1 26 c1 eb 79 c2 3b ce 80 2d 
08-24 21:39:15.868  8128  8203 W bt-btm  : Stopping oneshot timer
08-24 21:39:15.869  1850  2468 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 21:39:15.872  1850  1850 D BluetoothHeadset: Proxy object connected
,08-24 21:39:15.872  1037  1112 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 21:39:15.873  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 21:39:15.875  1037  1037 D BluetoothA2dp: Proxy object connected
08-24 21:39:15.877  1850  1850 D BluetoothHeadset: Proxy object connected
08-24 21:39:15.878  7043  7059 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 21:39:15.881  7043  7870 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 21:39:15.885  7043  7352 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 21:39:15.887  7043  7043 D BluetoothA2dp: Proxy object connected
08-24 21:39:15.887  7043  7043 D A2dpProfile: Bluetooth service connected
08-24 21:39:15.888  7043  7870 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 21:39:15.890  7043  7060 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 21:39:15.891  7043  7043 D BluetoothMap: Proxy object connected
08-24 21:39:15.891  7043  7043 D MapProfile: Bluetooth service connected
08-24 21:39:15.891  7043  7043 D BluetoothMap: getConnectedDevices()
08-24 21:39:15.894  8128  8145 V BluetoothMapService: getConnectedDevices()
,08-24 21:39:15.897  1037  1112 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 21:39:15.898  1037  1037 D BluetoothHeadset: Proxy object connected
08-24 21:39:15.898  1037  1112 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-24 21:39:15.898  1037  1112 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-24 21:39:15.899  7043  7043 D BluetoothInputDevice: Proxy object connected
08-24 21:39:15.899  7043  7043 D HidProfile: Bluetooth service connected
08-24 21:39:15.901  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 21:39:15.901  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:15.903  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:15.904  1940  2251 D LGBluetoothAPIService: Message: 1
08-24 21:39:15.904  1940  2251 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-24 21:39:15.904  1940  2251 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-24 21:39:15.904  1940  2251 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-24 21:39:15.907  7043  7043 D BluetoothHeadset: Proxy object connected
08-24 21:39:15.907  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:15.908  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-24 21:39:15.907  7043  7043 D HeadsetProfile: Bluetooth service connected
08-24 21:39:15.908  1037  1112 D BluetoothManagerService: Message: 40
08-24 21:39:15.908  1037  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-24 21:39:15.909  8128  8128 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:15.909  8128  8128 D BluetoothMapService: STATE_ON
08-24 21:39:15.914  7043  7043 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-24 21:39:15.916  7043  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 21:39:15.922  7043  7043 D DockEventReceiver: finishStartingService: stopping service
,08-24 21:39:15.924  8128  8128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b7abd96
08-24 21:39:15.925  8128  8128 V BluetoothPbapService: Pbap Service onCreate
,08-24 21:39:15.925  8128  8128 V BluetoothPbapService: Starting PBAP service
08-24 21:39:15.926  8128  8128 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-24 21:39:15.926  8128  8128 V BluetoothPbapService: Pbap Service onBind
08-24 21:39:15.927  8128  8128 V BluetoothMapService: Handler(): got msg=1
08-24 21:39:15.928  7043  7043 D BluetoothPbap: Proxy object connected
08-24 21:39:15.928  8128  8128 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-24 21:39:15.928  7043  7043 D PbapServerProfile: Bluetooth service connected
08-24 21:39:15.928  8128  8128 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:15.928  8128  8128 V BluetoothPbapService: state: 12
08-24 21:39:15.929  8128  8128 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 21:39:15.929  8128  8128 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:15.929  8128  8128 V BluetoothPbapReceiver: ***********state = 12
08-24 21:39:15.929  8128  8256 D BluetoothMapMasInstance: MAS initSocket()
08-24 21:39:15.930  8128  8128 V BluetoothPbapService: Handler(): got msg=1
08-24 21:39:15.930  8128  8256 D BluetoothMapMasInstance:   masId = 00
08-24 21:39:15.930  8128  8256 D BluetoothMapMasInstance:   msgTypes = 0e
08-24 21:39:15.930  8128  8256 D BluetoothMapMasInstance:   masName = SMS/MMS
08-24 21:39:15.930  8128  8256 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-24 21:39:15.930  8128  8128 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-24 21:39:15.932  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 21:39:15.932  1037  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:15.932  2196  2196 D c       : Getting all permits...
08-24 21:39:15.932  2196  2196 D a       : Opening database...
08-24 21:39:15.933  8128  8257 V BluetoothPbapService: Pbap Service initSocket
08-24 21:39:15.933  8128  8256 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 21:39:15.934  1037  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 21:39:15.936  8128  8257 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 21:39:15.936  2196  2196 D a       : Opening database auth.proximity.permit_store...
08-24 21:39:15.937  8128  8256 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-24 21:39:15.937  8128  8256 V BluetoothMapMasInstance: Succeed to create listening socket 
08-24 21:39:15.937  8128  8256 D BluetoothMapMasInstance: Accepting socket connection...
08-24 21:39:15.937  8128  8165 D BluetoothAdapterProperties: Scan Mode:21
08-24 21:39:15.938  8128  8165 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-24 21:39:15.940  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:15.941  2196  2196 D a       : Closing database...
08-24 21:39:15.942  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:15.943  8128  8257 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-24 21:39:15.943  8128  8257 V BluetoothPbapService: Succeed to create listening socket 
08-24 21:39:15.943  8128  8257 V BluetoothPbapService: Accepting socket connection...
08-24 21:39:15.951  7043  7043 D BluetoothPermissionRequest: onReceive
,08-24 21:39:15.954  7043  7043 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-24 21:39:15.956  7043  7043 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 21:39:15.959  8128  8128 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-24 21:39:15.960  8128  8128 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-24 21:39:15.965  8128  8128 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-24 21:39:15.990  8128  8128 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-24 21:39:15.991  8128  8128 V BtOppService: onCreate
08-24 21:39:15.995  8128  8128 V BluetoothOppNotification: send message
08-24 21:39:15.998  8128  8128 V BtOppService: Starting RfcommListener
08-24 21:39:16.001  8128  8128 D BluetoothOppPreference: Dumping Names:  
08-24 21:39:16.001  8128  8128 D BluetoothOppPreference: {}
08-24 21:39:16.001  8128  8128 D BluetoothOppPreference: Dumping Channels:  
,08-24 21:39:16.001  8128  8128 D BluetoothOppPreference: {}
08-24 21:39:16.002  8128  8128 V BtOppService: onStartCommand
,08-24 21:39:16.004  8128  8264 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 21:39:16.005  8128  8128 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:16.005  8128  8128 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-24 21:39:16.007  8128  8128 V BluetoothOppNotification: new notify threadi!
08-24 21:39:16.008  8128  8128 V BluetoothOppNotification: send delay message
08-24 21:39:16.009  8128  8261 V BtOppService: Deleted complete outbound shares, number =  0
08-24 21:39:16.009  8128  8128 V BtOppService: start RfcommListener
08-24 21:39:16.010  8128  8264 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 21:39:16.012  8128  8265 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-24 21:39:16.014  8128  8128 V BtOppService: RfcommListener started
,08-24 21:39:16.016  8128  8261 V BtOppService: Deleted complete inbound failed shares, number = 0
08-24 21:39:16.016  8128  8261 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-24 21:39:16.017  8128  8266 V BtOppRfcommListener: Starting RFCOMM listener....
08-24 21:39:16.018  1037  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:16.018  8128  8261 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18946232 on behalf of 
08-24 21:39:16.019  8128  8265 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11c53b83 on behalf of 
08-24 21:39:16.019  8128  8264 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@336e7100 on behalf of 
08-24 21:39:16.020  8128  8266 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 21:39:16.022  8128  8265 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-24 21:39:16.022  8128  8266 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-24 21:39:16.023  8128  8266 V BtOppRfcommListener: Started RFCOMM listener....
08-24 21:39:16.023  8128  8266 I BtOppRfcommListener: Accept thread started.
08-24 21:39:16.023  8128  8266 V BtOppRfcommListener: Accepting connection...
08-24 21:39:16.023  8128  8264 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-24 21:39:16.026  8128  8265 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-24 21:39:16.027  8128  8265 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32744d39 on behalf of 
,08-24 21:39:16.028  8128  8265 V BluetoothOppNotification: outbound: succ-0  fail-0
08-24 21:39:16.030  8128  8265 V BluetoothOppNotification: outbound notification was removed.
08-24 21:39:16.030  8128  8265 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-24 21:39:16.031  8128  8265 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e226f7e on behalf of 
08-24 21:39:16.032  8128  8265 V BluetoothOppNotification: inbound: succ-0  fail-0
08-24 21:39:16.034  8128  8265 V BluetoothOppNotification: inbound notification was removed.
08-24 21:39:16.034  8128  8265 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-24 21:39:16.035  8128  8265 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c160cdf on behalf of 
08-24 21:39:16.036  8128  8128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b7abd96
08-24 21:39:16.036  8128  8128 V BluetoothFtpService: Ftp Service onCreate
08-24 21:39:16.036  8128  8128 I BluetoothFtpService: Ftp Service onCreate
08-24 21:39:16.036  8128  8128 V BluetoothFtpService: Ftp Service onStartCommand
08-24 21:39:16.037  8128  8128 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:16.037  8128  8128 V BluetoothFtpService: Starting Listening on sockets
08-24 21:39:16.037  8128  8128 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 21:39:16.037  8128  8128 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 21:39:16.037  8128  8128 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 21:39:16.037  8128  8128 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-24 21:39:16.037  8128  8128 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-24 21:39:16.037  8128  8128 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-24 21:39:16.039  8128  8128 V BtOppService: ContentObserver received notification
08-24 21:39:16.040  8128  8128 V BtOppService: ContentObserver received notification
08-24 21:39:16.040  8128  8128 V BluetoothFtpService: Handler(): got msg=1
,08-24 21:39:16.040  8128  8128 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-24 21:39:16.040  8128  8128 V BluetoothFtpService: Ftp Service initSocket
08-24 21:39:16.043  1037  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:16.044  8128  8128 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 21:39:16.045  8128  8128 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-24 21:39:16.049  8128  8267 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 21:39:16.049  8128  8268 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-24 21:39:16.049  8128  8267 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 21:39:16.050  8128  8267 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2fc383f5 on behalf of 
08-24 21:39:16.051  8128  8267 V BluetoothOppNotification: update too frequent, put in queue
08-24 21:39:16.052  8128  8267 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-24 21:39:16.061  8128  8128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b7abd96
08-24 21:39:16.061  8128  8128 V BluetoothSapService: Sap Service onCreate
08-24 21:39:16.063  8128  8128 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 21:39:16.063  8128  8128 V BluetoothSapService: state: 12
08-24 21:39:16.063  8128  8128 V BluetoothSapService: Starting SAP server process
08-24 21:39:16.064  8128  8128 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-24 21:39:16.064  8269  8269 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 21:39:16.064  8269  8269 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:39:16.066  8128  8270 V BluetoothSapService: Sap Service initRfcommSocket
08-24 21:39:16.067  1037  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:16.069  8128  8270 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 21:39:16.070  8128  8270 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-24 21:39:16.070  8128  8270 V BluetoothSapService: Succeed to create listening socket 
08-24 21:39:16.070  8128  8270 V BluetoothSapService: Accepting socket connection...
08-24 21:39:16.080  8269  8269 V BT_SAP  : Event pipe created
08-24 21:39:16.080  8269  8269 V BT_SAP  : create_server_socket qcom.sap.server
08-24 21:39:16.080  8269  8269 V BT_SAP  : created socket fd 6
,08-24 21:39:17.010  8128  8128 V BluetoothOppNotification: new notify threadi!
,08-24 21:39:17.011  8128  8128 V BluetoothOppNotification: send delay message
,08-24 21:39:17.023  8128  8281 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-24 21:39:17.027  8128  8281 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e956a71 on behalf of 
,08-24 21:39:17.037  8128  8281 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-24 21:39:17.039  8128  8281 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-24 21:39:17.040  8128  8281 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1072f056 on behalf of 
08-24 21:39:17.041  8128  8281 V BluetoothOppNotification: outbound: succ-0  fail-0
08-24 21:39:17.042  8128  8281 V BluetoothOppNotification: outbound notification was removed.
08-24 21:39:17.042  8128  8281 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-24 21:39:17.043  8128  8281 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3eaeb8d7 on behalf of 
08-24 21:39:17.044  8128  8281 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-24 21:39:17.049  8128  8281 V BluetoothOppNotification: inbound notification was removed.
08-24 21:39:17.049  8128  8281 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-24 21:39:17.050  8128  8281 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a0065c4 on behalf of 
08-24 21:39:19.533  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:39:19.533  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:19.533  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:19.533  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 21:39:19.533  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:19.533  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:39:19.533  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:39:19.533  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 21:39:19.542  6886  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 21:39:19.542  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:19.542  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f918ec removed from the list
08-24 21:39:19.542  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:39:19.542  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:19.542  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:19.543  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 21:39:19.543  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a2fb4b5 added. We now have 4 listener(s)
08-24 21:39:19.544  6886  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 21:39:19.546  1037  1053 D WifiServiceImplEx: setWifiEnabled: false pid=6886, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 21:39:19.546  1037  1053 D WifiService: setWifiEnabled: false pid=6886, uid=10118
08-24 21:39:19.546  1037  1053 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 21:39:24.555  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 21:39:24.569  1037  1052 D WifiServiceImplEx: setWifiEnabled: true pid=6886, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 21:39:24.570  1037  1052 D WifiService: setWifiEnabled: true pid=6886, uid=10118
08-24 21:39:24.570  1037  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 21:39:24.588  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 21:39:24.588  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 21:39:24.588  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,08-24 21:39:24.592  1037  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-24 21:39:24.592  1037  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-24 21:39:24.595  1037  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-24 21:39:24.595  1037  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-24 21:39:24.595  1037  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-24 21:39:24.595  1037  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-24 21:39:24.595  1037  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-24 21:39:24.595  1037  1539 E WifiHW  : unknown target_country: EU , set to default
08-24 21:39:24.595  1037  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-24 21:39:24.595  1037  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-24 21:39:24.596  1037  1539 I WifiUtil: gEnableBmps=1
08-24 21:39:25.167   328   895 D SoftapController: Softap fwReload - Ok
,08-24 21:39:25.172  1037  1539 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (573ms)
08-24 21:39:25.177   328   895 D CommandListener: Setting iface cfg
08-24 21:39:25.177   328   895 D CommandListener: Trying to bring down wlan0
08-24 21:39:25.188  1037  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-24 21:39:25.196   328   895 D CommandListener: Clearing all IP addresses on wlan0
08-24 21:39:25.205  1037  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-24 21:39:25.204  8292  8292 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:39:25.224  8292  8292 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 21:39:25.237  1037  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 21:39:25.237  1037  1539 E WifiStateMachine: useWiFiOffloading() : false
08-24 21:39:25.237  1037  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 21:39:25.240  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-24 21:39:25.258  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 21:39:25.266  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-24 21:39:25.276  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 21:39:25.279  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:25.280  1037  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-24 21:39:25.280  1037  1539 D WifiMonitor: connecting to supplicant
08-24 21:39:25.288  8292  8292 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-24 21:39:25.315  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 21:39:25.315  7043  7043 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-24 21:39:25.315  7043  7043 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 21:39:25.315  7043  7043 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 21:39:25.316  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 21:39:25.318  7043  7043 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 21:39:25.318  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-24 21:39:25.318  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 21:39:25.318  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 21:39:25.318  7043  7043 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 21:39:25.318  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-24 21:39:25.319  7043  7043 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-24 21:39:25.353  8292  8292 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-24 21:39:25.353  8292  8292 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-24 21:39:25.382  1037  1995 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8310 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-24 21:39:25.387  1037  1112 D Tethering: InitialState.processMessage what=4
08-24 21:39:25.387  1037  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-24 21:39:25.488  1037  1921 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8331 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-24 21:39:25.492  8310  8329 W FormManager: Network not available. Please check & try again.
,08-24 21:39:25.496  8292  8292 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-24 21:39:25.503  8310  8330 V FormManager: Network unavailable.
,08-24 21:39:25.505  8310  8330 V FormManager: Network unavailable.
,08-24 21:39:25.516  1037  1958 I ActivityManager: Killing 7353:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-24 21:39:25.522  8331  8331 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 21:39:25.558  8292  8292 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-24 21:39:25.562  8292  8292 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-24 21:39:25.564  1037  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-24 21:39:25.565  1037  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-24 21:39:25.565  1037  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-24 21:39:25.566  1037  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-24 21:39:25.566  1037  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:39:25.566  1037  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:39:25.567  1037  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:39:25.567  1037  8352 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-24 21:39:25.567  1037  8352 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-24 21:39:25.567  1037  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:39:25.567  1037  8352 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-24 21:39:25.567  1037  8352 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-24 21:39:25.567  1037  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-24 21:39:25.567  1037  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-24 21:39:25.569  1037  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-24 21:39:25.569  1037  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-24 21:39:25.569  1037  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-24 21:39:25.579  1037  1884 W libprocessgroup: failed to open /acct/uid_10062/pid_7353/cgroup.procs: No such file or directory
,08-24 21:39:25.584  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 21:39:25.584  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:25.585  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:25.585  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:25.585  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 21:39:25.588  1037  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 21:39:25.588  1037  1539 E WifiStateMachine: useWiFiOffloading() : false
08-24 21:39:25.588  1037  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 21:39:25.590  1037  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-24 21:39:25.591  1037  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-24 21:39:25.591  1037  1539 D WifiConfigStore: Loading config and enabling all networks 
08-24 21:39:25.591  1037  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-24 21:39:25.591  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 21:39:25.592  1037  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-24 21:39:25.601  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:39:25.601  1037  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-24 21:39:25.605  1940  1940 D WfdService: Waiting for WifiP2p enabling
08-24 21:39:25.606  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:39:25.609  1037  2013 I ActivityManager: Killing 7370:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-24 21:39:25.609  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:39:25.609  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:25.609  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:25.609  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:39:25.609  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:25.609  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:39:25.609  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:39:25.609  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 21:39:25.613  1037  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-24 21:39:25.613  1037  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-24 21:39:25.618  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 21:39:25.621  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:39:25.621  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:25.621  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:25.621  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:39:25.621  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:25.621  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 21:39:25.621  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 21:39:25.621  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 21:39:25.623  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 21:39:25.722  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-24 21:39:25.723  1037  1539 D WifiStateMachine: enableVerboseLogging : level 2
08-24 21:39:25.723  1037  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-24 21:39:25.724  1037  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-24 21:39:25.725  1037  1623 W libprocessgroup: failed to open /acct/uid_10085/pid_7370/cgroup.procs: No such file or directory
08-24 21:39:25.725  1037  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-24 21:39:25.725  1037  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-24 21:39:25.727  1037  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-24 21:39:25.727  1037  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-24 21:39:25.728  1037  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-24 21:39:25.729  1037  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,08-24 21:39:25.730  1037  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-24 21:39:25.730  1037  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-24 21:39:25.731  1037  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-24 21:39:25.731  1037  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-24 21:39:25.732  1037  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-24 21:39:25.733  1037  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-24 21:39:25.734  1037  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-24 21:39:25.741  1940  1940 D WfdsService: Supplicant Connection state is changed : true
08-24 21:39:25.741  1037  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 21:39:25.741  1940  2383 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-24 21:39:25.741  1940  2383 D WfdsService: Set the WFDS Monitor: true
08-24 21:39:25.741  1037  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-24 21:39:25.741  1940  2383 D WfdsMonitor: WfdsMonitorThread create
08-24 21:39:25.742  1940  2383 D WfdsMonitor: WFDS Monitor is created and started
08-24 21:39:25.742  1940  2383 D WfdsService: WiFi: Supplicant connection re-established
08-24 21:39:25.743  7904  7904 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 21:39:25.744  1940  8353 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-24 21:39:25.745  1940  8353 E CtrlSupplicant: Succeed to open control connection
08-24 21:39:25.746  1940  8353 E CtrlSupplicant: Succeed to open monitor connection
08-24 21:39:25.747  1037  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-24 21:39:25.747  1037  1539 D WifiNative-HAL: Setting external_sim to 1
08-24 21:39:25.747  1037  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-24 21:39:25.748  1940  8353 D WfdsMonitor: Supplicant connection established
08-24 21:39:25.748  1940  2383 D WfdsService: Connected to the supplicant for wfds
08-24 21:39:25.749  1037  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-24 21:39:25.749  1037  1539 I WifiNative-HAL: startHal
08-24 21:39:25.749  1037  1539 D wifi    : setting scan oui 0xaf614100
08-24 21:39:25.750  1037  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 21:39:25.750  1037  1539 I WifiNative-HAL: startHal
08-24 21:39:25.750  1037  1539 D wifi    : setting scan oui 0xaf614100
08-24 21:39:25.751  1037  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-24 21:39:25.752  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 21:39:25.752  7043  7043 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 21:39:25.752  7043  7043 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 21:39:25.752  7043  7043 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 21:39:25.753  1037  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-24 21:39:25.753  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-24 21:39:25.753  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 21:39:25.753  8292  8292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-24 21:39:25.754  7043  7043 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 21:39:25.754  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-24 21:39:25.754  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,08-24 21:39:25.754  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 21:39:25.754  7043  7043 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 21:39:25.754  1037  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-24 21:39:25.754  7043  7043 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-24 21:39:25.754  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-24 21:39:25.755  8292  8292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 21:39:25.755  1037  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 21:39:25.755  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-24 21:39:25.756  8292  8292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-24 21:39:25.756  1037  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-24 21:39:25.756  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 21:39:25.757  8292  8292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-24 21:39:25.758  1037  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-24 21:39:25.758  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-24 21:39:25.758  8292  8292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 21:39:25.759  1037  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 21:39:25.759  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-24 21:39:25.759  8292  8292 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-24 21:39:25.760  1037  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-24 21:39:25.760  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 21:39:25.761  8292  8292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-24 21:39:25.762  1037  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-24 21:39:25.764  1037  1539 E WifiNative: : [382,552,522 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-24 21:39:25.764  1037  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-24 21:39:25.766  1037  1539 D WifiNative-wlan0: RECONNECT: returned true
08-24 21:39:25.766  1037  1539 D WifiNative-wlan0: doString: [STATUS]
08-24 21:39:25.767  1037  8352 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-24 21:39:25.767  1037  8352 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-24 21:39:25.767  1037  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-24 21:39:25.768  1037  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 21:39:25.768  8331  8331 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 21:39:25.768  1037  1539 D WifiNative-wlan0: SET ps 1: returned true
08-24 21:39:25.769  1037  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.771   328   895 D CommandListener: Setting iface cfg
08-24 21:39:25.771   328   895 D CommandListener: Trying to bring up p2p0
08-24 21:39:25.771  1037  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-24 21:39:25.771  1037  1538 D LGWifiP2pService: P2pEnablingState
08-24 21:39:25.771  1037  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.771  1037  1538 D LGWifiP2pService: P2p socket connection successful
08-24 21:39:25.771  1037  1538 D LGWifiP2pService: P2pEnabledState
08-24 21:39:25.774  1037  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-24 21:39:25.774  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
08-24 21:39:25.774  1037  1037 D RttService: SCAN_AVAILABLE : 3
08-24 21:39:25.774  1037  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.774  1037  1557 I WifiNative-HAL: startHal
08-24 21:39:25.775  1037  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf614100
08-24 21:39:25.775  1037  1557 D wifi    : failed to get capabilities : -3
08-24 21:39:25.775  1037  1557 E WifiScanningService: could not get scan capabilities
08-24 21:39:25.775  1037  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.775  1037  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-24 21:39:25.776  1037  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-24 21:39:25.776  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-24 21:39:25.776  1940  1940 D WfdsService: WifiP2pState is changed : true
,08-24 21:39:25.776  1037  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-24 21:39:25.777  1940  2383 D WfdsService: Receive the WFDS_ENABLE Method
08-24 21:39:25.777  1037  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-24 21:39:25.777  1940  2383 D WfdsService: Set the WFDS Monitor: true
08-24 21:39:25.777  1940  2383 D WfdsService: Connected to the supplicant for wfds
08-24 21:39:25.777  1940  2383 D WfdsJNI : doCommand: WFDS_SET TRUE
08-24 21:39:25.777  1037  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-24 21:39:25.777  1037  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-24 21:39:25.778  1037  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-24 21:39:25.778  8292  8292 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-24 21:39:25.778  1940  2383 D WfdsService: selectPreferredScanChannel [36]
08-24 21:39:25.778  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-24 21:39:25.778  1940  2383 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-24 21:39:25.779  1037  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-24 21:39:25.779  1037  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-24 21:39:25.779  1037  1538 D LGWifiP2pService: before postfix = G3
08-24 21:39:25.779  1037  1538 D WifiServerServiceExt: postfix byte check : 2
08-24 21:39:25.779  1037  1538 D LGWifiP2pService: after postfix = G3
08-24 21:39:25.779  1037  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-24 21:39:25.779  1940  1940 D WfdsService: isConnected: false
08-24 21:39:25.779  1037  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-24 21:39:25.779  1037  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-24 21:39:25.780  1037  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-24 21:39:25.780  1037  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-24 21:39:25.780  1037  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-24 21:39:25.780  1037  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-24 21:39:25.781  1037  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-24 21:39:25.781  1037  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-24 21:39:25.781  1037  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-24 21:39:25.781  1037  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-24 21:39:25.781  1037  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-24 21:39:25.781  1037  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-24 21:39:25.781  1037  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-24 21:39:25.782  1037  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-24 21:39:25.782  1037  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-24 21:39:25.782  1037  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
,08-24 21:39:25.782  1037  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-24 21:39:25.782  8292  8292 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-24 21:39:25.782  1037  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-24 21:39:25.782  1037  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-24 21:39:25.783  1037  1538 D WifiNative-p2p0:    returned OK
08-24 21:39:25.783  1037  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-24 21:39:25.783  1940  1940 I WfdStateTracker: handleP2pThisDeviceChanged
08-24 21:39:25.783  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-24 21:39:25.783  1940  1940 D WfdsService: Update P2p Interface State: 3
08-24 21:39:25.784  1037  1538 D WifiNative-p2p0: SAVE_CONFIG: returned false
08-24 21:39:25.784  1037  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-24 21:39:25.784  1037  1538 D LGWifiP2pService: InactiveState
08-24 21:39:25.784  1037  1538 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.784  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.784  1037  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-24 21:39:25.785  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 21:39:25.787  8310  8355 W FormManager: Network not available. Please check & try again.
08-24 21:39:25.790  8310  8356 V FormManager: Network unavailable.
,08-24 21:39:25.793  8310  8356 V FormManager: Network unavailable.
08-24 21:39:25.796  8292  8292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-24 21:39:25.796  1037  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-24 21:39:25.796  1037  1538 D LGWifiP2pService: InactiveState{ when=-12ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.796  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.796  8292  8292 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:39:25.797  1940  8353 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 21:39:25.797  1037  8352 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 21:39:25.797  1037  8352 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:39:25.797  1037  8352 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:39:25.797  1037  8352 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:39:25.797  8292  8292 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-24 21:39:25.797  8292  8292 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.798  1940  8353 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:39:25.798  1037  1538 D LGWifiP2pService: DefaultState{ when=-12ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.798  1037  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-24 21:39:25.798  1037  1538 D LGWifiP2pService: InactiveState{ when=-14ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.798  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.798  1037  1538 D LGWifiP2pService: DefaultState{ when=-14ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.798  1037  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
,08-24 21:39:25.798  1037  1538 D LGWifiP2pService: InactiveState{ when=-14ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.798  8292  8292 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.798  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.798  1037  1538 D LGWifiP2pService: DefaultState{ when=-14ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.798  1037  1538 D LGWifiP2pService: InactiveState{ when=-14ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.798  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.799  1037  1538 D LGWifiP2pService: DefaultState{ when=-15ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.799  1037  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-24 21:39:25.799  1940  2383 W WfdsService: DefaultState - msg [9441285] is not handled
08-24 21:39:25.799  1037  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-24 21:39:25.799  1037  1037 E WifiServerServiceExt: No p2p device connected
08-24 21:39:25.799  8292  8292 E wpa_supplicant: disconnect_rssi_lvl: -100
08-24 21:39:25.799  1037  8352 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:39:25.799  1037  8352 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.799  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:39:25.799  1037  8352 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.799  1037  8352 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.799  1037  8352 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:39:25.799  1037  8352 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.799  1037  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-24 21:39:25.800  1037  8352 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.800  1037  8352 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.800  1940  8353 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:39:25.800  1037  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-24 21:39:25.801  1037  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-24 21:39:25.801  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-24 21:39:25.801  8292  8292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-24 21:39:25.802  8292  8292 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:39:25.802  1037  8352 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 21:39:25.802  8292  8292 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-24 21:39:25.802  1037  8352 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:39:25.802  8292  8292 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.802  1037  8352 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:39:25.802  1037  8352 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 21:39:25.803  1037  8352 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:39:25.803  1037  8352 E WifiMonitor: WifiMonitor:p2p0 cnt=50 ,dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.803  1037  8352 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.803  1037  8352 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.803  1037  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-24 21:39:25.803  8292  8292 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.803  1037  1538 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.803  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:25.804  1037  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-24 21:39:25.804  1940  8353 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:39:25.804  1940  8353 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:39:25.804  1037  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-24 21:39:25.804  1037  8352 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 21:39:25.804  1037  8352 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.804  1037  8352 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.804  1037  8352 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 21:39:25.804  1037  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-24 21:39:25.804  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-24 21:39:25.805  8292  8292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-24 21:39:25.805  8292  8292 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 21:39:25.805  1037  8352 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-24 21:39:25.806  1037  8352 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN,
08-24 21:39:25.806  1037  8352 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 21:39:25.806  1037  8352 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 21:39:25.806  1037  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-24 21:39:25.806  1037  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-24 21:39:25.806  1037  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-24 21:39:25.806  1037  1539 D WifiNative-wlan0: doBoolean: SCAN
08-24 21:39:25.807  1037  1539 D WifiNative-wlan0: SCAN: returned false
08-24 21:39:25.808  1037  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=382597  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 21:39:25.810  1037  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=382599  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-24 21:39:25.810  1037  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 21:39:25.810  1037  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-24 21:39:25.811  1037  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 21:39:25.811  1037  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 21:39:25.812  1037  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 21:39:25.812  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:39:25.812  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:39:25.813  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:25.813  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:25.813  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-24 21:39:25.814  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:39:25.816  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:39:25.816  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-24 21:39:25.819  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 21:39:25.819  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 21:39:25.821  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 21:39:25.823  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 21:39:25.828  4325  8357 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 21:39:25.830  4325  8358 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 21:39:25.830  4325  8358 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 21:39:25.865  1037  1576 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8359 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-24 21:39:25.944  8359  8359 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-24 21:39:25.944  8359  8359 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-24 21:39:25.952  8359  8359 V [BNRBootReceiver]: Boot Receiver Return
08-24 21:39:25.953  8359  8359 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 21:39:26.030  1037  2013 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8377 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-24 21:39:26.032  1037  2013 I ActivityManager: Killing 7389:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-24 21:39:26.140  1037  1053 W libprocessgroup: failed to open /acct/uid_10093/pid_7389/cgroup.procs: No such file or directory
,08-24 21:39:26.184  1037  8352 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-24 21:39:26.185  1037  8352 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-24 21:39:26.185  1037  8352 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-24 21:39:26.185  8292  8292 E wpa_supplicant: USIM:  scard_init function
08-24 21:39:26.185  1037  8352 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-24 21:39:26.185  1037  8352 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-24 21:39:26.186  8292  8292 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-24 21:39:26.188  1037  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 21:39:26.190  1037  8352 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-24 21:39:26.190  1037  8352 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-24 21:39:26.193  1037  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 21:39:26.195  1037  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 21:39:26.196  1037  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 21:39:26.196  1037  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-24 21:39:26.201  8377  8377 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-24 21:39:26.211  1037  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=383000  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-24 21:39:26.215  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.215  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.215  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-24 21:39:26.215  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-24 21:39:26.215  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:39:26.217  1037  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=383007  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-24 21:39:26.217  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:39:26.224  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 21:39:26.225  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.225  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-24 21:39:26.225  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:39:26.225  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-24 21:39:26.239  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:39:26.239  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:39:26.240  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 21:39:26.245  8377  8377 D PluginManager: init()
08-24 21:39:26.309  8292  8292 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-24 21:39:26.310  1037  8352 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-24 21:39:26.310  1037  8352 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-24 21:39:26.311  1037  8352 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-24 21:39:26.311  1037  8352 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-24 21:39:26.311  1037  8352 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 21:39:26.311  1037  8352 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-24 21:39:26.312  1037  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=383102  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-24 21:39:26.313  1037  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-24 21:39:26.317  1037  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=383107  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-24 21:39:26.319  1037  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=383109
08-24 21:39:26.320  1037  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=383110
08-24 21:39:26.321  1037  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=383111
08-24 21:39:26.322  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=383112
08-24 21:39:26.324  1037  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=383114
08-24 21:39:26.325  1037  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=383115  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-24 21:39:26.326  8292  8292 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 21:39:26.326  1037  8352 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 21:39:26.326  8292  8292 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 21:39:26.326  1037  8352 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 21:39:26.327  1037  8352 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-24 21:39:26.327  1037  8352 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 21:39:26.327  1037  8352 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 21:39:26.327  1037  8352 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-24 21:39:26.327  1037  8352 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 21:39:26.327  1037  8352 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 21:39:26.328  1037  8352 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 21:39:26.328  1037  8352 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 21:39:26.329  1037  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=383118  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-24 21:39:26.329  1037  1539 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:39:26.330  1037  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:39:26.330  1037  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-24 21:39:26.330  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:39:26.331  1037  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 21:39:26.333  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:39:26.333  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:39:26.334  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:39:26.337  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.337  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.338  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-24 21:39:26.341  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.341  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.341  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-24 21:39:26.342  1037  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=383131  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-24 21:39:26.342  1037  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=383132  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-24 21:39:26.343  1037  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=383133
08-24 21:39:26.343  1037  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=383133
,08-24 21:39:26.344  1037  1539 D WifiNative-wlan0: doString: [STATUS]
08-24 21:39:26.344  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:39:26.344  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-24 21:39:26.344  1037  8352 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 21:39:26.344  1037  8352 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-24 21:39:26.344  1037  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-24 21:39:26.346  1037  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-24 21:39:26.352  1037  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-24 21:39:26.352  1037  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-24 21:39:26.358  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.358  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.358  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-24 21:39:26.360  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:39:26.360  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:39:26.361  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:39:26.362  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.362  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.362  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-24 21:39:26.363  1037  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1c43d604 type 2 when 377578 com.google.android.gms} when 377578
08-24 21:39:26.363  1037  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-24 21:39:26.364  1037  1546 D ConnectivityService: Got NetworkAgent Messenger
08-24 21:39:26.364  1037  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 21:39:26.364  1037  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 21:39:26.364  1037  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-24 21:39:26.364  1037  1546 D ConnectivityService: NetworkAgent connected
08-24 21:39:26.364  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:39:26.364  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:39:26.364  1037  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 21:39:26.364  1037  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 21:39:26.365  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:39:26.366  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:39:26.366  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:39:26.367  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 21:39:26.370  1037  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 21:39:26.370  1037  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 21:39:26.370  1037  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 21:39:26.371  1037  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 21:39:26.371  1037  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 21:39:26.374  1037  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 21:39:26.375   328   895 D CommandListener: Setting iface cfg
08-24 21:39:26.380  1037  1539 E WifiStateMachine: Start Dhcp Watchdog 3
08-24 21:39:26.380  1037  8395 D DhcpStateMachine: StoppedState
08-24 21:39:26.380  1037  8395 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:26.380  1037  8395 D DhcpStateMachine: WaitBeforeStartState
08-24 21:39:26.380  1037  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=383170  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 21:39:26.381  1037  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=383171  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 21:39:26.381  1037  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=383171  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 21:39:26.382  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:39:26.382  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-24 21:39:26.384  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:39:26.384  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-24 21:39:26.384  1037  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=383174  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 21:39:26.385  1037  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=383175  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 21:39:26.385  1037  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=383175  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 21:39:26.387  1037  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:29311] from screen [on:0 period:-1106216142] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-24 21:39:26.387  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1106216141] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-24 21:39:26.387  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-24 21:39:26.391  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:39:26.392  1037  1546 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-24 21:39:26.392  1037  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:39:26.393  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:39:26.393  1037  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:39:26.394  1037  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-24 21:39:26.394  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:39:26.394  1037  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:39:26.395  1037  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-24 21:39:26.395  1037  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=217,0,0
08-24 21:39:26.396  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=217,0,0
08-24 21:39:26.396  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-24 21:39:26.396  8292  8292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-24 21:39:26.396  1037  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-24 21:39:26.396  1037  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-24 21:39:26.397  1037  1539 D WifiNative-wlan0: SET ps 0: returned true
08-24 21:39:26.397  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-24 21:39:26.397  8292  8292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-24 21:39:26.397  1037  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-24 21:39:26.397  1037  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@125027ff target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:26.397  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@125027ff target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:26.398  1037  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-24 21:39:26.398  1037  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 21:39:26.398  1037  8395 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:26.398  1037  8395 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-24 21:39:26.398  1037  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-24 21:39:26.398   328   895 D CommandListener: Setting iface cfg
08-24 21:39:26.399   328   895 D CommandListener: Trying to bring up wlan0
08-24 21:39:26.399  1037  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-24 21:39:26.400  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:39:26.400  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-24 21:39:26.401  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 21:39:26.401  1037  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:39:26.401  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-24 21:39:26.401  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:39:26.402  1037  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:39:26.402  1037  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:39:26.403  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:39:26.403  1037  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 21:39:26.404  1037  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-24 21:39:26.404  1037  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-24 21:39:26.405  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-24 21:39:26.405  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 21:39:26.405  1037  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=,com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:26.405  1037  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:26.405  8292  8292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-24 21:39:26.406  1037  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 21:39:26.406  1037  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-24 21:39:26.407  8292  8292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,08-24 21:39:26.407  1037  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-24 21:39:26.407  1037  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 21:39:26.424  1037  1539 D WifiNative-wlan0: SET ps 1: returned true
08-24 21:39:26.424  1037  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-24 21:39:26.425  1037  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-24 21:39:26.426  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-24 21:39:26.426  1037  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-24 21:39:26.427  1037  1546 D ConnectivityService: ignoring duplicate network state non-change
08-24 21:39:26.431  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:39:26.431  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:39:26.432  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:39:26.434  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.434  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.434  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-24 21:39:26.435  1037  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-24 21:39:26.436  1037  1546 D ConnectivityService: Adding iface wlan0 to network 102
,08-24 21:39:26.443  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.443  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.443  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-24 21:39:26.446  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-24 21:39:26.448  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-24 21:39:26.449  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.449  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.449  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-24 21:39:26.451  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-24 21:39:26.452  1037  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-24 21:39:26.457  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:26.457  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 21:39:26.457  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-24 21:39:26.464  1037  1546 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-24 21:39:26.464  1037  1546 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-24 21:39:26.464  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:39:26.464  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 21:39:26.465  1037  1546 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-24 21:39:26.465  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:39:26.466   328   895 E Netd    : netlink response contains error (File exists)
08-24 21:39:26.466  1037  1546 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-24 21:39:26.467  1037  1546 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-24 21:39:26.467  1037  1546 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-24 21:39:26.467  1037  1546 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-24 21:39:26.468  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:39:26.468  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 21:39:26.468  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:39:26.470  1037  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-24 21:39:26.470  1037  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-24 21:39:26.470  1037  1546 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-24 21:39:26.470  1037  8394 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:26.470  1037  8394 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-24 21:39:26.470  1037  8394 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:26.470  1037  8394 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-24 21:39:26.472  1037  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-24 21:39:26.472  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 21:39:26.472  1037  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 21:39:26.472  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 21:39:26.472  1037  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:39:26.472  1037  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 21:39:26.473  1037  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:39:26.473  1037  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-24 21:39:26.473  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:39:26.473  1037  1546 D ConnectivityService: currentScore = 0, newScore = 20
08-24 21:39:26.473  1037  1546 D ConnectivityService:    accepting network in place of null
08-24 21:39:26.473  1037  1546 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 21:39:26.476   328  8399 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-24 21:39:26.476  1037  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:39:26.476  1037  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 21:39:26.477  1037  1546 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-24 21:39:26.477  1037  1546 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-24 21:39:26.477  1037  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 21:39:26.478  1037  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 21:39:26.478  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-24 21:39:26.479  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 21:39:26.479  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 21:39:26.479  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 21:39:26.480  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:39:26.480  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 21:39:26.482  1037  1546 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-24 21:39:26.483  1037  1546 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-24 21:39:26.483  1037  1546 D ConnectivityService: validation of new default Network = false
08-24 21:39:26.484  1037  1546 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-24 21:39:26.484  1037  1546 D DSQN    : enableDataServiceNotify 
08-24 21:39:26.484  1037  1546 D DSQN    : start dsqn bin
,08-24 21:39:26.492  1037  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-24 21:39:26.492  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:39:26.492  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:39:26.492  1037  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:39:26.493  1604  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 21:39:26.484  8400  8400 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:39:26.484  8400  8400 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:39:26.498  1037  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-24 21:39:26.506  8400  8400 E DSQN    : DSQN ssw
,08-24 21:39:26.509  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 21:39:26.510  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:39:26.510  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:39:26.534   328  8399 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-24 21:39:26.551  8377  8377 W ExternalStrings: load override strings
08-24 21:39:26.551  8377  8377 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 21:39:26.551  8377  8377 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-24 21:39:26.552  8377  8377 D StatusProvider: onCreate
08-24 21:39:26.580   328  8399 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-24 21:39:26.588  8377  8377 V Signer  : override build config not found
08-24 21:39:26.589  8377  8377 D Signer  : value of property debug is false
08-24 21:39:26.600  1037  8395 D DhcpStateMachine: DHCPV4 request on wlan0
,08-24 21:39:26.604  1037  8395 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-24 21:39:26.604  1037  8395 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-24 21:39:26.604  8404  8404 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:39:26.612  8377  8377 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-24 21:39:26.612  8377  8377 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-24 21:39:26.612  8377  8377 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-24 21:39:26.604  8404  8404 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 21:39:26.613  8377  8377 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-24 21:39:26.613  8377  8377 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-24 21:39:26.613  8377  8377 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-24 21:39:26.613  8377  8377 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-24 21:39:26.613  8377  8377 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-24 21:39:26.613  8377  8377 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-24 21:39:26.614  8377  8377 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-24 21:39:26.614  8377  8377 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-24 21:39:26.614  8377  8377 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-24 21:39:26.614  8377  8377 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-24 21:39:26.618   328   894 D LGDataListener: argv[0]=dsqncommand
,08-24 21:39:26.618   328   894 D LGDataListener: argv[1]=wlan0
,08-24 21:39:26.618   328   894 D LGDataListener: argv[2]=1
08-24 21:39:26.618   328   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-24 21:39:26.619  1037  1110 D DSQN    : DSQM DsqnNotification wlan0  1
08-24 21:39:26.619  1037  1110 D DSQN    : start to monitor internet connection
08-24 21:39:26.622  8377  8377 V LGMDMManager: Create singleton instance
,08-24 21:39:26.636  8404  8404 I dhcpcd  : version 5.5.6 starting
,08-24 21:39:26.641  8404  8404 E dhcpcd  : get_duid: m
08-24 21:39:26.641  8404  8404 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-24 21:39:26.641  8404  8404 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-24 21:39:26.658  8377  8377 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-24 21:39:26.658  1037  8394 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 19:39:26 GMT], X-Android-Received-Millis=[1472067566657], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472067566617]}
08-24 21:39:26.658  1037  8394 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-24 21:39:26.658  1037  8394 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-24 21:39:26.659  1037  1546 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-24 21:39:26.659  1037  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-24 21:39:26.659  1037  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 21:39:26.659  1037  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:39:26.659  1037  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 21:39:26.660  1037  1546 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-24 21:39:26.660  1037  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-24 21:39:26.660  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:39:26.660  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-24 21:39:26.661  1037  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:39:26.662  1604  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 21:39:26.664  1037  1546 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:39:26.665  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:39:26.666  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 21:39:26.667  1037  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:39:26.667  1037  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 21:39:26.667  1037  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-24 21:39:26.685  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 21:39:26.686  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:39:26.686  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 21:39:26.729  8404  8404 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-24 21:39:26.729  8404  8404 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-24 21:39:26.729  8404  8404 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-24 21:39:26.729  8404  8404 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-24 21:39:26.729  8404  8404 D dhcpcd  : wlan0: sending REQUEST (xid 0xb6535971), next in 4.26 seconds
08-24 21:39:26.739  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:39:26.739  8377  8415 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 21:39:26.754  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:39:26.755  8404  8404 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-24 21:39:26.760  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:39:26.766  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 21:39:26.767  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:39:26.768  7096  7096 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 21:39:26.775  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-24 21:39:26.776  8404  8404 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-24 21:39:26.776  8404  8404 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-24 21:39:26.776  8404  8404 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-24 21:39:26.776  8404  8404 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-24 21:39:26.776  8404  8404 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-24 21:39:26.777  8404  8404 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-24 21:39:26.777  8404  8404 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-24 21:39:26.777  8404  8404 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-24 21:39:26.778  7043  7043 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-24 21:39:26.781  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:39:26.781  8377  8415 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-24 21:39:26.789  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:39:26.797  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:39:26.805  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:39:26.805  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 21:39:26.807  7096  7096 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 21:39:26.895  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 21:39:26.896  8377  8414 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-24 21:39:26.902  8377  8415 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 21:39:26.909  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:39:26.921  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 21:39:26.926  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:39:26.927  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:39:26.927  7096  7096 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 21:39:26.931  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 21:39:26.931  7043  7043 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 21:39:26.931  7043  7043 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 21:39:26.931  7043  7043 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 21:39:26.931  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 21:39:26.932  7043  7043 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 21:39:26.933  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-24 21:39:26.933  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 21:39:26.933  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 21:39:26.933  7043  7043 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 21:39:26.933  7043  7043 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-24 21:39:26.933  7043  7043 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-24 21:39:26.935  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:39:26.936  8377  8415 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-24 21:39:26.942  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 21:39:26.945  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:39:26.953  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 21:39:26.953  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:39:26.955  7096  7096 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 21:39:26.959  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:39:26.959  8377  8415 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 21:39:26.966  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:39:26.970  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:39:26.976  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:39:26.976  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:39:26.977  7096  7096 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 21:39:26.980  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 21:39:26.980  8377  8415 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 21:39:26.987  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 21:39:26.990  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:39:26.997  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:39:26.998  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:39:26.998  7096  7096 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-24 21:39:27.000  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:39:27.001  8377  8415 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 21:39:27.006  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 21:39:27.010  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 21:39:27.012  1037  8395 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-24 21:39:27.012  1037  8395 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-24 21:39:27.012  1037  8395 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-24 21:39:27.013  1037  8395 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-24 21:39:27.013  1037  8395 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-24 21:39:27.013  1037  8395 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 21:39:27.013  1037  8395 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-24 21:39:27.013  1037  8395 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-24 21:39:27.013  1037  8395 D DhcpStateMachine: RunningState
08-24 21:39:27.014  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:39:27.014  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:39:27.015  7096  7096 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 21:39:27.017  1037  1576 I ActivityManager: Killing 7589:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-24 21:39:27.028   328  8444 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-24 21:39:27.028   328  8444 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-24 21:39:27.053  1037  1922 W libprocessgroup: failed to open /acct/uid_10005/pid_7589/cgroup.procs: No such file or directory
,08-24 21:39:27.057  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:39:27.058  8377  8415 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 21:39:27.067   328  8444 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-24 21:39:27.067  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:39:27.074  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:39:27.082  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:39:27.082  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 21:39:27.083  7096  7096 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 21:39:27.086  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:39:27.086  8377  8415 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 21:39:27.093  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:39:27.098  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:39:27.108  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 21:39:27.110  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:39:27.115  7096  7096 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 21:39:27.127  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 21:39:27.130  8377  8415 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 21:39:27.131  8331  8331 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-24 21:39:27.135  8331  8331 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-24 21:39:27.139  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 21:39:27.144  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 21:39:27.150  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 21:39:27.151  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:39:27.152  7096  7096 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-24 21:39:27.152  7096  7096 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-24 21:39:27.153  7096  7096 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-24 21:39:27.158  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 21:39:27.158  8377  8415 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 21:39:27.160  8377  8414 D LgDataFeature: LgDataFeature() Constructor: none
08-24 21:39:27.161  8377  8414 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 21:39:27.162  8331  8331 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-24 21:39:27.163  8331  8331 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 21:39:27.167  7043  7043 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 21:39:27.174  7043  7043 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 21:39:27.182  7096  7096 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 21:39:27.182  7096  7096 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 21:39:27.183  7096  7096 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-24 21:39:27.184  7096  7096 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-24 21:39:27.184  7096  7096 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-24 21:39:27.188  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-24 21:39:27.191  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-24 21:39:27.193  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-24 21:39:27.194  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-24 21:39:27.196  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-24 21:39:27.197  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-24 21:39:27.199  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-24 21:39:27.201  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-24 21:39:27.202  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-24 21:39:27.204  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-24 21:39:27.206  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-24 21:39:27.289  8377  8414 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-24 21:39:27.307  2196  8449 D GCM     : Connected
,08-24 21:39:27.322  8377  8414 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-24 21:39:27.328  2196  8449 D GCM     : Message class com.google.e.a.a.q
08-24 21:39:27.346  8377  8414 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-24 21:39:27.348  8377  8414 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-24 21:39:27.350  8377  8414 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-24 21:39:27.351  8377  8414 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-24 21:39:27.351  8377  8414 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-24 21:39:27.355  8377  8414 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-24 21:39:27.358  8377  8414 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-24 21:39:27.661  1037  1922 I art     : Explicit concurrent mark sweep GC freed 74766(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.692ms total 178.279ms
,08-24 21:39:28.223  1037  1539 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-24 21:39:28.225  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-24 21:39:28.237  1037  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-24 21:39:28.238  1037  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 21:39:28.238  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 21:39:28.238  1037  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 21:39:28.239  1037  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
,08-24 21:39:28.240  1037  1546 D ConnectivityService: identical MTU - not setting
08-24 21:39:28.240  1037  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-24 21:39:28.240  1037  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-24 21:39:28.240  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:39:28.240  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:39:28.241  1037  1546 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:39:28.242  1604  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-24 21:39:29.397  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2412 sc=60 link=72 tx=108.5, 0.0, 0.0  rx=104.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1106213131] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 21:39:29.409  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2412 sc=60 link=72 tx=108.5, 0.0, 0.0  rx=104.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1106213119] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-24 21:39:29.409  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-24 21:39:29.425  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 21:39:29.450  1037  1541 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-24 21:39:29.479  1037  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:39:29.494  1037  1112 D Tethering: MasterInitialState.processMessage what=3
08-24 21:39:29.514  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:39:29.514  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:29.514  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:29.514  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:39:29.514  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:29.514  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:39:29.514  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:39:29.514  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 21:39:29.521  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:39:29.525  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:39:29.525  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:29.525  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:29.525  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:39:29.525  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:29.525  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:39:29.525  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:39:29.525  6886  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:39:29.527  6886  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:39:29.539  1037  1095 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:39:29.547  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 21:39:29.557  5762  5762 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-24 21:39:29.596  8377  8414 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-24 21:39:29.606  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 21:39:29.606  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:29.606  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:29.606  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:39:29.606  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:29.606  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:39:29.606  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:39:29.606  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:39:29.607  6886  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:39:29.608  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:29.608  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a2fb4b5 removed from the list
08-24 21:39:29.608  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:39:29.608  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:29.608  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:29.616  6886  8465 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-24 21:39:29.616  6886  8465 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-24 21:39:29.629  2196  2196 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:39:29.642  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 21:39:29.642  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 21:39:29.642  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 21:39:29.642  7233  7233 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-24 21:39:29.646  7233  7233 I AppUp4:CustModeStarterReceiver: onReceive
08-24 21:39:29.649  7233  7233 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1ab2b83b
08-24 21:39:29.649  7233  7233 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 21:39:29.649  7233  7233 D AppUp4:CustFacade: isPhone : true
08-24 21:39:29.650  7233  7233 D AppUp4:CustModeStarterReceiver: begin check event
08-24 21:39:29.650  7233  7233 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-24 21:39:29.654  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 21:39:29.655  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-24 21:39:29.663  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 21:39:29.665  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 21:39:29.671  2848  2848 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-24 21:39:29.676  4325  8476 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-24 21:39:29.681  4325  8476 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-24 21:39:29.684  4325  8477 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 21:39:29.684  2848  2848 V DownloadManager: DownloadService onCreate
08-24 21:39:29.684  4325  8477 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-24 21:39:29.687  1037  1053 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
08-24 21:39:29.687  1037  8394 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:29.687  1037  8394 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:29.687  1037  8394 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-24 21:39:29.687  1037  8394 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-24 21:39:29.687  1037  8394 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-24 21:39:29.694  2848  8478 I DownloadManager: in removeSpuriousFiles
08-24 21:39:29.694  2848  8478 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-24 21:39:29.707  2848  8478 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@107cd1a6 on behalf of 2848
08-24 21:39:29.708  2848  8478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-24 21:39:29.708  2848  8478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-24 21:39:29.708  2848  8478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-24 21:39:29.708  2848  8478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-24 21:39:29.708  2848  8478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
,08-24 21:39:29.708  2848  8478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-24 21:39:29.709  2848  8478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-24 21:39:29.709  2848  8478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-24 21:39:29.709  2848  8478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-24 21:39:29.709  2848  8478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-24 21:39:29.709  2848  8478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-24 21:39:29.711  2848  8478 I DownloadManager: in trimDatabase
08-24 21:39:29.711  2848  8478 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-24 21:39:29.712  2848  8478 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2437ef94 on behalf of 2848
08-24 21:39:29.723  1037  1977 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8487 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-24 21:39:29.726  2848  2848 V DownloadManager: DownloadService onStartCommand
08-24 21:39:29.727  2848  8479 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-24 21:39:29.727  1037  8394 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 19:39:29 GMT], X-Android-Received-Millis=[1472067569727], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472067569688]}
08-24 21:39:29.728  1037  8394 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-24 21:39:29.728  1037  8394 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-24 21:39:29.728  1037  1546 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-24 21:39:29.728  1037  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-24 21:39:29.728  1037  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 21:39:29.728  1037  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:39:29.729  1037  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 21:39:29.729  1037  1546 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-24 21:39:29.729  1037  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-24 21:39:29.729  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 21:39:29.729  1037  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:39:29.729  1037  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 21:39:29.730  1604  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 21:39:29.730  4325  8476 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-24 21:39:29.735  4325  4325 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-24 21:39:29.735  1037  1095 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-24 21:39:29.738  4325  4325 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-24 21:39:29.738  4325  4325 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-24 21:39:29.740  4325  4325 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-24 21:39:29.743  2848  8479 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@18946232 on behalf of 2848
08-24 21:39:29.745  2848  8479 V DownloadManager: processing inserted download 1
08-24 21:39:29.746  2848  8479 V DownloadManager: processing inserted download 4
08-24 21:39:29.746  4325  4325 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-24 21:39:29.747  2848  8479 V DownloadManager: processing inserted download 7
08-24 21:39:29.748  2848  8479 V DownloadManager: processing inserted download 8
,08-24 21:39:29.749  2848  8479 V DownloadManager: processing inserted download 9
08-24 21:39:29.751  2848  8479 V DownloadManager: processing inserted download 10
08-24 21:39:29.752  2848  8479 V DownloadManager: processing inserted download 11
08-24 21:39:29.753  2848  8479 V DownloadManager: processing inserted download 12
08-24 21:39:29.754  2848  8479 V DownloadManager: processing inserted download 13
08-24 21:39:29.755  2848  8479 V DownloadManager: processing inserted download 14
08-24 21:39:29.756  2848  8479 V DownloadManager: processing inserted download 16
08-24 21:39:29.763  2848  2848 V DownloadManager: DownloadService onDestroy
,08-24 21:39:29.779  8487  8487 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 21:39:29.779  8487  8487 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 21:39:29.781  8487  8487 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 21:39:29.781  8487  8487 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 21:39:29.854  8487  8487 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-24 21:39:29.865  8487  8487 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-24 21:39:29.914  8487  8487 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-24 21:39:29.951  8487  8487 D LgDataFeature: LgDataFeature() Constructor: none
08-24 21:39:29.951  8487  8487 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 21:39:30.061  8487  8487 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-24 21:39:30.117  8487  8487 I HubEmail: JNI_OnLoad()
08-24 21:39:30.117  8487  8487 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-24 21:39:30.119  8487  8487 I HubEmail: registerNatives()
08-24 21:39:30.119  8487  8487 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-24 21:39:30.119  8487  8487 I HubEmail: registerNativeMethods()
,08-24 21:39:30.119  8487  8487 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-24 21:39:30.120  8487  8487 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-24 21:39:30.130  8487  8516 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 21:39:30.135   328  8519 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-24 21:39:30.136   328  8519 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-24 21:39:30.140  3433  3433 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 21:39:30.140  3433  3433 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 21:39:30.140  3433  3433 I LgeMiscReceiver: networkInfo.isConnected() = true
08-24 21:39:30.140  3433  3433 D PhoneState: setPdpRejectCasuse : false
08-24 21:39:30.182  1037  1921 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8520 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-24 21:39:30.209   328  8519 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-24 21:39:30.294  8310  8515 V FormManager: There are no updated forms. The schedule will be deleted.
,08-24 21:39:30.302  8310  8515 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-24 21:39:30.303  8520  8520 D LgDataFeature: LgDataFeature() Constructor: none
08-24 21:39:30.303  8520  8520 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 21:39:30.307  8520  8520 D PhoneMonitor: Register our PhoneStateListener
,08-24 21:39:30.328  8520  8520 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 21:39:30.330  8520  8520 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-24 21:39:30.343  8520  8520 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-24 21:39:30.344  8520  8520 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-24 21:39:30.344  8520  8520 D TelephonyAutoProfiling: [parse] Load xml
08-24 21:39:30.347  8520  8520 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-24 21:39:30.347  8520  8520 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-24 21:39:30.347  8520  8520 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-24 21:39:30.347  8520  8520 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-24 21:39:30.347  8520  8520 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-24 21:39:30.347  8520  8520 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-24 21:39:30.347  8520  8520 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-24 21:39:30.347  8520  8520 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-24 21:39:30.347  8520  8520 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-24 21:39:30.347  8520  8520 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-24 21:39:30.347  8520  8520 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-24 21:39:30.347  8520  8520 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-24 21:39:30.347  8520  8520 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-24 21:39:30.347  8520  8520 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-24 21:39:30.347  8520  8520 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-24 21:39:30.347  8520  8520 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-24 21:39:30.348  8520  8520 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-24 21:39:30.354  8520  8520 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-24 21:39:30.382  1037  2032 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8539 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 21:39:30.385  1037  2032 I ActivityManager: Killing 7904:com.google.android.talk/u0a72 (adj 15): empty #17
08-24 21:39:30.459  1037  2032 I ActivityManager: Killing 7956:com.android.contacts/u0a19 (adj 15): empty #17
,08-24 21:39:30.495  1037  1052 W libprocessgroup: failed to open /acct/uid_10072/pid_7904/cgroup.procs: No such file or directory
08-24 21:39:30.498  1037  1958 W libprocessgroup: failed to open /acct/uid_10019/pid_7956/cgroup.procs: No such file or directory
,08-24 21:39:30.527  1815  8556 I CheckinService: active receiver: enabled
,08-24 21:39:30.539  1815  8556 I CheckinService: Preparing to send checkin request
08-24 21:39:30.539  1815  8556 I EventLogService: Accumulating logs since 1472067531330
08-24 21:39:30.600  1815  8556 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-24 21:39:30.659   328  8559 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-24 21:39:30.659   328  8559 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-24 21:39:30.701   328  8559 D libc-netbsd: res_queryN name = www.google.com succeed
,08-24 21:39:30.714   328  8561 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-24 21:39:30.715   328  8561 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-24 21:39:30.715   328  8561 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-24 21:39:30.734  1037  1052 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8562 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-24 21:39:30.737  1037  1052 I ActivityManager: Killing 7979:com.android.gallery3d/u0a27 (adj 15): empty #17
08-24 21:39:30.792  1037  1542 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-24 21:39:30.793  1037  1958 W libprocessgroup: failed to open /acct/uid_10027/pid_7979/cgroup.procs: No such file or directory
,08-24 21:39:30.923  1037  1957 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8584 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 21:39:30.925  1037  1957 I ActivityManager: Killing 8040:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-24 21:39:31.012  1037  1539 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-24 21:39:31.013  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-24 21:39:31.016  1037  1539 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-24 21:39:31.017  1037  1539 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-24 21:39:31.019  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-24 21:39:31.021  1037  1539 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-24 21:39:31.088  1037  2032 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8602 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-24 21:39:31.088  1037  1576 W libprocessgroup: failed to open /acct/uid_10080/pid_8040/cgroup.procs: No such file or directory
,08-24 21:39:31.111   355   355 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 491us total 24.369ms
,08-24 21:39:31.134   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 456us total 21.375ms
,08-24 21:39:31.145  8584  8584 I art     : Almond Protected OAT
08-24 21:39:31.155   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 427us total 20.304ms
,08-24 21:39:31.168  8602  8602 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-24 21:39:31.168  8602  8602 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-24 21:39:31.199  8602  8602 I MultiDex: VM with version 2.1.0 has multidex support
08-24 21:39:31.199  8602  8602 I MultiDex: install
08-24 21:39:31.199  8602  8602 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-24 21:39:31.202  8584  8584 D WeatherApplication: removeAccount
08-24 21:39:31.203  8584  8584 D WeatherApplication: Account.length = 0
08-24 21:39:31.203  8584  8584 E WeatherApplication: OPERATOR:OPEN
08-24 21:39:31.208  8584  8584 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:39:31
08-24 21:39:31.211  8584  8584 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 21:39:31.211  8584  8584 D Weather.Utils: 2 : All the weather widget is gone.
08-24 21:39:31.213  8584  8584 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-24 21:39:31.216  8584  8584 D WeatherAncestor: connectivity changed - connection : true
08-24 21:39:31.217  8584  8584 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-24 21:39:31.221  8602  8602 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-24 21:39:31.225  8584  8584 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 21:39:31.225  8584  8584 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 21:39:31.225  8584  8584 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-24 21:39:31.254  8584  8584 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 21:39:31.255  8584  8584 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:39:31
,08-24 21:39:31.311  1037  1958 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8621 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 21:39:31.312  1037  1958 I ActivityManager: Killing 8001:com.android.vending/u0a44 (adj 15): empty #17
08-24 21:39:31.433  1037  1922 W libprocessgroup: failed to open /acct/uid_10044/pid_8001/cgroup.procs: No such file or directory
,08-24 21:39:31.563   281   361 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-24 21:39:31.563   281   361 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-24 21:39:31.564   281   361 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 21:39:31.566  8621  8639 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-24 21:39:31.569   281   361 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 21:39:31.570   281   361 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-24 21:39:31.570   281   361 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 21:39:31.571  8621  8639 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-24 21:39:31.576   281   361 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 21:39:31.576   281   361 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-24 21:39:31.576   281   361 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 21:39:31.577  8621  8643 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-24 21:39:31.584   281   361 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 21:39:31.584   281   361 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-24 21:39:31.584   281   361 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 21:39:31.585  8621  8643 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-24 21:39:31.766  8657  8657 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-24 21:39:31.835  8657  8657 I dex2oat : dex2oat took 68.311ms (threads: 4)
,08-24 21:39:31.836  8621  8621 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-24 21:39:31.847  8621  8621 I LibraryLoader: Loading: webviewchromium
,08-24 21:39:31.851  8621  8621 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8651-8655)
08-24 21:39:31.851  8621  8621 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 21:39:31.853  8602  8618 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 21:39:31.853  8602  8618 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 21:39:31.853  8602  8618 I Adreno-EGL: Build Date: 12/12/14 금
08-24 21:39:31.853  8602  8618 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 21:39:31.853  8602  8618 I Adreno-EGL: Remote Branch: 
08-24 21:39:31.853  8602  8618 I Adreno-EGL: Local Patches: 
08-24 21:39:31.853  8602  8618 I Adreno-EGL: Reconstruct Branch: 
08-24 21:39:31.856  8621  8621 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {19ab12d2}
08-24 21:39:31.858  8621  8621 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 21:39:31.858  8621  8621 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 21:39:31.870  8621  8621 I BrowserStartupController: Initializing chromium process, renderers=0
,08-24 21:39:31.871  8621  8621 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 21:39:31.881  8621  8621 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-24 21:39:31.882  8621  8621 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-24 21:39:31.882  8621  8621 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-24 21:39:31.887   332  1386 V AudioPolicyService: registerClient() client 0xb558ac80, uid 10093
08-24 21:39:31.888  8621  8672 W AudioManagerAndroid: Requires BLUETOOTH permission
08-24 21:39:31.899  8621  8621 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 21:39:31.899  8621  8621 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 21:39:31.899  8621  8621 I Adreno-EGL: Build Date: 12/12/14 금
08-24 21:39:31.899  8621  8621 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 21:39:31.899  8621  8621 I Adreno-EGL: Remote Branch: 
08-24 21:39:31.899  8621  8621 I Adreno-EGL: Local Patches: 
08-24 21:39:31.899  8621  8621 I Adreno-EGL: Reconstruct Branch: 
,08-24 21:39:31.968  8621  8621 I NSApplication: Starting up...
,08-24 21:39:31.977  8602  8618 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 21:39:31.977  8602  8618 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 21:39:31.977  8602  8618 I Adreno-EGL: Build Date: 12/12/14 금
08-24 21:39:31.977  8602  8618 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 21:39:31.977  8602  8618 I Adreno-EGL: Remote Branch: 
08-24 21:39:31.977  8602  8618 I Adreno-EGL: Local Patches: 
08-24 21:39:31.977  8602  8618 I Adreno-EGL: Reconstruct Branch: 
08-24 21:39:32.001  1037  1884 I ActivityManager: Killing 7770:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-24 21:39:32.101  1037  1886 W libprocessgroup: failed to open /acct/uid_10037/pid_7770/cgroup.procs: No such file or directory
,08-24 21:39:32.135  2196  2196 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-24 21:39:32.158  2196  2196 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-24 21:39:32.162  2196  2196 D c       : Getting all permits...
08-24 21:39:32.162  2196  2196 D a       : Opening database...
08-24 21:39:32.170  2196  2196 D a       : Opening database auth.proximity.permit_store...
08-24 21:39:32.172  2196  2196 D a       : Closing database...
08-24 21:39:32.198  8602  8618 D LgDataFeature: LgDataFeature() Constructor: none
08-24 21:39:32.198  8602  8618 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 21:39:32.210  8602  8618 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 21:39:32.210  8602  8618 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 21:39:32.210  8602  8618 I Adreno-EGL: Build Date: 12/12/14 금
08-24 21:39:32.210  8602  8618 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 21:39:32.210  8602  8618 I Adreno-EGL: Remote Branch: 
08-24 21:39:32.210  8602  8618 I Adreno-EGL: Local Patches: 
08-24 21:39:32.210  8602  8618 I Adreno-EGL: Reconstruct Branch: 
,08-24 21:39:32.420   328  8690 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-24 21:39:32.420   328  8690 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-24 21:39:32.433  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2412 sc=60 link=72 tx=63.2, 0.0, 0.0  rx=59.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1106210096] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-24 21:39:32.433  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2412 sc=60 link=72 tx=63.2, 0.0, 0.0  rx=59.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1106210095] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-24 21:39:32.433  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-24 21:39:32.459   328  8690 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-24 21:39:32.617  6886  8465 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-24 21:39:32.618  6886  8465 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-24 21:39:32.618  6886  8465 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-24 21:39:32.619  6886  8465 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-24 21:39:32.619  6886  8465 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-24 21:39:32.626  6886  8697 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-24 21:39:32.626  6886  8697 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-24 21:39:32.626  6886  8697 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-24 21:39:32.627  6886  8697 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-24 21:39:32.629  6886  8700 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 877, name: OutgoingSocketThread/Receiver)
08-24 21:39:32.629  6886  8700 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 877, thread name: OutgoingSocketThread/Receiver)
08-24 21:39:32.630  6886  8700 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-24 21:39:32.630  6886  8700 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 877, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-24 21:39:32.632  6886  8699 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 876, name: OutgoingSocketThread/Sender)
08-24 21:39:32.636  6886  8697 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-24 21:39:32.642  6886  8701 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 878, name: IncomingSocketThread/Sender)
08-24 21:39:32.643  6886  8702 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 879, name: IncomingSocketThread/Receiver)
08-24 21:39:32.643  6886  8702 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 879, thread name: IncomingSocketThread/Receiver)
08-24 21:39:32.643  6886  8702 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-24 21:39:32.643  6886  8702 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 879, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-24 21:39:32.658  1815  8556 I CheckinTask: Sending checkin request (7875 bytes)
,08-24 21:39:32.958  1815  8556 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-24 21:39:32.973  1815  8556 I CheckinService: active receiver: disabled
,08-24 21:39:33.000  2196  2196 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-24 21:39:33.018  2196  2196 I GCM     : GCM config loaded
,08-24 21:39:33.052  8520  8520 V SetupWizard: Connected to Gservices successfully
,08-24 21:39:33.061   328  8712 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-24 21:39:33.061   328  8712 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-24 21:39:33.061   328  8712 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-24 21:39:33.309  1037  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{174466bc type 2 when 390093 com.google.android.gms} when 390093
,08-24 21:39:33.322  2196  8714 D GCM     : Connected
,08-24 21:39:33.342  2196  8714 D GCM     : Message class com.google.e.a.a.q
,08-24 21:39:35.449  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=40.6, 0.0, 0.0  rx=35.2 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1106207079] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 21:39:35.452  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=40.6, 0.0, 0.0  rx=35.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1106207076] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-24 21:39:35.452  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-24 21:39:35.628  6886  6943 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-24 21:39:35.629  6886  6943 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-24 21:39:35.631  6886  6943 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2cbafaa5 Bundle[{}]
08-24 21:39:35.631  6886  6943 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 21:39:35.632  6886  6943 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-24 21:39:35.632  6886  6943 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-24 21:39:35.633  6886  6943 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 21:39:35.634  6886  6943 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-24 21:39:35.634  6886  6943 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-24 21:39:35.645  6886  6943 I System.out: Running OutgoingSocketThread
08-24 21:39:35.648  6886  8718 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-24 21:39:35.648  6886  8718 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-24 21:39:36.585  8621  8641 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-24 21:39:37.413  1037  1886 I ActivityManager: Killing 7811:com.lge.settings.easy/1000 (adj 15): empty #17
,08-24 21:39:37.449  1037  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_7811/cgroup.procs: No such file or directory
,08-24 21:39:38.474  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=32.8, 0.0, 0.0  rx=28.6 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1106204054] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 21:39:38.484  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=32.8, 0.0, 0.0  rx=28.6 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1106204044] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 21:39:38.485  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-24 21:39:38.663  6886  8718 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-24 21:39:38.663  6886  8718 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-24 21:39:38.663  6886  8718 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-24 21:39:38.664  6886  8718 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-24 21:39:38.665  6886  8718 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-24 21:39:38.677  6886  8721 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-24 21:39:38.678  6886  8721 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-24 21:39:38.678  6886  8721 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-24 21:39:38.678  6886  8721 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-24 21:39:38.678  6886  8721 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-24 21:39:38.681  6886  8724 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 889, name: OutgoingSocketThread/Receiver)
08-24 21:39:38.681  6886  8724 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 889, thread name: OutgoingSocketThread/Receiver)
08-24 21:39:38.681  6886  8724 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-24 21:39:38.681  6886  8724 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 889, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-24 21:39:38.685  6886  8723 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 888, name: OutgoingSocketThread/Sender)
,08-24 21:39:38.689  6886  8726 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 891, name: IncomingSocketThread/Receiver)
08-24 21:39:38.689  6886  8726 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 891, thread name: IncomingSocketThread/Receiver)
08-24 21:39:38.689  6886  8726 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-24 21:39:38.690  6886  8726 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 891, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-24 21:39:38.692  6886  8725 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 890, name: IncomingSocketThread/Sender)
08-24 21:39:40.634  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-24 21:39:40.664  1037  1409 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 21:39:40.742  1037  1097 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8727 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-24 21:39:40.761  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-24 21:39:40.768  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-24 21:39:40.769  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-24 21:39:40.772  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 21:39:40.779  1037  1037 D administrator: Handling package changes for user 0
,08-24 21:39:40.831  8727  8727 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-24 21:39:40.904  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-24 21:39:40.904  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-24 21:39:40.921  8727  8727 D LgDataFeature: LgDataFeature() Constructor: none
,08-24 21:39:40.921  8727  8727 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 21:39:40.960  1037  1095 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 21:39:40.966  1037  1095 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-24 21:39:40.974  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-24 21:39:40.976  2504  2504 V GmsNetworkLocationProvi: DISABLE
,08-24 21:39:41.015  1037  1095 D LocationProviderProxy: applying state to connected service
08-24 21:39:41.016  2504  2504 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-24 21:39:41.050  8727  8772 I Babel   : MmsConfig: mnc/mcc: 0/0
08-24 21:39:41.050  8727  8772 I Babel   : MmsConfig.loadMmsSettings
08-24 21:39:41.052  8727  8772 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-24 21:39:41.052  8727  8772 I Babel   : MmsConfig.loadFromDatabase
,08-24 21:39:41.071  8727  8727 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 21:39:41.071  8727  8772 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-24 21:39:41.072  8727  8772 I Babel   : MmsConfig.loadFromResources
08-24 21:39:41.074  8727  8770 W AudioCapabilities: Unsupported mime audio/evrc
,08-24 21:39:41.075  8727  8770 W AudioCapabilities: Unsupported mime audio/qcelp
08-24 21:39:41.078  8727  8772 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-24 21:39:41.078  8727  8770 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-24 21:39:41.078  8727  8772 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-24 21:39:41.093  8727  8770 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-24 21:39:41.095  8727  8770 W AudioCapabilities: Unsupported mime audio/qcelp
08-24 21:39:41.096  8727  8770 W AudioCapabilities: Unsupported mime audio/evrc
08-24 21:39:41.110  7233  7233 I AppUp4:CustModeStarterReceiver: onReceive
,08-24 21:39:41.112  1815  8773 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-24 21:39:41.112  1815  8773 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-24 21:39:41.116  7233  7233 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1ab2b83b
08-24 21:39:41.116  7233  7233 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 21:39:41.116  7233  7233 D AppUp4:CustFacade: isPhone : true
08-24 21:39:41.116  7233  7233 D AppUp4:CustModeStarterReceiver: begin check event
08-24 21:39:41.116  7233  7233 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-24 21:39:41.122  8727  8770 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-24 21:39:41.123  1815  4760 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-24 21:39:41.132  8727  8770 W VideoCapabilities: Unsupported mime video/divx
08-24 21:39:41.135  8727  8770 W VideoCapabilities: Unsupported mime video/divx311
08-24 21:39:41.138  8727  8770 W VideoCapabilities: Unsupported mime video/divx4
08-24 21:39:41.148  8727  8770 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-24 21:39:41.150  1037  2050 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8777 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-24 21:39:41.164  1037  2013 I ActivityManager: Killing 8359:com.lge.bnr/1000 (adj 15): empty #17
,08-24 21:39:41.182  8727  8770 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-24 21:39:41.186  8727  8770 W AudioCapabilities: Unsupported mime audio/eac3
,08-24 21:39:41.187  8727  8770 W AudioCapabilities: Unsupported mime audio/ac3
08-24 21:39:41.187  8727  8770 W AudioCapabilities: Unsupported mime audio/g726
08-24 21:39:41.188  8727  8770 W AudioCapabilities: Unsupported mime audio/wma-voice
08-24 21:39:41.189  8727  8770 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-24 21:39:41.190  8727  8770 W AudioCapabilities: Unsupported mime audio/adpcm
08-24 21:39:41.192  8727  8770 W VideoCapabilities: Unsupported mime video/theora
08-24 21:39:41.194  8727  8770 W VideoCapabilities: Unsupported mime video/mjpg
,08-24 21:39:41.270  1037  1977 W libprocessgroup: failed to open /acct/uid_1000/pid_8359/cgroup.procs: No such file or directory
08-24 21:39:41.286  8777  8777 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 21:39:41.286  8777  8777 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 21:39:41.286  8777  8777 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-24 21:39:41.287  8777  8777 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-24 21:39:41.287  8777  8777 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-24 21:39:41.335  8777  8777 I SystemConfig: BUILD Country: EU
08-24 21:39:41.335  8777  8777 I SystemConfig: BUILD Operator: OPEN
,08-24 21:39:41.369  1037  1977 I ActivityManager: Killing 8331:com.lge.sync/1000 (adj 15): empty #17
,08-24 21:39:41.459  1037  1921 W libprocessgroup: failed to open /acct/uid_1000/pid_8331/cgroup.procs: No such file or directory
,08-24 21:39:41.472  8777  8796 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-24 21:39:41.473  8777  8796 I SystemConfig: existFile = false
08-24 21:39:41.473  8777  8796 I SystemConfig: canReadFile = false
08-24 21:39:41.473  8777  8796 I SystemConfig: systemFeature RCS result false
08-24 21:39:41.473  8777  8796 D SystemConfig: refreshRcsSupport() :false
,08-24 21:39:41.505  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2412 sc=60 link=72 tx=16.9, 0.0, 0.0  rx=14.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1106201023] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 21:39:41.506  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2412 sc=60 link=72 tx=16.9, 0.0, 0.0  rx=14.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1106201022] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 21:39:41.507  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-24 21:39:41.527  1037  1977 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8798 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-24 21:39:41.662  6886  6943 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 900)
,08-24 21:39:41.665  6886  6943 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-24 21:39:41.665  6886  6943 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 901)
08-24 21:39:41.674  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 21:39:41.675  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@385d474a added. We now have 3 listener(s)
08-24 21:39:41.675  1037  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:41.679  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 21:39:41.679  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 21:39:41.679  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 21:39:41.679  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 21:39:41.679  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18ac16bb added. We now have 4 listener(s)
08-24 21:39:41.679  6886  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 21:39:41.679  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 21:39:41.689  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:39:41.694  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 21:39:41.694  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:41.694  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:41.694  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:39:41.694  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:41.694  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:39:41.694  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:39:41.694  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 21:39:41.699  6886  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 21:39:41.699  6886  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 21:39:41.702  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:41.704  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:39:41.704  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:39:41.704  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:39:41.705  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:39:41.705  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:41.705  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:41.705  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:39:41.705  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 21:39:41.705  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@385d474a removed from the list
08-24 21:39:41.706  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:41.706  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18ac16bb removed from the list
08-24 21:39:41.706  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:39:41.706  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:41.706  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:41.706  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:41.716  1037  1053 I art     : Explicit concurrent mark sweep GC freed 34993(1817KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.286ms total 153.588ms
08-24 21:39:41.718  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:39:41.718  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:39:41.718  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:41.718  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18ac16bb not in the list
08-24 21:39:41.718  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:41.718  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 21:39:41.720  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:39:41.720  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:39:41.720  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:41.720  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18ac16bb not in the list
08-24 21:39:41.720  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:39:41.720  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:41.720  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:41.720  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@385d474a not in the list
08-24 21:39:41.721  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 21:39:41.721  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1073e731 added. We now have 3 listener(s)
08-24 21:39:41.722  1037  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:41.725  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 21:39:41.725  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 21:39:41.725  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 21:39:41.725  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 21:39:41.725  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b08e16 added. We now have 4 listener(s)
08-24 21:39:41.725  6886  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 21:39:41.726  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 21:39:41.729  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:39:41.733  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 21:39:41.733  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:41.733  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:41.733  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:39:41.733  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:41.733  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:39:41.733  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:39:41.733  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:39:41.735  6886  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:39:41.735  6886  6943 D io.jxcore.node,.ConnectivityMonitor: start: OK
,08-24 21:39:41.737  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:41.738  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 21:39:41.738  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 21:39:41.738  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 21:39:41.738  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:39:41.738  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 21:39:41.741  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 21:39:41.742  1037  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:41.743  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:41.746  8798  8798 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 21:39:41.747  8798  8798 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-24 21:39:41.747  8798  8798 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-24 21:39:41.747  8798  8798 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 21:39:41.747  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 21:39:41.748  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 21:39:41.751  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 21:39:41.751  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:39:41.753  6886  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 21:39:41.753  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:39:41.753  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:39:41.860  8798  8798 I AppConfig: Total System Memory = 2995761152
,08-24 21:39:41.870  8798  8798 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-24 21:39:41.968  1037  1053 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8820 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 21:39:41.975  1037  1053 I ActivityManager: Killing 6760:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-24 21:39:41.995  7096  7096 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-24 21:39:41.999  7096  7096 W System.err: android.os.DeadObjectException
08-24 21:39:41.999  7096  7096 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-24 21:39:41.999  7096  7096 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-24 21:39:41.999  7096  7096 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-24 21:39:41.999  7096  7096 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-24 21:39:41.999  7096  7096 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-24 21:39:41.999  7096  7096 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-24 21:39:41.999  7096  7096 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 21:39:41.999  7096  7096 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 21:39:41.999  7096  7096 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 21:39:41.999  7096  7096 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 21:39:41.999  7096  7096 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 21:39:41.999  7096  7096 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 21:39:42.000  7096  7096 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 21:39:42.000  7096  7096 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 21:39:42.000  7096  7096 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-24 21:39:42.001  7096  7096 W System.err: android.os.DeadObjectException
08-24 21:39:42.001  7096  7096 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-24 21:39:42.001  7096  7096 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-24 21:39:42.001  7096  7096 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-24 21:39:42.001  7096  7096 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-24 21:39:42.001  7096  7096 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-24 21:39:42.001  7096  7096 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-24 21:39:42.001  7096  7096 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 21:39:42.001  7096  7096 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 21:39:42.001  7096  7096 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 21:39:42.002  7096  7096 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 21:39:42.002  7096  7096 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 21:39:42.002  7096  7096 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 21:39:42.002  7096  7096 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 21:39:42.002  7096  7096 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 21:39:42.002  7096  7096 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-24 21:39:42.002  7096  7096 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-24 21:39:42.035  1037  1885 W libprocessgroup: failed to open /acct/uid_1000/pid_6760/cgroup.procs: No such file or directory
08-24 21:39:42.036  1037  1885 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-24 21:39:42.044  7096  7096 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-24 21:39:42.045  7096  7096 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-24 21:39:42.104  1037  2032 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8838 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-24 21:39:42.109  7096  7096 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-24 21:39:42.188  8838  8838 D UEI.SmartControl: Quickset Services start...
08-24 21:39:42.190  8838  8838 I UEI.SmartControl: Manufacture = LGE
08-24 21:39:42.190  8838  8838 D UEI.SmartControl: Id = LGNevo
08-24 21:39:42.191  8838  8838 D UEI.SmartControl: File observer start...
,08-24 21:39:42.193  8838  8838 E UEI.SmartControl: IR Port is disabled: false
08-24 21:39:42.193  8838  8838 D UEI.SmartControl: Starting file observer...
08-24 21:39:42.193  8838  8838 D UEI.SmartControl: Extracting JNI libs...
08-24 21:39:42.194  8838  8838 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-24 21:39:42.268  8820  8820 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-24 21:39:42.286  8838  8838 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-24 21:39:42.286  8838  8838 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-24 21:39:42.286  8838  8838 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-24 21:39:42.342  8838  8838 I UEI.SmartControl: --- Selecting new region: 6
08-24 21:39:42.345  8820  8820 D LgDataFeature: LgDataFeature() Constructor: none
08-24 21:39:42.345  8838  8838 I UEI.SmartControl: Model = LG-D855
08-24 21:39:42.345  8820  8820 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 21:39:42.348  8838  8838 D UEI.SmartControl: QS Service created
,08-24 21:39:42.369  8838  8838 I UEI.SmartControl: Service initServices...
,08-24 21:39:42.376  8838  8838 D UEI.SmartControl: QS start get config
08-24 21:39:42.394  8820  8820 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-24 21:39:42.418  8820  8820 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-24 21:39:42.419  8820  8820 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-24 21:39:42.436  8820  8820 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-24 21:39:42.436  8820  8820 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-24 21:39:42.456  8838  8838 D UEI.SmartControl: Loading JNI Libs...
,08-24 21:39:42.458  1037  1958 I ActivityManager: Killing 7043:com.android.settings/1000 (adj 15): empty #17
,08-24 21:39:42.672  1037  1576 W libprocessgroup: failed to open /acct/uid_1000/pid_7043/cgroup.procs: No such file or directory
,08-24 21:39:42.682  2848  2865 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-24 21:39:42.684  2848  2865 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@336e7100 on behalf of 8820
08-24 21:39:42.687  4615  8876 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-24 21:39:42.735  1037  1052 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8877 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-24 21:39:42.739  8838  8838 I UEI.SmartControl: Supports setup maps: true
08-24 21:39:42.747  8838  8838 D UEI.SmartControl: QS start statue = true Error code = 0
08-24 21:39:42.748  8838  8838 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-24 21:39:42.748  8838  8838 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-24 21:39:42.748  8838  8838 I UEI.SmartControl: ### init IR Blaster...
,08-24 21:39:42.756  8838  8838 D serial_port: Configuring serial port
08-24 21:39:42.760  8838  8838 E UEI.SmartControl: UEIBLaster setting for 616
08-24 21:39:42.761  8838  8838 I UEI.SmartControl: Setting serial record hearder size = 2
08-24 21:39:42.761  8838  8838 I UEI.SmartControl: configuring settings for MAXQ616
08-24 21:39:42.761  8838  8838 I UEI.SmartControl: Get version...
08-24 21:39:42.766  8820  8820 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-24 21:39:42.781  8838  8891 D UEI.SmartControl: serial port data available: 21
,08-24 21:39:42.784  8820  8820 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-24 21:39:42.808  8838  8838 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-24 21:39:42.808  8838  8838 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-24 21:39:42.809  8838  8838 I UEI.SmartControl: QS saving settings...
08-24 21:39:42.809  8838  8838 D UEI.SmartControl: IR Blaster version: 25672567
,08-24 21:39:42.811  8877  8877 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-24 21:39:42.823  8838  8891 D UEI.SmartControl: serial port data available: 4
,08-24 21:39:42.832  8877  8877 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-24 21:39:42.832  8877  8877 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-24 21:39:42.832  8877  8877 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-24 21:39:42.832  8877  8877 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-24 21:39:42.832  8877  8877 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-24 21:39:42.832  8877  8877 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-24 21:39:42.844  1037  1053 I ActivityManager: Killing 7096:com.lge.qremote/u0a112 (adj 15): empty #17
,08-24 21:39:42.853  8838  8901 I UEI.SmartControl: Device manager: loading config....
08-24 21:39:42.854  8838  8901 D UEI.SmartControl: ----------- loading internal config...
08-24 21:39:42.856  8838  8838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-24 21:39:42.864  8838  8901 E UEI.SmartControl: Loading SETTINGS...
,08-24 21:39:42.870  8838  8901 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-24 21:39:42.873  8838  8900 I UEI.SmartControl: Notify AllClients services are ready: 0
08-24 21:39:42.873  8838  8900 D UEI.SmartControl: -----service ready thread exits
08-24 21:39:42.876  8838  8838 E UEI.SmartControl: Services init done
,08-24 21:39:42.876  1037  2013 W libprocessgroup: failed to open /acct/uid_10112/pid_7096/cgroup.procs: No such file or directory
08-24 21:39:42.876  8838  8838 D UEI.SmartControl: QS Service init finished
08-24 21:39:42.877  8838  8838 D UEI.SmartControl: QS Service version name: 2.1.91
08-24 21:39:42.877  8838  8838 D UEI.SmartControl: QS Service version code: 201091
08-24 21:39:42.877  8838  8838 D UEI.SmartControl: Service requested: Control
08-24 21:39:42.880  1037  1576 I ActivityManager: Killing 8487:com.lge.email/u0a23 (adj 15): empty #17
08-24 21:39:42.910  8838  8838 D UEI.SmartControl: Internal service binding...
,08-24 21:39:42.918  1037  1995 W libprocessgroup: failed to open /acct/uid_10023/pid_8487/cgroup.procs: No such file or directory
,08-24 21:39:43.048  1037  1053 V SIM_STK : Menu title from STK is T-Mobile
,08-24 21:39:43.062  4615  8876 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 375 ms] updated apps [took 375 ms] 
,08-24 21:39:44.526  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2412 sc=60 link=72 tx=8.5, 0.0, 0.0  rx=7.2 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1106198003] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 21:39:44.529  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2412 sc=60 link=72 tx=8.5, 0.0, 0.0  rx=7.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1106197999] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-24 21:39:44.530  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-24 21:39:44.754  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 21:39:44.755  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 21:39:44.755  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 21:39:44.767  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:39:44.767  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:44.767  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:39:44.767  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 21:39:44.767  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1073e731 removed from the list
08-24 21:39:44.767  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:44.767  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b08e16 removed from the list
08-24 21:39:44.767  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:39:44.767  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:44.768  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:44.769  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:44.771  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:39:44.771  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:39:44.772  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:39:44.772  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:39:44.772  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:44.773  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b08e16 not in the list
08-24 21:39:44.773  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:44.773  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:44.774  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:39:44.774  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:39:44.774  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:39:44.775  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:39:44.775  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:44.775  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b08e16 not in the list
08-24 21:39:44.775  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:39:44.775  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:44.775  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:44.775  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1073e731 not in the list
08-24 21:39:44.776  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 21:39:44.776  688,6  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@331f75a2 added. We now have 3 listener(s)
08-24 21:39:44.777  1037  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 21:39:44.783  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 21:39:44.784  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 21:39:44.784  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 21:39:44.784  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 21:39:44.784  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3788a233 added. We now have 4 listener(s)
08-24 21:39:44.784  6886  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 21:39:44.786  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 21:39:44.790  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 21:39:44.796  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 21:39:44.796  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:44.796  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:44.796  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:39:44.796  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:44.796  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:39:44.796  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:39:44.796  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:39:44.799  6886  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:39:44.799  6886  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 21:39:44.801  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:44.803  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 21:39:44.805  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-24 21:39:44.806  6886  6943 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-24 21:39:44.806  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-24 21:39:44.809  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-24 21:39:44.809  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-24 21:39:44.809  6886  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-24 21:39:44.809  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:39:44.813  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-24 21:39:44.813  6886  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-24 21:39:44.813  6886  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-24 21:39:44.814  6886  6886 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-24 21:39:44.818  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-24 21:39:44.818  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-24 21:39:44.818  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:39:44.818  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 21:39:44.823  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 21:39:44.826  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 21:39:44.831  1037  1623 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:44.833  6886  8909 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 21:39:44.833  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 21:39:44.835  8128  8145 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-24 21:39:44.837  6886  8909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-24 21:39:44.839  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 21:39:44.841  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 21:39:44.841  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-24 21:39:44.843  6886  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 21:39:47.559  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.6 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1106194969] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:39:47.562  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1106194966] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:39:47.562  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-24 21:39:47.845  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 21:39:47.852  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:39:47.853  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 21:39:47.853  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-24 21:39:47.853  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-24 21:39:47.853  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-24 21:39:47.855  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:39:47.855  6886  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-24 21:39:47.856  6886  8909 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-24 21:39:47.856  6886  8909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-24 21:39:47.856  6886  8909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-24 21:39:47.857  6886  6886 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-24 21:39:47.859  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 21:39:47.859  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:47.859  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:39:47.881  6886  6886 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:39:47.882  6886  6886 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-24 21:39:47.882  6886  6886 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-24 21:39:47.887  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:39:47.887  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:47.887  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:39:47.887  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 21:39:47.887  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@331f75a2 removed from the list
08-24 21:39:47.887  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:47.887  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3788a233 removed from the list
08-24 21:39:47.887  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:39:47.887  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:47.888  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:47.888  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:47.889  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:39:47.889  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:39:47.890  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:39:47.890  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:39:47.890  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:47.890  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3788a233 not in the list
08-24 21:39:47.890  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:47.890  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:47.894  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:39:47.894  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:39:47.894  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:39:47.894  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:39:47.894  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:47.894  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3788a233 not in the list
08-24 21:39:47.894  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:39:47.894  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:47.894  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:47.895  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@331f75a2 not in the list
08-24 21:39:47.897  8838  8902 D UEI.SmartControl: Internal timer expired: 1
08-24 21:39:47.897  8838  8902 D UEI.SmartControl: unbind inter,nal service
,08-24 21:39:47.902  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 21:39:47.902  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6212e8f added. We now have 3 listener(s)
08-24 21:39:47.907  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:47.910  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 21:39:47.911  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 21:39:47.911  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 21:39:47.911  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 21:39:47.911  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ea951c added. We now have 4 listener(s)
08-24 21:39:47.911  6886  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 21:39:47.915  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 21:39:47.919  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:39:47.923  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 21:39:47.923  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:47.923  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:47.923  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:39:47.923  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:47.923  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:39:47.923  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:39:47.923  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 21:39:47.926  6886  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:39:47.927  6886  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 21:39:47.929  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:47.931  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:47.932  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 21:39:47.932  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 21:39:47.932  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 21:39:47.932  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 21:39:47.932  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 21:39:47.936  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 21:39:47.938  1037  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:47.943  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 21:39:47.944  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 21:39:47.945  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 21:39:47.946  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:39:47.947  6886  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-24 21:39:47.950  8838  8838 D UEI.SmartControl: Service.onUnbind: IControl
08-24 21:39:47.951  8838  8838 D UEI.SmartControl: Service.onDestroy
08-24 21:39:47.951  8838  8838 D UEI.SmartControl: Lock is in USE false
08-24 21:39:47.951  8838  8838 D UEI.SmartControl: unbind internal service
08-24 21:39:47.951  8838  8838 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@310a9d17
08-24 21:39:47.952  8838  8838 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-24 21:39:47.952  8838  8838 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-24 21:39:47.952  8838  8838 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-24 21:39:47.952  8838  8838 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-24 21:39:47.952  8838  8838 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-24 21:39:47.952  8838  8838 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-24 21:39:47.952  8838  8838 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-24 21:39:47.952  8838  8838 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-24 21:39:47.952  8838  8838 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 21:39:47.952  8838  8838 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 21:39:47.952  8838  8838 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 21:39:47.952  8838  8838 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 21:39:47.952  8838  8838 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 21:39:47.952  8838  8838 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 21:39:47.952  8838  8838 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 21:39:47.953  8838  8838 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@310a9d17
08-24 21:39:47.955  8838  8838 D serial_port: close(fd = 25)
08-24 21:39:47.959  8838  8838 I UEI.SmartControl: Serial port is closed.
08-24 21:39:47.959  8838  8838 I UEI.SmartControl: Serial port is closed.
08-24 21:39:47.959  8838  8838 D UEI.SmartControl: Blaster closed
08-24 21:39:47.959  8838  8838 D UEI.SmartControl: Shut down QS...
08-24 21:39:47.959  8838  8838 D UEI.SmartControl: Stopping QS lib
08-24 21:39:47.959  8838  8838 D UEI.SmartControl: QS lib stop result = true
08-24 21:39:47.960  8838  8838 D UEI.SmartControl: Stopped QS lib
,08-24 21:39:47.963  8838  8838 D UEI.SmartControl: Stopped file observer...
,08-24 21:39:47.963  8838  8838 D UEI.SmartControl: QS shutdown complete
08-24 21:39:50.587  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1106191941] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-24 21:39:50.599  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1106191929] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-24 21:39:50.599  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-24 21:39:50.956  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:39:50.957  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:39:50.957  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 21:39:50.967  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:39:50.967  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:50.967  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:39:50.968  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 21:39:50.968  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6212e8f removed from the list
08-24 21:39:50.968  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:50.968  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ea951c removed from the list
08-24 21:39:50.968  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:39:50.969  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:50.969  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:50.969  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:50.970  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:39:50.970  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:39:50.971  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:39:50.971  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:39:50.971  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:50.971  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ea951c not in the list
08-24 21:39:50.971  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:50.971  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:50.974  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 21:39:50.977  6886  6943 D BluetoothLeScanner: could not find callback wrapper
08-24 21:39:50.977  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 21:39:50.977  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:39:50.977  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:50.977  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ea951c not in the list
08-24 21:39:50.977  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:39:50.977  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:50.977  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:50.977  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6212e8f not in the list
08-24 21:39:50.979  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 21:39:50.979  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2599e708 added. We now have 3 listener(s)
08-24 21:39:50.979  1037  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 21:39:50.982  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 21:39:50.982  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 21:39:50.982  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 21:39:50.982  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 21:39:50.982  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f1bfea1 added. We now have 4 listener(s)
08-24 21:39:50.982  6886  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 21:39:50.983  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 21:39:50.988  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 21:39:50.995  6886  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 21:39:50.995  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 21:39:50.995  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 21:39:50.995  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 21:39:50.995  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 21:39:50.995  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 21:39:50.995  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 21:39:50.995  6886  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 21:39:50.998  6886  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 21:39:50.998  6886  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 21:39:51.000  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 21:39:51.004  6886  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 21:39:51.005  6886  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 21:39:51.005  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 21:39:51.005  6886  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 21:39:51.006  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:39:51.006  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:51.006  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 21:39:51.006  6886  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 21:39:51.006  6886  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2599e708 removed from the list
08-24 21:39:51.006  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:51.006  6886  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f1bfea1 removed from the list
08-24 21:39:51.006  6886  6943 D io.jxcore.node.ConnectivityMonitor: stop
08-24 21:39:51.007  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:51.007  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:51.007  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:51.010  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:39:51.010  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:39:51.010  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:51.010  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f1bfea1 not in the list
08-24 21:39:51.010  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:51.010  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:51.011  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 21:39:51.011  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 21:39:51.011  6886  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 21:39:51.011  6886  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f1bfea1 not in the list
08-24 21:39:51.011  6886  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 21:39:51.011  6886  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 21:39:51.011  6886  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 21:39:51.011  6886  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: ,removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2599e708 not in the list
08-24 21:39:51.012  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-24 21:39:51.013  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-24 21:39:51.013  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-24 21:39:51.013  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 21:39:51.013  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-24 21:39:51.013  6886  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 21:39:53.035  6886  8910 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 910, name: My test thread name)
,08-24 21:39:53.618  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1106188910] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:39:53.621  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1106188907] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:39:53.621  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-24 21:39:55.031  6886  6943 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 910
08-24 21:39:55.032  6886  6943 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 910, name: My test thread name)
,08-24 21:39:55.048  6886  8911 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 911, name: My test thread name)
08-24 21:39:55.049  6886  8911 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 911, thread name: My test thread name)
08-24 21:39:55.049  6886  8911 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 911, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-24 21:39:55.050  6886  6943 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-24 21:39:55.056  6886  8912 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 915, name: My test thread name)
08-24 21:39:55.056  6886  8912 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 915, thread name: My test thread name): Test exception.
08-24 21:39:55.056  6886  8912 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 915, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-24 21:39:55.062  6886  6943 I jxcore-log: Total number of executed tests:  82
08-24 21:39:55.062  6886  6943 I jxcore-log: 
08-24 21:39:55.062  6886  6943 I jxcore-log: Number of passed tests:  82
08-24 21:39:55.062  6886  6943 I jxcore-log: 
08-24 21:39:55.062  6886  6943 I jxcore-log: Number of failed tests:  0
08-24 21:39:55.062  6886  6943 I jxcore-log: 
08-24 21:39:55.062  6886  6943 I jxcore-log: Number of ignored tests:  0
08-24 21:39:55.062  6886  6943 I jxcore-log: 
08-24 21:39:55.063  6886  6943 I jxcore-log: Total duration:  101540
08-24 21:39:55.063  6886  6943 I jxcore-log: 
08-24 21:39:55.065  6886  6943 I jxcore-log: Unit Test app is loaded
08-24 21:39:55.065  6886  6943 I jxcore-log: 
08-24 21:39:55.090  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.090  6886  6943 I jxcore-log: 
08-24 21:39:55.094  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.094  6886  6943 I jxcore-log: 
08-24 21:39:55.095  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.095  6886  6943 I jxcore-log: 
,08-24 21:39:55.099  6886  8910 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 910, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
08-24 21:39:55.105  6886  6886 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-24 21:39:55.107  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.107  6886  6943 I jxcore-log: 
08-24 21:39:55.108  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.108  6886  6943 I jxcore-log: 
08-24 21:39:55.109  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.109  6886  6943 I jxcore-log: 
08-24 21:39:55.113  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 21:39:55.113  6886  6943 I jxcore-log: 
08-24 21:39:55.114  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.114  6886  6943 I jxcore-log: 
08-24 21:39:55.115  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.115  6886  6943 I jxcore-log: 
08-24 21:39:55.117  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 21:39:55.117  6886  6943 I jxcore-log: 
08-24 21:39:55.118  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 21:39:55.118  6886  6943 I jxcore-log: 
08-24 21:39:55.119  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 21:39:55.119  6886  6943 I jxcore-log: 
08-24 21:39:55.120  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 21:39:55.120  6886  6943 I jxcore-log: 
08-24 21:39:55.121  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 21:39:55.121  6886  6943 I jxcore-log: 
08-24 21:39:55.121  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 21:39:55.121  6886  6943 I jxcore-log: 
08-24 21:39:55.122  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 21:39:55.122  6886  6943 I jxcore-log: 
08-24 21:39:55.123  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 21:39:55.123  6886  6943 I jxcore-log: 
08-24 21:39:55.124  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 21:39:55.124  6886  6943 I jxcore-log: 
08-24 21:39:55.125  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on",,"cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.125  6886  6943 I jxcore-log: 
,08-24 21:39:55.131  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.131  6886  6943 I jxcore-log: 
08-24 21:39:55.133  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.133  6886  6943 I jxcore-log: 
08-24 21:39:55.134  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 21:39:55.134  6886  6943 I jxcore-log: 
08-24 21:39:55.135  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 21:39:55.135  6886  6943 I jxcore-log: 
08-24 21:39:55.136  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 21:39:55.136  6886  6943 I jxcore-log: 
08-24 21:39:55.137  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 21:39:55.137  6886  6943 I jxcore-log: 
08-24 21:39:55.137  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 21:39:55.137  6886  6943 I jxcore-log: 
08-24 21:39:55.138  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 21:39:55.138  6886  6943 I jxcore-log: 
08-24 21:39:55.139  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 21:39:55.139  6886  6943 I jxcore-log: 
08-24 21:39:55.140  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 21:39:55.140  6886  6943 I jxcore-log: 
08-24 21:39:55.141  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 21:39:55.141  6886  6943 I jxcore-log: 
08-24 21:39:55.141  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 21:39:55.141  6886  6943 I jxcore-log: 
08-24 21:39:55.142  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 21:39:55.142  6886  6943 I jxcore-log: 
08-24 21:39:55.143  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 21:39:55.143  6886  6943 I jxcore-log: 
08-24 21:39:55.144  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 21:39:55.144  6886  6943 I jxcore-log: 
08-24 21:39:55.144  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 21:39:55.144  6886  6943 I jxcore-log: 
08-24 21:39:55.145  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.145  6886  6943 I jxcore-log: 
08-24 21:39:55.146  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":",on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.146  6886  6943 I jxcore-log: 
08-24 21:39:55.147  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.147  6886  6943 I jxcore-log: 
08-24 21:39:55.148  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.148  6886  6943 I jxcore-log: 
08-24 21:39:55.149  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.149  6886  6943 I jxcore-log: 
08-24 21:39:55.150  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.150  6886  6943 I jxcore-log: 
08-24 21:39:55.150  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.150  6886  6943 I jxcore-log: 
08-24 21:39:55.151  6886  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 21:39:55.151  6886  6943 I jxcore-log: 
08-24 21:39:55.155  6886  6943 I jxcore-log: My device name is: LGE-LG-D855
08-24 21:39:55.155  6886  6943 I jxcore-log: 
,08-24 21:39:56.641  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1106185887] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:39:56.642  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1106185886] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-24 21:39:56.642  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-24 21:39:57.655  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-24 21:39:57.655  6886  6943 I jxcore-log: 
,08-24 21:39:58.316  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-24 21:39:58.316  6886  6943 I jxcore-log: 
,08-24 21:39:58.342  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-24 21:39:58.342  6886  6943 I jxcore-log: 
08-24 21:39:59.659  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1106182870] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:39:59.661  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1106182867] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:39:59.661  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-24 21:39:59.690  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-24 21:39:59.690  6886  6943 I jxcore-log: 
,08-24 21:39:59.917  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-24 21:39:59.917  6886  6943 I jxcore-log: 
,08-24 21:39:59.923  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-24 21:39:59.923  6886  6943 I jxcore-log: 
,08-24 21:39:59.929  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-24 21:39:59.929  6886  6943 I jxcore-log: 
08-24 21:39:59.945  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-24 21:39:59.945  6886  6943 I jxcore-log: 
,08-24 21:39:59.949  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-24 21:39:59.949  6886  6943 I jxcore-log: 
08-24 21:40:00.056  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 21:40:00.056  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 21:40:00.056  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 21:40:00.057  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-24 21:40:00.065  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 21:40:00.065  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-24 21:40:00.067  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-24 21:40:00.068  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 21:40:00.614  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-24 21:40:00.614  6886  6943 I jxcore-log: 
,08-24 21:40:00.628  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-24 21:40:00.628  6886  6943 I jxcore-log: 
08-24 21:40:00.637  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-24 21:40:00.637  6886  6943 I jxcore-log: 
,08-24 21:40:00.644  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-24 21:40:00.644  6886  6943 I jxcore-log: 
,08-24 21:40:00.691  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-24 21:40:00.691  6886  6943 I jxcore-log: 
,08-24 21:40:00.748  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-24 21:40:00.748  6886  6943 I jxcore-log: 
,08-24 21:40:00.756  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-24 21:40:00.756  6886  6943 I jxcore-log: 
,08-24 21:40:01.098  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-24 21:40:01.098  6886  6943 I jxcore-log: 
,08-24 21:40:01.116  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-24 21:40:01.116  6886  6943 I jxcore-log: 
,08-24 21:40:01.121  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-24 21:40:01.121  6886  6943 I jxcore-log: 
,08-24 21:40:01.127  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-24 21:40:01.127  6886  6943 I jxcore-log: 
08-24 21:40:01.141  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-24 21:40:01.141  6886  6943 I jxcore-log: 
,08-24 21:40:01.212  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-24 21:40:01.212  6886  6943 I jxcore-log: 
,08-24 21:40:01.225  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-24 21:40:01.225  6886  6943 I jxcore-log: 
,08-24 21:40:01.250  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-24 21:40:01.250  6886  6943 I jxcore-log: 
,08-24 21:40:01.262  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-24 21:40:01.262  6886  6943 I jxcore-log: 
08-24 21:40:01.277  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-24 21:40:01.277  6886  6943 I jxcore-log: 
,08-24 21:40:01.306  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-24 21:40:01.306  6886  6943 I jxcore-log: 
,08-24 21:40:01.311  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-24 21:40:01.311  6886  6943 I jxcore-log: 
,08-24 21:40:01.336  6886  6943 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-24 21:40:01.336  6886  6943 I jxcore-log: 
,08-24 21:40:01.345  6886  6943 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-24 21:40:01.346  6886  6943 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-24 21:40:01.346  6886  6943 I jxcore-log: 
08-24 21:40:02.680  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1106179848] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:40:02.683  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1106179845] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:40:02.684  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-24 21:40:05.707  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2412 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=4.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1106176822] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 21:40:05.710  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2412 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=4.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1106176819] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 21:40:05.710  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-24 21:40:06.382  1037  1539 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-24 21:40:06.383  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-24 21:40:06.385  1037  1539 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-24 21:40:06.395  1037  1539 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-24 21:40:06.397  1037  1539 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-24 21:40:06.399  1037  1539 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-24 21:40:08.736  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1106173793] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:40:08.739  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1106173789] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:40:08.740  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-24 21:40:11.766  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1106170763] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-24 21:40:11.770  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1106170759] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:40:11.770  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-24 21:40:14.797  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1106167731] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-24 21:40:14.800  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1106167728] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-24 21:40:14.800  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-24 21:40:16.407  6886  6943 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-24 21:40:16.407  6886  6943 I jxcore-log: 
,08-24 21:40:16.740  8930  8930 D AndroidRuntime: 
08-24 21:40:16.740  8930  8930 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-24 21:40:16.745  8930  8930 D AndroidRuntime: CheckJNI is OFF
08-24 21:40:16.870  8930  8930 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 21:40:16.881  1037  1097 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-24 21:40:16.881  1037  1097 I ActivityManager: Killing 6886:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-24 21:40:16.943  1037  1886 I WindowState: WIN DEATH: Window{318ba69d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 21:40:16.945  1037  1545 D WifiService: Client connection lost with reason: 4
08-24 21:40:16.948  1037  1886 D InputDispatcher: Window went away: Window{318ba69d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 21:40:17.109  1037  1097 I ActivityManager:   Force finishing activity ActivityRecord{6289cfe u0 com.test.thalitest/.MainActivity t6}
,08-24 21:40:17.148   351   365 E GBMv2   : DFP En is all cleared set to be enabled
,08-24 21:40:17.153  1037  1884 W ActivityManager: Spurious death for ProcessRecord{3f19904 6886:com.test.thalitest/u0a118}, curProc for 6886: null
08-24 21:40:17.154  1037  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-24 21:40:17.162  1037  1125 I ActivityManager:   Force finishing activity ActivityRecord{6289cfe u0 com.test.thalitest/.MainActivity t6 f}
,08-24 21:40:17.162  1037  1125 W ActivityManager: Duplicate finish request for ActivityRecord{6289cfe u0 com.test.thalitest/.MainActivity t6 f}
,08-24 21:40:17.196  2033  2033 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-24 21:40:17.197  1940  3987 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-24 21:40:17.198  1940  3987 D SplitWindowPolicy: topRunningActivity=ActivityInfo{26b15054 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-24 21:40:17.199  2033  2033 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-24 21:40:17.200  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-24 21:40:17.202  2033  2143 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-24 21:40:17.204  1940  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
,08-24 21:40:17.204  1940  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{34f0fbfd co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-24 21:40:17.207  1904  1904 D ActionManagerService: notifyUserLog: 1000003
08-24 21:40:17.208  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-24 21:40:17.208  3831  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-24 21:40:17.210  2033  2033 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-24 21:40:17.211  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-24 21:40:17.222  1037  1409 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 21:40:17.240  2504  2622 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 21:40:17.247  1996  1996 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-24 21:40:17.248  3831  3831 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-24 21:40:17.250  8128  8128 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-24 21:40:17.250  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-24 21:40:17.252  8377  8377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-24 21:40:17.254  4508  4508 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-24 21:40:17.254  4508  4508 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-24 21:40:17.254  4508  4508 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-24 21:40:17.254  4508  4508 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-24 21:40:17.254  4508  4508 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 21:40:17.255  4508  4508 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 21:40:17.255  4508  4508 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 21:40:17.255  4508  4508 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 21:40:17.255  4508  4508 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 21:40:17.255  4508  4508 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 21:40:17.256  4508  4508 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 21:40:17.257  4508  4508 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 21:40:17.291  2033  2033 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-24 21:40:17.304  1037  1885 V SIM_STK : Menu title from STK is T-Mobile
08-24 21:40:17.310  1604  1654 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-24 21:40:17.310  2033  2033 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-24 21:40:17.310  1604  1654 D KeyguardModel: createShortcutInfo...
08-24 21:40:17.313  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-24 21:40:17.315  3831  4471 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 21:40:17.315  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-24 21:40:17.318  1904  1904 D ActionManagerService: notifyUserLog: 1000004
08-24 21:40:17.318  3831  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-24 21:40:17.319  1604  1654 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-24 21:40:17.319  1604  1654 D KeyguardModel: createShortcutInfo...
08-24 21:40:17.323  1604  1654 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-24 21:40:17.324  1604  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 21:40:17.324  1604  1654 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-24 21:40:17.325  1604  1654 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 21:40:17.326  1604  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 21:40:17.326  1604  1654 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-24 21:40:17.327  1867  1867 D SplitUIManager: split_name #11 / not available #0
,08-24 21:40:17.328  1867  1867 D SplitUIService: removed split : 
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262123
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , display: false
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , animation: false }
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262287
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , display: false
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , animation: false }
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , create_time: 1471602816196
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , display: false
08-24 21:40:17.330  2033  2033 I GBoardWebViewUtils: , animation: false }
08-24 21:40:17.337  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-24 21:40:17.337  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-24 21:40:17.337  2033  8960 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-24 21:40:17.344  1604  1654 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-24 21:40:17.344  1604  1654 D KeyguardModel: createShortcutInfo...
,08-24 21:40:17.348  1037  2032 V SIM_STK : Menu title from STK is T-Mobile
08-24 21:40:17.348  1037  2032 V SIM_STK : Menu title from STK is T-Mobile
08-24 21:40:17.352  1604  1654 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-24 21:40:17.352  1604  1654 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 21:40:17.353  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-24 21:40:17.355  1604  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 21:40:17.357  1604  1654 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-24 21:40:17.367  1604  1654 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 21:40:17.367  1604  1654 D KeyguardModel: createShortcutInfo...
,08-24 21:40:17.377  1867  1867 D SplitUIManager: split_name #11 / not available #0
08-24 21:40:17.377  1867  1867 I SplitUIService: split app #11
08-24 21:40:17.378  1604  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 21:40:17.379  1604  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-24 21:40:17.379  1604  1654 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-24 21:40:17.379  1604  1654 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 21:40:17.386  1604  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 21:40:17.386  1604  1654 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-24 21:40:17.387  1604  1654 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 21:40:17.387  1604  1654 D KeyguardModel: createShortcutInfo...
,08-24 21:40:17.387  1037  1037 I art     : Explicit concurrent mark sweep GC freed 33539(1904KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.429ms total 196.546ms
08-24 21:40:17.356  1815  1815 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-24 21:40:17.402  4615  4615 I art     : Explicit concurrent mark sweep GC freed 15677(895KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 1.017ms total 127.071ms
,08-24 21:40:17.420  1037  1623 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-24 21:40:17.420  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-24 21:40:17.420  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-24 21:40:17.420  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-24 21:40:17.420  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-24 21:40:17.420  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-24 21:40:17.420  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 21:40:17.421  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-24 21:40:17.421  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-24 21:40:17.421  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-24 21:40:17.421  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 21:40:17.421  8128  8128 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-24 21:40:17.422  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-24 21:40:17.422  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-24 21:40:17.426  1037  1037 D administrator: Handling package changes for user 0
08-24 21:40:17.427  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 21:40:17.429  1604  1654 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-24 21:40:17.429  1604  1654 D KeyguardModel: createShortcutInfo...
08-24 21:40:17.430  2033  2033 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-24 21:40:17.432  2196  2196 I ConfigService: onCreate
08-24 21:40:17.432  2196  2196 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-24 21:40:17.436  1604  1654 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-24 21:40:17.436  1604  1654 D KeyguardModel: createShortcutInfo...
08-24 21:40:17.437  2196  2196 I ConfigService: onBind returning update interface
08-24 21:40:17.437  1815  1815 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-24 21:40:17.438  2196  2196 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-24 21:40:17.439  2196  2196 I ConfigService: onBind returning config service
08-24 21:40:17.439  1604  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 21:40:17.439  1604  1654 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-24 21:40:17.440  1604  1654 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-24 21:40:17.440  1604  1654 D KeyguardModel: createShortcutInfo...
08-24 21:40:17.441  1604  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 21:40:17.441  1604  1654 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-24 21:40:17.442  1604  1654 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 21:40:17.442  1604  1654 D KeyguardModel: createShortcutInfo...
08-24 21:40:17.443  1604  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 21:40:17.443  1604  1654 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-24 21:40:17.444  1604  1654 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 21:40:17.444  1604  1654 D KeyguardModel: createShortcutInfo...
08-24 21:40:17.447  1037  1995 V SIM_STK : Menu title from STK is T-Mobile
08-24 21:40:17.465  1604  1604 D KeyguardModel: handleShortcutListChanged...
,08-24 21:40:17.466  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-24 21:40:17.470  2196  2196 I ConfigService: onDestroy
08-24 21:40:17.481   342   453 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-24 21:40:17.484  3191  8966 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-24 21:40:17.487  1815  8965 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-24 21:40:17.495  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-24 21:40:17.498  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 21:40:17.500  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-24 21:40:17.501  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-24 21:40:17.502  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-24 21:40:17.503  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-24 21:40:17.522  7233  7233 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-24 21:40:17.524  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-24 21:40:17.524  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 21:40:17.525  1037  1113 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2f2c1c u0 com.lge.launcher2/.Launcher t5} time:434329
08-24 21:40:17.526  2033  2218 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-24 21:40:17.526  2033  2218 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-24 21:40:17.527  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-24 21:40:17.527  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 21:40:17.528  1037  1037 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-24 21:40:17.529  1037  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-24 21:40:17.532  6040  8972 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-24 21:40:17.540  2332  8973 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-24 21:40:17.542  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-24 21:40:17.543  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-24 21:40:17.543  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-24 21:40:17.551  2033  2033 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-24 21:40:17.564  1037  2050 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8976 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-24 21:40:17.566  2600  2600 D [Concierge]Service: onStartCommand(). Type : 8
08-24 21:40:17.566  2600  2600 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-24 21:40:17.566  2600  2600 D [Concierge]Service: Update widget ID : 11
08-24 21:40:17.568  2033  2033 D [Concierge]WidgetView: change position of spinner
08-24 21:40:17.569  2033  2033 I [Concierge]WidgetView: initWebView(). Time : 1472067617569
08-24 21:40:17.570  2600  2600 D [Concierge]Service: onStartCommand(). Type : 0
08-24 21:40:17.581  1815  8975 W GmsApplication: Using Auth Proxy for data requests.
,08-24 21:40:17.584  1815  8975 W GmsApplication: Using Auth Proxy for data requests.
08-24 21:40:17.585  2033  2033 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 190693310
08-24 21:40:17.586  2033  2033 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-24 21:40:17.586  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-24 21:40:17.588  1815  8985 I PeopleContactsSync: CP2 sync disabled
08-24 21:40:17.589  2033  2033 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@fe6c243
08-24 21:40:17.589  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-24 21:40:17.590  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-24 21:40:17.590  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 21:40:17.593  1815  4760 I Icing   : doRemovePackageData com.test.thalitest
,08-24 21:40:17.595  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-24 21:40:17.595  2033  2033 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-24 21:40:17.596  2033  2033 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-24 21:40:17.596  2033  2033 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472067211567, New one : 1472067617569
08-24 21:40:17.596  2033  2033 D [Concierge]WidgetView: Unregister all receivers
08-24 21:40:17.596  2033  2033 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-24 21:40:17.597  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 21:40:17.599  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-24 21:40:17.600  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-24 21:40:17.601  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-24 21:40:17.602  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-24 21:40:17.603  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-24 21:40:17.603  8976  8976 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 21:40:17.604  8976  8976 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 21:40:17.604  8976  8976 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 21:40:17.605  8976  8976 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 21:40:17.610  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 21:40:17.611  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-24 21:40:17.642  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-24 21:40:17.650  2033  2033 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-24 21:40:17.650  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-24 21:40:17.652  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-24 21:40:17.675  2033  2033 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@369b75eb time:434479
,08-24 21:40:17.684  8976  8976 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-24 21:40:17.685  1037  1125 I art     : Explicit concurrent mark sweep GC freed 8501(597KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.639ms total 271.144ms
08-24 21:40:17.692  8976  8976 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-24 21:40:17.715  8976  8976 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-24 21:40:17.734  8976  8976 D LgDataFeature: LgDataFeature() Constructor: none
08-24 21:40:17.734  8976  8976 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 21:40:17.753  1815  1827 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-24 21:40:17.754  1815  1827 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-24 21:40:17.755  1815  1827 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-24 21:40:17.760  1815  8998 I art     : Explicit concurrent mark sweep GC freed 48066(3MB) AllocSpace objects, 28(448KB) LOS objects, 34% free, 30MB/46MB, paused 375us total 34.364ms
,08-24 21:40:17.775  8930  8930 D AndroidRuntime: Shutting down VM
,08-24 21:40:17.802  2033  2033 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-24 21:40:17.810  1037  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=9002 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-24 21:40:17.819  8976  8976 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-24 21:40:17.826  1037  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1106164702] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:40:17.826  1037  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1106164702] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 21:40:17.826  1037  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-24 21:40:17.830  1037  2050 I ActivityManager: Killing 8310:com.lge.formmanager/u0a26 (adj 15): empty #17
08-24 21:40:17.853  2033  2884 I GBoardtInterface: onReloaded()
,08-24 21:40:17.854  2033  2033 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-24 21:40:17.916  1996  1996 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-24 21:40:17.916  1996  1996 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-24 21:40:17.917  1996  1996 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-24 21:40:17.917  1037  1576 W libprocessgroup: failed to open /acct/uid_10026/pid_8310/cgroup.procs: No such file or directory
,08-24 21:40:17.924  3831  3846 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 21:40:17.926  8377  8377 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-24 21:40:17.929  3831  4471 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 21:40:17.929  1037  1095 W InputMethodInfo: Duplicated subtype definition found: , voice
08-24 21:40:17.956  1037  1995 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=9021 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-24 21:40:17.958  1037  1977 I ActivityManager: Killing 8539:com.android.chrome/u0a57 (adj 15): empty #17
08-24 21:40:18.046  1037  1886 W libprocessgroup: failed to open /acct/uid_10057/pid_8539/cgroup.procs: No such file or directory
,08-24 21:40:18.055  1904  1904 D ActionManagerService: notifyUserLog: 1000001
08-24 21:40:18.056  3831  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,08-24 21:40:18.057  3831  4477 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-24 21:40:18.057  1037  1095 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 21:40:18.060  1904  1904 D ActionManagerService: notifyUserLog: 1000001
08-24 21:40:18.061  3831  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-24 21:40:18.061  3831  4477 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-24 21:40:18.061  3831  4477 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-24 21:40:18.061  3831  4477 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-24 21:40:18.061  3831  3846 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 21:40:18.063  1037  1095 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-24 21:40:18.063  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-24 21:40:18.063  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-24 21:40:18.065  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-24 21:40:18.065  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-24 21:40:18.067  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-24 21:40:18.067  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-24 21:40:18.074  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-24 21:40:18.093  9021  9021 E SQLiteDatabase: Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 21:40:18.093  9021  9021 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: Unable to open database for writing.
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 21:40:18.094  9021  9021 E Lifetra,ckerProvider2: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.os.Looper.loop(Looper.java:135)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 21:40:18.094  9021  9021 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-24 21:40:18.105  9021  9021 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-24 21:40:18.105  9021  9021 W LG Account v2.2: No ProfileInfo entries
08-24 21:40:18.105  9021  9021 I LG Account v2.2: isEnabled: false
08-24 21:40:18.105  9021  9021 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-24 21:40:18.105  9021  9021 I Feature : [Lifetracker]Country: EU
08-24 21:40:18.105  9021  9021 I Feature : [Lifetracker]Operator: OPEN
08-24 21:40:18.105  9021  9021 I Feature : [Lifetracker]Ranking support: false
08-24 21:40:18.105  9021  9021 I Feature : [Lifetracker]Comfort support: false
08-24 21:40:18.105  9021  9021 I Feature : [Lifetracker]Accessory: true
08-24 21:40:18.105  9021  9021 I Feature : [Lifetracker]Health device: true
08-24 21:40:18.105  9021  9021 I Feature : [Lifetracker]Extra Pedometer: false
08-24 21:40:18.105  9021  9021 I Feature : [Lifetracker]Blood glucose device: false
08-24 21:40:18.105  9021  9021 I Feature : [Lifetracker]Device Number: 3
08-24 21:40:18.106  9021  9021 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-24 21:40:18.135  1037  2050 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=9042 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a

```
