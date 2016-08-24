#### Test 825189961ca4444_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-24 16:55:55.113  1605  1605 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 16:55:55.114  1605  1605 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 16:55:55.138  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
--------- beginning of system
08-24 16:55:55.140  1034  1545 D WifiController: battery changed pluggedType: 2
08-24 16:55:55.141  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:55:55.142  3875  3982 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 16:55:55.144  1605  1605 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
08-24 16:55:55.144  1605  1605 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 16:55:55.146  1974  2138 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 16:55:55.146  1974  2138 D LEDHandler: Battery Level Remaining: 100%
08-24 16:55:55.146  1974  2138 D LEDHandler: Battery Temp: 292, mChargingStatus=5, mChargingStop=false
08-24 16:55:55.148  1605  1605 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 16:55:55.154  6590  6590 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 16:55:55.420  6680  6680 D AndroidRuntime: 
08-24 16:55:55.420  6680  6680 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 16:55:55.424  6680  6680 D AndroidRuntime: CheckJNI is OFF
08-24 16:55:55.629  6680  6680 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-24 16:55:55.640  1034  1577 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 16:55:55.656  1974  1990 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-24 16:55:55.664  1034  1577 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-24 16:55:55.665  1034  1577 D ActivityManager: setTaskToReturnTo : TaskRecord{13c8da1a #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 16:55:55.665  1034  1577 D ActivityManager: setTaskToReturnTo : TaskRecord{13c8da1a #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 16:55:55.667  1034  1577 D WindowStateEx: AppWindowTokenEx init.. 
08-24 16:55:55.668   334   349 E GBMv2   : DFP En is all cleared set to be enabled
08-24 16:55:55.696  1034  1577 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6695 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 16:55:55.699  6680  6680 D AndroidRuntime: Shutting down VM
08-24 16:55:55.756  1974  2894 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-24 16:55:55.756  1974  2894 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3ffed055 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-24 16:55:55.757  1974  1989 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-24 16:55:55.757  1974  1989 D SplitWindowPolicy: topRunningActivity=ActivityInfo{19b6ca6a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-24 16:55:55.828  6695  6695 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-24 16:55:55.910  6695  6695 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-24 16:55:55.926  6695  6695 I LibraryLoader: Loading: webviewchromium
,08-24 16:55:55.930  6695  6695 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9017-9021)
08-24 16:55:55.930  6695  6695 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 16:55:55.952  6695  6695 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bc181cb}
,08-24 16:55:55.953  6695  6695 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-24 16:55:55.954  6695  6695 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 16:55:55.964  6695  6695 I BrowserStartupController: Initializing chromium process, renderers=0
08-24 16:55:55.965  6695  6695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 16:55:55.991  6695  6695 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-24 16:55:55.991  6695  6695 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-24 16:55:55.992  6695  6695 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-24 16:55:55.996   318   318 V AudioPolicyService: registerClient() client 0xb558a360, uid 10118
08-24 16:55:56.009  1034  1096 D BluetoothManagerService: Message: 20
,08-24 16:55:56.010  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ef215d4:true
08-24 16:55:56.025  6695  6695 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 16:55:56.025  6695  6695 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 16:55:56.025  6695  6695 I Adreno-EGL: Build Date: 12/12/14 금
08-24 16:55:56.025  6695  6695 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 16:55:56.025  6695  6695 I Adreno-EGL: Remote Branch: 
08-24 16:55:56.025  6695  6695 I Adreno-EGL: Local Patches: 
08-24 16:55:56.025  6695  6695 I Adreno-EGL: Reconstruct Branch: 
,08-24 16:55:56.125  6695  6740 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-24 16:55:56.128  6695  6695 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-24 16:55:56.164  6695  6695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 16:55:56.169  6695  6695 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-24 16:55:56.172  6695  6695 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-24 16:55:56.175  6695  6695 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-24 16:55:56.175  6695  6695 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-24 16:55:56.189  6695  6695 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-24 16:55:56.197  6695  6695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 16:55:56.197  6695  6695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 16:55:56.226  6695  6756 D OpenGLRenderer: Render dirty regions requested: true
08-24 16:55:56.226  6695  6756 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 16:55:56.232  6695  6756 D OpenGLRenderer: Enabling debug mode 0
,08-24 16:55:56.256  1034  1092 W ActivityManager: Activity pause timeout for ActivityRecord{2914f94b u0 com.test.thalitest/.MainActivity t6}
,08-24 16:55:56.257  6695  6695 D Atlas   : Validating map...
08-24 16:55:56.265  1034  1941 D SplitWindow: check instance of lgWin Window{195c386e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 16:55:56.317  6695  6754 D LgDataFeature: LgDataFeature() Constructor: none
,08-24 16:55:56.317  6695  6754 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 16:55:56.399  1034  1097 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +644ms (total +731ms)
08-24 16:55:56.401  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2914f94b u0 com.test.thalitest/.MainActivity t6} time:189493
,08-24 16:55:56.409  6695  6695 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b044f16 time:189501
08-24 16:55:56.512  6695  6695 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-24 16:55:56.512  6695  6695 I chromium: 
,08-24 16:55:56.563  6695  6695 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 16:55:56.627  6695  6754 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-24 16:55:56.627  6695  6754 I chromium: 
,08-24 16:55:56.784  6695  6768 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435161600
,08-24 16:55:56.798  6695  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 16:55:56.798  6695  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 16:55:56.798  6695  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 16:55:56.798  6695  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 16:55:56.798  6695  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 16:55:56.799  6695  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35b607fa added. We now have 1 listener(s)
08-24 16:55:56.805  1034  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:55:56.807  6695  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-24 16:55:56.809  6695  6768 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 16:55:56.810  6695  6768 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 16:55:56.811  6695  6768 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:55:56.819  6695  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 16:55:56.819  6695  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 16:55:56.819  6695  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 16:55:56.819  6695  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-24 16:55:56.819  6695  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 16:55:56.819  6695  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 16:55:56.819  6695  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 16:55:56.819  6695  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 16:55:56.819  6695  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 16:55:56.819  6695  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 16:55:56.819  6695  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 16:55:56.819  6695  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 16:55:56.819  6695  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 16:55:56.819  6695  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 16:55:56.819  6695  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33a563a1 added. We now have 1 listener(s)
08-24 16:55:56.819  6695  6768 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:55:56.824  1034  1545 D WifiService: New client listening to asynchronous messages
,08-24 16:55:56.827  6695  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 16:55:56.827  6695  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 16:55:56.828  6695  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 16:55:56.828  6695  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 16:55:56.828  6695  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-24 16:55:56.832  6695  6768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:55:56.832  1034  1967 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:55:56.833  6695  6768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-24 16:55:56.845  6695  6768 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-24 16:55:56.846  6695  6768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:55:56.846  6695  6768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:55:56.846  6695  6768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:55:56.846  6695  6768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:55:56.846  6695  6768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:55:56.846  6695  6768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:55:56.846  6695  6768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:55:56.846  6695  6768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:55:56.846  6695  6768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 16:55:56.846  6695  6768 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 16:55:56.848  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:55:56.851  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:55:56.851  6695  6768 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 16:55:56.889  6695  6695 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 16:55:57.646   334   351 E GBMv2   : DFP En is all cleared set to be enabled
,08-24 16:55:57.647   334   351 E GBMv2   : Set value is all cleared set the max
08-24 16:55:57.647   334   351 I GBMv2   : DFP Enabled. Ignore VFP set
08-24 16:55:57.937  6695  6771 W jxcore-log: Initializing JXcore engine
08-24 16:55:57.937  6695  6771 W jxcore-log: JXcore engine is ready
,08-24 16:55:57.975  6771  6771 W Thread-766: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10343]" dev="sockfs" ino=10343 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-24 16:55:57.975  6771  6771 W Thread-766: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3271 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-24 16:55:57.975  6771  6771 W Thread-766: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10478]" dev="sockfs" ino=10478 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-24 16:55:57.975  6771  6771 W Thread-766: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-24 16:55:57.975  6771  6771 W Thread-766: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32166]" dev="sockfs" ino=32166 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-24 16:55:57.996  6695  6771 W jxcore-log: Starting JXcore engine
,08-24 16:55:58.076  6695  6771 W jxcore-log: Platform android
08-24 16:55:58.076  6695  6771 W jxcore-log: 
08-24 16:55:58.076  6695  6771 W jxcore-log: Process ARCH arm
08-24 16:55:58.076  6695  6771 W jxcore-log: 
,08-24 16:55:58.260  6695  6771 I jxcore-log: JXcore Cordova bridge is ready!
08-24 16:55:58.260  6695  6771 I jxcore-log: 
08-24 16:55:58.260  6695  6771 W jxcore-log: JXcore engine is started
,08-24 16:55:58.271  6695  6768 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-24 16:55:58.276  6695  6695 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 16:56:00.053  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 16:56:00.053  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 16:56:00.053  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 16:56:00.054  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
08-24 16:56:00.060  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 16:56:00.060  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 16:56:00.062  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 16:56:00.064  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 16:56:07.629  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 16:56:07.629  6695  6771 I jxcore-log: 
,08-24 16:56:07.632  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 16:56:07.632  6695  6771 I jxcore-log: 
08-24 16:56:07.637  6695  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:56:07.637  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:07.637  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:07.637  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:07.637  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:07.637  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:07.637  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:56:07.637  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:56:07.640  6695  6771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:07.643  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 16:56:07.643  6695  6771 I jxcore-log: 
,08-24 16:56:07.644  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 16:56:07.644  6695  6771 I jxcore-log: 
08-24 16:56:08.149  6695  6771 D executeNativeTests: Running unit tests
,08-24 16:56:08.231  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 16:56:08.231  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a added. We now have 2 listener(s)
,08-24 16:56:08.231  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:08.233  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 16:56:08.233  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 16:56:08.233  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:56:08.233  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:08.233  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb added. We now have 2 listener(s)
08-24 16:56:08.234  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:08.234  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 16:56:08.237  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:08.240  6695  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:56:08.240  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:08.240  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:08.240  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:08.240  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:08.240  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:08.240  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:56:08.240  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:56:08.241  6695  6771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:08.241  6695  6771 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 16:56:08.243  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:08.244  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:08.249  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 16:56:08.250  6695  6771 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 16:56:08.250  6695  6771 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 16:56:08.251  6695  6771 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-24 16:56:08.254  6695  6771 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 16:56:08.254  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 16:56:08.254  6695  6771 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-24 16:56:08.254  6695  6771 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 16:56:08.256  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.257  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.257  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.257  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.257  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.257  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:56:08.258  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:56:08.258  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a removed from the list
08-24 16:56:08.258  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.258  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb removed from the list
08-24 16:56:08.258  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.258  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.259  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.259  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.259  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.259  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.259  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.259  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
,08-24 16:56:08.262  6695  6771 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-24 16:56:08.262  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,08-24 16:56:08.263  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.263  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.264  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.264  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.264  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.264  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.264  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.264  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.265  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.265  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.265  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.265  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.265  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.266  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.266  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.266  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:56:08.266  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.270  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-24 16:56:08.270  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 16:56:08.270  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-24 16:56:08.270  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 16:56:08.270  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-24 16:56:08.270  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 16:56:08.270  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-24 16:56:08.270  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 16:56:08.270  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710],
08-24 16:56:08.270  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 16:56:08.270  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910],
08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410],
08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710],
08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 16:56:08.271  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 16:56:08.271  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.271  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.271  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.272  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 16:56:08.272  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.272  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.272  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.272  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.272  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.272  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.272  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-24 16:56:08.272  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.272  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.272  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.273  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.273  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.273  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.273  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list,
08-24 16:56:08.274  6695  6771 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 16:56:08.276  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:08.278  6695  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:56:08.278  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:08.278  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:08.278  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:08.278  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:08.278  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:08.278  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:56:08.278  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:56:08.279  6695  6771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:08.279  6695  6771 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 16:56:08.280  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-24 16:56:08.281  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:08.281  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-24 16:56:08.281  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 16:56:08.281  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 16:56:08.281  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:08.281  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 16:56:08.284  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 16:56:08.284  1034  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
08-24 16:56:08.287  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 16:56:08.291  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 16:56:08.293  6695  6771 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-24 16:56:08.294  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 16:56:08.294  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:56:08.295  6695  6771 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 16:56:08.295  6695  6771 I io.jxcore.node.ConnectionHelper: start: OK,
08-24 16:56:08.298  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.298  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.298  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.298  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.299  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.299  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 16:56:08.299  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.299  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.299  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.299  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.299  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.299  6695  6771 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-24 16:56:08.300  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:08.302  6695  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:56:08.302  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:08.302  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:08.302  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:08.302  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:08.302  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:08.302  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:56:08.302  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:56:08.304  6695  6771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:08.304  6695  6771 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 16:56:08.305  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:08.306  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:08.306  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 16:56:08.306  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 16:56:08.306  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 16:56:08.306  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:08.306  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 16:56:08.309  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 16:56:08.309  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:56:08.310  6695  6771 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 16:56:08.310  6695  6771 I io.jxcore.node.ConnectionHelper: start: OK
08-24 16:56:08.311  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.311  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.311  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.311  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.311  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.311  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:56:08.311  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.311  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.311  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.311  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.311  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.311  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.311  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.312  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.312  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.313  6695  6771 D BluetoothLeScann,er: could not find callback wrapper
08-24 16:56:08.313  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:56:08.313  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.313  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.313  6695  6771 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 16:56:08.315  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:08.317  6695  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:56:08.317  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:08.317  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:08.317  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:08.317  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:08.317  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:08.317  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:56:08.317  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:56:08.317  6695  6771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:08.318  6695  6771 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 16:56:08.318  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 16:56:08.318  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 16:56:08.319  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 16:56:08.319  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:08.319  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 16:56:08.320  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:08.321  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:08.322  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 16:56:08.322  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:56:08.323  6695  6771 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 16:56:08.323  6695  6771 I io.jxcore.node.ConnectionHelper: start: OK
08-24 16:56:08.323  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.323  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.323  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.324  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.324  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.324  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.324  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.324  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.324  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:56:08.324  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.324  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.324  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.324  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.324  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.324  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.324  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.325  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.325  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.325  6695  6771 D BluetoothLeScanner: could not find callback wrapper
08-24 16:56:08.325  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:56:08.325  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.325  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.325  6695  6771 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-24 16:56:08.326  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.326  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.326  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.326  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.326  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.326  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.326  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.326  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.326  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.326  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.326  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.326  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.326  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.326  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.327  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.327  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.327  6695  6771 D BluetoothLeScanner: could not find callback wrapper
08-24 16:56:08.327  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:56:08.327  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.327  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.328  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 16:56:08.328  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.328  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.328  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.328  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.328  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.328  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.329  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.329  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.329  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.329  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.329  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.329  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.329  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.329  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.330  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.330  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.331  6695  6771 D BluetoothLeScanner: could not find callback wrapper
08-24 16:56:08.331  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:56:08.331  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.331  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.331  6695  6771 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-24 16:56:08.332  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.332  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.332  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.332  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.332  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.332  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.332  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.332  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.332  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.332  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.332  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.332  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.332  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.332  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.333  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.333  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.333  6695  6771 D BluetoothLeScanner: could not find callback wrapper
08-24 16:56:08.333  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:56:08.333  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.333  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.334  6695  6771 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-24 16:56:08.334  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.334  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.334  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.334  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.334  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.334  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.334  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.334  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.334  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.334  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.334  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.334  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.334  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.334  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.335  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.335  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.335  6695  6771 D BluetoothLeScanner: could not find callback wrapper
08-24 16:56:08.336  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:56:08.336  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.336  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.336  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 16:56:08.337  6695  6771 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 16:56:08.337  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 16:56:08.337  6695  6771 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 16:56:08.337  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 16:56:08.337  6695  6771 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 16:56:08.337  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.337  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.337  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.338  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.338  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.338  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.338  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.338  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.338  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.338  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.338  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.338  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.338  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.338  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.339  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.339  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.339  6695  6771 D BluetoothLeScanner: could not find callback wrapper
08-24 16:56:08.339  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:56:08.339  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.339  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.340  6695  6771 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 16:56:08.340  6695  6771 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 16:56:08.340  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 16:56:08.341  6695  6771 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 16:56:08.342  6695  6771 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-24 16:56:08.342  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 16:56:08.342  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 16:56:08.342  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 16:56:08.342  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-24 16:56:08.342  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 16:56:08.343  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 16:56:08.343  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 16:56:08.344  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 16:56:08.345  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 16:56:08.346  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 16:56:08.346  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 16:56:08.346  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 16:56:08.346  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 16:56:08.346  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 16:56:08.346  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 16:56:08.346  6695  6771 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-24 16:56:08.346  6695  6771 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 16:56:08.346  6695  6771 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-24 16:56:08.346  6695  6771 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 16:56:08.346  6695  6771 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 16:56:08.346  6695  6771 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-24 16:56:08.346  6695  6771 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 16:56:08.346  6695  6771 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 16:56:08.346  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-24 16:56:08.351  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-24 16:56:08.353  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-24 16:56:08.353  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-24 16:56:08.354  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-24 16:56:08.354  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-24 16:56:08.354  6695  6771 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-24 16:56:08.354  6695  6771 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 16:56:08.354  6695  6771 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-24 16:56:08.355  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.355  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.355  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.355  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.355  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.355  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.355  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-24 16:56:08.355  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.355  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.356  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.356  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.356  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.356  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.356  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.356  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.357  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.357  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.357  6695  6771 D BluetoothLeScanner: could not find callback wrapper
08-24 16:56:08.357  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:56:08.357  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.357  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.360  6695  6771 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-24 16:56:08.360  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.361  6695  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 830
08-24 16:56:08.361  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.361  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.361  6695  6777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 830)
08-24 16:56:08.362  6695  6777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 830)
08-24 16:56:08.362  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.362  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.362  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.362  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.362  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.362  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.362  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.362  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.362  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.362  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.362  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.363  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.363  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.364  6695  6771 D BluetoothLeScanner: could not find callback wrapper
08-24 16:56:08.364  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:56:08.364  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.364  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.364  6695  6771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-24 16:56:08.365  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.365  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.365  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.365  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.365  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.365  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.365  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.365  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.365  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.365  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.365  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.365  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.365  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.365  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.367  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.367  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.368  6695  6771 D BluetoothLeScanner: could not find callback wrapper
08-24 16:56:08.368  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:56:08.368  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.368  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.368  6695  6771 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-24 16:56:08.368  6695  6771 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-24 16:56:08.368  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 16:56:08.369  6695  6771 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-24 16:56:08.369  6695  6771 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 16:56:08.369  6695  6771 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-24 16:56:08.369  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 16:56:08.369  6695  6771 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-24 16:56:08.369  6695  6771 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 16:56:08.369  6695  6771 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 16:56:08.369  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 16:56:08.369  6695  6771 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-24 16:56:08.369  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.369  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.369  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.369  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.369  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.369  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.369  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.369  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.369  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.369  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.369  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.369  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.369  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.369  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.371  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.371  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.371  6695  6771 D BluetoothLeScanner: could not find callback wrapper
08-24 16:56:08.371  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:56:08.371  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.371  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.373  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.373  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.373  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.373  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.373  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.373  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.373  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.373  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.373  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.373  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.373  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.373  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.373  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.373  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.373  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.373  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.373  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.373  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.373  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.374  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.374  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.374  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.374  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.374  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.374  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.374  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.374  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.374  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.375  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.376  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.376  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.376  6695  6771 D BluetoothLeScanner: could not find callback wrapper
08-24 16:56:08.376  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:56:08.376  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.376  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.377  6695  6771 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-24 16:56:08.377  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:08.378  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-24 16:56:08.378  6695  6771 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-24 16:56:08.378  6695  6771 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-24 16:56:08.379  6695  6695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-24 16:56:08.379  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-24 16:56:08.379  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 16:56:08.380  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.380  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-24 16:56:08.380  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-24 16:56:08.380  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-24 16:56:08.380  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.380  6695  6771 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-24 16:56:08.380  6695  6695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-24 16:56:08.380  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.380  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.381  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 16:56:08.381  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:08.381  6695  6771 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 16:56:08.381  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 16:56:08.381  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 16:56:08.382  6695  6771 D BluetoothLeScanner: could not find callback wrapper
08-24 16:56:08.382  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:56:08.382  6695  6784 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 16:56:08.382  6695  6771 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 16:56:08.382  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.382  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.382  3875  3895 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-24 16:56:08.383  6695  6784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-24 16:56:08.383  6695  6784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-24 16:56:08.383  6695  6771 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 16:56:08.383  6695  6784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-24 16:56:08.384  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 16:56:08.384  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.384  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 16:56:08.384  6695  6695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-24 16:56:08.384  6695  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 16:56:08.384  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.384  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.384  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.384  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.384  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.384  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.384  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.384  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.385  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.385  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.385  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.385  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.385  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.385  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.386  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.386  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.386  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.386  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.387  6695  6771 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-24 16:56:08.387  6695  6771 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 16:56:08.387  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-24 16:56:08.388  6695  6771 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 16:56:08.388  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.389  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.389  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.389  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.389  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.389  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.389  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.389  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.390  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.390  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.390  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.391  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.391  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.391  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.391  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.391  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.391  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.391  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.392  1034  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:08.393  1034  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:08.393  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:08.393  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.393  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.393  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.394  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.394  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.394  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.394  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.394  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.394  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.394  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.394  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.394  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.394  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.394  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.395  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.395  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.395  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.395  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.396  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:08.396  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:08.396  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:08.396  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:08.396  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.396  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.396  6695  6771 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dfec4a not in the list
08-24 16:56:08.396  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.396  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.396  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:08.396  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.396  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.396  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:08.396  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:08.397  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:08.397  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:08.397  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:08.397  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9257bb not in the list
08-24 16:56:08.398  6695  6771 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-24 16:56:08.398  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 16:56:08.398  6695  6771 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-24 16:56:08.398  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 16:56:08.398  6695  6771 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-24 16:56:08.398  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 16:56:08.400  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 16:56:08.400  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-24 16:56:08.400  6695  6771 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-24 16:56:08.400  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 16:56:08.400  6695  6771 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-24 16:56:08.400  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 16:56:08.400  6695  6771 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-24 16:56:08.400  6695  6771 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-24 16:56:08.401  6695  6771 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-24 16:56:08.401  6695  6771 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-24 16:56:08.401  6695  6771 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-24 16:56:08.401  6695  6771 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-24 16:56:08.402  6695  6771 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-24 16:56:08.402  6695  6771 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-24 16:56:08.402  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:08.402  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e8b16f0 added. We now have 2 listener(s)
08-24 16:56:08.402  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:08.404  6695  6771 D BluetoothAdapter: enable(): BT is already enabled..!
08-24 16:56:08.405  1034  1920 D WifiServiceImplEx: setWifiEnabled: true pid=6695, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 16:56:08.406  1034  1920 D WifiService: setWifiEnabled: true pid=6695, uid=10118
08-24 16:56:08.406  1034  1920 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 16:56:08.407  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:08.408  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fd61469 added. We now have 3 listener(s)
08-24 16:56:08.408  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:08.411  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:08.411  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a94deee added. We now have 4 listener(s)
08-24 16:56:08.411  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:08.412  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:08.412  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17639f8f added. We now have 5 listener(s)
08-24 16:56:08.412  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:08.414  1034  1603 D WifiServiceImplEx: setWifiEnabled: false pid=6695, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 16:56:08.414  1034  1603 D WifiService: setWifiEnabled: false pid=6695, uid=10118
08-24 16:56:08.414  1034  1603 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 16:56:08.423  1034  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:08.423  1034  1991 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@6e8ac9 mBinding = false
08-24 16:56:08.425  1034  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-24 16:56:08.425  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-24 16:56:08.425  1034  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-24 16:56:08.425  1034  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-24 16:56:08.425  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-24 16:56:08.425  1034  1540 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-24 16:56:08.426  1034  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 16:56:08.426  1034  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 16:56:08.426  1034  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 16:56:08.426  1034  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 16:56:08.432  1034  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 16:56:08.432  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-24 16:56:08.432  2638  2638 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 16:56:08.432  1034  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.432  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.432  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 16:56:08.432  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
,08-24 16:56:08.433  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
08-24 16:56:08.433  1034  2809 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.434  1034  1096 D BluetoothManagerService: Message: 2
08-24 16:56:08.435  1034  1096 D BluetoothManagerService: Sending off request.
08-24 16:56:08.435  3875  3895 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-24 16:56:08.436   312   908 D CommandListener: Clearing all IP addresses on wlan0
,08-24 16:56:08.438  3875  3947 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-24 16:56:08.438  3875  3947 D BluetoothAdapterProperties: Setting state to 13
08-24 16:56:08.438  3875  3947 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 16:56:08.439  3875  3947 D BluetoothAdapterProperties: onBluetoothDisable()
08-24 16:56:08.439  3875  3947 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-24 16:56:08.439  3875  3951 D BluetoothAdapterProperties: Scan Mode:20
08-24 16:56:08.440  3875  3947 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-24 16:56:08.441  3875  4212 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-24 16:56:08.441  3875  4212 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 16:56:08.441  3875  4212 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-24 16:56:08.441  3875  4212 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-24 16:56:08.441  3875  4212 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-24 16:56:08.441  3875  4212 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-24 16:56:08.441  3875  4212 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-24 16:56:08.441  3875  4212 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-24 16:56:08.441  3875  4215 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 16:56:08.441  3875  4247 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 16:56:08.441  3875  4260 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 16:56:08.442  3875  4269 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 16:56:08.442  3875  3947 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 16:56:08.444  1034  1096 D BluetoothManagerService: Message: 60
08-24 16:56:08.444  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-24 16:56:08.444  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 16:56:08.444  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 16:56:08.444  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-24 16:56:08.445  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-24 16:56:08.450  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:08.450  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:08.450  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:08.450  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:08.450  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:08.450  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false,
08-24 16:56:08.450  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:08.450  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:56:08.450  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:56:08.456  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:08.456  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:08.473  1034  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-24 16:56:08.473  1034  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-24 16:56:08.477  1034  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6789 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-24 16:56:08.478  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:08.482  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:08.482  6695  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:56:08.482  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:08.482  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:08.482  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:08.482  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:56:08.482  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:08.482  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:08.482  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:56:08.483  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.483  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.483  1034  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@33ecef61
08-24 16:56:08.484  1034  1538 D LGWifiP2pService: P2pDisablingState
,08-24 16:56:08.484  1034  1538 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.484  1034  1538 D LGWifiP2pService: p2p socket connection lost
08-24 16:56:08.484  1034  1538 D LGWifiP2pService: P2pDisabledState
08-24 16:56:08.485  1034  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:08.485  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:08.486  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:08.486  1034  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:08.486  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:08.487  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:08.487  1034  1540 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 16:56:08.491  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:08.491  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:08.494  1974  1974 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-24 16:56:08.496  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:08.498  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:08.498  6695  6771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:56:08.498  6695  6771 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 16:56:08.500  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:08.502  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:08.503  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-24 16:56:08.503  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:08.503  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:08.503  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 16:56:08.508  1974  1974 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 16:56:08.508  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-24 16:56:08.508  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:08.508  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:08.508  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 16:56:08.508  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-24 16:56:08.509  1974  1974 D WfdsService: WifiP2pState is changed : false
08-24 16:56:08.509  1974  2298 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-24 16:56:08.509  1034  1558 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.509  1974  2298 D WfdsService: Set the WFDS Monitor: false
08-24 16:56:08.509  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-24 16:56:08.509  1034  1559 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.510  1974  2298 D WfdsMonitor: WFDS Monitor is stopped
,08-24 16:56:08.510  1974  2298 D WfdsService: STATE : WfdsDisabledState - enter
08-24 16:56:08.510  1974  2299 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-24 16:56:08.510  1974  2720 D CtrlSupplicant: Received on exit socket, terminate
08-24 16:56:08.510  1974  2720 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-24 16:56:08.510  1974  2720 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-24 16:56:08.510  1974  2720 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-24 16:56:08.510  1974  2298 W WfdsService: DefaultState - msg [9445378] is not handled
08-24 16:56:08.512  1974  1974 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:08.519  1034  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-24 16:56:08.519  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 16:56:08.519  2638  2638 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 16:56:08.519  1034  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.519  1034  1538 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.520  3875  3875 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:08.520  3875  3875 D BluetoothMapService: STATE_TURNING_OFF
08-24 16:56:08.520  3875  3875 V BtOppService: Receiver DISABLED_ACTION 
08-24 16:56:08.520  3875  3875 V BluetoothMapService: Handler(): got msg=4
08-24 16:56:08.521  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 16:56:08.521  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 16:56:08.521  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
08-24 16:56:08.521  3875  3875 D BluetoothMapService: MAP Service closeService in
08-24 16:56:08.522  3875  3875 D BluetoothMapMasInstance: MAP Service shutdown
08-24 16:56:08.522  3875  3875 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 16:56:08.522  3875  3875 V BluetoothMapService: MAP Service closeService out
08-24 16:56:08.522  3875  3875 I BtOppRfcommListener: stopping Accept Thread
08-24 16:56:08.522  3875  3875 V BtOppRfcommListener: close mBtServerSocket
08-24 16:56:08.522  3875  3875 V BtOppRfcommListener: waiting for thread to terminate
08-24 16:56:08.523  3875  4247 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 16:56:08.523  3875  3875 V BtOppRfcommListener: done waiting for thread to terminate
08-24 16:56:08.524  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:08.524  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-24 16:56:08.530  1034  2038 I art     : Explicit concurrent mark sweep GC freed 38618(1894KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.279ms total 86.253ms
08-24 16:56:08.532  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
,08-24 16:56:08.532  3875  4054 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-24 16:56:08.533  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 16:56:08.533  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 16:56:08.533  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 16:56:08.533  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 16:56:08.533  3875  4054 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 16:56:08.533  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 16:56:08.533  3875  4054 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 16:56:08.533  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 16:56:08.533  3875  4054 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 16:56:08.533  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-24 16:56:08.533  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-24 16:56:08.533  3875  4054 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 16:56:08.546   312   908 D CommandListener: Clearing all IP addresses on wlan0
08-24 16:56:08.547  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:08.547  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:08.547  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:08.547  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:08.547  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:08.547  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:56:08.547  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:08.547  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:08.547  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:56:08.547  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:08.547  1034  1546 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
,08-24 16:56:08.547  1034  1546 D DSQN    : disableDataServiceNotify
08-24 16:56:08.547  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:56:08.548  1034  1546 D DSQN    : stop dsqn bin
08-24 16:56:08.549  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:08.549  1034  1049 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-24 16:56:08.549  1034  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.549  1034  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.549  1034  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-24 16:56:08.549  1034  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.550  1034  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-24 16:56:08.551  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:08.552  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 16:56:08.556  1034  1546 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-24 16:56:08.556  1034  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:08.556  1034  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:08.556  1034  1546 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:08.556  1034  1546 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-24 16:56:08.557  1034  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6810 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-24 16:56:08.557  1034  1546 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-24 16:56:08.557  1034  1546 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-24 16:56:08.557  1034  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 16:56:08.557  1605  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-24 16:56:08.561  1034  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:08.562  1034  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMM,EDIATE
,08-24 16:56:08.563  1034  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:08.563  1034  1546 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:08.563  1034  1546 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:08.564  1034  1546 D NetworkManagementService: Removing idletimer
08-24 16:56:08.564  1034  1546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:08.564  1876  1876 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:08.564  1876  1876 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 16:56:08.566  3875  3875 V BtOppService: onDestroy
08-24 16:56:08.567  1034  1540 D WifiNative-p2p0: doBoolean: TERMINATE
08-24 16:56:08.567  1034  1540 D WifiNative-p2p0: TERMINATE: returned true
08-24 16:56:08.567  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 16:56:08.567  1034  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 16:56:08.567  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 16:56:08.568  1034  1540 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:08.568  1034  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 16:56:08.568   312  6821 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-24 16:56:08.569  3875  3875 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-24 16:56:08.569  1034  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-24 16:56:08.569  1034  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-13ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.569  1034  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-13ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.569  1034  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-24 16:56:08.570  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-24 16:56:08.570  1034  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 16:56:08.570  1034  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 16:56:08.572  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-24 16:56:08.572  1974  1974 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-24 16:56:08.572  1034  1546 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-24 16:56:08.575  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-24 16:56:08.575  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-24 16:56:08.575  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:08.575  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:08.575  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_,STATE_CHANGED_ACTION [DISCONNECTED]
,08-24 16:56:08.579  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-24 16:56:08.579  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 16:56:08.579  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-24 16:56:08.579  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 16:56:08.579  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 16:56:08.579  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 16:56:08.579  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 16:56:08.579  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 16:56:08.579  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 16:56:08.585  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:08.586  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:08.586  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:08.586  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:08.586  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:56:08.586  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:56:08.586  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:08.586  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:08.586  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:56:08.586  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:08.586  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:56:08.587  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:08.587  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:08.587  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:08.587  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:08.587  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:56:08.587  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:56:08.587  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:08.587  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:08.587  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 16:56:08.588  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:08.588  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 16:56:08.618  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 16:56:08.619  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:08.620  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:08.623  6810  6810 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 16:56:08.623  6810  6810 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-24 16:56:08.623  6810  6810 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 16:56:08.623  6810  6810 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-24 16:56:08.624  6810  6810 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 16:56:08.625  6810  6810 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 16:56:08.632  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 16:56:08.632  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:08.633  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:08.633  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-24 16:56:08.633  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:08.634  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:08.646  1034  2809 D DhcpStateMachine: StoppedState
08-24 16:56:08.646  1034  2809 D DhcpStateMachine: StoppedState{ when=-125ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:08.647  1034  1540 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,08-24 16:56:08.647  1034  1540 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-24 16:56:08.648  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 16:56:08.665  6789  6789 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-24 16:56:08.665  6789  6789 W LG Account v2.2: No ProfileInfo entries
08-24 16:56:08.665  6789  6789 I LG Account v2.2: isEnabled: false
08-24 16:56:08.666  6789  6789 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-24 16:56:08.666  6789  6789 I Feature : [Lifetracker]Country: EU
08-24 16:56:08.666  6789  6789 I Feature : [Lifetracker]Operator: OPEN
08-24 16:56:08.666  6789  6789 I Feature : [Lifetracker]Ranking support: false
08-24 16:56:08.666  6789  6789 I Feature : [Lifetracker]Comfort support: false
08-24 16:56:08.666  6789  6789 I Feature : [Lifetracker]Accessory: true
08-24 16:56:08.666  6789  6789 I Feature : [Lifetracker]Health device: true
08-24 16:56:08.666  6789  6789 I Feature : [Lifetracker]Extra Pedometer: false
08-24 16:56:08.666  6789  6789 I Feature : [Lifetracker]Blood glucose device: false
08-24 16:56:08.666  6789  6789 I Feature : [Lifetracker]Device Number: 3
,08-24 16:56:08.674  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:08.688  2638  2638 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-24 16:56:08.689  2638  2638 I wpa_supplicant: monitor socket send errors count : 1
08-24 16:56:08.689  2638  2638 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1974-2\x00 that cannot receive messages
,08-24 16:56:08.690  1034  2689 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-24 16:56:08.690  1034  2689 D WifiMonitor: Dropping event because (p2p0) is stopped
08-24 16:56:08.706  1034  1992 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6833 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-24 16:56:08.707  1034  1992 I ActivityManager: Killing 6157:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-24 16:56:08.719  6810  6810 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-24 16:56:08.726  2638  2638 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-24 16:56:08.726  1034  2689 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-24 16:56:08.726  1034  2689 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 16:56:08.726  1034  2689 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 16:56:08.726  1034  2689 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-24 16:56:08.727  2638  2638 W wpa_supplicant: USIM:  scard_deinit function
08-24 16:56:08.727  1034  2689 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 16:56:08.727  1034  2689 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 16:56:08.727  1034  1540 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=201806
08-24 16:56:08.727  1034  1540 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=201806
08-24 16:56:08.728  1034  1096 D Tethering: InitialState.processMessage what=4
08-24 16:56:08.728  1034  1540 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=201806  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-24 16:56:08.728  1034  1540 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=201807  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-24 16:56:08.741  1034  2010 W libprocessgroup: failed to open /acct/uid_10014/pid_6157/cgroup.procs: No such file or directory
,08-24 16:56:08.747  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 16:56:08.750  3875  3875 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 16:56:08.750  3875  3875 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:08.750  3875  3875 V BluetoothPbapReceiver: ***********state = 13
08-24 16:56:08.751  1034  1096 D BluetoothManagerService: Message: 20
08-24 16:56:08.751  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@67243e8:true
08-24 16:56:08.752  3875  3875 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-24 16:56:08.754  1034  1540 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
,08-24 16:56:08.755  1034  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-24 16:56:08.756  3875  3875 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:08.756  3875  3875 V BluetoothPbapService: state: 13
08-24 16:56:08.756  3875  3875 V BluetoothPbapService: Pbap Service closeService in
08-24 16:56:08.756  3875  3875 V BluetoothPbapService: successfully stopped pbap service
08-24 16:56:08.757  3875  3875 V BluetoothPbapService: Pbap Service closeService out
08-24 16:56:08.757  3875  3875 V BluetoothPbapService: Pbap Service onDestroy
08-24 16:56:08.757  3875  3875 V BluetoothPbapService: Pbap Service closeService in
,08-24 16:56:08.757  3875  3875 V BluetoothPbapService: Pbap Service closeService out
08-24 16:56:08.757  3875  3875 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-24 16:56:08.759  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 16:56:08.763  1034  1096 D BluetoothManagerService: Message: 30
08-24 16:56:08.770  1034  1096 D BluetoothManagerService: Message: 30
,08-24 16:56:08.773  6810  6810 D LocalBluetoothProfileManager: Adding local MAP profile
08-24 16:56:08.774  6810  6810 D BluetoothMap: Create BluetoothMap proxy object
08-24 16:56:08.775  1034  1096 D BluetoothManagerService: Message: 30
08-24 16:56:08.778  1034  1096 D BluetoothManagerService: Message: 30
08-24 16:56:08.779  6810  6810 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-24 16:56:08.780  6810  6810 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-24 16:56:08.791  6810  6810 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-24 16:56:08.794  6810  6810 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-24 16:56:08.799  2638  2638 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-24 16:56:08.799  1034  2689 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-24 16:56:08.800  1034  2689 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-24 16:56:08.800  1034  2689 D WifiMonitor: Disconnecting from the supplicant, no more events
08-24 16:56:08.802  1034  1540 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-24 16:56:08.802  6810  6810 D DockEventReceiver: finishStartingService: stopping service
,08-24 16:56:08.808  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 16:56:08.812  6810  6810 D BluetoothInputDevice: Proxy object connected
08-24 16:56:08.812  6810  6810 D HidProfile: Bluetooth service connected
08-24 16:56:08.813  6810  6810 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 16:56:08.814  6810  6810 D PanProfile: Bluetooth service connected
08-24 16:56:08.814  6810  6810 D BluetoothMap: Proxy object connected
08-24 16:56:08.815  6810  6810 D MapProfile: Bluetooth service connected
,08-24 16:56:08.815  6810  6810 D BluetoothMap: getConnectedDevices()
08-24 16:56:08.815  6810  6810 D BluetoothMap: Bluetooth is Not enabled
08-24 16:56:08.815  6810  6810 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-24 16:56:08.818  6810  6810 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-24 16:56:08.818  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 16:56:08.819  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 16:56:08.821  1034  1920 I ActivityManager: Killing 6275:com.android.defcontainer/u0a4 (adj 15): empty #17
08-24 16:56:08.849  1034  2033 W libprocessgroup: failed to open /acct/uid_10004/pid_6275/cgroup.procs: No such file or directory
,08-24 16:56:08.862  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:08.885  6695  6695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 16:56:08.904  1034  1540 D WifiOffDelayIfNotUsed: stopMonitoring
,08-24 16:56:08.904  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 16:56:08.904  1034  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 16:56:08.904  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 16:56:08.906  1974  1974 D WfdsService: Supplicant Connection state is changed : false
08-24 16:56:08.906  1974  2298 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-24 16:56:08.906  1974  2298 D WfdsService: Set the WFDS Monitor: false
08-24 16:56:08.906  1974  2298 D WfdsMonitor: WFDS Monitor is stopped
08-24 16:56:08.907  6810  6810 D LgDataFeature: LgDataFeature() Constructor: none
08-24 16:56:08.907  6810  6810 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 16:56:08.909  1974  1974 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 16:56:08.910  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:08.912  2468  2468 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:08.919  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-24 16:56:08.920  1034  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-24 16:56:08.920  1034  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,08-24 16:56:08.921  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:08.922  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:08.922  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:08.922  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:08.922  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:56:08.922  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:56:08.922  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:08.922  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:08.922  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:56:08.924  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:08.928  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:08.931  6810  6810 D BluetoothPermissionRequest: onReceive
08-24 16:56:08.937  6810  6810 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-24 16:56:08.945  1034  1992 I ActivityManager: Killing 6434:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-24 16:56:08.950  6810  6810 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 16:56:08.981  1034  1049 W libprocessgroup: failed to open /acct/uid_10008/pid_6434/cgroup.procs: No such file or directory
08-24 16:56:08.981  3875  3875 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-24 16:56:08.982  3875  3875 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-24 16:56:08.983  3875  3875 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-24 16:56:09.061  1034  2056 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6861 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-24 16:56:09.063  3875  3875 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:09.063  3875  3875 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-24 16:56:09.065  3875  3875 V BluetoothFtpService: Ftp Service onStartCommand
08-24 16:56:09.065  3875  3875 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:09.065  3875  3875 V BluetoothFtpService: Ftp Service closeService
08-24 16:56:09.065  3875  3875 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-24 16:56:09.069  3875  3875 V BluetoothFtpService: successfully stopped ftp service
08-24 16:56:09.069  3875  3875 V BluetoothFtpService: Ftp Service onDestroy
08-24 16:56:09.069  3875  3875 V BluetoothFtpService: Ftp Service closeService
08-24 16:56:09.074  3875  3875 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 16:56:09.074  3875  3875 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 16:56:09.074  3875  3875 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 16:56:09.074  3875  3875 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:09.074  3875  3875 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-24 16:56:09.074  3875  3875 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-24 16:56:09.078  3875  3875 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:09.078  3875  3875 V BluetoothSapService: state: 13
08-24 16:56:09.079  3875  3875 V BluetoothSapService: Stopping SAP server process
08-24 16:56:09.081  3875  3875 V BluetoothSapService: Sap Service closeSapService in
08-24 16:56:09.081  3875  3875 V BluetoothSapService: Close listen Socket : 
08-24 16:56:09.082  3875  3875 V BluetoothSapService: Close rfcomm Socket : 
08-24 16:56:09.082  3875  3875 V BluetoothSapService: Close sapd  Socket : 
08-24 16:56:09.131  1034  1050 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6881 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-24 16:56:09.133  3875  3875 V BluetoothSapService: Sap Service closeSapService out
08-24 16:56:09.135  3875  3875 V BluetoothSapService: Sap Service onDestroy
08-24 16:56:09.135  3875  3875 V BluetoothSapService: Sap Service closeSapService in
08-24 16:56:09.135  3875  3875 V BluetoothSapService: Close listen Socket : 
08-24 16:56:09.135  3875  3875 V BluetoothSapService: Close rfcomm Socket : 
08-24 16:56:09.135  3875  3875 V BluetoothSapService: Close sapd  Socket : 
08-24 16:56:09.139  3875  3875 V BluetoothSapService: Sap Service closeSapService out
08-24 16:56:09.152   338   338 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 21.466ms
,08-24 16:56:09.172   338   338 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 426us total 19.524ms
,08-24 16:56:09.176  6861  6861 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 16:56:09.190   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 17.338ms
,08-24 16:56:09.206  6861  6861 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-24 16:56:09.209  6881  6881 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 16:56:09.225  1034  2010 I ActivityManager: Killing 5942:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-24 16:56:09.247  6861  6861 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-24 16:56:09.247  6861  6861 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-24 16:56:09.247  6861  6861 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-24 16:56:09.248  6861  6861 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-24 16:56:09.248  6861  6861 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-24 16:56:09.250  6861  6861 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-24 16:56:09.255  6861  6861 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-24 16:56:09.270  1034  1992 W libprocessgroup: failed to open /acct/uid_10011/pid_5942/cgroup.procs: No such file or directory
,08-24 16:56:09.278  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:09.282  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 16:56:09.313  6861  6861 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-24 16:56:09.318  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 16:56:09.320  6861  6861 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-24 16:56:09.323  6861  6861 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-24 16:56:09.326  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 16:56:09.326  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 16:56:09.326  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 16:56:09.334  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:09.346  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:09.354  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 16:56:09.354  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:09.356  6861  6861 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 16:56:09.362  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:09.368  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 16:56:09.369  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 16:56:09.369  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 16:56:09.375  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:09.385  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 16:56:09.399  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:09.399  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 16:56:09.403  6861  6861 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 16:56:09.484  1034  1967 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6907 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-24 16:56:09.535  3875  4054 W bt-btif : ag scb idx 1 not allocated
08-24 16:56:09.535  3875  4054 E bt-btif : BTA AG is already disabled, ignoring ...
08-24 16:56:09.535  3875  3951 D bt_hci_bdroid: cleanup
,08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 16:56:09.535  3875  4056 I bt_lpm  : LPM is already off!!!
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 16:56:09.535  3875  4054 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 16:56:09.535  3875  4203 I bt_userial_mct: exiting userial_read_thread
08-24 16:56:09.535  3875  4203 D bt_userial_mct: Leaving userial_evt_read_thread()
08-24 16:56:09.536  3875  4054 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 16:56:09.536  3875  3951 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-24 16:56:09.536  3875  4056 I bt_vendor: hw_epilog_process
08-24 16:56:09.536  3875  3951 D bt_hci_bdroid: cleanup Finalizing cleanup
08-24 16:56:09.536  3875  3951 D bt_userial_mct: userial_close
08-24 16:56:09.536  3875  3951 E bt_userial_mct: pthread_join() FAILED result:3
08-24 16:56:09.536  3875  3951 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-24 16:56:09.587  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 16:56:09.595  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 16:56:09.596  3875  3951 D bt_hci_bdroid: set_power 0
08-24 16:56:09.596  3875  3951 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-24 16:56:09.596  3875  3951 I bt_vendor: bluetooth satus is on
08-24 16:56:09.596  3875  3951 I bt_vendor: bt-vendor : resetting BT status
08-24 16:56:09.596  3875  3951 I bt_vendor: Starting hciattach daemon
08-24 16:56:09.596  3875  3951 I bt_vendor: try to set false
08-24 16:56:09.598  3875  3951 I bt_vendor: Starting hciattach daemon
08-24 16:56:09.598  3875  3951 I bt_vendor: try to set false
08-24 16:56:09.598  3875  3951 I bt_vendor: cleanup
,08-24 16:56:09.600  3875  4054 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-24 16:56:09.601  3875  3951 I GKI_LINUX: GKI_exit_task 0 done
08-24 16:56:09.601  3875  3951 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-24 16:56:09.604  3875  3947 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-24 16:56:09.609  3875  3875 D HeadsetService: Received stop request...Stopping profile...
08-24 16:56:09.610  3875  3875 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-24 16:56:09.611  3875  3875 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 16:56:09.611  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f24da8
08-24 16:56:09.611  3875  3982 D HeadsetStateMachine: Exit Disconnected: -1
,08-24 16:56:09.612  1876  1876 D BluetoothHeadset: Proxy object disconnected
08-24 16:56:09.613  1876  1876 D BluetoothHeadset: Proxy object disconnected
08-24 16:56:09.614  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-24 16:56:09.614  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-24 16:56:09.614  1876  1876 D BluetoothHeadset: Proxy object disconnected
08-24 16:56:09.616  3875  3875 D A2dpService: Received stop request...Stopping profile...
08-24 16:56:09.616  3875  4016 D A2dpStateMachine: Exit Disconnected: -1
08-24 16:56:09.618  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-24 16:56:09.620  3875  3875 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-24 16:56:09.620  3875  3875 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 16:56:09.620  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f24da8
08-24 16:56:09.620  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:09.622  3875  3947 D BluetoothAdapterState: Stopping profile services that were post enabled
08-24 16:56:09.627  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-24 16:56:09.627  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-24 16:56:09.637  3875  3875 D HidService: Received stop request...Stopping profile...
08-24 16:56:09.637  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f24da8
08-24 16:56:09.638  6810  6810 D BluetoothInputDevice: Proxy object disconnected
08-24 16:56:09.639  6810  6810 D HidProfile: Bluetooth service disconnected
08-24 16:56:09.639  3875  3875 D HeadsetStateMachine: Unbinding service...
08-24 16:56:09.640  3875  3875 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 16:56:09.640  3875  3875 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 16:56:09.640  3875  3875 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 16:56:09.640  3875  3875 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 16:56:09.640  3875  3875 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-24 16:56:09.640  3875  3875 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 16:56:09.640  3875  3875 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-24 16:56:09.641  3875  3875 D HealthService: Received stop request...Stopping profile...
08-24 16:56:09.641  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f24da8
,08-24 16:56:09.644  3875  3875 D PanService: Received stop request...Stopping profile...
08-24 16:56:09.645  6907  6930 W FormManager: Network not available. Please check & try again.
08-24 16:56:09.646  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f24da8
08-24 16:56:09.650  3875  3875 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 16:56:09.651  3875  3875 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 16:56:09.651  3875  3875 D BtGatt.GattService: stop()
08-24 16:56:09.651  3875  3875 D BtGatt.AdvertiseManager: advertise clients cleared
08-24 16:56:09.652  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f24da8
08-24 16:56:09.653  3875  3875 D BluetoothMapService: Received stop request...Stopping profile...
08-24 16:56:09.653  3875  3875 D BluetoothMapService: stop()
08-24 16:56:09.654  3875  3875 D BluetoothMapEmailAppObserver: deinitObservers()
08-24 16:56:09.654  3875  3875 D BluetoothMapEmailAppObserver: removeReceiver()
,08-24 16:56:09.655  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f24da8
08-24 16:56:09.656  3875  3875 I BluetoothA2dpServiceJni: cleanupNative
08-24 16:56:09.656  3875  4018 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-24 16:56:09.656  3875  3875 I GKI_LINUX: GKI_exit_task 2 done
08-24 16:56:09.656  3875  3875 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-24 16:56:09.657  3875  3875 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 16:56:09.657  3875  3875 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 16:56:09.657  3875  3875 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 16:56:09.657  3875  3875 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 16:56:09.657  3875  3875 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 16:56:09.657  3875  3875 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 16:56:09.657  3875  3875 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 16:56:09.658  3875  3875 V BluetoothMapService: Handler(): got msg=4
08-24 16:56:09.658  3875  3875 D BluetoothMapService: MAP Service closeService in
08-24 16:56:09.658  3875  3875 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 16:56:09.658  3875  3875 V BluetoothMapService: MAP Service closeService out
08-24 16:56:09.659  3875  3875 D BluetoothMapService: cleanup()
08-24 16:56:09.659  3875  3875 D BluetoothMapService: MAP Service closeService in
08-24 16:56:09.659  3875  3875 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 16:56:09.659  3875  3947 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-24 16:56:09.659  3875  3875 V BluetoothMapService: MAP Service closeService out
08-24 16:56:09.659  3875  3947 D BluetoothAdapterProperties: Setting state to 10
08-24 16:56:09.659  3875  3947 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-24 16:56:09.659  1034  1096 D BluetoothManagerService: Message: 60
08-24 16:56:09.659  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-24 16:56:09.659  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-24 16:56:09.659  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 16:56:09.660  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:56:09.660  3875  3947 I BluetoothAdapterState: Entering OffState
08-24 16:56:09.660  6810  6829 D BluetoothMap: onBluetoothStateChange: up=false
08-24 16:56:09.661  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 16:56:09.661  1876  1891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:56:09.661  6810  6810 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 16:56:09.661  6810  6828 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 16:56:09.662  6810  6810 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 16:56:09.662  1876  1892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:56:09.662  6810  6810 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 16:56:09.664  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 16:56:09.664  6810  6829 D BluetoothPan: onBluetoothStateChange on: false
08-24 16:56:09.664  1876  2566 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-24 16:56:09.666  6810  6828 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 16:56:09.667  6907  6931 V FormManager: Network unavailable.
08-24 16:56:09.667  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-24 16:56:09.668  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-24 16:56:09.670  6907  6931 V FormManager: Network unavailable.
08-24 16:56:09.671  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-24 16:56:09.671  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-24 16:56:09.671  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@6e8ac9 mBinding = false
08-24 16:56:09.672  1034  1096 D BluetoothManagerService: Sending unbind request.
08-24 16:56:09.673  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-24 16:56:09.679  3875  3951 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-24 16:56:09.680  3875  3875 I GKI_LINUX: GKI_exit_task 1 done
08-24 16:56:09.680  3875  3875 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-24 16:56:09.680  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 16:56:09.680  3875  3875 I BluetoothServiceJni: cleanupNative: return from cleanup
08-24 16:56:09.680  3875  3875 I art     : --- WEIRD: removing null entry 246
08-24 16:56:09.680  3875  3875 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
,08-24 16:56:09.680  3875  3875 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-24 16:56:09.682  1974  1974 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:09.682  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:09.682  1974  2170 D LGBluetoothAPIService: Message: 2
08-24 16:56:09.682  1974  2170 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1c7cab5b mBinding = false
08-24 16:56:09.682  1974  2170 D LGBluetoothAPIService: Sending unbind request.
,08-24 16:56:09.683  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:09.687  3875  3875 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-24 16:56:09.688  1605  1605 D BluetoothAdapter: 991491648: getState() :  mService = null. Returning STATE_OFF
08-24 16:56:09.688  1605  1605 D BluetoothAdapter: 991491648: getState() :  mService = null. Returning STATE_OFF
08-24 16:56:09.693  6810  6810 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 16:56:09.693  3875  3875 I art     : System.exit called, status: 0
08-24 16:56:09.693  3875  3875 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 16:56:09.695  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-24 16:56:09.695  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 16:56:09.695  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-24 16:56:09.696  6810  6810 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 16:56:09.696  6810  6810 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-24 16:56:09.698  6810  6810 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-24 16:56:09.700  1034  2038 I ActivityManager: Killing 5964:com.android.contacts/u0a19 (adj 15): empty #17
08-24 16:56:09.701  6810  6810 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-24 16:56:09.701  6810  6810 D LGBluetoothEventManager: [BTUI] clear device connection state
08-24 16:56:09.702  6810  6810 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 16:56:09.721   318   318 V AudioFlinger: 3875 died, releasing its sessions
08-24 16:56:09.721   318   318 V AudioFlinger:  pid 1876 @ 0
08-24 16:56:09.721   318   318 V AudioFlinger:  pid 3449 @ 1
08-24 16:56:09.721   318   318 V AudioFlinger:  pid 3449 @ 2
,08-24 16:56:09.798  1034  1992 W libprocessgroup: failed to open /acct/uid_10019/pid_5964/cgroup.procs: No such file or directory
,08-24 16:56:09.803  6810  6810 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-24 16:56:09.818  1034  1991 I ActivityManager: Process com.android.bluetooth (pid 3875) has died
,08-24 16:56:09.819  1034  1991 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-24 16:56:09.834  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 16:56:09.834  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-24 16:56:09.840  6810  6810 D DockEventReceiver: finishStartingService: stopping service
08-24 16:56:09.843  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 16:56:09.843  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 16:56:09.856  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 16:56:09.880  4300  6942 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-24 16:56:09.889  4300  6943 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 16:56:09.890  4300  6943 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 16:56:09.911  6810  6810 D BluetoothPermissionRequest: onReceive
,08-24 16:56:09.921  6833  6833 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-24 16:56:09.921  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 16:56:09.921  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 16:56:09.926  6810  6810 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-24 16:56:09.927  6810  6810 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter,
08-24 16:56:09.941  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-24 16:56:09.951  6907  6945 W FormManager: Network not available. Please check & try again.
,08-24 16:56:09.961  6907  6946 V FormManager: Network unavailable.
08-24 16:56:09.963  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:09.964  6810  6810 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-24 16:56:10.019  1034  1992 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6950 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-24 16:56:10.027  6907  6946 V FormManager: Network unavailable.
08-24 16:56:10.051  6861  6861 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-24 16:56:10.052  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-24 16:56:10.053  6861  6861 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-24 16:56:10.092  6950  6950 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-24 16:56:10.093  6950  6950 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 16:56:10.093  6950  6950 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-24 16:56:10.094  6950  6950 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 16:56:10.096  6861  6861 D LgDataFeature: LgDataFeature() Constructor: none
08-24 16:56:10.097  6861  6861 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 16:56:10.110  6861  6861 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-24 16:56:10.114  6861  6861 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-24 16:56:10.114  6861  6861 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-24 16:56:10.114  6861  6861 V SoundPool: doLoad: loading sample sampleID=1
08-24 16:56:10.114  6861  6969 V SoundPool: Start decode
08-24 16:56:10.114  6861  6969 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-24 16:56:10.115   318  1383 V MediaPlayerService: decode(23, 10857164, 17813)
08-24 16:56:10.115   318  1383 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-24 16:56:10.115   318  1383 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-24 16:56:10.115   318  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-24 16:56:10.115   318  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-24 16:56:10.115   318  1383 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-24 16:56:10.115   318  1383 V MediaPlayerService: player type = 3
08-24 16:56:10.116   318  1383 V AwesomePlayer: AwesomePlayer create()
08-24 16:56:10.116  6950  6950 D BluetoothAdapterApp: Loading JNI Library
08-24 16:56:10.116   318  1383 V AwesomePlayer: reset_l() 
08-24 16:56:10.116   318  1383 V AwesomePlayer: cancelPlayerEvents
08-24 16:56:10.116   318  1383 V AwesomePlayer: setAudioSink() 
08-24 16:56:10.116   318  1383 V AwesomePlayer: reset_l() 
08-24 16:56:10.116   318  1383 V AudioCache: notify(0xb1436180, 8, 0, 0)
08-24 16:56:10.116   318  1383 V AudioCache: ignored
08-24 16:56:10.116   318  1383 V AwesomePlayer: cancelPlayerEvents
08-24 16:56:10.116  6861  6861 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-24 16:56:10.116   318  1383 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-24 16:56:10.116   318  1383 V AwesomePlayer: setDataSource_l dataSource
08-24 16:56:10.116   318  1383 V LGParserOSAL: SniffLGParser start
08-24 16:56:10.116   318  1383 V LGParserOSAL: MainType:5, SubType=0
08-24 16:56:10.116   318  1383 V LGParserOSAL: #### check Mime : application/ogg
08-24 16:56:10.116   318  1383 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-24 16:56:10.117   318  1383 E MediaExtractor: Use LGExtractor :application/ogg 
08-24 16:56:10.123  6615  6615 D UEI.SmartControl: QS Service created
08-24 16:56:10.124  6861  6861 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-24 16:56:10.128  6861  6861 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-24 16:56:10.129  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-24 16:56:10.142  6861  6861 V LGMDMManager: Create singleton instance
08-24 16:56:10.160  6950  6950 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@d201989 Instance Count = 1
08-24 16:56:10.164   318  1383 V LGParserOSAL: supported mime: application/ogg
08-24 16:56:10.164   318  1383 V AwesomePlayer: setDataSource_l() extractor countTracks=1
,08-24 16:56:10.164   318  1383 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-24 16:56:10.164   318  1383 V AwesomePlayer: mBitrate = -1 bits/sec
08-24 16:56:10.164   318  1383 V AwesomePlayer: AudioTrack Setting
08-24 16:56:10.164   318  1383 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-24 16:56:10.164   318  1383 V AwesomePlayer: setAudioSource() 
08-24 16:56:10.164   318  1383 V MediaPlayerService: prepare
08-24 16:56:10.164   318  1383 V AwesomePlayer: prepareAsync_l() 
08-24 16:56:10.164   318  1383 V MediaPlayerService: wait for prepare
08-24 16:56:10.164   318  6970 V AwesomePlayer: onPrepareAsyncEvent() 
08-24 16:56:10.164   318  6970 V AwesomePlayer: initAudioDecoder() 
08-24 16:56:10.164   318  6970 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-24 16:56:10.164   318  6970 V AudioSystem: isOffloadSupported()
08-24 16:56:10.164   318  6970 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-24 16:56:10.164   318  6970 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-24 16:56:10.164   318  6970 I AudioFlinger: isAudioPlaybackHookOn() false
08-24 16:56:10.165   318  6970 V AwesomePlayer: getUseOffload() = 0 
08-24 16:56:10.165   318  6970 V OMXCodec: OMXCodec::Create
08-24 16:56:10.165   318  6970 V OMXCodec: findMatchingCodecs()
08-24 16:56:10.165   318  6970 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-24 16:56:10.165   318  6970 V OMXCodec: matchingCodecs.size()=1
08-24 16:56:10.165   318  6970 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-24 16:56:10.166   318  6970 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-24 16:56:10.166   318  6970 V LGCodecAdapter: LG Codec Adapter start
08-24 16:56:10.166   318  6970 V OMXCodec: OMXCodec Createtor
08-24 16:56:10.166   318  6970 V OMXCodec: setComponentRole
08-24 16:56:10.166   318  6970 V OMXCodec: configureCodec protected=0
08-24 16:56:10.166   318  6970 V LGCodecAdapter: called getLGCodecSpecificData
08-24 16:56:10.166   318  6970 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-24 16:56:10.167   318  6970 V LGCodecOSAL: Called LGconfigureCodecMETA
08-24 16:56:10.167   318  6970 V LGCodecOSAL: Called LGconfigureCodecMSG
08-24 16:56:10.167   318  6970 V LGCodecOSAL: Not support LGCodec
08-24 16:56:10.167   318  6970 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-24 16:56:10.167   318  6970 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-24 16:56:10.167   318  6970 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-24 16:56:10.167   318  6970 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-24 16:56:10.167   318  6970 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-24 16:56:10.167   318  6970 V AudioSystem: isOffloadSupported()
08-24 16:56:10.167   318  6970 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-24 16:56:10.167   318  6970 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-24 16:56:10.167   318  6970 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-24 16:56:10.167   318  6970 V OMXCodec: init()
08-24 16:56:10.167   318  6970 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-24 16:56:10.167   318  6970 V OMXCodec: allocateBuffers
08-24 16:56:10.167   318  6970 V OMXCodec: allocateBuffersOnPort portIndex=0
08-2,4 16:56:10.167   318  6970 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-24 16:56:10.167   318  6970 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14341f0 on input port
08-24 16:56:10.167   318  6970 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb15430b0 on input port
08-24 16:56:10.167   318  6970 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1543100 on input port
08-24 16:56:10.167   318  6970 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1543790 on input port
08-24 16:56:10.168   318  6970 V OMXCodec: allocateBuffersOnPort portIndex=1
08-24 16:56:10.168   318  6970 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-24 16:56:10.168   318  6970 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb15437e0 on output port
08-24 16:56:10.168   318  6970 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1543880 on output port
08-24 16:56:10.168   318  6970 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb15438d0 on output port
08-24 16:56:10.168   318  6970 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1543c90 on output port
08-24 16:56:10.168   318  6970 V OMXCodec: init() mAsyncCompletion wait!!! 
08-24 16:56:10.169  6950  6950 D BluetoothAdapterApp: onCreate
08-24 16:56:10.175   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-24 16:56:10.175   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-24 16:56:10.175  6615  6615 I UEI.SmartControl: Service initServices...
08-24 16:56:10.176   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-24 16:56:10.176   318  6970 V OMXCodec: init() mAsyncCompletion wait!!! 
08-24 16:56:10.176  6615  6615 D UEI.SmartControl: QS start get config
,08-24 16:56:10.178   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-24 16:56:10.178   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-24 16:56:10.178   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-24 16:56:10.178   318  6970 V OMXCodec: init() mAsyncCompletion wait free! 
08-24 16:56:10.178   318  6970 V AwesomePlayer: finishAsyncPrepare_l() 
08-24 16:56:10.178   318  6970 V AudioCache: notify(0xb1436180, 5, 0, 0)
08-24 16:56:10.178   318  6970 V AudioCache: ignored
08-24 16:56:10.178   318  6970 V AudioCache: notify(0xb1436180, 1, 0, 0)
08-24 16:56:10.178   318  6970 V AudioCache: prepared
08-24 16:56:10.178   318  1383 V AudioCache: wait - success
08-24 16:56:10.179   318  1383 V MediaPlayerService: start
08-24 16:56:10.179   318  1383 V AwesomePlayer: play_l() 
,08-24 16:56:10.179   318  1383 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-24 16:56:10.179   318  1383 V AwesomePlayer: createAudioPlayer_l
08-24 16:56:10.179   318  1383 V AwesomePlayer: seekAudioIfNecessary_l() 
08-24 16:56:10.179   318  1383 V AwesomePlayer: startAudioPlayer_l() 
08-24 16:56:10.179   318  1383 D AudioPlayer: start of Playback, useOffload 0
08-24 16:56:10.179   318  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-24 16:56:10.179   318  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-24 16:56:10.181   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-24 16:56:10.181   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-24 16:56:10.181   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-24 16:56:10.182   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-24 16:56:10.182   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-24 16:56:10.182   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-24 16:56:10.182   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975086560
08-24 16:56:10.182   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 16:56:10.182   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975086720
08-24 16:56:10.182   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 16:56:10.182   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975086800
08-24 16:56:10.182   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 16:56:10.182   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975087760
08-24 16:56:10.182   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 16:56:10.183   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-24 16:56:10.183   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-24 16:56:10.183   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-24 16:56:10.183   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-24 16:56:10.183   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-24 16:56:10.183   318  6972 V OMXCodec: allocateBuffersOnPort portIndex=1
08-24 16:56:10.183   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-24 16:56:10.184   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb15438d0 on output port
08-24 16:56:10.184   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1543880 on output port
08-24 16:56:10.184   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb15437e0 on output port
08-24 16:56:10.184   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-24 16:56:10.184   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-24 16:56:10.184   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-24 16:56:10.185   318  1383 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-24 16:56:10.186   318  1383 V AudioCache: notify(0xb1436180, 6, 0, 0)
08-24 16:56:10.186   318  1383 V AudioCache: ignored
08-24 16:56:10.186   318  1383 V MediaPlayerService: wait for playback complete
08-24 16:56:10.187   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.187   318  6973 V AudioCache: memcpy(0xac1f9000, 0xb57e1000, 4096)
08-24 16:56:10.188   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.188   318  6973 V AudioCache: memcpy(0xac1fa000, 0xb57e1000, 4096)
08-24 16:56:10.189 ,  318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.189   318  6973 V AudioCache: memcpy(0xac1fb000, 0xb57e1000, 4096)
08-24 16:56:10.189   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.189   318  6973 V AudioCache: memcpy(0xac1fc000, 0xb57e1000, 4096)
08-24 16:56:10.190   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.190   318  6973 V AudioCache: memcpy(0xac1fd000, 0xb57e1000, 4096)
08-24 16:56:10.190   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.190   318  6973 V AudioCache: memcpy(0xac1fe000, 0xb57e1000, 4096)
08-24 16:56:10.190   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.190   318  6973 V AudioCache: memcpy(0xac1ff000, 0xb57e1000, 4096)
08-24 16:56:10.194   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.194   318  6973 V AudioCache: memcpy(0xac200000, 0xb57e1000, 4096)
08-24 16:56:10.194   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.194   318  6973 V AudioCache: memcpy(0xac201000, 0xb57e1000, 4096)
08-24 16:56:10.194   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.194   318  6973 V AudioCache: memcpy(0xac202000, 0xb57e1000, 4096)
08-24 16:56:10.194   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.194   318  6973 V AudioCache: memcpy(0xac203000, 0xb57e1000, 4096)
08-24 16:56:10.196   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.196   318  6973 V AudioCache: memcpy(0xac204000, 0xb57e1000, 4096)
08-24 16:56:10.196   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.196   318  6973 V AudioCache: memcpy(0xac205000, 0xb57e1000, 4096)
08-24 16:56:10.196   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.196   318  6973 V AudioCache: memcpy(0xac206000, 0xb57e1000, 4096)
08-24 16:56:10.196   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.196   318  6973 V AudioCache: memcpy(0xac207000, 0xb57e1000, 4096)
08-24 16:56:10.197   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.197   318  6973 V AudioCache: memcpy(0xac208000, 0xb57e1000, 4096)
08-24 16:56:10.197   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.197   318  6973 V AudioCache: memcpy(0xac209000, 0xb57e1000, 4096)
08-24 16:56:10.197   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.197   318  6973 V AudioCache: memcpy(0xac20a000, 0xb57e1000, 4096)
08-24 16:56:10.198   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.198   318  6973 V AudioCache: memcpy(0xac20b000, 0xb57e1000, 4096)
08-24 16:56:10.199   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.199   318  6973 V AudioCache: memcpy(0xac20c000, 0xb57e1000, 4096)
08-24 16:56:10.199   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.199   318  6973 V AudioCache: memcpy(0xac20d000, 0xb57e1000, 4096)
,08-24 16:56:10.200   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.200   318  6973 V AudioCache: memcpy(0xac20e000, 0xb57e1000, 4096)
08-24 16:56:10.200   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.200   318  6973 V AudioCache: memcpy(0xac20f000, 0xb57e1000, 4096)
08-24 16:56:10.202   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.202   318  6973 V AudioCache: memcpy(0xac210000, 0xb57e1000, 4096)
08-24 16:56:10.203   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.203   318  6973 V AudioCache: memcpy(0xac211000, 0xb57e1000, 4096)
08-24 16:56:10.203   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.203   318  6973 V AudioCache: memcpy(0xac212000, 0xb57e1000, 4096)
08-24 16:56:10.203   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.203   318  6973 V AudioCache: memcpy(0xac213000, 0xb57e1000, 4096)
08-24 16:56:10.205   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.205   318  6973 V AudioCache: memcpy(0xac214000, 0xb57e1000, 4096)
08-24 16:56:10.207   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.207   318  6973 V AudioCache: memcpy(0xac215000, 0xb57e1000, 4096)
08-24 16:56:10.207   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.207   318  6973 V AudioCache: memcpy(0xac216000, 0xb57e1000, 4096)
08-24 16:56:10.207   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.207   318  6973 V AudioCache: memcpy(0xac217000, 0xb57e1000, 4096)
08-24 16:56:10.207   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.207   318  6973 V AudioCache: memcpy(0xac218000, 0xb57e1000, 4096)
08-24 16:56:10.208   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.208   318  6973 V AudioCache: memcpy(0xac219000, 0xb57e1000, 4096)
08-24 16:56:10.209   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.209   318  6973 V AudioCache: memcpy(0xac21a000, 0xb57e1000, 4096)
08-24 16:56:10.209   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.210   318  6973 V AudioCache: memcpy(0xac21b000, 0xb57e1000, 4096)
08-24 16:56:10.210   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.210   318  6973 V AudioCache: memcpy(0xac21c000, 0xb57e1000, 4096)
08-24 16:56:10.210   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.210   318  6973 V AudioCache: memcpy(0xac21d000, 0xb57e1000, 4096)
,08-24 16:56:10.211   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.211   318  6973 V AudioCache: memcpy(0xac21e000, 0xb57e1000, 4096)
08-24 16:56:10.212   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.212   318  6973 V AudioCache: memcpy(0xac21f000, 0xb57e1000, 4096)
08-24 16:56:10.212   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.212   318  6973 V AudioCache: memcpy(0xac220000, 0xb57e1000, 4096)
08-24 16:56:10.213   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.213   318  6973 V AudioCache: memcpy(0xac221000, 0xb57e1000, 4096)
08-24 16:56:10.213   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.213   318  6973 V AudioCache: memcpy(0xac222000, 0xb57e1000, 4096)
08-24 16:56:10.214   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.214   318  6973 V AudioCache: memcpy(0xac223000, 0xb57e1000, 4096)
08-24 16:56:10.215  6950  6950 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-24 16:56:10.215  6950  6950 D ProfileConfigQcom: Adding HeadsetService
08-24 16:56:10.215  6950  6950 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-24 16:56:10.215   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.215   318  6973 V AudioCache: memcpy(0xac224000, 0xb57e1000, 4096)
08-24 16:56:10.215  6950  6950 D ProfileConfigQcom: Adding A2dpService
08-24 16:56:10.215  6950  6950 D ProfileConfigQcom: [BTUI] HidService is supported
08-24 16:56:10.216  6950  6950 D ProfileConfigQcom: Adding HidService
08-24 16:56:10.216   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.216   318  6973 V AudioCache: memcpy(0xac225000, 0xb57e1000, 4096)
08-24 16:56:10.216  6950  6950 D ProfileConfigQcom: [BTUI] HealthService is supported
08-24 16:56:10.216  6950  6950 D ProfileConfigQcom: Adding HealthService
08-24 16:56:10.216   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.216  6950  6950 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-24 16:56:10.216   318  6973 V AudioCache: memcpy(0xac226000, 0xb57e1000, 4096)
08-24 16:56:10.217   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.217   318  6973 V AudioCache: memcpy(0xac227000, 0xb57e1000, 4096)
08-24 16:56:10.217  6950  6950 D ProfileConfigQcom: [BTUI] PanService is supported
08-24 16:56:10.217  6950  6950 D ProfileConfigQcom: Adding PanService
08-24 16:56:10.217  6950  6950 D ProfileConfigQcom: [BTUI] GattService is supported
08-24 16:56:10.217   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.217   318  6973 V AudioCache: memcpy(0xac228000, 0xb57e1000, 4096)
08-24 16:56:10.218  6950  6950 D ProfileConfigQcom: Adding GattService
08-24 16:56:10.218  6950  6950 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-24 16:56:10.218  6950  6950 D ProfileConfigQcom: Adding BluetoothMapService
08-24 16:56:10.218  6950  6950 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-24 16:56:10.220  6950  6950 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-24 16:56:10.222   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.222   318  6973 V AudioCache: memcpy(0xac229000, 0xb57e1000, 4096)
08-24 16:56:10.222   318  6973 V AudioCache: write(0xb57e1000, 4096)
08-24 16:56:10.222   318  6973 V AudioCache: memcpy(0xac22a000, 0xb57e1000, 4096)
08-24 16:56:10.222   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-24 16:56:10.222   318  6973 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-24 16:56:10.222   318  6973 V AwesomePlayer: postAudioEOS() 
08-24 16:56:10.223   318  6973 V AudioCache: write(0xb57e1000, 280)
08-24 16:56:10.223   318  6973 V AudioCache: memcpy(0xac22b000, 0xb57e1000, 280)
08-24 16:56:10.224   318  6970 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-24 16:56:10.224   318  6970 V AwesomePlayer: onStreamDone
08-24 16:56:10.224   318  6970 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-24 16:56,:10.224   318  6970 V AudioCache: notify(0xb1436180, 2, 0, 0)
08-24 16:56:10.224   318  6970 V AudioCache: playback complete
08-24 16:56:10.224   318  6970 V AwesomePlayer: pause_l() 
08-24 16:56:10.224   318  1383 V AudioCache: wait - success
08-24 16:56:10.224   318  6970 V AudioCache: notify(0xb1436180, 7, 0, 0)
08-24 16:56:10.224   318  6970 V AudioCache: ignored
08-24 16:56:10.224   318  1383 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-24 16:56:10.224   318  6970 V AwesomePlayer: cancelPlayerEvents
08-24 16:56:10.224   318  6970 D AudioPlayer: Pause Playback at 1068125
08-24 16:56:10.225   318  1383 V AwesomePlayer: reset_l() 
08-24 16:56:10.225   318  1383 V AudioCache: notify(0xb1436180, 8, 0, 0)
08-24 16:56:10.225   318  1383 V AudioCache: ignored
08-24 16:56:10.225   318  1383 V AwesomePlayer: cancelPlayerEvents
08-24 16:56:10.225   318  1383 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-24 16:56:10.225   318  1383 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-24 16:56:10.225   318  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-24 16:56:10.225   318  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-24 16:56:10.225   318  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-24 16:56:10.225   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-24 16:56:10.225   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-24 16:56:10.225   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-24 16:56:10.225   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1543790 on port 0
08-24 16:56:10.225   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-24 16:56:10.225   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1543100 on port 0
08-24 16:56:10.225   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-24 16:56:10.225   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb15430b0 on port 0
08-24 16:56:10.225   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-24 16:56:10.225   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14341f0 on port 0
08-24 16:56:10.225   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-24 16:56:10.225   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-24 16:56:10.225   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-24 16:56:10.225   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-24 16:56:10.226   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb15437e0 on port 1
08-24 16:56:10.226   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-24 16:56:10.226   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1543880 on port 1
08-24 16:56:10.226   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-24 16:56:10.226   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb15438d0 on port 1
08-24 16:56:10.226   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-24 16:56:10.226   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-24 16:56:10.226   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-24 16:56:10.226   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-24 16:56:10.226   318  6972 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-24 16:56:10.226   318  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-24 16:56:10.226   318  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-24 16:56:10.226   318  1383 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-24 16:56:10.227   318  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-24 16:56:10.227   318  1383 D AudioPlayer: AudioPlayer releasing audio source
,08-24 16:56:10.227   318  1383 D AudioPlayer: AudioPlayer done releasing audio source
08-24 16:56:10.227   318  1383 V AwesomePlayer: reset_l() 
08-24 16:56:10.227   318  1383 V AwesomePlayer: cancelPlayerEvents
08-24 16:56:10.227   318  1383 V AwesomePlayer: ~AwesomePlayer call
08-24 16:56:10.228   318  1383 V AwesomePlayer: reset_l() 
08-24 16:56:10.228   318  1383 V AwesomePlayer: cancelPlayerEvents
,08-24 16:56:10.228  6861  6969 V SoundPool: close(31)
08-24 16:56:10.228  6861  6969 V SoundPool: pointer = 0x9fff1000, size = 205080, sampleRate = 48000, numChannels = 2
08-24 16:56:10.229  6810  6810 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-24 16:56:10.231  6950  6950 V LGMDMManagerInternal: Create singleton instance
,08-24 16:56:10.248  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-24 16:56:10.250  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-24 16:56:10.251  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9837
08-24 16:56:10.321  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-24 16:56:10.327  6950  6950 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 16:56:10.327  6950  6950 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 16:56:10.328  6950  6950 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 16:56:10.329  6950  6950 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:10.329  6950  6950 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-24 16:56:10.341  6881  6881 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-24 16:56:10.572  6615  6615 I UEI.SmartControl: Supports setup maps: true
,08-24 16:56:10.575  6615  6615 D UEI.SmartControl: QS start statue = true Error code = 0
08-24 16:56:10.575  6615  6615 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-24 16:56:10.575  6615  6615 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-24 16:56:10.575  6615  6615 I UEI.SmartControl: ### init IR Blaster...
08-24 16:56:10.578  6615  6615 D serial_port: Configuring serial port
08-24 16:56:10.579  6615  6615 E UEI.SmartControl: UEIBLaster setting for 616
08-24 16:56:10.579  6615  6615 I UEI.SmartControl: Setting serial record hearder size = 2
08-24 16:56:10.579  6615  6615 I UEI.SmartControl: configuring settings for MAXQ616
08-24 16:56:10.579  6615  6615 I UEI.SmartControl: Get version...
08-24 16:56:10.596  6615  6988 D UEI.SmartControl: serial port data available: 21
,08-24 16:56:10.621  6615  6615 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-24 16:56:10.622  6615  6615 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-24 16:56:10.622  6615  6615 I UEI.SmartControl: QS saving settings...
,08-24 16:56:10.625  6615  6615 D UEI.SmartControl: IR Blaster version: 25672567
,08-24 16:56:10.643  6615  6988 D UEI.SmartControl: serial port data available: 4
,08-24 16:56:10.672  6615  6615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-24 16:56:10.675  6615  6991 I UEI.SmartControl: Device manager: loading config....
08-24 16:56:10.675  6615  6991 D UEI.SmartControl: ----------- loading internal config...
08-24 16:56:10.677  6615  6615 E UEI.SmartControl: Services init done
08-24 16:56:10.677  6615  6615 D UEI.SmartControl: QS Service init finished
08-24 16:56:10.679  6615  6615 D UEI.SmartControl: QS Service version name: 2.1.91
08-24 16:56:10.679  6615  6615 D UEI.SmartControl: QS Service version code: 201091
08-24 16:56:10.680  6615  6615 D UEI.SmartControl: Service requested: Control
08-24 16:56:10.684  6615  6991 E UEI.SmartControl: Loading SETTINGS...
08-24 16:56:10.685  6615  6615 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-24 16:56:10.693  6615  6615 D UEI.SmartControl: Internal service binding...
,08-24 16:56:10.697  6861  6861 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-24 16:56:10.699  6615  6991 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-24 16:56:10.700  6615  6631 I UEI.SmartControl: ------ IControl API: 11
08-24 16:56:10.701  6615  6631 D UEI.SmartControl: File observer start...
08-24 16:56:10.702  6615  6631 E UEI.SmartControl: IR Port is disabled: false
08-24 16:56:10.702  6615  6631 D UEI.SmartControl: Starting file observer...
,08-24 16:56:10.709  6615  6631 I UEI.SmartControl: Registering callback...
08-24 16:56:10.710  6615  6630 I UEI.SmartControl: ------ IControl API: 19
08-24 16:56:10.713  6615  6630 I UEI.SmartControl: Registering Services Ready callback...
08-24 16:56:10.713  6615  6630 I UEI.SmartControl: Notify client services are ready...
08-24 16:56:10.713  6615  6990 I UEI.SmartControl: Notify AllClients services are ready: 0
08-24 16:56:10.715  6861  6880 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-24 16:56:10.716  6861  6880 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-24 16:56:10.716  6861  6967 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
,08-24 16:56:10.716  6861  6967 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-24 16:56:10.716  6861  6967 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-24 16:56:10.716  6615  6990 D UEI.SmartControl: -----service ready thread exits
08-24 16:56:10.717  6861  6967 D QRemote : [RemoteControlManager.java:391:handleMessage()] oooooo 140510:Retrieve msg remove
08-24 16:56:10.717  6861  6967 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-24 16:56:10.718  6861  6861 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-24 16:56:10.719  6861  6861 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,08-24 16:56:10.719  6615  6631 I UEI.SmartControl: ------ IControl API: 8
08-24 16:56:10.721  6861  6861 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-24 16:56:10.722  6861  6861 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-24 16:56:10.722  6861  6861 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-24 16:56:10.722  6861  6861 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-24 16:56:10.723  6861  6861 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-24 16:56:10.724  6861  6861 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-24 16:56:10.725  6861  6861 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-24 16:56:10.729  6861  6861 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-24 16:56:10.729  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-24 16:56:10.730  6861  6861 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-24 16:56:10.730  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-24 16:56:10.732  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-24 16:56:10.733  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-24 16:56:10.734  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-24 16:56:10.735  6861  6861 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472050570734]
08-24 16:56:10.738  6861  6861 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-24 16:56:10.739  1034  1941 I ActivityManager: Killing 5986:com.android.gallery3d/u0a27 (adj 15): empty #17
08-24 16:56:10.763  6861  6993 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-24 16:56:10.778  1034  1941 I ActivityManager: Killing 6483:com.lge.email/u0a23 (adj 15): empty #18
,08-24 16:56:10.809  1034  2033 W libprocessgroup: failed to open /acct/uid_10027/pid_5986/cgroup.procs: No such file or directory
,08-24 16:56:10.814  1034  2038 W libprocessgroup: failed to open /acct/uid_10023/pid_6483/cgroup.procs: No such file or directory
,08-24 16:56:10.819  6861  6861 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-24 16:56:10.820  6861  6861 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-24 16:56:10.821  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,08-24 16:56:10.821  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-24 16:56:10.822  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-24 16:56:10.822  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-24 16:56:10.823  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-24 16:56:10.839  6861  6861 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-24 16:56:11.503  1034  1603 D WifiServiceImplEx: setWifiEnabled: true pid=6695, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 16:56:11.505  1034  1603 D WifiService: setWifiEnabled: true pid=6695, uid=10118
08-24 16:56:11.505  1034  1603 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 16:56:11.533  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 16:56:11.533  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 16:56:11.533  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-24 16:56:11.537  1034  1540 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-24 16:56:11.537  1034  1540 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-24 16:56:11.539  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-24 16:56:11.539  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-24 16:56:11.539  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-24 16:56:11.539  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-24 16:56:11.540  1034  1540 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-24 16:56:11.540  1034  1540 E WifiHW  : unknown target_country: EU , set to default
08-24 16:56:11.540  1034  1540 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-24 16:56:11.540  1034  1540 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-24 16:56:11.540  1034  1540 I WifiUtil: gEnableBmps=1
08-24 16:56:11.565  1034  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:56:11.572  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-24 16:56:11.580  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:56:11.584  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:11.584  1034  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:11.592  1034  1096 D Tethering: MasterInitialState.processMessage what=3
,08-24 16:56:11.594  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:11.604  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:56:11.607  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:11.609  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 16:56:11.612  6390  6832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-24 16:56:11.623  5695  5695 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-24 16:56:11.632  5695  5695 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-24 16:56:11.650  2209  2209 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:56:11.682  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:56:11.733  1034  1992 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7003 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-24 16:56:11.739  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:11.741  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-24 16:56:11.808  7003  7003 I AppUp4:AppBoxCP: onCreate
,08-24 16:56:11.809  7003  7003 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-24 16:56:11.819  7003  7003 I AppUp4:DB:  setFingerPrint start
08-24 16:56:11.820  7003  7003 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-24 16:56:11.828  7003  7003 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-24 16:56:11.828  7003  7003 I AppUp4:DB:  SDK version = 21
08-24 16:56:11.828  7003  7003 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-24 16:56:11.831  7003  7003 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-24 16:56:11.832  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 16:56:11.832  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:11.835  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 16:56:11.835  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-24 16:56:11.840  7003  7003 I AppUp4:CustModeStarterReceiver: onReceive
08-24 16:56:11.886  7003  7003 D LgDataFeature: LgDataFeature() Constructor: none
,08-24 16:56:11.886  7003  7003 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 16:56:11.897  7003  7003 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bc181cb
,08-24 16:56:11.897  7003  7003 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 16:56:11.897  7003  7003 D AppUp4:CustFacade: isPhone : true
08-24 16:56:11.898  7003  7003 D AppUp4:CustModeStarterReceiver: begin check event
,08-24 16:56:11.899  7003  7003 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-24 16:56:11.899  7003  7003 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-24 16:56:11.900  7003  7032 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,08-24 16:56:11.900  7003  7032 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-24 16:56:11.901  7003  7032 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-24 16:56:11.910  1034  2033 I ActivityManager: Killing 6051:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-24 16:56:11.969  1034  1049 W libprocessgroup: failed to open /acct/uid_10080/pid_6051/cgroup.procs: No such file or directory
08-24 16:56:11.971  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:11.972  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-24 16:56:11.977  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 16:56:11.982  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 16:56:11.992  4300  7035 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-24 16:56:11.994  4300  7036 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:11.994  4300  7036 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 16:56:12.075  1034  1050 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7040 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-24 16:56:12.161  7040  7040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 16:56:12.162  7040  7040 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-24 16:56:12.163  7040  7040 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 16:56:12.164  7040  7040 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 16:56:12.260   312   908 D SoftapController: Softap fwReload - Ok
,08-24 16:56:12.265  1034  1540 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (720ms)
08-24 16:56:12.272  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-24 16:56:12.273   312   908 D CommandListener: Setting iface cfg
08-24 16:56:12.273   312   908 D CommandListener: Trying to bring down wlan0
08-24 16:56:12.276  1034  1096 D Tethering: InitialState.processMessage what=4
,08-24 16:56:12.283   312   908 D CommandListener: Clearing all IP addresses on wlan0
08-24 16:56:12.284  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 16:56:12.286  1034  1540 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-24 16:56:12.290  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 16:56:12.290  1034  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 16:56:12.290  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-24 16:56:12.296  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-24 16:56:12.296  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:12.298  1974  1974 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-24 16:56:12.295  7067  7067 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:12.295  7067  7067 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:12.301  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:56:12.304  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:12.305  1034  1540 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-24 16:56:12.305  1034  1540 D WifiMonitor: connecting to supplicant
08-24 16:56:12.336  7040  7040 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-24 16:56:12.351  7067  7067 I wpa_supplicant: Successfully initialized wpa_supplicant
08-24 16:56:12.352  7040  7040 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-24 16:56:12.386  7067  7067 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-24 16:56:12.386  7067  7067 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-24 16:56:12.390  7040  7040 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-24 16:56:12.425  7040  7040 D LgDataFeature: LgDataFeature() Constructor: none
08-24 16:56:12.425  7040  7040 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 16:56:12.465  7067  7067 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-24 16:56:12.500  7067  7067 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-24 16:56:12.503  7067  7067 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-24 16:56:12.504  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-24 16:56:12.504  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-24 16:56:12.505  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-24 16:56:12.505  1034  1540 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-24 16:56:12.506  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:12.506  1034  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:12.507  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:12.507  1034  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-24 16:56:12.508  1034  1540 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-24 16:56:12.508  1034  1540 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-24 16:56:12.508  1034  1540 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-24 16:56:12.508  1034  7083 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-24 16:56:12.508  1034  1540 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-24 16:56:12.508  1034  7083 D WifiMonitor: Dropping event because (p2p0) is stopped
08-24 16:56:12.508  1034  1540 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-24 16:56:12.508  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 16:56:12.508  1034  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 16:56:12.508  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 16:56:12.509  1034  1540 D WifiNative-wlan0: doBoolean: SET update_config 1
08-24 16:56:12.509  1034  1540 D WifiNative-wlan0: SET update_config 1: returned true
08-24 16:56:12.509  1034  1540 D WifiConfigStore: Loading config and enabling all networks 
08-24 16:56:12.509  1034  1540 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-24 16:56:12.510  1034  1540 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-24 16:56:12.511  1974  1974 D WfdService: Waiting for WifiP2p enabling
,08-24 16:56:12.512  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:12.512  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:12.512  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:12.513  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:12.513  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 16:56:12.514  1034  1540 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-24 16:56:12.515  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:12.519  1034  1540 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-24 16:56:12.519  1034  1540 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-24 16:56:12.520  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,08-24 16:56:12.520  1034  1540 D WifiStateMachine: enableVerboseLogging : level 2
08-24 16:56:12.520  1034  1540 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-24 16:56:12.520  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:12.521  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:12.521  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:12.521  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:12.521  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:12.521  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:56:12.521  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:12.521  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:12.521  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:56:12.521  1034  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-24 16:56:12.521  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:12.521  1034  1540 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-24 16:56:12.521  1034  1540 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-24 16:56:12.521  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:56:12.521  1034  1540 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-24 16:56:12.521  1034  1540 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-24 16:56:12.522  1034  1540 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-24 16:56:12.522  1034  1540 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-24 16:56:12.522  1034  1540 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-24 16:56:12.522  1034  1540 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-24 16:56:12.522  1034  1540 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-24 16:56:12.522  1034  1540 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-24 16:56:12.522  1034  1540 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-24 16:56:12.523  1034  1540 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-24 16:56:12.523  1034  1540 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-24 16:56:12.524  1034  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 16:56:12.524  1034  1540 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-24 16:56:12.524  1034  1540 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-24 16:56:12.524  1034  1540 D WifiNative-HAL: Setting external_sim to 1
08-24 16:56:12.524  1034  1540 D WifiNative-wlan0: doBoolean: SET external_sim 1
,08-24 16:56:12.524  1034  1540 D WifiNative-wlan0: SET external_sim 1: returned true
08-24 16:56:12.524  1034  1540 I WifiNative-HAL: startHal
08-24 16:56:12.524  1034  1540 D wifi    : setting scan oui 0x95786f60
08-24 16:56:12.525  1034  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 16:56:12.525  1034  1540 I WifiNative-HAL: startHal
08-24 16:56:12.525  1034  1540 D wifi    : setting scan oui 0x95786f60
08-24 16:56:12.525  1034  1540 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-24 16:56:12.525  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:12.525  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:12.525  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:12.525  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:12.525  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:12.525  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:56:12.525  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:12.525  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:12.525  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:56:12.525  1034  1540 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-24 16:56:12.525  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-24 16:56:12.525  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:12.525  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-24 16:56:12.525  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:56:12.526  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-24 16:56:12.526  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-24 16:56:12.526  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 16:56:12.526  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 16:56:12.526  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-24 16:56:12.526  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-24 16:56:12.526  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-24 16:56:12.526  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 16:56:12.527  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-24 16:56:12.527  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-24 16:56:12.527  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-24 16:56:12.527  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 16:56:12.527  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 16:56:12.527  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-24 16:56:12.527  7067  7067 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-24 16:56:12.527  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-24 16:56:12.527  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 16:56:12.527  1974  1974 D WfdsService: Supplicant Connection state is changed : true
08-24 16:56:12.528  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-24 16:56:12.528  1974  2298 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-24 16:56:12.528  1974  2298 D WfdsService: Set the WFDS Monitor: true
08-24 16:56:12.528  1974  2298 D WfdsMonitor: WfdsMonitorThread create
08-24 16:56:12.529  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-24 16:56:12.529  1974  2298 D WfdsMonitor: WFDS Monitor is created and started
08-24 16:56:12.529  1974  2298 D WfdsService: WiFi: Supplicant connection re-established
08-24 16:56:12.529  1034  1540 E WifiNative: : [205,607,937 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-24 16:56:12.529  1034  1540 D WifiNative-wlan0: doBoolean: RECONNECT
08-24 16:56:12.529  1034  1540 D WifiNative-wlan0: RECONNECT: returned true
08-24 16:56:12.529  1034  1540 D WifiNative-wlan0: doString: [STATUS]
08-24 16:56:12.530  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
08-24 16:56:12.530  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
08-24 16:56:12.530  1034  1540 D WifiNative-wlan0:    returned wpa_state=DISCONNECTED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-24 16:56:12.530  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 16:56:12.530  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
08-24 16:56:12.531  1034  1538 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.531  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-24 16:56:12.531  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-24 16:56:12.531  1034  1558 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.531  1034  1558 I WifiNative-HAL: startHal
08-24 16:56:12.531  1034  1558 D wifi    : getting scan capabilities on interface[1] = 0x95786f60
08-24 16:56:12.531  1034  1558 D wifi    : failed to get capabilities : -3
08-24 16:56:12.531  1034  1558 E WifiScanningService: could not get scan capabilities
08-24 16:56:12.531  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-24 16:56:12.531  7067  7067 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-24 16:56:12.531  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-24 16:56:12.531  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-24 16:56:12.531  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-24 16:56:12.532  1034  7083 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-24 16:56:12.532  1034  7083 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-24 16:56:12.532  1034  1559 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.532  1974  7084 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-24 16:56:12.532  1034  1540 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-24 16:56:12.532  1034  1540 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-24 16:56:12.532   312   908 D CommandListener: Setting iface cfg
08-24 16:56:12.532   312   908 D CommandListener: Trying to bring up p2p0
08-24 16:56:12.532  1034  1540 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-24 16:56:12.532  1034  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-24 16:56:12.532  1034  1538 D LGWifiP2pService: P2pEnablingState
08-24 16:56:12.532  1974  7084 E CtrlSupplicant: Succeed to open control connection
08-24 16:56:12.533  1034  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.533  1034  1538 D LGWifiP2pService: P2p socket connection successfu,l
08-24 16:56:12.533  1034  1540 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-24 16:56:12.533  1034  1538 D LGWifiP2pService: P2pEnabledState
08-24 16:56:12.533  1034  1540 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-24 16:56:12.533  1974  7084 E CtrlSupplicant: Succeed to open monitor connection
08-24 16:56:12.533  1034  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-24 16:56:12.533  1034  1540 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-24 16:56:12.533  1034  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-24 16:56:12.533  1034  1540 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-24 16:56:12.533  1034  1540 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-24 16:56:12.534  7067  7067 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-24 16:56:12.534  1034  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-24 16:56:12.534  1034  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-24 16:56:12.534  1034  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-24 16:56:12.534  1034  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-24 16:56:12.534  1034  1538 D LGWifiP2pService: before postfix = G3
08-24 16:56:12.534  1034  1538 D WifiServerServiceExt: postfix byte check : 2
08-24 16:56:12.534  1034  1538 D LGWifiP2pService: after postfix = G3
08-24 16:56:12.534  1034  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-24 16:56:12.534  1034  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-24 16:56:12.534  1034  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-24 16:56:12.535  1034  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-24 16:56:12.535  1034  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-24 16:56:12.535  1034  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-24 16:56:12.535  1034  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-24 16:56:12.535  1034  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-24 16:56:12.535  1034  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-24 16:56:12.535  1034  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-24 16:56:12.536  1974  1974 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-24 16:56:12.536  1974  1974 D WfdsService: WifiP2pState is changed : true
08-24 16:56:12.536  1974  2298 D WfdsService: Receive the WFDS_ENABLE Method
08-24 16:56:12.536  1974  2298 D WfdsService: Set the WFDS Monitor: true
08-24 16:56:12.536  1974  2298 D WfdsService: Connected to the supplicant for wfds
08-24 16:56:12.536  1974  2298 D WfdsJNI : doCommand: WFDS_SET TRUE
08-24 16:56:12.536  7067  7067 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-24 16:56:12.536  1974  2298 D WfdsService: selectPreferredScanChannel [36]
08-24 16:56:12.537  1974  2298 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-24 16:56:12.537  1034  1538 D LGWifiP2pService: DeviceAddress: 
08-24 16:56:12.537  1034  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-24 16:56:12.537  1034  1538 D WifiNative-p2p0: P2P_FLUSH: returned false
08-24 16:56:12.537  1034  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-24 16:56:12.538  1034  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-24 16:56:12.538  1034  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-24 16:56:12.538  1974  7084 D WfdsMonitor: Supplicant connection established
08-24 16:56:12.538  1034  1538 D WifiNative-p2p0:    returned OK
08-24 16:56:12.538  1974  2298 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
08-24 16:56:12.538  1034  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-24 16:56:12.538  1034  1538 D WifiNative-p2p0: SAVE_CONFIG: returned false
08-24 16:56:12.538  1034  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-24 16:56:12.539  1034  1538 D LGWifiP2pService: InactiveState
08-24 16:56:12.539  1034  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.539  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.539  1034  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-24 16:56:12.542  1974  1974 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-24 16:56:12.542  1974  1974 D WfdsService: isConnected: false
08-24 16:56:12.542  1974  1974 I WfdStateTracker: handleP2pThisDeviceChanged
08-24 16:56:12.542  1974  1974 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-24 16:56:12.543  1974  1974 D WfdsService: Update P2p Interface State: 3
08-24 16:56:12.549  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-24 16:56:12.549  7067  7067 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:12.549  1974  7084 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 16:56:12.549  1034  7083 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 16:56:12.550  1034  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-24 16:56:12.550  1034  7083 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:12.550  1034  7083 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:12.550  1034  7083 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:12.550  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.550  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.550  1034  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.550  1034  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.550  7067  7067 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-24 16:56:12.550  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.550  1034  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.550  7067  7067 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.550  1034  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.550  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.550  1034  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.550  1034  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.550  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.550  1034  1540 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-24 16:56:12.550  1034  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.551  7067  7067 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.551  1034  1034 E WifiServerServiceExt: No p2p device connected
08-24 16:56:12.551  1034  1540 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-24 16:56:12.551  1034  1540 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-24 16:56:12.551  1034  1540 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-24 16:56:12.551  1974  7084 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:12.551  1974  2298 W WfdsService: DefaultState - msg [9441285] is not handled
08-24 16:56:12.551  7067  7067 E wpa_supplicant: disconnect_rssi_lvl: -100
08-24 16:56:12.551  1974  7084 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:12.551  1034  7083 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:12.552  1034  7083 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.552  1034  7083 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.552  1034  7083 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.552  1034  7083 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:12.552  1034  7083 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.552  1034  7083 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.552  1034  7083 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.553  1034  1540 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-24 16:56:12.554  1034  1540 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-24 16:56:12.554  1034  1540 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-24 16:56:12.554  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-24 16:56:12.556  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-24 16:56:12.557  7067  7067 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:12.557  7067  7067 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-24 16:56:12.557  7067  7067 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.558  1034  1540 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-24 16:56:12.558  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.558  7067  7067 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.558  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:12.558  1034  1540 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-24 16:56:12.559  1034  1540 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-24 16:56:12.559  1034  1540 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-24 16:56:12.559  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-24 16:56:12.559  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-24 16:56:12.559  1974  7084 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:12.559  7067  7067 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 16:56:12.559  1974  7084 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:12.560  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 16:56:12.560  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:12.560  1034  7083 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:12.560  1034  7083 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:12.560  1034  7083 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:12.560  1034  7083 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.560  1034  7083 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.560  1034  7083 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.560  1034  7083 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:12.560  1034  7083 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.560  1034  7083 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.560  1034  1540 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-24 16:56:12.560  1034  7083 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:12.560  1034  1540 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-24 16:56:12.560  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-24 16:56:12.560  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 16:56:12.560  1034  7083 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 16:56:12.560  1034  7083 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 16:56:12.561  1034  1540 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-24 16:56:12.561  1034  1540 D WifiNative-wlan0: doBoolean: SCAN
08-24 16:56:12.561  1034  1540 D WifiNative-wlan0: SCAN: returned false
08-24 16:56:12.561  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=205640  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
08-24 16:56:12.562  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=205641  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
08-24 16:56:12.562  7040  7040 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-24 16:56:12.564  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=205642  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 16:56:12.564  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-24 16:56:12.565  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:12.565  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:12.565  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:12.565  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:12.565  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 16:56:12.566  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=205645  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 16:56:12.566  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:12.567  1034  1540 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 16:56:12.567  1034  1540 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 16:56:12.567  1034  1540 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 16:56:12.568  1034  1540 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 16:56:12.568  1034  1540 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 16:56:12.569  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:12.569  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:12.569  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:12.569  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:12.569  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-24 16:56:12.569  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 16:56:12.569  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-24 16:56:12.570  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:12.586  7040  7040 I HubEmail: JNI_OnLoad()
08-24 16:56:12.586  7040  7040 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-24 16:56:12.586  7040  7040 I HubEmail: registerNatives()
08-24 16:56:12.586  7040  7040 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-24 16:56:12.586  7040  7040 I HubEmail: registerNativeMethods()
08-24 16:56:12.586  7040  7040 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-24 16:56:12.587  7040  7040 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-24 16:56:12.587  3449  3449 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-24 16:56:12.587  3449  3449 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:56:12.588  3449  3449 I LgeMiscReceiver: networkInfo.isConnected() = false
08-24 16:56:12.621  1034  1920 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7091 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-24 16:56:12.626  7040  7090 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:12.626  6907  7087 W FormManager: Network not available. Please check & try again.
08-24 16:56:12.629  6907  7088 V FormManager: Network unavailable.
08-24 16:56:12.632  6907  7088 V FormManager: Network unavailable.
,08-24 16:56:12.638  1034  1049 I ActivityManager: Killing 6517:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-24 16:56:12.679  1034  1603 W libprocessgroup: failed to open /acct/uid_10061/pid_6517/cgroup.procs: No such file or directory
,08-24 16:56:12.767  7091  7091 D LgDataFeature: LgDataFeature() Constructor: none
08-24 16:56:12.767  7091  7091 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 16:56:12.771  7091  7091 D PhoneMonitor: Register our PhoneStateListener
08-24 16:56:12.795  7091  7091 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-24 16:56:12.800  7091  7091 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-24 16:56:12.830  7091  7091 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-24 16:56:12.832  7091  7091 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-24 16:56:12.834  7091  7091 D TelephonyAutoProfiling: [parse] Load xml
08-24 16:56:12.841  7091  7091 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-24 16:56:12.841  7091  7091 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-24 16:56:12.841  7091  7091 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-24 16:56:12.841  7091  7091 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-24 16:56:12.842  7091  7091 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-24 16:56:12.842  7091  7091 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-24 16:56:12.842  7091  7091 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-24 16:56:12.842  7091  7091 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-24 16:56:12.842  7091  7091 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-24 16:56:12.842  7091  7091 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-24 16:56:12.842  7091  7091 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-24 16:56:12.843  7091  7091 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-24 16:56:12.843  7091  7091 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-24 16:56:12.843  7091  7091 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-24 16:56:12.843  7091  7091 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
,08-24 16:56:12.843  7091  7091 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-24 16:56:12.843  7091  7091 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-24 16:56:12.858  7091  7091 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-24 16:56:12.886  1034  1603 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7110 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 16:56:12.886  1034  1603 I ActivityManager: Killing 6078:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-24 16:56:12.939  1034  1920 W libprocessgroup: failed to open /acct/uid_10097/pid_6078/cgroup.procs: No such file or directory
,08-24 16:56:13.187  1034  1049 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7131 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-24 16:56:13.190  1034  1049 I ActivityManager: Killing 6571:com.lge.eula/1000 (adj 15): empty #17
08-24 16:56:13.192  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-24 16:56:13.193  1034  7083 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-24 16:56:13.193  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-24 16:56:13.193  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-24 16:56:13.193  1034  7083 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-24 16:56:13.194  1034  1540 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 16:56:13.195  1034  1540 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 16:56:13.196  1034  1540 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 16:56:13.198  1034  1540 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 16:56:13.201  7067  7067 E wpa_supplicant: USIM:  scard_init function
08-24 16:56:13.202  7067  7067 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-24 16:56:13.203  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-24 16:56:13.203  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-24 16:56:13.211  1034  1540 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-24 16:56:13.269  1034  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_6571/cgroup.procs: No such file or directory
,08-24 16:56:13.270  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=206349  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-24 16:56:13.280  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=206359  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-24 16:56:13.282  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:13.282  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-24 16:56:13.285  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:13.289  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.289  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.290  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-24 16:56:13.290  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 16:56:13.290  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-24 16:56:13.319  7067  7067 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-24 16:56:13.322  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-24 16:56:13.322  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-24 16:56:13.322  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-24 16:56:13.322  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-24 16:56:13.323  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 16:56:13.323  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 16:56:13.325  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=206403  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-24 16:56:13.325  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=206404  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-24 16:56:13.326  1034  1540 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206405
08-24 16:56:13.327  7067  7067 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 16:56:13.328  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-24 16:56:13.328  7067  7067 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 16:56:13.329  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 16:56:13.329  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 16:56:13.330  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-24 16:56:13.330  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 16:56:13.330  1034  7083 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 16:56:13.331  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-24 16:56:13.331  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 16:56:13.331  1034  7083 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 16:56:13.332  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 16:56:13.332  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-24 16:56:13.338  1034  1540 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206417
08-24 16:56:13.338  1034  1540 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206417
08-24 16:56:13.339  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206418
08-24 16:56:13.339  1034  1540 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206418
08-24 16:56:13.340  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=206419  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-24 16:56:13.343  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:13.343  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:13.344  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.344  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.344  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-24 16:56:13.345  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:13.347  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=206426  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-24 16:56:13.350  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.351  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.351  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-24 16:56:13.352  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 16:56:13.352  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-24 16:56:13.352  1034  1540 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:13.353  1034  1540 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:13.353  1034  1540 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:13.353  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:13.354  1034  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:13.354  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=206433  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-24 16:56:13.355  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=206434  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-24 16:56:13.356  1034  1540 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206435
08-24 16:56:13.356  1034  1540 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206435
08-24 16:56:13.357  1034  1540 D WifiNative-wlan0: doString: [STATUS]
08-24 16:56:13.357  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 16:56:13.357  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 16:56:13.358  1034  1540 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-24 16:56:13.360  1034  1540 I WifiServiceExtension: setVHTCapabilityType  : false
08-24 16:56:13.365  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:13.365  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:13.367  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:13.367  1034  1540 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-24 16:56:13.367  1034  1540 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-24 16:56:13.374  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.374  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.375  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-24 16:56:13.377  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.377  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.377  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-24 16:56:13.383  1034  1540 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-24 16:56:13.383  1034  1546 D ConnectivityService: Got NetworkAgent Messenger
08-24 16:56:13.383  1034  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 16:56:13.383  1034  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-24 16:56:13.383  1034  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 16:56:13.383  1034  1546 D ConnectivityService: NetworkAgent connected
,08-24 16:56:13.384  1034  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 16:56:13.385  1034  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 16:56:13.390  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:13.390  1034  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 16:56:13.390  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:13.390  1034  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 16:56:13.390  1034  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 16:56:13.390  1034  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 16:56:13.390  1034  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 16:56:13.391  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:13.394  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:13.394  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:13.394  1034  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-24 16:56:13.395   312   908 D CommandListener: Setting iface cfg
08-24 16:56:13.397  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:13.420  1034  1967 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7163 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 16:56:13.422  1034  1967 I ActivityManager: Killing 6590:com.lge.bnr/1000 (adj 15): empty #17
,08-24 16:56:13.464  1034  1540 E WifiStateMachine: Start Dhcp Watchdog 2
08-24 16:56:13.465  1034  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=206544  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-24 16:56:13.465  1034  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=206544  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-24 16:56:13.466  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=206545  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 16:56:13.466  1034  7158 D DhcpStateMachine: StoppedState
08-24 16:56:13.467  1034  7158 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:13.467  1034  7158 D DhcpStateMachine: WaitBeforeStartState
08-24 16:56:13.469  1034  1049 W libprocessgroup: failed to open /acct/uid_1000/pid_6590/cgroup.procs: No such file or directory
08-24 16:56:13.473  1034  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=206552  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 16:56:13.473  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 16:56:13.473  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-24 16:56:13.474  1034  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=206553  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 16:56:13.475  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=206553  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 16:56:13.476  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:161380] from screen [on:0 period:-1123209052] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-24 16:56:13.477  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1123209051] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-24 16:56:13.477  1034  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-24 16:56:13.482  1034  1546 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-24 16:56:13.482  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:13.482  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:13.483  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:13.483  1034  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:13.483  1034  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:13.484  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:13.484  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:13.485  1034  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-24 16:56:13.485  1034  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:13.486  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:13.486  1034  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:13.486  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 16:56:13.486  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-24 16:56:13.488  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=106,0,0
08-24 16:56:13.488  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=106,0,0
08-24 16:56:13.489  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
,08-24 16:56:13.489  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-24 16:56:13.489  1034  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
,08-24 16:56:13.489  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 0
08-24 16:56:13.490  1034  1540 D WifiNative-wlan0: SET ps 0: returned true
08-24 16:56:13.490  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-24 16:56:13.490  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-24 16:56:13.490  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-24 16:56:13.491  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@bbbb4d9 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:13.491  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@bbbb4d9 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:13.491  1034  7158 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:13.491  1034  7158 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-24 16:56:13.492  1034  1540 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-24 16:56:13.492  1034  1540 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 16:56:13.492  1034  1540 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-24 16:56:13.493   312   908 D CommandListener: Setting iface cfg
08-24 16:56:13.493   312   908 D CommandListener: Trying to bring up wlan0
08-24 16:56:13.494  1034  1540 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-24 16:56:13.495  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 16:56:13.495  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-24 16:56:13.495  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-24 16:56:13.495  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-24 16:56:13.495  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 16:56:13.496  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:13.496  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:13.496  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 16:56:13.496  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 16:56:13.496  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-24 16:56:13.496  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-24 16:56:13.497  1034  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-24 16:56:13.497  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 16:56:13.516  7163  7163 I art     : Almond Protected OAT
08-24 16:56:13.516  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
08-24 16:56:13.517  1034  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-24 16:56:13.518  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 16:56:13.518  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 16:56:13.519  1034  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 16:56:13.519  1034  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 16:56:13.520  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 16:56:13.521  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 16:56:13.522  1034  1546 D ConnectivityService: Updat,e of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-24 16:56:13.522  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-24 16:56:13.523  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-24 16:56:13.523  1034  1540 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-24 16:56:13.524  1034  1546 D ConnectivityService: ignoring duplicate network state non-change
08-24 16:56:13.529  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:13.529  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:13.530  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.530  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.530  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-24 16:56:13.531  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:13.534  1034  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-24 16:56:13.536  1034  1546 D ConnectivityService: Adding iface wlan0 to network 101
08-24 16:56:13.543  1034  1540 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-24 16:56:13.570  1034  1546 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-24 16:56:13.570  1034  1546 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-24 16:56:13.571  1034  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 16:56:13.571  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 16:56:13.572  1034  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 16:56:13.572  1034  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 16:56:13.573  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 16:56:13.573  1034  1540 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 16:56:13.579  1034  1546 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-24 16:56:13.579   312   908 E Netd    : netlink response contains error (File exists)
08-24 16:56:13.580  1034  1546 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-24 16:56:13.581  1034  1546 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-24 16:56:13.581  1034  1546 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-24 16:56:13.581  1034  1546 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-24 16:56:13.582  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:13.582  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-24 16:56:13.584  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:13.584  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.584  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.584  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-24 16:56:13.585  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-24 16:56:13.586  1974  1974 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-24 16:56:13.587  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.587  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.587  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-24 16:56:13.588  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-24 16:56:13.591  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.591  1034  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-24 16:56:13.591  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:13.591  1034  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-24 16:56:13.591  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-24 16:56:13.591  1034  1546 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-24 16:56:13.591  1034  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-24 16:56:13.591  1034  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 16:56:13.591  1034  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:13.591  1034  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:13.591  1034  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 16:56:13.591  1034  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-24 16:56:13.591  1034  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:13.591  1034  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:13.591  1034  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-24 16:56:13.591  1034  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-24 16:56:13.591  1034  1546 D ConnectivityService: currentScore = 0, newScore = 20
08-24 16:56:13.591  1034  1546 D ConnectivityService:    accepting network in place of null
08-24 16:56:13.591  1034  1546 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
0,8-24 16:56:13.592  1034  1540 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:13.592  1034  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 16:56:13.592  1876  1876 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:13.592  1876  1876 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 16:56:13.593  1034  1546 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-24 16:56:13.593  1034  1546 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-24 16:56:13.593  1034  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-24 16:56:13.596   312  7185 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-24 16:56:13.598  7163  7163 D WeatherApplication: removeAccount
08-24 16:56:13.600  1034  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:13.600  1034  1546 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-24 16:56:13.601  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-24 16:56:13.602  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 16:56:13.602  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 16:56:13.602  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-24 16:56:13.605  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:13.605  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 16:56:13.605  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:13.608  1034  1546 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-24 16:56:13.609  1034  1546 D ConnectivityService: validation of new default Network = false
08-24 16:56:13.609  1034  1546 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-24 16:56:13.609  1034  1546 D DSQN    : enableDataServiceNotify 
08-24 16:56:13.609  1034  1546 D DSQN    : start dsqn bin
08-24 16:56:13.611  7163  7163 D WeatherApplication: Account.length = 0
08-24 16:56:13.611  7163  7163 E WeatherApplication: OPERATOR:OPEN
08-24 16:56:13.612  1034  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-24 16:56:13.613  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:13.613  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 16:56:13.614  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:13.617  1034  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-24 16:56:13.617  1034  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:13.617  1034  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:13.617  1034  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:13.618  1605  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 16:56:13.615  7186  7186 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 16:56:13.615  7186  7186 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:13.621  7163  7163 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:13
08-24 16:56:13.629  7163  7163 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 16:56:13.630  7163  7163 D Weather.Utils: 2 : All the weather widget is gone.
08-24 16:56:13.633  7186  7186 E DSQN    : DSQN ssw
08-24 16:56:13.633  7163  7163 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 16:56:13.635  7163  7163 D WeatherAncestor: connectivity changed - connection : true
08-24 16:56:13.636  7163  7163 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-24 16:56:13.637  1840  7188 I CheckinService: active receiver: enabled
,08-24 16:56:13.645  1840  7188 I CheckinService: Preparing to send checkin request
08-24 16:56:13.645  1840  7188 I EventLogService: Accumulating logs since 1472050424404
08-24 16:56:13.647  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 16:56:13.648  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:13.648  7163  7163 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 16:56:13.648  7163  7163 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 16:56:13.648  7163  7163 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-24 16:56:13.649  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:13.652   312  7185 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-24 16:56:13.666  7163  7163 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 16:56:13.666  7163  7163 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:13
08-24 16:56:13.684   312  7185 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-24 16:56:13.692  1034  7158 D DhcpStateMachine: DHCPV4 request on wlan0
08-24 16:56:13.693  1034  7158 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-24 16:56:13.693  1034  7158 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-24 16:56:13.685  7193  7193 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:13.685  7193  7193 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 16:56:13.704  7193  7193 I dhcpcd  : version 5.5.6 starting
08-24 16:56:13.705  1034  1920 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7194 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 16:56:13.706  7193  7193 E dhcpcd  : get_duid: m
08-24 16:56:13.706  7193  7193 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-24 16:56:13.706  7193  7193 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-24 16:56:13.706  1034  1920 I ActivityManager: Killing 2225:com.lge.music/u0a34 (adj 15): empty #17
08-24 16:56:13.717   312   907 D LGDataListener: argv[0]=dsqncommand
08-24 16:56:13.717   312   907 D LGDataListener: argv[1]=wlan0
08-24 16:56:13.717   312   907 D LGDataListener: argv[2]=1
08-24 16:56:13.717   312   907 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-24 16:56:13.717  1034  1094 D DSQN    : DSQM DsqnNotification wlan0  1
08-24 16:56:13.717  1034  1094 D DSQN    : start to monitor internet connection
,08-24 16:56:13.723  1034  1034 D MediaSessionService: clear user.mLastMediaButtonReceiver
08-24 16:56:13.724   318   318 V AudioFlinger: 2225 died, releasing its sessions
08-24 16:56:13.724   318   318 V AudioFlinger:  pid 1876 @ 0
08-24 16:56:13.724   318   318 V AudioFlinger:  pid 3449 @ 1
08-24 16:56:13.724   318   318 V AudioFlinger:  pid 3449 @ 2
08-24 16:56:13.758  1034  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 14:56:13 GMT], X-Android-Received-Millis=[1472050573758], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472050573716]}
08-24 16:56:13.758  1034  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-24 16:56:13.758  1034  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-24 16:56:13.759  1034  1546 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-24 16:56:13.759  1034  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-24 16:56:13.759  1034  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 16:56:13.759  1034  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:13.759  1034  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 16:56:13.759  1034  1546 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-24 16:56:13.759  1034  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-24 16:56:13.759  1034  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:13.759  1034  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:13.759  1034  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:13.760  1034  1546 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 16:56:13.760  1605  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 16:56:13.760  1034  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-24 16:56:13.760  1034  1540 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:13.760  1034  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 16:56:13.761  1876  1876 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:13.761  1876  1876 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 16:56:13.769  1840  7188 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-24 16:56:13.770  1034  1049 W libprocessgroup: failed to open /acct/uid_10034/pid_2225/cgroup.procs: No such file or directory
,08-24 16:56:13.776  7193  7193 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-24 16:56:13.776  7193  7193 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-24 16:56:13.776  7193  7193 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-24 16:56:13.776  7193  7193 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-24 16:56:13.777  7193  7193 D dhcpcd  : wlan0: sending REQUEST (xid 0xd65cf781), next in 4.25 seconds
,08-24 16:56:13.802  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 16:56:13.804  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:13.805  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:13.808  7193  7193 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-24 16:56:13.825  7193  7193 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-24 16:56:13.825  7193  7193 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-24 16:56:13.825  7193  7193 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-24 16:56:13.825  7193  7193 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-24 16:56:13.825  7193  7193 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-24 16:56:13.825  7193  7193 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-24 16:56:13.826  7193  7193 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-24 16:56:13.826  7193  7193 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-24 16:56:13.899  1034  1603 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7223 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-24 16:56:13.947   278   414 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 16:56:13.947   278   414 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-24 16:56:13.947   278   414 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 16:56:13.948  7194  7245 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-24 16:56:13.950   278   414 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 16:56:13.950   278   414 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-24 16:56:13.950   278   414 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 16:56:13.951  7194  7245 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-24 16:56:13.960  7223  7223 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-24 16:56:13.960  7223  7223 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-24 16:56:13.981   278   414 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-24 16:56:13.981   278   414 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-24 16:56:13.981   278   414 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 16:56:13.984  7223  7223 I MultiDex: VM with version 2.1.0 has multidex support
08-24 16:56:13.984  7223  7223 I MultiDex: install
08-24 16:56:13.984  7223  7223 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-24 16:56:13.988  7194  7248 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-24 16:56:13.991  7223  7223 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-24 16:56:13.999   278   414 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 16:56:13.999   278   414 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-24 16:56:13.999   278   414 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 16:56:14.000  7194  7248 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-24 16:56:14.096  1034  7158 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-24 16:56:14.097  1034  7158 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-24 16:56:14.097  1034  7158 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-24 16:56:14.097  1034  7158 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-24 16:56:14.097  1034  7158 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-24 16:56:14.097  1034  7158 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 16:56:14.097  1034  7158 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-24 16:56:14.097  1034  7158 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-24 16:56:14.098  1034  7158 D DhcpStateMachine: RunningState
,08-24 16:56:14.182  7194  7194 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-24 16:56:14.195  7194  7194 I LibraryLoader: Loading: webviewchromium
,08-24 16:56:14.199  7194  7194 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 7285-7291)
08-24 16:56:14.199  7194  7194 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 16:56:14.211  7194  7194 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {336e46a2}
,08-24 16:56:14.214  7194  7194 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 16:56:14.215  7194  7194 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 16:56:14.241  7194  7194 I BrowserStartupController: Initializing chromium process, renderers=0
08-24 16:56:14.242  7194  7194 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 16:56:14.263  7194  7194 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-24 16:56:14.264  7194  7194 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-24 16:56:14.265  7194  7194 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-24 16:56:14.268  7223  7242 D LgDataFeature: LgDataFeature() Constructor: none
08-24 16:56:14.268  7223  7242 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 16:56:14.280   318  3991 V AudioPolicyService: registerClient() client 0xb558a2a0, uid 10093
,08-24 16:56:14.283  7194  7283 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-24 16:56:14.287  7194  7194 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 16:56:14.287  7194  7194 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 16:56:14.287  7194  7194 I Adreno-EGL: Build Date: 12/12/14 금
08-24 16:56:14.287  7194  7194 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 16:56:14.287  7194  7194 I Adreno-EGL: Remote Branch: 
08-24 16:56:14.287  7194  7194 I Adreno-EGL: Local Patches: 
08-24 16:56:14.287  7194  7194 I Adreno-EGL: Reconstruct Branch: 
,08-24 16:56:14.381  7194  7194 I NSApplication: Starting up...
,08-24 16:56:14.446  1034  1049 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7296 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-24 16:56:14.447  1034  1049 I ActivityManager: Killing 6012:com.android.vending/u0a44 (adj 15): empty #17
08-24 16:56:14.462   338   338 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 311us total 16.119ms
,08-24 16:56:14.476   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 292us total 13.460ms
08-24 16:56:14.480  7305  7305 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-24 16:56:14.489   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 258us total 12.280ms
08-24 16:56:14.530  1034  2056 W libprocessgroup: failed to open /acct/uid_10044/pid_6012/cgroup.procs: No such file or directory
08-24 16:56:14.530  7305  7305 I dex2oat : dex2oat took 49.645ms (threads: 4)
,08-24 16:56:14.536  1034  1395 D PowerManagerServiceEx: acquireWakeLockInternal: lock=650044150, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
08-24 16:56:14.536  1034  1395 V AlarmManager: ELAPSED_WAKEUP set : Alarm{85dc180 type 2 when 207594 com.google.android.gms} when 207594
08-24 16:56:14.539  1034  2088 D WifiServiceImplEx: setWifiEnabled: false pid=6695, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 16:56:14.539  1034  2088 D WifiService: setWifiEnabled: false pid=6695, uid=10118
08-24 16:56:14.539  1034  2088 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 16:56:14.550  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 16:56:14.551  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 16:56:14.551  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-24 16:56:14.552  7223  7242 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 16:56:14.552  7223  7242 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 16:56:14.552  7223  7242 I Adreno-EGL: Build Date: 12/12/14 금
08-24 16:56:14.552  7223  7242 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 16:56:14.552  7223  7242 I Adreno-EGL: Remote Branch: 
08-24 16:56:14.552  7223  7242 I Adreno-EGL: Local Patches: 
08-24 16:56:14.552  7223  7242 I Adreno-EGL: Reconstruct Branch: 
08-24 16:56:14.552  1034  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-24 16:56:14.552  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-24 16:56:14.553  1034  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-24 16:56:14.553  7296  7296 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 16:56:14.553  1034  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-24 16:56:14.553  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-24 16:56:14.553  1034  1540 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-24 16:56:14.554  1034  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 16:56:14.554  1034  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 16:56:14.554  1034  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 16:56:14.554  1034  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 16:56:14.560  1034  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 16:56:14.560  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 16:56:14.561  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 16:56:14.564  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 16:56:14.564  1034  1538 D LGWifiP2pService: InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:14.564  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 16:56:14.564  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 16:56:14.566  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
08-24 16:56:14.566  1034  7158 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:14.566   312   908 D CommandListener: Clearing all IP addresses on wlan0
,08-24 16:56:14.571  2640  2640 D [Concierge]Service: onStartCommand(). Type : 9
08-24 16:56:14.598  1034  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-24 16:56:14.598  1034  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-24 16:56:14.599  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:14.599  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:14.599  1034  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@33ecef61
08-24 16:56:14.599  1034  1538 D LGWifiP2pService: P2pDisablingState
08-24 16:56:14.600  1034  1538 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:14.600  1034  1538 D LGWifiP2pService: p2p socket connection lost
08-24 16:56:14.600  1034  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:14.600  1034  1538 D LGWifiP2pService: P2pDisabledState
08-24 16:56:14.600  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:14.600  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:14.601  1034  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-24 16:56:14.601  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:14.601  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:14.602  1034  1540 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 16:56:14.602  1034  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-24 16:56:14.602  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 16:56:14.602  1034  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:14.602  1034  1538 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:14.602  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 16:56:14.603  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 16:56:14.603  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 16:56:14.603  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
08-24 16:56:14.605  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-24 16:56:14.607  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:14.607  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:14.609  1974  1974 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-24 16:56:14.609  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:14.613  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:14.613  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:14.613  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 16:56:14.614  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-24 16:56:14.618  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 16:56:14.618  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:14.618  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 16:56:14.619  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-24 16:56:14.619  1034  1558 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:14.619  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-24 16:56:14.619  1034  1559 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:14.620  1974  1974 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 16:56:14.620  1974  1974 D WfdsService: WifiP2pState is changed : false
08-24 16:56:14.620  1974  2298 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-24 16:56:14.620  1974  2298 D WfdsService: Set the WFDS Monitor: false
08-24 16:56:14.621  1974  2298 D WfdsMonitor: WFDS Monitor is stopped
08-24 16:56:14.621  1974  7084 D CtrlSupplicant: Received on exit socket, terminate
08-24 16:56:14.621  1974  2298 D WfdsService: STATE : WfdsDisabledState - enter
08-24 16:56:14.621  1974  7084 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-24 16:56:14.621  1974  7084 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-24 16:56:14.621  1974  7084 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-24 16:56:14.621  1974  2299 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-24 16:56:14.621  1974  2298 W WfdsService: DefaultState - msg [9445378] is not handled
08-24 16:56:14.635  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:14.635  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:14.636  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 16:56:14.642   312   908 D CommandListener: Clearing all IP addresses on wlan0
08-24 16:56:14.642  1034  1546 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-24 16:56:14.642  1034  1546 D DSQN    : disableDataServiceNotify
08-24 16:56:14.642  1034  1546 D DSQN    : stop dsqn bin
08-24 16:56:14.643  1034  1540 D WifiNative-p2p0: doBoolean: TERMINATE
08-24 16:56:14.644  1034  1540 D WifiNative-p2p0: TERMINATE: returned true
08-24 16:56:14.644  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 16:56:14.644  1034  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 16:56:14.644  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 16:56:14.645  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-24 16:56:14.646  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:14.646  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:14.646  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 16:56:14.647  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-24 16:56:14.647  1034  1546 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-24 16:56:14.647  1034  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:14.647  1034  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-24 16:56:14.648  1034  1546 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:14.648  1034  1546 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-24 16:56:14.648  1034  1546 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-24 16:56:14.648  1034  1546 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-24 16:56:14.648  1034  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 16:56:14.649  1605  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-24 16:56:14.649  1034  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:14.649  1034  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 16:56:14.649  1034  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:14.649  1034  1546 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:14.649  1034  1546 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:14.649  1034  1546 D NetworkManagementService: Removing idletimer
08-24 16:56:14.649  1034  1546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:14.649  1034  1546 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-24 16:56:14.649  1876  1876 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:14.649  1034  1546 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-24 16:56:14.650  1974  1974 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-24 16:56:14.650  1876  1876 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 16:56:14.650  1034  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:14.650  1034  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:14.650  1034  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-24 16:56:14.650  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 16:56:14.650  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-24 16:56:14.651  1034  1540 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabil,ities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:14.651  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:14.651  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:14.651  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:14.651  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:14.651  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:56:14.651  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:56:14.651  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:14.651  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:14.651  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:56:14.651  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:14.651  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:56:14.652  1034  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 16:56:14.652  1034  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 16:56:14.652  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-24 16:56:14.652  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 16:56:14.652  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 16:56:14.652  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 16:56:14.653  1034  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 16:56:14.654  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:14.654  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:14.654  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:14.654  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:14.654  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:56:14.654  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:56:14.654  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:14.654  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:14.654  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:56:14.654  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:14.654  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:56:14.654  1034  1034 D LocSvc_java: Sending msg: 4, arg1:0 arg2:1
08-24 16:56:14.654  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 16:56:14.654  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 16:56:14.654  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 16:56:14.660  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-24 16:56:14.660  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:14.661  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:14.664  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:14.682  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 16:56:14.682  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:14.683  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 16:56:14.693  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 16:56:14.694  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:14.694  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:14.741  7067  7067 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-24 16:56:14.741  7067  7067 I wpa_supplicant: monitor socket send errors count : 1
08-24 16:56:14.741  7067  7067 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1974-4\x00 that cannot receive messages
,08-24 16:56:14.746  1034  7083 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-24 16:56:14.746  1034  7083 D WifiMonitor: Dropping event because (p2p0) is stopped
08-24 16:56:14.757  1034  2010 I art     : Explicit concurrent mark sweep GC freed 123672(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.483ms total 99.393ms
,08-24 16:56:14.767  7067  7067 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 16:56:14.768  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-24 16:56:14.768  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 16:56:14.768  1034  7083 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 16:56:14.768  1034  7083 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-24 16:56:14.768  1034  1540 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=207847
08-24 16:56:14.768  1034  1540 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=207847
08-24 16:56:14.770  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 16:56:14.770  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 16:56:14.770  7067  7067 W wpa_supplicant: USIM:  scard_deinit function
08-24 16:56:14.770  1034  1540 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=207849  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-24 16:56:14.770  1034  1540 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=207849  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-24 16:56:14.776  1034  1096 D Tethering: InitialState.processMessage what=4
,08-24 16:56:14.779  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 16:56:14.783  1034  1540 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:14.783  1034  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:14.783  1034  7158 D DhcpStateMachine: StoppedState
08-24 16:56:14.784  1034  7158 D DhcpStateMachine: StoppedState{ when=-180ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:14.784  1034  1540 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-24 16:56:14.784  1034  1540 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-24 16:56:14.901  7067  7067 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-24 16:56:14.901  1034  7083 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-24 16:56:14.901  1034  7083 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-24 16:56:14.901  1034  7083 D WifiMonitor: Disconnecting from the supplicant, no more events
08-24 16:56:14.902  1034  1540 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
,08-24 16:56:14.933  7223  7242 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 16:56:14.933  7223  7242 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 16:56:14.933  7223  7242 I Adreno-EGL: Build Date: 12/12/14 금
08-24 16:56:14.933  7223  7242 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 16:56:14.933  7223  7242 I Adreno-EGL: Remote Branch: 
08-24 16:56:14.933  7223  7242 I Adreno-EGL: Local Patches: 
08-24 16:56:14.933  7223  7242 I Adreno-EGL: Reconstruct Branch: 
,08-24 16:56:14.939  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 16:56:14.943  6390  6832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-24 16:56:14.955  2209  2209 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:56:14.962  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 16:56:14.962  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:14.963  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 16:56:14.963  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-24 16:56:14.964  7003  7003 I AppUp4:CustModeStarterReceiver: onReceive
08-24 16:56:14.966  7003  7003 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bc181cb
,08-24 16:56:14.966  7003  7003 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 16:56:14.966  7003  7003 D AppUp4:CustFacade: isPhone : true
08-24 16:56:14.966  7003  7003 D AppUp4:CustModeStarterReceiver: begin check event
08-24 16:56:14.967  7003  7003 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-24 16:56:14.970  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:14.970  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 16:56:14.972  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 16:56:14.973  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 16:56:14.978  7040  7040 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-24 16:56:14.981  4300  7336 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:14.981  4300  7336 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 16:56:14.980  4300  7335 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 16:56:14.982  7223  7242 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 16:56:14.982  7223  7242 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 16:56:14.982  7223  7242 I Adreno-EGL: Build Date: 12/12/14 금
08-24 16:56:14.982  7223  7242 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 16:56:14.982  7223  7242 I Adreno-EGL: Remote Branch: 
08-24 16:56:14.982  7223  7242 I Adreno-EGL: Local Patches: 
08-24 16:56:14.982  7223  7242 I Adreno-EGL: Reconstruct Branch: 
08-24 16:56:14.996  7040  7337 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 16:56:15.002  3449  3449 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 16:56:15.002  3449  3449 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:15.003  3449  3449 I LgeMiscReceiver: networkInfo.isConnected() = false
08-24 16:56:15.004  1974  1974 D WfdsService: Supplicant Connection state is changed : false
08-24 16:56:15.004  1974  2298 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-24 16:56:15.004  1974  2298 D WfdsService: Set the WFDS Monitor: false
08-24 16:56:15.004  1974  2298 D WfdsMonitor: WFDS Monitor is stopped
08-24 16:56:15.004  1034  1540 D WifiOffDelayIfNotUsed: stopMonitoring
08-24 16:56:15.004  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 16:56:15.004  1034  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 16:56:15.004  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 16:56:15.007  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:15.007  1974  1974 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 16:56:15.008  2468  2468 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 16:56:15.009  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-24 16:56:15.010  1034  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-24 16:56:15.010  1034  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-24 16:56:15.011  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:15.012  6907  7340 V FormManager: Network unavailable.
08-24 16:56:15.012  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:15.012  6907  7339 W FormManager: Network not available. Please check & try again.
08-24 16:56:15.014  6907  7340 V FormManager: Network unavailable.
08-24 16:56:15.016  7091  7091 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 16:56:15.016  7091  7091 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-24 16:56:15.030  7163  7163 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:15
,08-24 16:56:15.032  7163  7163 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 16:56:15.032  7163  7163 D Weather.Utils: 2 : All the weather widget is gone.
08-24 16:56:15.033  7163  7163 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 16:56:15.033  7163  7163 D WeatherAncestor: connectivity changed - connection : true
08-24 16:56:15.033  7163  7163 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6c470c1
08-24 16:56:15.034  7163  7163 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 16:56:15.034  7163  7163 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 16:56:15.034  7163  7163 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-24 16:56:15.034  7163  7163 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 16:56:15.034  7163  7163 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:15
08-24 16:56:15.043   312  7346 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-24 16:56:15.043  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-24 16:56:15.044  1840  7188 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-24 16:56:15.052  1840  7188 I CheckinService: active receiver: disabled
,08-24 16:56:15.060  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 16:56:15.060  6810  6810 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 16:56:15.060  6810  6810 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 16:56:15.060  6810  6810 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 16:56:15.061  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 16:56:15.062  6810  6810 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 16:56:15.062  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-24 16:56:15.062  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 16:56:15.062  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 16:56:15.062  6810  6810 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 16:56:15.062  6810  6810 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-24 16:56:15.068  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 16:56:15.071  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 16:56:15.078  6907  7348 W FormManager: Network not available. Please check & try again.
08-24 16:56:15.079  6907  7349 V FormManager: Network unavailable.
,08-24 16:56:15.081  6907  7349 V FormManager: Network unavailable.
08-24 16:56:15.082  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:15.101  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 16:56:15.104  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 16:56:15.106  6907  7351 W FormManager: Network not available. Please check & try again.
08-24 16:56:15.109  6907  7352 V FormManager: Network unavailable.
08-24 16:56:15.109  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:15.119  6907  7352 V FormManager: Network unavailable.
,08-24 16:56:15.121  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 16:56:15.121  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 16:56:15.123  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 16:56:15.124  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 16:56:15.129  4300  7353 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 16:56:15.130  4300  7354 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 16:56:15.130  4300  7354 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 16:56:15.186  1034  1967 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7355 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-24 16:56:15.191  1034  1395 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1a61edf3 type 2 when 208206 com.google.android.gms} when 208206
,08-24 16:56:15.321  7355  7355 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-24 16:56:15.321  7355  7355 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-24 16:56:15.330  7355  7355 V [BNRBootReceiver]: Boot Receiver Return
,08-24 16:56:15.332  7355  7355 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 16:56:15.335  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 16:56:15.340  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 16:56:15.341  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 16:56:15.341  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 16:56:15.345  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:15.354  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:15.373  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:15.374  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 16:56:15.377  6861  6861 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 16:56:15.384  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:15.397  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:15.412  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:15.428  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 16:56:15.429  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 16:56:15.432  6861  6861 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 16:56:15.438  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-24 16:56:15.442  6810  6810 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-24 16:56:15.448  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:15.457  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:15.465  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:15.475  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 16:56:15.475  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:15.477  6861  6861 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 16:56:15.482  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:15.492  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:15.498  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:15.507  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:15.507  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 16:56:15.508  6861  6861 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 16:56:15.515  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:15.524  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:15.533  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:15.542  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:15.542  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:15.543  6861  6861 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-24 16:56:15.550  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:15.560  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:15.566  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:15.575  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 16:56:15.576  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 16:56:15.577  6861  6861 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 16:56:15.583  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:15.594  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:15.604  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 16:56:15.615  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:15.617  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:15.618  6861  6861 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-24 16:56:15.627  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:15.642  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:15.651  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:15.660  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:15.660  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:15.667  6861  6861 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-24 16:56:15.674  6615  6992 D UEI.SmartControl: Internal timer expired: 2
08-24 16:56:15.674  6615  6992 D UEI.SmartControl: unbind internal service
08-24 16:56:15.675  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:15.694  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:15.706  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 16:56:15.720  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 16:56:15.721  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:15.725  6861  6861 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.,
08-24 16:56:15.735  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 16:56:15.748  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-24 16:56:15.755  6615  6989 D serial_port: close(fd = 24)
,08-24 16:56:15.763  1034  1545 D WifiService: New client listening to asynchronous messages
08-24 16:56:15.763  6615  6989 I UEI.SmartControl: Serial port is closed.
08-24 16:56:15.765  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 16:56:15.773  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:15.785  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:15.799  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 16:56:15.800  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:15.802  6861  6861 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-24 16:56:15.806  6861  6861 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-24 16:56:15.807  6861  6861 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-24 16:56:15.819  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 16:56:15.827  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-24 16:56:15.831  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 16:56:15.838  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:15.852  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 16:56:15.866  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 16:56:15.867  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 16:56:15.870  6861  6861 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-24 16:56:15.872  6861  6861 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-24 16:56:15.873  6861  6861 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-24 16:56:15.879  1034  1941 I ActivityManager: Killing 6789:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-24 16:56:15.916  1034  1603 W libprocessgroup: failed to open /acct/uid_10037/pid_6789/cgroup.procs: No such file or directory
,08-24 16:56:15.924  2209  2209 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-24 16:56:15.940  2209  2209 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-24 16:56:15.941  2209  2209 D c       : Getting all permits...
08-24 16:56:15.941  2209  2209 D a       : Opening database...
,08-24 16:56:15.949  2209  2209 D a       : Opening database auth.proximity.permit_store...
08-24 16:56:15.951  2209  2209 D a       : Closing database...
08-24 16:56:15.980  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 16:56:15.981   312  7380 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-24 16:56:15.982  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-24 16:56:15.995  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 16:56:15.996  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-24 16:56:15.996  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 16:56:16.008  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:16.017  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:16.027  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 16:56:16.028  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 16:56:16.030  6861  6861 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 16:56:16.035  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:16.043  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 16:56:16.044  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 16:56:16.044  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 16:56:16.050  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:16.058  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:16.067  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:16.068  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 16:56:16.070  6861  6861 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 16:56:16.079  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:16.086  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 16:56:16.086  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 16:56:16.086  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 16:56:16.093  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:16.104  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:16.115  6861  6861 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:16.116  6861  6861 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:16.118  6861  6861 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-24 16:56:16.132  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 16:56:16.139  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-24 16:56:16.147  6907  7382 W FormManager: Network not available. Please check & try again.
08-24 16:56:16.149  6907  7383 V FormManager: Network unavailable.
08-24 16:56:16.151  6907  7383 V FormManager: Network unavailable.
08-24 16:56:16.154  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:16.174  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 16:56:16.174  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 16:56:16.176  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 16:56:16.181  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 16:56:16.187  4300  7384 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 16:56:16.194  6833  6833 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-24 16:56:16.195  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 16:56:16.195  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 16:56:16.199  4300  7385 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 16:56:16.199  4300  7385 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 16:56:16.203  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 16:56:16.208  6907  7387 W FormManager: Network not available. Please check & try again.
,08-24 16:56:16.216  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:16.226  6907  7388 V FormManager: Network unavailable.
,08-24 16:56:16.232  6907  7388 V FormManager: Network unavailable.
08-24 16:56:16.234  2209  2209 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-24 16:56:16.249  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=650044150 [*alarm*], flags=0x0
,08-24 16:56:16.486  1034  1540 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1123206043] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 16:56:16.488  1034  1540 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1123206040] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 16:56:16.603  1034  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:56:16.621  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-24 16:56:16.628  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:56:16.639  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:16.640  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:16.645  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-24 16:56:16.650  6390  6832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-24 16:56:16.652  5695  5695 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-24 16:56:16.686  2209  2209 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:56:16.713  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 16:56:16.714  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:16.714  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 16:56:16.714  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-24 16:56:16.720  7003  7003 I AppUp4:CustModeStarterReceiver: onReceive
08-24 16:56:16.724  7003  7003 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bc181cb
08-24 16:56:16.724  7003  7003 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 16:56:16.724  7003  7003 D AppUp4:CustFacade: isPhone : true
08-24 16:56:16.724  7003  7003 D AppUp4:CustModeStarterReceiver: begin check event
08-24 16:56:16.725  7003  7003 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-24 16:56:16.730  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:16.731  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 16:56:16.732  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 16:56:16.740  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 16:56:16.751  7040  7040 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-24 16:56:16.786  7040  7397 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 16:56:16.789  4300  7398 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0,
08-24 16:56:16.815  4300  7401 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:16.815  4300  7401 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-24 16:56:16.822  6907  7399 W FormManager: Network not available. Please check & try again.
08-24 16:56:16.823  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:16.829  3449  3449 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 16:56:16.829  3449  3449 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:16.830  3449  3449 I LgeMiscReceiver: networkInfo.isConnected() = true
08-24 16:56:16.830  3449  3449 D PhoneState: setPdpRejectCasuse : false
,08-24 16:56:16.835  7091  7091 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 16:56:16.835  7091  7091 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-24 16:56:16.840  6907  7400 V FormManager: Network unavailable.
08-24 16:56:16.847  7163  7163 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:16
,08-24 16:56:16.850  6907  7400 V FormManager: Network unavailable.
,08-24 16:56:16.851  7163  7163 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 16:56:16.851  7163  7163 D Weather.Utils: 2 : All the weather widget is gone.
08-24 16:56:16.851  7163  7163 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 16:56:16.851  7163  7163 D WeatherAncestor: connectivity changed - connection : true
08-24 16:56:16.851  7163  7163 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6c470c1
08-24 16:56:16.852  7163  7163 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 16:56:16.852  7163  7163 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 16:56:16.852  7163  7163 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-24 16:56:16.852  7163  7163 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 16:56:16.852  7163  7163 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:16
08-24 16:56:17.552  1034  2056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:17.553  1034  2056 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-24 16:56:17.584  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 16:56:17.585  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 16:56:17.585  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-24 16:56:17.586  1034  1096 D BluetoothManagerService: Message: 1
08-24 16:56:17.586  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-24 16:56:17.613  1034  1096 D BluetoothManagerService: Message: 20
08-24 16:56:17.613  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@399d3a0c:true
,08-24 16:56:17.617  6950  6950 D BluetoothAdapterState: make
08-24 16:56:17.622  6950  6950 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-24 16:56:17.622  6950  6950 I bluedroid-qcom: init
08-24 16:56:17.623  6950  7429 I BluetoothAdapterState: Entering OffState
08-24 16:56:17.624  6950  6950 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-24 16:56:17.624  6950  6950 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-24 16:56:17.624  6950  6950 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 16:56:17.624  6950  6950 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 16:56:17.624  6950  6950 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-24 16:56:17.626  6950  6950 I bluedroid-qcom: get_profile_interface socket
08-24 16:56:17.626  6950  6950 I bluedroid-qcom: get_profile_interface map_client
,08-24 16:56:17.630  6950  7433 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-24 16:56:17.625  7432  7432 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:17.636  6950  7433 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-24 16:56:17.625  7432  7432 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:17.644  7432  7432 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-24 16:56:17.644  7432  7432 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-24 16:56:17.644  7432  7432 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-24 16:56:17.649  1034  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:17.651  1034  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:17.652  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-24 16:56:17.652  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:17.655  7432  7432 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-24 16:56:17.661  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:56:17.665  7432  7432 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-24 16:56:17.665  7432  7432 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-24 16:56:17.667  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:17.673  1034  1096 D Tethering: MasterInitialState.processMessage what=3
,08-24 16:56:17.683  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:17.684  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:17.686  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-24 16:56:17.689  1034  1096 D BluetoothManagerService: Message: 40
08-24 16:56:17.689  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-24 16:56:17.690  6950  6966 I bluedroid-qcom: config_hci_snoop_log
08-24 16:56:17.691  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-24 16:56:17.691  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-24 16:56:17.696  6950  7433 D BluetoothAdapterProperties: Name is: G3
08-24 16:56:17.697  6950  7429 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-24 16:56:17.697  6950  7429 D BluetoothAdapterProperties: Setting state to 11
08-24 16:56:17.698  6950  7429 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-24 16:56:17.700  6950  7429 I LGBluetoothServiceJni: classInitNative: succeeds
,08-24 16:56:17.705  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 16:56:17.705  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-24 16:56:17.706  1034  1096 D BluetoothManagerService: Message: 60
08-24 16:56:17.706  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-24 16:56:17.706  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-24 16:56:17.710  1974  1974 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:17.713  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 16:56:17.716  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:17.717  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:56:17.726  6810  6810 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-24 16:56:17.728  6950  7429 D BluetoothBondStateMachine: make
,08-24 16:56:17.729  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 16:56:17.735  6950  7429 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:17.735  6950  7429 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-24 16:56:17.735  6950  7429 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:17.736  6950  7429 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-24 16:56:17.736  6950  6950 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 16:56:17.737  6950  7429 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-24 16:56:17.737  6950  6950 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:17.737  6950  6950 V BluetoothPbapReceiver: ***********state = 11
08-24 16:56:17.738  6950  7446 I BluetoothBondStateMachine: StableState(): Entering Off State
08-24 16:56:17.740  6390  6832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-24 16:56:17.743  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 16:56:17.751  5695  5695 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-24 16:56:17.756  6950  7429 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 16:56:17.807  1034  1603 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7451 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-24 16:56:17.811  5695  5695 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-24 16:56:17.818  6950  6950 D HeadsetService: Received start request. Starting profile...
08-24 16:56:17.819  6950  7429 E BluetoothAdapterService: File transfer profiles supported!!
08-24 16:56:17.820  6950  6950 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 16:56:17.820  6950  6950 D LGBluetoothHfpAdapter: Version 1.6
,08-24 16:56:17.823  6950  6950 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-24 16:56:17.824  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:17.824  6950  6950 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 16:56:17.825  6950  6950 D HeadsetStateMachine: make
08-24 16:56:17.825  6950  7429 E BluetoothAdapterService: File transfer profiles supported!!
08-24 16:56:17.837  2209  2209 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:56:17.842  6950  7429 E BluetoothAdapterService: File transfer profiles supported!!
08-24 16:56:17.848  6950  7429 E BluetoothAdapterService: File transfer profiles supported!!
08-24 16:56:17.855  6950  7429 E BluetoothAdapterService: File transfer profiles supported!!
08-24 16:56:17.855  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 16:56:17.855  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:56:17.855  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 16:56:17.855  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-24 16:56:17.857  7003  7003 I AppUp4:CustModeStarterReceiver: onReceive
08-24 16:56:17.858  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:17.858  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:17.863  6950  6950 D LgDataFeature: LgDataFeature() Constructor: none
08-24 16:56:17.863  6950  6950 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 16:56:17.865  6950  7429 E BluetoothAdapterService: File transfer profiles supported!!
08-24 16:56:17.865  7003  7003 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bc181cb
08-24 16:56:17.865  7003  7003 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 16:56:17.865  7003  7003 D AppUp4:CustFacade: isPhone : true
08-24 16:56:17.865  7003  7003 D AppUp4:CustModeStarterReceiver: begin check event
08-24 16:56:17.866  7003  7003 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-24 16:56:17.868  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:17.868  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 16:56:17.869  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 16:56:17.871  6950  6950 D HeadsetStateMachine: max_hf_connections = 1
08-24 16:56:17.871  6950  6950 I bluedroid-qcom: get_profile_interface handsfree
08-24 16:56:17.872  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 16:56:17.878  7040  7040 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-24 16:56:17.880  6950  6950 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-24 16:56:17.880   318   318 V AudioPolicyService: registerClient() client 0xb57f3880, uid 1002
08-24 16:56:17.880   318  3991 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-24 16:56:17.880   318  3991 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 16:56:17.880   318  3991 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 16:56:17.881  6950  6950 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-24 16:56:17.881   318  1384 V AudioFlinger: registerClient() client 0xb55816d0, pid 6950
08-24 16:56:17.882  6950  7429 V LGMDMManager: Create singleton instance
,08-24 16:56:17.882   318  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 16:56:17.882   318  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 16:56:17.882  6950  6950 V ToneGenerator: Create Track: 0xb4928080
08-24 16:56:17.882  6950  6950 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-24 16:56:17.882  6950  6950 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-24 16:56:17.883   318   318 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 16:56:17.883   318   318 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-24 16:56:17.883   318   318 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 16:56:17.883   318   318 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 16:56:17.883  1034  2088 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 16:56:17.883  6950  6950 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-24 16:56:17.883  1034  2088 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 16:56:17.883   318  1384 I AudioFlinger: isAudioPlaybackHookOn() false
08-24 16:56:17.883  1605  1623 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 16:56:17.884  1605  1623 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 16:56:17.884  3449  3464 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 16:56:17.884  3449  3464 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 16:56:17.884  6950  6965 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 16:56:17.884  6950  6965 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-24 16:56:17.884   318  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 16:56:17.884   318  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 16:56:17.884  1034  1920 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 16:56:17.884  1034  1920 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 16:56:17.884  1605  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 16:56:17.884  1605  1625 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 16:56:17.884  3449  3465 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 16:56:17.884  3449  3465 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 16:56:17.884  6950  6965 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 16:56:17.884  6950  6965 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-24 16:56:17.885  6950  7429 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-24 16:56:17.886   318  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 16:56:17.886   318  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-24 16:56:17.886   318  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 16:56:17.886   318  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 16:56:17.886  6950  6950 V AudioSystem: getLatency() output 2, latency 50
08-24 16:56:17.886  6950  6950 V AudioSystem: getFrameCount() output 2, frameCount 960
08-24 16:56:17.886  6950  6950 V AudioTrack: createTrack_l() output 2 afLatency 50
08-24 16:56:17.886  4300  7471 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 16:56:17.887  1876  2567 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 16:56:17.887  1876  2567 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 16:56:17,.887  1876  2567 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 16:56:17.887  1876  2567 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 16:56:17.888  4300  7473 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:17.888   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 16:56:17.888   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 16:56:17.888   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 16:56:17.888   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 16:56:17.888   318   318 V AudioFlinger: createTrack() lSessionId: 22
08-24 16:56:17.890  6950  6950 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-24 16:56:17.890   318  3991 V AudioFlinger: acquiring 22 from 6950, for 6950
08-24 16:56:17.890   318  3991 V AudioFlinger:  added new entry for 22
08-24 16:56:17.891  6950  6950 V ToneGenerator: ToneGenerator INIT OK, time: 210982
08-24 16:56:17.891  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:17.892  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:17.893  6950  7462 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-24 16:56:17.893  6950  7462 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 16:56:17.893  6950  7462 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 16:56:17.893  6950  7462 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-24 16:56:17.893   318  1384 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6950
08-24 16:56:17.895   318  1384 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-24 16:56:17.895   318  1384 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-24 16:56:17.895   318  1384 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-24 16:56:17.895   318  1384 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-24 16:56:17.895   318  1384 V voice   : voice_set_parameters: exit with code(0)
08-24 16:56:17.895   318  1384 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-24 16:56:17.895   318  1384 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-24 16:56:17.895   318  1384 V msm8974_platform: platform_set_parameters: exit with code(0)
08-24 16:56:17.895   318  1384 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-24 16:56:17.895   318  1384 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-24 16:56:17.895   318  1384 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-24 16:56:17.895  6950  6950 D A2dpService: Received start request. Starting profile...
08-24 16:56:17.896  6950  6950 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-24 16:56:17.897  6950  6950 V Avrcp   : make
08-24 16:56:17.897  4300  7473 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 16:56:17.897  6950  7462 V ToneGenerator: ToneGenerator destructor
08-24 16:56:17.897  6950  7462 V ToneGenerator: stopTone
08-24 16:56:17.897  6950  7462 V ToneGenerator: Delete Track: 0xb4928080
08-24 16:56:17.897  6950  6950 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-24 16:56:17.897  6950  6950 I bluedroid-qcom: get_profile_interface avrcp
08-24 16:56:17.898  6950  7462 V AudioTrack: ~AudioTrack, releasing session id from 6950 on behalf of 6950
08-24 16:56:17.898   318   318 V AudioPolicyService: AudioCommandThread() adding release output 2
08-24 16:56:17.898   318   318 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-24 16:56:17.898   318   318 V AudioFlinger: PlaybackThread::Track destructor
08-24 16:56:17.898   318  1259 V AudioPolicyService: AudioCommandThread() waking up
08-24 16:56:17.898   318   318 V AudioFlinger: removeClient_l() pid 6950, calling pid 318
08-24 16:56:17.898   318   318 V AudioFlinger: releasing 22 from 6950 for 6950
08-24 16:56:17.898   318   318 V AudioFlinger:  decremented refcount to 0
08-24 16:56:17.898   318   318 V AudioFlinger: purging stale effects
08-24 16:56:17.898   318  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
08-24 16:56:17.899   318  1259 V AudioPolicyManager: releaseOutput() 2
08-24 16:56:17.899   318  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-24 16:56:17.907  6950  6950 V AudioManager: registerRemoteController: size of Media player list: 0
08-24 16:56:17.910  6950  6950 E AudioManager: No RCC entry present to update
08-24 16:56:17.910  6950  6950 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-24 16:56:17.912  7040  7474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:17.913  6950  6950 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-24 16:56:17.913  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-24 16:56:17.913  6950  6950 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-24 16:56:17.915  3449  3449 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 16:56:17.915  3449  3449 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:17.916  3449  3449 I LgeMiscReceiver: networkInfo.isConnected() = false
08-24 16:56:17.917  7091  7091 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 16:56:17.918  7091  7091 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-24 16:56:17.921  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-24 16:56:17.971  7451  7451 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-24 16:56:17.971  7451  7451 W LG Account v2.2: No ProfileInfo entries
08-24 16:56:17.971  7163  7163 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:17
08-24 16:56:17.971  7451  7451 I LG Account v2.2: isEnabled: false
08-24 16:56:17.971  7451  7451 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-24 16:56:17.971  7451  7451 I Feature : [Lifetracker]Country: EU
08-24 16:56:17.971  7451  7451 I Feature : [Lifetracker]Operator: OPEN
08-24 16:56:17.972  7451  7451 I Feature : [Lifetracker]Ranking support: false
08-24 16:56:17.972  7451  7451 I Feature : [Lifetracker]Comfort support: false
08-24 16:56:17.972  7451  7451 I Feature : [Lifetracker]Accessory: true
08-24 16:56:17.972  7451  7451 I Feature : [Lifetracker]Health device: true
08-24 16:56:17.972  6907  7480 V FormManager: Network unavailable.
08-24 16:56:17.972  7451  7451 I Feature : [Lifetracker]Extra Pedometer: false
08-24 16:56:17.972  7451  7451 I Feature : [Lifetracker]Blood glucose device: false
08-24 16:56:17.972  7451  7451 I Feature : [Lifetracker]Device Number: 3
08-24 16:56:17.972  6907  7479 W FormManager: Network not available. Please check & try again.
,08-24 16:56:17.974  7163  7163 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 16:56:17.974  7163  7163 D Weather.Utils: 2 : All the weather widget is gone.
08-24 16:56:17.975  7163  7163 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 16:56:17.975  7163  7163 D WeatherAncestor: connectivity changed - connection : true
08-24 16:56:17.975  7163  7163 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6c470c1
08-24 16:56:17.976  7163  7163 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 16:56:17.976  7163  7163 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 16:56:17.976  7163  7163 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-24 16:56:17.976  7163  7163 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 16:56:17.976  7163  7163 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:17
08-24 16:56:17.979  6907  7480 V FormManager: Network unavailable.
08-24 16:56:17.985  6810  6810 D BluetoothPermissionRequest: onReceive
,08-24 16:56:17.993  6810  6810 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 16:56:18.006  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-24 16:56:18.009  6390  6832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-24 16:56:18.021  2209  2209 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:56:18.022  1034  1049 V SIM_STK : Menu title from STK is T-Mobile
,08-24 16:56:18.022  1034  1049 V SIM_STK : Menu title from STK is T-Mobile
08-24 16:56:18.031  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 16:56:18.031  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:18.031  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 16:56:18.031  7003  7003 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-24 16:56:18.032  7003  7003 I AppUp4:CustModeStarterReceiver: onReceive
,08-24 16:56:18.034  7003  7003 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bc181cb
08-24 16:56:18.034  7003  7003 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 16:56:18.034  7003  7003 D AppUp4:CustFacade: isPhone : true
08-24 16:56:18.034  7003  7003 D AppUp4:CustModeStarterReceiver: begin check event
08-24 16:56:18.034  7003  7003 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-24 16:56:18.039  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:18.039  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 16:56:18.041  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 16:56:18.042  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 16:56:18.047  4300  7483 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-24 16:56:18.050  7040  7040 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-24 16:56:18.052  4300  7484 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:18.052  4300  7484 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 16:56:18.069  6907  7487 W FormManager: Network not available. Please check & try again.
08-24 16:56:18.069  7040  7485 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 16:56:18.075  3449  3449 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-24 16:56:18.075  3449  3449 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:18.075  3449  3449 I LgeMiscReceiver: networkInfo.isConnected() = false
08-24 16:56:18.078  7091  7091 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 16:56:18.078  7091  7091 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-24 16:56:18.087  7163  7163 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:18
,08-24 16:56:18.090  6907  7488 V FormManager: Network unavailable.
08-24 16:56:18.091  7163  7163 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 16:56:18.091  7163  7163 D Weather.Utils: 2 : All the weather widget is gone.
08-24 16:56:18.091  7163  7163 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 16:56:18.091  7163  7163 D WeatherAncestor: connectivity changed - connection : true
08-24 16:56:18.091  7163  7163 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6c470c1
08-24 16:56:18.092  6907  7488 V FormManager: Network unavailable.
08-24 16:56:18.092  7163  7163 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 16:56:18.092  7163  7163 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 16:56:18.093  7163  7163 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-24 16:56:18.093  7163  7163 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 16:56:18.093  7163  7163 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:18
08-24 16:56:18.109  1034  1049 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-24 16:56:18.115  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-24 16:56:18.119  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-24 16:56:18.120  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-24 16:56:18.120  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-24 16:56:18.120  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-24 16:56:18.120  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 16:56:18.120  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-24 16:56:18.120  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-24 16:56:18.120  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
,08-24 16:56:18.120  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 16:56:18.120  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-24 16:56:18.121  6950  6950 I BluetoothA2dpServiceJni: classInitNative
08-24 16:56:18.121  6950  6950 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 16:56:18.121  6950  6950 D A2dpStateMachine: make
08-24 16:56:18.122  6950  6950 I bluedroid-qcom: get_profile_interface a2dp
08-24 16:56:18.122  6950  7491 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-24 16:56:18.124  6950  6950 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-24 16:56:18.124  6950  6950 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-24 16:56:18.125  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:18.125  6950  7490 D A2dpStateMachine: Enter Disconnected: -2
08-24 16:56:18.126  6950  6950 I BluetoothHidServiceJni: classInitNative: succeeds
08-24 16:56:18.127  6950  6950 D HidService: Received start request. Starting profile...
08-24 16:56:18.127  6950  6950 I bluedroid-qcom: get_profile_interface hidhost
08-24 16:56:18.127  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:18.127  6950  6950 I BluetoothHealthServiceJni: classInitNative: succeeds
08-24 16:56:18.129  6950  6950 D HealthService: Received start request. Starting profile...
08-24 16:56:18.130  6950  6950 I bluedroid-qcom: get_profile_interface health
08-24 16:56:18.130  6950  6950 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-24 16:56:18.130  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:18.131  6950  6950 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-24 16:56:18.132  6950  6950 D PanService: Received start request. Starting profile...
08-24 16:56:18.132  6950  6950 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 16:56:18.132  6950  6950 I bluedroid-qcom: get_profile_interface pan
08-24 16:56:18.137  6950  6950 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-24 16:56:18.137  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
,08-24 16:56:18.138  6950  6950 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-24 16:56:18.142  6950  6950 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 16:56:18.142  6950  6950 D BtGatt.GattService: Received start request. Starting profile...
08-24 16:56:18.143  6950  6950 D BtGatt.GattService: start()
08-24 16:56:18.143  6950  6950 I bluedroid-qcom: get_profile_interface gatt
08-24 16:56:18.143  6950  6950 D BtGatt.AdvertiseManager: advertise manager created
08-24 16:56:18.148  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:18.149  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:18.149  6950  6950 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-24 16:56:18.150  6950  6950 V BluetoothMapService: BluetoothMapBinder()
08-24 16:56:18.150  6950  6950 D BluetoothMapService: Received start request. Starting profile...
08-24 16:56:18.150  6950  6950 D BluetoothMapService: start()
08-24 16:56:18.153  6950  6950 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-24 16:56:18.153  6950  6950 D BluetoothMapEmailAppObserver: createReceiver()
08-24 16:56:18.154  6950  6950 D BluetoothMapEmailAppObserver: initObservers()
08-24 16:56:18.154  6950  6950 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-24 16:56:18.161  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:18.161  6950  6950 D HeadsetStateMachine: Proxy object connected
08-24 16:56:18.161  6950  6950 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-24 16:56:18.162  6950  6950 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-24 16:56:18.163  6950  7462 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 16:56:18.163  6950  7462 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 16:56:18.163  6950  7462 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-24 16:56:18.167  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 16:56:18.173  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 16:56:18.178  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-24 16:56:18.182  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 16:56:18.182  6950  6950 V PanService: [BTUI] SIM Extra State :ABSENT
08-24 16:56:18.186  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 16:56:18.190  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-24 16:56:18.191  6950  6950 V BluetoothMapService: Handler(): got msg=1
,08-24 16:56:18.192  6950  7429 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,08-24 16:56:18.192  6950  7429 I bluedroid-qcom: enable
08-24 16:56:18.193  6950  7429 I bt_hci_bdroid: init
08-24 16:56:18.193  6950  7498 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-24 16:56:18.194  6950  7498 I bt-btu  : btu_task pending for preload complete event
08-24 16:56:18.194  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:18.195  6950  7429 I bt_vendor: bt-vendor : init
08-24 16:56:18.195  6950  7429 I bt_vendor: bt-vendor : get_bt_soc_type
08-24 16:56:18.195  6950  7429 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-24 16:56:18.195  6950  7429 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-24 16:56:18.195  6950  7429 D bt_userial_mct: userial_init
08-24 16:56:18.196  6950  6950 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 16:56:18.196  6950  6950 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 16:56:18.196  6950  6950 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 16:56:18.196  6950  6950 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:18.196  6950  6950 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-24 16:56:18.198  6950  7429 D bt_hci_bdroid: set_power 1
08-24 16:56:18.198  6950  7429 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-24 16:56:18.198  6950  7429 I bt_vendor: Starting hciattach daemon
08-24 16:56:18.198  6950  7429 I bt_vendor: try to set true
08-24 16:56:18.195  7501  7501 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:18.195  7501  7501 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 16:56:18.246  7502  7502 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-24 16:56:18.340  7511  7511 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-24 16:56:18.352  7512  7512 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-24 16:56:18.391  7517  7517 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-24 16:56:18.402  7518  7518 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-24 16:56:18.413  7519  7519 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-24 16:56:18.426  7520  7520 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-24 16:56:18.446  7522  7522 I libmdmdetect: ESOC framework not supported
08-24 16:56:18.447  7522  7522 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-24 16:56:18.458  7522  7522 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-24 16:56:18.458  7522  7522 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-24 16:56:18.458  7522  7522 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-24 16:56:18.458  7522  7522 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-24 16:56:18.458  7522  7522 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-24 16:56:18.458  7522  7522 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-24 16:56:18.458  7522  7522 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-24 16:56:18.499  7522  7523 E QC-QMI  : qmi_client [7522] 14: failed to locate client data
08-24 16:56:18.499   466   466 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-24 16:56:18.499   466   466 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-24 16:56:18.549  7524  7524 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-24 16:56:18.563  7525  7525 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-24 16:56:18.601  6950  7429 I bt_vendor: bluetooth satus is on
08-24 16:56:18.601  6950  7429 D bt_hci_bdroid: preload
,08-24 16:56:18.605  6950  7500 D bt_userial_mct: userial_open(port:0)
08-24 16:56:18.605  6950  7500 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-24 16:56:18.609  6950  7500 I bt_vendor: Done intiailizing UART
08-24 16:56:18.613  6950  7500 I bt_vendor: Done intiailizing UART
08-24 16:56:18.613  6950  7500 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-24 16:56:18.613  6950  7500 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-24 16:56:18.613  6950  7527 D bt_userial_mct: Entering userial_read_thread()
08-24 16:56:18.614  6950  7498 I bt-btu  : btu_task received preload complete event
08-24 16:56:18.615  6950  7498 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-24 16:56:18.615  6950  7498 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-24 16:56:18.625  6950  7498 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-24 16:56:18.635  6950  7498 I         : BTE_InitTraceLevels -- TRC_HCI
08-24 16:56:18.635  6950  7498 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-24 16:56:18.635  6950  7498 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 16:56:18.635  6950  7498 I         : BTE_InitTraceLevels -- TRC_AVDT
08-24 16:56:18.635  6950  7498 I         : BTE_InitTraceLevels -- TRC_AVRC
08-24 16:56:18.635  6950  7498 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 16:56:18.635  6950  7498 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 16:56:18.635  6950  7498 I         : BTE_InitTraceLevels -- TRC_BTM
08-24 16:56:18.635  6950  7498 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-24 16:56:18.635  6950  7498 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 16:56:18.635  6950  7498 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 16:56:18.635  6950  7498 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 16:56:18.635  6950  7498 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 16:56:18.636  6950  7498 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 16:56:18.636  6950  7498 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 16:56:18.636  6950  7498 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 16:56:18.703  6950  7498 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-24 16:56:18.703  6950  7498 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ff061 
08-24 16:56:18.703  6950  7498 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ff061 
,08-24 16:56:18.740  6950  7433 E bt-btif : Calling BTA_HhEnable
,08-24 16:56:18.740  6950  7433 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-24 16:56:18.740  6950  7433 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-24 16:56:18.744  6950  7433 D BluetoothAdapterProperties: Name is: G3
,08-24 16:56:18.747  6950  7498 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-24 16:56:18.747  6950  7498 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-24 16:56:18.747  6950  7498 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-24 16:56:18.747  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 16:56:18.747  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-24 16:56:18.748  6950  7498 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-24 16:56:18.748  6950  7498 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-24 16:56:18.751  6950  7433 D BluetoothAdapterProperties: Scan Mode:20
08-24 16:56:18.751  6950  7433 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 16:56:18.751  6950  7433 D bt_hci_bdroid: postload
08-24 16:56:18.753  6950  7498 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-24 16:56:18.753  6950  7500 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 16:56:18.754  6950  7433 D bte_conf: Device ID record 1 : primary
08-24 16:56:18.754  6950  7433 D bte_conf:   vendorId            = 00c4
,08-24 16:56:18.754  6950  7433 D bte_conf:   vendorIdSource      = 0001
08-24 16:56:18.754  6950  7433 D bte_conf:   product             = 13a1
08-24 16:56:18.754  6950  7433 D bte_conf:   version             = 1000
08-24 16:56:18.754  6950  7433 D bte_conf:   clientExecutableURL = 
08-24 16:56:18.754  6950  7433 D bte_conf:   serviceDescription  = 
,08-24 16:56:18.754  6950  7433 D bte_conf:   documentationURL    = 
08-24 16:56:18.754  6950  7433 D bte_conf: bte_load_did_conf no section named DID2.
08-24 16:56:18.758  6950  7500 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 16:56:18.758  6950  7500 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 16:56:18.760  6950  7429 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-24 16:56:18.760  6950  7429 D BluetoothAdapterProperties: ScanMode =  20
08-24 16:56:18.760  6950  7429 D BluetoothAdapterProperties: State =  11
08-24 16:56:18.761  6950  7500 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 16:56:18.761  6950  7500 D bt_hci_bdroid: Used up Tx Cmd credits
,08-24 16:56:18.761  6950  7429 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-24 16:56:18.762  6950  7429 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-24 16:56:18.762  6950  7429 D BluetoothAdapterProperties: Setting state to 12
08-24 16:56:18.762  6950  7429 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 16:56:18.763  6950  7433 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-24 16:56:18.763  6950  7433 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-24 16:56:18.765  7529  7529 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:18.772  1034  1096 D BluetoothManagerService: Message: 60
08-24 16:56:18.772  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-24 16:56:18.772  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-24 16:56:18.772  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 16:56:18.773  6950  7429 I BluetoothAdapterState: Entering On State
08-24 16:56:18.765  7529  7529 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:18.779  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 16:56:18.781  6950  7429 D LGBluetoothServiceAdapter: [BTUI] OnState
08-24 16:56:18.781  6950  7429 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-24 16:56:18.781  6950  7429 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-24 16:56:18.785  6950  7498 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 16:56:18.785  6950  7498 W bt-smp  : Plain text(LSB ~ MSB) = 93 d0 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 16:56:18.785  6950  7498 W bt-smp  : Encrypted text(LSB ~ MSB) = 9b b3 58 08 c2 f4 4b c7 43 b7 17 3b 84 31 ba cb 
08-24 16:56:18.785  6950  7498 W bt-btm  : Stopping oneshot timer
08-24 16:56:18.785  6950  7500 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 16:56:18.787  6950  7429 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-24 16:56:18.790  6950  7527 E bt_mct  : hci lib postload completed
,08-24 16:56:18.792  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:18.792  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:18.792  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:18.792  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:56:18.792  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:18.792  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:18.792  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:18.792  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:56:18.793  1034  1034 D BluetoothA2dp: Proxy object connected
08-24 16:56:18.794  6950  7433 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 16:56:18.795  6950  7433 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-24 16:56:18.801  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:56:18.805  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:18.805  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:18.805  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:18.805  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:56:18.805  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:18.805  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:18.805  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:18.805  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:56:18.807  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:56:18.807  6950  7498 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 16:56:18.808  6950  7498 W bt-smp  : Plain text(LSB ~ MSB) = b6 87 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 16:56:18.808  6950  7498 W bt-smp  : Encrypted text(LSB ~ MSB) = 9a 0a 61 b9 d1 9f 6d 5b 97 49 5d e4 5c d0 13 15 
08-24 16:56:18.808  6950  7498 W bt-btm  : Stopping oneshot timer
,08-24 16:56:18.811  1034  1034 D BluetoothHeadset: Proxy object connected
08-24 16:56:18.815  6810  6829 D BluetoothMap: onBluetoothStateChange: up=true
08-24 16:56:18.823  6950  7429 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-24 16:56:18.824  1876  1892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 16:56:18.826  6810  6810 D BluetoothMap: Proxy object connected
08-24 16:56:18.826  6810  6810 D MapProfile: Bluetooth service connected
08-24 16:56:18.826  6810  6810 D BluetoothMap: getConnectedDevices()
08-24 16:56:18.828  6950  7530 V BluetoothMapService: getConnectedDevices()
08-24 16:56:18.833  1876  1876 D BluetoothHeadset: Proxy object connected
08-24 16:56:18.835  6810  6828 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 16:56:18.839  1876  2567 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 16:56:18.841  6950  7498 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 16:56:18.841  6950  7498 W bt-smp  : Plain text(LSB ~ MSB) = 07 54 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 16:56:18.841  6950  7498 W bt-smp  : Encrypted text(LSB ~ MSB) = 06 1d 4a 21 ec 2e 92 c1 3b c5 fb 4c 73 1e 85 b0 
08-24 16:56:18.841  6950  7498 W bt-btm  : Stopping oneshot timer
08-24 16:56:18.848  1876  1876 D BluetoothHeadset: Proxy object connected
,08-24 16:56:18.849  6810  6829 D BluetoothPan: onBluetoothStateChange on: true
08-24 16:56:18.849  6810  6829 D BluetoothPan: onBluetoothStateChange call bindService
08-24 16:56:18.853  6810  6810 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 16:56:18.853  6810  6810 D PanProfile: Bluetooth service connected
08-24 16:56:18.854  6950  7498 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 16:56:18.854  6950  7498 W bt-smp  : Plain text(LSB ~ MSB) = 7a 7f 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 16:56:18.854  6950  7498 W bt-smp  : Encrypted text(LSB ~ MSB) = 7d e2 ed 7b 48 6f 63 77 5c 6c eb af 2b 46 05 71 
08-24 16:56:18.854  6950  7498 W bt-btm  : Stopping oneshot timer
08-24 16:56:18.855  1876  2566 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 16:56:18.858  1876  1876 D BluetoothHeadset: Proxy object connected
08-24 16:56:18.859  6810  6828 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 16:56:18.863  7546  7546 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-24 16:56:18.864  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-24 16:56:18.865  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-24 16:56:18.865  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-24 16:56:18.866  1034  1096 D BluetoothManagerService: Message: 40
08-24 16:56:18.866  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-24 16:56:18.866  6810  6810 D BluetoothInputDevice: Proxy object connected
08-24 16:56:18.866  6810  6810 D HidProfile: Bluetooth service connected
08-24 16:56:18.867  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 16:56:18.868  6950  7498 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 16:56:18.868  6950  7498 W bt-smp  : Plain text(LSB ~ MSB) = ed c3 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 16:56:18.868  6950  7498 W bt-smp  : Encrypted text(LSB ~ MSB) = e6 bc 89 04 62 44 c7 c4 28 74 88 5d 1e 35 38 c1 
08-24 16:56:18.868  6950  7498 W bt-btm  : Stopping oneshot timer
08-24 16:56:18.869  1974  1974 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:18.870  1974  2170 D LGBluetoothAPIService: Message: 1
08-24 16:56:18.870  1974  2170 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-24 16:56:18.875  6695  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-24 16:56:18.876  1974  2170 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-24 16:56:18.878  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:18.878  6950  6950 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:18.878  6950  6950 D BluetoothMapService: STATE_ON
,08-24 16:56:18.880  6950  6950 D LGBluetoothAPIServer: [BTUI] onCreate()
08-24 16:56:18.880  6950  6950 D LGBluetoothAPIServer: [BTUI] onBind()
08-24 16:56:18.882  1974  1974 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-24 16:56:18.882  1974  2170 D LGBluetoothAPIService: Message: 100
08-24 16:56:18.882  1974  2170 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-24 16:56:18.888  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:18.888  6810  6810 D LocalBluetoothProfileManager: Adding local A2DP profile
08-24 16:56:18.891  1034  1096 D BluetoothManagerService: Message: 30
08-24 16:56:18.894  6810  6810 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-24 16:56:18.897  1034  1096 D BluetoothManagerService: Message: 30
08-24 16:56:18.899  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:18.899  6950  6950 V BluetoothPbapService: Pbap Service onCreate
08-24 16:56:18.899  6950  6950 V BluetoothPbapService: Starting PBAP service
08-24 16:56:18.901  6950  6950 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-24 16:56:18.901  6950  6950 V BluetoothPbapService: Pbap Service onBind
08-24 16:56:18.902  6950  6950 V BluetoothMapService: Handler(): got msg=1
08-24 16:56:18.902  6950  6950 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-24 16:56:18.903  6950  6950 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:18.903  6810  6810 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-24 16:56:18.903  6950  6950 V BluetoothPbapService: state: 12
08-24 16:56:18.903  6950  6950 V BluetoothPbapService: Handler(): got msg=1
08-24 16:56:18.904  6950  6950 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-24 16:56:18.905  6810  6810 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 16:56:18.908  6950  7549 D BluetoothMapMasInstance: MAS initSocket()
,08-24 16:56:18.909  6950  7549 D BluetoothMapMasInstance:   masId = 00
08-24 16:56:18.909  6950  7549 D BluetoothMapMasInstance:   msgTypes = 0e
08-24 16:56:18.909  6950  7549 D BluetoothMapMasInstance:   masName = SMS/MMS
08-24 16:56:18.909  6950  7549 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-24 16:56:18.909  6950  6950 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 16:56:18.909  6950  6950 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:18.909  6950  6950 V BluetoothPbapReceiver: ***********state = 12
08-24 16:56:18.910  1034  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:18.910  6810  6810 D BluetoothA2dp: Proxy object connected
08-24 16:56:18.911  6950  7550 V BluetoothPbapService: Pbap Service initSocket
08-24 16:56:18.911  6810  6810 D A2dpProfile: Bluetooth service connected
08-24 16:56:18.912  6950  7549 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 16:56:18.913  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 16:56:18.914  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:18.914  2209  2209 D c       : Getting all permits...
08-24 16:56:18.914  2209  2209 D a       : Opening database...
08-24 16:56:18.914  6810  6810 D BluetoothHeadset: Proxy object connected
08-24 16:56:18.915  6950  7549 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-24 16:56:18.915  6810  6810 D HeadsetProfile: Bluetooth service connected
08-24 16:56:18.916  6950  7549 V BluetoothMapMasInstance: Succeed to create listening socket 
08-24 16:56:18.916  6950  7549 D BluetoothMapMasInstance: Accepting socket connection...
08-24 16:56:18.916  6950  7433 D BluetoothAdapterProperties: Scan Mode:21
08-24 16:56:18.917  6950  7433 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-24 16:56:18.917  6950  7550 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 16:56:18.917  2209  2209 D a       : Opening database auth.proximity.permit_store...
08-24 16:56:18.919  2209  2209 D a       : Closing database...
08-24 16:56:18.920  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:56:18.921  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:18.924  6810  6810 D BluetoothPbap: Proxy object connected
08-24 16:56:18.925  6810  6810 D PbapServerProfile: Bluetooth service connected
08-24 16:56:18.926  6950  7550 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-24 16:56:18.926  6950  7550 V BluetoothPbapService: Succeed to create listening socket 
08-24 16:56:18.926  6950  7550 V BluetoothPbapService: Accepting socket connection...
08-24 16:56:18.929  6810  6810 D DockEventReceiver: finishStartingService: stopping service
08-24 16:56:18.933  6810  6810 D BluetoothPermissionRequest: onReceive
,08-24 16:56:18.935  6810  6810 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-24 16:56:18.937  6810  6810 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 16:56:18.942  6950  6950 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-24 16:56:18.943  6950  6950 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-24 16:56:18.950  6950  6950 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-24 16:56:18.972  7194  7250 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-24 16:56:18.977  6950  6950 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-24 16:56:18.978  6950  6950 V BtOppService: onCreate
08-24 16:56:18.982  6950  6950 V BluetoothOppNotification: send message
08-24 16:56:18.985  6950  6950 V BtOppService: Starting RfcommListener
,08-24 16:56:18.992  6950  6950 D BluetoothOppPreference: Dumping Names:  
,08-24 16:56:18.992  6950  6950 D BluetoothOppPreference: {}
08-24 16:56:18.992  6950  6950 D BluetoothOppPreference: Dumping Channels:  
08-24 16:56:18.992  6950  6950 D BluetoothOppPreference: {}
08-24 16:56:18.993  6950  6950 V BtOppService: onStartCommand
08-24 16:56:18.996  6950  7560 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 16:56:18.998  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:18.998  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-24 16:56:19.000  6950  7560 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 16:56:19.003  6950  7557 V BtOppService: Deleted complete outbound shares, number =  0
08-24 16:56:19.003  6950  6950 V BluetoothOppNotification: new notify threadi!
08-24 16:56:19.004  6950  7560 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@135dbe02 on behalf of 
08-24 16:56:19.004  6950  6950 V BluetoothOppNotification: send delay message
08-24 16:56:19.006  6950  7557 V BtOppService: Deleted complete inbound failed shares, number = 0
08-24 16:56:19.006  6950  6950 V BtOppService: start RfcommListener
08-24 16:56:19.006  6950  7561 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-24 16:56:19.006  6950  7557 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-24 16:56:19.008  6950  7561 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@65ab313 on behalf of 
08-24 16:56:19.009  6950  7557 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ae03950 on behalf of 
08-24 16:56:19.010  6950  6950 V BtOppService: RfcommListener started
08-24 16:56:19.011  6950  6950 V BtOppService: ContentObserver received notification
,08-24 16:56:19.013  6950  7562 V BtOppRfcommListener: Starting RFCOMM listener....
08-24 16:56:19.013  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:19.015  6950  7561 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-24 16:56:19.015  6950  7560 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 16:56:19.016  6950  7560 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 16:56:19.017  6950  7561 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-24 16:56:19.018  6950  7562 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 16:56:19.018  6950  7560 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36cef749 on behalf of 
08-24 16:56:19.019  6950  7560 V BluetoothOppNotification: update too frequent, put in queue
,08-24 16:56:19.020  6950  7561 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30edb84e on behalf of 
08-24 16:56:19.021  6950  7561 V BluetoothOppNotification: outbound: succ-0  fail-0
08-24 16:56:19.022  6950  7562 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-24 16:56:19.022  6950  7562 V BtOppRfcommListener: Started RFCOMM listener....
08-24 16:56:19.022  6950  7560 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-24 16:56:19.022  6950  7562 I BtOppRfcommListener: Accept thread started.
08-24 16:56:19.022  6950  7562 V BtOppRfcommListener: Accepting connection...
,08-24 16:56:19.025  6950  7561 V BluetoothOppNotification: outbound notification was removed.
,08-24 16:56:19.025  6950  7561 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-24 16:56:19.027  6950  7561 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1db36d6f on behalf of 
08-24 16:56:19.027  6950  7561 V BluetoothOppNotification: inbound: succ-0  fail-0
08-24 16:56:19.029  6950  7561 V BluetoothOppNotification: inbound notification was removed.
08-24 16:56:19.029  6950  7561 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-24 16:56:19.031  6950  7561 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23979a7c on behalf of 
08-24 16:56:19.035  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:19.035  6950  6950 V BluetoothFtpService: Ftp Service onCreate
08-24 16:56:19.035  6950  6950 I BluetoothFtpService: Ftp Service onCreate
08-24 16:56:19.036  6950  6950 V BluetoothFtpService: Ftp Service onStartCommand
08-24 16:56:19.036  6950  6950 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-24 16:56:19.036  6950  6950 V BluetoothFtpService: Starting Listening on sockets
08-24 16:56:19.036  6950  6950 V BtOppService: ContentObserver received notification
08-24 16:56:19.037  6950  6950 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 16:56:19.037  6950  6950 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 16:56:19.037  6950  6950 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 16:56:19.037  6950  6950 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:19.037  6950  6950 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-24 16:56:19.037  6950  6950 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-24 16:56:19.038  6950  7563 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 16:56:19.038  6950  7563 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 16:56:19.040  6950  6950 V BluetoothFtpService: Handler(): got msg=1
08-24 16:56:19.040  6950  7563 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a710b5a on behalf of 
08-24 16:56:19.041  6950  6950 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-24 16:56:19.041  6950  6950 V BluetoothFtpService: Ftp Service initSocket
08-24 16:56:19.042  6950  7563 V BluetoothOppNotification: update too frequent, put in queue
08-24 16:56:19.043  6950  7563 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-24 16:56:19.049  1034  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:19.051  6950  6950 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 16:56:19.052  6950  6950 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-24 16:56:19.054  6950  7564 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-24 16:56:19.074  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:19.074  6950  6950 V BluetoothSapService: Sap Service onCreate
,08-24 16:56:19.077  6950  6950 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:19.077  6950  6950 V BluetoothSapService: state: 12
08-24 16:56:19.077  6950  6950 V BluetoothSapService: Starting SAP server process
08-24 16:56:19.080  6950  6950 V BluetoothSapService: SAP Service startRfcommListenerThread
08-24 16:56:19.075  7565  7565 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:19.075  7565  7565 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:19.084  6950  7566 V BluetoothSapService: Sap Service initRfcommSocket
08-24 16:56:19.085  1034  2056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:19.086  6950  7566 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 16:56:19.087  6950  7566 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-24 16:56:19.087  6950  7566 V BluetoothSapService: Succeed to create listening socket 
08-24 16:56:19.087  6950  7566 V BluetoothSapService: Accepting socket connection...
,08-24 16:56:19.093  7565  7565 V BT_SAP  : Event pipe created
08-24 16:56:19.093  7565  7565 V BT_SAP  : create_server_socket qcom.sap.server
08-24 16:56:19.093  7565  7565 V BT_SAP  : created socket fd 6
08-24 16:56:19.605  1034  1538 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:19.605  1034  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 16:56:19.650  1034  1540 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-24 16:56:19.656  1034  1540 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-24 16:56:19.964  1034  1577 I ActivityManager: Killing 7355:com.lge.bnr/1000 (adj 15): empty #17
,08-24 16:56:20.000  1034  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_7355/cgroup.procs: No such file or directory
,08-24 16:56:20.005  6950  6950 V BluetoothOppNotification: new notify threadi!
08-24 16:56:20.006  6950  6950 V BluetoothOppNotification: send delay message
08-24 16:56:20.007  6950  7576 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-24 16:56:20.009  6950  7576 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ca48326 on behalf of 
08-24 16:56:20.009  6950  7576 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-24 16:56:20.010  6950  7576 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-24 16:56:20.011  6950  7576 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27659b67 on behalf of 
08-24 16:56:20.012  6950  7576 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-24 16:56:20.016  6950  7576 V BluetoothOppNotification: outbound notification was removed.
08-24 16:56:20.016  6950  7576 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-24 16:56:20.018  6950  7576 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1446bd14 on behalf of 
08-24 16:56:20.018  6950  7576 V BluetoothOppNotification: inbound: succ-0  fail-0
08-24 16:56:20.020  6950  7576 V BluetoothOppNotification: inbound notification was removed.
08-24 16:56:20.020  6950  7576 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-24 16:56:20.021  6950  7576 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@132c9bd on behalf of 
08-24 16:56:20.029  1034  1050 I ActivityManager: Killing 6615:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-24 16:56:20.050  6861  6861 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-24 16:56:20.050  6861  6861 W System.err: android.os.DeadObjectException
08-24 16:56:20.050  6861  6861 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-24 16:56:20.050  6861  6861 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-24 16:56:20.050  6861  6861 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-24 16:56:20.051  6861  6861 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-24 16:56:20.051  6861  6861 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-24 16:56:20.051  6861  6861 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-24 16:56:20.051  6861  6861 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 16:56:20.051  6861  6861 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 16:56:20.051  6861  6861 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 16:56:20.051  6861  6861 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 16:56:20.051  6861  6861 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:56:20.051  6861  6861 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 16:56:20.051  6861  6861 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 16:56:20.051  6861  6861 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 16:56:20.051  6861  6861 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-24 16:56:20.051  6861  6861 W System.err: android.os.DeadObjectException
08-24 16:56:20.052  6861  6861 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-24 16:56:20.052  6861  6861 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-24 16:56:20.052  6861  6861 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-24 16:56:20.052  6861  6861 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-24 16:56:20.052  6861  6861 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-24 16:56:20.052  6861  6861 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-24 16:56:20.052  6861  6861 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 16:56:20.052  6861  6861 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 16:56:20.052  6861  6861 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 16:56:20.052  6861  6861 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 16:56:20.052  6861  6861 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:56:20.052  6861  6861 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 16:56:20.052  6861  6861 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 16:56:20.052  6861  6861 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 16:56:20.052  6861  6861 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-24 16:56:20.053  6861  6861 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-24 16:56:20.087  1034  2033 W libprocessgroup: failed to open /acct/uid_1000/pid_6615/cgroup.procs: No such file or directory
08-24 16:56:20.087  1034  2033 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-24 16:56:20.095  6861  6861 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-24 16:56:20.095  6861  6861 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-24 16:56:20.140  1034  1049 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7577 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-24 16:56:20.141  6861  6861 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-24 16:56:20.232  7577  7577 D UEI.SmartControl: Quickset Services start...
08-24 16:56:20.234  7577  7577 I UEI.SmartControl: Manufacture = LGE
08-24 16:56:20.234  7577  7577 D UEI.SmartControl: Id = LGNevo
,08-24 16:56:20.238  7577  7577 D UEI.SmartControl: File observer start...
08-24 16:56:20.239  7577  7577 E UEI.SmartControl: IR Port is disabled: false
08-24 16:56:20.239  7577  7577 D UEI.SmartControl: Starting file observer...
08-24 16:56:20.240  7577  7577 D UEI.SmartControl: Extracting JNI libs...
08-24 16:56:20.240  7577  7577 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-24 16:56:20.348  7577  7577 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-24 16:56:20.348  7577  7577 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-24 16:56:20.348  7577  7577 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-24 16:56:20.387  7577  7577 I UEI.SmartControl: --- Selecting new region: 6
,08-24 16:56:20.390  7577  7577 I UEI.SmartControl: Model = LG-D855
08-24 16:56:20.392  7577  7577 D UEI.SmartControl: QS Service created
08-24 16:56:20.408  7577  7577 I UEI.SmartControl: Service initServices...
,08-24 16:56:20.413  7577  7577 D UEI.SmartControl: QS start get config
08-24 16:56:20.466  7577  7577 D UEI.SmartControl: Loading JNI Libs...
,08-24 16:56:20.601  1034  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 16:56:20.601  1034  1941 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42dead7 mBinding = false
,08-24 16:56:20.616  1034  1096 D BluetoothManagerService: Message: 2
08-24 16:56:20.618  1034  1096 D BluetoothManagerService: Sending off request.
08-24 16:56:20.619  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 16:56:20.620  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 16:56:20.622  6950  6965 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-24 16:56:20.623  6950  7429 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-24 16:56:20.623  6950  7429 D BluetoothAdapterProperties: Setting state to 13
08-24 16:56:20.624  6950  7429 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 16:56:20.625  6950  7429 D BluetoothAdapterProperties: onBluetoothDisable()
08-24 16:56:20.625  6950  7429 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-24 16:56:20.631  6950  7433 D BluetoothAdapterProperties: Scan Mode:20
08-24 16:56:20.632  6950  7429 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-24 16:56:20.633  6950  7429 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 16:56:20.635  6950  7562 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 16:56:20.636  6950  7564 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 16:56:20.636  6950  7550 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 16:56:20.639  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-24 16:56:20.639  6950  7498 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,08-24 16:56:20.641  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 16:56:20.641  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 16:56:20.641  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 16:56:20.641  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 16:56:20.641  6950  7498 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 16:56:20.641  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 16:56:20.641  6950  7498 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 16:56:20.641  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 16:56:20.641  6950  7498 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 16:56:20.641  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-24 16:56:20.641  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-24 16:56:20.642  6950  7498 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 16:56:20.642  6950  7566 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 16:56:20.642  6950  7549 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-24 16:56:20.642  6950  7549 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 16:56:20.642  6950  7549 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-24 16:56:20.642  6950  7549 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-24 16:56:20.642  6950  7549 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-24 16:56:20.642  6950  7549 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-24 16:56:20.642  6950  7549 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-24 16:56:20.642  6950  7549 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-24 16:56:20.644  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:20.644  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:20.644  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:20.644  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:20.644  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:56:20.644  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:56:20.644  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:20.644  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:20.644  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:56:20.644  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-24 16:56:20.644  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:20.644  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:56:20.646  1034  1096 D BluetoothManagerService: Message: 60
08-24 16:56:20.646  1034  1096 D BluetoothManagerServi,ce: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-24 16:56:20.646  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-24 16:56:20.646  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:20.646  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:20.646  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:20.646  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:20.646  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:56:20.646  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:56:20.646  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:20.646  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:20.646  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:56:20.647  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:56:20.647  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:56:20.648  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 16:56:20.648  1974  1974 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:20.650  6810  6810 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-24 16:56:20.654  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:20.655  6950  6950 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:20.656  6950  6950 D BluetoothMapService: STATE_TURNING_OFF
08-24 16:56:20.656  6950  6950 V BluetoothMapService: Handler(): got msg=4
08-24 16:56:20.656  6950  6950 D BluetoothMapService: MAP Service closeService in
08-24 16:56:20.656  6950  6950 D BluetoothMapMasInstance: MAP Service shutdown
08-24 16:56:20.657  6950  6950 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 16:56:20.657  6950  6950 V BluetoothMapService: MAP Service closeService out
08-24 16:56:20.658  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:20.659  6950  6950 V BtOppService: Receiver DISABLED_ACTION 
08-24 16:56:20.659  6950  6950 I BtOppRfcommListener: stopping Accept Thread
08-24 16:56:20.659  6950  6950 V BtOppRfcommListener: close mBtServerSocket
08-24 16:56:20.659  6950  7562 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 16:56:20.660  6950  6950 V BtOppRfcommListener: waiting for thread to terminate
08-24 16:56:20.660  6950  6950 V BtOppRfcommListener: done waiting for thread to terminate
08-24 16:56:20.666  6950  6950 V BtOppService: onDestroy
,08-24 16:56:20.672  6950  6950 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-24 16:56:20.745  1034  2010 I art     : Explicit concurrent mark sweep GC freed 72567(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.333ms total 82.243ms
,08-24 16:56:20.749  6810  6810 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 16:56:20.752  6950  6950 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 16:56:20.753  6950  6950 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-24 16:56:20.753  6950  6950 V BluetoothPbapReceiver: ***********state = 13
08-24 16:56:20.754  6810  6810 D DockEventReceiver: finishStartingService: stopping service
08-24 16:56:20.757  6950  6950 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-24 16:56:20.760  6950  6950 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:20.760  6950  6950 V BluetoothPbapService: state: 13
08-24 16:56:20.760  6950  6950 V BluetoothPbapService: Pbap Service closeService in
08-24 16:56:20.762  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 16:56:20.762  6950  6950 V BluetoothPbapService: successfully stopped pbap service
08-24 16:56:20.763  6950  6950 V BluetoothPbapService: Pbap Service closeService out
08-24 16:56:20.763  6810  6810 D BluetoothPbap: Proxy object disconnected
08-24 16:56:20.763  6810  6810 D PbapServerProfile: Bluetooth service disconnected
08-24 16:56:20.763  6950  6950 V BluetoothPbapService: Pbap Service onDestroy
08-24 16:56:20.763  6950  6950 V BluetoothPbapService: Pbap Service closeService in
08-24 16:56:20.763  6950  6950 V BluetoothPbapService: Pbap Service closeService out
08-24 16:56:20.763  6950  6950 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-24 16:56:20.774  6810  6810 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-24 16:56:20.777  6810  6810 D BluetoothPermissionRequest: onReceive
08-24 16:56:20.778  6810  6810 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-24 16:56:20.781  6810  6810 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 16:56:20.783  6950  6950 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-24 16:56:20.783  6950  6950 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-24 16:56:20.783  6950  6950 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-24 16:56:20.785  7577  7577 I UEI.SmartControl: Supports setup maps: true
,08-24 16:56:20.786  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-24 16:56:20.786  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-24 16:56:20.787  6950  6950 V BluetoothFtpService: Ftp Service onStartCommand
08-24 16:56:20.787  6950  6950 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:20.788  6950  6950 V BluetoothFtpService: Ftp Service closeService
08-24 16:56:20.788  6950  6950 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-24 16:56:20.789  6950  6950 V BluetoothFtpService: successfully stopped ftp service
08-24 16:56:20.789  6950  6950 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 16:56:20.789  6950  6950 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 16:56:20.789  6950  6950 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 16:56:20.790  6950  6950 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:20.790  6950  6950 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-24 16:56:20.790  6950  6950 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-24 16:56:20.791  6950  6950 V BluetoothFtpService: Ftp Service onDestroy
08-24 16:56:20.791  6950  6950 V BluetoothFtpService: Ftp Service closeService
08-24 16:56:20.791  7577  7577 D UEI.SmartControl: QS start statue = true Error code = 0
08-24 16:56:20.791  7577  7577 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-24 16:56:20.791  7577  7577 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-24 16:56:20.791  7577  7577 I UEI.SmartControl: ### init IR Blaster...
08-24 16:56:20.794  6950  6950 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-24 16:56:20.794  6950  6950 V BluetoothSapService: state: 13
08-24 16:56:20.794  6950  6950 V BluetoothSapService: Stopping SAP server process
08-24 16:56:20.795  6950  6950 V BluetoothSapService: Sap Service closeSapService in
08-24 16:56:20.795  6950  6950 V BluetoothSapService: Close listen Socket : 
08-24 16:56:20.795  6950  6950 V BluetoothSapService: Close rfcomm Socket : 
08-24 16:56:20.795  6950  6950 V BluetoothSapService: Close sapd  Socket : 
08-24 16:56:20.797  7577  7577 D serial_port: Configuring serial port
08-24 16:56:20.797  6950  6950 V BluetoothSapService: Sap Service closeSapService out
08-24 16:56:20.797  6950  6950 V BluetoothSapService: Sap Service onDestroy
08-24 16:56:20.797  6950  6950 V BluetoothSapService: Sap Service closeSapService in
08-24 16:56:20.797  6950  6950 V BluetoothSapService: Close listen Socket : 
08-24 16:56:20.797  6950  6950 V BluetoothSapService: Close rfcomm Socket : 
08-24 16:56:20.797  6950  6950 V BluetoothSapService: Close sapd  Socket : 
08-24 16:56:20.798  6950  6950 V BluetoothSapService: Sap Service closeSapService out
,08-24 16:56:20.801  7577  7577 E UEI.SmartControl: UEIBLaster setting for 616
08-24 16:56:20.801  7577  7577 I UEI.SmartControl: Setting serial record hearder size = 2
08-24 16:56:20.802  7577  7577 I UEI.SmartControl: configuring settings for MAXQ616
,08-24 16:56:20.802  7577  7577 I UEI.SmartControl: Get version...
08-24 16:56:20.819  7577  7615 D UEI.SmartControl: serial port data available: 21
,08-24 16:56:20.847  7577  7577 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-24 16:56:20.847  7577  7577 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-24 16:56:20.847  7577  7577 I UEI.SmartControl: QS saving settings...
08-24 16:56:20.849  7577  7577 D UEI.SmartControl: IR Blaster version: 25672567
,08-24 16:56:20.866  7577  7615 D UEI.SmartControl: serial port data available: 4
,08-24 16:56:20.907  7577  7618 I UEI.SmartControl: Device manager: loading config....
,08-24 16:56:20.908  7577  7577 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-24 16:56:20.910  7577  7618 D UEI.SmartControl: ----------- loading internal config...
08-24 16:56:20.912  7577  7577 E UEI.SmartControl: Services init done
08-24 16:56:20.913  7577  7577 D UEI.SmartControl: QS Service init finished
08-24 16:56:20.915  7577  7577 D UEI.SmartControl: QS Service version name: 2.1.91
08-24 16:56:20.918  7577  7577 D UEI.SmartControl: QS Service version code: 201091
08-24 16:56:20.920  7577  7577 D UEI.SmartControl: Service requested: Control
08-24 16:56:20.928  7577  7618 E UEI.SmartControl: Loading SETTINGS...
08-24 16:56:20.930  7577  7577 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-24 16:56:20.937  1034  1992 I ActivityManager: Killing 6861:com.lge.qremote/u0a112 (adj 15): empty #17
08-24 16:56:20.946  7577  7618 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-24 16:56:20.961  7577  7617 I UEI.SmartControl: Notify AllClients services are ready: 0
08-24 16:56:20.961  7577  7617 D UEI.SmartControl: -----service ready thread exits
,08-24 16:56:21.009  1034  1941 W libprocessgroup: failed to open /acct/uid_10112/pid_6861/cgroup.procs: No such file or directory
,08-24 16:56:21.010  7577  7577 D UEI.SmartControl: Internal service binding...
,08-24 16:56:21.640  6950  7433 D bt_hci_bdroid: cleanup
,08-24 16:56:21.648  6950  7500 I bt_lpm  : LPM is already off!!!
08-24 16:56:21.650  6950  7527 I bt_userial_mct: exiting userial_read_thread
08-24 16:56:21.650  6950  7527 D bt_userial_mct: Leaving userial_evt_read_thread()
08-24 16:56:21.650  6950  7498 W bt-btif : ag scb idx 1 not allocated
08-24 16:56:21.651  6950  7498 E bt-btif : BTA AG is already disabled, ignoring ...
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 16:56:21.651  6950  7498 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 16:56:21.651  6950  7498 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 16:56:21.652  6950  7433 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-24 16:56:21.652  6950  7500 I bt_vendor: hw_epilog_process
08-24 16:56:21.652  6950  7433 D bt_hci_bdroid: cleanup Finalizing cleanup
08-24 16:56:21.652  6950  7433 D bt_userial_mct: userial_close
08-24 16:56:21.652  6950  7433 E bt_userial_mct: pthread_join() FAILED result:3
08-24 16:56:21.652  6950  7433 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-24 16:56:21.659  6950  7433 D bt_hci_bdroid: set_power 0
08-24 16:56:21.659  6950  7433 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-24 16:56:21.659  6950  7433 I bt_vendor: bluetooth satus is on
08-24 16:56:21.659  6950  7433 I bt_vendor: bt-vendor : resetting BT status
08-24 16:56:21.659  6950  7433 I bt_vendor: Starting hciattach daemon
08-24 16:56:21.659  6950  7433 I bt_vendor: try to set false
,08-24 16:56:21.665  6950  7433 I bt_vendor: Starting hciattach daemon
08-24 16:56:21.666  6950  7433 I bt_vendor: try to set false
08-24 16:56:21.667  6950  7433 I bt_vendor: cleanup
08-24 16:56:21.667  6950  7498 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-24 16:56:21.668  6950  7433 I GKI_LINUX: GKI_exit_task 0 done
08-24 16:56:21.668  6950  7433 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-24 16:56:21.670  6950  7429 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-24 16:56:21.674  6950  6950 D HeadsetService: Received stop request...Stopping profile...
,08-24 16:56:21.679  6950  6950 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-24 16:56:21.679  6950  6950 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 16:56:21.679  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:21.680  6950  7462 D HeadsetStateMachine: Exit Disconnected: -1
08-24 16:56:21.684  1876  1876 D BluetoothHeadset: Proxy object disconnected
08-24 16:56:21.684  1876  1876 D BluetoothHeadset: Proxy object disconnected
08-24 16:56:21.684  1876  1876 D BluetoothHeadset: Proxy object disconnected
08-24 16:56:21.684  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-24 16:56:21.684  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-24 16:56:21.686  6950  6950 D A2dpService: Received stop request...Stopping profile...
,08-24 16:56:21.689  6950  7490 D A2dpStateMachine: Exit Disconnected: -1
08-24 16:56:21.690  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-24 16:56:21.694  6950  6950 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-24 16:56:21.694  6950  6950 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 16:56:21.694  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:21.697  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-24 16:56:21.698  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-24 16:56:21.699  6950  7429 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-24 16:56:21.701  6950  6950 D HidService: Received stop request...Stopping profile...
08-24 16:56:21.701  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:21.704  6950  6950 D HealthService: Received stop request...Stopping profile...
08-24 16:56:21.704  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:21.706  6950  6950 D HeadsetStateMachine: Unbinding service...
08-24 16:56:21.709  6950  6950 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 16:56:21.709  6950  6950 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 16:56:21.709  6950  6950 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 16:56:21.709  6950  6950 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 16:56:21.709  6950  6950 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-24 16:56:21.709  6950  6950 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 16:56:21.709  6950  6950 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-24 16:56:21.710  6950  6950 D PanService: Received stop request...Stopping profile...
,08-24 16:56:21.713  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:21.714  6950  6950 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 16:56:21.716  6950  6950 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 16:56:21.716  6950  6950 D BtGatt.GattService: stop()
08-24 16:56:21.716  6950  6950 D BtGatt.AdvertiseManager: advertise clients cleared
08-24 16:56:21.718  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:21.719  6950  6950 I BluetoothA2dpServiceJni: cleanupNative
08-24 16:56:21.719  6950  7491 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-24 16:56:21.720  6950  6950 I GKI_LINUX: GKI_exit_task 2 done
08-24 16:56:21.720  6950  6950 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-24 16:56:21.721  6950  6950 D BluetoothMapService: Received stop request...Stopping profile...
08-24 16:56:21.721  6950  6950 D BluetoothMapService: stop()
08-24 16:56:21.722  6950  6950 D BluetoothMapEmailAppObserver: deinitObservers()
08-24 16:56:21.722  6950  6950 D BluetoothMapEmailAppObserver: removeReceiver()
,08-24 16:56:21.725  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6c470c1
08-24 16:56:21.726  6950  6950 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 16:56:21.726  6950  6950 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 16:56:21.726  6950  6950 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 16:56:21.727  6950  6950 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 16:56:21.727  6950  6950 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 16:56:21.727  6950  6950 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 16:56:21.727  6950  6950 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 16:56:21.729  6950  6950 V BluetoothMapService: Handler(): got msg=4
08-24 16:56:21.729  6950  6950 D BluetoothMapService: MAP Service closeService in
08-24 16:56:21.729  6950  6950 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 16:56:21.729  6950  6950 V BluetoothMapService: MAP Service closeService out
08-24 16:56:21.731  6950  7429 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-24 16:56:21.731  6950  7429 D BluetoothAdapterProperties: Setting state to 10
08-24 16:56:21.731  6950  7429 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-24 16:56:21.732  1034  1096 D BluetoothManagerService: Message: 60
08-24 16:56:21.732  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-24 16:56:21.732  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-24 16:56:21.732  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 16:56:21.732  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:56:21.734  6950  6950 D BluetoothMapService: cleanup()
08-24 16:56:21.734  6950  6950 D BluetoothMapService: MAP Service closeService in
08-24 16:56:21.734  6950  6950 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 16:56:21.734  6950  6950 V BluetoothMapService: MAP Service closeService out
,08-24 16:56:21.740  6950  7429 I BluetoothAdapterState: Entering OffState
08-24 16:56:21.741  6810  6829 D BluetoothMap: onBluetoothStateChange: up=false
08-24 16:56:21.742  1876  1891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:56:21.743  6810  6829 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 16:56:21.744  1876  1892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:56:21.744  6810  6829 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 16:56:21.745  6810  6829 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:56:21.745  6810  6829 D BluetoothPan: onBluetoothStateChange on: false
,08-24 16:56:21.747  1876  2566 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:56:21.748  6810  6829 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 16:56:21.750  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-24 16:56:21.750  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-24 16:56:21.752  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-24 16:56:21.752  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-24 16:56:21.752  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42dead7 mBinding = false
08-24 16:56:21.752  1034  1096 D BluetoothManagerService: Sending unbind request.
08-24 16:56:21.758  6950  7433 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-24 16:56:21.760  6950  6950 I GKI_LINUX: GKI_exit_task 1 done
08-24 16:56:21.760  6950  6950 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-24 16:56:21.760  6950  6950 I BluetoothServiceJni: cleanupNative: return from cleanup
08-24 16:56:21.761  6950  6950 I art     : --- WEIRD: removing null entry 248
08-24 16:56:21.761  6950  6950 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-24 16:56:21.761  6950  6950 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-24 16:56:21.762  6950  6950 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-24 16:56:21.763  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-24 16:56:21.765  6950  6950 I art     : System.exit called, status: 0
08-24 16:56:21.765  6950  6950 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-24 16:56:21.785   318  1383 V AudioFlinger: 6950 died, releasing its sessions
08-24 16:56:21.786   318  1383 V AudioFlinger:  pid 1876 @ 0
08-24 16:56:21.786   318  1383 V AudioFlinger:  pid 3449 @ 1
08-24 16:56:21.786   318  1383 V AudioFlinger:  pid 3449 @ 2
,08-24 16:56:21.795  6810  6810 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-24 16:56:21.796  1974  1974 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-24 16:56:21.797  1974  2170 D LGBluetoothAPIService: Message: 101
08-24 16:56:21.797  1974  2170 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-24 16:56:21.797  1974  2170 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-24 16:56:21.797  1974  2170 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-24 16:56:21.868  1034  2088 I ActivityManager: Process com.android.bluetooth (pid 6950) has died
08-24 16:56:21.869  1034  2088 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-24 16:56:21.869  1034  2088 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 10999ms
,08-24 16:56:21.879  1974  1974 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-24 16:56:21.879  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 16:56:21.880  1974  2170 D LGBluetoothAPIService: Message: 2
08-24 16:56:21.880  1974  2170 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-24 16:56:21.884  6810  6810 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-24 16:56:21.884  6810  6810 D LGBluetoothEventManager: [BTUI] clear device connection state
08-24 16:56:21.887  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:21.888  6810  6810 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 16:56:21.889  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:56:21.892  1605  1605 D BluetoothAdapter: 991491648: getState() :  mService = null. Returning STATE_OFF
08-24 16:56:21.893  1605  1605 D BluetoothAdapter: 991491648: getState() :  mService = null. Returning STATE_OFF
08-24 16:56:21.944  1034  2010 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7649 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-24 16:56:21.946  6810  6810 D DockEventReceiver: finishStartingService: stopping service
,08-24 16:56:22.014  7649  7649 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-24 16:56:22.015  7649  7649 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 16:56:22.015  7649  7649 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-24 16:56:22.016  7649  7649 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-24 16:56:22.037  7649  7649 D BluetoothAdapterApp: Loading JNI Library
,08-24 16:56:22.074  7649  7649 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@d201989 Instance Count = 1
,08-24 16:56:22.081  7649  7649 D BluetoothAdapterApp: onCreate
,08-24 16:56:22.109  7649  7649 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-24 16:56:22.110  7649  7649 D ProfileConfigQcom: Adding HeadsetService
08-24 16:56:22.110  7649  7649 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-24 16:56:22.111  7649  7649 D ProfileConfigQcom: Adding A2dpService
08-24 16:56:22.111  7649  7649 D ProfileConfigQcom: [BTUI] HidService is supported
08-24 16:56:22.112  7649  7649 D ProfileConfigQcom: Adding HidService
08-24 16:56:22.113  7649  7649 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-24 16:56:22.113  7649  7649 D ProfileConfigQcom: Adding HealthService
,08-24 16:56:22.114  7649  7649 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-24 16:56:22.115  7649  7649 D ProfileConfigQcom: [BTUI] PanService is supported
08-24 16:56:22.116  7649  7649 D ProfileConfigQcom: Adding PanService
08-24 16:56:22.116  7649  7649 D ProfileConfigQcom: [BTUI] GattService is supported
,08-24 16:56:22.118  7649  7649 D ProfileConfigQcom: Adding GattService
08-24 16:56:22.120  7649  7649 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-24 16:56:22.120  7649  7649 D ProfileConfigQcom: Adding BluetoothMapService
,08-24 16:56:22.121  7649  7649 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-24 16:56:22.123  7649  7649 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 16:56:22.126  7649  7649 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:22.126  7649  7649 V BluetoothPbapReceiver: ***********state = 10
,08-24 16:56:22.133  7649  7649 V LGMDMManagerInternal: Create singleton instance
08-24 16:56:22.253  7649  7649 D LGBluetoothAPIServer: [BTUI] onCreate()
08-24 16:56:22.253  7649  7649 D LGBluetoothAPIServer: [BTUI] onBind()
,08-24 16:56:22.256  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 16:56:22.258  1974  1974 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-24 16:56:22.258  1974  2170 D LGBluetoothAPIService: Message: 100
08-24 16:56:22.258  1974  2170 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-24 16:56:22.270  6810  6810 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-24 16:56:22.284  6810  6810 D BluetoothPermissionRequest: onReceive
,08-24 16:56:22.288  6810  6810 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-24 16:56:22.288  6810  6810 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-24 16:56:22.293  6810  6810 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 16:56:22.308  7649  7649 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-24 16:56:22.318  7649  7649 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:22.323  7649  7649 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 16:56:22.324  7649  7649 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 16:56:22.324  7649  7649 V BluetoothSapReceiver: SapReceiver onReceive 
,08-24 16:56:22.327  7649  7649 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-24 16:56:22.327  7649  7649 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-24 16:56:22.331  6881  6881 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-24 16:56:23.616  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:23.616  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:56:23.717  1605  1605 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-24 16:56:23.741  2091  2091 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-24 16:56:23.778  1034  1464 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 16:56:23.842  1034  1034 D administrator: Handling package changes for user 0
,08-24 16:56:23.848  1034  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7685 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-24 16:56:23.852  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-24 16:56:23.853  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-24 16:56:23.875  2091  2091 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-24 16:56:23.935  7685  7685 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-24 16:56:23.965  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-24 16:56:23.965  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-24 16:56:24.035  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 16:56:24.042  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-24 16:56:24.046  7685  7685 D LgDataFeature: LgDataFeature() Constructor: none
08-24 16:56:24.047  7685  7685 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 16:56:24.053  2468  2468 V GmsNetworkLocationProvi: DISABLE
,08-24 16:56:24.056  2091  2091 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-24 16:56:24.083  1034  1091 D LocationProviderProxy: applying state to connected service
08-24 16:56:24.085  2468  2468 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-24 16:56:24.162  7685  7721 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-24 16:56:24.163  7685  7721 I Babel   : MmsConfig.loadMmsSettings
08-24 16:56:24.169  7685  7721 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-24 16:56:24.169  7685  7721 I Babel   : MmsConfig.loadFromDatabase
,08-24 16:56:24.195  7685  7721 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-24 16:56:24.195  7685  7721 I Babel   : MmsConfig.loadFromResources
08-24 16:56:24.199  7685  7721 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-24 16:56:24.200  7685  7721 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-24 16:56:24.220  7685  7685 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:24.224  7685  7720 W AudioCapabilities: Unsupported mime audio/evrc
,08-24 16:56:24.225  7685  7720 W AudioCapabilities: Unsupported mime audio/qcelp
08-24 16:56:24.228  7685  7720 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-24 16:56:24.244  7685  7720 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-24 16:56:24.246  1840  7724 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-24 16:56:24.246  1840  7724 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-24 16:56:24.248  7685  7720 W AudioCapabilities: Unsupported mime audio/qcelp
08-24 16:56:24.252  7003  7003 I AppUp4:CustModeStarterReceiver: onReceive
08-24 16:56:24.252  7685  7720 W AudioCapabilities: Unsupported mime audio/evrc
,08-24 16:56:24.257  7003  7003 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bc181cb
08-24 16:56:24.257  7003  7003 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 16:56:24.257  7003  7003 D AppUp4:CustFacade: isPhone : true
08-24 16:56:24.257  7003  7003 D AppUp4:CustModeStarterReceiver: begin check event
08-24 16:56:24.258  7003  7003 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-24 16:56:24.269  1840  4731 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-24 16:56:24.271  7685  7720 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-24 16:56:24.274  7685  7720 W VideoCapabilities: Unsupported mime video/divx
08-24 16:56:24.277  7685  7720 W VideoCapabilities: Unsupported mime video/divx311
08-24 16:56:24.279  7685  7720 W VideoCapabilities: Unsupported mime video/divx4
08-24 16:56:24.287  7685  7720 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-24 16:56:24.306  7685  7720 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-24 16:56:24.310  1034  1967 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7728 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-24 16:56:24.315  1034  1967 I ActivityManager: Killing 6833:com.lge.sync/1000 (adj 15): empty #17
08-24 16:56:24.317  7685  7720 W AudioCapabilities: Unsupported mime audio/eac3
08-24 16:56:24.319  7685  7720 W AudioCapabilities: Unsupported mime audio/ac3
08-24 16:56:24.322  7685  7720 W AudioCapabilities: Unsupported mime audio/g726
,08-24 16:56:24.331  1034  1545 D WifiService: Client connection lost with reason: 4
08-24 16:56:24.338  7685  7720 W AudioCapabilities: Unsupported mime audio/wma-voice
,08-24 16:56:24.340  7685  7720 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-24 16:56:24.341  7685  7720 W AudioCapabilities: Unsupported mime audio/adpcm
08-24 16:56:24.343  7685  7720 W VideoCapabilities: Unsupported mime video/theora
08-24 16:56:24.346  7685  7720 W VideoCapabilities: Unsupported mime video/mjpg
08-24 16:56:24.401  1034  1991 W libprocessgroup: failed to open /acct/uid_1000/pid_6833/cgroup.procs: No such file or directory
,08-24 16:56:24.453  7728  7728 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 16:56:24.454  7728  7728 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-24 16:56:24.456  7728  7728 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-24 16:56:24.459  7728  7728 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-24 16:56:24.459  7728  7728 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 16:56:24.546  7728  7728 I SystemConfig: BUILD Country: EU
08-24 16:56:24.546  7728  7728 I SystemConfig: BUILD Operator: OPEN
,08-24 16:56:24.596  1034  1992 I ActivityManager: Killing 7040:com.lge.email/u0a23 (adj 15): empty #17
,08-24 16:56:24.820  1034  1992 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7751 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-24 16:56:24.820  1034  2088 W libprocessgroup: failed to open /acct/uid_10023/pid_7040/cgroup.procs: No such file or directory
,08-24 16:56:24.831  7728  7749 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-24 16:56:24.831  7728  7749 I SystemConfig: existFile = false
08-24 16:56:24.832  7728  7749 I SystemConfig: canReadFile = false
08-24 16:56:24.832  7728  7749 I SystemConfig: systemFeature RCS result false
08-24 16:56:24.832  7728  7749 D SystemConfig: refreshRcsSupport() :false
,08-24 16:56:24.887  7751  7751 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 16:56:24.888  7751  7751 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-24 16:56:24.888  7751  7751 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-24 16:56:24.888  7751  7751 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 16:56:24.985  7751  7751 I AppConfig: Total System Memory = 2995761152
,08-24 16:56:24.995  7751  7751 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-24 16:56:25.082  1034  2056 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7770 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 16:56:25.083  1034  2056 I ActivityManager: Killing 6907:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-24 16:56:25.179  1034  2033 W libprocessgroup: failed to open /acct/uid_10026/pid_6907/cgroup.procs: No such file or directory
,08-24 16:56:25.376  7770  7770 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-24 16:56:25.473  7770  7770 D LgDataFeature: LgDataFeature() Constructor: none
08-24 16:56:25.473  7770  7770 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 16:56:25.525  7770  7770 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-24 16:56:25.546  7770  7770 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-24 16:56:25.547  7770  7770 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-24 16:56:25.574  7770  7770 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 16:56:25.574  7770  7770 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-24 16:56:25.591  1034  1050 I ActivityManager: Killing 6390:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-24 16:56:25.624  1034  1920 W libprocessgroup: failed to open /acct/uid_1000/pid_6390/cgroup.procs: No such file or directory
,08-24 16:56:25.629  2849  2865 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-24 16:56:25.630  2849  2865 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@338de67f on behalf of 7770
08-24 16:56:25.635  4583  7810 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-24 16:56:25.686  1034  1050 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7812 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-24 16:56:25.701  7770  7770 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-24 16:56:25.737  7770  7770 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-24 16:56:25.802  7812  7812 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-24 16:56:25.826  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-24 16:56:25.826  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-24 16:56:25.826  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-24 16:56:25.826  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-24 16:56:25.826  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-24 16:56:25.826  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-24 16:56:25.846  1034  1603 I ActivityManager: Killing 7091:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-24 16:56:25.905  7577  7619 D UEI.SmartControl: Internal timer expired: 1
,08-24 16:56:25.905  7577  7619 D UEI.SmartControl: unbind internal service
08-24 16:56:25.910  1034  2056 W libprocessgroup: failed to open /acct/uid_10046/pid_7091/cgroup.procs: No such file or directory
08-24 16:56:25.917  7577  7577 D UEI.SmartControl: Service.onUnbind: IControl
,08-24 16:56:25.917  7577  7577 D UEI.SmartControl: Service.onDestroy
08-24 16:56:25.918  7577  7577 D UEI.SmartControl: Lock is in USE false
08-24 16:56:25.918  7577  7577 D UEI.SmartControl: unbind internal service
08-24 16:56:25.918  7577  7577 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@22646fa7
08-24 16:56:25.918  7577  7577 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-24 16:56:25.918  7577  7577 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-24 16:56:25.918  7577  7577 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-24 16:56:25.918  7577  7577 W System.err: 	at com.uei.control.Service.c(Unknown Source)
,08-24 16:56:25.918  7577  7577 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-24 16:56:25.918  7577  7577 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-24 16:56:25.918  7577  7577 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-24 16:56:25.918  7577  7577 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-24 16:56:25.918  7577  7577 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:56:25.918  7577  7577 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 16:56:25.918  7577  7577 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 16:56:25.919  7577  7577 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:56:25.919  7577  7577 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 16:56:25.919  7577  7577 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 16:56:25.919  7577  7577 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 16:56:25.919  7577  7577 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@22646fa7
08-24 16:56:25.919  7577  7577 D serial_port: close(fd = 25)
08-24 16:56:25.922  7577  7577 I UEI.SmartControl: Serial port is closed.
08-24 16:56:25.923  7577  7577 I UEI.SmartControl: Serial port is closed.
08-24 16:56:25.923  7577  7577 D UEI.SmartControl: Blaster closed
08-24 16:56:25.923  7577  7577 D UEI.SmartControl: Shut down QS...
08-24 16:56:25.923  7577  7577 D UEI.SmartControl: Stopping QS lib
08-24 16:56:25.924  7577  7577 D UEI.SmartControl: QS lib stop result = true
08-24 16:56:25.924  7577  7577 D UEI.SmartControl: Stopped QS lib
08-24 16:56:25.924  7577  7577 D UEI.SmartControl: Stopped file observer...
08-24 16:56:25.924  7577  7577 D UEI.SmartControl: QS shutdown complete
08-24 16:56:26.140  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
,08-24 16:56:26.166  4583  7810 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 531 ms] updated apps [took 531 ms] 
,08-24 16:56:26.632  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 16:56:26.640  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30328e25 added. We now have 6 listener(s)
08-24 16:56:26.640  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:26.642  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:26.642  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@273fbfa added. We now have 7 listener(s)
08-24 16:56:26.642  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:26.642  6695  6771 I System.out: IsBluetoothEnabled
08-24 16:56:26.643  1034  1967 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:26.643  1034  1967 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-24 16:56:26.644  1034  1096 D BluetoothManagerService: Message: 2
08-24 16:56:26.647  6695  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:26.647  1034  2038 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:26.647  1034  2038 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-24 16:56:26.665  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 16:56:26.666  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 16:56:26.666  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-24 16:56:26.669  1034  1096 D BluetoothManagerService: Message: 1
08-24 16:56:26.670  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-24 16:56:26.696  1034  1096 D BluetoothManagerService: Message: 20
08-24 16:56:26.696  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@331c22d:true
,08-24 16:56:26.700  7649  7649 D BluetoothAdapterState: make
08-24 16:56:26.705  7649  7649 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-24 16:56:26.705  7649  7649 I bluedroid-qcom: init
08-24 16:56:26.706  7649  7856 I BluetoothAdapterState: Entering OffState
08-24 16:56:26.706  7649  7649 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-24 16:56:26.707  7649  7649 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-24 16:56:26.707  7649  7649 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 16:56:26.707  7649  7649 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 16:56:26.707  7649  7649 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-24 16:56:26.709  7649  7649 I bluedroid-qcom: get_profile_interface socket
08-24 16:56:26.709  7649  7649 I bluedroid-qcom: get_profile_interface map_client
,08-24 16:56:26.713  7649  7860 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-24 16:56:26.705  7859  7859 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:26.715  7859  7859 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:26.726  7859  7859 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-24 16:56:26.726  7859  7859 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-24 16:56:26.726  7859  7859 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-24 16:56:26.732  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-24 16:56:26.732  1034  1096 D BluetoothManagerService: Message: 40
08-24 16:56:26.732  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-24 16:56:26.733  7649  7664 I bluedroid-qcom: config_hci_snoop_log
08-24 16:56:26.734  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-24 16:56:26.734  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-24 16:56:26.737  7649  7860 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-24 16:56:26.737  7859  7859 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-24 16:56:26.740  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 16:56:26.740  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
,08-24 16:56:26.744  7649  7860 D BluetoothAdapterProperties: Name is: G3
08-24 16:56:26.746  7859  7859 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-24 16:56:26.746  7859  7859 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-24 16:56:26.750  7649  7856 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-24 16:56:26.751  7649  7856 D BluetoothAdapterProperties: Setting state to 11
08-24 16:56:26.751  7649  7856 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-24 16:56:26.753  7649  7856 I LGBluetoothServiceJni: classInitNative: succeeds
,08-24 16:56:26.759  1034  1096 D BluetoothManagerService: Message: 60
08-24 16:56:26.759  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-24 16:56:26.759  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-24 16:56:26.763  1974  1974 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:26.764  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 16:56:26.767  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:56:26.772  6810  6810 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-24 16:56:26.776  7649  7649 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 16:56:26.776  7649  7649 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:26.776  7649  7649 V BluetoothPbapReceiver: ***********state = 11
08-24 16:56:26.795  7649  7856 D BluetoothBondStateMachine: make
,08-24 16:56:26.797  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 16:56:26.798  7649  7856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32450066
08-24 16:56:26.799  7649  7856 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-24 16:56:26.799  7649  7856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32450066
08-24 16:56:26.799  7649  7856 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-24 16:56:26.800  7649  7856 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-24 16:56:26.800  7649  7873 I BluetoothBondStateMachine: StableState(): Entering Off State
08-24 16:56:26.803  7649  7856 E BluetoothAdapterService: File transfer profiles supported!!
08-24 16:56:26.813  7649  7856 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 16:56:26.814  7649  7649 D HeadsetService: Received start request. Starting profile...
08-24 16:56:26.815  7649  7649 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 16:56:26.815  7649  7649 D LGBluetoothHfpAdapter: Version 1.6
08-24 16:56:26.819  7649  7649 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-24 16:56:26.820  7649  7649 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 16:56:26.820  7649  7856 E BluetoothAdapterService: File transfer profiles supported!!
08-24 16:56:26.820  7649  7649 D HeadsetStateMachine: make
08-24 16:56:26.821  6810  6810 D BluetoothPermissionRequest: onReceive
08-24 16:56:26.831  6810  6810 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 16:56:26.831  7649  7856 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 16:56:26.839  7649  7856 E BluetoothAdapterService: File transfer profiles supported!!
08-24 16:56:26.845  7649  7856 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 16:56:26.851  7649  7856 E BluetoothAdapterService: File transfer profiles supported!!
08-24 16:56:26.861  7649  7649 D LgDataFeature: LgDataFeature() Constructor: none
,08-24 16:56:26.861  7649  7649 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 16:56:26.865  7649  7649 D HeadsetStateMachine: max_hf_connections = 1
08-24 16:56:26.866  7649  7649 I bluedroid-qcom: get_profile_interface handsfree
08-24 16:56:26.868  7649  7856 V LGMDMManager: Create singleton instance
08-24 16:56:26.868  7649  7649 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-24 16:56:26.869   318  3991 V AudioPolicyService: registerClient() client 0xb1542900, uid 1002
08-24 16:56:26.869   318  1384 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-24 16:56:26.869   318  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 16:56:26.869   318  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 16:56:26.869  7649  7649 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-24 16:56:26.870   318   318 V AudioFlinger: registerClient() client 0xb14386b8, pid 7649
08-24 16:56:26.870  7649  7856 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-24 16:56:26.870   318  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 16:56:26.870   318  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 16:56:26.870  1605  1938 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 16:56:26.870  1605  1938 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 16:56:26.870  3449  3464 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 16:56:26.871   318  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 16:56:26.871   318  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 16:56:26.871  1876  2567 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 16:56:26.871  1876  2567 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 16:56:26.871  1034  1967 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 16:56:26.871  1034  1967 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 16:56:26.871  1605  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 16:56:26.871  1605  1625 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 16:56:26.871  1034  1967 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 16:56:26.871  1034  1967 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 16:56:26.871  3449  3464 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 16:56:26.871  1876  1891 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 16:56:26.871  1876  1891 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 16:56:26.871  3449  3464 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 16:56:26.871  3449  3464 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 16:56:26.871  7649  7665 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 16:56:26.871  7649  7665 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-24 16:56:26.871  7649  7665 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 16:56:26.871  7649  7665 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-24 16:56:26.871  7649  7649 V ToneGenerator: Create Track: 0xb4928a80
08-24 16:56:26.871  7649  7649 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-24 16:56:26.871  7649  7649 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-24 16:56:26.871   318  3991 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 16:56:26.871   318  3991 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, form,at 0, channelMask 3, flags 0
08-24 16:56:26.871   318  3991 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 16:56:26.871   318  3991 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 16:56:26.872   318  1384 I AudioFlinger: isAudioPlaybackHookOn() false
08-24 16:56:26.872   318   318 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 16:56:26.872   318   318 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-24 16:56:26.872   318   318 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 16:56:26.872   318   318 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 16:56:26.873  7649  7649 V AudioSystem: getLatency() output 2, latency 50
08-24 16:56:26.873  7649  7649 V AudioSystem: getFrameCount() output 2, frameCount 960
08-24 16:56:26.873  7649  7649 V AudioTrack: createTrack_l() output 2 afLatency 50
08-24 16:56:26.873   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 16:56:26.873   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 16:56:26.873   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 16:56:26.873   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 16:56:26.873   318  1383 V AudioFlinger: createTrack() lSessionId: 23
08-24 16:56:26.874  7649  7649 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-24 16:56:26.874   318  3991 V AudioFlinger: acquiring 23 from 7649, for 7649
08-24 16:56:26.874   318  3991 V AudioFlinger:  added new entry for 23
08-24 16:56:26.874  7649  7649 V ToneGenerator: ToneGenerator INIT OK, time: 219966
08-24 16:56:26.874  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32450066
08-24 16:56:26.875  7649  7876 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-24 16:56:26.875  7649  7876 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 16:56:26.875  7649  7876 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 16:56:26.875  7649  7876 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-24 16:56:26.876  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32450066
08-24 16:56:26.876   318  1384 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7649
08-24 16:56:26.877   318  1384 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-24 16:56:26.877   318  1384 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-24 16:56:26.877   318  1384 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-24 16:56:26.877   318  1384 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-24 16:56:26.877   318  1384 V voice   : voice_set_parameters: exit with code(0)
08-24 16:56:26.877   318  1384 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-24 16:56:26.877   318  1384 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-24 16:56:26.877   318  1384 V msm8974_platform: platform_set_parameters: exit with code(0)
08-24 16:56:26.877   318  1384 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-24 16:56:26.877   318  1384 V audio_hw_primary: adev_set_parameters: exit with code(0)
,08-24 16:56:26.877   318  1384 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-24 16:56:26.877  7649  7876 V ToneGenerator: ToneGenerator destructor
08-24 16:56:26.877  7649  7876 V ToneGenerator: stopTone
08-24 16:56:26.877  7649  7876 V ToneGenerator: Delete Track: 0xb4928a80
08-24 16:56:26.878  7649  7649 D A2dpService: Received start request. Starting profile...
08-24 16:56:26.878  7649  7649 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-24 16:56:26.879  7649  7649 V Avrcp   : make
08-24 16:56:26.880  7649  7649 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-24 16:56:26.880  7649  7649 I bluedroid-qcom: get_profile_interface avrcp
08-24 16:56:26.882  7649  7876 V AudioTrack: ~AudioTrack, releasing session id from 7649 on behalf of 7649
08-24 16:56:26.882   318  3991 V AudioFlinger: releasing 23 from 7649 for 7649
08-24 16:56:26.882   318  3991 V AudioFlinger:  decremented refcount to 0
08-24 16:56:26.882   318  3991 V AudioFlinger: purging stale effects
08-24 16:56:26.883   318  3991 V AudioPolicyService: AudioCommandThread() adding release output 2
08-24 16:56:26.883   318  3991 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-24 16:56:26.883   318  1259 V AudioPolicyService: AudioCommandThread() waking up
08-24 16:56:26.883   318  3991 V AudioFlinger: PlaybackThread::Track destructor
08-24 16:56:26.883   318  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
08-24 16:56:26.883   318  3991 V AudioFlinger: removeClient_l() pid 7649, calling pid 318
08-24 16:56:26.883   318  1259 V AudioPolicyManager: releaseOutput() 2
08-24 16:56:26.883   318  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-24 16:56:26.890  7649  7649 V AudioManager: registerRemoteController: size of Media player list: 0
,08-24 16:56:26.892  7649  7649 E AudioManager: No RCC entry present to update
08-24 16:56:26.892  7649  7649 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-24 16:56:26.896  7649  7649 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-24 16:56:26.897  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-24 16:56:26.897  7649  7649 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-24 16:56:26.901  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-24 16:56:27.014  1034  2010 V SIM_STK : Menu title from STK is T-Mobile
08-24 16:56:27.014  1034  2010 V SIM_STK : Menu title from STK is T-Mobile
,08-24 16:56:27.137  1034  2056 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-24 16:56:27.144  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-24 16:56:27.149  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-24 16:56:27.149  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-24 16:56:27.149  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-24 16:56:27.149  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-24 16:56:27.149  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 16:56:27.149  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-24 16:56:27.149  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-24 16:56:27.149  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-24 16:56:27.149  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 16:56:27.149  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-24 16:56:27.150  7649  7649 I BluetoothA2dpServiceJni: classInitNative
08-24 16:56:27.150  7649  7649 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 16:56:27.150  7649  7649 D A2dpStateMachine: make
08-24 16:56:27.153  7649  7649 I bluedroid-qcom: get_profile_interface a2dp
08-24 16:56:27.153  7649  7887 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-24 16:56:27.156  7649  7649 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-24 16:56:27.156  7649  7649 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-24 16:56:27.156  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32450066
08-24 16:56:27.157  7649  7886 D A2dpStateMachine: Enter Disconnected: -2
08-24 16:56:27.157  7649  7649 I BluetoothHidServiceJni: classInitNative: succeeds
08-24 16:56:27.159  7649  7649 D HidService: Received start request. Starting profile...
08-24 16:56:27.159  7649  7649 I bluedroid-qcom: get_profile_interface hidhost
08-24 16:56:27.159  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32450066
08-24 16:56:27.159  7649  7649 I BluetoothHealthServiceJni: classInitNative: succeeds
08-24 16:56:27.161  7649  7649 D HealthService: Received start request. Starting profile...
08-24 16:56:27.164  7649  7649 I bluedroid-qcom: get_profile_interface health
08-24 16:56:27.164  7649  7649 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-24 16:56:27.164  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32450066
08-24 16:56:27.165  7649  7649 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-24 16:56:27.166  7649  7649 D PanService: Received start request. Starting profile...
08-24 16:56:27.166  7649  7649 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 16:56:27.167  7649  7649 I bluedroid-qcom: get_profile_interface pan
,08-24 16:56:27.171  7649  7649 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-24 16:56:27.171  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32450066,
08-24 16:56:27.172  7649  7649 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-24 16:56:27.175  7649  7649 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 16:56:27.176  7649  7649 D BtGatt.GattService: Received start request. Starting profile...
08-24 16:56:27.176  7649  7649 D BtGatt.GattService: start()
08-24 16:56:27.176  7649  7649 I bluedroid-qcom: get_profile_interface gatt
08-24 16:56:27.176  7649  7649 D BtGatt.AdvertiseManager: advertise manager created
08-24 16:56:27.184  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32450066
08-24 16:56:27.185  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32450066
08-24 16:56:27.185  7649  7649 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-24 16:56:27.186  7649  7649 V BluetoothMapService: BluetoothMapBinder()
08-24 16:56:27.187  7649  7649 D BluetoothMapService: Received start request. Starting profile...
08-24 16:56:27.187  7649  7649 D BluetoothMapService: start()
,08-24 16:56:27.189  7649  7649 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-24 16:56:27.190  7649  7649 D BluetoothMapEmailAppObserver: createReceiver()
08-24 16:56:27.190  7649  7649 D BluetoothMapEmailAppObserver: initObservers()
08-24 16:56:27.191  7649  7649 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-24 16:56:27.196  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32450066
08-24 16:56:27.196  7649  7649 D HeadsetStateMachine: Proxy object connected
08-24 16:56:27.197  7649  7649 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-24 16:56:27.197  7649  7649 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-24 16:56:27.202  7649  7649 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 16:56:27.203  7649  7876 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 16:56:27.204  7649  7876 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 16:56:27.204  7649  7649 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 16:56:27.204  7649  7876 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-24 16:56:27.206  7649  7649 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-24 16:56:27.208  7649  7649 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:27.210  7649  7649 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 16:56:27.210  7649  7649 V PanService: [BTUI] SIM Extra State :ABSENT
08-24 16:56:27.212  7649  7649 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 16:56:27.215  7649  7649 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-24 16:56:27.215  7649  7649 V BluetoothMapService: Handler(): got msg=1
08-24 16:56:27.216  7649  7649 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 16:56:27.216  7649  7649 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 16:56:27.216  7649  7649 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 16:56:27.216  7649  7649 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:27.216  7649  7649 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-24 16:56:27.216  7649  7856 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-24 16:56:27.216  7649  7856 I bluedroid-qcom: enable
08-24 16:56:27.217  7649  7856 I bt_hci_bdroid: init
08-24 16:56:27.221  7649  7895 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-24 16:56:27.221  7649  7895 I bt-btu  : btu_task pending for preload complete event
08-24 16:56:27.221  7649  7856 I bt_vendor: bt-vendor : init
08-24 16:56:27.221  7649  7856 I bt_vendor: bt-vendor : get_bt_soc_type
08-24 16:56:27.221  7649  7856 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-24 16:56:27.222  7649  7856 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-24 16:56:27.222  7649  7856 D bt_userial_mct: userial_init
08-24 16:56:27.222  7649  7856 D bt_hci_bdroid: set_power 1
08-24 16:56:27.222  7649  7856 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-24 16:56:27.222  7649  7856 I bt_vendor: Starting hciattach daemon
,08-24 16:56:27.223  7649  7856 I bt_vendor: try to set true
,08-24 16:56:27.215  7898  7898 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:27.215  7898  7898 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:27.252  7899  7899 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-24 16:56:27.356  7905  7905 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-24 16:56:27.371  7906  7906 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-24 16:56:27.401  7908  7908 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-24 16:56:27.421  7909  7909 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-24 16:56:27.442  7910  7910 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-24 16:56:27.456  7911  7911 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-24 16:56:27.479  7913  7913 I libmdmdetect: ESOC framework not supported
,08-24 16:56:27.481  7913  7913 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-24 16:56:27.494  7913  7913 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-24 16:56:27.494  7913  7913 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-24 16:56:27.494  7913  7913 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-24 16:56:27.494  7913  7913 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-24 16:56:27.494  7913  7913 D bthci_qcomm_common: [BTUI]     LE: Class 2
,08-24 16:56:27.495  7913  7913 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-24 16:56:27.495  7913  7913 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-24 16:56:27.543  7913  7914 E QC-QMI  : qmi_client [7913] 15: failed to locate client data
,08-24 16:56:27.549   466   466 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-24 16:56:27.549   466   466 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-24 16:56:27.590  7915  7915 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-24 16:56:27.605  7916  7916 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-24 16:56:27.629  7649  7856 I bt_vendor: bluetooth satus is on
08-24 16:56:27.629  7649  7856 D bt_hci_bdroid: preload
08-24 16:56:27.629  7649  7897 D bt_userial_mct: userial_open(port:0)
08-24 16:56:27.629  7649  7897 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-24 16:56:27.633  7649  7897 I bt_vendor: Done intiailizing UART
08-24 16:56:27.633  7649  7897 I bt_vendor: Done intiailizing UART
08-24 16:56:27.633  7649  7897 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-24 16:56:27.633  7649  7897 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-24 16:56:27.633  7649  7918 D bt_userial_mct: Entering userial_read_thread()
08-24 16:56:27.634  7649  7895 I bt-btu  : btu_task received preload complete event
08-24 16:56:27.634  7649  7895 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-24 16:56:27.634  7649  7895 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-24 16:56:27.636  7649  7895 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_HCI
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_AVDT
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_AVRC
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_BTM
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 16:56:27.640  7649  7895 I         : BTE_InitTraceLevels -- TRC_BTIF
08-24 16:56:27.697  7649  7895 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-24 16:56:27.697  7649  7895 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ff061 
08-24 16:56:27.697  7649  7895 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ff061 
,08-24 16:56:27.721  7649  7860 E bt-btif : Calling BTA_HhEnable
08-24 16:56:27.721  7649  7860 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-24 16:56:27.722  7649  7860 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-24 16:56:27.726  7649  7895 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-24 16:56:27.726  7649  7895 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-24 16:56:27.726  7649  7895 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-24 16:56:27.726  7649  7895 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-24 16:56:27.726  7649  7895 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-24 16:56:27.728  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 16:56:27.728  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-24 16:56:27.729  7649  7860 D BluetoothAdapterProperties: Name is: G3
08-24 16:56:27.732  7649  7860 D BluetoothAdapterProperties: Scan Mode:20
08-24 16:56:27.732  7649  7860 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 16:56:27.732  7649  7860 D bt_hci_bdroid: postload
08-24 16:56:27.732  7649  7897 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 16:56:27.734  7649  7897 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 16:56:27.737  7649  7895 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-24 16:56:27.740  7649  7860 D bte_conf: Device ID record 1 : primary
08-24 16:56:27.741  7649  7860 D bte_conf:   vendorId            = 00c4
08-24 16:56:27.741  7649  7860 D bte_conf:   vendorIdSource      = 0001
08-24 16:56:27.741  7649  7860 D bte_conf:   product             = 13a1
08-24 16:56:27.741  7649  7860 D bte_conf:   version             = 1000
08-24 16:56:27.741  7649  7860 D bte_conf:   clientExecutableURL = 
08-24 16:56:27.741  7649  7860 D bte_conf:   serviceDescription  = 
08-24 16:56:27.741  7649  7860 D bte_conf:   documentationURL    = 
08-24 16:56:27.741  7649  7860 D bte_conf: bte_load_did_conf no section named DID2.
08-24 16:56:27.742  7649  7897 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 16:56:27.747  7649  7856 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-24 16:56:27.747  7649  7856 D BluetoothAdapterProperties: ScanMode =  20
08-24 16:56:27.747  7649  7856 D BluetoothAdapterProperties: State =  11
08-24 16:56:27.747  7649  7856 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-24 16:56:27.750  7649  7856 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-24 16:56:27.751  7649  7856 D BluetoothAdapterProperties: Setting state to 12
08-24 16:56:27.751  7649  7856 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-24 16:56:27.753  7649  7860 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-24 16:56:27.745  7926  7926 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:27.756  1034  1096 D BluetoothManagerService: Message: 60
08-24 16:56:27.756  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-24 16:56:27.756  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-24 16:56:27.756  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 16:56:27.745  7926  7926 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:27.761  7649  7856 I BluetoothAdapterState: Entering On State
08-24 16:56:27.767  7649  7895 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 16:56:27.767  7649  7895 W bt-smp  : Plain text(LSB ~ MSB) = d2 06 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 16:56:27.767  7649  7895 W bt-smp  : Encrypted text(LSB ~ MSB) = c9 51 3b 13 e8 bd 65 e5 0f 04 8c 76 33 e6 13 a9 
,08-24 16:56:27.769  7649  7897 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 16:56:27.769  7649  7895 W bt-btm  : Stopping oneshot timer
08-24 16:56:27.777  7649  7918 E bt_mct  : hci lib postload completed
08-24 16:56:27.779  7649  7860 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-24 16:56:27.785  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:27.808  7649  7856 D LGBluetoothServiceAdapter: [BTUI] OnState
,08-24 16:56:27.810  7649  7856 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-24 16:56:27.811  7649  7856 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-24 16:56:27.814  7649  7856 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-24 16:56:27.814  7649  7856 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-24 16:56:27.815  7649  7895 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 16:56:27.815  7649  7895 W bt-smp  : Plain text(LSB ~ MSB) = cc 88 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 16:56:27.815  7649  7895 W bt-smp  : Encrypted text(LSB ~ MSB) = ae 9b d8 19 61 d8 38 25 73 b4 42 20 4f a6 19 5e 
08-24 16:56:27.815  7649  7895 W bt-btm  : Stopping oneshot timer
08-24 16:56:27.815  7649  7860 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 16:56:27.816  7649  7860 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-24 16:56:27.816  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 16:56:27.825  1034  1034 D BluetoothA2dp: Proxy object connected
,08-24 16:56:27.835  7649  7895 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 16:56:27.835  7649  7895 W bt-smp  : Plain text(LSB ~ MSB) = 59 2f 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 16:56:27.836  7649  7895 W bt-smp  : Encrypted text(LSB ~ MSB) = 1e a7 9b bc 2a f8 31 c3 4a 28 bf d0 9e 7c 87 d7 
08-24 16:56:27.836  7649  7895 W bt-btm  : Stopping oneshot timer
08-24 16:56:27.836  1034  1034 D BluetoothHeadset: Proxy object connected
08-24 16:56:27.842  6810  6829 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 16:56:27.871  7931  7931 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-24 16:56:27.880  1876  2566 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 16:56:27.882  1876  1876 D BluetoothHeadset: Proxy object connected
08-24 16:56:27.882  6810  6829 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 16:56:27.884  7649  7895 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 16:56:27.884  7649  7895 W bt-smp  : Plain text(LSB ~ MSB) = 67 15 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 16:56:27.884  7649  7895 W bt-smp  : Encrypted text(LSB ~ MSB) = a5 3c 0e 19 ee 70 74 48 44 52 3f 32 43 ce 58 8c 
08-24 16:56:27.884  7649  7895 W bt-btm  : Stopping oneshot timer
08-24 16:56:27.885  1876  1891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 16:56:27.890  6810  6810 D BluetoothMap: Proxy object connected
,08-24 16:56:27.894  6810  6810 D MapProfile: Bluetooth service connected
08-24 16:56:27.895  6810  6810 D BluetoothMap: getConnectedDevices()
08-24 16:56:27.896  7649  7664 V BluetoothMapService: getConnectedDevices()
08-24 16:56:27.897  1876  1876 D BluetoothHeadset: Proxy object connected
08-24 16:56:27.902  6810  6828 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 16:56:27.905  6810  6828 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 16:56:27.906  6810  6810 D BluetoothA2dp: Proxy object connected
,08-24 16:56:27.906  6810  6810 D A2dpProfile: Bluetooth service connected
,08-24 16:56:27.910  7649  7895 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 16:56:27.910  7649  7895 W bt-smp  : Plain text(LSB ~ MSB) = 5d ff 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 16:56:27.910  7649  7895 W bt-smp  : Encrypted text(LSB ~ MSB) = f6 b8 e6 fd 1f 6e 10 49 cc 3a ab 8c 0e 87 b1 54 
08-24 16:56:27.910  7649  7895 W bt-btm  : Stopping oneshot timer
08-24 16:56:27.911  6810  6828 D BluetoothPan: onBluetoothStateChange on: true
08-24 16:56:27.911  6810  6828 D BluetoothPan: onBluetoothStateChange call bindService
08-24 16:56:27.912  6810  6810 D BluetoothHeadset: Proxy object connected
08-24 16:56:27.912  6810  6810 D HeadsetProfile: Bluetooth service connected
08-24 16:56:27.915  1876  2567 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 16:56:27.918  6810  6829 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 16:56:27.919  1876  1876 D BluetoothHeadset: Proxy object connected
08-24 16:56:27.921  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-24 16:56:27.922  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-24 16:56:27.923  1974  1974 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:27.924  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 16:56:27.928  1974  2170 D LGBluetoothAPIService: Message: 1
08-24 16:56:27.928  1974  2170 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-24 16:56:27.928  1974  2170 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-24 16:56:27.929  6810  6810 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 16:56:27.930  6810  6810 D PanProfile: Bluetooth service connected
,08-24 16:56:27.936  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-24 16:56:27.936  1034  1096 D BluetoothManagerService: Message: 40
08-24 16:56:27.936  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-24 16:56:27.937  1974  2170 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-24 16:56:27.938  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:27.938  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:27.938  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:27.938  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:56:27.938  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:27.938  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:27.938  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:27.938  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:56:27.944  7649  7649 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:27.944  7649  7649 D BluetoothMapService: STATE_ON
08-24 16:56:27.944  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 16:56:27.945  6810  6810 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-24 16:56:27.947  6810  6810 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 16:56:27.954  6810  6810 D BluetoothInputDevice: Proxy object connected
08-24 16:56:27.954  6810  6810 D HidProfile: Bluetooth service connected
08-24 16:56:27.960  6810  6810 D DockEventReceiver: finishStartingService: stopping service
,08-24 16:56:27.961  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32450066
,08-24 16:56:27.961  7649  7649 V BluetoothPbapService: Pbap Service onCreate
08-24 16:56:27.961  7649  7649 V BluetoothPbapService: Starting PBAP service
08-24 16:56:27.963  7649  7649 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-24 16:56:27.963  7649  7649 V BluetoothPbapService: Pbap Service onBind
08-24 16:56:27.964  6810  6810 D BluetoothPbap: Proxy object connected
08-24 16:56:27.964  7649  7649 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:27.964  6810  6810 D PbapServerProfile: Bluetooth service connected
08-24 16:56:27.965  7649  7649 V BluetoothPbapService: state: 12
08-24 16:56:27.965  7649  7649 V BluetoothMapService: Handler(): got msg=1
08-24 16:56:27.965  7649  7649 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-24 16:56:27.966  7649  7649 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 16:56:27.966  7649  7649 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:27.966  7649  7649 V BluetoothPbapReceiver: ***********state = 12
08-24 16:56:27.967  7649  7952 D BluetoothMapMasInstance: MAS initSocket()
,08-24 16:56:27.967  7649  7952 D BluetoothMapMasInstance:   masId = 00
08-24 16:56:27.967  7649  7952 D BluetoothMapMasInstance:   msgTypes = 0e
08-24 16:56:27.967  7649  7952 D BluetoothMapMasInstance:   masName = SMS/MMS
08-24 16:56:27.967  7649  7952 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-24 16:56:27.968  7649  7649 V BluetoothPbapService: Handler(): got msg=1
08-24 16:56:27.969  7649  7649 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-24 16:56:27.971  7649  7953 V BluetoothPbapService: Pbap Service initSocket
08-24 16:56:27.972  1034  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:27.972  1034  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:27.972  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 16:56:27.973  2209  2209 D c       : Getting all permits...
08-24 16:56:27.973  2209  2209 D a       : Opening database...
,08-24 16:56:27.974  7649  7953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 16:56:27.976  7649  7953 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-24 16:56:27.977  7649  7953 V BluetoothPbapService: Succeed to create listening socket 
08-24 16:56:27.977  7649  7953 V BluetoothPbapService: Accepting socket connection...
08-24 16:56:27.977  7649  7860 D BluetoothAdapterProperties: Scan Mode:21
08-24 16:56:27.977  7649  7860 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-24 16:56:27.979  2209  2209 D a       : Opening database auth.proximity.permit_store...
08-24 16:56:27.979  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:27.980  2209  2209 D a       : Closing database...
08-24 16:56:27.980  7649  7952 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 16:56:27.985  7649  7952 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-24 16:56:27.985  7649  7952 V BluetoothMapMasInstance: Succeed to create listening socket 
08-24 16:56:27.985  7649  7952 D BluetoothMapMasInstance: Accepting socket connection...
,08-24 16:56:27.993  6810  6810 D BluetoothPermissionRequest: onReceive
08-24 16:56:27.995  6810  6810 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-24 16:56:27.996  6810  6810 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 16:56:27.999  7649  7649 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-24 16:56:28.001  7649  7649 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-24 16:56:28.007  7649  7649 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-24 16:56:28.027  7649  7649 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-24 16:56:28.027  7649  7649 V BtOppService: onCreate
,08-24 16:56:28.032  7649  7649 V BluetoothOppNotification: send message
08-24 16:56:28.038  7649  7649 V BtOppService: Starting RfcommListener
08-24 16:56:28.048  7649  7649 D BluetoothOppPreference: Dumping Names:  
08-24 16:56:28.048  7649  7649 D BluetoothOppPreference: {}
,08-24 16:56:28.049  7649  7649 D BluetoothOppPreference: Dumping Channels:  
08-24 16:56:28.049  7649  7649 D BluetoothOppPreference: {}
08-24 16:56:28.050  7649  7649 V BtOppService: onStartCommand
08-24 16:56:28.052  7649  7960 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 16:56:28.060  7649  7957 V BtOppService: Deleted complete outbound shares, number =  0
08-24 16:56:28.061  7649  7649 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-24 16:56:28.061  7649  7649 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-24 16:56:28.063  7649  7960 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 16:56:28.065  7649  7957 V BtOppService: Deleted complete inbound failed shares, number = 0
08-24 16:56:28.066  7649  7957 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-24 16:56:28.067  7649  7960 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@135dbe02 on behalf of 
08-24 16:56:28.069  7649  7957 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@65ab313 on behalf of 
08-24 16:56:28.069  7649  7649 V BluetoothOppNotification: new notify threadi!
08-24 16:56:28.070  7649  7649 V BluetoothOppNotification: send delay message
08-24 16:56:28.073  7649  7960 V BluetoothOppNotification: update too frequent, put in queue
08-24 16:56:28.073  7649  7649 V BtOppService: start RfcommListener
08-24 16:56:28.073  7649  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-24 16:56:28.074  7649  7960 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 16:56:28.075  7649  7960 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 16:56:28.078  7649  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ae03950 on behalf of 
08-24 16:56:28.079  7649  7961 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-24 16:56:28.081  7649  7649 V BtOppService: RfcommListener started
08-24 16:56:28.081  7649  7649 V BtOppService: ContentObserver received notification
08-24 16:56:28.081  7649  7649 V BtOppService: ContentObserver received notification
08-24 16:56:28.089  7649  7962 V BtOppRfcommListener: Starting RFCOMM listener....
08-24 16:56:28.092  1034  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:28.094  7649  7962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 16:56:28.096  7649  7962 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-24 16:56:28.096  7649  7962 V BtOppRfcommListener: Started RFCOMM listener....
08-24 16:56:28.096  7649  7962 I BtOppRfcommListener: Accept thread started.
08-24 16:56:28.097  7649  7962 V BtOppRfcommListener: Accepting connection...
08-24 16:56:28.102  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32450066
08-24 16:56:28.102  7649  7649 V BluetoothFtpService: Ftp Service onCreate
08-24 16:56:28.102  7649  7649 I BluetoothFtpService: Ftp Service onCreate
08-24 16:56:28.102  7649  7649 V BluetoothFtpService: Ftp Service onStartCommand
08-24 16:56:28.103  7649  7649 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:28.103  7649  7649 V BluetoothFtpService: Starting Listening on sockets
08-24 16:56:28.103  7649  7649 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 16:56:28.103  7649  7649 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 16:56:28.103  7649  7649 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 16:56:28.103  7649  7649 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:28.103  7649  7649 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-24 16:56:28.104  7649  7649 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-24 16:56:28.210  1034  1050 I art     : Explicit concurrent mark sweep GC freed 26018(1268KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.792ms total 134.651ms
08-24 16:56:28.211  7649  7960 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30edb84e on behalf of 
,08-24 16:56:28.213  7649  7960 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 16:56:28.213  7649  7960 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 16:56:28.214  7649  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-24 16:56:28.215  7649  7649 V BluetoothFtpService: Handler(): got msg=1
08-24 16:56:28.216  7649  7960 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1db36d6f on behalf of 
08-24 16:56:28.216  7649  7649 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-24 16:56:28.216  7649  7649 V BluetoothFtpService: Ftp Service initSocket
08-24 16:56:28.219  7649  7960 V BluetoothOppNotification: update too frequent, put in queue
08-24 16:56:28.219  7649  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23979a7c on behalf of 
08-24 16:56:28.221  7649  7960 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-24 16:56:28.221  7649  7961 V BluetoothOppNotification: outbound: succ-0  fail-0
08-24 16:56:28.223  1034  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 16:56:28.224  7649  7961 V BluetoothOppNotification: outbound notification was removed.
08-24 16:56:28.224  7649  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-24 16:56:28.226  7649  7649 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 16:56:28.227  7649  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1086bf05 on behalf of 
08-24 16:56:28.228  7649  7961 V BluetoothOppNotification: inbound: succ-0  fail-0
08-24 16:56:28.228  7649  7649 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-24 16:56:28.229  7649  7649 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-24 16:56:28.231  7649  7961 V BluetoothOppNotification: inbound notification was removed.
08-24 16:56:28.231  7649  7963 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-24 16:56:28.232  7649  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-24 16:56:28.234  7649  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a710b5a on behalf of 
08-24 16:56:28.247  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32450066
,08-24 16:56:28.247  7649  7649 V BluetoothSapService: Sap Service onCreate
08-24 16:56:28.248  7649  7649 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:56:28.249  7649  7649 V BluetoothSapService: state: 12
08-24 16:56:28.249  7649  7649 V BluetoothSapService: Starting SAP server process
08-24 16:56:28.250  7649  7649 V BluetoothSapService: SAP Service startRfcommListenerThread
08-24 16:56:28.245  7964  7964 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:28.251  7649  7965 V BluetoothSapService: Sap Service initRfcommSocket
08-24 16:56:28.252  1034  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:28.245  7964  7964 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:28.253  7649  7965 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 16:56:28.253  7649  7965 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-24 16:56:28.254  7649  7965 V BluetoothSapService: Succeed to create listening socket 
08-24 16:56:28.254  7649  7965 V BluetoothSapService: Accepting socket connection...
08-24 16:56:28.257  7964  7964 V BT_SAP  : Event pipe created
08-24 16:56:28.257  7964  7964 V BT_SAP  : create_server_socket qcom.sap.server
08-24 16:56:28.257  7964  7964 V BT_SAP  : created socket fd 6
08-24 16:56:28.702  6695  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:28.702  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:28.702  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:28.702  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:56:28.702  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:28.702  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:28.702  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:28.702  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 16:56:28.725  6695  6771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 16:56:28.729  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:28.730  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f84a5ab added. We now have 8 listener(s)
08-24 16:56:28.730  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:28.733  1034  1050 D WifiServiceImplEx: setWifiEnabled: false pid=6695, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 16:56:28.733  1034  1050 D WifiService: setWifiEnabled: false pid=6695, uid=10118
08-24 16:56:28.733  1034  1050 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 16:56:28.738  6695  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:56:28.742  1034  1603 D WifiServiceImplEx: setWifiEnabled: true pid=6695, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 16:56:28.743  1034  1603 D WifiService: setWifiEnabled: true pid=6695, uid=10118
08-24 16:56:28.743  1034  1603 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 16:56:28.764  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 16:56:28.764  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 16:56:28.764  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-24 16:56:28.765  1034  1540 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-24 16:56:28.765  1034  1540 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-24 16:56:28.768  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-24 16:56:28.768  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-24 16:56:28.768  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-24 16:56:28.768  1034  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-24 16:56:28.768  1034  1540 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-24 16:56:28.768  1034  1540 E WifiHW  : unknown target_country: EU , set to default
08-24 16:56:28.768  1034  1540 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-24 16:56:28.768  1034  1540 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-24 16:56:28.769  1034  1540 I WifiUtil: gEnableBmps=1
08-24 16:56:29.072  7649  7649 V BluetoothOppNotification: new notify threadi!
08-24 16:56:29.072  7649  7649 V BluetoothOppNotification: send delay message
,08-24 16:56:29.076  7649  7978 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-24 16:56:29.077  7649  7978 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ca48326 on behalf of 
08-24 16:56:29.079  7649  7978 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-24 16:56:29.080  7649  7978 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-24 16:56:29.081  7649  7978 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27659b67 on behalf of 
08-24 16:56:29.082  7649  7978 V BluetoothOppNotification: outbound: succ-0  fail-0
08-24 16:56:29.083  7649  7978 V BluetoothOppNotification: outbound notification was removed.
08-24 16:56:29.083  7649  7978 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-24 16:56:29.084  7649  7978 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1446bd14 on behalf of 
08-24 16:56:29.085  7649  7978 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-24 16:56:29.089  7649  7978 V BluetoothOppNotification: inbound notification was removed.
08-24 16:56:29.089  7649  7978 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-24 16:56:29.108  7649  7978 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@132c9bd on behalf of 
,08-24 16:56:29.331  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-24 16:56:29.339   312   908 D SoftapController: Softap fwReload - Ok
08-24 16:56:29.342  1034  1540 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (570ms)
08-24 16:56:29.352   312   908 D CommandListener: Setting iface cfg
08-24 16:56:29.352   312   908 D CommandListener: Trying to bring down wlan0
,08-24 16:56:29.369   312   908 D CommandListener: Clearing all IP addresses on wlan0
,08-24 16:56:29.371  1034  1096 D Tethering: InitialState.processMessage what=4
08-24 16:56:29.373  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 16:56:29.380  1034  1540 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-24 16:56:29.385  7986  7986 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 16:56:29.395  7986  7986 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:29.416  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 16:56:29.416  1034  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 16:56:29.416  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-24 16:56:29.427  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:29.441  1034  1540 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-24 16:56:29.442  1034  1540 D WifiMonitor: connecting to supplicant
,08-24 16:56:29.456  7986  7986 I wpa_supplicant: Successfully initialized wpa_supplicant
08-24 16:56:29.461  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:29.462  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-24 16:56:29.462  1974  1974 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-24 16:56:29.470  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 16:56:29.470  6810  6810 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 16:56:29.470  6810  6810 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 16:56:29.470  6810  6810 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 16:56:29.470  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 16:56:29.471  6810  6810 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 16:56:29.471  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-24 16:56:29.471  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 16:56:29.471  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 16:56:29.471  6810  6810 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 16:56:29.471  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-24 16:56:29.472  6810  6810 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-24 16:56:29.474  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 16:56:29.474  6810  6810 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 16:56:29.474  6810  6810 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 16:56:29.474  6810  6810 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 16:56:29.477  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 16:56:29.478  6810  6810 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 16:56:29.479  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-24 16:56:29.479  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 16:56:29.479  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 16:56:29.479  6810  6810 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 16:56:29.479  6810  6810 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-24 16:56:29.494  7986  7986 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-24 16:56:29.495  7986  7986 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-24 16:56:29.530  1034  1991 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8003 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-24 16:56:29.566  7986  7986 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-24 16:56:29.637  7986  7986 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-24 16:56:29.644  7986  7986 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-24 16:56:29.644  7986  7986 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-24 16:56:29.646  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-24 16:56:29.647  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-24 16:56:29.647  1034  8025 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-24 16:56:29.647  1034  8025 D WifiMonitor: Dropping event because (p2p0) is stopped
08-24 16:56:29.647  1034  8025 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-24 16:56:29.647  1034  8025 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-24 16:56:29.647  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-24 16:56:29.647  1034  8025 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-24 16:56:29.647  1034  8025 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-24 16:56:29.647  1034  1540 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-24 16:56:29.648  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:29.649  1034  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:29.649  1034  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:29.649  1034  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:29.650  1034  1540 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,08-24 16:56:29.650  1034  1540 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-24 16:56:29.651  1034  1540 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-24 16:56:29.651  1034  1540 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-24 16:56:29.651  1034  1540 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-24 16:56:29.685  1034  2038 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8026 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-24 16:56:29.688  1034  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 16:56:29.688  1034  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 16:56:29.688  1034  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 16:56:29.689  1034  1540 D WifiNative-wlan0: doBoolean: SET update_config 1
08-24 16:56:29.689  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:29.689  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:29.689  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:29.689  1034  1540 D WifiNative-wlan0: SET update_config 1: returned true
08-24 16:56:29.689  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:29.689  1034  1540 D WifiConfigStore: Loading config and enabling all networks 
08-24 16:56:29.689  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 16:56:29.689  1034  1540 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-24 16:56:29.690  1034  1540 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-24 16:56:29.693  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-24 16:56:29.693  1034  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-24 16:56:29.694  1974  1974 D WfdService: Waiting for WifiP2p enabling
08-24 16:56:29.694  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:29.696  1034  1540 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-24 16:56:29.706  1034  1540 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-24 16:56:29.706  1034  1540 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-24 16:56:29.707  1034  1540 D WifiStateMachine: enableVerboseLogging : level 2
08-24 16:56:29.707  1034  1540 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-24 16:56:29.710  8003  8022 W FormManager: Network not available. Please check & try again.
08-24 16:56:29.711   338   338 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 502us total 25.003ms
08-24 16:56:29.711  1034  1540 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-24 16:56:29.711  1034  1540 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-24 16:56:29.711  1034  1540 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-24 16:56:29.712  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:29.712  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:29.712  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:29.712  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:29.712  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:29.712  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:29.712  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:29.712  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:56:29.714  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:56:29.715  1034  1540 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-24 16:56:29.716  1034  1540 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-24 16:56:29.716  1034  1540 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-24 16:56:29.716  1034  1540 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-24 16:56:29.717  1034  1540 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-24 16:56:29.717  8003  8024 V FormManager: Network unavailable.
08-24 16:56:29.717  1034  1540 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-24 16:56:29.717  1034  1540 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-24 16:56:29.718  1034  1540 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
,08-24 16:56:29.719  8003  8024 V FormManager: Network unavailable.
08-24 16:56:29.719  1034  1540 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-24 16:56:29.721  1034  1540 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-24 16:56:29.723  7685  7685 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:29.723  1034  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 16:56:29.723  1034  1540 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-24 16:56:29.724  1034  1540 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-24 16:56:29.724  1034  1540 D WifiNative-HAL: Setting external_sim to 1
08-24 16:56:29.724  1034  1540 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-24 16:56:29.724  1034  1540 D WifiNative-wlan0: SET external_sim 1: returned true
08-24 16:56:29.724  1034  1540 I WifiNative-HAL: startHal
08-24 16:56:29.724  1034  1540 D wifi    : setting scan oui 0x95786f60
08-24 16:56:29.725  1034  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 16:56:29.725  1034  1540 I WifiNative-HAL: startHal
08-24 16:56:29.725  1034  1540 D wifi    : setting scan oui 0x95786f60
08-24 16:56:29.725  1034  1540 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-24 16:56:29.725  1034  1540 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-24 16:56:29.725  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-24 16:56:29.726  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-24 16:56:29.726  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-24 16:56:29.726  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-24 16:56:29.726  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 16:56:29.726  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 16:56:29.726  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-24 16:56:29.727  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-24 16:56:29.727  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-24 16:56:29.727  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 16:56:29.727  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-24 16:56:29.727  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-24 16:56:29.727  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-24 16:56:29.727  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 16:56:29.728  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 16:56:29.728  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-24 16:56:29.728  7986  7986 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-24 16:56:29.728  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-24 16:56:29.728  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 16:56:29.729  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-24 16:56:29.729  1034  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-24 16:56:29.730  1034  1540 E WifiNative: : [222,808,177 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-24 16:56:29.730  1034  1540 D WifiNative-wlan0: doBoolean: RECONNECT
,08-24 16:56:29.732  1034  1540 D WifiNative-wlan0: RECONNECT: returned true
08-24 16:56:29.732  1034  1540 D WifiNative-wlan0: doString: [STATUS]
08-24 16:56:29.732  1034  8025 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-24 16:56:29.733  1034  8025 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-24 16:56:29.733  1034  1540 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-24 16:56:29.733  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 16:56:29.733  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
08-24 16:56:29.734  1034  1538 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.735  1974  1974 D WfdsService: Supplicant Connection state is changed : true
08-24 16:56:29.735  1974  2298 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-24 16:56:29.735  1974  2298 D WfdsService: Set the WFDS Monitor: true
08-24 16:56:29.735  1974  2298 D WfdsMonitor: WfdsMonitorThread create
08-24 16:56:29.735  1974  2298 D WfdsMonitor: WFDS Monitor is created and started
08-24 16:56:29.735  1974  2298 D WfdsService: WiFi: Supplicant connection re-established
08-24 16:56:29.736   312   908 D CommandListener: Setting iface cfg
08-24 16:56:29.736   312   908 D CommandListener: Trying to bring up p2p0
08-24 16:56:29.736   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 2.743ms total 24.639ms
08-24 16:56:29.736  1034  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-24 16:56:29.736  1034  1538 D LGWifiP2pService: P2pEnablingState
08-24 16:56:29.737  1034  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.737  1034  1538 D LGWifiP2pService: P2p socket connection successful
08-24 16:56:29.737  1034  1538 D LGWifiP2pService: P2pEnabledState
08-24 16:56:29.737  1974  8044 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-24 16:56:29.737  1974  8044 E CtrlSupplicant: Succeed to open control connection
08-24 16:56:29.737  1974  8044 E CtrlSupplicant: Succeed to open monitor connection
08-24 16:56:29.738  1974  8044 D WfdsMonitor: Supplicant connection established
08-24 16:56:29.738  1974  2298 D WfdsService: Connected to the supplicant for wfds
08-24 16:56:29.739  1034  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-24 16:56:29.739  1034  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-24 16:56:29.740  1034  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-24 16:56:29.740  1034  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-24 16:56:29.741  1034  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-24 16:56:29.741  1034  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-24 16:56:29.741  1034  1538 D LGWifiP2pService: before postfix = G3
08-24 16:56:29.741  1034  1538 D WifiServerServiceExt: postfix byte check : 2
08-24 16:56:29.741  1034  1538 D LGWifiP2pService: after postfix = G3
08-24 16:56:29.741  1034  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-24 16:56:29.741  1034  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-24 16:56:29.741  1034  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-24 16:56:29.742  1034  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-24 16:56:29.742  1034  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-24 16:56:29.742  1034  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-24 16:56:29.742  1034  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
0,8-24 16:56:29.742  1034  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-24 16:56:29.742  1034  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-24 16:56:29.744  1034  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-24 16:56:29.744  1034  1540 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-24 16:56:29.744  1034  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-24 16:56:29.744  1034  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-24 16:56:29.744  1034  1540 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-24 16:56:29.744  1034  1540 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-24 16:56:29.744  1034  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
08-24 16:56:29.744  1034  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-24 16:56:29.745  1034  1540 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-24 16:56:29.745  1974  1974 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-24 16:56:29.745  1974  1974 D WfdsService: WifiP2pState is changed : true
08-24 16:56:29.745  1034  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-24 16:56:29.745  1974  1974 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-24 16:56:29.745  1034  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-24 16:56:29.745  1974  1974 D WfdsService: isConnected: false
08-24 16:56:29.745  1974  2298 D WfdsService: Receive the WFDS_ENABLE Method
08-24 16:56:29.746  1974  2298 D WfdsService: Set the WFDS Monitor: true
08-24 16:56:29.746  1974  2298 D WfdsService: Connected to the supplicant for wfds
08-24 16:56:29.746  1974  2298 D WfdsJNI : doCommand: WFDS_SET TRUE
08-24 16:56:29.746  7986  7986 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-24 16:56:29.746  1974  2298 D WfdsService: selectPreferredScanChannel [36]
08-24 16:56:29.746  1974  2298 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-24 16:56:29.746  1034  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-24 16:56:29.746  1034  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-24 16:56:29.749  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-24 16:56:29.749  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-24 16:56:29.749  1974  1974 I WfdStateTracker: handleP2pThisDeviceChanged
08-24 16:56:29.749  1034  1558 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.749  1974  1974 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-24 16:56:29.749  1034  1558 I WifiNative-HAL: startHal
08-24 16:56:29.749  1974  1974 D WfdsService: Update P2p Interface State: 3
08-24 16:56:29.750  1034  1540 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-24 16:56:29.750  1034  1540 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-24 16:56:29.750  1034  1540 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-24 16:56:29.750  1034  1540 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-24 16:56:29.751  1034  1559 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.752  1034  1049 I ActivityManager: Killing 7110:com.android.chrome/u0a57 (adj 15): empty #17
08-24 16:56:29.756   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 399us total 18.771ms
08-24 16:56:29.758  7986  7986 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-24 16:56:29.758  1034  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-24 16:56:29.758  1034  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-24 16:56:29.759  1034  1558 D wifi    : getting scan capabilities on interface[1] = 0x95786f60
08-24 16:56:29.759  1034  1540 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-24 16:56:29.759  1034  1558 D wifi    : failed to get capabilities : -3
08-24 16:56:29.759  1034  1558 E WifiScanningService: could not get scan capabilities
08-24 16:56:29.759  1034  1540 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-24 16:56:29.759  1034  1540 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-24 16:56:29.760  1034  1540 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-24 16:56:29.760  7986  7986 E wpa_supplicant: disconnect_rssi_lvl: -100
,08-24 16:56:29.760  1034  1540 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-24 16:56:29.761  1034  1540 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-24 16:56:29.761  1034  1540 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-24 16:56:29.761  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-24 16:56:29.762  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-24 16:56:29.762  7986  7986 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:29.763  7986  7986 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-24 16:56:29.763  7986  7986 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.763  1974  8044 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:29.764  7986  7986 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.764  1974  8044 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:29.766  1034  8025 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 16:56:29.766  1034  8025 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:29.766  1034  8025 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:29.766  1034  8025 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:29.766  1034  8025 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:29.767  1034  8025 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.767  1034  8025 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.767  1034  8025 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.767  1034  8025 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:29.767  1034  8025 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.767  1034  8025 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.767  1034  8025 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.767  1034  1540 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-24 16:56:29.767  1034  1540 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-24 16:56:29.768  1034  1540 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-24 16:56:29.768  1034  1540 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-24 16:56:29.768  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-24 16:56:29.768  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-24 16:56:29.769  7986  7986 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 16:56:29.769  1034  8025 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-24 16:56:29.769  1034  8025 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 16:56:29.769  1034  8025 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 16:56:29.769  1034  8025 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 16:56:29.769  1034  1540 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-24 16:56:29.769  1034  1540 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-24 16:56:29.770  1034  1540 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-24 16:56:29.770  1034  1540 D WifiNative-wlan0: doBoolean: SCAN
08-24 16:56:29.770  1034  1540 D WifiNative-wlan0: SCAN: ,returned false
08-24 16:56:29.771  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=222850  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-24 16:56:29.777  6695  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:56:29.777  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:29.777  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:29.777  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:29.777  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:29.777  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:56:29.777  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:56:29.777  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:56:29.778  8026  8026 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 16:56:29.778  6695  6771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:56:29.783  6695  6771 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-24 16:56:29.784  6695  6771 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-24 16:56:29.786  6695  6771 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8dd89b5 Bundle[{}]
08-24 16:56:29.787  6695  6771 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 16:56:29.787  6695  6771 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-24 16:56:29.787  6695  6771 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-24 16:56:29.788  6695  6771 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 16:56:29.789  6695  6771 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-24 16:56:29.790  6695  6771 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-24 16:56:29.795  6695  6771 I System.out: Running OutgoingSocketThread
,08-24 16:56:29.796  6695  8048 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 861)
08-24 16:56:29.797  6695  8048 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39459
08-24 16:56:29.797  6695  8048 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-24 16:56:29.810  1034  1941 W libprocessgroup: failed to open /acct/uid_10057/pid_7110/cgroup.procs: No such file or directory
,08-24 16:56:29.810  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-24 16:56:29.813  1034  1538 D LGWifiP2pService: InactiveState
08-24 16:56:29.813  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=222892  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 16:56:29.813  1034  1538 D LGWifiP2pService: InactiveState{ when=-68ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
,08-24 16:56:29.813  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-68ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.814  1034  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-24 16:56:29.814  1034  1540 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 16:56:29.815  1034  1540 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 16:56:29.815  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:29.815  1034  1540 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 16:56:29.815  1034  1540 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 16:56:29.816  1034  1540 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 16:56:29.816  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-24 16:56:29.817  7986  7986 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:29.818  1034  8025 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 16:56:29.818  1034  8025 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:29.818  1034  8025 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:29.818  1034  8025 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 16:56:29.818  1974  8044 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 16:56:29.818  7986  7986 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-24 16:56:29.818  7986  7986 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.819  1034  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-24 16:56:29.819  1034  1538 D LGWifiP2pService: InactiveState{ when=-52ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.819  1034  8025 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:29.819  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-52ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.819  1034  8025 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.819  1034  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.819  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:29.819  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.819  7986  7986 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.819  1034  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.819  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:29.819  1034  8025 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.819  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-24 16:56:29.819  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 16:56:29.819  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-24 16:56:29.819  1034  8025 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.819  1034  8025 D WifiMonitor: E,vent [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:29.819  1034  8025 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.820  1034  8025 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.820  1974  8044 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:29.820  1034  8025 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 16:56:29.820  1974  8044 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 16:56:29.820  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:29.820  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:29.820  1034  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.820  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.820  1034  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.820  1034  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.820  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.820  1034  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.821  1034  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.821  1034  1049 I ActivityManager: Killing 7131:com.lge.drmservice/u0a62 (adj 15): empty #17
08-24 16:56:29.821  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:29.822  1974  2298 W WfdsService: DefaultState - msg [9441285] is not handled
08-24 16:56:29.821  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.822  1034  1538 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:29.822  1034  1034 E WifiServerServiceExt: No p2p device connected
,08-24 16:56:29.869  1034  1577 W libprocessgroup: failed to open /acct/uid_10062/pid_7131/cgroup.procs: No such file or directory
,08-24 16:56:29.894  8026  8026 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 16:56:29.896  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-24 16:56:29.903  8003  8050 W FormManager: Network not available. Please check & try again.
08-24 16:56:29.903  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:29.926  8003  8051 V FormManager: Network unavailable.
,08-24 16:56:29.926  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 16:56:29.927  4300  4300 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 16:56:29.928  8003  8051 V FormManager: Network unavailable.
08-24 16:56:29.931  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 16:56:29.934  4300  4300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 16:56:29.943  4300  8052 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-24 16:56:29.946  4300  8053 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 16:56:29.947  4300  8053 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 16:56:30.000  1034  2038 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8054 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-24 16:56:30.133  8054  8054 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-24 16:56:30.134  8054  8054 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-24 16:56:30.143  8054  8054 V [BNRBootReceiver]: Boot Receiver Return
,08-24 16:56:30.143  8054  8054 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-24 16:56:30.222  1034  1991 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8075 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-24 16:56:30.223  1034  1991 I ActivityManager: Killing 7163:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-24 16:56:30.261  1034  8025 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-24 16:56:30.261  1034  8025 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-24 16:56:30.261  1034  8025 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-24 16:56:30.261  7986  7986 E wpa_supplicant: USIM:  scard_init function
08-24 16:56:30.261  1034  8025 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-24 16:56:30.261  1034  8025 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-24 16:56:30.261  7986  7986 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-24 16:56:30.263  1034  1540 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-24 16:56:30.264  1034  8025 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-24 16:56:30.264  1034  8025 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-24 16:56:30.264  1034  1540 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 16:56:30.265  1034  1540 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 16:56:30.265  1034  1540 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 16:56:30.265  1034  1540 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-24 16:56:30.277  1034  1967 W libprocessgroup: failed to open /acct/uid_10085/pid_7163/cgroup.procs: No such file or directory
,08-24 16:56:30.282  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=223360  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-24 16:56:30.289  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:30.289  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:30.290  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 16:56:30.291  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.291  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-24 16:56:30.291  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 16:56:30.293  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.293  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.293  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-24 16:56:30.294  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:30.294  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:30.295  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=223374  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-24 16:56:30.295  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:30.296  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 16:56:30.296  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-24 16:56:30.312  8075  8075 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-24 16:56:30.337  8075  8075 D PluginManager: init()
,08-24 16:56:30.379  7986  7986 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-24 16:56:30.383  1034  8025 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-24 16:56:30.384  1034  8025 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-24 16:56:30.385  1034  8025 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-24 16:56:30.385  1034  8025 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-24 16:56:30.385  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=223464  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-24 16:56:30.385  1034  8025 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 16:56:30.385  1034  8025 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 16:56:30.386  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=223464  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-24 16:56:30.386  1034  1540 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223465
08-24 16:56:30.387  1034  1540 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223465
08-24 16:56:30.387  1034  1540 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223466
08-24 16:56:30.388  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223466
08-24 16:56:30.388  1034  1540 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223467
08-24 16:56:30.389  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=223467  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-24 16:56:30.391  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:30.391  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:30.393  7986  7986 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-24 16:56:30.393  7986  7986 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 16:56:30.394  1034  8025 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 16:56:30.394  1034  8025 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 16:56:30.394  1034  8025 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-24 16:56:30.394  1034  8025 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 16:56:30.394  1034  8025 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 16:56:30.394  1034  8025 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-24 16:56:30.395  1034  8025 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 16:56:30.395  1034  8025 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 16:56:30.395  1034  8025 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 16:56:30.395  1034  8025 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 16:56:30.397  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.397  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.397  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-24 16:56:30.397  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-24 16:56:30.399  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=223477  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-24 16:56:30.400  1034  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=223478  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-24 16:56:30.400  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=223479  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-24 16:56:30.401  1034  1540 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=223480
08-24 16:56:30.402  1034  1540 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=223480
08-24 16:56:30.402  1034  1540 D WifiNative-wlan0: doString: [STATUS]
08-24 16:56:30.403  1034  8025 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 16:56:30.403  1034  8025 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 16:56:30.404  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:30.406  1034  1540 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-24 16:56:30.409  1034  1540 I WifiServiceExtension: setVHTCapabilityType  : false
08-24 16:56:30.411  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.411  1034  1034 W Settings: Sett,ing wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.411  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-24 16:56:30.411  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 16:56:30.411  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-24 16:56:30.419  1034  1540 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-24 16:56:30.419  1034  1540 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-24 16:56:30.425  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:30.425  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:30.426  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 16:56:30.433  1034  1540 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-24 16:56:30.433  1034  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 16:56:30.433  1034  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 16:56:30.434  1034  1546 D ConnectivityService: Got NetworkAgent Messenger
08-24 16:56:30.434  1034  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-24 16:56:30.434  1034  1546 D ConnectivityService: NetworkAgent connected
08-24 16:56:30.434  1034  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 16:56:30.434  1034  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 16:56:30.435  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.435  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.435  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-24 16:56:30.441  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.441  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.441  1034  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 16:56:30.441  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-24 16:56:30.441  1034  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 16:56:30.441  1034  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 16:56:30.442  1034  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 16:56:30.442  1034  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 16:56:30.445  1034  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 16:56:30.447   312   908 D CommandListener: Setting iface cfg
08-24 16:56:30.450  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:30.450  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-24 16:56:30.450  1034  1540 E WifiStateMachine: Start Dhcp Watchdog 3
08-24 16:56:30.451  1034  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=223530  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 16:56:30.451  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:30.452  1034  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=223530  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 16:56:30.452  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=223531  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 16:56:30.453  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:30.453  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:30.453  1034  8099 D DhcpStateMachine: StoppedState
08-24 16:56:30.453  1034  8099 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:30.454  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:30.454  1034  8099 D DhcpStateMachine: WaitBeforeStartState
08-24 16:56:30.455  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 16:56:30.456  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-24 16:56:30.456  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 16:56:30.456  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-24 16:56:30.457  1034  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=223536  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 16:56:30.458  1034  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=223537  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 16:56:30.459  1034  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=223537  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 16:56:30.459  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:30.460  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:30.460  1034  1540 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:30.460  1034  1540 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:30.461  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:30.461  1034  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 16:56:30.462  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13973] from screen [on:0 period:-1123192066] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-24 16:56:30.463  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1123192065] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-24 16:56:30.464  1034  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-24 16:56:30.470  1034  1546 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-24 16:56:30.470  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:30.471  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-24 16:56:30.471  1034  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:30.471  1034  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:30.472  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:30.472  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:30.472  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:30.473  1034  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-24 16:56:30.474  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 16:56:30.474  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-24 16:56:30.474  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=115,0,0
08-24 16:56:30.474  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=115,0,0
08-24 16:56:30.475  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-24 16:56:30.475  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-24 16:56:30.475  1034  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-24 16:56:30.475  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 0
08-24 16:56:30.476  1034  1540 D WifiNative-wlan0: SET ps 0: returned true
08-24 16:56:30.476  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-24 16:56:30.476  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-24 16:56:30.476  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-24 16:56:30.476  1034  1540 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-24 16:56:30.476  1034  1540 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 16:56:30.476  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3700ba8a target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:30.476  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3700ba8a target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:30.476  1034  1540 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-24 16:56:30.477  1034  8099 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:30.477  1034  8099 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-24 16:56:30.478   312   908 D CommandListener: Setting iface cfg
08-24 16:56:30.478   312   908 D CommandListener: Trying to bring up wlan0
08-24 16:56:30.479  1034  1540 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-24 16:56:30.479  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 16:56:30.479  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-24 16:56:30.480  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:30.480  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:30.481  1034  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:30.481  1034  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:30.482  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:30.482  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 16:56:30.482  1034  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-24 16:56:30.483  1034  1540 E WifiStateMachine:,  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-24 16:56:30.483  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-24 16:56:30.483  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 16:56:30.483  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:30.484  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:30.484  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-24 16:56:30.484  1034  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true,
08-24 16:56:30.484  1034  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-24 16:56:30.484  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-24 16:56:30.485  1034  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-24 16:56:30.485  1034  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 16:56:30.504  1034  1540 D WifiNative-wlan0: SET ps 1: returned true
,08-24 16:56:30.505  1034  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-24 16:56:30.506  1034  1540 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-24 16:56:30.506  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-24 16:56:30.506  1034  1540 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-24 16:56:30.507  1034  1546 D ConnectivityService: ignoring duplicate network state non-change
08-24 16:56:30.513  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:30.514  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:30.515  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 16:56:30.520  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.520  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.520  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-24 16:56:30.521  1034  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-24 16:56:30.523  1034  1546 D ConnectivityService: Adding iface wlan0 to network 102
08-24 16:56:30.524  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.524  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.524  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-24 16:56:30.527  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-24 16:56:30.529  1974  1974 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-24 16:56:30.533  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.533  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.533  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-24 16:56:30.536  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-24 16:56:30.539  1034  1540 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-24 16:56:30.540  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:30.540  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 16:56:30.541  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 16:56:30.541  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:56:30.542  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-24 16:56:30.542  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:30.546  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:30.546  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 16:56:30.546  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:30.549  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 16:56:30.550  1034  1546 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-24 16:56:30.550  1034  1546 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-24 16:56:30.550  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 16:56:30.550  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:30.551  1034  1546 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-24 16:56:30.552   312   908 E Netd    : netlink response contains error (File exists)
08-24 16:56:30.552  1034  1546 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-24 16:56:30.553  1034  1546 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-24 16:56:30.553  1034  1546 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-24 16:56:30.553  1034  1546 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-24 16:56:30.557  1034  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-24 16:56:30.557  1034  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-24 16:56:30.557  1034  1546 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-24 16:56:30.557  1034  8098 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:30.558  1034  8098 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-24 16:56:30.558  1034  8098 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 16:56:30.558  1034  8098 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-24 16:56:30.559  1034  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-24 16:56:30.559  1034  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 16:56:30.559  1034  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:30.559  1034  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 16:56:30.560  1034  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:30.560  1034  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-24 16:56:30.560  1034  1546 D ConnectivityService: currentScore = 0, newScore = 20
08-24 16:56:30.560  1034  1546 D ConnectivityService:    accepting network in place of null
08-24 16:56:30.560  1034  1546 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:30.560  1034  1540 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:30.560  1876  1876 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:30.560  1034  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 16:56:30.561  1876  1876 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 16:56:30.561   312  8103 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-24 16:56:30.561  1034  1546 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-24 16:56:30.561  1034  1546 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-24 16:56:30.561  1034  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 16:56:30.562  1034  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 16:56:30.562  1034  1034 D LocSvc_java: Sending msg:, 4 arg1:1 arg2:1
08-24 16:56:30.563  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 16:56:30.563  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 16:56:30.563  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 16:56:30.562  1034  1546 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-24 16:56:30.567  1034  1546 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-24 16:56:30.568  1034  1546 D ConnectivityService: validation of new default Network = false
08-24 16:56:30.568  1034  1546 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-24 16:56:30.568  1034  1546 D DSQN    : enableDataServiceNotify 
08-24 16:56:30.568  1034  1546 D DSQN    : start dsqn bin
,08-24 16:56:30.575  1034  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-24 16:56:30.575  1034  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:30.575  1034  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:30.575  1034  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:30.576  1605  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 16:56:30.565  8104  8104 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:30.565  8104  8104 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:30.581  1034  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-24 16:56:30.587  8104  8104 E DSQN    : DSQN ssw
,08-24 16:56:30.592  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 16:56:30.594  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:30.594  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:30.617   312  8103 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-24 16:56:30.653   312  8103 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-24 16:56:30.678  1034  8099 D DhcpStateMachine: DHCPV4 request on wlan0
,08-24 16:56:30.679  1034  8099 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-24 16:56:30.679  1034  8099 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-24 16:56:30.681   312   907 D LGDataListener: argv[0]=dsqncommand
08-24 16:56:30.681   312   907 D LGDataListener: argv[1]=wlan0
08-24 16:56:30.681   312   907 D LGDataListener: argv[2]=1
08-24 16:56:30.681   312   907 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-24 16:56:30.683  1034  1094 D DSQN    : DSQM DsqnNotification wlan0  1
08-24 16:56:30.683  1034  1094 D DSQN    : start to monitor internet connection
08-24 16:56:30.675  8110  8110 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:30.675  8110  8110 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 16:56:30.696  8110  8110 I dhcpcd  : version 5.5.6 starting
08-24 16:56:30.699  8110  8110 E dhcpcd  : get_duid: m
08-24 16:56:30.699  8110  8110 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-24 16:56:30.699  8110  8110 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-24 16:56:30.712  1034  8098 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 14:56:30 GMT], X-Android-Received-Millis=[1472050590711], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472050590680]}
08-24 16:56:30.712  1034  8098 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-24 16:56:30.712  1034  8098 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-24 16:56:30.712  1034  1546 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
,08-24 16:56:30.712  1034  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-24 16:56:30.713  1034  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 16:56:30.713  1034  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,08-24 16:56:30.713  1034  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 16:56:30.713  1034  1546 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-24 16:56:30.713  1034  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-24 16:56:30.714  1034  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:30.714  1034  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:30.714  1034  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:30.715  1034  1546 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:30.716  1605  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 16:56:30.717  1034  1540 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:30.717  1034  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 16:56:30.717  1876  1876 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:30.717  1034  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-24 16:56:30.718  1876  1876 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 16:56:30.730  1034  1395 V AlarmManager: RTC_WAKEUP set : Alarm{32b39d18 type 0 when 1472050585044 com.google.android.gms} when 1472050585044
08-24 16:56:30.730  1034  1395 V AlarmManager: ELAPSED_WAKEUP set : Alarm{28e76371 type 2 when 223808 android} when 223808
,08-24 16:56:30.740  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 16:56:30.741  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:30.742  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 16:56:30.784  8110  8110 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-24 16:56:30.784  8110  8110 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-24 16:56:30.784  8110  8110 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-24 16:56:30.784  8110  8110 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-24 16:56:30.784  8110  8110 D dhcpcd  : wlan0: sending REQUEST (xid 0x48a7d783), next in 3.23 seconds
,08-24 16:56:30.796  6695  6771 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 862)
08-24 16:56:30.797  6695  6771 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 862)
,08-24 16:56:30.801  6695  6771 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 867)
08-24 16:56:30.802  6695  6771 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-24 16:56:30.802  6695  6771 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 868)
08-24 16:56:30.805  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 16:56:30.805  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@336d408 added. We now have 2 listener(s)
08-24 16:56:30.805  1034  1603 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:30.808  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 16:56:30.808  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 16:56:30.808  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:56:30.808  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:30.808  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1922e7a1 added. We now have 9 listener(s)
08-24 16:56:30.808  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:30.809  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 16:56:30.811  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:56:30.819  6695  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:56:30.819  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:30.819  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:30.819  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:30.819  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:30.819  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:30.819  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:56:30.819  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:56:30.820  6695  6771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:30.820  6695  6771 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 16:56:30.820  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 16:56:30.820  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3865f187 added. We now have 3 listener(s)
08-24 16:56:30.821  1034  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:30.822  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:30.823  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 16:56:30.823  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 16:56:30.823  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:56:30.823  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:30.823  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@286928b4 added. We now have 10 listener(s)
08-24 16:56:30.824  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:30.824  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:30.824  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:30.824  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:30.824  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:30.824  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.824  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:56:30.824  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:56:30.824  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Con,nectionManager@336d408 removed from the list
08-24 16:56:30.824  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:30.824  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1922e7a1 removed from the list
,08-24 16:56:30.826  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:30.826  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:30.826  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.827  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.827  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.828  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:30.829  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:30.829  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:30.829  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1922e7a1 not in the list
08-24 16:56:30.829  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.829  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.829  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:30.829  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:30.829  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:30.829  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@286928b4 removed from the list
08-24 16:56:30.830  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:30.830  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.830  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.830  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:56:30.830  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3865f187 removed from the list
08-24 16:56:30.830  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 16:56:30.830  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e655cdd added. We now have 2 listener(s)
08-24 16:56:30.830  1034  1967 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:30.832  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 16:56:30.832  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 16:56:30.832  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:56:30.832  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:30.832  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.Disc,overyManager@13621052 added. We now have 9 listener(s)
08-24 16:56:30.832  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:30.832  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 16:56:30.834  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:30.836  8110  8110 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-24 16:56:30.838  6695  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:56:30.838  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:30.838  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:30.838  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:30.838  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:30.838  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:30.838  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:56:30.838  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:56:30.839  6695  6771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:30.839  6695  6771 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 16:56:30.840  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 16:56:30.840  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cca1c20 added. We now have 3 listener(s)
08-24 16:56:30.840  1034  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:30.842  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 16:56:30.842  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 16:56:30.842  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:56:30.842  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:30.842  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175fe9d9 added. We now have 10 listener(s)
08-24 16:56:30.842  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:30.842  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 16:56:30.842  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 16:56:30.842  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 16:56:30.842  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:30.842  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 16:56:30.843  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:30.844  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 16:56:30.845  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:30.845  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:30.848  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 16:56:30.848  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 16:56:30.850  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 16:56:30.850  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:56:30.852  6695  6771 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 16:56:30.852  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:30.852  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:30.854  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:30.854  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:30.854  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:30.854  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:30.854  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.854  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:56:30.854  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:56:30.854  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e655cdd removed from the list
08-24 16:56:30.854  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:30.854  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13621052 removed from the list
08-24 16:56:30.854  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:30.854  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.855  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.855  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.855  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:30.855  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:30.855  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:30.856  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13621052 not in the list
08-24 16:56:30.856  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.856  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.856  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:30.856  6695  6771 D BluetoothLeScanner: could not find callback wrapper
08-24 16:56:30.857  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stop,ped
08-24 16:56:30.857  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:30.857  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:30.857  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175fe9d9 removed from the list
08-24 16:56:30.857  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:30.857  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.857  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.857  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:56:30.857  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cca1c20 removed from the list
08-24 16:56:30.857  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 16:56:30.857  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c84da4c added. We now have 2 listener(s)
08-24 16:56:30.857  1034  1967 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:30.858  8110  8110 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-24 16:56:30.858  8110  8110 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-24 16:56:30.858  8110  8110 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-24 16:56:30.858  8110  8110 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-24 16:56:30.859  8110  8110 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-24 16:56:30.859  8110  8110 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-24 16:56:30.859  8110  8110 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-24 16:56:30.859  8110  8110 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-24 16:56:30.859  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-24 16:56:30.859  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 16:56:30.859  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:56:30.859  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:30.859  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31dc4a95 added. We now have 9 listener(s)
08-24 16:56:30.859  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:30.860  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 16:56:30.862  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:30.865  6695  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:56:30.865  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:30.865  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:30.865  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:30.865  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:30.865  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:30.865  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:56:30.865  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:56:30.866  6695  6771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:30.866  6695  6771 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 16:56:30.866  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 16:56:30.866  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@285e4f9b added. We now have 3 listener(s)
08-24 16:56:30.867  1034  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:30.868  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:30.870  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:30.872  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 16:56:30.872  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 16:56:30.872  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:56:30.872  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:30.872  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@194b4f38 added. We now have 10 listener(s)
08-24 16:56:30.872  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:30.872  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 16:56:30.873  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 16:56:30.873  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 16:56:30.873  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 16:56:30.873  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:30.873  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 16:56:30.879  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 16:56:30.879  1034  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:30.883  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 16:56:30.884  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 16:56:30.885  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 16:56:30.886  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:56:30.887  6695  6771 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 16:56:30.888  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:30.888  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:30.888  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 16:56:30.888  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:30.888  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.888  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:56:30.888  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 16:56:30.888  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c84da4c removed from the list
08-24 16:56:30.888  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:30.888  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31dc4a95 removed from the list
08-24 16:56:30.888  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:30.889  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.889  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.889  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.890  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:30.890  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:30.890  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:30.890  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31dc4a95 not in the list
08-24 16:56:30.890  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.890  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.891  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:30.892  6695  6771 D BluetoothLeScanner: could not find callback wrapper
08-24 16:56:30.892  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:56:30.892  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 16:56:30.892  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:30.892  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@194b4f38 removed from the list
08-24 16:56:30.892  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:30.892  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.892  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.892  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:56:30.892  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@285e4f9b removed from the list
08-24 16:56:30.893  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 16:56:30.893  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c84a77 added. We now have 2 listener(s)
08-24 16:56:30.893  1034  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:30.896  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 16:56:30.896  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 16:56:30.896  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:56:30.896  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:30.896  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0226e4 added. We now have 9 listener(s)
08-24 16:56:30.896  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:30.898  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 16:56:30.901  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:30.906  6695  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:56:30.906  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:30.906  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:30.906  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:30.906  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:30.906  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:30.906  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:56:30.906  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:56:30.908  6695  6771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:30.908  6695  6771 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 16:56:30.909  6695  6,771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 16:56:30.909  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@306b3202 added. We now have 3 listener(s)
08-24 16:56:30.909  1034  2056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 16:56:30.911  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:30.913  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:56:30.913  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 16:56:30.913  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 16:56:30.913  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:56:30.913  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:30.913  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@366d1713 added. We now have 10 listener(s)
08-24 16:56:30.913  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:30.913  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 16:56:30.913  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 16:56:30.913  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 16:56:30.913  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:30.913  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 16:56:30.914  8075  8075 W ExternalStrings: load override strings
08-24 16:56:30.914  8075  8075 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAn,dArgsCaller.run(ZygoteInit.java:909)
08-24 16:56:30.914  8075  8075 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 16:56:30.916  8075  8075 D StatusProvider: onCreate
08-24 16:56:30.916  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 16:56:30.916  1034  2088 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:30.920  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 16:56:30.921  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 16:56:30.923  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 16:56:30.924  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:56:30.926  6695  6771 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 16:56:30.928  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:30.929  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:30.929  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:30.929  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:30.929  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.929  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:56:30.929  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:56:30.929  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c84a77 removed from the list
08-24 16:56:30.929  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:30.929  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0226e4 removed from the list
08-24 16:56:30.929  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:30.929  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.934  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.934  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.934  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:30.934  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:30.934  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:30.934  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0226e4 not in the list
08-24 16:56:30.935  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.935  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:56:30.938  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:30.944  6695  6771 D BluetoothLeScanner: could not find callback wrapper
08-24 16:56:30.944  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:56:30.944  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:30.944  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:30.944  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@366d1713 removed from the list
08-24 16:56:30.944  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:30.944  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.944  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.945  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:56:30.945  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@306b3202 removed from the list
08-24 16:56:30.945  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 16:56:30.945  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e6c4e added. We now have 2 listener(s)
08-24 16:56:30.945  1034  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 16:56:30.948  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 16:56:30.948  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 16:56:30.948  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:56:30.948  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:30.949  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@688116f added. We now have 9 listener(s)
08-24 16:56:30.949  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:30.949  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 16:56:30.952  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:56:30.954  6695  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:56:30.954  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:56:30.954  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:56:30.954  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:56:30.954  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:56:30.954  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:30.954  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:56:30.954  6695  6771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:56:30.956  6695  6771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:56:30.956  6695  6771 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 16:56:30.956  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 16:56:30.956  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2660305 added. We now have 3 listener(s)
08-24 16:56:30.957  1034  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:56:30.959  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:56:30.960  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:56:30.961  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 16:56:30.961  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 16:56:30.961  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:56:30.961  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:56:30.961  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3538ff5a added. We now have 10 listener(s)
08-24 16:56:30.961  6695  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:56:30.961  6695  6771 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:56:30.962  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:30.962  6695  6771 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:56:30.962  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:30.962  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.962  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:56:30.962  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:56:30.962  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e6c4e removed from the list
08-24 16:56:30.962  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:30.962  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@688116f removed from the list
08-24 16:56:30.962  6695  6771 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:56:30.962  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.962  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.962  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.963  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:30.963  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:30.963  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:30.963  6695  6771 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@688116f not in the list
08-24 16:56:30.963  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.963  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.963  6695  6771 I org.thaliproject,.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:56:30.963  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:56:30.964  6695  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:56:30.964  6695  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3538ff5a removed from the list
08-24 16:56:30.964  6695  6771 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:56:30.964  6695  6771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:56:30.964  6695  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:56:30.964  6695  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:56:30.964  6695  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2660305 removed from the list
08-24 16:56:30.964  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-24 16:56:30.964  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-24 16:56:30.965  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-24 16:56:30.965  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 16:56:30.965  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-24 16:56:30.965  6695  6771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 16:56:30.973  6695  8128 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 875, name: My test thread name)
08-24 16:56:30.973  6695  8128 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 875, thread name: My test thread name)
08-24 16:56:30.973  6695  8128 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 875, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-24 16:56:30.975  6695  8129 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 877, name: My test thread name)
08-24 16:56:30.975  6695  8129 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 877, thread name: My test thread name)
08-24 16:56:30.975  6695  8129 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 877, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-24 16:56:30.980  6695  6771 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-24 16:56:30.980  6695  6771 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-24 16:56:30.980  6695  6771 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-24 16:56:30.980  6695  6771 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-24 16:56:30.980  6695  6771 D com.test.thalitest.ThaliTestRunner: Total duration: 22752 ms
08-24 16:56:30.981  6695  6771 I jxcore-log: Total number of executed tests:  80
08-24 16:56:30.981  6695  6771 I jxcore-log: 
08-24 16:56:30.982  6695  6771 I jxcore-log: Number of passed tests:  80
08-24 16:56:30.982  6695  6771 I jxcore-log: 
08-24 16:56:30.982  6695  6771 I jxcore-log: Number of failed tests:  0
08-24 16:56:30.982  6695  6771 I jxcore-log: 
08-24 16:56:30.982  6695  6771 I jxcore-log: Number of ignored tests:  0
08-24 16:56:30.982  6695  6771 I jxcore-log: 
08-24 16:56:30.982  6695  6771 I jxcore-log: Total duration:  22752
08-24 16:56:30.982  6695  6771 I jxcore-log: 
08-24 16:56:30.983  6695  6771 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-24 16:56:30.983  6695  6771 I jxcore-log: 
08-24 16:56:30.983  8075  8075 V Signer  : override build config not found
08-24 16:56:30.983  8075  8075 D Signer  : value of property debug is false
,08-24 16:56:30.989  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:56:30.989  6695  6771 I jxcore-log: 
08-24 16:56:30.991  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:56:30.991  6695  6771 I jxcore-log: 
08-24 16:56:30.992  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:56:30.992  6695  6771 I jxcore-log: 
08-24 16:56:30.993  6695  6695 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-24 16:56:30.993  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:56:30.993  6695  6771 I jxcore-log: 
08-24 16:56:30.994  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:56:30.994  6695  6771 I jxcore-log: 
08-24 16:56:30.995  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:56:30.995  6695  6771 I jxcore-log: 
,08-24 16:56:30.997  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 16:56:30.997  6695  6771 I jxcore-log: 
08-24 16:56:30.999  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 16:56:30.999  6695  6771 I jxcore-log: 
08-24 16:56:30.999  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 16:56:30.999  6695  6771 I jxcore-log: 
08-24 16:56:31.000  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 16:56:31.000  6695  6771 I jxcore-log: 
08-24 16:56:31.001  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 16:56:31.001  6695  6771 I jxcore-log: 
08-24 16:56:31.002  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 16:56:31.002  6695  6771 I jxcore-log: 
08-24 16:56:31.002  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 16:56:31.002  6695  6771 I jxcore-log: 
08-24 16:56:31.003  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 16:56:31.003  6695  6771 I jxcore-log: 
08-24 16:56:31.003  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 16:56:31.003  6695  6771 I jxcore-log: 
08-24 16:56:31.004  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 16:56:31.004  6695  6771 I jxcore-log: 
08-24 16:56:31.005  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 16:56:31.005  6695  6771 I jxcore-log: 
08-24 16:56:31.005  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 16:56:31.005  6695  6771 I jxcore-log: 
08-24 16:56:31.006  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 16:56:31.006  6695  6771 I jxcore-log: 
08-24 16:56:31.006  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 16:56:31.006  6695  6771 I jxcore-log: 
08-24 16:56:31.007  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 16:56:31.007  6695  6771 I jxcore-log: 
08-24 16:56:31.007  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 16:56:31.007  6695  6771 I jxcore-log: 
08-24 16:56:31.008  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 16:56:31.008  6695  6771 I jxcore-log: 
08-24 16:56:31.009  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:56:31.009  6695  6771 I ,jxcore-log: 
08-24 16:56:31.009  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:56:31.009  6695  6771 I jxcore-log: 
08-24 16:56:31.010  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:56:31.010  6695  6771 I jxcore-log: 
08-24 16:56:31.010  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:56:31.010  6695  6771 I jxcore-log: 
08-24 16:56:31.011  6695  6771 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:56:31.011  6695  6771 I jxcore-log: 
08-24 16:56:31.018  8075  8075 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-24 16:56:31.018  8075  8075 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-24 16:56:31.018  8075  8075 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-24 16:56:31.018  8075  8075 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-24 16:56:31.018  8075  8075 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-24 16:56:31.019  8075  8075 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-24 16:56:31.019  8075  8075 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-24 16:56:31.019  8075  8075 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-24 16:56:31.019  8075  8075 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-24 16:56:31.019  8075  8075 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-24 16:56:31.019  8075  8075 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-24 16:56:31.020  8075  8075 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-24 16:56:31.020  8075  8075 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-24 16:56:31.028  8075  8075 V LGMDMManager: Create singleton instance
08-24 16:56:31.069  8075  8075 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-24 16:56:31.082  1034  8099 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-24 16:56:31.084  1034  8099 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-24 16:56:31.084  1034  8099 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-24 16:56:31.084  1034  8099 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-24 16:56:31.084  1034  8099 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-24 16:56:31.084  1034  8099 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 16:56:31.084  1034  8099 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-24 16:56:31.084  1034  8099 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-24 16:56:31.085  1034  8099 D DhcpStateMachine: RunningState
08-24 16:56:31.104  8075  8075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 16:56:31.106  8075  8143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 16:56:31.112  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 16:56:31.117  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 16:56:31.159  1034  1992 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8146 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-24 16:56:31.159  1034  1992 I ActivityManager: Killing 7194:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-24 16:56:31.209  8075  8142 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-24 16:56:31.262  8139  8139 D AndroidRuntime: 
08-24 16:56:31.262  8139  8139 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-24 16:56:31.264  8139  8139 D AndroidRuntime: CheckJNI is OFF
,08-24 16:56:31.440  1034  1991 W libprocessgroup: failed to open /acct/uid_10093/pid_7194/cgroup.procs: No such file or directory
,08-24 16:56:31.450  8139  8139 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 16:56:31.470  8146  8146 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 16:56:31.473  1034  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-24 16:56:31.473  1034  1092 I ActivityManager: Killing 6695:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-24 16:56:31.514  1034  2033 I WindowState: WIN DEATH: Window{195c386e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 16:56:31.516  1034  1545 D WifiService: Client connection lost with reason: 4
08-24 16:56:31.523  1034  2033 D InputDispatcher: Window went away: Window{195c386e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 16:56:31.579  1034  1540 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 16:56:31.580  1034  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-24 16:56:31.580  1034  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 16:56:31.581  1034  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 16:56:31.581  1034  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 16:56:31.581  1034  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 16:56:31.583  1034  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-24 16:56:31.583  1034  1546 D ConnectivityService: identical MTU - not setting
08-24 16:56:31.583  1034  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-24 16:56:31.583  1034  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-24 16:56:31.583  1034  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 16:56:31.583  1034  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:31.584  1034  1546 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 16:56:31.584  1605  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-24 16:56:31.591  1034  1092 I ActivityManager:   Force finishing activity ActivityRecord{2914f94b u0 com.test.thalitest/.MainActivity t6}
,08-24 16:56:31.613   334   349 E GBMv2   : DFP En is all cleared set to be enabled
,08-24 16:56:31.617  1034  1941 W ActivityManager: Spurious death for ProcessRecord{3b438778 6695:com.test.thalitest/u0a118}, curProc for 6695: null
08-24 16:56:31.623  8146  8146 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-24 16:56:31.627  1034  1113 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-24 16:56:31.629  1034  1113 I ActivityManager:   Force finishing activity ActivityRecord{2914f94b u0 com.test.thalitest/.MainActivity t6 f}
08-24 16:56:31.629  1034  1113 W ActivityManager: Duplicate finish request for ActivityRecord{2914f94b u0 com.test.thalitest/.MainActivity t6 f}
,08-24 16:56:31.649  1974  1990 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-24 16:56:31.649  2091  2091 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-24 16:56:31.650  1974  1990 D SplitWindowPolicy: topRunningActivity=ActivityInfo{46f2336 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-24 16:56:31.651  2091  2091 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-24 16:56:31.653  1974  1989 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-24 16:56:31.653  1974  1989 D SplitWindowPolicy: topRunningActivity=ActivityInfo{31d0a237 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-24 16:56:31.654  2091  2091 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-24 16:56:31.654  2091  2176 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-24 16:56:31.661  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-24 16:56:31.669  1034  1464 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-24 16:56:31.675  2039  2039 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-24 16:56:31.676  3817  3817 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-24 16:56:31.676  2468  2619 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-24 16:56:31.678  7649  7649 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-24 16:56:31.678  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-24 16:56:31.705  4458  4458 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-24 16:56:31.705  4458  4458 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-24 16:56:31.705  4458  4458 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-24 16:56:31.705  4458  4458 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-24 16:56:31.705  4458  4458 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 16:56:31.705  4458  4458 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 16:56:31.705  4458  4458 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 16:56:31.705  4458  4458 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 16:56:31.705  4458  4458 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:56:31.705  4458  4458 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 16:56:31.705  4458  4458 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 16:56:31.705  4458  4458 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-24 16:56:31.736  1034  1967 V SIM_STK : Menu title from STK is T-Mobile
,08-24 16:56:31.739  2091  2091 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-24 16:56:31.741  1928  1928 D ActionManagerService: notifyUserLog: 1000003
08-24 16:56:31.742  3817  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-24 16:56:31.743  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-24 16:56:31.744  2091  2091 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-24 16:56:31.745  2091  2091 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-24 16:56:31.746  2091  2091 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-24 16:56:31.752  2091  2091 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-24 16:56:31.753  1605  1653 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-24 16:56:31.753  1605  1653 D KeyguardModel: createShortcutInfo...
08-24 16:56:31.753  1928  1928 D ActionManagerService: notifyUserLog: 1000004
08-24 16:56:31.753  3817  4481 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 16:56:31.753  3817  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-24 16:56:31.756  1605  1653 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-24 16:56:31.756  1605  1653 D KeyguardModel: createShortcutInfo...
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , create_time: 1430832262123
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , expire_time: 0
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , display: false
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , animation: false }
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , create_time: 1430832262287
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , expire_time: 0
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , display: false
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , animation: false }
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , create_time: 1471602816196
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , expire_time: 0
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , display: false
08-24 16:56:31.756  2091  2091 I GBoardWebViewUtils: , animation: false }
08-24 16:56:31.760  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-24 16:56:31.760  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-24 16:56:31.762  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-24 16:56:31.763  1605  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 16:56:31.763  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-24 16:56:31.764  1605  1653 W ResourcesManager: Asset path '/system/framew,ork/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 16:56:31.768  2091  8190 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-24 16:56:31.769  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 16:56:31.769  1605  1653 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-24 16:56:31.783  2091  2091 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 16:56:31.784  2091  2091 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-24 16:56:31.784  1605  1653 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-24 16:56:31.784  1605  1653 D KeyguardModel: createShortcutInfo...
08-24 16:56:31.789  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-24 16:56:31.789  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 16:56:31.790  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 16:56:31.790  1605  1653 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-24 16:56:31.791  1893  1893 D SplitUIManager: split_name #11 / not available #0
08-24 16:56:31.791  1893  1893 D SplitUIService: removed split : 
08-24 16:56:31.793  1605  1653 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 16:56:31.793  1605  1653 D KeyguardModel: createShortcutInfo...
08-24 16:56:31.795  1034  2038 V SIM_STK : Menu title from STK is T-Mobile
08-24 16:56:31.795  1034  2038 V SIM_STK : Menu title from STK is T-Mobile
08-24 16:56:31.798  1605  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 16:56:31.798  1605  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-24 16:56:31.798  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-24 16:56:31.798  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 16:56:31.801  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 16:56:31.801  1605  1653 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-24 16:56:31.812  8146  8146 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-24 16:56:31.812  8146  8146 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-24 16:56:31.812  8146  8146 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-24 16:56:31.812  8146  8146 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-24 16:56:31.813  8146  8146 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-24 16:56:31.814  8146  8146 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-24 16:56:31.819  4583  4583 I art     : Explicit concurrent mark sweep GC freed 8198(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 441us total 179.085ms
,08-24 16:56:31.829  1034  1034 D administrator: Handling package changes for user 0
08-24 16:56:31.841  8075  8142 D LgDataFeature: LgDataFeature() Constructor: none
08-24 16:56:31.841  8075  8142 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 16:56:31.845  1605  1653 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 16:56:31.845  1605  1653 D KeyguardModel: createShortcutInfo...
,08-24 16:56:31.861  1893  1893 D SplitUIManager: split_name #11 / not available #0
08-24 16:56:31.861  1893  1893 I SplitUIService: split app #11
08-24 16:56:31.878  8146  8146 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-24 16:56:31.880  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-24 16:56:31.880  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-24 16:56:31.881  2091  2091 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-24 16:56:31.898  1034  1049 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-24 16:56:31.899  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-24 16:56:31.899  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-24 16:56:31.899  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-24 16:56:31.899  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-24 16:56:31.899  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-24 16:56:31.899  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 16:56:31.899  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-24 16:56:31.899  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-24 16:56:31.899  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-24 16:56:31.899  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 16:56:31.899  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-24 16:56:31.901  1034  2010 V SIM_STK : Menu title from STK is T-Mobile
08-24 16:56:31.911  1034  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-24 16:56:31.915  1605  1653 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-24 16:56:31.915  1605  1653 D KeyguardModel: createShortcutInfo...
08-24 16:56:31.917  1605  1653 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-24 16:56:31.917  1605  1653 D KeyguardModel: createShortcutInfo...
,08-24 16:56:31.921  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 16:56:31.921  1605  1653 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-24 16:56:31.923  8146  8146 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:31.924  1605  1653 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-24 16:56:31.924  1605  1653 D KeyguardModel: createShortcutInfo...
08-24 16:56:31.925  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 16:56:31.925  1605  1653 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-24 16:56:31.926  1605  1653 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 16:56:31.926  1605  1653 D KeyguardModel: createShortcutInfo...
08-24 16:56:31.926  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 16:56:31.927  1605  1653 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-24 16:56:31.927  1605  1653 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 16:56:31.927  1605  1653 D KeyguardModel: createShortcutInfo...
08-24 16:56:31.928  8146  8146 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:31.949  2091  2091 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-24 16:56:31.952  2091  2091 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 16:56:31.954  2091  2091 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-24 16:56:31.955  2091  2091 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-24 16:56:31.956  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-24 16:56:31.956  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 16:56:31.956  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-24 16:56:31.956  2091  2091 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-24 16:56:31.958  2091  2091 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-24 16:56:31.959  1034  1579 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-24 16:56:31.967  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-24 16:56:31.967  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-24 16:56:31.980  8146  8146 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 16:56:31.981  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-24 16:56:31.983  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1bce7946 u0 com.lge.launcher2/.Launcher t5} time:225075
,08-24 16:56:31.985  6810  6810 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-24 16:56:31.987  8146  8146 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-24 16:56:31.987  8075  8075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:31.988  8075  8143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 16:56:31.990  2091  2091 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-24 16:56:31.991  2091  2091 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 16:56:31.993  8146  8146 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-24 16:56:31.993  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 16:56:31.999  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 16:56:32.004  2091  2091 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-24 16:56:32.004  2091  2091 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-24 16:56:32.005  2091  2091 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 16:56:32.005  2091  2294 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-24 16:56:32.006  2091  2294 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-24 16:56:32.013  2091  2091 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-24 16:56:32.014  2640  2640 D [Concierge]Service: onStartCommand(). Type : 8
08-24 16:56:32.014  2640  2640 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-24 16:56:32.016  2640  2640 D [Concierge]Service: Update widget ID : 11
,08-24 16:56:32.017  2091  2091 D [Concierge]WidgetView: change position of spinner
08-24 16:56:32.019  2091  2091 I [Concierge]WidgetView: initWebView(). Time : 1472050592019
08-24 16:56:32.019  2640  2640 D [Concierge]Service: onStartCommand(). Type : 0
08-24 16:56:32.023  8146  8146 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:32.023  8146  8146 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:32.026  8146  8146 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-24 16:56:32.030  8075  8142 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-24 16:56:32.032  8075  8075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:32.032  8075  8143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 16:56:32.036  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:32.046  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:32.047  2091  2091 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 36763790
08-24 16:56:32.048  2091  2091 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-24 16:56:32.048  2091  2091 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-24 16:56:32.049  8146  8146 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:32.049  8146  8146 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:32.050  8146  8146 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 16:56:32.050  2091  2091 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@27c98e0e
08-24 16:56:32.051  2091  2091 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-24 16:56:32.052  2091  2091 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-24 16:56:32.052  2091  2091 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 16:56:32.052  8075  8075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:32.052  8075  8143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 16:56:32.056  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 16:56:32.059  2091  2091 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-24 16:56:32.060  2091  2091 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
,08-24 16:56:32.061  2091  2091 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-24 16:56:32.061  2091  2091 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472050395472, New one : 1472050592019
08-24 16:56:32.061  2091  2091 D [Concierge]WidgetView: Unregister all receivers
08-24 16:56:32.061  2091  2091 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-24 16:56:32.062  2091  2091 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 16:56:32.063  2091  2091 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-24 16:56:32.064  2091  2091 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-24 16:56:32.066  2091  2091 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-24 16:56:32.067  2091  2091 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-24 16:56:32.067  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:32.067  8075  8142 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-24 16:56:32.068  2091  2091 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-24 16:56:32.070  2091  2091 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 16:56:32.070  2091  2091 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 16:56:32.074  8146  8146 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:32.074  8146  8146 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:32.074  8146  8146 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-24 16:56:32.077  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 16:56:32.077  6810  6810 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 16:56:32.077  6810  6810 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 16:56:32.077  6810  6810 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 16:56:32.077  8075  8142 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-24 16:56:32.077  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 16:56:32.078  6810  6810 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 16:56:32.078  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-24 16:56:32.078  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 16:56:32.078  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 16:56:32.078  6810  6810 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 16:56:32.078  6810  6810 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-24 16:56:32.078  6810  6810 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-24 16:56:32.078  8075  8142 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-24 16:56:32.079  8075  8142 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-24 16:56:32.079  8075  8142 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-24 16:56:32.079  8075  8142 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-24 16:56:32.080  8075  8075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:32.080  8075  8143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 16:56:32.085  8075  8142 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-24 16:56:32.085  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:32.090  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:32.090  8075  8142 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-24 16:56:32.097  8146  8146 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:32.097  8146  8146 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:32.097  8146  8146 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 16:56:32.100  8075  8143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 16:56:32.100  8075  8075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 16:56:32.107  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 16:56:32.111  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:32.115  8146  8146 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:32.115  8146  8146 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:32.115  8146  8146 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 16:56:32.118  8075  8075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:32.118  2091  2091 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-24 16:56:32.119  8075  8143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-24 16:56:32.126  2091  2091 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-24 16:56:32.126  2091  2091 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-24 16:56:32.128  2091  2091 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 16:56:32.131  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:32.138  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:32.141  8146  8146 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:32.142  8146  8146 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:32.143  8146  8146 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 16:56:32.148  8075  8143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 16:56:32.150  8075  8075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:32.151  2091  2091 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ec7d37b time:225243
,08-24 16:56:32.158  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 16:56:32.161  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:32.164  1034  1113 I art     : Explicit concurrent mark sweep GC freed 84173(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.969ms total 273.537ms
,08-24 16:56:32.165  8146  8146 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:32.166  8146  8146 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:32.169  8146  8146 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 16:56:32.171  8075  8075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:32.173  8075  8143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 16:56:32.208  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 16:56:32.208  8139  8139 D AndroidRuntime: Shutting down VM
,08-24 16:56:32.213  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:32.217  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 16:56:32.219  8146  8146 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:32.220  8146  8146 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 16:56:32.221  8146  8146 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 16:56:32.223  8075  8075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 16:56:32.223  8075  8143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 16:56:32.226  8026  8026 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-24 16:56:32.227  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-24 16:56:32.228  8026  8026 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-24 16:56:32.230  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 16:56:32.232  2091  2091 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-24 16:56:32.234  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:32.238  8146  8146 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:32.238  8146  8146 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:32.239  8146  8146 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-24 16:56:32.239  8146  8146 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-24 16:56:32.239  8146  8146 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-24 16:56:32.242  8075  8075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 16:56:32.259  8026  8026 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-24 16:56:32.259  8026  8026 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-24 16:56:32.261  6810  6810 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 16:56:32.265  6810  6810 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 16:56:32.269  8146  8146 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 16:56:32.270  8146  8146 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 16:56:32.270  8146  8146 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-24 16:56:32.271  8146  8146 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-24 16:56:32.271  8146  8146 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-24 16:56:32.280  8146  8146 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-24 16:56:32.281  8146  8146 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9837
,08-24 16:56:32.283  8075  8075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 16:56:32.286  8075  8075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-24 16:56:32.286  1840  8206 I CheckinService: active receiver: enabled
,08-24 16:56:32.311  1840  8206 I CheckinService: Preparing to send checkin request
08-24 16:56:32.311  1840  8206 I EventLogService: Accumulating logs since 1472050573645
08-24 16:56:32.312  1840  1840 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-24 16:56:32.316  2209  2209 I ConfigService: onCreate
08-24 16:56:32.317  2209  2209 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-24 16:56:32.319  1840  1840 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-24 16:56:32.323  2209  2209 I ConfigService: onBind returning update interface
,08-24 16:56:32.324  2209  2209 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-24 16:56:32.324  2209  2209 I ConfigService: onBind returning config service
08-24 16:56:32.331  2091  2091 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-24 16:56:32.340  2209  2209 I ConfigService: onDestroy
,08-24 16:56:32.342  1840  8209 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-24 16:56:32.346  1840  8206 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-24 16:56:32.366  5873  8212 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-24 16:56:32.381  1840  8216 I PeopleContactsSync: CP2 sync disabled
,08-24 16:56:32.387  1840  4731 I Icing   : doRemovePackageData com.test.thalitest
08-24 16:56:32.394  2091  2954 I GBoardtInterface: onReloaded()
08-24 16:56:32.395  1840  8215 W GmsApplication: Using Auth Proxy for data requests.
,08-24 16:56:32.397  2091  2091 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-24 16:56:32.398  3817  4481 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 16:56:32.403  3817  3832 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 16:56:32.405  1840  8215 W GmsApplication: Using Auth Proxy for data requests.
08-24 16:56:32.412  1928  1928 D ActionManagerService: notifyUserLog: 1000001
,08-24 16:56:32.415  3817  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-24 16:56:32.415  3817  4489 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-24 16:56:32.419  1928  1928 D ActionManagerService: notifyUserLog: 1000001
08-24 16:56:32.420  3817  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-24 16:56:32.420  3817  4489 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-24 16:56:32.420  3817  4489 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-24 16:56:32.420  3817  4489 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-24 16:56:32.422  3817  4481 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 16:56:32.433  2209  2231 I art     : Explicit concurrent mark sweep GC freed 6205(373KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 789us total 27.356ms
,08-24 16:56:32.456  1034  1113 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8218 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-24 16:56:32.457  2091  2091 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-24 16:56:32.457  2091  2091 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-24 16:56:32.460  2091  2091 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-24 16:56:32.460  2091  2091 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-24 16:56:32.463  2091  2091 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-24 16:56:32.463  2091  2091 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-24 16:56:32.471  7003  7003 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-24 16:56:32.483  2268  8237 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-24 16:56:32.517  1034  2038 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8238 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-24 16:56:32.550  1840  8211 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-24 16:56:32.550  1840  8211 E DriveAsyncService: disk I/O error (code 3850)
08-24 16:56:32.550  1840  8211 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 16:56:32.550  1840  8211 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-24 16:56:32.550  1840  8211 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-24 16:56:32.550  1840  8211 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-24 16:56:32.550  1840  8211 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-24 16:56:32.550  1840  8211 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-24 16:56:32.550  1840  8211 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-24 16:56:32.550  1840  8211 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
08-24 16:56:32.550  1840  8211 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
08-24 16:56:32.550  1840  8211 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
08-24 16:56:32.550  1840  8211 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
08-24 16:56:32.550  1840  8211 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-24 16:56:32.550  1840  8211 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:56:32.550  1840  8211 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
08-24 16:56:32.550  1840  8211 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 16:56:32.569  8238  8238 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 16:56:32.569  8238  8238 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-24 16:56:32.570  8238  8238 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 16:56:32.570  8238  8238 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 16:56:32.607  8238  8238 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 16:56:32.607  8238  8238 W Sy,stem.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 16:56:32.607  8238  8238 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)

```
