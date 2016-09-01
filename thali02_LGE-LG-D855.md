#### Test 8359140042466a2_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-01 11:00:43.949  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-01 11:00:43.949  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-01 11:00:43.959  1604  1604 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
--------- beginning of system
09-01 11:00:43.966  1035  1492 D WifiController: battery changed pluggedType: 2
09-01 11:00:43.968  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:00:43.968  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:00:43.971  1941  2076 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-01 11:00:43.971  1941  2076 D LEDHandler: Battery Level Remaining: 100%
09-01 11:00:43.971  1941  2076 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
09-01 11:00:43.973  4407  4510 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-01 11:00:43.973  1604  1604 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-01 11:00:43.975  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-01 11:00:43.979  5727  5727 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-01 11:00:44.267  6916  6916 D AndroidRuntime: 
09-01 11:00:44.267  6916  6916 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-01 11:00:44.271  6916  6916 D AndroidRuntime: CheckJNI is OFF
09-01 11:00:44.479  6916  6916 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-01 11:00:44.489  1035  2005 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-01 11:00:44.505  1941  1957 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-01 11:00:44.511  1035  2005 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-01 11:00:44.512  1035  2005 D ActivityManager: setTaskToReturnTo : TaskRecord{11760b19 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-01 11:00:44.512  1035  2005 D ActivityManager: setTaskToReturnTo : TaskRecord{11760b19 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-01 11:00:44.514  1035  2005 D WindowStateEx: AppWindowTokenEx init.. 
09-01 11:00:44.515   330   345 E GBMv2   : DFP En is all cleared set to be enabled
09-01 11:00:44.543  1035  2005 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6931 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-01 11:00:44.546  6916  6916 D AndroidRuntime: Shutting down VM
09-01 11:00:44.603  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-01 11:00:44.604  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{decde15 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-01 11:00:44.604  1941  4535 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-01 11:00:44.605  1941  4535 D SplitWindowPolicy: topRunningActivity=ActivityInfo{32c3252a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-01 11:00:44.651  6931  6931 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-01 11:00:44.732  6931  6931 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-01 11:00:44.741  6931  6931 I LibraryLoader: Loading: webviewchromium
09-01 11:00:44.743  6931  6931 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9154-9157)
09-01 11:00:44.744  6931  6931 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 11:00:44.774  6931  6931 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fa7958b}
,09-01 11:00:44.776  6931  6931 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 11:00:44.776  6931  6931 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-01 11:00:44.789  6931  6931 I BrowserStartupController: Initializing chromium process, renderers=0
,09-01 11:00:44.790  6931  6931 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-01 11:00:44.802  6931  6931 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-01 11:00:44.803  6931  6931 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,09-01 11:00:44.804  6931  6931 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-01 11:00:44.826   312  1397 V AudioPolicyService: registerClient() client 0xb57c6c60, uid 10118
,09-01 11:00:44.830  6931  6931 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:00:44.830  6931  6931 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:00:44.830  6931  6931 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:00:44.830  6931  6931 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:00:44.830  6931  6931 I Adreno-EGL: Remote Branch: 
09-01 11:00:44.830  6931  6931 I Adreno-EGL: Local Patches: 
09-01 11:00:44.830  6931  6931 I Adreno-EGL: Reconstruct Branch: 
09-01 11:00:44.838  1035  1105 D BluetoothManagerService: Message: 20
09-01 11:00:44.838  1035  1105 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3166db:true
,09-01 11:00:44.941  6931  6977 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-01 11:00:44.944  6931  6931 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-01 11:00:44.961  6931  6931 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 11:00:44.965  6931  6931 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-01 11:00:44.968  6931  6931 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-01 11:00:44.971  6931  6931 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-01 11:00:44.971  6931  6931 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-01 11:00:44.983  6931  6931 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-01 11:00:44.990  6931  6931 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-01 11:00:44.990  6931  6931 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 11:00:45.042  6931  6993 D OpenGLRenderer: Render dirty regions requested: true
09-01 11:00:45.043  6931  6993 I OpenGLRenderer: Initialized EGL, version 1.4
09-01 11:00:45.063  6931  6993 D OpenGLRenderer: Enabling debug mode 0
,09-01 11:00:45.071  6931  6931 D Atlas   : Validating map...
09-01 11:00:45.075  1035  2051 D SplitWindow: check instance of lgWin Window{31e0bafd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-01 11:00:45.112  6931  6991 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:00:45.112  6931  6991 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:00:45.230  1035  1106 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +628ms (total +714ms)
,09-01 11:00:45.232  1035  1106 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{14fa87de u0 com.test.thalitest/.MainActivity t6} time:189646
09-01 11:00:45.238  6931  6931 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@377c75d6 time:189652
09-01 11:00:45.346  6931  6931 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-01 11:00:45.346  6931  6931 I chromium: 
,09-01 11:00:45.415  6931  6931 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-01 11:00:45.513  6931  6991 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-01 11:00:45.513  6931  6991 I chromium: 
,09-01 11:00:45.658  6931  7007 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435169792
,09-01 11:00:45.678  6931  7007 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-01 11:00:45.678  6931  7007 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-01 11:00:45.678  6931  7007 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-01 11:00:45.678  6931  7007 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-01 11:00:45.678  6931  7007 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-01 11:00:45.678  6931  7007 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83972ba added. We now have 1 listener(s)
,09-01 11:00:45.691  1035  1699 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-01 11:00:45.695  6931  7007 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-01 11:00:45.698  6931  7007 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:00:45.700  6931  7007 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:00:45.700  6931  7007 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:00:45.709  6931  7007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-01 11:00:45.709  6931  7007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-01 11:00:45.709  6931  7007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-01 11:00:45.709  6931  7007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-01 11:00:45.709  6931  7007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-01 11:00:45.709  6931  7007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-01 11:00:45.709  6931  7007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-01 11:00:45.709  6931  7007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-01 11:00:45.709  6931  7007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-01 11:00:45.709  6931  7007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-01 11:00:45.709  6931  7007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-01 11:00:45.709  6931  7007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-01 11:00:45.709  6931  7007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-01 11:00:45.709  6931  7007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-01 11:00:45.709  6931  7007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cb4dd61 added. We now have 1 listener(s)
09-01 11:00:45.710  6931  7007 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:00:45.716  1035  1492 D WifiService: New client listening to asynchronous messages
09-01 11:00:45.722  6931  7007 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 11:00:45.723  6931  7007 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-01 11:00:45.726  6931  7007 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-01 11:00:45.726  6931  7007 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-01 11:00:45.726  6931  7007 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-01 11:00:45.732  6931  7007 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:00:45.732  1035  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:00:45.733  6931  7007 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-01 11:00:45.748  6931  7007 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-01 11:00:45.748  6931  7007 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:00:45.748  6931  7007 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:00:45.748  6931  7007 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:00:45.748  6931  7007 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:00:45.748  6931  7007 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:00:45.748  6931  7007 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:00:45.748  6931  7007 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:00:45.748  6931  7007 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:00:45.749  6931  7007 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-01 11:00:45.749  6931  7007 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:00:45.755  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:00:45.756  6931  7007 I io.jxcore.node.LifeCycleMonitor: start: OK
09-01 11:00:45.758  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:00:45.814  6931  6931 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-01 11:00:46.455   330   355 E GBMv2   : DFP En is all cleared set to be enabled
09-01 11:00:46.455   330   355 E GBMv2   : Set value is all cleared set the max
09-01 11:00:46.455   330   355 I GBMv2   : DFP Enabled. Ignore VFP set
,09-01 11:00:46.924  6931  7010 W jxcore-log: Initializing JXcore engine
09-01 11:00:46.924  6931  7010 W jxcore-log: JXcore engine is ready
,09-01 11:00:46.989  7010  7010 W Thread-807: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7547]" dev="sockfs" ino=7547 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-01 11:00:46.989  7010  7010 W Thread-807: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,09-01 11:00:46.989  7010  7010 W Thread-807: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8801]" dev="sockfs" ino=8801 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-01 11:00:46.989  7010  7010 W Thread-807: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-01 11:00:46.989  7010  7010 W Thread-807: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33529]" dev="sockfs" ino=33529 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-01 11:00:47.023  6931  7010 W jxcore-log: Starting JXcore engine
,09-01 11:00:47.173  6931  7010 W jxcore-log: Platform android
09-01 11:00:47.173  6931  7010 W jxcore-log: 
09-01 11:00:47.173  6931  7010 W jxcore-log: Process ARCH arm
09-01 11:00:47.173  6931  7010 W jxcore-log: 
,09-01 11:00:47.594  6931  7010 I jxcore-log: JXcore Cordova bridge is ready!
09-01 11:00:47.594  6931  7010 I jxcore-log: 
,09-01 11:00:47.595  6931  7010 W jxcore-log: JXcore engine is started
,09-01 11:00:47.603  6931  7007 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-01 11:00:47.606  6931  6931 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-01 11:01:00.057  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-01 11:01:00.057  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
09-01 11:01:00.057  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-01 11:01:00.059  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
09-01 11:01:00.061  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
09-01 11:01:00.062  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
09-01 11:01:00.062  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
09-01 11:01:00.063  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
09-01 11:01:05.642  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-01 11:01:05.642  6931  7010 I jxcore-log: 
,09-01 11:01:05.648  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-01 11:01:05.648  6931  7010 I jxcore-log: 
09-01 11:01:05.653  6931  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:01:05.653  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:05.653  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:05.653  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:05.653  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:01:05.653  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:05.653  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:01:05.653  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:01:05.658  6931  7010 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:01:05.664  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-01 11:01:05.664  6931  7010 I jxcore-log: 
09-01 11:01:05.667  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-01 11:01:05.667  6931  7010 I jxcore-log: 
09-01 11:01:06.638  6931  7010 D executeNativeTests: Running unit tests
,09-01 11:01:06.774  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:01:06.774  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a added. We now have 2 listener(s)
,09-01 11:01:06.778  1035  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:06.780  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:01:06.780  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:01:06.780  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:01:06.781  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:06.781  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b added. We now have 2 listener(s)
09-01 11:01:06.781  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:06.781  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:01:06.785  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:01:06.789  6931  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:01:06.789  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:06.789  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:06.789  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:06.789  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:01:06.789  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:06.789  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:01:06.789  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:01:06.793  6931  7010 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:06.794  6931  7010 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:01:06.796  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:06.797  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:06.801  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-01 11:01:06.804  6931  7010 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:01:06.804  6931  7010 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:01:06.810  6931  7010 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-01 11:01:06.811  6931  7010 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 11:01:06.811  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:01:06.811  6931  7010 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:01:06.811  6931  7010 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:01:06.811  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:06.812  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:06.812  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:06.813  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:06.813  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.813  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:01:06.814  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:01:06.814  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a removed from the list
09-01 11:01:06.814  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.814  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b removed from the list
09-01 11:01:06.814  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:06.814  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:01:06.818  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.818  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.820  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:06.820  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:06.820  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.820  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.823  6931  7010 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-01 11:01:06.825  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:06.826  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:06.826  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:01:06.828  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:06.828  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.829  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.829  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:06.829  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.829  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.829  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:06.829  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.829  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.829  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.829  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.831  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:06.831  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:06.831  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.831  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.839  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 11:01:06.839  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 11:01:06.839  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 11:01:06.839  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 11:01:06.839  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
0,9-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 11:01:06.840  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-01 11:01:06.841  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 11:01:06.841  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 11:01:06.841  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:06.841  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:06.841  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:01:06.848  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:06.848  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.848  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.848  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:06.848  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.848  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.848  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:06.848  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.848  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.848  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.850  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.851  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:06.851  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:06.851  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.851  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.852  6931  7010 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 11:01:06.854  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:01:06.860  6931  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:01:06.860  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:06.860  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:06.860  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:06.860  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:01:06.860  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:06.860  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:01:06.860  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:01:06.862  6931  7010 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:06.862  6931  7010 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:01:06.864  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:06.866  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:01:06.867  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:01:06.868  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:01:06.868  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:01:06.868  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:01:06.868  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:01:06.873  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:01:06.874  1035  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:06.880  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 11:01:06.889  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 11:01:06.892  6931  7010 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-01 11:01:06.894  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:01:06.895  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:01:06.896  6931  7010 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-01 11:01:06.898  6931  7010 I io.jxcore.node.ConnectionHelper: start: OK
09-01 11:01:06.902  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:06.902  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:06.902  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:06.904  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:06.904  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.904  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:01:06.904  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:06.904  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.904  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.904  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:06.904  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.905  6931  7010 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 11:01:06.908  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:01:06.913  6931  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:01:06.913  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:06.913  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:06.913  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:06.913  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:01:06.913  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:06.913  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:01:06.913  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:01:06.914  6931  7010 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:06.915  6931  7010 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:01:06.917  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:06.919  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:01:06.920  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:01:06.920  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:01:06.920  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:01:06.920  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:01:06.920  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:01:06.928  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:01:06.930  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:01:06.933  6931  7010 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-01 11:01:06.933  6931  7010 I io.jxcore.node.ConnectionHelper: start: OK
09-01 11:01:06.935  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:06.935  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:06.935  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:06.936  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:06.936  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.936  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:01:06.936  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:06.936  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.936  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.936  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:06.936  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.937  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.937  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.937  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:06.938  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:06.940  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:06.940  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:06.940  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.940  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.941  6931  7010 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 11:01:06.944  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:01:06.950  6931  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:01:06.950  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:06.950  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:06.950  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:06.950  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:01:06.950  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:06.950  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:01:06.950  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:01:06.952  6931  7010 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:06.952  6931  7010 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:01:06.954  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:06.957  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:01:06.958  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:01:06.958  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:01:06.958  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:01:06.958  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:01:06.959  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:01:06.963  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:01:06.964  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:01:06.965  6931  7010 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 11:01:06.966  6931  7010 I io.jxcore.node.ConnectionHelper: start: OK
09-01 11:01:06.966  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:06.967  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:06.967  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:06.968  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:06.968  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:06.968  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:01:06.970  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:06.970  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.970  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:01:06.970  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:06.971  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.971  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.971  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:06.971  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.971  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.971  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.972  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:06.972  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:06.973  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:06.973  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:06.973  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.973  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.974  6931  7010 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-01 11:01:06.974  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:06.974  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:06.974  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:06.975  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:06.975  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.975  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.975  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:06.975  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.975  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.975  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:06.975  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.975  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluet,oothManager: release: 1 listener(s) left
09-01 11:01:06.975  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.975  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.977  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:06.977  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:06.978  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:06.978  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:06.978  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.978  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.980  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 11:01:06.980  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:06.980  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:06.980  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:06.980  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:06.980  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.980  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.980  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:06.980  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.980  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.980  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:06.980  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.980  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.980  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.980  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.982  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:06.982  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:06.983  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:06.983  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:06.983  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.983  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.984  6931  7010 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-01 11:01:06.984  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:06.985  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:06.985  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:06.985  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:06.985  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.985  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.985  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:06.985  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.985  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.985  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:06.985  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.985  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.985  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.985  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.986  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:06.986  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:06.987  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:06.987  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:06.987  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.987  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.988  6931  7010 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-01 11:01:06.988  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:06.988  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:06.988  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:06.988  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:06.988  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.988  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.988  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:06.988  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.988  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.988  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:06.989  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.989  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.989  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.989  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.990  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:06.990  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:06.991  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:06.991  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:06.991  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.991  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.992  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 11:01:06.994  6931  7010 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:01:06.994  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:01:06.994  6931  7010 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:01:06.994  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 11:01:06.994  6931  7010 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:01:06.995  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:06.995  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:06.995  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:06.995  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:06.995  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.995  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.995  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:06.995  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.996  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.996  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:06.996  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.996  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.996  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:06.996  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:06.997  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:06.997  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:06.998  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:06.998  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:06.998  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:06.998  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:06.999  6931  7010 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:01:06.999  6931  7010 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 11:01:06.999  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 11:01:07.002  6931  7010 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:01:07.003  6931  7010 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 11:01:07.003  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 11:01:07.004  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 11:01:07.004  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 11:01:07.004  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 11:01:07.004  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 11:01:07.004  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 11:01:07.004  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 11:01:07.004  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 11:01:07.004  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 11:01:07.004  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 11:01:07.004  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 11:01:07.004  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 11:01:07.004  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 11:01:07.004  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 11:01:07.004  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 11:01:07.004  6931  7010 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-01 11:01:07.004  6931  7010 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:01:07.005  6931  7010 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-01 11:01:07.005  6931  7010 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:01:07.005  6931  7010 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:01:07.005  6931  7010 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-01 11:01:07.005  6931  7010 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:01:07.005  6931  7010 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:01:07.005  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-01 11:01:07.016  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-01 11:01:07.017  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-01 11:01:07.017  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-01 11:01:07.018  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-01 11:01:07.018  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-01 11:01:07.019  6931  7010 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-01 11:01:07.019  6931  7010 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:01:07.019  6931  7010 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-01 11:01:07.019  6931  7029 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 871)
09-01 11:01:07.019  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:07.019  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:07.019  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:07.020  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:07.020  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.020  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.021  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-01 11:01:07.021  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:07.021  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.021  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.021  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:07.021  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.021  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.021  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.021  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.022  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:07.022  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:07.024  6931  7030 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 871
09-01 11:01:07.025  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:07.025  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:07.025  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.025  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.029  6931  7010 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-01 11:01:07.032  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:07.032  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:07.032  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:07.032  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:07.032  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.032  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.032  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:07.032  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.032  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.032  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:07.032  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.032  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.033  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.033  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.034  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:07.034  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:07.035  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:07.035  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:07.035  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.035  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.036  6931  7010 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-01 11:01:07.037  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:07.037  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:07.037  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:07.037  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:07.037  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.037  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.037  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:07.037  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.039  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.039  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:07.039  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.039  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.039  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.039  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.046  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:07.046  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:07.047  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:07.047  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:07.047  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.047  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.048  6931  7010 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-01 11:01:07.048  6931  7010 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-01 11:01:07.048  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:01:07.048  6931  7010 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-01 11:01:07.049  6931  7010 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 11:01:07.049  6931  7010 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-01 11:01:07.049  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:01:07.049  6931  7010 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-01 11:01:07.049  6931  7010 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 11:01:07.049  6931  7010 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 11:01:07.049  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:01:07.049  6931  7010 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-01 11:01:07.049  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:07.049  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:07.049  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:07.050  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:07.050  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:01:07.050  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.050  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:07.050  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.050  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.050  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:07.050  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:01:07.050  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.050  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.050  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:01:07.056  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:07.057  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:07.058  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:07.058  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:07.058  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.058  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.059  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:07.059  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.059  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.059  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:07.059  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.059  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.059  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:07.060  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.060  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.060  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.060  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.060  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:07.060  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.061  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.061  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:07.061  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:07.061  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:07.061  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:07.062  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:07.062  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.062  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.062  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01, 11:01:07.062  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.062  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.062  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:07.062  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.062  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.062  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.062  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.064  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:07.064  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:07.065  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:07.065  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:07.065  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.065  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.067  6931  7010 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-01 11:01:07.068  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:01:07.068  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-01 11:01:07.069  6931  7010 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-01 11:01:07.069  6931  7010 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-01 11:01:07.070  6931  6931 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-01 11:01:07.070  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-01 11:01:07.070  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-01 11:01:07.072  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:07.072  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-01 11:01:07.072  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-01 11:01:07.072  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-01 11:01:07.072  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.072  6931  7010 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-01 11:01:07.072  6931  6931 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-01 11:01:07.073  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:07.073  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.073  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:01:07.073  6931  7010 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 11:01:07.073  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:01:07.074  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:01:07.075  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:07.075  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:07.075  6931  7010 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:01:07.075  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.075  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.076  6931  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-01 11:01:07.076  6931  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-01 11:01:07.083  6931  7010 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:01:07.084  6931  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:01:07.084  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.084  6931  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:01:07.085  6931  6931 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-01 11:01:07.085  6931  6931 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:01:07.085  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:07.085  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:07.086  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:07.087  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:07.087  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.087  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.087  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:07.087  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.087  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.087  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:07.087  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.087  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.087  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.087  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.088  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:07.089  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:07.089  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.089  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.090  6931  7010 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-01 11:01:07.096  6931  7010 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 11:01:07.096  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:01:07.096  6931  7010 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:01:07.096  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:07.096  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:07.096  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:07.097  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:07.097  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.097  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.097  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:07.097  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.097  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.097  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:07.097  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.097  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.097  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.097  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.099  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:07.099  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:07.099  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.099  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.100  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:07.101  1035  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:07.102  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:07.103  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:07.103  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:07.103  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-01 11:01:07.103  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:07.103  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.103  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.103  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:07.103  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.103  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.104  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:07.104  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.104  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.104  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.104  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:01:07.105  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:07.105  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:07.105  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.105  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
,09-01 11:01:07.106  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:07.106  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:07.107  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:07.107  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:07.107  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.107  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.107  6931  7010 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893270a not in the list
09-01 11:01:07.107  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.107  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.107  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:07.107  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.107  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.108  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:07.108  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:07.109  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:01:07.109  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:07.109  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:07.109  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848db7b not in the list
09-01 11:01:07.111  6931  7010 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-01 11:01:07.111  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:01:07.111  6931  7010 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-01 11:01:07.112  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:01:07.112  6931  7010 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-01 11:01:07.112  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-01 11:01:07.115  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 11:01:07.115  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-01 11:01:07.116  6931  7010 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-01 11:01:07.116  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 11:01:07.117  6931  7010 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-01 11:01:07.117  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 11:01:07.117  6931  7010 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-01 11:01:07.117  6931  7010 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-01 11:01:07.119  6931  7010 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-01 11:01:07.119  6931  7010 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-01 11:01:07.120  6931  7010 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-01 11:01:07.120  6931  7010 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-01 11:01:07.120  6931  7010 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-01 11:01:07.120  6931  7010 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-01 11:01:07.122  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:07.122  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b0807b0 added. We now have 2 listener(s)
09-01 11:01:07.122  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:07.123  6931  7010 D BluetoothAdapter: enable(): BT is already enabled..!
09-01 11:01:07.125  1035  2051 D WifiServiceImplEx: setWifiEnabled: true pid=6931, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-01 11:01:07.127  1035  2051 D WifiService: setWifiEnabled: true pid=6931, uid=10118
09-01 11:01:07.127  1035  2051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:01:07.129  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:07.129  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16e31629 added. We now have 3 listener(s)
09-01 11:01:07.129  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:07.135  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:07.136  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c271dae added. We now have 4 listener(s)
09-01 11:01:07.136  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:07.140  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:07.140  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a46d74f added. We now have 5 listener(s)
,09-01 11:01:07.140  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:07.145  1035  1958 D WifiServiceImplEx: setWifiEnabled: false pid=6931, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-01 11:01:07.145  1035  1958 D WifiService: setWifiEnabled: false pid=6931, uid=10118
09-01 11:01:07.145  1035  1958 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-01 11:01:07.148  6931  7029 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-01 11:01:07.148  6931  7029 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:01:07.149  4407  4429 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:01:07.149  4407  4581 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
09-01 11:01:07.151  4407  4429 D LGBluetoothServiceAdapter: [BTUI] connectSocket FD=84 mFd=82
,09-01 11:01:07.167  1035  1440 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-01 11:01:07.167  1035  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:07.167  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-01 11:01:07.168  1035  1440 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-01 11:01:07.168  1035  2033 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@219863b4 mBinding = false
09-01 11:01:07.168  1035  1440 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-01 11:01:07.168  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-01 11:01:07.168  1035  1440 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-01 11:01:07.169  1035  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:01:07.169  1035  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-01 11:01:07.169  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:01:07.169  1035  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-01 11:01:07.169  1035  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-01 11:01:07.170  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:01:07.170  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-01 11:01:07.189  1035  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-01 11:01:07.189  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-01 11:01:07.189  2767  2767 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-01 11:01:07.189  1035  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:07.189  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:07.190  1035  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-01 11:01:07.190  1035  1440 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:01:07.191  1035  1440 D WifiNative-wlan0: SET ps 1: returned true
,09-01 11:01:07.192  1035  2869 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:07.196   308   891 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:01:07.200  1035  1105 D BluetoothManagerService: Message: 2
,09-01 11:01:07.202  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:01:07.202  1035  1105 D BluetoothManagerService: Sending off request.
09-01 11:01:07.202  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:01:07.202  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-01 11:01:07.203  4407  4514 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-01 11:01:07.204  4407  4464 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-01 11:01:07.204  4407  4464 D BluetoothAdapterProperties: Setting state to 13
09-01 11:01:07.205  4407  4464 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 11:01:07.207  4407  4464 D BluetoothAdapterProperties: onBluetoothDisable()
09-01 11:01:07.207  4407  4464 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-01 11:01:07.209  4407  4471 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:01:07.210  1035  1105 D BluetoothManagerService: Message: 60
09-01 11:01:07.210  1035  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-01 11:01:07.210  1035  1105 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-01 11:01:07.211  4407  4464 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-01 11:01:07.212  4407  4800 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:01:07.212  4407  4464 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-01 11:01:07.212  4407  4802 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:01:07.213  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-01 11:01:07.213  4407  4581 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-01 11:01:07.213  4407  4799 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:01:07.213  4407  4735 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:01:07.216  6931  7029 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 871)
09-01 11:01:07.216  4407  4733 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-01 11:01:07.216  4407  4733 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:01:07.216  4407  4733 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-01 11:01:07.216  4407  4733 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-01 11:01:07.216  4407  4733 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-01 11:01:07.216  4407  4733 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-01 11:01:07.216  4407  4733 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-01 11:01:07.216  4407  4733 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-01 11:01:07.216  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:01:07.216  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:01:07.216  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:01:07.216  4,407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:01:07.217  4407  4581 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:01:07.217  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:01:07.217  4407  4581 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:01:07.217  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:01:07.217  4407  4581 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:01:07.217  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-01 11:01:07.217  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-01 11:01:07.217  4407  4581 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-01 11:01:07.221  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:07.221  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:07.221  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:07.221  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:07.221  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:07.221  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:01:07.221  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:07.221  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:01:07.221  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:01:07.230  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:07.230  6931  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:07.237  1035  1501 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-01 11:01:07.237  1035  1501 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,09-01 11:01:07.245  1035  1938 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-01 11:01:07.246  1035  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:07.246  1035  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:07.246  1035  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-01 11:01:07.246  1035  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:07.246  1035  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-01 11:01:07.254  1035  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7048 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-01 11:01:07.258  4407  4407 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:07.259  4407  4407 D BluetoothMapService: STATE_TURNING_OFF
09-01 11:01:07.259  4407  4407 V BluetoothMapService: Handler(): got msg=4
09-01 11:01:07.259  4407  4407 D BluetoothMapService: MAP Service closeService in
09-01 11:01:07.259  4407  4407 D BluetoothMapMasInstance: MAP Service shutdown
09-01 11:01:07.259  4407  4407 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:01:07.259  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:07.259  4407  4407 V BluetoothMapService: MAP Service closeService out
09-01 11:01:07.259  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:01:07.261  4407  4407 V BtOppService: Receiver DISABLED_ACTION 
09-01 11:01:07.261  4407  4407 I BtOppRfcommListener: stopping Accept Thread
09-01 11:01:07.261  4407  4407 V BtOppRfcommListener: close mBtServerSocket
09-01 11:01:07.261  4407  4407 V BtOppRfcommListener: waiting for thread to terminate
09-01 11:01:07.262  4407  4799 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-01 11:01:07.262  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:07.262  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:07.262  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:07.262  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:07.262  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:07.262  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:01:07.262  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:07.262  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:07.262  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:01:07.262  4407  4407 V BtOppRfcommListener: done waiting for thread to terminate
09-01 11:01:07.263  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:07.263  6931  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:01:07.292  1035  1501 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-01 11:01:07.293  1035  1501 D DSQN    : disableDataServiceNotify
09-01 11:01:07.293  1035  1501 D DSQN    : stop dsqn bin
09-01 11:01:07.293   308  7067 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-01 11:01:07.293  1035  1102 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-01 11:01:07.293  1035  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,09-01 11:01:07.299  1035  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7068 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-01 11:01:07.301  4407  4407 V BtOppService: onDestroy
09-01 11:01:07.302  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-01 11:01:07.304  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:01:07.304  1035  1501 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-01 11:01:07.304  1035  1501 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:07.304  1035  1501 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:07.305  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-01 11:01:07.305  1035  1501 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:07.305  4407  4407 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-01 11:01:07.305  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:07.305  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:07.306  1035  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:07.306  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:07.306  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:01:07.306  1604  2114 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-01 11:01:07.306  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-01 11:01:07.306  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:07.306  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:07.306  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:01:07.306  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-01 11:01:07.306  1035  1391 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@a522921
09-01 11:01:07.306  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-01 11:01:07.306  1035  1558 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:07.307  1035  1391 D LGWifiP2pService: P2pDisablingState
09-01 11:01:07.307  1035  1391 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:07.307  1035  1391 D LGWifiP2pService: p2p socket connection lost
09-01 11:01:07.307  1035  1391 D LGWifiP2pService: P2pDisabledState
09-01 11:01:07.307  1035  1559 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:07.307  1035  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:07.307  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-01 11:01:07.307  1941  1941 D WfdsService: WifiP2pState is changed : false
09-01 11:01:07.307  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:07.308  1941  2209 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-01 11:01:07.308  1941  2209 D WfdsService: Set the WFDS Monitor: false
09-01 11:01:07.308  1035  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:07.308  1941  2209 D WfdsMonitor: WFDS Monitor is stopped
09-01 11:01:07.308  1035  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:07.308  1941  2209 D WfdsService: STATE : WfdsDisabledState - enter
09-01 11:01:07.308  1941  2787 D CtrlSupplicant: Received on exit socket, terminate
09-01 11:01:07,.308  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:07.309  1941  2213 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-01 11:01:07.309  1035  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:07.308  1941  2787 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-01 11:01:07.309  1941  2787 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-01 11:01:07.309  1941  2787 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-01 11:01:07.309  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:07.309  6931  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:01:07.309  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:07.309  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:07.309  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:07.309  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:01:07.309  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:07.309  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:07.309  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:01:07.309  1941  2209 W WfdsService: DefaultState - msg [9445378] is not handled
09-01 11:01:07.309  1035  1440 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-01 11:01:07.309  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:07.309  6931  7010 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:01:07.309  1035  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:07.309  6931  7010 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:01:07.310  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:07.310  1035  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:07.310  1035  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-01 11:01:07.312  1035  1501 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-01 11:01:07.313  1035  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-8ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:07.313  1035  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-8ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:07.313  1035  1501 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explic,itlySelected{false} } list []  wasFirstNetwork :true
09-01 11:01:07.313  1035  1501 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-01 11:01:07.313  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:07.313  1035  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-01 11:01:07.313  1035  1501 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:01:07.314  1035  1501 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:07.314  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:07.315  1035  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-01 11:01:07.315  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-01 11:01:07.316  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-01 11:01:07.316  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-01 11:01:07.316  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-01 11:01:07.314  1035  1501 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:01:07.316  1035  1501 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:07.316  1035  1501 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:07.318  1035  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-01 11:01:07.318  1035  1501 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:07.318  1035  1501 D NetworkManagementService: Removing idletimer
09-01 11:01:07.319  1035  1501 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:07.319  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-01 11:01:07.319  1854  1854 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:07.320  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-01 11:01:07.320  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-01 11:01:07.320  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-01 11:01:07.320  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-01 11:01:07.320  1035  1501 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-01 11:01:07.320  1035  1391 D LGWifiP2pService: P2pDisabledState{ when=-10ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:07.320  1035  1391 D LGWifiP2pService: DefaultState{ when=-10ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:07.320  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-01 11:01:07.321  2767  2767 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-01 11:01:07.321  1035  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-01 11:01:07.321  1035  1440 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:01:07.322  1035  1440 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:01:07.323   308   891 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:01:07.327  1035  1440 D WifiNative-p2p0: doBoolean: TERMINATE
09-01 11:01:07.327  1035  1440 D WifiNative-p2p0: TERMINATE: returned true
09-01 11:01:07.327  1035  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:01:07.327  1035  1440 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:01:07.327  1035  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:01:07.328  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-01 11:01:07.328  1035  1440 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:07.328  1035  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:01:07.328  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:07.328  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:07.329  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:01:07.329  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-01 11:01:07.333  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-01 11:01:07.334  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:07.334  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:07.334  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:07.334  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:07.334  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:01:07.334  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:01:07.334  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:07.334  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:07.334  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:01:07.335  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:01:07.335  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-01 11:01:07.335  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:07.335  6931  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:01:07.336  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:07.336  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:07.337  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:07.342  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:07.342  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:07.342  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:07.342  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:07.342  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:01:07.342  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:01:07.342  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:07.342  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:07.342  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:01:07.343  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:07.343  6931  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:01:07.350  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:07.350  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:07.351  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:07.366  7068  7068 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:01:07.366  7068  7068 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-01 11:01:07.367  7068  7068 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:01:07.367  7068  7068 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-01 11:01:07.368  7068  7068 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-01 11:01:07.368  7068  7068 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-01 11:01:07.370  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:01:07.370  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:07.371  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:01:07.383  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:01:07.384  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:07.384  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:07.388  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-01 11:01:07.388  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:07.389  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:07.390  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:07.409  2767  2767 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-01 11:01:07.409  2767  2767 I wpa_supplicant: monitor socket send errors count : 1
09-01 11:01:07.409  2767  2767 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
09-01 11:01:07.409  1035  2869 D DhcpStateMachine: StoppedState
,09-01 11:01:07.409  1035  2869 D DhcpStateMachine: StoppedState{ when=-86ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:01:07.410  1035  1440 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-01 11:01:07.410  1035  1440 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-01 11:01:07.410  1035  2786 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-01 11:01:07.410  1035  2786 D WifiMonitor: Dropping event because (p2p0) is stopped
09-01 11:01:07.412  7048  7048 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-01 11:01:07.413  7048  7048 W LG Account v2.2: No ProfileInfo entries
09-01 11:01:07.413  7048  7048 I LG Account v2.2: isEnabled: false
09-01 11:01:07.413  7048  7048 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-01 11:01:07.413  7048  7048 I Feature : [Lifetracker]Country: EU
09-01 11:01:07.413  7048  7048 I Feature : [Lifetracker]Operator: OPEN
09-01 11:01:07.413  7048  7048 I Feature : [Lifetracker]Ranking support: false
09-01 11:01:07.413  7048  7048 I Feature : [Lifetracker]Comfort support: false
09-01 11:01:07.413  7048  7048 I Feature : [Lifetracker]Accessory: true
09-01 11:01:07.413  7048  7048 I Feature : [Lifetracker]Health device: true
09-01 11:01:07.413  7048  7048 I Feature : [Lifetracker]Extra Pedometer: false
09-01 11:01:07.413  7048  7048 I Feature : [Lifetracker]Blood glucose device: false
09-01 11:01:07.413  7048  7048 I Feature : [Lifetracker]Device Number: 3
09-01 11:01:07.423  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:01:07.446  7068  7068 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-01 11:01:07.453  1035  1577 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7089 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-01 11:01:07.454  1035  1726 I ActivityManager: Killing 6410:com.android.defcontainer/u0a4 (adj 15): empty #17
09-01 11:01:07.488  4407  4407 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:01:07.488  4407  4407 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:07.488  4407  4407 V BluetoothPbapReceiver: ***********state = 13
09-01 11:01:07.490  4407  4407 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,09-01 11:01:07.491  1035  1995 W libprocessgroup: failed to open /acct/uid_10004/pid_6410/cgroup.procs: No such file or directory
09-01 11:01:07.493  4407  4407 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:07.493  4407  4407 V BluetoothPbapService: state: 13
09-01 11:01:07.493  4407  4407 V BluetoothPbapService: Pbap Service closeService in
09-01 11:01:07.494  1035  1105 D BluetoothManagerService: Message: 20
09-01 11:01:07.494  1035  1105 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f3eb17f:true
09-01 11:01:07.495  4407  4407 V BluetoothPbapService: successfully stopped pbap service
09-01 11:01:07.495  4407  4407 V BluetoothPbapService: Pbap Service closeService out
09-01 11:01:07.495  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:01:07.495  4407  4407 V BluetoothPbapService: Pbap Service onDestroy
09-01 11:01:07.495  4407  4407 V BluetoothPbapService: Pbap Service closeService in
09-01 11:01:07.495  4407  4407 V BluetoothPbapService: Pbap Service closeService out
09-01 11:01:07.495  4407  4407 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-01 11:01:07.512  1035  1105 D BluetoothManagerService: Message: 30
,09-01 11:01:07.517  1035  1105 D BluetoothManagerService: Message: 30
09-01 11:01:07.519  7068  7068 D LocalBluetoothProfileManager: Adding local MAP profile
09-01 11:01:07.520  7068  7068 D BluetoothMap: Create BluetoothMap proxy object
09-01 11:01:07.520  1035  1105 D BluetoothManagerService: Message: 30
09-01 11:01:07.523  1035  1105 D BluetoothManagerService: Message: 30
09-01 11:01:07.524  2767  2767 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:01:07.525  2767  2767 W wpa_supplicant: USIM:  scard_deinit function
,09-01 11:01:07.525  7068  7068 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-01 11:01:07.525  1035  2786 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-01 11:01:07.525  1035  2786 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:01:07.525  1035  2786 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:01:07.526  1035  2786 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-01 11:01:07.526  1035  2786 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:01:07.526  1035  2786 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:01:07.526  7068  7068 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-01 11:01:07.526  1035  1440 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=211928
09-01 11:01:07.527  1035  1440 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=211929
09-01 11:01:07.527  1035  1440 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=211929  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-01 11:01:07.528  1035  1440 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=211930  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-01 11:01:07.528  1035  1105 D Tethering: InitialState.processMessage what=4
09-01 11:01:07.530  1035  1105 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-01 11:01:07.530  1035  1440 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:07.531  1035  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:07.536  7089  7089 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-01 11:01:07.538  7068  7068 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-01 11:01:07.540  7068  7068 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-01 11:01:07.546  7089  7089 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:01:07.547  7089  7089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:01:07.548  1035  1962 I ActivityManager: Killing 6599:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-01 11:01:07.549  7068  7068 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:01:07.556  7068  7068 D BluetoothInputDevice: Proxy object connected
09-01 11:01:07.556  7068  7068 D HidProfile: Bluetooth service connected
,09-01 11:01:07.557  7068  7068 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:01:07.557  7068  7068 D PanProfile: Bluetooth service connected
09-01 11:01:07.558  7068  7068 D BluetoothMap: Proxy object connected
09-01 11:01:07.558  7068  7068 D MapProfile: Bluetooth service connected
09-01 11:01:07.559  7068  7068 D BluetoothMap: getConnectedDevices()
09-01 11:01:07.559  7068  7068 D BluetoothMap: Bluetooth is Not enabled
09-01 11:01:07.559  7068  7068 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-01 11:01:07.577  2767  2767 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-01 11:01:07.577  1035  2786 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-01 11:01:07.577  1035  2786 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-TERMINATING 
09-01 11:01:07.577  1035  2786 D WifiMonitor: Disconnecting from the supplicant, no more events
09-01 11:01:07.578  1035  1440 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 21 0
,09-01 11:01:07.584  1035  1050 W libprocessgroup: failed to open /acct/uid_10008/pid_6599/cgroup.procs: No such file or directory
09-01 11:01:07.585  6931  6931 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-01 11:01:07.602  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:07.650  7068  7068 D LgDataFeature: LgDataFeature() Constructor: none
,09-01 11:01:07.650  7068  7068 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:01:07.662  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:07.666  7068  7068 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-01 11:01:07.673  7068  7068 D BluetoothPermissionRequest: onReceive
09-01 11:01:07.677  7068  7068 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-01 11:01:07.682  1941  1941 D WfdsService: Supplicant Connection state is changed : false
09-01 11:01:07.682  1035  1440 D WifiOffDelayIfNotUsed: stopMonitoring
09-01 11:01:07.682  1035  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:01:07.682  1035  1440 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:01:07.682  1035  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:01:07.682  1941  2209 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-01 11:01:07.682  1941  2209 D WfdsService: Set the WFDS Monitor: false
09-01 11:01:07.682  1941  2209 D WfdsMonitor: WFDS Monitor is stopped
09-01 11:01:07.683  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-01 11:01:07.684  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:07.685  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-01 11:01:07.686  1035  1469 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-01 11:01:07.686  1035  1469 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-01 11:01:07.688  2427  2427 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:07.690  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:07.692  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:01:07.700  1035  1958 I ActivityManager: Killing 6126:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-01 11:01:07.702  7068  7068 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-01 11:01:07.769  1035  1995 W libprocessgroup: failed to open /acct/uid_10011/pid_6126/cgroup.procs: No such file or directory
09-01 11:01:07.771  4407  4407 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-01 11:01:07.771  4407  4407 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-01 11:01:07.773  4407  4407 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-01 11:01:07.861  1035  1051 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7117 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-01 11:01:07.863  4407  4407 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:07.863  4407  4407 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-01 11:01:07.866  4407  4407 V BluetoothFtpService: Ftp Service onStartCommand
09-01 11:01:07.866  4407  4407 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:07.867  4407  4407 V BluetoothFtpService: Ftp Service closeService
09-01 11:01:07.867  4407  4407 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-01 11:01:07.869  4407  4407 V BluetoothFtpService: successfully stopped ftp service
09-01 11:01:07.869  4407  4407 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:01:07.869  4407  4407 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:01:07.869  4407  4407 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:01:07.869  4407  4407 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:07.869  4407  4407 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-01 11:01:07.869  4407  4407 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-01 11:01:07.871  4407  4407 V BluetoothFtpService: Ftp Service onDestroy
09-01 11:01:07.871  4407  4407 V BluetoothFtpService: Ftp Service closeService
09-01 11:01:07.936  1035  1938 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7134 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-01 11:01:07.950  4407  4407 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:07.950  4407  4407 V BluetoothSapService: state: 13
,09-01 11:01:07.950  4407  4407 V BluetoothSapService: Stopping SAP server process
09-01 11:01:07.954  4407  4407 V BluetoothSapService: Sap Service closeSapService in
09-01 11:01:07.954  4407  4407 V BluetoothSapService: Close listen Socket : 
09-01 11:01:07.955  4407  4407 V BluetoothSapService: Close rfcomm Socket : 
09-01 11:01:07.955  4407  4407 V BluetoothSapService: Close sapd  Socket : 
09-01 11:01:07.956  4407  4407 V BluetoothSapService: Sap Service closeSapService out
09-01 11:01:07.957  4407  4407 V BluetoothSapService: Sap Service onDestroy
09-01 11:01:07.957  4407  4407 V BluetoothSapService: Sap Service closeSapService in
09-01 11:01:07.957  4407  4407 V BluetoothSapService: Close listen Socket : 
09-01 11:01:07.957  4407  4407 V BluetoothSapService: Close rfcomm Socket : 
09-01 11:01:07.957  4407  4407 V BluetoothSapService: Close sapd  Socket : 
09-01 11:01:07.958  4407  4407 V BluetoothSapService: Sap Service closeSapService out
09-01 11:01:07.973  7117  7117 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-01 11:01:08.000  7134  7134 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-01 11:01:08.013  7117  7117 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-01 11:01:08.017  1035  2033 I ActivityManager: Killing 6149:com.android.contacts/u0a19 (adj 15): empty #17
09-01 11:01:08.088  1035  1050 W libprocessgroup: failed to open /acct/uid_10019/pid_6149/cgroup.procs: No such file or directory
,09-01 11:01:08.137  7117  7117 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-01 11:01:08.138  7117  7117 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-01 11:01:08.138  7117  7117 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-01 11:01:08.138  7117  7117 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-01 11:01:08.139  7117  7117 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-01 11:01:08.141  7117  7117 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-01 11:01:08.148  7117  7117 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-01 11:01:08.156  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-01 11:01:08.160  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:08.194  7117  7117 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-01 11:01:08.198  7117  7117 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-01 11:01:08.200  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:08.202  7117  7117 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-01 11:01:08.207  7089  7089 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-01 11:01:08.208  7089  7089 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:01:08.208  7089  7089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:01:08.214  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:08.219  4407  4471 D bt_hci_bdroid: cleanup
09-01 11:01:08.219  4407  4584 I bt_lpm  : LPM is already off!!!
09-01 11:01:08.220  4407  4693 I bt_userial_mct: exiting userial_read_thread
09-01 11:01:08.220  4407  4693 D bt_userial_mct: Leaving userial_evt_read_thread()
09-01 11:01:08.221  4407  4581 W bt-btif : ag scb idx 1 not allocated
09-01 11:01:08.221  4407  4581 E bt-btif : BTA AG is already disabled, ignoring ...
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:01:08.221  4407  4471 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:01:08.221  4407  4584 I bt_vendor: hw_epilog_process
09-01 11:01:08.221  4407  4581 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:01:08.221  4407  4581 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-01 11:01:08.222  4407  4471 D bt_hci_bdroid: cleanup Finalizing cleanup
09-01 11:01:08.222  4407  4471 D bt_userial_mct: userial_close
09-01 11:01:08.222  4407  4471 E bt_userial_mct: pthread_join() FAILED result:3
,09-01 11:01:08.222  4407  4471 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-01 11:01:08.226  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:08.243  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:08.243  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:08.245  7117  7117 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-01 11:01:08.248  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:01:08.253  7089  7089 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-01 11:01:08.253  7089  7089 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:01:08.253  7089  7089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:01:08.257  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:08.266  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:08.276  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:08.276  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-01 11:01:08.278  7117  7117 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-01 11:01:08.336  4407  4471 D bt_hci_bdroid: set_power 0
09-01 11:01:08.336  4407  4471 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-01 11:01:08.336  4407  4471 I bt_vendor: bluetooth satus is on
09-01 11:01:08.336  4407  4471 I bt_vendor: bt-vendor : resetting BT status
09-01 11:01:08.336  4407  4471 I bt_vendor: Starting hciattach daemon
09-01 11:01:08.336  4407  4471 I bt_vendor: try to set false
,09-01 11:01:08.338  4407  4471 I bt_vendor: Starting hciattach daemon
09-01 11:01:08.338  4407  4471 I bt_vendor: try to set false
09-01 11:01:08.339  4407  4471 I bt_vendor: cleanup
09-01 11:01:08.339  4407  4581 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-01 11:01:08.340  4407  4471 I GKI_LINUX: GKI_exit_task 0 done
09-01 11:01:08.340  4407  4471 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-01 11:01:08.341  4407  4464 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-01 11:01:08.346  1035  2031 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7161 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-01 11:01:08.350  4407  4407 D HeadsetService: Received stop request...Stopping profile...
,09-01 11:01:08.353  4407  4407 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-01 11:01:08.353  4407  4407 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:01:08.353  4407  4407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e6d3668
09-01 11:01:08.354  4407  4510 D HeadsetStateMachine: Exit Disconnected: -1
09-01 11:01:08.356  1854  1854 D BluetoothHeadset: Proxy object disconnected
09-01 11:01:08.356  1854  1854 D BluetoothHeadset: Proxy object disconnected
09-01 11:01:08.356  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-01 11:01:08.356  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-01 11:01:08.357  1854  1854 D BluetoothHeadset: Proxy object disconnected
09-01 11:01:08.358  4407  4407 D A2dpService: Received stop request...Stopping profile...
09-01 11:01:08.359  4407  4464 D BluetoothAdapterState: Stopping profile services that were post enabled
09-01 11:01:08.359  4407  4569 D A2dpStateMachine: Exit Disconnected: -1
09-01 11:01:08.359  4407  4407 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-01 11:01:08.361  4407  4407 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-01 11:01:08.361  4407  4407 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:01:08.361  4407  4407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e6d3668
,09-01 11:01:08.365  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-01 11:01:08.365  4407  4407 D HidService: Received stop request...Stopping profile...
09-01 11:01:08.365  4407  4407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e6d3668
09-01 11:01:08.366  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-01 11:01:08.366  4407  4407 D HealthService: Received stop request...Stopping profile...
09-01 11:01:08.367  4407  4407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e6d3668
09-01 11:01:08.368  4407  4407 D HeadsetStateMachine: Unbinding service...
09-01 11:01:08.370  4407  4407 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:01:08.370  4407  4407 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:01:08.370  4407  4407 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:01:08.370  4407  4407 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:01:08.370  4407  4407 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 11:01:08.370  4407  4407 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:01:08.370  4407  4407 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-01 11:01:08.371  4407  4407 D PanService: Received stop request...Stopping profile...
09-01 11:01:08.371  4407  4407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e6d3668
09-01 11:01:08.372  7068  7068 D BluetoothInputDevice: Proxy object disconnected
09-01 11:01:08.372  7068  7068 D HidProfile: Bluetooth service disconnected
09-01 11:01:08.372  7068  7068 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 11:01:08.372  7068  7068 D PanProfile: Bluetooth service disconnected
09-01 11:01:08.373  4407  4407 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 11:01:08.373  4407  4407 D BtGatt.GattService: Received stop request...Stopping profile...
09-01 11:01:08.373  4407  4407 D BtGatt.GattService: stop()
09-01 11:01:08.374  4407  4407 D BtGatt.AdvertiseManager: advertise clients cleared
09-01 11:01:08.374  4407  4407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e6d3668
,09-01 11:01:08.376  4407  4407 D BluetoothMapService: Received stop request...Stopping profile...
,09-01 11:01:08.376  4407  4407 D BluetoothMapService: stop()
09-01 11:01:08.377  4407  4407 D BluetoothMapEmailAppObserver: deinitObservers()
09-01 11:01:08.377  4407  4407 D BluetoothMapEmailAppObserver: removeReceiver()
09-01 11:01:08.378  4407  4407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e6d3668
09-01 11:01:08.379  4407  4407 I BluetoothA2dpServiceJni: cleanupNative
09-01 11:01:08.379  4407  4570 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-01 11:01:08.379  4407  4407 I GKI_LINUX: GKI_exit_task 2 done
09-01 11:01:08.379  4407  4407 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-01 11:01:08.380  4407  4407 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 11:01:08.380  4407  4407 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 11:01:08.380  4407  4407 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 11:01:08.381  4407  4407 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 11:01:08.381  4407  4407 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 11:01:08.382  4407  4407 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 11:01:08.382  4407  4407 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-01 11:01:08.382  7068  7068 D BluetoothMap: Proxy object disconnected
09-01 11:01:08.382  7068  7068 D MapProfile: Bluetooth service disconnected
09-01 11:01:08.383  4407  4407 V BluetoothMapService: Handler(): got msg=4
09-01 11:01:08.383  4407  4407 D BluetoothMapService: MAP Service closeService in
09-01 11:01:08.383  4407  4407 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:01:08.383  4407  4407 V BluetoothMapService: MAP Service closeService out
09-01 11:01:08.384  4407  4464 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-01 11:01:08.384  4407  4464 D BluetoothAdapterProperties: Setting state to 10
09-01 11:01:08.384  4407  4464 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-01 11:01:08.385  4407  4464 I BluetoothAdapterState: Entering OffState
09-01 11:01:08.385  1035  1105 D BluetoothManagerService: Message: 60
09-01 11:01:08.385  1035  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-01 11:01:08.385  1035  1105 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-01 11:01:08.385  4407  4407 D BluetoothMapService: cleanup()
,09-01 11:01:08.385  4407  4407 D BluetoothMapService: MAP Service closeService in
09-01 11:01:08.385  4407  4407 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:01:08.385  4407  4407 V BluetoothMapService: MAP Service closeService out
09-01 11:01:08.386  7068  7085 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 11:01:08.387  7068  7084 D BluetoothMap: onBluetoothStateChange: up=false
09-01 11:01:08.388  7068  7085 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 11:01:08.389  1854  2443 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-01 11:01:08.389  1854  4534 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:01:08.390  1035  1105 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:01:08.390  1854  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:01:08.391  7068  7084 D BluetoothPan: onBluetoothStateChange on: false
09-01 11:01:08.391  1035  1105 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 11:01:08.392  1035  1105 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-01 11:01:08.392  1035  1105 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-01 11:01:08.397  1035  1105 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-01 11:01:08.397  1035  1105 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-01 11:01:08.398  1035  1105 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@219863b4 mBinding = false
09-01 11:01:08.398  1035  1105 D BluetoothManagerService: Sending unbind request.
09-01 11:01:08.399  1035  1105 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-01 11:01:08.403  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:01:08.404  7068  7068 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-01 11:01:08.404  7068  7068 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-01 11:01:08.404  7068  7068 D LGBluetoothEventManager: [BTUI] clear device connection state
09-01 11:01:08.406  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:01:08.407  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:08.407  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:08.410  1604  1604 D BluetoothAdapter: 721991424: getState() :  mService = null. Returning STATE_OFF
09-01 11:01:08.410  1604  1604 D BluetoothAdapter: 721991424: getState() :  mService = null. Returning STATE_OFF
09-01 11:01:08.411  1941  2102 D LGBluetoothAPIService: Message: 2
09-01 11:01:08.411  1941  2102 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3ae5cf1b mBinding = false
09-01 11:01:08.411  1941  2102 D LGBluetoothAPIService: Sending unbind request.
09-01 11:01:08.422  4407  4471 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-01 11:01:08.423  4407  4407 I GKI_LINUX: GKI_exit_task 1 done
09-01 11:01:08.423  4407  4407 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-01 11:01:08.423  4407  4407 I BluetoothServiceJni: cleanupNative: return from cleanup
09-01 11:01:08.423  4407  4407 I art     : --- WEIRD: removing null entry 246
09-01 11:01:08.423  4407  4407 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-01 11:01:08.423  4407  4407 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-01 11:01:08.425  4407  4407 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-01 11:01:08.426  7068  7068 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-01 11:01:08.427  4407  4407 I art     : System.exit called, status: 0
09-01 11:01:08.427  4407  4407 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-01 11:01:08.451   312  2185 V AudioFlinger: 4407 died, releasing its sessions
09-01 11:01:08.451   312  2185 V AudioFlinger:  pid 1854 @ 0
09-01 11:01:08.451   312  2185 V AudioFlinger:  pid 3219 @ 1
09-01 11:01:08.451   312  2185 V AudioFlinger:  pid 3219 @ 2
09-01 11:01:08.556  1035  1051 I ActivityManager: Process com.android.bluetooth (pid 4407) has died
09-01 11:01:08.557  1035  1051 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-01 11:01:08.567  7068  7068 D DockEventReceiver: finishStartingService: stopping service
09-01 11:01:08.571  7068  7068 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,09-01 11:01:08.576  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:01:08.604  7089  7089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:01:08.616  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:01:08.623  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:08.628  7068  7068 D BluetoothPermissionRequest: onReceive
09-01 11:01:08.631  7161  7192 W FormManager: Network not available. Please check & try again.
,09-01 11:01:08.637  7068  7068 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-01 11:01:08.638  7068  7068 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-01 11:01:08.641  7068  7068 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:01:08.698  1035  1699 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7196 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-01 11:01:08.706  7161  7194 V FormManager: Network unavailable.
09-01 11:01:08.710  7161  7194 V FormManager: Network unavailable.
,09-01 11:01:08.730  1035  1962 I ActivityManager: Killing 6657:com.lge.email/u0a23 (adj 15): empty #17
,09-01 11:01:08.767  1035  2051 W libprocessgroup: failed to open /acct/uid_10023/pid_6657/cgroup.procs: No such file or directory
,09-01 11:01:08.793  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-01 11:01:08.793  7068  7068 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-01 11:01:08.793  7068  7068 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-01 11:01:08.794  7068  7068 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-01 11:01:08.796  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-01 11:01:08.804  7196  7196 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-01 11:01:08.805  7196  7196 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:01:08.806  7196  7196 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-01 11:01:08.807  7196  7196 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-01 11:01:08.818  7068  7068 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:01:08.819  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-01 11:01:08.819  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-01 11:01:08.819  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-01 11:01:08.819  7068  7068 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:01:08.820  7068  7068 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-01 11:01:08.827  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:01:08.828  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:01:08.833  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:01:08.837  7196  7196 D BluetoothAdapterApp: Loading JNI Library
09-01 11:01:08.838  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:01:08.856  7089  7089 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-01 11:01:08.856  7089  7089 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:01:08.856  7089  7089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:01:08.859  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-01 11:01:08.862  4855  7216 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:01:08.862  4855  7215 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-01 11:01:08.866  4855  7216 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:01:08.867  7161  7219 W FormManager: Network not available. Please check & try again.
,09-01 11:01:08.871  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:08.880  7161  7220 V FormManager: Network unavailable.
,09-01 11:01:08.885  7161  7220 V FormManager: Network unavailable.
09-01 11:01:08.886  7196  7196 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@4153b49 Instance Count = 1
09-01 11:01:08.892  7196  7196 D BluetoothAdapterApp: onCreate
09-01 11:01:08.895  7117  7117 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-01 11:01:08.897  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-01 11:01:08.897  7117  7117 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-01 11:01:08.916  7196  7196 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,09-01 11:01:08.917  7196  7196 D ProfileConfigQcom: Adding HeadsetService
09-01 11:01:08.917  7196  7196 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-01 11:01:08.917  7196  7196 D ProfileConfigQcom: Adding A2dpService
09-01 11:01:08.917  7196  7196 D ProfileConfigQcom: [BTUI] HidService is supported
09-01 11:01:08.917  7196  7196 D ProfileConfigQcom: Adding HidService
09-01 11:01:08.918  7196  7196 D ProfileConfigQcom: [BTUI] HealthService is supported
09-01 11:01:08.918  7196  7196 D ProfileConfigQcom: Adding HealthService
09-01 11:01:08.918  7196  7196 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-01 11:01:08.919  7196  7196 D ProfileConfigQcom: [BTUI] PanService is supported
09-01 11:01:08.919  7196  7196 D ProfileConfigQcom: Adding PanService
09-01 11:01:08.920  7196  7196 D ProfileConfigQcom: [BTUI] GattService is supported
09-01 11:01:08.920  7196  7196 D ProfileConfigQcom: Adding GattService
09-01 11:01:08.920  7196  7196 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-01 11:01:08.920  7196  7196 D ProfileConfigQcom: Adding BluetoothMapService
09-01 11:01:08.921  7196  7196 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-01 11:01:08.922  7196  7196 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-01 11:01:08.928  7068  7068 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-01 11:01:08.931  7196  7196 V LGMDMManagerInternal: Create singleton instance
,09-01 11:01:08.942  7117  7117 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:01:08.942  7117  7117 D LgDataFeature: LgDataFeature() Constructor Done, null
09-01 11:01:08.951  7117  7117 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,09-01 11:01:08.952  7117  7117 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-01 11:01:08.952  7117  7117 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-01 11:01:08.952  7117  7117 V SoundPool: doLoad: loading sample sampleID=1
09-01 11:01:08.953  7117  7117 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-01 11:01:08.958  6808  6808 D UEI.SmartControl: QS Service created
09-01 11:01:08.959  7117  7117 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-01 11:01:08.959  7117  7224 V SoundPool: Start decode
09-01 11:01:08.959  7117  7224 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-01 11:01:08.960   312  2186 V MediaPlayerService: decode(22, 10857164, 17813)
09-01 11:01:08.960   312  2186 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-01 11:01:08.960   312  2186 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-01 11:01:08.960   312  2186 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-01 11:01:08.960   312  2186 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-01 11:01:08.960   312  2186 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-01 11:01:08.960   312  2186 V MediaPlayerService: player type = 3
09-01 11:01:08.960   312  2186 V AwesomePlayer: AwesomePlayer create()
09-01 11:01:08.961   312  2186 V AwesomePlayer: reset_l() 
09-01 11:01:08.961   312  2186 V AwesomePlayer: cancelPlayerEvents
09-01 11:01:08.961   312  2186 V AwesomePlayer: setAudioSink() 
09-01 11:01:08.961   312  2186 V AwesomePlayer: reset_l() 
09-01 11:01:08.961   312  2186 V AudioCache: notify(0xb5474a80, 8, 0, 0)
09-01 11:01:08.961   312  2186 V AudioCache: ignored
09-01 11:01:08.961   312  2186 V AwesomePlayer: cancelPlayerEvents
09-01 11:01:08.961   312  2186 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-01 11:01:08.961   312  2186 V AwesomePlayer: setDataSource_l dataSource
09-01 11:01:08.961   312  2186 V LGParserOSAL: SniffLGParser start
09-01 11:01:08.961   312  2186 V LGParserOSAL: MainType:5, SubType=0
09-01 11:01:08.961   312  2186 V LGParserOSAL: #### check Mime : application/ogg
09-01 11:01:08.961   312  2186 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-01 11:01:08.961   312  2186 E MediaExtractor: Use LGExtractor :application/ogg 
09-01 11:01:08.963  7117  7117 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-01 11:01:08.964  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,09-01 11:01:08.992  7117  7117 V LGMDMManager: Create singleton instance
09-01 11:01:08.995  6808  6808 I UEI.SmartControl: Service initServices...
09-01 11:01:08.995  6808  6808 D UEI.SmartControl: QS start get config
,09-01 11:01:09.003   312  2186 V LGParserOSAL: supported mime: application/ogg
09-01 11:01:09.003   312  2186 V AwesomePlayer: setDataSource_l() extractor countTracks=1
,09-01 11:01:09.003   312  2186 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-01 11:01:09.003   312  2186 V AwesomePlayer: mBitrate = -1 bits/sec
09-01 11:01:09.004   312  2186 V AwesomePlayer: AudioTrack Setting
09-01 11:01:09.004   312  2186 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-01 11:01:09.004   312  2186 V AwesomePlayer: setAudioSource() 
09-01 11:01:09.004   312  2186 V MediaPlayerService: prepare
09-01 11:01:09.004   312  2186 V AwesomePlayer: prepareAsync_l() 
09-01 11:01:09.004   312  2186 V MediaPlayerService: wait for prepare
09-01 11:01:09.004   312  7225 V AwesomePlayer: onPrepareAsyncEvent() 
09-01 11:01:09.004   312  7225 V AwesomePlayer: initAudioDecoder() 
09-01 11:01:09.004   312  7225 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-01 11:01:09.004   312  7225 V AudioSystem: isOffloadSupported()
09-01 11:01:09.004   312  7225 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-01 11:01:09.004   312  7225 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-01 11:01:09.004   312  7225 I AudioFlinger: isAudioPlaybackHookOn() false
09-01 11:01:09.004   312  7225 V AwesomePlayer: getUseOffload() = 0 
09-01 11:01:09.004   312  7225 V OMXCodec: OMXCodec::Create
09-01 11:01:09.004   312  7225 V OMXCodec: findMatchingCodecs()
09-01 11:01:09.004   312  7225 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-01 11:01:09.004   312  7225 V OMXCodec: matchingCodecs.size()=1
09-01 11:01:09.004   312  7225 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-01 11:01:09.006   312  7225 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-01 11:01:09.006   312  7225 V LGCodecAdapter: LG Codec Adapter start
09-01 11:01:09.006   312  7225 V OMXCodec: OMXCodec Createtor
09-01 11:01:09.006   312  7225 V OMXCodec: setComponentRole
09-01 11:01:09.006   312  7225 V OMXCodec: configureCodec protected=0
09-01 11:01:09.006   312  7225 V LGCodecAdapter: called getLGCodecSpecificData
09-01 11:01:09.006   312  7225 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-01 11:01:09.006   312  7225 V LGCodecOSAL: Called LGconfigureCodecMETA
09-01 11:01:09.006   312  7225 V LGCodecOSAL: Called LGconfigureCodecMSG
09-01 11:01:09.006   312  7225 V LGCodecOSAL: Not support LGCodec
09-01 11:01:09.007   312  7225 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-01 11:01:09.007   312  7225 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-01 11:01:09.007   312  7225 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-01 11:01:09.007   312  7225 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-01 11:01:09.007   312  7225 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-01 11:01:09.007   312  7225 V AudioSystem: isOffloadSupported()
09-01 11:01:09.007   312  7225 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-01 11:01:09.007   312  7225 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-01 11:01:09.007   312  7225 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-01 11:01:09.007   312  7225 V OMXCodec: init()
09-01 11:01:09.007   312  7225 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-01 11:01:09.007   312  7225 V OMXCodec: allocateBuffers
09-01 11:01:09.007   312  7225 V OMXCodec: allocateBuffersOnPort portIndex=0
09-0,1 11:01:09.007   312  7225 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-01 11:01:09.007   312  7225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
09-01 11:01:09.007   312  7225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
09-01 11:01:09.007   312  7225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
09-01 11:01:09.007   312  7225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
09-01 11:01:09.007   312  7225 V OMXCodec: allocateBuffersOnPort portIndex=1
09-01 11:01:09.007   312  7225 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-01 11:01:09.008   312  7225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
09-01 11:01:09.008   312  7225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
09-01 11:01:09.008   312  7225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
09-01 11:01:09.008   312  7225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c2060 on output port
09-01 11:01:09.008   312  7225 V OMXCodec: init() mAsyncCompletion wait!!! 
09-01 11:01:09.008   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-01 11:01:09.008   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-01 11:01:09.008   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-01 11:01:09.008   312  7225 V OMXCodec: init() mAsyncCompletion wait!!! 
09-01 11:01:09.008   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-01 11:01:09.008   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-01 11:01:09.008   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-01 11:01:09.008   312  7225 V OMXCodec: init() mAsyncCompletion wait free! 
09-01 11:01:09.008   312  7225 V AwesomePlayer: finishAsyncPrepare_l() 
09-01 11:01:09.008   312  7225 V AudioCache: notify(0xb5474a80, 5, 0, 0)
09-01 11:01:09.008   312  7225 V AudioCache: ignored
09-01 11:01:09.008   312  7225 V AudioCache: notify(0xb5474a80, 1, 0, 0)
09-01 11:01:09.008   312  7225 V AudioCache: prepared
09-01 11:01:09.009   312  2186 V AudioCache: wait - success
09-01 11:01:09.009   312  2186 V MediaPlayerService: start
09-01 11:01:09.009   312  2186 V AwesomePlayer: play_l() 
09-01 11:01:09.009   312  2186 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-01 11:01:09.009   312  2186 V AwesomePlayer: createAudioPlayer_l
09-01 11:01:09.009   312  2186 V AwesomePlayer: seekAudioIfNecessary_l() 
,09-01 11:01:09.009   312  2186 V AwesomePlayer: startAudioPlayer_l() 
09-01 11:01:09.009   312  2186 D AudioPlayer: start of Playback, useOffload 0
09-01 11:01:09.009   312  2186 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-01 11:01:09.009   312  2186 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-01 11:01:09.011   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-01 11:01:09.011   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-01 11:01:09.011   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-01 11:01:09.011   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-01 11:01:09.012   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-01 11:01:09.012   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,09-01 11:01:09.012   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
09-01 11:01:09.012   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:01:09.012   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
09-01 11:01:09.012   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:01:09.012   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
09-01 11:01:09.012   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:01:09.012   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044810848
09-01 11:01:09.012   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:01:09.012   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,09-01 11:01:09.012   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-01 11:01:09.012   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-01 11:01:09.012   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-01 11:01:09.012   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-01 11:01:09.013   312  7227 V OMXCodec: allocateBuffersOnPort portIndex=1
09-01 11:01:09.013   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-01 11:01:09.013   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
09-01 11:01:09.013   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
09-01 11:01:09.013   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
,09-01 11:01:09.013   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on output port
09-01 11:01:09.013   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-01 11:01:09.013   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-01 11:01:09.015   312  2186 V AudioCache: open(48000, 2, 0x0, 1, 4)
,09-01 11:01:09.022   312  2186 V AudioCache: notify(0xb5474a80, 6, 0, 0)
09-01 11:01:09.022   312  2186 V AudioCache: ignored
09-01 11:01:09.022   312  2186 V MediaPlayerService: wait for playback complete
09-01 11:01:09.025   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.025   312  7228 V AudioCache: memcpy(0xaf0f9000, 0xb16b3000, 4096)
09-01 11:01:09.027   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.027   312  7228 V AudioCache: memcpy(0xaf0fa000, 0xb16b3000, 4096)
09-01 11:01:09.027   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.027   312  7228 V AudioCache: memcpy(0xaf0fb000, 0xb16b3000, 4096)
09-01 11:01:09.027   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.027   312  7228 V AudioCache: memcpy(0xaf0fc000, 0xb16b3000, 4096)
09-01 11:01:09.028   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.028   312  7228 V AudioCache: memcpy(0xaf0fd000, 0xb16b3000, 4096)
09-01 11:01:09.029   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.029   312  7228 V AudioCache: memcpy(0xaf0fe000, 0xb16b3000, 4096)
,09-01 11:01:09.030   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.030   312  7228 V AudioCache: memcpy(0xaf0ff000, 0xb16b3000, 4096)
09-01 11:01:09.031   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.031   312  7228 V AudioCache: memcpy(0xaf100000, 0xb16b3000, 4096)
09-01 11:01:09.032   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.032   312  7228 V AudioCache: memcpy(0xaf101000, 0xb16b3000, 4096)
09-01 11:01:09.033   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.033   312  7228 V AudioCache: memcpy(0xaf102000, 0xb16b3000, 4096)
09-01 11:01:09.033   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.033   312  7228 V AudioCache: memcpy(0xaf103000, 0xb16b3000, 4096)
09-01 11:01:09.034   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.034   312  7228 V AudioCache: memcpy(0xaf104000, 0xb16b3000, 4096)
09-01 11:01:09.035   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.035   312  7228 V AudioCache: memcpy(0xaf105000, 0xb16b3000, 4096)
09-01 11:01:09.035   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.035   312  7228 V AudioCache: memcpy(0xaf106000, 0xb16b3000, 4096)
09-01 11:01:09.036   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.036   312  7228 V AudioCache: memcpy(0xaf107000, 0xb16b3000, 4096)
09-01 11:01:09.037   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.037   312  7228 V AudioCache: memcpy(0xaf108000, 0xb16b3000, 4096)
09-01 11:01:09.037   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.037   312  7228 V AudioCache: memcpy(0xaf109000, 0xb16b3000, 4096)
09-01 11:01:09.038   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.038   312  7228 V AudioCache: memcpy(0xaf10a000, 0xb16b3000, 4096)
09-01 11:01:09.039   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.039   312  7228 V AudioCache: memcpy(0xaf10b000, 0xb16b3000, 4096)
09-01 11:01:09.039   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.039   312  7228 V AudioCache: memcpy(0xaf10c000, 0xb16b3000, 4096)
09-01 11:01:09.040   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.040   312  7228 V AudioCache: memcpy(0xaf10d000, 0xb16b3000, 4096)
09-01 11:01:09.040   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.041   312  7228 V AudioCache: memcpy(0xaf10e000, 0xb16b3000, 4096)
09-01 11:01:09.041  7196  7196 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:09.041   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.041   312  7228 V AudioCache: memcpy(0xaf10f000, 0xb16b3000, 4096)
09-01 11:01:09.042   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.042   312  7228 V AudioCache: memcpy(0xaf110000, 0xb16b3000, 4096)
,09-01 11:01:09.043   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.043   312  7228 V AudioCache: memcpy(0xaf111000, 0xb16b3000, 4096)
09-01 11:01:09.044   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.044   312  7228 V AudioCache: memcpy(0xaf112000, 0xb16b3000, 4096)
09-01 11:01:09.044   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.044   312  7228 V AudioCache: memcpy(0xaf113000, 0xb16b3000, 4096)
09-01 11:01:09.044  7196  7196 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:01:09.044  7196  7196 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:01:09.044  7196  7196 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:01:09.045   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.045   312  7228 V AudioCache: memcpy(0xaf114000, 0xb16b3000, 4096)
09-01 11:01:09.045   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.045   312  7228 V AudioCache: memcpy(0xaf115000, 0xb16b3000, 4096)
09-01 11:01:09.045  7196  7196 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:09.046  7196  7196 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-01 11:01:09.046   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.046   312  7228 V AudioCache: memcpy(0xaf116000, 0xb16b3000, 4096)
09-01 11:01:09.046   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.046   312  7228 V AudioCache: memcpy(0xaf117000, 0xb16b3000, 4096)
09-01 11:01:09.046   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.046   312  7228 V AudioCache: memcpy(0xaf118000, 0xb16b3000, 4096)
09-01 11:01:09.049   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.049   312  7228 V AudioCache: memcpy(0xaf119000, 0xb16b3000, 4096)
09-01 11:01:09.049   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.049   312  7228 V AudioCache: memcpy(0xaf11a000, 0xb16b3000, 4096)
09-01 11:01:09.050   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.050   312  7228 V AudioCache: memcpy(0xaf11b000, 0xb16b3000, 4096)
09-01 11:01:09.050   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.050   312  7228 V AudioCache: memcpy(0xaf11c000, 0xb16b3000, 4096)
09-01 11:01:09.050   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.050   312  7228 V AudioCache: memcpy(0xaf11d000, 0xb16b3000, 4096)
09-01 11:01:09.051   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.051   312  7228 V AudioCache: memcpy(0xaf11e000, 0xb16b3000, 4096)
09-01 11:01:09.051   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.051   312  7228 V AudioCache: memcpy(0xaf11f000, 0xb16b3000, 4096)
09-01 11:01:09.051   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.051   312  7228 V AudioCache: memcpy(0xaf120000, 0xb16b3000, 4096)
09-01 11:01:09.052  7134  7134 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-01 11:01:09.052   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.052   312  7228 V AudioCache: memcpy(0xaf121000, 0xb16b3000, 4096)
09-01 11:01:09.052   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.052   312  7228 V AudioCache: memcpy(0xaf122000, 0xb16b3000, 4096)
09-01 11:01:09.052   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.052   312  7228 V AudioCache: memcpy(0xaf123000, 0xb16b3000, 4096)
09-01 11:01:09.053   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.053   312  7228 V AudioCache: memcpy(0xaf124000, 0xb16b3000, 4096)
09-01 11:01:09.053   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.053   312  7228 V AudioCache: memcpy(0xaf125000, 0xb16b3000, 4096)
09-01 11:01:09.053   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.054   312  7228 V AudioCache: memcpy(0xaf126000, 0xb16b3000, 4096)
09-01 11:01:09.054   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.054   312  7228 V AudioCache: memcpy(0xaf127000, 0xb,16b3000, 4096)
09-01 11:01:09.054   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.054   312  7228 V AudioCache: memcpy(0xaf128000, 0xb16b3000, 4096)
09-01 11:01:09.055   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.055   312  7228 V AudioCache: memcpy(0xaf129000, 0xb16b3000, 4096)
09-01 11:01:09.055   312  7228 V AudioCache: write(0xb16b3000, 4096)
09-01 11:01:09.055   312  7228 V AudioCache: memcpy(0xaf12a000, 0xb16b3000, 4096)
09-01 11:01:09.055   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-01 11:01:09.055   312  7228 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-01 11:01:09.055   312  7228 V AwesomePlayer: postAudioEOS() 
09-01 11:01:09.055   312  7228 V AudioCache: write(0xb16b3000, 280)
09-01 11:01:09.055   312  7228 V AudioCache: memcpy(0xaf12b000, 0xb16b3000, 280)
,09-01 11:01:09.057   312  7225 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-01 11:01:09.057   312  7225 V AwesomePlayer: onStreamDone
09-01 11:01:09.057   312  7225 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-01 11:01:09.057   312  7225 V AudioCache: notify(0xb5474a80, 2, 0, 0)
09-01 11:01:09.057   312  7225 V AudioCache: playback complete
09-01 11:01:09.057   312  7225 V AwesomePlayer: pause_l() 
09-01 11:01:09.057   312  7225 V AudioCache: notify(0xb5474a80, 7, 0, 0)
09-01 11:01:09.057   312  7225 V AudioCache: ignored
09-01 11:01:09.057   312  7225 V AwesomePlayer: cancelPlayerEvents
09-01 11:01:09.057   312  2186 V AudioCache: wait - success
09-01 11:01:09.057   312  2186 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-01 11:01:09.057   312  7225 D AudioPlayer: Pause Playback at 1068125
09-01 11:01:09.057   312  2186 V AwesomePlayer: reset_l() 
09-01 11:01:09.057   312  2186 V AudioCache: notify(0xb5474a80, 8, 0, 0)
09-01 11:01:09.057   312  2186 V AudioCache: ignored
09-01 11:01:09.057   312  2186 V AwesomePlayer: cancelPlayerEvents
09-01 11:01:09.057   312  2186 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-01 11:01:09.057   312  2186 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-01 11:01:09.057   312  2186 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-01 11:01:09.057   312  2186 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-01 11:01:09.057   312  2186 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 1
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-01 11:01:09.058   312  2186 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-01 11:01:09.058   312  2186 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-01 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-01, 11:01:09.058   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-01 11:01:09.059   312  7227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-01 11:01:09.059   312  2186 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-01 11:01:09.059   312  2186 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-01 11:01:09.059   312  2186 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-01 11:01:09.059   312  2186 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-01 11:01:09.060   312  2186 D AudioPlayer: AudioPlayer releasing audio source
09-01 11:01:09.060   312  2186 D AudioPlayer: AudioPlayer done releasing audio source
09-01 11:01:09.060   312  2186 V AwesomePlayer: reset_l() 
09-01 11:01:09.060   312  2186 V AwesomePlayer: cancelPlayerEvents
09-01 11:01:09.060   312  2186 V AwesomePlayer: ~AwesomePlayer call
09-01 11:01:09.060   312  2186 V AwesomePlayer: reset_l() 
09-01 11:01:09.060   312  2186 V AwesomePlayer: cancelPlayerEvents
09-01 11:01:09.060  7117  7224 V SoundPool: close(31)
09-01 11:01:09.060  7117  7224 V SoundPool: pointer = 0x9ffe8000, size = 205080, sampleRate = 48000, numChannels = 2
09-01 11:01:09.088  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-01 11:01:09.088  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,09-01 11:01:09.090  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3229
09-01 11:01:09.275  6808  6808 I UEI.SmartControl: Supports setup maps: true
,09-01 11:01:09.278  6808  6808 D UEI.SmartControl: QS start statue = true Error code = 0
09-01 11:01:09.278  6808  6808 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-01 11:01:09.278  6808  6808 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-01 11:01:09.278  6808  6808 I UEI.SmartControl: ### init IR Blaster...
09-01 11:01:09.282  6808  6808 D serial_port: Configuring serial port
09-01 11:01:09.282  6808  6808 E UEI.SmartControl: UEIBLaster setting for 616
09-01 11:01:09.282  6808  6808 I UEI.SmartControl: Setting serial record hearder size = 2
09-01 11:01:09.282  6808  6808 I UEI.SmartControl: configuring settings for MAXQ616
09-01 11:01:09.282  6808  6808 I UEI.SmartControl: Get version...
09-01 11:01:09.301  6808  7230 D UEI.SmartControl: serial port data available: 21
,09-01 11:01:09.327  6808  6808 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-01 11:01:09.327  6808  6808 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-01 11:01:09.328  6808  6808 I UEI.SmartControl: QS saving settings...
09-01 11:01:09.330  6808  6808 D UEI.SmartControl: IR Blaster version: 25672567
,09-01 11:01:09.347  6808  7230 D UEI.SmartControl: serial port data available: 4
,09-01 11:01:09.380  6808  6808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-01 11:01:09.387  6808  6808 E UEI.SmartControl: Services init done
,09-01 11:01:09.387  6808  6808 D UEI.SmartControl: QS Service init finished
09-01 11:01:09.388  6808  6808 D UEI.SmartControl: QS Service version name: 2.1.91
09-01 11:01:09.389  6808  6808 D UEI.SmartControl: QS Service version code: 201091
09-01 11:01:09.389  6808  6808 D UEI.SmartControl: Service requested: Control
09-01 11:01:09.392  6808  7239 I UEI.SmartControl: Device manager: loading config....
09-01 11:01:09.392  6808  7239 D UEI.SmartControl: ----------- loading internal config...
09-01 11:01:09.394  6808  6808 D UEI.SmartControl: Internal service binding...
09-01 11:01:09.395  7117  7117 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-01 11:01:09.397  6808  6824 I UEI.SmartControl: ------ IControl API: 11
,09-01 11:01:09.399  6808  6824 D UEI.SmartControl: File observer start...
09-01 11:01:09.400  6808  6824 E UEI.SmartControl: IR Port is disabled: false
09-01 11:01:09.400  6808  7239 E UEI.SmartControl: Loading SETTINGS...
09-01 11:01:09.400  6808  6824 D UEI.SmartControl: Starting file observer...
09-01 11:01:09.401  6808  6824 I UEI.SmartControl: Registering callback...
09-01 11:01:09.402  6808  6823 I UEI.SmartControl: ------ IControl API: 19
09-01 11:01:09.403  6808  6823 I UEI.SmartControl: Registering Services Ready callback...
09-01 11:01:09.405  6808  7239 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-01 11:01:09.411  6808  7238 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-01 11:01:09.412  7117  7132 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-01 11:01:09.412  6808  7238 D UEI.SmartControl: -----service ready thread exits
09-01 11:01:09.414  7117  7222 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-01 11:01:09.414  7117  7222 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-01 11:01:09.415  7117  7117 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-01 11:01:09.416  7117  7117 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-01 11:01:09.416  6808  6824 I UEI.SmartControl: ------ IControl API: 8
09-01 11:01:09.418  7117  7117 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-01 11:01:09.418  7117  7117 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-01 11:01:09.418  7117  7117 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-01 11:01:09.419  7117  7117 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-01 11:01:09.420  7117  7117 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-01 11:01:09.420  7117  7117 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-01 11:01:09.422  7117  7117 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-01 11:01:09.424  7117  7117 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-01 11:01:09.425  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-01 11:01:09.427  7117  7117 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-01 11:01:09.428  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-01 11:01:09.428  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-01 11:01:09.430  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-01 11:01:09.430  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-01 11:01:09.431  7117  7117 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472720469431]
09-01 11:01:09.434  7117  7117 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-01 11:01:09.436  1035  1938 I ActivityManager: Killing 6690:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-01 11:01:09.459  7117  7241 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-01 11:01:09.476  1035  1938 I ActivityManager: Killing 6168:com.android.gallery3d/u0a27 (adj 15): empty #18
,09-01 11:01:09.505  1035  1967 W libprocessgroup: failed to open /acct/uid_10061/pid_6690/cgroup.procs: No such file or directory
,09-01 11:01:09.518  1035  1995 W libprocessgroup: failed to open /acct/uid_10027/pid_6168/cgroup.procs: No such file or directory
,09-01 11:01:09.520  7117  7117 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-01 11:01:09.526  7117  7117 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-01 11:01:09.528  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-01 11:01:09.528  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-01 11:01:09.529  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,09-01 11:01:09.530  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-01 11:01:09.531  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-01 11:01:09.544  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-01 11:01:10.314  1035  2051 D WifiServiceImplEx: setWifiEnabled: true pid=6931, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-01 11:01:10.321  1035  1501 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:10.327  1035  2051 D WifiService: setWifiEnabled: true pid=6931, uid=10118
09-01 11:01:10.327  1035  2051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-01 11:01:10.331  1035  1105 D Tethering: MasterInitialState.processMessage what=3
,09-01 11:01:10.344  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:01:10.347  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:10.351  1035  1501 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:10.352  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:10.357  1035  1105 D Tethering: MasterInitialState.processMessage what=3
,09-01 11:01:10.366  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:10.367  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:10.369  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-01 11:01:10.376  1035  1440 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-01 11:01:10.376  1035  1440 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-01 11:01:10.379  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:01:10.380  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:01:10.380  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-01 11:01:10.382  1035  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-01 11:01:10.382  1035  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-01 11:01:10.382  1035  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-01 11:01:10.382  1035  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-01 11:01:10.382  1035  1440 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-01 11:01:10.382  1035  1440 E WifiHW  : unknown target_country: EU , set to default
09-01 11:01:10.382  1035  1440 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-01 11:01:10.382  1035  1440 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-01 11:01:10.382  1035  1440 I WifiUtil: gEnableBmps=1
09-01 11:01:10.384  5893  5893 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-01 11:01:10.401  6563  7088 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-01 11:01:10.409  5893  5893 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-01 11:01:10.442  2081  2081 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:01:10.482  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:01:10.524  1035  1938 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7258 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-01 11:01:10.526  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:10.526  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:10.547   343   343 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 189us total 23.881ms
,09-01 11:01:10.558   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 9.014ms
09-01 11:01:10.568   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 181us total 9.126ms
,09-01 11:01:10.583  7258  7258 I AppUp4:AppBoxCP: onCreate
,09-01 11:01:10.584  7258  7258 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-01 11:01:10.592  7258  7258 I AppUp4:DB:  setFingerPrint start
,09-01 11:01:10.593  7258  7258 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-01 11:01:10.600  7258  7258 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-01 11:01:10.600  7258  7258 I AppUp4:DB:  SDK version = 21
09-01 11:01:10.600  7258  7258 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-01 11:01:10.602  7258  7258 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-01 11:01:10.603  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-01 11:01:10.603  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:10.605  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-01 11:01:10.605  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-01 11:01:10.610  7258  7258 I AppUp4:CustModeStarterReceiver: onReceive
09-01 11:01:10.648  7258  7258 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:01:10.648  7258  7258 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:01:10.658  7258  7258 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@fa7958b
09-01 11:01:10.658  7258  7258 D AppUp4:CustFacade: isCustomizationCompleted : false
09-01 11:01:10.659  7258  7258 D AppUp4:CustFacade: isPhone : true
09-01 11:01:10.660  7258  7258 D AppUp4:CustModeStarterReceiver: begin check event
,09-01 11:01:10.661  7258  7258 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-01 11:01:10.662  7258  7258 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-01 11:01:10.664  7258  7279 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-01 11:01:10.664  7258  7279 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-01 11:01:10.664  7258  7279 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-01 11:01:10.670  1035  1995 I ActivityManager: Killing 6717:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-01 11:01:10.730  1035  2033 W libprocessgroup: failed to open /acct/uid_10080/pid_6717/cgroup.procs: No such file or directory
,09-01 11:01:10.732  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:10.733  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:01:10.742  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:01:10.747  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-01 11:01:10.754  4855  7283 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-01 11:01:10.760  4855  7284 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:01:10.761  4855  7284 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:01:10.817  1035  1699 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7285 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-01 11:01:10.907  7285  7285 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:01:10.908  7285  7285 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:01:10.910  7285  7285 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-01 11:01:10.910  7285  7285 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-01 11:01:11.047  7285  7285 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-01 11:01:11.065  7285  7285 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-01 11:01:11.106  7285  7285 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-01 11:01:11.155  7285  7285 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:01:11.155  7285  7285 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:01:11.199  1035  1105 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-01 11:01:11.199  1035  1105 D Tethering: InitialState.processMessage what=4
,09-01 11:01:11.203   308   891 D SoftapController: Softap fwReload - Ok
09-01 11:01:11.205  1035  1440 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (815ms)
09-01 11:01:11.207   308   891 D CommandListener: Setting iface cfg
09-01 11:01:11.207   308   891 D CommandListener: Trying to bring down wlan0
09-01 11:01:11.209  1035  1105 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-01 11:01:11.209   308   891 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:01:11.213  1035  1440 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-01 11:01:11.217  1035  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:01:11.217  1035  1440 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:01:11.217  1035  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-01 11:01:11.222  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-01 11:01:11.209  7317  7317 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:11.209  7317  7317 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:11.223  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:11.230  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-01 11:01:11.234  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:11.235  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:11.239  1035  1440 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-01 11:01:11.239  1035  1440 D WifiMonitor: connecting to supplicant
09-01 11:01:11.263  7317  7317 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-01 11:01:11.295  7317  7317 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-01 11:01:11.295  7317  7317 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-01 11:01:11.358  7285  7285 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-01 11:01:11.381  7317  7317 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-01 11:01:11.402  3219  3219 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-01 11:01:11.402  3219  3219 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:11.402  3219  3219 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-01 11:01:11.411  7285  7285 I HubEmail: JNI_OnLoad()
09-01 11:01:11.411  7285  7285 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-01 11:01:11.411  7285  7285 I HubEmail: registerNatives()
09-01 11:01:11.411  7285  7285 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-01 11:01:11.411  7285  7285 I HubEmail: registerNativeMethods()
09-01 11:01:11.411  7285  7285 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-01 11:01:11.411  7285  7285 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-01 11:01:11.418  7317  7317 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-01 11:01:11.425  7317  7317 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-01 11:01:11.425  1035  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-01 11:01:11.426  1035  1440 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-01 11:01:11.426  1035  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-01 11:01:11.427  1035  1440 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-01 11:01:11.427  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-01 11:01:11.427  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-01 11:01:11.427  1035  7336 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-01 11:01:11.427  1035  7336 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-01 11:01:11.427  1035  1440 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:11.427  1035  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:11.428  1035  1440 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-01 11:01:11.428  1035  1440 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,09-01 11:01:11.428  1035  1440 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-01 11:01:11.429  1035  1440 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-01 11:01:11.429  1035  1440 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-01 11:01:11.458  1035  2031 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7337 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
09-01 11:01:11.459  7161  7331 W FormManager: Network not available. Please check & try again.
,09-01 11:01:11.463  1035  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:01:11.463  1035  1440 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:01:11.463  1035  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:01:11.463  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:11.463  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:11.463  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:11.463  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:11.464  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:01:11.464  1035  1440 D WifiNative-wlan0: doBoolean: SET update_config 1
09-01 11:01:11.464  7285  7335 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:11.464  1035  1440 D WifiNative-wlan0: SET update_config 1: returned true
09-01 11:01:11.464  1035  1440 D WifiConfigStore: Loading config and enabling all networks 
09-01 11:01:11.465  1035  1440 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-01 11:01:11.465  1035  1440 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,09-01 11:01:11.467  1941  1941 D WfdService: Waiting for WifiP2p enabling
09-01 11:01:11.469  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:11.472  1035  1440 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-01 11:01:11.474  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:11.474  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:11.474  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:11.474  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:11.474  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:11.474  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:01:11.474  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:11.474  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:11.474  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:01:11.474  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:11.474  6931  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:01:11.476  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-01 11:01:11.477  1035  1469 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,09-01 11:01:11.480  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:11.480  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:11.480  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:11.480  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:11.480  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:11.480  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:01:11.480  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:11.480  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:11.480  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:01:11.480  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:11.480  6931  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:01:11.482  7161  7333 V FormManager: Network unavailable.
09-01 11:01:11.485  7161  7333 V FormManager: Network unavailable.
09-01 11:01:11.486  1035  1440 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-01 11:01:11.486  1035  1440 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-01 11:01:11.487  1035  1440 D WifiStateMachine: enableVerboseLogging : level 2
09-01 11:01:11.487  1035  1440 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-01 11:01:11.488  1035  1440 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-01 11:01:11.488  1035  1440 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-01 11:01:11.488  1035  1440 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-01 11:01:11.488  1035  1440 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-01 11:01:11.488  1035  1440 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-01 11:01:11.489  1035  1440 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-01 11:01:11.489  1035  1440 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-01 11:01:11.489  1035  1440 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-01 11:01:11.489  1035  1440 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-01 11:01:11.489  1035  1440 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-01 11:01:11.490  1035  1440 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-01 11:01:11.490  1035  1440 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-01 11:01:11.490  1035  1440 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-01 11:01:11.491  1035  1440 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 11:01:11.491  1035  1440 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,09-01 11:01:11.491  1035  1440 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-01 11:01:11.491  1035  1440 D WifiNative-HAL: Setting external_sim to 1
09-01 11:01:11.491  1035  1440 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-01 11:01:11.492  1035  1440 D WifiNative-wlan0: SET external_sim 1: returned true
09-01 11:01:11.492  1035  1440 I WifiNative-HAL: startHal
09-01 11:01:11.492  1035  1440 D wifi    : setting scan oui 0xaf7708a0
09-01 11:01:11.492  1035  1440 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 11:01:11.492  1035  1440 I WifiNative-HAL: startHal
09-01 11:01:11.492  1035  1440 D wifi    : setting scan oui 0xaf7708a0
09-01 11:01:11.492  1035  1440 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-01 11:01:11.493  1035  1440 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-01 11:01:11.493  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-01 11:01:11.493  7317  7317 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-01 11:01:11.493  1941  1941 D WfdsService: Supplicant Connection state is changed : true
09-01 11:01:11.493  1035  1440 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-01 11:01:11.493  1941  2209 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-01 11:01:11.494  1941  2209 D WfdsService: Set the WFDS Monitor: true
09-01 11:01:11.494  1941  2209 D WfdsMonitor: WfdsMonitorThread create
09-01 11:01:11.494  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-01 11:01:11.494  7317  7317 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-01 11:01:11.494  1941  2209 D WfdsMonitor: WFDS Monitor is created and started
09-01 11:01:11.494  1941  2209 D WfdsService: WiFi: Supplicant connection re-established
09-01 11:01:11.494  1035  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-01 11:01:11.494  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-01 11:01:11.494  7317  7317 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-01 11:01:11.495  1035  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-01 11:01:11.495  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-01 11:01:11.495  7317  7317 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-01 11:01:11.495  1941  7352 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-01 11:01:11.496  1035  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-01 11:01:11.496  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-01 11:01:11.496  7317  7317 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-01 11:01:11.496  1941  7352 E CtrlSupplicant: Succeed to open control connection
09-01 11:01:11.496  1035  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-01 11:01:11.496  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-01 11:01:11.496  1941  7352 E CtrlSupplicant: Succeed to open monitor connection
09-01 11:01:11.497  7317  7317 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-01 11:01:11.497  1035  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-01 11:01:11.497  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-01 11:01:11.497  7317  7317 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-01 11:01:11.497  1941  7352 D WfdsMonitor: Supplicant connection established
09-01 11:01:11.498  1941  2209 D WfdsService: Connected to the supplicant for wfds
09-01 11:01:11.498  1035  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-01 11:01:11.499  1035  1440 E WifiNative: : [215,900,510 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-01 11:01:11.499  1035  1440 D WifiNative-wlan0: doBoolean: RECONNECT
09-01 11:01:11.500  1035  1440 D WifiNative-wlan0: RECONNECT: returned true
09-01 11:01:11.500  1035  1440 D WifiNative-wlan0: doString: [STATUS]
09-01 11:01:11.500  1035  7336 D WifiMonito,r: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-01 11:01:11.500  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-01 11:01:11.501  1035  1440 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-01 11:01:11.501  1035  1440 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:01:11.502  1035  1918 I ActivityManager: Killing 6738:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-01 11:01:11.503  1035  1440 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:01:11.503  1035  1391 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:01:11.507   308   891 D CommandListener: Setting iface cfg
09-01 11:01:11.507   308   891 D CommandListener: Trying to bring up p2p0
09-01 11:01:11.507  1035  1391 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-01 11:01:11.507  1035  1391 D LGWifiP2pService: P2pEnablingState
09-01 11:01:11.507  1035  1391 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.507  1035  1391 D LGWifiP2pService: P2p socket connection successful
09-01 11:01:11.507  1035  1391 D LGWifiP2pService: P2pEnabledState
09-01 11:01:11.537  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-01 11:01:11.537  1035  1035 D RttService: SCAN_AVAILABLE : 3
,09-01 11:01:11.537  1035  1440 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-01 11:01:11.538  1035  1440 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-01 11:01:11.538  1035  1440 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-01 11:01:11.539  1035  1440 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-01 11:01:11.539  1035  1440 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-01 11:01:11.539  1035  1559 D RttService: DefaultState got{ when=-3ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.539  1035  1440 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-01 11:01:11.540  1035  1558 D WifiScanningService: DefaultState got{ when=-3ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.540  1035  1558 I WifiNative-HAL: startHal
09-01 11:01:11.540  1035  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf7708a0
09-01 11:01:11.540  1035  1440 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-01 11:01:11.540  1035  1558 D wifi    : failed to get capabilities : -3
09-01 11:01:11.540  1035  1558 E WifiScanningService: could not get scan capabilities
09-01 11:01:11.540  1035  1440 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-01 11:01:11.540  7317  7317 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-01 11:01:11.540  1035  2051 W libprocessgroup: failed to open /acct/uid_10097/pid_6738/cgroup.procs: No such file or directory
09-01 11:01:11.541  1035  1440 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-01 11:01:11.541  1035  1440 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-01 11:01:11.542  1035  1440 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-01 11:01:11.542  1035  1440 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-01 11:01:11.542  7317  7317 E wpa_supplicant: disconnect_rssi_lvl: -100
09-01 11:01:11.542  1035  1391 D LGWifiP2pService: sending p2p connection changed broadcast
09-01 11:01:11.542  1035  1440 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-01 11:01:11.543  1035  1391 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-01 11:01:11.543  1035  1440 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-01 11:01:11.543  1035  1391 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-01 11:01:11.543  1035  1440 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-01 11:01:11.543  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-01 11:01:11.543  1035  1391 D WifiNative-p2p0: doBoolean: SET device_name G3
09-01 11:01:11.544  7317  7317 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-01 11:01:11.545  7317  7317 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:11.545  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-01 11:01:11.545  1941  1941 D WfdsService: WifiP2pState is changed : true
09-01 11:01:11.545  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-01 11:01:11.546  7317  7317 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-01 11:01:11.546  7317  7317 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.546  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:01:11.546  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:11.546  1035  1440 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-01 11:01:11.546  1035  7336 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:11.546  1035  7336 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:11.546  1035  7336 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVE,R type=WORLD]
09-01 11:01:11.546  1035  7336 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.546  1035  7336 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.546  1035  7336 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.546  1941  1941 D WfdsService: isConnected: false
09-01 11:01:11.546  1035  1440 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:01:11.546  7317  7317 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.546  1941  7352 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:01:11.547  1035  1440 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:01:11.547  1941  7352 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:01:11.547  1035  7336 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:01:11.547  1035  7336 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.547  1035  7336 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.547  1035  7336 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.547  1035  1440 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:01:11.547  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-01 11:01:11.547  1941  2209 D WfdsService: Receive the WFDS_ENABLE Method
09-01 11:01:11.547  1941  2209 D WfdsService: Set the WFDS Monitor: true
09-01 11:01:11.547  1941  2209 D WfdsService: Connected to the supplicant for wfds
09-01 11:01:11.547  7317  7317 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-01 11:01:11.547  1941  2209 D WfdsJNI : doCommand: WFDS_SET TRUE
09-01 11:01:11.547  7317  7317 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:01:11.548  7317  7317 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-01 11:01:11.548  1035  1440 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-01 11:01:11.548  1035  1440 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,09-01 11:01:11.548  1941  2209 D WfdsService: selectPreferredScanChannel [36]
09-01 11:01:11.548  1941  2209 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-01 11:01:11.549  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-01 11:01:11.549  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:01:11.549  1035  7336 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:01:11.549  1035  7336 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:01:11.550  1035  1440 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-01 11:01:11.550  1035  1391 D WifiNative-p2p0: SET device_name G3: returned true
09-01 11:01:11.550  1035  1391 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-01 11:01:11.550  1035  1391 D LGWifiP2pService: before postfix = G3
09-01 11:01:11.550  1035  1391 D WifiServerServiceExt: postfix byte check : 2
09-01 11:01:11.550  1035  1391 D LGWifiP2pService: after postfix = G3
09-01 11:01:11.550  1035  1391 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-01 11:01:11.551  1035  1391 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-01 11:01:11.551  1035  1391 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-01 11:01:11.551  1035  1391 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-01 11:01:11.551  1035  1391 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-01 11:01:11.551  1035  1391 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-01 11:01:11.552  1035  1391 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-01 11:01:11.552  1035  1391 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-01 11:01:11.552  1035  1391 D WifiNative-HAL: p2pGetDeviceAddress
09-01 11:01:11.552  1035  1391 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-01 11:01:11.553  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
09-01 11:01:11.553  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-01 11:01:11.553  1035  1391 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-01 11:01:11.554  1035  1391 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-01 11:01:11.554  1941  1941 D WfdsService: Update P2p Interface State: 3
09-01 11:01:11.554  1035  1440 D WifiNative-wlan0: doBoolean: SCAN
09-01 11:01:11.554  1035  1391 D WifiNative-p2p0: P2P_FLUSH: returned true
09-01 11:01:11.554  1035  1391 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-01 11:01:11.555  1035  1440 D WifiNative-wlan0: SCAN: returned false
09-01 11:01:11.555  1035  1391 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-01 11:01:11.555  1035  1391 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-01 11:01:11.556  1035  1391 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-01 11:01:11.556  1035  1391 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-01 11:01:11.556  1035  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=215958  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-01 11:01:11.559  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:11.559  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:11.560  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:11.560  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:11.560  1035  1035 D WifiOffDelay,IfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-01 11:01:11.561  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:11.561  1035  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=215963  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,09-01 11:01:11.563  1035  1440 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:01:11.564  1035  1440 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-01 11:01:11.565  1035  1440 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:01:11.566  1035  1440 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:01:11.567  1035  1440 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:01:11.568  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:01:11.568  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-01 11:01:11.569  1035  1391 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-01 11:01:11.569  1035  1391 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-01 11:01:11.569  1035  1391 D LGWifiP2pService: InactiveState
09-01 11:01:11.569  1035  1391 D LGWifiP2pService: InactiveState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.569  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.569  1035  1391 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-01 11:01:11.570  7317  7317 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-01 11:01:11.570  7317  7317 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:11.570  1035  7336 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:01:11.570  1035  7336 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:11.571  1035  7336 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:11.571  1035  7336 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:11.571  1941  7352 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:01:11.571  7317  7317 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-01 11:01:11.571  7317  7317 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.571  1035  1391 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-01 11:01:11.572  1035  1391 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.572  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.572  7317  7317 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.572  1035  1391 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.572  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.572  1035  1391 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.572  1035  1391 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.572  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.572  1035  1391 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.572  1941  7352 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:01:11.572  1941  7352 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:01:11.572  1035  7336 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:01:11.573  1035  7336 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.573  1035,  7336 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.573  1035  7336 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.573  1035  7336 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:01:11.573  1035  7336 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.573  1035  7336 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.573  1035  7336 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:11.573  1035  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.573  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.573  1035  1391 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.573  1035  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.573  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.573  1035  1391 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:11.573  1941  2209 W WfdsService: DefaultState - msg [9441285] is not handled
09-01 11:01:11.574  1035  1035 E WifiServerServiceExt: No p2p device connected
,09-01 11:01:11.622  7337  7337 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:01:11.622  7337  7337 D LgDataFeature: LgDataFeature() Constructor Done, null
09-01 11:01:11.625  7337  7337 D PhoneMonitor: Register our PhoneStateListener
,09-01 11:01:11.646  7337  7337 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-01 11:01:11.651  7337  7337 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-01 11:01:11.677  7337  7337 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-01 11:01:11.678  7337  7337 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-01 11:01:11.680  7337  7337 D TelephonyAutoProfiling: [parse] Load xml
09-01 11:01:11.687  7337  7337 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-01 11:01:11.688  7337  7337 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-01 11:01:11.688  7337  7337 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-01 11:01:11.688  7337  7337 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-01 11:01:11.688  7337  7337 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-01 11:01:11.688  7337  7337 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-01 11:01:11.688  7337  7337 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-01 11:01:11.689  7337  7337 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-01 11:01:11.689  7337  7337 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-01 11:01:11.689  7337  7337 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-01 11:01:11.689  7337  7337 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-01 11:01:11.689  7337  7337 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-01 11:01:11.689  7337  7337 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-01 11:01:11.689  7337  7337 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-01 11:01:11.689  7337  7337 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-01 11:01:11.690  7337  7337 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-01 11:01:11.690  7337  7337 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-01 11:01:11.692  1035  1938 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7359 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 11:01:11.693  1035  1938 I ActivityManager: Killing 6767:com.lge.eula/1000 (adj 15): empty #17
,09-01 11:01:11.712  7337  7337 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-01 11:01:11.736  1035  1967 W libprocessgroup: failed to open /acct/uid_1000/pid_6767/cgroup.procs: No such file or directory
,09-01 11:01:12.024  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-01 11:01:12.024  1035  7336 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-01 11:01:12.025  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-01 11:01:12.025  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: WPS-AP-AVAILABLE 
,09-01 11:01:12.025  1035  7336 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,09-01 11:01:12.027  7317  7317 E wpa_supplicant: USIM:  scard_init function
09-01 11:01:12.028  7317  7317 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-01 11:01:12.033  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-01 11:01:12.033  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-01 11:01:12.039  1035  1440 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
,09-01 11:01:12.041  1035  1440 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-01 11:01:12.042  1035  1440 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-01 11:01:12.044  1035  1440 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-01 11:01:12.044  1035  1440 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-01 11:01:12.052  1035  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=216454  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-01 11:01:12.054  1035  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=216456  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-01 11:01:12.056  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:12.056  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:12.058  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:01:12.059  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.059  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.059  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-01 11:01:12.066  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.066  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.066  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-01 11:01:12.074  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:01:12.074  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,09-01 11:01:12.078  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-01 11:01:12.078  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:12.081  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:12.104  1035  1995 I art     : Explicit concurrent mark sweep GC freed 81521(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 3.314ms total 198.801ms
,09-01 11:01:12.151  1035  1918 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7387 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-01 11:01:12.152  1035  1918 I ActivityManager: Killing 5727:com.lge.bnr/1000 (adj 15): empty #17
09-01 11:01:12.188  7317  7317 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-01 11:01:12.191  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-01 11:01:12.191  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-01 11:01:12.191  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-01 11:01:12.191  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-01 11:01:12.191  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:01:12.191  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:01:12.191  1035  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=216593  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-01 11:01:12.192  1035  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=216594  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-01 11:01:12.193  1035  1440 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 34 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=216595
09-01 11:01:12.193  1035  1440 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 34 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=216595
09-01 11:01:12.194  1035  1440 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 34 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=216596
09-01 11:01:12.194  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 34 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=216596
09-01 11:01:12.194  1035  1440 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 34 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=216597
09-01 11:01:12.195  1035  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=216597  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-01 11:01:12.197  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:01:12.197  7317  7317 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:01:12.197  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:01:12.197  7317  7317 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:01:12.197  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-01 11:01:12.197  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:01:12.197  1035  7336 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:01:12.197  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-01 11:01:12.198  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:01:12.198  1035  7336 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:01:12.199  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:01:12.199  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:01:12.202  1035  1105 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-01 11:01:12.204  1035  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=216606  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-01 11:01:12.205  1035  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=216607  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-01 11:01:12.205  1035  2051 W libprocessgroup: failed to open /acct/uid_1000/pid_5727/cgroup.procs: No such file or directory
09-01 11:01:12.207  1035  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=216609  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-01 11:01:12.213  1035  1440 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=216615
09-01 11:01:12.214  1035  1440 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=216616
09-01 11:01:12.214  1035  1440 D WifiNative-wlan0: doString: [STATUS]
,09-01 11:01:12.215  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:01:12.215  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:01:12.226  1035  1440 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,09-01 11:01:12.228  1035  1440 I WifiServiceExtension: setVHTCapabilityType  : false
09-01 11:01:12.237  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:12.237  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:12.237  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.237  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.237  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-01 11:01:12.240  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:12.246  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:01:12.246  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.247  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-01 11:01:12.247  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-01 11:01:12.247  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-01 11:01:12.265  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:12.265  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-01 11:01:12.270  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:12.285  1035  1577 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7412 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 11:01:12.290  1035  1577 I ActivityManager: Killing 2255:com.lge.music/u0a34 (adj 15): empty #17
09-01 11:01:12.307  1035  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:01:12.307  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:12.307  1035  1391 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:12.309   312  2185 V AudioFlinger: 2255 died, releasing its sessions
09-01 11:01:12.309   312  2185 V AudioFlinger:  pid 1854 @ 0
09-01 11:01:12.309   312  2185 V AudioFlinger:  pid 3219 @ 1
09-01 11:01:12.309   312  2185 V AudioFlinger:  pid 3219 @ 2
09-01 11:01:12.327  1035  1967 W libprocessgroup: failed to open /acct/uid_10034/pid_2255/cgroup.procs: No such file or directory
,09-01 11:01:12.329  1035  1440 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-01 11:01:12.329  1035  1440 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-01 11:01:12.336  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:12.336  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:12.336  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.336  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.336  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-01 11:01:12.339  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:01:12.340  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.340  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.340  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-01 11:01:12.342  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:12.342  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:12.343  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:12.358  1035  1440 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-01 11:01:12.359  1035  1501 D ConnectivityService: Got NetworkAgent Messenger
09-01 11:01:12.359  1035  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:01:12.359  1035  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-01 11:01:12.359  1035  1501 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-01 11:01:12.359  1035  1501 D ConnectivityService: NetworkAgent connected
,09-01 11:01:12.360  1035  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-01 11:01:12.360  1035  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-01 11:01:12.362  7412  7412 I art     : Almond Protected OAT
09-01 11:01:12.368  1035  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-01 11:01:12.368  1035  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:01:12.368  1035  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-01 11:01:12.368  1035  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-01 11:01:12.368  1035  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-01 11:01:12.373  1035  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-01 11:01:12.374   308   891 D CommandListener: Setting iface cfg
,09-01 11:01:12.378  1035  1440 E WifiStateMachine: Start Dhcp Watchdog 2
,09-01 11:01:12.378  1035  7431 D DhcpStateMachine: StoppedState
,09-01 11:01:12.378  1035  7431 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:12.378  1035  7431 D DhcpStateMachine: WaitBeforeStartState
09-01 11:01:12.378  1035  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=216780  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:01:12.378  1035  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=216780  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:01:12.379  1035  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=216781  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:01:12.379  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:01:12.379  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-01 11:01:12.381  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:01:12.381  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-01 11:01:12.381  1035  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=216783  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:01:12.382  1035  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=216784  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:01:12.382  1035  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=216784  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:01:12.382  1035  1440 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:12.383  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:12.383  1035  1440 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:12.383  1035  1440 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:12.383  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:12.383  1035  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:12.384  1035  1440 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
09-01 11:01:12.384  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-01 11:01:12.384  1035  1440 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-01 11:01:12.384  1035  1440 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-01 11:01:12.385  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-01 11:01:12.385  1035  1440 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-01 11:01:12.386  1035  1440 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:169698] from screen [on:0 period:-453310142] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-01 11:01:12.386  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-453310142] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-01 11:01:12.386  1035  1440 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-01 11:01:12.389  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:12.391  1035  1501 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-01 11:01:12.391  1035  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:12.391  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:12.391  1035  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:12.392  1035  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:12.392  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:12.392  1035  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:12.392  1035  1501 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-01 11:01:12.393  1035  1440 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=166,0,0
09-01 11:01:12.393  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=166,0,0
09-01 11:01:12.393  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-01 11:01:12.393  7317  7317 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-01 11:01:12.396  1035  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-01 11:01:12.396  1035  1440 D WifiNative-wlan0: doBoolean: SET ps 0
09-01 11:01:12.396  1035  1440 D WifiNative-wlan0: SET ps 0: returned true
09-01 11:01:12.396  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-01 11:01:12.396  7317  7317 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-01 11:01:12.396  1035  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-01 11:01:12.396  1035  1440 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-01 11:01:12.396  1035  1440 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-01 11:01:12.396  1035  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2f53f304 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:12.396  1035  1440 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-01 11:01:12.396  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2f53f304 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:12.397  1035  7431 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:12.397  1035  7431 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-01 11:01:12.397   308   891 D CommandListener: Setting iface cfg
09-01 11:01:12.397   308   891 D CommandListener: Trying to bring up wlan0
09-01 11:01:12.398  1035  1440 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-01 11:01:12.399  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:01:12.399  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-01 11:01:12.399  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:01:12.399  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-01 11:01:12.399  1035  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:12.400  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:12.400  1035  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:12.400  1035  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:12.400  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:12.401  1035  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:12.401  1035  1501 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-01 11:01:12.401  1035  1440 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-01 11:01:12.401  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-01 11:01:12.401  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-01 11:01:12.401  1035  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:12.401  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:12.402  7317  7317 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-01 11:01:12.402  1035  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-01 11:01:12.402  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-01 11:01:12.402  7317  7317 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-01 11:01:12.402  1035  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-01 11:01:12.402  1035  1440 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:01:12.419  7412  7412 D WeatherApplication: removeAccount
,09-01 11:01:12.420  7412  7412 D WeatherApplication: Account.length = 0
09-01 11:01:12.420  7412  7412 E WeatherApplication: OPERATOR:OPEN
09-01 11:01:12.420  1035  1440 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:01:12.420  1035  1501 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-01 11:01:12.421  1035  1440 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-01 11:01:12.421  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-01 11:01:12.421  1035  1440 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-01 11:01:12.422  1035  1501 D ConnectivityService: ignoring duplicate network state non-change
09-01 11:01:12.424  7412  7412 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:1:12
09-01 11:01:12.424  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:12.424  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:12.425  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:12.426  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.426  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.426  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-01 11:01:12.428  1035  1501 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-01 11:01:12.428  1035  1501 D ConnectivityService: Adding iface wlan0 to network 101
09-01 11:01:12.429  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.429  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.429  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-01 11:01:12.431  1035  1440 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-01 11:01:12.431  7412  7412 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-01 11:01:12.431  7412  7412 D Weather.Utils: 2 : All the weather widget is gone.
,09-01 11:01:12.433  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-01 11:01:12.437  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-01 11:01:12.438  7412  7412 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-01 11:01:12.441  7412  7412 D WeatherAncestor: connectivity changed - connection : true
09-01 11:01:12.441  7412  7412 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-01 11:01:12.443  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.443  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.443  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-01 11:01:12.445  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:12.445  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:12.446  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:01:12.447  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-01 11:01:12.448  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:12.448  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-01 11:01:12.449  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:12.451  1035  1501 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-01 11:01:12.451  1035  1501 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-01 11:01:12.452  1035  1501 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-01 11:01:12.453   308   891 E Netd    : netlink response contains error (File exists)
09-01 11:01:12.453  1035  1501 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-01 11:01:12.453  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.454  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:12.454  1035  1501 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-01 11:01:12.454  1035  1501 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-01 11:01:12.454  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-01 11:01:12.454  1035  1501 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-01 11:01:12.454  1035  1501 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-01 11:01:12.454  1035  1501 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-01 11:01:12.454  1035  1501 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-01 11:01:12.455  1035  1501 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-01 11:01:12.455  1035  1501 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:01:12.455  1035  1501 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:12.455  1035  1501 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-01 11:01:12.455  1035  7430 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:12.455  1035  7430 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-01 11:01:12.455  1035  1501 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:12.455  1035  1501 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-01 11:01:12.455  1035  7430 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:12.455  1035  1501 D ConnectivityService: currentScore = 0, newScore = 20
09-01 11:01:12.455  1035  1501 D ConnectivityService:    accepting network in place of null
09-01 11:01:12.455  1035  7430 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-01 11:01:12.455  1035  1501 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, ,legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:12.458  1854  1854 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:12.458   308  7436 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-01 11:01:12.458  1035  1440 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:12.458  1035  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-01 11:01:12.460  7412  7412 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-01 11:01:12.460  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-01 11:01:12.460  7412  7412 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-01 11:01:12.460  1035  1501 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-01 11:01:12.460  7412  7412 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-01 11:01:12.460  1035  1501 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-01 11:01:12.460  1035  1501 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:01:12.461  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-01 11:01:12.461  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-01 11:01:12.461  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-01 11:01:12.461  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-01 11:01:12.464  1035  1501 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:12.464  1035  1501 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-01 11:01:12.465  1035  1501 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-01 11:01:12.465  1035  1501 D ConnectivityService: validation of new default Network = false
09-01 11:01:12.465  1035  1501 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-01 11:01:12.465  1035  1501 D DSQN    : enableDataServiceNotify 
09-01 11:01:12.465  1035  1501 D DSQN    : start dsqn bin
09-01 11:01:12.467  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:12.467  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-01 11:01:12.467  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:12.472  1035  1501 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-01 11:01:12.472  1035  1501 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:12.472  1035  1501 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:12.472  1035  1501 D ConnectivityService: sending n,otification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:12.459  7437  7437 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:12.459  7437  7437 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-01 11:01:12.480  1035  1390 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-01 11:01:12.480  1604  2114 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-01 11:01:12.488  7437  7437 E DSQN    : DSQN ssw
,09-01 11:01:12.492  7412  7412 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-01 11:01:12.492  7412  7412 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:1:12
09-01 11:01:12.531   308  7436 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-01 11:01:12.544  1035  1918 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7442 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 11:01:12.546  1035  1918 I ActivityManager: Killing 6190:com.android.vending/u0a44 (adj 15): empty #17
09-01 11:01:12.577   308  7436 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-01 11:01:12.586   308   890 D LGDataListener: argv[0]=dsqncommand
09-01 11:01:12.586   308   890 D LGDataListener: argv[1]=wlan0
09-01 11:01:12.586   308   890 D LGDataListener: argv[2]=1
09-01 11:01:12.586   308   890 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-01 11:01:12.587  1035  1102 D DSQN    : DSQM DsqnNotification wlan0  1
09-01 11:01:12.587  1035  1102 D DSQN    : start to monitor internet connection
09-01 11:01:12.597  1035  7430 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 09:01:12 GMT], X-Android-Received-Millis=[1472720472596], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472720472586]}
09-01 11:01:12.597  1819  7439 I CheckinService: active receiver: enabled
09-01 11:01:12.597  1035  7430 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-01 11:01:12.597  1035  7430 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-01 11:01:12.598  1035  7431 D DhcpStateMachine: DHCPV4 request on wlan0
,09-01 11:01:12.600  1035  7431 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-01 11:01:12.600  1035  7431 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-01 11:01:12.600  1035  1501 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-01 11:01:12.601  1035  1501 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-01 11:01:12.601  1035  1501 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:01:12.601  1035  1501 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:12.601  1035  1501 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-01 11:01:12.601  1035  1501 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-01 11:01:12.601  1035  1501 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,09-01 11:01:12.601  1035  1501 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:12.601  1035  1501 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:12.601  1035  1501 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:12.602  1035  1501 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:12.602  1604  2114 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-01 11:01:12.602  1035  1501 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-01 11:01:12.603  1035  1440 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:12.603  1035  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:01:12.603  1854  1854 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:12.603  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-01 11:01:12.589  7461  7461 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:12.589  7461  7461 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:12.607  1819  7439 I CheckinService: Preparing to send checkin request
09-01 11:01:12.607  1819  7439 I EventLogService: Accumulating logs since 1472720368483
09-01 11:01:12.610  1035  2005 W libprocessgroup: failed to open /acct/uid_10044/pid_6190/cgroup.procs: No such file or directory
09-01 11:01:12.612  7461  7461 I dhcpcd  : version 5.5.6 starting
,09-01 11:01:12.614  7461  7461 E dhcpcd  : get_duid: m
09-01 11:01:12.614  7461  7461 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-01 11:01:12.614  7461  7461 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-01 11:01:12.623  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:01:12.624  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:12.624  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:01:12.645  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:01:12.646  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:12.647  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:12.665  1819  7439 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-01 11:01:12.671  7461  7461 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-01 11:01:12.672  7461  7461 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-01 11:01:12.672  7461  7461 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-01 11:01:12.672  7461  7461 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-01 11:01:12.672  7461  7461 D dhcpcd  : wlan0: sending REQUEST (xid 0x91ce49f1), next in 3.68 seconds
,09-01 11:01:12.697   278   453 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-01 11:01:12.697   278   453 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,09-01 11:01:12.697   278   453 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 11:01:12.698  7442  7470 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-01 11:01:12.699   278   453 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-01 11:01:12.699   278   453 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-01 11:01:12.699   278   453 W Vold    : Returning OperationFailed - no handler for errno 0
09-01 11:01:12.700  7442  7470 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-01 11:01:12.704  7461  7461 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-01 11:01:12.711   278   453 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-01 11:01:12.711   278   453 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-01 11:01:12.711   278   453 W Vold    : Returning OperationFailed - no handler for errno 0
09-01 11:01:12.712  7442  7472 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-01 11:01:12.716   278   453 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-01 11:01:12.716   278   453 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-01 11:01:12.716   278   453 W Vold    : Returning OperationFailed - no handler for errno 0
09-01 11:01:12.716  7442  7472 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-01 11:01:12.724  7461  7461 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-01 11:01:12.724  7461  7461 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-01 11:01:12.724  7461  7461 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-01 11:01:12.724  7461  7461 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,09-01 11:01:12.724  7461  7461 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-01 11:01:12.725  7461  7461 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-01 11:01:12.725  7461  7461 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-01 11:01:12.725  7461  7461 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-01 11:01:12.773  1035  1967 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7478 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-01 11:01:12.843  7478  7478 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-01 11:01:12.843  7478  7478 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-01 11:01:12.869  7478  7478 I MultiDex: VM with version 2.1.0 has multidex support
09-01 11:01:12.869  7478  7478 I MultiDex: install
09-01 11:01:12.869  7478  7478 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-01 11:01:12.880  7478  7478 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-01 11:01:12.979  7442  7442 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-01 11:01:12.987  7442  7442 I LibraryLoader: Loading: webviewchromium
09-01 11:01:12.989  7442  7442 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7401-7403)
,09-01 11:01:12.989  7442  7442 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 11:01:12.993  7442  7442 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b221962}
09-01 11:01:12.994  7442  7442 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 11:01:12.994  7442  7442 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-01 11:01:13.002  7442  7442 I BrowserStartupController: Initializing chromium process, renderers=0
09-01 11:01:13.003  7442  7442 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 11:01:13.003  1035  7431 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-01 11:01:13.004  1035  7431 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-01 11:01:13.004  1035  7431 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-01 11:01:13.004  1035  7431 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-01 11:01:13.004  1035  7431 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-01 11:01:13.004  1035  7431 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-01 11:01:13.004  1035  7431 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-01 11:01:13.004  1035  7431 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-01 11:01:13.004  1035  7431 D DhcpStateMachine: RunningState
09-01 11:01:13.011  7442  7442 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-01 11:01:13.012  7442  7442 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-01 11:01:13.012  7442  7442 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-01 11:01:13.015   312  1398 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10093
09-01 11:01:13.015  7442  7533 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-01 11:01:13.032  7442  7442 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:01:13.032  7442  7442 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:01:13.032  7442  7442 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:01:13.032  7442  7442 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:01:13.032  7442  7442 I Adreno-EGL: Remote Branch: 
09-01 11:01:13.032  7442  7442 I Adreno-EGL: Local Patches: 
09-01 11:01:13.032  7442  7442 I Adreno-EGL: Reconstruct Branch: 
,09-01 11:01:13.098  7442  7442 I NSApplication: Starting up...
,09-01 11:01:13.148  1035  1967 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7546 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-01 11:01:13.149  1035  1967 I ActivityManager: Killing 6868:com.lge.clock/u0a10 (adj 15): empty #17
,09-01 11:01:13.170  7478  7497 D LgDataFeature: LgDataFeature() Constructor: none
,09-01 11:01:13.170  7478  7497 D LgDataFeature: LgDataFeature() Constructor Done, null
09-01 11:01:13.197  1035  1684 W libprocessgroup: failed to open /acct/uid_10010/pid_6868/cgroup.procs: No such file or directory
,09-01 11:01:13.226  7546  7546 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 11:01:13.344  7568  7568 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-01 11:01:13.377  1035  1699 D WifiServiceImplEx: setWifiEnabled: false pid=6931, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-01 11:01:13.377  1035  1699 D WifiService: setWifiEnabled: false pid=6931, uid=10118
09-01 11:01:13.377  1035  1699 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-01 11:01:13.387  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:01:13.388  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:01:13.388  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-01 11:01:13.388  1035  1440 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-01 11:01:13.389  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-01 11:01:13.389  1035  1440 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-01 11:01:13.389  1035  1440 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-01 11:01:13.390  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-01 11:01:13.390  1035  1440 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-01 11:01:13.390  1035  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:01:13.390  1035  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-01 11:01:13.390  1035  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-01 11:01:13.391  1035  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-01 11:01:13.399  1035  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-01 11:01:13.399  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-01 11:01:13.399  1035  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:13.399  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:13.399  7317  7317 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-01 11:01:13.399  1035  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-01 11:01:13.399  1035  1440 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:01:13.400  1035  1440 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:01:13.400   308   891 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:01:13.401  1035  7431 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:13.424  7568  7568 I dex2oat : dex2oat took 79.006ms (threads: 4)
,09-01 11:01:13.426  1035  1501 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-01 11:01:13.426  1035  1501 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-01 11:01:13.429  1035  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:13.429  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:13.430  1035  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:13.430  1035  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:13.430  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:13.431  1035  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:13.431  1035  1440 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-01 11:01:13.433  1035  1391 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:13.433  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:13.433  7478  7497 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:01:13.433  7478  7497 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:01:13.433  7478  7497 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:01:13.433  7478  7497 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:01:13.433  7478  7497 I Adreno-EGL: Remote Branch: 
09-01 11:01:13.433  7478  7497 I Adreno-EGL: Local Patches: 
09-01 11:01:13.433  7478  7497 I Adreno-EGL: Reconstruct Branch: 
09-01 11:01:13.433  1035  1391 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@a522921
09-01 11:01:13.434  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-01 11:01:13.434  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:13.434  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:13.434  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:01:13.436  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-01 11:01:13.437  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:13.437  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-01 11:01:13.443  1035  1391 D LGWifiP2pService: P2pDisablingState
09-01 11:01:13.443  1035  1391 D LGWifiP2pService: P2pDisablingState{ when=-10ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:13.443  1035  1391 D LGWifiP2pService: p2p socket connection lost
09-01 11:01:13.443  1035  1391 D LGWifiP2pService: P2pDisabledState
09-01 11:01:13.443  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-01 11:01:13.443  1035  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-01 11:01:13.444  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-01 11:01:13.444  7317  7317 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-01 11:01:13.444  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:13.444  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:13.444  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:01:13.444  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-01 11:01:13.444  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-01 11:01:13.444  1035  1558 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:13.445  1035  1559 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:13.445  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:13.446  1035  1391 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:13.446  1035  1391 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:13.448  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:13.448  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:13.449  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:13.450  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-01 11:01:13.450  1941  1941 D WfdsService: WifiP2pState is changed : false
09-01 11:01:13.450  1941  2209 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-01 11:01:13.450  1941  2209 D WfdsService: Set the WFDS Monitor: false
09-01 11:01:13.450  1941  2209 D WfdsMonitor: WFDS Monitor is stopped
09-01 11:01:13.450  1941  2209 D WfdsService: STATE : WfdsDisabledState - enter
09-01 11:01:13.450  1941  7352 D CtrlSupplicant: Received on exit socket, terminate
09-01 11:01:13.450  1941  7352 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-01 11:01:13.450  1941  7352 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-01 11:01:13.450  1941  7352 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-01 11:01:13.451  1941  2213 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
,09-01 11:01:13.453  1941  2209 W WfdsService: DefaultState - msg [9445378] is not handled
09-01 11:01:13.457  1035  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-01 11:01:13.457  1035  1440 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:01:13.466  1035  1440 D WifiNative-wlan0: SET ps 1: returned true
,09-01 11:01:13.482   308   891 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:01:13.483  1035  1501 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-01 11:01:13.483  1035  1501 D DSQN    : disableDataServiceNotify
09-01 11:01:13.483  1035  1501 D DSQN    : stop dsqn bin
09-01 11:01:13.484  1035  1440 D WifiNative-p2p0: doBoolean: TERMINATE
09-01 11:01:13.484  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-01 11:01:13.485  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-01 11:01:13.485  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:13.485  1035  1440 D WifiNative-p2p0: TERMINATE: returned true
09-01 11:01:13.485  1035  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:01:13.485  1035  1440 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:01:13.485  1035  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:01:13.485  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:13.485  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:13.485  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:01:13.488  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-01 11:01:13.488  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:01:13.488  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,09-01 11:01:13.488  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-01 11:01:13.489  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:13.489  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:13.489  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:13.489  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:13.489  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:13.489  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:01:13.489  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:01:13.489  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:13.489  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:13.489  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:01:13.489  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:13.489  6931  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:01:13.491  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:13.491  1035  1501 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-01 11:01:13.491  1035  1501 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:13.491  1035  1501 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:13.492  1035  1501 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:13.492  1035  1501 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-01 11:01:13.492  1035  7430 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:13.492  1035  7430 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:13.492  1035  7430 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-01 11:01:13.492  1604  2114 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-01 11:01:13.493  1035  1501 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-01 11:01:13.493  1035  1501 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-01 11:01:13.493  1035  1501 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:01:13.493  1035  1501 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:13.493  1035  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-01 11:01:13.493  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-01 11:01:13.494  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-01 11:01:13.494  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-01 11:01:13.494  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-01 11:01:13.494  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:13.494  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:13.494  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:13.494  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:13.494  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:01:13.494  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:01:13.494  6931  6931 V io.jxcore.node.Con,nectivityMonitor:     - BSSID name: null
09-01 11:01:13.494  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:13.494  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:01:13.494  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:13.494  6931  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:01:13.494  1035  1501 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:01:13.494  1035  1501 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:13.494  1035  1501 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:13.495  1035  1501 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:13.495  1035  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-01 11:01:13.495  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-01 11:01:13.495  1035  1440 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:13.495  1035  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:01:13.495  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-01 11:01:13.495  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-01 11:01:13.496  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-01 11:01:13.496  1035  1501 D NetworkManagementService: Removing idletimer
09-01 11:01:13.496  1035  1501 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:13.496  1035  1501 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-01 11:01:13.496  1035  1501 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-01 11:01:13.496  1854  1854 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:13.496  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-01 11:01:13.523  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:01:13.524  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:13.525  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:01:13.542  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:01:13.543  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:13.544  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:13.546  7317  7317 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-01 11:01:13.547  7317  7317 I wpa_supplicant: monitor socket send errors count : 1
09-01 11:01:13.547  7317  7317 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
09-01 11:01:13.547  1035  7336 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-01 11:01:13.547  1035  7336 D WifiMonitor: Dropping event because (p2p0) is stopped
09-01 11:01:13.548  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-01 11:01:13.549  6563  7088 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-01 11:01:13.560  2081  2081 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:01:13.567  7317  7317 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:01:13.568  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-01 11:01:13.568  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:01:13.568  1035  7336 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:01:13.568  1035  7336 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-01 11:01:13.568  7317  7317 W wpa_supplicant: USIM:  scard_deinit function
09-01 11:01:13.568  1035  1440 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=217970
09-01 11:01:13.569  1035  1440 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=217971
09-01 11:01:13.569  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:01:13.569  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:01:13.569  1035  1440 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=217971  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-01 11:01:13.570  1035  1440 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=217972  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-01 11:01:13.570  1035  1105 D Tethering: InitialState.processMessage what=4
09-01 11:01:13.570  1035  1105 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-01 11:01:13.571  7478  7497 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:01:13.571  7478  7497 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:01:13.571  7478  7497 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:01:13.571  7478  7497 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:01:13.571  7478  7497 I Adreno-EGL: Remote Branch: 
09-01 11:01:13.571  7478  7497 I Adreno-EGL: Local Patches: 
09-01 11:01:13.571  7478  7497 I Adreno-EGL: Reconstruct Branch: 
09-01 11:01:13.571  1035  1440 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:13.572  1035  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:13.572  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-01 11:01:13.572  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:13.573  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,09-01 11:01:13.573  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-01 11:01:13.576  7258  7258 I AppUp4:CustModeStarterReceiver: onReceive
09-01 11:01:13.580  7258  7258 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@fa7958b
09-01 11:01:13.580  7258  7258 D AppUp4:CustFacade: isCustomizationCompleted : false
09-01 11:01:13.580  7258  7258 D AppUp4:CustFacade: isPhone : true
09-01 11:01:13.581  7258  7258 D AppUp4:CustModeStarterReceiver: begin check event
09-01 11:01:13.581  7258  7258 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-01 11:01:13.583  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:13.583  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:01:13.584  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:01:13.587  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-01 11:01:13.592  4855  7592 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-01 11:01:13.593  7285  7285 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-01 11:01:13.598  4855  7593 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:13.598  4855  7593 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:01:13.606  3219  3219 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-01 11:01:13.606  3219  3219 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:13.607  3219  3219 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-01 11:01:13.608  7285  7596 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:13.610  1035  7431 D DhcpStateMachine: StoppedState
09-01 11:01:13.610  1035  7431 D DhcpStateMachine: StoppedState{ when=-144ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:13.611  1035  1440 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-01 11:01:13.611  1035  1440 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-01 11:01:13.613  7337  7337 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-01 11:01:13.613  7337  7337 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-01 11:01:13.619  7161  7599 W FormManager: Network not available. Please check & try again.
,09-01 11:01:13.620  7478  7497 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:01:13.620  7478  7497 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:01:13.620  7478  7497 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:01:13.620  7478  7497 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:01:13.620  7478  7497 I Adreno-EGL: Remote Branch: 
09-01 11:01:13.620  7478  7497 I Adreno-EGL: Local Patches: 
09-01 11:01:13.620  7478  7497 I Adreno-EGL: Reconstruct Branch: 
09-01 11:01:13.628  7412  7412 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:1:13
09-01 11:01:13.628  7161  7600 V FormManager: Network unavailable.
09-01 11:01:13.629  7412  7412 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-01 11:01:13.629  7412  7412 D Weather.Utils: 2 : All the weather widget is gone.
09-01 11:01:13.630  7412  7412 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-01 11:01:13.630  7412  7412 D WeatherAncestor: connectivity changed - connection : true
09-01 11:01:13.630  7412  7412 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@7840a81
,09-01 11:01:13.631  7412  7412 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-01 11:01:13.631  7412  7412 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-01 11:01:13.631  7412  7412 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-01 11:01:13.631  7412  7412 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-01 11:01:13.631  7412  7412 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:1:13
09-01 11:01:13.634  7161  7600 V FormManager: Network unavailable.
09-01 11:01:13.654  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-01 11:01:13.654  7068  7068 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-01 11:01:13.654  7068  7068 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-01 11:01:13.654  7068  7068 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-01 11:01:13.654  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-01 11:01:13.655  7068  7068 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:01:13.655  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-01 11:01:13.655  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-01 11:01:13.655  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-01 11:01:13.655  7068  7068 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:01:13.655  7068  7068 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-01 11:01:13.662  7089  7089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:01:13.664  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:01:13.668  7161  7605 V FormManager: Network unavailable.
09-01 11:01:13.669  7161  7604 W FormManager: Network not available. Please check & try again.
09-01 11:01:13.669  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:13.669  7161  7605 V FormManager: Network unavailable.
09-01 11:01:13.682  7089  7089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:01:13.684  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-01 11:01:13.689  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:13.697  7161  7607 W FormManager: Network not available. Please check & try again.
,09-01 11:01:13.699  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:01:13.699  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:01:13.699  7161  7608 V FormManager: Network unavailable.
09-01 11:01:13.701  7161  7608 V FormManager: Network unavailable.
09-01 11:01:13.701  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:01:13.703  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:01:13.706  7317  7317 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-01 11:01:13.708  4855  7609 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-01 11:01:13.708  1035  7336 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-01 11:01:13.708  1035  7336 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-TERMINATING 
09-01 11:01:13.708  1035  7336 D WifiMonitor: Disconnecting from the supplicant, no more events
09-01 11:01:13.709  1035  1440 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 43 0
,09-01 11:01:13.711  4855  7610 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:01:13.711  4855  7610 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:01:13.741  1035  1050 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7611 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-01 11:01:13.747  1035  1440 D WifiOffDelayIfNotUsed: stopMonitoring
09-01 11:01:13.747  1035  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:01:13.747  1035  1440 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:01:13.747  1035  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:01:13.748  1941  1941 D WfdsService: Supplicant Connection state is changed : false
09-01 11:01:13.749  1941  2209 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-01 11:01:13.749  1941  2209 D WfdsService: Set the WFDS Monitor: false
09-01 11:01:13.749  1941  2209 D WfdsMonitor: WFDS Monitor is stopped
09-01 11:01:13.749  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:13.749  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:13.749  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:13.749  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:13.749  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:01:13.749  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:01:13.749  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:13.749  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:13.749  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:01:13.749  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:13.752  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-01 11:01:13.752  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:13.752  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:13.752  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:13.752  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:13.752  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:01:13.752  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:01:13.752  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:13.752  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:13.752  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:01:13.752  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-01 11:01:13.752  2427  2427 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:13.753  1035  1469 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-01 11:01:13.753  1035  1469 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,09-01 11:01:13.815  7611  7611 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-01 11:01:13.815  7611  7611 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-01 11:01:13.819  7611  7611 V [BNRBootReceiver]: Boot Receiver Return
09-01 11:01:13.823  7611  7611 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-01 11:01:13.823  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:13.831  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:13.838  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:13.850  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:13.850  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-01 11:01:13.852  7117  7117 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-01 11:01:13.857  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-01 11:01:13.858  7068  7068 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-01 11:01:13.862  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:01:13.867  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:01:13.871  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:13.877  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:13.877  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-01 11:01:13.879  7117  7117 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-01 11:01:13.882  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:13.888  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:13.891  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:13.896   308  7630 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-01 11:01:13.896  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:13.896  1035  1102 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-01 11:01:13.896  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:13.897  1819  7439 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-01 11:01:13.897  7117  7117 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:01:13.900  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:01:13.905  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:01:13.910  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:13.912  1819  7439 I CheckinService: active receiver: disabled
,09-01 11:01:13.923  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:13.923  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:13.923  7117  7117 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:01:13.928  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:01:13.937  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:13.941  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:13.945  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:13.945  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:13.946  7117  7117 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:01:13.950  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:01:13.958  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:13.966  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:13.975  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:13.975  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-01 11:01:13.976  7117  7117 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-01 11:01:13.982  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:13.992  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:14.000  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:14.010  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-01 11:01:14.010  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-01 11:01:14.011  7117  7117 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-01 11:01:14.021  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:14.035  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:14.046  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:14.065  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-01 11:01:14.066  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:14.075  7117  7117 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:01:14.082  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:01:14.095  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:01:14.098  1035  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=244901309, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,09-01 11:01:14.103  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:14.113  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:14.114  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-01 11:01:14.117  7117  7117 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:01:14.125  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:01:14.132  7089  7089 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-01 11:01:14.145  1035  1492 D WifiService: New client listening to asynchronous messages
09-01 11:01:14.146  2607  2607 D [Concierge]Service: onStartCommand(). Type : 9
,09-01 11:01:14.147  7089  7089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:01:14.164  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:14.174  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:14.186  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:14.186  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:14.187  7117  7117 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-01 11:01:14.188  7117  7117 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-01 11:01:14.188  7117  7117 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-01 11:01:14.195  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:14.199  7089  7089 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-01 11:01:14.201  7089  7089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:01:14.207  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:14.213  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:14.220  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:14.221  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:14.222  7117  7117 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-01 11:01:14.223  7117  7117 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-01 11:01:14.223  7117  7117 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-01 11:01:14.226  1035  1967 I ActivityManager: Killing 7048:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-01 11:01:14.260  1035  1699 W libprocessgroup: failed to open /acct/uid_10037/pid_7048/cgroup.procs: No such file or directory
,09-01 11:01:14.265  2081  2081 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-01 11:01:14.283  2081  2081 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-01 11:01:14.284  2081  2081 D c       : Getting all permits...
09-01 11:01:14.284  2081  2081 D a       : Opening database...
,09-01 11:01:14.292  2081  2081 D a       : Opening database auth.proximity.permit_store...
09-01 11:01:14.293  2081  2081 D a       : Closing database...
09-01 11:01:14.314  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:01:14.324  7089  7089 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-01 11:01:14.325  7089  7089 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:01:14.325  7089  7089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:01:14.330  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:14.344  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-01 11:01:14.360  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-01 11:01:14.361  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:14.368  7117  7117 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-01 11:01:14.376  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:01:14.379  6808  7240 D UEI.SmartControl: Internal timer expired: 2
09-01 11:01:14.379  6808  7240 D UEI.SmartControl: unbind internal service
09-01 11:01:14.381  7089  7089 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-01 11:01:14.382  7089  7089 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:01:14.382  7089  7089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:01:14.386  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:14.394  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:14.401  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:14.402  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-01 11:01:14.404  7117  7117 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-01 11:01:14.407  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:14.412  7089  7089 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-01 11:01:14.412  7089  7089 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:01:14.412  7089  7089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:01:14.419  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:14.426  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-01 11:01:14.434  7117  7117 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:14.435  7117  7117 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-01 11:01:14.437  7117  7117 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-01 11:01:14.448  7089  7089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:01:14.454  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-01 11:01:14.461  7161  7639 W FormManager: Network not available. Please check & try again.
,09-01 11:01:14.465  7161  7640 V FormManager: Network unavailable.
09-01 11:01:14.466  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:14.474  7161  7640 V FormManager: Network unavailable.
,09-01 11:01:14.487  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:01:14.488  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-01 11:01:14.491  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:01:14.495  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:01:14.502  4855  7641 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-01 11:01:14.508  7089  7089 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-01 11:01:14.508  7089  7089 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:01:14.508  7089  7089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:01:14.509  6808  7234 D serial_port: close(fd = 24)
09-01 11:01:14.509  4855  7642 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:01:14.509  4855  7642 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:01:14.514  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-01 11:01:14.515  6808  7234 I UEI.SmartControl: Serial port is closed.
,09-01 11:01:14.522  7161  7644 W FormManager: Network not available. Please check & try again.
09-01 11:01:14.527  7161  7645 V FormManager: Network unavailable.
09-01 11:01:14.527  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:14.535  7161  7645 V FormManager: Network unavailable.
,09-01 11:01:14.548  2081  2081 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-01 11:01:14.564  7117  7117 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,09-01 11:01:14.565  7117  7117 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3229
,09-01 11:01:14.567  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=244901309 [*alarm*], flags=0x0
09-01 11:01:15.394  1035  1440 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-453307135] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-01 11:01:15.404  1035  1440 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-453307124] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-01 11:01:15.466  1035  1501 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:01:15.482  1035  1105 D Tethering: MasterInitialState.processMessage what=3
09-01 11:01:15.500  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:01:15.504  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:15.506  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:15.509  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-01 11:01:15.511  6563  7088 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-01 11:01:15.522  5893  5893 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-01 11:01:15.548  2081  2081 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:01:15.595  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-01 11:01:15.595  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:15.596  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-01 11:01:15.596  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-01 11:01:15.600  7258  7258 I AppUp4:CustModeStarterReceiver: onReceive
09-01 11:01:15.604  7258  7258 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@fa7958b
09-01 11:01:15.604  7258  7258 D AppUp4:CustFacade: isCustomizationCompleted : false
09-01 11:01:15.604  7258  7258 D AppUp4:CustFacade: isPhone : true
09-01 11:01:15.605  7258  7258 D AppUp4:CustModeStarterReceiver: begin check event
09-01 11:01:15.606  7258  7258 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-01 11:01:15.610  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:15.611  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:01:15.612  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-01 11:01:15.618  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:01:15.625  7285  7285 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-01 11:01:15.646  4855  7664 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-01 11:01:15.659  4855  7666 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:15.659  4855  7666 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-01 11:01:15.667  7285  7674 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:15.671  3219  3219 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-01 11:01:15.671  3219  3219 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:15.671  3219  3219 I LgeMiscReceiver: networkInfo.isConnected() = true
09-01 11:01:15.671  3219  3219 D PhoneState: setPdpRejectCasuse : false
,09-01 11:01:15.678  7337  7337 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-01 11:01:15.678  7337  7337 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-01 11:01:15.682  7161  7673 V FormManager: Network unavailable.
09-01 11:01:15.684  7161  7670 W FormManager: Network not available. Please check & try again.
09-01 11:01:15.690  7161  7673 V FormManager: Network unavailable.
09-01 11:01:15.693  7412  7412 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:1:15
,09-01 11:01:15.699  7412  7412 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-01 11:01:15.699  7412  7412 D Weather.Utils: 2 : All the weather widget is gone.
09-01 11:01:15.699  7412  7412 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-01 11:01:15.699  7412  7412 D WeatherAncestor: connectivity changed - connection : true
09-01 11:01:15.700  7412  7412 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@7840a81
09-01 11:01:15.700  7412  7412 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-01 11:01:15.700  7412  7412 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-01 11:01:15.701  7412  7412 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-01 11:01:15.701  7412  7412 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-01 11:01:15.701  7412  7412 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:1:15
09-01 11:01:15.777  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-01 11:01:16.390  1035  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-01 11:01:16.390  1035  1577 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-01 11:01:16.419  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:01:16.419  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:01:16.419  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-01 11:01:16.420  1035  1105 D BluetoothManagerService: Message: 1
09-01 11:01:16.420  1035  1105 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-01 11:01:16.445  1035  1105 D BluetoothManagerService: Message: 20
09-01 11:01:16.445  1035  1105 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3058c2ad:true
,09-01 11:01:16.449  7196  7196 D BluetoothAdapterState: make
09-01 11:01:16.454  7196  7196 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-01 11:01:16.454  7196  7196 I bluedroid-qcom: init
09-01 11:01:16.455  7196  7686 I BluetoothAdapterState: Entering OffState
09-01 11:01:16.456  7196  7196 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-01 11:01:16.456  7196  7196 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-01 11:01:16.456  7196  7196 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 11:01:16.456  7196  7196 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-01 11:01:16.456  7196  7196 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-01 11:01:16.458  7196  7196 I bluedroid-qcom: get_profile_interface socket
09-01 11:01:16.458  7196  7196 I bluedroid-qcom: get_profile_interface map_client
,09-01 11:01:16.463  7196  7690 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-01 11:01:16.465  7196  7690 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-01 11:01:16.459  7689  7689 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:16.459  7689  7689 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:16.474  7689  7689 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-01 11:01:16.475  7689  7689 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-01 11:01:16.475  7689  7689 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-01 11:01:16.481  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-01 11:01:16.481  1035  1105 D BluetoothManagerService: Message: 40
09-01 11:01:16.481  1035  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-01 11:01:16.482  7196  7213 I bluedroid-qcom: config_hci_snoop_log
09-01 11:01:16.484  1035  1105 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-01 11:01:16.484  1035  1105 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-01 11:01:16.486  7689  7689 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-01 11:01:16.491  7689  7689 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-01 11:01:16.491  7689  7689 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-01 11:01:16.496  1035  1501 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:16.508  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:01:16.511  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:16.511  1035  1501 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:16.521  7196  7686 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,09-01 11:01:16.523  1035  1105 D Tethering: MasterInitialState.processMessage what=3
09-01 11:01:16.523  1035  1105 D Tethering: MasterInitialState.processMessage what=3
09-01 11:01:16.529  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:16.531  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:16.532  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:16.532  7196  7690 D BluetoothAdapterProperties: Name is: G3
09-01 11:01:16.534  7196  7686 D BluetoothAdapterProperties: Setting state to 11
09-01 11:01:16.534  7196  7686 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-01 11:01:16.536  1035  1105 D BluetoothManagerService: Message: 60
,09-01 11:01:16.536  1035  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-01 11:01:16.536  1035  1105 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-01 11:01:16.538  7196  7686 I LGBluetoothServiceJni: classInitNative: succeeds
,09-01 11:01:16.541  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-01 11:01:16.541  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-01 11:01:16.542  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:16.544  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:01:16.555  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:01:16.565  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:16.567  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-01 11:01:16.569  6563  7088 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-01 11:01:16.573  7068  7068 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-01 11:01:16.579  7196  7686 D BluetoothBondStateMachine: make
09-01 11:01:16.583  7196  7686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:16.584  7196  7686 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-01 11:01:16.584  7196  7686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:16.584  7196  7686 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-01 11:01:16.584  7196  7686 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-01 11:01:16.589  7196  7686 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:01:16.590  7196  7707 I BluetoothBondStateMachine: StableState(): Entering Off State
09-01 11:01:16.593  5893  5893 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-01 11:01:16.598  7196  7196 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:01:16.599  7196  7196 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:16.599  7196  7196 V BluetoothPbapReceiver: ***********state = 11
09-01 11:01:16.604  7196  7686 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:01:16.605  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:16.605  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:01:16.606  7196  7196 D HeadsetService: Received start request. Starting profile...
09-01 11:01:16.606  7196  7196 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 11:01:16.606  7196  7196 D LGBluetoothHfpAdapter: Version 1.6
09-01 11:01:16.609  7196  7196 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-01 11:01:16.612  7196  7196 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 11:01:16.612  7196  7196 D HeadsetStateMachine: make
09-01 11:01:16.613  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:16.613  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:16.650  7196  7196 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:01:16.651  7196  7196 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:01:16.658  1035  1050 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7711 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-01 11:01:16.661  7196  7196 D HeadsetStateMachine: max_hf_connections = 1
09-01 11:01:16.661  7196  7196 I bluedroid-qcom: get_profile_interface handsfree
09-01 11:01:16.663  7196  7686 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:01:16.663  7196  7196 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-01 11:01:16.664  5893  5893 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-01 11:01:16.664   312  2186 V AudioPolicyService: registerClient() client 0xb57c6c80, uid 1002
09-01 11:01:16.664   312  2185 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-01 11:01:16.664   312  2185 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:01:16.664   312  2185 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:01:16.665  7196  7196 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,09-01 11:01:16.667   312  1398 V AudioFlinger: registerClient() client 0xb5581568, pid 7196
09-01 11:01:16.667  7196  7196 V ToneGenerator: Create Track: 0xb4928080
,09-01 11:01:16.668  7196  7196 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
,09-01 11:01:16.668  7196  7196 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-01 11:01:16.668   312  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:01:16.668   312  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:01:16.669  1035  2051 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:01:16.669  1035  2051 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:01:16.669  7196  7212 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:01:16.669   312  2185 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-01 11:01:16.669  7196  7212 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-01 11:01:16.669   312  2185 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-01 11:01:16.669   312  2185 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:01:16.669   312  2185 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:01:16.669  7196  7196 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-01 11:01:16.669  1604  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:01:16.669  1604  1624 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:01:16.669   312  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:01:16.669   312  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:01:16.669  1854  4534 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:01:16.669  1854  4534 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:01:16.670  1604  3335 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:01:16.670  1854  3452 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:01:16.670  1604  3335 V AudioSystem: ioConfigChanged() opening already existing output! 2
,09-01 11:01:16.670  1854  3452 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:01:16.670  7196  7213 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:01:16.670  7196  7213 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-01 11:01:16.670  3219  3241 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:01:16.670  3219  3241 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:01:16.670   312  2185 I AudioFlinger: isAudioPlaybackHookOn() false
09-01 11:01:16.670  3219  3241 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:01:16.670  3219  3241 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:01:16.670   312  2186 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-01 11:01:16.671   312  2186 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-01 11:01:16.671   312  2186 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:01:16.671   312  2186 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:01:16.671  1035  2051 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:01:16.671  1035  2051 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:01:16.671  7196  7196 V AudioSystem: getLatency() output 2, latency 50
09-01 11:01:16.671  7196  7196 V AudioSystem: getFrameCount() output 2, frameCount 960
09-01 11:01:16.671  7196  7196 V AudioTrack: createTrack_l() output 2 afLatency 50
09-01 11:01:16.671   312  2185 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-01 11:01:16.671   312  2185 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-01 11:01:16.671   312  2185 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-01 11:01:16.671   312  2185 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-01 11:01:16.671   312  2185 V AudioFlinger: createTrack() lSessionId: 22
09-01 11:01:16.672  7196  7196 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-01 11:01:16.673   312  1398 V AudioFlinger: acquiring 22 from 7196, for 7196
09-01 11:01:16.674   312  1398 V AudioFlinger:  added new entry for 22
09-01 11:01:16.674  7196  7196 V ToneGenerator: ToneGenerator INIT OK, time: 221088
09-01 11:01:16.674  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:16.675  7196  7709 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-01 11:01:16.675  7196  7709 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:01:16.676  7196  7709 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:01:16.676  7196  7709 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-01 11:01:16.676  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:16.677  7196  7686 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:01:16.678   312  1397 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7196
09-01 11:01:16.679  7196  7196 D A2dpService: Received start request. Starting profile...
09-01 11:01:16.679  7196  7196 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 11:01:16.680  7196  7196 V Avrcp   : make
,09-01 11:01:16.681  7196  7196 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-01 11:01:16.681  7196  7196 I bluedroid-qcom: get_profile_interface avrcp
09-01 11:01:16.682   312  1397 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-01 11:01:16.682   312  1397 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-01 11:01:16.682   312  1397 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-01 11:01:16.682   312  1397 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-01 11:01:16.682   312  1397 V voice   : voice_set_parameters: exit with code(0)
09-01 11:01:16.682   312  1397 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-01 11:01:16.682   312  1397 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-01 11:01:16.682   312  1397 V msm8974_platform: platform_set_parameters: exit with code(0)
09-01 11:01:16.682   312  1397 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-01 11:01:16.682   312  1397 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-01 11:01:16.682   312  1397 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-01 11:01:16.686  7196  7686 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:01:16.686  7196  7709 V ToneGenerator: ToneGenerator destructor
09-01 11:01:16.686  7196  7709 V ToneGenerator: stopTone
09-01 11:01:16.686  7196  7709 V ToneGenerator: Delete Track: 0xb4928080
09-01 11:01:16.686  7196  7709 V AudioTrack: ~AudioTrack, releasing session id from 7196 on behalf of 7196
09-01 11:01:16.687   312  1398 V AudioFlinger: releasing 22 from 7196 for 7196
09-01 11:01:16.687   312  1398 V AudioFlinger:  decremented refcount to 0
09-01 11:01:16.687   312  1398 V AudioFlinger: purging stale effects
09-01 11:01:16.687   312  1398 V AudioPolicyService: AudioCommandThread() adding release output 2
09-01 11:01:16.687   312  1398 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-01 11:01:16.687   312  1256 V AudioPolicyService: AudioCommandThread() waking up
09-01 11:01:16.687   312  1398 V AudioFlinger: PlaybackThread::Track destructor
09-01 11:01:16.687   312  1256 V AudioPolicyService: AudioCommandThread() processing release output 2
09-01 11:01:16.687   312  1256 V AudioPolicyManager: releaseOutput() 2
09-01 11:01:16.687   312  1256 V AudioPolicyService: AudioCommandThread() going to sleep
09-01 11:01:16.687   312  1398 V AudioFlinger: removeClient_l() pid 7196, calling pid 312
09-01 11:01:16.693  7196  7196 V AudioManager: registerRemoteController: size of Media player list: 0
09-01 11:01:16.695  2081  2081 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:16.695  7196  7196 E AudioManager: No RCC entry present to update
09-01 11:01:16.695  7196  7196 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 11:01:16.698  7196  7686 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:01:16.699  7196  7196 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-01 11:01:16.700  7196  7196 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-01 11:01:16.700  7196  7196 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-01 11:01:16.709  7196  7196 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-01 11:01:16.711  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-01 11:01:16.711  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:16.711  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-01 11:01:16.711  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-01 11:01:16.712  7196  7686 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:01:16.756  7258  7258 I AppUp4:CustModeStarterReceiver: onReceive
,09-01 11:01:16.777  7196  7686 V LGMDMManager: Create singleton instance
09-01 11:01:16.777  7258  7258 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@fa7958b
09-01 11:01:16.777  7258  7258 D AppUp4:CustFacade: isCustomizationCompleted : false
09-01 11:01:16.777  7258  7258 D AppUp4:CustFacade: isPhone : true
,09-01 11:01:16.780  7196  7686 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-01 11:01:16.780  7258  7258 D AppUp4:CustModeStarterReceiver: begin check event
09-01 11:01:16.780  7258  7258 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-01 11:01:16.784  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:16.785  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:01:16.786  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:01:16.788  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:01:16.795  4855  7732 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-01 11:01:16.798  1035  1962 V SIM_STK : Menu title from STK is T-Mobile
,09-01 11:01:16.799  1035  1962 V SIM_STK : Menu title from STK is T-Mobile
09-01 11:01:16.800  4855  7733 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:16.801  4855  7733 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:01:16.803  7285  7285 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-01 11:01:16.818  3219  3219 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-01 11:01:16.818  3219  3219 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:16.818  3219  3219 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-01 11:01:16.818  7285  7734 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:16.820  7337  7337 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-01 11:01:16.820  7337  7337 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-01 11:01:16.824  7161  7736 W FormManager: Network not available. Please check & try again.
09-01 11:01:16.829  7412  7412 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:1:16
09-01 11:01:16.830  7412  7412 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-01 11:01:16.830  7412  7412 D Weather.Utils: 2 : All the weather widget is gone.
09-01 11:01:16.830  7412  7412 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-01 11:01:16.830  7412  7412 D WeatherAncestor: connectivity changed - connection : true
09-01 11:01:16.830  7412  7412 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@7840a81
09-01 11:01:16.830  7161  7737 V FormManager: Network unavailable.
,09-01 11:01:16.833  7412  7412 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-01 11:01:16.833  7412  7412 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-01 11:01:16.833  7412  7412 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-01 11:01:16.833  7412  7412 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-01 11:01:16.833  7412  7412 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:1:16
09-01 11:01:16.838  7711  7711 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-01 11:01:16.839  7711  7711 W LG Account v2.2: No ProfileInfo entries
09-01 11:01:16.839  7711  7711 I LG Account v2.2: isEnabled: false
09-01 11:01:16.839  7161  7737 V FormManager: Network unavailable.
09-01 11:01:16.839  7711  7711 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-01 11:01:16.839  7711  7711 I Feature : [Lifetracker]Country: EU
09-01 11:01:16.839  7711  7711 I Feature : [Lifetracker]Operator: OPEN
09-01 11:01:16.839  7711  7711 I Feature : [Lifetracker]Ranking support: false
09-01 11:01:16.839  7711  7711 I Feature : [Lifetracker]Comfort support: false
09-01 11:01:16.839  7711  7711 I Feature : [Lifetracker]Accessory: true
09-01 11:01:16.839  7711  7711 I Feature : [Lifetracker]Health device: true
09-01 11:01:16.840  7711  7711 I Feature : [Lifetracker]Extra Pedometer: false
09-01 11:01:16.840  7711  7711 I Feature : [Lifetracker]Blood glucose device: false
09-01 11:01:16.840  7711  7711 I Feature : [Lifetracker]Device Number: 3
09-01 11:01:16.851  7068  7068 D BluetoothPermissionRequest: onReceive
,09-01 11:01:16.852  6563  6563 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-01 11:01:16.854  6563  7088 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-01 11:01:16.859  7068  7068 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:01:16.867  2081  2081 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:01:16.877  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-01 11:01:16.877  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:16.877  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-01 11:01:16.877  7258  7258 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-01 11:01:16.878  7258  7258 I AppUp4:CustModeStarterReceiver: onReceive
,09-01 11:01:16.883  7258  7258 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@fa7958b
09-01 11:01:16.883  7258  7258 D AppUp4:CustFacade: isCustomizationCompleted : false
09-01 11:01:16.883  7258  7258 D AppUp4:CustFacade: isPhone : true
09-01 11:01:16.883  7258  7258 D AppUp4:CustModeStarterReceiver: begin check event
09-01 11:01:16.883  7258  7258 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-01 11:01:16.884  1035  1995 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-01 11:01:16.887  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:16.887  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:01:16.888  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:01:16.890  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:01:16.891  7196  7196 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-01 11:01:16.893  4855  7741 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-01 11:01:16.894  7285  7285 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-01 11:01:16.897  7196  7196 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-01 11:01:16.897  4855  7742 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:16.897  4855  7742 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:01:16.897  7196  7196 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-01 11:01:16.897  7196  7196 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-01 11:01:16.898  7196  7196 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-01 11:01:16.898  7196  7196 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:01:16.898  7196  7196 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-01 11:01:16.898  7196  7196 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-01 11:01:16.898  7196  7196 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-01 11:01:16.898  7196  7196 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:01:16.898  7196  7196 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-01 11:01:16.899  7196  7196 I BluetoothA2dpServiceJni: classInitNative
09-01 11:01:16.899  7196  7196 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 11:01:16.899  7196  7196 D A2dpStateMachine: make
09-01 11:01:16.900  7196  7196 I bluedroid-qcom: get_profile_interface a2dp
09-01 11:01:16.900  7196  7744 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-01 11:01:16.902  7196  7196 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-01 11:01:16.902  7196  7196 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-01 11:01:16.903  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:16.903  7196  7196 D HeadsetStateMachine: Proxy object connected
09-01 11:01:16.903  7196  7743 D A2dpStateMachine: Enter Disconnected: -2
09-01 11:01:16.904  7196  7196 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,09-01 11:01:16.904  7196  7196 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-01 11:01:16.905  7196  7196 I BluetoothHidServiceJni: classInitNative: succeeds
09-01 11:01:16.907  7196  7196 D HidService: Received start request. Starting profile...
09-01 11:01:16.907  7196  7196 I bluedroid-qcom: get_profile_interface hidhost
09-01 11:01:16.907  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:16.911  7196  7196 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:01:16.911  7196  7709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-01 11:01:16.911  7196  7196 I BluetoothHealthServiceJni: classInitNative: succeeds
09-01 11:01:16.912  7196  7709 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-01 11:01:16.912  7196  7709 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-01 11:01:16.913  7196  7196 D HealthService: Received start request. Starting profile...
09-01 11:01:16.915  7196  7196 I bluedroid-qcom: get_profile_interface health
09-01 11:01:16.915  7196  7196 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-01 11:01:16.915  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:16.916  7196  7196 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-01 11:01:16.917  3219  3219 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-01 11:01:16.917  3219  3219 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:16.917  3219  3219 I LgeMiscReceiver: networkInfo.isConnected() = false
09-01 11:01:16.917  7196  7196 D PanService: Received start request. Starting profile...
09-01 11:01:16.917  7196  7196 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 11:01:16.917  7196  7196 I bluedroid-qcom: get_profile_interface pan
09-01 11:01:16.919  7285  7746 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:16.920  7337  7337 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-01 11:01:16.920  7337  7337 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-01 11:01:16.926  7196  7196 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-01 11:01:16.926  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:16.927  7196  7196 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-01 11:01:16.931  7161  7751 W FormManager: Network not available. Please check & try again.
09-01 11:01:16.932  7196  7196 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 11:01:16.932  7196  7196 D BtGatt.GattService: Received start request. Starting profile...
09-01 11:01:16.932  7196  7196 D BtGatt.GattService: start()
09-01 11:01:16.932  7196  7196 I bluedroid-qcom: get_profile_interface gatt
09-01 11:01:16.933  7196  7196 D BtGatt.AdvertiseManager: advertise manager created
,09-01 11:01:16.934  7412  7412 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:1:16
09-01 11:01:16.935  7412  7412 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-01 11:01:16.935  7412  7412 D Weather.Utils: 2 : All the weather widget is gone.
09-01 11:01:16.935  7412  7412 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-01 11:01:16.935  7412  7412 D WeatherAncestor: connectivity changed - connection : true
09-01 11:01:16.935  7412  7412 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@7840a81
09-01 11:01:16.936  7161  7752 V FormManager: Network unavailable.
09-01 11:01:16.937  7412  7412 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-01 11:01:16.938  7161  7752 V FormManager: Network unavailable.
09-01 11:01:16.942  7412  7412 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-01 11:01:16.942  7412  7412 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-01 11:01:16.942  7412  7412 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-01 11:01:16.942  7412  7412 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:1:16
09-01 11:01:17.056  1035  2005 I art     : Explicit concurrent mark sweep GC freed 122759(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.486ms total 119.039ms
,09-01 11:01:17.064  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:17.067  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:17.068  7196  7196 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-01 11:01:17.071  7196  7196 V BluetoothMapService: BluetoothMapBinder()
09-01 11:01:17.072  7196  7196 D BluetoothMapService: Received start request. Starting profile...
09-01 11:01:17.072  7196  7196 D BluetoothMapService: start()
,09-01 11:01:17.077  7196  7196 D BluetoothMapEmailSettingsLoader: Found 0 applications
,09-01 11:01:17.077  7196  7196 D BluetoothMapEmailAppObserver: createReceiver()
09-01 11:01:17.078  7196  7196 D BluetoothMapEmailAppObserver: initObservers()
09-01 11:01:17.078  7196  7196 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-01 11:01:17.083  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:17.086  7196  7196 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:01:17.088  7196  7196 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-01 11:01:17.090  7196  7196 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:01:17.092  7196  7196 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:01:17.092  7196  7196 V PanService: [BTUI] SIM Extra State :ABSENT
09-01 11:01:17.094  7196  7196 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-01 11:01:17.094  7196  7196 V BluetoothMapService: Handler(): got msg=1
,09-01 11:01:17.095  7196  7686 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-01 11:01:17.095  7196  7686 I bluedroid-qcom: enable
09-01 11:01:17.096  7196  7756 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-01 11:01:17.096  7196  7196 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:17.096  7196  7756 I bt-btu  : btu_task pending for preload complete event
09-01 11:01:17.096  7196  7686 I bt_hci_bdroid: init
09-01 11:01:17.098  7196  7196 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:01:17.098  7196  7196 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:01:17.098  7196  7196 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:01:17.098  7196  7196 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:17.098  7196  7196 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-01 11:01:17.103  7196  7686 I bt_vendor: bt-vendor : init
09-01 11:01:17.103  7196  7686 I bt_vendor: bt-vendor : get_bt_soc_type
09-01 11:01:17.103  7196  7686 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-01 11:01:17.103  7196  7686 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-01 11:01:17.103  7196  7686 D bt_userial_mct: userial_init
09-01 11:01:17.104  7196  7686 D bt_hci_bdroid: set_power 1
09-01 11:01:17.104  7196  7686 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-01 11:01:17.104  7196  7686 I bt_vendor: Starting hciattach daemon
,09-01 11:01:17.104  7196  7686 I bt_vendor: try to set true
09-01 11:01:17.099  7759  7759 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:17.099  7759  7759 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:17.137  7760  7760 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-01 11:01:17.224  7766  7766 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-01 11:01:17.243  7767  7767 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-01 11:01:17.272  7769  7769 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-01 11:01:17.284  7770  7770 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-01 11:01:17.292  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7767
,09-01 11:01:17.296  7771  7771 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-01 11:01:17.306  7772  7772 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-01 11:01:17.325  7774  7774 I libmdmdetect: ESOC framework not supported
,09-01 11:01:17.327  7774  7774 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-01 11:01:17.335  7774  7774 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-01 11:01:17.335  7774  7774 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-01 11:01:17.335  7774  7774 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-01 11:01:17.335  7774  7774 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-01 11:01:17.335  7774  7774 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-01 11:01:17.335  7774  7774 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-01 11:01:17.335  7774  7774 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-01 11:01:17.372  7774  7775 E QC-QMI  : qmi_client [7774] 14: failed to locate client data
09-01 11:01:17.373   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-01 11:01:17.373   484   484 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-01 11:01:17.407  7779  7779 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-01 11:01:17.421  7780  7780 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-01 11:01:17.456  7196  7686 I bt_vendor: bluetooth satus is on
,09-01 11:01:17.456  7196  7686 D bt_hci_bdroid: preload
09-01 11:01:17.456  7196  7758 D bt_userial_mct: userial_open(port:0)
09-01 11:01:17.456  7196  7758 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-01 11:01:17.459  7196  7758 I bt_vendor: Done intiailizing UART
09-01 11:01:17.461  7196  7758 I bt_vendor: Done intiailizing UART
,09-01 11:01:17.461  7196  7758 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-01 11:01:17.461  7196  7758 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-01 11:01:17.461  7196  7782 D bt_userial_mct: Entering userial_read_thread()
09-01 11:01:17.461  7196  7756 I bt-btu  : btu_task received preload complete event
09-01 11:01:17.462  7196  7756 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-01 11:01:17.462  7196  7756 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-01 11:01:17.465  7196  7756 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_HCI
09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_AVRC
09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_BNEP
09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_PAN
,09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_SDP
09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_GATT
09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 11:01:17.468  7196  7756 I         : BTE_InitTraceLevels -- TRC_BTIF
09-01 11:01:17.549  7196  7756 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-01 11:01:17.549  7196  7756 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f6061 
,09-01 11:01:17.550  7196  7756 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f6061 
,09-01 11:01:17.610  7196  7690 E bt-btif : Calling BTA_HhEnable
09-01 11:01:17.610  7196  7690 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-01 11:01:17.611  7196  7690 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-01 11:01:17.634  7196  7756 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-01 11:01:17.635  7196  7756 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-01 11:01:17.635  7196  7756 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-01 11:01:17.635  7196  7756 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-01 11:01:17.635  7196  7756 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-01 11:01:17.637  7196  7690 D BluetoothAdapterProperties: Name is: G3
09-01 11:01:17.639  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-01 11:01:17.639  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-01 11:01:17.640  7196  7690 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:01:17.640  7196  7690 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:01:17.641  7196  7690 D bt_hci_bdroid: postload
,09-01 11:01:17.643  7196  7758 D bt_hci_bdroid: Used up Tx Cmd credits
09-01 11:01:17.644  7196  7756 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-01 11:01:17.644  7196  7690 D bte_conf: Device ID record 1 : primary
09-01 11:01:17.644  7196  7690 D bte_conf:   vendorId            = 00c4
09-01 11:01:17.644  7196  7690 D bte_conf:   vendorIdSource      = 0001
09-01 11:01:17.644  7196  7690 D bte_conf:   product             = 13a1
09-01 11:01:17.644  7196  7690 D bte_conf:   version             = 1000
09-01 11:01:17.644  7196  7690 D bte_conf:   clientExecutableURL = 
09-01 11:01:17.644  7196  7690 D bte_conf:   serviceDescription  = 
09-01 11:01:17.644  7196  7690 D bte_conf:   documentationURL    = 
09-01 11:01:17.644  7196  7690 D bte_conf: bte_load_did_conf no section named DID2.
09-01 11:01:17.648  7196  7686 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-01 11:01:17.648  7196  7686 D BluetoothAdapterProperties: ScanMode =  20
09-01 11:01:17.648  7196  7686 D BluetoothAdapterProperties: State =  11
09-01 11:01:17.648  7196  7686 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-01 11:01:17.649  7196  7686 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-01 11:01:17.649  7196  7686 D BluetoothAdapterProperties: Setting state to 12
09-01 11:01:17.649  7196  7686 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-01 11:01:17.651  7196  7690 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-01 11:01:17.651  7196  7690 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-01 11:01:17.639  7790  7790 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-01 11:01:17.649  7790  7790 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:17.660  1035  1105 D BluetoothManagerService: Message: 60
09-01 11:01:17.660  1035  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-01 11:01:17.660  1035  1105 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-01 11:01:17.661  7196  7758 D bt_hci_bdroid: Used up Tx Cmd credits
09-01 11:01:17.665  7196  7758 D bt_hci_bdroid: Used up Tx Cmd credits
09-01 11:01:17.673  7196  7756 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:01:17.673  7196  7756 W bt-smp  : Plain text(LSB ~ MSB) = 5e 5a 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:01:17.673  7196  7756 W bt-smp  : Encrypted text(LSB ~ MSB) = f9 8a 79 66 60 74 f9 cc 8b 65 4b f2 29 73 a8 81 
,09-01 11:01:17.676  7196  7758 D bt_hci_bdroid: Used up Tx Cmd credits
09-01 11:01:17.676  7196  7756 W bt-btm  : Stopping oneshot timer
09-01 11:01:17.677  7196  7782 E bt_mct  : hci lib postload completed
09-01 11:01:17.686  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:17.686  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:17.686  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:17.686  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:01:17.686  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:01:17.686  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:17.686  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:17.686  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:01:17.697  6931  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:01:17.700  7196  7686 I BluetoothAdapterState: Entering On State
,09-01 11:01:17.706  7196  7690 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:01:17.706  7196  7690 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-01 11:01:17.712  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:17.712  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:17.712  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:17.712  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:01:17.712  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:01:17.712  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:17.712  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:17.712  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:01:17.715  7196  7756 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:01:17.715  7196  7756 W bt-smp  : Plain text(LSB ~ MSB) = f9 ff 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:01:17.715  7196  7756 W bt-smp  : Encrypted text(LSB ~ MSB) = 53 2e 83 dc 51 7f a7 ce eb 2f a5 8c 19 f5 39 72 
09-01 11:01:17.715  7196  7756 W bt-btm  : Stopping oneshot timer
09-01 11:01:17.722  6931  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:01:17.734  7196  7686 D LGBluetoothServiceAdapter: [BTUI] OnState
09-01 11:01:17.735  7196  7686 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-01 11:01:17.735  7196  7686 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-01 11:01:17.738  7196  7686 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-01 11:01:17.739  7068  7085 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 11:01:17.741  7068  7084 D BluetoothMap: onBluetoothStateChange: up=true
09-01 11:01:17.743  7196  7756 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:01:17.743  7196  7756 W bt-smp  : Plain text(LSB ~ MSB) = b6 72 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:01:17.743  7196  7756 W bt-smp  : Encrypted text(LSB ~ MSB) = 0e 92 9e cc 0a 48 9c 5d a5 9a a1 49 b2 76 8d 4d 
09-01 11:01:17.744  7196  7756 W bt-btm  : Stopping oneshot timer
09-01 11:01:17.750  7196  7686 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-01 11:01:17.756  7068  7085 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 11:01:17.768  7196  7756 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:01:17.768  7196  7756 W bt-smp  : Plain text(LSB ~ MSB) = ed 3e 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:01:17.768  7196  7756 W bt-smp  : Encrypted text(LSB ~ MSB) = 11 7c 25 f5 1f af 1e 96 48 f9 5a ae 3f 6f e9 f4 
09-01 11:01:17.768  7196  7756 W bt-btm  : Stopping oneshot timer
,09-01 11:01:17.771  1854  4534 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:01:17.791  7196  7756 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:01:17.791  7196  7756 W bt-smp  : Plain text(LSB ~ MSB) = b2 1d 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:01:17.791  7196  7756 W bt-smp  : Encrypted text(LSB ~ MSB) = a3 92 1a 8f 35 75 c9 cb 03 83 91 bd 4b 81 91 a6 
09-01 11:01:17.791  7196  7756 W bt-btm  : Stopping oneshot timer
,09-01 11:01:17.797  7796  7796 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-01 11:01:17.803  1854  1854 D BluetoothHeadset: Proxy object connected
,09-01 11:01:17.806  1854  1870 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:01:17.808  1854  1854 D BluetoothHeadset: Proxy object connected
09-01 11:01:17.808  1035  1105 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:01:17.809  1035  1035 D BluetoothHeadset: Proxy object connected
09-01 11:01:17.812  1854  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:01:17.815  1854  1854 D BluetoothHeadset: Proxy object connected
,09-01 11:01:17.819  7068  7084 D BluetoothPan: onBluetoothStateChange on: true
09-01 11:01:17.819  7068  7084 D BluetoothPan: onBluetoothStateChange call bindService
09-01 11:01:17.823  1035  1105 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:01:17.824  1035  1035 D BluetoothA2dp: Proxy object connected
09-01 11:01:17.828  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,09-01 11:01:17.830  1035  1105 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-01 11:01:17.830  1035  1105 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-01 11:01:17.835  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:17.835  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:01:17.840  1941  2102 D LGBluetoothAPIService: Message: 1
09-01 11:01:17.840  1941  2102 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,09-01 11:01:17.844  7068  7068 D BluetoothMap: Proxy object connected
09-01 11:01:17.844  7068  7068 D MapProfile: Bluetooth service connected
09-01 11:01:17.844  7068  7068 D BluetoothMap: getConnectedDevices()
09-01 11:01:17.848  7196  7213 V BluetoothMapService: getConnectedDevices()
09-01 11:01:17.855  6931  6931 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,09-01 11:01:17.861  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:17.862  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:17.863  7068  7068 D BluetoothInputDevice: Proxy object connected
09-01 11:01:17.863  7068  7068 D HidProfile: Bluetooth service connected
09-01 11:01:17.868  7196  7196 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:17.868  7196  7196 D BluetoothMapService: STATE_ON
09-01 11:01:17.870  7196  7196 D LGBluetoothAPIServer: [BTUI] onCreate()
09-01 11:01:17.870  7196  7196 D LGBluetoothAPIServer: [BTUI] onBind()
,09-01 11:01:17.875  7196  7196 V BluetoothMapService: Handler(): got msg=1
09-01 11:01:17.876  7196  7196 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-01 11:01:17.876  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-01 11:01:17.893  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:17.893  7196  7196 V BluetoothPbapService: Pbap Service onCreate
09-01 11:01:17.893  7196  7196 V BluetoothPbapService: Starting PBAP service
,09-01 11:01:17.897  7196  7196 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-01 11:01:17.897  7196  7196 V BluetoothPbapService: Handler(): got msg=1
09-01 11:01:17.898  7196  7196 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-01 11:01:17.899  7068  7068 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:01:17.899  7068  7068 D PanProfile: Bluetooth service connected
09-01 11:01:17.902  7196  7196 V BluetoothPbapService: Pbap Service onBind
09-01 11:01:17.903  7196  7196 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:17.903  7196  7196 V BluetoothPbapService: state: 12
09-01 11:01:17.905  7068  7068 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-01 11:01:17.909  1941  2102 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,09-01 11:01:17.910  1941  2102 D LGBluetoothAPIService: Message: 100
09-01 11:01:17.910  1941  2102 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-01 11:01:17.912  1035  1105 D BluetoothManagerService: Message: 40
09-01 11:01:17.912  1035  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-01 11:01:17.912  1035  1105 D BluetoothManagerService: Message: 30
,09-01 11:01:17.914  7068  7068 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-01 11:01:17.925  1035  1105 D BluetoothManagerService: Message: 30
09-01 11:01:17.929  7196  7797 D BluetoothMapMasInstance: MAS initSocket()
,09-01 11:01:17.929  7196  7797 D BluetoothMapMasInstance:   masId = 00
09-01 11:01:17.929  7196  7797 D BluetoothMapMasInstance:   msgTypes = 0e
09-01 11:01:17.929  7196  7797 D BluetoothMapMasInstance:   masName = SMS/MMS
09-01 11:01:17.929  7196  7797 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-01 11:01:17.931  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-01 11:01:17.933  7196  7797 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:01:17.935  7196  7797 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-01 11:01:17.935  7196  7797 V BluetoothMapMasInstance: Succeed to create listening socket 
09-01 11:01:17.935  7196  7797 D BluetoothMapMasInstance: Accepting socket connection...
09-01 11:01:17.937  7196  7798 V BluetoothPbapService: Pbap Service initSocket
09-01 11:01:17.939  7196  7690 D BluetoothAdapterProperties: Scan Mode:21
09-01 11:01:17.939  7196  7690 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-01 11:01:17.939  1035  1684 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:17.941  7196  7798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:01:17.942  7196  7798 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-01 11:01:17.943  7196  7798 V BluetoothPbapService: Succeed to create listening socket 
09-01 11:01:17.943  7196  7798 V BluetoothPbapService: Accepting socket connection...
,09-01 11:01:17.943  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:17.955  7068  7068 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-01 11:01:17.960  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:17.960  7068  7068 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-01 11:01:17.963  7068  7068 D BluetoothPbap: Proxy object connected
09-01 11:01:17.964  7068  7068 D PbapServerProfile: Bluetooth service connected
09-01 11:01:17.964  7068  7068 D BluetoothA2dp: Proxy object connected
09-01 11:01:17.965  7068  7068 D A2dpProfile: Bluetooth service connected
09-01 11:01:17.968  7196  7196 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:01:17.968  7068  7068 D BluetoothHeadset: Proxy object connected
09-01 11:01:17.968  7196  7196 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:17.968  7196  7196 V BluetoothPbapReceiver: ***********state = 12
09-01 11:01:17.969  7068  7068 D HeadsetProfile: Bluetooth service connected
09-01 11:01:17.974  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:01:17.974  2081  2081 D c       : Getting all permits...
09-01 11:01:17.974  2081  2081 D a       : Opening database...
09-01 11:01:17.975  7068  7068 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:01:17.981  2081  2081 D a       : Opening database auth.proximity.permit_store...
09-01 11:01:17.982  2081  2081 D a       : Closing database...
09-01 11:01:17.994  7068  7068 D BluetoothPermissionRequest: onReceive
,09-01 11:01:17.997  7068  7068 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-01 11:01:17.998  7068  7068 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:01:18.001  7442  7473 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-01 11:01:18.001  7196  7196 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-01 11:01:18.003  7196  7196 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-01 11:01:18.009  7196  7196 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-01 11:01:18.028  7196  7196 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-01 11:01:18.028  7196  7196 V BtOppService: onCreate
09-01 11:01:18.032  7196  7196 V BluetoothOppNotification: send message
09-01 11:01:18.035  7196  7196 V BtOppService: Starting RfcommListener
09-01 11:01:18.039  7196  7196 D BluetoothOppPreference: Dumping Names:  
09-01 11:01:18.039  7196  7196 D BluetoothOppPreference: {}
,09-01 11:01:18.039  7196  7196 D BluetoothOppPreference: Dumping Channels:  
09-01 11:01:18.039  7196  7196 D BluetoothOppPreference: {}
09-01 11:01:18.040  7196  7196 V BtOppService: onStartCommand
09-01 11:01:18.041  7196  7824 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-01 11:01:18.043  7196  7196 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:18.044  7196  7196 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-01 11:01:18.047  7196  7196 V BluetoothOppNotification: new notify threadi!
09-01 11:01:18.049  7196  7196 V BluetoothOppNotification: send delay message
09-01 11:01:18.049  7196  7824 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-01 11:01:18.049  7196  7196 V BtOppService: start RfcommListener
09-01 11:01:18.051  7196  7821 V BtOppService: Deleted complete outbound shares, number =  0
09-01 11:01:18.051  7196  7825 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-01 11:01:18.051  7196  7824 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ff1f0c2 on behalf of 
,09-01 11:01:18.053  7196  7821 V BtOppService: Deleted complete inbound failed shares, number = 0
09-01 11:01:18.054  7196  7821 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-01 11:01:18.054  7196  7196 V BtOppService: RfcommListener started
09-01 11:01:18.054  7196  7824 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-01 11:01:18.054  7196  7824 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-01 11:01:18.056  7196  7821 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@96aced3 on behalf of 
09-01 11:01:18.056  7196  7826 V BtOppRfcommListener: Starting RFCOMM listener....
09-01 11:01:18.058  7196  7824 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17b08a10 on behalf of 
09-01 11:01:18.058  7196  7825 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@389bd909 on behalf of 
09-01 11:01:18.058  1035  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:18.059  7196  7826 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:01:18.060  7196  7826 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
09-01 11:01:18.061  7196  7826 V BtOppRfcommListener: Started RFCOMM listener....
09-01 11:01:18.061  7196  7826 I BtOppRfcommListener: Accept thread started.
09-01 11:01:18.061  7196  7826 V BtOppRfcommListener: Accepting connection...
09-01 11:01:18.061  7196  7825 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-01 11:01:18.061  7196  7824 V BluetoothOppNotification: update too frequent, put in queue
09-01 11:01:18.062  7196  7824 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-01 11:01:18.063  7196  7825 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-01 11:01:18.064  7196  7825 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c72570e on behalf of 
09-01 11:01:18.065  7196  7825 V BluetoothOppNotification: outbound: succ-0  fail-0
09-01 11:01:18.066  7196  7825 V BluetoothOppNotification: outbound notification was removed.
09-01 11:01:18.066  7196  7825 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-01 11:01:18.068  7196  7825 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3609852f on behalf of 
09-01 11:01:18.068  7196  7825 V BluetoothOppNotification: inbound: succ-0  fail-0
09-01 11:01:18.069  7196  7825 V BluetoothOppNotification: inbound notification was removed.
09-01 11:01:18.070  7196  7825 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-01 11:01:18.071  7196  7825 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19fc373c on behalf of 
09-01 11:01:18.072  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:18.073  7196  7196 V BluetoothFtpService: Ftp Service onCreate
09-01 11:01:18.073  7196  7196 I BluetoothFtpService: Ftp Service onCreate
09-01 11:01:18.073  7196  7196 V BluetoothFtpService: Ftp Service onStartCommand
09-01 11:01:18.073  7196  7196 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:18.073  7196  7196 V BluetoothFtpService: Starting Listening on sockets
09-01 11:01:18.074  7196  7196 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:01:18.074  7196  7196 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:01:18.074  7196  7196 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:01:18.074  7196  7196 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:18.074  7196  7196 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-01 11:01:18.074  7196  7196 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-01 11:01:18.076  7196  7196 V BtOppService: ContentObserver received notification
09-01 11:01:18.076  7196  7196 V BtOppService: ContentObserver received notification
09-01 11:01:18.077  7196  7196 V BluetoothFtpService: Handler(): got msg=1
,09-01 11:01:18.077  7196  7828 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-01 11:01:18.078  7196  7828 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-01 11:01:18.078  7196  7196 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-01 11:01:18.078  7196  7196 V BluetoothFtpService: Ftp Service initSocket
09-01 11:01:18.079  7196  7828 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2180d61a on behalf of 
09-01 11:01:18.081  1035  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:18.082  7196  7828 V BluetoothOppNotification: update too frequent, put in queue
09-01 11:01:18.082  7196  7196 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:01:18.083  7196  7828 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-01 11:01:18.083  7196  7196 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-01 11:01:18.085  7196  7829 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-01 11:01:18.102  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:18.102  7196  7196 V BluetoothSapService: Sap Service onCreate
,09-01 11:01:18.105  7196  7196 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:01:18.105  7196  7196 V BluetoothSapService: state: 12
09-01 11:01:18.105  7196  7196 V BluetoothSapService: Starting SAP server process
09-01 11:01:18.107  7196  7196 V BluetoothSapService: SAP Service startRfcommListenerThread
09-01 11:01:18.099  7830  7830 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:18.099  7830  7830 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:18.109  7196  7831 V BluetoothSapService: Sap Service initRfcommSocket
09-01 11:01:18.109  1035  1684 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:18.110  7196  7831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:01:18.111  7196  7831 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-01 11:01:18.111  7196  7831 V BluetoothSapService: Succeed to create listening socket 
09-01 11:01:18.111  7196  7831 V BluetoothSapService: Accepting socket connection...
09-01 11:01:18.120  7830  7830 V BT_SAP  : Event pipe created
09-01 11:01:18.120  7830  7830 V BT_SAP  : create_server_socket qcom.sap.server
09-01 11:01:18.120  7830  7830 V BT_SAP  : created socket fd 6
,09-01 11:01:18.448  1035  1391 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:01:18.449  1035  1391 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:01:18.488  1035  1440 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-01 11:01:18.495  1035  1440 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
09-01 11:01:18.563  1035  1962 I ActivityManager: Killing 7611:com.lge.bnr/1000 (adj 15): empty #17
,09-01 11:01:18.594  1035  2005 W libprocessgroup: failed to open /acct/uid_1000/pid_7611/cgroup.procs: No such file or directory
,09-01 11:01:18.889  1035  1967 I ActivityManager: Killing 7089:com.lge.sync/1000 (adj 15): empty #17
,09-01 11:01:18.916  1035  1492 D WifiService: Client connection lost with reason: 4
,09-01 11:01:18.927  1035  1995 W libprocessgroup: failed to open /acct/uid_1000/pid_7089/cgroup.procs: No such file or directory
,09-01 11:01:19.029  1035  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2829c149 type 2 when 223423 com.google.android.gms} when 223423
,09-01 11:01:19.044   308  7842 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-01 11:01:19.044  1035  1102 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-01 11:01:19.049  7196  7196 V BluetoothOppNotification: new notify threadi!
09-01 11:01:19.050  7196  7196 V BluetoothOppNotification: send delay message
,09-01 11:01:19.053  7196  7843 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-01 11:01:19.058  7196  7843 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ac639e6 on behalf of 
09-01 11:01:19.059  7196  7843 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-01 11:01:19.062  7196  7843 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-01 11:01:19.065  7196  7843 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9eeeb27 on behalf of 
09-01 11:01:19.066  7196  7843 V BluetoothOppNotification: outbound: succ-0  fail-0
09-01 11:01:19.068  7196  7843 V BluetoothOppNotification: outbound notification was removed.
09-01 11:01:19.068  7196  7843 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-01 11:01:19.069  7196  7843 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d8a31d4 on behalf of 
09-01 11:01:19.069  7196  7843 V BluetoothOppNotification: inbound: succ-0  fail-0
09-01 11:01:19.072  7196  7843 V BluetoothOppNotification: inbound notification was removed.
09-01 11:01:19.072  7196  7843 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-01 11:01:19.074  7196  7843 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3cfdff7d on behalf of 
,09-01 11:01:19.439  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-01 11:01:19.439  1035  1050 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1a21ba4e mBinding = false
,09-01 11:01:19.467  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:01:19.468  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:01:19.468  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-01 11:01:19.472  1035  1105 D BluetoothManagerService: Message: 2
09-01 11:01:19.473  1035  1105 D BluetoothManagerService: Sending off request.
09-01 11:01:19.474  7196  7691 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-01 11:01:19.475  7196  7686 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-01 11:01:19.475  7196  7686 D BluetoothAdapterProperties: Setting state to 13
09-01 11:01:19.475  7196  7686 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 11:01:19.476  7196  7686 D BluetoothAdapterProperties: onBluetoothDisable()
09-01 11:01:19.476  7196  7686 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-01 11:01:19.478  7196  7690 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:01:19.479  7196  7686 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-01 11:01:19.482  7196  7686 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-01 11:01:19.487  7196  7798 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:01:19.488  7196  7826 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:01:19.488  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-01 11:01:19.489  7196  7756 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-01 11:01:19.490  7196  7797 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-01 11:01:19.490  7196  7797 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:01:19.490  7196  7797 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-01 11:01:19.490  7196  7797 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-01 11:01:19.490  7196  7797 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-01 11:01:19.490  7196  7797 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-01 11:01:19.490  7196  7797 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-01 11:01:19.490  7196  7797 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-01 11:01:19.491  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:01:19.491  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:01:19.491  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:01:19.491  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:01:19.491  7196  7756 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:01:19.491  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:01:19.491  7196  7756 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:01:19.491  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:01:19.491  7196  7756 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:01:19.491  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-01 11:01:19.491  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-01 11:01:19.491  7196  7756 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-01 11:01:19.504  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:19.504  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:19.504  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:19.504  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:19.504  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:01:19.504  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:01:19.504  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:19.504  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:19.504  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:01:19.510  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:19.510  6931  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:01:19.513  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:19.513  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:19.513  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:19.513  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:19.513  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:01:19.513  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:01:19.513  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:19.513  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:19.513  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:01:19.514  6931  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:01:19.514  6931  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:01:19.515  1035  1105 D BluetoothManagerService: Message: 60
09-01 11:01:19.515  1035  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-01 11:01:19.516  1035  1105 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-01 11:01:19.519  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:01:19.523  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:01:19.527  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:19.528  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:19.531  7196  7196 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:19.531  7196  7196 D BluetoothMapService: STATE_TURNING_OFF
09-01 11:01:19.532  7196  7196 V BluetoothMapService: Handler(): got msg=4
09-01 11:01:19.532  7196  7196 D BluetoothMapService: MAP Service closeService in
09-01 11:01:19.532  7196  7196 D BluetoothMapMasInstance: MAP Service shutdown
09-01 11:01:19.532  7196  7196 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:01:19.532  7196  7196 V BluetoothMapService: MAP Service closeService out
,09-01 11:01:19.535  7196  7196 V BtOppService: Receiver DISABLED_ACTION 
09-01 11:01:19.536  7196  7196 I BtOppRfcommListener: stopping Accept Thread
09-01 11:01:19.536  7196  7196 V BtOppRfcommListener: close mBtServerSocket
09-01 11:01:19.536  7196  7826 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-01 11:01:19.537  7196  7196 V BtOppRfcommListener: waiting for thread to terminate
09-01 11:01:19.537  7196  7196 V BtOppRfcommListener: done waiting for thread to terminate
09-01 11:01:19.540  7068  7068 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-01 11:01:19.545  7196  7829 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-01 11:01:19.550  7196  7831 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:01:19.554  7068  7068 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-01 11:01:19.557  7196  7196 V BtOppService: onDestroy
,09-01 11:01:19.559  7196  7196 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-01 11:01:19.564  7196  7196 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:01:19.565  7196  7196 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:19.565  7196  7196 V BluetoothPbapReceiver: ***********state = 13
09-01 11:01:19.566  7196  7196 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-01 11:01:19.569  7196  7196 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:19.569  7196  7196 V BluetoothPbapService: state: 13
09-01 11:01:19.569  7196  7196 V BluetoothPbapService: Pbap Service closeService in
,09-01 11:01:19.575  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:01:19.580  7196  7196 V BluetoothPbapService: successfully stopped pbap service
09-01 11:01:19.580  7196  7196 V BluetoothPbapService: Pbap Service closeService out
09-01 11:01:19.582  7196  7196 V BluetoothPbapService: Pbap Service onDestroy
09-01 11:01:19.582  7196  7196 V BluetoothPbapService: Pbap Service closeService in
09-01 11:01:19.582  7196  7196 V BluetoothPbapService: Pbap Service closeService out
09-01 11:01:19.582  7196  7196 D LGBluetoothPbapAdapter: [BTUI] cleanup
,09-01 11:01:19.612  7068  7068 D DockEventReceiver: finishStartingService: stopping service
09-01 11:01:19.614  7068  7068 D BluetoothPbap: Proxy object disconnected
09-01 11:01:19.615  7068  7068 D PbapServerProfile: Bluetooth service disconnected
,09-01 11:01:19.622  7068  7068 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-01 11:01:19.629  7068  7068 D BluetoothPermissionRequest: onReceive
09-01 11:01:19.630  7068  7068 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-01 11:01:19.635  7068  7068 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:01:19.637  7196  7196 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-01 11:01:19.637  7196  7196 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-01 11:01:19.638  7196  7196 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-01 11:01:19.643  7196  7196 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:19.643  7196  7196 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-01 11:01:19.644  7196  7196 V BluetoothFtpService: Ftp Service onStartCommand
09-01 11:01:19.644  7196  7196 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:19.644  7196  7196 V BluetoothFtpService: Ftp Service closeService
09-01 11:01:19.644  7196  7196 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-01 11:01:19.648  7196  7196 V BluetoothFtpService: successfully stopped ftp service
09-01 11:01:19.648  7196  7196 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-01 11:01:19.648  7196  7196 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,09-01 11:01:19.648  7196  7196 V BluetoothSapReceiver: SapReceiver onReceive 
,09-01 11:01:19.648  7196  7196 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:19.649  7196  7196 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-01 11:01:19.649  7196  7196 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-01 11:01:19.650  7196  7196 V BluetoothFtpService: Ftp Service onDestroy
09-01 11:01:19.650  7196  7196 V BluetoothFtpService: Ftp Service closeService
,09-01 11:01:19.654  7196  7196 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED,
09-01 11:01:19.654  7196  7196 V BluetoothSapService: state: 13,
09-01 11:01:19.654  7196  7196 V BluetoothSapService: Stopping SAP server process
09-01 11:01:19.655  7196  7196 V BluetoothSapService: Sap Service closeSapService in
09-01 11:01:19.655  7196  7196 V BluetoothSapService: Close listen Socket : 
,09-01 11:01:19.656  7196  7196 V BluetoothSapService: Close rfcomm Socket : 
09-01 11:01:19.656  7196  7196 V BluetoothSapService: Close sapd  Socket : 
09-01 11:01:19.659  7196  7196 V BluetoothSapService: Sap Service closeSapService out
09-01 11:01:19.660  7196  7196 V BluetoothSapService: Sap Service onDestroy,
09-01 11:01:19.660  7196  7196 V BluetoothSapService: Sap Service closeSapService in
09-01 11:01:19.660  7196  7196 V BluetoothSapService: Close listen Socket : 
09-01 11:01:19.660  7196  7196 V BluetoothSapService: Close rfcomm Socket : 
,09-01 11:01:19.660  7196  7196 V BluetoothSapService: Close sapd  Socket : 
09-01 11:01:19.660  7196  7196 V BluetoothSapService: Sap Service closeSapService out
09-01 11:01:20.414  1035  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{17206c7c type 2 when 224810 android} when 224810
,09-01 11:01:20.479  7196  7690 D bt_hci_bdroid: cleanup
,09-01 11:01:20.485  7196  7782 I bt_userial_mct: exiting userial_read_thread
09-01 11:01:20.485  7196  7782 D bt_userial_mct: Leaving userial_evt_read_thread()
09-01 11:01:20.486  7196  7758 I bt_lpm  : LPM is already off!!!
09-01 11:01:20.487  7196  7756 W bt-btif : ag scb idx 1 not allocated
09-01 11:01:20.487  7196  7756 E bt-btif : BTA AG is already disabled, ignoring ...
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:01:20.487  7196  7756 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:01:20.487  7196  7756 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-01 11:01:20.488  7196  7690 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-01 11:01:20.488  7196  7758 I bt_vendor: hw_epilog_process
09-01 11:01:20.489  7196  7690 D bt_hci_bdroid: cleanup Finalizing cleanup
09-01 11:01:20.489  7196  7690 D bt_userial_mct: userial_close
09-01 11:01:20.489  7196  7690 E bt_userial_mct: pthread_join() FAILED result:3
09-01 11:01:20.489  7196  7690 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-01 11:01:20.496  7196  7690 D bt_hci_bdroid: set_power 0
09-01 11:01:20.496  7196  7690 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-01 11:01:20.496  7196  7690 I bt_vendor: bluetooth satus is on
09-01 11:01:20.496  7196  7690 I bt_vendor: bt-vendor : resetting BT status
09-01 11:01:20.496  7196  7690 I bt_vendor: Starting hciattach daemon
09-01 11:01:20.496  7196  7690 I bt_vendor: try to set false
,09-01 11:01:20.503  7196  7690 I bt_vendor: Starting hciattach daemon
09-01 11:01:20.504  7196  7690 I bt_vendor: try to set false
09-01 11:01:20.505  7196  7690 I bt_vendor: cleanup
09-01 11:01:20.505  7196  7756 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-01 11:01:20.506  7196  7690 I GKI_LINUX: GKI_exit_task 0 done
09-01 11:01:20.506  7196  7690 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-01 11:01:20.508  7196  7686 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-01 11:01:20.512  7196  7196 D HeadsetService: Received stop request...Stopping profile...
,09-01 11:01:20.516  7196  7196 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-01 11:01:20.516  7196  7196 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:01:20.516  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:20.517  7196  7709 D HeadsetStateMachine: Exit Disconnected: -1
09-01 11:01:20.522  1854  1854 D BluetoothHeadset: Proxy object disconnected
09-01 11:01:20.522  1854  1854 D BluetoothHeadset: Proxy object disconnected
09-01 11:01:20.522  1854  1854 D BluetoothHeadset: Proxy object disconnected
09-01 11:01:20.525  7196  7686 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-01 11:01:20.528  7196  7196 D A2dpService: Received stop request...Stopping profile...
09-01 11:01:20.530  7196  7743 D A2dpStateMachine: Exit Disconnected: -1
09-01 11:01:20.532  7196  7196 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-01 11:01:20.533  7196  7196 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-01 11:01:20.533  7196  7196 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:01:20.533  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:20.535  7196  7196 D HidService: Received stop request...Stopping profile...
09-01 11:01:20.535  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:20.537  7196  7196 D HealthService: Received stop request...Stopping profile...
09-01 11:01:20.537  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
,09-01 11:01:20.541  7196  7196 D HeadsetStateMachine: Unbinding service...
09-01 11:01:20.543  7196  7196 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:01:20.543  7196  7196 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:01:20.543  7196  7196 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:01:20.543  7196  7196 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:01:20.543  7196  7196 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 11:01:20.543  7196  7196 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:01:20.543  7196  7196 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-01 11:01:20.544  7196  7196 D PanService: Received stop request...Stopping profile...
09-01 11:01:20.545  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:20.547  7196  7196 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 11:01:20.549  7196  7196 D BtGatt.GattService: Received stop request...Stopping profile...
09-01 11:01:20.549  7196  7196 D BtGatt.GattService: stop()
09-01 11:01:20.549  7196  7196 D BtGatt.AdvertiseManager: advertise clients cleared
09-01 11:01:20.550  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
,09-01 11:01:20.554  7196  7196 D BluetoothMapService: Received stop request...Stopping profile...
09-01 11:01:20.554  7196  7196 D BluetoothMapService: stop()
09-01 11:01:20.555  7196  7196 D BluetoothMapEmailAppObserver: deinitObservers()
09-01 11:01:20.556  7196  7196 D BluetoothMapEmailAppObserver: removeReceiver()
09-01 11:01:20.556  7196  7196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7840a81
09-01 11:01:20.557  7196  7196 I BluetoothA2dpServiceJni: cleanupNative
09-01 11:01:20.558  7196  7744 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-01 11:01:20.558  7196  7196 I GKI_LINUX: GKI_exit_task 2 done
09-01 11:01:20.558  7196  7196 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-01 11:01:20.558  7196  7196 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 11:01:20.558  7196  7196 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 11:01:20.559  7196  7196 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 11:01:20.559  7196  7196 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 11:01:20.559  7196  7196 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 11:01:20.559  7196  7196 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 11:01:20.559  7196  7196 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-01 11:01:20.562  7196  7196 V BluetoothMapService: Handler(): got msg=4
09-01 11:01:20.562  7196  7196 D BluetoothMapService: MAP Service closeService in
09-01 11:01:20.562  7196  7196 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:01:20.562  7196  7196 V BluetoothMapService: MAP Service closeService out
,09-01 11:01:20.566  7196  7686 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-01 11:01:20.566  7196  7686 D BluetoothAdapterProperties: Setting state to 10
09-01 11:01:20.566  7196  7686 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-01 11:01:20.567  7196  7196 D BluetoothMapService: cleanup()
09-01 11:01:20.568  7196  7196 D BluetoothMapService: MAP Service closeService in
09-01 11:01:20.568  7196  7196 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:01:20.568  7196  7196 V BluetoothMapService: MAP Service closeService out
09-01 11:01:20.569  1035  1105 D BluetoothManagerService: Message: 60
09-01 11:01:20.569  1035  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-01 11:01:20.569  1035  1105 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-01 11:01:20.569  7196  7686 I BluetoothAdapterState: Entering OffState
09-01 11:01:20.569  7068  7794 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 11:01:20.570  7068  7794 D BluetoothMap: onBluetoothStateChange: up=false
09-01 11:01:20.571  7068  7794 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 11:01:20.571  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-01 11:01:20.571  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-01 11:01:20.571  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-01 11:01:20.572  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-01 11:01:20.572  1854  3452 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:01:20.573  7068  7794 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 11:01:20.575  1854  4534 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-01 11:01:20.579  1035  1105 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:01:20.580  1854  4521 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:01:20.580  7068  7794 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:01:20.581  7068  7085 D BluetoothPan: onBluetoothStateChange on: false
09-01 11:01:20.582  1035  1105 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 11:01:20.582  1035  1105 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-01 11:01:20.582  1035  1105 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-01 11:01:20.584  1035  1105 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-01 11:01:20.584  1035  1105 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-01 11:01:20.584  1035  1105 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1a21ba4e mBinding = false
09-01 11:01:20.585  1035  1105 D BluetoothManagerService: Sending unbind request.
09-01 11:01:20.590  7196  7690 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-01 11:01:20.592  7196  7196 I GKI_LINUX: GKI_exit_task 1 done
09-01 11:01:20.592  7196  7196 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-01 11:01:20.593  7196  7196 I BluetoothServiceJni: cleanupNative: return from cleanup
09-01 11:01:20.594  7196  7196 I art     : --- WEIRD: removing null entry 248
09-01 11:01:20.594  7196  7196 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-01 11:01:20.594  7196  7196 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-01 11:01:20.595  7196  7196 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-01 11:01:20.597  1035  1105 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-01 11:01:20.599  7196  7196 I art     : System.exit called, status: 0
09-01 11:01:20.599  7196  7196 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-01 11:01:20.619   312   312 V AudioFlinger: 7196 died, releasing its sessions
09-01 11:01:20.619   312   312 V AudioFlinger:  pid 1854 @ 0
09-01 11:01:20.619   312   312 V AudioFlinger:  pid 3219 @ 1
09-01 11:01:20.619   312   312 V AudioFlinger:  pid 3219 @ 2
,09-01 11:01:20.623  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-01 11:01:20.623  1941  2102 D LGBluetoothAPIService: Message: 101
,09-01 11:01:20.623  1941  2102 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-01 11:01:20.623  1941  2102 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-01 11:01:20.624  1941  2102 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-01 11:01:20.625  7068  7068 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-01 11:01:20.667  1035  1967 I ActivityManager: Process com.android.bluetooth (pid 7196) has died
,09-01 11:01:20.668  1035  1967 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,09-01 11:01:20.668  1035  1967 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
09-01 11:01:20.681  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:20.681  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:20.682  1941  2102 D LGBluetoothAPIService: Message: 2
09-01 11:01:20.682  1941  2102 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
,09-01 11:01:20.685  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-01 11:01:20.686  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:20.692  1604  1604 D BluetoothAdapter: 721991424: getState() :  mService = null. Returning STATE_OFF
,09-01 11:01:20.692  1604  1604 D BluetoothAdapter: 721991424: getState() :  mService = null. Returning STATE_OFF
09-01 11:01:20.695  7068  7068 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-01 11:01:20.695  7068  7068 D LGBluetoothEventManager: [BTUI] clear device connection state
,09-01 11:01:20.699  7068  7068 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-01 11:01:20.761  1035  1726 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7886 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-01 11:01:20.762  7068  7068 D DockEventReceiver: finishStartingService: stopping service
09-01 11:01:20.788   343   343 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 460us total 27.506ms
,09-01 11:01:20.810   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 21.368ms
,09-01 11:01:20.833   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 422us total 22.005ms
,09-01 11:01:20.834  7886  7886 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-01 11:01:20.834  7886  7886 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:01:20.834  7886  7886 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-01 11:01:20.835  7886  7886 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-01 11:01:20.852  7886  7886 D BluetoothAdapterApp: Loading JNI Library
,09-01 11:01:20.885  7886  7886 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@4153b49 Instance Count = 1
,09-01 11:01:20.891  7886  7886 D BluetoothAdapterApp: onCreate
,09-01 11:01:20.914  7886  7886 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,09-01 11:01:20.915  7886  7886 D ProfileConfigQcom: Adding HeadsetService
09-01 11:01:20.915  7886  7886 D ProfileConfigQcom: [BTUI] A2dpService is supported
,09-01 11:01:20.915  7886  7886 D ProfileConfigQcom: Adding A2dpService
09-01 11:01:20.915  7886  7886 D ProfileConfigQcom: [BTUI] HidService is supported
09-01 11:01:20.916  7886  7886 D ProfileConfigQcom: Adding HidService
09-01 11:01:20.916  7886  7886 D ProfileConfigQcom: [BTUI] HealthService is supported
09-01 11:01:20.916  7886  7886 D ProfileConfigQcom: Adding HealthService
09-01 11:01:20.916  7886  7886 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-01 11:01:20.917  7886  7886 D ProfileConfigQcom: [BTUI] PanService is supported
09-01 11:01:20.917  7886  7886 D ProfileConfigQcom: Adding PanService
09-01 11:01:20.918  7886  7886 D ProfileConfigQcom: [BTUI] GattService is supported
09-01 11:01:20.918  7886  7886 D ProfileConfigQcom: Adding GattService
09-01 11:01:20.918  7886  7886 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-01 11:01:20.918  7886  7886 D ProfileConfigQcom: Adding BluetoothMapService
09-01 11:01:20.918  7886  7886 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-01 11:01:20.919  7886  7886 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-01 11:01:20.920  7886  7886 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:01:20.921  7886  7886 V BluetoothPbapReceiver: ***********state = 10
,09-01 11:01:20.922  7886  7886 V LGMDMManagerInternal: Create singleton instance
09-01 11:01:21.001  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:01:21.003  7068  7068 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-01 11:01:21.010  7886  7886 D LGBluetoothAPIServer: [BTUI] onCreate()
09-01 11:01:21.011  7886  7886 D LGBluetoothAPIServer: [BTUI] onBind()
,09-01 11:01:21.013  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,09-01 11:01:21.013  1941  2102 D LGBluetoothAPIService: Message: 100
09-01 11:01:21.013  1941  2102 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-01 11:01:21.015  7068  7068 D BluetoothPermissionRequest: onReceive
09-01 11:01:21.017  7068  7068 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-01 11:01:21.017  7068  7068 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-01 11:01:21.019  7068  7068 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:01:21.025  7886  7886 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-01 11:01:21.032  7886  7886 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:21.038  7886  7886 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-01 11:01:21.039  7886  7886 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:01:21.039  7886  7886 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:01:21.040  7886  7886 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:21.040  7886  7886 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,09-01 11:01:21.045  7134  7134 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-01 11:01:22.531  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:22.531  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:01:22.644  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-01 11:01:22.668  1035  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-01 11:01:22.696  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-01 11:01:22.702  1035  1035 D administrator: Handling package changes for user 0
,09-01 11:01:22.822  1035  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7924 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-01 11:01:22.830  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-01 11:01:22.838  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,09-01 11:01:22.877  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-01 11:01:22.888  7924  7924 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-01 11:01:22.903  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-01 11:01:22.903  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-01 11:01:22.961  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 11:01:22.967  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-01 11:01:22.969  7924  7924 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:01:22.969  7924  7924 D LgDataFeature: LgDataFeature() Constructor Done, null
09-01 11:01:22.973  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-01 11:01:22.974  2427  2427 V GmsNetworkLocationProvi: DISABLE
,09-01 11:01:23.007  2427  2427 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-01 11:01:23.008  1035  1091 D LocationProviderProxy: applying state to connected service
,09-01 11:01:23.093  7924  7955 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-01 11:01:23.093  7924  7955 I Babel   : MmsConfig.loadMmsSettings
,09-01 11:01:23.102  7924  7955 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-01 11:01:23.102  7924  7955 I Babel   : MmsConfig.loadFromDatabase
,09-01 11:01:23.119  7924  7955 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-01 11:01:23.119  7924  7955 I Babel   : MmsConfig.loadFromResources
09-01 11:01:23.122  7924  7955 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-01 11:01:23.122  7924  7955 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-01 11:01:23.140  7924  7924 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:23.152  7924  7954 W AudioCapabilities: Unsupported mime audio/evrc
,09-01 11:01:23.157  7924  7954 W AudioCapabilities: Unsupported mime audio/qcelp
09-01 11:01:23.161  7924  7954 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-01 11:01:23.164  1819  7959 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-01 11:01:23.164  1819  7959 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-01 11:01:23.171  7258  7258 I AppUp4:CustModeStarterReceiver: onReceive
,09-01 11:01:23.185  1819  5230 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-01 11:01:23.186  7258  7258 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@fa7958b
09-01 11:01:23.186  7258  7258 D AppUp4:CustFacade: isCustomizationCompleted : false
09-01 11:01:23.186  7258  7258 D AppUp4:CustFacade: isPhone : true
09-01 11:01:23.186  7258  7258 D AppUp4:CustModeStarterReceiver: begin check event
09-01 11:01:23.186  7258  7258 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-01 11:01:23.194  7924  7954 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-01 11:01:23.195  7924  7954 W AudioCapabilities: Unsupported mime audio/qcelp
09-01 11:01:23.198  7924  7954 W AudioCapabilities: Unsupported mime audio/evrc
,09-01 11:01:23.208  7924  7954 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-01 11:01:23.214  7924  7954 W VideoCapabilities: Unsupported mime video/divx
,09-01 11:01:23.217  7924  7954 W VideoCapabilities: Unsupported mime video/divx311
09-01 11:01:23.219  7924  7954 W VideoCapabilities: Unsupported mime video/divx4
09-01 11:01:23.224  7924  7954 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-01 11:01:23.232  1035  2005 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7962 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-01 11:01:23.237  1035  2051 I ActivityManager: Killing 6808:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-01 11:01:23.254  7117  7117 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-01 11:01:23.254  7117  7117 W System.err: android.os.DeadObjectException
09-01 11:01:23.254  7117  7117 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-01 11:01:23.254  7117  7117 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-01 11:01:23.254  7117  7117 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-01 11:01:23.254  7117  7117 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-01 11:01:23.254  7117  7117 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-01 11:01:23.254  7117  7117 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-01 11:01:23.254  7117  7117 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 11:01:23.254  7117  7117 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 11:01:23.254  7117  7117 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:01:23.254  7117  7117 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-01 11:01:23.254  7117  7117 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:01:23.254  7117  7117 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:01:23.254  7117  7117 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-01 11:01:23.254  7117  7117 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-01 11:01:23.254  7117  7117 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-01 11:01:23.255  7117  7117 W System.err: android.os.DeadObjectException
09-01 11:01:23.255  7117  7117 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-01 11:01:23.255  7117  7117 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-01 11:01:23.255  7117  7117 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-01 11:01:23.255  7117  7117 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-01 11:01:23.255  7117  7117 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-01 11:01:23.255  7117  7117 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-01 11:01:23.255  7117  7117 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 11:01:23.255  7117  7117 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 11:01:23.255  7117  7117 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:01:23.255  7117  7117 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-01 11:01:23.255  7117  7117 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:01:23.255  7117  7117 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:01:23.255  7117  7117 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-01 11:01:23.255  7117  7117 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-01 11:01:23.255  7117  7117 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,09-01 11:01:23.258  7117  7117 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-01 11:01:23.261  7924  7954 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-01 11:01:23.266  7924  7954 W AudioCapabilities: Unsupported mime audio/eac3
09-01 11:01:23.266  7924  7954 W AudioCapabilities: Unsupported mime audio/ac3
09-01 11:01:23.267  7924  7954 W AudioCapabilities: Unsupported mime audio/g726
,09-01 11:01:23.268  7924  7954 W AudioCapabilities: Unsupported mime audio/wma-voice
09-01 11:01:23.269  7924  7954 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-01 11:01:23.270  7924  7954 W AudioCapabilities: Unsupported mime audio/adpcm
09-01 11:01:23.272  7924  7954 W VideoCapabilities: Unsupported mime video/theora
09-01 11:01:23.274  7924  7954 W VideoCapabilities: Unsupported mime video/mjpg
09-01 11:01:23.444  1035  2051 E libprocessgroup: failed to kill 1 processes for processgroup 6808
,09-01 11:01:23.586  1035  1958 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-01 11:01:23.609  7117  7117 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-01 11:01:23.609  7117  7117 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-01 11:01:23.614  1035  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{350c15e9 type 2 when 227751 com.google.android.gms} when 227751
09-01 11:01:23.666  1035  1995 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7986 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-01 11:01:23.669  7117  7117 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-01 11:01:23.678  7962  7962 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 11:01:23.680  7962  7962 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:01:23.680  7962  7962 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-01 11:01:23.682  7962  7962 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-01 11:01:23.682  7962  7962 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-01 11:01:23.756  7986  7986 D UEI.SmartControl: Quickset Services start...
,09-01 11:01:23.757  7962  7962 I SystemConfig: BUILD Country: EU
09-01 11:01:23.758  7962  7962 I SystemConfig: BUILD Operator: OPEN
09-01 11:01:23.758  7986  7986 I UEI.SmartControl: Manufacture = LGE
09-01 11:01:23.758  7986  7986 D UEI.SmartControl: Id = LGNevo
,09-01 11:01:23.759  7986  7986 D UEI.SmartControl: File observer start...
09-01 11:01:23.760  7986  7986 E UEI.SmartControl: IR Port is disabled: false
,09-01 11:01:23.760  7986  7986 D UEI.SmartControl: Starting file observer...
09-01 11:01:23.760  7986  7986 D UEI.SmartControl: Extracting JNI libs...
09-01 11:01:23.760  7986  7986 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only,
09-01 11:01:23.803  1035  1967 I ActivityManager: Killing 7117:com.lge.qremote/u0a112 (adj 15): empty #17
,09-01 11:01:23.843  7986  7986 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,09-01 11:01:23.843  7986  7986 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,09-01 11:01:23.844  7986  7986 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-01 11:01:23.875  7986  7986 I UEI.SmartControl: --- Selecting new region: 6
09-01 11:01:23.877  7986  7986 I UEI.SmartControl: Model = LG-D855
,09-01 11:01:23.879  7986  7986 D UEI.SmartControl: QS Service created
,09-01 11:01:23.890  1035  1995 W libprocessgroup: failed to open /acct/uid_10112/pid_7117/cgroup.procs: No such file or directory
,09-01 11:01:23.906  7962  8010 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-01 11:01:23.906  7962  8010 I SystemConfig: existFile = false
09-01 11:01:23.906  7962  8010 I SystemConfig: canReadFile = false
09-01 11:01:23.909  7962  8010 I SystemConfig: systemFeature RCS result false
09-01 11:01:23.909  7962  8010 D SystemConfig: refreshRcsSupport() :false
,09-01 11:01:23.926  7986  7986 I UEI.SmartControl: Service initServices...
09-01 11:01:23.931  7986  7986 D UEI.SmartControl: QS start get config
,09-01 11:01:23.954  1035  1967 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8013 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-01 11:01:24.005  8013  8013 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 11:01:24.005  8013  8013 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-01 11:01:24.005  8013  8013 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-01 11:01:24.006  8013  8013 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-01 11:01:24.013  7986  7986 D UEI.SmartControl: Loading JNI Libs...
09-01 11:01:24.096  8013  8013 I AppConfig: Total System Memory = 2995761152
,09-01 11:01:24.106  8013  8013 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-01 11:01:24.182  1035  1918 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8038 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 11:01:24.183  1035  1918 I ActivityManager: Killing 7285:com.lge.email/u0a23 (adj 15): empty #17
,09-01 11:01:24.251  7986  7986 I UEI.SmartControl: Supports setup maps: true
,09-01 11:01:24.254  7986  7986 D UEI.SmartControl: QS start statue = true Error code = 0
09-01 11:01:24.254  7986  7986 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-01 11:01:24.254  7986  7986 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-01 11:01:24.254  7986  7986 I UEI.SmartControl: ### init IR Blaster...
09-01 11:01:24.259  7986  7986 D serial_port: Configuring serial port
09-01 11:01:24.261  7986  7986 E UEI.SmartControl: UEIBLaster setting for 616
09-01 11:01:24.262  7986  7986 I UEI.SmartControl: Setting serial record hearder size = 2
09-01 11:01:24.262  7986  7986 I UEI.SmartControl: configuring settings for MAXQ616
09-01 11:01:24.262  7986  7986 I UEI.SmartControl: Get version...
09-01 11:01:24.268  1035  1050 W libprocessgroup: failed to open /acct/uid_10023/pid_7285/cgroup.procs: No such file or directory
,09-01 11:01:24.281  7986  8055 D UEI.SmartControl: serial port data available: 21
,09-01 11:01:24.308  7986  7986 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-01 11:01:24.308  7986  7986 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-01 11:01:24.308  7986  7986 I UEI.SmartControl: QS saving settings...
09-01 11:01:24.309  7986  7986 D UEI.SmartControl: IR Blaster version: 25672567
,09-01 11:01:24.322  7986  8055 D UEI.SmartControl: serial port data available: 4
,09-01 11:01:24.356  7986  8059 I UEI.SmartControl: Device manager: loading config....
,09-01 11:01:24.359  7986  7986 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-01 11:01:24.359  7986  8059 D UEI.SmartControl: ----------- loading internal config...
09-01 11:01:24.368  7986  7986 E UEI.SmartControl: Services init done
09-01 11:01:24.368  7986  7986 D UEI.SmartControl: QS Service init finished
09-01 11:01:24.369  7986  7986 D UEI.SmartControl: QS Service version name: 2.1.91
09-01 11:01:24.370  7986  7986 D UEI.SmartControl: QS Service version code: 201091
09-01 11:01:24.370  7986  7986 D UEI.SmartControl: Service requested: Control
,09-01 11:01:24.376  7986  8059 E UEI.SmartControl: Loading SETTINGS...
,09-01 11:01:24.380  7986  7986 D UEI.SmartControl: Request IControl service: devices are loaded...
09-01 11:01:24.382  7986  7986 D UEI.SmartControl: Service.onUnbind: IControl
,09-01 11:01:24.389  7986  7986 D UEI.SmartControl: Service.onDestroy
09-01 11:01:24.389  7986  7986 D UEI.SmartControl: Lock is in USE false
09-01 11:01:24.390  7986  7986 D UEI.SmartControl: unbind internal service
09-01 11:01:24.392  7986  7986 D serial_port: close(fd = 25)
09-01 11:01:24.393  7986  8059 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-01 11:01:24.395  7986  8058 I UEI.SmartControl: Notify AllClients services are ready: 0
09-01 11:01:24.396  7986  8058 D UEI.SmartControl: -----service ready thread exits
09-01 11:01:24.397  7986  7986 I UEI.SmartControl: Serial port is closed.
09-01 11:01:24.397  7986  7986 I UEI.SmartControl: Serial port is closed.
09-01 11:01:24.398  7986  7986 D UEI.SmartControl: Blaster closed
,09-01 11:01:24.400  7986  7986 D UEI.SmartControl: Shut down QS...
09-01 11:01:24.400  7986  7986 D UEI.SmartControl: Stopping QS lib
09-01 11:01:24.400  7986  7986 D UEI.SmartControl: QS lib stop result = true
09-01 11:01:24.400  7986  7986 D UEI.SmartControl: Stopped QS lib
09-01 11:01:24.400  7986  7986 D UEI.SmartControl: Stopped file observer...
09-01 11:01:24.400  7986  7986 D UEI.SmartControl: QS shutdown complete
09-01 11:01:24.401  7986  7986 D UEI.SmartControl: QS Service created
09-01 11:01:24.411  7986  7986 I UEI.SmartControl: Service initServices...
09-01 11:01:24.411  7986  7986 D UEI.SmartControl: QS start get config
09-01 11:01:24.482  8038  8038 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-01 11:01:24.599  8038  8038 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:01:24.600  8038  8038 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:01:24.646  8038  8038 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-01 11:01:24.659  7986  7986 I UEI.SmartControl: Supports setup maps: true
,09-01 11:01:24.661  7986  7986 D UEI.SmartControl: QS start statue = true Error code = 0
,09-01 11:01:24.662  7986  7986 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-01 11:01:24.662  7986  7986 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-01 11:01:24.662  7986  7986 I UEI.SmartControl: ### init IR Blaster...
09-01 11:01:24.665  7986  7986 D serial_port: Configuring serial port
09-01 11:01:24.665  7986  7986 E UEI.SmartControl: UEIBLaster setting for 616
09-01 11:01:24.665  7986  7986 I UEI.SmartControl: Setting serial record hearder size = 2
09-01 11:01:24.665  7986  7986 I UEI.SmartControl: configuring settings for MAXQ616
,09-01 11:01:24.665  7986  7986 I UEI.SmartControl: Get version...
09-01 11:01:24.665  8038  8038 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-01 11:01:24.666  8038  8038 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-01 11:01:24.679  8038  8038 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:01:24.679  8038  8038 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-01 11:01:24.688  7986  8080 D UEI.SmartControl: serial port data available: 21
,09-01 11:01:24.706  1035  2051 I ActivityManager: Killing 7161:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-01 11:01:24.713  7986  7986 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-01 11:01:24.713  7986  7986 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-01 11:01:24.713  7986  7986 I UEI.SmartControl: QS saving settings...
09-01 11:01:24.714  7986  7986 D UEI.SmartControl: IR Blaster version: 25672567
09-01 11:01:24.730  7986  8080 D UEI.SmartControl: serial port data available: 4
,09-01 11:01:24.749  1035  1050 W libprocessgroup: failed to open /acct/uid_10026/pid_7161/cgroup.procs: No such file or directory
,09-01 11:01:24.756  3401  4242 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-01 11:01:24.757  7986  7986 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-01 11:01:24.761  7986  8088 I UEI.SmartControl: Device manager: loading config....
09-01 11:01:24.761  7986  7986 E UEI.SmartControl: Services init done
09-01 11:01:24.761  7986  7986 D UEI.SmartControl: QS Service init finished
09-01 11:01:24.761  7986  8088 D UEI.SmartControl: ----------- loading internal config...
,09-01 11:01:24.763  5122  8086 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-01 11:01:24.765  7986  7986 D UEI.SmartControl: QS Service version name: 2.1.91
09-01 11:01:24.765  7986  7986 D UEI.SmartControl: QS Service version code: 201091
09-01 11:01:24.766  7986  7986 D UEI.SmartControl: Service requested: Control
,09-01 11:01:24.767  3401  4242 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3c8a8e3f on behalf of 8038
,09-01 11:01:24.771  7986  7986 D UEI.SmartControl: Request IControl service: devices are loaded...
09-01 11:01:24.772  7986  8088 E UEI.SmartControl: Loading SETTINGS...
09-01 11:01:24.777  7986  8088 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-01 11:01:24.790  7986  8087 I UEI.SmartControl: Notify AllClients services are ready: 0
09-01 11:01:24.790  7986  8087 D UEI.SmartControl: -----service ready thread exits
,09-01 11:01:24.816  1035  1995 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8090 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
09-01 11:01:24.819  1035  1995 I ActivityManager: Killing 6563:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-01 11:01:24.820  7986  7986 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@3ef7ff67 that was originally bound here
09-01 11:01:24.820  7986  7986 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@3ef7ff67 that was originally bound here
09-01 11:01:24.820  7986  7986 E ActivityThread: ,	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,09-01 11:01:24.820  7986  7986 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-01 11:01:24.820  7986  7986 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-01 11:01:24.971  1035  2051 W libprocessgroup: failed to open /acct/uid_1000/pid_6563/cgroup.procs: No such file or directory
,09-01 11:01:24.991  7986  7986 D UEI.SmartControl: Internal service binding...
,09-01 11:01:25.012  8038  8038 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-01 11:01:25.033  8038  8038 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-01 11:01:25.044  8090  8090 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
09-01 11:01:25.068  8090  8090 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-01 11:01:25.068  8090  8090 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-01 11:01:25.068  8090  8090 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-01 11:01:25.069  8090  8090 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-01 11:01:25.069  8090  8090 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-01 11:01:25.069  8090  8090 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-01 11:01:25.081   308  8112 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-01 11:01:25.081  1035  1102 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-01 11:01:25.090  1035  1050 I ActivityManager: Killing 7337:com.google.android.setupwizard/u0a46 (adj 15): empty #17
09-01 11:01:25.119  1035  1995 W libprocessgroup: failed to open /acct/uid_10046/pid_7337/cgroup.procs: No such file or directory
,09-01 11:01:25.386  7986  8062 D UEI.SmartControl: Internal timer expired: 2
,09-01 11:01:25.409  1035  1958 I art     : Explicit concurrent mark sweep GC freed 31369(1483KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 4.237ms total 187.877ms
,09-01 11:01:25.516  1035  2031 V SIM_STK : Menu title from STK is T-Mobile
,09-01 11:01:25.538  5122  8086 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 774 ms] updated apps [took 774 ms] 
,09-01 11:01:25.540  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:25.540  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@266debe5 added. We now have 6 listener(s)
09-01 11:01:25.540  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:25.542  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:25.542  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32cb66ba added. We now have 7 listener(s)
,09-01 11:01:25.542  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:25.543  6931  7010 I System.out: IsBluetoothEnabled
09-01 11:01:25.544  1035  1699 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:25.544  1035  1699 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-01 11:01:25.544  1035  1105 D BluetoothManagerService: Message: 2
09-01 11:01:25.547  6931  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:01:25.548  1035  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:25.548  1035  1577 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-01 11:01:25.560  1035  1105 D BluetoothManagerService: Message: 1
09-01 11:01:25.560  1035  1105 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-01 11:01:25.560  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:01:25.561  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:01:25.561  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-01 11:01:25.580  1035  1105 D BluetoothManagerService: Message: 20
,09-01 11:01:25.580  1035  1105 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@199c0aa6:true
09-01 11:01:25.581  7886  7886 D BluetoothAdapterState: make
09-01 11:01:25.586  7886  7886 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-01 11:01:25.586  7886  7886 I bluedroid-qcom: init
09-01 11:01:25.587  7886  8119 I BluetoothAdapterState: Entering OffState
09-01 11:01:25.587  7886  7886 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-01 11:01:25.588  7886  7886 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-01 11:01:25.588  7886  7886 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 11:01:25.588  7886  7886 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-01 11:01:25.588  7886  7886 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-01 11:01:25.588  7886  7886 I bluedroid-qcom: get_profile_interface socket
09-01 11:01:25.588  7886  7886 I bluedroid-qcom: get_profile_interface map_client
09-01 11:01:25.579  8123  8123 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:25.579  8123  8123 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:25.592  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-01 11:01:25.595  7886  8122 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-01 11:01:25.596  1035  1105 D BluetoothManagerService: Message: 40
09-01 11:01:25.596  1035  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-01 11:01:25.598  7886  7903 I bluedroid-qcom: config_hci_snoop_log
,09-01 11:01:25.598  8123  8123 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-01 11:01:25.599  8123  8123 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-01 11:01:25.599  8123  8123 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-01 11:01:25.599  8123  8123 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-01 11:01:25.599  1035  1105 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-01 11:01:25.599  1035  1105 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-01 11:01:25.604  8123  8123 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-01 11:01:25.604  8123  8123 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-01 11:01:25.605  7886  8122 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-01 11:01:25.609  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-01 11:01:25.609  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-01 11:01:25.610  7886  8122 D BluetoothAdapterProperties: Name is: G3
09-01 11:01:25.611  7886  8119 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-01 11:01:25.611  7886  8119 D BluetoothAdapterProperties: Setting state to 11
09-01 11:01:25.611  7886  8119 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-01 11:01:25.612  1035  1105 D BluetoothManagerService: Message: 60
09-01 11:01:25.612  1035  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-01 11:01:25.612  1035  1105 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-01 11:01:25.612  7886  8119 I LGBluetoothServiceJni: classInitNative: succeeds
09-01 11:01:25.613  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:25.616  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:01:25.619  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:01:25.620  7068  7068 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-01 11:01:25.625  7886  7886 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:01:25.625  7886  7886 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:25.625  7886  7886 V BluetoothPbapReceiver: ***********state = 11
09-01 11:01:25.629  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:01:25.631  7886  8119 D BluetoothBondStateMachine: make
,09-01 11:01:25.640  7886  8119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f31f726
09-01 11:01:25.640  7886  8125 I BluetoothBondStateMachine: StableState(): Entering Off State
09-01 11:01:25.640  7886  8119 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-01 11:01:25.640  7886  8119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f31f726
09-01 11:01:25.640  7886  8119 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-01 11:01:25.641  7886  8119 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-01 11:01:25.644  7886  8119 E BluetoothAdapterService: File transfer profiles supported!!
,09-01 11:01:25.647  7068  7068 D BluetoothPermissionRequest: onReceive
09-01 11:01:25.651  7068  7068 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:01:25.660  7886  7886 D HeadsetService: Received start request. Starting profile...
09-01 11:01:25.661  7886  7886 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 11:01:25.661  7886  7886 D LGBluetoothHfpAdapter: Version 1.6
09-01 11:01:25.662  7886  8119 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:01:25.664  7886  7886 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-01 11:01:25.665  7886  7886 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 11:01:25.667  7886  8119 E BluetoothAdapterService: File transfer profiles supported!!
,09-01 11:01:25.669  7886  7886 D HeadsetStateMachine: make
09-01 11:01:25.672  7886  8119 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:01:25.677  7886  8119 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:01:25.682  7886  8119 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:01:25.686  7886  8119 E BluetoothAdapterService: File transfer profiles supported!!
,09-01 11:01:25.701  7886  8119 V LGMDMManager: Create singleton instance
,09-01 11:01:25.704  7886  8119 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-01 11:01:25.709  7886  7886 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:01:25.709  7886  7886 D LgDataFeature: LgDataFeature() Constructor Done, null
09-01 11:01:25.712  7886  7886 D HeadsetStateMachine: max_hf_connections = 1
09-01 11:01:25.713  7886  7886 I bluedroid-qcom: get_profile_interface handsfree
,09-01 11:01:25.714  7886  7886 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-01 11:01:25.714   312  1397 V AudioPolicyService: registerClient() client 0xb57c6da0, uid 1002
09-01 11:01:25.715   312  1398 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-01 11:01:25.715   312  1398 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:01:25.715   312  1398 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:01:25.715  7886  7886 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-01 11:01:25.715   312   312 V AudioFlinger: registerClient() client 0xb5581748, pid 7886
09-01 11:01:25.716   312  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:01:25.716   312  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:01:25.716  1854  3452 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:01:25.716  1854  3452 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:01:25.716  7886  7886 V ToneGenerator: Create Track: 0xb4928080
09-01 11:01:25.716  7886  7886 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-01 11:01:25.716  7886  7886 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-01 11:01:25.716  7886  7902 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:01:25.716  7886  7902 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
,09-01 11:01:25.716  1035  1684 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:01:25.716  1035  1684 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:01:25.716   312  2185 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-01 11:01:25.716   312  2185 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-01 11:01:25.716   312  2185 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:01:25.716   312  2185 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:01:25.716  7886  7886 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-01 11:01:25.716  3219  3237 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:01:25.716  3219  3237 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:01:25.717   312  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:01:25.717   312  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:01:25.717  1604  3335 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:01:25.717  1604  3335 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:01:25.717  1035  1050 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:01:25.717  1035  1050 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:01:25.717  7886  8124 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:01:25.717  7886  8124 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-01 11:01:25.717   312  2185 I AudioFlinger: isAudioPlaybackHookOn() false
09-01 11:01:25.717  3219  3241 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:01:25.717   312   312 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-01 11:01:25.717  3219  3241 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:01:25.717   312   312 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-01 11:01:25.717   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:01:25.717   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:01:25.718  7886  7886 V AudioSystem: getLatency() output 2, latency 50
09-01 11:01:25.718  7886  7886 V AudioSystem: getFrameCount() output 2, frameCount 960
09-01 11:01:25.718  7886  7886 V AudioTrack: createTrack_l() output 2 afLatency 50
09-01 11:01:25.718   312  2186 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-01 11:01:25.718   312  2186 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-01 11:01:25.718   312  2186 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-01 11:01:25.718   312  2186 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-01 11:01:25.718   312  2186 V AudioFlinger: createTrack() lSessionId: 23
09-01 11:01:25.718  1604  2205 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:01:25.718  1604  2205 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:01:25.718  1854  4521 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:01:25.718  1854  4521 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:01:25.719  7886  7886 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-01 11:01:25.719   312  2186 V AudioFlinger: acquiring 23 from 7886, for 7886
09-01 11:01:25.719   312  2186 V AudioFlinger:  added new entry for 23
09-01 11:01:25.719  7886  7886 V ToneGenerator: ToneGenerator INIT OK, time: 230133
09-01 11:01:25.719  7886  7886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f31f726
09-01 11:01:25.720  7886  8126 D HeadsetStateMachine: Enter Di,sconnected: -2, size: 0
09-01 11:01:25.720  7886  8126 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:01:25.720  7886  8126 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:01:25.720  7886  8126 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-01 11:01:25.720   312  1398 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7886
09-01 11:01:25.721   312  1398 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-01 11:01:25.721   312  1398 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-01 11:01:25.721   312  1398 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-01 11:01:25.721   312  1398 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-01 11:01:25.721   312  1398 V voice   : voice_set_parameters: exit with code(0)
09-01 11:01:25.721   312  1398 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-01 11:01:25.721   312  1398 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-01 11:01:25.721   312  1398 V msm8974_platform: platform_set_parameters: exit with code(0)
09-01 11:01:25.721   312  1398 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-01 11:01:25.721   312  1398 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-01 11:01:25.721   312  1398 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-01 11:01:25.721  7886  8126 V ToneGenerator: ToneGenerator destructor
09-01 11:01:25.721  7886  8126 V ToneGenerator: stopTone
09-01 11:01:25.721  7886  8126 V ToneGenerator: Delete Track: 0xb4928080
09-01 11:01:25.721  7886  8126 V AudioTrack: ~AudioTrack, releasing session id from 7886 on behalf of 7886
09-01 11:01:25.721   312  2186 V AudioFlinger: releasing 23 from 7886 for 7886
09-01 11:01:25.721   312  2186 V AudioFlinger:  decremented refcount to 0
09-01 11:01:25.721   312  2186 V AudioFlinger: purging stale effects
09-01 11:01:25.722   312  2186 V AudioPolicyService: AudioCommandThread() adding release output 2
09-01 11:01:25.722   312  2186 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-01 11:01:25.722   312  1256 V AudioPolicyService: AudioCommandThread() waking up
09-01 11:01:25.722   312  1256 V AudioPolicyService: AudioCommandThread() processing release output 2
09-01 11:01:25.722   312  1256 V AudioPolicyManager: releaseOutput() 2
09-01 11:01:25.722   312  1256 V AudioPolicyService: AudioCommandThread() going to sleep
09-01 11:01:25.722   312  2186 V AudioFlinger: PlaybackThread::Track destructor
09-01 11:01:25.722   312  2186 V AudioFlinger: removeClient_l() pid 7886, calling pid 312
09-01 11:01:25.723  7886  7886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f31f726
09-01 11:01:25.725  7886  7886 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:01:25.731  7886  7886 D A2dpService: Received start request. Starting profile...
,09-01 11:01:25.731  1035  1962 W Process : Unable to open /proc/8135/status
09-01 11:01:25.732  7886  7886 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 11:01:25.733  7886  7886 V Avrcp   : make
09-01 11:01:25.733  7886  7886 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-01 11:01:25.733  7886  7886 I bluedroid-qcom: get_profile_interface avrcp
09-01 11:01:25.740  7886  7886 V AudioManager: registerRemoteController: size of Media player list: 0
,09-01 11:01:25.741  7886  7886 E AudioManager: No RCC entry present to update
09-01 11:01:25.741  7886  7886 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-01 11:01:25.743  7886  7886 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-01 11:01:25.744  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-01 11:01:25.744  7886  7886 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-01 11:01:25.747  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-01 11:01:25.857  1035  1918 V SIM_STK : Menu title from STK is T-Mobile
09-01 11:01:25.857  1035  1918 V SIM_STK : Menu title from STK is T-Mobile
,09-01 11:01:26.002  1035  1962 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-01 11:01:26.017  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-01 11:01:26.037  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,09-01 11:01:26.039  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,09-01 11:01:26.039  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,09-01 11:01:26.040  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-01 11:01:26.040  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:01:26.040  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-01 11:01:26.040  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-01 11:01:26.040  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-01 11:01:26.041  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:01:26.041  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,09-01 11:01:26.043  7886  7886 I BluetoothA2dpServiceJni: classInitNative
09-01 11:01:26.043  7886  7886 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 11:01:26.043  7886  7886 D A2dpStateMachine: make
09-01 11:01:26.050  7886  7886 I bluedroid-qcom: get_profile_interface a2dp
09-01 11:01:26.050  7886  8148 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-01 11:01:26.054  7886  7886 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-01 11:01:26.054  7886  7886 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-01 11:01:26.055  7886  7886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f31f726
09-01 11:01:26.056  7886  7886 I BluetoothHidServiceJni: classInitNative: succeeds
09-01 11:01:26.058  7886  8147 D A2dpStateMachine: Enter Disconnected: -2
,09-01 11:01:26.064  7886  7886 D HidService: Received start request. Starting profile...
09-01 11:01:26.064  7886  7886 I bluedroid-qcom: get_profile_interface hidhost
09-01 11:01:26.064  7886  7886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f31f726
09-01 11:01:26.065  7886  7886 I BluetoothHealthServiceJni: classInitNative: succeeds
09-01 11:01:26.067  7886  7886 D HealthService: Received start request. Starting profile...
09-01 11:01:26.070  7886  7886 I bluedroid-qcom: get_profile_interface health
09-01 11:01:26.071  7886  7886 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-01 11:01:26.071  7886  7886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f31f726
09-01 11:01:26.073  7886  7886 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-01 11:01:26.077  7886  7886 D PanService: Received start request. Starting profile...
09-01 11:01:26.077  7886  7886 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 11:01:26.077  7886  7886 I bluedroid-qcom: get_profile_interface pan
09-01 11:01:26.088  7886  7886 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-01 11:01:26.088  7886  7886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f31f726
,09-01 11:01:26.089  7886  7886 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-01 11:01:26.096  7886  7886 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 11:01:26.096  7886  7886 D BtGatt.GattService: Received start request. Starting profile...
09-01 11:01:26.096  7886  7886 D BtGatt.GattService: start()
09-01 11:01:26.096  7886  7886 I bluedroid-qcom: get_profile_interface gatt
09-01 11:01:26.097  7886  7886 D BtGatt.AdvertiseManager: advertise manager created
09-01 11:01:26.103  7886  7886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f31f726
,09-01 11:01:26.105  7886  7886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f31f726
09-01 11:01:26.106  7886  7886 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-01 11:01:26.107  7886  7886 V BluetoothMapService: BluetoothMapBinder()
09-01 11:01:26.108  7886  7886 D BluetoothMapService: Received start request. Starting profile...
09-01 11:01:26.108  7886  7886 D BluetoothMapService: start()
09-01 11:01:26.112  7886  7886 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-01 11:01:26.112  7886  7886 D BluetoothMapEmailAppObserver: createReceiver()
09-01 11:01:26.113  7886  7886 D BluetoothMapEmailAppObserver: initObservers()
09-01 11:01:26.113  7886  7886 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-01 11:01:26.123  7886  7886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f31f726
,09-01 11:01:26.123  7886  7886 D HeadsetStateMachine: Proxy object connected
09-01 11:01:26.124  7886  7886 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-01 11:01:26.124  7886  7886 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-01 11:01:26.126  7886  8126 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-01 11:01:26.128  7886  8126 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-01 11:01:26.132  7886  8126 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-01 11:01:26.134  7886  7886 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:01:26.134  7886  7886 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:01:26.134  7886  7886 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:01:26.134  7886  7886 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:01:26.134  7886  7886 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:26.134  7886  7886 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,09-01 11:01:26.140  7886  7886 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:01:26.144  7886  7886 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:01:26.147  7886  7886 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-01 11:01:26.147  7886  7886 V PanService: [BTUI] SIM Extra State :ABSENT
09-01 11:01:26.151  7886  7886 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:01:26.154  7886  7886 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-01 11:01:26.154  7886  7886 V BluetoothMapService: Handler(): got msg=1
09-01 11:01:26.156  7886  8119 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-01 11:01:26.156  7886  8119 I bluedroid-qcom: enable
09-01 11:01:26.156  7886  8119 I bt_hci_bdroid: init
09-01 11:01:26.158  7886  8155 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-01 11:01:26.158  7886  8155 I bt-btu  : btu_task pending for preload complete event
09-01 11:01:26.158  7886  8119 I bt_vendor: bt-vendor : init
09-01 11:01:26.158  7886  8119 I bt_vendor: bt-vendor : get_bt_soc_type
09-01 11:01:26.158  7886  8119 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-01 11:01:26.158  7886  8119 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-01 11:01:26.158  7886  8119 D bt_userial_mct: userial_init
,09-01 11:01:26.159  7886  8119 D bt_hci_bdroid: set_power 1
,09-01 11:01:26.159  7886  8119 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-01 11:01:26.159  7886  8119 I bt_vendor: Starting hciattach daemon
09-01 11:01:26.159  7886  8119 I bt_vendor: try to set true
09-01 11:01:26.149  8158  8158 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:26.149  8158  8158 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:26.187  8159  8159 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-01 11:01:26.260  8165  8165 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-01 11:01:26.274  8166  8166 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-01 11:01:26.301  8168  8168 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-01 11:01:26.314  8169  8169 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-01 11:01:26.327  8170  8170 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-01 11:01:26.340  8171  8171 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-01 11:01:26.379  8173  8173 I libmdmdetect: ESOC framework not supported
09-01 11:01:26.380  8173  8173 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-01 11:01:26.388  8173  8173 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-01 11:01:26.388  8173  8173 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-01 11:01:26.388  8173  8173 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-01 11:01:26.388  8173  8173 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-01 11:01:26.388  8173  8173 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-01 11:01:26.388  8173  8173 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-01 11:01:26.388  8173  8173 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-01 11:01:26.424  8173  8174 E QC-QMI  : qmi_client [8173] 15: failed to locate client data
,09-01 11:01:26.426   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,09-01 11:01:26.426   484   484 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
09-01 11:01:26.468  8175  8175 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-01 11:01:26.482  8176  8176 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-01 11:01:26.516  7886  8119 I bt_vendor: bluetooth satus is on
09-01 11:01:26.516  7886  8119 D bt_hci_bdroid: preload
,09-01 11:01:26.516  7886  8157 D bt_userial_mct: userial_open(port:0)
,09-01 11:01:26.516  7886  8157 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-01 11:01:26.520  7886  8157 I bt_vendor: Done intiailizing UART
09-01 11:01:26.523  7886  8157 I bt_vendor: Done intiailizing UART
09-01 11:01:26.523  7886  8157 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-01 11:01:26.523  7886  8157 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-01 11:01:26.523  7886  8178 D bt_userial_mct: Entering userial_read_thread()
09-01 11:01:26.524  7886  8155 I bt-btu  : btu_task received preload complete event
09-01 11:01:26.524  7886  8155 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-01 11:01:26.524  7886  8155 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-01 11:01:26.530  7886  8155 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-01 11:01:26.541  7886  8155 I         : BTE_InitTraceLevels -- TRC_HCI
09-01 11:01:26.541  7886  8155 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 11:01:26.541  7886  8155 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-01 11:01:26.541  7886  8155 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 11:01:26.541  7886  8155 I         : BTE_InitTraceLevels -- TRC_AVRC
09-01 11:01:26.541  7886  8155 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 11:01:26.541  7886  8155 I         : BTE_InitTraceLevels -- TRC_BNEP
09-01 11:01:26.541  7886  8155 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 11:01:26.542  7886  8155 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-01 11:01:26.542  7886  8155 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 11:01:26.542  7886  8155 I         : BTE_InitTraceLevels -- TRC_PAN
09-01 11:01:26.542  7886  8155 I         : BTE_InitTraceLevels -- TRC_SDP
09-01 11:01:26.542  7886  8155 I         : BTE_InitTraceLevels -- TRC_GATT
09-01 11:01:26.542  7886  8155 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 11:01:26.542  7886  8155 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 11:01:26.542  7886  8155 I         : BTE_InitTraceLevels -- TRC_BTIF
09-01 11:01:26.616  7886  8155 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-01 11:01:26.616  7886  8155 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f6061 
09-01 11:01:26.616  7886  8155 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f6061 
,09-01 11:01:26.634  7886  8122 E bt-btif : Calling BTA_HhEnable
09-01 11:01:26.634  7886  8122 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-01 11:01:26.635  7886  8122 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-01 11:01:26.637  7886  8155 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-01 11:01:26.638  7886  8155 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-01 11:01:26.638  7886  8155 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-01 11:01:26.639  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-01 11:01:26.639  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-01 11:01:26.640  7886  8155 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-01 11:01:26.640  7886  8155 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-01 11:01:26.640  7886  8122 D BluetoothAdapterProperties: Name is: G3
09-01 11:01:26.641  7886  8122 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:01:26.641  7886  8122 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:01:26.642  7886  8122 D bt_hci_bdroid: postload
09-01 11:01:26.642  7886  8157 D bt_hci_bdroid: Used up Tx Cmd credits
09-01 11:01:26.643  7886  8122 D bte_conf: Device ID record 1 : primary
09-01 11:01:26.643  7886  8122 D bte_conf:   vendorId            = 00c4
09-01 11:01:26.643  7886  8122 D bte_conf:   vendorIdSource      = 0001
09-01 11:01:26.643  7886  8122 D bte_conf:   product             = 13a1
09-01 11:01:26.643  7886  8122 D bte_conf:   version             = 1000
09-01 11:01:26.643  7886  8122 D bte_conf:   clientExecutableURL = 
09-01 11:01:26.643  7886  8122 D bte_conf:   serviceDescription  = 
09-01 11:01:26.643  7886  8122 D bte_conf:   documentationURL    = 
09-01 11:01:26.643  7886  8122 D bte_conf: bte_load_did_conf no section named DID2.
09-01 11:01:26.644  7886  8155 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-01 11:01:26.644  7886  8157 D bt_hci_bdroid: Used up Tx Cmd credits
09-01 11:01:26.649  7886  8157 D bt_hci_bdroid: Used up Tx Cmd credits
,09-01 11:01:26.655  7886  8157 D bt_hci_bdroid: Used up Tx Cmd credits
09-01 11:01:26.657  7886  8119 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-01 11:01:26.657  7886  8119 D BluetoothAdapterProperties: ScanMode =  20
09-01 11:01:26.658  7886  8119 D BluetoothAdapterProperties: State =  11
09-01 11:01:26.649  8183  8183 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:26.649  8183  8183 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:26.660  7886  8119 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-01 11:01:26.661  7886  8119 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-01 11:01:26.661  7886  8119 D BluetoothAdapterProperties: Setting state to 12
09-01 11:01:26.661  7886  8119 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-01 11:01:26.661  7886  8122 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-01 11:01:26.662  7886  8122 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-01 11:01:26.680  1035  1105 D BluetoothManagerService: Message: 60
09-01 11:01:26.680  1035  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-01 11:01:26.680  1035  1105 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,09-01 11:01:26.683  7886  8119 I BluetoothAdapterState: Entering On State
09-01 11:01:26.688  7886  8178 E bt_mct  : hci lib postload completed
09-01 11:01:26.699  7886  8155 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:01:26.699  7886  8155 W bt-smp  : Plain text(LSB ~ MSB) = 18 b7 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:01:26.699  7886  8155 W bt-smp  : Encrypted text(LSB ~ MSB) = ad f6 2e 22 7e bf 21 18 3c 10 02 dd e2 eb d2 79 
,09-01 11:01:26.702  7886  8155 W bt-btm  : Stopping oneshot timer
09-01 11:01:26.727  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:26.727  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:26.727  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:26.727  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:01:26.727  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:01:26.727  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:26.727  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:26.727  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:01:26.734  7886  8122 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:01:26.735  7886  8122 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-01 11:01:26.741  7886  8155 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:01:26.741  7886  8155 W bt-smp  : Plain text(LSB ~ MSB) = c6 d3 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:01:26.741  7886  8155 W bt-smp  : Encrypted text(LSB ~ MSB) = 87 df f0 1e 60 13 0b 87 63 e9 69 79 e2 d3 25 36 
,09-01 11:01:26.744  7886  8155 W bt-btm  : Stopping oneshot timer
09-01 11:01:26.748  7886  8119 D LGBluetoothServiceAdapter: [BTUI] OnState
09-01 11:01:26.748  7886  8119 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-01 11:01:26.748  7886  8119 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-01 11:01:26.753  7886  8119 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-01 11:01:26.753  7886  8119 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-01 11:01:26.761  7886  8155 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:01:26.761  7886  8155 W bt-smp  : Plain text(LSB ~ MSB) = 94 1a 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:01:26.761  7886  8155 W bt-smp  : Encrypted text(LSB ~ MSB) = b4 ce 59 c0 89 f8 30 e8 55 a1 f2 f0 18 41 90 9a 
,09-01 11:01:26.764  7886  8155 W bt-btm  : Stopping oneshot timer
,09-01 11:01:26.764  6931  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:01:26.770  7068  7794 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 11:01:26.778  7886  8155 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:01:26.778  7886  8155 W bt-smp  : Plain text(LSB ~ MSB) = b5 10 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:01:26.778  7886  8155 W bt-smp  : Encrypted text(LSB ~ MSB) = 52 17 f4 00 d5 fa 39 34 fd eb d0 92 15 0d 14 46 
09-01 11:01:26.778  7886  8155 W bt-btm  : Stopping oneshot timer
,09-01 11:01:26.785  7068  7085 D BluetoothMap: onBluetoothStateChange: up=true
09-01 11:01:26.790  7068  7794 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 11:01:26.794  1854  2443 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:01:26.799  1854  1854 D BluetoothHeadset: Proxy object connected
09-01 11:01:26.800  7068  7085 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:01:26.804  8188  8188 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-01 11:01:26.805  1854  4534 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:01:26.808  7068  7068 D BluetoothMap: Proxy object connected
09-01 11:01:26.808  7068  7068 D MapProfile: Bluetooth service connected
09-01 11:01:26.809  7068  7068 D BluetoothMap: getConnectedDevices()
09-01 11:01:26.809  7886  8124 V BluetoothMapService: getConnectedDevices()
09-01 11:01:26.810  1035  1105 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:01:26.811  7886  8155 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:01:26.811  7886  8155 W bt-smp  : Plain text(LSB ~ MSB) = 39 06 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:01:26.811  7886  8155 W bt-smp  : Encrypted text(LSB ~ MSB) = 90 ed 3b 72 91 d3 60 59 6a 0f 15 a4 84 b5 6b f1 
09-01 11:01:26.811  7886  8155 W bt-btm  : Stopping oneshot timer
09-01 11:01:26.811  1854  1854 D BluetoothHeadset: Proxy object connected
09-01 11:01:26.812  7068  7068 D BluetoothInputDevice: Proxy object connected
09-01 11:01:26.812  7068  7068 D HidProfile: Bluetooth service connected
09-01 11:01:26.813  1035  1035 D BluetoothHeadset: Proxy object connected
09-01 11:01:26.814  1854  3452 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:01:26.816  7068  7068 D BluetoothA2dp: Proxy object connected
09-01 11:01:26.816  7068  7068 D A2dpProfile: Bluetooth service connected
,09-01 11:01:26.818  1854  1854 D BluetoothHeadset: Proxy object connected
,09-01 11:01:26.818  7068  7794 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:01:26.822  7068  7068 D BluetoothHeadset: Proxy object connected
09-01 11:01:26.822  7068  7068 D HeadsetProfile: Bluetooth service connected
09-01 11:01:26.823  7068  7794 D BluetoothPan: onBluetoothStateChange on: true
09-01 11:01:26.823  7068  7794 D BluetoothPan: onBluetoothStateChange call bindService
09-01 11:01:26.827  1035  1105 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 11:01:26.827  7068  7068 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:01:26.827  7068  7068 D PanProfile: Bluetooth service connected
09-01 11:01:26.830  1035  1035 D BluetoothA2dp: Proxy object connected
,09-01 11:01:26.831  1035  1105 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-01 11:01:26.831  1035  1105 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-01 11:01:26.832  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:01:26.835  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:26.835  1941  2102 D LGBluetoothAPIService: Message: 1
09-01 11:01:26.835  1941  2102 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-01 11:01:26.835  1941  2102 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-01 11:01:26.835  1941  2102 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-01 11:01:26.836  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:26.838  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-01 11:01:26.838  1035  1105 D BluetoothManagerService: Message: 40
09-01 11:01:26.838  1035  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-01 11:01:26.840  7886  7886 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:26.840  7886  7886 D BluetoothMapService: STATE_ON
09-01 11:01:26.841  7068  7068 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-01 11:01:26.842  7068  7068 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-01 11:01:26.848  7068  7068 D DockEventReceiver: finishStartingService: stopping service
09-01 11:01:26.857  7886  7886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f31f726
09-01 11:01:26.857  7886  7886 V BluetoothPbapService: Pbap Service onCreate
09-01 11:01:26.858  7886  7886 V BluetoothPbapService: Starting PBAP service
09-01 11:01:26.859  7886  7886 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,09-01 11:01:26.859  7886  7886 V BluetoothMapService: Handler(): got msg=1
09-01 11:01:26.860  7886  7886 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-01 11:01:26.860  7886  7886 V BluetoothPbapService: Pbap Service onBind
09-01 11:01:26.861  7886  7886 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:26.861  7886  7886 V BluetoothPbapService: state: 12
09-01 11:01:26.862  7886  7886 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:01:26.862  7886  7886 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:26.862  7886  7886 V BluetoothPbapReceiver: ***********state = 12
09-01 11:01:26.862  7886  8207 D BluetoothMapMasInstance: MAS initSocket()
09-01 11:01:26.862  7886  8207 D BluetoothMapMasInstance:   masId = 00
09-01 11:01:26.862  7886  8207 D BluetoothMapMasInstance:   msgTypes = 0e
09-01 11:01:26.862  7886  8207 D BluetoothMapMasInstance:   masName = SMS/MMS
09-01 11:01:26.862  7886  8207 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-01 11:01:26.863  7068  7068 D BluetoothPbap: Proxy object connected
09-01 11:01:26.863  7886  7886 V BluetoothPbapService: Handler(): got msg=1
09-01 11:01:26.863  7068  7068 D PbapServerProfile: Bluetooth service connected
09-01 11:01:26.864  7886  7886 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-01 11:01:26.865  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:01:26.865  7886  8208 V BluetoothPbapService: Pbap Service initSocket
09-01 11:01:26.865  1035  1726 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:26.865  1035  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:26.866  2081  2081 D c       : Getting all permits...
09-01 11:01:26.866  2081  2081 D a       : Opening database...
09-01 11:01:26.866  7886  8207 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:01:26.866  7886  8208 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:01:26.867  7886  8208 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-01 11:01:26.867  7886  8207 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=0
09-01 11:01:26.867  7886  8207 V BluetoothMapMasInstance: Succeed to create listening socket 
09-01 11:01:26.867  7886  8208 V BluetoothPbapService: Succeed to create listening socket 
09-01 11:01:26.867  7886  8208 V BluetoothPbapService: Accepting socket connection...
09-01 11:01:26.868  7886  8122 D BluetoothAdapterProperties: Scan Mode:21
09-01 11:01:26.868  7886  8122 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-01 11:01:26.868  7886  8207 D BluetoothMapMasInstance: Accepting socket connection...
09-01 11:01:26.869  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:26.870  2081  2081 D a       : Opening database auth.proximity.permit_store...
,09-01 11:01:26.871  2081  2081 D a       : Closing database...
09-01 11:01:26.879  7068  7068 D BluetoothPermissionRequest: onReceive
09-01 11:01:26.881  7068  7068 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-01 11:01:26.883  7068  7068 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-01 11:01:26.886  7886  7886 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-01 11:01:26.888  7886  7886 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-01 11:01:26.893  7886  7886 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-01 11:01:26.912  7886  7886 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-01 11:01:26.913  7886  7886 V BtOppService: onCreate
,09-01 11:01:26.917  7886  7886 V BluetoothOppNotification: send message
09-01 11:01:26.920  7886  7886 V BtOppService: Starting RfcommListener
09-01 11:01:26.926  7886  7886 D BluetoothOppPreference: Dumping Names:  
09-01 11:01:26.926  7886  7886 D BluetoothOppPreference: {}
09-01 11:01:26.926  7886  7886 D BluetoothOppPreference: Dumping Channels:  
09-01 11:01:26.926  7886  7886 D BluetoothOppPreference: {}
09-01 11:01:26.927  7886  7886 V BtOppService: onStartCommand
,09-01 11:01:26.930  7886  7886 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:26.930  7886  7886 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-01 11:01:26.930  7886  8216 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,09-01 11:01:26.933  7886  7886 V BluetoothOppNotification: new notify threadi!
09-01 11:01:26.933  7886  7886 V BluetoothOppNotification: send delay message
09-01 11:01:26.934  7886  7886 V BtOppService: start RfcommListener
09-01 11:01:26.938  7886  7886 V BtOppService: RfcommListener started
09-01 11:01:26.939  7886  8213 V BtOppService: Deleted complete outbound shares, number =  0
09-01 11:01:26.940  7886  8213 V BtOppService: Deleted complete inbound failed shares, number = 0
09-01 11:01:26.941  7886  8213 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-01 11:01:26.941  7886  8216 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-01 11:01:26.942  7886  8213 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ff1f0c2 on behalf of 
09-01 11:01:26.938  7886  8217 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-01 11:01:26.947  7886  8216 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@96aced3 on behalf of 
,09-01 11:01:26.947  7886  8218 V BtOppRfcommListener: Starting RFCOMM listener....
09-01 11:01:26.948  1035  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:26.949  7886  8217 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17b08a10 on behalf of 
09-01 11:01:26.949  7886  8217 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-01 11:01:26.951  7886  8218 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:01:26.951  7886  8216 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-01 11:01:26.952  7886  8218 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-01 11:01:26.952  7886  8217 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-01 11:01:26.953  7886  8217 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@389bd909 on behalf of 
09-01 11:01:26.954  7886  8217 V BluetoothOppNotification: outbound: succ-0  fail-0
09-01 11:01:26.956  7886  8218 V BtOppRfcommListener: Started RFCOMM listener....
09-01 11:01:26.956  7886  8218 I BtOppRfcommListener: Accept thread started.
09-01 11:01:26.956  7886  8218 V BtOppRfcommListener: Accepting connection...
09-01 11:01:26.957  7886  8217 V BluetoothOppNotification: outbound notification was removed.
,09-01 11:01:26.957  7886  8217 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-01 11:01:26.959  7886  8217 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c72570e on behalf of 
09-01 11:01:26.960  7886  8217 V BluetoothOppNotification: inbound: succ-0  fail-0
09-01 11:01:26.962  7886  8217 V BluetoothOppNotification: inbound notification was removed.
09-01 11:01:26.962  7886  8217 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-01 11:01:26.963  7886  8217 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3609852f on behalf of 
09-01 11:01:26.964  7886  7886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f31f726
09-01 11:01:26.965  7886  7886 V BluetoothFtpService: Ftp Service onCreate
09-01 11:01:26.965  7886  7886 I BluetoothFtpService: Ftp Service onCreate
09-01 11:01:26.965  7886  7886 V BluetoothFtpService: Ftp Service onStartCommand
,09-01 11:01:26.965  7886  7886 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:26.965  7886  7886 V BluetoothFtpService: Starting Listening on sockets
09-01 11:01:26.966  7886  7886 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:01:26.966  7886  7886 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:01:26.966  7886  7886 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:01:26.966  7886  7886 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:26.966  7886  7886 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-01 11:01:26.966  7886  7886 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-01 11:01:26.969  7886  7886 V BtOppService: ContentObserver received notification
09-01 11:01:26.969  7886  7886 V BtOppService: ContentObserver received notification
09-01 11:01:26.969  7886  7886 V BluetoothFtpService: Handler(): got msg=1
,09-01 11:01:26.970  7886  7886 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-01 11:01:26.970  7886  7886 V BluetoothFtpService: Ftp Service initSocket
09-01 11:01:26.972  7886  8219 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-01 11:01:26.972  7886  8219 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-01 11:01:26.974  1035  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:26.974  7886  8219 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d9ffcc5 on behalf of 
09-01 11:01:26.975  7886  7886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:01:26.976  7886  8219 V BluetoothOppNotification: update too frequent, put in queue
09-01 11:01:26.976  7886  7886 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
09-01 11:01:26.976  7886  7886 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-01 11:01:26.978  7886  8219 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-01 11:01:26.979  7886  8220 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-01 11:01:26.995  7886  7886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f31f726
,09-01 11:01:26.996  7886  7886 V BluetoothSapService: Sap Service onCreate
09-01 11:01:26.998  7886  7886 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:01:26.998  7886  7886 V BluetoothSapService: state: 12
09-01 11:01:26.998  7886  7886 V BluetoothSapService: Starting SAP server process
09-01 11:01:27.000  7886  7886 V BluetoothSapService: SAP Service startRfcommListenerThread
09-01 11:01:27.001  7886  8221 V BluetoothSapService: Sap Service initRfcommSocket
09-01 11:01:27.002  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:26.989  8222  8222 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:27.002  7886  8221 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:01:26.989  8222  8222 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:27.004  7886  8221 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
09-01 11:01:27.004  7886  8221 V BluetoothSapService: Succeed to create listening socket 
09-01 11:01:27.004  7886  8221 V BluetoothSapService: Accepting socket connection...
09-01 11:01:27.016  8222  8222 V BT_SAP  : Event pipe created
09-01 11:01:27.016  8222  8222 V BT_SAP  : create_server_socket qcom.sap.server
09-01 11:01:27.016  8222  8222 V BT_SAP  : created socket fd 6
,09-01 11:01:27.580  6931  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:27.580  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:27.580  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:27.580  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:01:27.580  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:01:27.580  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:27.580  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:27.580  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:01:27.590  6931  7010 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:01:27.592  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:27.592  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7c3996b added. We now have 8 listener(s)
09-01 11:01:27.592  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:27.595  1035  1050 D WifiServiceImplEx: setWifiEnabled: false pid=6931, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-01 11:01:27.595  1035  1050 D WifiService: setWifiEnabled: false pid=6931, uid=10118
09-01 11:01:27.595  1035  1050 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-01 11:01:27.601  6931  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:01:27.604  1035  1962 D WifiServiceImplEx: setWifiEnabled: true pid=6931, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-01 11:01:27.605  1035  1962 D WifiService: setWifiEnabled: true pid=6931, uid=10118
09-01 11:01:27.605  1035  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:01:27.626  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:01:27.626  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:01:27.626  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-01 11:01:27.627  1035  1440 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-01 11:01:27.627  1035  1440 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-01 11:01:27.630  1035  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-01 11:01:27.630  1035  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-01 11:01:27.630  1035  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-01 11:01:27.630  1035  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-01 11:01:27.630  1035  1440 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-01 11:01:27.630  1035  1440 E WifiHW  : unknown target_country: EU , set to default
09-01 11:01:27.630  1035  1440 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-01 11:01:27.630  1035  1440 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-01 11:01:27.630  1035  1440 I WifiUtil: gEnableBmps=1
09-01 11:01:27.934  7886  7886 V BluetoothOppNotification: new notify threadi!
09-01 11:01:27.934  7886  7886 V BluetoothOppNotification: send delay message
,09-01 11:01:27.941  7886  8235 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-01 11:01:27.952  7886  8235 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f08a041 on behalf of 
09-01 11:01:27.953  7886  8235 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-01 11:01:27.967  7886  8235 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-01 11:01:27.978  7886  8235 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ac639e6 on behalf of 
09-01 11:01:27.978  7886  8235 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-01 11:01:27.994  7886  8235 V BluetoothOppNotification: outbound notification was removed.
09-01 11:01:27.994  7886  8235 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-01 11:01:28.066  7886  8235 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9eeeb27 on behalf of 
,09-01 11:01:28.076  7886  8235 V BluetoothOppNotification: inbound: succ-0  fail-0
09-01 11:01:28.080  7886  8235 V BluetoothOppNotification: inbound notification was removed.
09-01 11:01:28.080  7886  8235 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-01 11:01:28.081  7886  8235 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d8a31d4 on behalf of 
,09-01 11:01:28.209  1035  1105 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-01 11:01:28.209  1035  1105 D Tethering: InitialState.processMessage what=4
09-01 11:01:28.213  1035  1105 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-01 11:01:28.215   308   891 D SoftapController: Softap fwReload - Ok
09-01 11:01:28.216  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-01 11:01:28.216  7068  7068 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-01 11:01:28.217  7068  7068 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-01 11:01:28.217  7068  7068 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-01 11:01:28.218  1035  1440 E NetdConnector: NDC Command {82 softap fwreload wlan0 STA} took too long (584ms)
,09-01 11:01:28.222  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-01 11:01:28.223   308   891 D CommandListener: Setting iface cfg
09-01 11:01:28.223   308   891 D CommandListener: Trying to bring down wlan0
09-01 11:01:28.225   308   891 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:01:28.225  7068  7068 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:01:28.225  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-01 11:01:28.225  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-01 11:01:28.225  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-01 11:01:28.225  7068  7068 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:01:28.226  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-01 11:01:28.227  7068  7068 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-01 11:01:28.228  1035  1440 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-01 11:01:28.229  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-01 11:01:28.229  7068  7068 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-01 11:01:28.229  7068  7068 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-01 11:01:28.229  7068  7068 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-01 11:01:28.230  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-01 11:01:28.230  7068  7068 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:01:28.230  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,09-01 11:01:28.230  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-01 11:01:28.230  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-01 11:01:28.231  7068  7068 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:01:28.231  7068  7068 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-01 11:01:28.219  8261  8261 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:28.219  8261  8261 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:28.256  8261  8261 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-01 11:01:28.289  8261  8261 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-01 11:01:28.289  8261  8261 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-01 11:01:28.329  1035  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:01:28.329  1035  1440 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:01:28.329  1035  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-01 11:01:28.331  1035  1440 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-01 11:01:28.331  1035  1440 D WifiMonitor: connecting to supplicant
09-01 11:01:28.332  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-01 11:01:28.333  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:28.341  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:01:28.373  8261  8261 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-01 11:01:28.398  1035  1092 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8262 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-01 11:01:28.400  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-01 11:01:28.425  8261  8261 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-01 11:01:28.439  1035  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-01 11:01:28.440  1035  1440 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-01 11:01:28.440  1035  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-01 11:01:28.441  1035  1440 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-01 11:01:28.441  1035  1440 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:28.442  1035  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:28.442  1035  1440 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:28.443  1035  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:28.443  1035  1440 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-01 11:01:28.443  1035  1440 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-01 11:01:28.444  1035  1440 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-01 11:01:28.444  1035  1440 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-01 11:01:28.444  1035  1440 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-01 11:01:28.445  1035  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:01:28.445  1035  1440 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:01:28.445  1035  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:01:28.445  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:28.445  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:28.446  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:28.446  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:28.446  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:01:28.447  1941  1941 D WfdService: Waiting for WifiP2p enabling
09-01 11:01:28.448  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-01 11:01:28.449  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:28.449  1035  1469 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-01 11:01:28.449  8261  8261 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-01 11:01:28.449  1035  8279 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-01 11:01:28.450  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-01 11:01:28.451  1035  8279 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-01 11:01:28.451  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-01 11:01:28.451  1035  8279 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-01 11:01:28.446  1035  1440 D WifiNative-wlan0: doBoolean: SET update_config 1
09-01 11:01:28.451  1035  8279 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,09-01 11:01:28.453  1035  1440 D WifiNative-wlan0: SET update_config 1: returned true
09-01 11:01:28.453  1035  1440 D WifiConfigStore: Loading config and enabling all networks 
09-01 11:01:28.453  1035  1440 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-01 11:01:28.453  1035  1440 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-01 11:01:28.460  1035  1440 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-01 11:01:28.462  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:28.462  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:28.462  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:28.462  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:28.462  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:01:28.462  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:28.462  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:28.462  6931  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:01:28.464  6931  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:01:28.471  1035  1440 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-01 11:01:28.471  1035  1440 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-01 11:01:28.472  1035  1440 D WifiStateMachine: enableVerboseLogging : level 2
09-01 11:01:28.472  1035  1440 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-01 11:01:28.472  1035  1440 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-01 11:01:28.472  1035  1440 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-01 11:01:28.473  1035  1440 D WifiNative-wlan0: SET manufacturer LGE: returned true
,09-01 11:01:28.473  1035  1440 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-01 11:01:28.473  1035  1440 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-01 11:01:28.474  1035  1440 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-01 11:01:28.474  1035  1440 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-01 11:01:28.474  1035  1440 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-01 11:01:28.474  1035  1440 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-01 11:01:28.474  1035  1440 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-01 11:01:28.475  1035  1440 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-01 11:01:28.475  1035  1440 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-01 11:01:28.476  1035  1440 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-01 11:01:28.476  1035  1440 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 11:01:28.476  1035  1440 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-01 11:01:28.477  1941  1941 D WfdsService: Supplicant Connection state is changed : true
09-01 11:01:28.477  1035  1440 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-01 11:01:28.477  1035  1440 D WifiNative-HAL: Setting external_sim to 1
09-01 11:01:28.477  1035  1440 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-01 11:01:28.478  1035  1440 D WifiNative-wlan0: SET external_sim 1: returned true
09-01 11:01:28.478  1035  1440 I WifiNative-HAL: startHal
09-01 11:01:28.478  7924  7924 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:28.478  1035  1440 D wifi    : setting scan oui 0xaf7708a0
09-01 11:01:28.478  1035  1440 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 11:01:28.478  1035  1440 I WifiNative-HAL: startHal
09-01 11:01:28.479  1035  1440 D wifi    : setting scan oui 0xaf7708a0
09-01 11:01:28.479  1035  1440 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-01 11:01:28.480  1035  1440 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-01 11:01:28.480  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-01 11:01:28.480  8261  8261 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-01 11:01:28.480  1035  1440 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
,09-01 11:01:28.480  1941  2209 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-01 11:01:28.480  1941  2209 D WfdsService: Set the WFDS Monitor: true
09-01 11:01:28.480  1941  2209 D WfdsMonitor: WfdsMonitorThread create
09-01 11:01:28.480  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-01 11:01:28.481  1941  2209 D WfdsMonitor: WFDS Monitor is created and started
09-01 11:01:28.481  1941  2209 D WfdsService: WiFi: Supplicant connection re-established
09-01 11:01:28.481  8261  8261 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-01 11:01:28.481  1035  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-01 11:01:28.481  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-01 11:01:28.482  8261  8261 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-01 11:01:28.482  1035  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-01 11:01:28.482  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-01 11:01:28.482  8261  8261 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-01 11:01:28.483  1035  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-01 11:01:28.483  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-01 11:01:28.483  8261  8261 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-01 11:01:28.483  1035  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-01 11:01:28.483  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-01 11:01:28.484  8261  8261 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-01 11:01:28.484  1035  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
,09-01 11:01:28.484  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-01 11:01:28.484  8261  8261 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-01 11:01:28.485  1035  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-01 11:01:28.486  1035  1440 E WifiNative: : [232,887,341 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-01 11:01:28.486  1035  1440 D WifiNative-wlan0: doBoolean: RECONNECT
09-01 11:01:28.486  1941  8280 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-01 11:01:28.486  1035  1440 D WifiNative-wlan0: RECONNECT: returned true
09-01 11:01:28.486  1035  1440 D WifiNative-wlan0: doString: [STATUS]
09-01 11:01:28.487  1941  8280 E CtrlSupplicant: Succeed to open control connection
09-01 11:01:28.487  1035  8279 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=],
09-01 11:01:28.487  1941  8280 E CtrlSupplicant: Succeed to open monitor connection
09-01 11:01:28.487  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-01 11:01:28.487  1941  8280 D WfdsMonitor: Supplicant connection established
09-01 11:01:28.487  1035  1440 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-01 11:01:28.487  1035  1440 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:01:28.488  1941  2209 D WfdsService: Connected to the supplicant for wfds
09-01 11:01:28.488  1035  1440 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:01:28.488  1035  1391 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:01:28.490   308   891 D CommandListener: Setting iface cfg
09-01 11:01:28.490   308   891 D CommandListener: Trying to bring up p2p0
09-01 11:01:28.490  1035  1391 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-01 11:01:28.490  1035  1391 D LGWifiP2pService: P2pEnablingState
09-01 11:01:28.490  1035  1391 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.490  1035  1391 D LGWifiP2pService: P2p socket connection successful
09-01 11:01:28.490  1035  1391 D LGWifiP2pService: P2pEnabledState
09-01 11:01:28.492  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-01 11:01:28.493  1941  1941 D WfdsService: WifiP2pState is changed : true
09-01 11:01:28.493  1941  2209 D WfdsService: Receive the WFDS_ENABLE Method
,09-01 11:01:28.493  1941  2209 D WfdsService: Set the WFDS Monitor: true
09-01 11:01:28.493  1941  2209 D WfdsService: Connected to the supplicant for wfds
09-01 11:01:28.493  1941  2209 D WfdsJNI : doCommand: WFDS_SET TRUE
09-01 11:01:28.493  8261  8261 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-01 11:01:28.493  1941  2209 D WfdsService: selectPreferredScanChannel [36]
09-01 11:01:28.494  1941  2209 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-01 11:01:28.495  1035  1391 D LGWifiP2pService: sending p2p connection changed broadcast
09-01 11:01:28.497  1035  1391 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-01 11:01:28.497  1035  1391 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-01 11:01:28.498  1035  1391 D WifiNative-p2p0: doBoolean: SET device_name G3
09-01 11:01:28.498  1035  1391 D WifiNative-p2p0: SET device_name G3: returned true
09-01 11:01:28.498  1035  1391 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-01 11:01:28.498  1035  1391 D LGWifiP2pService: before postfix = G3
09-01 11:01:28.498  1035  1391 D WifiServerServiceExt: postfix byte check : 2
09-01 11:01:28.498  1035  1391 D LGWifiP2pService: after postfix = G3
09-01 11:01:28.498  1035  1391 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-01 11:01:28.498  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-01 11:01:28.498  1035  1391 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-01 11:01:28.498  1035  1391 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-01 11:01:28.499  1941  1941 D WfdsService: isConnected: false
09-01 11:01:28.499  1035  1391 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-01 11:01:28.499  1035  1391 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-01 11:01:28.499  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-01 11:01:28.499  1035  1440 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-01 11:01:28.499  1035  1391 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-01 11:01:28.499  1035  1035 D RttService: SCAN_AVAILABLE : 3
09-01 11:01:28.499  1035  1391 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-01 11:01:28.499  1035  1558 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.499  1035  1558 I WifiNative-HAL: startHal
09-01 11:01:28.499  1035  1559 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.500  1035  1391 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-01 11:01:28.500  1035  1440 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-01 11:01:28.500  1035  1391 D WifiNative-HAL: p2pGetDeviceAddress
09-01 11:01:28.500  1035  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf7708a0
09-01 11:01:28.500  1035  1391 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-01 11:01:28.500  1035  1440 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-01 11:01:28.500  1035  1440 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-01 11:01:28.500  1035  1558 D wifi    : failed to get capabilities : -3
09-01 11:01:28.500  1035  1558 E WifiScanningService: could not get scan capabilities
09-01 11:01:28.501  1035  1440 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-01 11:01:28.501  1035  1440 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-01 11:01:28.502  1035  1440 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-01 11:01:28.502  1035  1440 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-01 11:01:28.503  8261  8261 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-01 11:01:28.503  1035  1440 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-01 11:01:28.504  1035  1440 E WifiStateMachine:  Co,nnectModeState what:132096 -100 0
09-01 11:01:28.504  1035  1440 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-01 11:01:28.504  1035  1440 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-01 11:01:28.504  8261  8261 E wpa_supplicant: disconnect_rssi_lvl: -100
09-01 11:01:28.505  1035  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=232907  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,09-01 11:01:28.548  1035  1684 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8285 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-01 11:01:28.550  1035  1391 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-01 11:01:28.550  1035  1391 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-01 11:01:28.551  1035  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=232953  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-01 11:01:28.551  1035  1391 D WifiNative-p2p0: P2P_FLUSH: returned true
09-01 11:01:28.552  1035  1391 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-01 11:01:28.552  1035  1440 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-01 11:01:28.552  1035  1391 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-01 11:01:28.552  1035  1391 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-01 11:01:28.552  1035  1440 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-01 11:01:28.553  1035  1440 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-01 11:01:28.553  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-01 11:01:28.553  1035  1391 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-01 11:01:28.553  1035  1391 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-01 11:01:28.555  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
09-01 11:01:28.555  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-01 11:01:28.555  1941  1941 D WfdsService: Update P2p Interface State: 3
09-01 11:01:28.555  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:28.555  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:28.557  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:28.557  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:28.557  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-01 11:01:28.558  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:28.563  8262  8283 W FormManager: Network not available. Please check & try again.
,09-01 11:01:28.565  1035  1391 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-01 11:01:28.565  1035  1391 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-01 11:01:28.565  1035  1391 D LGWifiP2pService: InactiveState
09-01 11:01:28.565  1035  1391 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.565  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.566  8261  8261 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-01 11:01:28.566  1035  1391 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-01 11:01:28.567  8261  8261 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:28.568  8261  8261 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-01 11:01:28.568  8261  8261 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.568  1035  8279 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:01:28.568  1941  8280 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:01:28.568  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:28.568  1035  8279 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:28.568  1035  8279 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:28.568  1035  8279 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:01:28.568  1035  8279 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.568  1035  8279 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.568  1035  8279 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.568  8261  8261 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.569  1035  1440 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-01 11:01:28.569  1941  8280 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:01:28.570  1035  1440 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:01:28.570  1035  8279 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:01:28.570  1035  8279 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.570  1035  8279 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.570  1035  1440 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:01:28.570  1035  8279 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.570  8262  8284 V FormManager: Network unavailable.
09-01 11:01:28.571  8261  8261 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-01 11:01:28.571  8261  8261 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:28.571  1035  8279 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:01:28.571  1035  8279 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:28.571  1035  8279 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:28.572  1035  1440 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:01:28.572  1035  8279 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:01:28.572  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-01 11:01:,28.572  1941  8280 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:01:28.572  8261  8261 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-01 11:01:28.572  8261  8261 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.572  1035  8279 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:01:28.572  1035  8279 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.572  1035  8279 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.572  1035  8279 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.572  1941  8280 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:01:28.573  8261  8261 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.573  1035  8279 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:01:28.573  1035  8279 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.573  1035  8279 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.573  1941  8280 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:01:28.573  1035  8279 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:01:28.573  8262  8284 V FormManager: Network unavailable.
09-01 11:01:28.574  1035  1391 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-01 11:01:28.575  1035  1391 D LGWifiP2pService: InactiveState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.575  8261  8261 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-01 11:01:28.575  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.575  1035  1391 D LGWifiP2pService: DefaultState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.575  8261  8261 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:01:28.575  1035  1391 D LGWifiP2pService: InactiveState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.575  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.575  1035  1391 D LGWifiP2pService: DefaultState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.575  1035  8279 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-01 11:01:28.576  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:01:28.576  1035  8279 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:01:28.576  1035  8279 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:01:28.576  1035  1391 D LGWifiP2pService: InactiveState{ when=-6ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.576  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.576  1035  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.576  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:01:28.576  1035  1391 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.576  1035  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.576  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.576  1035  1391 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:28.576  1035  1035 E WifiServerServiceExt: No p2p device connected
09-01 11:01:28.578  1035  1440 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-01 11:01:28.578  1941  2209 W WfdsService: DefaultState - msg [9441285] is not handled
09-01 11:01:28.578  1035  1440 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-01 11:01:28.578  1035  1440 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-01 11:01:28.578  1035  1440 D WifiNative-wlan0: doBoolean: SCAN
09-01 11:01:28.579  1035  1440 D WifiNative-wlan0: SCAN: returned false
09-01 11:01:28.579  1035  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=232981  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,09-01 11:01:28.582  1035  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=232984  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-01 11:01:28.582  1035  1440 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:01:28.583  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:28.583  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:28.583  1035  1440 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-01 11:01:28.583  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-01 11:01:28.583  1035  1440 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:01:28.584  1035  1440 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:01:28.584  1035  1440 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:01:28.586  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:01:28.586  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-01 11:01:28.588  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:28.588  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:28.591  1035  1958 I ActivityManager: Killing 7359:com.android.chrome/u0a57 (adj 15): empty #17
09-01 11:01:28.591  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:01:28.639  6931  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:01:28.639  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:28.639  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:28.639  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:28.639  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:01:28.639  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:01:28.639  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:01:28.639  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:01:28.640  1035  1051 W libprocessgroup: failed to open /acct/uid_10057/pid_7359/cgroup.procs: No such file or directory
09-01 11:01:28.641  6931  7010 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:01:28.647  6931  7010 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-01 11:01:28.648  6931  7010 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-01 11:01:28.651  6931  7010 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3b9df775 Bundle[{}]
09-01 11:01:28.652  6931  7010 I io.jxcore.node.LifeCycleMonitor: start: OK
09-01 11:01:28.652  6931  7010 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-01 11:01:28.653  6931  7010 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-01 11:01:28.653  6931  7010 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-01 11:01:28.654  6931  7010 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-01 11:01:28.655  6931  7010 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-01 11:01:28.664  6931  7010 I System.out: Running OutgoingSocketThread
,09-01 11:01:28.668  6931  8303 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 901)
09-01 11:01:28.671  6931  8303 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60786
09-01 11:01:28.671  6931  8303 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-01 11:01:28.676  8285  8285 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:01:28.682  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-01 11:01:28.687  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:28.689  1035  1918 I ActivityManager: Killing 7387:com.lge.drmservice/u0a62 (adj 15): empty #17
,09-01 11:01:28.719  1035  1699 W libprocessgroup: failed to open /acct/uid_10062/pid_7387/cgroup.procs: No such file or directory
,09-01 11:01:28.748  8285  8285 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:01:28.751  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-01 11:01:28.757  8262  8307 W FormManager: Network not available. Please check & try again.
09-01 11:01:28.762  8262  8308 V FormManager: Network unavailable.
,09-01 11:01:28.765  8262  8308 V FormManager: Network unavailable.
09-01 11:01:28.767  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:28.786  7986  8002 E UEI.SmartControl: file observer is disposed!
09-01 11:01:28.788  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:01:28.789  4855  4855 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:01:28.791  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-01 11:01:28.793  4855  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:01:28.802  4855  8309 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-01 11:01:28.803  4855  8310 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:01:28.804  4855  8310 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-01 11:01:28.855  1035  1962 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8311 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-01 11:01:29.016  8311  8311 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-01 11:01:29.017  8311  8311 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-01 11:01:29.023  8311  8311 V [BNRBootReceiver]: Boot Receiver Return
,09-01 11:01:29.024  8311  8311 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-01 11:01:29.071  1035  1051 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8332 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-01 11:01:29.072  1035  1051 I ActivityManager: Killing 7412:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-01 11:01:29.117  1035  1684 W libprocessgroup: failed to open /acct/uid_10085/pid_7412/cgroup.procs: No such file or directory
,09-01 11:01:29.128  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-01 11:01:29.128  1035  8279 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-01 11:01:29.128  1035  8279 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-01 11:01:29.128  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
09-01 11:01:29.128  1035  8279 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-01 11:01:29.128  8261  8261 E wpa_supplicant: USIM:  scard_init function
09-01 11:01:29.129  8261  8261 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-01 11:01:29.129  1035  1440 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-01 11:01:29.129  1035  1440 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-01 11:01:29.130  1035  1440 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-01 11:01:29.130  1035  1440 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
,09-01 11:01:29.130  1035  1440 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-01 11:01:29.131  1035  8279 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-01 11:01:29.131  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-01 11:01:29.137  1035  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=233539  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-01 11:01:29.139  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:29.139  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:29.139  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.139  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.139  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-01 11:01:29.140  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:29.140  1035  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=233542  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-01 11:01:29.141  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:01:29.141  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-01 11:01:29.143  8332  8332 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:01:29.163  8332  8332 D PluginManager: init()
,09-01 11:01:29.399  1035  8279 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,09-01 11:01:29.399  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-01 11:01:29.399  8261  8261 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-01 11:01:29.400  1035  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=233802  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-01 11:01:29.400  1035  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=233802  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-01 11:01:29.400  1035  8279 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-01 11:01:29.400  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-01 11:01:29.400  1035  8279 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:01:29.400  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:01:29.401  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:01:29.401  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,09-01 11:01:29.402  1035  1440 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=233804
09-01 11:01:29.402  1035  1440 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=233804
09-01 11:01:29.402  1035  1440 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=233804
09-01 11:01:29.402  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=233804
09-01 11:01:29.403  1035  1440 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=233805
09-01 11:01:29.403  1035  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=233805  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-01 11:01:29.408  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:29.408  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:29.409  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.409  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.409  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-01 11:01:29.412  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.412  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.412  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-01 11:01:29.413  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:29.417  1035  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=233819  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-01 11:01:29.418  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:01:29.418  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,09-01 11:01:29.429  1035  1105 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-01 11:01:29.432  1035  1440 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:29.433  1035  1440 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:29.434  1035  1440 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:29.434  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:29.434  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:29.435  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:29.435  1035  8279 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:01:29.435  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:01:29.435  8261  8261 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:01:29.435  1035  8279 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-01 11:01:29.435  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:01:29.435  8261  8261 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:01:29.436  1035  8279 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:01:29.436  1035  8279 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-01 11:01:29.436  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:01:29.436  1035  8279 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:01:29.436  1035  8279 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:01:29.436  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:01:29.439  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:29.440  1035  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:01:29.440  1035  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=233842  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-01 11:01:29.441  1035  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=233843  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-01 11:01:29.441  1035  1440 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=233843
09-01 11:01:29.442  1035  1440 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=233844
09-01 11:01:29.445  1035  1440 D WifiNative-wlan0: doString: [STATUS]
09-01 11:01:29.447  1035  8279 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:01:29.447  1035  8279 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:01:29.447  1035  1440 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-01 11:01:29.449  1035  1440 I WifiServiceExtension: setVHTCapabilityType  : ,false
,09-01 11:01:29.459  1035  1440 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-01 11:01:29.459  1035  1440 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-01 11:01:29.461  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:29.461  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-01 11:01:29.463  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:29.464  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.464  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.464  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-01 11:01:29.467  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.467  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.467  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-01 11:01:29.469  1035  1379 V AlarmManager: RTC_WAKEUP set : Alarm{166f09dd type 0 when 1472720483897 com.google.android.gms} when 1472720483897
09-01 11:01:29.470  1035  1440 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-01 11:01:29.470  1035  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:01:29.470  1035  1501 D ConnectivityService: Got NetworkAgent Messenger
09-01 11:01:29.470  1035  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-01 11:01:29.471  1035  1501 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-01 11:01:29.471  1035  1501 D ConnectivityService: NetworkAgent connected
09-01 11:01:29.471  1035  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-01 11:01:29.471  1035  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-01 11:01:29.476  1035  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-01 11:01:29.476  1035  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:01:29.476  1035  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,09-01 11:01:29.476  1035  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-01 11:01:29.476  1035  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-01 11:01:29.480  1035  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-01 11:01:29.482  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:29.482  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:29.482   308   891 D CommandListener: Setting iface cfg
09-01 11:01:29.484  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:29.485  1035  1440 E WifiStateMachine: Start Dhcp Watchdog 3
09-01 11:01:29.486  1035  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=233888  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:01:29.486  1035  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=233888  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:01:29.487  1035  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=233889  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:01:29.488  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:01:29.488  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-01 11:01:29.489  1035  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=233891  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-01 11:01:29.489  1035  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=233891  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:01:29.489  1035  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=233891  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:01:29.490  1035  1440 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14084] from screen [on:0 period:-453293038] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-01 11:01:29.491  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-453293037] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-01 11:01:29.491  1035  1440 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-01 11:01:29.492  1035  8353 D DhcpStateMachine: StoppedState
09-01 11:01:29.492  1035  8353 D DhcpStateMachine: StoppedState{ when=-7ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:29.492  1035  8353 D DhcpStateMachine: WaitBeforeStartState
09-01 11:01:29.497  1035  1501 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-01 11:01:29.498  1035  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:29.498  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:29.498  1035  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:29.499  1035  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:29.499  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:29.499  1035  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:29.500  1035  1501 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-01 11:01:29.501  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:01:29.501  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-01 11:01:29.502  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:29.502  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:01:29.502  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-01 11:01:29.503  1035  1440 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=175,0,0
09-01 11:01:29.503  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=175,0,0
09-01 11:01:29.503  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-01 11:01:29.504  8261  8261 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-01 11:01:29.504  1035  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-01 11:01:29.504  1035  1440 D WifiNative-wlan0: doBoolean: SET ps 0
09-01 11:01:29.505  1035  1440 D WifiNative-wlan0: SET ps 0: returned true
09-01 11:01:29.505  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-01 11:01:29.505  8261  8261 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-01 11:01:29.505  1035  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-01 11:01:29.506  1035  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@297b0f7c target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:29.506  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@297b0f7c target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:29.506  1035  8353 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.inte,rnal.util.StateMachine$SmHandler }
09-01 11:01:29.508  1035  8353 D DhcpStateMachine: DHCP Start wake lock is acquired.
,09-01 11:01:29.510  1035  1440 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-01 11:01:29.510  1035  1440 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-01 11:01:29.510  1035  1440 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-01 11:01:29.511   308   891 D CommandListener: Setting iface cfg
09-01 11:01:29.511   308   891 D CommandListener: Trying to bring up wlan0
09-01 11:01:29.513  1035  1440 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-01 11:01:29.513  1035  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:29.513  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:29.513  1035  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:29.514  1035  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:29.514  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:29.514  1035  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:01:29.515  1035  1501 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-01 11:01:29.515  1035  1440 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-01 11:01:29.515  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-01 11:01:29.515  1035  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:29.515  1035  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:29.516  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-01 11:01:29.516  8261  8261 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-01 11:01:29.516  1035  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-01 11:01:29.516  1035  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-01 11:01:29.516  8261  8261 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-01 11:01:29.516  1035  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-01 11:01:29.516  1035  1440 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:01:29.536  1035  1440 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:01:29.536  1035  1501 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-01 11:01:29.536  1035  1440 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-01 11:01:29.537  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-01 11:01:29.537  1035  1440 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-01 11:01:29.537  1035  1501 D ConnectivityService: ignoring duplicate network state non-change
,09-01 11:01:29.542  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.542  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.542  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-01 11:01:29.543  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:29.543  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:29.544  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:29.548  1035  1501 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-01 11:01:29.548  1035  1501 D ConnectivityService: Adding iface wlan0 to network 102
09-01 11:01:29.551  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.551  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.551  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-01 11:01:29.553  1035  1440 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-01 11:01:29.553  8332  8332 W ExternalStrings: load override strings
09-01 11:01:29.553  8332  8332 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-01 11:01:29.553  8332  8332 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-01 11:01:29.554  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-01 11:01:29.554  8332  8332 D StatusProvider: onCreate
09-01 11:01:29.556  1941  1941 V WfdStateTracker: handleWifiStateC,hangedEvent: 1
,09-01 11:01:29.559  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.559  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.559  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-01 11:01:29.560  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-01 11:01:29.566  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.566  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:01:29.566  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-01 11:01:29.566  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:29.566  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:01:29.567  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:29.569  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:29.569  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-01 11:01:29.569  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:29.571  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:01:29.571  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-01 11:01:29.571  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:01:29.576  1035  1501 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-01 11:01:29.576  1035  1501 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-01 11:01:29.577  1035  1501 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-01 11:01:29.578   308   891 E Netd    : netlink response contains error (File exists)
09-01 11:01:29.579  1035  1501 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-01 11:01:29.579  1035  1501 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-01 11:01:29.579  1035  1501 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-01 11:01:29.580  1035  1501 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-01 11:01:29.581  1035  1501 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-01 11:01:29.581  1035  1501 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-01 11:01:29.581  1035  1501 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-01 11:01:29.581  1035  1501 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-01 11:01:29.581  1035  1501 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:01:29.581  1035  1501 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:29.581  1035  1501 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,09-01 11:01:29.581  1035  1501 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:29.581  1035  1501 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-01 11:01:29.581  1035  1501 D ConnectivityService: currentScore = 0, newScore = 20
09-01 11:01:29.581  1035  1501 D ConnectivityService:    accepting network in place of null
09-01 11:01:29.581  1035  1501 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:29.581  1035  8352 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:29.581  1035  8352 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-01 11:01:29.581  1035  8352 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:01:29.582  1035  8352 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-01 11:01:29.583   308  8368 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-01 11:01:29.583  1854  1854 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:29.583  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-01 11:01:29.587  1035  1440 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:29.587  1035  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:01:29.588  1035  1501 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-01 11:01:29.588  1035  1501 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-01 11:01:29.588  1035  1501 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:01:29.589  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-01 11:01:29.590  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-01 11:01:29.590  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-01 11:01:29.590  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-01 11:01:29.591  1035  1501 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:01:29.591  1035  1501 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-01 11:01:29.592  1035  1501 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-01 11:01:29.592  1035  1501 D ConnectivityService: validation of new default Network = false
09-01 11:01:29.592  1035  1501 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-01 11:01:29.592  1035  1501 D DSQN    : enableDataServiceNotify 
09-01 11:01:29.593  1035  1501 D DSQN    : start dsqn bin
09-01 11:01:29.599  1035  1390 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-01 11:01:29.604  1035  1501 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-01 11:01:29.604  1035  1501 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:29.604  1035  1501 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:29.604  1035  1501 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:29.589  8369  8369 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:29.605  1604  2114 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-01 11:01:29.589  8369  8369 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-01 11:01:29.612  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:01:29.613  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:29.613  8369  8369 E DSQN    : DSQN ssw
09-01 11:01:29.614  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:29.614  8332  8332 V Signer  : override build config not found
09-01 11:01:29.614  8332  8332 D Signer  : value of property debug is false
09-01 11:01:29.635  8332  8332 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-01 11:01:29.635  8332  8332 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-01 11:01:29.635  8332  8332 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-01 11:01:29.635  8332  8332 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-01 11:01:29.635  8332  8332 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-01 11:01:29.636  8332  8332 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-01 11:01:29.636  8332  8332 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-01 11:01:29.636  8332  8332 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-01 11:01:29.636  8332  8332 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-01 11:01:29.636  8332  8332 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-01 11:01:29.636  8332  8332 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
,09-01 11:01:29.636  8332  8332 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-01 11:01:29.636  8332  8332 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,09-01 11:01:29.643  8332  8332 V LGMDMManager: Create singleton instance
09-01 11:01:29.643   308  8368 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-01 11:01:29.667  6931  7010 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 902)
09-01 11:01:29.667  6931  7010 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 902)
,09-01 11:01:29.675  6931  7010 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 907)
09-01 11:01:29.678  8332  8332 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
09-01 11:01:29.679  6931  7010 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-01 11:01:29.680   308  8368 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-01 11:01:29.680  6931  7010 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 908)
09-01 11:01:29.687  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:01:29.687  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ac91cc8 added. We now have 2 listener(s)
,09-01 11:01:29.687  1035  1684 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:29.690  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:01:29.690  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:01:29.690  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:01:29.691  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:29.691  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19166161 added. We now have 9 listener(s)
09-01 11:01:29.691  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:29.691  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:01:29.695  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:01:29.701  6931  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:01:29.701  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:29.701  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:29.701  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:29.701  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:01:29.701  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:29.701  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:01:29.701  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:01:29.702  6931  7010 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:01:29.703  6931  7010 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:01:29.703  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:01:29.703  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36006147 added. We now have 3 listener(s)
09-01 11:01:29.704  1035  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:29.705   308   890 D LGDataListener: argv[0]=dsqncommand
09-01 11:01:29.705   308   890 D LGDataListener: argv[1]=wlan0
09-01 11:01:29.705   308   890 D LGDataListener: argv[2]=1
09-01 11:01:29.705   308   890 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-01 11:01:29.705  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:29.705  1035  1102 D DSQN    : DSQM DsqnNotification wlan0  1
09-01 11:01:29.705  1035  1102 D DSQN    : start to monitor internet connection
09-01 11:01:29.706  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:29.707  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:01:29.707  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:01:29.707  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:01:29.707  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:29.707  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb73d74 added. We now have 10 listener(s)
09-01 11:01:29.707  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:29.707  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:29.708  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:29.708  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:29.708  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:29.708  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:29.708  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:01:29.708  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:01:29.708  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ac91cc8 removed from the list
09-01 11:01:29.708  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:29.708  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19166161 removed from the list
09-01 11:01:29.708  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:29.708  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: re,lease: 1 listener(s) left
09-01 11:01:29.708  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:29.709  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:29.709  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:29.709  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:29.709  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:29.709  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19166161 not in the list
09-01 11:01:29.709  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:29.709  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:29.710  1035  8353 D DhcpStateMachine: DHCPV4 request on wlan0
09-01 11:01:29.711  1035  8353 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,09-01 11:01:29.711  1035  8353 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-01 11:01:29.712  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-01 11:01:29.712  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:01:29.712  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:29.712  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb73d74 removed from the list
,09-01 11:01:29.712  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:29.712  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:29.712  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:29.712  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:01:29.712  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36006147 removed from the list
09-01 11:01:29.699  8376  8376 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file,
09-01 11:01:29.699  8376  8376 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:01:29.713  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:01:29.713  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1176b29d added. We now have 2 listener(s)
09-01 11:01:29.713  1035  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:29.717  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:01:29.717  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:01:29.717  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 11:01:29.717  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:29.718  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c641312 added. We now have 9 listener(s)
09-01 11:01:29.718  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:29.718  8376  8376 I dhcpcd  : version 5.5.6 starting
09-01 11:01:29.718  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:01:29.719  8376  8376 E dhcpcd  : get_duid: m
,09-01 11:01:29.719  8376  8376 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-01 11:01:29.719  8376  8376 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-01 11:01:29.720  1035  8352 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 09:01:29 GMT], X-Android-Received-Millis=[1472720489720], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472720489704]}
09-01 11:01:29.720  1035  8352 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-01 11:01:29.720  1035  8352 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-01 11:01:29.721  1035  1501 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-01 11:01:29.721  1035  1501 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-01 11:01:29.721  1035  1501 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
09-01 11:01:29.721  1035  1501 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:29.721  1035  1501 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-01 11:01:29.721  1035  1501 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-01 11:01:29.721  1035  1501 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-01 11:01:29.721  1035  1501 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:29.721  1035  1501 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ],
09-01 11:01:29.721  1035  1501 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:29.722  1035  1501 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:29.722  1035  1501 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-01 11:01:29.723  1035  1440 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:29.723  1035  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:01:29.723  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:01:29.723  1604  2114 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-01 11:01:29.724  1854  1854 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:29.724  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-01 11:01:29.728  6931  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:01:29.728  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:29.728  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:29.728  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:29.728  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:01:29.728  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:29.728  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:01:29.728  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:01:29.731  6931  7010 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:29.731  6931  7010 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:01:29.732  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:01:29.732  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c4bce0 added. We now have 3 listener(s)
09-01 11:01:29.733  1035  1726 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:29.734  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:29.735  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:01:29.736  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:01:29.736  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:01:29.736  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:29.736  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@790db99 added. We now have 10 listener(s)
09-01 11:01:29.736  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:29.736  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start opera,tion: Should affect listening to advertisements only
09-01 11:01:29.736  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:01:29.736  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:01:29.736  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:01:29.736  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:01:29.738  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:29.738  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:01:29.739  1035  1699 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-01 11:01:29.742  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:29.744  8332  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-01 11:01:29.745  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:01:29.746  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 11:01:29.748  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:01:29.748  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:01:29.750  6931  7010 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 11:01:29.751  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:29.751  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:01:29.753  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:01:29.754  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:29.755  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:01:29.755  8376  8376 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-01 11:01:29.755  8376  8376 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-01 11:01:29.755  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:29.755  8376  8376 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-01 11:01:29.755  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:29.755  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:29.755  8376  8376 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-01 11:01:29.755  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:29.755  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:29.755  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:01:29.755  8376  8376 D dhcpcd  : wlan0: sending REQUEST (xid 0x5816c4ed), next in 3.10 seconds
09-01 11:01:29.756  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:01:29.756  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1176b29d removed from the list
09-01 11:01:29.756  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:29.756  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c641312 removed from the list
09-01 11:01:29.756  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:29.756  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:29.758  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:29.758  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:29.759  7986  8089 D UEI.SmartControl: Internal timer expired: 3
09-01 11:01:29.759  7986  8089 D UEI.SmartControl: unbind internal service
09-01 11:01:29.759  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:01:29.761  7986  7986 D UEI.SmartControl: Service.onUnbind: IControl
09-01 11:01:29.761  7986  7986 D UEI.SmartControl: Service.onDestroy
09-01 11:01:29.761  7986  7986 D UEI.SmartControl: Lock is in USE false
09-01 11:01:29.761  7986  7986 D UEI.SmartControl: unbind internal service
09-01 11:01:29.762  7986  7986 D serial_port: close(fd = 24)
,09-01 11:01:29.762  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:29.762  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:29.762  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:29.762  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c641312 not in the list
09-01 11:01:29.762  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:29.762  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:29.762  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:01:29.763  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:29.763  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:29.763  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:01:29.763  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:29.763  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@790db99 removed from the list
09-01 11:01:29.763  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:29.763  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:29.763  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:29.763  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:01:29.763  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c4bce0 removed from the list
09-01 11:01:29.764  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:01:29.764  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b68c70c added. We now have 2 listener(s)
09-01 11:01:29.764  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:29.767  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:01:29.767  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:01:29.767  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:01:29.767  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:29.767  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@178a9855 added. We now have 9 listener(s)
09-01 11:01:29.767  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:29.767  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:01:29.769  7986  7986 I UEI.SmartControl: Serial port is closed.
09-01 11:01:29.769  7986  7986 I UEI.SmartControl: Serial port is closed.
09-01 11:01:29.769  7986  7986 D UEI.SmartControl: Blaster closed
09-01 11:01:29.769  7986  7986 D UEI.SmartControl: Shut down QS...
09-01 11:01:29.769  7986  7986 D UEI.SmartControl: Stopping QS lib
09-01 11:01:29.769  7986  7986 D UEI.SmartControl: QS lib stop result = true
09-01 11:01:29.769  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:01:29.769  7986  7986 D UEI.SmartControl: Stopped QS lib
09-01 11:01:29.769  7986  7986 D UEI.SmartControl: QS shutdown complete
09-01 11:01:29.771  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:29.773  6931  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:01:29.773  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:29.773  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:29.773  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:29.773  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is ,Bluetooth enabled: true
09-01 11:01:29.773  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:29.773  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:01:29.773  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:01:29.774  6931  7010 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:29.774  6931  7010 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:01:29.774  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:01:29.774  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b21b35b added. We now have 3 listener(s)
,09-01 11:01:29.776  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:29.777  8376  8376 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-01 11:01:29.778  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:29.816  8376  8376 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-01 11:01:29.816  8376  8376 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-01 11:01:29.816  8376  8376 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-01 11:01:29.816  8376  8376 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-01 11:01:29.816  8376  8376 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-01 11:01:29.816  8376  8376 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-01 11:01:29.816  8376  8376 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-01 11:01:29.816  8376  8376 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-01 11:01:29.822  1035  1967 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8388 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-01 11:01:29.823  1035  1967 I ActivityManager: Killing 7442:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
09-01 11:01:29.842   343   343 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 375us total 21.211ms
,09-01 11:01:29.861   343   343 I art     : Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 475us total 17.808ms
,09-01 11:01:29.874   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 264us total 12.194ms
09-01 11:01:29.897  8332  8377 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-01 11:01:30.068  1035  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-01 11:01:30.071  1035  1684 W libprocessgroup: failed to open /acct/uid_10093/pid_7442/cgroup.procs: No such file or directory
,09-01 11:01:30.077  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:01:30.077  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:01:30.077  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:01:30.078  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:30.078  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@356147f8 added. We now have 10 listener(s)
09-01 11:01:30.078  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:30.079  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:01:30.081  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 11:01:30.087  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:01:30.087  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:01:30.087  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:01:30.087  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:01:30.099  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 11:01:30.099  1035  1684 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:30.105  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:01:30.110  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 11:01:30.112  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:01:30.112  1035  8353 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-01 11:01:30.114  1035  8353 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-01 11:01:30.114  1035  8353 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-01 11:01:30.114  1035  8353 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-01 11:01:30.114  1035  8353 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-01 11:01:30.114  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:01:30.114  1035  8353 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-01 11:01:30.114  1035  8353 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-01 11:01:30.114  1035  8353 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-01 11:01:30.115  1035  8353 D DhcpStateMachine: RunningState
09-01 11:01:30.116  6931  7010 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 11:01:30.117  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:30.117  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:30.117  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:30.117  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:30.117  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:30.117  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:01:30.117  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:01:30.117  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b68c70c removed from the list
09-01 11:01:30.117  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:30.117  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@178a9855 removed from the list
09-01 11:01:30.117  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:30.117  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:30.118  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:30.118  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:30.119  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:30.119  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:30.119  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:30.119  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@178a9855 not in the list
09-01 11:01:30.119  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:30.119  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:30.120  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDisc,overy
09-01 11:01:30.121  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:30.121  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:30.121  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:30.121  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:30.121  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@356147f8 removed from the list
09-01 11:01:30.121  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:30.121  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:30.121  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:30.121  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:01:30.121  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b21b35b removed from the list
09-01 11:01:30.122  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:01:30.122  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39be2a37 added. We now have 2 listener(s)
09-01 11:01:30.122  1035  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:30.125  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:01:30.125  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:01:30.125  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:01:30.125  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:30.125  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@245eeba4 added. We now have 9 listener(s),
09-01 11:01:30.125  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:30.126  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 11:01:30.128  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:01:30.132  8388  8388 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:01:30.133  6931  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:01:30.133  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:30.133  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:30.133  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:30.133  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:01:30.133  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:30.133  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:01:30.133  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:01:30.135  6931  7010 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:30.135  6931  7010 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:01:30.135  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:01:30.135  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e5364c2 added. We now have 3 listener(s)
09-01 11:01:30.136  1035  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:30.138  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:01:30.139  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:01:30.139  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:01:30.139  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 11:01:30.139  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:30.139  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@224132d3 added. We now have 10 listener(s)
09-01 11:01:30.140  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:30.140  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:01:30.140  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:01:30.140  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:01:30.140  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:01:30.140  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:01:30.141  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:30.143  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:01:30.143  1035  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:30.147  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:01:30.148  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 11:01:30.150  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:01:30.150  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:01:30.152  6931  7010 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 11:01:30.154  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:30.154  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:30.154  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:30.154  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:30.155  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:30.155  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:01:30.155  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:01:30.155  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39be2a37 removed from the list
09-01 11:01:30.155  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:30.155  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@245eeba4 removed from the list
09-01 11:01:30.155  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:30.155  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:30.155  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:30.155  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:30.157  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:30.157  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:30.157  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:30.157  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@245eeba4 not in the list
09-01 11:01:30.157  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:30.157  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:30.158  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:30.159  6931  7010 D BluetoothLeScanner: could not find callback wrapper
09-01 11:01:30.159  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:01:30.159  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:30.159  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:30.159  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@224132d3 removed from the list
09-01 11:01:30.159  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:30.159  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:30.159  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:30.159  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:01:30.159  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e5364c2 removed from the list
09-01 11:01:30.160  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:01:30.160  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11770b0e added. We now have 2 listener(s)
09-01 11:01:30.160  1035  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:30.163  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of th,e following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:01:30.163  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:01:30.163  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:01:30.163  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:30.163  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe2292f added. We now have 9 listener(s)
09-01 11:01:30.163  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:30.163  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:01:30.166  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:01:30.170  6931  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:01:30.170  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:01:30.170  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:01:30.170  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:01:30.170  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:01:30.170  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:30.170  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:01:30.170  6931  7010 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:01:30.172  6931  7010 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:01:30.172  6931  7010 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:01:30.172  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:01:30.172  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122340c5 added. We now have 3 listener(s)
09-01 11:01:30.173  8388  8388 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-01 11:01:30.173  1035  1726 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:01:30.177  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:30.179  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:01:30.179  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:01:30.179  6931  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:01:30.179  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:01:30.179  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:01:30.179  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@141cca1a added. We now have 10 listener(s)
09-01 11:01:30.179  6931  7010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:01:30.180  6931  7010 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:01:30.180  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:30.180  6931  7010 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:01:30.180  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 11:01:30.180  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:30.180  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:01:30.180  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:01:30.180  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11770b0e removed from the list
09-01 11:01:30.180  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:30.180  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe2292f removed from the list
09-01 11:01:30.180  6931  7010 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:01:30.180  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:30.181  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:30.181  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:30.182  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:30.182  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:30.182  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:30.182  6931  7010 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe2292f not in the list
09-01 11:01:30.182  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:01:30.182  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:30.183  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:01:30.183  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:01:30.183  6931  7010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:01:30.183  6931  7010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@141cca1a removed from the list
,09-01 11:01:30.183  6931  7010 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:01:30.183  6931  7010 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:01:30.183  6931  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:01:30.183  6931  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:01:30.184  6931  7010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122340c5 removed from the list
09-01 11:01:30.185  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-01 11:01:30.185  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-01 11:01:30.185  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-01 11:01:30.185  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:01:30.186  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-01 11:01:30.186  6931  7010 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 11:01:30.197  6931  8432 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 915, name: My test thread name)
,09-01 11:01:30.197  6931  8432 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 915, thread name: My test thread name)
09-01 11:01:30.198  6931  8432 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 915, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-01 11:01:30.202  6931  8433 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 917, name: My test thread name)
09-01 11:01:30.202  6931  8433 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 917, thread name: My test thread name)
09-01 11:01:30.203  6931  8433 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 917, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-01 11:01:30.205  6931  7010 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-01 11:01:30.206  6931  7010 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-01 11:01:30.206  6931  7010 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-01 11:01:30.206  6931  7010 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-01 11:01:30.206  6931  7010 D com.test.thalitest.ThaliTestRunner: Total duration: 23435 ms
09-01 11:01:30.207  6931  7010 I jxcore-log: *Native tests were executed*
09-01 11:01:30.207  6931  7010 I jxcore-log: 
09-01 11:01:30.208  6931  7010 I jxcore-log: Total number of executed tests:  80
09-01 11:01:30.208  6931  7010 I jxcore-log: 
09-01 11:01:30.208  6931  7010 I jxcore-log: Number of passed tests:  80
09-01 11:01:30.208  6931  7010 I jxcore-log: 
09-01 11:01:30.208  6931  7010 I jxcore-log: Number of failed tests:  0
09-01 11:01:30.208  6931  7010 I jxcore-log: 
09-01 11:01:30.208  6931  7010 I jxcore-log: Number of ignored tests:  0
09-01 11:01:30.208  6931  7010 I jxcore-log: 
09-01 11:01:30.209  6931  7010 I jxcore-log: Total duration:  23435
09-01 11:01:30.209  6931  7010 I jxcore-log: 
09-01 11:01:30.209  6931  7010 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-01 11:01:30.209  6931  7010 I jxcore-log: 
09-01 11:01:30.214  8388  8388 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-01 11:01:30.215  8388  8388 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-01 11:01:30.215  8388  8388 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,09-01 11:01:30.216  8388  8388 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-01 11:01:30.216  8388  8388 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-01 11:01:30.217  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:01:30.217  6931  7010 I jxcore-log: 
09-01 11:01:30.218  8388  8388 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-01 11:01:30.223  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:01:30.223  6931  7010 I jxcore-log: 
09-01 11:01:30.225  8388  8388 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-01 11:01:30.226  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:01:30.226  6931  7010 I jxcore-log: 
09-01 11:01:30.228  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:01:30.228  6931  7010 I jxcore-log: 
09-01 11:01:30.228  6931  6931 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-01 11:01:30.230  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:01:30.230  6931  7010 I jxcore-log: 
09-01 11:01:30.231  8388  8388 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:30.233  8388  8388 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:30.233  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:01:30.233  6931  7010 I jxcore-log: 
09-01 11:01:30.238  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:01:30.238  6931  7010 I jxcore-log: 
09-01 11:01:30.238  8332  8377 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:01:30.238  8332  8377 D LgDataFeature: LgDataFeature() Constructor Done, null
09-01 11:01:30.240  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:01:30.240  6931  7010 I jxcore-log: 
09-01 11:01:30.241  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:01:30.241  6931  7010 I jxcore-log: 
09-01 11:01:30.242  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:01:30.242  6931  7010 I jxcore-log: 
09-01 11:01:30.243  8388  8388 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-01 11:01:30.243  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 11:01:30.243  6931  7010 I jxcore-log: 
09-01 11:01:30.245  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:30.245  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:01:30.245  6931  7010 I jxcore-log: 
09-01 11:01:30.245  8332  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-01 11:01:30.247  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:01:30.247  6931  7010 I jxcore-log: 
09-01 11:01:30.247  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:01:30.247  6931  7010 I jxcore-log: 
09-01 11:01:30.248  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:01:30.248  6931  7010 I jxcore-log: 
09-01 11:01:30.249  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:01:30.249  6931  7010 I jxcore-log: 
09-01 11:01:30.249  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:01:30.250  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:01:30.250  6931  7010 I jxcore-log: 
09-01 11:01:30.251  8388  8388 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-01 11:01:30.251  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:01:30.251  6931  7010 I jxcore-log: 
09-01 11:01:30.252  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:01:30.252  6931  7010 I jxcore-log: 
09-01 11:01:30.253  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:01:30.253  6931  7010 I jxcore-log: 
09-01 11:01:30.254  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:01:30.254  6931  7010 I jxcore-log: 
09-01 11:01:30.254  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:30.254  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:01:30.254  6931  7010 I jxcore-log: 
09-01 11:01:30.255  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:01:30.255  6931  7010 I jxcore-log: 
09-01 11:01:30.255  8388  8388 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-01 11:01:30.256  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:01:30.256  6931  7010 I jxcore-log: 
09-01 11:01:30.257  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:01:30.257  6931  7010 I jxcore-log: 
09-01 11:01:30.258  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:01:30.258  6931  7010 I jxcore-log: 
,09-01 11:01:30.259  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:01:30.259  6931  7010 I jxcore-log: 
09-01 11:01:30.259  8388  8388 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:30.259  8388  8388 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:30.259  6931  7010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:01:30.259  6931  7010 I jxcore-log: 
09-01 11:01:30.260  8388  8388 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-01 11:01:30.262  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-01 11:01:30.264  7068  7068 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-01 11:01:30.267  8332  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-01 11:01:30.267  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:30.272  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:30.281  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:30.285  8388  8388 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:30.285  8388  8388 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:30.286  8388  8388 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-01 11:01:30.289  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:30.289  8332  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-01 11:01:30.295  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:30.300  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:30.307  8388  8388 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:30.307  8388  8388 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:30.307  8388  8388 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:01:30.310  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:01:30.311  8332  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-01 11:01:30.318  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:30.325  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:30.330  8388  8388 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:30.331  8388  8388 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:30.331  8388  8388 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:01:30.334  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-01 11:01:30.334  7068  7068 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-01 11:01:30.334  7068  7068 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,09-01 11:01:30.334  7068  7068 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-01 11:01:30.334  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-01 11:01:30.335  7068  7068 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:01:30.335  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-01 11:01:30.335  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-01 11:01:30.335  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,09-01 11:01:30.335  7068  7068 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:01:30.335  7068  7068 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-01 11:01:30.336  7068  7068 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-01 11:01:30.340  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:30.340  8332  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-01 11:01:30.345  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:30.351  8332  8377 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-01 11:01:30.351  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:30.359  8388  8388 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-01 11:01:30.359  8388  8388 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:30.359  8388  8388 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:01:30.362  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:30.362  8332  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-01 11:01:30.369  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:01:30.373  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-01 11:01:30.379  8388  8388 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:30.380  8388  8388 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:30.380  8388  8388 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:01:30.381  8332  8377 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-01 11:01:30.389  8332  8377 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,09-01 11:01:30.389  8332  8377 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-01 11:01:30.394  8332  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-01 11:01:30.394  8332  8377 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-01 11:01:30.395  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:30.396  8332  8377 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-01 11:01:30.397  8332  8377 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-01 11:01:30.398  1819  8440 I CheckinService: active receiver: enabled
,09-01 11:01:30.401  8332  8377 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-01 11:01:30.408  1819  8440 I CheckinService: Preparing to send checkin request
,09-01 11:01:30.408  1819  8440 I EventLogService: Accumulating logs since 1472720472608
09-01 11:01:30.409  8332  8377 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-01 11:01:30.413  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:30.418  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:30.426  8388  8388 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:30.426  8388  8388 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:30.431  8388  8388 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:01:30.434  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:30.434  8332  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-01 11:01:30.441  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:01:30.442  1819  8440 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-01 11:01:30.449  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:30.455  8388  8388 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:30.455  8388  8388 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:30.455  8388  8388 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-01 11:01:30.458  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:30.459  8332  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-01 11:01:30.461  8437  8437 D AndroidRuntime: 
09-01 11:01:30.461  8437  8437 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-01 11:01:30.462  8285  8285 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-01 11:01:30.463  8437  8437 D AndroidRuntime: CheckJNI is OFF
09-01 11:01:30.470  8285  8285 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:01:30.476  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:01:30.482  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:30.487  8388  8388 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:30.487  8388  8388 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:30.488  8388  8388 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-01 11:01:30.489  8388  8388 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-01 11:01:30.489  8388  8388 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-01 11:01:30.493  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:01:30.495  8285  8285 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-01 11:01:30.495  8285  8285 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:01:30.496  8332  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-01 11:01:30.498  7068  7068 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:01:30.504  7068  7068 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:01:30.508  8388  8388 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:01:30.508  8388  8388 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:01:30.509  8388  8388 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-01 11:01:30.509  8388  8388 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-01 11:01:30.509  8388  8388 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-01 11:01:30.512  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-01 11:01:30.516  8388  8388 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-01 11:01:30.519  8388  8388 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-01 11:01:30.519  8388  8388 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-01 11:01:30.543  8388  8388 D LgDataFeature: LgDataFeature() Constructor: none
,09-01 11:01:30.543  8388  8388 D LgDataFeature: LgDataFeature() Constructor Done, null
09-01 11:01:30.548  8388  8388 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-01 11:01:30.549  8388  8388 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-01 11:01:30.549  8388  8388 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-01 11:01:30.549  8388  8388 V SoundPool: doLoad: loading sample sampleID=1
09-01 11:01:30.549  8388  8388 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-01 11:01:30.551  8388  8458 V SoundPool: Start decode
09-01 11:01:30.551  8388  8458 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-01 11:01:30.551  7986  7986 D UEI.SmartControl: QS Service created
09-01 11:01:30.552   312  1397 V MediaPlayerService: decode(22, 10857164, 17813)
09-01 11:01:30.552   312  1397 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-01 11:01:30.552   312  1397 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-01 11:01:30.552   312  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-01 11:01:30.552   312  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-01 11:01:30.552   312  1397 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-01 11:01:30.552   312  1397 V MediaPlayerService: player type = 3
09-01 11:01:30.552   312  1397 V AwesomePlayer: AwesomePlayer create()
09-01 11:01:30.552   312  1397 V AwesomePlayer: reset_l() 
09-01 11:01:30.552   312  1397 V AwesomePlayer: cancelPlayerEvents
09-01 11:01:30.552   312  1397 V AwesomePlayer: setAudioSink() 
09-01 11:01:30.552   312  1397 V AwesomePlayer: reset_l() 
09-01 11:01:30.552   312  1397 V AudioCache: notify(0xb0409500, 8, 0, 0)
09-01 11:01:30.552   312  1397 V AudioCache: ignored
09-01 11:01:30.552   312  1397 V AwesomePlayer: cancelPlayerEvents
09-01 11:01:30.552   312  1397 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-01 11:01:30.553   312  1397 V AwesomePlayer: setDataSource_l dataSource
09-01 11:01:30.553   312  1397 V LGParserOSAL: SniffLGParser start
09-01 11:01:30.553   312  1397 V LGParserOSAL: MainType:5, SubType=0
09-01 11:01:30.553   312  1397 V LGParserOSAL: #### check Mime : application/ogg
09-01 11:01:30.553   312  1397 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-01 11:01:30.553   312  1397 E MediaExtractor: Use LGExtractor :application/ogg 
09-01 11:01:30.563  8437  8437 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-01 11:01:30.564  8388  8388 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-01 11:01:30.569  8388  8388 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-01 11:01:30.569  8388  8388 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,09-01 11:01:30.573  1035  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-01 11:01:30.573  1035  1092 I ActivityManager: Killing 6931:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-01 11:01:30.574   312  1397 V LGParserOSAL: supported mime: application/ogg
09-01 11:01:30.574   312  1397 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-01 11:01:30.574   312  1397 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-01 11:01:30.574   312  1397 V AwesomePlayer: mBitrate = -1 bits/sec
09-01 11:01:30.574   312  1397 V AwesomePlayer: AudioTrack Setting
09-01 11:01:30.574   312  1397 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-01 11:01:30.574   312  1397 V AwesomePlayer: setAudioSource() 
09-01 11:01:30.574   312  1397 V MediaPlayerService: prepare
09-01 11:01:30.574   312  1397 V AwesomePlayer: prepareAsync_l() 
09-01 11:01:30.574   312  1397 V MediaPlayerService: wait for prepare
09-01 11:01:30.574   312  8461 V AwesomePlayer: onPrepareAsyncEvent() 
09-01 11:01:30.574   312  8461 V AwesomePlayer: initAudioDecoder() 
09-01 11:01:30.574   312  8461 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-01 11:01:30.574   312  8461 V AudioSystem: isOffloadSupported()
09-01 11:01:30.575   312  8461 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-01 11:01:30.575   312  8461 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-01 11:01:30.575   312  8461 I AudioFlinger: isAudioPlaybackHookOn() false
09-01 11:01:30.575   312  8461 V AwesomePlayer: getUseOffload() = 0 
09-01 11:01:30.575   312  8461 V OMXCodec: OMXCodec::Create
09-01 11:01:30.575   312  8461 V OMXCodec: findMatchingCodecs()
09-01 11:01:30.575   312  8461 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-01 11:01:30.575   312  8461 V OMXCodec: matchingCodecs.size()=1
09-01 11:01:30.575   312  8461 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-01 11:01:30.576   312  8461 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-01 11:01:30.576   312  8461 V LGCodecAdapter: LG Codec Adapter start
09-01 11:01:30.576   312  8461 V OMXCodec: OMXCodec Createtor
09-01 11:01:30.576   312  8461 V OMXCodec: setComponentRole
09-01 11:01:30.576   312  8461 V OMXCodec: configureCodec protected=0
09-01 11:01:30.576   312  8461 V LGCodecAdapter: called getLGCodecSpecificData
09-01 11:01:30.576   312  8461 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-01 11:01:30.576   312  8461 V LGCodecOSAL: Called LGconfigureCodecMETA
09-01 11:01:30.576   312  8461 V LGCodecOSAL: Called LGconfigureCodecMSG
09-01 11:01:30.576   312  8461 V LGCodecOSAL: Not support LGCodec
09-01 11:01:30.576   312  8461 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-01 11:01:30.576   312  8461 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-01 11:01:30.576   312  8461 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-01 11:01:30.576   312  8461 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-01 11:01:30.576   312  8461 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-01 11:01:30.576   312  8461 V AudioSystem: isOffloadSupported()
09-01 11:01:30.576   312  8461 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-01 11:01:30.576   312  8461 D AudioPolicyManager: isOffloadSupported: stream_t,ype != MUSIC, returning false
09-01 11:01:30.576   312  8461 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-01 11:01:30.576   312  8461 V OMXCodec: init()
09-01 11:01:30.576   312  8461 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-01 11:01:30.576   312  8461 V OMXCodec: allocateBuffers
09-01 11:01:30.576   312  8461 V OMXCodec: allocateBuffersOnPort portIndex=0
09-01 11:01:30.576   312  8461 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-01 11:01:30.576   312  8461 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
09-01 11:01:30.576   312  8461 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
09-01 11:01:30.576   312  8461 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
09-01 11:01:30.576   312  8461 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
09-01 11:01:30.576   312  8461 V OMXCodec: allocateBuffersOnPort portIndex=1
09-01 11:01:30.576   312  8461 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-01 11:01:30.576   312  8461 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-01 11:01:30.576   312  8461 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
09-01 11:01:30.576   312  8461 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-01 11:01:30.576   312  8461 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
09-01 11:01:30.576   312  8461 V OMXCodec: init() mAsyncCompletion wait!!! 
09-01 11:01:30.576   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-01 11:01:30.576   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-01 11:01:30.576   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-01 11:01:30.577   312  8461 V OMXCodec: init() mAsyncCompletion wait!!! 
09-01 11:01:30.577   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-01 11:01:30.577   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-01 11:01:30.577   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-01 11:01:30.577   312  8461 V OMXCodec: init() mAsyncCompletion wait free! 
09-01 11:01:30.577   312  8461 V AwesomePlayer: finishAsyncPrepare_l() 
09-01 11:01:30.577   312  8461 V AudioCache: notify(0xb0409500, 5, 0, 0)
09-01 11:01:30.577   312  8461 V AudioCache: ignored
09-01 11:01:30.577   312  8461 V AudioCache: notify(0xb0409500, 1, 0, 0)
09-01 11:01:30.577   312  8461 V AudioCache: prepared
09-01 11:01:30.577   312  1397 V AudioCache: wait - success
09-01 11:01:30.577   312  1397 V MediaPlayerService: start
09-01 11:01:30.577   312  1397 V AwesomePlayer: play_l() 
09-01 11:01:30.577   312  1397 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-01 11:01:30.577   312  1397 V AwesomePlayer: createAudioPlayer_l
09-01 11:01:30.577   312  1397 V AwesomePlayer: seekAudioIfNecessary_l() 
09-01 11:01:30.577   312  1397 V AwesomePlayer: startAudioPlayer_l() 
09-01 11:01:30.577   312  1397 D AudioPlayer: start of Playback, useOffload 0
09-01 11:01:30.577   312  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-01 11:01:30.577   312  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-01 11:01:30.577  7986  7986 I UEI.SmartControl: Service initServices...
09-01 11:01:30.577  7986  7986 D UEI.SmartControl: QS start get config
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.dec,oder] disablePortAsync portIndex=1
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-01 11:01:30.578   312  8463 V OMXCodec: allocateBuffersOnPort portIndex=1
09-01 11:01:30.578   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-01 11:01:30.579   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-01 11:01:30.579   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
09-01 11:01:30.579   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-01 11:01:30.579   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c21f0 on output port
09-01 11:01:30.579   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-01 11:01:30.579   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-01 11:01:30.579   312  1397 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-01 11:01:30.579  8388  8388 V LGMDMManager: Create singleton instance
09-01 11:01:30.579   312  1397 V AudioCache: notify(0xb0409500, 6, 0, 0)
09-01 11:01:30.579   312  1397 V AudioCache: ignored
09-01 11:01:30.580   312  1397 V MediaPlayerService: wait for playback complete
09-01 11:01:30.581   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.581   312  8464 V AudioCache: memcpy(0xaf0f9000, 0xb0403000, 4096)
09-01 11:01:30.583   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.583   312  8464 V AudioCache: memcpy(0xaf0fa000, 0xb0403000, 4096)
09-01 11:01:30.587   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.587   312  8464 V AudioCache: memcpy(0xaf0fb000, 0xb0403000, 4096)
09-01 11:01:30.588   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.588   312  8464 V AudioCache: memcpy(0xaf0fc000, 0xb0403000, 4096)
09-01 11:01:30.589   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.589   312  8464 V AudioCache: memcpy(0xaf0fd000, 0xb0403000, 4096)
09-01 11:01:30.589   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.589   312  8464 V AudioCache: memcpy(0xaf0fe000, 0xb0403000, 4096)
09-01 11:01:30.589   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.589   312  8464 V AudioCache: memcpy(0xaf0ff000, 0xb0403000, 4096)
09-01 11:01:30.590   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.590   312  8464 V AudioCache: memcpy(0xaf100000, 0xb0403000, 4096)
09-01 11:01:30.590   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.590   312  8464 V AudioCache: memcpy(0xaf101000, 0xb0403000, 4096)
09-01 11:01:30.590   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.590   312  8464 V AudioCache: memcpy(0xaf102000, 0xb0403000, 4096)
09-01 11:01:30.590   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.590   312  8464 V AudioCache: memcpy(0xaf103000, 0xb0403000, 4096)
09-01 11:01:30.591   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.591   312  8464 V AudioCache: memcpy(0xaf104000, 0xb0403000, 4096)
09-01 11:01:30.591   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.591   312  8464 V AudioCache: memcpy(0xaf105000, 0xb0403000, 4096)
09-01 11:01:30.591   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.591   312  8464 V AudioCache: memcpy(0xaf106000, 0xb0403000, 4096)
09-01 11:01:30.592   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.592   312  8464 V AudioCache: memcpy(0xaf107000, 0xb0403000, 4096)
09-01 11:01:30.592   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.592   312  8464 V AudioCache: memcpy(0xaf108000, 0xb0403000, 4096)
09-01 11:01:30.593   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.593   312  8464 V AudioCache: memcpy(0xaf109000, 0xb0403000, 4096)
09-01 11:01:30.593   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.593   312  8464 V AudioCache: memcpy(0xaf10a000, 0xb0403000, 4096)
09-01 11:01:30.593   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.593   312  8464 V AudioCache: memcpy(0xaf10b000, 0xb0403000, 4096)
09-01 11:01:30.593   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.593   312  8464 V AudioCache: memcpy(0xaf10c000, 0xb0403000, 4096)
09-01 11:01:30.594   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.594   312  8464 V AudioCache: memcpy(0xaf10d000, 0xb0403000, 4096)
09-01 11:01:30.594   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.594   312  8464 V AudioCache: memcpy(0xaf10e000, 0xb0403000, 4096)
09-01 11:01:30.594   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.595   312  8464 V AudioCache: memcpy(0xaf10f000, 0xb0403000, 4096)
09-01 11:01:30.595   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.595   312  8464 V AudioCache: memcpy(0xaf110000, 0xb0403000, 4096)
09-01 11:01:30.597   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.597   312  8464 V AudioCache: memcpy(0xaf111000, 0xb0403000, 4096)
09-01 11:01:30.598   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.598   312  8464 V AudioCache: memcpy(0xaf112000, 0xb0403000, 4096)
09-01 11:01:30.598   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.598   312  8464 V AudioCache: memcpy(0xaf113000, 0xb0403000, 4096)
09-01 11:01:30.599   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.599   312  8464 V AudioCache: memcpy(0xaf114000, 0xb0403000, 4096)
09-01 11:01:30.599   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.599   312  8464 V AudioCache: memcpy(0xaf115000, 0xb0403000, 4096)
09-01 11:01:30.599   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.599   312  8464 V AudioCache: memcpy(0xaf116000, 0xb0403000, 4096)
09-01 11:01:30.600   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.600   312  8464 V AudioCache: memcpy(0xaf117000, 0xb0403000, 4096)
09-01 11:01:30.600   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.600   312  8464 V AudioCache: memcpy(0xaf118000, 0xb0403000, 4096)
09-01 11:01:30.600   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.601   312  8464 V AudioCache: memcpy(0xaf119000, 0xb0403000, 4096)
09-01 11:01:30.601   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.601   312  8464 V AudioCache: memcpy(0xaf11a000, 0xb0403000, 4096)
09-01 11:01:30.601   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.601   312  8464 V AudioCache: memcpy(0xaf11b000, 0xb0403000, 4096)
09-01 11:01:30.603   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.603   312  8464 V AudioCache: memcpy(0xaf11c000, 0xb0403000, 4096)
09-01 11:01:30.603   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.603   312  8464 V AudioCache: memcpy(0xaf11d000, 0xb0403000, 4096)
09-01 11:01:30.604   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.604   312  8464 V AudioCache: memcpy(0xaf11e000, 0xb0403000, 4096)
09-01 11:01:30.604   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.604   312  8464 V AudioCache: memcpy(0xaf11f000, 0xb0403000, 4096)
09-01 11:01:30.604   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.604   312  8464 V AudioCache: memcpy(0xaf120000, 0xb0403000, 4096)
09-01 11:01:30.605   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.605   312  8464 V AudioCache: memcpy(0xaf121000, 0xb0403000, 4096)
09-01 11:01:30.605   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.605   312  8464 V AudioCache: memcpy(0xaf122000, 0xb0403000, 4096)
09-01 11:01:30.606   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.606   312  8464 V AudioCache: memcpy(0xaf123000, 0xb0403000, 4096)
09-01 11:01:30.606   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.606   312  8464 V AudioCache: memcpy(0xaf124000, 0xb0403000, 4096)
09-01 11:01:30.608   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.608   312  8464 V AudioCache: memcpy(0xaf125000, 0xb0403000, 4096)
09-01 11:01:30.608   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.608   312  8464 V AudioCache: memcpy(0xaf126000, 0xb0403000, 4096)
09-01 11:01:30.609   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.609   312  8464 V AudioCache: memcpy(0xaf127000, 0xb0403000, 4096)
09-01 11:01:30.609   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.609   312  8464 V AudioCache: memcpy(0xaf128000, 0xb0403000, 4096)
09-01 11:01:30.609   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.610   312  8464 V AudioCache: memcpy(0xaf129000, 0xb0403000, 4096)
09-01 11:01:30.610   312  8464 V AudioCache: write(0xb0403000, 4096)
09-01 11:01:30.610   312  8464 V AudioCache: memcpy(0xaf12a000, 0xb0403000, 4096)
09-01 11:01:30.610   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-01 11:01:30.610   312  8464 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-01 11:01:30.610   312  8464 V AwesomePlayer: postAudioEOS() 
09-01 11:01:30.610   312  8464 V AudioCache: write(0xb0403000, 280)
09-01 11:01:30.610   312  8464 V AudioCache: memcpy(0xaf12b000, 0xb0403000, 280)
09-01 11:01:30.614   312  8461 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-01 11:01:30.614   312  8461 V AwesomePlayer: onStreamDone
09-01 11:01:30.614   312  8461 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-01 11:01:30.614   312  8461 V AudioCache: notify(0xb0409500, 2, 0, 0)
09-01 11:01:30.614   312  8461 V AudioCache: playback complete
09-01 11:01:30.615   312  8461 V AwesomePlayer: pause_l() 
09-01 11:01:30.615   312  8461 V AudioCache: notify(0xb0409500, 7, 0, 0)
09-01 11:01:30.615   312  8461 V AudioCache: ignored
09-01 11:01:30.615   312  8461 V AwesomePlayer: cancelPlayerEvents
09-01 11:01:30.615   312  8461 D AudioPlayer: Pause Playback at 1068125
09-01 11:01:30.615   312  1397 V AudioCache: wait - success
09-01 11:01:30.615   312  1397 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-01 11:01:30.615   312  1397 V AwesomePlayer: reset_l() 
09-01 11:01:30.615   312  1397 V AudioCache: notify(0xb0409500, 8, 0, 0)
09-01 11:01:30.615   312  1397 V AudioCache: ignored
09-01 11:01:30.615   312  1397 V AwesomePlayer: cancelPlayerEvents
09-01 11:01:30.615   312  1397 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-01 11:01:30.615   312  1397 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-01 11:01:30.615   312  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-01 11:01:30.615   312  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-01 11:01:30.615   312  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c21f0 on port 1
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
09-01 11:01:30.615   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:01:30.616   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-01 11:01:30.616   312  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-01 11:01:30.616   312  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-01 11:01:30.616  8388  8388 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-01 11:01:30.616   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-01 11:01:30.616   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-01 11:01:30.616   312  8463 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-01 11:01:30.616   312  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-01 11:01:30.616   312  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-01 11:01:30.616   312  1397 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-01 11:01:30.617   312  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-01 11:01:30.617   312  1397 D AudioPlayer: AudioPlayer releasing audio source
09-01 11:01:30.617   312  1397 D AudioPlayer: AudioPlayer done releasing audio source
09-01 11:01:30.617   312  1397 V AwesomePlayer: reset_l() 
09-01 11:01:30.617   312  1397 V AwesomePlayer: cancelPlayerEvents
09-01 11:01:30.617   312  1397 V AwesomePlayer: ~AwesomePlayer call
,09-01 11:01:30.617   312  1397 V AwesomePlayer: reset_l() 
09-01 11:01:30.617   312  1397 V AwesomePlayer: cancelPlayerEvents
09-01 11:01:30.620  8388  8458 V SoundPool: close(31)
09-01 11:01:30.620  8388  8458 V SoundPool: pointer = 0x9ffe8000, size = 205080, sampleRate = 48000, numChannels = 2
09-01 11:01:30.639  1035  1699 I WindowState: WIN DEATH: Window{31e0bafd u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-01 11:01:30.639  1035  1492 D WifiService: Client connection lost with reason: 4
,09-01 11:01:30.644  1035  1699 D InputDispatcher: Window went away: Window{31e0bafd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-01 11:01:30.675  8388  8388 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,09-01 11:01:30.781  1035  1092 E libprocessgroup: failed to kill 1 processes for processgroup 6931
09-01 11:01:30.782  1035  1092 I ActivityManager:   Force finishing activity ActivityRecord{14fa87de u0 com.test.thalitest/.MainActivity t6}
,09-01 11:01:30.823   330   345 E GBMv2   : DFP En is all cleared set to be enabled
,09-01 11:01:30.824  1035  1726 W ActivityManager: Spurious death for ProcessRecord{3464f8 6931:com.test.thalitest/u0a118}, curProc for 6931: null
09-01 11:01:30.825  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-01 11:01:30.825  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2fc669f6 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-01 11:01:30.825  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-01 11:01:30.826  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{360841f7 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-01 11:01:30.827  8388  8388 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4422
09-01 11:01:30.830  1035  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,09-01 11:01:30.843  7986  7986 I UEI.SmartControl: Supports setup maps: true
09-01 11:01:30.846  7986  7986 D UEI.SmartControl: QS start statue = true Error code = 0
09-01 11:01:30.846  7986  7986 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-01 11:01:30.846  7986  7986 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-01 11:01:30.847  7986  7986 I UEI.SmartControl: ### init IR Blaster...
09-01 11:01:30.849  7986  7986 D serial_port: Configuring serial port
,09-01 11:01:30.850  7986  7986 E UEI.SmartControl: UEIBLaster setting for 616
09-01 11:01:30.850  7986  7986 I UEI.SmartControl: Setting serial record hearder size = 2
09-01 11:01:30.850  7986  7986 I UEI.SmartControl: configuring settings for MAXQ616
09-01 11:01:30.850  7986  7986 I UEI.SmartControl: Get version...
09-01 11:01:30.859  3811  3811 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-01 11:01:30.859  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-01 11:01:30.860  2427  2597 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-01 11:01:30.861  7886  7886 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-01 11:01:30.861  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-01 11:01:30.864  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-01 11:01:30.865  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-01 11:01:30.866  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-01 11:01:30.867  1996  1996 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-01 11:01:30.867  2034  2075 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,09-01 11:01:30.870  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-01 11:01:30.871  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-01 11:01:30.871  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:30.872  1905  1905 D ActionManagerService: notifyUserLog: 1000003
09-01 11:01:30.872  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-01 11:01:30.873  3811  5039 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-01 11:01:30.873  1035  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-01 11:01:30.873  7986  8465 D UEI.SmartControl: serial port data available: 21
09-01 11:01:30.873  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-01 11:01:30.876  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-01 11:01:30.878  1035  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
09-01 11:01:30.880  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-01 11:01:30.881  3811  3826 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-01 11:01:30.881  1905  1905 D ActionManagerService: notifyUserLog: 1000004
09-01 11:01:30.882  5006  5006 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-01 11:01:30.882  3811  5039 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,09-01 11:01:30.882  5006  5006 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-01 11:01:30.882  5006  5006 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-01 11:01:30.882  5006  5006 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-01 11:01:30.882  5006  5006 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 11:01:30.882  5006  5006 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 11:01:30.882  5006  5006 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:01:30.882  5006  5006 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-01 11:01:30.882  5006  5006 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:01:30.882  5006  5006 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:01:30.882  5006  5006 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-01 11:01:30.882  5006  5006 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-01 11:01:30.883  7478  7523 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:01:30.883  7478  7523 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:01:30.883  7478  7523 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:01:30.883  7478  7523 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:01:30.883  7478  7523 I Adreno-EGL: Remote Branch: 
09-01 11:01:30.883  7478  7523 I Adreno-EGL: Local Patches: 
09-01 11:01:30.883  7478  7523 I Adreno-EGL: Reconstruct Branch: 
09-01 11:01:30.884  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-01 11:01:30.889  1604  1662 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-01 11:01:30.889  1604  1662 D KeyguardModel: createShortcutInfo...
09-01 11:01:30.890  1604  1662 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-01 11:01:30.890  1604  1662 D KeyguardModel: createShortcutInfo...
09-01 11:01:30.894  1604  1662 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-01 11:01:30.894  1604  1662 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:01:30.894  1604  1662 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-01 11:01:30.895  1604  1662 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-01 11:01:30.896  1604  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:01:30.896  1604  1662 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-01 11:01:30.897  1604  1662 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-01 11:01:30.897  1604  1662 D KeyguardModel: createShortcutInfo...
09-01 11:01:30.900  1604  1662 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-01 11:01:30.900  1604  1662 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:01:30.900  1604  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:01:30.900  1604  1662 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-01 11:01:30.901  1604  1662 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-01 11:01:30.901  1604  1662 D KeyguardModel: createShortcutInfo...
09-01 11:01:30.904  1604  1662 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:01:30.904  1604  1662 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-01 11:01:30.905  1604  1662 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-01 11:01:30.905  1604  1662 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-01 11:01:30.905  5122  5122 I art     : Explicit concurrent mark sweep GC freed 8260(472KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 407us total 67.638ms
09-01 11:01:30.905  7986  7986 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-01 11:01:30.905  7986  7986 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-01 11:01:30.905  7986  7986 I UEI.SmartControl: QS saving settings...
09-01 11:01:30.906  7986  7986 D UEI.SmartControl: IR Blaster version: 25672567
09-01 11:01:30.928  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
09-01 11:01:30.935  7986  8465 D UEI.SmartControl: serial port data available: 4
09-01 11:01:30.935  1604  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:01:30.935  1604  1662 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-01 11:01:30.935  7478  7523 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:01:30.935  7478  7523 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:01:30.935  7478  7523 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:01:30.935  7478  7523 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:01:30.935  7478  7523 I Adreno-EGL: Remote Branch: 
09-01 11:01:30.935  7478  7523 I Adreno-EGL: Local Patches: 
09-01 11:01:30.935  7478  7523 I Adreno-EGL: Reconstruct Branch: 
,09-01 11:01:30.949  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , expire_time: 0
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , display: false
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , animation: false }
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , expire_time: 0
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , display: false
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , animation: false }
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , create_time: 1472216588858
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , expire_time: 0
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , display: false
09-01 11:01:30.949  2034  2034 I GBoardWebViewUtils: , animation: false }
09-01 11:01:30.952  2034  8468 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,09-01 11:01:30.958  1604  1662 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-01 11:01:30.958  1604  1662 D KeyguardModel: createShortcutInfo...
09-01 11:01:30.966  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-01 11:01:30.967  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-01 11:01:30.968  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:30.989  7478  7523 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:01:30.989  7478  7523 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:01:30.989  7478  7523 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:01:30.989  7478  7523 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:01:30.989  7478  7523 I Adreno-EGL: Remote Branch: 
09-01 11:01:30.989  7478  7523 I Adreno-EGL: Local Patches: 
09-01 11:01:30.989  7478  7523 I Adreno-EGL: Reconstruct Branch: 
,09-01 11:01:31.003  1035  2033 V SIM_STK : Menu title from STK is T-Mobile
09-01 11:01:31.003  1035  2033 V SIM_STK : Menu title from STK is T-Mobile
,09-01 11:01:31.021  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
,09-01 11:01:31.036  7986  7986 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-01 11:01:31.044  7986  8471 I UEI.SmartControl: Device manager: loading config....
09-01 11:01:31.044  7986  8471 D UEI.SmartControl: ----------- loading internal config...
09-01 11:01:31.048  7986  8471 E UEI.SmartControl: Loading SETTINGS...
,09-01 11:01:31.049   323   413 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-01 11:01:31.050  3296  8473 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-01 11:01:31.055  7986  7986 E UEI.SmartControl: Services init done
09-01 11:01:31.055  7986  7986 D UEI.SmartControl: QS Service init finished
09-01 11:01:31.055  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:31.056  1604  1604 D KeyguardModel: handleShortcutListChanged...
09-01 11:01:31.056  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-01 11:01:31.059  1035  1967 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-01 11:01:31.059  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-01 11:01:31.059  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-01 11:01:31.059  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-01 11:01:31.059  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-01 11:01:31.059  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-01 11:01:31.059  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:01:31.059  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-01 11:01:31.059  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-01 11:01:31.059  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-01 11:01:31.059  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:01:31.059  7886  7886 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-01 11:01:31.060  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:01:31.061  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-01 11:01:31.065  1035  1035 I art     : Explicit concurrent mark sweep GC freed 80003(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 5.063ms total 212.479ms
09-01 11:01:31.075  1871  1871 D SplitUIManager: split_name #11 / not available #0
09-01 11:01:31.075  1871  1871 D SplitUIService: removed split : 
,09-01 11:01:31.080  7986  7986 D UEI.SmartControl: QS Service version name: 2.1.91
09-01 11:01:31.080  7986  7986 D UEI.SmartControl: QS Service version code: 201091
09-01 11:01:31.080  7986  7986 D UEI.SmartControl: Service requested: Control
09-01 11:01:31.097  1035  1440 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:01:31.097  1035  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:01:31.097  1035  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:01:31.097  1035  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:01:31.098  1035  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:01:31.098  1035  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-01 11:01:31.098  1035  1501 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-01 11:01:31.098  1035  1501 D ConnectivityService: identical MTU - not setting
09-01 11:01:31.099  1035  1501 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-01 11:01:31.099  1035  1501 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-01 11:01:31.099  1035  1501 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:01:31.099  1035  1501 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:31.099  1035  1501 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:01:31.099  1604  2114 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-01 11:01:31.102  1871  1871 D SplitUIManager: split_name #11 / not available #0
09-01 11:01:31.102  1871  1871 I SplitUIService: split app #11
09-01 11:01:31.103  7986  8471 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-01 11:01:31.104  1035  1035 D administrator: Handling package changes for user 0
09-01 11:01:31.111  7986  8470 I UEI.SmartControl: Notify AllClients services are ready: 0
09-01 11:01:31.111  7986  8470 D UEI.SmartControl: -----service ready thread exits
09-01 11:01:31.116  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,09-01 11:01:31.128  7986  7986 D UEI.SmartControl: Internal service binding...
,09-01 11:01:31.128  8388  8388 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-01 11:01:31.129  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:31.129  7986  8006 I UEI.SmartControl: ------ IControl API: 11
09-01 11:01:31.129  7986  8006 D UEI.SmartControl: File observer start...
09-01 11:01:31.129  7986  8006 E UEI.SmartControl: IR Port is disabled: false
09-01 11:01:31.130  7986  8006 D UEI.SmartControl: Starting file observer...
09-01 11:01:31.130  7986  8006 I UEI.SmartControl: Registering callback...
09-01 11:01:31.131  7986  8007 I UEI.SmartControl: ------ IControl API: 19
09-01 11:01:31.132  7986  8007 I UEI.SmartControl: Registering Services Ready callback...
09-01 11:01:31.132  7986  8007 I UEI.SmartControl: Notify client services are ready...
09-01 11:01:31.132  8388  8407 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-01 11:01:31.133  8388  8456 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-01 11:01:31.134  8388  8456 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-01 11:01:31.134  1604  1662 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-01 11:01:31.134  1604  1662 D KeyguardModel: createShortcutInfo...
09-01 11:01:31.134  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:31.135  8388  8388 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-01 11:01:31.135  8388  8388 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-01 11:01:31.137  1604  1662 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-01 11:01:31.137  1604  1662 D KeyguardModel: createShortcutInfo...
09-01 11:01:31.138  1604  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:01:31.138  1604  1662 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-01 11:01:31.139  1604  1662 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-01 11:01:31.139  1604  1662 D KeyguardModel: createShortcutInfo...
09-01 11:01:31.139  1604  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:01:31.139  1604  1662 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-01 11:01:31.140  1604  1662 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-01 11:01:31.140  1604  1662 D KeyguardModel: createShortcutInfo...
09-01 11:01:31.141  7986  8006 I UEI.SmartControl: ------ IControl API: 8
09-01 11:01:31.142  1604  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:01:31.142  1604  1662 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-01 11:01:31.142  8388  8388 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-01 11:01:31.142  8388  8388 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
,09-01 11:01:31.142  8388  8388 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-01 11:01:31.143  8388  8388 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-01 11:01:31.143  8388  8388 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-01 11:01:31.143  8388  8388 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-01 11:01:31.144  8388  8388 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-01 11:01:31.145  1604  1662 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-01 11:01:31.145  1604  1662 D KeyguardModel: createShortcutInfo...
09-01 11:01:31.146  8388  8388 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-01 11:01:31.151  1604  1604 D KeyguardModel: handleShortcutListChanged...
09-01 11:01:31.151  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-01 11:01:31.152  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:01:31.170  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:01:31.186  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:01:31.189  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-01 11:01:31.192  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:01:31.193  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-01 11:01:31.194  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-01 11:01:31.194  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-01 11:01:31.194  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-01 11:01:31.195  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-01 11:01:31.195  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-01 11:01:31.195  8332  8332 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-01 11:01:31.196  1035  1579 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-01 11:01:31.196  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-01 11:01:31.199  1819  1819 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-01 11:01:31.208  2081  2081 I ConfigService: onCreate
09-01 11:01:31.208  2081  2081 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-01 11:01:31.210  1819  1819 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-01 11:01:31.213  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-01 11:01:31.213  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:01:31.213  2034  2138 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-01 11:01:31.214  2034  2138 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-01 11:01:31.214  1035  1106 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2df02893 u0 com.lge.launcher2/.Launcher t5} time:235628
,09-01 11:01:31.216  2081  2081 I ConfigService: onBind returning update interface
,09-01 11:01:31.218  2081  2081 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-01 11:01:31.219  2081  2081 I ConfigService: onBind returning config service
09-01 11:01:31.228  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-01 11:01:31.229  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-01 11:01:31.229  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-01 11:01:31.232  2081  2081 I ConfigService: onDestroy
09-01 11:01:31.233  1819  8478 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-01 11:01:31.240  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-01 11:01:31.241  2607  2607 D [Concierge]Service: onStartCommand(). Type : 8
09-01 11:01:31.241  2607  2607 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-01 11:01:31.242  2607  2607 D [Concierge]Service: Update widget ID : 11
09-01 11:01:31.244  2034  2034 D [Concierge]WidgetView: change position of spinner
09-01 11:01:31.246  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1472720491246
,09-01 11:01:31.247  2607  2607 D [Concierge]Service: onStartCommand(). Type : 0
09-01 11:01:31.261  1819  8485 I PeopleContactsSync: CP2 sync disabled
,09-01 11:01:31.262  5935  8484 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-01 11:01:31.264  1819  5230 I Icing   : doRemovePackageData com.test.thalitest
,09-01 11:01:31.314  2081  2631 I art     : Explicit concurrent mark sweep GC freed 6689(391KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 813us total 26.961ms
,09-01 11:01:31.317  1819  8483 W GmsApplication: Using Auth Proxy for data requests.
09-01 11:01:31.322  1819  8483 W GmsApplication: Using Auth Proxy for data requests.
09-01 11:01:31.329  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 11:01:31.334  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-01 11:01:31.334   308  8488 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-01 11:01:31.334   308  8488 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
09-01 11:01:31.358  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 691576943
09-01 11:01:31.359  7258  7258 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-01 11:01:31.359  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-01 11:01:31.359  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-01 11:01:31.363  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3378c7ef
09-01 11:01:31.363  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-01 11:01:31.365  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-01 11:01:31.365  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:01:31.370  2301  8490 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-01 11:01:31.371  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-01 11:01:31.372  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-01 11:01:31.372  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-01 11:01:31.372  1035  1124 I art     : Explicit concurrent mark sweep GC freed 16963(1084KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.121ms total 257.992ms
,09-01 11:01:31.377   308  8488 D libc-netbsd: res_queryN name = android.clients.google.com succeed
09-01 11:01:31.395  1035  1684 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8491 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-01 11:01:31.396  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472720283884, New one : 1472720491246
09-01 11:01:31.396  2034  2034 D [Concierge]WidgetView: Unregister all receivers
09-01 11:01:31.396  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-01 11:01:31.398  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-01 11:01:31.399  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:01:31.401  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-01 11:01:31.402  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-01 11:01:31.403  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-01 11:01:31.405  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-01 11:01:31.406  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,09-01 11:01:31.410  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:01:31.410  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-01 11:01:31.445  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-01 11:01:31.445  8491  8491 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:01:31.449  8491  8491 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:01:31.450  8491  8491 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-01 11:01:31.450  8491  8491 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-01 11:01:31.452  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-01 11:01:31.453  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-01 11:01:31.454  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:01:31.477  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@287b804 time:235891
,09-01 11:01:31.486  8437  8437 D AndroidRuntime: Shutting down VM
09-01 11:01:31.513  8491  8491 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-01 11:01:31.521  8491  8491 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-01 11:01:31.539  8491  8491 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-01 11:01:31.551  1819  8440 I CheckinTask: Sending checkin request (7866 bytes)
,09-01 11:01:31.560  8491  8491 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:01:31.560  8491  8491 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:01:31.608  8491  8491 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-01 11:01:31.610  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
09-01 11:01:31.616  1035  1958 I ActivityManager: Killing 7924:com.google.android.talk/u0a72 (adj 15): empty #17
09-01 11:01:31.647  2034  2874 I GBoardtInterface: onReloaded()
,09-01 11:01:31.648  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-01 11:01:31.656  1996  1996 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-01 11:01:31.656  1996  1996 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-01 11:01:31.657  1035  2051 W libprocessgroup: failed to open /acct/uid_10072/pid_7924/cgroup.procs: No such file or directory
09-01 11:01:31.658  1996  1996 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,09-01 11:01:31.658  3811  3826 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-01 11:01:31.661  3811  5034 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-01 11:01:31.666  1905  1905 D ActionManagerService: notifyUserLog: 1000001
09-01 11:01:31.667  3811  5039 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-01 11:01:31.667  3811  5039 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-01 11:01:31.669  1905  1905 D ActionManagerService: notifyUserLog: 1000001
,09-01 11:01:31.669  3811  5039 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-01 11:01:31.669  3811  5039 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-01 11:01:31.669  3811  5039 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-01 11:01:31.669  3811  5039 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-01 11:01:31.670  3811  3826 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-01 11:01:31.672  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-01 11:01:31.672  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-01 11:01:31.673  8332  8332 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-01 11:01:31.674  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-01 11:01:31.674  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-01 11:01:31.676  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-01 11:01:31.676  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-01 11:01:31.676  7711  7711 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
09-01 11:01:31.682  7068  7068 D PackageIntentReceiver: Not supported Hotkey customization function 
,09-01 11:01:31.689  7068  7068 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
09-01 11:01:31.689  7068  7068 D HideNavigationAppsReceiver: replacing : false
09-01 11:01:31.691  7068  7068 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
09-01 11:01:31.692  7068  7068 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
09-01 11:01:31.692  7068  7068 D ButtonCombinationReceiver: replacing : false
,09-01 11:01:31.706  5122  8514 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-01 11:01:31.729  1035  1726 V SIM_STK : Menu title from STK is T-Mobile
,09-01 11:01:31.740  1035  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8515 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-01 11:01:31.778  1035  1967 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8533 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 11:01:31.812  5122  8514 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-01 11:01:31.814  2081  2631 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
09-01 11:01:31.815  2081  2631 W ServiceConnection: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
09-01 11:01:31.815  2081  2631 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-01 11:01:31.815  2081  2631 W ServiceConnection: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 11:01:31.815  2081  2631 W ServiceConnection: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
09-01 11:01:31.815  2081  2631 W ServiceConnection: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
09-01 11:01:31.815  2081  2631 W ServiceConnection: 	at com.google.android.gms.common.internal.bf.b(SourceFile:56)
09-01 11:01:31.815  2081  2631 W ServiceConnection: 	at com.google.android.gms.common.internal.bf.a(SourceFile:48)
09-01 11:01:31.815  2081  2631 W ServiceConnection: 	at com.google.android.gms.common.internal.be.a(SourceFile:45)
09-01 11:01:31.815  2081  2631 W ServiceConnection: 	at com.google.android.gms.icing.service.n.b(SourceFile:118)
09-01 11:01:31.815  2081  2631 W ServiceConnection: 	at com.google.android.gms.common.internal.bd.b(SourceFile:218)
09-01 11:01:31.815  2081  2631 W ServiceConnection: 	at com.google.android.gms.common.internal.ao.onTransact(SourceFile:460)
09-01 11:01:31.815  2081  2631 W ServiceConnection: 	at android.os.Binder.execTransact(Binder.java:446)
09-01 11:01:31.815  2081  2631 W ServiceConnection: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 11:01:31.815  2081  2631 W ServiceConnection: 	at libcore.io.Posix.open(Native Method)
09-01 11:01:31.815  2081  2631 W ServiceConnection: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 11:01:31.815  2081  2631 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-01 11:01:31.815  2081  2631 W ServiceConnection: 	... 10 more
,09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: Exception thrown from notifyTableChanged
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at beg.a(PG:301)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at beg.c(PG:222)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at cun.b(PG:660)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at cun.a(PG:651)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at cun.g(PG:597)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at cuw.Tg(PG:368)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at cuy.ub(PG:301)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at bea.a(PG:382)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at beg.i(PG:325)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at beh.call(PG:215)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	at beg.a(PG:299)
09-01 11:01:31.824  5122  8514 E IcingCorporaProvider: 	... 15 more
09-01 11:01:31.824  5122  8514 W IcingCorporaProvider: notifyTableChanged failed.
09-01 11:01:31.824  5122  8514 W IcingCorporaProvider: Table change notification failed for TableStorageSpec[applications]
09-01 11:01:31.824  5122  8514 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 118 ms] updated apps [took 118 ms] 
09-01 11:01:31.824  1819  5230 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
09-01 11:01:31.824  1819  5230 E Icing   : Could not init tag ds.tag.corpusid-1
09-01 11:01:31.824  1819  5230 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-13 for write failed: Read-only file system
09-01 11:01:31.824  1819  5230 E Icing   : Could not, init tag ds.tag.corpusid-13
09-01 11:01:31.824  1819  5230 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-7 for write failed: Read-only file system
09-01 11:01:31.824  1819  5230 E Icing   : Could not init tag ds.tag.corpusid-7
09-01 11:01:31.824  1819  5230 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-8 for write failed: Read-only file system
09-01 11:01:31.824  1819  5230 E Icing   : Could not init tag ds.tag.corpusid-8
09-01 11:01:31.824  1819  5230 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-9 for write failed: Read-only file system
09-01 11:01:31.824  1819  5230 E Icing   : Could not init tag ds.tag.corpusid-9
09-01 11:01:31.824  1819  5230 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
09-01 11:01:31.824  1819  5230 E Icing   : Could not init tag ds.tag.deleted
09-01 11:01:31.825  1819  5230 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
09-01 11:01:31.827  1819  5230 E Icing   : Writing status failed
,09-01 11:01:31.834  1035  2005 I ActivityManager: Killing 7546:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-01 11:01:31.886  1035  1938 W libprocessgroup: failed to open /acct/uid_10097/pid_7546/cgroup.procs: No such file or directory

```
