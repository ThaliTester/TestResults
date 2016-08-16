#### Test 81418577e915171_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-16 13:19:54.124  1602  1602 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-16 13:19:54.125  1602  1602 I [SystemUI]LGPowerUI: On Skip Timer : true
,--------- beginning of system
08-16 13:19:54.148  1049  1542 D WifiController: battery changed pluggedType: 2
08-16 13:19:54.153  1602  1602 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
08-16 13:19:54.153  1602  1602 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-16 13:19:54.155  1966  2142 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-16 13:19:54.155  1966  2142 D LEDHandler: Battery Level Remaining: 100%
08-16 13:19:54.155  1966  2142 D LEDHandler: Battery Temp: 283, mChargingStatus=5, mChargingStop=false
08-16 13:19:54.156  1602  1602 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-16 13:19:54.159  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:19:54.159  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:19:54.160  3892  4007 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 13:19:54.166  6501  6501 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 13:19:54.415  6616  6616 D AndroidRuntime: 
08-16 13:19:54.415  6616  6616 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 13:19:54.421  6616  6616 D AndroidRuntime: CheckJNI is OFF
08-16 13:19:54.544  6616  6616 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-16 13:19:54.549  1049  2045 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 13:19:54.558  1966  3397 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-16 13:19:54.562  1049  2045 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-16 13:19:54.563  1049  2045 D ActivityManager: setTaskToReturnTo : TaskRecord{3ec10612 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 13:19:54.563  1049  2045 D ActivityManager: setTaskToReturnTo : TaskRecord{3ec10612 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 13:19:54.565  1049  2045 D WindowStateEx: AppWindowTokenEx init.. 
08-16 13:19:54.565   331   344 E GBMv2   : DFP En is all cleared set to be enabled
08-16 13:19:54.604  1049  2045 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6636 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 13:19:54.606  6616  6616 D AndroidRuntime: Shutting down VM
08-16 13:19:54.647  1966  3397 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-16 13:19:54.648  1966  3397 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1ab6b098 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 13:19:54.648  1966  1989 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-16 13:19:54.648  1966  1989 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3727b0f1 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 13:19:54.689  6636  6636 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-16 13:19:54.787  6636  6636 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-16 13:19:54.796  6636  6636 I LibraryLoader: Loading: webviewchromium
08-16 13:19:54.799  6636  6636 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9037-9041)
08-16 13:19:54.799  6636  6636 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 13:19:54.815  6636  6636 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cce3a06}
08-16 13:19:54.816  6636  6636 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 13:19:54.817  6636  6636 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 13:19:54.828  6636  6636 I BrowserStartupController: Initializing chromium process, renderers=0
,08-16 13:19:54.829  6636  6636 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 13:19:54.840  6636  6636 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-16 13:19:54.841  6636  6636 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-16 13:19:54.841  6636  6636 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-16 13:19:54.843   310  1785 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
08-16 13:19:54.847  1049  1131 D BluetoothManagerService: Message: 20
08-16 13:19:54.848  1049  1131 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3266220c:true
08-16 13:19:54.853  6636  6636 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:19:54.853  6636  6636 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:19:54.853  6636  6636 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:19:54.853  6636  6636 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:19:54.853  6636  6636 I Adreno-EGL: Remote Branch: 
08-16 13:19:54.853  6636  6636 I Adreno-EGL: Local Patches: 
08-16 13:19:54.853  6636  6636 I Adreno-EGL: Reconstruct Branch: 
,08-16 13:19:54.923  6636  6666 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-16 13:19:54.927  6636  6636 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-16 13:19:54.942  6636  6636 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 13:19:54.946  6636  6636 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 13:19:54.949  6636  6636 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-16 13:19:54.952  6636  6636 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-16 13:19:54.952  6636  6636 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-16 13:19:54.965  6636  6636 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-16 13:19:54.971  6636  6636 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 13:19:54.971  6636  6636 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 13:19:55.006  6636  6678 D OpenGLRenderer: Render dirty regions requested: true
08-16 13:19:55.006  6636  6678 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 13:19:55.020  6636  6678 D OpenGLRenderer: Enabling debug mode 0
,08-16 13:19:55.028  6636  6636 D Atlas   : Validating map...
08-16 13:19:55.034  1049  2069 D SplitWindow: check instance of lgWin Window{30aeb0e6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 13:19:55.064  6636  6676 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:19:55.064  6636  6676 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 13:19:55.163  6636  6636 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@735408d time:189405
,08-16 13:19:55.165  1049  1132 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +518ms (total +599ms)
08-16 13:19:55.166  1049  1132 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{bf541e3 u0 com.test.thalitest/.MainActivity t6} time:189409
08-16 13:19:55.274  6636  6636 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-16 13:19:55.274  6636  6636 I chromium: 
,08-16 13:19:55.295  6636  6636 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 13:19:55.365  6636  6676 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-16 13:19:55.365  6636  6676 I chromium: 
,08-16 13:19:55.488  6636  6689 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435169792
,08-16 13:19:55.508  6636  6689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 13:19:55.508  6636  6689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 13:19:55.508  6636  6689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 13:19:55.508  6636  6689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 13:19:55.508  6636  6689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 13:19:55.508  6636  6689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0f8fc1 added. We now have 1 listener(s)
,08-16 13:19:55.519  1049  1984 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:19:55.522  6636  6689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-16 13:19:55.523  6636  6689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-16 13:19:55.528  6636  6689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:19:55.528  6636  6689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:19:55.537  6636  6689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 13:19:55.537  6636  6689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 13:19:55.537  6636  6689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 13:19:55.537  6636  6689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-16 13:19:55.537  6636  6689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 13:19:55.537  6636  6689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 13:19:55.537  6636  6689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 13:19:55.537  6636  6689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 13:19:55.537  6636  6689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 13:19:55.537  6636  6689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 13:19:55.537  6636  6689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 13:19:55.537  6636  6689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 13:19:55.537  6636  6689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 13:19:55.537  6636  6689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-16 13:19:55.537  6636  6689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d38754 added. We now have 1 listener(s)
08-16 13:19:55.537  6636  6689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:19:55.544  1049  1542 D WifiService: New client listening to asynchronous messages
08-16 13:19:55.547  6636  6689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:19:55.548  6636  6689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 13:19:55.549  6636  6689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 13:19:55.550  6636  6689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 13:19:55.550  6636  6689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 13:19:55.558  6636  6689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:19:55.559  1049  1644 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:19:55.560  6636  6689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-16 13:19:55.572  6636  6689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-16 13:19:55.575  6636  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:19:55.575  6636  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:19:55.575  6636  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:19:55.575  6636  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:19:55.575  6636  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:19:55.575  6636  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:19:55.575  6636  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:19:55.575  6636  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:19:55.575  6636  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 13:19:55.575  6636  6689 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:19:55.577  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:19:55.580  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:19:55.581  6636  6689 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 13:19:55.596   331   346 E GBMv2   : DFP En is all cleared set to be enabled
08-16 13:19:55.596   331   346 E GBMv2   : Set value is all cleared set the max
08-16 13:19:55.596   331   346 I GBMv2   : DFP Enabled. Ignore VFP set
,08-16 13:19:55.622  6636  6636 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 13:19:56.370  6636  6692 W jxcore-log: Initializing JXcore engine
08-16 13:19:56.370  6636  6692 W jxcore-log: JXcore engine is ready
,08-16 13:19:56.437  6692  6692 W Thread-767: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8374]" dev="sockfs" ino=8374 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-16 13:19:56.437  6692  6692 W Thread-767: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-16 13:19:56.437  6692  6692 W Thread-767: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9598]" dev="sockfs" ino=9598 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 13:19:56.437  6692  6692 W Thread-767: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-16 13:19:56.437  6692  6692 W Thread-767: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31949]" dev="sockfs" ino=31949 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-16 13:19:56.478  6636  6692 W jxcore-log: Starting JXcore engine
,08-16 13:19:56.599  6636  6692 W jxcore-log: Platform android
08-16 13:19:56.599  6636  6692 W jxcore-log: 
,08-16 13:19:56.600  6636  6692 W jxcore-log: Process ARCH arm
08-16 13:19:56.600  6636  6692 W jxcore-log: 
08-16 13:19:56.809  6636  6692 I jxcore-log: JXcore Cordova bridge is ready!
08-16 13:19:56.809  6636  6692 I jxcore-log: 
08-16 13:19:56.810  6636  6692 W jxcore-log: JXcore engine is started
,08-16 13:19:56.816  6636  6689 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-16 13:19:56.819  6636  6636 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-16 13:20:00.054  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 13:20:00.054  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 13:20:00.054  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 13:20:00.054  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
08-16 13:20:00.055  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 13:20:00.055  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-16 13:20:00.055  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-16 13:20:00.056  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 13:20:06.751  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 13:20:06.751  6636  6692 I jxcore-log: 
08-16 13:20:06.753  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 13:20:06.753  6636  6692 I jxcore-log: 
,08-16 13:20:06.758  6636  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:20:06.758  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:06.758  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:06.758  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:06.758  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:06.758  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:06.758  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:20:06.758  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:20:06.761  6636  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:06.763  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 13:20:06.763  6636  6692 I jxcore-log: 
08-16 13:20:06.765  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 13:20:06.765  6636  6692 I jxcore-log: 
08-16 13:20:07.091  6636  6692 D ExecuteNativeTests: Running unit tests
,08-16 13:20:07.177  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 13:20:07.177  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf added. We now have 2 listener(s)
,08-16 13:20:07.177  1049  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:07.180  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:20:07.180  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:20:07.180  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 13:20:07.181  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:20:07.181  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c added. We now have 2 listener(s)
08-16 13:20:07.181  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:20:07.182  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:20:07.184  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:20:07.188  6636  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:20:07.188  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:07.188  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:07.188  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:07.188  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:07.188  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:07.188  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:20:07.188  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:20:07.190  6636  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:07.190  6636  6692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:20:07.192  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 13:20:07.193  6636  6692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 13:20:07.193  6636  6692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 13:20:07.194  6636  6692 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 13:20:07.194  6636  6692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 13:20:07.194  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 13:20:07.194  6636  6692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 13:20:07.194  6636  6692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 13:20:07.195  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.196  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:20:07.200  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.200  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.201  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.201  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.201  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:20:07.201  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:20:07.201  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:07.201  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf removed from the list
08-16 13:20:07.201  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.201  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c removed from the list
08-16 13:20:07.201  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.201  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.202  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.202  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.202  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.202  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.203  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.203  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.204  6636  6692 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 13:20:07.205  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.205  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.205  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.205  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.205  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.205  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.205  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.205  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.205  6636  6692 E org.thaliproject.p2p.btconnectorli,b.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.205  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.205  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.205  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.205  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.206  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.206  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.206  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.206  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.206  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.210  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 13:20:07.210  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 13:20:07.210  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 13:20:07.210  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 13:20:07.210  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 13:20:07.210  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 13:20:07.210  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 13:2,0:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 13:20:07.211  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.211  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.211  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.211  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.211  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.211  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.211  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.211  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.211  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list,
08-16 13:20:07.211  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.211  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.211  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.211  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.211  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.212  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.212  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.212  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.212  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.212  6636  6692 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 13:20:07.214  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:20:07.218  6636  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:20:07.218  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:07.218  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:07.218  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:07.218  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:07.218  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:07.218  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:20:07.218  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:20:07.220  6636  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:07.220  6636  6692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:20:07.221  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:07.221  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:20:07.222  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:07.222  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:20:07.223  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:20:07.223  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:20:07.223  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:20:07.226  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 13:20:07.227  1049  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:07.232  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 13:20:07.238  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 13:20:07.240  6636  6692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 13:20:07.242  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:20:07.242  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:20:07.244  6636  6692 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 13:20:07.244  6636  6692 I io.jxcore.node.ConnectionHelper: start: OK
08-16 13:20:07.247  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.247  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.248  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.248  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.248  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.248  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:20:07.248  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.248  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.248  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.248  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.248  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.248  6636  6692 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 13:20:07.250  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:20:07.252  6636  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:20:07.252  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:07.252  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:07.252  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:07.252  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:07.252  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:07.252  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:20:07.252  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:20:07.254  6636  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:07.254  6636  6692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:20:07.254  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:20:07.254  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:20:07.254  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:20:07.254  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:20:07.254  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:20:07.255  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:07.257  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:07.260  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:20:07.260  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:20:07.261  6636  6692 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 13:20:07.261  6636  6692 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 13:20:07.263  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.263  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.263  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.263  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.263  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.263  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:20:07.263  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.263  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.263  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.263  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.263  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.264  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.264  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.265  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.265  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.267  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:07.267  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:07.267  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.267  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.267  6636  6692 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 13:20:07.269  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:20:07.271  6636  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:20:07.271  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:07.271  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:07.271  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:07.271  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:07.271  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:07.271  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:20:07.271  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:20:07.272  6636  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:07.272  6636  6692 D io.jxcore.node.ConnectivityM,onitor: start: OK
08-16 13:20:07.273  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:20:07.273  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:20:07.273  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:20:07.273  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:20:07.273  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:20:07.276  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:07.278  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:07.278  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:20:07.279  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:20:07.280  6636  6692 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 13:20:07.280  6636  6692 I io.jxcore.node.ConnectionHelper: start: OK
08-16 13:20:07.280  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.280  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.280  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.281  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.281  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.281  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.281  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.281  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.281  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:20:07.281  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.281  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.281  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.281  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.281  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.282  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.282  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.282  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.282  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.283  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:07.283  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:07.283  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.283  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.283  6636  6692 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 13:20:07.283  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.283  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.284  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.285  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.285  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.285  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.285  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.285  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.285  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.285  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.285  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.285  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.285  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.285  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.286  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.286  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.287  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:07.287  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:07.287  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.287  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.288  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 13:20:07.288  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.289  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.289  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.289  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.289  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.289  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.289  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.289  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.289  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.289  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.289  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.289  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.289  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.289  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.290  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.290  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.291  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:07.291  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:07.291  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.291  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.291  6636  6692 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 13:20:07.292  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.292  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.292  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.292  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.292  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.292  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.292  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.292  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.292  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.292  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.292  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.292  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.292  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.292  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.293  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.293  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.294  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:07.294  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:07.294  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.294  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.295  6636  6692 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 13:20:07.295  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.295  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.295  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.295  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.295  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.295  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.295  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.295  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.295  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.295  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.295  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.295  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.295  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.295  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.298  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.298  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:20:07.300  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:07.300  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:07.300  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.300  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.301  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 13:20:07.303  6636  6692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 13:20:07.303  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 13:20:07.303  6636  6692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 13:20:07.304  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 13:20:07.304  6636  6692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 13:20:07.304  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.304  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.304  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.305  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.305  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.305  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.305  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.305  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.305  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.305  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.306  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.306  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.306  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.306  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.307  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.307  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.307  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:07.307  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:07.307  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.307  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.308  6636  6692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 13:20:07.308  6636  6692 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 13:20:07.308  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 13:20:07.311  6636  6692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 13:20:07.311  6636  6692 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 13:20:07.311  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 13:20:07.312  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 13:20:07.312  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 13:20:07.312  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 13:20:07.312  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 13:20:07.312  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 13:20:07.312  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 13:20:07.312  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 13:20:07.312  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 13:20:07.312  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 13:20:07.312  6636  6692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 13:20:07.312  6636  6692 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 13:20:07.312  6636  6692 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 13:20:07.312  6636  6692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 13:20:07.312  6636  6692 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 13:20:07.312  6636  6692 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 13:20:07.312  6636  6692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 13:20:07.312  6636  6692 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 13:20:07.312  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 13:20:07.317  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 13:20:07.318  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 13:20:07.318  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 13:20:07.319  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 13:20:07.319  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 13:20:07.319  6636  6692 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 13:20:07.320  6636  6692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 13:20:07.320  6636  6692 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 13:20:07.320  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.320  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.321  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.321  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.321  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.321  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.322  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 13:20:07.322  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.322  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.322  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.322  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.322  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.322  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.322  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.322  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.323  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.323  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.323  6636  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 831
08-16 13:20:07.324  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:07.324  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:07.324  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.324  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.325  6636  6692 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 13:20:07.325  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.325  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.325  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.325  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.325  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.325  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.325  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.325  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.325  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.325  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.325  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.326  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.326  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.326  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.327  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.327  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.328  6636  6693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 831)
08-16 13:20:07.328  6636  6693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 831)
08-16 13:20:07.329  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:07.329  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:07.329  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.329  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.330  6636  6692 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 13:20:07.331  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.331  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.331  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.331  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.331  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.331  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.332  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.332  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.332  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.332  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.332  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.332  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.332  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.332  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.333  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.333  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.333  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:07.333  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:07.333  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.333  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.334  6636  6692 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 13:20:07.334  6636  6692 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 13:20:07.334  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 13:20:07.334  6636  6692 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 13:20:07.334  6636  6692 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 13:20:07.334  6636  6692 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 13:20:07.334  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 13:20:07.334  6636  6692 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 13:20:07.334  6636  6692 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 13:20:07.334  6636  6692 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 13:20:07.334  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 13:20:07.335  6636  6692 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 13:20:07.335  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.335  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.335  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.335  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.335  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.335  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.335  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.335  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.335  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.335  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.336  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.336  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.336  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.336  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.336  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.336  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.337  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:07.337  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:07.337  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.337  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.337  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.337  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.337  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.338  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.338  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.338  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.338  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.338  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.338  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.338  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.338  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.338  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.338  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.338  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.338  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.338  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.338  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.338  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.338  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.338  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.338  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.338  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.338  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.338  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.338  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.338  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.338  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.338  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.338  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:20:07.341  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.341  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.342  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:07.342  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:07.342  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.342  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.345  6636  6692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 13:20:07.345  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:20:07.346  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 13:20:07.347  6636  6692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 13:20:07.347  6636  6692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 13:20:07.347  6636  6636 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 13:20:07.347  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 13:20:07.347  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 13:20:07.349  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.349  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 13:20:07.349  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 13:20:07.349  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 13:20:07.349  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.349  6636  6692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 13:20:07.349  6636  6636 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 13:20:07.349  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.349  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.349  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 13:20:07.349  6636  6692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 13:20:07.349  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 13:20:07.350  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 13:20:07.350  1049  1065 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:07.351  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:07.351  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:07.351  6636  6692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 13:20:07.351  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.351  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.352  6636  6695 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:20:07.353  3892  3914 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-16 13:20:07.354  6636  6692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:20:07.354  6636  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 13:20:07.354  6636  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 13:20:07.354  6636  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 13:20:07.355  6636  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:20:07.355  6636  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:20:07.355  6636  6636 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:20:07.355  6636  6636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 13:20:07.356  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.356  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.356  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.356  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.356  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.356  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.356  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.356  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.356  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.356  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.356  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.356  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.356  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.356  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.356  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.357  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.357  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.357  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.357  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.358  6636  6692 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 13:20:07.358  6636  6692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 13:20:07.358  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 13:20:07.359  6636  6692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 13:20:07.360  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.360  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.360  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.360  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.360  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.360  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.360  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.360  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.360  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.360  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.360  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.360  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.360  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.360  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.361  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.361  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.361  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.361  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.362  1049  1758 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:07.362  1049  2045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:07.363  1049  2069 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:07.363  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.364  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.364  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.364  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.364  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.364  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.364  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.364  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.364  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.364  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.364  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.364  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.364  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.364  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.365  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.365  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.365  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.365  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.367  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:07.367  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:07.367  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:07.368  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:07.368  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.368  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.368  6636  6692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a11f0bf not in the list
08-16 13:20:07.371  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.372  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.372  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:07.372  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.372  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.372  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:07.372  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:07.372  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:07.372  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:07.372  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:07.372  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7e38c not in the list
08-16 13:20:07.374  6636  6692 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 13:20:07.374  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 13:20:07.374  6636  6692 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 13:20:07.374  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 13:20:07.374  6636  6692 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 13:20:07.374  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 13:20:07.376  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 13:20:07.376  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 13:20:07.376  6636  6692 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 13:20:07.376  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 13:20:07.377  6636  6692 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 13:20:07.377  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 13:20:07.377  6636  6692 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 13:20:07.377  6636  6692 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 13:20:07.378  6636  6692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 13:20:07.378  6636  6692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 13:20:07.378  6636  6692 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 13:20:07.378  6636  6692 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 13:20:07.379  6636  6692 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 13:20:07.379  6636  6692 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 13:20:07.380  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:20:07.380  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30be6f8d added. We now have 2 listener(s)
08-16 13:20:07.380  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:20:07.381  6636  6692 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 13:20:07.381  1049  1644 D WifiServiceImplEx: setWifiEnabled: true pid=6636, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 13:20:07.382  1049  1644 D WifiService: setWifiEnabled: true pid=6636, uid=10118
08-16 13:20:07.382  1049  1644 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 13:20:07.383  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:20:07.383  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b20a542 added. We now have 3 listener(s)
08-16 13:20:07.383  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:20:07.386  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 13:20:07.386  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@124ca953 added. We now have 4 listener(s)
08-16 13:20:07.386  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:20:07.387  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:20:07.387  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f6d9290 added. We now have 5 listener(s)
08-16 13:20:07.388  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:20:07.389  1049  2111 D WifiServiceImplEx: setWifiEnabled: false pid=6636, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 13:20:07.389  1049  2111 D WifiService: setWifiEnabled: false pid=6636, uid=10118
08-16 13:20:07.390  1049  2111 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:20:07.399  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:20:07.399  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 13:20:07.399  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-16 13:20:07.400  1049  1536 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 13:20:07.400  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 13:20:07.400  1049  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 13:20:07.401  1049  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 13:20:07.401  1049  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 13:20:07.401  1049  1536 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 13:20:07.401  1049  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 13:20:07.401  1049  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 13:20:07.402  1049  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 13:20:07.402  1049  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 13:20:07.403  1049  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:07.403  1049  2018 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@16a0c621 mBinding = false
08-16 13:20:07.407  1049  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 13:20:07.407  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 13:20:07.407  2642  2642 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 13:20:07.407  1049  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.407  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.407  1049  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 13:20:07.407  1049  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 13:20:07.408  1049  1536 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:20:07.408  1049  2815 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.408   306   907 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:20:07.421  1049  1963 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-16 13:20:07.425  1049  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-4ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.425  1049  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.425  1049  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 13:20:07.425  1049  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.425  1049  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 13:20:07.427  1049  1535 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.427  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.427  1049  1535 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3b06f614
08-16 13:20:07.427  1049  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 13:20:07.428  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-16 13:20:07.428  1049  1543 D ConnectivityService: ignoring duplicate network state non-change
08-16 13:20:07.428  1049  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:07.428  1049  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-16 13:20:07.428  1049  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:07.429  1049  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:07.429  1049  1536 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 13:20:07.429  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:07.430  1966  1966 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-16 13:20:07.433  1049  1535 D LGWifiP2pService: P2pDisablingState
08-16 13:20:07.433  1049  1535 D LGWifiP2pService: P2pDisablingState{ when=-6ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.433  1049  1535 D LGWifiP2pService: p2p socket connection lost
08-16 13:20:07.433  1049  1535 D LGWifiP2pService: P2pDisabledState
08-16 13:20:07.434  1049  1131 D BluetoothManagerService: Message: 2
08-16 13:20:07.434  1049  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 13:20:07.434  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 13:20:07.434  2642  2642 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 13:20:07.435  1049  1131 D BluetoothManagerService: Sending off request.
08-16 13:20:07.435  3892  3914 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 13:20:07.435  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:07.435  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 13:20:07.436  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-16 13:20:07.436  3892  3974 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 13:20:07.436  3892  3974 D BluetoothAdapterProperties: Setting state to 13
08-16 13:20:07.436  3892  3974 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 13:20:07.436  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:07.436  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:07.436  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 13:20:07.436  1049  1049 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 13:20:07.436  1049  1049 D RttService: SCAN_AVAILABLE : 1
08-16 13:20:07.436  3892  3974 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 13:20:07.436  3892  3974 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 13:20:07.437  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:20:07.437  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 13:20:07.437  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-16 13:20:07.439  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:20:07.429  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:07.442  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:07.447  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:07.447  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:07.451  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-16 13:20:07.452  1966  1966 D WfdsService: WifiP2pState is changed : false
08-16 13:20:07.452  1966  2321 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 13:20:07.452  1966  2321 D WfdsService: Set the WFDS Monitor: false
08-16 13:20:07.453  1966  2321 D WfdsMonitor: WFDS Monitor is stopped
08-16 13:20:07.453  1966  2321 D WfdsService: STATE : WfdsDisabledState - enter
08-16 13:20:07.453  1966  2723 D CtrlSupplicant: Received on exit socket, terminate
08-16 13:20:07.454  1966  2723 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 13:20:07.454  1966  2723 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 13:20:07.454  1966  2723 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 13:20:07.455  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:07.455  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:07.455  1966  2321 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 13:20:07.455  1966  2324 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 13:20:07.456  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:07.457  1049  1555 D RttService: EnabledState got{ when=-22ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.458  1049  1131 D BluetoothManagerService: Message: 60
08-16 13:20:07.458  1049  1535 D LGWifiP2pService: P2pDisabledState{ when=-25ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.458  1049  1131 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 13:20:07.458  1049  1131 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 13:20:07.458  1049  1535 D LGWifiP2pService: DefaultState{ when=-25ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.459  1049  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 13:20:07.459  1049  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 13:20:07.459  1049  1554 D WifiScanningService: DefaultState got{ when=-24ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.459  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:07.459  6636  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:20:07.459  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:07.459  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:07.459  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:07.459  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:20:07.459  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:07.459  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:07.459  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:20:07.459  1049  1536 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:20:07.460  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:07.460  6636  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-F,i: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:20:07.460  6636  6692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:20:07.461  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:07.461  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:07.462  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:07.464  3892  3892 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:07.465  3892  3892 D BluetoothMapService: STATE_TURNING_OFF
08-16 13:20:07.465  3892  3892 V BluetoothMapService: Handler(): got msg=4
08-16 13:20:07.465  3892  3892 D BluetoothMapService: MAP Service closeService in
08-16 13:20:07.465  3892  3892 D BluetoothMapMasInstance: MAP Service shutdown
,08-16 13:20:07.465  3892  4242 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 13:20:07.465  3892  4242 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:20:07.465  3892  4242 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 13:20:07.465  3892  4242 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 13:20:07.465  3892  4242 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 13:20:07.465  3892  4242 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 13:20:07.465  3892  4242 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 13:20:07.465  3892  4242 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 13:20:07.466  3892  3892 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 13:20:07.466  3892  3892 V BluetoothMapService: MAP Service closeService out
08-16 13:20:07.466  3892  3892 V BtOppService: Receiver DISABLED_ACTION 
08-16 13:20:07.466  3892  3892 I BtOppRfcommListener: stopping Accept Thread
08-16 13:20:07.466  3892  3892 V BtOppRfcommListener: close mBtServerSocket
08-16 13:20:07.466  3892  3892 V BtOppRfcommListener: waiting for thread to terminate
08-16 13:20:07.467  3892  4275 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:20:07.467  3892  4275 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 13:20:07.467  3892  3892 V BtOppRfcommListener: done waiting for thread to terminate
08-16 13:20:07.468  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:07.468  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:20:07.468  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:07.468  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:07.468  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:07.468  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:20:07.468  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:07.468  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:07.468  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:20:07.469  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:07.469  6636  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:20:07.470  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:07.471  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 13:20:07.472   306   907 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:20:07.472  1049  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 13:20:07.472  1049  1543 D DSQN    : disableDataServiceNotify
08-16 13:20:07.473   306  6716 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 13:20:07.473  1049  1543 D DSQN    : stop dsqn bin
08-16 13:20:0,7.473  1049  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 13:20:07.474  1049  1129 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 13:20:07.488  1049  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 13:20:07.488  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:07.488  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:07.488  1049  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:07.488  1049  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 13:20:07.488  1049  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.488  1049  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.489  1049  2810 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 13:20:07.489  1049  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 13:20:07.489  1049  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 13:20:07.489  1049  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-16 13:20:07.492  1602  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 13:20:07.505  1049  1124 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6717 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 13:20:07.506  3892  3892 V BtOppService: onDestroy
08-16 13:20:07.507  1049  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:07.507  1049  1536 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 13:20:07.507  1049  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 13:20:07.508  1049  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:07.508  1049  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 13:20:07.508  1049  1536 D WifiNative-p2p0: TERMINATE: returned true
08-16 13:20:07.508  1049  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:07.508  1049  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:20:07.508  1049  1536 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:20:07.508  1049  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 13:20:07.508  1049  1543 D NetworkManagementService: Removing idletimer
08-16 13:20:07.508  1049  1536 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:07.508  1049  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:20:07.508  1049  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:07.510  1876  1876 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:07.510  1876  1876 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 13:20:07.511  1049  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 13:20:07.511  1049  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 13:20:07.513  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 13:20:07.513  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:07.515  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 13:20:07.519  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-16 13:20:07.519  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:07.519  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:07.519  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 13:20:07.519  1049  1049 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 13:20:07.519  1049  1049 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 13:20:07.519  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 13:20:07.520  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:07.520  1049  1049 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 13:20:07.520  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 13:20:07.520  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 13:20:07.520  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 13:20:07.520  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 13:20:07.520  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 13:20:07.520  1049  104,9 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 13:20:07.527  1049  2045 I art     : Explicit concurrent mark sweep GC freed 32821(1581KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 4.205ms total 89.410ms
08-16 13:20:07.533  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:07.536  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:07.536  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:20:07.536  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:07.536  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:07.536  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:20:07.536  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:20:07.536  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:07.536  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:07.536  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:20:07.548  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:07.548  6636  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:20:07.549  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:07.549  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:20:07.549  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:07.549  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:07.549  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:20:07.549  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:20:07.549  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:07.549  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:07.549  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:20:07.550  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:07.550  6636  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:20:07.554  1049  2011 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6734 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 13:20:07.556  3892  3892 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 13:20:07.556  3892  3978 D BluetoothAdapterProperties: Scan Mode:20
08-16 13:20:07.556  3892  3974 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 13:20:07.557  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 13:20:07.557  3892  4053 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 13:20:07.557  3892  4290 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:20:07.557  3892  3974 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 13:20:07.557  3892  4243 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 13:20:07.558  3892  4277 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:20:07.559  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:07.559  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:20:07.559  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:20:07.559  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:20:07.559  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:20:07.559  3892  4053 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:20:07.559  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:20:07.559  3892  4053 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:20:07.559  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:20:07.559  3892  4053 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 13:20:07.559  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 13:20:07.559  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 13:20:07.559  3892  4053 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 13:20:07.563  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:20:07.578  6717  6717 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 13:20:07.579  6717  6717 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-16 13:20:07.579  6717  6717 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:20:07.579  6717  6717 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-16 13:20:07.580  6717  6717 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 13:20:07.580  6717  6717 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 13:20:07.597  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 13:20:07.598  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:07.598  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:07.608  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-16 13:20:07.609  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:07.609  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:07.610  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:07.612  1049  2815 D DhcpStateMachine: StoppedState
08-16 13:20:07.612  1049  2815 D DhcpStateMachine: StoppedState{ when=-152ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:07.612  1049  1536 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 13:20:07.612  1049  1536 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 13:20:07.614  2642  2642 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 13:20:07.614  2642  2642 I wpa_supplicant: monitor socket send errors count : 1
08-16 13:20:07.614  2642  2642 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1966-2\x00 that cannot receive messages
08-16 13:20:07.615  1049  2703 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 13:20:07.615  1049  2703 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 13:20:07.629  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 13:20:07.632  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-16 13:20:07.632  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:20:07.634  1049  1758 I ActivityManager: Killing 5891:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-16 13:20:07.652  2642  2642 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 13:20:07.652  1049  2703 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 13:20:07.652  1049  2703 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 13:20:07.652  1049  2703 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 13:20:07.652  2642  2642 W wpa_supplicant: USIM:  scard_deinit function
,08-16 13:20:07.653  1049  2703 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
,08-16 13:20:07.653  1049  2703 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:20:07.653  1049  2703 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:20:07.654  1049  1131 D Tethering: InitialState.processMessage what=4
08-16 13:20:07.654  1049  1536 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=201882
08-16 13:20:07.655  1049  1536 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=201883
08-16 13:20:07.656  1049  1536 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=201884  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 13:20:07.656  1049  1536 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=201884  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 13:20:07.668  6717  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 13:20:07.693  1049  1936 W libprocessgroup: failed to open /acct/uid_10014/pid_5891/cgroup.procs: No such file or directory
,08-16 13:20:07.699  1049  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 13:20:07.708  1049  1536 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:07.709  1049  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:07.711  3892  3892 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 13:20:07.711  3892  3892 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:07.711  3892  3892 V BluetoothPbapReceiver: ***********state = 13
08-16 13:20:07.715  3892  3892 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 13:20:07.718  3892  3892 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:07.718  3892  3892 V BluetoothPbapService: state: 13
08-16 13:20:07.718  3892  3892 V BluetoothPbapService: Pbap Service closeService in
08-16 13:20:07.721  2239  2239 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:20:07.738  2642  2642 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-16 13:20:07.739  1049  2703 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 13:20:07.739  1049  2703 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 13:20:07.739  1049  2703 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 13:20:07.740  1049  1536 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-16 13:20:07.742  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 13:20:07.777  1049  1064 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6755 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 13:20:07.778  3892  3892 V BluetoothPbapService: successfully stopped pbap service
08-16 13:20:07.778  3892  3892 V BluetoothPbapService: Pbap Service closeService out
08-16 13:20:07.778  3892  3892 V BluetoothPbapService: Pbap Service onDestroy
08-16 13:20:07.778  3892  3892 V BluetoothPbapService: Pbap Service closeService in
08-16 13:20:07.778  3892  3892 V BluetoothPbapService: Pbap Service closeService out
08-16 13:20:07.779  3892  3892 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 13:20:07.802  6717  6717 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:20:07.802  6717  6717 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 13:20:07.812  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 13:20:07.823  1049  1131 D BluetoothManagerService: Message: 20
08-16 13:20:07.824  1049  1131 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fe2f4a0:true
08-16 13:20:07.836  1049  1131 D BluetoothManagerService: Message: 30
,08-16 13:20:07.841  1049  1536 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 13:20:07.841  1049  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:20:07.841  1049  1536 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:20:07.841  1049  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 13:20:07.842  1966  1966 D WfdsService: Supplicant Connection state is changed : false
08-16 13:20:07.843  1966  2321 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 13:20:07.843  1966  2321 D WfdsService: Set the WFDS Monitor: false
08-16 13:20:07.843  1966  2321 D WfdsMonitor: WFDS Monitor is stopped
08-16 13:20:07.843  1049  1131 D BluetoothManagerService: Message: 30
08-16 13:20:07.844  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-16 13:20:07.844  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:07.848  2467  2467 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:07.848  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 13:20:07.848  1049  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 13:20:07.848  1049  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 13:20:07.850  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:07.850  6717  6717 D LocalBluetoothProfileManager: Adding local MAP profile
08-16 13:20:07.852  6717  6717 D BluetoothMap: Create BluetoothMap proxy object
08-16 13:20:07.852  1049  1131 D BluetoothManagerService: Message: 30
,08-16 13:20:07.853  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:07.856  6636  6636 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 13:20:07.860  1049  1131 D BluetoothManagerService: Message: 30
08-16 13:20:07.863  6717  6717 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-16 13:20:07.864  6717  6717 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-16 13:20:07.876  6717  6717 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-16 13:20:07.879  6717  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-16 13:20:07.890  6717  6717 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:20:07.896  6755  6755 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 13:20:07.897  6755  6755 W LG Account v2.2: No ProfileInfo entries
08-16 13:20:07.897  6755  6755 I LG Account v2.2: isEnabled: false
08-16 13:20:07.897  6755  6755 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 13:20:07.897  6755  6755 I Feature : [Lifetracker]Country: EU
08-16 13:20:07.897  6755  6755 I Feature : [Lifetracker]Operator: OPEN
08-16 13:20:07.897  6755  6755 I Feature : [Lifetracker]Ranking support: false
08-16 13:20:07.897  6755  6755 I Feature : [Lifetracker]Comfort support: false
08-16 13:20:07.897  6755  6755 I Feature : [Lifetracker]Accessory: true
08-16 13:20:07.897  6755  6755 I Feature : [Lifetracker]Health device: true
08-16 13:20:07.897  6755  6755 I Feature : [Lifetracker]Extra Pedometer: false
08-16 13:20:07.897  6755  6755 I Feature : [Lifetracker]Blood glucose device: false
08-16 13:20:07.898  6755  6755 I Feature : [Lifetracker]Device Number: 3
08-16 13:20:07.902  1049  2018 I ActivityManager: Killing 6207:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-16 13:20:07.907  6717  6717 D BluetoothInputDevice: Proxy object connected
,08-16 13:20:07.908  6717  6717 D HidProfile: Bluetooth service connected
08-16 13:20:07.908  6717  6717 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 13:20:07.909  6717  6717 D PanProfile: Bluetooth service connected
08-16 13:20:07.910  6717  6717 D BluetoothMap: Proxy object connected
08-16 13:20:07.910  6717  6717 D MapProfile: Bluetooth service connected
08-16 13:20:07.910  6717  6717 D BluetoothMap: getConnectedDevices()
08-16 13:20:07.911  6717  6717 D BluetoothMap: Bluetooth is Not enabled
08-16 13:20:07.911  6717  6717 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 13:20:07.933  1049  1588 W libprocessgroup: failed to open /acct/uid_10004/pid_6207/cgroup.procs: No such file or directory
,08-16 13:20:07.946  6717  6717 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 13:20:07.959  6717  6717 D BluetoothPermissionRequest: onReceive
08-16 13:20:07.962  6717  6717 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 13:20:07.970  1049  2018 I ActivityManager: Killing 6344:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-16 13:20:07.975  6717  6717 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 13:20:08.002  3892  3892 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 13:20:08.003  3892  3892 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-16 13:20:08.004  1049  1644 W libprocessgroup: failed to open /acct/uid_10008/pid_6344/cgroup.procs: No such file or directory
08-16 13:20:08.005  3892  3892 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-16 13:20:08.086  1049  2018 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6781 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-16 13:20:08.090  3892  3892 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:08.091  3892  3892 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-16 13:20:08.092  3892  3892 V BluetoothFtpService: Ftp Service onStartCommand
08-16 13:20:08.092  3892  3892 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:08.092  3892  3892 V BluetoothFtpService: Ftp Service closeService
08-16 13:20:08.092  3892  3892 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-16 13:20:08.094  3892  3892 V BluetoothFtpService: successfully stopped ftp service
08-16 13:20:08.094  3892  3892 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:20:08.094  3892  3892 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:20:08.094  3892  3892 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 13:20:08.094  3892  3892 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:08.094  3892  3892 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 13:20:08.094  3892  3892 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 13:20:08.096  3892  3892 V BluetoothFtpService: Ftp Service onDestroy
08-16 13:20:08.096  3892  3892 V BluetoothFtpService: Ftp Service closeService
08-16 13:20:08.147  1049  2045 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6801 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 13:20:08.153  3892  3892 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:08.153  3892  3892 V BluetoothSapService: state: 13
08-16 13:20:08.153  3892  3892 V BluetoothSapService: Stopping SAP server process
08-16 13:20:08.156  3892  3892 V BluetoothSapService: Sap Service closeSapService in
08-16 13:20:08.156  3892  3892 V BluetoothSapService: Close listen Socket : 
08-16 13:20:08.156  3892  3892 V BluetoothSapService: Close rfcomm Socket : 
,08-16 13:20:08.156  3892  3892 V BluetoothSapService: Close sapd  Socket : 
08-16 13:20:08.157  3892  3892 V BluetoothSapService: Sap Service closeSapService out
08-16 13:20:08.157  3892  3892 V BluetoothSapService: Sap Service onDestroy
08-16 13:20:08.157  3892  3892 V BluetoothSapService: Sap Service closeSapService in
08-16 13:20:08.157  3892  3892 V BluetoothSapService: Close listen Socket : 
08-16 13:20:08.157  3892  3892 V BluetoothSapService: Close rfcomm Socket : 
08-16 13:20:08.157  3892  3892 V BluetoothSapService: Close sapd  Socket : 
08-16 13:20:08.158  3892  3892 V BluetoothSapService: Sap Service closeSapService out
08-16 13:20:08.167   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 388us total 18.368ms
,08-16 13:20:08.182   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 14.056ms
,08-16 13:20:08.196   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 291us total 13.432ms
,08-16 13:20:08.209  6801  6801 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:20:08.209  6781  6781 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 13:20:08.222  1049  1963 I ActivityManager: Killing 6009:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-16 13:20:08.254  1049  1936 W libprocessgroup: failed to open /acct/uid_10011/pid_6009/cgroup.procs: No such file or directory
,08-16 13:20:08.256  6781  6781 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-16 13:20:08.304  6781  6781 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-16 13:20:08.304  6781  6781 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 13:20:08.305  6781  6781 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 13:20:08.306  6781  6781 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 13:20:08.306  6781  6781 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 13:20:08.309  6781  6781 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 13:20:08.315  6781  6781 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 13:20:08.323  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 13:20:08.332  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:08.369  6781  6781 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 13:20:08.373  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:08.378  6781  6781 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 13:20:08.382  6781  6781 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 13:20:08.382  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 13:20:08.382  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 13:20:08.382  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:20:08.391  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:08.398  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:08.405  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:08.405  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 13:20:08.407  6781  6781 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 13:20:08.411  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:08.414  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 13:20:08.414  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 13:20:08.415  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:20:08.417  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:08.424  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 13:20:08.432  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:08.433  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 13:20:08.436  6781  6781 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 13:20:08.480  1049  1984 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6821 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 13:20:08.561  3892  4053 W bt-btif : ag scb idx 1 not allocated
08-16 13:20:08.561  3892  3978 D bt_hci_bdroid: cleanup
08-16 13:20:08.561  3892  4053 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 13:20:08.561  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:20:08.561  3892  4053 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:20:08.561  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:20:08.561  3892  4053 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:20:08.561  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:20:08.561  3892  4053 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 13:20:08.561  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:20:08.561  3892  4053 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:20:08.561  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:20:08.561  3892  4053 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:20:08.561  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:20:08.561  3892  4053 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 13:20:08.561  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:20:08.561  3892  4055 I bt_lpm  : LPM is already off!!!
08-16 13:20:08.561  3892  4053 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:20:08.562  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:20:08.562  3892  4053 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:20:08.562  3892  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:20:08.562  3892  4053 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 13:20:08.562  3892  4216 I bt_userial_mct: exiting userial_read_thread
08-16 13:20:08.562  3892  4053 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 13:20:08.562  3892  4216 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 13:20:08.563  3892  3978 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 13:20:08.563  3892  4055 I bt_vendor: hw_epilog_process
08-16 13:20:08.564  3892  3978 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 13:20:08.564  3892  3978 D bt_userial_mct: userial_close
08-16 13:20:08.564  3892  3978 E bt_userial_mct: pthread_join() FAILED result:3
08-16 13:20:08.564  3892  3978 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-16 13:20:08.580  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 13:20:08.584  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 13:20:08.604  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:08.623  6821  6848 W FormManager: Network not available. Please check & try again.
,08-16 13:20:08.630  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 13:20:08.630  6717  6717 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 13:20:08.630  6717  6717 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 13:20:08.630  6717  6717 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 13:20:08.631  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 13:20:08.640  6821  6849 V FormManager: Network unavailable.
,08-16 13:20:08.643  6821  6849 V FormManager: Network unavailable.
08-16 13:20:08.645  6717  6717 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 13:20:08.645  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 13:20:08.645  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 13:20:08.646  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 13:20:08.646  6717  6717 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 13:20:08.646  6717  6717 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 13:20:08.650  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 13:20:08.650  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:20:08.652  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:20:08.654  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 13:20:08.659  4326  6853 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 13:20:08.663  6734  6734 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 13:20:08.663  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 13:20:08.663  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:20:08.667  3892  3978 D bt_hci_bdroid: set_power 0
08-16 13:20:08.667  3892  3978 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 13:20:08.667  3892  3978 I bt_vendor: bluetooth satus is on
08-16 13:20:08.667  3892  3978 I bt_vendor: bt-vendor : resetting BT status
08-16 13:20:08.667  3892  3978 I bt_vendor: Starting hciattach daemon
08-16 13:20:08.667  3892  3978 I bt_vendor: try to set false
08-16 13:20:08.668  3892  3978 I bt_vendor: Starting hciattach daemon
08-16 13:20:08.668  3892  3978 I bt_vendor: try to set false
,08-16 13:20:08.669  3892  3978 I bt_vendor: cleanup
08-16 13:20:08.669  3892  4053 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 13:20:08.670  4326  6854 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 13:20:08.670  4326  6854 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 13:20:08.672  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 13:20:08.675  3892  3978 I GKI_LINUX: GKI_exit_task 0 done
08-16 13:20:08.675  3892  3978 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 13:20:08.676  3892  3974 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 13:20:08.680  6821  6855 W FormManager: Network not available. Please check & try again.
08-16 13:20:08.681  3892  3892 D HeadsetService: Received stop request...Stopping profile...
,08-16 13:20:08.681  3892  3892 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 13:20:08.681  3892  3892 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 13:20:08.682  3892  3892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3020b8c7
08-16 13:20:08.682  3892  4007 D HeadsetStateMachine: Exit Disconnected: -1
08-16 13:20:08.683  1049  1049 D BluetoothHeadset: Proxy object disconnected
08-16 13:20:08.683  1876  1876 D BluetoothHeadset: Proxy object disconnected
08-16 13:20:08.683  1049  1049 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 13:20:08.683  1876  1876 D BluetoothHeadset: Proxy object disconnected
08-16 13:20:08.685  3892  3892 D A2dpService: Received stop request...Stopping profile...
08-16 13:20:08.686  3892  4034 D A2dpStateMachine: Exit Disconnected: -1
08-16 13:20:08.686  3892  3892 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 13:20:08.687  1876  1876 D BluetoothHeadset: Proxy object disconnected
08-16 13:20:08.688  3892  3892 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 13:20:08.688  3892  3892 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 13:20:08.688  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:08.688  3892  3892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3020b8c7
08-16 13:20:08.693  1049  1049 D BluetoothA2dp: Proxy object disconnected
08-16 13:20:08.693  1049  1049 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-16 13:20:08.699  3892  3892 D HeadsetStateMachine: Unbinding service...
08-16 13:20:08.699  3892  3974 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 13:20:08.700  3892  3892 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 13:20:08.700  3892  3892 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 13:20:08.700  3892  3892 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 13:20:08.700  3892  3892 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 13:20:08.700  3892  3892 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 13:20:08.700  3892  3892 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 13:20:08.700  3892  3892 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 13:20:08.701  3892  3892 D HidService: Received stop request...Stopping profile...
08-16 13:20:08.701  3892  3892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3020b8c7
08-16 13:20:08.702  6821  6856 V FormManager: Network unavailable.
08-16 13:20:08.702  3892  3892 D HealthService: Received stop request...Stopping profile...
08-16 13:20:08.702  3892  3892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3020b8c7
08-16 13:20:08.703  6717  6717 D BluetoothInputDevice: Proxy object disconnected
08-16 13:20:08.704  6717  6717 D HidProfile: Bluetooth service disconnected
08-16 13:20:08.705  3892  3892 D PanService: Received stop request...Stopping profile...
08-16 13:20:08.706  3892  3892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3020b8c7
,08-16 13:20:08.708  3892  3892 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 13:20:08.709  3892  3892 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 13:20:08.709  3892  3892 D BtGatt.GattService: stop()
08-16 13:20:08.709  3892  3892 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 13:20:08.710  6717  6717 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 13:20:08.711  3892  3892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3020b8c7
08-16 13:20:08.712  3892  3892 D BluetoothMapService: Received stop request...Stopping profile...
08-16 13:20:08.712  3892  3892 D BluetoothMapService: stop()
08-16 13:20:08.713  3892  3892 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 13:20:08.713  3892  3892 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 13:20:08.714  3892  3892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3020b8c7
08-16 13:20:08.714  6821  6856 V FormManager: Network unavailable.
08-16 13:20:08.715  3892  3892 I BluetoothA2dpServiceJni: cleanupNative
08-16 13:20:08.715  3892  4035 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 13:20:08.715  3892  3892 I GKI_LINUX: GKI_exit_task 2 done
08-16 13:20:08.715  3892  3892 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 13:20:08.716  3892  3892 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 13:20:08.716  3892  3892 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 13:20:08.716  3892  3892 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 13:20:08.716  3892  3892 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 13:20:08.716  3892  3892 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 13:20:08.716  3892  3892 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 13:20:08.716  3892  3892 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 13:20:08.717  3892  3892 V BluetoothMapService: Handler(): got msg=4
08-16 13:20:08.717  3892  3892 D BluetoothMapService: MAP Service closeService in
08-16 13:20:08.717  6717  6717 D PanProfile: Bluetooth service disconnected
08-16 13:20:08.717  3892  3892 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 13:20:08.717  3892  3892 V BluetoothMapService: MAP Service closeService out
08-16 13:20:08.718  6717  6717 D BluetoothMap: Proxy object disconnected
08-16 13:20:08.718  6717  6717 D MapProfile: Bluetooth service disconnected
08-16 13:20:08.718  3892  3892 D BluetoothMapService: cleanup()
08-16 13:20:08.718  3892  3892 D BluetoothMapService: MAP Service closeService in
08-16 13:20:08.718  3892  3892 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 13:20:08.718  3892  3892 V BluetoothMapService: MAP Service closeService out
08-16 13:20:08.718  3892  3974 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
,08-16 13:20:08.718  3892  3974 D BluetoothAdapterProperties: Setting state to 10
08-16 13:20:08.718  3892  3974 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 13:20:08.719  1049  1131 D BluetoothManagerService: Message: 60
08-16 13:20:08.719  1049  1131 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 13:20:08.719  1049  1131 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-16 13:20:08.719  1049  1131 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 13:20:08.719  6781  6781 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 13:20:08.719  3892  3974 I BluetoothAdapterState: Entering OffState
,08-16 13:20:08.719  1876  4006 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:20:08.720  6717  6732 D BluetoothMap: onBluetoothStateChange: up=false
08-16 13:20:08.720  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 13:20:08.721  6717  6733 D BluetoothPan: onBluetoothStateChange on: false
08-16 13:20:08.721  6781  6781 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 13:20:08.721  1876  1892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:20:08.722  6717  6732 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 13:20:08.723  1876  4012 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 13:20:08.723  1049  1131 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:20:08.723  6717  6733 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 13:20:08.725  1049  1131 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 13:20:08.725  1049  1131 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 13:20:08.729  1049  1131 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 13:20:08.729  1049  1131 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 13:20:08.729  1049  1131 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@16a0c621 mBinding = false
08-16 13:20:08.730  1049  1131 D BluetoothManagerService: Sending unbind request.
08-16 13:20:08.730  1049  2018 I ActivityManager: Killing 6031:com.android.contacts/u0a19 (adj 15): empty #17
,08-16 13:20:08.761  6781  6781 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 13:20:08.761  6781  6781 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:20:08.768  6781  6781 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 13:20:08.769  6781  6781 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 13:20:08.769  6781  6781 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 13:20:08.769  6781  6781 V SoundPool: doLoad: loading sample sampleID=1
08-16 13:20:08.770  6781  6781 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 13:20:08.772  6781  6866 V SoundPool: Start decode
08-16 13:20:08.772  6781  6866 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 13:20:08.773   310  1384 V MediaPlayerService: decode(22, 10857164, 17813)
08-16 13:20:08.773   310  1384 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 13:20:08.773   310  1384 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 13:20:08.773   310  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 13:20:08.773   310  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 13:20:08.773   310  1384 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 13:20:08.773   310  1384 V MediaPlayerService: player type = 3
08-16 13:20:08.773   310  1384 V AwesomePlayer: AwesomePlayer create()
,08-16 13:20:08.774   310  1384 V AwesomePlayer: reset_l() 
08-16 13:20:08.774   310  1384 V AwesomePlayer: cancelPlayerEvents
08-16 13:20:08.774   310  1384 V AwesomePlayer: setAudioSink() 
08-16 13:20:08.774   310  1384 V AwesomePlayer: reset_l() 
08-16 13:20:08.774   310  1384 V AudioCache: notify(0xb1432f80, 8, 0, 0)
08-16 13:20:08.774   310  1384 V AudioCache: ignored
08-16 13:20:08.774   310  1384 V AwesomePlayer: cancelPlayerEvents
08-16 13:20:08.774   310  1384 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 13:20:08.774   310  1384 V AwesomePlayer: setDataSource_l dataSource
08-16 13:20:08.774   310  1384 V LGParserOSAL: SniffLGParser start
08-16 13:20:08.774   310  1384 V LGParserOSAL: MainType:5, SubType=0
08-16 13:20:08.774   310  1384 V LGParserOSAL: #### check Mime : application/ogg
08-16 13:20:08.774   310  1384 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 13:20:08.774   310  1384 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 13:20:08.782  1049  2111 W libprocessgroup: failed to open /acct/uid_10019/pid_6031/cgroup.procs: No such file or directory
08-16 13:20:08.783  1049  1131 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 13:20:08.791  6781  6781 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 13:20:08.792  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 13:20:08.793  6526  6526 D UEI.SmartControl: QS Service created
08-16 13:20:08.797  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:08.797  1966  2177 D LGBluetoothAPIService: Message: 2
08-16 13:20:08.798  1966  2177 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1f35f4d6 mBinding = false
08-16 13:20:08.798  1966  2177 D LGBluetoothAPIService: Sending unbind request.
08-16 13:20:08.798  6781  6781 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 13:20:08.799  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 13:20:08.799  1602  1602 D BluetoothAdapter: 685001113: getState() :  mService = null. Returning STATE_OFF
08-16 13:20:08.799  1602  1602 D BluetoothAdapter: 685001113: getState() :  mService = null. Returning STATE_OFF
08-16 13:20:08.800  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:08.801  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:08.803  3892  3978 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 13:20:08.803  3892  3892 I GKI_LINUX: GKI_exit_task 1 done
08-16 13:20:08.803  3892  3892 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 13:20:08.803  3892  3892 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 13:20:08.804  3892  3892 I art     : --- WEIRD: removing null entry 246
08-16 13:20:08.804  3892  3892 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-16 13:20:08.804  3892  3892 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 13:20:08.805  6717  6717 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 13:20:08.806  3892  3892 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 13:20:08.807  6717  6717 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 13:20:08.807  6717  6717 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-16 13:20:08.808  3892  3892 I art     : System.exit called, status: 0
08-16 13:20:08.808  3892  3892 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 13:20:08.810  6717  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 13:20:08.815  6717  6717 D DockEventReceiver: finishStartingService: stopping service
08-16 13:20:08.820  6781  6781 V LGMDMManager: Create singleton instance
,08-16 13:20:08.825   310  1785 V AudioFlinger: 3892 died, releasing its sessions
08-16 13:20:08.825   310  1785 V AudioFlinger:  pid 1876 @ 0
08-16 13:20:08.825   310  1785 V AudioFlinger:  pid 3370 @ 1
08-16 13:20:08.825   310  1785 V AudioFlinger:  pid 3370 @ 2
08-16 13:20:08.825  6717  6717 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 13:20:08.831   310  1384 V LGParserOSAL: supported mime: application/ogg
08-16 13:20:08.831   310  1384 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 13:20:08.831   310  1384 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 13:20:08.831   310  1384 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 13:20:08.831   310  1384 V AwesomePlayer: AudioTrack Setting
08-16 13:20:08.831  6526  6526 I UEI.SmartControl: Service initServices...
08-16 13:20:08.831   310  1384 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 13:20:08.831   310  1384 V AwesomePlayer: setAudioSource() 
08-16 13:20:08.831   310  1384 V MediaPlayerService: prepare
08-16 13:20:08.831   310  1384 V AwesomePlayer: prepareAsync_l() 
08-16 13:20:08.831   310  1384 V MediaPlayerService: wait for prepare
08-16 13:20:08.831   310  6869 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 13:20:08.832   310  6869 V AwesomePlayer: initAudioDecoder() 
08-16 13:20:08.832   310  6869 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 13:20:08.832   310  6869 V AudioSystem: isOffloadSupported()
08-16 13:20:08.832   310  6869 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 13:20:08.832   310  6869 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 13:20:08.832   310  6869 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 13:20:08.832   310  6869 V AwesomePlayer: getUseOffload() = 0 
08-16 13:20:08.832   310  6869 V OMXCodec: OMXCodec::Create
08-16 13:20:08.832   310  6869 V OMXCodec: findMatchingCodecs()
08-16 13:20:08.832   310  6869 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 13:20:08.832   310  6869 V OMXCodec: matchingCodecs.size()=1
08-16 13:20:08.832   310  6869 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 13:20:08.833  6526  6526 D UEI.SmartControl: QS start get config
08-16 13:20:08.840   310  6869 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 13:20:08.840   310  6869 V LGCodecAdapter: LG Codec Adapter start
08-16 13:20:08.840   310  6869 V OMXCodec: OMXCodec Createtor
08-16 13:20:08.840   310  6869 V OMXCodec: setComponentRole
08-16 13:20:08.840   310  6869 V OMXCodec: configureCodec protected=0
08-16 13:20:08.840   310  6869 V LGCodecAdapter: called getLGCodecSpecificData
08-16 13:20:08.840   310  6869 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 13:20:08.840   310  6869 V LGCodecOSAL: Called LGconfigureCodecMETA
,08-16 13:20:08.840   310  6869 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 13:20:08.840   310  6869 V LGCodecOSAL: Not support LGCodec
08-16 13:20:08.840   310  6869 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 13:20:08.841   310  6869 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 13:20:08.841   310  6869 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 13:20:08.841   310  6869 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 13:20:08.841   310  6869 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 13:20:08.841   310  6869 V AudioSystem: isOffloadSupported()
08-16 13:20:08.841   310  6869 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 13:20:08.841   310  6869 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 13:20:08.841   310  6869 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 13:20:08.841   310  6869 V OMXCodec: init()
08-16 13:20:08.841   310  6869 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 13:20:08.841   310  6869 V OMXCodec: allocateBuffers
08-16 13:20:08.841   310  6869 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 13:20:08.841   310  6869 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 13:20:08.841   310  6869 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
08-16 13:20:08.841   310  6869 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-16 13:20:08.841   310  6869 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-16 13:20:08.841   310  6869 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-16 13:20:08.841   310  6869 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 13:20:08.841   310  6869 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 13:20:08.842   310  6869 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-16 13:20:08.842   310  6869 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-16 13:20:08.842   310  6869 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 13:20:08.842   310  6869 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-16 13:20:08.842   310  6869 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 13:20:08.842   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 13:20:08.842   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 13:20:08.842   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 13:20:08.842   310  6869 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 13:20:08.842   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 13:20:08.842   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 13:20:08.842   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 13:20:08.842   310  6869 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 13:20:08.843   310  6869 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 13:20:08.843   310  6869 V AudioCache: notify(0xb1432f80, 5, 0, 0)
08-16 13:20:08.843   310  6869 V AudioCache: ignored
08-16 13:20:08.843   310  6869 V AudioCache: notify(0xb1432f80, 1, 0, 0)
08-16 13:20:08.843   310  6869 V AudioCache: prepared
08-16 13:20:08.843   310  1384 V AudioCache: wait - success
08-16 13:20:08.843   310  1384 V MediaPlayerService: star,t
08-16 13:20:08.843   310  1384 V AwesomePlayer: play_l() 
08-16 13:20:08.843   310  1384 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 13:20:08.843   310  1384 V AwesomePlayer: createAudioPlayer_l
08-16 13:20:08.843   310  1384 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 13:20:08.843   310  1384 V AwesomePlayer: startAudioPlayer_l() 
08-16 13:20:08.843   310  1384 D AudioPlayer: start of Playback, useOffload 0
08-16 13:20:08.843   310  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 13:20:08.843   310  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 13:20:08.845   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 13:20:08.845   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 13:20:08.845   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 13:20:08.845   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 13:20:08.845   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 13:20:08.845   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 13:20:08.846   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
08-16 13:20:08.846   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 13:20:08.846   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
08-16 13:20:08.846   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 13:20:08.846   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-16 13:20:08.846   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 13:20:08.846   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
08-16 13:20:08.846   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 13:20:08.846   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 13:20:08.846   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 13:20:08.846   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 13:20:08.846   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 13:20:08.846   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 13:20:08.847   310  6871 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 13:20:08.847   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 13:20:08.847   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 13:20:08.847   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-16 13:20:08.847   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-16 13:20:08.847   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd4c0 on output port
08-16 13:20:08.847   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 13:20:08.847   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 13:20:08.849   310  1384 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 13:20:08.849   310  1384 V AudioCache: notify(0xb1432f80, 6, 0, 0)
08-16 13:20:08.849   310  1384 V AudioCache: ignored
08-16 13:20:08.849   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.849   310  6872 V AudioCache: memcpy(0xaf104000, 0xb57bb000, 4096)
08-16 13:20:08.849   310  1384 V MediaPlayerService: wait for playback complete
08-16 13:20:08.851   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.851   310  6872 V AudioCa,che: memcpy(0xaf105000, 0xb57bb000, 4096)
08-16 13:20:08.851   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.851   310  6872 V AudioCache: memcpy(0xaf106000, 0xb57bb000, 4096)
08-16 13:20:08.852   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.853   310  6872 V AudioCache: memcpy(0xaf107000, 0xb57bb000, 4096)
08-16 13:20:08.853   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.853   310  6872 V AudioCache: memcpy(0xaf108000, 0xb57bb000, 4096)
08-16 13:20:08.854   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.854   310  6872 V AudioCache: memcpy(0xaf109000, 0xb57bb000, 4096)
08-16 13:20:08.854   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.854   310  6872 V AudioCache: memcpy(0xaf10a000, 0xb57bb000, 4096)
08-16 13:20:08.855   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.855   310  6872 V AudioCache: memcpy(0xaf10b000, 0xb57bb000, 4096)
08-16 13:20:08.855   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.856   310  6872 V AudioCache: memcpy(0xaf10c000, 0xb57bb000, 4096)
08-16 13:20:08.856   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.856   310  6872 V AudioCache: memcpy(0xaf10d000, 0xb57bb000, 4096)
08-16 13:20:08.857   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.857   310  6872 V AudioCache: memcpy(0xaf10e000, 0xb57bb000, 4096)
08-16 13:20:08.857   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.857   310  6872 V AudioCache: memcpy(0xaf10f000, 0xb57bb000, 4096)
08-16 13:20:08.858   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.858   310  6872 V AudioCache: memcpy(0xaf110000, 0xb57bb000, 4096)
08-16 13:20:08.859   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.859   310  6872 V AudioCache: memcpy(0xaf111000, 0xb57bb000, 4096)
08-16 13:20:08.860   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.860   310  6872 V AudioCache: memcpy(0xaf112000, 0xb57bb000, 4096)
08-16 13:20:08.861   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.861   310  6872 V AudioCache: memcpy(0xaf113000, 0xb57bb000, 4096)
08-16 13:20:08.861   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.861   310  6872 V AudioCache: memcpy(0xaf114000, 0xb57bb000, 4096)
08-16 13:20:08.862   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.862   310  6872 V AudioCache: memcpy(0xaf115000, 0xb57bb000, 4096)
08-16 13:20:08.862   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.862   310  6872 V AudioCache: memcpy(0xaf116000, 0xb57bb000, 4096)
08-16 13:20:08.863   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.863   310  6872 V AudioCache: memcpy(0xaf117000, 0xb57bb000, 4096)
08-16 13:20:08.864   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.864   310  6872 V AudioCache: memcpy(0xaf118000, 0xb57bb000, 4096)
08-16 13:20:08.864   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.864   310  6872 V AudioCache: memcpy(0xaf119000, 0xb57bb000, 4096)
08-16 13:20:08.865   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.865   310  6872 V AudioCache: memcpy(0xaf11a000, 0xb57bb000, 4096)
08-16 13:20:08.865   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.865   310  6872 V AudioCache: memcpy(0xaf11b000, 0xb57bb000, 4096)
08-16 13:20:08.866   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.866   310  6872 V AudioCache: memcpy(0xaf11c000, 0xb57bb000, 4096)
08-16 13:20:08.866   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.866   310  6872 V AudioCache: memcpy(0xaf11d000, 0xb57bb000, 4096)
08-16 13:20:08.867   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.867   310  6872 V AudioCache: memcpy(0xaf11e000, 0xb57bb000, 4096)
08-16 13:20:08.868   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.868   310  6872 V AudioCache: memcpy(0xaf11f000, 0xb57bb000, 4096)
08-16 13:20:08.869   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.869   310  6872 V AudioCache: memcpy(0xaf120000, 0xb57bb000, 4096)
08-16 13:20:08.871   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.871   310  6872 V AudioCache: memcpy(0xaf121000, 0xb57bb000, 4096)
08-16 13:20:08.871   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.871   310  6872 V AudioCache: memcpy(0xaf122000, 0xb57bb000, 4096)
08-16 13:20:08.871   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.871   310  6872 V AudioCache: memcpy(0xaf123000, 0xb57bb000, 4096)
08-16 13:20:08.871   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.871   310  6872 V AudioCache: memcpy(0xaf124000, 0xb57bb000, 4096)
08-16 13:20:08.873   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.873   310  6872 V AudioCache: memcpy(0xaf125000, 0xb57bb000, 4096)
08-16 13:20:08.873   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.873   310  6872 V AudioCache: memcpy(0xaf126000, 0xb57bb000, 4096)
08-16 13:20:08.873   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.873   310  6872 V AudioCache: memcpy(0xaf127000, 0xb57bb000, 4096)
08-16 13:20:08.874   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.874   310  6872 V AudioCache: memcpy(0xaf128000, 0xb57bb000, 4096)
08-16 13:20:08.874   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.874   310  6872 V AudioCache: memcpy(0xaf129000, 0xb57bb000, 4096)
08-16 13:20:08.875   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.875   310  6872 V AudioCache: memcpy(0xaf12a000, 0xb57bb000, 4096)
08-16 13:20:08.876   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.876   310  6872 V AudioCache: memcpy(0xaf12b000, 0xb57bb000, 4096)
08-16 13:20:08.876   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.876   310  6872 V AudioCache: memcpy(0xaf12c000, 0xb57bb000, 4096)
08-16 13:20:08.877   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.877   310  6872 V AudioCache: memcpy(0xaf12d000, 0xb57bb000, 4096)
,08-16 13:20:08.878   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.878   310  6872 V AudioCache: memcpy(0xaf12e000, 0xb57bb000, 4096)
08-16 13:20:08.878   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.878   310  6872 V AudioCache: memcpy(0xaf12f000, 0xb57bb000, 4096)
08-16 13:20:08.879   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.879   310  6872 V AudioCache: memcpy(0xaf130000, 0xb57bb000, 4096)
08-16 13:20:08.880   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.880   310  6872 V AudioCache: memcpy(0xaf131000, 0xb57bb000, 4096)
08-16 13:20:08.880   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.880   310  6872 V AudioCache: memcpy(0xaf132000, 0xb57bb000, 4096)
08-16 13:20:08.881   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.881   310  6872 V AudioCache: memcpy(0xaf133000, 0xb57bb000, 4096)
08-16 13:20:08.882   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.882   310  6872 V AudioCache: memcpy(0xaf134000, 0xb57bb000, 4096)
08-16 13:20:08.882   310  6872 V AudioCache: write(0xb57bb000, 4096)
08-16 13:20:08.882   310  6872 V AudioCache: memcpy(0xaf135000, 0xb57bb000, 4096)
08-16 13:20:08.882   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 13:20:08.883   310  6872 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 13:20:08.883   310  6872 V AwesomePlayer: postAudioEOS() 
08-16 13:20:08.883   310  6872 V AudioCache: write(0xb57bb000, 280)
08-16 13:20:08.883   310  6872 V AudioCache: memcpy(0xaf136000, 0xb57bb000, 280)
08-16 13:20:08.885  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 13:20:08.886  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 13:20:08.887   310  6869 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 13:20:08.887   310  6869 V AwesomePlayer: onStreamDone
08-16 13:20:08.887   310  6869 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 13:20:08.887   310  6869 V AudioCache: notify(0xb1432f80, 2, 0, 0)
08-16 13:20:08.887   310  6869 V AudioCache: playback complete
08-16 13:20:08.887   310  6869 V AwesomePlayer: pause_l() 
08-16 13:20:08.887   310  6869 V AudioCache: notify(0xb1432f80, 7, 0, 0)
08-16 13:20:08.887   310  6869 V AudioCache: ignored
08-16 13:20:08.887   310  6869 V AwesomePlayer: cancelPlayerEvents
08-16 13:20:08.887   310  1384 V AudioCache: wait - success
08-16 13:20:08.887   310  1384 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 13:20:08.887   310  6869 D AudioPlayer: Pause Playback at 1068125
08-16 13:20:08.887   310  1384 V AwesomePlayer: reset_l() 
08-16 13:20:08.887   310  1384 V AudioCache: notify(0xb1432f80, 8, 0, 0)
08-16 13:20:08.887   310  1384 V AudioCache: ignored
08-16 13:20:08.887   310  1384 V AwesomePlayer: cancelPlayerEvents
08-16 13:20:08.887   310  1384 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 13:20:08.887   310  1384 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 13:20:08.887   310  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 13:20:08.887   310  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 13:20:08.887   310  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd4c0 on port 1
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 13:20:08.888   310  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 13:20:08.888   310  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 13:20:08.888   310  6871 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 13:20:08.888   310  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 13:20:08.888   310  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 13:20:08.889   310  1384 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 13:20:08.889   310  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 13:20:08.889   310  1384 D AudioPlayer: AudioPlayer releasing audio source
08-16 13:20:08.889   310  1384 D AudioPlayer: AudioPlayer done releasing audio source
08-16 13:20:08.889   310  1384 V AwesomePlayer: reset_l() 
08-16 13:20:08.889   310  1384 V AwesomePlayer: cancelPlayerEvents
08-16 13:20:08.889   310  1384 V AwesomePlayer: ~AwesomePlayer call
08-16 13:20:08.890   310  1384 V AwesomePlayer: reset_l() 
08-16 13:20:08.890   310  1384 V AwesomePlayer: cancelPlayerEvents
08-16 13:20:08.890  6781  6866 V SoundPool: close(31)
08-16 13:20:08.890  6781  6866 V SoundPool: pointer = 0xa0012000, size = 205080, sampleRate = 48000, numChannels = 2
,08-16 13:20:08.958  1049  1064 I ActivityManager: Process com.android.bluetooth (pid 3892) has died
,08-16 13:20:08.958  1049  1064 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-16 13:20:08.965  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7567
08-16 13:20:08.965  2239  2239 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 13:20:08.986  6717  6717 D BluetoothPermissionRequest: onReceive
,08-16 13:20:08.991  6717  6717 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 13:20:08.991  6717  6717 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 13:20:08.994  6717  6717 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 13:20:09.067  1049  2018 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6873 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 13:20:09.091  6526  6526 I UEI.SmartControl: Supports setup maps: true
,08-16 13:20:09.093  6526  6526 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 13:20:09.093  6526  6526 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 13:20:09.093  6526  6526 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 13:20:09.093  6526  6526 I UEI.SmartControl: ### init IR Blaster...
08-16 13:20:09.097  6526  6526 D serial_port: Configuring serial port
08-16 13:20:09.097  6526  6526 E UEI.SmartControl: UEIBLaster setting for 616
08-16 13:20:09.097  6526  6526 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 13:20:09.097  6526  6526 I UEI.SmartControl: configuring settings for MAXQ616
08-16 13:20:09.097  6526  6526 I UEI.SmartControl: Get version...
08-16 13:20:09.113  6526  6888 D UEI.SmartControl: serial port data available: 21
,08-16 13:20:09.139  6526  6526 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 13:20:09.139  6526  6526 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-16 13:20:09.139  6526  6526 I UEI.SmartControl: QS saving settings...
08-16 13:20:09.140  6526  6526 D UEI.SmartControl: IR Blaster version: 25672567
08-16 13:20:09.157  6526  6888 D UEI.SmartControl: serial port data available: 4
,08-16 13:20:09.162  6873  6873 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 13:20:09.163  6873  6873 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:20:09.163  6873  6873 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 13:20:09.164  6873  6873 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 13:20:09.185  6873  6873 D BluetoothAdapterApp: Loading JNI Library
,08-16 13:20:09.192  6526  6893 I UEI.SmartControl: Device manager: loading config....
08-16 13:20:09.193  6526  6526 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 13:20:09.196  6526  6526 E UEI.SmartControl: Services init done
08-16 13:20:09.196  6526  6526 D UEI.SmartControl: QS Service init finished
08-16 13:20:09.196  6526  6893 D UEI.SmartControl: ----------- loading internal config...
08-16 13:20:09.196  6526  6526 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 13:20:09.197  6526  6526 D UEI.SmartControl: QS Service version code: 201091
08-16 13:20:09.198  6526  6526 D UEI.SmartControl: Service requested: Control
08-16 13:20:09.205  6526  6893 E UEI.SmartControl: Loading SETTINGS...
,08-16 13:20:09.208  6526  6526 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 13:20:09.211  6526  6526 D UEI.SmartControl: Internal service binding...
08-16 13:20:09.212  6781  6781 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 13:20:09.214  6526  6541 I UEI.SmartControl: ------ IControl API: 11
08-16 13:20:09.214  6526  6541 D UEI.SmartControl: File observer start...
08-16 13:20:09.215  6526  6541 E UEI.SmartControl: IR Port is disabled: false
08-16 13:20:09.215  6526  6541 D UEI.SmartControl: Starting file observer...
08-16 13:20:09.217  6526  6541 I UEI.SmartControl: Registering callback...
08-16 13:20:09.218  6526  6542 I UEI.SmartControl: ------ IControl API: 19
,08-16 13:20:09.220  6526  6542 I UEI.SmartControl: Registering Services Ready callback...
08-16 13:20:09.221  6526  6893 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 13:20:09.225  6873  6873 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@265b805c Instance Count = 1
08-16 13:20:09.231  6873  6873 D BluetoothAdapterApp: onCreate
08-16 13:20:09.248  6526  6892 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 13:20:09.248  6526  6892 D UEI.SmartControl: -----service ready thread exits
08-16 13:20:09.249  6781  6796 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-16 13:20:09.250  6781  6864 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 13:20:09.251  6781  6864 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 13:20:09.252  6781  6781 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 13:20:09.254  6873  6873 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 13:20:09.254  6873  6873 D ProfileConfigQcom: Adding HeadsetService
08-16 13:20:09.253  6781  6781 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 13:20:09.254  6873  6873 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 13:20:09.254  6873  6873 D ProfileConfigQcom: Adding A2dpService
08-16 13:20:09.254  6526  6541 I UEI.SmartControl: ------ IControl API: 8
08-16 13:20:09.254  6873  6873 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 13:20:09.255  6873  6873 D ProfileConfigQcom: Adding HidService
08-16 13:20:09.255  6873  6873 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 13:20:09.255  6873  6873 D ProfileConfigQcom: Adding HealthService
08-16 13:20:09.255  6873  6873 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 13:20:09.256  6873  6873 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 13:20:09.257  6873  6873 D ProfileConfigQcom: Adding PanService
08-16 13:20:09.257  6873  6873 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 13:20:09.257  6873  6873 D ProfileConfigQcom: Adding GattService
08-16 13:20:09.258  6873  6873 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 13:20:09.258  6873  6873 D ProfileConfigQcom: Adding BluetoothMapService
08-16 13:20:09.258  6873  6873 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 13:20:09.259  6781  6781 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 13:20:09.260  6873  6873 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 13:20:09.260  6781  6781 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 13:20:09.261  6781  6781 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
,08-16 13:20:09.262  6781  6781 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 13:20:09.264  6717  6717 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 13:20:09.264  6781  6781 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 13:20:09.265  6873  6873 V LGMDMManagerInternal: Create singleton instance
08-16 13:20:09.265  6781  6781 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 13:20:09.269  6781  6781 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 13:20:09.272  6781  6781 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 13:20:09.274  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-16 13:20:09.275  6781  6781 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 13:20:09.276  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 13:20:09.277  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 13:20:09.289  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,08-16 13:20:09.290  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 13:20:09.293  6781  6781 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471346409291]
08-16 13:20:09.298  6781  6781 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 13:20:09.300  1049  2069 I ActivityManager: Killing 6396:com.lge.email/u0a23 (adj 15): empty #17
08-16 13:20:09.332  6781  6896 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 13:20:09.339  1049  2111 W libprocessgroup: failed to open /acct/uid_10023/pid_6396/cgroup.procs: No such file or directory
08-16 13:20:09.339  6873  6873 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:09.345  6873  6873 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:20:09.345  6781  6781 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-16 13:20:09.345  6873  6873 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:20:09.345  6781  6781 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 13:20:09.345  6873  6873 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 13:20:09.345  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 13:20:09.345  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 13:20:09.346  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 13:20:09.346  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 13:20:09.346  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 13:20:09.346  6873  6873 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:09.346  6873  6873 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-16 13:20:09.356  6801  6801 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-16 13:20:09.363  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 13:20:09.368  1049  1758 I ActivityManager: Killing 6055:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-16 13:20:09.401  1049  1984 W libprocessgroup: failed to open /acct/uid_10027/pid_6055/cgroup.procs: No such file or directory
,08-16 13:20:10.465  1049  1064 D WifiServiceImplEx: setWifiEnabled: true pid=6636, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 13:20:10.466  1049  1064 D WifiService: setWifiEnabled: true pid=6636, uid=10118
08-16 13:20:10.466  1049  1064 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:20:10.494  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:20:10.494  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 13:20:10.494  1049  1049 D Ulp_jni : JNI:system_update. Event-4
,08-16 13:20:10.497  1049  1536 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 13:20:10.497  1049  1536 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 13:20:10.500  1049  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1049] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 13:20:10.500  1049  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 13:20:10.500  1049  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1049] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 13:20:10.500  1049  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 13:20:10.500  1049  1536 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 13:20:10.500  1049  1536 E WifiHW  : unknown target_country: EU , set to default
08-16 13:20:10.500  1049  1536 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 13:20:10.500  1049  1536 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 13:20:10.501  1049  1536 I WifiUtil: gEnableBmps=1
08-16 13:20:10.511  1049  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:20:10.521  1049  1131 D Tethering: MasterInitialState.processMessage what=3
08-16 13:20:10.527  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:20:10.531  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:10.531  1049  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:10.536  1049  1131 D Tethering: MasterInitialState.processMessage what=3
08-16 13:20:10.545  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:20:10.549  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:10.549  1049  1122 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:10.551  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 13:20:10.554  6296  6712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 13:20:10.568  5764  5764 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 13:20:10.575  5764  5764 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 13:20:10.592  2239  2239 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:20:10.635  1049  1122 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:20:10.665  1049  2018 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6921 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-16 13:20:10.673  1049  1122 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:10.673  1049  1122 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 13:20:10.720  6921  6921 I AppUp4:AppBoxCP: onCreate
08-16 13:20:10.721  6921  6921 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-16 13:20:10.727  6921  6921 I AppUp4:DB:  setFingerPrint start
08-16 13:20:10.727  6921  6921 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-16 13:20:10.733  6921  6921 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-16 13:20:10.733  6921  6921 I AppUp4:DB:  SDK version = 21
08-16 13:20:10.733  6921  6921 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-16 13:20:10.735  6921  6921 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-16 13:20:10.735  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 13:20:10.736  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE,
08-16 13:20:10.737  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 13:20:10.737  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 13:20:10.744  6921  6921 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 13:20:10.805  6921  6921 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:20:10.805  6921  6921 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:20:10.813  6921  6921 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@cce3a06
08-16 13:20:10.813  6921  6921 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 13:20:10.813  6921  6921 D AppUp4:CustFacade: isPhone : true
08-16 13:20:10.814  6921  6921 D AppUp4:CustModeStarterReceiver: begin check event
08-16 13:20:10.815  6921  6921 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-16 13:20:10.815  6921  6921 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-16 13:20:10.816  6921  6940 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-16 13:20:10.816  6921  6940 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-16 13:20:10.816  6921  6940 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-16 13:20:10.821  1049  1588 I ActivityManager: Killing 6118:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-16 13:20:10.881  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:20:10.882  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 13:20:10.884  1049  1963 W libprocessgroup: failed to open /acct/uid_10080/pid_6118/cgroup.procs: No such file or directory
,08-16 13:20:10.884  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:20:10.891  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:20:10.898  4326  6944 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 13:20:10.902  4326  6945 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:10.902  4326  6945 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 13:20:10.975  1049  2111 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6949 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 13:20:11.051  6949  6949 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 13:20:11.051  6949  6949 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:20:11.053  6949  6949 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 13:20:11.054  6949  6949 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 13:20:11.138  6949  6949 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 13:20:11.151  6949  6949 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 13:20:11.193  6949  6949 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 13:20:11.196  1049  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 13:20:11.204  1049  1131 D Tethering: InitialState.processMessage what=4
08-16 13:20:11.204  1049  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 13:20:11.219   306   907 D SoftapController: Softap fwReload - Ok
08-16 13:20:11.219  1049  1536 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (712ms)
,08-16 13:20:11.222   306   907 D CommandListener: Setting iface cfg
08-16 13:20:11.222   306   907 D CommandListener: Trying to bring down wlan0
08-16 13:20:11.223   306   907 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:20:11.227  1049  1536 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 13:20:11.237  1049  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:20:11.237  1049  1536 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:20:11.237  1049  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 13:20:11.241  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 13:20:11.227  6983  6983 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:11.227  6983  6983 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:11.249  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:11.250  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-16 13:20:11.257  1049  1536 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 13:20:11.257  1049  1536 D WifiMonitor: connecting to supplicant
08-16 13:20:11.258  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:11.259  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:11.264  6949  6949 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:20:11.264  6949  6949 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:20:11.273  6983  6983 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 13:20:11.319  6983  6983 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 13:20:11.320  6983  6983 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 13:20:11.377  6949  6949 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 13:20:11.408  6949  6949 I HubEmail: JNI_OnLoad()
08-16 13:20:11.408  6949  6949 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 13:20:11.409  6949  6949 I HubEmail: registerNatives()
08-16 13:20:11.409  6949  6949 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 13:20:11.409  6949  6949 I HubEmail: registerNativeMethods()
08-16 13:20:11.409  6949  6949 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 13:20:11.409  6949  6949 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 13:20:11.410  3370  3370 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-16 13:20:11.410  3370  3370 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:11.410  3370  3370 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 13:20:11.411  6983  6983 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 13:20:11.431  6983  6983 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 13:20:11.437  6983  6983 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-16 13:20:11.438  1049  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 13:20:11.438  1049  1536 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 13:20:11.438  1049  6998 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 13:20:11.438  1049  6998 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 13:20:11.438  1049  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 13:20:11.438  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 13:20:11.438  6983  6983 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 13:20:11.439  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 13:20:11.439  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 13:20:11.439  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 13:20:11.439  1049  6998 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 13:20:11.439  1049  1536 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 13:20:11.439  1049  6998 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 13:20:11.439  1049  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:11.440  1049  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:11.440  1049  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:11.440  1049  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:11.441  1049  1536 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 13:20:11.441  1049  1536 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 13:20:11.441  1049  1536 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 13:20:11.442  1049  1536 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 13:20:11.442  1049  1536 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 13:20:11.468  1049  1963 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6999 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-16 13:20:11.471  1049  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:20:11.471  1049  1536 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:20:11.471  1049  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 13:20:11.472  1049  1536 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 13:20:11.474  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:11.474  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:11.474  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:11.474  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 13:20:11.475  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:11.475  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 13:20:11.475  1966  1966 D WfdService: Waiting for WifiP2p enabling
08-16 13:20:11.475  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 13:20:11.477  1049  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 13:20:11.480  1049  1536 D WifiNative-wlan0: SET update_config 1: returned true
08-16 13:20:11.480  1049  1536 D WifiConfigStore: Loading config and enabling all networks 
08-16 13:20:11.480  1049  1536 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 13:20:11.480  1049  1536 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 13:20:11.482  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:11.482  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:20:11.482  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:11.482  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:11.482  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:11.482  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:20:11.482  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:11.482  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:11.482  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:20:11.482  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:11.482  6636  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:20:11.483  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:11.483  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:20:11.483  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:11.483  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:11.483  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:11.483  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:20:11.483  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:11.483  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:11.483  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:20:11.484  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:11.484  6636  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:20:11.486  1049  1536 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-16 13:20:11.492  6949  6997 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 13:20:11.493  6821  6994 W FormManager: Network not available. Please check & try again.
08-16 13:20:11.495  1049  1536 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 13:20:11.495  1049  1536 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 13:20:11.496  6821  6996 V FormManager: Network unavailable.
08-16 13:20:11.500  1049  1536 D WifiStateMachine: enableVerboseLogging : level 2
08-16 13:20:11.500  1049  1536 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 13:20:11.500  1049  1536 D WifiNative-wlan0: SET device_name g3_global_com: returned true
,08-16 13:20:11.500  1049  1536 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 13:20:11.501  1049  1536 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 13:20:11.501  1049  1536 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 13:20:11.501  1049  1536 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 13:20:11.501  1049  1536 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 13:20:11.502  1049  1536 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 13:20:11.502  1049  1536 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 13:20:11.502  1049  1536 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 13:20:11.502  1049  1536 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 13:20:11.502  1049  1536 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 13:20:11.502  1049  1536 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
,08-16 13:20:11.503  1049  1536 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 13:20:11.503  6821  6996 V FormManager: Network unavailable.
08-16 13:20:11.503  1049  1536 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 13:20:11.503  1049  1536 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 13:20:11.504  1049  1536 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 13:20:11.504  1966  1966 D WfdsService: Supplicant Connection state is changed : true
08-16 13:20:11.504  1049  1536 D WifiNative-HAL: Setting external_sim to 1
08-16 13:20:11.504  1049  1536 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 13:20:11.504  1966  2321 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 13:20:11.504  1966  2321 D WfdsService: Set the WFDS Monitor: true
08-16 13:20:11.504  1966  2321 D WfdsMonitor: WfdsMonitorThread create
08-16 13:20:11.504  1966  2321 D WfdsMonitor: WFDS Monitor is created and started
08-16 13:20:11.504  1966  2321 D WfdsService: WiFi: Supplicant connection re-established
08-16 13:20:11.504  1049  1536 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 13:20:11.504  1049  1536 I WifiNative-HAL: startHal
08-16 13:20:11.504  1049  1536 D wifi    : setting scan oui 0x957c7120
08-16 13:20:11.505  1049  1536 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 13:20:11.505  1049  1536 I WifiNative-HAL: startHal
08-16 13:20:11.505  1049  1536 D wifi    : setting scan oui 0x957c7120
08-16 13:20:11.505  1049  1536 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 13:20:11.505  1966  7013 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 13:20:11.505  1966  7013 E CtrlSupplicant: Succeed to open control connection
08-16 13:20:11.506  1049  1536 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 13:20:11.506  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 13:20:11.506  1966  7013 E CtrlSupplicant: Succeed to open monitor connection
08-16 13:20:11.506  6983  6983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 13:20:11.506  1049  1536 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 13:20:11.506  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 13:20:11.506  6983  6983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 13:20:11.507  1966  7013 D WfdsMonitor: Supplicant connection established
08-16 13:20:11.507  1049  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 13:20:11.507  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 13:20:11.507  1966  2321 D WfdsService: Connected to the supplicant for wfds
08-16 13:20:11.507  6983  6983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 13:20:11.507  1049  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 13:20:11.507  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 13:20:11.508  6983  6983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 13:20:11.508  1049  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 13:20:11.508  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 13:20:11.508  6983  6983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 13:20:11.508  1049  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 13:20:11.508  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 13:20:11.508  6983  6983 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 13:20:11.509  1049  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 13:20:11.509  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 13:20:11.509  6983  6983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 13:20:11.509  1049  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 13:20:11.510  1049  1536 E WifiNative: : [205,737,914 us] RECONNECT  stack:logDbg - rec,onnect - enter - invokeEnterMethods - performTransitions
08-16 13:20:11.510  1049  1536 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 13:20:11.511  1049  1536 D WifiNative-wlan0: RECONNECT: returned true
08-16 13:20:11.511  1049  1536 D WifiNative-wlan0: doString: [STATUS]
08-16 13:20:11.511  1049  1536 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 13:20:11.511  1049  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 13:20:11.512  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 13:20:11.512  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 13:20:11.512  1049  1536 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:20:11.512  1049  1535 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.513  1049  1536 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 13:20:11.513  1049  1049 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 13:20:11.513  1049  1049 D RttService: SCAN_AVAILABLE : 3
08-16 13:20:11.514  1049  1536 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 13:20:11.514   306   907 D CommandListener: Setting iface cfg
08-16 13:20:11.514   306   907 D CommandListener: Trying to bring up p2p0
08-16 13:20:11.514  1049  1536 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 13:20:11.514  1049  1554 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.514  1049  1554 I WifiNative-HAL: startHal
08-16 13:20:11.514  1049  1554 D wifi    : getting scan capabilities on interface[1] = 0x957c7120
08-16 13:20:11.514  1049  1554 D wifi    : failed to get capabilities : -3
08-16 13:20:11.514  1049  1554 E WifiScanningService: could not get scan capabilities
08-16 13:20:11.514  1049  1536 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 13:20:11.514  1049  1555 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.515  1049  1535 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 13:20:11.515  1049  1535 D LGWifiP2pService: P2pEnablingState
08-16 13:20:11.515  1049  1535 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.515  1049  1535 D LGWifiP2pService: P2p socket connection successful
08-16 13:20:11.515  1049  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=205743  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 13:20:11.515  1049  1535 D LGWifiP2pService: P2pEnabledState
08-16 13:20:11.515  1049  1535 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 13:20:11.516  1049  1535 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
,08-16 13:20:11.516  1049  1535 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 13:20:11.516  1049  1535 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 13:20:11.517  1049  1535 D WifiNative-p2p0: SET device_name G3: returned true
08-16 13:20:11.517  1049  1535 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 13:20:11.517  1049  1535 D LGWifiP2pService: before postfix = G3
08-16 13:20:11.517  1049  1535 D WifiServerServiceExt: postfix byte check : 2
08-16 13:20:11.517  1049  1535 D LGWifiP2pService: after postfix = G3
08-16 13:20:11.517  1049  1535 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 13:20:11.517  1049  1535 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 13:20:11.518  1049  1535 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 13:20:11.518  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 13:20:11.518  1966  1966 D WfdsService: WifiP2pState is changed : true
08-16 13:20:11.518  1966  2321 D WfdsService: Receive the WFDS_ENABLE Method
08-16 13:20:11.518  1966  2321 D WfdsService: Set the WFDS Monitor: true
08-16 13:20:11.518  1049  1535 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 13:20:11.518  1966  2321 D WfdsService: Connected to the supplicant for wfds
08-16 13:20:11.518  1049  1535 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 13:20:11.518  1966  2321 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 13:20:11.518  6983  6983 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 13:20:11.518  1966  2321 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
08-16 13:20:11.518  6983  6983 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
08-16 13:20:11.518  1966  2321 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
08-16 13:20:11.519  1049  1535 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 13:20:11.519  1049  1535 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 13:20:11.519  1049  1535 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 13:20:11.519  1966  2321 D WfdsService: selectPreferredScanChannel [36]
08-16 13:20:11.519  1049  1535 D WifiNative-HAL: p2pGetDeviceAddress
08-16 13:20:11.519  1966  2321 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 13:20:11.519  1049  1535 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 13:20:11.520  1049  1535 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 13:20:11.520  1049  1535 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 13:20:11.520  1966  1966 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 13:20:11.520  1049  1535 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 13:20:11.520  1049  1535 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 13:20:11.520  1049  1535 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 13:20:11.520  1049  1535 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 13:20:11.520  1966  1966 D WfdsService: isConnected: false
08-16 13:20:11.521  1049  1535 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 13:20:11.521  1049  1535 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 13:20:11.521  1966  1966 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 13:20:11.521  1966  1966 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 13:20:11.521  1966  1966 D WfdsService: Update P2p Interface State: 3
08-16 13:20:11.523  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:11.523  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:11.525  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=205753  SS,ID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 13:20:11.526  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:11.526  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:11.526  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 13:20:11.526  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:11.527  1049  1933 I ActivityManager: Killing 6431:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-16 13:20:11.528  1049  1536 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 13:20:11.528  1049  1536 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 13:20:11.528  1049  1536 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 13:20:11.528  1049  1536 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-16 13:20:11.530  6983  6983 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 13:20:11.530  1049  1535 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 13:20:11.531  1049  1535 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 13:20:11.531  1049  1536 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 13:20:11.531  1049  1536 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 13:20:11.532  1049  1536 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 13:20:11.532  1049  1536 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 13:20:11.532  6983  6983 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 13:20:11.532  1049  1536 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 13:20:11.533  1049  1536 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 13:20:11.533  1049  1536 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 13:20:11.533  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 13:20:11.534  6983  6983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 13:20:11.534  6983  6983 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:11.534  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 13:20:11.534  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:11.534  1049  6998 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:11.534  1049  6998 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:11.535  6983  6983 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 13:20:11.535  6983  6983 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:11.535  1966  7013 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:11.535  1049  6998 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:11.535  1049  6998 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:11.535  1049  6998 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:11.535  1049  6998 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:11.535  1049  1536 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 13:20:11.535  6983  6983 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:11.535  1966  7013 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:11.535  1049  6998 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:11.535  1049  6998 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:11.536  1049  6998 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:11.536  1049  6998 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:11.536  1049  1536 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 13:20:11.536  1049  1536 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 13:20:11.536  1049  1536 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 13:20:11.536  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 13:20:11.537  6983  6983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 13:20:11.537  6983  6983 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 13:20:11.537  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 13:20:11.537  1049  6998 E Wi,fiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 13:20:11.537  1049  6998 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 13:20:11.537  1049  6998 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 13:20:11.538  1049  1536 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 13:20:11.538  1049  1536 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 13:20:11.538  1049  1536 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 13:20:11.538  1049  1536 D WifiNative-wlan0: doBoolean: SCAN
08-16 13:20:11.538  1049  1536 D WifiNative-wlan0: SCAN: returned false
08-16 13:20:11.539  1049  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=205767  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 13:20:11.578  1049  1535 D LGWifiP2pService: InactiveState
08-16 13:20:11.578  1049  1535 D LGWifiP2pService: InactiveState{ when=-57ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.578  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=-57ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.578  1049  1535 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-16 13:20:11.578  6983  6983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 13:20:11.579  6983  6983 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:11.579  1049  6998 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 13:20:11.579  1049  6998 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:11.579  1049  6998 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:11.579  1049  6998 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:11.579  6983  6983 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 13:20:11.579  6983  6983 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:11.580  6983  6983 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:11.580  1966  7013 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 13:20:11.580  1966  7013 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:11.580  1966  7013 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:11.580  1049  1535 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 13:20:11.580  1049  1535 D LGWifiP2pService: InactiveState{ when=-45ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.580  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=-45ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.580  1049  1535 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.580  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.581  1049  1535 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.581  1049  1535 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.581  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.581  1049  1535 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.581  1049  1535 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.581  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.581  1049  1535 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.581  1049  1535 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.581  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.581  1049  1535 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:11.581  1049  1049 E WifiServerServiceExt: No p2p device connected
08-16 13:20:11.581  1049  6998 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:11.581  1049  6998 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:11.581  1966  2321 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 13:20:11.581  1049  6998 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20,:11.581  1049  6998 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:11.581  1049  6998 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:11.581  1049  6998 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:11.582  1049  6998 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:11.582  1049  6998 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:11.584  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=205812  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 13:20:11.584  1049  2069 W libprocessgroup: failed to open /acct/uid_10061/pid_6431/cgroup.procs: No such file or directory
08-16 13:20:11.584  1049  1536 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:20:11.585  1049  1536 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:20:11.585  1049  1536 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:20:11.585  1049  1536 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:20:11.586  1049  1536 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:20:11.587  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:11.587  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:11.588  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:11.588  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:11.588  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:11.588  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 13:20:11.589  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:11.589  1049  1049 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 13:20:11.590  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:11.590  1049  1049 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-16 13:20:11.635  6999  6999 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:20:11.635  6999  6999 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:20:11.638  6999  6999 D PhoneMonitor: Register our PhoneStateListener
,08-16 13:20:11.653  6999  6999 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 13:20:11.657  6999  6999 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 13:20:11.677  6999  6999 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-16 13:20:11.677  6999  6999 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 13:20:11.678  6999  6999 D TelephonyAutoProfiling: [parse] Load xml
08-16 13:20:11.681  6999  6999 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 13:20:11.681  6999  6999 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 13:20:11.681  6999  6999 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 13:20:11.681  6999  6999 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 13:20:11.681  6999  6999 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 13:20:11.681  6999  6999 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 13:20:11.681  6999  6999 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 13:20:11.681  6999  6999 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 13:20:11.681  6999  6999 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 13:20:11.682  6999  6999 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 13:20:11.682  6999  6999 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
,08-16 13:20:11.682  6999  6999 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 13:20:11.682  6999  6999 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 13:20:11.682  6999  6999 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 13:20:11.682  6999  6999 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 13:20:11.682  6999  6999 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 13:20:11.682  6999  6999 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-16 13:20:11.690  6999  6999 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-16 13:20:11.711  1049  2018 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7019 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 13:20:11.712  1049  2018 I ActivityManager: Killing 6138:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-16 13:20:11.800  1049  1064 W libprocessgroup: failed to open /acct/uid_10097/pid_6138/cgroup.procs: No such file or directory
,08-16 13:20:12.051  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 13:20:12.051  1049  6998 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 13:20:12.051  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 13:20:12.051  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-16 13:20:12.052  1049  6998 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 13:20:12.052  6983  6983 E wpa_supplicant: USIM:  scard_init function
08-16 13:20:12.053  1049  1536 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 13:20:12.053  6983  6983 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 13:20:12.054  1049  1536 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 13:20:12.054  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 13:20:12.054  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 13:20:12.055  1049  1536 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 13:20:12.056  1049  1536 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 13:20:12.056  1049  1536 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-16 13:20:12.089  1049  1963 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7040 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-16 13:20:12.090  1049  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=206318  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 13:20:12.091  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=206319  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 13:20:12.094  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:12.094  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:12.097  1049  1963 I ActivityManager: Killing 6484:com.lge.eula/1000 (adj 15): empty #17
08-16 13:20:12.101  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.101  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.101  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 13:20:12.101  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:12.101  1049  1049 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 13:20:12.103  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:20:12.148  1049  1933 W libprocessgroup: failed to open /acct/uid_1000/pid_6484/cgroup.procs: No such file or directory
,08-16 13:20:12.168  6983  6983 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 13:20:12.170  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 13:20:12.170  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 13:20:12.170  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 13:20:12.170  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 13:20:12.170  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:20:12.170  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:20:12.171  1049  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 13:20:12.172  1049  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=206400  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 13:20:12.172  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=206400  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 13:20:12.173  1049  1536 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206401
08-16 13:20:12.173  1049  1536 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206401
08-16 13:20:12.173  1049  1536 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206402
08-16 13:20:12.174  1049  1536 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206402
,08-16 13:20:12.182  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:20:12.182  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:20:12.183  6983  6983 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 13:20:12.183  1049  1536 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206411
08-16 13:20:12.183  6983  6983 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 13:20:12.184  1049  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=206412  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 13:20:12.185  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 13:20:12.185  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 13:20:12.185  1049  6998 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 13:20:12.186  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 13:20:12.186  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 13:20:12.186  1049  6998 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 13:20:12.186  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:20:12.186  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:20:12.190  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:12.190  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 13:20:12.191  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.191  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.191  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 13:20:12.194  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:20:12.194  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=206422  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 13:20:12.197  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.197  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.197  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 13:20:12.198  1049  1536 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:12.199  1049  1536 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:12.199  1049  1536 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:12.199  1049  1536 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:12.200  1049  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:12.200  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:12.200  1049  1049 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 13:20:12.201  1049  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=206429  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 13:20:12.201  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=206429  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 13:20:12.202  1049  1536 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206430
08-16 13:20:12.202  1049  1536 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206431
,08-16 13:20:12.203  1049  1536 D WifiNative-wlan0: doString: [STATUS]
08-16 13:20:12.204  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:20:12.204  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:20:12.205  1049  1536 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 13:20:12.207  1049  1536 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 13:20:12.216  1049  1536 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 13:20:12.216  1049  1536 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 13:20:12.217  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:12.217  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:12.218  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:20:12.220  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.220  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.221  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 13:20:12.224  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.224  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.224  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 13:20:12.231  1049  1536 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-16 13:20:12.233  1049  1543 D ConnectivityService: Got NetworkAgent Messenger
08-16 13:20:12.233  1049  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 13:20:12.233  1049  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 13:20:12.233  1049  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 13:20:12.233  1049  1543 D ConnectivityService: NetworkAgent connected
08-16 13:20:12.234  1049  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 13:20:12.234  1049  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 13:20:12.241  1049  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 13:20:12.241  1049  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 13:20:12.241  1049  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 13:20:12.242  1049  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 13:20:12.242  1049  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 13:20:12.244  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:12.244  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 13:20:12.245  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:12.247  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:12.247  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:12.248  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:12.249  1049  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 13:20:12.251   306   907 D CommandListener: Setting iface cfg
08-16 13:20:12.304  1049  1065 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7064 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 13:20:12.304  1049  1536 E WifiStateMachine: Start Dhcp Watchdog 2
08-16 13:20:12.304  1049  7058 D DhcpStateMachine: StoppedState
08-16 13:20:12.305  1049  7058 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:12.305  1049  7058 D DhcpStateMachine: WaitBeforeStartState
08-16 13:20:12.305  1049  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=206533  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:20:12.306  1049  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=206534  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:20:12.306  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=206534  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:20:12.307  1049  1065 I ActivityManager: Killing 6501:com.lge.bnr/1000 (adj 15): empty #17
08-16 13:20:12.359  1049  1064 W libprocessgroup: failed to open /acct/uid_1000/pid_6501/cgroup.procs: No such file or directory
,08-16 13:20:12.370  1049  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=206598  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:20:12.370  1049  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=206598  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:20:12.370  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:12.371  1049  1049 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 13:20:12.371  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=206599  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:20:12.372  1049  1536 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:161048] from screen [on:0 period:-1827370156] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:20:12.374  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1827370155] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:20:12.374  1049  1536 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:20:12.377  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:12.379  1049  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-16 13:20:12.379  1049  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:12.380  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:12.380  1049  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 13:20:12.381  1049  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:12.381  1049  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:12.382  1049  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:12.382  1049  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 13:20:12.383  1049  1536 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=174,0,0
08-16 13:20:12.383  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=174,0,0
08-16 13:20:12.383  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 13:20:12.384  6983  6983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 13:20:12.384  1049  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 13:20:12.384  1049  1536 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 13:20:12.384  1049  1536 D WifiNative-wlan0: SET ps 0: returned true
08-16 13:20:12.385  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 13:20:12.385  6983  6983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 13:20:12.385  1049  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 13:20:12.387  1049  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1b89f6d8 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:12.387  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1b89f6d8 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:12.387  1049  1536 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 13:20:12.387  1049  7058 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:12.388  1049  7058 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 13:20:12.388  1049  1536 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 13:20:12.388  1049  1536 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-16 13:20:12.390   306   907 D CommandListener: Setting iface cfg
08-16 13:20:12.390   306   907 D CommandListener: Trying to bring up wlan0
08-16 13:20:12.391  1049  1536 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 13:20:12.392  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:12.392  1049  1049 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 13:20:12.393  1049  1536 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-16 13:20:12.393  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:12.393  1049  1049 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 13:20:12.393  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-16 13:20:12.394  1049  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:12.394  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:12.394  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 13:20:12.394  6983  6983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 13:20:12.395  1049  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 13:20:12.395  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 13:20:12.395  6983  6983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 13:20:12.396  1049  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 13:20:12.396  1049  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 13:20:12.408  7064  7064 I art     : Almond Protected OAT
,08-16 13:20:12.413  1049  1536 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:20:12.414  1049  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 13:20:12.414  1049  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:12.415  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:12.415  1049  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:12.416  1049  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:12.416  1049  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:12.417  1049  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:12.419  1049  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 13:20:12.419  1049  1536 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 13:20:12.420  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 13:20:12.420  1049  1536 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 13:20:12.420  1049  1543 D ConnectivityService: ignoring duplicate network state non-change
08-16 13:20:12.421  1049  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 13:20:12.422  1049  1543 D ConnectivityService: Adding iface wlan0 to network 101
08-16 13:20:12.423  1049  1536 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 13:20:12.433  1049  1535 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:12.433  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:12.433  1049  1535 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:12.460  1049  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 13:20:12.460  1049  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-16 13:20:12.461  1049  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 13:20:12.462   306   907 E Netd    : netlink response contains error (File exists)
08-16 13:20:12.463  1049  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-16 13:20:12.464  1049  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 13:20:12.464  1049  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-16 13:20:12.464  1049  1543 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-16 13:20:12.465  1049  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 13:20:12.465  1049  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 13:20:12.465  1049  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 13:20:12.466  1049  7057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:12.466  1049  7057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 13:20:12.466  1049  7057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:12.466  1049  7057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 13:20:12.468  1049  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 13:20:12.468  1049  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:20:12.468  1049  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:12.468  1049  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 13:20:12.468  1049  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:12.468  1049  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 13:20:12.468  1049  1543 D ConnectivityService: currentScore = 0, newScore = 20
08-16 13:20:12.468  1049  1543 D ConnectivityService:    accepting network in place of null
08-16 13:20:12.468  1049  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:12.469   306  7085 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 13:20:12.469  1049  1536 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:12.469  1049  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:20:12.470  1876  1876 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:12.470  1876  1876 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 13:20:12.471  1049  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe8,0::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 13:20:12.471  1049  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 13:20:12.471  1049  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 13:20:12.472  1049  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:12.472  1049  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 13:20:12.472  1049  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 13:20:12.473  1049  1543 D ConnectivityService: validation of new default Network = false
08-16 13:20:12.473  1049  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 13:20:12.474  1049  1543 D DSQN    : enableDataServiceNotify 
08-16 13:20:12.474  1049  1543 D DSQN    : start dsqn bin
,08-16 13:20:12.481  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:12.481  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:12.483  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:12.483  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.483  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.483  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 13:20:12.486  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:12.486  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:12.488  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:20:12.489  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.489  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.489  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 13:20:12.489  1049  1049 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 13:20:12.490  1049  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 13:20:12.477  7086  7086 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:12.477  7086  7086 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:12.492  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:12.493  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:12.493  1049  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:12.493  1966  1966 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 13:20:12.494  1602  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 13:20:12.495  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 13:20:12.495  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.495  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 13:20:12.497  1049  1049 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 13:20:12.503  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.503  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:12.503  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-16 13:20:12.507  1049  1049 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 13:20:12.508  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 13:20:12.508  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 13:20:12.508  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 13:20:12.508  7086  7086 E DSQN    : DSQN ssw
08-16 13:20:12.508  1049  1536 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 13:20:12.509  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 13:20:12.509  1049  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 13:20:12.509  1049  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 13:20:12.511  1049  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 13:20:12.512  1049  1536 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 13:20:12.515  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:12.515  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 13:20:12.516  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:20:12.517  7064  7064 D WeatherApplication: removeAccount
08-16 13:20:12.519  7064  7064 D WeatherApplication: Account.length = 0
08-16 13:20:12.519  7064  7064 E WeatherApplication: OPERATOR:OPEN
08-16 13:20:12.526  7064  7064 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:20:12
08-16 13:20:12.528  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:12.531  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 13:20:12.531  7064  7064 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 13:20:12.531  7064  7064 D Weather.Utils: 2 : All the weather widget is gone.
08-16 13:20:12.533  7064  7064 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 13:20:12.535  7064  7064 D WeatherAncestor: connectivity changed - connection : true
,08-16 13:20:12.538   306  7085 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 13:20:12.538  7064  7064 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-16 13:20:12.539  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:12.540  1049  1534 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 13:20:12.549  1841  7090 I CheckinService: active receiver: enabled
,08-16 13:20:12.568  7064  7064 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 13:20:12.568  7064  7064 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 13:20:12.568  7064  7064 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-16 13:20:12.569  1841  7090 I CheckinService: Preparing to send checkin request
08-16 13:20:12.569  1841  7090 I EventLogService: Accumulating logs since 1471346263666
08-16 13:20:12.569   306  7085 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 13:20:12.589  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 13:20:12.590  1049  7058 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 13:20:12.590  1049  7058 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 13:20:12.590  1049  7058 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 13:20:12.590  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:20:12.592  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:12.597  7093  7093 I dhcpcd  : version 5.5.6 starting
08-16 13:20:12.599  7093  7093 E dhcpcd  : get_duid: m
08-16 13:20:12.600  7093  7093 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 13:20:12.600  7093  7093 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 13:20:12.600  7064  7064 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 13:20:12.600  7064  7064 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:20:12
08-16 13:20:12.577  7093  7093 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:12.577  7093  7093 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:12.603   306   906 D LGDataListener: argv[0]=dsqncommand
08-16 13:20:12.603   306   906 D LGDataListener: argv[1]=wlan0
08-16 13:20:12.603   306   906 D LGDataListener: argv[2]=1
08-16 13:20:12.603   306   906 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 13:20:12.614  1049  1129 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 13:20:12.614  1049  1129 D DSQN    : start to monitor internet connection
,08-16 13:20:12.627  1049  2111 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7098 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 13:20:12.628  1049  2111 I ActivityManager: Killing 2222:com.lge.music/u0a34 (adj 15): empty #17
08-16 13:20:12.630  1049  7057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 11:20:12 GMT], X-Android-Received-Millis=[1471346412630], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471346412600]}
08-16 13:20:12.630  1049  7057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 13:20:12.630  1049  7057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 13:20:12.631  1049  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-16 13:20:12.631  1049  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 13:20:12.631  1049  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:20:12.631  1049  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:12.631  1049  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 13:20:12.631  1049  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-16 13:20:12.631  1049  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 13:20:12.631  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:12.631  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:12.631  1049  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:12.631  1049  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:12.632  1049  1536 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:12.632  1049  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 13:20:12.632  1049  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:20:12.632  1602  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 13:20:12.633  1876  1876 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:12.633  1876  1876 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 13:20:12.648   310  1785 V AudioFlinger: 2222 died, releasing its sessions
08-16 13:20:12.648   310  1785 V AudioFlinger:  pid 1876 @ 0
08-16 13:20:12.648   310  1785 V AudioFlinger:  pid 3370 @ 1
08-16 13:20:12.648   310  1785 V AudioFlinger:  pid 3370 @ 2
,08-16 13:20:12.660  7093  7093 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 13:20:12.660  7093  7093 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-16 13:20:12.660  7093  7093 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 13:20:12.660  7093  7093 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 13:20:12.660  7093  7093 D dhcpcd  : wlan0: sending REQUEST (xid 0xf0764a68), next in 3.17 seconds
08-16 13:20:12.671  1049  2018 W libprocessgroup: failed to open /acct/uid_10034/pid_2222/cgroup.procs: No such file or directory
,08-16 13:20:12.672  1841  7090 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 13:20:12.676  7093  7093 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 13:20:12.686  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-16 13:20:12.687  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:12.687  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:12.697  7093  7093 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 13:20:12.697  7093  7093 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 13:20:12.697  7093  7093 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 13:20:12.698  7093  7093 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 13:20:12.698  7093  7093 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 13:20:12.698  7093  7093 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 13:20:12.698  7093  7093 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 13:20:12.698  7093  7093 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-16 13:20:12.754   277   472 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-16 13:20:12.754   277   472 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 13:20:12.754   277   472 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 13:20:12.755  7098  7127 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 13:20:12.757   277   472 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 13:20:12.757   277   472 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 13:20:12.757   277   472 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 13:20:12.757  1049  1933 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7130 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-16 13:20:12.758  7098  7127 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-16 13:20:12.788   277   472 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 13:20:12.788   277   472 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 13:20:12.788   277   472 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 13:20:12.789  7098  7138 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 13:20:12.794  7130  7130 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 13:20:12.794  7130  7130 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 13:20:12.798   277   472 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 13:20:12.798   277   472 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 13:20:12.798   277   472 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 13:20:12.799  7098  7138 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 13:20:12.811  7130  7130 I MultiDex: VM with version 2.1.0 has multidex support
,08-16 13:20:12.811  7130  7130 I MultiDex: install
08-16 13:20:12.812  7130  7130 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-16 13:20:12.821  7130  7130 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-16 13:20:12.960  7098  7098 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 13:20:12.966  7098  7098 I LibraryLoader: Loading: webviewchromium
08-16 13:20:12.969  7098  7098 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7208-7211)
08-16 13:20:12.969  7098  7098 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 13:20:12.974  7098  7098 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {15425889}
08-16 13:20:12.975  7098  7098 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 13:20:12.975  7098  7098 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 13:20:12.984  7098  7098 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 13:20:12.984  7098  7098 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 13:20:12.992  1049  7058 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-16 13:20:12.993  1049  7058 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-16 13:20:12.993  1049  7058 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 13:20:12.993  1049  7058 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 13:20:12.993  1049  7058 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 13:20:12.993  1049  7058 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 13:20:12.993  1049  7058 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 13:20:12.993  1049  7058 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 13:20:12.994  1049  7058 D DhcpStateMachine: RunningState
08-16 13:20:13.000   310  1385 V AudioPolicyService: registerClient() client 0xb558aba0, uid 10093
08-16 13:20:13.001  7098  7183 W AudioManagerAndroid: Requires BLUETOOTH permission
08-16 13:20:13.001  7098  7098 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 13:20:13.002  7098  7098 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 13:20:13.002  7098  7098 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-16 13:20:13.025  7098  7098 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:20:13.025  7098  7098 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:20:13.025  7098  7098 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:20:13.025  7098  7098 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:20:13.025  7098  7098 I Adreno-EGL: Remote Branch: 
08-16 13:20:13.025  7098  7098 I Adreno-EGL: Local Patches: 
08-16 13:20:13.025  7098  7098 I Adreno-EGL: Reconstruct Branch: 
,08-16 13:20:13.119  7098  7098 I NSApplication: Starting up...
,08-16 13:20:13.149  7130  7149 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:20:13.150  7130  7149 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:20:13.230  1049  2011 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7196 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-16 13:20:13.231  1049  2011 I ActivityManager: Killing 6079:com.android.vending/u0a44 (adj 15): empty #17
,08-16 13:20:13.253   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 20.960ms
,08-16 13:20:13.273   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 386us total 19.255ms
,08-16 13:20:13.289   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 294us total 14.886ms
,08-16 13:20:13.311  1049  1933 W libprocessgroup: failed to open /acct/uid_10044/pid_6079/cgroup.procs: No such file or directory
,08-16 13:20:13.353  7196  7196 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 13:20:13.391  1049  1536 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:13.392  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:13.393  1049  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:13.394  7213  7213 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-16 13:20:13.395  1049  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:13.396  1049  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 13:20:13.398  1049  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:13.399  1049  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-16 13:20:13.399  1049  1543 D ConnectivityService: identical MTU - not setting
08-16 13:20:13.399  1049  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 13:20:13.399  1049  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 13:20:13.399  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:13.399  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:13.400  1049  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:13.401  1602  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-16 13:20:13.459  7213  7213 I dex2oat : dex2oat took 65.281ms (threads: 4)
08-16 13:20:13.478  7130  7149 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:20:13.478  7130  7149 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:20:13.478  7130  7149 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:20:13.478  7130  7149 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:20:13.478  7130  7149 I Adreno-EGL: Remote Branch: 
08-16 13:20:13.478  7130  7149 I Adreno-EGL: Local Patches: 
08-16 13:20:13.478  7130  7149 I Adreno-EGL: Reconstruct Branch: 
,08-16 13:20:13.490  1049  1543 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-16 13:20:13.501  1049  2011 D WifiServiceImplEx: setWifiEnabled: false pid=6636, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 13:20:13.501  1049  2011 D WifiService: setWifiEnabled: false pid=6636, uid=10118
08-16 13:20:13.501  1049  2011 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:20:13.518  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:20:13.518  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 13:20:13.518  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-16 13:20:13.520  1049  1536 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 13:20:13.521  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 13:20:13.522  1049  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 13:20:13.523  1049  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 13:20:13.529  1049  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 13:20:13.529  1049  1536 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 13:20:13.529  1049  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 13:20:13.529  1049  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 13:20:13.532  1049  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 13:20:13.532  1049  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-16 13:20:13.541  1049  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 13:20:13.541  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 13:20:13.541  6983  6983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 13:20:13.542  1049  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:13.542  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:13.544  1049  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 13:20:13.544  1049  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 13:20:13.545  1049  1536 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:20:13.545   306   907 D CommandListener: Clearing all IP addresses on wlan0
,08-16 13:20:13.548  1049  7058 D DhcpStateMachine: RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:13.573  1049  2018 I art     : Explicit concurrent mark sweep GC freed 101613(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.025ms total 112.769ms
,08-16 13:20:13.578  1049  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 13:20:13.578  1049  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-16 13:20:13.580  1049  1536 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 13:20:13.581  1049  1535 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:13.581  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:13.581  1049  1535 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3b06f614
08-16 13:20:13.581  1049  1049 D WifiHS20: hidePasspointNotification off =false
,08-16 13:20:13.595  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:13.595  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:13.595  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:13.596  1966  1966 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 13:20:13.597  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:13.597  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:13.598  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:13.598  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:13.598  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 13:20:13.598  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-16 13:20:13.598  1049  1535 D LGWifiP2pService: P2pDisablingState
08-16 13:20:13.598  1049  1535 D LGWifiP2pService: P2pDisablingState{ when=-17ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:13.598  1049  1535 D LGWifiP2pService: p2p socket connection lost
08-16 13:20:13.599  1049  1535 D LGWifiP2pService: P2pDisabledState
08-16 13:20:13.599  1049  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 13:20:13.599  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:13.600  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 13:20:13.600  6983  6983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 13:20:13.600  1049  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 13:20:13.600  1049  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 13:20:13.600  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 13:20:13.600  1049  1536 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:20:13.600  1966  1966 D WfdsService: WifiP2pState is changed : false
08-16 13:20:13.600  1966  2321 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 13:20:13.600  1966  2321 D WfdsService: Set the WFDS Monitor: false
08-16 13:20:13.601  1966  2321 D WfdsMonitor: WFDS Monitor is stopped
08-16 13:20:13.601  1966  2321 D WfdsService: STATE : WfdsDisabledState - enter
08-16 13:20:13.601  1966  7013 D CtrlSupplicant: Received on exit socket, terminate
08-16 13:20:13.601  1966  7013 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 13:20:13.601  1966  7013 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 13:20:13.601  1966  7013 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 13:20:13.602  1966  2324 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 13:20:13.602  1966  2321 W WfdsService: DefaultState - msg [9445378] is not handled
,08-16 13:20:13.602  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:13.602  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:13.602  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 13:20:13.602  1049  1049 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 13:20:13.603  1049  1049 D RttService: SCAN_AVAILABLE : 1
08-16 13:20:13.603  1049  1554 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:13.603  1049  1555 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:13.603  1049  1535 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:13.603  1049  1535 D LGWifiP2pService: DefaultState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:13.613  7130  7149 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:20:13.613  7130  7149 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:20:13.613  7130  7149 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:20:13.613  7130  7149 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:20:13.613  7130  7149 I Adreno-EGL: Remote Branch: 
08-16 13:20:13.613  7130  7149 I Adreno-EGL: Local Patches: 
08-16 13:20:13.613  7130  7149 I Adreno-EGL: Reconstruct Branch: 
08-16 13:20:13.615   306   907 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:20:13.615  1049  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 13:20:13.615  1049  1543 D DSQN    : disableDataServiceNotify
08-16 13:20:13.615  1049  1543 D DSQN    : stop dsqn bin
,08-16 13:20:13.617  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-16 13:20:13.617  1049  1536 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 13:20:13.618  1049  1536 D WifiNative-p2p0: TERMINATE: returned true
08-16 13:20:13.618  1049  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:20:13.618  1049  1536 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:20:13.618  1049  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 13:20:13.620  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 13:20:13.620  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:13.621  1049  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 13:20:13.621  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:13.621  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:13.621  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:13.622  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:13.622  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:13.622  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 13:20:13.623  1049  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:13.623  1049  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 13:20:13.623  1049  7057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 13:20:13.623  1602  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 13:20:13.623  1049  7057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 13:20:13.623  1049  7057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 13:20:13.623  1049  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 13:20:13.623  1049  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 13:20:13.623  1049  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 13:20:13.623  1049  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:13.624  1049  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 13:20:13.624  1049  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:13.624  1049  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:13.624  1049  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:13.624  1049  1543 D NetworkManagementService: Removing idletimer
08-16 13:20:13.624  1049  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:13.624  1876  1876 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:13.624  1049  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 13:20:13.624  1876  1876 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 13:20:13.625  1049  1536 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:13.625  1049  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:20:13.626  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 13:20:13.627  1049  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 13:20:13.627  1049  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 13:20:13.628  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:13.628  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:20:13.628  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:13.628  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:13.,628  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:20:13.628  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:20:13.628  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:13.628  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:13.628  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:20:13.628  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:20:13.628  6636  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:20:13.629  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:13.629  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:20:13.629  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:13.629  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:13.629  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:20:13.629  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:20:13.629  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:13.629  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:13.629  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:20:13.629  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:13.629  6636  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:20:13.629  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 13:20:13.629  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:13.629  1049  1049 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 13:20:13.637  1049  1049 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 13:20:13.637  1049  1049 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 13:20:13.638  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 13:20:13.638  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 13:20:13.638  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 13:20:13.638  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 13:20:13.638  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 13:20:13.638  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 13:20:13.645  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:20:13.656  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 13:20:13.656  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:13.657  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:13.667  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 13:20:13.668  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:13.668  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:13.707  7130  7149 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:20:13.707  7130  7149 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:20:13.707  7130  7149 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:20:13.707  7130  7149 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:20:13.707  7130  7149 I Adreno-EGL: Remote Branch: 
08-16 13:20:13.707  7130  7149 I Adreno-EGL: Local Patches: 
08-16 13:20:13.707  7130  7149 I Adreno-EGL: Reconstruct Branch: 
,08-16 13:20:13.719  6983  6983 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-16 13:20:13.719  6983  6983 I wpa_supplicant: monitor socket send errors count : 1
08-16 13:20:13.719  6983  6983 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1966-4\x00 that cannot receive messages
08-16 13:20:13.720  1049  6998 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 13:20:13.721  1049  6998 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 13:20:13.746  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 13:20:13.748  6296  6712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 13:20:13.757  6983  6983 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 13:20:13.758  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 13:20:13.759  6983  6983 W wpa_supplicant: USIM:  scard_deinit function
,08-16 13:20:13.760  1049  7058 D DhcpStateMachine: StoppedState
08-16 13:20:13.760  1049  7058 D DhcpStateMachine: StoppedState{ when=-159ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:13.760  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 13:20:13.760  1049  6998 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 13:20:13.760  1049  6998 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 13:20:13.760  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:20:13.760  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:20:13.760  1049  1131 D Tethering: InitialState.processMessage what=4
08-16 13:20:13.761  1049  1536 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=207989
08-16 13:20:13.761  1049  1536 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=207989
08-16 13:20:13.762  1049  1536 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=207990  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 13:20:13.762  1049  1536 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=207990  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 13:20:13.763  1049  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 13:20:13.765  1049  1536 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 13:20:13.766  1049  1536 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 13:20:13.766  1049  1536 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:13.767  1049  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-16 13:20:13.775  2239  2239 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:13.798  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 13:20:13.798  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:13.798  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 13:20:13.798  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 13:20:13.802  6921  6921 I AppUp4:CustModeStarterReceiver: onReceive
08-16 13:20:13.806  6921  6921 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@cce3a06
08-16 13:20:13.806  6921  6921 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 13:20:13.806  6921  6921 D AppUp4:CustFacade: isPhone : true
08-16 13:20:13.806  6921  6921 D AppUp4:CustModeStarterReceiver: begin check event
08-16 13:20:13.806  6921  6921 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 13:20:13.808  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:13.808  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:20:13.809  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:20:13.812  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 13:20:13.816  4326  7248 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 13:20:13.818  4326  7249 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:13.818  4326  7249 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 13:20:13.820  6949  6949 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 13:20:13.838  6949  7251 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:13.838  6821  7252 W FormManager: Network not available. Please check & try again.
08-16 13:20:13.841  3370  3370 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 13:20:13.841  3370  3370 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:20:13.841  3370  3370 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-16 13:20:13.846  6999  6999 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 13:20:13.846  6999  6999 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 13:20:13.846  6821  7253 V FormManager: Network unavailable.
08-16 13:20:13.852  7064  7064 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:20:13
08-16 13:20:13.853  6821  7253 V FormManager: Network unavailable.
,08-16 13:20:13.854  7064  7064 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 13:20:13.854  7064  7064 D Weather.Utils: 2 : All the weather widget is gone.
08-16 13:20:13.854  7064  7064 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 13:20:13.855  7064  7064 D WeatherAncestor: connectivity changed - connection : true
08-16 13:20:13.855  7064  7064 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@27257ef4
08-16 13:20:13.855  7064  7064 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 13:20:13.855  7064  7064 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 13:20:13.856  7064  7064 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 13:20:13.856  7064  7064 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 13:20:13.856  7064  7064 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:20:13
08-16 13:20:13.868  6983  6983 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-16 13:20:13.871  1049  6998 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 13:20:13.871  1049  6998 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 13:20:13.871  1049  6998 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 13:20:13.872  1049  1536 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-16 13:20:13.873  1966  1966 D WfdsService: Supplicant Connection state is changed : false
08-16 13:20:13.874  1966  2321 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 13:20:13.874  1966  2321 D WfdsService: Set the WFDS Monitor: false
08-16 13:20:13.874  1966  2321 D WfdsMonitor: WFDS Monitor is stopped
08-16 13:20:13.874  1049  1536 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 13:20:13.874  1049  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:20:13.874  1049  1536 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:20:13.874  1049  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 13:20:13.875  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 13:20:13.875  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:13.877  2467  2467 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:13.878  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:13.878  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:13.880  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 13:20:13.881  1049  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 13:20:13.881  1049  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 13:20:13.881  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 13:20:13.881  6717  6717 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 13:20:13.882  6717  6717 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 13:20:13.882  6717  6717 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-16 13:20:13.883  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 13:20:13.884  6717  6717 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 13:20:13.884  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 13:20:13.884  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 13:20:13.884  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 13:20:13.884  6717  6717 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 13:20:13.884  6717  6717 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 13:20:13.894  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 13:20:13.896  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 13:20:13.898  6821  7257 V FormManager: Network unavailable.
08-16 13:20:13.898  6821  7256 W FormManager: Network not available. Please check & try again.
08-16 13:20:13.899  6821  7257 V FormManager: Network unavailable.
08-16 13:20:13.901  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:13.914  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 13:20:13.916  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 13:20:13.921  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:13.922  6821  7259 W FormManager: Network not available. Please check & try again.
08-16 13:20:13.924  6821  7260 V FormManager: Network unavailable.
08-16 13:20:13.926  6821  7260 V FormManager: Network unavailable.
,08-16 13:20:13.931  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 13:20:13.932  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:20:13.933  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 13:20:13.934  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:20:13.936  4326  7261 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 13:20:13.938  4326  7262 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 13:20:13.938  4326  7262 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 13:20:13.974  1049  1758 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7263 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 13:20:13.975  1049  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=830816915, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1049
08-16 13:20:13.984   306  7278 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 13:20:13.985  1049  1129 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-16 13:20:13.985  1841  7090 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-16 13:20:13.993  1841  7090 I CheckinService: active receiver: disabled
,08-16 13:20:14.021  2644  2644 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 13:20:14.052  7263  7263 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 13:20:14.052  7263  7263 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-16 13:20:14.058  7263  7263 V [BNRBootReceiver]: Boot Receiver Return
08-16 13:20:14.058  7263  7263 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 13:20:14.061  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:14.072  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:14.079  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:14.091  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:14.092  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:14.094  6781  6781 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 13:20:14.100  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:14.112  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:14.119  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 13:20:14.129  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:14.130  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 13:20:14.132  6781  6781 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 13:20:14.138  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-16 13:20:14.162  6717  6717 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-16 13:20:14.168  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:14.185  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:14.192  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:14.192  6526  6894 D UEI.SmartControl: Internal timer expired: 2
08-16 13:20:14.192  6526  6894 D UEI.SmartControl: unbind internal service
08-16 13:20:14.205  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 13:20:14.206  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:14.207  6781  6781 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:20:14.214  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:14.223  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:14.233  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 13:20:14.245  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 13:20:14.246  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 13:20:14.247  6781  6781 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:20:14.252  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:14.260  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:14.269  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:14.280  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:14.281  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:14.281  6781  6781 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 13:20:14.288  6526  6891 D serial_port: close(fd = 24)
08-16 13:20:14.293  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:14.294  6526  6891 I UEI.SmartControl: Serial port is closed.
,08-16 13:20:14.305  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:14.315  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 13:20:14.323  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:14.323  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:14.324  6781  6781 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 13:20:14.328  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:14.336  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:14.344  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:14.356  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:14.356  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:14.357  6781  6781 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 13:20:14.367  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:20:14.384  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:14.397  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:14.407  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 13:20:14.408  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:14.412  6781  6781 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:20:14.419  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:14.433  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:14.441  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:14.461  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 13:20:14.462  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 13:20:14.464  6781  6781 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:20:14.475  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:14.485  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-16 13:20:14.505  1049  1542 D WifiService: New client listening to asynchronous messages
,08-16 13:20:14.506  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:20:14.513  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:14.529  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 13:20:14.543  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 13:20:14.544  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:14.546  6781  6781 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 13:20:14.548  6781  6781 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 13:20:14.549  6781  6781 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 13:20:14.558  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:20:14.563  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 13:20:14.566  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:20:14.574  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:14.587  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:14.601  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:14.601  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:14.603  6781  6781 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-16 13:20:14.604  6781  6781 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 13:20:14.605  6781  6781 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 13:20:14.611  1049  2045 I ActivityManager: Killing 6755:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-16 13:20:14.654  1049  1933 W libprocessgroup: failed to open /acct/uid_10037/pid_6755/cgroup.procs: No such file or directory
,08-16 13:20:14.662  2239  2239 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-16 13:20:14.682  2239  2239 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-16 13:20:14.683  2239  2239 D c       : Getting all permits...
08-16 13:20:14.683  2239  2239 D a       : Opening database...
,08-16 13:20:14.689  2239  2239 D a       : Opening database auth.proximity.permit_store...
08-16 13:20:14.690  2239  2239 D a       : Closing database...
08-16 13:20:14.703  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:20:14.708  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 13:20:14.708  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 13:20:14.708  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:20:14.712  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:14.718  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:14.726  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:14.727  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:14.728  6781  6781 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 13:20:14.733  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:20:14.736  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 13:20:14.736  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 13:20:14.736  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:20:14.740  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:14.747  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 13:20:14.756  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:14.757  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 13:20:14.759  6781  6781 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 13:20:14.764  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:14.770  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 13:20:14.770  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-16 13:20:14.770  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:20:14.773  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 13:20:14.782  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:14.791  6781  6781 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:14.792  6781  6781 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:14.794  6781  6781 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 13:20:14.806  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:20:14.812  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 13:20:14.821  6821  7290 W FormManager: Network not available. Please check & try again.
08-16 13:20:14.822  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:14.830  6821  7291 V FormManager: Network unavailable.
,08-16 13:20:14.839  6821  7291 V FormManager: Network unavailable.
08-16 13:20:14.846  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 13:20:14.847  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:20:14.849  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 13:20:14.856  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:20:14.863  4326  7292 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 13:20:14.868  4326  7293 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 13:20:14.868  4326  7293 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 13:20:14.869  6734  6734 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 13:20:14.869  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 13:20:14.870  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:20:14.875  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 13:20:14.886  6821  7295 W FormManager: Network not available. Please check & try again.
,08-16 13:20:14.889  6821  7296 V FormManager: Network unavailable.
08-16 13:20:14.892  6821  7296 V FormManager: Network unavailable.
08-16 13:20:14.897  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:14.916  6781  6781 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 13:20:14.917  6781  6781 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7567
,08-16 13:20:14.917  1049  1049 D PowerManagerServiceEx: releaseWakeLockInternal: lock=830816915 [*alarm*], flags=0x0
08-16 13:20:14.923  2239  2239 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-16 13:20:15.382  1049  1536 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1827367147] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:20:15.384  1049  1536 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1827367144] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 13:20:15.474  1049  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:20:15.487  1049  1131 D Tethering: MasterInitialState.processMessage what=3
08-16 13:20:15.496  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:20:15.500  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:15.503  1049  1122 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:15.506  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 13:20:15.507  6296  6712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 13:20:15.518  5764  5764 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 13:20:15.536  2239  2239 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:20:15.560  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 13:20:15.560  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:15.560  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 13:20:15.560  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 13:20:15.565  6921  6921 I AppUp4:CustModeStarterReceiver: onReceive
08-16 13:20:15.568  6921  6921 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@cce3a06
08-16 13:20:15.568  6921  6921 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 13:20:15.568  6921  6921 D AppUp4:CustFacade: isPhone : true
08-16 13:20:15.569  6921  6921 D AppUp4:CustModeStarterReceiver: begin check event
08-16 13:20:15.569  6921  6921 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 13:20:15.573  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:15.574  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:20:15.575  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 13:20:15.581  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:20:15.589  6949  6949 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 13:20:15.618  3370  3370 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 13:20:15.618  3370  3370 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:15.619  3370  3370 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 13:20:15.619  3370  3370 D PhoneState: setPdpRejectCasuse : false
,08-16 13:20:15.624  6999  6999 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 13:20:15.624  6999  6999 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 13:20:15.642  1049  1122 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 13:20:15.651  4326  7305 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 13:20:15.659  6821  7319 W FormManager: Network not available. Please check & try again.
08-16 13:20:15.660  7064  7064 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:20:15
08-16 13:20:15.660  6821  7320 V FormManager: Network unavailable.
,08-16 13:20:15.661  4326  7322 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:20:15.661  4326  7322 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 13:20:15.664  6821  7320 V FormManager: Network unavailable.
08-16 13:20:15.664  7064  7064 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-16 13:20:15.665  7064  7064 D Weather.Utils: 2 : All the weather widget is gone.
08-16 13:20:15.665  7064  7064 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 13:20:15.666  7064  7064 D WeatherAncestor: connectivity changed - connection : true
08-16 13:20:15.666  7064  7064 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@27257ef4
,08-16 13:20:15.667  6949  7304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:15.668  7064  7064 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 13:20:15.668  7064  7064 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-16 13:20:15.668  7064  7064 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 13:20:15.668  7064  7064 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 13:20:15.668  7064  7064 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:20:15
08-16 13:20:16.531  1049  2045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:16.532  1049  2045 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 13:20:16.561  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:20:16.562  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 13:20:16.562  1049  1049 D Ulp_jni : JNI:system_update. Event-4
,08-16 13:20:16.565  1049  1131 D BluetoothManagerService: Message: 1
08-16 13:20:16.565  1049  1131 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-16 13:20:16.599  1049  1131 D BluetoothManagerService: Message: 20
08-16 13:20:16.599  1049  1131 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23f7dff1:true
,08-16 13:20:16.603  6873  6873 D BluetoothAdapterState: make
08-16 13:20:16.607  6873  6873 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 13:20:16.608  6873  6873 I bluedroid-qcom: init
08-16 13:20:16.609  6873  7335 I BluetoothAdapterState: Entering OffState
08-16 13:20:16.609  6873  6873 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 13:20:16.610  6873  6873 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 13:20:16.610  6873  6873 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 13:20:16.610  6873  6873 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 13:20:16.610  6873  6873 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 13:20:16.612  6873  6873 I bluedroid-qcom: get_profile_interface socket
08-16 13:20:16.612  6873  6873 I bluedroid-qcom: get_profile_interface map_client
,08-16 13:20:16.616  6873  7339 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 13:20:16.607  7338  7338 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:16.607  7338  7338 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:16.625  1049  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:20:16.630  1049  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:16.630  1049  1131 D Tethering: MasterInitialState.processMessage what=3
08-16 13:20:16.639  7338  7338 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 13:20:16.639  7338  7338 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 13:20:16.639  7338  7338 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-16 13:20:16.642  7338  7338 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 13:20:16.646  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:16.648  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:16.649  7338  7338 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 13:20:16.649  7338  7338 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 13:20:16.656  1049  1131 D Tethering: MasterInitialState.processMessage what=3
,08-16 13:20:16.661  6873  7339 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 13:20:16.669  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:20:16.673  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:16.674  1049  1049 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 13:20:16.675  1049  1131 D BluetoothManagerService: Message: 40
08-16 13:20:16.675  1049  1131 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 13:20:16.676  6873  6889 I bluedroid-qcom: config_hci_snoop_log
08-16 13:20:16.677  1049  1131 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 13:20:16.677  1049  1131 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 13:20:16.681  6873  7339 D BluetoothAdapterProperties: Name is: G3
,08-16 13:20:16.686  6873  7335 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-16 13:20:16.686  6873  7335 D BluetoothAdapterProperties: Setting state to 11
,08-16 13:20:16.686  6873  7335 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 13:20:16.690  1049  1131 D BluetoothManagerService: Message: 60
08-16 13:20:16.690  1049  1131 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 13:20:16.690  1049  1131 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 13:20:16.693  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 13:20:16.699  6873  7335 I LGBluetoothServiceJni: classInitNative: succeeds
,08-16 13:20:16.705  1049  1049 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 13:20:16.705  1049  1049 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 13:20:16.706  1049  1122 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:16.710  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:16.710  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 13:20:16.712  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:16.712  6717  6717 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 13:20:16.713  6296  6712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 13:20:16.716  5764  5764 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 13:20:16.718  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:16.725  6873  7335 D BluetoothBondStateMachine: make
,08-16 13:20:16.731  6873  7335 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:16.731  6873  7355 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 13:20:16.731  6873  7335 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 13:20:16.731  6873  7335 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:16.731  6873  7335 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 13:20:16.732  6873  7335 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 13:20:16.733  6873  6873 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 13:20:16.736  6873  6873 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:16.737  6873  6873 V BluetoothPbapReceiver: ***********state = 11
,08-16 13:20:16.739  6873  7335 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:20:16.743  5764  5764 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 13:20:16.745  2239  2239 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 13:20:16.797  1049  1984 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7358 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 13:20:16.806  1049  1122 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:16.808  6873  7335 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:20:16.809  6873  6873 D HeadsetService: Received start request. Starting profile...
08-16 13:20:16.809  6873  6873 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 13:20:16.810  6873  6873 D LGBluetoothHfpAdapter: Version 1.6
08-16 13:20:16.812  6873  6873 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 13:20:16.814  6873  6873 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 13:20:16.814  6873  6873 D HeadsetStateMachine: make
,08-16 13:20:16.832  1049  1122 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:16.832  1049  1122 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 13:20:16.835  2239  2239 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:16.840  6873  7335 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:20:16.846  6873  7335 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 13:20:16.856  6873  6873 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:20:16.857  6873  6873 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 13:20:16.858  6873  7335 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:20:16.861  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 13:20:16.861  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:16.861  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 13:20:16.861  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 13:20:16.864  6873  7335 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 13:20:16.864  6873  6873 D HeadsetStateMachine: max_hf_connections = 1
08-16 13:20:16.864  6873  6873 I bluedroid-qcom: get_profile_interface handsfree
08-16 13:20:16.864  6921  6921 I AppUp4:CustModeStarterReceiver: onReceive
08-16 13:20:16.866  6873  6873 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 13:20:16.868   310  1785 V AudioPolicyService: registerClient() client 0xb558aec0, uid 1002
08-16 13:20:16.869   310  1385 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 13:20:16.869   310  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 13:20:16.869   310  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 13:20:16.869  6873  6873 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 13:20:16.870  6873  7335 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:20:16.876   310   310 V AudioFlinger: registerClient() client 0xb5581808, pid 6873
08-16 13:20:16.877   310  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:20:16.877   310  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-16 13:20:16.877  6873  6873 V ToneGenerator: Create Track: 0xb4928080
08-16 13:20:16.877  6873  6873 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 13:20:16.877  6873  6873 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 13:20:16.878  1049  1064 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:20:16.878  1049  1064 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:20:16.878   310  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 13:20:16.878   310  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 13:20:16.878   310  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 13:20:16.878   310  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 13:20:16.878  6873  6873 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 13:20:16.878  1876  1891 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:20:16.878  1876  1891 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-16 13:20:16.879  3370  3387 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:20:16.879  3370  3387 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:20:16.879  1602  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:20:16.879  1602  1619 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:20:16.879   310  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:20:16.879   310  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:20:16.879  1602  2690 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:20:16.879  1049  1984 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:20:16.879  1602  2690 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:20:16.879  1049  1984 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:20:16.879  1876  4006 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:20:16.879  1876  4006 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:20:16.879  3370  3390 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:20:16.879  3370  3390 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:20:16.880  6873  6890 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:20:16.880  6873  6890 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 13:20:16.880  6873  6890 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:20:16.880   310   310 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 13:20:16.880  6873  6890 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 13:20:16.880   310  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 13:20:16.880   310  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 13:20:16.880   310  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 13:20:16.880   310  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 13:20:16.880  6873  6873 V AudioSystem: getLatency() output 2, latency 50
08-16 13:20:16.880  6873  6873 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 13:20:16.880  6873  6873 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 13:20:16.881   310  1785 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 13:20:16.881   310  1785 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 13:20:16.881   310  1785 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 13:20:16.881   310  1785 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 13:20:16.881   310  1785 V AudioFlinger: createTrack() lSessionId: 22
08-16 13:20:16.882  6921  6921 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@cce3a06
08-16 13:20:16.882  6873  6873 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 13:20:16.882  6921  6921 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 13:20:16.882  6921  6921 D AppUp4:CustFacade: isPhone : true
08-16 13:20:16.882   310   310 V AudioFlinger: acquiring 22 from 6873, for 6873
08-16 13:20:16.882   310   310 V AudioFlinger:  added new entry for 22
08-16 13:20:16.882  6921  6921 D AppUp4:CustModeStarterReceiver: begin check event
08-16 13:20:16.882  6873  6873 V ToneGenerator: ToneGenerator INIT OK, time: 211125
08-16 13:20:16.882  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:16.882  6921  6921 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 13:20:16.883  6873  7373 D HeadsetStateMachine: Enter Disconnected: -2, s,ize: 0
08-16 13:20:16.883  6873  7373 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 13:20:16.883  6873  7373 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 13:20:16.883  6873  7373 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 13:20:16.884   310  1384 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6873
08-16 13:20:16.884   310  1384 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 13:20:16.884   310  1384 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 13:20:16.884   310  1384 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 13:20:16.884   310  1384 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 13:20:16.884   310  1384 V voice   : voice_set_parameters: exit with code(0)
08-16 13:20:16.884   310  1384 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 13:20:16.884   310  1384 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 13:20:16.884   310  1384 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 13:20:16.884   310  1384 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 13:20:16.884   310  1384 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 13:20:16.884   310  1384 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 13:20:16.884  6873  7373 V ToneGenerator: ToneGenerator destructor
08-16 13:20:16.884  6873  7373 V ToneGenerator: stopTone
08-16 13:20:16.884  6873  7373 V ToneGenerator: Delete Track: 0xb4928080
08-16 13:20:16.885  6873  7373 V AudioTrack: ~AudioTrack, releasing session id from 6873 on behalf of 6873
08-16 13:20:16.885   310   310 V AudioFlinger: releasing 22 from 6873 for 6873
08-16 13:20:16.885   310  1385 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 13:20:16.885   310   310 V AudioFlinger:  decremented refcount to 0
08-16 13:20:16.885   310   310 V AudioFlinger: purging stale effects
08-16 13:20:16.885   310  1385 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 13:20:16.885   310  1287 V AudioPolicyService: AudioCommandThread() waking up
08-16 13:20:16.885   310  1287 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 13:20:16.885   310  1287 V AudioPolicyManager: releaseOutput() 2
08-16 13:20:16.885   310  1287 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 13:20:16.885   310  1385 V AudioFlinger: PlaybackThread::Track destructor
08-16 13:20:16.885   310  1385 V AudioFlinger: removeClient_l() pid 6873, calling pid 310
08-16 13:20:16.886  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:16.886  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:16.886  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:20:16.887  6873  6873 D A2dpService: Received start request. Starting profile...
08-16 13:20:16.888  6873  6873 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 13:20:16.888  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:20:16.888  6873  6873 V Avrcp   : make
08-16 13:20:16.889  6873  6873 D Avrcp   : [BTUI] Use Native AVRCP : init jni
,08-16 13:20:16.889  6873  6873 I bluedroid-qcom: get_profile_interface avrcp
08-16 13:20:16.890  1049  2045 W Process : Unable to open /proc/7377/status
,08-16 13:20:16.892  6873  7335 V LGMDMManager: Create singleton instance
08-16 13:20:16.893  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:20:16.896  6873  7335 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 13:20:16.897  6873  6873 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 13:20:16.899  6873  6873 E AudioManager: No RCC entry present to update
08-16 13:20:16.899  6873  6873 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 13:20:16.901  6873  6873 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 13:20:16.902  6949  6949 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 13:20:16.902  4326  7379 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 13:20:16.902  6873  6873 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 13:20:16.902  6873  6873 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 13:20:16.908  6873  6873 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-16 13:20:16.918  4326  7380 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:16.918  4326  7380 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 13:20:16.946  6949  7382 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 13:20:16.949  7358  7358 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 13:20:16.949  7358  7358 W LG Account v2.2: No ProfileInfo entries
08-16 13:20:16.950  7358  7358 I LG Account v2.2: isEnabled: false
08-16 13:20:16.950  7358  7358 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 13:20:16.950  7358  7358 I Feature : [Lifetracker]Country: EU
08-16 13:20:16.952  7358  7358 I Feature : [Lifetracker]Operator: OPEN
08-16 13:20:16.952  7358  7358 I Feature : [Lifetracker]Ranking support: false
08-16 13:20:16.952  7358  7358 I Feature : [Lifetracker]Comfort support: false
08-16 13:20:16.952  7358  7358 I Feature : [Lifetracker]Accessory: true
08-16 13:20:16.952  7358  7358 I Feature : [Lifetracker]Health device: true
08-16 13:20:16.953  7358  7358 I Feature : [Lifetracker]Extra Pedometer: false
08-16 13:20:16.953  7358  7358 I Feature : [Lifetracker]Blood glucose device: false
08-16 13:20:16.953  7358  7358 I Feature : [Lifetracker]Device Number: 3
08-16 13:20:16.956  3370  3370 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 13:20:16.957  3370  3370 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:16.957  3370  3370 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 13:20:16.961  6999  6999 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 13:20:16.962  6999  6999 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 13:20:16.973  6717  6717 D BluetoothPermissionRequest: onReceive
,08-16 13:20:16.980  6821  7387 W FormManager: Network not available. Please check & try again.
08-16 13:20:16.985  7064  7064 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:20:16
,08-16 13:20:16.989  7064  7064 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 13:20:16.989  7064  7064 D Weather.Utils: 2 : All the weather widget is gone.
08-16 13:20:16.989  6717  6717 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 13:20:16.989  7064  7064 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 13:20:16.991  7064  7064 D WeatherAncestor: connectivity changed - connection : true
08-16 13:20:16.991  7064  7064 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@27257ef4
08-16 13:20:16.992  7064  7064 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 13:20:16.992  7064  7064 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 13:20:16.992  7064  7064 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 13:20:16.992  7064  7064 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 13:20:16.992  1049  1065 V SIM_STK : Menu title from STK is T-Mobile
08-16 13:20:16.992  1049  1065 V SIM_STK : Menu title from STK is T-Mobile
08-16 13:20:16.992  7064  7064 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:20:16
08-16 13:20:16.994  6821  7388 V FormManager: Network unavailable.
08-16 13:20:17.011  6821  7388 V FormManager: Network unavailable.
,08-16 13:20:17.022  6296  6296 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 13:20:17.023  6296  6712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 13:20:17.046  1049  1984 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 13:20:17.050  2239  2239 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:17.052  6873  6873 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 13:20:17.055  6873  6873 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-16 13:20:17.055  6873  6873 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 13:20:17.055  6873  6873 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 13:20:17.055  6873  6873 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 13:20:17.055  6873  6873 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 13:20:17.055  6873  6873 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 13:20:17.055  6873  6873 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 13:20:17.055  6873  6873 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 13:20:17.055  6873  6873 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 13:20:17.056  6873  6873 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 13:20:17.056  6873  6873 I BluetoothA2dpServiceJni: classInitNative
08-16 13:20:17.056  6873  6873 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 13:20:17.056  6873  6873 D A2dpStateMachine: make
08-16 13:20:17.058  6873  6873 I bluedroid-qcom: get_profile_interface a2dp
08-16 13:20:17.058  6873  7390 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 13:20:17.060  6873  6873 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 13:20:17.060  6873  6873 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 13:20:17.061  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:17.062  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 13:20:17.062  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:17.062  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 13:20:17.062  6921  6921 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 13:20:17.062  6873  7389 D A2dpStateMachine: Enter Disconnected: -2
08-16 13:20:17.062  6873  6873 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 13:20:17.063  6921  6921 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 13:20:17.064  6873  6873 D HidService: Received start request. Starting profile...
,08-16 13:20:17.064  6873  6873 I bluedroid-qcom: get_profile_interface hidhost
08-16 13:20:17.065  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:17.065  6873  6873 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 13:20:17.065  6921  6921 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@cce3a06
,08-16 13:20:17.065  6921  6921 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 13:20:17.065  6921  6921 D AppUp4:CustFacade: isPhone : true
08-16 13:20:17.066  6921  6921 D AppUp4:CustModeStarterReceiver: begin check event
08-16 13:20:17.066  6921  6921 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 13:20:17.067  6873  6873 D HealthService: Received start request. Starting profile...
08-16 13:20:17.069  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:17.069  6873  6873 I bluedroid-qcom: get_profile_interface health
08-16 13:20:17.069  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:20:17.070  6873  6873 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 13:20:17.070  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:17.071  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:20:17.071  6873  6873 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 13:20:17.073  6873  6873 D PanService: Received start request. Starting profile...
08-16 13:20:17.073  6873  6873 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 13:20:17.073  6873  6873 I bluedroid-qcom: get_profile_interface pan
08-16 13:20:17.073  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 13:20:17.079  4326  7394 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 13:20:17.082  6949  6949 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 13:20:17.082  6873  6873 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 13:20:17.082  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:17.083  6873  6873 D HeadsetStateMachine: Proxy object connected
08-16 13:20:17.083  6873  6873 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 13:20:17.084  6873  6873 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 13:20:17.084  4326  7396 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:17.084  4326  7396 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 13:20:17.086  6873  6873 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 13:20:17.092  6873  6873 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 13:20:17.093  6873  6873 D BtGatt.GattService: Received start request. Starting profile...
08-16 13:20:17.093  6873  6873 D BtGatt.GattService: start()
08-16 13:20:17.093  6873  6873 I bluedroid-qcom: get_profile_interface gatt
08-16 13:20:17.094  6873  6873 D BtGatt.AdvertiseManager: advertise manager created
08-16 13:20:17.095  6949  7397 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:17.103  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:17.104  3370  3370 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 13:20:17.104  3370  3370 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:17.104  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:17.105  6821  7400 W FormManager: Network not available. Please check & try again.
08-16 13:20:17.105  3370  3370 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 13:20:17.105  6873  6873 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 13:20:17.106  6873  6873 V BluetoothMapService: BluetoothMapBinder()
,08-16 13:20:17.107  6873  6873 D BluetoothMapService: Received start request. Starting profile...
08-16 13:20:17.107  6873  6873 D BluetoothMapService: start()
08-16 13:20:17.108  6999  6999 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 13:20:17.108  6999  6999 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 13:20:17.113  6821  7401 V FormManager: Network unavailable.
,08-16 13:20:17.113  6873  6873 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 13:20:17.114  6873  6873 D BluetoothMapEmailAppObserver: createReceiver()
08-16 13:20:17.117  6873  6873 D BluetoothMapEmailAppObserver: initObservers()
08-16 13:20:17.117  6873  6873 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 13:20:17.120  7064  7064 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:20:17
08-16 13:20:17.121  6821  7401 V FormManager: Network unavailable.
08-16 13:20:17.122  7064  7064 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 13:20:17.122  7064  7064 D Weather.Utils: 2 : All the weather widget is gone.
08-16 13:20:17.122  7064  7064 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 13:20:17.122  7064  7064 D WeatherAncestor: connectivity changed - connection : true
08-16 13:20:17.122  7064  7064 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@27257ef4
08-16 13:20:17.123  7064  7064 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 13:20:17.123  7064  7064 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 13:20:17.123  7064  7064 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 13:20:17.123  7064  7064 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 13:20:17.123  7064  7064 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:20:17
08-16 13:20:17.126  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
,08-16 13:20:17.129  6873  6873 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 13:20:17.130  6873  7373 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 13:20:17.130  6873  7373 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 13:20:17.131  6873  7373 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 13:20:17.132  6873  6873 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 13:20:17.135  6873  6873 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 13:20:17.137  6873  6873 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 13:20:17.137  6873  6873 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 13:20:17.140  6873  6873 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 13:20:17.143  6873  6873 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 13:20:17.144  6873  6873 V BluetoothMapService: Handler(): got msg=1
08-16 13:20:17.145  6873  7335 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 13:20:17.145  6873  7335 I bluedroid-qcom: enable
08-16 13:20:17.145  6873  7404 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 13:20:17.145  6873  7404 I bt-btu  : btu_task pending for preload complete event
08-16 13:20:17.145  6873  7335 I bt_hci_bdroid: init
08-16 13:20:17.146  6873  6873 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:17.146  6873  7335 I bt_vendor: bt-vendor : init
08-16 13:20:17.146  6873  7335 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 13:20:17.146  6873  7335 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 13:20:17.146  6873  7335 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 13:20:17.146  6873  7335 D bt_userial_mct: userial_init
08-16 13:20:17.147  6873  7335 D bt_hci_bdroid: set_power 1
08-16 13:20:17.147  6873  7335 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 13:20:17.147  6873  7335 I bt_vendor: Starting hciattach daemon
08-16 13:20:17.147  6873  7335 I bt_vendor: try to set true
08-16 13:20:17.148  6873  6873 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:20:17.148  6873  6873 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:20:17.148  6873  6873 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 13:20:17.149  6873  6873 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:17.149  6873  6873 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 13:20:17.137  7407  7407 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:17.137  7407  7407 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:17.176  7408  7408 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 13:20:17.266  7414  7414 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 13:20:17.287  7415  7415 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 13:20:17.329  7417  7417 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 13:20:17.352  7418  7418 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 13:20:17.373  7419  7419 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 13:20:17.388  7420  7420 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 13:20:17.416  7425  7425 I libmdmdetect: ESOC framework not supported
,08-16 13:20:17.420  7425  7425 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 13:20:17.428  7425  7425 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 13:20:17.428  7425  7425 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 13:20:17.428  7425  7425 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 13:20:17.428  7425  7425 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 13:20:17.428  7425  7425 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 13:20:17.429  7425  7425 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 13:20:17.429  7425  7425 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 13:20:17.473  7425  7426 E QC-QMI  : qmi_client [7425] 14: failed to locate client data
08-16 13:20:17.474   470   470 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 13:20:17.474   470   470 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-16 13:20:17.539  7430  7430 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 13:20:17.559  7434  7434 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 13:20:17.601  1049  1124 W ProcessCpuTracker: Skipping unknown process pid 7345
08-16 13:20:17.602  1049  1124 W ProcessCpuTracker: Skipping unknown process pid 7346
08-16 13:20:17.603  1049  1124 W ProcessCpuTracker: Skipping unknown process pid 7354
08-16 13:20:17.604  1049  1124 W ProcessCpuTracker: Skipping unknown process pid 7376
08-16 13:20:17.604  1049  1124 W ProcessCpuTracker: Skipping unknown process pid 7407
08-16 13:20:17.604  1049  1124 W ProcessCpuTracker: Skipping unknown process pid 7427
08-16 13:20:17.605  1049  1124 W ProcessCpuTracker: Skipping unknown process pid 7430
,08-16 13:20:17.612  6873  7335 I bt_vendor: bluetooth satus is on
08-16 13:20:17.612  6873  7335 D bt_hci_bdroid: preload
08-16 13:20:17.613  6873  7406 D bt_userial_mct: userial_open(port:0)
08-16 13:20:17.613  6873  7406 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 13:20:17.616  6873  7406 I bt_vendor: Done intiailizing UART
08-16 13:20:17.617  6873  7406 I bt_vendor: Done intiailizing UART
08-16 13:20:17.617  6873  7406 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 13:20:17.617  6873  7406 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 13:20:17.617  6873  7404 I bt-btu  : btu_task received preload complete event
08-16 13:20:17.618  6873  7404 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 13:20:17.618  6873  7404 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 13:20:17.620  6873  7404 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 13:20:17.623  6873  7436 D bt_userial_mct: Entering userial_read_thread()
,08-16 13:20:17.626  6873  7404 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 13:20:17.626  6873  7404 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 13:20:17.626  6873  7404 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 13:20:17.626  6873  7404 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 13:20:17.626  6873  7404 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 13:20:17.626  6873  7404 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 13:20:17.626  6873  7404 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 13:20:17.627  6873  7404 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 13:20:17.627  6873  7404 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 13:20:17.627  6873  7404 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 13:20:17.627  6873  7404 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 13:20:17.627  6873  7404 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 13:20:17.627  6873  7404 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 13:20:17.627  6873  7404 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 13:20:17.627  6873  7404 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 13:20:17.627  6873  7404 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 13:20:17.706  6873  7404 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 13:20:17.706  6873  7404 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0220061 
08-16 13:20:17.706  6873  7404 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0220061 
,08-16 13:20:17.723  6873  7339 E bt-btif : Calling BTA_HhEnable
08-16 13:20:17.724  6873  7339 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 13:20:17.724  6873  7339 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 13:20:17.727  6873  7404 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 13:20:17.727  6873  7404 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 13:20:17.727  6873  7404 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 13:20:17.727  6873  7404 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 13:20:17.727  6873  7404 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 13:20:17.729  1049  1049 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 13:20:17.729  1049  1049 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 13:20:17.729  6873  7339 D BluetoothAdapterProperties: Name is: G3
08-16 13:20:17.730  6873  7339 D BluetoothAdapterProperties: Scan Mode:20
08-16 13:20:17.730  6873  7339 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 13:20:17.731  6873  7339 D bt_hci_bdroid: postload
08-16 13:20:17.731  6873  7406 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 13:20:17.732  6873  7406 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 13:20:17.732  6873  7404 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 13:20:17.733  6873  7339 D bte_conf: Device ID record 1 : primary
08-16 13:20:17.733  6873  7436 E bt_mct  : hci lib postload completed
08-16 13:20:17.733  6873  7339 D bte_conf:   vendorId            = 00c4
08-16 13:20:17.733  6873  7339 D bte_conf:   vendorIdSource      = 0001
08-16 13:20:17.733  6873  7339 D bte_conf:   product             = 13a1
08-16 13:20:17.733  6873  7339 D bte_conf:   version             = 1000
08-16 13:20:17.733  6873  7339 D bte_conf:   clientExecutableURL = 
08-16 13:20:17.733  6873  7339 D bte_conf:   serviceDescription  = 
08-16 13:20:17.733  6873  7339 D bte_conf:   documentationURL    = 
08-16 13:20:17.733  6873  7339 D bte_conf: bte_load_did_conf no section named DID2.
08-16 13:20:17.737  6873  7335 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 13:20:17.737  6873  7335 D BluetoothAdapterProperties: ScanMode =  20
,08-16 13:20:17.741  6873  7335 D BluetoothAdapterProperties: State =  11
08-16 13:20:17.742  6873  7335 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 13:20:17.742  6873  7335 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 13:20:17.742  6873  7335 D BluetoothAdapterProperties: Setting state to 12
08-16 13:20:17.742  6873  7335 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 13:20:17.743  6873  7339 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 13:20:17.743  6873  7339 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 13:20:17.727  7438  7438 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:17.727  7438  7438 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:17.748  1049  1131 D BluetoothManagerService: Message: 60
08-16 13:20:17.749  1049  1131 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 13:20:17.749  1049  1131 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-16 13:20:17.749  1049  1131 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 13:20:17.750  6873  7404 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 13:20:17.750  6873  7404 W bt-smp  : Plain text(LSB ~ MSB) = 85 50 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 13:20:17.750  6873  7404 W bt-smp  : Encrypted text(LSB ~ MSB) = df a0 32 60 df 2c ca f6 bc 4c 08 20 29 01 77 e4 
,08-16 13:20:17.754  6873  7404 W bt-btm  : Stopping oneshot timer
08-16 13:20:17.769  6873  7335 I BluetoothAdapterState: Entering On State
,08-16 13:20:17.777  6873  7335 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 13:20:17.777  6873  7335 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 13:20:17.777  6873  7335 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-16 13:20:17.783  6873  7335 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-16 13:20:17.785  6873  7404 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 13:20:17.785  6873  7404 W bt-smp  : Plain text(LSB ~ MSB) = 05 4d 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 13:20:17.785  6873  7404 W bt-smp  : Encrypted text(LSB ~ MSB) = 72 fd 77 b4 0c ef 07 c9 45 29 b9 80 95 4d 34 04 
08-16 13:20:17.785  6873  7404 W bt-btm  : Stopping oneshot timer
08-16 13:20:17.788  1049  1049 D BluetoothA2dp: Proxy object connected
08-16 13:20:17.793  6873  7339 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 13:20:17.794  6873  7339 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 13:20:17.800  6873  7404 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 13:20:17.800  6873  7404 W bt-smp  : Plain text(LSB ~ MSB) = 82 92 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 13:20:17.800  6873  7404 W bt-smp  : Encrypted text(LSB ~ MSB) = 17 9d b6 fb 7a 7a f2 22 b0 d2 e3 3d da ed d9 7e 
,08-16 13:20:17.803  6873  7404 W bt-btm  : Stopping oneshot timer
08-16 13:20:17.810  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:20:17.810  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:17.810  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:17.810  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:20:17.810  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:17.810  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:17.810  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:17.810  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:20:17.814  1876  1892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 13:20:17.816  6873  7404 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 13:20:17.816  6873  7404 W bt-smp  : Plain text(LSB ~ MSB) = a9 17 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 13:20:17.816  6873  7404 W bt-smp  : Encrypted text(LSB ~ MSB) = bf 5a 5d db c0 b9 b7 7b ca d0 fa 78 e6 e1 5f 26 
08-16 13:20:17.817  6873  7404 W bt-btm  : Stopping oneshot timer
08-16 13:20:17.817  6636  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:20:17.821  6873  7335 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 13:20:17.827  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:20:17.827  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:17.827  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:17.827  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:20:17.827  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:17.827  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:17.827  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:17.827  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:20:17.830  6873  7404 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-16 13:20:17.830  6873  7404 W bt-smp  : Plain text(LSB ~ MSB) = 0e ee 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-16 13:20:17.830  6873  7404 W bt-smp  : Encrypted text(LSB ~ MSB) = 68 ee 77 16 f5 65 3c db 63 74 61 d0 86 e0 ff f3 
08-16 13:20:17.830  6873  7404 W bt-btm  : Stopping oneshot timer
08-16 13:20:17.841  6636  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:20:17.858  1876  1876 D BluetoothHeadset: Proxy object connected
,08-16 13:20:17.858  6717  6733 D BluetoothMap: onBluetoothStateChange: up=true
08-16 13:20:17.863  6717  6732 D BluetoothPan: onBluetoothStateChange on: true
08-16 13:20:17.863  6717  6732 D BluetoothPan: onBluetoothStateChange call bindService
08-16 13:20:17.866  1876  2619 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:20:17.869  1876  1876 D BluetoothHeadset: Proxy object connected
08-16 13:20:17.869  6717  6717 D BluetoothMap: Proxy object connected
08-16 13:20:17.869  6717  6717 D MapProfile: Bluetooth service connected
08-16 13:20:17.869  6717  6717 D BluetoothMap: getConnectedDevices()
08-16 13:20:17.869  6717  7458 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 13:20:17.871  1876  1891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:20:17.873  1876  1876 D BluetoothHeadset: Proxy object connected
08-16 13:20:17.873  1049  1131 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:20:17.874  6717  6733 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 13:20:17.878  1049  1049 D BluetoothHeadset: Proxy object connected
,08-16 13:20:17.883  1049  1131 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 13:20:17.883  1049  1131 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 13:20:17.885  1049  1049 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 13:20:17.885  1049  1131 D BluetoothManagerService: Message: 40
08-16 13:20:17.885  1049  1131 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 13:20:17.886  7460  7460 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 13:20:17.887  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:17.888  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 13:20:17.890  6873  6889 V BluetoothMapService: getConnectedDevices()
08-16 13:20:17.890  6873  6873 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:17.891  6636  6636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 13:20:17.891  6873  6873 D BluetoothMapService: STATE_ON
08-16 13:20:17.891  6873  6873 V BluetoothMapService: Handler(): got msg=1
,08-16 13:20:17.893  6873  6873 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 13:20:17.893  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:17.894  6873  7463 D BluetoothMapMasInstance: MAS initSocket()
08-16 13:20:17.894  6873  7463 D BluetoothMapMasInstance:   masId = 00
08-16 13:20:17.894  6873  7463 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 13:20:17.894  6873  7463 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 13:20:17.894  6873  7463 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 13:20:17.895  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:17.895  1966  2177 D LGBluetoothAPIService: Message: 1
08-16 13:20:17.895  1966  2177 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 13:20:17.895  6717  6717 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 13:20:17.895  6717  6717 D PanProfile: Bluetooth service connected
08-16 13:20:17.897  7098  7128 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-16 13:20:17.898  1049  1644 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:17.898  1966  2177 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 13:20:17.899  6717  6717 D BluetoothInputDevice: Proxy object connected
08-16 13:20:17.899  6717  6717 D HidProfile: Bluetooth service connected
08-16 13:20:17.903  6873  7463 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:20:17.905  6873  7463 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 13:20:17.905  6873  7463 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 13:20:17.905  6873  7463 D BluetoothMapMasInstance: Accepting socket connection...
08-16 13:20:17.905  6873  7339 D BluetoothAdapterProperties: Scan Mode:21
08-16 13:20:17.905  6873  7339 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-16 13:20:17.907  6717  6717 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 13:20:17.909  1049  1131 D BluetoothManagerService: Message: 30
08-16 13:20:17.910  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:17.911  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:17.911  6873  6873 V BluetoothPbapService: Pbap Service onCreate
08-16 13:20:17.911  6873  6873 V BluetoothPbapService: Starting PBAP service
08-16 13:20:17.911  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:17.912  6873  6873 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 13:20:17.912  6873  6873 V BluetoothPbapService: Pbap Service onBind
08-16 13:20:17.916  6717  6717 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-16 13:20:17.916  6873  6873 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:17.916  6873  6873 V BluetoothPbapService: state: 12
08-16 13:20:17.918  6873  6873 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-16 13:20:17.918  6873  6873 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 13:20:17.919  1049  1131 D BluetoothManagerService: Message: 30
08-16 13:20:17.919  6873  6873 V BluetoothPbapService: Handler(): got msg=1
08-16 13:20:17.919  1966  1966 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 13:20:17.920  1966  2177 D LGBluetoothAPIService: Message: 100
08-16 13:20:17.920  1966  2177 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 13:20:17.920  6873  6873 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 13:20:17.921  6873  7467 V BluetoothPbapService: Pbap Service initSocket
08-16 13:20:17.921  1049  2045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:17.922  6873  7467 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:20:17.923  6873  7467 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 13:20:17.923  6873  7467 V BluetoothPbapService: Succeed to create listening socket 
08-16 13:20:17.923  6873  7467 V BluetoothPbapService: Accepting socket connection...
08-16 13:20:17.923  6717  6717 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 13:20:17.925  6717  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 13:20:17.926  6717  6717 D BluetoothA2dp: Proxy object connected
08-16 13:20:17.927  6873  6873 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 13:20:17.927  6873  6873 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:17.927  6873  6873 V BluetoothPbapReceiver: ***********state = 12
08-16 13:20:17.927  6717  6717 D A2dpProfile: Bluetooth service connected
08-16 13:20:17.930  2239  2239 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:20:17.931  2239  2239 D c       : Getting all permits...
,08-16 13:20:17.931  2239  2239 D a       : Opening database...
08-16 13:20:17.934  2239  2239 D a       : Opening database auth.proximity.permit_store...
08-16 13:20:17.934  2239  2239 D a       : Closing database...
08-16 13:20:17.935  6717  6717 D BluetoothPbap: Proxy object connected
08-16 13:20:17.936  6717  6717 D PbapServerProfile: Bluetooth service connected
08-16 13:20:17.936  6717  6717 D BluetoothHeadset: Proxy object connected
08-16 13:20:17.937  6717  6717 D HeadsetProfile: Bluetooth service connected
08-16 13:20:17.942  6717  6717 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:20:17.946  6717  6717 D BluetoothPermissionRequest: onReceive
08-16 13:20:17.948  6717  6717 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 13:20:17.949  6717  6717 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 13:20:17.952  6873  6873 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 13:20:17.953  6873  6873 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-16 13:20:17.958  6873  6873 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-16 13:20:17.977  6873  6873 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 13:20:17.977  6873  6873 V BtOppService: onCreate
08-16 13:20:17.984  6873  6873 V BluetoothOppNotification: send message
08-16 13:20:17.989  6873  6873 V BtOppService: Starting RfcommListener
,08-16 13:20:17.997  6873  6873 D BluetoothOppPreference: Dumping Names:  
08-16 13:20:17.997  6873  6873 D BluetoothOppPreference: {}
08-16 13:20:17.997  6873  6873 D BluetoothOppPreference: Dumping Channels:  
08-16 13:20:17.997  6873  6873 D BluetoothOppPreference: {}
08-16 13:20:17.999  6873  6873 V BtOppService: onStartCommand
08-16 13:20:18.004  6873  6873 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:18.004  6873  6873 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 13:20:18.004  6873  7475 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-16 13:20:18.009  6873  6873 V BluetoothOppNotification: new notify threadi!
08-16 13:20:18.010  6873  6873 V BluetoothOppNotification: send delay message
08-16 13:20:18.011  6873  6873 V BtOppService: start RfcommListener
08-16 13:20:18.017  6873  7476 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 13:20:18.017  6873  6873 V BtOppService: RfcommListener started
08-16 13:20:18.019  6873  7477 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 13:20:18.019  1049  1588 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:18.019  6873  7472 V BtOppService: Deleted complete outbound shares, number =  0
08-16 13:20:18.020  6873  7475 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-16 13:20:18.021  6873  7477 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 13:20:18.022  6873  7477 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-16 13:20:18.023  6873  7477 V BtOppRfcommListener: Started RFCOMM listener....
08-16 13:20:18.023  6873  7477 I BtOppRfcommListener: Accept thread started.
08-16 13:20:18.023  6873  7477 V BtOppRfcommListener: Accepting connection...
08-16 13:20:18.029  6873  7476 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1522cf69 on behalf of 
08-16 13:20:18.031  6873  7472 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 13:20:18.031  6873  7475 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f3a7dee on behalf of 
08-16 13:20:18.032  6873  7476 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 13:20:18.032  6873  7472 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-16 13:20:18.036  6873  7472 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25a528f on behalf of 
08-16 13:20:18.038  6873  7476 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 13:20:18.039  6873  7476 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f36e91c on behalf of 
08-16 13:20:18.039  6873  7475 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 13:20:18.040  6873  7476 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 13:20:18.042  6873  7476 V BluetoothOppNotification: outbound notification was removed.
08-16 13:20:18.042  6873  7476 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 13:20:18.043  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:18.043  6873  6873 V BluetoothFtpService: Ftp Service onCreate
08-16 13:20:18.043  6873  6873 I BluetoothFtpService: Ftp Service onCreate
08-16 13:20:18.044  6873  6873 V BluetoothFtpService: Ftp Service onStartCommand
08-16 13:20:18.044  6873  6873 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:18.044  6873  6873 V BluetoothFtpService: Starting Listening on sockets
08-16 13:20:18.044  6873  6873 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:20:18.044  6873  6873 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:20:18.044  6873  6873 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 13:20:18.045  6873  6873 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:18.045  6873  7476 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35548afa on behalf of 
08-16 13:20:18.045  6873  6873 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 13:20:18.045  6873  6873 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 13:20:18.046  6873  7476 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 13:20:18.048  6873  6873 V BtOppService: ContentObserver received notification
08-16 13:20:18.049  6873  6873 V BtOppService: ContentObserver received notification
08-16 13:20:18.049  6873  6873 V BluetoothFtpService: Handler(): got msg=1
08-16 13:20:18.049  6873  6873 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 13:20:18.050  6873  6873 V BluetoothFtpService: Ftp Service initSocket
08-16 13:20:18.050  6873  7478 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 13:20:18.050  6873  7478 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 13:20:18.051  6873  7478 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2eb388ab on behalf of 
08-16 13:20:18.055  6873  7476 V BluetoothOppNotification: inbound notification was removed.
08-16 13:20:18.055  1049  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:18.055  6873  7476 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 13:20:18.056  6873  6873 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:20:18.056  6873  7478 V BluetoothOppNotification: update too frequent, put in queue
08-16 13:20:18.058  6873  6873 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
,08-16 13:20:18.058  6873  6873 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 13:20:18.060  6873  7479 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 13:20:18.061  6873  7478 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 13:20:18.061  6873  7476 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35577b08 on behalf of 
08-16 13:20:18.088  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
,08-16 13:20:18.089  6873  6873 V BluetoothSapService: Sap Service onCreate
08-16 13:20:18.091  6873  6873 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:18.091  6873  6873 V BluetoothSapService: state: 12
08-16 13:20:18.091  6873  6873 V BluetoothSapService: Starting SAP server process
08-16 13:20:18.094  6873  6873 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 13:20:18.077  7480  7480 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:18.077  7480  7480 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:18.097  6873  7481 V BluetoothSapService: Sap Service initRfcommSocket
08-16 13:20:18.098  1049  1064 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:18.100  6873  7481 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:20:18.101  6873  7481 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-16 13:20:18.101  6873  7481 V BluetoothSapService: Succeed to create listening socket 
08-16 13:20:18.101  6873  7481 V BluetoothSapService: Accepting socket connection...
08-16 13:20:18.115  7480  7480 V BT_SAP  : Event pipe created
08-16 13:20:18.115  7480  7480 V BT_SAP  : create_server_socket qcom.sap.server
08-16 13:20:18.115  7480  7480 V BT_SAP  : created socket fd 6
,08-16 13:20:18.604  1049  1535 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 13:20:18.604  1049  1535 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 13:20:18.622  1049  1536 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-16 13:20:18.623  1049  1536 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-16 13:20:18.766  1049  2018 I ActivityManager: Killing 7263:com.lge.bnr/1000 (adj 15): empty #17
,08-16 13:20:18.802  1049  2093 W libprocessgroup: failed to open /acct/uid_1000/pid_7263/cgroup.procs: No such file or directory
,08-16 13:20:18.983  1049  2011 I ActivityManager: Killing 6734:com.lge.sync/1000 (adj 15): empty #17
,08-16 13:20:19.011  6873  6873 V BluetoothOppNotification: new notify threadi!
,08-16 13:20:19.014  6873  6873 V BluetoothOppNotification: send delay message
08-16 13:20:19.018  6873  7491 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 13:20:19.021  1049  1542 D WifiService: Client connection lost with reason: 4
08-16 13:20:19.022  6873  7491 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@196d3fb4 on behalf of 
08-16 13:20:19.023  6873  7491 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 13:20:19.024  6873  7491 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-16 13:20:19.028  6873  7491 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@162527dd on behalf of 
08-16 13:20:19.028  6873  7491 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 13:20:19.030  6873  7491 V BluetoothOppNotification: outbound notification was removed.
08-16 13:20:19.030  6873  7491 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 13:20:19.031  6873  7491 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31e57f52 on behalf of 
08-16 13:20:19.032  6873  7491 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 13:20:19.033  6873  7491 V BluetoothOppNotification: inbound notification was removed.
08-16 13:20:19.033  6873  7491 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 13:20:19.034  6873  7491 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36ee6223 on behalf of 
08-16 13:20:19.048  1049  1984 W libprocessgroup: failed to open /acct/uid_1000/pid_6734/cgroup.procs: No such file or directory
,08-16 13:20:19.580  1049  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 13:20:19.581  1049  1933 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2f81a4cd mBinding = false
,08-16 13:20:19.611  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:20:19.611  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 13:20:19.611  1049  1049 D Ulp_jni : JNI:system_update. Event-4
,08-16 13:20:19.614  1049  1131 D BluetoothManagerService: Message: 2
08-16 13:20:19.615  1049  1131 D BluetoothManagerService: Sending off request.
08-16 13:20:19.616  6873  7440 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 13:20:19.617  6873  7335 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 13:20:19.617  6873  7335 D BluetoothAdapterProperties: Setting state to 13
08-16 13:20:19.617  6873  7335 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 13:20:19.618  6873  7335 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 13:20:19.618  6873  7335 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 13:20:19.620  6873  7339 D BluetoothAdapterProperties: Scan Mode:20
08-16 13:20:19.621  6873  7335 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 13:20:19.624  6873  7463 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 13:20:19.624  6873  7463 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:20:19.624  6873  7463 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 13:20:19.624  6873  7463 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 13:20:19.624  6873  7463 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 13:20:19.624  6873  7463 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 13:20:19.624  6873  7463 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 13:20:19.624  6873  7463 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-16 13:20:19.628  6873  7467 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:20:19.628  6873  7477 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:20:19.629  6873  7479 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:20:19.630  6873  7335 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 13:20:19.631  6873  7481 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:20:19.633  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 13:20:19.633  6873  7404 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 13:20:19.635  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:20:19.635  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:20:19.635  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:20:19.635  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:20:19.635  6873  7404 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:20:19.635  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:20:19.635  6873  7404 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:20:19.635  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:20:19.635  6873  7404 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 13:20:19.635  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 13:20:19.635  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 13:20:19.635  6873  7404 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 13:20:19.645  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:19.645  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:20:19.645  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:19.645  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:19.645  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:20:19.645  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:20:19.645  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:19.645  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:19.645  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:20:19.650  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:19.650  6636  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:20:19.652  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:19.652  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:20:19.652  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:19.652  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:19.652  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:20:19.652  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:20:19.652  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:19.652  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:19.652  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:20:19.654  6636  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:20:19.654  6636  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:20:19.657  1049  1131 D BluetoothManagerService: Message: 60
08-16 13:20:19.657  1049  1131 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 13:20:19.657  1049  1131 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-16 13:20:19.663  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:19.664  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 13:20:19.670  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:19.672  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:20:19.675  6873  6873 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:19.675  6873  6873 D BluetoothMapService: STATE_TURNING_OFF
08-16 13:20:19.675  6873  6873 V BluetoothMapService: Handler(): got msg=4
08-16 13:20:19.676  6873  6873 D BluetoothMapService: MAP Service closeService in
08-16 13:20:19.676  6873  6873 D BluetoothMapMasInstance: MAP Service shutdown
08-16 13:20:19.676  6873  6873 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 13:20:19.676  6873  6873 V BluetoothMapService: MAP Service closeService out
08-16 13:20:19.677  6873  6873 V BtOppService: Receiver DISABLED_ACTION 
08-16 13:20:19.678  6873  6873 I BtOppRfcommListener: stopping Accept Thread
08-16 13:20:19.678  6873  6873 V BtOppRfcommListener: close mBtServerSocket
08-16 13:20:19.678  6873  7477 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 13:20:19.679  6873  6873 V BtOppRfcommListener: waiting for thread to terminate
08-16 13:20:19.679  6873  6873 V BtOppRfcommListener: done waiting for thread to terminate
08-16 13:20:19.682  6717  6717 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-16 13:20:19.695  6717  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 13:20:19.700  6873  6873 V BtOppService: onDestroy
08-16 13:20:19.701  6873  6873 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-16 13:20:19.705  6873  6873 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 13:20:19.705  6873  6873 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:19.705  6873  6873 V BluetoothPbapReceiver: ***********state = 13
08-16 13:20:19.707  6873  6873 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 13:20:19.709  6873  6873 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:19.709  6873  6873 V BluetoothPbapService: state: 13
08-16 13:20:19.710  6873  6873 V BluetoothPbapService: Pbap Service closeService in
08-16 13:20:19.713  2239  2239 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:20:19.716  6873  6873 V BluetoothPbapService: successfully stopped pbap service
08-16 13:20:19.716  6873  6873 V BluetoothPbapService: Pbap Service closeService out
08-16 13:20:19.717  6873  6873 V BluetoothPbapService: Pbap Service onDestroy
08-16 13:20:19.717  6873  6873 V BluetoothPbapService: Pbap Service closeService in
08-16 13:20:19.717  6873  6873 V BluetoothPbapService: Pbap Service closeService out
08-16 13:20:19.717  6873  6873 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 13:20:19.739  6717  6717 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:20:19.750  6717  6717 D BluetoothPbap: Proxy object disconnected
08-16 13:20:19.750  6717  6717 D PbapServerProfile: Bluetooth service disconnected
08-16 13:20:19.754  6717  6717 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 13:20:19.762  6717  6717 D BluetoothPermissionRequest: onReceive
08-16 13:20:19.762  6717  6717 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 13:20:19.774  6717  6717 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 13:20:19.777  6873  6873 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 13:20:19.777  6873  6873 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-16 13:20:19.779  6873  6873 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 13:20:19.785  6873  6873 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:19.785  6873  6873 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 13:20:19.786  6873  6873 V BluetoothFtpService: Ftp Service onStartCommand
08-16 13:20:19.787  6873  6873 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:19.787  6873  6873 V BluetoothFtpService: Ftp Service closeService
08-16 13:20:19.788  6873  6873 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 13:20:19.789  6873  6873 V BluetoothFtpService: successfully stopped ftp service
,08-16 13:20:19.789  6873  6873 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:20:19.790  6873  6873 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:20:19.790  6873  6873 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 13:20:19.790  6873  6873 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:19.790  6873  6873 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 13:20:19.790  6873  6873 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-16 13:20:19.792  6873  6873 V BluetoothFtpService: Ftp Service onDestroy
08-16 13:20:19.792  6873  6873 V BluetoothFtpService: Ftp Service closeService
,08-16 13:20:19.798  6873  6873 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:19.798  6873  6873 V BluetoothSapService: state: 13
08-16 13:20:19.798  6873  6873 V BluetoothSapService: Stopping SAP server process
08-16 13:20:19.799  6873  6873 V BluetoothSapService: Sap Service closeSapService in
08-16 13:20:19.799  6873  6873 V BluetoothSapService: Close listen Socket : 
08-16 13:20:19.799  6873  6873 V BluetoothSapService: Close rfcomm Socket : 
08-16 13:20:19.799  6873  6873 V BluetoothSapService: Close sapd  Socket : 
08-16 13:20:19.802  6873  6873 V BluetoothSapService: Sap Service closeSapService out
08-16 13:20:19.802  6873  6873 V BluetoothSapService: Sap Service onDestroy
,08-16 13:20:19.802  6873  6873 V BluetoothSapService: Sap Service closeSapService in
,08-16 13:20:19.802  6873  6873 V BluetoothSapService: Close listen Socket : 
08-16 13:20:19.802  6873  6873 V BluetoothSapService: Close rfcomm Socket : 
08-16 13:20:19.802  6873  6873 V BluetoothSapService: Close sapd  Socket : 
,08-16 13:20:19.804  6873  6873 V BluetoothSapService: Sap Service closeSapService out
08-16 13:20:20.637  6873  7339 D bt_hci_bdroid: cleanup
,08-16 13:20:20.646  6873  7406 I bt_lpm  : LPM is already off!!!
08-16 13:20:20.648  6873  7404 W bt-btif : ag scb idx 1 not allocated
08-16 13:20:20.648  6873  7404 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 13:20:20.649  6873  7404 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 13:20:20.649  6873  7404 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-16 13:20:20.651  6873  7436 I bt_userial_mct: exiting userial_read_thread
08-16 13:20:20.651  6873  7436 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 13:20:20.652  6873  7339 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 13:20:20.652  6873  7406 I bt_vendor: hw_epilog_process
08-16 13:20:20.652  6873  7339 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 13:20:20.652  6873  7339 D bt_userial_mct: userial_close
08-16 13:20:20.652  6873  7339 E bt_userial_mct: pthread_join() FAILED result:3
08-16 13:20:20.653  6873  7339 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 13:20:20.658  6873  7339 D bt_hci_bdroid: set_power 0
08-16 13:20:20.658  6873  7339 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 13:20:20.658  6873  7339 I bt_vendor: bluetooth satus is on
08-16 13:20:20.658  6873  7339 I bt_vendor: bt-vendor : resetting BT status
08-16 13:20:20.658  6873  7339 I bt_vendor: Starting hciattach daemon
,08-16 13:20:20.658  6873  7339 I bt_vendor: try to set false
,08-16 13:20:20.665  6873  7339 I bt_vendor: Starting hciattach daemon
08-16 13:20:20.665  6873  7339 I bt_vendor: try to set false
08-16 13:20:20.667  6873  7339 I bt_vendor: cleanup
08-16 13:20:20.667  6873  7404 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 13:20:20.668  6873  7339 I GKI_LINUX: GKI_exit_task 0 done
08-16 13:20:20.668  6873  7339 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 13:20:20.670  6873  7335 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 13:20:20.674  6873  6873 D HeadsetService: Received stop request...Stopping profile...
,08-16 13:20:20.678  6873  6873 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 13:20:20.678  6873  6873 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 13:20:20.678  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:20.680  6873  7373 D HeadsetStateMachine: Exit Disconnected: -1
08-16 13:20:20.684  1876  1876 D BluetoothHeadset: Proxy object disconnected
08-16 13:20:20.684  1876  1876 D BluetoothHeadset: Proxy object disconnected
08-16 13:20:20.684  1876  1876 D BluetoothHeadset: Proxy object disconnected
08-16 13:20:20.684  1049  1049 D BluetoothHeadset: Proxy object disconnected
08-16 13:20:20.684  1049  1049 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 13:20:20.687  6873  6873 D A2dpService: Received stop request...Stopping profile...
,08-16 13:20:20.690  6873  7389 D A2dpStateMachine: Exit Disconnected: -1
08-16 13:20:20.693  6873  7335 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 13:20:20.694  6873  6873 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 13:20:20.695  6873  6873 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 13:20:20.695  6873  6873 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 13:20:20.695  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:20.697  1049  1049 D BluetoothA2dp: Proxy object disconnected
08-16 13:20:20.697  1049  1049 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 13:20:20.698  6873  6873 D HidService: Received stop request...Stopping profile...
08-16 13:20:20.698  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:20.701  6873  6873 D HealthService: Received stop request...Stopping profile...
08-16 13:20:20.701  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
,08-16 13:20:20.705  6873  6873 D HeadsetStateMachine: Unbinding service...
08-16 13:20:20.708  6873  6873 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 13:20:20.708  6873  6873 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 13:20:20.708  6873  6873 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 13:20:20.708  6873  6873 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 13:20:20.708  6873  6873 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 13:20:20.708  6873  6873 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 13:20:20.708  6873  6873 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 13:20:20.709  6873  6873 D PanService: Received stop request...Stopping profile...
08-16 13:20:20.710  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:20.711  6873  6873 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 13:20:20.712  6873  6873 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 13:20:20.712  6873  6873 D BtGatt.GattService: stop()
08-16 13:20:20.712  6873  6873 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 13:20:20.713  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
,08-16 13:20:20.717  6873  6873 D BluetoothMapService: Received stop request...Stopping profile...
08-16 13:20:20.717  6873  6873 D BluetoothMapService: stop()
08-16 13:20:20.719  6873  6873 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 13:20:20.719  6873  6873 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 13:20:20.720  6873  6873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27257ef4
08-16 13:20:20.721  6873  6873 I BluetoothA2dpServiceJni: cleanupNative
08-16 13:20:20.721  6873  7390 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 13:20:20.721  6873  6873 I GKI_LINUX: GKI_exit_task 2 done
08-16 13:20:20.721  6873  6873 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 13:20:20.722  6873  6873 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 13:20:20.722  6873  6873 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 13:20:20.722  6873  6873 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 13:20:20.722  6873  6873 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 13:20:20.723  6873  6873 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 13:20:20.723  6873  6873 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 13:20:20.723  6873  6873 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 13:20:20.726  6873  6873 V BluetoothMapService: Handler(): got msg=4
08-16 13:20:20.726  6873  6873 D BluetoothMapService: MAP Service closeService in
08-16 13:20:20.726  6873  6873 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 13:20:20.726  6873  6873 V BluetoothMapService: MAP Service closeService out
,08-16 13:20:20.729  6873  7335 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 13:20:20.729  6873  7335 D BluetoothAdapterProperties: Setting state to 10
08-16 13:20:20.729  6873  7335 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 13:20:20.731  6873  6873 D BluetoothMapService: cleanup()
08-16 13:20:20.731  6873  6873 D BluetoothMapService: MAP Service closeService in
08-16 13:20:20.731  6873  6873 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 13:20:20.731  6873  6873 V BluetoothMapService: MAP Service closeService out
08-16 13:20:20.732  1049  1131 D BluetoothManagerService: Message: 60
08-16 13:20:20.732  1049  1131 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 13:20:20.732  1049  1131 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-16 13:20:20.732  1049  1131 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 13:20:20.733  6873  7335 I BluetoothAdapterState: Entering OffState
08-16 13:20:20.733  6717  6732 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:20:20.736  6717  6732 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 13:20:20.737  1876  2320 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:20:20.738  6717  6732 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 13:20:20.741  6717  6732 D BluetoothPan: onBluetoothStateChange on: false
08-16 13:20:20.743  1876  1891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:20:20.743  6717  6732 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 13:20:20.744  1876  4012 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:20:20.744  1049  1131 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:20:20.745  6717  6732 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 13:20:20.745  1049  1131 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 13:20:20.746  1049  1131 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 13:20:20.748  1049  1131 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 13:20:20.748  1049  1131 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 13:20:20.748  1049  1131 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2f81a4cd mBinding = false
08-16 13:20:20.749  1049  1131 D BluetoothManagerService: Sending unbind request.
08-16 13:20:20.753  6873  7339 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 13:20:20.756  6873  6873 I GKI_LINUX: GKI_exit_task 1 done
08-16 13:20:20.756  6873  6873 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 13:20:20.757  6873  6873 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 13:20:20.757  6873  6873 I art     : --- WEIRD: removing null entry 248
08-16 13:20:20.758  6873  6873 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-16 13:20:20.758  6873  6873 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 13:20:20.758  6873  6873 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 13:20:20.760  1049  1131 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 13:20:20.762  6873  6873 I art     : System.exit called, status: 0
08-16 13:20:20.762  6873  6873 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 13:20:20.781   310   310 V AudioFlinger: 6873 died, releasing its sessions
08-16 13:20:20.781   310   310 V AudioFlinger:  pid 1876 @ 0
08-16 13:20:20.781   310   310 V AudioFlinger:  pid 3370 @ 1
08-16 13:20:20.781   310   310 V AudioFlinger:  pid 3370 @ 2
,08-16 13:20:20.785  1966  1966 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-16 13:20:20.785  1966  2177 D LGBluetoothAPIService: Message: 101
08-16 13:20:20.785  1966  2177 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-16 13:20:20.785  1966  2177 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-16 13:20:20.785  1966  2177 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-16 13:20:20.787  6717  6717 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 13:20:20.878  1049  2045 I ActivityManager: Process com.android.bluetooth (pid 6873) has died
,08-16 13:20:20.878  1049  2045 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-16 13:20:20.879  1049  2045 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-16 13:20:20.886  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:20.887  1966  2177 D LGBluetoothAPIService: Message: 2
08-16 13:20:20.887  1966  2177 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-16 13:20:20.889  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 13:20:20.892  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:20.893  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:20:20.897  6717  6717 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-16 13:20:20.897  6717  6717 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 13:20:20.901  1602  1602 D BluetoothAdapter: 685001113: getState() :  mService = null. Returning STATE_OFF
08-16 13:20:20.901  1602  1602 D BluetoothAdapter: 685001113: getState() :  mService = null. Returning STATE_OFF
08-16 13:20:20.902  6717  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 13:20:20.963  1049  1065 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7539 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-16 13:20:20.965  6717  6717 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:20:21.168  1049  2045 I art     : Explicit concurrent mark sweep GC freed 92429(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.979ms total 141.684ms
,08-16 13:20:21.201  7539  7539 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 13:20:21.202  7539  7539 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:20:21.202  7539  7539 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 13:20:21.202  7539  7539 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 13:20:21.231  7539  7539 D BluetoothAdapterApp: Loading JNI Library
,08-16 13:20:21.267  7539  7539 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@265b805c Instance Count = 1
,08-16 13:20:21.273  7539  7539 D BluetoothAdapterApp: onCreate
08-16 13:20:21.300  7539  7539 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-16 13:20:21.300  7539  7539 D ProfileConfigQcom: Adding HeadsetService
08-16 13:20:21.300  7539  7539 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 13:20:21.300  7539  7539 D ProfileConfigQcom: Adding A2dpService
08-16 13:20:21.301  7539  7539 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 13:20:21.301  7539  7539 D ProfileConfigQcom: Adding HidService
08-16 13:20:21.301  7539  7539 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 13:20:21.301  7539  7539 D ProfileConfigQcom: Adding HealthService
08-16 13:20:21.302  7539  7539 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 13:20:21.303  7539  7539 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 13:20:21.303  7539  7539 D ProfileConfigQcom: Adding PanService
08-16 13:20:21.303  7539  7539 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 13:20:21.303  7539  7539 D ProfileConfigQcom: Adding GattService
08-16 13:20:21.304  7539  7539 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 13:20:21.304  7539  7539 D ProfileConfigQcom: Adding BluetoothMapService
08-16 13:20:21.304  7539  7539 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 13:20:21.305  7539  7539 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 13:20:21.306  7539  7539 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:21.307  7539  7539 V BluetoothPbapReceiver: ***********state = 10
08-16 13:20:21.309  7539  7539 V LGMDMManagerInternal: Create singleton instance
08-16 13:20:21.402  2239  2239 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 13:20:21.403  7539  7539 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 13:20:21.404  7539  7539 D LGBluetoothAPIServer: [BTUI] onBind()
,08-16 13:20:21.411  1966  1966 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 13:20:21.411  1966  2177 D LGBluetoothAPIService: Message: 100
08-16 13:20:21.411  1966  2177 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 13:20:21.427  6717  6717 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 13:20:21.429  6717  6717 D BluetoothPermissionRequest: onReceive
,08-16 13:20:21.432  6717  6717 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 13:20:21.432  6717  6717 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 13:20:21.435  6717  6717 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 13:20:21.441  7539  7539 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-16 13:20:21.446  7539  7539 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:21.449  7539  7539 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:20:21.450  7539  7539 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:20:21.450  7539  7539 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 13:20:21.451  7539  7539 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:21.451  7539  7539 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 13:20:21.455  6801  6801 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 13:20:22.638  1049  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 13:20:22.642  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
08-16 13:20:22.674  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:22.674  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:20:22.734  1049  1049 D administrator: Handling package changes for user 0
,08-16 13:20:22.743  1049  1124 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7567 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-16 13:20:22.751  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 13:20:22.755  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-16 13:20:22.770  2094  2094 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 13:20:22.818  2094  2094 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 13:20:22.834  7567  7567 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 13:20:22.875  1049  1049 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 13:20:22.875  1049  1049 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 13:20:22.916  7567  7567 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:20:22.916  7567  7567 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:20:22.940  1049  1122 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 13:20:22.947  1049  1122 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 13:20:22.959  2094  2094 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-16 13:20:22.962  2467  2467 V GmsNetworkLocationProvi: DISABLE
08-16 13:20:22.984  1049  1122 D LocationProviderProxy: applying state to connected service
,08-16 13:20:22.986  2467  2467 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-16 13:20:23.051  7567  7611 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-16 13:20:23.051  7567  7611 I Babel   : MmsConfig.loadMmsSettings
08-16 13:20:23.054  7567  7611 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 13:20:23.054  7567  7611 I Babel   : MmsConfig.loadFromDatabase
,08-16 13:20:23.077  7567  7611 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 13:20:23.078  7567  7611 I Babel   : MmsConfig.loadFromResources
08-16 13:20:23.080  7567  7611 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 13:20:23.081  7567  7611 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-16 13:20:23.092  7567  7567 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 13:20:23.120  7567  7610 W AudioCapabilities: Unsupported mime audio/evrc
08-16 13:20:23.121  7567  7610 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 13:20:23.125  7567  7610 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 13:20:23.129  1841  7615 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 13:20:23.129  1841  7615 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-16 13:20:23.130  6921  6921 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 13:20:23.139  6921  6921 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@cce3a06
08-16 13:20:23.139  6921  6921 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-16 13:20:23.139  6921  6921 D AppUp4:CustFacade: isPhone : true
08-16 13:20:23.140  6921  6921 D AppUp4:CustModeStarterReceiver: begin check event
08-16 13:20:23.140  6921  6921 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 13:20:23.142  1841  4756 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-16 13:20:23.150  7567  7610 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-16 13:20:23.151  7567  7610 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 13:20:23.152  7567  7610 W AudioCapabilities: Unsupported mime audio/evrc
08-16 13:20:23.163  7567  7610 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-16 13:20:23.165  7567  7610 W VideoCapabilities: Unsupported mime video/divx
08-16 13:20:23.167  7567  7610 W VideoCapabilities: Unsupported mime video/divx311
08-16 13:20:23.169  7567  7610 W VideoCapabilities: Unsupported mime video/divx4
,08-16 13:20:23.173  7567  7610 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-16 13:20:23.186  7567  7610 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-16 13:20:23.187  1049  1065 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7618 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-16 13:20:23.191  1049  1064 I ActivityManager: Killing 6526:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-16 13:20:23.197  7567  7610 W AudioCapabilities: Unsupported mime audio/eac3
08-16 13:20:23.198  7567  7610 W AudioCapabilities: Unsupported mime audio/ac3
08-16 13:20:23.199  7567  7610 W AudioCapabilities: Unsupported mime audio/g726
08-16 13:20:23.201  7567  7610 W AudioCapabilities: Unsupported mime audio/wma-voice
,08-16 13:20:23.202  7567  7610 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 13:20:23.203  7567  7610 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 13:20:23.205  7567  7610 W VideoCapabilities: Unsupported mime video/theora
08-16 13:20:23.206  6781  6781 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-16 13:20:23.207  6781  6781 W System.err: android.os.DeadObjectException
08-16 13:20:23.207  6781  6781 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 13:20:23.207  6781  6781 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 13:20:23.207  6781  6781 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 13:20:23.207  6781  6781 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 13:20:23.207  6781  6781 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 13:20:23.207  6781  6781 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 13:20:23.207  6781  6781 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 13:20:23.207  6781  6781 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 13:20:23.208  7567  7610 W VideoCapabilities: Unsupported mime video/mjpg
08-16 13:20:23.208  6781  6781 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:20:23.208  6781  6781 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:20:23.209  6781  6781 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:20:23.209  6781  6781 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:20:23.209  6781  6781 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:20:23.209  6781  6781 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 13:20:23.209  6781  6781 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-16 13:20:23.209  6781  6781 W System.err: android.os.DeadObjectException
08-16 13:20:23.209  6781  6781 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 13:20:23.209  6781  6781 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 13:20:23.210  6781  6781 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 13:20:23.210  6781  6781 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 13:20:23.210  6781  6781 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 13:20:23.210  6781  6781 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 13:20:23.210  6781  6781 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 13:20:23.210  6781  6781 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 13:20:23.210  6781  6781 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:20:23.210  6781  6781 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:20:23.210  6781  6781 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:20:23.210  6781  6781 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:20:23.210  6781  6781 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:20:23.210  6781  6781 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 13:20:23.210  6781  6781 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 13:20:23.210  6781  6781 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind befor,e rebinding.
08-16 13:20:23.399  1049  1064 E libprocessgroup: failed to kill 1 processes for processgroup 6526
,08-16 13:20:23.524  1049  1588 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-16 13:20:23.564  6781  6781 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,08-16 13:20:23.564  6781  6781 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-16 13:20:23.599  7618  7618 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 13:20:23.600  7618  7618 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:20:23.600  7618  7618 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 13:20:23.601  7618  7618 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 13:20:23.602  7618  7618 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-16 13:20:23.613  1049  1933 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7641 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 13:20:23.615  6781  6781 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 13:20:23.628  1049  1543 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-16 13:20:23.687  7641  7641 D UEI.SmartControl: Quickset Services start...
08-16 13:20:23.689  7641  7641 I UEI.SmartControl: Manufacture = LGE
,08-16 13:20:23.689  7641  7641 D UEI.SmartControl: Id = LGNevo
08-16 13:20:23.691  7641  7641 D UEI.SmartControl: File observer start...
08-16 13:20:23.691  7641  7641 E UEI.SmartControl: IR Port is disabled: false
08-16 13:20:23.691  7641  7641 D UEI.SmartControl: Starting file observer...
08-16 13:20:23.691  7641  7641 D UEI.SmartControl: Extracting JNI libs...
08-16 13:20:23.691  7641  7641 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-16 13:20:23.697  7618  7618 I SystemConfig: BUILD Country: EU
08-16 13:20:23.697  7618  7618 I SystemConfig: BUILD Operator: OPEN
08-16 13:20:23.738  1049  1963 I ActivityManager: Killing 6781:com.lge.qremote/u0a112 (adj 15): empty #17
08-16 13:20:23.741  7641  7641 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-16 13:20:23.741  7641  7641 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 13:20:23.741  7641  7641 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-16 13:20:23.761  7641  7641 I UEI.SmartControl: --- Selecting new region: 6
,08-16 13:20:23.763  7641  7641 I UEI.SmartControl: Model = LG-D855
,08-16 13:20:23.764  7641  7641 D UEI.SmartControl: QS Service created
08-16 13:20:23.849  1049  2018 W libprocessgroup: failed to open /acct/uid_10112/pid_6781/cgroup.procs: No such file or directory
,08-16 13:20:23.860  7618  7669 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 13:20:23.862  7618  7669 I SystemConfig: existFile = false
08-16 13:20:23.864  7618  7669 I SystemConfig: canReadFile = false
08-16 13:20:23.865  7618  7669 I SystemConfig: systemFeature RCS result false
08-16 13:20:23.866  7618  7669 D SystemConfig: refreshRcsSupport() :false
,08-16 13:20:23.885  7641  7641 I UEI.SmartControl: Service initServices...
,08-16 13:20:23.890  7641  7641 D UEI.SmartControl: QS start get config
08-16 13:20:23.931  1049  1963 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7673 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 13:20:23.959  7641  7641 D UEI.SmartControl: Loading JNI Libs...
,08-16 13:20:24.016  7673  7673 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 13:20:24.016  7673  7673 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 13:20:24.016  7673  7673 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 13:20:24.017  7673  7673 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 13:20:24.099  7673  7673 I AppConfig: Total System Memory = 2995761152
,08-16 13:20:24.108  7673  7673 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-16 13:20:24.169  1049  1064 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7701 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 13:20:24.171  1049  1064 I ActivityManager: Killing 6949:com.lge.email/u0a23 (adj 15): empty #17
,08-16 13:20:24.238  1049  1644 W libprocessgroup: failed to open /acct/uid_10023/pid_6949/cgroup.procs: No such file or directory
,08-16 13:20:24.279  7641  7641 I UEI.SmartControl: Supports setup maps: true
,08-16 13:20:24.282  7641  7641 D UEI.SmartControl: QS start statue = true Error code = 0
,08-16 13:20:24.282  7641  7641 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 13:20:24.282  7641  7641 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 13:20:24.283  7641  7641 I UEI.SmartControl: ### init IR Blaster...
08-16 13:20:24.288  7641  7641 D serial_port: Configuring serial port
08-16 13:20:24.291  7641  7641 E UEI.SmartControl: UEIBLaster setting for 616
08-16 13:20:24.291  7641  7641 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 13:20:24.291  7641  7641 I UEI.SmartControl: configuring settings for MAXQ616
08-16 13:20:24.291  7641  7641 I UEI.SmartControl: Get version...
08-16 13:20:24.308  7641  7718 D UEI.SmartControl: serial port data available: 21
,08-16 13:20:24.335  7641  7641 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 13:20:24.335  7641  7641 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 13:20:24.336  7641  7641 I UEI.SmartControl: QS saving settings...
,08-16 13:20:24.337  7641  7641 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 13:20:24.354  7641  7718 D UEI.SmartControl: serial port data available: 4
,08-16 13:20:24.391  7641  7728 I UEI.SmartControl: Device manager: loading config....
08-16 13:20:24.392  7641  7728 D UEI.SmartControl: ----------- loading internal config...
08-16 13:20:24.393  7641  7641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 13:20:24.398  7641  7641 E UEI.SmartControl: Services init done
,08-16 13:20:24.398  7641  7641 D UEI.SmartControl: QS Service init finished
08-16 13:20:24.403  7641  7641 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 13:20:24.403  7641  7641 D UEI.SmartControl: QS Service version code: 201091
08-16 13:20:24.404  7641  7641 D UEI.SmartControl: Service requested: Control
08-16 13:20:24.410  7641  7728 E UEI.SmartControl: Loading SETTINGS...
08-16 13:20:24.416  7641  7641 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-16 13:20:24.419  7641  7641 D UEI.SmartControl: Service.onUnbind: IControl
,08-16 13:20:24.421  7641  7641 D UEI.SmartControl: Service.onDestroy
08-16 13:20:24.422  7641  7641 D UEI.SmartControl: Lock is in USE false
08-16 13:20:24.422  7641  7641 D UEI.SmartControl: unbind internal service
08-16 13:20:24.425  7641  7641 D serial_port: close(fd = 25)
08-16 13:20:24.429  7641  7641 I UEI.SmartControl: Serial port is closed.
08-16 13:20:24.429  7641  7641 I UEI.SmartControl: Serial port is closed.
08-16 13:20:24.430  7641  7641 D UEI.SmartControl: Blaster closed
08-16 13:20:24.430  7641  7727 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 13:20:24.430  7641  7641 D UEI.SmartControl: Shut down QS...
08-16 13:20:24.430  7641  7727 D UEI.SmartControl: -----service ready thread exits
08-16 13:20:24.430  7641  7641 D UEI.SmartControl: Stopping QS lib
,08-16 13:20:24.431  7641  7641 D UEI.SmartControl: QS lib stop result = true
08-16 13:20:24.434  7641  7641 D UEI.SmartControl: Stopped QS lib
08-16 13:20:24.434  7641  7728 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 13:20:24.435  7641  7641 D UEI.SmartControl: Stopped file observer...
08-16 13:20:24.435  7641  7641 D UEI.SmartControl: QS shutdown complete
08-16 13:20:24.438  7641  7641 D UEI.SmartControl: QS Service created
08-16 13:20:24.453  7641  7641 I UEI.SmartControl: Service initServices...
,08-16 13:20:24.453  7641  7641 D UEI.SmartControl: QS start get config
08-16 13:20:24.474  7701  7701 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 13:20:24.555  7701  7701 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:20:24.555  7701  7701 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 13:20:24.604  7701  7701 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 13:20:24.631  7701  7701 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 13:20:24.633  7701  7701 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 13:20:24.657  7701  7701 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 13:20:24.657  7701  7701 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 13:20:24.674  1049  2111 I ActivityManager: Killing 6821:com.lge.formmanager/u0a26 (adj 15): empty #17
08-16 13:20:24.814  1049  1064 W libprocessgroup: failed to open /acct/uid_10026/pid_6821/cgroup.procs: No such file or directory
,08-16 13:20:24.837  4583  7747 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-16 13:20:24.841  3465  3485 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-16 13:20:24.848  3465  3485 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@5eebb4a on behalf of 7701
08-16 13:20:24.896  1049  2045 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7748 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 13:20:24.923  7701  7701 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-16 13:20:24.934  7641  7641 I UEI.SmartControl: Supports setup maps: true
08-16 13:20:24.935  7701  7701 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-16 13:20:24.937  7641  7641 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 13:20:24.937  7641  7641 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 13:20:24.938  7641  7641 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 13:20:24.938  7641  7641 I UEI.SmartControl: ### init IR Blaster...
,08-16 13:20:24.944  7641  7641 D serial_port: Configuring serial port
08-16 13:20:24.945  7641  7641 E UEI.SmartControl: UEIBLaster setting for 616
08-16 13:20:24.945  7641  7641 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 13:20:24.945  7641  7641 I UEI.SmartControl: configuring settings for MAXQ616
08-16 13:20:24.945  7641  7641 I UEI.SmartControl: Get version...
08-16 13:20:24.962  7641  7768 D UEI.SmartControl: serial port data available: 21
,08-16 13:20:24.964  7748  7748 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-16 13:20:24.978  7748  7748 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 13:20:24.978  7748  7748 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 13:20:24.978  7748  7748 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 13:20:24.978  7748  7748 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 13:20:24.978  7748  7748 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 13:20:24.978  7748  7748 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-16 13:20:24.988  7641  7641 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 13:20:24.988  7641  7641 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 13:20:24.988  7641  7641 I UEI.SmartControl: QS saving settings...
08-16 13:20:24.988  7641  7641 D UEI.SmartControl: IR Blaster version: 25672567
08-16 13:20:24.995  1049  1933 I ActivityManager: Killing 6296:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-16 13:20:25.004  7641  7768 D UEI.SmartControl: serial port data available: 4
08-16 13:20:25.029  1049  1963 W libprocessgroup: failed to open /acct/uid_1000/pid_6296/cgroup.procs: No such file or directory
,08-16 13:20:25.034  7641  7641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 13:20:25.036  7641  7641 E UEI.SmartControl: Services init done
08-16 13:20:25.036  7641  7641 D UEI.SmartControl: QS Service init finished
,08-16 13:20:25.038  7641  7641 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 13:20:25.038  7641  7641 D UEI.SmartControl: QS Service version code: 201091
08-16 13:20:25.038  7641  7641 D UEI.SmartControl: Service requested: Control
08-16 13:20:25.039  7641  7772 I UEI.SmartControl: Device manager: loading config....
08-16 13:20:25.040  1049  2069 I ActivityManager: Killing 6999:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-16 13:20:25.041  7641  7772 D UEI.SmartControl: ----------- loading internal config...
,08-16 13:20:25.048  7641  7772 E UEI.SmartControl: Loading SETTINGS...
08-16 13:20:25.053  7641  7772 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 13:20:25.061  7641  7771 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 13:20:25.061  7641  7771 D UEI.SmartControl: -----service ready thread exits
,08-16 13:20:25.129  1049  1065 W libprocessgroup: failed to open /acct/uid_10046/pid_6999/cgroup.procs: No such file or directory
,08-16 13:20:25.133  7641  7641 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@2f03f092 that was originally bound here
08-16 13:20:25.133  7641  7641 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@2f03f092 that was originally bound here
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:20:25.133  7641  7641 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 13:20:25.139  7641  7641 D UEI.SmartControl: Internal service binding...
08-16 13:20:25.292  1049  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{8e8994e type 2 when 219519 com.google.android.gms} when 219519
,08-16 13:20:25.301   306  7775 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 13:20:25.301  1049  1129 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-16 13:20:25.338  1049  2111 V SIM_STK : Menu title from STK is T-Mobile
,08-16 13:20:25.361  4583  7747 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 523 ms] updated apps [took 523 ms] 
,08-16 13:20:25.431  7641  7730 D UEI.SmartControl: Internal timer expired: 2
,08-16 13:20:25.754  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 13:20:25.754  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1117d38e added. We now have 6 listener(s)
08-16 13:20:25.754  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:20:25.767  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 13:20:25.767  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@376e87af added. We now have 7 listener(s)
08-16 13:20:25.767  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:20:25.770  6636  6692 I System.out: IsBluetoothEnabled
08-16 13:20:25.775  1049  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:25.775  1049  1963 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,08-16 13:20:25.780  1049  1131 D BluetoothManagerService: Message: 2
08-16 13:20:25.783  6636  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:25.784  1049  1758 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:25.784  1049  1758 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-16 13:20:25.797  1049  1131 D BluetoothManagerService: Message: 1
08-16 13:20:25.797  1049  1131 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-16 13:20:25.804  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:20:25.804  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 13:20:25.804  1049  1049 D Ulp_jni : JNI:system_update. Event-4
,08-16 13:20:25.833  1049  1131 D BluetoothManagerService: Message: 20
08-16 13:20:25.834  1049  1131 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c430e8b:true
,08-16 13:20:25.837  7539  7539 D BluetoothAdapterState: make
08-16 13:20:25.842  7539  7539 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 13:20:25.842  7539  7539 I bluedroid-qcom: init
08-16 13:20:25.843  7539  7785 I BluetoothAdapterState: Entering OffState
08-16 13:20:25.844  7539  7539 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 13:20:25.844  7539  7539 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 13:20:25.844  7539  7539 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 13:20:25.844  7539  7539 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 13:20:25.844  7539  7539 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 13:20:25.846  7539  7539 I bluedroid-qcom: get_profile_interface socket
08-16 13:20:25.846  7539  7539 I bluedroid-qcom: get_profile_interface map_client
,08-16 13:20:25.850  7539  7789 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 13:20:25.837  7788  7788 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:25.837  7788  7788 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:25.860  1049  1049 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-16 13:20:25.862  1049  1131 D BluetoothManagerService: Message: 40
08-16 13:20:25.862  1049  1131 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 13:20:25.863  7539  7555 I bluedroid-qcom: config_hci_snoop_log
08-16 13:20:25.865  1049  1131 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 13:20:25.865  1049  1131 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 13:20:25.869  7539  7789 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 13:20:25.872  7788  7788 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 13:20:25.872  7788  7788 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 13:20:25.872  7788  7788 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-16 13:20:25.876  7788  7788 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 13:20:25.879  1049  1049 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 13:20:25.879  1049  1049 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 13:20:25.880  7539  7789 D BluetoothAdapterProperties: Name is: G3
08-16 13:20:25.891  7539  7785 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 13:20:25.891  7539  7785 D BluetoothAdapterProperties: Setting state to 11
08-16 13:20:25.891  7539  7785 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-16 13:20:25.896  7539  7785 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 13:20:25.898  1049  1131 D BluetoothManagerService: Message: 60
08-16 13:20:25.898  1049  1131 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 13:20:25.898  1049  1131 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 13:20:25.902  7788  7788 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 13:20:25.902  7788  7788 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 13:20:25.906  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-16 13:20:25.913  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:25.925  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:20:25.928  6717  6717 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 13:20:25.932  7539  7785 D BluetoothBondStateMachine: make
08-16 13:20:25.935  7539  7785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c5d961d
08-16 13:20:25.935  7539  7785 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 13:20:25.935  7539  7785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c5d961d
08-16 13:20:25.935  7539  7785 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 13:20:25.936  7539  7785 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 13:20:25.936  7539  7804 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 13:20:25.938  7539  7539 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 13:20:25.939  7539  7539 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:25.939  7539  7539 V BluetoothPbapReceiver: ***********state = 11
,08-16 13:20:25.944  7539  7785 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:20:25.945  2239  2239 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 13:20:25.959  7539  7785 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 13:20:25.961  6717  6717 D BluetoothPermissionRequest: onReceive
08-16 13:20:25.962  7539  7539 D HeadsetService: Received start request. Starting profile...
08-16 13:20:25.964  7539  7539 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 13:20:25.964  7539  7539 D LGBluetoothHfpAdapter: Version 1.6
08-16 13:20:25.967  7539  7785 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:20:25.967  6717  6717 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 13:20:25.970  7539  7539 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 13:20:25.972  7539  7539 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 13:20:25.973  7539  7539 D HeadsetStateMachine: make
08-16 13:20:25.974  7539  7785 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:20:25.978  7539  7785 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:20:25.983  7539  7785 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 13:20:25.988  7539  7785 E BluetoothAdapterService: File transfer profiles supported!!
08-16 13:20:25.998  7539  7785 V LGMDMManager: Create singleton instance
,08-16 13:20:26.005  7539  7785 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 13:20:26.008  7539  7539 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:20:26.008  7539  7539 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 13:20:26.012  7539  7539 D HeadsetStateMachine: max_hf_connections = 1
08-16 13:20:26.012  7539  7539 I bluedroid-qcom: get_profile_interface handsfree
08-16 13:20:26.014  7539  7539 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-16 13:20:26.014   310  1785 V AudioPolicyService: registerClient() client 0xb558a640, uid 1002
08-16 13:20:26.015   310  1785 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 13:20:26.015   310  1785 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 13:20:26.015   310  1785 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 13:20:26.015  7539  7539 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 13:20:26.015   310  1384 V AudioFlinger: registerClient() client 0xb1433130, pid 7539
08-16 13:20:26.016   310  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:20:26.016   310  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:20:26.017  1049  1963 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:20:26.017  1876  4006 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:20:26.017  1049  1963 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:20:26.017  1876  4006 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:20:26.017  1602  2555 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:20:26.017  1602  2555 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:20:26.017  7539  7556 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:20:26.017  3370  3387 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 13:20:26.017  3370  3387 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 13:20:26.017   310  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:20:26.017   310  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:20:26.017  7539  7556 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 13:20:26.017  7539  7539 V ToneGenerator: Create Track: 0xb4928080
08-16 13:20:26.017  7539  7539 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 13:20:26.017  7539  7539 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 13:20:26.017   310  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 13:20:26.018  1049  2018 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:20:26.018   310  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 13:20:26.018  1049  2018 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:20:26.018   310  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 13:20:26.018   310  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 13:20:26.018  1602  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:20:26.018  1602  1619 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:20:26.018  1876  2320 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:20:26.018  1876  2320 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:20:26.019   310   310 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 13:20:26.019  3370  3390 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:20:26.019  3370  3390 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 13:20:26.019  7539  7555 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 13:20:26.019  7539  7555 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 13:20:26.019   310  1785 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 13:20:26.019   310  1785 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 13:20:26.019   310  1785 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 13:20:26.019   310  1785 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 13:20:26.019  7539  7539 V AudioSystem: getLatency() output 2, latency 50
08-16 13:20:26.019  7539  7539 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 13:20:26.019  7539  7539 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 13:20:26.019   310  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 13:20:26.019   310  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 13:20:26.019   310  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 13:20:26.019   310  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 13:20:26.019   310  1385 V AudioFlinger: createTrack() lSessionId: 23
08-16 13:20:26.020  7539  7539 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 13:20:26.020   310  1384 V AudioFlinger: acquiring 23 from 7539, for 7539
08-16 13:20:26.020   310  1384 V AudioFlinger:  added new entry for 23
08-16 13:20:26.020  7539  7539 V ToneGenerator: ToneGenerator INIT OK, time: 220263
08-16 13:20:26.020  7539  7539 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c5d961d
08-16 13:20:26.021  7539  7808 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 13:20:26.021  7539  7808 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 13:20:26.021  7539  7808 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 13:20:26.022  7539  7808 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 13:20:26.022   310   310 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7539
08-16 13:20:26.022  7539  7539 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c5d961d
08-16 13:20:26.022   310   310 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 13:20:26.022   310   310 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 13:20:26.022   310   310 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 13:20:26.022   310   310 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 13:20:26.022   310   310 V voice   : voice_set_parameters: exit with code(0)
08-16 13:20:26.022   310   310 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 13:20:26.022   310   310 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 13:20:26.022   310   310 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 13:20:26.022   310   310 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 13:20:26.023   310   310 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 13:20:26.023   310   310 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 13:20:26.023  7539  7808 V ToneGenerator: ToneGenerator destructor
08-16 13:20:26.023  7539  7808 V ToneGenerator: stopTone
08-16 13:20:26.023  7539  7808 V ToneGenerator: Delete Track: 0xb4928080
08-16 13:20:26.023  7539  7539 D A2dpService: Received start request. Starting profile...
08-16 13:20:26.024  7539  7539 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 13:20:26.024  7539  7808 V AudioTrack: ~AudioTrack, releasing session id from 7539 on behalf of 7539
08-16 13:20:26.024   310  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 13:20:26.024   310  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 13:20:26.024   310  1287 V AudioPolicyService: AudioCommandThread() waking up
08-16 13:20:26.024   310   310 V AudioFlinger: releasing 23 from 7539 for 7539
08-16 13:20:26.024   310  1287, V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 13:20:26.024   310   310 V AudioFlinger:  decremented refcount to 0
08-16 13:20:26.024   310  1287 V AudioPolicyManager: releaseOutput() 2
08-16 13:20:26.024   310   310 V AudioFlinger: purging stale effects
08-16 13:20:26.024   310  1287 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 13:20:26.024   310  1384 V AudioFlinger: PlaybackThread::Track destructor
08-16 13:20:26.024   310  1384 V AudioFlinger: removeClient_l() pid 7539, calling pid 310
08-16 13:20:26.025  7539  7539 V Avrcp   : make
08-16 13:20:26.025  7539  7539 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 13:20:26.025  7539  7539 I bluedroid-qcom: get_profile_interface avrcp
08-16 13:20:26.028  1049  1933 W Process : Unable to open /proc/7810/status
08-16 13:20:26.035  7539  7539 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 13:20:26.036  7539  7539 E AudioManager: No RCC entry present to update
08-16 13:20:26.036  7539  7539 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 13:20:26.039  7539  7539 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 13:20:26.040  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 13:20:26.040  7539  7539 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-16 13:20:26.044  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 13:20:26.179  1049  2045 V SIM_STK : Menu title from STK is T-Mobile
08-16 13:20:26.179  1049  2045 V SIM_STK : Menu title from STK is T-Mobile
,08-16 13:20:26.273  1049  2111 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 13:20:26.281  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 13:20:26.285  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 13:20:26.287  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 13:20:26.287  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 13:20:26.288  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 13:20:26.288  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 13:20:26.288  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 13:20:26.288  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 13:20:26.288  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 13:20:26.289  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 13:20:26.289  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-16 13:20:26.290  7539  7539 I BluetoothA2dpServiceJni: classInitNative
,08-16 13:20:26.290  7539  7539 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 13:20:26.291  7539  7539 D A2dpStateMachine: make
08-16 13:20:26.292  7539  7539 I bluedroid-qcom: get_profile_interface a2dp
,08-16 13:20:26.293  7539  7817 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 13:20:26.296  7539  7539 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 13:20:26.296  7539  7539 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 13:20:26.296  7539  7539 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c5d961d
08-16 13:20:26.298  7539  7539 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 13:20:26.299  7539  7539 D HidService: Received start request. Starting profile...
08-16 13:20:26.299  7539  7539 I bluedroid-qcom: get_profile_interface hidhost
08-16 13:20:26.299  7539  7539 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c5d961d
08-16 13:20:26.299  7539  7816 D A2dpStateMachine: Enter Disconnected: -2
08-16 13:20:26.300  7539  7539 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 13:20:26.301  7539  7539 D HealthService: Received start request. Starting profile...
08-16 13:20:26.304  7539  7539 I bluedroid-qcom: get_profile_interface health
08-16 13:20:26.304  7539  7539 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 13:20:26.304  7539  7539 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c5d961d
,08-16 13:20:26.305  7539  7539 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 13:20:26.307  7539  7539 D PanService: Received start request. Starting profile...
08-16 13:20:26.307  7539  7539 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 13:20:26.307  7539  7539 I bluedroid-qcom: get_profile_interface pan
08-16 13:20:26.314  7539  7539 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 13:20:26.314  7539  7539 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c5d961d
08-16 13:20:26.314  7539  7539 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 13:20:26.318  7539  7539 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 13:20:26.319  7539  7539 D BtGatt.GattService: Received start request. Starting profile...
08-16 13:20:26.319  7539  7539 D BtGatt.GattService: start()
08-16 13:20:26.319  7539  7539 I bluedroid-qcom: get_profile_interface gatt
08-16 13:20:26.319  7539  7539 D BtGatt.AdvertiseManager: advertise manager created
08-16 13:20:26.329  7539  7539 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c5d961d
08-16 13:20:26.330  7539  7539 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c5d961d
08-16 13:20:26.331  7539  7539 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 13:20:26.331  7539  7539 V BluetoothMapService: BluetoothMapBinder()
08-16 13:20:26.332  7539  7539 D BluetoothMapService: Received start request. Starting profile...
08-16 13:20:26.332  7539  7539 D BluetoothMapService: start()
,08-16 13:20:26.334  7539  7539 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 13:20:26.334  7539  7539 D BluetoothMapEmailAppObserver: createReceiver()
08-16 13:20:26.335  7539  7539 D BluetoothMapEmailAppObserver: initObservers()
08-16 13:20:26.335  7539  7539 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 13:20:26.340  7539  7539 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c5d961d
08-16 13:20:26.341  7539  7539 D HeadsetStateMachine: Proxy object connected
08-16 13:20:26.341  7539  7539 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 13:20:26.341  7539  7539 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 13:20:26.343  7539  7808 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 13:20:26.344  7539  7808 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 13:20:26.344  7539  7808 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-16 13:20:26.348  7539  7539 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 13:20:26.351  7539  7539 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 13:20:26.353  7539  7539 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 13:20:26.355  7539  7539 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:26.358  7539  7539 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 13:20:26.359  7539  7539 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 13:20:26.361  7539  7539 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 13:20:26.364  7539  7539 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 13:20:26.364  7539  7539 V BluetoothMapService: Handler(): got msg=1
08-16 13:20:26.365  7539  7539 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:20:26.365  7539  7539 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:20:26.365  7539  7539 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 13:20:26.365  7539  7539 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:26.365  7539  7539 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 13:20:26.365  7539  7785 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 13:20:26.365  7539  7785 I bluedroid-qcom: enable
08-16 13:20:26.366  7539  7785 I bt_hci_bdroid: init
08-16 13:20:26.369  7539  7824 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 13:20:26.369  7539  7824 I bt-btu  : btu_task pending for preload complete event
08-16 13:20:26.370  7539  7785 I bt_vendor: bt-vendor : init
08-16 13:20:26.370  7539  7785 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 13:20:26.370  7539  7785 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 13:20:26.370  7539  7785 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 13:20:26.370  7539  7785 D bt_userial_mct: userial_init
08-16 13:20:26.371  7539  7785 D bt_hci_bdroid: set_power 1
08-16 13:20:26.371  7539  7785 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 13:20:26.371  7539  7785 I bt_vendor: Starting hciattach daemon
08-16 13:20:26.371  7539  7785 I bt_vendor: try to set true
08-16 13:20:26.357  7827  7827 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 13:20:26.367  7827  7827 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 13:20:26.418  7829  7829 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 13:20:26.555  7835  7835 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 13:20:26.590  7836  7836 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 13:20:26.615  7841  7841 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 13:20:26.628  7842  7842 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 13:20:26.639  7843  7843 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 13:20:26.651  7844  7844 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-16 13:20:26.688  7846  7846 I libmdmdetect: ESOC framework not supported
,08-16 13:20:26.689  7846  7846 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 13:20:26.698  7846  7846 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-16 13:20:26.698  7846  7846 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 13:20:26.698  7846  7846 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 13:20:26.698  7846  7846 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 13:20:26.698  7846  7846 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 13:20:26.698  7846  7846 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 13:20:26.698  7846  7846 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 13:20:26.742  7846  7847 E QC-QMI  : qmi_client [7846] 15: failed to locate client data
08-16 13:20:26.743   470   470 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 13:20:26.744   470   470 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-16 13:20:26.794  7848  7848 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 13:20:26.822  7849  7849 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 13:20:26.844  1049  1378 V AlarmManager: RTC_WAKEUP set : Alarm{1c991899 type 0 when 1471346423985 com.google.android.gms} when 1471346423985
,08-16 13:20:26.844  1049  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3204475e type 2 when 221069 android} when 221069
,08-16 13:20:26.860  1841  7851 I CheckinService: active receiver: enabled
08-16 13:20:26.874  7539  7785 I bt_vendor: bluetooth satus is on
08-16 13:20:26.874  7539  7785 D bt_hci_bdroid: preload
08-16 13:20:26.874  7539  7826 D bt_userial_mct: userial_open(port:0)
,08-16 13:20:26.874  7539  7826 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 13:20:26.878  7539  7826 I bt_vendor: Done intiailizing UART
08-16 13:20:26.879  7539  7826 I bt_vendor: Done intiailizing UART
08-16 13:20:26.879  7539  7826 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 13:20:26.879  7539  7826 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 13:20:26.879  7539  7824 I bt-btu  : btu_task received preload complete event
08-16 13:20:26.880  7539  7824 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 13:20:26.880  7539  7824 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 13:20:26.882  7539  7824 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 13:20:26.884  7539  7852 D bt_userial_mct: Entering userial_read_thread()
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 13:20:26.885  7539  7824 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 13:20:26.892  2239  2239 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 13:20:26.944  7539  7824 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 13:20:26.944  7539  7824 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0220061 
08-16 13:20:26.944  7539  7824 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0220061 
,08-16 13:20:26.960  7539  7789 E bt-btif : Calling BTA_HhEnable
08-16 13:20:26.960  7539  7789 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 13:20:26.961  7539  7789 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 13:20:26.961  7539  7824 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 13:20:26.961  7539  7824 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 13:20:26.961  7539  7824 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 13:20:26.961  7539  7824 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 13:20:26.961  7539  7824 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,08-16 13:20:26.972  7539  7824 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-16 13:20:26.972  7539  7824 W bt-smp  : Plain text(LSB ~ MSB) = 4b 96 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 13:20:26.972  7539  7824 W bt-smp  : Encrypted text(LSB ~ MSB) = 81 64 b7 c9 4c bd dd 88 f8 a4 b7 6f 36 ee 56 fb 
08-16 13:20:26.973  7539  7824 W bt-btm  : Stopping oneshot timer
08-16 13:20:26.975  1049  1758 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7853 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-16 13:20:26.981  1049  1049 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 13:20:26.982  7539  7789 D BluetoothAdapterProperties: Name is: G3
08-16 13:20:26.982  1049  1049 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 13:20:26.988  7539  7789 D BluetoothAdapterProperties: Scan Mode:20
08-16 13:20:26.988  7539  7789 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 13:20:26.988  7539  7789 D bt_hci_bdroid: postload
08-16 13:20:26.989  7539  7824 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 13:20:26.989  7539  7826 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 13:20:26.989  7539  7789 D bte_conf: Device ID record 1 : primary
08-16 13:20:26.989  7539  7789 D bte_conf:   vendorId            = 00c4
08-16 13:20:26.989  7539  7789 D bte_conf:   vendorIdSource      = 0001
08-16 13:20:26.990  7539  7789 D bte_conf:   product             = 13a1
08-16 13:20:26.977  7870  7870 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:26.977  7870  7870 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:26.990  7539  7789 D bte_conf:   version             = 1000
08-16 13:20:26.990  7539  7789 D bte_conf:   clientExecutableURL = 
08-16 13:20:26.990  7539  7789 D bte_conf:   serviceDescription  = 
08-16 13:20:26.990  7539  7789 D bte_conf:   documentationURL    = 
08-16 13:20:26.990  7539  7789 D bte_conf: bte_load_did_conf no section named DID2.
08-16 13:20:26.995  7539  7785 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 13:20:26.995  7539  7785 D BluetoothAdapterProperties: ScanMode =  20
08-16 13:20:26.995  7539  7785 D BluetoothAdapterProperties: State =  11
08-16 13:20:26.995  7539  7785 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 13:20:26.996  7539  7785 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 13:20:26.996  7539  7785 D BluetoothAdapterProperties: Setting state to 12
08-16 13:20:26.996  7539  7785 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 13:20:26.996  7539  7789 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 13:20:26.996  7539  7789 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 13:20:27.000  1049  1131 D BluetoothManagerService: Message: 60
08-16 13:20:27.001  1049  1131 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 13:20:27.001  1049  1131 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-16 13:20:27.001  1049  1131 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 13:20:27.001  7539  7785 I BluetoothAdapterState: Entering On State
08-16 13:20:27.009  7539  7785 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 13:20:27.010  7539  7785 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 13:20:27.010  7539  7785 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-16 13:20:27.014  7539  7826 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 13:20:27.014  7539  7826 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 13:20:27.014  7539  7785 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 13:20:27.018  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:20:27.018  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:27.018  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:27.018  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:20:27.018  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:27.018  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:27.018  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:27.018  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:20:27.019  7539  7826 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 13:20:27.020  6717  6733 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:20:27.023  1049  1049 D BluetoothA2dp: Proxy object connected
,08-16 13:20:27.027  6636  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:20:27.029  7539  7852 E bt_mct  : hci lib postload completed
08-16 13:20:27.032  6717  6733 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 13:20:27.033  6717  6717 D BluetoothHeadset: Proxy object connected
08-16 13:20:27.033  6717  6717 D HeadsetProfile: Bluetooth service connected
08-16 13:20:27.051  7539  7785 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-16 13:20:27.056  1876  2320 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:20:27.059  1876  1876 D BluetoothHeadset: Proxy object connected
08-16 13:20:27.060  6717  6732 D BluetoothMap: onBluetoothStateChange: up=true
08-16 13:20:27.061  7876  7876 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 13:20:27.063  6717  7458 D BluetoothPan: onBluetoothStateChange on: true
08-16 13:20:27.063  6717  7458 D BluetoothPan: onBluetoothStateChange call bindService
,08-16 13:20:27.068  1876  4012 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:20:27.071  1876  1876 D BluetoothHeadset: Proxy object connected
08-16 13:20:27.071  6717  6717 D BluetoothA2dp: Proxy object connected
08-16 13:20:27.071  6717  6717 D A2dpProfile: Bluetooth service connected
08-16 13:20:27.071  6717  6733 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 13:20:27.073  1876  2619 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:20:27.080  1876  1876 D BluetoothHeadset: Proxy object connected
08-16 13:20:27.080  1049  1131 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 13:20:27.081  1049  1049 D BluetoothHeadset: Proxy object connected
08-16 13:20:27.081  6717  7458 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 13:20:27.084  6717  6717 D BluetoothMap: Proxy object connected
08-16 13:20:27.084  6717  6717 D MapProfile: Bluetooth service connected
08-16 13:20:27.084  6717  6717 D BluetoothMap: getConnectedDevices()
08-16 13:20:27.088  1049  1131 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 13:20:27.088  1049  1131 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 13:20:27.088  7539  7555 V BluetoothMapService: getConnectedDevices()
08-16 13:20:27.099  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 13:20:27.100  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 13:20:27.104  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:27.105  6717  6717 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 13:20:27.105  6717  6717 D PanProfile: Bluetooth service connected
08-16 13:20:27.108  1966  2177 D LGBluetoothAPIService: Message: 1
08-16 13:20:27.108  1966  2177 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 13:20:27.108  1966  2177 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-16 13:20:27.109  1966  2177 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-16 13:20:27.197  1049  1644 I art     : Explicit concurrent mark sweep GC freed 25490(1285KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.250ms total 110.382ms
,08-16 13:20:27.200  1049  1049 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 13:20:27.201  1049  1131 D BluetoothManagerService: Message: 40
08-16 13:20:27.201  1049  1131 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 13:20:27.201  6717  6717 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 13:20:27.202  6717  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 13:20:27.205  6717  6717 D BluetoothInputDevice: Proxy object connected
08-16 13:20:27.205  6717  6717 D HidProfile: Bluetooth service connected
08-16 13:20:27.210  7539  7539 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:27.210  7539  7539 D BluetoothMapService: STATE_ON
,08-16 13:20:27.220  7539  7539 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c5d961d
08-16 13:20:27.220  7539  7539 V BluetoothPbapService: Pbap Service onCreate
08-16 13:20:27.220  7539  7539 V BluetoothPbapService: Starting PBAP service
,08-16 13:20:27.222  7539  7539 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 13:20:27.223  7539  7539 V BluetoothPbapService: Pbap Service onBind
08-16 13:20:27.224  7539  7789 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 13:20:27.224  7539  7789 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 13:20:27.224  7539  7539 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:27.225  7539  7539 V BluetoothPbapService: state: 12
08-16 13:20:27.225  6717  6717 D DockEventReceiver: finishStartingService: stopping service
08-16 13:20:27.225  7539  7539 V BluetoothMapService: Handler(): got msg=1
08-16 13:20:27.225  7539  7539 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 13:20:27.226  6717  6717 D BluetoothPbap: Proxy object connected
08-16 13:20:27.226  6717  6717 D PbapServerProfile: Bluetooth service connected
,08-16 13:20:27.227  7539  7539 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 13:20:27.227  7539  7539 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:27.227  7539  7539 V BluetoothPbapReceiver: ***********state = 12
08-16 13:20:27.228  7539  7539 V BluetoothPbapService: Handler(): got msg=1
08-16 13:20:27.228  7539  7889 D BluetoothMapMasInstance: MAS initSocket()
08-16 13:20:27.229  7539  7539 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 13:20:27.229  7539  7889 D BluetoothMapMasInstance:   masId = 00
08-16 13:20:27.229  7539  7889 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 13:20:27.229  7539  7889 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 13:20:27.229  7539  7889 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 13:20:27.231  1049  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:27.232  2239  2239 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 13:20:27.233  2239  2239 D c       : Getting all permits...
08-16 13:20:27.233  2239  2239 D a       : Opening database...
08-16 13:20:27.233  7539  7889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:20:27.234  7539  7890 V BluetoothPbapService: Pbap Service initSocket
08-16 13:20:27.234  7539  7889 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 13:20:27.234  7539  7889 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 13:20:27.234  7539  7889 D BluetoothMapMasInstance: Accepting socket connection...
08-16 13:20:27.235  2239  2239 D a       : Opening database auth.proximity.permit_store...
08-16 13:20:27.235  1049  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:27.235  7539  7789 D BluetoothAdapterProperties: Scan Mode:21
08-16 13:20:27.235  7539  7789 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 13:20:27.235  2239  2239 D a       : Closing database...
08-16 13:20:27.237  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:20:27.238  7539  7890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:20:27.239  7539  7890 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 13:20:27.240  7539  7890 V BluetoothPbapService: Succeed to create listening socket 
08-16 13:20:27.240  7539  7890 V BluetoothPbapService: Accepting socket connection...
08-16 13:20:27.244  6717  6717 D BluetoothPermissionRequest: onReceive
08-16 13:20:27.246  6717  6717 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 13:20:27.247  6717  6717 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 13:20:27.250  7539  7539 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-16 13:20:27.251  7539  7539 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-16 13:20:27.256  7539  7539 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-16 13:20:27.265  7853  7853 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:20:27.265  7853  7853 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 13:20:27.267  7853  7853 D PhoneMonitor: Register our PhoneStateListener
,08-16 13:20:27.275  7539  7539 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 13:20:27.276  7539  7539 V BtOppService: onCreate
08-16 13:20:27.277  1049  1936 I ActivityManager: Killing 7019:com.android.chrome/u0a57 (adj 15): empty #17
,08-16 13:20:27.288  7539  7539 V BluetoothOppNotification: send message
,08-16 13:20:27.294  7539  7895 V BtOppService: Deleted complete outbound shares, number =  0
,08-16 13:20:27.295  7539  7895 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 13:20:27.295  7539  7895 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 13:20:27.296  7539  7895 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@879ddf0 on behalf of 
08-16 13:20:27.297  7853  7853 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-16 13:20:27.298  7853  7853 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 13:20:27.298  7853  7853 D TelephonyAutoProfiling: [parse] Load xml
08-16 13:20:27.301  7853  7853 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 13:20:27.301  7853  7853 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 13:20:27.301  7853  7853 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 13:20:27.301  7853  7853 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 13:20:27.301  7853  7853 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
,08-16 13:20:27.301  7853  7853 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 13:20:27.301  7853  7853 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 13:20:27.301  7853  7853 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 13:20:27.301  7853  7853 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 13:20:27.301  7853  7853 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 13:20:27.301  7853  7853 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 13:20:27.301  7853  7853 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 13:20:27.301  7853  7853 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 13:20:27.301  7853  7853 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 13:20:27.301  7853  7853 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 13:20:27.301  7853  7853 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 13:20:27.301  7853  7853 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 13:20:27.306  7853  7853 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-16 13:20:27.319  1049  1588 W libprocessgroup: failed to open /acct/uid_10057/pid_7019/cgroup.procs: No such file or directory
,08-16 13:20:27.321  7539  7539 V BtOppService: Starting RfcommListener
08-16 13:20:27.324  7539  7539 D BluetoothOppPreference: Dumping Names:  
08-16 13:20:27.324  7539  7539 D BluetoothOppPreference: {}
08-16 13:20:27.324  7539  7539 D BluetoothOppPreference: Dumping Channels:  
08-16 13:20:27.324  7539  7539 D BluetoothOppPreference: {}
08-16 13:20:27.325  7539  7539 V BtOppService: onStartCommand
08-16 13:20:27.326  7539  7899 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 13:20:27.326  7539  7899 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 13:20:27.327  7539  7539 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:27.328  7539  7539 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 13:20:27.328  7539  7899 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f3a7dee on behalf of 
08-16 13:20:27.328  7539  7899 V BluetoothOppNotification: update too frequent, put in queue
08-16 13:20:27.329  7539  7899 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 13:20:27.330  7539  7539 V BluetoothOppNotification: new notify threadi!
08-16 13:20:27.330  7539  7539 V BluetoothOppNotification: send delay message
08-16 13:20:27.331  7539  7539 V BtOppService: ContentObserver received notification
,08-16 13:20:27.332  7539  7539 V BtOppService: ContentObserver received notification
,08-16 13:20:27.333  7539  7539 V BtOppService: start RfcommListener
08-16 13:20:27.333  7539  7901 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 13:20:27.333  7539  7901 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 13:20:27.334  7539  7900 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 13:20:27.334  7539  7901 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25a528f on behalf of 
08-16 13:20:27.335  7539  7900 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f36e91c on behalf of 
08-16 13:20:27.335  7539  7901 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 13:20:27.336  7539  7900 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 13:20:27.336  7539  7900 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 13:20:27.337  7539  7539 V BtOppService: RfcommListener started
08-16 13:20:27.338  7539  7900 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d0ff925 on behalf of 
08-16 13:20:27.338  7539  7902 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 13:20:27.338  1049  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:27.339  7539  7902 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:20:27.340  7539  7902 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-16 13:20:27.340  7539  7900 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 13:20:27.340  7539  7902 V BtOppRfcommListener: Started RFCOMM listener....
08-16 13:20:27.340  7539  7902 I BtOppRfcommListener: Accept thread started.
08-16 13:20:27.340  7539  7902 V BtOppRfcommListener: Accepting connection...
08-16 13:20:27.341  7539  7900 V BluetoothOppNotification: outbound notification was removed.
08-16 13:20:27.341  7539  7900 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 13:20:27.342  7539  7900 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35548afa on behalf of 
08-16 13:20:27.343  7539  7900 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 13:20:27.345  7539  7900 V BluetoothOppNotification: inbound notification was removed.
,08-16 13:20:27.345  7539  7900 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-16 13:20:27.346  7539  7900 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2eb388ab on behalf of 
08-16 13:20:27.356  7539  7539 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c5d961d
,08-16 13:20:27.356  7539  7539 V BluetoothFtpService: Ftp Service onCreate
08-16 13:20:27.356  7539  7539 I BluetoothFtpService: Ftp Service onCreate
08-16 13:20:27.356  7539  7539 V BluetoothFtpService: Ftp Service onStartCommand
08-16 13:20:27.357  7539  7539 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:27.357  7539  7539 V BluetoothFtpService: Starting Listening on sockets
08-16 13:20:27.357  7539  7539 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 13:20:27.357  7539  7539 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 13:20:27.357  7539  7539 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 13:20:27.358  7539  7539 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:27.358  7539  7539 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 13:20:27.358  7539  7539 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-16 13:20:27.360  7539  7539 V BluetoothFtpService: Handler(): got msg=1
,08-16 13:20:27.360  7539  7539 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 13:20:27.360  7539  7539 V BluetoothFtpService: Ftp Service initSocket
08-16 13:20:27.365  1049  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:27.366  7539  7539 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:20:27.367  7539  7539 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-16 13:20:27.367  7539  7539 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 13:20:27.369  7539  7904 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-16 13:20:27.388  7539  7539 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c5d961d
,08-16 13:20:27.388  7539  7539 V BluetoothSapService: Sap Service onCreate
,08-16 13:20:27.390  7539  7539 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:20:27.390  7539  7539 V BluetoothSapService: state: 12
,08-16 13:20:27.391  7539  7539 V BluetoothSapService: Starting SAP server process
08-16 13:20:27.392  7539  7539 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 13:20:27.377  7905  7905 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:27.377  7905  7905 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:27.394  7539  7906 V BluetoothSapService: Sap Service initRfcommSocket
08-16 13:20:27.394  1049  1064 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:27.395  7539  7906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:20:27.396  7539  7906 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 13:20:27.397  7539  7906 V BluetoothSapService: Succeed to create listening socket 
08-16 13:20:27.397  7539  7906 V BluetoothSapService: Accepting socket connection...
08-16 13:20:27.405  7905  7905 V BT_SAP  : Event pipe created
08-16 13:20:27.405  7905  7905 V BT_SAP  : create_server_socket qcom.sap.server
08-16 13:20:27.405  7905  7905 V BT_SAP  : created socket fd 6
,08-16 13:20:27.838  6636  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:20:27.838  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:27.838  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:27.838  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:20:27.838  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:27.838  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:27.838  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:27.838  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:20:27.848  6636  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:20:27.850  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:20:27.850  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27c147bc added. We now have 8 listener(s)
08-16 13:20:27.850  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:20:27.854  1049  2069 D WifiServiceImplEx: setWifiEnabled: false pid=6636, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 13:20:27.854  1049  2069 D WifiService: setWifiEnabled: false pid=6636, uid=10118
08-16 13:20:27.854  1049  2069 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:20:27.867  6636  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:20:27.871  1049  1963 D WifiServiceImplEx: setWifiEnabled: true pid=6636, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 13:20:27.871  1049  1963 D WifiService: setWifiEnabled: true pid=6636, uid=10118
,08-16 13:20:27.871  1049  1963 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 13:20:27.886  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 13:20:27.887  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 13:20:27.887  1049  1049 D Ulp_jni : JNI:system_update. Event-4
,08-16 13:20:27.892  1049  1536 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 13:20:27.892  1049  1536 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 13:20:27.894  1049  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1049] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 13:20:27.894  1049  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 13:20:27.894  1049  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1049] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 13:20:27.894  1049  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 13:20:27.895  1049  1536 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 13:20:27.895  1049  1536 E WifiHW  : unknown target_country: EU , set to default
08-16 13:20:27.895  1049  1536 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 13:20:27.895  1049  1536 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 13:20:27.895  1049  1536 I WifiUtil: gEnableBmps=1
08-16 13:20:28.332  7539  7539 V BluetoothOppNotification: new notify threadi!
,08-16 13:20:28.336  7539  7539 V BluetoothOppNotification: send delay message
08-16 13:20:28.338  7539  7925 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 13:20:28.339  7539  7925 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@196d3fb4 on behalf of 
08-16 13:20:28.339  7539  7925 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 13:20:28.341  7539  7925 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 13:20:28.342  7539  7925 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@162527dd on behalf of 
08-16 13:20:28.342  7539  7925 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 13:20:28.345  7539  7925 V BluetoothOppNotification: outbound notification was removed.
08-16 13:20:28.346  7539  7925 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-16 13:20:28.349  7539  7925 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31e57f52 on behalf of 
08-16 13:20:28.349  7539  7925 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 13:20:28.351  7539  7925 V BluetoothOppNotification: inbound notification was removed.
08-16 13:20:28.351  7539  7925 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 13:20:28.352  7539  7925 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36ee6223 on behalf of 
08-16 13:20:28.518   306   907 D SoftapController: Softap fwReload - Ok
,08-16 13:20:28.524  1049  1536 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (624ms)
08-16 13:20:28.529   306   907 D CommandListener: Setting iface cfg
08-16 13:20:28.529   306   907 D CommandListener: Trying to bring down wlan0
08-16 13:20:28.534  1049  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 13:20:28.547   306   907 D CommandListener: Clearing all IP addresses on wlan0
,08-16 13:20:28.560  1049  1536 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-16 13:20:28.570  1049  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:20:28.570  1049  1536 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:20:28.570  1049  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 13:20:28.557  7927  7927 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 13:20:28.567  7927  7927 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:28.584  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 13:20:28.589  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:20:28.604  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-16 13:20:28.608  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:28.610  1049  1536 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 13:20:28.610  1049  1536 D WifiMonitor: connecting to supplicant
08-16 13:20:28.654  7927  7927 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 13:20:28.671  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 13:20:28.672  6717  6717 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 13:20:28.672  6717  6717 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 13:20:28.672  6717  6717 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 13:20:28.674  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 13:20:28.676  6717  6717 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 13:20:28.676  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 13:20:28.676  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 13:20:28.676  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 13:20:28.676  6717  6717 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 13:20:28.676  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 13:20:28.677  6717  6717 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 13:20:28.691  7641  7652 E UEI.SmartControl: file observer is disposed!
,08-16 13:20:28.701  7927  7927 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 13:20:28.701  7927  7927 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-16 13:20:28.703  1049  1131 D Tethering: InitialState.processMessage what=4
,08-16 13:20:28.725  1049  1758 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7945 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-16 13:20:28.728  1049  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 13:20:28.744   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 544us total 19.080ms
,08-16 13:20:28.760   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 281us total 15.860ms
,08-16 13:20:28.773   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 284us total 13.151ms
,08-16 13:20:28.775  7927  7927 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 13:20:28.819  1049  1644 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7966 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 13:20:28.830  7945  7964 W FormManager: Network not available. Please check & try again.
08-16 13:20:28.830  7927  7927 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 13:20:28.836  7945  7965 V FormManager: Network unavailable.
08-16 13:20:28.837  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-16 13:20:28.838  1049  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 13:20:28.838  1049  1536 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 13:20:28.839  1049  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 13:20:28.839  1049  1536 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 13:20:28.840  7945  7965 V FormManager: Network unavailable.
08-16 13:20:28.840  1049  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:28.840  1049  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:28.840  1049  7983 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 13:20:28.840  1049  7983 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 13:20:28.841  1049  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:28.841  1049  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-16 13:20:28.842  1049  1536 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 13:20:28.842  1049  1536 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 13:20:28.842  1049  1536 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 13:20:28.842  1049  1536 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 13:20:28.842  1049  1536 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 13:20:28.843  1049  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 13:20:28.843  1049  1536 E WifiStateMachine: useWiFiOffloading() : false
08-16 13:20:28.843  1049  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 13:20:28.844  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:28.844  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:28.844  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:28.845  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:28.845  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 13:20:28.845  1966  1966 D WfdService: Waiting for WifiP2p enabling
08-16 13:20:28.846  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:28.848  7927  7927 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 13:20:28.848  1049  7983 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 13:20:28.848  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 13:20:28.849  1049  7983 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 13:20:28.849  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 13:20:28.849  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 13:20:28.849  1049  7983 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 13:20:28.849  1049  7983 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 13:20:28.849  1049  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 13:20:28.849  1049  1536 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 13:20:28.850  1049  1536 D WifiNative-wlan0: SET update_config 1: returned true
08-16 13:20:28.850  1049  1536 D WifiConfigStore: Loading config and enabling all networks 
08-16 13:20:28.850  1049  1536 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 13:20:28.850  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:20:28.850  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:28.850  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:28.850  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:28.850  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:28.850  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:28.850  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:28.850  6636  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:20:28.851  1049  1536 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 13:20:28.852  6636  6636 D io.jxcore.node.JXcor,eExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:20:28.858  1049  1536 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 13:20:28.868  1049  1758 I ActivityManager: Killing 7040:com.lge.drmservice/u0a62 (adj 15): empty #17
08-16 13:20:28.871  1049  1536 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 13:20:28.872  1049  1536 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 13:20:28.901  6636  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:20:28.901  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:28.901  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:28.901  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:28.901  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:28.901  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:20:28.901  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:20:28.901  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:20:28.903  6636  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:20:28.907  7966  7966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:20:28.908  6636  6692 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-16 13:20:28.908  6636  6692 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 13:20:28.910  6636  6692 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a43d178 Bundle[{}]
08-16 13:20:28.910  6636  6692 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 13:20:28.910  6636  6692 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 13:20:28.911  6636  6692 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 13:20:28.911  6636  6692 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 13:20:28.912  6636  6692 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 13:20:28.913  6636  6692 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 13:20:28.917  6636  6692 I System.out: Running OutgoingSocketThread
,08-16 13:20:28.918  6636  7988 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 861)
,08-16 13:20:28.919  6636  7988 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57792
08-16 13:20:28.919  6636  7988 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-16 13:20:28.941  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 13:20:28.942  1049  1536 D WifiStateMachine: enableVerboseLogging : level 2
08-16 13:20:28.942  1049  1536 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 13:20:28.942  1049  1936 W libprocessgroup: failed to open /acct/uid_10062/pid_7040/cgroup.procs: No such file or directory
08-16 13:20:28.942  1049  1536 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 13:20:28.942  1049  1536 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 13:20:28.943  1049  1536 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 13:20:28.943  1049  1536 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 13:20:28.944  1049  1536 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 13:20:28.944  1049  1536 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 13:20:28.944  1049  1536 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 13:20:28.944  1049  1536 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 13:20:28.944  1049  1536 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 13:20:28.945  1049  1536 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 13:20:28.945  1049  1536 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 13:20:28.945  1049  1536 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 13:20:28.945  1049  1536 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 13:20:28.946  1049  1536 D WifiStateMachine: Setting OUI to DA-A1-19
,08-16 13:20:28.946  1049  1536 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 13:20:28.946  1049  1536 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 13:20:28.946  1049  1536 D WifiNative-HAL: Setting external_sim to 1
08-16 13:20:28.946  1966  1966 D WfdsService: Supplicant Connection state is changed : true
08-16 13:20:28.946  1049  1536 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 13:20:28.947  1966  2321 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 13:20:28.947  1966  2321 D WfdsService: Set the WFDS Monitor: true
08-16 13:20:28.947  1966  2321 D WfdsMonitor: WfdsMonitorThread create
08-16 13:20:28.947  1049  1536 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 13:20:28.947  1966  2321 D WfdsMonitor: WFDS Monitor is created and started
08-16 13:20:28.947  1049  1536 I WifiNative-HAL: startHal
08-16 13:20:28.948  1049  1536 D wifi    : setting scan oui 0x957c7120
08-16 13:20:28.947  1966  2321 D WfdsService: WiFi: Supplicant connection re-established
08-16 13:20:28.948  1966  7989 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 13:20:28.948  1049  1536 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 13:20:28.948  1049  1536 I WifiNative-HAL: startHal
08-16 13:20:28.948  1049  1536 D wifi    : setting scan oui 0x957c7120
08-16 13:20:28.948  1966  7989 E CtrlSupplicant: Succeed to open control connection
08-16 13:20:28.948  1049  1536 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 13:20:28.948  7567  7567 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:28.949  1966  7989 E CtrlSupplicant: Succeed to open monitor connection
08-16 13:20:28.949  1966  7989 D WfdsMonitor: Supplicant connection established
08-16 13:20:28.949  1049  1536 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 13:20:28.949  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 13:20:28.949  1966  2321 D WfdsService: Connected to the supplicant for wfds
08-16 13:20:28.949  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 13:20:28.950  1049  1536 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 13:20:28.950  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 13:20:28.950  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 13:20:28.951  1049  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 13:20:28.951  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 13:20:28.951  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 13:20:28.951  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:28.951  1049  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 13:20:28.951  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 13:20:28.952  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 13:20:28.952  1049  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 13:20:28.952  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 13:20:28.952  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 13:20:28.953  1049  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 13:20:28.953  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 13:20:28.953  1049  1984 I ActivityManager: Killing 7064:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-16 13:20:28.953  7927  7927 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 13:20:28.954  1049  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 13:20:28.954  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 13:20:28.954  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 13:20:28.954  1049  1536 D WifiNa,tive-wlan0: DRIVER RXFILTER-START: returned true
08-16 13:20:28.955  1049  1536 E WifiNative: : [223,182,826 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 13:20:28.955  1049  1536 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 13:20:28.956  1049  1536 D WifiNative-wlan0: RECONNECT: returned true
08-16 13:20:28.956  1049  1536 D WifiNative-wlan0: doString: [STATUS]
08-16 13:20:28.956  1049  7983 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 13:20:28.956  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 13:20:28.956  1049  1536 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 13:20:28.956  1049  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 13:20:28.958  1049  1536 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:20:28.958  1049  1535 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:28.961   306   907 D CommandListener: Setting iface cfg
08-16 13:20:28.961   306   907 D CommandListener: Trying to bring up p2p0
08-16 13:20:28.961  1049  1535 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 13:20:28.961  1049  1535 D LGWifiP2pService: P2pEnablingState
08-16 13:20:28.961  1049  1535 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:28.961  1049  1535 D LGWifiP2pService: P2p socket connection successful
08-16 13:20:28.961  1049  1535 D LGWifiP2pService: P2pEnabledState
,08-16 13:20:29.000  1049  1535 D LGWifiP2pService: sending p2p connection changed broadcast
,08-16 13:20:29.000  1049  1535 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 13:20:29.002  1049  1536 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 13:20:29.002  1049  1536 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 13:20:29.003  1049  1536 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 13:20:29.003  1049  1536 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 13:20:29.004  1049  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=223232  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 13:20:29.005  1049  1535 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 13:20:29.006  1049  1535 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 13:20:29.006  1049  1535 D WifiNative-p2p0: SET device_name G3: returned true
08-16 13:20:29.006  1049  1535 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 13:20:29.006  1049  1535 D LGWifiP2pService: before postfix = G3
08-16 13:20:29.006  1049  1535 D WifiServerServiceExt: postfix byte check : 2
08-16 13:20:29.006  1049  1535 D LGWifiP2pService: after postfix = G3
08-16 13:20:29.006  1049  1535 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 13:20:29.007  1049  1535 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 13:20:29.007  1049  1535 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 13:20:29.007  1049  1535 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 13:20:29.007  1049  1535 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 13:20:29.008  1049  1535 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 13:20:29.008  1049  1535 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 13:20:29.010  1049  1535 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 13:20:29.010  1049  1535 D WifiNative-HAL: p2pGetDeviceAddress
08-16 13:20:29.011  1049  1535 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 13:20:29.011  1049  1049 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 13:20:29.011  1049  1554 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.011  1049  1049 D RttService: SCAN_AVAILABLE : 3
08-16 13:20:29.011  1049  1554 I WifiNative-HAL: startHal
08-16 13:20:29.011  1049  1554 D wifi    : getting scan capabilities on interface[1] = 0x957c7120
,08-16 13:20:29.011  1049  1554 D wifi    : failed to get capabilities : -3
,08-16 13:20:29.011  1049  1554 E WifiScanningService: could not get scan capabilities
08-16 13:20:29.011  1049  1555 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.012  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 13:20:29.012  1966  1966 D WfdsService: WifiP2pState is changed : true
,08-16 13:20:29.012  1966  2321 D WfdsService: Receive the WFDS_ENABLE Method
08-16 13:20:29.012  1966  2321 D WfdsService: Set the WFDS Monitor: true
08-16 13:20:29.012  1966  2321 D WfdsService: Connected to the supplicant for wfds
08-16 13:20:29.012  1966  2321 D WfdsJNI : doCommand: WFDS_SET TRUE
,08-16 13:20:29.012  1966  1966 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 13:20:29.013  7927  7927 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 13:20:29.013  1966  2321 D WfdsService: selectPreferredScanChannel [36]
08-16 13:20:29.013  1966  2321 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,08-16 13:20:29.013  1049  1933 W libprocessgroup: failed to open /acct/uid_10085/pid_7064/cgroup.procs: No such file or directory
08-16 13:20:29.014  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=223242  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 13:20:29.015  1966  1966 D WfdsService: isConnected: false
08-16 13:20:29.016  1049  1536 E WifiStateMachine:  DisconnectedState what:132106 1 0
,08-16 13:20:29.019  1049  1536 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 13:20:29.020  1049  1536 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 13:20:29.020  1049  1536 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 13:20:29.021  7927  7927 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-16 13:20:29.023  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:29.023  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:29.024  1049  1536 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 13:20:29.024  1049  1536 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 13:20:29.025  1049  1536 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 13:20:29.025  1049  1536 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 13:20:29.026  7927  7927 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 13:20:29.027  1049  1536 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 13:20:29.028  1049  1536 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
,08-16 13:20:29.028  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:29.029  1049  1536 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 13:20:29.029  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 13:20:29.029  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 13:20:29.030  7927  7927 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:29.030  1049  7983 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 13:20:29.030  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:29.030  1049  7983 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:29.030  1049  7983 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:29.031  7927  7927 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 13:20:29.031  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:29.031  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:29.032  1966  7989 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:29.032  1049  7983 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:29.032  1049  7983 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:29.032  1966  7989 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:29.032  1049  7983 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:29.032  1049  7983 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:29.033  1049  7983 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:29.033  1049  7983 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:29.033  1049  7983 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:29.033  1049  7983 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:29.034  1049  1536 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 13:20:29.035  1049  1536 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 13:20:29.035  1049  1536 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 13:20:29.036  1049  1536 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 13:20:29.036  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 13:20:29.036  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 13:20:29.036  7927  7927 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 13:20:29.036  1049  7983 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 13:20:29.036  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 13:20:29.036  1049  7983 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 13:20:29.036  1049  7983 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-16 13:20:29.038  1049  1536 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 13:20:29.038  1049  1536 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 13:20:29.038  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.038  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.038  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 13:20:29.039  1049  1536 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 13:20:29.039  1049  1536 D WifiNative-wlan0: doBoolean: SCAN
08-16 13:20:29.039  1049  1536 D WifiNative-wlan0: SCAN: returned false
08-16 13:20:29.040  1049  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=223268  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 13:20:29.041  1049  1535 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 13:20:29.041  1049  1535 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 13:20:29.042  1049  1535 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 13:20:29.042  1049  1535 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 13:20:29.042  1966  1966 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 13:20:29.042  1966  1966 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 13:20:29.042  1966  1966 D WfdsService: Update P2p Interface State: 3
08-16 13:20:29.043  1049  1535 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 13:20:29.043  1049  1535 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 13:20:29.043  1049  1535 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 13:20:29.043  1049  1535 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 13:20:29.044  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=223272  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 13:20:29.044  1049  1536 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:20:29.045  1049  1536 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:20:29.045  1049  1536 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:20:29.046  1049  1536 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:20:29.046  1049  1536 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 13:20:29.052  1049  1535 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 13:20:29.052  1049  1535 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 13:20:29.052  1049  1535 D LGWifiP2pService: InactiveState
08-16 13:20:29.053  1049  1535 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.053  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.053  1049  1535 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 13:20:29.053  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 13:20:29.053  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.053  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 13:20:29.053  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:29.053  1049  1049 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 13:20:29.053  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 13:20:29.054  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:29.054  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:29.054  1049  1049 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 13:20:29.054  7927  7927 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 13:20:29.055  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:29.055  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:29.055  1049  7983 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 13:20:29.056  1049  7983 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:29.056  1049  7983 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:29.056  1049  7983 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 13:20:29.056  1049  7983 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:29.056  1049  7983 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:29.056  1049  7983 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:29.056  1049  7983 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:29.056  1049  7983 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:29.056  1049  7983 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:29.056  1049  1535 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 13:20:29.056  1049  7983 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-16 13:20:29.056  1049  7983 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 13:20:29.056  1049  1535 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.056  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.056  1966  7989 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 13:20:29.056  1049  1535 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.056  1966  7989 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:29.056  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.056  1966  7989 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 13:20:29.056  1049  1535 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.057  1049  1535 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.057  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.057  1049  1535 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.057  1049  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.057  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.057  1049  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.057  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 13:20:29.057  6717  6717 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 13:20:29.058  6717  6717 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 13:20:29.058  6717  6717 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 13:20:29.058  1966  2321 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 13:20:29.058  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:29.058  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:29.058  1049  1535 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.058  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 13:20:29.058  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.058  1049  1535 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.059  1049  1049 E WifiServerServiceExt: No p2p device connected
08-16 13:20:29.059  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:29.059  6717  6717 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 13:20:29.059  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 13:20:29.059  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 13:20:29.059  671,7  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 13:20:29.059  6717  6717 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 13:20:29.059  6717  6717 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 13:20:29.075  7966  7966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:20:29.078  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 13:20:29.083  7945  7991 W FormManager: Network not available. Please check & try again.
08-16 13:20:29.085  7945  7992 V FormManager: Network unavailable.
08-16 13:20:29.086  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:29.091  7945  7992 V FormManager: Network unavailable.
08-16 13:20:29.104  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 13:20:29.104  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 13:20:29.106  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:20:29.108  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 13:20:29.115  4326  7993 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 13:20:29.116  4326  7994 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 13:20:29.116  4326  7994 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 13:20:29.168  1049  2045 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7995 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 13:20:29.287  7995  7995 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 13:20:29.287  7995  7995 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 13:20:29.295  7995  7995 V [BNRBootReceiver]: Boot Receiver Return
08-16 13:20:29.297  7995  7995 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-16 13:20:29.358  1049  2069 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8013 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 13:20:29.359  1049  2069 I ActivityManager: Killing 7098:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-16 13:20:29.496  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-16 13:20:29.497  7927  7927 E wpa_supplicant: USIM:  scard_init function
08-16 13:20:29.497  1049  7983 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 13:20:29.498  7927  7927 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-16 13:20:29.504  1049  7983 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 13:20:29.504  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
08-16 13:20:29.504  1049  7983 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 13:20:29.505  1049  7983 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 13:20:29.505  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 13:20:29.506  1049  1536 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 13:20:29.509  1049  1536 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 13:20:29.509  1049  1536 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 13:20:29.510  1049  1536 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 13:20:29.510  1049  1536 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 13:20:29.519  1049  1933 W libprocessgroup: failed to open /acct/uid_10093/pid_7098/cgroup.procs: No such file or directory
,08-16 13:20:29.533  1049  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=223761  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 13:20:29.538  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:29.538  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:29.541  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:29.541  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.541  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.541  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 13:20:29.542  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=223770  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 13:20:29.543  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:29.543  1049  1049 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 13:20:29.557  8013  8013 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 13:20:29.584  8013  8013 D PluginManager: init()
,08-16 13:20:29.619  7927  7927 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 13:20:29.622  1049  7983 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 13:20:29.622  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 13:20:29.622  1049  7983 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 13:20:29.622  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 13:20:29.622  1049  7983 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:20:29.622  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-16 13:20:29.623  1049  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=223851  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 13:20:29.624  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=223852  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 13:20:29.625  1049  1536 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223853
08-16 13:20:29.625  1049  1536 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223853
08-16 13:20:29.625  1049  1536 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223854
08-16 13:20:29.626  1049  1536 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223854
08-16 13:20:29.626  1049  1536 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223854
08-16 13:20:29.627  1049  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=223855  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 13:20:29.629  7927  7927 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 13:20:29.629  7927  7927 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 13:20:29.629  1049  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 13:20:29.630  1049  7983 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:20:29.630  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:20:29.630  1049  7983 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 13:20:29.630  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 13:20:29.630  1049  7983 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 13:20:29.630  1049  7983 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 13:20:29.630  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 13:20:29.631  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=223859  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 13:20:29.632  1049  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=223860  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 13:20:29.632  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:29.632  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:29.632  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=223860  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 13:20:29.633  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 13:20:29.636  1049  7983 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 13:20:29.636  1049  7983 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:20:29.636  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:20:29.640  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.640  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.640  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 13:20:29.641  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.642  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.642  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 13:20:29.642  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:29.642  1049  1049 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 13:20:29.644  1049  1536 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=223872
08-16 13:20:29.644  1049  1536 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=223872
08-16 13:20:29.645  1049  1536 D WifiNative-wlan0: doString: [STATUS]
08-16 13:20:29.645  1049  7983 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 13:20:29.645  1049  7983 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 13:20:29.646  1049  1536 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 13:20:29.647  1049  1536 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 13:20:29.648  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:29.648  1049  1049 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-16 13:20:29.654  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:29.654  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:29.657  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:29.657  1049  1536 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 13:20:29.657  1049  1536 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 13:20:29.664  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.664  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.664  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 13:20:29.664  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.664  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.665  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-16 13:20:29.670  1049  1536 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 13:20:29.670  1049  1543 D ConnectivityService: Got NetworkAgent Messenger
08-16 13:20:29.670  1049  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 13:20:29.670  1049  1543 D ConnectivityService: NetworkAgent connected
08-16 13:20:29.670  1049  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 13:20:29.670  1049  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 13:20:29.671  1049  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 13:20:29.671  1049  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 13:20:29.675  1049  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 13:20:29.675  1049  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 13:20:29.675  1049  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-16 13:20:29.676  1049  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 13:20:29.676  1049  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 13:20:29.678  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:29.679  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:29.680  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:29.680  1049  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 13:20:29.682  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:29.682  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:29.682   306   907 D CommandListener: Setting iface cfg
08-16 13:20:29.683  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:29.684  1049  1536 E WifiStateMachine: Start Dhcp Watchdog 3
08-16 13:20:29.684  1049  8034 D DhcpStateMachine: StoppedState
08-16 13:20:29.684  1049  8034 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 13:20:29.685  1049  8034 D DhcpStateMachine: WaitBeforeStartState
08-16 13:20:29.685  1049  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=223913  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:20:29.685  1049  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=223913  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:20:29.686  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=223914  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:20:29.687  1049  1536 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:29.687  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:29.687  1049  1536 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:29.688  1049  1536 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:29.688  1049  1536 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:29.689  1049  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 13:20:29.689  1049  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=223917  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:20:29.690  1049  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=223918  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:20:29.690  1049  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=223918  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 13:20:29.691  1049  1536 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14306] from screen [on:0 period:-1827352837] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:20:29.692  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1827352836] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 13:20:29.692  1049  1536 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 13:20:29.696  1049  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-16 13:20:29.697  1049  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:29.697  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:29.698  1049  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:29.698  1049  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:29.698  1049  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:29.699  1049  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:29.699  1049  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 13:20:29.700  1049  1536 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=183,0,0
08-16 13:20:29.700  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=183,0,0
08-16 13:20:29.700  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 13:20:29.700  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:29.700  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 13:20:29.701  1049  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 13:20:29.701  1049  1536 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 13:20:29.702  1049  1536 D WifiNative-wlan0: SET ps 0: returned true
08-16 13:20:29.702  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 13:20:29.702  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 13:20:29.702  1049  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 13:20:29.703  1049  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d999701 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.703  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d999701 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.703  1049  8034 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.703  1049  8034 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 13:20:29.704  1049  1536 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 13:20:29.705  1049  1536 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 13:20:29.705  1049  1536 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 13:20:29.705   306   907 D CommandListener: Setting iface cfg
08-16 13:20:29.706   306   907 D CommandListener: Trying to bring up wlan0
,08-16 13:20:29.708  1049  1536 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 13:20:29.709  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:29.709  1049  1049 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 13:20:29.711  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 13:20:29.711  1049  1049 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 13:20:29.712  1049  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:29.712  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:29.713  1049  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:29.713  1049  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:29.714  1049  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:29.714  1049  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 13:20:29.714  1049  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 13:20:29.715  1049  1536 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 13:20:29.715  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 13:20:29.715  1049  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.716  1049  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.716  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 13:20:29.716  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 13:20:29.716  1049  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 13:20:29.716  1049  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 13:20:29.717  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 13:20:29.717  1049  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 13:20:29.718  1049  1536 D WifiNative-wlan0: doBoolean: SET ps 1
,08-16 13:20:29.735  1049  1536 D WifiNative-wlan0: SET ps 1: returned true
08-16 13:20:29.736  1049  1536 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 13:20:29.736  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-16 13:20:29.736  1049  1536 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 13:20:29.742  1049  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 13:20:29.742  1049  1543 D ConnectivityService: ignoring duplicate network state non-change
08-16 13:20:29.742  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:29.744  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 13:20:29.745  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:29.749  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.749  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.749  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 13:20:29.749  1049  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 13:20:29.750  1049  1543 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 13:20:29.756  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.756  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.757  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 13:20:29.759  1049  1049 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 13:20:29.760  1049  1536 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 13:20:29.761  1966  1966 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 13:20:29.767  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:29.767  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 13:20:29.777  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:29.780  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 13:20:29.780  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 13:20:29.781  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:29.782  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.783  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.783  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 13:20:29.783  1049  1049 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 13:20:29.786  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.786  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:20:29.787  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 13:20:29.789  1049  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 13:20:29.789  1049  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-16 13:20:29.790  1049  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-16 13:20:29.791   306   907 E Netd    : netlink response contains error (File exists)
08-16 13:20:29.792  1049  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-16 13:20:29.792  1049  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 13:20:29.793  1049  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-16 13:20:29.793  1049  1543 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-16 13:20:29.794  1049  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 13:20:29.795  1049  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 13:20:29.795  1049  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 13:20:29.795  1049  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 13:20:29.795  1049  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:20:29.795  1049  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:29.796  1049  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 13:20:29.796  1049  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:29.796  1049  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 13:20:29.796  1049  1543 D ConnectivityService: currentScore = 0, newScore = 20
08-16 13:20:29.796  1049  1543 D ConnectivityService:    accepting network in place of null
08-16 13:20:29.796  1049  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:29.796  1049  1536 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:29.796  1049  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:20:29.797  1049  8033 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.797  1049  8033 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 13:20:29.798  1049  8033 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 13:20:29.798  1049  8033 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 13:20:29.800  1876  1876 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:29.800  1876  1876 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 13:20:29.800  1049  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnB,andwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 13:20:29.800  1049  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-16 13:20:29.800  1049  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 13:20:29.802   306  8044 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 13:20:29.803  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 13:20:29.803  1049  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:20:29.803  1049  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 13:20:29.803  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 13:20:29.804  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:29.804  1049  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 13:20:29.805  1049  1543 D ConnectivityService: validation of new default Network = false
08-16 13:20:29.805  1049  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 13:20:29.805  1049  1543 D DSQN    : enableDataServiceNotify 
08-16 13:20:29.805  1049  1543 D DSQN    : start dsqn bin
08-16 13:20:29.806  1049  1049 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 13:20:29.806  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 13:20:29.806  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 13:20:29.806  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 13:20:29.813  1049  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 13:20:29.813  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:29.813  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:29.814  1049  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:29.815  1602  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 13:20:29.797  8045  8045 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:29.797  8045  8045 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:29.830  1049  1534 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 13:20:29.831  8045  8045 E DSQN    : DSQN ssw
,08-16 13:20:29.838  1841  8046 I CheckinService: active receiver: enabled
08-16 13:20:29.839  1841  8046 I CheckinService: Preparing to send checkin request
08-16 13:20:29.839  1841  8046 I EventLogService: Accumulating logs since 1471346412577
08-16 13:20:29.844  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 13:20:29.844  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:29.845  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:29.850   306  8044 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 13:20:29.876  1841  8046 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 13:20:29.899   306  8044 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 13:20:29.905  1049  8034 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 13:20:29.906  1049  8034 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 13:20:29.906  1049  8034 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 13:20:29.897  8051  8051 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:29.897  8051  8051 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 13:20:29.915  8051  8051 I dhcpcd  : version 5.5.6 starting
08-16 13:20:29.916  8051  8051 E dhcpcd  : get_duid: m
08-16 13:20:29.916  8051  8051 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 13:20:29.916  8051  8051 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-16 13:20:29.918  6636  6692 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 862)
08-16 13:20:29.919  6636  6692 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 862)
08-16 13:20:29.921  6636  6692 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 867)
08-16 13:20:29.922  6636  6692 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 13:20:29.922  6636  6692 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 868)
08-16 13:20:29.924  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:20:29.924  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f0345 added. We now have 2 listener(s)
08-16 13:20:29.925  1049  1758 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:29.927  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:20:29.928  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:20:29.928  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:20:29.928  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:20:29.928  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4419a9a added. We now have 9 listener(s)
08-16 13:20:29.928  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:20:29.928  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 13:20:29.929  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:20:29.931   306   906 D LGDataListener: argv[0]=dsqncommand
08-16 13:20:29.931   306   906 D LGDataListener: argv[1]=wlan0
08-16 13:20:29.931   306   906 D LGDataListener: argv[2]=1
08-16 13:20:29.931   306   906 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 13:20:29.932  1049  1129 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 13:20:29.933  1049  1129 D DSQN    : start to monitor internet connection
08-16 13:20:29.935  6636  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:20:29.935  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:29.935  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:29.935  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:29.935  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:29.935  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:29.935  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:20:29.935  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:20:29.936  6636  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:29.936  6636  6692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:20:29.936  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:20:29.936  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133923a8 added. We now have 3 listener(s)
08-16 13:20:29.936  1049  2069 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:29.943  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:20:29.945  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:29.950  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:20:29.950  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:20:29.950  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:20:29.950  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:20:29.950  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14218ec1 added. We now have 10 listener(s)
08-16 13:20:29.950  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:20:29.951  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:29.951  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:29.951  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:29.951  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:29.951  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:29.951  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:20:29.951  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:20:29.951  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f0345 removed from the list
08-16 13:20:29.951  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:29.951  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4419a9a removed from the list
08-16 13:20:29.951  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:29.951  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:29.952  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:29.952  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:29.953  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:29.953  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:29.953  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:29.953  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4419a9a not in the list
08-16 13:20:29.953  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:29.953  6636  6692 D org.thaliproject.p2p.btconnecto,rlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:29.954  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:29.954  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:29.954  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:29.954  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14218ec1 removed from the list
08-16 13:20:29.954  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:29.954  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:29.954  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:29.954  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:20:29.954  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133923a8 removed from the list
08-16 13:20:29.955  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:20:29.955  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360ec666 added. We now have 2 listener(s)
08-16 13:20:29.957  1049  2093 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:29.960  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:20:29.960  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:20:29.960  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:20:29.961  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:20:29.961  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da1bda7 added. We now have 9 listener(s)
08-16 13:20:29.961  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:20:29.961  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:20:29.962  1049  8033 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 11:20:29 GMT], X-Android-Received-Millis=[1471346429962], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471346429931]}
08-16 13:20:29.962  1049  8033 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 13:20:29.963  1049  8033 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 13:20:29.963  1049  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 13:20:29.963  1049  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 13:20:29.963  1049  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:20:29.963  1049  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:29.963  1049  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 13:20:29.963  1049  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 13:20:29.963  1049  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 13:20:29.963  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:29.963  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:29.963  1049  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:29.963  1049  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:29.963  1049  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 13:20:29.964  1049  1536 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:29.964  1049  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 13:20:29.964  1602  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 13:20:29.965  1876  1876 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:29.965  1876  1876 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 13:20:29.978  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:20:29.984  6636  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:20:29.984  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:29.984  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:29.984  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:29.984  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:29.984  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:29.984  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:20:29.984  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:20:29.987  6636  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:29.987  6636  6692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:20:29.988  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:20:29.988  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f755fd added. We now have 3 listener(s)
08-16 13:20:29.988  1049  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:29.989  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:29.991  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:20:29.991  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:20:29.991  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:20:29.991  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:20:29.991  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c30e2f2 added. We now have 10 listener(s)
08-16 13:20:29.991  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:20:29.992  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:20:29.992  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:20:29.992  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:20:29.992  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:20:29.992  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:20:29.992  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:29.995  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 13:20:29.995  1049  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:29.997  8051  8051 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 13:20:29.997  8051  8051 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 13:20:29.997  8051  8051 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 13:20:29.998  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 13:20:29.998  8051  8051 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 13:20:29.998  8051  8051 D dhcpcd  : wlan0: sending REQUEST (xid 0x9d16ee0), next in 3.19 seconds
08-16 13:20:29.998  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 13:20:29.998  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 13:20:29.999  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:30.000  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:20:30.000  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 13:20:30.000  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:20:30.001  6636  6692 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 13:20:30.001  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:30.001  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:30.002  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:30.002  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:30.002  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:30.002  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:30.002  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.,bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.002  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:20:30.002  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:20:30.002  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360ec666 removed from the list
08-16 13:20:30.002  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:30.002  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da1bda7 removed from the list
08-16 13:20:30.002  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:30.002  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.002  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.003  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.003  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:30.003  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:30.003  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:30.003  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da1bda7 not in the list
08-16 13:20:30.003  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.003  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.003  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:30.004  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:30.004  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:30.004  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:30.004  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:30.004  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c30e2f2 removed from the list
08-16 13:20:30.004  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:30.004  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.004  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.004  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:20:30.004  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f755fd removed from the list
08-16 13:20:30.004  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:20:30.004  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c6854f9 added. We now have 2 listener(s)
08-16 13:20:30.004  1049  1644 D Blueto,othManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:30.006  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:20:30.006  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:20:30.006  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:20:30.006  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:20:30.006  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23e63c3e added. We now have 9 listener(s)
08-16 13:20:30.006  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:20:30.006  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:20:30.008  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:20:30.012  6636  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:20:30.012  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:30.012  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:30.012  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:30.012  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:30.012  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:30.012  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:20:30.012  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:20:30.013  6636  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:30.013  6636  6692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:20:30.013  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:20:30.013  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28c417ec added. We now have 3 listener(s)
08-16 13:20:30.014  1049  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:30.015  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:30.015  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:20:30.015  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:20:30.015  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:20:30.015  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:20:30.015  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75047b5 added. We now have 10 listener(s)
08-16 13:20:30.015  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:20:30.015  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:20:30.016  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:20:30.016  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:20:30.016  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:20:30.016  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:20:30.016  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:20:30.017  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:30.018  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 13:20:30.018  1049  2093 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:30.021  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 13:20:30.021  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 13:20:30.024  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:20:30.026  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:20:30.027  6636  6692 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 13:20:30.027  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:30.027  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:30.027  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:30.027  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:30.027  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.028  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:20:30.028  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:20:30.028  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c6854f9 removed from the list
08-16 13:20:30.028  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:30.028  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23e63c3e removed from the list
08-16 13:20:30.028  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:30.028  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.028  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.028  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.029  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:30.029  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:30.029  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:30.029  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23e63c3e not in the list
08-16 13:20:30.029  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.029  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.029  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:30.030  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:30.030  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:30.030  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:30.030  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:30.030  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75047b5 removed from the list
08-16 13:20:30.030  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:30.030  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.030  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.030  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:20:30.030  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28c417ec removed from the list
08-16 13:20:30.030  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:20:30.030  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad0c6d8 added. We now have 2 listener(s)
08-16 13:20:30.031  1049  1064 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:30.032  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:20:30.032  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:20:30.032  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:20:30.032  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:20:30.032  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8aaa31 added. We now have 9 listener(s)
08-16 13:20:30.032  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:20:30.032  7641  7773 D UEI.SmartControl: Internal timer expired: 3
08-16 13:20:30.032  7641  7773 D UEI.SmartControl: unbind internal service
08-16 13:20:30.032  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:20:30.035  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:20:30.037  6636  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:20:30.037  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:30.037  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:30.037  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:30.037  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:30.037  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:30.037  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:20:30.037  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:20:30.038  6636  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:30.038  6636  6692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:20:30.038  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:20:30.038  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361f5e97 added. We now have 3 listener(s)
08-16 13:20:30.038  1049  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:30.039  7641  7641 D UEI.SmartControl: Service.onUnbind: IControl
08-16 13:20:30.040  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:20:30.040  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:20:30.040  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:20:30.040  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:20:30.040  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f77884 added. We now have 10 listener(s)
08-16 13:20:30.041  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:20:30.041  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:20:30.041  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:20:30.041  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:20:30.041  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:20:30.041  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:20:30.041  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:20:30.043  8051  8051 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-16 13:20:30.044  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:20:30.044  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 13:20:30.044  7641  7641 D UEI.SmartControl: Service.onDestroy
08-16 13:20:30.044  1049  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:30.044  7641  7641 D UEI.SmartControl: Lock is in USE false
08-16 13:20:30.044  7641  7641 D UEI.SmartControl: unbind internal service
08-16 13:20:30.045  7641  7641 D serial_port: close(fd = 24)
08-16 13:20:30.048  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 13:20:30.048  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 13:20:30.049  7641  7641 I UEI.SmartControl: Serial port is closed.
08-16 13:20:30.049  7641  7641 I UEI.SmartControl: Serial port is closed.
08-16 13:20:30.049  7641  7641 D UEI.SmartControl: Blaster closed
08-16 13:20:30.049  7641  7641 D UEI.SmartControl: Shut down QS...
08-16 13:20:30.049  7641  7641 D UEI.SmartControl: Stopping QS lib
08-16 13:20:30.049  7641  7641 D UEI.SmartControl: QS lib stop result = true
08-16 13:20:30.049  7641  7641 D UEI.SmartControl: Stopped QS lib
08-16 13:20:30.049  7641  7641 D UEI.SmartControl: QS shutdown complete
08-16 13:20:30.050  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:20:30.050  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:20:30.051  6636  6692 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 13:20:30.052  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:30.052  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:30.052  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:30.052  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:30.052  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.052  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:20:30.052  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:20:30.052  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad0c6d8 removed from the list
08-16 13:20:30.052  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:30.052  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8aaa31 removed from the list
08-16 13:20:30.052  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:30.052  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.053  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.053  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.053  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:30.053  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:30.053  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:30.053  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8aaa31 not in the list
08-16 13:20:30.053  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.053  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.054  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:30.054  6636  6692 D BluetoothLeScanner: could not find callback wrapper
08-16 13:20:30.054  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:20:30.054  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:30.054  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:30.054  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f77884 removed from the list
08-16 13:20:30.054  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:30.054  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.054  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.054  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:20:30.054  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361f5e97 removed from the list
08-16 13:20:30.055  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:20:30.055  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17f14d33 added. We now have 2 listener(s)
08-16 13:20:30.055  1049  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:30.056  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:20:30.057  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:20:30.057  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:20:30.057  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:20:30.057  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb598f0 added. We now have 9 listener(s)
08-16 13:20:30.057  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:20:30.067  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:20:30.075  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:20:30.077  8051  8051 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 13:20:30.077  8051  8051 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 13:20:30.078  8051  8051 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 13:20:30.078  8051  8051 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 13:20:30.078  8051  8051 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 13:20:30.078  8051  8051 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 13:20:30.078  8051  8051 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 13:20:30.078  8051  8051 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 13:20:30.078  6636  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:20:30.078  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:20:30.078  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 13:20:30.078  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:20:30.078  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:20:30.078  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:30.078  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:20:30.078  6636  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:20:30.079  6636  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:20:30.079  6636  6692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:20:30.079  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:20:30.079  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b3830ee added. We now have 3 listener(s)
08-16 13:20:30.080  1049  1758 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 13:20:30.081  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:20:30.083  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 13:20:30.083  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:20:30.083  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:20:30.083  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:20:30.083  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be9898f added. We now have 10 listener(s)
08-16 13:20:30.083  6636  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:20:30.083  6636  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:20:30.084  6636  6692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:20:30.084  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:30.084  6636  6692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:20:30.084  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:30.084  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.084  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:20:30.084  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:20:30.084  6636  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17f14d33 removed from the list
08-16 13:20:30.084  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:30.084  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb598f0 removed from the list
08-16 13:20:30.084  6636  6692 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:20:30.084  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.084  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.084  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.085  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:30.085  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:30.085  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:30.085  6636  6692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb598f0 not in the list
08-16 13:20:30.085  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.085  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.086  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:20:30.086  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:20:30.086  6636  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:20:30.086  6636  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be9898f removed from the list
08-16 13:20:30.086  6636  6692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:20:30.086  6636  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:20:30.086  6636  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:20:30.086  6636  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:20:30.086  6636  6692 V org.thaliproject.p2p.btconnectorlib.Conne,ctionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b3830ee removed from the list
08-16 13:20:30.087  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 13:20:30.087  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 13:20:30.087  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 13:20:30.087  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:20:30.087  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 13:20:30.088  6636  6692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 13:20:30.095  6636  8063 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 875, name: My test thread name)
08-16 13:20:30.095  6636  8063 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 875, thread name: My test thread name)
08-16 13:20:30.095  6636  8063 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 875, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 13:20:30.096  6636  8064 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 877, name: My test thread name)
08-16 13:20:30.100  6636  8064 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 877, thread name: My test thread name)
08-16 13:20:30.100  6636  8064 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 877, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 13:20:30.101  6636  6692 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-16 13:20:30.101  6636  6692 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 13:20:30.101  6636  6692 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 13:20:30.102  6636  6692 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 13:20:30.102  6636  6692 D com.test.thalitest.ThaliTestRunner: Total duration: 22927 ms
08-16 13:20:30.102  6636  6692 I jxcore-log: Total number of executed tests:  80
08-16 13:20:30.102  6636  6692 I jxcore-log: 
08-16 13:20:30.102  6636  6692 I jxcore-log: Number of passed tests:  80
08-16 13:20:30.102  6636  6692 I jxcore-log: 
08-16 13:20:30.103  6636  6692 I jxcore-log: Number of failed tests:  0
08-16 13:20:30.103  6636  6692 I jxcore-log: 
08-16 13:20:30.103  6636  6692 I jxcore-log: Number of ignored tests:  0
08-16 13:20:30.103  6636  6692 I jxcore-log: 
08-16 13:20:30.103  6636  6692 I jxcore-log: Total duration:  22927
08-16 13:20:30.103  6636  6692 I jxcore-log: 
08-16 13:20:30.103  6636  6692 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 13:20:30.103  6636  6692 I jxcore-log: 
08-16 13:20:30.106  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:20:30.106  6636  6692 I jxcore-log: 
08-16 13:20:30.109  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:20:30.109  6636  6692 I jxcore-log: 
08-16 13:20:30.110  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:20:30.110  6636  6692 I jxcore-log: 
08-16 13:20:30.110  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:20:30.110  6636  6692 I jxcore-log: 
08-16 13:20:30.111  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:20:30.111  6636  6692 I jxcore-log: 
08-16 13:20:30.112  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:20:30.112  6636  6692 I jxcore-log: 
08-16 13:20:30.114  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:20:30.114  6636  6692 I jxcore-log: 
08-16 13:20:30.115  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:20:30.115  6636  6692 I jxcore-log: 
08-16 13:20:30.116  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:20:30.116  6636  6692 I jxcore-log: 
08-16 13:20:30.116  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActiv,e":false,"advertisingActive":false}
08-16 13:20:30.116  6636  6692 I jxcore-log: 
08-16 13:20:30.117  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:20:30.117  6636  6692 I jxcore-log: 
08-16 13:20:30.118  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:20:30.118  6636  6692 I jxcore-log: 
08-16 13:20:30.119  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:20:30.119  6636  6692 I jxcore-log: 
08-16 13:20:30.119  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:20:30.119  6636  6692 I jxcore-log: 
08-16 13:20:30.120  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:20:30.120  6636  6692 I jxcore-log: 
08-16 13:20:30.120  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:20:30.120  6636  6692 I jxcore-log: 
08-16 13:20:30.121  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:20:30.121  6636  6692 I jxcore-log: 
08-16 13:20:30.121  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:20:30.121  6636  6692 I jxcore-log: 
08-16 13:20:30.122  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:20:30.122  6636  6692 I jxcore-log: 
08-16 13:20:30.122  6636  6636 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 13:20:30.122  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:20:30.122  6636  6692 I jxcore-log: 
,08-16 13:20:30.123  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 13:20:30.123  6636  6692 I jxcore-log: 
08-16 13:20:30.123  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 13:20:30.123  6636  6692 I jxcore-log: 
08-16 13:20:30.124  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:20:30.124  6636  6692 I jxcore-log: 
08-16 13:20:30.124  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:20:30.124  6636  6692 I jxcore-log: 
08-16 13:20:30.125  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:20:30.125  6636  6692 I jxcore-log: 
08-16 13:20:30.125  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:20:30.125  6636  6692 I jxcore-log: 
08-16 13:20:30.126  6636  6692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:20:30.126  6636  6692 I jxcore-log: 
08-16 13:20:30.182  8013  8013 W ExternalStrings: load override strings
08-16 13:20:30.182  8013  8013 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:20:30.182  8013  8013 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 13:20:30.183  8013  8013 D StatusProvider: onCreate
,08-16 13:20:30.272  7130  7149 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:20:30.272  7130  7149 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:20:30.272  7130  7149 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:20:30.272  7130  7149 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:20:30.272  7130  7149 I Adreno-EGL: Remote Branch: 
08-16 13:20:30.272  7130  7149 I Adreno-EGL: Local Patches: 
08-16 13:20:30.272  7130  7149 I Adreno-EGL: Reconstruct Branch: 
08-16 13:20:30.282  8013  8013 V Signer  : override build config not found
08-16 13:20:30.282  8013  8013 D Signer  : value of property debug is false
,08-16 13:20:30.308  1049  8034 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-16 13:20:30.310  1049  8034 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-16 13:20:30.310  1049  8034 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 13:20:30.310  1049  8034 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 13:20:30.310  1049  8034 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 13:20:30.310  1049  8034 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 13:20:30.310  1049  8034 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 13:20:30.310  1049  8034 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 13:20:30.310  1049  8034 D DhcpStateMachine: RunningState
08-16 13:20:30.319  7130  7149 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:20:30.319  7130  7149 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:20:30.319  7130  7149 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:20:30.319  7130  7149 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:20:30.319  7130  7149 I Adreno-EGL: Remote Branch: 
08-16 13:20:30.319  7130  7149 I Adreno-EGL: Local Patches: 
08-16 13:20:30.319  7130  7149 I Adreno-EGL: Reconstruct Branch: 
08-16 13:20:30.321  8079  8079 D AndroidRuntime: 
08-16 13:20:30.321  8079  8079 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 13:20:30.322  8013  8013 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-16 13:20:30.322  8013  8013 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-16 13:20:30.323  8013  8013 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-16 13:20:30.323  8013  8013 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-16 13:20:30.323  8079  8079 D AndroidRuntime: CheckJNI is OFF
08-16 13:20:30.323  8013  8013 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-16 13:20:30.323  8013  8013 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-16 13:20:30.323  8013  8013 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-16 13:20:30.324  8013  8013 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-16 13:20:30.324  8013  8013 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-16 13:20:30.324  8013  8013 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-16 13:20:30.324  8013  8013 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-16 13:20:30.325  8013  8013 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-16 13:20:30.325  8013  8013 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-16 13:20:30.343  8013  8013 V LGMDMManager: Create singleton instance
,08-16 13:20:30.376  7130  7149 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 13:20:30.376  7130  7149 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 13:20:30.376  7130  7149 I Adreno-EGL: Build Date: 12/12/14 금
08-16 13:20:30.376  7130  7149 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 13:20:30.376  7130  7149 I Adreno-EGL: Remote Branch: 
08-16 13:20:30.376  7130  7149 I Adreno-EGL: Local Patches: 
08-16 13:20:30.376  7130  7149 I Adreno-EGL: Reconstruct Branch: 
,08-16 13:20:30.405  8013  8013 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-16 13:20:30.437  8079  8079 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 13:20:30.447  1049  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-16 13:20:30.447  1049  1124 I ActivityManager: Killing 6636:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-16 13:20:30.451  8013  8013 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 13:20:30.452  8013  8098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 13:20:30.506  1049  1758 I WindowState: WIN DEATH: Window{30aeb0e6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 13:20:30.506  1049  1542 D WifiService: Client connection lost with reason: 4
08-16 13:20:30.511  1049  1758 D InputDispatcher: Window went away: Window{30aeb0e6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 13:20:30.557  8013  8097 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 13:20:30.654  1049  1124 E libprocessgroup: failed to kill 1 processes for processgroup 6636
,08-16 13:20:30.659  1049  1124 I ActivityManager:   Force finishing activity ActivityRecord{bf541e3 u0 com.test.thalitest/.MainActivity t6}
,08-16 13:20:30.720   331   344 E GBMv2   : DFP En is all cleared set to be enabled
,08-16 13:20:30.728  1049  1064 W ActivityManager: Spurious death for ProcessRecord{2b8aa9e1 6636:com.test.thalitest/u0a118}, curProc for 6636: null
08-16 13:20:30.731  2094  2094 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-16 13:20:30.733  2094  2094 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-16 13:20:30.739  2094  2094 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-16 13:20:30.740  1049  1137 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-16 13:20:30.740  2094  2176 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-16 13:20:30.747  1049  1137 I ActivityManager:   Force finishing activity ActivityRecord{bf541e3 u0 com.test.thalitest/.MainActivity t6 f}
08-16 13:20:30.747  1049  1137 W ActivityManager: Duplicate finish request for ActivityRecord{bf541e3 u0 com.test.thalitest/.MainActivity t6 f}
,08-16 13:20:30.774  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-16 13:20:30.782  3838  3838 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-16 13:20:30.784  2038  2038 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 13:20:30.788  7539  7539 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-16 13:20:30.788  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 13:20:30.793  4472  4472 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-16 13:20:30.793  4472  4472 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-16 13:20:30.794  4472  4472 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-16 13:20:30.794  4472  4472 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-16 13:20:30.794  4472  4472 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 13:20:30.794  4472  4472 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 13:20:30.794  4472  4472 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:20:30.794  4472  4472 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:20:30.794  4472  4472 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:20:30.794  4472  4472 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:20:30.794  4472  4472 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:20:30.794  4472  4472 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 13:20:30.796  2467  2604 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 13:20:30.807  1049  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 13:20:30.818  4583  4583 I art     : Explicit concurrent mark sweep GC freed 8256(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 724us total 59.054ms
,08-16 13:20:30.860  1049  1049 D administrator: Handling package changes for user 0
08-16 13:20:30.862  1966  1989 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-16 13:20:30.862  1049  2011 V SIM_STK : Menu title from STK is T-Mobile
08-16 13:20:30.862  1966  1989 D SplitWindowPolicy: topRunningActivity=ActivityInfo{24756b2d co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 13:20:30.862  2094  2094 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-16 13:20:30.864  1966  3397 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-16 13:20:30.864  1966  3397 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1e748862 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 13:20:30.865  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 13:20:30.865  1927  1927 D ActionManagerService: notifyUserLog: 1000003
08-16 13:20:30.868  3838  4471 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-16 13:20:30.873  2094  2094 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-16 13:20:30.874  1602  1646 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 13:20:30.874  1602  1646 D KeyguardModel: createShortcutInfo...
08-16 13:20:30.874  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-16 13:20:30.874  2094  2094 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-16 13:20:30.875  2094  2094 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-16 13:20:30.877  1602  1646 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 13:20:30.878  1602  1646 D KeyguardModel: createShortcutInfo...
08-16 13:20:30.882  1602  1646 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 13:20:30.882  1602  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 13:20:30.883  1602  1646 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 13:20:30.883  1602  1646 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 13:20:30.885  1927  1927 D ActionManagerService: notifyUserLog: 1000004
08-16 13:20:30.885  1602  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 13:20:30.885  1602  1646 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 13:20:30.886  3838  4471 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-16 13:20:30.888  2094  2094 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-16 13:20:30.899  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-16 13:20:30.901  1602  1646 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 13:20:30.901  1602  1646 D KeyguardModel: createShortcutInfo...
08-16 13:20:30.902  3838  3854 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 13:20:30.903  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-16 13:20:30.904  2094  2094 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-16 13:20:30.904  2094  2094 I GBoardWebViewUtils: , create_time: 1430832262123
08-16 13:20:30.904  2094  2094 I GBoardWebViewUtils: , expire_time: 0
08-16 13:20:30.904  2094  2094 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-16 13:20:30.904  2094  2094 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-16 13:20:30.904  2094  2094 I GBoardWebViewUtils: , display: false
08-16 13:20:30.904  2094  2094 I GBoardWebViewUtils: , animation: false }
08-16 13:20:30.904  2094  2094 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-16 13:20:30.904  2094  2094 I GBoardWebViewUtils: , create_time: 1430832262287
08-16 13:20:30.904  2094  2094 I GBoardWebViewUtils: , expire_time: 0
08-16 13:20:30.904  2094  2094 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 13:20:30.904  2094  2094 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 13:20:30.904  2094  2094 I GBoardWebViewUtils: , display: false
08-16 13:20:30.904  2094  2094 I GBoardWebViewUtils: , animation: false }
08-16 13:20:30.905  2094  2094 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-16 13:20:30.905  2094  2094 I GBoardWebViewUtils: , create_time: 1471007226523
08-16 13:20:30.905  2094  2094 I GBoardWebViewUtils: , expire_time: 0
08-16 13:20:30.905  2094  2094 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 13:20:30.905  2094  2094 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 13:20:30.905  2094  2094 I GBoardWebViewUtils: , display: false
08-16 13:20:30.905  2094  2094 I GBoardWebViewUtils: , animation: false }
08-16 13:20:30.910  2094  8106 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-16 13:20:30.916  1602  1646 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 13:20:30.916  1602  1646 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:20:30.917  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:30.917  1602  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 13:20:30.918  1602  1646 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 13:20:30.928  1602  1646 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
,08-16 13:20:30.928  1602  1646 D KeyguardModel: createShortcutInfo...
08-16 13:20:30.939  1602  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 13:20:30.939  1602  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 13:20:30.940  1602  1646 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 13:20:30.940  1602  1646 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 13:20:30.942  1602  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 13:20:30.942  1602  1646 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-16 13:20:30.946  2094  2094 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 13:20:30.947  2094  2094 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-16 13:20:30.954  1602  1646 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 13:20:30.954  1602  1646 D KeyguardModel: createShortcutInfo...
08-16 13:20:30.960  1893  1893 D SplitUIManager: split_name #11 / not available #0
08-16 13:20:30.961  1893  1893 D SplitUIService: removed split : 
,08-16 13:20:30.966  1049  1065 V SIM_STK : Menu title from STK is T-Mobile
08-16 13:20:30.967  1049  1065 V SIM_STK : Menu title from STK is T-Mobile
08-16 13:20:30.974  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-16 13:20:30.974  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-16 13:20:31.009  1049  1984 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8113 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-16 13:20:31.020  1893  1893 D SplitUIManager: split_name #11 / not available #0
08-16 13:20:31.020  1893  1893 I SplitUIService: split app #11
08-16 13:20:31.032  1049  1963 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 13:20:31.033  1602  1646 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 13:20:31.033  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 13:20:31.033  1602  1646 D KeyguardModel: createShortcutInfo...
08-16 13:20:31.033  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 13:20:31.033  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 13:20:31.033  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 13:20:31.033  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 13:20:31.033  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 13:20:31.033  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 13:20:31.033  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 13:20:31.033  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 13:20:31.035  1602  1646 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 13:20:31.035  1602  1646 D KeyguardModel: createShortcutInfo...
08-16 13:20:31.036  1602  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 13:20:31.036  1602  1646 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 13:20:31.037  1602  1646 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 13:20:31.037  1602  1646 D KeyguardModel: createShortcutInfo...
08-16 13:20:31.038  1602  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 13:20:31.038  1602  1646 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 13:20:31.038  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 13:20:31.038  7539  7539 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 13:20:31.039  1602  1646 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 13:20:31.039  1602  1646 D KeyguardModel: createShortcutInfo...
08-16 13:20:31.040  1602  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 13:20:31.040  1602  1646 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 13:20:31.041  1602  1646 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 13:20:31.041  1602  1646 D KeyguardModel: createShortcutInfo...
08-16 13:20:31.045  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-16 13:20:31.045  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-16 13:20:31.059  1049  2111 V SIM_STK : Menu title from STK is T-Mobile
08-16 13:20:31.062  1049  1049 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-16 13:20:31.062  1049  1049 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 13:20:31.062  1049  1049 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-16 13:20:31.065  1049  1575 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-16 13:20:31.073  1049  1122 W InputMethodInfo: Duplicated subtype definition found: , voice
08-16 13:20:31.075   306  8131 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 13:20:31.076   306  8131 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-16 13:20:31.089  2094  2094 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-16 13:20:31.089  2094  2094 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-16 13:20:31.092  2094  2094 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 13:20:31.093  2094  2094 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-16 13:20:31.095  2094  2094 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-16 13:20:31.096  8013  8097 D LgDataFeature: LgDataFeature() Constructor: none
08-16 13:20:31.096  8013  8097 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 13:20:31.096  2094  2094 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-16 13:20:31.097  2094  2094 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-16 13:20:31.111   306  8131 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-16 13:20:31.115  2094  2094 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-16 13:20:31.115  2094  2301 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-16 13:20:31.115  2094  2094 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 13:20:31.115  2094  2301 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-16 13:20:31.126  1049  1132 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3fdb5c7d u0 com.lge.launcher2/.Launcher t5} time:225368
08-16 13:20:31.128  1049  1536 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:31.128  1049  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:31.128  1049  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:31.129  1049  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:31.129  1049  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:31.129  1049  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 13:20:31.129  2094  2094 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-16 13:20:31.130  1049  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-16 13:20:31.130  1049  1543 D ConnectivityService: identical MTU - not setting
08-16 13:20:31.130  1049  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 13:20:31.130  1049  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 13:20:31.130  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 13:20:31.130  1049  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:31.130  1049  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 13:20:31.130  2094  2094 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 13:20:31.130  2094  2094 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 13:20:31.130  1602  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 13:20:31.136   325   433 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-16 13:20:31.137  3241  8134 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-16 13:20:31.137  2094  2094 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-16 13:20:31.139  2644  2644 D [Concierge]Service: onStartCommand(). Type : 8
08-16 13:20:31.139  2644  2644 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-16 13:20:31.140  2644  2644 D [Concierge]Service: Update widget ID : 11
08-16 13:20:31.141  2094  2094 D [Concierge]WidgetView: change position of spinner
08-16 13:20:31.142  2094  2094 I [Concierge]WidgetView: initWebView(). Time : 1471346431142
08-16 13:20:31.143  2644  2644 D [Concierge]Service: onStartCommand(). Type : 0
08-16 13:20:31.159  8113  8113 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 13:20:31.169  2094  2094 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 586204773
08-16 13:20:31.170  2094  2094 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-16 13:20:31.170  2094  2094 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 13:20:31.173  2094  2094 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@139f73ae
08-16 13:20:31.173  2094  2094 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-16 13:20:31.174  2094  2094 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 13:20:31.174  2094  2094 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 13:20:31.179  2094  2094 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-16 13:20:31.179  2094  2094 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-16 13:20:31.179  2094  2094 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-16 13:20:31.187  2094  2094 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471346234057, New one : 1471346431142
,08-16 13:20:31.187  2094  2094 D [Concierge]WidgetView: Unregister all receivers
08-16 13:20:31.187  2094  2094 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 13:20:31.189  2094  2094 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 13:20:31.190  2094  2094 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-16 13:20:31.191  2094  2094 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-16 13:20:31.192  2094  2094 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-16 13:20:31.193  2094  2094 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-16 13:20:31.195  2094  2094 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-16 13:20:31.195  2094  2094 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 13:20:31.195  2094  2094 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 13:20:31.208  8113  8113 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-16 13:20:31.226  2094  2094 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 13:20:31.226  8113  8113 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 13:20:31.226  8113  8113 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 13:20:31.227  8113  8113 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 13:20:31.227  8113  8113 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 13:20:31.227  8113  8113 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 13:20:31.228  8113  8113 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-16 13:20:31.232  8113  8113 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 13:20:31.234  8013  8097 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-16 13:20:31.234  2094  2094 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-16 13:20:31.234  2094  2094 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-16 13:20:31.236  2094  2094 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 13:20:31.237  8113  8113 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:31.245  8113  8113 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 13:20:31.255  1841  8046 I CheckinTask: Sending checkin request (7904 bytes)
08-16 13:20:31.263  2094  2094 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2bcf8376 time:225506
,08-16 13:20:31.265  8013  8097 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-16 13:20:31.265  8113  8113 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 13:20:31.267  8013  8013 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:31.267  8113  8113 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-16 13:20:31.267  8013  8098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 13:20:31.269  8113  8113 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 13:20:31.274  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 13:20:31.277  8013  8097 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-16 13:20:31.277  8013  8097 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 13:20:31.277  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:31.278  8013  8097 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 13:20:31.278  8013  8097 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
,08-16 13:20:31.278  8013  8097 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-16 13:20:31.282  8113  8113 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:31.282  8113  8113 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:31.283  8113  8113 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 13:20:31.285  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 13:20:31.286  6717  6717 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 13:20:31.288  8013  8097 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-16 13:20:31.288  8013  8013 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:31.289  8013  8098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 13:20:31.289  8013  8097 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-16 13:20:31.294  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 13:20:31.297  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:31.297  1049  1137 I art     : Explicit concurrent mark sweep GC freed 85473(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.362ms total 366.610ms
08-16 13:20:31.301  8113  8113 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:31.301  8113  8113 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:31.302  8113  8113 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:20:31.303  8013  8013 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:31.304  8013  8098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 13:20:31.308  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 13:20:31.311  1049  1122 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 13:20:31.319  1049  1122 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-16 13:20:31.326  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:31.349  2094  2094 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-16 13:20:31.351  8079  8079 D AndroidRuntime: Shutting down VM
08-16 13:20:31.355  8113  8113 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:31.355  8113  8113 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:31.355  8113  8113 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:20:31.358  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 13:20:31.358  6717  6717 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 13:20:31.358  6717  6717 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 13:20:31.358  6717  6717 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 13:20:31.358  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 13:20:31.387  1049  1137 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8141 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-16 13:20:31.390  2094  2094 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-16 13:20:31.394  6717  6717 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 13:20:31.394  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 13:20:31.394  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 13:20:31.394  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 13:20:31.394  6717  6717 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 13:20:31.394  6717  6717 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 13:20:31.394  6717  6717 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 13:20:31.399  8013  8013 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:31.400  8013  8098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 13:20:31.408  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:31.414  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:31.421  8113  8113 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:31.421  8113  8113 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 13:20:31.421  8113  8113 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:20:31.423  8013  8013 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:31.423  8013  8098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 13:20:31.430  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:31.436  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 13:20:31.439  1049  1065 I ActivityManager: Killing 7567:com.google.android.talk/u0a72 (adj 15): empty #17
08-16 13:20:31.440  2094  2948 I GBoardtInterface: onReloaded()
08-16 13:20:31.448  2094  2094 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-16 13:20:31.468  8113  8113 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 13:20:31.468  8113  8113 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:31.469  1049  2018 W libprocessgroup: failed to open /acct/uid_10072/pid_7567/cgroup.procs: No such file or directory
08-16 13:20:31.469  8113  8113 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:20:31.469  3838  3854 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 13:20:31.472  8013  8013 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:31.473  3838  4467 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 13:20:31.478  1927  1927 D ActionManagerService: notifyUserLog: 1000001
08-16 13:20:31.478  3838  4471 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 13:20:31.479  3838  4471 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 13:20:31.481  1927  1927 D ActionManagerService: notifyUserLog: 1000001
,08-16 13:20:31.482  3838  4471 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,08-16 13:20:31.482  3838  4471 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 13:20:31.482  3838  4471 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-16 13:20:31.482  3838  4471 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-16 13:20:31.483  3838  3854 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 13:20:31.485  2094  2094 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-16 13:20:31.485  2094  2094 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-16 13:20:31.488  2094  2094 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-16 13:20:31.488  2094  2094 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 13:20:31.489  2094  2094 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-16 13:20:31.489  2094  2094 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 13:20:31.496  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:31.498  1841  8046 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
08-16 13:20:31.500  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 13:20:31.503  8113  8113 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:31.504  1841  8046 I CheckinService: active receiver: disabled
08-16 13:20:31.504  8113  8113 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:31.506  8113  8113 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 13:20:31.526  8013  8013 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:31.535  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:31.541  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:31.545  8113  8113 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:31.546  8113  8113 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:31.549  8113  8113 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 13:20:31.550  8013  8013 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:31.554  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 13:20:31.559  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:31.562  8113  8113 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:31.563  8113  8113 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 13:20:31.563  8113  8113 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 13:20:31.565  8013  8013 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:31.567  7966  7966 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 13:20:31.569  7966  7966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:20:31.571  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 13:20:31.573  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 13:20:31.577  8113  8113 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:31.577  8113  8113 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:31.577  8113  8113 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 13:20:31.578  8113  8113 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 13:20:31.578  8113  8113 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 13:20:31.580  8013  8013 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 13:20:31.582  7966  7966 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 13:20:31.582  7966  7966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 13:20:31.584  6717  6717 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 13:20:31.587  6717  6717 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 13:20:31.590  8113  8113 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 13:20:31.591  8113  8113 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 13:20:31.591  8113  8113 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 13:20:31.591  8113  8113 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 13:20:31.591  8113  8113 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 13:20:31.593  8013  8013 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 13:20:31.595  1841  1841 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-16 13:20:31.598  2239  2239 I ConfigService: onCreate
08-16 13:20:31.599  2239  2239 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-16 13:20:31.601  1841  1841 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-16 13:20:31.603  2239  2239 I ConfigService: onBind returning update interface
08-16 13:20:31.603  2239  2239 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-16 13:20:31.603  2239  2239 I ConfigService: onBind returning config service
08-16 13:20:31.648  2239  2239 I ConfigService: onDestroy
,08-16 13:20:31.652  1841  8164 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-16 13:20:31.675  5941  8169 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-16 13:20:31.678  1841  8171 I PeopleContactsSync: CP2 sync disabled
08-16 13:20:31.698  1841  4756 I Icing   : doRemovePackageData com.test.thalitest
,08-16 13:20:31.701  2239  2254 I art     : Explicit concurrent mark sweep GC freed 6505(386KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 772us total 16.800ms
,08-16 13:20:31.714  1841  8170 W GmsApplication: Using Auth Proxy for data requests.
,08-16 13:20:31.718  1841  8170 W GmsApplication: Using Auth Proxy for data requests.
08-16 13:20:31.766  6921  6921 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-16 13:20:31.770  2094  2948 I GBoardtInterface: exportHTML()
08-16 13:20:31.777  2203  8174 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 13:20:31.785  2203  2369 E SQLiteLog: (2570) os_unix.c:31441: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjCCD797944) - 
08-16 13:20:31.795  2203  2369 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-16 13:20:31.795  2203  2369 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
08-16 13:20:31.795  2203  2369 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-16 13:20:31.795  2203  2369 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-16 13:20:31.795  2203  2369 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
08-16 13:20:31.795  2203  2369 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
08-16 13:20:31.795  2203  2369 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:525)
08-16 13:20:31.795  2203  2369 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:414)
08-16 13:20:31.795  2203  2369 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-16 13:20:31.795  2203  2369 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-16 13:20:31.795  2203  2369 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-16 13:20:31.795  2203  2369 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-16 13:20:31.795  2203  2369 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:20:31.795  2203  2369 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:20:31.795  2203  2369 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 13:20:31.797  2203  8174 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
08-16 13:20:31.798  2203  8174 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-16 13:20:31.798  2203  8174 E AndroidRuntime: Process: android.process.acore, PID: 2203
08-16 13:20:31.798  2203  8174 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:20:31.798  2203  8174 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 13:20:31.805  2094  2948 I GBoardtInterface: exportHTML()
08-16 13:20:31.807  1049  2093 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8176 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 13:20:31.813  2203  8174 I Process : Sending signal. PID: 2203 SIG: 9
08-16 13:20:31.814   275   275 E lowmemorykiller: Error writing /proc/2203/oom_score_adj; errno=22
08-16 13:20:31.815  1049  8185 E DropBoxManagerService: Can't write: system_app_crash
08-16 13:20:31.815  1049  8185 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-16 13:20:31.815  1049  8185 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-16 13:20:31.815  1049  8185 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 13:20:31.815  1049  8185 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 13:20:31.815  1049  8185 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 13:20:31.815  1049  8185 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-16 13:20:31.815  1049  8185 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-16 13:20:31.815  1049  8185 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 13:20:31.815  1049  8185 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 13:20:31.815  1049  8185 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 13:20:31.815  1049  8185 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 13:20:31.815  1049  8185 E DropBoxManagerService: 	... 5 more
08-16 13:20:31.830  1841  8166 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-16 13:20:31.833  2094  2948 I GBoardtInterface: exportHTML()
08-16 13:20:31.835  1841  8166 E DriveAsyncService: disk I/O error (code 3850)
08-16 13:20:31.835  1841  8166 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 13:20:31.835  1841  8166 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-16 13:20:31.835  1841  8166 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-16 13:20:31.835  1841  8166 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-16 13:20:31.835  1841  8166 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-16 13:20:31.835  1841  8166 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-16 13:20:31.835  1841  8166 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-16 13:20:31.835  1841  8166 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
08-16 13:20:31.835  1841  8166 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
08-16 13:20:31.835  1841  8166 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
08-16 13:20:31.835  1841  8166 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
08-16 13:20:31.835  1841  8166 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-16 13:20:31.835  1841  8166 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:20:31.835  1841  8166 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:20:31.835  1841  8166 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 13:20:31.848  8176  8176 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 13:20:31.849  8176  8176 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 13:20:31.849  8176  8176 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 13:20:31.850  8176  8176 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 13:20:31.877  1049  1758 I ActivityManager: Process android.process.acore (pid 2203) has died
08-16 13:20:31.877  1049  1758 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 1000ms
08-16 13:20:31.878  1049  1758 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
,08-16 13:20:31.890  8176  8176 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:20:31.890  8176  8176 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 13:20:31.890  8176  8176 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:20:31.891  8176  8176 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:20:31.891  8176  8176 W System.err: 	at a,ndroid.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:20:31.891  8176  8176 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:20:31.891  8176  8176 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:20:31.891  8176  8176 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:20:31.891  8176  8176 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:20:31.891  8176  8176 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:20:31.891  8176  8176 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 13:20:31.895  8176  8176 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:20:31.895  8176  8176 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 13:20:31.896  8176  8176 D AndroidRuntime: Shutting down VM
08-16 13:20:31.896  8176  8176 E AndroidRuntime: FATAL EXCEPTION: main
08-16 13:20:31.896  8176  8176 E AndroidRuntime: Process: com.lge.email, PID: 8176
08-16 13:20:31.896  8176  8176 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.email.pr,oviders.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-16 13:20:31.896  8176  8176 E AndroidRuntime: 	... 11 more
08-16 13:20:31.899  1049  8196 E DropBoxManagerService: Can't write: system_app_crash
08-16 13:20:31.899  1049  8196 E Dro,pBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
08-16 13:20:31.899  1049  8196 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-16 13:20:31.899  1049  8196 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 13:20:31.899  1049  8196 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 13:20:31.899  1049  8196 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 13:20:31.899  1049  8196 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-16 13:20:31.899  1049  8196 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-16 13:20:31.899  1049  8196 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 13:20:31.899  1049  8196 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 13:20:31.899  1049  8196 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 13:20:31.899  1049  8196 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 13:20:31.899  1049  8196 E DropBoxManagerService: 	... 5 more
08-16 13:20:31.899  8176  8176 I Process : Sending signal. PID: 8176 SIG: 9
08-16 13:20:31.977  1049  2011 I ActivityManager: Process com.lge.email (pid 8176) has died
,08-16 13:20:32.019  4472  4520 E SQLiteLog: (2570) os_unix.c:31441: (30) unlink(/mpt/MPT_CommonData.db-journal) - 

```
