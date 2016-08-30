#### Test 82914073a71b108_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
,08-30 14:41:56.603  1586  1586 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-30 14:41:56.603  1586  1586 I [SystemUI]LGPowerUI: On Skip Timer : true
--------- beginning of system
08-30 14:41:56.622  1927  2099 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-30 14:41:56.622  1927  2099 D LEDHandler: Battery Level Remaining: 100%
08-30 14:41:56.622  1927  2099 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
08-30 14:41:56.624  1586  1586 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
08-30 14:41:56.624  1586  1586 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-30 14:41:56.626  1586  1586 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-30 14:41:56.627  1035  1430 D WifiController: battery changed pluggedType: 2
08-30 14:41:56.629  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:41:56.630  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:41:56.632  3899  4023 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 14:41:56.636  6590  6590 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 14:41:56.864  6697  6697 D AndroidRuntime: 
08-30 14:41:56.864  6697  6697 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 14:41:56.867  6697  6697 D AndroidRuntime: CheckJNI is OFF
08-30 14:41:56.998  6697  6697 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 14:41:57.004  1035  1926 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 14:41:57.012  1927  1943 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 14:41:57.015  1035  1926 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 14:41:57.016  1035  1926 D ActivityManager: setTaskToReturnTo : TaskRecord{1919262b #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 14:41:57.016  1035  1926 D ActivityManager: setTaskToReturnTo : TaskRecord{1919262b #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 14:41:57.017  1035  1926 D WindowStateEx: AppWindowTokenEx init.. 
08-30 14:41:57.018   346   419 E GBMv2   : DFP En is all cleared set to be enabled
08-30 14:41:57.047  1035  1926 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6717 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 14:41:57.048  6697  6697 D AndroidRuntime: Shutting down VM
08-30 14:41:57.086  1927  4008 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 14:41:57.086  1927  4008 D SplitWindowPolicy: topRunningActivity=ActivityInfo{22ecf22a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 14:41:57.087  1927  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 14:41:57.087  1927  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{728181b co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 14:41:57.122  6717  6717 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 14:41:57.235  6717  6717 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-30 14:41:57.245  6717  6717 I LibraryLoader: Loading: webviewchromium
08-30 14:41:57.248  6717  6717 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9003-9007)
,08-30 14:41:57.248  6717  6717 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 14:41:57.268  6717  6717 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {26998b68}
08-30 14:41:57.269  6717  6717 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 14:41:57.269  6717  6717 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 14:41:57.278  6717  6717 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 14:41:57.279  6717  6717 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 14:41:57.295  6717  6717 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-30 14:41:57.295  6717  6717 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 14:41:57.296  6717  6717 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-30 14:41:57.298   323  2144 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
08-30 14:41:57.302  1035  1117 D BluetoothManagerService: Message: 20
08-30 14:41:57.303  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3581d95d:true
08-30 14:41:57.319  6717  6717 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 14:41:57.319  6717  6717 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 14:41:57.319  6717  6717 I Adreno-EGL: Build Date: 12/12/14 금
08-30 14:41:57.319  6717  6717 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 14:41:57.319  6717  6717 I Adreno-EGL: Remote Branch: 
08-30 14:41:57.319  6717  6717 I Adreno-EGL: Local Patches: 
08-30 14:41:57.319  6717  6717 I Adreno-EGL: Reconstruct Branch: 
,08-30 14:41:57.390  6717  6747 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-30 14:41:57.397  6717  6717 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-30 14:41:57.413  6717  6717 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 14:41:57.419  6717  6717 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 14:41:57.422  6717  6717 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 14:41:57.424  6717  6717 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 14:41:57.424  6717  6717 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-30 14:41:57.437  6717  6717 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 14:41:57.444  6717  6717 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 14:41:57.444  6717  6717 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 14:41:57.475  6717  6759 D OpenGLRenderer: Render dirty regions requested: true
08-30 14:41:57.475  6717  6759 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 14:41:57.485  6717  6759 D OpenGLRenderer: Enabling debug mode 0
,08-30 14:41:57.490  6717  6717 D Atlas   : Validating map...
08-30 14:41:57.496  1035  2033 D SplitWindow: check instance of lgWin Window{e23c9ef u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 14:41:57.539  6717  6757 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:41:57.539  6717  6757 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:41:57.670  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +585ms (total +651ms)
08-30 14:41:57.670  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9988a88 u0 com.test.thalitest/.MainActivity t6} time:189430
08-30 14:41:57.671  6717  6717 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25e5e957 time:189430
,08-30 14:41:57.786  6717  6717 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 14:41:57.827  6717  6717 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 14:41:57.827  6717  6717 I chromium: 
,08-30 14:41:57.854  6717  6757 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 14:41:57.854  6717  6757 I chromium: 
,08-30 14:41:57.990  6717  6769 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435032064
,08-30 14:41:58.007  6717  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 14:41:58.007  6717  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 14:41:58.007  6717  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 14:41:58.007  6717  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 14:41:58.007  6717  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 14:41:58.007  6717  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ac3be6b added. We now have 1 listener(s)
,08-30 14:41:58.014  1035  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
08-30 14:41:58.017  6717  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-30 14:41:58.020  6717  6769 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:41:58.022  6717  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:41:58.022  6717  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 14:41:58.030  6717  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 14:41:58.030  6717  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 14:41:58.030  6717  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 14:41:58.030  6717  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 14:41:58.030  6717  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 14:41:58.030  6717  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 14:41:58.030  6717  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 14:41:58.030  6717  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 14:41:58.030  6717  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 14:41:58.030  6717  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 14:41:58.030  6717  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 14:41:58.030  6717  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 14:41:58.030  6717  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 14:41:58.030  6717  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 14:41:58.031  6717  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d7f5d86 added. We now have 1 listener(s)
08-30 14:41:58.031  6717  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:41:58.039  1035  1430 D WifiService: New client listening to asynchronous messages
08-30 14:41:58.042  6717  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 14:41:58.042  6717  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 14:41:58.045  6717  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-30 14:41:58.045  6717  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 14:41:58.045  6717  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 14:41:58.054  6717  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:41:58.055  1035  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 14:41:58.057  6717  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-30 14:41:58.067  6717  6769 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 14:41:58.067  6717  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:41:58.067  6717  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:41:58.067  6717  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:41:58.067  6717  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:41:58.067  6717  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:41:58.067  6717  6769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:41:58.067  6717  6769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:41:58.067  6717  6769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:41:58.067  6717  6769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 14:41:58.067  6717  6769 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 14:41:58.071  6717  6769 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 14:41:58.072  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:41:58.074  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:41:58.107  6717  6717 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 14:41:58.144   346   421 E GBMv2   : DFP En is all cleared set to be enabled
08-30 14:41:58.145   346   421 E GBMv2   : Set value is all cleared set the max
08-30 14:41:58.145   346   421 I GBMv2   : DFP Enabled. Ignore VFP set
,08-30 14:41:59.064  6717  6772 W jxcore-log: Initializing JXcore engine
08-30 14:41:59.064  6717  6772 W jxcore-log: JXcore engine is ready
,08-30 14:41:59.107  6772  6772 W Thread-771: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8400]" dev="sockfs" ino=8400 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-30 14:41:59.107  6772  6772 W Thread-771: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 14:41:59.107  6772  6772 W Thread-771: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10563]" dev="sockfs" ino=10563 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 14:41:59.107  6772  6772 W Thread-771: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-30 14:41:59.107  6772  6772 W Thread-771: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33251]" dev="sockfs" ino=33251 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-30 14:41:59.131  6717  6772 W jxcore-log: Starting JXcore engine
08-30 14:41:59.229  6717  6772 W jxcore-log: Platform android
08-30 14:41:59.229  6717  6772 W jxcore-log: 
,08-30 14:41:59.232  6717  6772 W jxcore-log: Process ARCH arm
08-30 14:41:59.232  6717  6772 W jxcore-log: 
08-30 14:41:59.555  6717  6772 I jxcore-log: JXcore Cordova bridge is ready!
08-30 14:41:59.555  6717  6772 I jxcore-log: 
,08-30 14:41:59.555  6717  6772 W jxcore-log: JXcore engine is started
,08-30 14:41:59.568  6717  6769 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 14:41:59.572  6717  6717 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 14:42:00.050  1586  1586 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 14:42:00.050  1586  1586 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 14:42:00.050  1586  1586 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 14:42:00.050  1586  1586 I [SystemUI]Clock: called onTimeUpdated()
,08-30 14:42:00.053  1586  1586 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 14:42:00.053  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-30 14:42:00.055  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-30 14:42:00.057  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 14:42:09.058  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 14:42:09.058  6717  6772 I jxcore-log: 
,08-30 14:42:09.061  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 14:42:09.061  6717  6772 I jxcore-log: 
08-30 14:42:09.067  6717  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:42:09.067  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:09.067  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:09.067  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:09.067  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:09.067  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:09.067  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:42:09.067  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:42:09.070  6717  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:09.072  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 14:42:09.072  6717  6772 I jxcore-log: 
08-30 14:42:09.074  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 14:42:09.074  6717  6772 I jxcore-log: 
,08-30 14:42:09.580  6717  6772 D executeNativeTests: Running unit tests
,08-30 14:42:09.662  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 14:42:09.662  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b added. We now have 2 listener(s)
08-30 14:42:09.663  1035  1769 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:09.665  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:42:09.665  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:42:09.665  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:42:09.665  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:09.665  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 added. We now have 2 listener(s)
08-30 14:42:09.665  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:42:09.667  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 14:42:09.672  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:42:09.675  6717  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:42:09.675  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:09.675  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:09.675  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:09.675  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:09.675  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:09.675  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:42:09.675  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:42:09.676  6717  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:09.676  6717  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:42:09.678  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:42:09.681  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:09.682  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 14:42:09.682  6717  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 14:42:09.682  6717  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 14:42:09.684  6717  6772 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 14:42:09.685  6717  6772 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 14:42:09.685  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 14:42:09.685  6717  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 14:42:09.685  6717  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 14:42:09.685  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.686  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.686  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.687  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.687  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.687  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:42:09.687  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:42:09.687  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b removed from the list
08-30 14:42:09.687  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.687  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 removed from the list
08-30 14:42:09.687  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.687  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.688  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.688  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.689  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.689  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.689  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.689  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.691  6717  6772 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 14:42:09.691  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.691  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.691  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.692  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.692  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.692  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.692  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.6,92  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.692  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.692  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.692  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.692  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.692  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.692  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:42:09.693  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.693  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.693  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.693  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 14:42:09.698  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 14:42:09.699  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 14:42:09.699  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 14:42:09.699  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 14:42:09.699  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 14:42:09.699  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 14:42:09.699  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 14:42:09.699  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 14:42:09.699  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 14:42:09.699  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 14:42:09.699  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 14:42:09.699  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 14:42:09.699  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 14:42:09.699  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 14:42:09.699  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.700  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.700  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.700  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.700  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.700  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.700  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.700  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.700  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.700  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 14:42:09.700  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.700  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.700  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.700  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.702  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.702  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.702  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.702  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.703  6717  6772 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 14:42:09.778  1035  1560 I art     : Explicit concurrent mark sweep GC freed 36757(1781KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.966ms total 74.728ms
08-30 14:42:09.779  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:42:09.781  6717  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:42:09.781  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:09.781  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:09.781  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:09.781  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:09.781  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:09.781  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:42:09.781  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:42:09.782  6717  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:09.782  6717  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:42:09.782  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:42:09.782  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:42:09.783  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:42:09.783  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:42:09.783  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:42:09.788  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:09.789  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:09.793  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 14:42:09.793  1035  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 14:42:09.797  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 14:42:09.801  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 14:42:09.802  6717  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,08-30 14:42:09.803  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 14:42:09.803  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:42:09.804  6717  6772 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 14:42:09.804  6717  6772 I io.jxcore.node.ConnectionHelper: start: OK
08-30 14:42:09.807  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.807  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.807  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.807  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.807  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.808  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:42:09.808  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.808  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.808  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.808  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.808  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.808  6717  6772 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 14:42:09.809  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:42:09.812  6717  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:42:09.812  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:09.812  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:09.812  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:09.812  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:09.812  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:09.812  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:42:09.812  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:42:09.812  6717  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:09.813  6717  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:42:09.814  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:09.815  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:09.815  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:42:09.815  671,7  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:42:09.815  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:42:09.815  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:42:09.815  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:42:09.817  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 14:42:09.818  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:42:09.818  6717  6772 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 14:42:09.819  6717  6772 I io.jxcore.node.ConnectionHelper: start: OK
08-30 14:42:09.820  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.820  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.820  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.820  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.820  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:42:09.820  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:42:09.820  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.820  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.820  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.820  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.820  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.820  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.820  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.821  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.821  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 14:42:09.822  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:09.822  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:09.822  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.822  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.823  6717  6772 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 14:42:09.826  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:42:09.829  6717  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:42:09.829  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:09.829  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:09.829  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:09.829  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:09.829  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:09.829  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:42:09.829  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:42:09.830  6717  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:09.830  6717  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:42:09.831  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:42:09.831  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:42:09.831  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:42:09.831  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:42:09.831  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:42:09.832  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:09.833  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:42:09.836  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 14:42:09.836  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:42:09.837  6717  6772 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 14:42:09.837  6717  6772 I io.jxcore.node.ConnectionHelper: start: OK
08-30 14:42:09.837  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.837  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.837  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.838  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.838  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.838  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.838  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.838  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:42:09.838  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:42:09.838  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.838  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.838  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.838  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.838  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.838  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.838  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.839  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.839  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.839  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:09.839  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:09.839  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.839  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.840  6717  6772 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 14:42:09.840  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.840  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.840  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.841  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.841  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.841  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.841  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.841  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.841  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.841  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.841  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.841  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.841  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.841  6717  6772 D org.thaliproject.p2p,.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.841  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.841  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.841  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:09.841  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:09.841  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.841  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.842  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 14:42:09.842  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.842  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.842  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.842  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.842  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.842  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.843  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.843  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.843  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.843  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.843  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.843  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.843  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.843  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.843  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.843  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.843  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:09.843  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:09.843  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.843  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.844  6717  6772 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 14:42:09.844  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.844  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.844  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.844  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.844  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.844  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.844  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.844  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.844  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.844  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.844  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.844  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.844  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.844  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.845  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.845  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.846  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:09.846  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:09.846  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.846  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.846  6717  6772 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 14:42:09.846  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.846  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.847  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.847  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.847  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.847  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.847  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.847  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.847  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.847  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.847  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.847  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.847  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.847  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.848  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.848  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.848  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:09.848  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:09.848  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.848  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.849  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 14:42:09.850  6717  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 14:42:09.850  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 14:42:09.850  6717  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 14:42:09.850  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 14:42:09.850  6717  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 14:42:09.851  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.851  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.851  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.851  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.851  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.851  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.851  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.851  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.851  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.851  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.851  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.851  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.851  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.851  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.852  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.852  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.853  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:09.853  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:09.853  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.853  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.854  6717  6772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:42:09.854  6717  6772 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 14:42:09.854  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 14:42:09.857  6717  6772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:42:09.858  6717  6772 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 14:42:09.858  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 14:42:09.858  6717  6772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 14:42:09.858  6717  6772 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 14:42:09.858  6717  6772 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 14:42:09.859  6717  6772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:42:09.859  6717  6772 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 14:42:09.859  6717  6772 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 14:42:09.859  6717  6772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:42:09.859  6717  6772 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 14:42:09.859  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 14:42:09.862  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 14:42:09.865  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 14:42:09.865  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 14:42:09.867  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 14:42:09.867  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 14:42:09.867  6717  6772 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 14:42:09.868  6717  6772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:42:09.868  6717  6772 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-30 14:42:09.869  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.869  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.869  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.874  6717  6788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
08-30 14:42:09.881  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.881  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.881  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.881  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 14:42:09.882  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.882  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.882  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.882  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.882  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.883  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.883  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.883  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.884  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.884  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.884  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:09.884  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:09.884  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.884  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.886  6717  6772 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 14:42:09.887  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.888  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.888  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.889  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.889  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.889  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.889  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.889  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.889  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.889  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.889  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.889  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.889  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.889  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.890  6717  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
08-30 14:42:09.891  6717  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 836)
08-30 14:42:09.891  6717  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 836)
08-30 14:42:09.891  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.891  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.892  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:09.892  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:09.892  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.892  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.893  6717  6772 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 14:42:09.893  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.893  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.893  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.894  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.894  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.894  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.894  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.894  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.894  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.894  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.894  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.894  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.894  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.894  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.897  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.897  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.898  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:09.898  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:09.898  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.898  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.898  6717  6772 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 14:42:09.898  6717  6772 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 14:42:09.899  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 14:42:09.899  6717  6772 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 14:42:09.899  6717  6772 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 14:42:09.899  6717  6772 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 14:42:09.899  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 14:42:09.899  6717  6772 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 14:42:09.899  6717  6772 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 14:42:09.899  6717  6772 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 14:42:09.899  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 14:42:09.899  6717  6772 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 14:42:09.900  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.900  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.900  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.900  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.900  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.900  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.900  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.900  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.900  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.900  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.900  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.900  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.900  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.900  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.901  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.901  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.901  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:09.902  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:09.902  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.902  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.902  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.902  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.902  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.902  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.902  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.902  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.902  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.902  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.902  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.902  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.902  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.902  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.902  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.902  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.902  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.902  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.903  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.903  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.903  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.903  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.903  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.903  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.903  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.903  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.903  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.903  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.903  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.903  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.903  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.903  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.903  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.904  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:09.904  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:09.904  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.904  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.905  6717  6772 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 14:42:09.905  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:42:09.905  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 14:42:09.906  6717  6772 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 14:42:09.906  6717  6772 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 14:42:09.906  6717  6717 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 14:42:09.906  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 14:42:09.906  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 14:42:09.907  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.907  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 14:42:09.907  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 14:42:09.907  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 14:42:09.907  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.907  6717  6772 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 14:42:09.907  1035  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:09.907  6717  6717 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 14:42:09.907  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.907  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.907  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 14:42:09.907  6717  6772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 14:42:09.907  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 14:42:09.908  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 14:42:09.909  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:09.909  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:09.909  6717  6772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 14:42:09.909  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.909  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.910  6717  6772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:42:09.911  6717  6717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:42:09.911  6717  6717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:42:09.911  6717  6717 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:42:09.911  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.911  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.911  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.911  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.911  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.911  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.911  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.911  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.911  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.911  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.911  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.911  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.911  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.911  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.911  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:42:09.912  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.912  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.912  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.912  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.913  6717  6772 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 14:42:09.913  6717  6772 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 14:42:09.913  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 14:42:09.913  6717  6795 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:42:09.915  6717  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 14:42:09.915  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.915  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.915  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.915  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.915  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.915  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.915  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.915  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.915  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.915  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.915  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.915  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.915  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.915  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.916  3899  3918 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-30 14:42:09.917  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.917  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.917  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.917  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.918  6717  6795 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 14:42:09.918  6717  6795 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 14:42:09.918  6717  6795 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 14:42:09.919  6717  6717 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 14:42:09.923  1035  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:09.924  1035  1057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:09.925  1035  1769 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:09.926  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.926  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.926  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.926  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.926  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.926  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.927  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.927  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.927  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.927  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.927  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.927  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.927  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.927  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.928  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.929  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.929  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.929  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.931  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:09.931  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:09.931  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:09.931  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:09.931  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.931  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.931  6717  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf1a47b not in the list
08-30 14:42:09.931  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.931  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.931  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:09.931  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.931  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.931  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:09.931  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:09.932  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:09.932  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:09.932  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:09.932  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2522b298 not in the list
08-30 14:42:09.934  6717  6772 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 14:42:09.934  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 14:42:09.934  6717  6772 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 14:42:09.934  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 14:42:09.934  6717  6772 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 14:42:09.934  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 14:42:09.936  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 14:42:09.936  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 14:42:09.937  6717  6772 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 14:42:09.937  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 14:42:09.938  6717  6772 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 14:42:09.938  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 14:42:09.938  6717  6772 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 14:42:09.938  6717  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 14:42:09.938  6717  6772 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 14:42:09.938  6717  6772 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 14:42:09.939  6717  6772 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 14:42:09.939  6717  6772 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 14:42:09.939  6717  6772 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 14:42:09.940  6717  6772 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 14:42:09.941  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:09.941  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b04a729 added. We now have 2 listener(s)
08-30 14:42:09.941  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:09.942  6717  6772 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 14:42:09.943  1035  1889 D WifiServiceImplEx: setWifiEnabled: true pid=6717, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 14:42:09.943  1035  1889 D WifiService: setWifiEnabled: true pid=6717, uid=10118
08-30 14:42:09.943  1035  1889 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:42:09.944  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:09.944  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e9fdaae added. We now have 3 listener(s)
,08-30 14:42:09.944  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:09.948  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:09.948  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f45504f added. We now have 4 listener(s)
08-30 14:42:09.948  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:09.950  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:09.950  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b1573dc added. We now have 5 listener(s)
08-30 14:42:09.950  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:09.952  1035  1889 D WifiServiceImplEx: setWifiEnabled: false pid=6717, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 14:42:09.952  1035  1889 D WifiService: setWifiEnabled: false pid=6717, uid=10118
08-30 14:42:09.952  1035  1889 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:42:09.963  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:42:09.964  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 14:42:09.964  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 14:42:09.965  1035  1377 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 14:42:09.965  1035  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:09.966  1035  1058 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@21feb42e mBinding = false
08-30 14:42:09.966  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0,
08-30 14:42:09.966  1035  1377 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 14:42:09.967  1035  1377 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 14:42:09.967  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 14:42:09.967  1035  1377 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 14:42:09.967  1035  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 14:42:09.967  1035  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 14:42:09.968  1035  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 14:42:09.968  1035  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-30 14:42:09.975  1035  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 14:42:09.975  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 14:42:09.975  2622  2622 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 14:42:09.975  1035  1375 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:09.975  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:09.976  1035  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 14:42:09.977  1035  1377 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:42:09.977  1035  1377 D WifiNative-wlan0: SET ps 1: returned true
08-30 14:42:09.978  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:42:09.978  1035  2802 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:09.978  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 14:42:09.978  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 14:42:09.978   319   917 D CommandListener: Clearing all IP addresses on wlan0
08-30 14:42:09.980  1035  1117 D BluetoothManagerService: Message: 2
08-30 14:42:09.983  1035  1117 D BluetoothManagerService: Sending off request.
08-30 14:42:09.983  3899  4025 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 14:42:09.984  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:42:09.985  3899  3989 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 14:42:09.985  3899  3989 D BluetoothAdapterProperties: Setting state to 13
08-30 14:42:09.985  3899  3989 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 14:42:09.985  3899  3989 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 14:42:09.986  3899  3989 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 14:42:09.989  3899  3993 D BluetoothAdapterProperties: Scan Mode:20
,08-30 14:42:09.990  3899  3989 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 14:42:09.991  3899  3989 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 14:42:09.994  3899  4358 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:42:09.995  3899  4356 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:42:09.995  3899  4295 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:42:09.995  1035  1117 D BluetoothManagerService: Message: 60
08-30 14:42:09.996  3899  4293 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 14:42:09.996  3899  4293 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:42:09.996  3899  4293 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 14:42:09.996  3899  4293 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 14:42:09.996  3899  4293 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 14:42:09.996  3899  4293 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 14:42:09.996  3899  4293 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 14:42:09.996  3899  4293 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 14:42:09.997  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 14:42:09.997  3899  4099 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 14:42:09.997  3899  4355 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:42:09.999  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,08-30 14:42:09.999  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 14:42:10.001  1035  1434 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 14:42:10.001  1035  1434 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-30 14:42:10.002  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:42:10.002  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:42:10.002  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:42:10.002  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:42:10.002  3899  4099 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:42:10.002  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:42:10.002  3899  4099 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:42:10.002  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:42:10.002  3899  4099 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:42:10.002  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 14:42:10.002  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 14:42:10.002  3899  4099 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 14:42:10.004  1035  1890 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-30 14:42:10.004  1035  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:10.004  1035  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:10.005  1035  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 14:42:10.005  1035  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:10.005  1035  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-30 14:42:10.016  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:10.016  6717  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:42:10.016  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:10.016  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:10.016  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:10.016  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:42:10.016  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:10.016  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:42:10.016  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:42:10.017  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:10.017  6717  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:42:10.017  6717  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:42:10.018  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:10.018  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:10.018  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:10.018  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:10.018  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:10.018  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:42:10.018  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:10.018  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:10.018  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:42:10.023  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:10.025  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:10.025  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:10.025  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:10.025  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:10.025  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:10.025  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:42:10.025  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:10.025  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:10.025  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:42:10.026  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:10.026  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:42:10.027  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:10.030  6717  6788 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-30 14:42:10.030  6717  6788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 836)
08-30 14:42:10.039  1035  1113 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6804 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-30 14:42:10.043  3899  3899 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:10.043  3899  3899 D BluetoothMapService: STATE_TURNING_OFF
08-30 14:42:10.043  3899  3899 V BluetoothMapService: Handler(): got msg=4
08-30 14:42:10.043  3899  3899 D BluetoothMapService: MAP Service closeService in
08-30 14:42:10.043  3899  3899 D BluetoothMapMasInstance: MAP Service shutdown
08-30 14:42:10.043  3899  3899 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 14:42:10.044  3899  3899 V BluetoothMapService: MAP Service closeService out
08-30 14:42:10.044  3899  3899 V BtOppService: Receiver DISABLED_ACTION 
08-30 14:42:10.044  3899  3899 I BtOppRfcommListener: stopping Accept Thread
08-30 14:42:10.044  3899  3899 V BtOppRfcommListener: close mBtServerSocket
08-30 14:42:10.044  3899  3899 V BtOppRfcommListener: waiting for thread to terminate
08-30 14:42:10.044  3899  4355 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 14:42:10.045  1035  1434 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 14:42:10.045  1035  1434 D DSQN    : disableDataServiceNotify
08-30 14:42:10.045  1035  1434 D DSQN    : stop dsqn bin
08-30 14:42:10.045  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 14:42:10.046   319  6818 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 14:42:10.046  3899  3899 V BtOppRfcommListener: done waiting for thread to terminate
08-30 14:42:10.046  1035  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-30 14:42:10.046  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:10.047  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 14:42:10.047  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:10.048  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:10.052  1035  1434 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 14:42:10.052  1035  1434 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:10.052  1035  1434 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:42:10.052  1035  1434 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:42:10.052  1035  1434 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 14:42:10.052  1035  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:10.052  1035  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:10.052  1035  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 14:42:10.053  1035  1434 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 14:42:10.053  1035  1434 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 14:42:10.053  1035  1434 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-30 14:42:10.053  1586  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 14:42:10.078  1035  1113 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6823 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 14:42:10.080  3899  3899 V BtOppService: onDestroy
08-30 14:42:10.081  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 14:42:10.082  1035  1434 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:10.082  1035  1434 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 14:42:10.083  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:10.083  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:10.083  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:42:10.083  1035  1374 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 14:42:10.083  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 14:42:10.084  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 14:42:10.084  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 14:42:10.084  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 14:42:10.084  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 14:42:10.087  1035  1434 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:10.087  1035  1434 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:10.087  1035  1434 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:10.088  3899  3899 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 14:42:10.089  1035  1434 D NetworkManagementService: Removing idletimer
08-30 14:42:10.089  1035  1434 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:10.089  1035  1375 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:10.089  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:10.089  1035  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:10.089  1035  1375 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@293a1e46
08-30 14:42:10.089  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:10.089  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:10.089  1035  1375 D LGWifiP2pService: P2pDisablingState
08-30 14:42:10.090  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 14:42:10.090  1035  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:10.090  1035  1375 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:10.090  1035  1375 D LGWifiP2pService: p2p socket connection lost
08-30 14:42:10.090  1035  1375 D LGWifiP2pService: P2pDisabledState
08-30 14:42:10.090  1035  1374 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 14:42:10.090  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 14:42:10.091  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 14:42:10.091  1035  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:10.091  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 14:42:10.091  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 14:42:10.091  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 14:42:10.091  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:10.092  1035  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:10.092  1035  1377 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 14:42:10.092  1035  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:10.093  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:10.093  1035  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:10.093  1035  1377 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:10.093  1035  1434 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 14:42:10.093  1035  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 14:42:10.094  1035  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 14:42:10.094  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 14:42:10.094  1035  1375 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:10.094  1035  1375 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:10.094  2622  2622 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 14:42:10.094  1035  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 14:42:10.094  1035  1377 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:42:10.094  1035  1377 D WifiNative-wlan0: SET ps 1: returned true
08-30 14:42:10.095   319   917 D CommandListener: Clearing all IP addresses on wlan0
08-30 14:42:10.095  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:10.095  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:10.097  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:10.097  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:10.097  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:42:10.098  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 14:42:10.098  1927  1927 D WfdsService: WifiP2pState is changed : false
08-30 14:42:10.098  1927  2286 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 14:42:10.098  1927  2286 D WfdsService: Set the WFDS Monitor: false
08-30 14:42:10.099  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 14:42:10.099  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-30 14:42:10.099  1035  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:10.099  1035  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:10.100  1927  2286 D WfdsMonitor: WFDS Monitor is stopped
08-30 14:42:10.100  1927  2715 D CtrlSupplicant: Received on exit socket, terminate
08-30 14:42:10.100  1927  2715 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 14:42:10.100  1927  2715 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 14:42:10.100  1927  2715 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 14:42:10.101  1927  2286 D WfdsService: STATE : WfdsDisabledState - enter
08-30 14:42:10.101  1927  2286 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 14:42:10.101  1927  2288 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 14:42:10.102  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:10.103  1035  1377 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 14:42:10.106  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 14:42:10.106  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:10.106  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:10.106  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:42:10.106  1035  1377 D WifiNative-p2p0: TERMINATE: returned true
08-30 14:42:10.107  1035  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:42:10.107  1035  1377 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:42:10.107  1035  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 14:42:10.109  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 14:42:10.109  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:42:10.109  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,08-30 14:42:10.115  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 14:42:10.118  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:10.118  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:10.118  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:10.118  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:10.118  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:42:10.118  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:42:10.118  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:10.118  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:10.118  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:42:10.118  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:10.118  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:42:10.119  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:10.119  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:10.119  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:10.119  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:10.119  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:42:10.119  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:42:10.119  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:10.119  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:10.119  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:42:10.120  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:10.120  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:42:10.132  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 14:42:10.132  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:10.133  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:10.140  6823  6823 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 14:42:10.141  6823  6823 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 14:42:10.141  6823  6823 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 14:42:10.141  6823  6823 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 14:42:10.143  6823  6823 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 14:42:10.143  6823  6823 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 14:42:10.144  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 14:42:10.144  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:10.145  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:10.148  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:10.148  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:10.148  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:10.161  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 14:42:10.161  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:10.162  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 14:42:10.163  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:10.172  6804  6804 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 14:42:10.172  6804  6804 W LG Account v2.2: No ProfileInfo entries
08-30 14:42:10.172  6804  6804 I LG Account v2.2: isEnabled: false
08-30 14:42:10.172  6804  6804 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 14:42:10.173  6804  6804 I Feature : [Lifetracker]Country: EU
08-30 14:42:10.173  6804  6804 I Feature : [Lifetracker]Operator: OPEN
08-30 14:42:10.173  6804  6804 I Feature : [Lifetracker]Ranking support: false
08-30 14:42:10.173  6804  6804 I Feature : [Lifetracker]Comfort support: false
08-30 14:42:10.173  6804  6804 I Feature : [Lifetracker]Accessory: true
08-30 14:42:10.173  6804  6804 I Feature : [Lifetracker]Health device: true
08-30 14:42:10.173  6804  6804 I Feature : [Lifetracker]Extra Pedometer: false
08-30 14:42:10.173  6804  6804 I Feature : [Lifetracker]Blood glucose device: false
08-30 14:42:10.173  6804  6804 I Feature : [Lifetracker]Device Number: 3
,08-30 14:42:10.180  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:10.191  2622  2622 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-30 14:42:10.191  2622  2622 I wpa_supplicant: monitor socket send errors count : 1
08-30 14:42:10.191  2622  2622 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-2\x00 that cannot receive messages
08-30 14:42:10.192  1035  2689 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 14:42:10.192  1035  2689 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 14:42:10.198  1035  2802 D DhcpStateMachine: StoppedState
08-30 14:42:10.198  1035  2802 D DhcpStateMachine: StoppedState{ when=-104ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:10.209  1035  1871 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6843 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 14:42:10.211  1035  1871 I ActivityManager: Killing 6178:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-30 14:42:10.229  2622  2622 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 14:42:10.229  2622  2622 W wpa_supplicant: USIM:  scard_deinit function
,08-30 14:42:10.230  1035  2689 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 14:42:10.230  1035  2689 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 14:42:10.230  1035  2689 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 14:42:10.230  1035  1117 D Tethering: InitialState.processMessage what=4
08-30 14:42:10.231  1035  2689 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 14:42:10.231  1035  2689 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:42:10.231  1035  2689 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:42:10.232  1035  1377 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=201980
08-30 14:42:10.232  1035  1377 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=201980
08-30 14:42:10.233  1035  1377 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=201980  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 14:42:10.233  1035  1377 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=201981  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 14:42:10.241  2622  2622 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 14:42:10.241  1035  2689 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 14:42:10.241  1035  2689 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 14:42:10.242  1035  2689 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 14:42:10.242  1035  1377 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-30 14:42:10.251  1035  1057 W libprocessgroup: failed to open /acct/uid_10014/pid_6178/cgroup.procs: No such file or directory
08-30 14:42:10.255  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 14:42:10.310  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-30 14:42:10.315  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:42:10.315  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:42:10.316  6823  6823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 14:42:10.318  1035  1057 I ActivityManager: Killing 6263:com.android.defcontainer/u0a4 (adj 15): empty #17
08-30 14:42:10.408  1035  1769 W libprocessgroup: failed to open /acct/uid_10004/pid_6263/cgroup.procs: No such file or directory
08-30 14:42:10.411  6717  6717 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 14:42:10.417  1035  1377 D WifiOffDelayIfNotUsed: stopMonitoring
,08-30 14:42:10.418  1035  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:42:10.418  1035  1377 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:42:10.418  1035  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 14:42:10.426  3899  3899 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 14:42:10.427  3899  3899 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:10.427  3899  3899 V BluetoothPbapReceiver: ***********state = 13
,08-30 14:42:10.431  1927  1927 D WfdsService: Supplicant Connection state is changed : false
08-30 14:42:10.432  1927  2286 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 14:42:10.432  1927  2286 D WfdsService: Set the WFDS Monitor: false
08-30 14:42:10.432  1927  2286 D WfdsMonitor: WFDS Monitor is stopped
,08-30 14:42:10.432  3899  3899 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 14:42:10.433  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:10.433  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 14:42:10.437  2492  2492 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:10.439  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:10.441  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:10.442  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 14:42:10.442  1035  1421 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 14:42:10.442  1035  1421 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 14:42:10.443  3899  3899 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:10.443  3899  3899 V BluetoothPbapService: state: 13
08-30 14:42:10.443  3899  3899 V BluetoothPbapService: Pbap Service closeService in
08-30 14:42:10.445  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 14:42:10.445  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:10.447  3899  3899 V BluetoothPbapService: successfully stopped pbap service
,08-30 14:42:10.447  3899  3899 V BluetoothPbapService: Pbap Service closeService out
08-30 14:42:10.447  3899  3899 V BluetoothPbapService: Pbap Service onDestroy
08-30 14:42:10.447  3899  3899 V BluetoothPbapService: Pbap Service closeService in
08-30 14:42:10.447  3899  3899 V BluetoothPbapService: Pbap Service closeService out
08-30 14:42:10.448  3899  3899 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 14:42:10.494  6823  6823 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:42:10.494  6823  6823 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:42:10.510  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:10.518  1035  1117 D BluetoothManagerService: Message: 20
,08-30 14:42:10.519  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2497d1e1:true
08-30 14:42:10.533  1035  1117 D BluetoothManagerService: Message: 30
,08-30 14:42:10.542  1035  1117 D BluetoothManagerService: Message: 30
,08-30 14:42:10.547  6823  6823 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 14:42:10.552  6823  6823 D BluetoothMap: Create BluetoothMap proxy object
,08-30 14:42:10.553  1035  1117 D BluetoothManagerService: Message: 30
08-30 14:42:10.562  1035  1117 D BluetoothManagerService: Message: 30
,08-30 14:42:10.564  6823  6823 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-30 14:42:10.565  6823  6823 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-30 14:42:10.584  6823  6823 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-30 14:42:10.590  6823  6823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-30 14:42:10.611  6823  6823 D DockEventReceiver: finishStartingService: stopping service
,08-30 14:42:10.634  6823  6823 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 14:42:10.637  1035  1377 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
08-30 14:42:10.637  6823  6823 D BluetoothInputDevice: Proxy object connected
08-30 14:42:10.638  1035  1377 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 14:42:10.639  6823  6823 D HidProfile: Bluetooth service connected
08-30 14:42:10.639  1035  1377 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:10.640  6823  6823 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 14:42:10.640  1035  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:10.641  6823  6823 D PanProfile: Bluetooth service connected
08-30 14:42:10.641  6823  6823 D BluetoothMap: Proxy object connected
08-30 14:42:10.642  6823  6823 D MapProfile: Bluetooth service connected
08-30 14:42:10.642  6823  6823 D BluetoothMap: getConnectedDevices()
08-30 14:42:10.643  6823  6823 D BluetoothMap: Bluetooth is Not enabled
08-30 14:42:10.643  6823  6823 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 14:42:10.646  6823  6823 D BluetoothPermissionRequest: onReceive
,08-30 14:42:10.649  6823  6823 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 14:42:10.658  6823  6823 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 14:42:10.659  1035  1890 I ActivityManager: Killing 6452:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-30 14:42:10.694  3899  3899 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 14:42:10.695  3899  3899 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-30 14:42:10.695  1035  1926 W libprocessgroup: failed to open /acct/uid_10008/pid_6452/cgroup.procs: No such file or directory
08-30 14:42:10.697  3899  3899 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 14:42:10.711  3899  3899 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 14:42:10.711  3899  3899 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 14:42:10.713  3899  3899 V BluetoothFtpService: Ftp Service onStartCommand
08-30 14:42:10.714  3899  3899 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:10.714  3899  3899 V BluetoothFtpService: Ftp Service closeService
08-30 14:42:10.715  3899  3899 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 14:42:10.775  1035  1890 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6874 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 14:42:10.783  3899  3899 V BluetoothFtpService: successfully stopped ftp service
08-30 14:42:10.783  3899  3899 V BluetoothFtpService: Ftp Service onDestroy
08-30 14:42:10.783  3899  3899 V BluetoothFtpService: Ftp Service closeService
08-30 14:42:10.793  3899  3899 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 14:42:10.793  3899  3899 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:42:10.793  3899  3899 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 14:42:10.793  3899  3899 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:10.793  3899  3899 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 14:42:10.793  3899  3899 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-30 14:42:10.798  3899  3899 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:10.798  3899  3899 V BluetoothSapService: state: 13
08-30 14:42:10.798  3899  3899 V BluetoothSapService: Stopping SAP server process
08-30 14:42:10.799   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 573us total 24.636ms
08-30 14:42:10.800  3899  3899 V BluetoothSapService: Sap Service closeSapService in
08-30 14:42:10.801  3899  3899 V BluetoothSapService: Close listen Socket : 
08-30 14:42:10.801  3899  3899 V BluetoothSapService: Close rfcomm Socket : 
08-30 14:42:10.801  3899  3899 V BluetoothSapService: Close sapd  Socket : 
08-30 14:42:10.803  3899  3899 V BluetoothSapService: Sap Service closeSapService out
08-30 14:42:10.803  3899  3899 V BluetoothSapService: Sap Service onDestroy
08-30 14:42:10.803  3899  3899 V BluetoothSapService: Sap Service closeSapService in
08-30 14:42:10.803  3899  3899 V BluetoothSapService: Close listen Socket : 
08-30 14:42:10.803  3899  3899 V BluetoothSapService: Close rfcomm Socket : 
08-30 14:42:10.803  3899  3899 V BluetoothSapService: Close sapd  Socket : 
08-30 14:42:10.804  3899  3899 V BluetoothSapService: Sap Service closeSapService out
08-30 14:42:10.823   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 455us total 21.866ms
,08-30 14:42:10.856   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 443us total 32.288ms
,08-30 14:42:10.912  1035  1890 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6896 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 14:42:10.950  6874  6874 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 14:42:10.979  6896  6896 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 14:42:10.979  6874  6874 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-30 14:42:10.997  1035  1889 I ActivityManager: Killing 5969:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-30 14:42:11.003  3899  3993 D bt_hci_bdroid: cleanup
08-30 14:42:11.003  3899  4101 I bt_lpm  : LPM is already off!!!
08-30 14:42:11.003  3899  4258 I bt_userial_mct: exiting userial_read_thread
08-30 14:42:11.003  3899  4099 W bt-btif : ag scb idx 1 not allocated
08-30 14:42:11.003  3899  4258 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 14:42:11.003  3899  4099 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:42:11.003  3899  4099 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:42:11.003  3899  4099 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 14:42:11.004  3899  3993 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 14:42:11.004  3899  4101 I bt_vendor: hw_epilog_process
08-30 14:42:11.004  3899  3993 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 14:42:11.004  3899  3993 D bt_userial_mct: userial_close
08-30 14:42:11.004  3899  3993 E bt_userial_mct: pthread_join() FAILED result:3
08-30 14:42:11.004  3899  3993 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 14:42:11.034  6874  6874 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-30 14:42:11.035  6874  6874 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 14:42:11.035  6874  6874 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 14:42:11.035  6874  6874 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 14:42:11.036  6874  6874 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 14:42:11.037  6874  6874 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 14:42:11.043  6874  6874 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 14:42:11.063  1035  1925 W libprocessgroup: failed to open /acct/uid_10011/pid_5969/cgroup.procs: No such file or directory
,08-30 14:42:11.076  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 14:42:11.080  3899  3993 D bt_hci_bdroid: set_power 0
08-30 14:42:11.080  3899  3993 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 14:42:11.080  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:11.080  3899  3993 I bt_vendor: bluetooth satus is on
08-30 14:42:11.080  3899  3993 I bt_vendor: bt-vendor : resetting BT status
08-30 14:42:11.081  3899  3993 I bt_vendor: Starting hciattach daemon
08-30 14:42:11.081  3899  3993 I bt_vendor: try to set false
08-30 14:42:11.082  3899  3993 I bt_vendor: Starting hciattach daemon
08-30 14:42:11.082  3899  3993 I bt_vendor: try to set false
08-30 14:42:11.084  3899  3993 I bt_vendor: cleanup
08-30 14:42:11.086  3899  4099 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 14:42:11.086  3899  3993 I GKI_LINUX: GKI_exit_task 0 done
08-30 14:42:11.086  3899  3993 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 14:42:11.089  3899  3989 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-30 14:42:11.094  3899  3899 D HeadsetService: Received stop request...Stopping profile...
08-30 14:42:11.097  3899  4023 D HeadsetStateMachine: Exit Disconnected: -1
08-30 14:42:11.097  3899  3899 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 14:42:11.097  3899  3899 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 14:42:11.097  3899  3899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@324a3b81
08-30 14:42:11.099  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-30 14:42:11.099  6874  6874 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 14:42:11.099  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 14:42:11.101  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-30 14:42:11.101  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-30 14:42:11.101  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-30 14:42:11.102  3899  3899 D A2dpService: Received stop request...Stopping profile...
08-30 14:42:11.103  3899  4077 D A2dpStateMachine: Exit Disconnected: -1
08-30 14:42:11.103  3899  3899 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 14:42:11.106  6874  6874 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 14:42:11.108  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:42:11.113  3899  3899 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 14:42:11.113  3899  3899 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 14:42:11.113  3899  3899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@324a3b81
08-30 14:42:11.116  6874  6874 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 14:42:11.118  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 14:42:11.118  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:42:11.118  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:42:11.119  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-30 14:42:11.119  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 14:42:11.121  3899  3899 D HidService: Received stop request...Stopping profile...
08-30 14:42:11.121  3899  3899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@324a3b81
08-30 14:42:11.121  3899  3989 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-30 14:42:11.127  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:42:11.128  3899  3899 D HealthService: Received stop request...Stopping profile...
08-30 14:42:11.128  3899  3899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@324a3b81
08-30 14:42:11.131  3899  3899 D HeadsetStateMachine: Unbinding service...
08-30 14:42:11.132  3899  3899 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 14:42:11.132  3899  3899 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 14:42:11.132  3899  3899 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 14:42:11.132  3899  3899 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 14:42:11.132  3899  3899 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 14:42:11.132  3899  3899 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 14:42:11.132  3899  3899 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-30 14:42:11.134  3899  3899 D PanService: Received stop request...Stopping profile...
08-30 14:42:11.134  3899  3899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@324a3b81
08-30 14:42:11.137  3899  3899 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 14:42:11.137  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:11.137  6823  6823 D BluetoothInputDevice: Proxy object disconnected
08-30 14:42:11.137  6823  6823 D HidProfile: Bluetooth service disconnected
08-30 14:42:11.137  6823  6823 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 14:42:11.137  6823  6823 D PanProfile: Bluetooth service disconnected
08-30 14:42:11.139  3899  3899 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 14:42:11.139  3899  3899 D BtGatt.GattService: stop()
08-30 14:42:11.139  3899  3899 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 14:42:11.140  3899  3899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@324a3b81
08-30 14:42:11.143  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:11.144  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:11.145  3899  3899 I BluetoothA2dpServiceJni: cleanupNative
08-30 14:42:11.145  6874  6874 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 14:42:11.145  3899  4079 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 14:42:11.146  3899  3899 I GKI_LINUX: GKI_exit_task 2 done
08-30 14:42:11.146  3899  3899 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-30 14:42:11.146  3899  3899 D BluetoothMapService: Received stop request...Stopping profile...
08-30 14:42:11.147  3899  3899 D BluetoothMapService: stop()
08-30 14:42:11.149  3899  3899 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 14:42:11.149  3899  3899 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 14:42:11.150  3899  3899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@324a3b81
08-30 14:42:11.151  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:11.152  3899  3899 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 14:42:11.152  3899  3899 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 14:42:11.152  6823  6823 D BluetoothMap: Proxy object disconnected
08-30 14:42:11.152  6823  6823 D MapProfile: Bluetooth service disconnected
08-30 14:42:11.152  3899  3899 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 14:42:11.152  3899  3899 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 14:42:11.152  3899  3899 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 14:42:11.153  3899  3899 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 14:42:11.153  3899  3899 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 14:42:11.154  3899  3899 V BluetoothMapService: Handler(): got msg=4
08-30 14:42:11.154  3899  3899 D BluetoothMapService: MAP Service closeService in
08-30 14:42:11.154  3899  3899 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 14:42:11.154  3899  3899 V BluetoothMapService: MAP Service closeService out
08-30 14:42:11.155  3899  3989 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 14:42:11.155  3899  3899 D BluetoothMapService: cleanup()
08-30 14:42:11.155  3899  3989 D BluetoothAdapterProperties: Setting state to 10
08-30 14:42:11.155  3899  3899 D BluetoothMapService: MAP Service closeService in
08-30 14:42:11.155  3899  3989 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 14:42:11.155  3899  3899 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 14:42:11.155  3899  3899 V BluetoothMapService: MAP Service closeService out
08-30 14:42:11.155  3899  3989 I BluetoothAdapterState: Entering OffState
08-30 14:42:11.155  1035  1117 D BluetoothManagerService: Message: 60
,08-30 14:42:11.156  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 14:42:11.156  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-30 14:42:11.156  6823  6839 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 14:42:11.159  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:42:11.160  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 14:42:11.160  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:42:11.160  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:42:11.165  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:42:11.166  1837  4433 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:42:11.167  6823  6839 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 14:42:11.169  1837  3510 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 14:42:11.171  6823  6838 D BluetoothPan: onBluetoothStateChange on: false
08-30 14:42:11.171  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:42:11.172  6823  6839 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 14:42:11.172  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 14:42:11.173  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 14:42:11.173  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 14:42:11.176  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:11.177  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 14:42:11.177  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 14:42:11.177  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@21feb42e mBinding = false
08-30 14:42:11.178  1035  1117 D BluetoothManagerService: Sending unbind request.
08-30 14:42:11.184  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-30 14:42:11.185  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:11.185  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:11.188  6874  6874 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 14:42:11.191  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:11.191  1927  2127 D LGBluetoothAPIService: Message: 2
08-30 14:42:11.192  1927  2127 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@34cadb8 mBinding = false
08-30 14:42:11.192  1927  2127 D LGBluetoothAPIService: Sending unbind request.
,08-30 14:42:11.193  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 14:42:11.195  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:11.195  3899  3993 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 14:42:11.196  3899  3899 I GKI_LINUX: GKI_exit_task 1 done
,08-30 14:42:11.196  3899  3899 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 14:42:11.197  3899  3899 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 14:42:11.197  3899  3899 I art     : --- WEIRD: removing null entry 246
08-30 14:42:11.197  3899  3899 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-30 14:42:11.197  3899  3899 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 14:42:11.200  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:11.200  1586  1586 D BluetoothAdapter: 571042873: getState() :  mService = null. Returning STATE_OFF
08-30 14:42:11.200  1586  1586 D BluetoothAdapter: 571042873: getState() :  mService = null. Returning STATE_OFF
08-30 14:42:11.201  6823  6823 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 14:42:11.202  6823  6823 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 14:42:11.202  6823  6823 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 14:42:11.206  6823  6823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 14:42:11.264  1035  1925 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6918 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 14:42:11.272  3899  3899 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 14:42:11.278  3899  3899 I art     : System.exit called, status: 0
08-30 14:42:11.278  3899  3899 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 14:42:11.295  6823  6823 D DockEventReceiver: finishStartingService: stopping service
,08-30 14:42:11.314   323   323 V AudioFlinger: 3899 died, releasing its sessions
,08-30 14:42:11.314   323   323 V AudioFlinger:  pid 1837 @ 0
08-30 14:42:11.314   323   323 V AudioFlinger:  pid 3414 @ 1
08-30 14:42:11.314   323   323 V AudioFlinger:  pid 3414 @ 2
08-30 14:42:11.315  6823  6823 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 14:42:11.330  1035  1890 I ActivityManager: Process com.android.bluetooth (pid 3899) has died
,08-30 14:42:11.330  1035  1890 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-30 14:42:11.341  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 14:42:11.358  6823  6823 D BluetoothPermissionRequest: onReceive
,08-30 14:42:11.363  6823  6823 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 14:42:11.363  6823  6823 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 14:42:11.369  6823  6823 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 14:42:11.445  1035  1889 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6937 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 14:42:11.464  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 14:42:11.471  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 14:42:11.478  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:11.500  6918  6956 W FormManager: Network not available. Please check & try again.
,08-30 14:42:11.502  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 14:42:11.503  6823  6823 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 14:42:11.503  6823  6823 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 14:42:11.503  6823  6823 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 14:42:11.504  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 14:42:11.514  6823  6823 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-30 14:42:11.515  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 14:42:11.515  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 14:42:11.516  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 14:42:11.516  6823  6823 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 14:42:11.516  6823  6823 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 14:42:11.516  6918  6957 V FormManager: Network unavailable.
08-30 14:42:11.520  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 14:42:11.520  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:42:11.521  6918  6957 V FormManager: Network unavailable.
08-30 14:42:11.522  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:42:11.524  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 14:42:11.532  4330  6960 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 14:42:11.533  6843  6843 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 14:42:11.533  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:42:11.533  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:42:11.535  4330  6961 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 14:42:11.535  4330  6961 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 14:42:11.536  6937  6937 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 14:42:11.537  6937  6937 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 14:42:11.537  6937  6937 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 14:42:11.538  6937  6937 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 14:42:11.538  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 14:42:11.548  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:11.549  6918  6962 W FormManager: Network not available. Please check & try again.
08-30 14:42:11.554  6918  6963 V FormManager: Network unavailable.
,08-30 14:42:11.561  6937  6937 D BluetoothAdapterApp: Loading JNI Library
08-30 14:42:11.562  6918  6963 V FormManager: Network unavailable.
08-30 14:42:11.567  6874  6874 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-30 14:42:11.568  1035  2033 I ActivityManager: Killing 5992:com.android.contacts/u0a19 (adj 15): empty #17
08-30 14:42:11.570  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 14:42:11.570  6874  6874 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-30 14:42:11.597  6937  6937 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@12f6e94e Instance Count = 1
,08-30 14:42:11.613  6874  6874 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:42:11.613  6874  6874 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:42:11.622  6874  6874 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 14:42:11.623  6874  6874 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 14:42:11.623  6874  6874 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 14:42:11.623  6874  6874 V SoundPool: doLoad: loading sample sampleID=1
08-30 14:42:11.623  6874  6966 V SoundPool: Start decode
08-30 14:42:11.624  6874  6966 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 14:42:11.624  6874  6874 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 14:42:11.624   323  1383 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 14:42:11.624   323  1383 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 14:42:11.624   323  1383 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 14:42:11.624   323  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 14:42:11.624   323  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 14:42:11.624   323  1383 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 14:42:11.625   323  1383 V MediaPlayerService: player type = 3
08-30 14:42:11.625   323  1383 V AwesomePlayer: AwesomePlayer create()
08-30 14:42:11.626   323  1383 V AwesomePlayer: reset_l() 
08-30 14:42:11.626   323  1383 V AwesomePlayer: cancelPlayerEvents
08-30 14:42:11.626   323  1383 V AwesomePlayer: setAudioSink() 
08-30 14:42:11.626   323  1383 V AwesomePlayer: reset_l() 
08-30 14:42:11.626   323  1383 V AudioCache: notify(0xb5474480, 8, 0, 0)
08-30 14:42:11.626   323  1383 V AudioCache: ignored
08-30 14:42:11.626   323  1383 V AwesomePlayer: cancelPlayerEvents
08-30 14:42:11.626   323  1383 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 14:42:11.626   323  1383 V AwesomePlayer: setDataSource_l dataSource
08-30 14:42:11.626   323  1383 V LGParserOSAL: SniffLGParser start
08-30 14:42:11.626   323  1383 V LGParserOSAL: MainType:5, SubType=0
08-30 14:42:11.626   323  1383 V LGParserOSAL: #### check Mime : application/ogg
08-30 14:42:11.626   323  1383 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 14:42:11.626   323  1383 E MediaExtractor: Use LGExtractor :application/ogg 
,08-30 14:42:11.638  1035  1722 W libprocessgroup: failed to open /acct/uid_10019/pid_5992/cgroup.procs: No such file or directory
08-30 14:42:11.642  6937  6937 D BluetoothAdapterApp: onCreate
08-30 14:42:11.643  6874  6874 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 14:42:11.645  6874  6874 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 14:42:11.645  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 14:42:11.646  6614  6614 D UEI.SmartControl: QS Service created
08-30 14:42:11.657  6874  6874 V LGMDMManager: Create singleton instance
08-30 14:42:11.678  6614  6614 I UEI.SmartControl: Service initServices...
08-30 14:42:11.678   323  1383 V LGParserOSAL: supported mime: application/ogg
08-30 14:42:11.678   323  1383 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 14:42:11.678   323  1383 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 14:42:11.678   323  1383 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 14:42:11.678   323  1383 V AwesomePlayer: AudioTrack Setting
08-30 14:42:11.678   323  1383 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 14:42:11.678   323  1383 V AwesomePlayer: setAudioSource() 
08-30 14:42:11.678  6614  6614 D UEI.SmartControl: QS start get config
08-30 14:42:11.678   323  1383 V MediaPlayerService: prepare
08-30 14:42:11.678   323  1383 V AwesomePlayer: prepareAsync_l() 
08-30 14:42:11.678   323  1383 V MediaPlayerService: wait for prepare
08-30 14:42:11.679   323  6967 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 14:42:11.679   323  6967 V AwesomePlayer: initAudioDecoder() 
08-30 14:42:11.679   323  6967 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 14:42:11.679   323  6967 V AudioSystem: isOffloadSupported()
08-30 14:42:11.679   323  6967 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 14:42:11.679   323  6967 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 14:42:11.679   323  6967 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 14:42:11.679   323  6967 V AwesomePlayer: getUseOffload() = 0 
08-30 14:42:11.679   323  6967 V OMXCodec: OMXCodec::Create
08-30 14:42:11.679   323  6967 V OMXCodec: findMatchingCodecs()
08-30 14:42:11.679   323  6967 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 14:42:11.679   323  6967 V OMXCodec: matchingCodecs.size()=1
08-30 14:42:11.679   323  6967 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-30 14:42:11.681   323  6967 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,08-30 14:42:11.682   323  6967 V LGCodecAdapter: LG Codec Adapter start
08-30 14:42:11.682   323  6967 V OMXCodec: OMXCodec Createtor
08-30 14:42:11.682   323  6967 V OMXCodec: setComponentRole
,08-30 14:42:11.682   323  6967 V OMXCodec: configureCodec protected=0
08-30 14:42:11.682   323  6967 V LGCodecAdapter: called getLGCodecSpecificData
08-30 14:42:11.682   323  6967 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 14:42:11.682   323  6967 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 14:42:11.682   323  6967 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 14:42:11.682   323  6967 V LGCodecOSAL: Not support LGCodec
08-30 14:42:11.682   323  6967 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 14:42:11.682   323  6967 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 14:42:11.682   323  6967 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 14:42:11.682   323  6967 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 14:42:11.682   323  6967 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 14:42:11.682   323  6967 V AudioSystem: isOffloadSupported()
08-30 14:42:11.682   323  6967 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 14:42:11.682   323  6967 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 14:42:11.682   323  6967 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 14:42:11.682   323  6967 V OMXCodec: init()
08-30 14:42:11.682   323  6967 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 14:42:11.682   323  6967 V OMXCodec: allocateBuffers
08-30 14:42:11.682   323  6967 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 14:42:11.682   323  6967 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 14:42:11.683   323  6967 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-30 14:42:11.683   323  6967 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-30 14:42:11.683   323  6967 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-30 14:42:11.683   323  6967 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-30 14:42:11.683   323  6967 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 14:42:11.683   323  6967 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 14:42:11.683   323  6967 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-30 14:42:11.684   323  6967 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-30 14:42:11.684   323  6967 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-30 14:42:11.684   323  6967 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-30 14:42:11.684   323  6967 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 14:42:11.685  6937  6937 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 14:42:11.685   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 14:42:11.685   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 14:42:11.685  6937  6937 D ProfileConfigQcom: Adding HeadsetService
08-30 14:42:11.685   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 14:42:11.685   323  6967 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 14:42:11.685   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 14:42:11.685   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 14:42:11.685   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 14:42:11.685   323  6967 V OMXCodec: init() mAsyncCo,mpletion wait free! 
08-30 14:42:11.685   323  6967 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 14:42:11.685  6937  6937 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 14:42:11.685   323  6967 V AudioCache: notify(0xb5474480, 5, 0, 0)
08-30 14:42:11.685   323  6967 V AudioCache: ignored
08-30 14:42:11.686   323  6967 V AudioCache: notify(0xb5474480, 1, 0, 0)
08-30 14:42:11.686   323  6967 V AudioCache: prepared
08-30 14:42:11.686   323  1383 V AudioCache: wait - success
08-30 14:42:11.686  6937  6937 D ProfileConfigQcom: Adding A2dpService
08-30 14:42:11.686   323  1383 V MediaPlayerService: start
08-30 14:42:11.686   323  1383 V AwesomePlayer: play_l() 
08-30 14:42:11.686   323  1383 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 14:42:11.686   323  1383 V AwesomePlayer: createAudioPlayer_l
08-30 14:42:11.686   323  1383 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 14:42:11.686   323  1383 V AwesomePlayer: startAudioPlayer_l() 
08-30 14:42:11.686   323  1383 D AudioPlayer: start of Playback, useOffload 0
08-30 14:42:11.686   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 14:42:11.686  6937  6937 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 14:42:11.686   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 14:42:11.686  6937  6937 D ProfileConfigQcom: Adding HidService
08-30 14:42:11.686  6937  6937 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 14:42:11.686  6937  6937 D ProfileConfigQcom: Adding HealthService
08-30 14:42:11.687  6937  6937 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 14:42:11.688  6937  6937 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 14:42:11.688  6937  6937 D ProfileConfigQcom: Adding PanService
08-30 14:42:11.688  6937  6937 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 14:42:11.688  6937  6937 D ProfileConfigQcom: Adding GattService
08-30 14:42:11.688  6937  6937 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 14:42:11.689  6937  6937 D ProfileConfigQcom: Adding BluetoothMapService
08-30 14:42:11.689   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 14:42:11.689  6937  6937 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 14:42:11.689   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 14:42:11.689   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 14:42:11.689   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 14:42:11.689   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 14:42:11.689   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 14:42:11.689   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-30 14:42:11.689   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:42:11.689   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-30 14:42:11.689   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-30 14:42:11.689   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-30 14:42:11.689   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:42:11.690   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
08-30 14:42:11.690   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:42:11.690   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 14:42:11.690   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 14:42:11.690   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
,08-30 14:42:11.690   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 14:42:11.690   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 14:42:11.690   323  6969 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 14:42:11.690   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 14:42:11.690   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-30 14:42:11.691   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-30 14:42:11.691   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
,08-30 14:42:11.691   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57cd1a0 on output port
08-30 14:42:11.691   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 14:42:11.691   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 14:42:11.691  6937  6937 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 14:42:11.693   323  1383 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 14:42:11.693   323  1383 V AudioCache: notify(0xb5474480, 6, 0, 0)
08-30 14:42:11.693   323  1383 V AudioCache: ignored
,08-30 14:42:11.696   323  1383 V MediaPlayerService: wait for playback complete
08-30 14:42:11.697  6823  6823 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 14:42:11.699  6937  6937 V LGMDMManagerInternal: Create singleton instance
08-30 14:42:11.712   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.712   323  6971 V AudioCache: memcpy(0xac300000, 0xb16e0000, 4096)
08-30 14:42:11.712  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 14:42:11.714  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-30 14:42:11.714   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.714   323  6971 V AudioCache: memcpy(0xac301000, 0xb16e0000, 4096)
,08-30 14:42:11.715   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.715   323  6971 V AudioCache: memcpy(0xac302000, 0xb16e0000, 4096)
08-30 14:42:11.716   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.716   323  6971 V AudioCache: memcpy(0xac303000, 0xb16e0000, 4096)
08-30 14:42:11.716   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.716   323  6971 V AudioCache: memcpy(0xac304000, 0xb16e0000, 4096)
08-30 14:42:11.717   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.717   323  6971 V AudioCache: memcpy(0xac305000, 0xb16e0000, 4096)
08-30 14:42:11.718   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.718   323  6971 V AudioCache: memcpy(0xac306000, 0xb16e0000, 4096)
08-30 14:42:11.718   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.718   323  6971 V AudioCache: memcpy(0xac307000, 0xb16e0000, 4096)
08-30 14:42:11.719  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:144
08-30 14:42:11.719   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.719   323  6971 V AudioCache: memcpy(0xac308000, 0xb16e0000, 4096)
08-30 14:42:11.720   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.720   323  6971 V AudioCache: memcpy(0xac309000, 0xb16e0000, 4096)
08-30 14:42:11.720   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.720   323  6971 V AudioCache: memcpy(0xac30a000, 0xb16e0000, 4096)
08-30 14:42:11.721   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.721   323  6971 V AudioCache: memcpy(0xac30b000, 0xb16e0000, 4096)
08-30 14:42:11.722   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.722   323  6971 V AudioCache: memcpy(0xac30c000, 0xb16e0000, 4096)
08-30 14:42:11.722   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.722   323  6971 V AudioCache: memcpy(0xac30d000, 0xb16e0000, 4096)
08-30 14:42:11.723   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.723   323  6971 V AudioCache: memcpy(0xac30e000, 0xb16e0000, 4096)
08-30 14:42:11.723   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.723   323  6971 V AudioCache: memcpy(0xac30f000, 0xb16e0000, 4096)
08-30 14:42:11.723   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.723   323  6971 V AudioCache: memcpy(0xac310000, 0xb16e0000, 4096)
08-30 14:42:11.723   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.723   323  6971 V AudioCache: memcpy(0xac311000, 0xb16e0000, 4096)
08-30 14:42:11.725   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.725   323  6971 V AudioCache: memcpy(0xac312000, 0xb16e0000, 4096)
08-30 14:42:11.725   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.726   323  6971 V AudioCache: memcpy(0xac313000, 0xb16e0000, 4096)
08-30 14:42:11.726   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.726   323  6971 V AudioCache: memcpy(0xac314000, 0xb16e0000, 4096)
08-30 14:42:11.726   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.726   323  6971 V AudioCache: memcpy(0xac315000, 0xb16e0000, 4096)
08-30 14:42:11.727   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.727   323  6971 V AudioCache: memcpy(0xac316000, 0xb16e0000, 4096)
08-30 14:42:11.727   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.727   323  6971 V AudioCache: memcpy(0xac317000, 0xb16e0000, 4096)
08-30 14:42:11.728   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.728   323  6971 V AudioCache: memcpy(0xac318000, 0xb16e0000, 4096)
,08-30 14:42:11.728   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.728   323  6971 V AudioCache: memcpy(0xac319000, 0xb16e0000, 4096)
08-30 14:42:11.729   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.729   323  6971 V AudioCache: memcpy(0xac31a000, 0xb16e0000, 4096)
08-30 14:42:11.729   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.729   323  6971 V AudioCache: memcpy(0xac31b000, 0xb16e0000, 4096)
08-30 14:42:11.730   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.730   323  6971 V AudioCache: memcpy(0xac31c000, 0xb16e0000, 4096)
08-30 14:42:11.731   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.731   323  6971 V AudioCache: memcpy(0xac31d000, 0xb16e0000, 4096)
08-30 14:42:11.731   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.731   323  6971 V AudioCache: memcpy(0xac31e000, 0xb16e0000, 4096)
08-30 14:42:11.732   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.732   323  6971 V AudioCache: memcpy(0xac31f000, 0xb16e0000, 4096)
08-30 14:42:11.732   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.732   323  6971 V AudioCache: memcpy(0xac320000, 0xb16e0000, 4096)
08-30 14:42:11.733   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.733   323  6971 V AudioCache: memcpy(0xac321000, 0xb16e0000, 4096)
08-30 14:42:11.733   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.733   323  6971 V AudioCache: memcpy(0xac322000, 0xb16e0000, 4096)
08-30 14:42:11.734   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.734   323  6971 V AudioCache: memcpy(0xac323000, 0xb16e0000, 4096)
,08-30 14:42:11.735   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.735   323  6971 V AudioCache: memcpy(0xac324000, 0xb16e0000, 4096)
08-30 14:42:11.735   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.735   323  6971 V AudioCache: memcpy(0xac325000, 0xb16e0000, 4096)
08-30 14:42:11.736   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.736   323  6971 V AudioCache: memcpy(0xac326000, 0xb16e0000, 4096)
08-30 14:42:11.736   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.736   323  6971 V AudioCache: memcpy(0xac327000, 0xb16e0000, 4096)
08-30 14:42:11.737   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.737   323  6971 V AudioCache: memcpy(0xac328000, 0xb16e0000, 4096)
08-30 14:42:11.737   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.737   323  6971 V AudioCache: memcpy(0xac329000, 0xb16e0000, 4096)
08-30 14:42:11.738   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.738   323  6971 V AudioCache: memcpy(0xac32a000, 0xb16e0000, 4096)
08-30 14:42:11.738   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.738   323  6971 V AudioCache: memcpy(0xac32b000, 0xb16e0000, 4096)
08-30 14:42:11.739   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.739   323  6971 V AudioCache: memcpy(0xac32c000, 0xb16e0000, 4096)
08-30 14:42:11.740   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.740   323  6971 V AudioCache: memcpy(0xac32d000, 0xb16e0000, 4096)
,08-30 14:42:11.740   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.740   323  6971 V AudioCache: memcpy(0xac32e000, 0xb16e0000, 4096)
08-30 14:42:11.741   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.741   323  6971 V AudioCache: memcpy(0xac32f000, 0xb16e0000, 4096)
08-30 14:42:11.741   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.741   323  6971 V AudioCache: memcpy(0xac330000, 0xb16e0000, 4096)
08-30 14:42:11.742   323  6971 V AudioCache: write(0xb16e0000, 4096)
08-30 14:42:11.742   323  6971 V AudioCache: memcpy(0xac331000, 0xb16e0000, 4096)
08-30 14:42:11.742   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 14:42:11.742   323  6971 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 14:42:11.742   323  6971 V AwesomePlayer: postAudioEOS() 
08-30 14:42:11.742   323  6971 V AudioCache: write(0xb16e0000, 280)
08-30 14:42:11.742   323  6971 V AudioCache: memcpy(0xac332000, 0xb16e0000, 280)
08-30 14:42:11.744   323  6967 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 14:42:11.744   323  6967 V AwesomePlayer: onStreamDone
08-30 14:42:11.744   323  6967 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 14:42:11.744   323  6967 V AudioCache: notify(0xb5474480, 2, 0, 0)
08-30 14:42:11.744   323  6967 V AudioCache: playback complete
08-30 14:42:11.744   323  6967 V AwesomePlayer: pause_l() 
08-30 14:42:11.744   323  6967 V AudioCache: notify(0xb5474480, 7, 0, 0)
,08-30 14:42:11.744   323  6967 V AudioCache: ignored,
08-30 14:42:11.744   323  6967 V AwesomePlayer: cancelPlayerEvents
08-30 14:42:11.744   323  6967 D AudioPlayer: Pause Playback at 1068125
08-30 14:42:11.744   323  1383 V AudioCache: wait - success
08-30 14:42:11.744   323  1383 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 14:42:11.744   323  1383 V AwesomePlayer: reset_l() 
08-30 14:42:11.744   323  1383 V AudioCache: notify(0xb5474480, 8, 0, 0)
08-30 14:42:11.744   323  1383 V AudioCache: ignored
08-30 14:42:11.744   323  1383 V AwesomePlayer: cancelPlayerEvents
08-30 14:42:11.744   323  1383 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 14:42:11.744   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 14:42:11.744   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 14:42:11.744   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
,08-30 14:42:11.744   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 14:42:11.745   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 14:42:11.745   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 14:42:11.745   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 14:42:11.745   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-30 14:42:11.745   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 14:42:11.745   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-30 14:42:11.745   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 14:42:11.745   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-30 14:42:11.745   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 14:42:11.745   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-30 14:42:11.745   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0,
08-30 14:42:11.745   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 14:42:11.745   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57cd1a0 on port 1
08-30 14:42:11.745   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 14:42:11.745   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-30 14:42:11.746   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 14:42:11.746   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-30 14:42:11.746   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 14:42:11.746   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
,08-30 14:42:11.746   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:42:11.746   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 14:42:11.746   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 14:42:11.746   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 14:42:11.746   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 14:42:11.746   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 14:42:11.746   323  6969 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 14:42:11.746   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 14:42:11.746   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1,
08-30 14:42:11.746   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 14:42:11.747   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 14:42:11.747   323  1383 D AudioPlayer: AudioPlayer releasing audio source
08-30 14:42:11.747   323  1383 D AudioPlayer: AudioPlayer done releasing audio source
08-30 14:42:11.747   323  1383 V AwesomePlayer: reset_l() 
08-30 14:42:11.747   323  1383 V AwesomePlayer: cancelPlayerEvents
08-30 14:42:11.747   323  1383 V AwesomePlayer: ~AwesomePlayer call
,08-30 14:42:11.748   323  1383 V AwesomePlayer: reset_l() 
08-30 14:42:11.748   323  1383 V AwesomePlayer: cancelPlayerEvents
08-30 14:42:11.748  6874  6966 V SoundPool: close(31)
08-30 14:42:11.748  6874  6966 V SoundPool: pointer = 0xa0039000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 14:42:11.792  6937  6937 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 14:42:11.798  6937  6937 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 14:42:11.799  6937  6937 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:42:11.799  6937  6937 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 14:42:11.800  6937  6937 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:11.800  6937  6937 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 14:42:11.808  6896  6896 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-30 14:42:11.960  6614  6614 I UEI.SmartControl: Supports setup maps: true
,08-30 14:42:11.962  6614  6614 D UEI.SmartControl: QS start statue = true Error code = 0
,08-30 14:42:11.962  6614  6614 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 14:42:11.962  6614  6614 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 14:42:11.963  6614  6614 I UEI.SmartControl: ### init IR Blaster...
08-30 14:42:11.966  6614  6614 D serial_port: Configuring serial port
08-30 14:42:11.966  6614  6614 E UEI.SmartControl: UEIBLaster setting for 616
08-30 14:42:11.966  6614  6614 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 14:42:11.967  6614  6614 I UEI.SmartControl: configuring settings for MAXQ616
08-30 14:42:11.967  6614  6614 I UEI.SmartControl: Get version...
08-30 14:42:11.981  6614  6973 D UEI.SmartControl: serial port data available: 21
,08-30 14:42:12.007  6614  6614 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 14:42:12.007  6614  6614 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-30 14:42:12.007  6614  6614 I UEI.SmartControl: QS saving settings...
08-30 14:42:12.009  6614  6614 D UEI.SmartControl: IR Blaster version: 25672567
08-30 14:42:12.026  6614  6973 D UEI.SmartControl: serial port data available: 4
,08-30 14:42:12.054  6614  6614 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 14:42:12.060  6614  6982 I UEI.SmartControl: Device manager: loading config....
08-30 14:42:12.061  6614  6982 D UEI.SmartControl: ----------- loading internal config...
08-30 14:42:12.062  6614  6614 E UEI.SmartControl: Services init done
08-30 14:42:12.062  6614  6614 D UEI.SmartControl: QS Service init finished
08-30 14:42:12.063  6614  6614 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 14:42:12.063  6614  6614 D UEI.SmartControl: QS Service version code: 201091
08-30 14:42:12.064  6614  6614 D UEI.SmartControl: Service requested: Control
08-30 14:42:12.067  6614  6982 E UEI.SmartControl: Loading SETTINGS...
08-30 14:42:12.069  6614  6614 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-30 14:42:12.073  6874  6874 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 14:42:12.074  6614  6614 D UEI.SmartControl: Internal service binding...
08-30 14:42:12.074  6614  6630 I UEI.SmartControl: ------ IControl API: 11
08-30 14:42:12.074  6614  6630 D UEI.SmartControl: File observer start...
08-30 14:42:12.075  6614  6630 E UEI.SmartControl: IR Port is disabled: false
08-30 14:42:12.075  6614  6630 D UEI.SmartControl: Starting file observer...
08-30 14:42:12.075  6614  6630 I UEI.SmartControl: Registering callback...
08-30 14:42:12.075  6614  6629 I UEI.SmartControl: ------ IControl API: 19
08-30 14:42:12.076  6614  6629 I UEI.SmartControl: Registering Services Ready callback...
08-30 14:42:12.077  6614  6982 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 14:42:12.084  6614  6981 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 14:42:12.085  6614  6981 D UEI.SmartControl: -----service ready thread exits
08-30 14:42:12.085  6874  6890 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-30 14:42:12.086  6874  6964 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 14:42:12.086  6874  6964 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 14:42:12.087  6874  6874 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 14:42:12.087  6874  6874 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 14:42:12.087  6614  6630 I UEI.SmartControl: ------ IControl API: 8
08-30 14:42:12.090  6874  6874 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 14:42:12.090  6874  6874 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 14:42:12.091  6874  6874 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 14:42:12.091  6874  6874 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 14:42:12.092  6874  6874 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 14:42:12.093  6874  6874 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 14:42:12.094  6874  6874 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-30 14:42:12.096  6874  6874 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 14:42:12.096  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 14:42:12.097  6874  6874 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 14:42:12.097  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 14:42:12.099  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 14:42:12.100  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,08-30 14:42:12.100  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 14:42:12.101  6874  6874 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472560932101]
08-30 14:42:12.106  6874  6874 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 14:42:12.109  1035  1889 I ActivityManager: Killing 6019:com.android.gallery3d/u0a27 (adj 15): empty #17
08-30 14:42:12.128  6874  6984 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 14:42:12.140  1035  1889 I ActivityManager: Killing 6499:com.lge.email/u0a23 (adj 15): empty #18
,08-30 14:42:12.172  1035  1998 W libprocessgroup: failed to open /acct/uid_10027/pid_6019/cgroup.procs: No such file or directory
,08-30 14:42:12.175  1035  1722 W libprocessgroup: failed to open /acct/uid_10023/pid_6499/cgroup.procs: No such file or directory
08-30 14:42:12.182  6874  6874 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-30 14:42:12.183  6874  6874 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 14:42:12.185  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 14:42:12.185  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 14:42:12.186  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 14:42:12.187  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 14:42:12.188  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 14:42:12.201  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 14:42:13.023  1035  1560 D WifiServiceImplEx: setWifiEnabled: true pid=6717, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 14:42:13.025  1035  1560 D WifiService: setWifiEnabled: true pid=6717, uid=10118
08-30 14:42:13.025  1035  1560 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:42:13.049  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:42:13.049  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 14:42:13.049  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 14:42:13.051  1035  1377 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 14:42:13.051  1035  1377 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 14:42:13.053  1035  1377 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 14:42:13.054  1035  1377 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 14:42:13.054  1035  1377 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 14:42:13.054  1035  1377 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 14:42:13.054  1035  1377 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 14:42:13.054  1035  1377 E WifiHW  : unknown target_country: EU , set to default
08-30 14:42:13.054  1035  1377 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 14:42:13.054  1035  1377 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 14:42:13.054  1035  1377 I WifiUtil: gEnableBmps=1
08-30 14:42:13.085  1035  1434 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:42:13.091  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-30 14:42:13.101  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:42:13.106  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:13.107  1035  1434 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:13.113  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,08-30 14:42:13.117  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:13.124  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:13.126  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:42:13.129  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 14:42:13.133  6401  6842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 14:42:13.142  5290  5290 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 14:42:13.149  5290  5290 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 14:42:13.164  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:42:13.193  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:42:13.238  1035  1962 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6994 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 14:42:13.245  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:13.245  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 14:42:13.325  6994  6994 I AppUp4:AppBoxCP: onCreate
08-30 14:42:13.326  6994  6994 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-30 14:42:13.336  6994  6994 I AppUp4:DB:  setFingerPrint start
08-30 14:42:13.336  6994  6994 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-30 14:42:13.345  6994  6994 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-30 14:42:13.345  6994  6994 I AppUp4:DB:  SDK version = 21
08-30 14:42:13.345  6994  6994 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-30 14:42:13.347  6994  6994 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-30 14:42:13.348  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 14:42:13.348  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:13.350  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 14:42:13.351  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 14:42:13.357  6994  6994 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 14:42:13.397  6994  6994 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 14:42:13.398  6994  6994 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:42:13.406  6994  6994 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26998b68
08-30 14:42:13.406  6994  6994 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 14:42:13.406  6994  6994 D AppUp4:CustFacade: isPhone : true
08-30 14:42:13.407  6994  6994 D AppUp4:CustModeStarterReceiver: begin check event
08-30 14:42:13.407  6994  6994 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-30 14:42:13.407  6994  6994 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-30 14:42:13.408  6994  7022 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-30 14:42:13.409  6994  7022 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-30 14:42:13.409  6994  7022 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-30 14:42:13.415  1035  1769 I ActivityManager: Killing 6534:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-30 14:42:13.472  1035  1889 W libprocessgroup: failed to open /acct/uid_10061/pid_6534/cgroup.procs: No such file or directory
,08-30 14:42:13.474  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:13.475  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:42:13.479  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:42:13.481  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:42:13.491  4330  7026 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 14:42:13.501  4330  7027 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:13.502  4330  7027 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 14:42:13.564  1035  1962 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7031 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 14:42:13.647  7031  7031 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 14:42:13.650  7031  7031 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 14:42:13.652  7031  7031 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 14:42:13.652  7031  7031 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 14:42:13.746  7031  7031 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 14:42:13.775  7031  7031 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 14:42:13.797  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 14:42:13.803  1035  1117 D Tethering: InitialState.processMessage what=4
08-30 14:42:13.805  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 14:42:13.811   319   917 D SoftapController: Softap fwReload - Ok
08-30 14:42:13.811  1035  1377 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (751ms)
,08-30 14:42:13.817   319   917 D CommandListener: Setting iface cfg
08-30 14:42:13.817   319   917 D CommandListener: Trying to bring down wlan0
08-30 14:42:13.817   319   917 D CommandListener: Clearing all IP addresses on wlan0
08-30 14:42:13.819  1035  1377 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 14:42:13.823  1035  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:42:13.823  1035  1377 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:42:13.823  1035  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 14:42:13.825  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-30 14:42:13.825  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 14:42:13.828  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:13.817  7056  7056 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:13.829  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:13.830  1035  1377 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 14:42:13.830  1035  1377 D WifiMonitor: connecting to supplicant
08-30 14:42:13.817  7056  7056 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:13.830  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:13.855  7056  7056 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 14:42:13.871  7031  7031 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 14:42:13.897  7056  7056 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 14:42:13.898  7056  7056 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 14:42:13.907  7031  7031 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:42:13.907  7031  7031 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:42:13.991  7056  7056 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 14:42:14.007  7031  7031 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 14:42:14.032  3414  3414 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 14:42:14.032  3414  3414 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:42:14.033  3414  3414 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 14:42:14.039  7031  7031 I HubEmail: JNI_OnLoad()
08-30 14:42:14.039  7031  7031 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-30 14:42:14.039  7031  7031 I HubEmail: registerNatives()
08-30 14:42:14.040  7031  7031 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 14:42:14.040  7031  7031 I HubEmail: registerNativeMethods()
08-30 14:42:14.040  7031  7031 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 14:42:14.040  7031  7031 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-30 14:42:14.053  7056  7056 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-30 14:42:14.061  1035  1889 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7070 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 14:42:14.062  1035  1377 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 14:42:14.063  1035  1377 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 14:42:14.063  1035  1377 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 14:42:14.065  6918  7068 V FormManager: Network unavailable.
08-30 14:42:14.065  7056  7056 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-30 14:42:14.065  7056  7056 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 14:42:14.065  1035  7080 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 14:42:14.066  1035  1377 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 14:42:14.066  1035  7080 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 14:42:14.066  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 14:42:14.066  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 14:42:14.066  1035  7080 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 14:42:14.067  1035  7080 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-30 14:42:14.070  6918  7068 V FormManager: Network unavailable.
08-30 14:42:14.070  1035  1377 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:14.071  1035  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:14.071  7031  7069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.071  1035  1377 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:14.072  1035  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:14.072  1035  1377 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 14:42:14.072  1035  1377 D WifiNative-wlan0: doString: [DRIVER MACADDR],
08-30 14:42:14.072  1035  1377 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 14:42:14.073  1035  1377 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 14:42:14.073  1035  1377 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 14:42:14.073  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.073  1035  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:42:14.073  1035  1377 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:42:14.073  1035  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 14:42:14.073  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.074  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.074  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.074  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:42:14.074  1035  1377 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 14:42:14.074  6918  7066 W FormManager: Network not available. Please check & try again.
08-30 14:42:14.075  1035  1377 D WifiNative-wlan0: SET update_config 1: returned true
08-30 14:42:14.075  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:14.076  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 14:42:14.076  1035  1421 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 14:42:14.077  1927  1927 D WfdService: Waiting for WifiP2p enabling
08-30 14:42:14.078  1035  1377 D WifiConfigStore: Loading config and enabling all networks 
08-30 14:42:14.078  1035  1377 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 14:42:14.079  1035  1377 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-30 14:42:14.080  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:14.081  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:14.081  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:14.081  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:14.081  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:14.081  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:42:14.081  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:14.081  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:14.081  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:42:14.081  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:14.081  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:42:14.082  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:14.082  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:14.082  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:14.082  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:14.082  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:14.082  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:42:14.082  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:14.082  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:14.082  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:42:14.082  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:14.082  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:42:14.085  1035  1962 I ActivityManager: Killing 6084:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-30 14:42:14.086  1035  1377 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 14:42:14.095  1035  1377 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 14:42:14.096  1035  1377 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 14:42:14.121  1035  1998 W libprocessgroup: failed to open /acct/uid_10080/pid_6084/cgroup.procs: No such file or directory
08-30 14:42:14.121  1035  1377 D WifiStateMachine: enableVerboseLogging : level 2
08-30 14:42:14.121  1035  1377 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 14:42:14.121  1035  1377 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 14:42:14.121  1035  1377 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,08-30 14:42:14.122  1035  1377 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 14:42:14.122  1035  1377 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 14:42:14.122  1035  1377 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 14:42:14.122  1035  1377 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 14:42:14.123  1035  1377 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 14:42:14.123  1035  1377 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 14:42:14.123  1035  1377 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 14:42:14.123  1035  1377 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 14:42:14.124  1035  1377 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 14:42:14.124  1035  1377 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 14:42:14.124  1035  1377 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 14:42:14.126  1035  1377 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 14:42:14.126  1035  1377 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 14:42:14.127  1927  1927 D WfdsService: Supplicant Connection state is changed : true
08-30 14:42:14.127  1927  2286 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
,08-30 14:42:14.127  1927  2286 D WfdsService: Set the WFDS Monitor: true
08-30 14:42:14.127  1927  2286 D WfdsMonitor: WfdsMonitorThread create
08-30 14:42:14.127  1035  1377 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 14:42:14.127  1035  1377 D WifiNative-HAL: Setting external_sim to 1
08-30 14:42:14.127  1035  1377 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 14:42:14.127  1927  2286 D WfdsMonitor: WFDS Monitor is created and started
08-30 14:42:14.127  1927  2286 D WfdsService: WiFi: Supplicant connection re-established
08-30 14:42:14.128  1035  1377 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 14:42:14.128  1035  1377 I WifiNative-HAL: startHal
,08-30 14:42:14.128  1035  1377 D wifi    : setting scan oui 0xaf67bb20
08-30 14:42:14.128  1035  1377 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 14:42:14.128  1927  7088 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 14:42:14.128  1035  1377 I WifiNative-HAL: startHal
08-30 14:42:14.128  1035  1377 D wifi    : setting scan oui 0xaf67bb20
08-30 14:42:14.128  1035  1377 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 14:42:14.129  1927  7088 E CtrlSupplicant: Succeed to open control connection
08-30 14:42:14.129  1035  1377 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 14:42:14.129  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 14:42:14.129  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 14:42:14.129  1927  7088 E CtrlSupplicant: Succeed to open monitor connection
08-30 14:42:14.129  1927  7088 D WfdsMonitor: Supplicant connection established
08-30 14:42:14.129  1035  1377 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 14:42:14.129  1927  2286 D WfdsService: Connected to the supplicant for wfds
08-30 14:42:14.129  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 14:42:14.130  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 14:42:14.130  1035  1377 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 14:42:14.130  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 14:42:14.130  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 14:42:14.131  1035  1377 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 14:42:14.131  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 14:42:14.131  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 14:42:14.131  1035  1377 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 14:42:14.131  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 14:42:14.131  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 14:42:14.132  1035  1377 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 14:42:14.132  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 14:42:14.132  7056  7056 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 14:42:14.132  1035  1377 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 14:42:14.132  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 14:42:14.132  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 14:42:14.133  1035  1377 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 14:42:14.134  1035  1377 E WifiNative: : [205,881,113 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 14:42:14.134  1035  1377 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 14:42:14.134  1035  1377 D WifiNative-wlan0: RECONNECT: returned true
08-30 14:42:14.134  1035  1377 D WifiNative-wlan0: doString: [STATUS]
08-30 14:42:14.135  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 14:42:14.135  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 14:42:14.135  1035  1377 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 14:42:14.135  1035  1377 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:42:14.136  1035  1377 D WifiNative-wlan0: SET ps 1: returned true
08-30 14:42:14.136  1035  1375 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 14:42:14.138   319   917 D CommandListener: Setting iface cfg
08-30 14:42:14.138   319   917 D CommandListener: Trying to bring up p2p0
08-30 14:42:14.139  1035  1375 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 14:42:14.139  1035  1375 D LGWifiP2pService: P2pEnablingState
08-30 14:42:14.139  1035  1375 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.139  1035  1375 D LGWifiP2pService: P2p socket connection successful
08-30 14:42:14.139  1035  1375 D LGWifiP2pService: P2pEnabledState
08-30 14:42:14.139  1035  1375 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 14:42:14.140  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 14:42:14.140  1927  1927 D WfdsService: WifiP2pState is changed : true
08-30 14:42:14.140  1927  2286 D WfdsService: Receive the WFDS_ENABLE Method
08-30 14:42:14.140  1927  2286 D WfdsService: Set the WFDS Monitor: true
08-30 14:42:14.141  1927  2286 D WfdsService: Connected to the supplicant for wfds
08-30 14:42:14.141  1927  2286 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 14:42:14.141  7056  7056 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 14:42:14.141  1927  2286 D WfdsService: selectPreferredScanChannel [36]
08-30 14:42:14.141  1927  2286 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 14:42:14.141  1035  1375 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 14:42:14.141  1035  1375 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 14:42:14.141  1035  1375 D WifiNative-p2p0: doBoolean: SET device_name G3
,08-30 14:42:14.141  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 14:42:14.142  1035  1375 D WifiNative-p2p0: SET device_name G3: returned true
08-30 14:42:14.142  1035  1375 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 14:42:14.142  1035  1375 D LGWifiP2pService: before postfix = G3
,08-30 14:42:14.142  1035  1375 D WifiServerServiceExt: postfix byte check : 2
08-30 14:42:14.142  1035  1375 D LGWifiP2pService: after postfix = G3
08-30 14:42:14.142  1035  1375 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 14:42:14.142  1927  1927 D WfdsService: isConnected: false
08-30 14:42:14.142  1035  1375 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 14:42:14.142  1035  1375 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 14:42:14.143  1035  1375 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 14:42:14.143  1035  1375 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 14:42:14.143  1035  1375 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 14:42:14.143  1035  1375 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 14:42:14.144  1035  1377 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 14:42:14.144  1035  1377 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 14:42:14.144  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 14:42:14.144  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-30 14:42:14.144  1035  1541 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.144  1035  1541 I WifiNative-HAL: startHal
08-30 14:42:14.144  1035  1377 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 14:42:14.145  1035  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.145  1035  1375 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 14:42:14.145  1035  1377 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 14:42:14.145  1035  1541 D wifi    : getting scan capabilities on interface[1] = 0xaf67bb20
08-30 14:42:14.145  1035  1541 D wifi    : failed to get capabilities : -3
08-30 14:42:14.145  1035  1541 E WifiScanningService: could not get scan capabilities
08-30 14:42:14.145  1035  1375 D WifiNative-HAL: p2pGetDeviceAddress
08-30 14:42:14.145  1035  1375 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 14:42:14.145  1035  1377 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 14:42:14.145  1035  1375 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 14:42:14.145  1035  1375 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 14:42:14.146  1035  1377 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 14:42:14.146  1035  1375 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 14:42:14.146  1035  1375 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 14:42:14.146  1035  1377 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 14:42:14.146  1035  1377 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 14:42:14.146  7056  7056 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 14:42:14.146  1035  1375 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 14:42:14.146  1035  1375 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 14:42:14.147  1035  1375 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 14:42:14.147  1035  1375 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 14:42:14.147  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 14:42:14.147  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 14:42:14.147  1035  1377 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 14:42:14.147  1927  1927 D WfdsService: Update P2p Interface State: 3
08-30 14:42:14.147  1035  1377 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 14:42:14.147  1035  1377 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 14:42:14.148  1035  1377 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-30 14:42:14.166  7056  7056 E wpa_supplicant: disconnect_rssi_lvl: -100
,08-30 14:42:14.166  1035  1375 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 14:42:14.166  1035  1375 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 14:42:14.166  1035  1377 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 14:42:14.166  1035  1375 D LGWifiP2pService: InactiveState
08-30 14:42:14.166  1035  1375 D LGWifiP2pService: InactiveState{ when=-20ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.166  1035  1377 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 14:42:14.166  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=-20ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.166  1035  1375 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 14:42:14.167  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 14:42:14.168  1035  1377 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 14:42:14.168  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 14:42:14.168  7056  7056 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:14.168  7056  7056 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 14:42:14.168  7056  7056 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.169  1035  1375 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 14:42:14.169  1035  1375 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.169  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.169  1035  1375 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.169  1035  1375 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.169  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.169  1035  1375 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.169  1035  1375 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.169  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.169  1035  1375 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.169  1927  2286 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 14:42:14.169  1035  1375 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.169  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.169  1035  1375 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.169  1927  7088 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 14:42:14.170  1035  1035 E WifiServerServiceExt: No p2p device connected
08-30 14:42:14.170  1035  7080 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 14:42:14.170  1035  7080 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:14.170  1035  7080 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:14.170  1035  7080 E WifiMonitor: handleEvent unknown: 14  CT,RL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:14.170  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 14:42:14.171  7056  7056 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:14.171  1927  7088 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:14.171  1035  7080 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:14.171  1035  7080 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.171  1035  7080 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.171  1035  7080 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.171  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 14:42:14.171  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:14.171  7056  7056 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 14:42:14.171  1035  7080 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:14.171  1035  7080 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:14.171  7056  7056 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.171  1035  1377 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 14:42:14.172  1035  1377 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 14:42:14.172  7056  7056 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.172  1035  1377 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 14:42:14.172  1035  1377 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 14:42:14.172  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 14:42:14.172  1927  7088 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:14.172  1927  7088 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:14.172  1035  7080 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:14.172  1035  7080 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.172  1035  7080 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.172  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 14:42:14.172  1035  7080 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.172  7056  7056 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 14:42:14.172  1035  7080 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:14.172  1035  7080 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.172  1035  7080 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.172  1035  7080 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.173  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 14:42:14.173  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 14:42:14.173  1035  7080 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 14:42:14.173  1035  7080 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 14:42:14.173  1035  1375 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target,=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.173  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:14.173  7056  7056 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.173  1035  1377 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 14:42:14.173  1035  1377 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 14:42:14.173  1035  7080 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:14.173  1035  7080 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.173  1035  7080 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.173  1035  7080 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:14.174  1927  7088 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:14.174  1035  1377 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 14:42:14.174  1035  1377 D WifiNative-wlan0: doBoolean: SCAN
08-30 14:42:14.174  1035  1377 D WifiNative-wlan0: SCAN: returned false
08-30 14:42:14.174  1035  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=205922  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 14:42:14.175  1035  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=205923  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 14:42:14.176  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:14.176  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:14.177  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:14.177  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.177  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.177  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 14:42:14.178  1035  1377 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:42:14.179  1035  1377 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:42:14.180  1035  1377 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:42:14.181  1035  1377 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:42:14.182  1035  1377 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:42:14.183  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:42:14.183  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 14:42:14.186  7070  7070 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:42:14.186  7070  7070 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 14:42:14.189  7070  7070 D PhoneMonitor: Register our PhoneStateListener
08-30 14:42:14.200  7070  7070 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 14:42:14.201  7070  7070 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 14:42:14.219  7070  7070 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-30 14:42:14.220  7070  7070 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-30 14:42:14.221  7070  7070 D TelephonyAutoProfiling: [parse] Load xml
08-30 14:42:14.226  7070  7070 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 14:42:14.226  7070  7070 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 14:42:14.226  7070  7070 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 14:42:14.226  7070  7070 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 14:42:14.226  7070  7070 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 14:42:14.226  7070  7070 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 14:42:14.226  7070  7070 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 14:42:14.227  7070  7070 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 14:42:14.227  7070  7070 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 14:42:14.227  7070  7070 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 14:42:14.227  7070  7070 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 14:42:14.227  7070  7070 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 14:42:14.227  7070  7070 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 14:42:14.227  7070  7070 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 14:42:14.227  7070  7070 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 14:42:14.227  7070  7070 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 14:42:14.227  7070  7070 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-30 14:42:14.238  7070  7070 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-30 14:42:14.246  1035  1871 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7092 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 14:42:14.246  1035  1871 I ActivityManager: Killing 6115:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-30 14:42:14.303  1035  1889 W libprocessgroup: failed to open /acct/uid_10097/pid_6115/cgroup.procs: No such file or directory
,08-30 14:42:14.557  1035  1058 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7116 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-30 14:42:14.563  1035  1058 I ActivityManager: Killing 6571:com.lge.eula/1000 (adj 15): empty #17
08-30 14:42:14.611  1035  1980 W libprocessgroup: failed to open /acct/uid_1000/pid_6571/cgroup.procs: No such file or directory
,08-30 14:42:14.713  1035  2033 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7133 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 14:42:14.714  1035  2033 I ActivityManager: Killing 6590:com.lge.bnr/1000 (adj 15): empty #17
,08-30 14:42:14.742  7056  7056 E wpa_supplicant: USIM:  scard_init function
08-30 14:42:14.743  7056  7056 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-30 14:42:14.748  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 14:42:14.748  1035  7080 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 14:42:14.748  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 14:42:14.748  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-30 14:42:14.748  1035  7080 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 14:42:14.748  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 14:42:14.748  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 14:42:14.749  1035  1377 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 14:42:14.750  1035  1377 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 14:42:14.750  1035  1377 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 14:42:14.751  1035  1377 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 14:42:14.751  1035  1377 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 14:42:14.770  1035  1058 W libprocessgroup: failed to open /acct/uid_1000/pid_6590/cgroup.procs: No such file or directory
,08-30 14:42:14.777  1035  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=206524  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 14:42:14.786  1035  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=206534  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 14:42:14.790  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:14.792  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:14.793  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:14.794  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.794  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.794  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 14:42:14.796  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.797  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.797  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 14:42:14.798  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:42:14.798  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-30 14:42:14.814  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 14:42:14.814  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:14.817  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:14.831  7133  7133 I art     : Almond Protected OAT
,08-30 14:42:14.859  7056  7056 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 14:42:14.860  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 14:42:14.860  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 14:42:14.860  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 14:42:14.860  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 14:42:14.860  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:42:14.860  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:42:14.861  1035  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=206608  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 14:42:14.861  1035  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=206609  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 14:42:14.861  1035  1377 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206609
08-30 14:42:14.862  1035  1377 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206609
08-30 14:42:14.862  1035  1377 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206610
08-30 14:42:14.862  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206610
08-30 14:42:14.862  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 14:42:14.862  1035  1377 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206610
08-30 14:42:14.863  1035  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=206611  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 14:42:14.865  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:14.865  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:14.865  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.865  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.865  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 14:42:14.866  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:14.866  1035  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=206614  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 14:42:14.868  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:42:14.868  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:42:14.868  7056  7056 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 14:42:14.868  1035  1377 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:14.868  7056  7056 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 14:42:14.868  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation complete,d with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 14:42:14.868  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 14:42:14.868  1035  7080 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 14:42:14.868  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 14:42:14.868  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 14:42:14.868  1035  1377 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:14.868  1035  7080 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 14:42:14.869  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:42:14.869  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:42:14.870  1035  1377 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:14.871  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:14.871  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 14:42:14.871  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.871  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 14:42:14.871  1035  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:14.871  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:42:14.872  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 14:42:14.874  1035  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=206622  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 14:42:14.875  1035  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=206623  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 14:42:14.876  1035  1377 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206623
08-30 14:42:14.876  1035  1377 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206624
08-30 14:42:14.876  1035  1377 D WifiNative-wlan0: doString: [STATUS]
08-30 14:42:14.877  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:42:14.877  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:42:14.877  1035  1377 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 14:42:14.878  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:42:14.878  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 14:42:14.879  1035  1377 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 14:42:14.883  7133  7133 D WeatherApplication: removeAccount
,08-30 14:42:14.886  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:14.886  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:14.887  7133  7133 D WeatherApplication: Account.length = 0
08-30 14:42:14.887  7133  7133 E WeatherApplication: OPERATOR:OPEN
08-30 14:42:14.887  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:14.889  1035  1377 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 14:42:14.889  1035  1377 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 14:42:14.891  7133  7133 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:42:14
08-30 14:42:14.892  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.892  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.892  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 14:42:14.893  7133  7133 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 14:42:14.893  7133  7133 D Weather.Utils: 2 : All the weather widget is gone.
08-30 14:42:14.895  7133  7133 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 14:42:14.895  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.895  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:14.895  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 14:42:14.896  7133  7133 D WeatherAncestor: connectivity changed - connection : true
08-30 14:42:14.897  7133  7133 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-30 14:42:14.899  1035  1377 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-30 14:42:14.899  1035  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 14:42:14.899  1035  1434 D ConnectivityService: Got NetworkAgent Messenger
08-30 14:42:14.900  1035  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 14:42:14.900  1035  1434 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 14:42:14.900  1035  1434 D ConnectivityService: NetworkAgent connected
08-30 14:42:14.900  1035  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 14:42:14.900  1035  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 14:42:14.903  7133  7133 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 14:42:14.903  7133  7133 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 14:42:14.903  7133  7133 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-30 14:42:14.907  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:14.907  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:14.908  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 14:42:14.910  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:14.910  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:14.911  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:14.917  7133  7133 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 14:42:14.917  1035  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 14:42:14.917  1035  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 14:42:14.917  1035  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 14:42:14.917  7133  7133 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:42:14
08-30 14:42:14.917  1035  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 14:42:14.917  1035  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 14:42:14.924  1035  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-30 14:42:14.925   319   917 D CommandListener: Setting iface cfg
08-30 14:42:14.956  1035  1925 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7165 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 14:42:14.958  1035  1925 I ActivityManager: Killing 2109:com.lge.music/u0a34 (adj 15): empty #17
08-30 14:42:14.986   323   323 V AudioFlinger: 2109 died, releasing its sessions
08-30 14:42:14.986   323   323 V AudioFlinger:  pid 1837 @ 0
08-30 14:42:14.986   323   323 V AudioFlinger:  pid 3414 @ 1
08-30 14:42:14.986   323   323 V AudioFlinger:  pid 3414 @ 2
,08-30 14:42:15.013  1035  1377 E WifiStateMachine: Start Dhcp Watchdog 2
08-30 14:42:15.013  1035  7164 D DhcpStateMachine: StoppedState
08-30 14:42:15.013  1035  1890 W libprocessgroup: failed to open /acct/uid_10034/pid_2109/cgroup.procs: No such file or directory
,08-30 14:42:15.013  1035  7164 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 14:42:15.013  1035  7164 D DhcpStateMachine: WaitBeforeStartState
08-30 14:42:15.013  1035  1377 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=206761  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:42:15.014  1035  1377 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=206762  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:42:15.014  1035  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=206762  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:42:15.020  1035  1377 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=206768  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:42:15.021  1035  1377 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=206769  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:42:15.021  1035  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=206769  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:42:15.022  1035  1377 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:160923] from screen [on:0 period:-612847506] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 14:42:15.023  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-612847505] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 14:42:15.028  1035  1377 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 14:42:15.034  1035  1434 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-30 14:42:15.035  1035  1377 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:15.036  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:15.037  1035  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:15.037  1035  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:15.038  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:15.039  1035  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:15.040  1035  1434 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-30 14:42:15.040  1035  1377 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=103,0,0
,08-30 14:42:15.041  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=103,0,0
08-30 14:42:15.041  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 14:42:15.042  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 14:42:15.043  1035  1377 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 14:42:15.043  1035  1377 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 14:42:15.044  1035  1377 D WifiNative-wlan0: SET ps 0: returned true
08-30 14:42:15.044  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 14:42:15.044  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 14:42:15.045  1035  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 14:42:15.045  1035  1377 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 14:42:15.045  1035  1377 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 14:42:15.045  1035  1375 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@390f28b9 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:15.045  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@390f28b9 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:15.045  1035  7164 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:15.045  1035  7164 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 14:42:15.045  1035  1377 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 14:42:15.047   319   917 D CommandListener: Setting iface cfg
08-30 14:42:15.047   319   917 D CommandListener: Trying to bring up wlan0
08-30 14:42:15.047  1035  1377 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 14:42:15.048  1035  1377 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:15.049  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:15.049  1035  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:15.049  1035  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:15.050  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:15.050  1035  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:15.051  1035  1434 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 14:42:15.051  1035  1377 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 14:42:15.051  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,08-30 14:42:15.052  1035  1375 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:15.052  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:15.053  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 14:42:15.053  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 14:42:15.054  1035  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 14:42:15.054  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 14:42:15.054  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 14:42:15.055  1035  1377 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 14:42:15.055  1035  1377 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:42:15.060  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:42:15.060  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 14:42:15.061  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:15.070  1035  1377 D WifiNative-wlan0: SET ps 1: returned true
08-30 14:42:15.071  1035  1377 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 14:42:15.071  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 14:42:15.071  1035  1377 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-30 14:42:15.073  1035  1434 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 14:42:15.073  1035  1434 D ConnectivityService: ignoring duplicate network state non-change
08-30 14:42:15.075  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:15.075  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:15.075  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:15.075  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:15.075  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 14:42:15.076  1035  1434 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 14:42:15.076  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:15.077  1035  1434 D ConnectivityService: Adding iface wlan0 to network 101
08-30 14:42:15.079  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:15.079  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:15.079  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 14:42:15.082  1035  1377 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 14:42:15.084  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-30 14:42:15.089  1035  1375 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:15.090  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 14:42:15.090  1035  1375 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:15.091  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 14:42:15.093  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:15.093  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:15.093  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 14:42:15.094  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 14:42:15.094  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:15.094  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:15.094  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 14:42:15.097  1035  1434 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 14:42:15.097  1035  1434 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-30 14:42:15.097  1035  1434 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-30 14:42:15.098   319   917 E Netd    : netlink response contains error (File exists)
08-30 14:42:15.098  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:15.098  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:15.098  1035  1434 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 14:42:15.099  1035  1434 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 14:42:15.099  1035  1434 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-30 14:42:15.099  1035  1434 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-30 14:42:15.099  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:15.099  1035  1434 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 14:42:15.099  1035  1434 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 14:42:15.100  1035  1434 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 14:42:15.100  1035  1434 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 14:42:15.100  1035  1434 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 14:42:15.100  1035  1434 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:42:15.100  1035  1434 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 14:42:15.100  1035  1434 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:15.100  1035  7162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:15.100  1035  7162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 14:42:15.100  1035  7162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:15.100  1035  7162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 14:42:15.100  1035  1434 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 14:42:15.102  1035  1434 D ConnectivityService: currentScore = 0, newScore = 20
08-30 14:42:15.102  1035  1434 D ConnectivityService:    accepting network in place of null
08-30 14:42:15.102  1035  1434 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:15.102  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:15.103  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:15.103  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 14:42:15.103  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 14:42:15.103  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:15.103  1035  1434 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 ,wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 14:42:15.103  1035  1434 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 14:42:15.104  1035  1434 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 14:42:15.104  1035  1377 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:15.104  1035  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 14:42:15.105   319  7185 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 14:42:15.106  1035  1434 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:15.106  1035  1434 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 14:42:15.106  1035  1434 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 14:42:15.106  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 14:42:15.106  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:15.106  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 14:42:15.107  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 14:42:15.107  1035  1434 D ConnectivityService: validation of new default Network = false
08-30 14:42:15.107  1035  1434 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 14:42:15.107  1035  1434 D DSQN    : enableDataServiceNotify 
08-30 14:42:15.107  1035  1434 D DSQN    : start dsqn bin
08-30 14:42:15.107  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:15.107  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 14:42:15.107  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 14:42:15.108  1035  1377 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 14:42:15.109  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 14:42:15.109  1035  1377 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 14:42:15.109  1035  1377 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 14:42:15.110  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 14:42:15.112  1035  1377 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-30 14:42:15.131   281   436 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 14:42:15.131   281   436 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 14:42:15.131   281   436 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 14:42:15.131  7165  7187 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 14:42:15.132  1800  7188 I CheckinService: active receiver: enabled
08-30 14:42:15.135  1035  1374 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 14:42:15.137   281   436 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 14:42:15.137   281   436 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 14:42:15.137   281   436 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 14:42:15.137  7165  7187 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 14:42:15.152   281   436 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 14:42:15.152   281   436 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 14:42:15.152   281   436 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 14:42:15.152  7165  7190 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 14:42:15.155   281   436 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 14:42:15.155   281   436 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 14:42:15.155   281   436 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 14:42:15.155  7165  7190 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 14:42:15.199  1035  1434 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 14:42:15.199  1035  1434 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 14:42:15.199  1035  1434 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:42:15.199  1035  1434 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:42:15.200  1800  7188 I CheckinService: Preparing to send checkin request
08-30 14:42:15.200  1800  7188 I EventLogService: Accumulating logs since 1472560786220
08-30 14:42:15.201  1586  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 14:42:15.197  7192  7192 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:15.197  7192  7192 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:15.219  7192  7192 E DSQN    : DSQN ssw
,08-30 14:42:15.223  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 14:42:15.226  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:15.228  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:15.234  1800  7188 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 14:42:15.246  1035  7164 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 14:42:15.247  1035  7164 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 14:42:15.247  1035  7164 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-30 14:42:15.237  7199  7199 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:15.237  7199  7199 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:15.253  7199  7199 I dhcpcd  : version 5.5.6 starting
08-30 14:42:15.254  7199  7199 E dhcpcd  : get_duid: m
08-30 14:42:15.254  7199  7199 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 14:42:15.254  7199  7199 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-30 14:42:15.310  7199  7199 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 14:42:15.311  7199  7199 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 14:42:15.311  7199  7199 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 14:42:15.311  7199  7199 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 14:42:15.311  7199  7199 D dhcpcd  : wlan0: sending REQUEST (xid 0xdb6d984b), next in 4.89 seconds
,08-30 14:42:15.338  1035  1889 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7218 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-30 14:42:15.345  7199  7199 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-30 14:42:15.354   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 291us total 15.409ms
,08-30 14:42:15.368   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 276us total 12.674ms
,08-30 14:42:15.381   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 12.115ms
,08-30 14:42:15.388  7199  7199 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 14:42:15.388  7199  7199 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 14:42:15.388  7199  7199 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 14:42:15.388  7199  7199 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 14:42:15.388  7199  7199 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 14:42:15.389  7199  7199 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 14:42:15.389  7199  7199 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 14:42:15.389  7199  7199 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 14:42:15.398  7218  7218 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 14:42:15.398  7218  7218 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 14:42:15.430  7218  7218 I MultiDex: VM with version 2.1.0 has multidex support
08-30 14:42:15.431  7218  7218 I MultiDex: install
08-30 14:42:15.431  7218  7218 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 14:42:15.440  7165  7165 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-30 14:42:15.441  7218  7218 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-30 14:42:15.462  7165  7165 I LibraryLoader: Loading: webviewchromium
,08-30 14:42:15.465  7165  7165 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7221-7224)
08-30 14:42:15.465  7165  7165 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 14:42:15.479  7165  7165 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {375c3f3}
,08-30 14:42:15.491  7165  7165 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 14:42:15.491  7165  7165 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 14:42:15.499  7165  7165 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 14:42:15.499  7165  7165 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 14:42:15.509   323  2143 V AudioPolicyService: registerClient() client 0xb1003760, uid 10093
08-30 14:42:15.510  7165  7254 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 14:42:15.510  7165  7165 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 14:42:15.511  7165  7165 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 14:42:15.511  7165  7165 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-30 14:42:15.532  7165  7165 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 14:42:15.532  7165  7165 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 14:42:15.532  7165  7165 I Adreno-EGL: Build Date: 12/12/14 금
08-30 14:42:15.532  7165  7165 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 14:42:15.532  7165  7165 I Adreno-EGL: Remote Branch: 
08-30 14:42:15.532  7165  7165 I Adreno-EGL: Local Patches: 
08-30 14:42:15.532  7165  7165 I Adreno-EGL: Reconstruct Branch: 
,08-30 14:42:15.649  1035  7164 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-30 14:42:15.651  1035  7164 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 14:42:15.652  1035  7164 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 14:42:15.652  1035  7164 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 14:42:15.652  1035  7164 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 14:42:15.652  1035  7164 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 14:42:15.652  1035  7164 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 14:42:15.652  1035  7164 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-30 14:42:15.653  1035  7164 D DhcpStateMachine: RunningState
08-30 14:42:15.693  7218  7235 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:42:15.693  7218  7235 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:42:15.711  1035  1962 I art     : Explicit concurrent mark sweep GC freed 101980(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.738ms total 96.917ms
08-30 14:42:15.712  7165  7165 I NSApplication: Starting up...
,08-30 14:42:15.763  1035  1980 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7275 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-30 14:42:15.764  1035  1980 I ActivityManager: Killing 6041:com.android.vending/u0a44 (adj 15): empty #17
,08-30 14:42:15.845  7292  7292 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 14:42:15.854  1035  1057 W libprocessgroup: failed to open /acct/uid_10044/pid_6041/cgroup.procs: No such file or directory
,08-30 14:42:15.900  7275  7275 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 14:42:15.909  7292  7292 I dex2oat : dex2oat took 63.571ms (threads: 4)
08-30 14:42:15.925  7218  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 14:42:15.925  7218  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 14:42:15.925  7218  7235 I Adreno-EGL: Build Date: 12/12/14 금
08-30 14:42:15.925  7218  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 14:42:15.925  7218  7235 I Adreno-EGL: Remote Branch: 
08-30 14:42:15.925  7218  7235 I Adreno-EGL: Local Patches: 
08-30 14:42:15.925  7218  7235 I Adreno-EGL: Reconstruct Branch: 
,08-30 14:42:16.032  7218  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 14:42:16.032  7218  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 14:42:16.032  7218  7235 I Adreno-EGL: Build Date: 12/12/14 금
08-30 14:42:16.032  7218  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 14:42:16.032  7218  7235 I Adreno-EGL: Remote Branch: 
08-30 14:42:16.032  7218  7235 I Adreno-EGL: Local Patches: 
08-30 14:42:16.032  7218  7235 I Adreno-EGL: Reconstruct Branch: 
,08-30 14:42:16.053  1035  1722 D WifiServiceImplEx: setWifiEnabled: false pid=6717, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 14:42:16.053  1035  1722 D WifiService: setWifiEnabled: false pid=6717, uid=10118
08-30 14:42:16.053  1035  1722 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:42:16.067  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:42:16.067  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 14:42:16.067  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 14:42:16.067  1035  1377 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-30 14:42:16.068  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 14:42:16.069  1035  1377 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 14:42:16.070  1035  1377 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 14:42:16.071  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 14:42:16.071  1035  1377 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 14:42:16.071  1035  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 14:42:16.071  1035  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 14:42:16.072  1035  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 14:42:16.072  1035  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 14:42:16.081  1035  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 14:42:16.081  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 14:42:16.081  1035  1375 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:16.081  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 14:42:16.081  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 14:42:16.082  1035  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 14:42:16.082  1035  1377 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:42:16.083  1035  1377 D WifiNative-wlan0: SET ps 1: returned true
08-30 14:42:16.084   319   917 D CommandListener: Clearing all IP addresses on wlan0
08-30 14:42:16.084  1035  7164 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:16.087  7218  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 14:42:16.087  7218  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 14:42:16.087  7218  7235 I Adreno-EGL: Build Date: 12/12/14 금
08-30 14:42:16.087  7218  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 14:42:16.087  7218  7235 I Adreno-EGL: Remote Branch: 
08-30 14:42:16.087  7218  7235 I Adreno-EGL: Local Patches: 
08-30 14:42:16.087  7218  7235 I Adreno-EGL: Reconstruct Branch: 
08-30 14:42:16.119  1035  1375 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:16.119  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:16.119  1035  1375 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@293a1e46
08-30 14:42:16.119  1035  1375 D LGWifiP2pService: P2pDisablingState
08-30 14:42:16.119  1035  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:16.119  1035  1375 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:16.119  1035  1375 D LGWifiP2pService: p2p socket connection lost
08-30 14:42:16.119  1035  1375 D LGWifiP2pService: P2pDisabledState
08-30 14:42:16.120  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:16.120  1035  1434 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 14:42:16.120  1035  1434 D ConnectivityService: ignoring duplicate network state non-change
08-30 14:42:16.120  1035  1434 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-30 14:42:16.130  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 14:42:16.130  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:16.130  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:16.130  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:42:16.131  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 14:42:16.131  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:16.131  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:16.131  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:42:16.131  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 14:42:16.131  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-30 14:42:16.131  1035  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:16.131  1035  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:16.132  1035  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:16.132  1035  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:16.132  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:16.133  1035  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:16.133  1035  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 14:42:16.134  1035  1375 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:16.134  1035  1375 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 14:42:16.135  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 14:42:16.135  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 14:42:16.135  1035  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 14:42:16.136  1035  1377 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:42:16.136  1035  1377 D WifiNative-wlan0: SET ps 1: returned true
08-30 14:42:16.138  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:16.138  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 14:42:16.138  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:16.139  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 14:42:16.139  1927  1927 D WfdsService: WifiP2pState is changed : false
08-30 14:42:16.139  1927  2286 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 14:42:16.139  1927  2286 D WfdsService: Set the WFDS Monitor: false
08-30 14:42:16.141  1927  2286 D WfdsMonitor: WFDS Monitor is stopped
08-30 14:42:16.141  1927  2286 D WfdsService: STATE : WfdsDisabledState - enter
08-30 14:42:16.141  1927  7088 D CtrlSupplicant: Received on exit socket, terminate
08-30 14:42:16.141  1927  7088 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 14:42:16.141  1927  7088 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 14:42:16.141  1927  7088 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 14:42:16.142  1927  2288 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 14:42:16.142  1927  2286 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 14:42:16.142  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:16.144  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:16.144  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:16.145  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 14:42:16.161  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 14:42:16.162  6401  6842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 14:42:16.169   319   917 D CommandListener: Clearing all IP addresses on wlan0
,08-30 14:42:16.169  1035  1434 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 14:42:16.170  1035  1434 D DSQN    : disableDataServiceNotify
08-30 14:42:16.170  1035  1434 D DSQN    : stop dsqn bin
08-30 14:42:16.172  1035  1377 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 14:42:16.172  1035  1377 D WifiNative-p2p0: TERMINATE: returned true
08-30 14:42:16.173  1035  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:42:16.173  1035  1377 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:42:16.173  1035  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 14:42:16.173  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 14:42:16.174  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 14:42:16.174  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:16.175  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:16.177  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:16.177  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:16.177  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:42:16.178  1035  1377 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 14:42:16.181  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 14:42:16.182  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:16.182  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:16.182  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:16.182  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:16.182  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:42:16.182  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:42:16.182  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:16.182  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:16.182  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:42:16.182  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:16.182  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:42:16.183  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:16.183  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:16.183  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:16.183  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:16.183  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:42:16.183  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:42:16.183  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:16.183  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:16.183  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:42:16.183  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will retur,n stored value
08-30 14:42:16.183  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:42:16.185  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 14:42:16.185  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:42:16.185  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 14:42:16.188  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:16.188  2195  2195 W GCM     : ACTIVE NETWORK NOT CONNECTED
08-30 14:42:16.192  1035  1925 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-30 14:42:16.193   319  7314 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 14:42:16.194  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 14:42:16.196  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:16.198  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 14:42:16.198  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:16.198  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 14:42:16.198  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 14:42:16.202  6994  6994 I AppUp4:CustModeStarterReceiver: onReceive
08-30 14:42:16.204  6994  6994 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26998b68
08-30 14:42:16.204  6994  6994 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 14:42:16.204  6994  6994 D AppUp4:CustFacade: isPhone : true
08-30 14:42:16.204  6994  6994 D AppUp4:CustModeStarterReceiver: begin check event
08-30 14:42:16.204  6994  6994 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 14:42:16.206  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:16.206  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:42:16.207  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:42:16.209  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 14:42:16.212  4330  7315 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 14:42:16.214  7031  7031 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 14:42:16.218  4330  7316 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:16.218  4330  7316 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 14:42:16.228  1035  1434 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 14:42:16.228  1035  1434 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:16.228  1035  1434 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:42:16.228  1035  1434 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:42:16.228  1035  1434 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 14:42:16.228  1035  1434 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 14:42:16.228  1035  1434 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 14:42:16.228  1035  1434 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 14:42:16.229  1035  1434 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:16.229  1035  1434 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 14:42:16.229  1035  1434 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:42:16.229  1035  1434 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:16.230  1035  1434 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:16.230  1035  1434 D NetworkManagementService: Removing idletimer
08-30 14:42:16.230  1035  1434 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:16.230  1035  1434 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-30 14:42:16.230  1586  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 14:42:16.231  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:16.231  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 14:42:16.231  1035  1377 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:16.231  1035  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 14:42:16.231  1035  1374 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 14:42:16.231  1035  1374 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 14:42:16.231  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 14:42:16.232  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 14:42:16.232  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 14:42:16.232  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 14:42:16.232  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 14:42:16.232  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 14:42:16.232  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 14:42:16.232  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 14:42:16.232  7031  7317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:16.242  6918  7319 W FormManager: Network not available. Please check & try again.
08-30 14:42:16.244  3414  3414 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 14:42:16.244  3414  3414 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:16.244  3414  3414 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 14:42:16.246  7070  7070 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 14:42:16.246  7070  7070 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 14:42:16.251  7056  7056 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 14:42:16.251  7056  7056 I wpa_supplicant: monitor socket send errors count : 1
,08-30 14:42:16.251  7056  7056 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-4\x00 that cannot receive messages
08-30 14:42:16.252  6918  7320 V FormManager: Network unavailable.
08-30 14:42:16.252  1035  7080 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 14:42:16.252  1035  7080 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 14:42:16.260  6918  7320 V FormManager: Network unavailable.
08-30 14:42:16.260  7133  7133 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:42:16
,08-30 14:42:16.262  7133  7133 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 14:42:16.262  7133  7133 D Weather.Utils: 2 : All the weather widget is gone.
08-30 14:42:16.262  7133  7133 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 14:42:16.263  7133  7133 D WeatherAncestor: connectivity changed - connection : true
08-30 14:42:16.263  7133  7133 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@e82d426
08-30 14:42:16.263  7133  7133 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 14:42:16.263  7133  7133 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 14:42:16.263  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 14:42:16.263  7133  7133 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 14:42:16.263  7133  7133 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 14:42:16.263  7133  7133 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:42:16
08-30 14:42:16.264  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:16.264  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:16.273  7056  7056 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 14:42:16.273  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 14:42:16.273  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 14:42:16.273  1035  7080 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 14:42:16.273  1035  7080 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 14:42:16.273  7056  7056 W wpa_supplicant: USIM:  scard_deinit function
08-30 14:42:16.274  1035  1377 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=208021
08-30 14:42:16.274  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:42:16.274  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:42:16.274  1035  1377 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=208022
08-30 14:42:16.275  1035  1377 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=208022  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 14:42:16.275  1035  1377 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=208023  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-30 14:42:16.275  1035  1117 D Tethering: InitialState.processMessage what=4
08-30 14:42:16.277   319  7328 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 14:42:16.277  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 14:42:16.277  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 14:42:16.278  1035  1377 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:16.278  1035  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:16.279  1800  7188 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-30 14:42:16.287  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 14:42:16.287  6823  6823 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 14:42:16.287  6823  6823 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 14:42:16.287  6823  6823 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 14:42:16.287  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 14:42:16.287  6823  6823 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 14:42:16.287  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 14:42:16.287  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 14:42:16.287  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 14:42:16.288  6823  6823 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 14:42:16.288  6823  6823 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 14:42:16.291  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 14:42:16.291  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:16.292  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:16.297  1800  7188 I CheckinService: active receiver: disabled
08-30 14:42:16.297  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:42:16.299  1035  7164 D DhcpStateMachine: StoppedState
08-30 14:42:16.299  1035  7164 D DhcpStateMachine: StoppedState{ when=-163ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 14:42:16.307  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 14:42:16.308  1035  1377 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 14:42:16.308  1035  1377 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 14:42:16.311  6918  7330 W FormManager: Network not available. Please check & try again.
,08-30 14:42:16.312  6918  7331 V FormManager: Network unavailable.
08-30 14:42:16.314  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:16.314  6918  7331 V FormManager: Network unavailable.
08-30 14:42:16.327  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:42:16.329  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 14:42:16.332  6918  7333 W FormManager: Network not available. Please check & try again.
08-30 14:42:16.334  6918  7334 V FormManager: Network unavailable.
08-30 14:42:16.335  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:16.351  7056  7056 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 14:42:16.351  1035  7080 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 14:42:16.351  1035  7080 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 14:42:16.351  1035  7080 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 14:42:16.352  1035  1377 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-30 14:42:16.352  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 14:42:16.353  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:42:16.355  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:42:16.357  6918  7334 V FormManager: Network unavailable.
08-30 14:42:16.357  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 14:42:16.364  4330  7335 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 14:42:16.365  4330  7336 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 14:42:16.365  4330  7336 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 14:42:16.394  1035  1871 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7337 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 14:42:16.453  1035  1377 D WifiOffDelayIfNotUsed: stopMonitoring
,08-30 14:42:16.453  1035  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:42:16.453  1035  1377 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:42:16.453  1035  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 14:42:16.454  1927  1927 D WfdsService: Supplicant Connection state is changed : false
,08-30 14:42:16.455  1927  2286 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 14:42:16.455  1927  2286 D WfdsService: Set the WFDS Monitor: false
08-30 14:42:16.455  1927  2286 D WfdsMonitor: WFDS Monitor is stopped
08-30 14:42:16.455  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:16.456  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 14:42:16.457  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 14:42:16.458  1035  1421 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 14:42:16.458  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:16.458  1035  1421 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 14:42:16.458  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:16.458  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:16.458  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:16.458  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:42:16.458  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:42:16.458  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:16.458  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:16.458  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:42:16.458  2492  2492 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:16.459  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:16.459  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:16.459  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:16.459  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:16.459  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:42:16.459  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:42:16.459  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:16.459  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:16.459  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:42:16.484  7337  7337 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 14:42:16.484  7337  7337 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 14:42:16.491  7337  7337 V [BNRBootReceiver]: Boot Receiver Return
,08-30 14:42:16.494  7337  7337 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 14:42:16.494  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:16.506  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:16.511  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:16.523  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:16.523  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:16.525  6874  6874 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 14:42:16.532  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 14:42:16.536  6823  6823 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 14:42:16.542  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:42:16.553  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:16.557  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:16.566  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:16.566  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:16.568  6874  6874 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 14:42:16.573  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:42:16.583  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:16.587  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:16.593  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:16.593  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:16.594  6874  6874 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:42:16.598  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:42:16.606  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:16.614  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:16.621  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:16.621  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:16.622  6874  6874 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 14:42:16.628  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:42:16.637  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:16.646  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:16.653  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 14:42:16.654  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:16.655  6874  6874 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:42:16.659  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:42:16.666  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:16.676  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 14:42:16.684  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:16.684  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:16.685  6874  6874 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 14:42:16.689  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:16.699  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:16.707  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:16.714  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 14:42:16.715  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:16.715  6874  6874 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:42:16.720  1035  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=462632365, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
08-30 14:42:16.724  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:16.738  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:16.747  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:16.756  2580  2580 D [Concierge]Service: onStartCommand(). Type : 9
,08-30 14:42:16.761  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:16.762  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:16.771  6874  6874 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 14:42:16.777  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:16.789  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:16.797  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 14:42:16.805  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:16.806  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:16.806  6874  6874 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 14:42:16.811  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:16.815  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 14:42:16.823  1035  1430 D WifiService: New client listening to asynchronous messages
,08-30 14:42:16.823  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:42:16.828  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:42:16.833  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:16.840  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:16.841  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:16.842  6874  6874 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 14:42:16.843  6874  6874 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 14:42:16.844  6874  6874 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 14:42:16.849  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:16.854  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 14:42:16.855  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:42:16.860  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:42:16.867  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 14:42:16.876  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:16.877  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:16.878  6874  6874 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 14:42:16.879  6874  6874 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 14:42:16.880  6874  6874 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 14:42:16.884  1035  1926 I ActivityManager: Killing 6804:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-30 14:42:16.913  1035  1925 W libprocessgroup: failed to open /acct/uid_10037/pid_6804/cgroup.procs: No such file or directory
,08-30 14:42:16.919  2195  2195 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-30 14:42:16.930  2195  2195 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-30 14:42:16.931  2195  2195 D c       : Getting all permits...
08-30 14:42:16.931  2195  2195 D a       : Opening database...
08-30 14:42:16.936  2195  2195 D a       : Opening database auth.proximity.permit_store...
08-30 14:42:16.937  2195  2195 D a       : Closing database...
08-30 14:42:16.952  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:42:16.957  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 14:42:16.957  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:42:16.957  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:42:16.962  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:16.971  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:16.983  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 14:42:16.984  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:16.988  6874  6874 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 14:42:16.993  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:16.999  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 14:42:16.999  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:42:16.999  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 14:42:17.007  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:17.018  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:17.028  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 14:42:17.029  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:17.032  6874  6874 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 14:42:17.037  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:17.042  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-30 14:42:17.042  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:42:17.042  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 14:42:17.048  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:42:17.054  6614  6983 D UEI.SmartControl: Internal timer expired: 2
08-30 14:42:17.054  6614  6983 D UEI.SmartControl: unbind internal service
,08-30 14:42:17.057  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 14:42:17.065  6874  6874 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:17.065  6874  6874 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:17.068  6874  6874 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 14:42:17.077  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:42:17.080  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 14:42:17.091  6918  7362 W FormManager: Network not available. Please check & try again.
08-30 14:42:17.094  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:17.105  6918  7363 V FormManager: Network unavailable.
,08-30 14:42:17.116  6918  7363 V FormManager: Network unavailable.
,08-30 14:42:17.120  2195  2195 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-30 14:42:17.145  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 14:42:17.145  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 14:42:17.148  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:42:17.151  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:42:17.161  4330  7364 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 14:42:17.166  6843  6843 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 14:42:17.167  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:42:17.167  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:42:17.173  4330  7366 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 14:42:17.173  4330  7366 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 14:42:17.174  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 14:42:17.182  6918  7367 W FormManager: Network not available. Please check & try again.
08-30 14:42:17.185  6918  7368 V FormManager: Network unavailable.
08-30 14:42:17.187  6918  7368 V FormManager: Network unavailable.
,08-30 14:42:17.190  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:17.199  6614  6977 D serial_port: close(fd = 24)
,08-30 14:42:17.203  6614  6977 I UEI.SmartControl: Serial port is closed.
08-30 14:42:17.211  6874  6874 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-30 14:42:17.211  6874  6874 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:144
,08-30 14:42:17.213  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=462632365 [*alarm*], flags=0x0
,08-30 14:42:18.037  1035  1377 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-612844491] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 14:42:18.039  1035  1377 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-612844489] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 14:42:18.107  1035  1434 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:42:18.124  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,08-30 14:42:18.132  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:18.133  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:18.137  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:42:18.142  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 14:42:18.144  6401  6842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 14:42:18.155  5290  5290 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 14:42:18.171  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:42:18.193  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 14:42:18.193  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:18.193  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 14:42:18.193  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 14:42:18.197  6994  6994 I AppUp4:CustModeStarterReceiver: onReceive
08-30 14:42:18.201  6994  6994 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26998b68
08-30 14:42:18.201  6994  6994 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 14:42:18.202  6994  6994 D AppUp4:CustFacade: isPhone : true
08-30 14:42:18.202  6994  6994 D AppUp4:CustModeStarterReceiver: begin check event
08-30 14:42:18.202  6994  6994 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 14:42:18.207  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:18.207  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:42:18.209  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 14:42:18.214  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:42:18.222  7031  7031 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 14:42:18.250  7031  7383 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 14:42:18.252  4330  7384 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 14:42:18.265  4330  7387 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:42:18.266  4330  7387 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 14:42:18.278  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:18.286  6918  7385 W FormManager: Network not available. Please check & try again.
,08-30 14:42:18.287  3414  3414 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 14:42:18.288  3414  3414 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:18.288  6918  7386 V FormManager: Network unavailable.
08-30 14:42:18.288  3414  3414 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 14:42:18.288  3414  3414 D PhoneState: setPdpRejectCasuse : false
08-30 14:42:18.292  7070  7070 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 14:42:18.292  7070  7070 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 14:42:18.297  6918  7386 V FormManager: Network unavailable.
,08-30 14:42:18.306  7133  7133 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:42:18
,08-30 14:42:18.307  7133  7133 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 14:42:18.307  7133  7133 D Weather.Utils: 2 : All the weather widget is gone.
08-30 14:42:18.308  7133  7133 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 14:42:18.308  7133  7133 D WeatherAncestor: connectivity changed - connection : true
08-30 14:42:18.308  7133  7133 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@e82d426
08-30 14:42:18.309  7133  7133 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 14:42:18.309  7133  7133 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 14:42:18.310  7133  7133 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 14:42:18.310  7133  7133 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 14:42:18.310  7133  7133 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:42:18
08-30 14:42:19.072  1035  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:19.073  1035  1980 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 14:42:19.112  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:42:19.113  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 14:42:19.113  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 14:42:19.114  1035  1117 D BluetoothManagerService: Message: 1
08-30 14:42:19.114  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 14:42:19.148  1035  1117 D BluetoothManagerService: Message: 20
08-30 14:42:19.148  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d454135:true
,08-30 14:42:19.152  6937  6937 D BluetoothAdapterState: make
08-30 14:42:19.157  6937  6937 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 14:42:19.157  6937  6937 I bluedroid-qcom: init
08-30 14:42:19.158  6937  7415 I BluetoothAdapterState: Entering OffState
08-30 14:42:19.158  6937  6937 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 14:42:19.159  6937  6937 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 14:42:19.159  6937  6937 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 14:42:19.159  6937  6937 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 14:42:19.159  6937  6937 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 14:42:19.161  6937  6937 I bluedroid-qcom: get_profile_interface socket
08-30 14:42:19.161  6937  6937 I bluedroid-qcom: get_profile_interface map_client
,08-30 14:42:19.165  6937  7419 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 14:42:19.169  6937  7419 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 14:42:19.157  7418  7418 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:19.167  7418  7418 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:19.178  7418  7418 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 14:42:19.178  7418  7418 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 14:42:19.178  7418  7418 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-30 14:42:19.183  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 14:42:19.183  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 14:42:19.185  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 14:42:19.186  1035  1117 D BluetoothManagerService: Message: 40
08-30 14:42:19.186  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 14:42:19.187  6937  6955 I bluedroid-qcom: config_hci_snoop_log
08-30 14:42:19.188  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 14:42:19.188  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 14:42:19.189  7418  7418 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 14:42:19.196  6937  7415 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-30 14:42:19.199  6937  7419 D BluetoothAdapterProperties: Name is: G3
08-30 14:42:19.199  6937  7415 D BluetoothAdapterProperties: Setting state to 11
08-30 14:42:19.200  7418  7418 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
,08-30 14:42:19.200  7418  7418 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 14:42:19.202  6937  7415 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 14:42:19.203  1035  1117 D BluetoothManagerService: Message: 60
08-30 14:42:19.203  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 14:42:19.203  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 14:42:19.207  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:19.208  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-30 14:42:19.213  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:19.214  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:19.218  6823  6823 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 14:42:19.224  6937  6937 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 14:42:19.225  6937  6937 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:19.225  6937  6937 V BluetoothPbapReceiver: ***********state = 11
,08-30 14:42:19.233  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:42:19.239  1035  1434 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:42:19.248  6937  7415 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 14:42:19.304  1035  1926 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7436 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-30 14:42:19.307  1035  1434 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:42:19.311  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-30 14:42:19.311  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-30 14:42:19.317  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:19.319  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:19.320  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:19.324  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 14:42:19.325  6937  7415 D BluetoothBondStateMachine: make
08-30 14:42:19.326  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:19.327  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:19.329  6937  7415 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:19.330  6937  7415 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 14:42:19.330  6937  7415 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:19.330  6937  7415 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 14:42:19.332  6937  7451 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 14:42:19.333  6937  7415 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 14:42:19.336  5290  5290 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 14:42:19.337  6937  7415 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:42:19.338  6401  6842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 14:42:19.344  5290  5290 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 14:42:19.349  6937  7415 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:42:19.350  6937  6937 D HeadsetService: Received start request. Starting profile...
08-30 14:42:19.351  6937  6937 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 14:42:19.351  6937  6937 D LGBluetoothHfpAdapter: Version 1.6
08-30 14:42:19.354  6937  6937 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 14:42:19.351  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:19.355  6937  6937 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 14:42:19.355  6937  6937 D HeadsetStateMachine: make
08-30 14:42:19.363  6937  7415 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:42:19.368  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:19.379  6937  7415 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 14:42:19.381  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:19.381  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:19.383  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 14:42:19.383  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:19.383  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 14:42:19.383  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 14:42:19.385  6994  6994 I AppUp4:CustModeStarterReceiver: onReceive
08-30 14:42:19.386  6937  7415 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:42:19.389  6937  6937 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:42:19.389  6937  6937 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 14:42:19.391  6937  7415 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 14:42:19.391  6994  6994 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26998b68
08-30 14:42:19.392  6994  6994 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 14:42:19.392  6994  6994 D AppUp4:CustFacade: isPhone : true
08-30 14:42:19.393  6937  6937 D HeadsetStateMachine: max_hf_connections = 1
08-30 14:42:19.393  6937  6937 I bluedroid-qcom: get_profile_interface handsfree
08-30 14:42:19.393  6994  6994 D AppUp4:CustModeStarterReceiver: begin check event
08-30 14:42:19.394  6994  6994 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 14:42:19.394  6937  6937 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 14:42:19.397   323  1383 V AudioPolicyService: registerClient() client 0xb1003460, uid 1002
08-30 14:42:19.397   323   323 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 14:42:19.397   323   323 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 14:42:19.397   323   323 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 14:42:19.397  6937  6937 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 14:42:19.398   323  2143 V AudioFlinger: registerClient() client 0xb5581610, pid 6937
08-30 14:42:19.398  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:19.398   323  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:42:19.398   323  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:42:19.398  6937  6937 V ToneGenerator: Create Track: 0xb4928080
08-30 14:42:19.398  6937  6937 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 14:42:19.398  6937  6937 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 14:42:19.398   323  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 14:42:19.398   323  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 14:42:19.398   323  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 14:42:19.398   323  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 14:42:19.398  1035  1962 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:42:19.398  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:42:19.398  1035  1962 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:42:19.398  1586  3090 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:42:19.399  1586  3090 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:42:19.399  1837  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:42:19.399  1837  1852 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:42:19.399  3414  3431 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:42:19.399  3414  3431 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:42:19.399  6937  6937 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 14:42:19.399   323  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:42:19.399   323  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:42:19.399  6937  6955 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:42:19.399  6937  6955 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 14:42:19.400  1035  1889 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:42:19.400  1035  1889 V AudioSystem: ioConfigChanged() opening already existing output! 4,
08-30 14:42:19.400  6937  6955 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:42:19.400  6937  6955 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 14:42:19.400   323  2144 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 14:42:19.400  1586  2084 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:42:19.400  1586  2084 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:42:19.400   323  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 14:42:19.400   323  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 14:42:19.400   323  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 14:42:19.400   323  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 14:42:19.400  6937  6937 V AudioSystem: getLatency() output 2, latency 50
08-30 14:42:19.400  6937  6937 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 14:42:19.400  6937  6937 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 14:42:19.401   323  2143 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 14:42:19.401   323  2143 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 14:42:19.401   323  2143 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 14:42:19.401   323  2143 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 14:42:19.401   323  2143 V AudioFlinger: createTrack() lSessionId: 20
08-30 14:42:19.401  1837  1853 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:42:19.401  1837  1853 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:42:19.401  3414  3429 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:42:19.401  3414  3429 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:42:19.401  6937  6937 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 14:42:19.401  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:42:19.402   323  2144 V AudioFlinger: acquiring 20 from 6937, for 6937
08-30 14:42:19.402   323  2144 V AudioFlinger:  added new entry for 20
08-30 14:42:19.402  6937  6937 V ToneGenerator: ToneGenerator INIT OK, time: 211161
08-30 14:42:19.402  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:19.403  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:19.404  6937  7415 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:42:19.403  6937  7454 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 14:42:19.404  6937  7454 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 14:42:19.404  6937  6937 D A2dpService: Received start request. Starting profile...
08-30 14:42:19.405  6937  6937 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 14:42:19.406  6937  6937 V Avrcp   : make
08-30 14:42:19.406  6937  6937 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 14:42:19.406  6937  6937 I bluedroid-qcom: get_profile_interface avrcp
08-30 14:42:19.406  6937  7454 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 14:42:19.407  6937  7454 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 14:42:19.408   323  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6937
08-30 14:42:19.408   323  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 14:42:19.408   323  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 14:42:19.408   323  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 14:42:19.408   323  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 14:42:19.408   323  1383 V voice   : voice_set_parameters: exit with code(0)
08-30 14:42:19.408   323  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 14:42:19.409   323  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 14:42:19.409   323  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 14:42:19.409   323  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 14:42:19.409   323  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 14:42:19.409   323  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 14:42:19.409  6937  7454 V ToneGenerator: ToneGenerator destructor
08-30 14:42:19.409  6937  7454 V ToneGenerator: stopTone
08-30 14:42:19.409  6937  7454 V ToneGenerator: Delete Track: 0xb4928080
08-30 14:42:19.410  6937  7454 V AudioTrack: ~AudioTrack, releasing session id from 6937 on behalf of 6937
08-30 14:42:19.410   323  2143 V AudioFlinger: releasing 20 from 6937 for 6937
08-30 14:42:19.410   323  2143 V AudioFlinger:  decremented refcount to 0
08-30 14:42:19.410   323  2143 V AudioFlinger: purging stale effects
08-30 14:42:19.410   323  2143 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 14:42:19.410   323  2143 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 14:42:19.410   323  1272 V AudioPolicyService: AudioCommandThread() waking up
08-30 14:42:19.410   323  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 14:42:19.410   323  1272 V AudioPolicyManager: releaseOutput() 2
08-30 14:42:19.410   323  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 14:42:19.410   323  2143 V AudioFlinger: PlaybackThread::Track destructor
08-30 14:42:19.410   323  2143 V AudioFlinger: removeClient_l() pid 6937, calling pid 323
08-30 14:42:19.412  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:42:19.416  6937  6937 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 14:42:19.417  6937  7415 V LGMDMManager: Create singleton instance
08-30 14:42:19.418  6937  6937 E AudioManager: No RCC entry present to update
08-30 14:42:19.418  6937  6937 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 14:42:19.419  4330  7458 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 14:42:19.420  6937  6937 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 14:42:19.421  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 14:42:19.421  6937  6937 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 14:42:19.423  7031  7031 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 14:42:19.424  6937  7415 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 14:42:19.424  4330  7459 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:19.424  4330  7459 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 14:42:19.429  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 14:42:19.483  7436  7436 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 14:42:19.485  7436  7436 W LG Account v2.2: No ProfileInfo entries
08-30 14:42:19.485  7436  7436 I LG Account v2.2: isEnabled: false
08-30 14:42:19.486  7436  7436 I Feature : [Lifetracker]ver: 4.21.112(40211120)
,08-30 14:42:19.486  7436  7436 I Feature : [Lifetracker]Country: EU
08-30 14:42:19.486  7436  7436 I Feature : [Lifetracker]Operator: OPEN
08-30 14:42:19.486  7436  7436 I Feature : [Lifetracker]Ranking support: false
08-30 14:42:19.487  7436  7436 I Feature : [Lifetracker]Comfort support: false
08-30 14:42:19.487  3414  3414 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 14:42:19.487  3414  3414 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:19.487  7436  7436 I Feature : [Lifetracker]Accessory: true
08-30 14:42:19.487  3414  3414 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 14:42:19.487  7436  7436 I Feature : [Lifetracker]Health device: true
08-30 14:42:19.487  7436  7436 I Feature : [Lifetracker]Extra Pedometer: false
08-30 14:42:19.487  7436  7436 I Feature : [Lifetracker]Blood glucose device: false
08-30 14:42:19.487  7436  7436 I Feature : [Lifetracker]Device Number: 3
08-30 14:42:19.490  7070  7070 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 14:42:19.490  7070  7070 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 14:42:19.505  6918  7466 W FormManager: Network not available. Please check & try again.
,08-30 14:42:19.507  7031  7464 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:19.510  6918  7467 V FormManager: Network unavailable.
08-30 14:42:19.516  6823  6823 D BluetoothPermissionRequest: onReceive
,08-30 14:42:19.517  6918  7467 V FormManager: Network unavailable.
08-30 14:42:19.519  7133  7133 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:42:19
08-30 14:42:19.520  7133  7133 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 14:42:19.521  7133  7133 D Weather.Utils: 2 : All the weather widget is gone.
08-30 14:42:19.521  7133  7133 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 14:42:19.522  7133  7133 D WeatherAncestor: connectivity changed - connection : true
08-30 14:42:19.522  7133  7133 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@e82d426
08-30 14:42:19.522  6823  6823 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 14:42:19.524  7133  7133 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 14:42:19.524  7133  7133 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 14:42:19.524  7133  7133 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 14:42:19.524  7133  7133 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 14:42:19.524  7133  7133 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:42:19
08-30 14:42:19.532  1035  1944 V SIM_STK : Menu title from STK is T-Mobile
08-30 14:42:19.532  1035  1944 V SIM_STK : Menu title from STK is T-Mobile
,08-30 14:42:19.545  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 14:42:19.547  6401  6842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 14:42:19.557  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:42:19.563  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 14:42:19.563  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:19.564  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 14:42:19.564  6994  6994 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 14:42:19.564  6994  6994 I AppUp4:CustModeStarterReceiver: onReceive
08-30 14:42:19.567  6994  6994 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26998b68
08-30 14:42:19.567  6994  6994 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 14:42:19.567  6994  6994 D AppUp4:CustFacade: isPhone : true
08-30 14:42:19.567  6994  6994 D AppUp4:CustModeStarterReceiver: begin check event
08-30 14:42:19.567  6994  6994 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 14:42:19.569  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:42:19.569  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:42:19.571  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:42:19.573  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:42:19.575  4330  7469 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 14:42:19.576  4330  7470 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:19.576  4330  7470 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 14:42:19.582  7031  7031 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 14:42:19.593  7031  7471 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 14:42:19.597  3414  3414 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 14:42:19.597  3414  3414 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:19.598  3414  3414 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 14:42:19.600  7070  7070 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 14:42:19.600  7070  7070 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 14:42:19.601  6918  7473 W FormManager: Network not available. Please check & try again.
08-30 14:42:19.608  7133  7133 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:42:19
,08-30 14:42:19.610  6918  7475 V FormManager: Network unavailable.
,08-30 14:42:19.611  7133  7133 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 14:42:19.611  7133  7133 D Weather.Utils: 2 : All the weather widget is gone.
08-30 14:42:19.611  7133  7133 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 14:42:19.612  7133  7133 D WeatherAncestor: connectivity changed - connection : true
08-30 14:42:19.612  6918  7475 V FormManager: Network unavailable.
08-30 14:42:19.612  7133  7133 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@e82d426
08-30 14:42:19.613  7133  7133 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 14:42:19.613  7133  7133 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 14:42:19.613  7133  7133 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 14:42:19.613  7133  7133 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 14:42:19.613  7133  7133 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:42:19
08-30 14:42:19.619  1035  1962 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 14:42:19.627  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 14:42:19.632  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 14:42:19.632  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 14:42:19.632  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,08-30 14:42:19.632  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 14:42:19.633  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 14:42:19.633  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 14:42:19.633  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 14:42:19.633  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 14:42:19.633  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 14:42:19.633  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 14:42:19.633  6937  6937 I BluetoothA2dpServiceJni: classInitNative
08-30 14:42:19.633  6937  6937 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 14:42:19.633  6937  6937 D A2dpStateMachine: make
08-30 14:42:19.635  6937  6937 I bluedroid-qcom: get_profile_interface a2dp
08-30 14:42:19.635  6937  7477 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 14:42:19.637  6937  6937 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 14:42:19.637  6937  6937 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 14:42:19.638  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:19.638  6937  7476 D A2dpStateMachine: Enter Disconnected: -2
08-30 14:42:19.639  6937  6937 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 14:42:19.641  6937  6937 D HidService: Received start request. Starting profile...
08-30 14:42:19.641  6937  6937 I bluedroid-qcom: get_profile_interface hidhost
08-30 14:42:19.641  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:19.641  6937  6937 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 14:42:19.642  6937  6937 D HealthService: Received start request. Starting profile...
08-30 14:42:19.644  6937  6937 I bluedroid-qcom: get_profile_interface health
08-30 14:42:19.644  6937  6937 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 14:42:19.644  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:19.645  6937  6937 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 14:42:19.646  6937  6937 D PanService: Received start request. Starting profile...
08-30 14:42:19.646  6937  6937 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 14:42:19.646  6937  6937 I bluedroid-qcom: get_profile_interface pan
08-30 14:42:19.651  6937  6937 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 14:42:19.651  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:19.651  6937  6937 D HeadsetStateMachine: Proxy object connected
08-30 14:42:19.652  6937  6937 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 14:42:19.652  6937  6937 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 14:42:19.653  6937  6937 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 14:42:19.657  6937  6937 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 14:42:19.657  6937  6937 D BtGatt.GattService: Received start request. Starting profile...
08-30 14:42:19.657  6937  6937 D BtGatt.GattService: start()
08-30 14:42:19.657  6937  6937 I bluedroid-qcom: get_profile_interface gatt
08-30 14:42:19.658  6937  6937 D BtGatt.AdvertiseManager: advertise manager created
08-30 14:42:19.663  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:19.666  6937  6937 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:42:19.666  6937  7454 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 14:42:19.667  6937  7454 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 14:42:19.667  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:19.667  6937  7454 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 14:42:19.667  6937  6937 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 14:42:19.668  6937  6937 V BluetoothMapService: BluetoothMapBinder()
08-30 14:42:19.668  6937  6937 D BluetoothMapService: Received start request. Starting profile...
,08-30 14:42:19.668  6937  6937 D BluetoothMapService: start()
08-30 14:42:19.671  6937  6937 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 14:42:19.671  6937  6937 D BluetoothMapEmailAppObserver: createReceiver()
08-30 14:42:19.672  6937  6937 D BluetoothMapEmailAppObserver: initObservers()
08-30 14:42:19.672  6937  6937 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 14:42:19.678  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:19.680  6937  6937 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 14:42:19.683  6937  6937 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:42:19.685  6937  6937 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:42:19.686  6937  6937 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 14:42:19.688  6937  6937 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:42:19.690  6937  6937 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 14:42:19.691  6937  6937 V BluetoothMapService: Handler(): got msg=1
08-30 14:42:19.691  6937  7415 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 14:42:19.692  6937  7415 I bluedroid-qcom: enable
08-30 14:42:19.692  6937  7484 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 14:42:19.692  6937  7415 I bt_hci_bdroid: init
08-30 14:42:19.692  6937  6937 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:19.692  6937  7484 I bt-btu  : btu_task pending for preload complete event
08-30 14:42:19.694  6937  6937 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 14:42:19.694  6937  6937 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:42:19.694  6937  6937 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 14:42:19.694  6937  6937 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:19.694  6937  6937 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 14:42:19.694  6937  7415 I bt_vendor: bt-vendor : init
08-30 14:42:19.694  6937  7415 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 14:42:19.694  6937  7415 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 14:42:19.694  6937  7415 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 14:42:19.694  6937  7415 D bt_userial_mct: userial_init
08-30 14:42:19.695  6937  7415 D bt_hci_bdroid: set_power 1
08-30 14:42:19.695  6937  7415 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 14:42:19.695  6937  7415 I bt_vendor: Starting hciattach daemon
08-30 14:42:19.695  6937  7415 I bt_vendor: try to set true
,08-30 14:42:19.687  7487  7487 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 14:42:19.687  7487  7487 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:19.747  7488  7488 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 14:42:19.867  7494  7494 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 14:42:19.897  7495  7495 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 14:42:19.925  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 14:42:19.951  7501  7501 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 14:42:19.967  7502  7502 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 14:42:19.982  7503  7503 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 14:42:20.028  7505  7505 I libmdmdetect: ESOC framework not supported
08-30 14:42:20.029  7505  7505 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 14:42:20.042  7505  7505 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 14:42:20.042  7505  7505 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 14:42:20.042  7505  7505 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 14:42:20.042  7505  7505 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 14:42:20.042  7505  7505 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 14:42:20.042  7505  7505 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 14:42:20.042  7505  7505 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 14:42:20.084  7505  7509 E QC-QMI  : qmi_client [7505] 14: failed to locate client data
08-30 14:42:20.085   457   457 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 14:42:20.085   457   457 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-30 14:42:20.092  1035  1113 W ProcessCpuTracker: Skipping unknown process pid 7425
08-30 14:42:20.092  1035  1113 W ProcessCpuTracker: Skipping unknown process pid 7426
08-30 14:42:20.093  1035  1113 W ProcessCpuTracker: Skipping unknown process pid 7435
08-30 14:42:20.094  1035  1113 W ProcessCpuTracker: Skipping unknown process pid 7468
08-30 14:42:20.095  1035  1113 W ProcessCpuTracker: Skipping unknown process pid 7506
08-30 14:42:20.110   319  7185 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 14:42:20.111   319  7185 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
08-30 14:42:20.111   319  7185 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
,08-30 14:42:20.113  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 14:42:20.114  1035  7162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-30 14:42:20.114  1035  7162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-3s921ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:20.114  1035  7162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-3s886ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:20.114  1035  7162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3s886ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:20.114  1035  7162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 14:42:20.130  7510  7510 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 14:42:20.143  7511  7511 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-30 14:42:20.167  7165  7191 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-30 14:42:20.199  6937  7415 I bt_vendor: bluetooth satus is on
,08-30 14:42:20.199  6937  7415 D bt_hci_bdroid: preload
08-30 14:42:20.200  6937  7486 D bt_userial_mct: userial_open(port:0)
08-30 14:42:20.200  6937  7486 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 14:42:20.203  6937  7486 I bt_vendor: Done intiailizing UART
08-30 14:42:20.204  6937  7486 I bt_vendor: Done intiailizing UART
08-30 14:42:20.204  6937  7486 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 14:42:20.204  6937  7486 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 14:42:20.204  6937  7484 I bt-btu  : btu_task received preload complete event
08-30 14:42:20.204  6937  7515 D bt_userial_mct: Entering userial_read_thread()
08-30 14:42:20.205  6937  7484 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 14:42:20.205  6937  7484 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 14:42:20.210  6937  7484 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 14:42:20.216  6937  7484 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 14:42:20.216  6937  7484 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 14:42:20.216  6937  7484 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 14:42:20.216  6937  7484 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 14:42:20.216  6937  7484 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 14:42:20.216  6937  7484 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 14:42:20.216  6937  7484 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 14:42:20.216  6937  7484 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 14:42:20.216  6937  7484 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 14:42:20.217  6937  7484 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 14:42:20.217  6937  7484 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 14:42:20.217  6937  7484 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 14:42:20.217  6937  7484 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 14:42:20.217  6937  7484 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 14:42:20.217  6937  7484 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 14:42:20.217  6937  7484 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 14:42:20.306  6937  7484 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-30 14:42:20.306  6937  7484 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01c2061 
08-30 14:42:20.306  6937  7484 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01c2061 
,08-30 14:42:20.354  6937  7419 E bt-btif : Calling BTA_HhEnable
,08-30 14:42:20.354  6937  7419 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-30 14:42:20.372  6937  7419 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 14:42:20.373  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 14:42:20.376  6937  7419 D BluetoothAdapterProperties: Name is: G3
08-30 14:42:20.377  6937  7419 D BluetoothAdapterProperties: Scan Mode:20
08-30 14:42:20.377  6937  7419 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 14:42:20.377  6937  7419 D bt_hci_bdroid: postload
08-30 14:42:20.378  6937  7419 D bte_conf: Device ID record 1 : primary
08-30 14:42:20.378  6937  7419 D bte_conf:   vendorId            = 00c4
08-30 14:42:20.378  6937  7419 D bte_conf:   vendorIdSource      = 0001
08-30 14:42:20.378  6937  7419 D bte_conf:   product             = 13a1
08-30 14:42:20.378  6937  7419 D bte_conf:   version             = 1000
08-30 14:42:20.378  6937  7419 D bte_conf:   clientExecutableURL = 
08-30 14:42:20.378  6937  7419 D bte_conf:   serviceDescription  = 
08-30 14:42:20.378  6937  7419 D bte_conf:   documentationURL    = 
08-30 14:42:20.378  6937  7419 D bte_conf: bte_load_did_conf no section named DID2.
08-30 14:42:20.379  6937  7486 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 14:42:20.385  6937  7415 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 14:42:20.385  6937  7415 D BluetoothAdapterProperties: ScanMode =  20
08-30 14:42:20.385  6937  7415 D BluetoothAdapterProperties: State =  11
08-30 14:42:20.385  6937  7415 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 14:42:20.386  6937  7415 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 14:42:20.386  6937  7415 D BluetoothAdapterProperties: Setting state to 12
08-30 14:42:20.386  6937  7415 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 14:42:20.387  6937  7419 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 14:42:20.387  7520  7520 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 14:42:20.387  7520  7520 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:20.401  1035  1117 D BluetoothManagerService: Message: 60
08-30 14:42:20.401  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 14:42:20.401  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-30 14:42:20.406  6937  7486 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 14:42:20.408  6937  7415 I BluetoothAdapterState: Entering On State
08-30 14:42:20.426  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:20.426  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:20.426  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:20.426  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:42:20.426  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:20.426  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:20.426  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:20.426  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:42:20.430  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 14:42:20.433  6937  7419 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 14:42:20.433  6937  7419 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 14:42:20.434  6937  7515 E bt_mct  : hci lib postload completed
08-30 14:42:20.434  6937  7484 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 14:42:20.434  6937  7484 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 14:42:20.434  6937  7484 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 14:42:20.435  6937  7484 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 14:42:20.435  6937  7484 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 14:42:20.435  6937  7484 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 14:42:20.437  6937  7419 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 14:42:20.442  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:42:20.450  6937  7484 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:42:20.450  6937  7484 W bt-smp  : Plain text(LSB ~ MSB) = 8e fd 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:42:20.450  6937  7484 W bt-smp  : Encrypted text(LSB ~ MSB) = 8c f5 bd d5 5b cf c4 1c 70 38 5b f5 d7 59 d2 97 
08-30 14:42:20.451  6937  7484 W bt-btm  : Stopping oneshot timer
08-30 14:42:20.464  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:20.464  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:20.464  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:20.464  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:42:20.464  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:20.464  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:20.464  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:20.464  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:42:20.475  6937  7484 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:42:20.475  6937  7484 W bt-smp  : Plain text(LSB ~ MSB) = 2b c6 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:42:20.475  6937  7484 W bt-smp  : Encrypted text(LSB ~ MSB) = de 16 9a 30 d2 54 18 13 17 d5 1c e0 ce ce 73 67 
08-30 14:42:20.476  6937  7484 W bt-btm  : Stopping oneshot timer
08-30 14:42:20.477  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:42:20.486  6937  7415 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 14:42:20.486  6937  7415 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 14:42:20.486  6937  7415 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 14:42:20.487  6937  7415 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 14:42:20.487  6937  7415 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 14:42:20.494  6823  6838 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 14:42:20.509  7525  7525 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-30 14:42:20.516  6937  7484 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 ,
08-30 14:42:20.516  6937  7484 W bt-smp  : Plain text(LSB ~ MSB) = 13 84 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:42:20.516  6937  7484 W bt-smp  : Encrypted text(LSB ~ MSB) = 8e 52 6e 2e a2 6d 1a 8c 38 f6 59 61 d3 9b d7 f5 
08-30 14:42:20.516  6937  7484 W bt-btm  : Stopping oneshot timer
08-30 14:42:20.524  1837  3510 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:42:20.531  1837  2555 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 14:42:20.532  1837  1837 D BluetoothHeadset: Proxy object connected
08-30 14:42:20.534  6937  7484 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:42:20.534  6937  7484 W bt-smp  : Plain text(LSB ~ MSB) = d9 19 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:42:20.534  6937  7484 W bt-smp  : Encrypted text(LSB ~ MSB) = f1 dc 37 30 e7 0c a0 11 41 da 95 d9 3b aa 5b ec 
08-30 14:42:20.534  6937  7484 W bt-btm  : Stopping oneshot timer
08-30 14:42:20.537  1837  1837 D BluetoothHeadset: Proxy object connected
08-30 14:42:20.537  6823  6839 D BluetoothMap: onBluetoothStateChange: up=true
08-30 14:42:20.539  1837  4433 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:42:20.540  6823  6823 D BluetoothMap: Proxy object connected
08-30 14:42:20.541  6823  6823 D MapProfile: Bluetooth service connected
08-30 14:42:20.541  6823  6823 D BluetoothMap: getConnectedDevices()
08-30 14:42:20.541  1837  1837 D BluetoothHeadset: Proxy object connected
,08-30 14:42:20.542  6823  6839 D BluetoothPan: onBluetoothStateChange on: true
08-30 14:42:20.542  6823  6839 D BluetoothPan: onBluetoothStateChange call bindService
08-30 14:42:20.543  6937  6955 V BluetoothMapService: getConnectedDevices()
08-30 14:42:20.545  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:42:20.546  6823  6823 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 14:42:20.546  6823  6823 D PanProfile: Bluetooth service connected
,08-30 14:42:20.547  1035  1035 D BluetoothHeadset: Proxy object connected
08-30 14:42:20.547  6823  6839 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 14:42:20.547  6937  7484 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:42:20.548  6937  7484 W bt-smp  : Plain text(LSB ~ MSB) = b3 54 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:42:20.548  6937  7484 W bt-smp  : Encrypted text(LSB ~ MSB) = 81 bd ad f1 9a 0f 62 80 8f 9d a3 52 29 f7 c1 24 
08-30 14:42:20.548  6937  7484 W bt-btm  : Stopping oneshot timer
08-30 14:42:20.551  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 14:42:20.553  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 14:42:20.553  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 14:42:20.555  1035  1035 D BluetoothA2dp: Proxy object connected
08-30 14:42:20.556  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-30 14:42:20.560  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:20.561  1927  2127 D LGBluetoothAPIService: Message: 1
08-30 14:42:20.562  1927  2127 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 14:42:20.563  6823  6823 D BluetoothInputDevice: Proxy object connected
08-30 14:42:20.563  6823  6823 D HidProfile: Bluetooth service connected
08-30 14:42:20.565  6937  6937 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:20.565  6937  6937 D BluetoothMapService: STATE_ON
08-30 14:42:20.565  6937  6937 V BluetoothMapService: Handler(): got msg=1
08-30 14:42:20.566  6937  6937 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 14:42:20.569  1927  2127 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-30 14:42:20.573  6937  7543 D BluetoothMapMasInstance: MAS initSocket()
08-30 14:42:20.573  6937  7543 D BluetoothMapMasInstance:   masId = 00
08-30 14:42:20.573  6937  7543 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 14:42:20.573  6937  7543 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 14:42:20.573  6937  7543 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 14:42:20.575  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 14:42:20.576  1035  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:20.576  6717  6717 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 14:42:20.578  1035  1117 D BluetoothManagerService: Message: 40
08-30 14:42:20.578  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 14:42:20.579  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:20.580  6823  6823 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 14:42:20.584  6937  7543 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:42:20.584  1035  1117 D BluetoothManagerService: Message: 30
08-30 14:42:20.586  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:20.586  6937  6937 V BluetoothPbapService: Pbap Service onCreate
08-30 14:42:20.587  6937  6937 V BluetoothPbapService: Starting PBAP service
08-30 14:42:20.587  6937  7543 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 14:42:20.587  6937  7543 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 14:42:20.588  6937  7543 D BluetoothMapMasInstance: Accepting socket connection...
08-30 14:42:20.588  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:20.589  6937  7419 D BluetoothAdapterProperties: Scan Mode:21
08-30 14:42:20.590  6937  6937 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 14:42:20.590  6937  7419 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 14:42:20.590  6937  6937 V BluetoothPbapService: Pbap Service onBind
08-30 14:42:20.592  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:20.592  6937  6937 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:20.592  6937  6937 V BluetoothPbapService: state: 12
08-30 14:42:20.594  6937  6937 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 14:42:20.594  6937  6937 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 14:42:20.595  6937  6937 V BluetoothPbapService: Handler(): got msg=1
08-30 14:42:20.595  6823  6823 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 14:42:20.596  6937  6937 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,08-30 14:42:20.597  6937  7547 V BluetoothPbapService: Pbap Service initSocket
08-30 14:42:20.597  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 14:42:20.598  1927  2127 D LGBluetoothAPIService: Message: 100
08-30 14:42:20.598  1927  2127 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 14:42:20.598  1035  1117 D BluetoothManagerService: Message: 30
08-30 14:42:20.599  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:20.602  1035  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:20.603  6937  7547 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:42:20.605  6937  7547 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 14:42:20.605  6937  7547 V BluetoothPbapService: Succeed to create listening socket 
08-30 14:42:20.605  6937  7547 V BluetoothPbapService: Accepting socket connection...
08-30 14:42:20.605  6823  6823 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 14:42:20.607  6823  6823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 14:42:20.610  6823  6823 D BluetoothPbap: Proxy object connected
08-30 14:42:20.610  6937  6937 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-30 14:42:20.610  6937  6937 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:20.610  6937  6937 V BluetoothPbapReceiver: ***********state = 12
08-30 14:42:20.611  6823  6823 D PbapServerProfile: Bluetooth service connected
08-30 14:42:20.611  6823  6823 D BluetoothA2dp: Proxy object connected
08-30 14:42:20.611  6823  6823 D A2dpProfile: Bluetooth service connected
,08-30 14:42:20.615  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:42:20.615  2195  2195 D c       : Getting all permits...
08-30 14:42:20.615  2195  2195 D a       : Opening database...
08-30 14:42:20.615  6823  6823 D BluetoothHeadset: Proxy object connected
08-30 14:42:20.617  6823  6823 D HeadsetProfile: Bluetooth service connected
08-30 14:42:20.619  2195  2195 D a       : Opening database auth.proximity.permit_store...
08-30 14:42:20.620  2195  2195 D a       : Closing database...
08-30 14:42:20.629  6823  6823 D DockEventReceiver: finishStartingService: stopping service
,08-30 14:42:20.634  6823  6823 D BluetoothPermissionRequest: onReceive
08-30 14:42:20.636  6823  6823 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 14:42:20.637  6823  6823 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 14:42:20.641  6937  6937 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-30 14:42:20.643  6937  6937 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 14:42:20.650  6937  6937 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 14:42:20.674  6937  6937 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 14:42:20.675  6937  6937 V BtOppService: onCreate
,08-30 14:42:20.679  6937  6937 V BluetoothOppNotification: send message
08-30 14:42:20.683  6937  6937 V BtOppService: Starting RfcommListener
08-30 14:42:20.692  6937  6937 D BluetoothOppPreference: Dumping Names:  
08-30 14:42:20.692  6937  6937 D BluetoothOppPreference: {}
08-30 14:42:20.692  6937  6937 D BluetoothOppPreference: Dumping Channels:  
,08-30 14:42:20.692  6937  6937 D BluetoothOppPreference: {}
08-30 14:42:20.694  6937  6937 V BtOppService: onStartCommand
08-30 14:42:20.696  6937  7554 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 14:42:20.697  6937  7554 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 14:42:20.700  6937  7551 V BtOppService: Deleted complete outbound shares, number =  0
08-30 14:42:20.700  6937  7554 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c7c37d3 on behalf of 
08-30 14:42:20.702  6937  6937 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:20.702  6937  7554 V BluetoothOppNotification: update too frequent, put in queue
08-30 14:42:20.702  6937  6937 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 14:42:20.704  6937  7554 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 14:42:20.704  6937  7554 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 14:42:20.705  6937  7551 V BtOppService: Deleted complete inbound failed shares, number = 0
,08-30 14:42:20.706  6937  7551 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 14:42:20.706  6937  6937 V BluetoothOppNotification: new notify threadi!
08-30 14:42:20.708  6937  6937 V BluetoothOppNotification: send delay message
08-30 14:42:20.709  6937  6937 V BtOppService: start RfcommListener
08-30 14:42:20.709  6937  7551 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a183f10 on behalf of 
08-30 14:42:20.714  6937  7554 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15e9ea09 on behalf of 
08-30 14:42:20.714  6937  7555 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-30 14:42:20.715  6937  6937 V BtOppService: RfcommListener started
08-30 14:42:20.715  6937  6937 V BtOppService: ContentObserver received notification
08-30 14:42:20.716  6937  6937 V BtOppService: ContentObserver received notification
08-30 14:42:20.717  6937  7554 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 14:42:20.717  6937  7554 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-30 14:42:20.720  6937  7556 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 14:42:20.722  1035  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:20.723  6937  7555 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25dd940e on behalf of 
08-30 14:42:20.724  6937  7555 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 14:42:20.724  6937  7554 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33487e2f on behalf of 
08-30 14:42:20.725  6937  7556 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:42:20.725  6937  7554 V BluetoothOppNotification: update too frequent, put in queue
08-30 14:42:20.727  6937  7554 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 14:42:20.728  6937  7556 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-30 14:42:20.728  6937  7555 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 14:42:20.728  6937  7556 V BtOppRfcommListener: Started RFCOMM listener....
08-30 14:42:20.728  6937  7556 I BtOppRfcommListener: Accept thread started.
08-30 14:42:20.728  6937  7556 V BtOppRfcommListener: Accepting connection...
08-30 14:42:20.730  6937  7555 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33aa3c3c on behalf of 
,08-30 14:42:20.735  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:20.736  6937  6937 V BluetoothFtpService: Ftp Service onCreate
08-30 14:42:20.736  6937  6937 I BluetoothFtpService: Ftp Service onCreate
08-30 14:42:20.736  6937  6937 V BluetoothFtpService: Ftp Service onStartCommand
08-30 14:42:20.737  6937  6937 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:20.737  6937  6937 V BluetoothFtpService: Starting Listening on sockets
08-30 14:42:20.737  6937  7555 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 14:42:20.738  6937  6937 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 14:42:20.738  6937  6937 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:42:20.738  6937  6937 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 14:42:20.738  6937  6937 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:20.738  6937  6937 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 14:42:20.739  6937  6937 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 14:42:20.740  6937  7555 V BluetoothOppNotification: outbound notification was removed.
08-30 14:42:20.740  6937  7555 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 14:42:20.742  6937  7555 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e2e31a on behalf of 
08-30 14:42:20.742  6937  6937 V BluetoothFtpService: Handler(): got msg=1
08-30 14:42:20.742  6937  6937 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 14:42:20.742  6937  7555 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 14:42:20.743  6937  6937 V BluetoothFtpService: Ftp Service initSocket
,08-30 14:42:20.744  6937  7555 V BluetoothOppNotification: inbound notification was removed.
08-30 14:42:20.744  6937  7555 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 14:42:20.746  6937  7555 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1be8ce4b on behalf of 
08-30 14:42:20.748  1035  1057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:20.751  6937  6937 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:42:20.755  6937  6937 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-30 14:42:20.755  6937  6937 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-30 14:42:20.757  6937  7557 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-30 14:42:20.772  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:20.772  6937  6937 V BluetoothSapService: Sap Service onCreate
,08-30 14:42:20.908  1035  1925 I art     : Explicit concurrent mark sweep GC freed 92381(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.586ms total 133.806ms
,08-30 14:42:20.909  6937  6937 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:20.909  6937  6937 V BluetoothSapService: state: 12
08-30 14:42:20.909  6937  6937 V BluetoothSapService: Starting SAP server process
08-30 14:42:20.913  6937  6937 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 14:42:20.907  7558  7558 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:20.907  7558  7558 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:20.914  6937  7559 V BluetoothSapService: Sap Service initRfcommSocket
08-30 14:42:20.915  1035  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:20.917  7558  7558 V BT_SAP  : Event pipe created
08-30 14:42:20.917  7558  7558 V BT_SAP  : create_server_socket qcom.sap.server
08-30 14:42:20.917  7558  7558 V BT_SAP  : created socket fd 6
08-30 14:42:20.917  6937  7559 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:42:20.918  6937  7559 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 14:42:20.919  6937  7559 V BluetoothSapService: Succeed to create listening socket 
08-30 14:42:20.919  6937  7559 V BluetoothSapService: Accepting socket connection...
,08-30 14:42:21.120  1035  1375 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 14:42:21.121  1035  1375 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 14:42:21.180  1035  1980 I ActivityManager: Killing 7337:com.lge.bnr/1000 (adj 15): empty #17
,08-30 14:42:21.182  1035  1377 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-30 14:42:21.183  1035  1377 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 14:42:21.212  1035  1889 W libprocessgroup: failed to open /acct/uid_1000/pid_7337/cgroup.procs: No such file or directory
,08-30 14:42:21.257  1035  1998 I ActivityManager: Killing 6843:com.lge.sync/1000 (adj 15): empty #17
,08-30 14:42:21.294  1035  1430 D WifiService: Client connection lost with reason: 4
,08-30 14:42:21.319  1035  1962 W libprocessgroup: failed to open /acct/uid_1000/pid_6843/cgroup.procs: No such file or directory
,08-30 14:42:21.709  6937  6937 V BluetoothOppNotification: new notify threadi!
,08-30 14:42:21.709  6937  6937 V BluetoothOppNotification: send delay message
,08-30 14:42:21.724  6937  7570 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 14:42:21.730  6937  7570 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ef40427 on behalf of 
,08-30 14:42:21.733  6937  7570 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 14:42:21.735  6937  7570 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 14:42:21.736  6937  7570 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@453d6d4 on behalf of 
08-30 14:42:21.736  6937  7570 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 14:42:21.738  6937  7570 V BluetoothOppNotification: outbound notification was removed.
08-30 14:42:21.738  6937  7570 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 14:42:21.740  6937  7570 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f1f407d on behalf of 
08-30 14:42:21.741  6937  7570 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-30 14:42:21.744  6937  7570 V BluetoothOppNotification: inbound notification was removed.
,08-30 14:42:21.745  6937  7570 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 14:42:21.746  6937  7570 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23a2bb72 on behalf of 
08-30 14:42:22.126  1035  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:22.126  1035  1926 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2ade0c51 mBinding = false
,08-30 14:42:22.164  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:42:22.165  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 14:42:22.165  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-30 14:42:22.168  1035  1117 D BluetoothManagerService: Message: 2
08-30 14:42:22.170  1035  1117 D BluetoothManagerService: Sending off request.
08-30 14:42:22.171  6937  7544 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 14:42:22.172  6937  7415 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 14:42:22.172  6937  7415 D BluetoothAdapterProperties: Setting state to 13
08-30 14:42:22.172  6937  7415 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 14:42:22.173  6937  7415 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 14:42:22.173  6937  7415 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 14:42:22.175  6937  7419 D BluetoothAdapterProperties: Scan Mode:20
08-30 14:42:22.176  6937  7415 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 14:42:22.177  6937  7415 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 14:42:22.181  6937  7547 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:42:22.182  6937  7556 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:42:22.182  6937  7557 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:42:22.183  6937  7559 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:42:22.184  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 14:42:22.184  6937  7484 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 14:42:22.185  6937  7543 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 14:42:22.185  6937  7543 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:42:22.185  6937  7543 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 14:42:22.185  6937  7543 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 14:42:22.185  6937  7543 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 14:42:22.185  6937  7543 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 14:42:22.185  6937  7543 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 14:42:22.185  6937  7543 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 14:42:22.189  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:42:22.189  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:42:22.189  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:42:22.189  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:42:22.190  6937  7484 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:42:22.190  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:42:22.190  6937  7484 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:42:22.190  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:42:22.190  6937  7484 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:42:22.190  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 14:42:22.190  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 14:42:22.190  6937  7484 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-30 14:42:22.196  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:22.196  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:22.196  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:22.196  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:22.196  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:42:22.196  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:42:22.196  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:22.196  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:22.196  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:42:22.202  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:22.202  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:42:22.211  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:22.211  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:22.211  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:22.211  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:22.211  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:42:22.211  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:42:22.211  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:22.211  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:22.211  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:42:22.214  6717  6717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:42:22.214  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:42:22.216  1035  1117 D BluetoothManagerService: Message: 60
08-30 14:42:22.217  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 14:42:22.217  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 14:42:22.218  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:22.220  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 14:42:22.227  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:42:22.232  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:22.233  6937  6937 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:22.233  6937  6937 D BluetoothMapService: STATE_TURNING_OFF
08-30 14:42:22.233  6937  6937 V BluetoothMapService: Handler(): got msg=4
08-30 14:42:22.233  6937  6937 D BluetoothMapService: MAP Service closeService in
08-30 14:42:22.233  6937  6937 D BluetoothMapMasInstance: MAP Service shutdown
08-30 14:42:22.233  6937  6937 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 14:42:22.233  6937  6937 V BluetoothMapService: MAP Service closeService out
08-30 14:42:22.234  6937  6937 V BtOppService: Receiver DISABLED_ACTION 
08-30 14:42:22.235  6937  6937 I BtOppRfcommListener: stopping Accept Thread
08-30 14:42:22.235  6937  6937 V BtOppRfcommListener: close mBtServerSocket
08-30 14:42:22.235  6937  7556 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 14:42:22.235  6937  6937 V BtOppRfcommListener: waiting for thread to terminate
08-30 14:42:22.236  6937  6937 V BtOppRfcommListener: done waiting for thread to terminate
08-30 14:42:22.239  6823  6823 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-30 14:42:22.250  6823  6823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 14:42:22.253  6937  6937 V BtOppService: onDestroy
,08-30 14:42:22.255  6937  6937 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 14:42:22.260  6937  6937 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 14:42:22.260  6937  6937 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:22.260  6937  6937 V BluetoothPbapReceiver: ***********state = 13
08-30 14:42:22.262  6937  6937 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 14:42:22.265  6937  6937 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:22.265  6937  6937 V BluetoothPbapService: state: 13
08-30 14:42:22.265  6937  6937 V BluetoothPbapService: Pbap Service closeService in
,08-30 14:42:22.270  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 14:42:22.271  6937  6937 V BluetoothPbapService: successfully stopped pbap service
08-30 14:42:22.271  6937  6937 V BluetoothPbapService: Pbap Service closeService out
08-30 14:42:22.272  6937  6937 V BluetoothPbapService: Pbap Service onDestroy
08-30 14:42:22.272  6937  6937 V BluetoothPbapService: Pbap Service closeService in
08-30 14:42:22.272  6937  6937 V BluetoothPbapService: Pbap Service closeService out
08-30 14:42:22.272  6937  6937 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 14:42:22.295  6823  6823 D DockEventReceiver: finishStartingService: stopping service
,08-30 14:42:22.296  6823  6823 D BluetoothPbap: Proxy object disconnected,
08-30 14:42:22.296  6823  6823 D PbapServerProfile: Bluetooth service disconnected
08-30 14:42:22.303  6823  6823 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 14:42:22.309  6823  6823 D BluetoothPermissionRequest: onReceive
,08-30 14:42:22.309  6823  6823 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 14:42:22.318  6823  6823 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 14:42:22.321  6937  6937 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-30 14:42:22.322  6937  6937 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 14:42:22.322  6937  6937 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 14:42:22.327  6937  6937 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:22.327  6937  6937 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 14:42:22.328  6937  6937 V BluetoothFtpService: Ftp Service onStartCommand
,08-30 14:42:22.328  6937  6937 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:22.328  6937  6937 V BluetoothFtpService: Ftp Service closeService
08-30 14:42:22.329  6937  6937 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 14:42:22.333  6937  6937 V BluetoothFtpService: successfully stopped ftp service
08-30 14:42:22.333  6937  6937 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 14:42:22.333  6937  6937 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:42:22.333  6937  6937 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 14:42:22.333  6937  6937 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:22.334  6937  6937 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 14:42:22.334  6937  6937 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 14:42:22.335  6937  6937 V BluetoothFtpService: Ftp Service onDestroy
08-30 14:42:22.335  6937  6937 V BluetoothFtpService: Ftp Service closeService
08-30 14:42:22.338  6937  6937 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:22.339  6937  6937 V BluetoothSapService: state: 13
,08-30 14:42:22.339  6937  6937 V BluetoothSapService: Stopping SAP server process
,08-30 14:42:22.340  6937  6937 V BluetoothSapService: Sap Service closeSapService in
08-30 14:42:22.340  6937  6937 V BluetoothSapService: Close listen Socket : 
08-30 14:42:22.340  6937  6937 V BluetoothSapService: Close rfcomm Socket : 
08-30 14:42:22.341  6937  6937 V BluetoothSapService: Close sapd  Socket : 
08-30 14:42:22.348  6937  6937 V BluetoothSapService: Sap Service closeSapService out
08-30 14:42:22.349  6937  6937 V BluetoothSapService: Sap Service onDestroy
08-30 14:42:22.349  6937  6937 V BluetoothSapService: Sap Service closeSapService in
08-30 14:42:22.349  6937  6937 V BluetoothSapService: Close listen Socket : 
08-30 14:42:22.349  6937  6937 V BluetoothSapService: Close rfcomm Socket : 
08-30 14:42:22.349  6937  6937 V BluetoothSapService: Close sapd  Socket : 
08-30 14:42:22.349  6937  6937 V BluetoothSapService: Sap Service closeSapService out
,08-30 14:42:23.093  6937  7419 D bt_hci_bdroid: cleanup
,08-30 14:42:23.099  6937  7486 I bt_lpm  : LPM is already off!!!
08-30 14:42:23.099  6937  7515 I bt_userial_mct: exiting userial_read_thread
08-30 14:42:23.099  6937  7515 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 14:42:23.102  6937  7484 W bt-btif : ag scb idx 1 not allocated
08-30 14:42:23.102  6937  7484 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 14:42:23.102  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:42:23.103  6937  7484 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:42:23.103  6937  7484 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 14:42:23.104  6937  7419 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 14:42:23.104  6937  7486 I bt_vendor: hw_epilog_process
08-30 14:42:23.104  6937  7419 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 14:42:23.104  6937  7419 D bt_userial_mct: userial_close
08-30 14:42:23.104  6937  7419 E bt_userial_mct: pthread_join() FAILED result:3
08-30 14:42:23.104  6937  7419 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 14:42:23.111  6937  7419 D bt_hci_bdroid: set_power 0
08-30 14:42:23.111  6937  7419 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 14:42:23.111  6937  7419 I bt_vendor: bluetooth satus is on
08-30 14:42:23.111  6937  7419 I bt_vendor: bt-vendor : resetting BT status
08-30 14:42:23.111  6937  7419 I bt_vendor: Starting hciattach daemon
08-30 14:42:23.111  6937  7419 I bt_vendor: try to set false
,08-30 14:42:23.118  6937  7419 I bt_vendor: Starting hciattach daemon
08-30 14:42:23.118  6937  7419 I bt_vendor: try to set false
08-30 14:42:23.118  6937  7419 I bt_vendor: cleanup
08-30 14:42:23.119  6937  7484 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 14:42:23.119  6937  7419 I GKI_LINUX: GKI_exit_task 0 done
08-30 14:42:23.119  6937  7419 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 14:42:23.121  6937  7415 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 14:42:23.123  6937  6937 D HeadsetService: Received stop request...Stopping profile...
08-30 14:42:23.124  6937  6937 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 14:42:23.124  6937  6937 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 14:42:23.124  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
,08-30 14:42:23.128  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-30 14:42:23.128  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 14:42:23.130  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-30 14:42:23.132  6937  6937 D HeadsetStateMachine: Unbinding service...
08-30 14:42:23.133  6937  7454 D HeadsetStateMachine: Exit Disconnected: -1
08-30 14:42:23.134  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-30 14:42:23.135  6937  6937 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 14:42:23.135  6937  6937 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 14:42:23.135  6937  6937 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 14:42:23.135  6937  6937 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 14:42:23.135  6937  6937 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 14:42:23.135  6937  6937 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 14:42:23.135  6937  6937 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 14:42:23.136  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-30 14:42:23.139  6937  6937 D A2dpService: Received stop request...Stopping profile...
,08-30 14:42:23.142  6937  7476 D A2dpStateMachine: Exit Disconnected: -1
08-30 14:42:23.146  6937  6937 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 14:42:23.150  6937  7415 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 14:42:23.151  6937  6937 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 14:42:23.151  6937  6937 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 14:42:23.152  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
,08-30 14:42:23.155  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-30 14:42:23.155  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 14:42:23.156  6937  6937 D HidService: Received stop request...Stopping profile...
08-30 14:42:23.156  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:23.158  6937  6937 D HealthService: Received stop request...Stopping profile...
08-30 14:42:23.159  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:23.161  6937  6937 D PanService: Received stop request...Stopping profile...
08-30 14:42:23.162  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:23.163  6937  6937 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 14:42:23.166  6937  6937 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 14:42:23.166  6937  6937 D BtGatt.GattService: stop()
08-30 14:42:23.166  6937  6937 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 14:42:23.168  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:23.170  6937  6937 D BluetoothMapService: Received stop request...Stopping profile...
08-30 14:42:23.170  6937  6937 D BluetoothMapService: stop()
08-30 14:42:23.171  6937  6937 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 14:42:23.171  6937  6937 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 14:42:23.171  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:23.173  6937  6937 I BluetoothA2dpServiceJni: cleanupNative
08-30 14:42:23.173  6937  7477 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 14:42:23.173  6937  6937 I GKI_LINUX: GKI_exit_task 2 done
08-30 14:42:23.173  6937  6937 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 14:42:23.174  6937  6937 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 14:42:23.174  6937  6937 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 14:42:23.174  6937  6937 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 14:42:23.174  6937  6937 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 14:42:23.174  6937  6937 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 14:42:23.175  6937  6937 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 14:42:23.175  6937  6937 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 14:42:23.179  6937  6937 V BluetoothMapService: Handler(): got msg=4
08-30 14:42:23.180  6937  6937 D BluetoothMapService: MAP Service closeService in
08-30 14:42:23.180  6937  6937 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 14:42:23.180  6937  6937 V BluetoothMapService: MAP Service closeService out
08-30 14:42:23.182  6937  7415 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 14:42:23.182  6937  7415 D BluetoothAdapterProperties: Setting state to 10
08-30 14:42:23.182  6937  7415 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 14:42:23.182  1035  1117 D BluetoothManagerService: Message: 60
08-30 14:42:23.182  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 14:42:23.182  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-30 14:42:23.183  6937  7415 I BluetoothAdapterState: Entering OffState
08-30 14:42:23.184  6937  6937 D BluetoothMapService: cleanup()
08-30 14:42:23.184  6937  6937 D BluetoothMapService: MAP Service closeService in
08-30 14:42:23.184  6937  6937 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 14:42:23.184  6937  6937 V BluetoothMapService: MAP Service closeService out
08-30 14:42:23.184  6823  6839 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 14:42:23.186  6823  6839 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:42:23.187  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 14:42:23.192  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:42:23.193  6823  6839 D BluetoothMap: onBluetoothStateChange: up=false
08-30 14:42:23.194  1837  2555 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:42:23.195  6823  6839 D BluetoothPan: onBluetoothStateChange on: false
08-30 14:42:23.195  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:42:23.195  6823  6839 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 14:42:23.198  6823  7537 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 14:42:23.198  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 14:42:23.200  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 14:42:23.200  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 14:42:23.202  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 14:42:23.202  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 14:42:23.203  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2ade0c51 mBinding = false
08-30 14:42:23.203  1035  1117 D BluetoothManagerService: Sending unbind request.
08-30 14:42:23.208  6937  7419 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 14:42:23.209  6937  6937 I GKI_LINUX: GKI_exit_task 1 done
08-30 14:42:23.209  6937  6937 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 14:42:23.209  6937  6937 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 14:42:23.210  6937  6937 I art     : --- WEIRD: removing null entry 248
08-30 14:42:23.210  6937  6937 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-30 14:42:23.210  6937  6937 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 14:42:23.211  6937  6937 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-30 14:42:23.214  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 14:42:23.219  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:23.219  1927  2127 D LGBluetoothAPIService: Message: 2
08-30 14:42:23.219  1927  2127 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@18e43791 mBinding = false
08-30 14:42:23.219  1927  2127 D LGBluetoothAPIService: Sending unbind request.
08-30 14:42:23.222  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:42:23.224  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:23.224  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 14:42:23.233  6823  6823 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 14:42:23.233  6823  6823 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-30 14:42:23.238  6937  6937 I art     : System.exit called, status: 0
08-30 14:42:23.238  6937  6937 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 14:42:23.245  6823  6823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 14:42:23.258  1586  1586 D BluetoothAdapter: 571042873: getState() :  mService = null. Returning STATE_OFF
08-30 14:42:23.258  1586  1586 D BluetoothAdapter: 571042873: getState() :  mService = null. Returning STATE_OFF
,08-30 14:42:23.269  6823  6823 D DockEventReceiver: finishStartingService: stopping service
08-30 14:42:23.277   323  1383 V AudioFlinger: 6937 died, releasing its sessions
08-30 14:42:23.277   323  1383 V AudioFlinger:  pid 1837 @ 0
08-30 14:42:23.277   323  1383 V AudioFlinger:  pid 3414 @ 1
08-30 14:42:23.277   323  1383 V AudioFlinger:  pid 3414 @ 2
08-30 14:42:23.278  6823  6823 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-30 14:42:23.361  1035  1962 I ActivityManager: Process com.android.bluetooth (pid 6937) has died
08-30 14:42:23.361  1035  1962 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-30 14:42:23.367  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:42:23.390  6823  6823 D BluetoothPermissionRequest: onReceive
,08-30 14:42:23.395  6823  6823 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 14:42:23.395  6823  6823 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-30 14:42:23.400  6823  6823 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 14:42:23.486  1035  1926 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7617 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 14:42:23.581  7617  7617 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 14:42:23.582  7617  7617 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 14:42:23.582  7617  7617 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 14:42:23.583  7617  7617 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 14:42:23.603  7617  7617 D BluetoothAdapterApp: Loading JNI Library
,08-30 14:42:23.636  7617  7617 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@12f6e94e Instance Count = 1
,08-30 14:42:23.642  7617  7617 D BluetoothAdapterApp: onCreate
,08-30 14:42:23.666  7617  7617 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 14:42:23.666  7617  7617 D ProfileConfigQcom: Adding HeadsetService
08-30 14:42:23.666  7617  7617 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 14:42:23.666  7617  7617 D ProfileConfigQcom: Adding A2dpService
08-30 14:42:23.666  7617  7617 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 14:42:23.667  7617  7617 D ProfileConfigQcom: Adding HidService
08-30 14:42:23.667  7617  7617 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 14:42:23.667  7617  7617 D ProfileConfigQcom: Adding HealthService
08-30 14:42:23.667  7617  7617 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-30 14:42:23.669  7617  7617 D ProfileConfigQcom: [BTUI] PanService is supported
,08-30 14:42:23.669  7617  7617 D ProfileConfigQcom: Adding PanService
,08-30 14:42:23.670  7617  7617 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 14:42:23.671  7617  7617 D ProfileConfigQcom: Adding GattService
08-30 14:42:23.672  7617  7617 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 14:42:23.673  7617  7617 D ProfileConfigQcom: Adding BluetoothMapService
08-30 14:42:23.673  7617  7617 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 14:42:23.677  7617  7617 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-30 14:42:23.683  6823  6823 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-30 14:42:23.686  7617  7617 V LGMDMManagerInternal: Create singleton instance
08-30 14:42:23.762  7617  7617 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 14:42:23.766  7617  7617 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-30 14:42:23.767  7617  7617 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:42:23.767  7617  7617 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 14:42:23.768  7617  7617 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:23.768  7617  7617 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 14:42:23.771  6896  6896 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-30 14:42:23.773  1035  1871 I ActivityManager: Killing 6614:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-30 14:42:23.787  6874  6874 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-30 14:42:23.788  6874  6874 W System.err: android.os.DeadObjectException
08-30 14:42:23.788  6874  6874 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 14:42:23.788  6874  6874 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 14:42:23.788  6874  6874 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 14:42:23.788  6874  6874 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 14:42:23.788  6874  6874 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 14:42:23.788  6874  6874 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 14:42:23.788  6874  6874 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 14:42:23.788  6874  6874 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 14:42:23.788  6874  6874 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 14:42:23.788  6874  6874 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 14:42:23.788  6874  6874 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:42:23.788  6874  6874 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 14:42:23.788  6874  6874 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 14:42:23.788  6874  6874 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 14:42:23.788  6874  6874 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 14:42:23.789  6874  6874 W System.err: android.os.DeadObjectException
08-30 14:42:23.789  6874  6874 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 14:42:23.789  6874  6874 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 14:42:23.789  6874  6874 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 14:42:23.789  6874  6874 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 14:42:23.789  6874  6874 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 14:42:23.789  6874  6874 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 14:42:23.789  6874  6874 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 14:42:23.789  6874  6874 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 14:42:23.789  6874  6874 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 14:42:23.789  6874  6874 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 14:42:23.789  6874  6874 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:42:23.789  6874  6874 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 14:42:23.789  6874  6874 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 14:42:23.789  6874  6874 W System.err: 	at com.android.int,ernal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 14:42:23.789  6874  6874 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 14:42:23.790  6874  6874 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-30 14:42:23.831  1035  2035 W libprocessgroup: failed to open /acct/uid_1000/pid_6614/cgroup.procs: No such file or directory
08-30 14:42:23.832  1035  2035 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-30 14:42:23.834  6874  6874 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 14:42:23.835  6874  6874 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 14:42:23.883  1035  1925 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7644 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 14:42:23.884  6874  6874 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 14:42:23.959  7644  7644 D UEI.SmartControl: Quickset Services start...
08-30 14:42:23.962  7644  7644 I UEI.SmartControl: Manufacture = LGE
,08-30 14:42:23.962  7644  7644 D UEI.SmartControl: Id = LGNevo
,08-30 14:42:23.964  7644  7644 D UEI.SmartControl: File observer start...
08-30 14:42:23.965  7644  7644 E UEI.SmartControl: IR Port is disabled: false
08-30 14:42:23.965  7644  7644 D UEI.SmartControl: Starting file observer...
08-30 14:42:23.965  7644  7644 D UEI.SmartControl: Extracting JNI libs...
,08-30 14:42:23.965  7644  7644 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 14:42:24.064  7644  7644 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-30 14:42:24.064  7644  7644 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 14:42:24.064  7644  7644 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-30 14:42:24.104  7644  7644 I UEI.SmartControl: --- Selecting new region: 6
,08-30 14:42:24.106  7644  7644 I UEI.SmartControl: Model = LG-D855
08-30 14:42:24.108  7644  7644 D UEI.SmartControl: QS Service created
08-30 14:42:24.138  7644  7644 I UEI.SmartControl: Service initServices...
,08-30 14:42:24.144  7644  7644 D UEI.SmartControl: QS start get config
08-30 14:42:24.193  7644  7644 D UEI.SmartControl: Loading JNI Libs...
,08-30 14:42:24.550  7644  7644 I UEI.SmartControl: Supports setup maps: true
,08-30 14:42:24.556  7644  7644 D UEI.SmartControl: QS start statue = true Error code = 0
,08-30 14:42:24.556  7644  7644 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 14:42:24.556  7644  7644 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 14:42:24.557  7644  7644 I UEI.SmartControl: ### init IR Blaster...
08-30 14:42:24.562  7644  7644 D serial_port: Configuring serial port
,08-30 14:42:24.569  7644  7644 E UEI.SmartControl: UEIBLaster setting for 616
08-30 14:42:24.569  7644  7644 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 14:42:24.571  7644  7644 I UEI.SmartControl: configuring settings for MAXQ616
08-30 14:42:24.571  7644  7644 I UEI.SmartControl: Get version...
08-30 14:42:24.588  7644  7662 D UEI.SmartControl: serial port data available: 21
,08-30 14:42:24.620  7644  7644 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 14:42:24.620  7644  7644 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-30 14:42:24.620  7644  7644 I UEI.SmartControl: QS saving settings...
,08-30 14:42:24.622  7644  7644 D UEI.SmartControl: IR Blaster version: 25672567
08-30 14:42:24.639  7644  7662 D UEI.SmartControl: serial port data available: 4
,08-30 14:42:24.681  7644  7665 I UEI.SmartControl: Device manager: loading config....
,08-30 14:42:24.682  7644  7665 D UEI.SmartControl: ----------- loading internal config...
,08-30 14:42:24.691  7644  7644 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 14:42:24.700  7644  7644 E UEI.SmartControl: Services init done
08-30 14:42:24.701  7644  7644 D UEI.SmartControl: QS Service init finished
08-30 14:42:24.703  7644  7644 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 14:42:24.703  7644  7644 D UEI.SmartControl: QS Service version code: 201091
08-30 14:42:24.704  7644  7644 D UEI.SmartControl: Service requested: Control
,08-30 14:42:24.714  7644  7665 E UEI.SmartControl: Loading SETTINGS...
08-30 14:42:24.718  7644  7644 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-30 14:42:24.721  7644  7665 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 14:42:24.724  1035  1998 I ActivityManager: Killing 6874:com.lge.qremote/u0a112 (adj 15): empty #17
08-30 14:42:24.738  7644  7664 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 14:42:24.738  7644  7664 D UEI.SmartControl: -----service ready thread exits
,08-30 14:42:24.780  1035  1871 W libprocessgroup: failed to open /acct/uid_10112/pid_6874/cgroup.procs: No such file or directory
08-30 14:42:24.785  7644  7644 D UEI.SmartControl: Internal service binding...
,08-30 14:42:25.232  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 14:42:25.232  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:42:25.279  1586  1586 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 14:42:25.313  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 14:42:25.324  1035  1035 D administrator: Handling package changes for user 0
08-30 14:42:25.379  1035  1366 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 14:42:25.400  1035  1113 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7683 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 14:42:25.406  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 14:42:25.407  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-30 14:42:25.412  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 14:42:25.457  7683  7683 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 14:42:25.487  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-30 14:42:25.487  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 14:42:25.525  7683  7683 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:42:25.525  7683  7683 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:42:25.542  1035  1112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 14:42:25.548  1035  1112 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 14:42:25.555  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 14:42:25.559  2492  2492 V GmsNetworkLocationProvi: DISABLE
,08-30 14:42:25.594  1035  1112 D LocationProviderProxy: applying state to connected service
08-30 14:42:25.600  2492  2492 E GCoreFlp: Bound FusedProviderService with LocationManager
08-30 14:42:25.625  7683  7715 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-30 14:42:25.625  7683  7715 I Babel   : MmsConfig.loadMmsSettings
,08-30 14:42:25.629  7683  7715 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 14:42:25.629  7683  7715 I Babel   : MmsConfig.loadFromDatabase
,08-30 14:42:25.651  7683  7715 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 14:42:25.651  7683  7715 I Babel   : MmsConfig.loadFromResources
,08-30 14:42:25.652  7683  7715 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 14:42:25.653  7683  7715 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 14:42:25.677  7683  7683 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:25.680  7683  7714 W AudioCapabilities: Unsupported mime audio/evrc
08-30 14:42:25.681  7683  7714 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 14:42:25.684  7683  7714 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 14:42:25.693  7683  7714 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-30 14:42:25.694  7683  7714 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 14:42:25.695  7683  7714 W AudioCapabilities: Unsupported mime audio/evrc
08-30 14:42:25.706  7683  7714 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 14:42:25.714  1800  7718 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 14:42:25.714  1800  7718 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-30 14:42:25.715  6994  6994 I AppUp4:CustModeStarterReceiver: onReceive
08-30 14:42:25.716  7683  7714 W VideoCapabilities: Unsupported mime video/divx
08-30 14:42:25.718  7683  7714 W VideoCapabilities: Unsupported mime video/divx311
08-30 14:42:25.719  6994  6994 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26998b68
08-30 14:42:25.719  6994  6994 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 14:42:25.719  6994  6994 D AppUp4:CustFacade: isPhone : true
08-30 14:42:25.719  6994  6994 D AppUp4:CustModeStarterReceiver: begin check event
08-30 14:42:25.719  6994  6994 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-30 14:42:25.721  7683  7714 W VideoCapabilities: Unsupported mime video/divx4
08-30 14:42:25.721  1800  4763 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-30 14:42:25.725  7683  7714 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 14:42:25.742  7683  7714 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-30 14:42:25.746  7683  7714 W AudioCapabilities: Unsupported mime audio/eac3
,08-30 14:42:25.748  7683  7714 W AudioCapabilities: Unsupported mime audio/ac3
08-30 14:42:25.751  7683  7714 W AudioCapabilities: Unsupported mime audio/g726
08-30 14:42:25.752  7683  7714 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 14:42:25.752  7683  7714 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 14:42:25.753  7683  7714 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 14:42:25.755  7683  7714 W VideoCapabilities: Unsupported mime video/theora
08-30 14:42:25.759  1035  1560 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7722 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-30 14:42:25.760  7683  7714 W VideoCapabilities: Unsupported mime video/mjpg
,08-30 14:42:25.762  1035  1926 I ActivityManager: Killing 7031:com.lge.email/u0a23 (adj 15): empty #17
08-30 14:42:25.874  1035  1769 W libprocessgroup: failed to open /acct/uid_10023/pid_7031/cgroup.procs: No such file or directory
,08-30 14:42:25.929  7722  7722 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 14:42:25.929  7722  7722 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 14:42:25.929  7722  7722 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 14:42:25.931  7722  7722 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 14:42:25.932  7722  7722 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 14:42:26.007  7722  7722 I SystemConfig: BUILD Country: EU
08-30 14:42:26.007  7722  7722 I SystemConfig: BUILD Operator: OPEN
,08-30 14:42:26.051  1035  1944 I ActivityManager: Killing 6918:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-30 14:42:26.188  1035  1890 W libprocessgroup: failed to open /acct/uid_10026/pid_6918/cgroup.procs: No such file or directory
,08-30 14:42:26.200  7722  7741 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 14:42:26.200  7722  7741 I SystemConfig: existFile = false
08-30 14:42:26.200  7722  7741 I SystemConfig: canReadFile = false
08-30 14:42:26.200  7722  7741 I SystemConfig: systemFeature RCS result false
08-30 14:42:26.200  7722  7741 D SystemConfig: refreshRcsSupport() :false
08-30 14:42:26.236  1035  1944 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7746 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 14:42:26.283  7746  7746 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 14:42:26.283  7746  7746 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 14:42:26.284  7746  7746 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 14:42:26.284  7746  7746 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 14:42:26.358  7746  7746 I AppConfig: Total System Memory = 2995761152
,08-30 14:42:26.366  7746  7746 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 14:42:26.474  1035  2033 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7765 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 14:42:26.476  1035  2033 I ActivityManager: Killing 6401:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-30 14:42:26.532  1035  1890 W libprocessgroup: failed to open /acct/uid_1000/pid_6401/cgroup.procs: No such file or directory
,08-30 14:42:26.728  7765  7765 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 14:42:26.828  7765  7765 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:42:26.828  7765  7765 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:42:26.884  7765  7765 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 14:42:26.902  7765  7765 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,08-30 14:42:26.904  7765  7765 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 14:42:26.918  7765  7765 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 14:42:26.919  7765  7765 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 14:42:26.938  1035  2033 I ActivityManager: Killing 7070:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-30 14:42:26.965  1035  1889 W libprocessgroup: failed to open /acct/uid_10046/pid_7070/cgroup.procs: No such file or directory
,08-30 14:42:26.969  3475  3492 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 14:42:26.971  3475  3492 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1302b80c on behalf of 7765
08-30 14:42:26.975  4596  7805 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-30 14:42:27.011  1035  1560 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7806 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 14:42:27.035  7765  7765 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 14:42:27.080  7765  7765 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-30 14:42:27.126  7806  7806 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 14:42:27.149  7806  7806 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 14:42:27.149  7806  7806 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 14:42:27.149  7806  7806 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 14:42:27.149  7806  7806 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 14:42:27.149  7806  7806 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,08-30 14:42:27.149  7806  7806 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-30 14:42:27.169  1035  1926 I ActivityManager: Killing 7092:com.android.chrome/u0a57 (adj 15): empty #17
,08-30 14:42:27.242  1035  1925 W libprocessgroup: failed to open /acct/uid_10057/pid_7092/cgroup.procs: No such file or directory
,08-30 14:42:27.538  1035  1890 V SIM_STK : Menu title from STK is T-Mobile
,08-30 14:42:27.560  4596  7805 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 584 ms] updated apps [took 584 ms] 
,08-30 14:42:28.243  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 14:42:28.243  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2092f3ba added. We now have 6 listener(s)
08-30 14:42:28.243  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:42:28.257  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:28.257  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20b0a26b added. We now have 7 listener(s)
08-30 14:42:28.257  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:28.262  6717  6772 I System.out: IsBluetoothEnabled
,08-30 14:42:28.264  1035  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:28.264  1035  1998 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-30 14:42:28.265  1035  1117 D BluetoothManagerService: Message: 2
08-30 14:42:28.268  6717  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:28.269  1035  1769 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:28.269  1035  1769 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 14:42:28.290  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:42:28.291  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 14:42:28.293  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 14:42:28.293  1035  1117 D BluetoothManagerService: Message: 1
08-30 14:42:28.293  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 14:42:28.322  1035  1117 D BluetoothManagerService: Message: 20
08-30 14:42:28.322  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14491d10:true
,08-30 14:42:28.326  7617  7617 D BluetoothAdapterState: make
08-30 14:42:28.330  7617  7617 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 14:42:28.331  7617  7617 I bluedroid-qcom: init
08-30 14:42:28.332  7617  7850 I BluetoothAdapterState: Entering OffState
08-30 14:42:28.332  7617  7617 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 14:42:28.332  7617  7617 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 14:42:28.332  7617  7617 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 14:42:28.332  7617  7617 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 14:42:28.332  7617  7617 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 14:42:28.334  7617  7617 I bluedroid-qcom: get_profile_interface socket
08-30 14:42:28.334  7617  7617 I bluedroid-qcom: get_profile_interface map_client
,08-30 14:42:28.338  7617  7854 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 14:42:28.343  7617  7854 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 14:42:28.337  7853  7853 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:28.337  7853  7853 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:28.353  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-30 14:42:28.355  1035  1117 D BluetoothManagerService: Message: 40
08-30 14:42:28.355  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 14:42:28.357  7853  7853 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 14:42:28.358  7853  7853 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 14:42:28.358  7853  7853 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-30 14:42:28.359  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 14:42:28.359  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 14:42:28.360  7617  7633 I bluedroid-qcom: config_hci_snoop_log
08-30 14:42:28.361  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 14:42:28.361  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 14:42:28.362  7853  7853 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 14:42:28.367  7853  7853 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 14:42:28.367  7853  7853 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-30 14:42:28.374  7617  7850 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 14:42:28.375  7617  7854 D BluetoothAdapterProperties: Name is: G3
08-30 14:42:28.375  7617  7850 D BluetoothAdapterProperties: Setting state to 11
08-30 14:42:28.376  7617  7850 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 14:42:28.376  1035  1117 D BluetoothManagerService: Message: 60
08-30 14:42:28.376  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 14:42:28.376  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 14:42:28.378  7617  7850 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 14:42:28.384  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 14:42:28.386  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 14:42:28.389  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:28.394  6823  6823 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 14:42:28.402  7617  7617 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-30 14:42:28.403  7617  7617 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:28.403  7617  7617 V BluetoothPbapReceiver: ***********state = 11
08-30 14:42:28.406  7617  7850 D BluetoothBondStateMachine: make
08-30 14:42:28.411  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 14:42:28.412  7617  7850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:28.412  7617  7850 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 14:42:28.412  7617  7850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:28.412  7617  7850 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 14:42:28.412  7617  7850 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 14:42:28.413  7617  7864 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 14:42:28.417  7617  7850 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 14:42:28.426  6823  6823 D BluetoothPermissionRequest: onReceive
08-30 14:42:28.431  7617  7850 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:42:28.431  7617  7617 D HeadsetService: Received start request. Starting profile...
08-30 14:42:28.432  7617  7617 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 14:42:28.432  7617  7617 D LGBluetoothHfpAdapter: Version 1.6
08-30 14:42:28.435  7617  7617 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 14:42:28.436  7617  7617 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 14:42:28.436  6823  6823 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 14:42:28.436  7617  7617 D HeadsetStateMachine: make
,08-30 14:42:28.445  7617  7850 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:42:28.453  7617  7850 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 14:42:28.460  7617  7850 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:42:28.467  7617  7850 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 14:42:28.474  7617  7617 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:42:28.474  7617  7617 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 14:42:28.475  7617  7850 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:42:28.478  7617  7617 D HeadsetStateMachine: max_hf_connections = 1
08-30 14:42:28.478  7617  7617 I bluedroid-qcom: get_profile_interface handsfree
08-30 14:42:28.480  7617  7617 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 14:42:28.481   323  1383 V AudioPolicyService: registerClient() client 0xb10036e0, uid 1002
,08-30 14:42:28.484   323  2144 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 14:42:28.484   323  2144 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 14:42:28.484   323  2144 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 14:42:28.484  7617  7617 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 14:42:28.485   323  2143 V AudioFlinger: registerClient() client 0xb1433148, pid 7617
08-30 14:42:28.485   323  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:42:28.486   323  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:42:28.486  1035  1058 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:42:28.486  1035  1058 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:42:28.486  3414  3431 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:42:28.486  3414  3431 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:42:28.486   323  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:42:28.486   323  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:42:28.486  1586  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:42:28.486  1586  1607 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:42:28.486  1035  2033 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:42:28.486  1586  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:42:28.486  1035  2033 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:42:28.486  1586  1607 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:42:28.486  3414  3429 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:42:28.486  3414  3429 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:42:28.486  7617  7633 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:42:28.486  1837  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:42:28.486  1837  1852 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:42:28.487  1837  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:42:28.487  1837  1852 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:42:28.487  7617  7633 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 14:42:28.487  7617  7633 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:42:28.487  7617  7633 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 14:42:28.487  7617  7617 V ToneGenerator: Create Track: 0xb4928080
08-30 14:42:28.487  7617  7617 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 14:42:28.487  7617  7617 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 14:42:28.488   323  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 14:42:28.488   323  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 14:42:28.488   323  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 14:42:28.488   323  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 14:42:28.488   323  1383 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 14:42:28.488   323  2144 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 14:42:28.488   323  2144 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 14:42:28.488   323  2144 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 14:42:28.488   323 , 2144 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 14:42:28.488  7617  7617 V AudioSystem: getLatency() output 2, latency 50
08-30 14:42:28.488  7617  7617 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 14:42:28.488  7617  7617 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 14:42:28.489   323  2143 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 14:42:28.489   323  2143 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 14:42:28.489   323  2143 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 14:42:28.489   323  2143 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 14:42:28.489   323  2143 V AudioFlinger: createTrack() lSessionId: 21
08-30 14:42:28.490  7617  7617 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 14:42:28.491   323  2143 V AudioFlinger: acquiring 21 from 7617, for 7617
08-30 14:42:28.491   323  2143 V AudioFlinger:  added new entry for 21
08-30 14:42:28.491  7617  7617 V ToneGenerator: ToneGenerator INIT OK, time: 220251
08-30 14:42:28.491  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:28.492  7617  7867 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 14:42:28.492  7617  7867 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 14:42:28.492  7617  7867 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 14:42:28.493  7617  7867 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 14:42:28.493  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:28.495  7617  7617 D A2dpService: Received start request. Starting profile...
08-30 14:42:28.496  7617  7617 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 14:42:28.497  7617  7617 V Avrcp   : make
,08-30 14:42:28.497   323   323 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7617
08-30 14:42:28.497  7617  7617 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 14:42:28.497  7617  7617 I bluedroid-qcom: get_profile_interface avrcp
08-30 14:42:28.498   323   323 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 14:42:28.498   323   323 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 14:42:28.498   323   323 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 14:42:28.498   323   323 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 14:42:28.498   323   323 V voice   : voice_set_parameters: exit with code(0)
08-30 14:42:28.498   323   323 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 14:42:28.498   323   323 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 14:42:28.498   323   323 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 14:42:28.498   323   323 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 14:42:28.498   323   323 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 14:42:28.498   323   323 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 14:42:28.498  7617  7867 V ToneGenerator: ToneGenerator destructor
08-30 14:42:28.498  7617  7867 V ToneGenerator: stopTone
08-30 14:42:28.498  7617  7867 V ToneGenerator: Delete Track: 0xb4928080
08-30 14:42:28.499  7617  7867 V AudioTrack: ~AudioTrack, releasing session id from 7617 on behalf of 7617
08-30 14:42:28.499   323  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 14:42:28.499   323  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 14:42:28.499   323  1384 V AudioFlinger: PlaybackThread::Track destructor
08-30 14:42:28.499   323  1272 V AudioPolicyService: AudioCommandThread() waking up
08-30 14:42:28.499   323  1384 V AudioFlinger: removeClient_l() pid 7617, calling pid 323
08-30 14:42:28.499   323  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 14:42:28.499   323  1272 V AudioPolicyManager: releaseOutput() 2
08-30 14:42:28.499   323  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 14:42:28.501   323  2143 V AudioFlinger: releasing 21 from 7617 for 7617
08-30 14:42:28.501   323  2143 V AudioFlinger:  decremented refcount to 0
08-30 14:42:28.501   323  2143 V AudioFlinger: purging stale effects
08-30 14:42:28.506  7617  7850 V LGMDMManager: Create singleton instance
08-30 14:42:28.508  7617  7850 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-30 14:42:28.510  7617  7617 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 14:42:28.512  7617  7617 E AudioManager: No RCC entry present to update
08-30 14:42:28.512  7617  7617 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 14:42:28.516  7617  7617 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 14:42:28.517  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 14:42:28.517  7617  7617 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 14:42:28.523  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-30 14:42:28.654  1035  1890 V SIM_STK : Menu title from STK is T-Mobile
,08-30 14:42:28.654  1035  1890 V SIM_STK : Menu title from STK is T-Mobile
,08-30 14:42:28.727  1035  1944 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 14:42:28.736  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 14:42:28.740  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 14:42:28.740  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 14:42:28.740  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 14:42:28.740  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 14:42:28.741  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 14:42:28.741  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 14:42:28.741  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 14:42:28.741  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 14:42:28.741  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 14:42:28.741  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 14:42:28.741  7617  7617 I BluetoothA2dpServiceJni: classInitNative
,08-30 14:42:28.741  7617  7617 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 14:42:28.741  7617  7617 D A2dpStateMachine: make
08-30 14:42:28.744  7617  7617 I bluedroid-qcom: get_profile_interface a2dp
,08-30 14:42:28.750  7617  7879 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 14:42:28.752  7617  7617 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 14:42:28.752  7617  7617 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 14:42:28.753  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:28.753  7617  7878 D A2dpStateMachine: Enter Disconnected: -2
08-30 14:42:28.754  7617  7617 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 14:42:28.755  7617  7617 D HidService: Received start request. Starting profile...
08-30 14:42:28.755  7617  7617 I bluedroid-qcom: get_profile_interface hidhost
08-30 14:42:28.755  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
,08-30 14:42:28.755  7617  7617 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 14:42:28.758  7617  7617 D HealthService: Received start request. Starting profile...
08-30 14:42:28.761  7617  7617 I bluedroid-qcom: get_profile_interface health
08-30 14:42:28.761  7617  7617 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 14:42:28.761  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:28.764  7617  7617 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 14:42:28.768  7617  7617 D PanService: Received start request. Starting profile...
08-30 14:42:28.769  7617  7617 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 14:42:28.769  7617  7617 I bluedroid-qcom: get_profile_interface pan
,08-30 14:42:28.781  7617  7617 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 14:42:28.781  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:28.782  7617  7617 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-30 14:42:28.785  7617  7617 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 14:42:28.785  7617  7617 D BtGatt.GattService: Received start request. Starting profile...
08-30 14:42:28.785  7617  7617 D BtGatt.GattService: start()
08-30 14:42:28.785  7617  7617 I bluedroid-qcom: get_profile_interface gatt
08-30 14:42:28.786  7617  7617 D BtGatt.AdvertiseManager: advertise manager created
08-30 14:42:28.794  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:28.794  7617  7617 D HeadsetStateMachine: Proxy object connected
08-30 14:42:28.795  7617  7617 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 14:42:28.795  7617  7617 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 14:42:28.797  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:28.798  7617  7617 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 14:42:28.799  7617  7617 V BluetoothMapService: BluetoothMapBinder()
,08-30 14:42:28.799  7617  7617 D BluetoothMapService: Received start request. Starting profile...
08-30 14:42:28.799  7617  7617 D BluetoothMapService: start()
,08-30 14:42:28.803  7617  7617 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 14:42:28.803  7617  7617 D BluetoothMapEmailAppObserver: createReceiver()
08-30 14:42:28.804  7617  7617 D BluetoothMapEmailAppObserver: initObservers()
08-30 14:42:28.804  7617  7617 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 14:42:28.812  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
,08-30 14:42:28.817  7617  7617 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:42:28.818  7617  7867 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 14:42:28.818  7617  7867 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 14:42:28.818  7617  7867 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 14:42:28.821  7617  7617 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:42:28.824  7617  7617 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:42:28.826  7617  7617 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 14:42:28.829  7617  7617 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:42:28.830  7617  7617 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 14:42:28.833  7617  7617 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:42:28.837  7617  7617 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 14:42:28.837  7617  7617 V BluetoothMapService: Handler(): got msg=1
08-30 14:42:28.838  7617  7617 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 14:42:28.838  7617  7617 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:42:28.838  7617  7617 V BluetoothSapReceiver: SapReceiver onReceive 
,08-30 14:42:28.838  7617  7617 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-30 14:42:28.838  7617  7617 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 14:42:28.838  7617  7850 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 14:42:28.838  7617  7850 I bluedroid-qcom: enable
08-30 14:42:28.839  7617  7850 I bt_hci_bdroid: init
08-30 14:42:28.843  7617  7889 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 14:42:28.843  7617  7889 I bt-btu  : btu_task pending for preload complete event
08-30 14:42:28.845  7617  7850 I bt_vendor: bt-vendor : init
08-30 14:42:28.845  7617  7850 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 14:42:28.846  7617  7850 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 14:42:28.846  7617  7850 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 14:42:28.846  7617  7850 D bt_userial_mct: userial_init
08-30 14:42:28.846  7617  7850 D bt_hci_bdroid: set_power 1
08-30 14:42:28.846  7617  7850 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 14:42:28.847  7617  7850 I bt_vendor: Starting hciattach daemon
08-30 14:42:28.847  7617  7850 I bt_vendor: try to set true
08-30 14:42:28.847  7892  7892 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:28.847  7892  7892 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 14:42:28.873  7893  7893 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 14:42:28.970  7899  7899 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 14:42:28.982  7900  7900 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 14:42:29.008  7902  7902 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 14:42:29.021  7903  7903 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-30 14:42:29.036  7904  7904 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 14:42:29.048  7905  7905 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-30 14:42:29.086  7907  7907 I libmdmdetect: ESOC framework not supported
,08-30 14:42:29.087  7907  7907 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-30 14:42:29.096  7907  7907 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 14:42:29.096  7907  7907 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 14:42:29.096  7907  7907 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 14:42:29.096  7907  7907 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 14:42:29.096  7907  7907 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 14:42:29.096  7907  7907 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 14:42:29.096  7907  7907 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 14:42:29.138  7907  7908 E QC-QMI  : qmi_client [7907] 15: failed to locate client data
08-30 14:42:29.140   457   457 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 14:42:29.140   457   457 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-30 14:42:29.195  7909  7909 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 14:42:29.213  7910  7910 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 14:42:29.251  7617  7850 I bt_vendor: bluetooth satus is on
08-30 14:42:29.251  7617  7850 D bt_hci_bdroid: preload
08-30 14:42:29.253  7617  7891 D bt_userial_mct: userial_open(port:0)
08-30 14:42:29.253  7617  7891 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 14:42:29.259  7617  7891 I bt_vendor: Done intiailizing UART
08-30 14:42:29.264  7617  7891 I bt_vendor: Done intiailizing UART
08-30 14:42:29.264  7617  7891 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 14:42:29.265  7617  7891 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 14:42:29.265  7617  7912 D bt_userial_mct: Entering userial_read_thread()
08-30 14:42:29.265  7617  7889 I bt-btu  : btu_task received preload complete event
08-30 14:42:29.266  7617  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 14:42:29.267  7617  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-30 14:42:29.273  7617  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 14:42:29.282  7617  7889 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 14:42:29.282  7617  7889 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 14:42:29.282  7617  7889 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 14:42:29.282  7617  7889 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 14:42:29.282  7617  7889 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 14:42:29.282  7617  7889 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 14:42:29.282  7617  7889 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 14:42:29.283  7617  7889 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 14:42:29.283  7617  7889 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 14:42:29.283  7617  7889 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 14:42:29.283  7617  7889 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 14:42:29.283  7617  7889 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 14:42:29.283  7617  7889 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 14:42:29.283  7617  7889 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 14:42:29.283  7617  7889 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 14:42:29.283  7617  7889 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 14:42:29.388  7617  7889 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 14:42:29.388  7617  7889 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01c2061 
08-30 14:42:29.388  7617  7889 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01c2061 
,08-30 14:42:29.405  7617  7854 E bt-btif : Calling BTA_HhEnable
08-30 14:42:29.405  7617  7854 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 14:42:29.406  7617  7854 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 14:42:29.408  7617  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 14:42:29.408  7617  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 14:42:29.408  7617  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 14:42:29.408  7617  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 14:42:29.408  7617  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 14:42:29.410  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 14:42:29.410  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 14:42:29.411  7617  7854 D BluetoothAdapterProperties: Name is: G3
08-30 14:42:29.412  7617  7854 D BluetoothAdapterProperties: Scan Mode:20
08-30 14:42:29.412  7617  7854 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 14:42:29.412  7617  7854 D bt_hci_bdroid: postload
08-30 14:42:29.413  7617  7891 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 14:42:29.413  7617  7854 D bte_conf: Device ID record 1 : primary
08-30 14:42:29.413  7617  7854 D bte_conf:   vendorId            = 00c4
08-30 14:42:29.413  7617  7854 D bte_conf:   vendorIdSource      = 0001
08-30 14:42:29.413  7617  7854 D bte_conf:   product             = 13a1
08-30 14:42:29.413  7617  7854 D bte_conf:   version             = 1000
08-30 14:42:29.413  7617  7854 D bte_conf:   clientExecutableURL = 
08-30 14:42:29.413  7617  7854 D bte_conf:   serviceDescription  = 
08-30 14:42:29.414  7617  7854 D bte_conf:   documentationURL    = 
08-30 14:42:29.414  7617  7854 D bte_conf: bte_load_did_conf no section named DID2.
08-30 14:42:29.414  7617  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 14:42:29.415  7617  7891 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 14:42:29.416  7617  7891 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 14:42:29.418  7617  7891 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 14:42:29.423  7617  7912 E bt_mct  : hci lib postload completed
08-30 14:42:29.417  7920  7920 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:29.417  7920  7920 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:29.429  7617  7850 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 14:42:29.429  7617  7850 D BluetoothAdapterProperties: ScanMode =  20
08-30 14:42:29.429  7617  7850 D BluetoothAdapterProperties: State =  11
08-30 14:42:29.429  7617  7850 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 14:42:29.429  7617  7850 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 14:42:29.430  7617  7850 D BluetoothAdapterProperties: Setting state to 12
08-30 14:42:29.430  7617  7850 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 14:42:29.431  1035  1117 D BluetoothManagerService: Message: 60
08-30 14:42:29.431  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 14:42:29.432  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-30 14:42:29.436  7617  7850 I BluetoothAdapterState: Entering On State
08-30 14:42:29.441  7617  7889 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:42:29.441  7617  7889 W bt-smp  : Plain text(LSB ~ MSB) = 57 f3 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:42:29.441  7617  7889 W bt-smp  : Encrypted text(LSB ~ MSB) = 1e 9f 5f 30 c3 6a 72 0b 01 e2 62 50 16 d1 67 a3 
08-30 14:42:29.441  7617  7889 W bt-btm  : Stopping oneshot timer
08-30 14:42:29.442  7617  7854 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 14:42:29.442  7617  7854 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 14:42:29.473  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:29.473  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:29.473  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:29.473  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:42:29.473  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:29.473  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:29.473  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:29.473  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:42:29.477  7617  7854 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 14:42:29.477  7617  7854 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 14:42:29.480  7617  7850 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 14:42:29.480  7617  7850 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 14:42:29.480  7617  7850 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 14:42:29.482  7617  7850 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 14:42:29.486  7617  7850 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-30 14:42:29.490  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:42:29.493  7617  7889 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:42:29.493  7617  7889 W bt-smp  : Plain text(LSB ~ MSB) = 10 cc 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:42:29.493  7617  7889 W bt-smp  : Encrypted text(LSB ~ MSB) = c7 ae cb e6 bf 01 bc 8b 1c e3 bb 0c ff d8 07 59 
08-30 14:42:29.493  7617  7889 W bt-btm  : Stopping oneshot timer
08-30 14:42:29.535  7925  7925 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-30 14:42:29.539  7617  7889 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:42:29.539  7617  7889 W bt-smp  : Plain text(LSB ~ MSB) = 4a 38 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:42:29.539  7617  7889 W bt-smp  : Encrypted text(LSB ~ MSB) = 12 45 b6 21 78 a5 fb a9 e9 71 12 87 d7 92 c7 4f 
08-30 14:42:29.539  7617  7889 W bt-btm  : Stopping oneshot timer
08-30 14:42:29.545  6823  6838 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 14:42:29.548  6823  6839 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:42:29.551  1837  4433 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 14:42:29.553  7617  7889 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:42:29.553  7617  7889 W bt-smp  : Plain text(LSB ~ MSB) = a3 33 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:42:29.553  7617  7889 W bt-smp  : Encrypted text(LSB ~ MSB) = 65 52 be 5e 27 53 77 06 65 48 c1 e7 ea f3 82 e8 
08-30 14:42:29.554  7617  7889 W bt-btm  : Stopping oneshot timer
08-30 14:42:29.554  6823  6823 D BluetoothHeadset: Proxy object connected
08-30 14:42:29.554  6823  6823 D HeadsetProfile: Bluetooth service connected
08-30 14:42:29.555  1837  1837 D BluetoothHeadset: Proxy object connected
08-30 14:42:29.556  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:42:29.558  6823  6838 D BluetoothMap: onBluetoothStateChange: up=true
08-30 14:42:29.558  1837  1837 D BluetoothHeadset: Proxy object connected
08-30 14:42:29.561  6823  6823 D BluetoothMap: Proxy object connected
08-30 14:42:29.561  6823  6823 D MapProfile: Bluetooth service connected
08-30 14:42:29.561  6823  6823 D BluetoothMap: getConnectedDevices()
08-30 14:42:29.561  7617  7633 V BluetoothMapService: getConnectedDevices()
08-30 14:42:29.563  7617  7889 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:42:29.563  7617  7889 W bt-smp  : Plain text(LSB ~ MSB) = b4 20 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:42:29.563  7617  7889 W bt-smp  : Encrypted text(LSB ~ MSB) = 9b b2 06 3b 82 f7 47 2a 1f 6c 4b 3f c0 9f f6 92 
08-30 14:42:29.563  7617  7889 W bt-btm  : Stopping oneshot timer
,08-30 14:42:29.565  1837  2555 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:42:29.569  1837  1837 D BluetoothHeadset: Proxy object connected
08-30 14:42:29.569  6823  7537 D BluetoothPan: onBluetoothStateChange on: true
08-30 14:42:29.569  6823  7537 D BluetoothPan: onBluetoothStateChange call bindService
08-30 14:42:29.573  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:42:29.574  6823  6823 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 14:42:29.574  6823  6823 D PanProfile: Bluetooth service connected
08-30 14:42:29.576  1035  1035 D BluetoothHeadset: Proxy object connected
,08-30 14:42:29.580  6823  6839 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 14:42:29.582  6823  7537 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 14:42:29.583  6823  6823 D BluetoothA2dp: Proxy object connected
08-30 14:42:29.583  6823  6823 D A2dpProfile: Bluetooth service connected
08-30 14:42:29.585  6823  6823 D BluetoothInputDevice: Proxy object connected
08-30 14:42:29.585  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 14:42:29.585  6823  6823 D HidProfile: Bluetooth service connected
08-30 14:42:29.586  1035  1035 D BluetoothA2dp: Proxy object connected
08-30 14:42:29.586  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 14:42:29.587  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-30 14:42:29.593  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 14:42:29.593  1035  1117 D BluetoothManagerService: Message: 40
08-30 14:42:29.593  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 14:42:29.595  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:29.595  1927  2127 D LGBluetoothAPIService: Message: 1
08-30 14:42:29.595  1927  2127 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 14:42:29.595  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 14:42:29.602  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:42:29.679  7644  7666 D UEI.SmartControl: Internal timer expired: 1
08-30 14:42:29.679  7644  7666 D UEI.SmartControl: unbind internal service
,08-30 14:42:29.711  1035  1722 I art     : Explicit concurrent mark sweep GC freed 27650(1367KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.785ms total 109.971ms
,08-30 14:42:29.713  7617  7617 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 14:42:29.713  7617  7617 D BluetoothMapService: STATE_ON
08-30 14:42:29.714  7617  7617 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 14:42:29.716  1927  2127 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-30 14:42:29.716  7617  7617 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 14:42:29.720  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 14:42:29.720  7617  7617 V BluetoothMapService: Handler(): got msg=1
08-30 14:42:29.721  1927  2127 D LGBluetoothAPIService: Message: 100
,08-30 14:42:29.721  1927  2127 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 14:42:29.721  7617  7617 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 14:42:29.721  7644  7644 D UEI.SmartControl: Service.onUnbind: IControl
08-30 14:42:29.722  6823  6823 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 14:42:29.722  7644  7644 D UEI.SmartControl: Service.onDestroy
08-30 14:42:29.723  7644  7644 D UEI.SmartControl: Lock is in USE false
08-30 14:42:29.723  7644  7644 D UEI.SmartControl: unbind internal service
08-30 14:42:29.723  7617  7943 D BluetoothMapMasInstance: MAS initSocket()
08-30 14:42:29.723  7644  7644 D serial_port: close(fd = 25)
08-30 14:42:29.724  7617  7943 D BluetoothMapMasInstance:   masId = 00
08-30 14:42:29.724  7617  7943 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 14:42:29.724  7617  7943 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 14:42:29.724  7617  7943 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 14:42:29.725  1035  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:29.726  6823  6823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 14:42:29.726  7617  7943 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:42:29.731  7617  7854 D BluetoothAdapterProperties: Scan Mode:21
08-30 14:42:29.731  7617  7854 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 14:42:29.731  7617  7943 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 14:42:29.732  7617  7943 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 14:42:29.732  7617  7943 D BluetoothMapMasInstance: Accepting socket connection...
08-30 14:42:29.733  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:29.740  7644  7644 I UEI.SmartControl: Serial port is closed.
,08-30 14:42:29.741  7644  7644 I UEI.SmartControl: Serial port is closed.
08-30 14:42:29.742  7644  7644 D UEI.SmartControl: Blaster closed
08-30 14:42:29.742  7644  7644 D UEI.SmartControl: Shut down QS...
08-30 14:42:29.742  7644  7644 D UEI.SmartControl: Stopping QS lib
08-30 14:42:29.742  7644  7644 D UEI.SmartControl: QS lib stop result = true
08-30 14:42:29.742  6823  6823 D DockEventReceiver: finishStartingService: stopping service
08-30 14:42:29.743  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:29.743  7617  7617 V BluetoothPbapService: Pbap Service onCreate
08-30 14:42:29.743  7617  7617 V BluetoothPbapService: Starting PBAP service
08-30 14:42:29.743  7644  7644 D UEI.SmartControl: Stopped QS lib
08-30 14:42:29.743  7644  7644 D UEI.SmartControl: Stopped file observer...
08-30 14:42:29.743  7644  7644 D UEI.SmartControl: QS shutdown complete
08-30 14:42:29.744  7617  7617 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 14:42:29.745  7617  7617 V BluetoothPbapService: Pbap Service onBind
08-30 14:42:29.746  7617  7617 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:29.746  7617  7617 V BluetoothPbapService: state: 12
08-30 14:42:29.747  7617  7617 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 14:42:29.747  7617  7617 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:29.747  7617  7617 V BluetoothPbapReceiver: ***********state = 12
08-30 14:42:29.747  6823  6823 D BluetoothPbap: Proxy object connected
08-30 14:42:29.747  6823  6823 D PbapServerProfile: Bluetooth service connected
08-30 14:42:29.748  7617  7617 V BluetoothPbapService: Handler(): got msg=1
08-30 14:42:29.749  7617  7617 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 14:42:29.750  7617  7947 V BluetoothPbapService: Pbap Service initSocket
08-30 14:42:29.750  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 14:42:29.750  1035  1057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:29.750  2195  2195 D c       : Getting all permits...
08-30 14:42:29.750  2195  2195 D a       : Opening database...
08-30 14:42:29.751  7617  7947 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:42:29.754  2195  2195 D a       : Opening database auth.proximity.permit_store...
,08-30 14:42:29.757  2195  2195 D a       : Closing database...
08-30 14:42:29.760  7617  7947 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 14:42:29.761  7617  7947 V BluetoothPbapService: Succeed to create listening socket 
08-30 14:42:29.761  7617  7947 V BluetoothPbapService: Accepting socket connection...
08-30 14:42:29.766  6823  6823 D BluetoothPermissionRequest: onReceive
,08-30 14:42:29.767  6823  6823 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 14:42:29.769  6823  6823 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 14:42:29.772  7617  7617 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 14:42:29.773  7617  7617 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 14:42:29.778  7617  7617 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-30 14:42:29.796  7617  7617 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 14:42:29.797  7617  7617 V BtOppService: onCreate
08-30 14:42:29.801  7617  7617 V BluetoothOppNotification: send message
08-30 14:42:29.805  7617  7617 V BtOppService: Starting RfcommListener
08-30 14:42:29.813  7617  7617 D BluetoothOppPreference: Dumping Names:  
08-30 14:42:29.813  7617  7617 D BluetoothOppPreference: {}
08-30 14:42:29.813  7617  7617 D BluetoothOppPreference: Dumping Channels:  
08-30 14:42:29.813  7617  7617 D BluetoothOppPreference: {}
,08-30 14:42:29.816  7617  7617 V BtOppService: onStartCommand
08-30 14:42:29.821  7617  7953 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 14:42:29.821  7617  7617 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:29.821  7617  7617 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 14:42:29.825  7617  7617 V BluetoothOppNotification: new notify threadi!
08-30 14:42:29.826  7617  7617 V BluetoothOppNotification: send delay message
08-30 14:42:29.827  7617  7617 V BtOppService: start RfcommListener
,08-30 14:42:29.830  7617  7617 V BtOppService: RfcommListener started
08-30 14:42:29.834  7617  7955 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 14:42:29.835  1035  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:29.837  7617  7955 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:42:29.840  7617  7955 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-30 14:42:29.840  7617  7955 V BtOppRfcommListener: Started RFCOMM listener....
08-30 14:42:29.844  7617  7953 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 14:42:29.844  7617  7955 I BtOppRfcommListener: Accept thread started.
08-30 14:42:29.844  7617  7955 V BtOppRfcommListener: Accepting connection...
08-30 14:42:29.845  7617  7954 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 14:42:29.846  7617  7953 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c7c37d3 on behalf of 
08-30 14:42:29.846  7617  7950 V BtOppService: Deleted complete outbound shares, number =  0
08-30 14:42:29.847  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:29.847  7617  7617 V BluetoothFtpService: Ftp Service onCreate
08-30 14:42:29.847  7617  7617 I BluetoothFtpService: Ftp Service onCreate
,08-30 14:42:29.848  7617  7617 V BluetoothFtpService: Ftp Service onStartCommand
08-30 14:42:29.848  7617  7617 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:29.848  7617  7617 V BluetoothFtpService: Starting Listening on sockets
08-30 14:42:29.848  7617  7617 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 14:42:29.848  7617  7617 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:42:29.848  7617  7617 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 14:42:29.849  7617  7617 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:29.849  7617  7617 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 14:42:29.849  7617  7617 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 14:42:29.850  7617  7954 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15e9ea09 on behalf of 
08-30 14:42:29.851  7617  7954 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 14:42:29.852  7617  7950 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 14:42:29.854  7617  7950 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 14:42:29.854  7617  7617 V BtOppService: ContentObserver received notification
08-30 14:42:29.854  7617  7617 V BluetoothFtpService: Handler(): got msg=1
08-30 14:42:29.854  7617  7954 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 14:42:29.857  7617  7617 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 14:42:29.857  7617  7617 V BluetoothFtpService: Ftp Service initSocket
08-30 14:42:29.857  7617  7953 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 14:42:29.857  7617  7953 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 14:42:29.858  7617  7950 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25dd940e on behalf of 
,08-30 14:42:29.861  7617  7953 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33487e2f on behalf of 
,08-30 14:42:29.863  7617  7953 V BluetoothOppNotification: update too frequent, put in queue
08-30 14:42:29.863  1035  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:29.864  7617  7954 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33aa3c3c on behalf of 
08-30 14:42:29.864  7617  7953 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 14:42:29.864  7617  7954 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 14:42:29.866  7617  7954 V BluetoothOppNotification: outbound notification was removed.
08-30 14:42:29.866  7617  7954 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 14:42:29.866  7617  7617 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:42:29.868  7617  7954 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@303e1dc5 on behalf of 
08-30 14:42:29.869  7617  7617 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
08-30 14:42:29.869  7617  7954 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 14:42:29.869  7617  7617 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-30 14:42:29.871  7617  7954 V BluetoothOppNotification: inbound notification was removed.
08-30 14:42:29.871  7617  7954 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 14:42:29.871  7617  7956 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 14:42:29.872  7617  7954 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e2e31a on behalf of 
08-30 14:42:29.891  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82d426
08-30 14:42:29.891  7617  7617 V BluetoothSapService: Sap Service onCreate
,08-30 14:42:29.893  7617  7617 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:42:29.893  7617  7617 V BluetoothSapService: state: 12
08-30 14:42:29.893  7617  7617 V BluetoothSapService: Starting SAP server process
08-30 14:42:29.895  7617  7617 V BtOppService: ContentObserver received notification
08-30 14:42:29.896  7617  7617 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 14:42:29.887  7957  7957 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:29.887  7957  7957 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 14:42:29.897  7617  7958 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 14:42:29.897  7617  7958 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 14:42:29.898  7617  7958 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14bc16e6 on behalf of 
08-30 14:42:29.899  7617  7958 V BluetoothOppNotification: update too frequent, put in queue
08-30 14:42:29.900  7617  7958 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 14:42:29.902  7617  7959 V BluetoothSapService: Sap Service initRfcommSocket
08-30 14:42:29.902  1035  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:29.903  7617  7959 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:42:29.904  7617  7959 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-30 14:42:29.904  7617  7959 V BluetoothSapService: Succeed to create listening socket 
08-30 14:42:29.904  7617  7959 V BluetoothSapService: Accepting socket connection...
,08-30 14:42:29.923  7957  7957 V BT_SAP  : Event pipe created
08-30 14:42:29.923  7957  7957 V BT_SAP  : create_server_socket qcom.sap.server
,08-30 14:42:29.923  7957  7957 V BT_SAP  : created socket fd 6
,08-30 14:42:30.336  6717  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:30.336  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:30.336  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:30.336  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:42:30.336  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:30.336  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:30.336  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:30.336  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:42:30.352  6717  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:42:30.354  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:30.354  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@673f1c8 added. We now have 8 listener(s)
08-30 14:42:30.354  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:30.357  1035  1962 D WifiServiceImplEx: setWifiEnabled: false pid=6717, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 14:42:30.358  1035  1962 D WifiService: setWifiEnabled: false pid=6717, uid=10118
08-30 14:42:30.358  1035  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:42:30.365  6717  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:30.367  1035  1722 D WifiServiceImplEx: setWifiEnabled: true pid=6717, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 14:42:30.368  1035  1722 D WifiService: setWifiEnabled: true pid=6717, uid=10118
08-30 14:42:30.368  1035  1722 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:42:30.389  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:42:30.389  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 14:42:30.389  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 14:42:30.391  1035  1377 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 14:42:30.391  1035  1377 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 14:42:30.394  1035  1377 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 14:42:30.394  1035  1377 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 14:42:30.394  1035  1377 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 14:42:30.394  1035  1377 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 14:42:30.394  1035  1377 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 14:42:30.394  1035  1377 E WifiHW  : unknown target_country: EU , set to default
08-30 14:42:30.394  1035  1377 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 14:42:30.394  1035  1377 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 14:42:30.394  1035  1377 I WifiUtil: gEnableBmps=1
08-30 14:42:30.831  7617  7617 V BluetoothOppNotification: new notify threadi!
08-30 14:42:30.832  7617  7617 V BluetoothOppNotification: send delay message
,08-30 14:42:30.842  7617  7972 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 14:42:30.849  7617  7972 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ef40427 on behalf of 
08-30 14:42:30.849  7617  7972 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-30 14:42:30.868  7617  7972 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-30 14:42:30.873  7617  7972 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@453d6d4 on behalf of 
08-30 14:42:30.874  7617  7972 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 14:42:30.875  7617  7972 V BluetoothOppNotification: outbound notification was removed.
08-30 14:42:30.875  7617  7972 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 14:42:30.877  7617  7972 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f1f407d on behalf of 
08-30 14:42:30.877  7617  7972 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 14:42:30.879  7617  7972 V BluetoothOppNotification: inbound notification was removed.
08-30 14:42:30.879  7617  7972 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 14:42:30.880  7617  7972 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23a2bb72 on behalf of 
08-30 14:42:31.049   319   917 D SoftapController: Softap fwReload - Ok
,08-30 14:42:31.053  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 14:42:31.053  1035  1117 D Tethering: InitialState.processMessage what=4
,08-30 14:42:31.073  1035  1377 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (676ms)
08-30 14:42:31.077  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 14:42:31.097   319   917 D CommandListener: Setting iface cfg
08-30 14:42:31.097   319   917 D CommandListener: Trying to bring down wlan0
08-30 14:42:31.098   319   917 D CommandListener: Clearing all IP addresses on wlan0
08-30 14:42:31.111  1035  1377 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-30 14:42:31.107  7980  7980 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:31.119  1035  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:42:31.119  1035  1377 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:42:31.119  1035  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 14:42:31.117  7980  7980 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:31.141  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 14:42:31.155  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-30 14:42:31.158  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:31.159  1035  1377 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 14:42:31.160  1035  1377 D WifiMonitor: connecting to supplicant
08-30 14:42:31.160  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 14:42:31.164  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 14:42:31.165  6823  6823 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 14:42:31.165  6823  6823 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 14:42:31.165  6823  6823 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 14:42:31.167  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 14:42:31.168  6823  6823 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 14:42:31.169  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 14:42:31.169  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 14:42:31.169  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 14:42:31.169  6823  6823 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 14:42:31.169  6823  6823 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 14:42:31.173  7980  7980 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 14:42:31.177  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 14:42:31.177  6823  6823 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 14:42:31.177  6823  6823 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 14:42:31.177  6823  6823 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 14:42:31.177  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 14:42:31.178  6823  6823 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 14:42:31.178  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 14:42:31.178  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 14:42:31.178  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 14:42:31.178  6823  6823 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 14:42:31.179  6823  6823 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 14:42:31.214  7980  7980 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 14:42:31.214  7980  7980 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 14:42:31.229  1035  1944 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7997 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 14:42:31.252   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 20.527ms
,08-30 14:42:31.272   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 398us total 19.823ms
,08-30 14:42:31.289   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 347us total 16.455ms
,08-30 14:42:31.296  7980  7980 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 14:42:31.329  1035  1058 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8019 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 14:42:31.333  7997  8017 W FormManager: Network not available. Please check & try again.
08-30 14:42:31.338  7997  8018 V FormManager: Network unavailable.
08-30 14:42:31.340  7997  8018 V FormManager: Network unavailable.
,08-30 14:42:31.352  7980  7980 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-30 14:42:31.355  7980  7980 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-30 14:42:31.356  7980  7980 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 14:42:31.356  1035  1377 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 14:42:31.356  1035  1377 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 14:42:31.357  1035  1377 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 14:42:31.357  1035  8038 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 14:42:31.357  1035  8038 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 14:42:31.357  1035  8038 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 14:42:31.357  1035  8038 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 14:42:31.357  1035  1377 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 14:42:31.357  1035  8038 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 14:42:31.357  1035  8038 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 14:42:31.357  1035  1377 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:31.358  1035  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:31.358  1035  1377 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:31.358  1035  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:31.358  1035  1377 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 14:42:31.358  1035  1377 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 14:42:31.359  1035  1377 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 14:42:31.359  1035  1377 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 14:42:31.359  1035  1377 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 14:42:31.360  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:31.360  1035  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:42:31.360  1035  1377 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:42:31.360  1035  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 14:42:31.360  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:31.360  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:31.360  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:31.360  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:42:31.360  1035  1377 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 14:42:31.361  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:31.361  1035  1377 D WifiNative-wlan0: SET update_config 1: returned true
08-30 14:42:31.361  1035  1377 D WifiConfigStore: Loading config and enabling all networks 
08-30 14:42:31.361  1035  1377 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 14:42:31.362  1927  1927 D WfdService: Waiting for WifiP2p enabling
08-30 14:42:31.362  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 14:42:31.363  1035  1377 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 14:42:31.363  1035  1421 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 14:42:31.367  1035  1377 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-30 14:42:31.367  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:31.367  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:31.367  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:31.367  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:31.367  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:31.367  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:31.367  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:31.367  6717  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:42:31.369  6717  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:42:31.373  1035  1377 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 14:42:31.374  1035  1377 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 14:42:31.374  1035  1377 D WifiStateMachine: enableVerboseLogging : level 2
08-30 14:42:31.374  1035  1377 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 14:42:31.374  1035  1377 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 14:42:31.374  1035  1377 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 14:42:31.375  1035  1377 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 14:42:31.375  1035  1377 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 14:42:31.375  1035  1377 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 14:42:31.375  1035  1377 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 14:42:31.375  1035  1377 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 14:42:31.375  1035  1377 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,08-30 14:42:31.376  1035  1377 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 14:42:31.376  1035  1377 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 14:42:31.376  1035  1377 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 14:42:31.376  1035  1377 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 14:42:31.376  1035  1377 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 14:42:31.376  1035  1377 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 14:42:31.377  1927  1927 D WfdsService: Supplicant Connection state is changed : true
08-30 14:42:31.377  1927  2286 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 14:42:31.377  1927  2286 D WfdsService: Set the WFDS Monitor: true
08-30 14:42:31.377  1927  2286 D WfdsMonitor: WfdsMonitorThread create
08-30 14:42:31.377  1035  1377 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 14:42:31.377  1927  2286 D WfdsMonitor: WFDS Monitor is created and started
08-30 14:42:31.377  1927  2286 D WfdsService: WiFi: Supplicant connection re-established
08-30 14:42:31.377  1035  1377 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 14:42:31.377  1035  1377 D WifiNative-HAL: Setting external_sim to 1
08-30 14:42:31.377  1035  1377 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 14:42:31.378  1035  1377 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 14:42:31.378  1035  1377 I WifiNative-HAL: startHal
08-30 14:42:31.378  1035  1377 D wifi    : setting scan oui 0xaf67bb20
08-30 14:42:31.378  1927  8039 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 14:42:31.378  1035  1377 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 14:42:31.378  1035  1377 I WifiNative-HAL: startHal
08-30 14:42:31.378  1035  1377 D wifi    : setting scan oui 0xaf67bb20
08-30 14:42:31.378  1035  1377 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 14:42:31.378  1927  8039 E CtrlSupplicant: Succeed to open control connection
08-30 14:42:31.378  1035  1377 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 14:42:31.378  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 14:42:31.379  7980  7980 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 14:42:31.379  1927  8039 E CtrlSupplicant: Succeed to open monitor connection
08-30 14:42:31.379  1035  1377 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 14:42:31.379  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 14:42:31.379  7980  7980 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 14:42:31.379  7683  7683 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:31.379  1035  1377 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 14:42:31.380  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 14:42:31.380  7980  7980 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 14:42:31.380  1035  1377 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 14:42:31.380  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 14:42:31.380  7980  7980 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 14:42:31.380  1927  8039 D WfdsMonitor: Supplicant connection established
08-30 14:42:31.380  1035  1377 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 14:42:31.380  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 14:42:31.380  1927  2286 D WfdsService: Connected to the supplicant for wfds
08-30 14:42:31.380  7980  7980 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 14:42:31.381  1035  1377 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 14:42:31.381  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 14:42:31.381,  7980  7980 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 14:42:31.381  1035  1377 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 14:42:31.381  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 14:42:31.381  7980  7980 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 14:42:31.381  1035  1377 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 14:42:31.382  1035  1377 E WifiNative: : [223,129,685 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 14:42:31.382  1035  1377 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 14:42:31.382  1035  1377 D WifiNative-wlan0: RECONNECT: returned true
08-30 14:42:31.382  1035  1377 D WifiNative-wlan0: doString: [STATUS]
08-30 14:42:31.382  1035  8038 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 14:42:31.383  1035  8038 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 14:42:31.383  1035  1377 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 14:42:31.383  1035  1377 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:42:31.383  1035  1377 D WifiNative-wlan0: SET ps 1: returned true
08-30 14:42:31.383  1035  1375 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.383  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 14:42:31.384  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-30 14:42:31.384  1035  1541 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.384  1035  1541 I WifiNative-HAL: startHal
08-30 14:42:31.384  1035  1541 D wifi    : getting scan capabilities on interface[1] = 0xaf67bb20
08-30 14:42:31.384  1035  1541 D wifi    : failed to get capabilities : -3
08-30 14:42:31.384  1035  1541 E WifiScanningService: could not get scan capabilities
08-30 14:42:31.384  1035  1542 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.384   319   917 D CommandListener: Setting iface cfg
08-30 14:42:31.384   319   917 D CommandListener: Trying to bring up p2p0
08-30 14:42:31.385  1035  1377 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 14:42:31.385  1035  1375 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 14:42:31.385  1035  1377 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 14:42:31.385  1035  1375 D LGWifiP2pService: P2pEnablingState
08-30 14:42:31.385  1035  1375 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.385  1035  1375 D LGWifiP2pService: P2p socket connection successful
08-30 14:42:31.385  1035  1375 D LGWifiP2pService: P2pEnabledState
08-30 14:42:31.385  1035  1377 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 14:42:31.385  1035  1375 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 14:42:31.386  1035  1377 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 14:42:31.386  1035  1375 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 14:42:31.386  1035  1377 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 14:42:31.386  1035  1377 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 14:42:31.386  1035  1377 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 14:42:31.386  1035  1377 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 14:42:31.386  7980  7980 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 14:42:31.387  1035  1375 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 14:42:31.387  1035  1377 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 14:42:31.387  1035  1375 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 14:42:31.387  1035  1375 D WifiNative-p2p0: SET device_name G3: returned true
08-30 14:42:31.387  1035  1375 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 14:42:31.387  1035  1375 D LGWifiP2pService: before postfix = G3
08-30 14:42:31.387  1035  1375 D WifiServerServiceExt: postfix byte check : 2
08-30 14:42:31.387  1035  1375 D LGWifiP2pService: after postfix = G3
08-30 14:42:31.387  1035  1375 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 14:42:31.387  1035  1375 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 14:42:31.387  1035  1375 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 14:42:31.388  1035  1375 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 14:42:31.388  1035  1375 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 14:42:31.388  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 14:42:31.388  1035  1375 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 14:42:31.388  1035  1375 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 14:42:31.388  1927  1927 D WfdsService: WifiP2pState is changed : true
08-30 14:42:31.388  1035  1377 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 14:42:31.388  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 14:42:31.388  1035  1377 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 14:42:31.388  1035  1377 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 14:42:31.388  1035  1375 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 14:42:31.388  1035  1375 D WifiNative-HAL: p2pGetDeviceAddress
08-30 14:42:31.388  7980  7980 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 14:42:31.388  1035  1375 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-30 14:42:31.388  1927  1927 D WfdsService: isConnected: false
08-30 14:42:31.389  1927  2286 D WfdsService: Receive the WFDS_ENABLE Method
08-30 14:42:31.389  1927  2286 D WfdsService: Set the WFDS Monitor: true
08-30 14:42:31.389  1927  2286 D WfdsService: Connected to the supplicant for wfds
08-30 14:42:31.389  1035  1377 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 14:42:31.389  1927  2286 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 14:42:31.389  7980  7980 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 14:42:31.389  1035  1377 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 14:42:31.389  1927  2286 D WfdsService: selectPreferredScanChannel [36]
08-30 14:42:31.389  1927  2286 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 14:42:31.389  1035  1377 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 14:42:31.389  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 14:42:31.390  7980  7980 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 14:42:31.390  7980  7980 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:31.391  7980  7980 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 14:42:31.391  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 14:42:31.391  7980  7980 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.391  1035  1377 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 14:42:31.391  1035  8038 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 14:42:31.391  1927  8039 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:31.391  1035  8038 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:31.392  1035  8038 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:31.392  1035  8038 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:31.392  1035  1377 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 14:42:31.392  1035  8038 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:31.392  1035  8038 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.392  1035  8038 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.392  1035  8038 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.392  1035  1377 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 14:42:31.392  7980  7980 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.392  1927  8039 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:31.392  1035  8038 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:31.392  1035  1377 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 14:42:31.392  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 14:42:31.392  1035  8038 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.392  1035  8038 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.392  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 14:42:31.392  1035  8038 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.392  1035  1375 D LGWifiP2pService: DeviceAddress: 
08-30 14:42:31.392  1927  1927 D WfdsService: Update P2p Interface State: 3
08-30 14:42:31.392  1035  1375 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 14:42:31.393  7980  7980 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 14:42:31.393  7980  7980 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 14:42:31.393  1035  8038 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 14:42:31.393  1035  8038 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 14:42:31.393  1035  8038 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 14:42:31.393  1035  8038 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 14:42:31.393  1035  1377 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 14:42:31.393  1035  1377 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 14:42:31.394  1035  1375 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 14:42:31.394  1035  1377 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 14:42:31.394  1035  1377 D WifiNative-wlan0: doBoolean: SCAN
08-30 14:42:31.394  1035  1375 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 14:42:31.394  1035  1377 D WifiNative-wlan0: SCAN: returned false
08-30 14:42:31.395  1035  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=223143  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 14:42:31.396  1035  1375 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 14:42:31.396  1035  1375 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 14:42:31.396  1035  1375 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 14:42:31.396  1035  1375 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 14:42:31.399  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:31.399  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:31.399  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 14:42:31.400  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:31.400  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:31.401  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:31.402  1035  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=223150  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 14:42:31.403  1035  1377 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:42:31.403  1035  1377 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:42:31.403  1035  1377 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-30 14:42:31.404  6717  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:42:31.404  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:31.404  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:31.404  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:31.404  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:31.404  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:42:31.404  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:42:31.404  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:42:31.404  1035  1377 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:42:31.404  1035  1375 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 14:42:31.404  1035  1375 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 14:42:31.405  1035  1377 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:42:31.405  1035  1375 D LGWifiP2pService: InactiveState
08-30 14:42:31.405  1035  1375 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.405  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.405  1035  1375 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 14:42:31.406  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:42:31.406  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 14:42:31.406  7980  7980 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 14:42:31.406  6717  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:42:31.406  7980  7980 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:31.406  1035  8038 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 14:42:31.406  1035  8038 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:31.407  1035  8038 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:31.407  1035  8038 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:42:31.407  7980  7980 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 14:42:31.407  7980  7980 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.407  1927  8039 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 14:42:31.407  1927  8039 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:31.407  7980  7980 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.407  8019  8019 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:42:31.408  1927  8039 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:31.408  1035  8038 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:31.408  1035  8038 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.408  1035  8038 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.408  1035  8038 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.408  1035  8038 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:42:31.408  1035  8038 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.408  1035  8038 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.408  1035  8038 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:42:31.408  1035  1375 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 14:42:31.408  1035  1375 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.408  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.408  1035  1375 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.408  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.408  1035  1375 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.408  1035  1375 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.408  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.408  1035  1375 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.408  1035  1375 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.408  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.408  1035  1375 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.409  1927  2286 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 14:42:31.409  1035  1375 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.409  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.410  1035  1375 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:31.410  1035  1035 E WifiServerServiceExt: No p2p device connected
08-30 14:42:31.411  6717  6772 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-30 14:42:31.412  6717  6772 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 14:42:31.414  6717  6772 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2c10800a Bundle[{}]
08-30 14:42:31.414  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 14:42:31.415  6717  6772 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 14:42:31.415  6717  6772 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 14:42:31.415  6717  6772 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 14:42:31.416  6717  6772 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 14:42:31.417  6717  6772 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 14:42:31.417  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:31.418  6717  6772 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 14:42:31.419  1035  1980 I ActivityManager: Killing 7116:com.lge.drmservice/u0a62 (adj 15): empty #17
08-30 14:42:31.423  6717  6772 I System.out: Running OutgoingSocketThread
08-30 14:42:31.424  6717  8042 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 866)
08-30 14:42:31.425  6717  8042 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 34528
08-30 14:42:31.425  6717  8042 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 14:42:31.441  1035  1057 W libprocessgroup: failed to open /acct/uid_10062/pid_7116/cgroup.procs: No such file or directory
08-30 14:42:31.453  8019  8019 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:42:31.455  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 14:42:31.458  7997  8044 W FormManager: Network not available. Please check & try again.
08-30 14:42:31.460  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:31.462  7997  8045 V FormManager: Network unavailable.
08-30 14:42:31.464  7997  8045 V FormManager: Network unavailable.
08-30 14:42:31.472  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 14:42:31.473  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 14:42:31.474  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 14:42:31.477  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:42:31.481  4330  8046 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 14:42:31.483  4330  8047 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 14:42:31.483  4330  8047 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 14:42:31.533  1035  2035 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8048 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 14:42:31.657  8048  8048 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 14:42:31.657  8048  8048 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 14:42:31.665  8048  8048 V [BNRBootReceiver]: Boot Receiver Return
08-30 14:42:31.667  8048  8048 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-30 14:42:31.714  1035  1890 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8066 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 14:42:31.716  1035  1890 I ActivityManager: Killing 7133:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-30 14:42:31.761  1035  1722 W libprocessgroup: failed to open /acct/uid_10085/pid_7133/cgroup.procs: No such file or directory
,08-30 14:42:31.789  8066  8066 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 14:42:31.815  8066  8066 D PluginManager: init()
,08-30 14:42:32.027  1035  8038 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 14:42:32.027  1035  8038 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-30 14:42:32.040  1035  8038 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 14:42:32.040  1035  8038 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-30 14:42:32.040  1035  8038 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 14:42:32.041  1035  1377 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 14:42:32.041  7980  7980 E wpa_supplicant: USIM:  scard_init function
08-30 14:42:32.041  1035  1377 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 14:42:32.041  1035  1377 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 14:42:32.042  7980  7980 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 14:42:32.042  1035  1377 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 14:42:32.042  1035  1377 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 14:42:32.043  1035  8038 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 14:42:32.043  1035  8038 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 14:42:32.056  1035  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=223803  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 14:42:32.061  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:32.061  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:32.061  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.061  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.061  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 14:42:32.062  1035  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=223810  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 14:42:32.065  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.065  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.065  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 14:42:32.066  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:32.067  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:42:32.068  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 14:42:32.071  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:32.071  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 14:42:32.075  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:32.155  7980  7980 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-30 14:42:32.155  1035  8038 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 14:42:32.155  1035  8038 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 14:42:32.156  1035  8038 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 14:42:32.156  1035  8038 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 14:42:32.156  1035  8038 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:42:32.156  1035  8038 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:42:32.156  1035  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=223904  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 14:42:32.157  1035  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=223904  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 14:42:32.157  1035  1377 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223905
08-30 14:42:32.157  1035  1377 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223905
08-30 14:42:32.158  1035  1377 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223905
,08-30 14:42:32.158  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223906
08-30 14:42:32.158  1035  1377 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223906
,08-30 14:42:32.159  1035  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=223906  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 14:42:32.163  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 14:42:32.164  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:32.164  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:32.165  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.165  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.165  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 14:42:32.165  1035  8038 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:42:32.166  1035  8038 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:42:32.166  7980  7980 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 14:42:32.166  7980  7980 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 14:42:32.169  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.169  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.169  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 14:42:32.170  1035  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=223918  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-30 14:42:32.171  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:42:32.171  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 14:42:32.172  1035  1377 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:32.173  1035  1377 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:32.173  1035  1377 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:32.173  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:32.173  1035  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:42:32.174  1035  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=223921  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 14:42:32.174  1035  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=223922  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 14:42:32.176  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:42:32.176  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 14:42:32.176  1035  8038 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 14:42:32.177  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:32.177  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:42:32.177  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 14:42:32.178  1035  8038 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 14:42:32.178  1035  8038 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 14:42:32.178  1035  8038 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 14:42:32.178  1035  8038 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 14:42:32.178  1035  8038 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 14:42:32.178  1035  8038 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:42:32.178  1035  8038 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:42:32.179  1035  1377 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=223926
08-30 14:42:32.179  1035  1377 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=223927
08-30 14:42:32.179  1035  1377 D WifiNative-wlan0: doString: [STATUS]
08-30 14:42:32.180  1035  8038 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:42:32.180  1035  8038 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:42:32.180  1035  1377 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 14:42:32.183  1035  1377 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 14:42:32.185  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:32.185  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 14:42:32.188  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:32.191  1035  1377 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 14:42:32.191  1035  1377 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 14:42:32.196  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.196  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 14:42:32.196  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 14:42:32.197  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.197  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.197  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 14:42:32.199  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:32.199  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:32.200  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:32.201  1035  1364 V AlarmManager: RTC_WAKEUP set : Alarm{385e9b3a type 0 when 1472560946279 com.google.android.gms} when 1472560946279
08-30 14:42:32.202  1035  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1c6ff3eb type 2 when 221981 android} when 221981
08-30 14:42:32.202  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:32.202  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:32.203  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:32.204  1035  1377 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 14:42:32.204  1035  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 14:42:32.204  1035  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 14:42:32.204  1035  1434 D ConnectivityService: Got NetworkAgent Messenger
08-30 14:42:32.204  1035  1434 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 14:42:32.205  1035  1434 D ConnectivityService: NetworkAgent connected
08-30 14:42:32.205  1035  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 14:42:32.205  1035  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 14:42:32.208  1035  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 14:42:32.208  1035  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 14:42:32.208  1035  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-30 14:42:32.210  1035  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 14:42:32.210  1035  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 14:42:32.214  1035  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 14:42:32.216   319   917 D CommandListener: Setting iface cfg
08-30 14:42:32.222  1035  1377 E WifiStateMachine: Start Dhcp Watchdog 3
08-30 14:42:32.222  1035  1377 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=223970  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:42:32.223  1035  1377 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=223970  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-30 14:42:32.224  1035  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=223971  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:42:32.224  1035  1377 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=223972  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:42:32.225  1035  1377 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=223972  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:42:32.225  1035  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=223973  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:42:32.226  1035  1377 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14178] from screen [on:0 period:-612830302] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 14:42:32.227  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-612830301] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 14:42:32.227  1035  1377 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 14:42:32.227  1035  8090 D DhcpStateMachine: StoppedState
08-30 14:42:32.228  1035  8090 D DhcpStateMachine: StoppedState{ when=-6ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:32.228  1035  8090 D DhcpStateMachine: WaitBeforeStartState
08-30 14:42:32.230  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:32.231  1035  1434 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-30 14:42:32.232  1035  1377 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 14:42:32.232  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:32.232  1035  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:32.233  1035  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:32.233  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:32.233  1035  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:32.234  1035  1434 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 14:42:32.237  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:42:32.237  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 14:42:32.238  1035  1377 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=106,0,0
08-30 14:42:32.238  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=106,0,0
08-30 14:42:32.238  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 14:42:32.238  7980  7980 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 14:42:32.238  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:42:32.238  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 14:42:32.239  1035  1377 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 14:42:32.239  1035  1377 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 14:42:32.239  1035  1377 D WifiNative-wlan0: SET ps 0: returned true
08-30 14:42:32.239  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 14:42:32.239  7980  7980 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 14:42:32.239  1035  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 14:42:32.240  1035  1377 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 14:42:32.240  1035  1377 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 14:42:32.240  1035  1377 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 14:42:32.240  1035  1375 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@27a2c942 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:32.240  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@27a2c942 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:32.241  1035  8090 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:32.241  1035  8090 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 14:42:32.242   319   917 D CommandListener: Setting iface cfg
08-30 14:42:32.242   319   917 D CommandListener: Trying to bring up wlan0
08-30 14:42:32.243  1035  1377 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 14:42:32.244  1035  1377 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:32.244  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:32.244  1035  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:32.245  1035  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:32.245  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:32.245  1035  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:42:32.246  1035  1434 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 14:42:32.246  1035  1377 E WifiStateMachine:  ObtainingIpState CMD_POST,_DHCP_ACTION 1 0 OK  v4
08-30 14:42:32.246  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 14:42:32.246  1035  1375 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:32.246  1035  1375 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:32.247  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 14:42:32.247  7980  7980 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 14:42:32.247  1035  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 14:42:32.247  1035  1377 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 14:42:32.247  7980  7980 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 14:42:32.248  1035  1377 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 14:42:32.248  1035  1377 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:42:32.264  1035  1377 D WifiNative-wlan0: SET ps 1: returned true
08-30 14:42:32.265  1035  1377 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 14:42:32.265  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 14:42:32.265  1035  1377 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-30 14:42:32.268  1035  1434 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 14:42:32.268  1035  1434 D ConnectivityService: ignoring duplicate network state non-change
08-30 14:42:32.270  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.270  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.270  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 14:42:32.271  1035  1434 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 14:42:32.271  1035  1434 D ConnectivityService: Adding iface wlan0 to network 102
08-30 14:42:32.272  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:32.272  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:32.273  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:32.274  1035  1377 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 14:42:32.288  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.288  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.288  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 14:42:32.291  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 14:42:32.294  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 14:42:32.294  1035  1434 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 14:42:32.294  1035  1434 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-30 14:42:32.295  1035  1434 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 14:42:32.296   319   917 E Netd    : netlink response contains error (File exists)
08-30 14:42:32.296  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:32.296  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:42:32.296  1035  1434 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-30 14:42:32.296  1035  1434 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 14:42:32.296  1035  1434 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
,08-30 14:42:32.296  1035  1434 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-30 14:42:32.296  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:32.298  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.298  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.298  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 14:42:32.298  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 14:42:32.298  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:32.298  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-30 14:42:32.299  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:32.300  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.300  1035  1434 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 14:42:32.300  1035  1434 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 14:42:32.300  1035  1434 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 14:42:32.301  1035  1434 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 14:42:32.301  1035  1434 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 14:42:32.301  1035  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:32.301  1035  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 14:42:32.301  1035  1434 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:42:32.301  1035  1434 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 14:42:32.301  1035  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:42:32.301  1035  1434 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:32.301  1035  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 14:42:32.301  1035  1434 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 14:42:32.301  1035  1434 D ConnectivityService: currentScore = 0, newScore = 20
08-30 14:42:32.301  1035  1434 D ConnectivityService:    accepting network in place of null
08-30 14:42:32.301  1035  1434 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:32.301  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:42:32.301  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 14:42:32.301  1035  1377 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:32.301  1035  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 14:42:32.302  1035  1434 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 14:42:32.302  1035  1434 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 14:42:32.303  1035  1434 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 14:42:32.303  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:32.303  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 14:42:32.303  1035  1434 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:42:32.303  1035  1434 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 14:42:32.304  1035  1434 D ConnectivityService: Switching to new default network: Ne,tworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 14:42:32.304  1035  1434 D ConnectivityService: validation of new default Network = false
08-30 14:42:32.304  1035  1434 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 14:42:32.304  1035  1434 D DSQN    : enableDataServiceNotify 
08-30 14:42:32.304  1035  1434 D DSQN    : start dsqn bin
08-30 14:42:32.304   319  8105 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 14:42:32.305  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 14:42:32.306  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 14:42:32.306  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 14:42:32.307  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-30 14:42:32.310  1035  1434 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 14:42:32.307  8106  8106 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:32.307  8106  8106 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:32.311  1035  1434 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:32.311  1035  1434 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:42:32.311  1035  1434 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:42:32.312  1586  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 14:42:32.319  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:42:32.319  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-30 14:42:32.319  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:32.319  8106  8106 E DSQN    : DSQN ssw
,08-30 14:42:32.320  8066  8066 W ExternalStrings: load override strings
08-30 14:42:32.320  8066  8066 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 14:42:32.320  8066  8066 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 14:42:32.322  1035  1374 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 14:42:32.325  8066  8066 D StatusProvider: onCreate
,08-30 14:42:32.333  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 14:42:32.333  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:32.334  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:32.361   319  8105 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-30 14:42:32.363  8066  8066 V Signer  : override build config not found
,08-30 14:42:32.363  8066  8066 D Signer  : value of property debug is false
08-30 14:42:32.387  8066  8066 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-30 14:42:32.387  8066  8066 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-30 14:42:32.387  8066  8066 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-30 14:42:32.387  8066  8066 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-30 14:42:32.387  8066  8066 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-30 14:42:32.387  8066  8066 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-30 14:42:32.388  8066  8066 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-30 14:42:32.388  8066  8066 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-30 14:42:32.388  8066  8066 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-30 14:42:32.388  8066  8066 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-30 14:42:32.388  8066  8066 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-30 14:42:32.388  8066  8066 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
,08-30 14:42:32.388  8066  8066 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-30 14:42:32.396  8066  8066 V LGMDMManager: Create singleton instance
08-30 14:42:32.397   319  8105 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-30 14:42:32.426  6717  6772 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 867)
,08-30 14:42:32.426  6717  6772 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 867)
08-30 14:42:32.431  8066  8066 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-30 14:42:32.436  6717  6772 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 872)
,08-30 14:42:32.438  6717  6772 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 14:42:32.438  6717  6772 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 873)
08-30 14:42:32.443  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 14:42:32.443  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bb91261 added. We now have 2 listener(s)
08-30 14:42:32.444  1035  1057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:32.445  1035  8090 D DhcpStateMachine: DHCPV4 request on wlan0
,08-30 14:42:32.445   319   916 D LGDataListener: argv[0]=dsqncommand
08-30 14:42:32.446   319   916 D LGDataListener: argv[1]=wlan0
08-30 14:42:32.446   319   916 D LGDataListener: argv[2]=1
08-30 14:42:32.446   319   916 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 14:42:32.446  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 14:42:32.446  1035  1115 D DSQN    : start to monitor internet connection
08-30 14:42:32.447  1035  8090 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-30 14:42:32.447  1035  8090 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 14:42:32.449  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:42:32.449  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:42:32.449  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 14:42:32.450  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:32.450  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96c9186 added. We now have 9 listener(s)
08-30 14:42:32.450  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:32.451  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,08-30 14:42:32.454  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:42:32.447  8114  8114 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:32.460  6717  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:42:32.460  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:32.460  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:32.460  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:32.460  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:32.460  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:32.460  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:42:32.460  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:42:32.461  6717  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:32.462  6717  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:42:32.462  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:42:32.457  8114  8114 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:42:32.462  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23ba6274 added. We now have 3 listener(s)
08-30 14:42:32.462  1035  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:32.464  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:42:32.465  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:32.466  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:42:32.466  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:42:32.467  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:42:32.467  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:32.467  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a13739d added. We now have 10 listener(s)
08-30 14:42:32.467  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:32.467  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:32.467  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:32.467  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:32.467  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:32.467  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.467  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 14:42:32.467  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:42:32.467  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bb91261 removed from the list
08-30 14:42:32.467  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:32.467  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96c9186 removed from the list
08-30 14:42:32.467  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:32.467  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.468  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.468  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.469  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:32.469  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:32.469  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:32.469  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96c9186 not in the list
08-30 14:42:32.469  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.469  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.470  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 14:42:32.470  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:32.470  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:32.470  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a13739d removed from the list
08-30 14:42:32.470  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:32.471  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.471  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.471  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:42:32.471  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23ba6274 removed from the list
08-30 14:42:32.471  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:42:32.471  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff04012 added. We now have 2 listener(s)
08-30 14:42:32.472  1035  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:32.474  1035  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 12:42:32 GMT], X-Android-Received-Millis=[1472560952473], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472560952445]}
08-30 14:42:32.474  1035  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-30 14:42:32.474  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:42:32.474  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:42:32.474  8114  8114 I dhcpcd  : version 5.5.6 starting
08-30 14:42:32.474  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:42:32.474  1035  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 14:42:32.474  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:32.474  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cbcf3e3 added. We now have 9 listener(s)
08-30 14:42:32.474  1035  1434 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 14:42:32.474  1035  1434 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 14:42:32.475  1035  1434 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 14:42:32.475  1035  1434 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:42:32.475  1035  1434 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 14:42:32.475  1035  1434 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 14:42:32.475  1035  1434 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,08-30 14:42:32.475  1035  1434 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:32.475  1035  1434 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:42:32.475  1035  1434 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:42:32.475  1035  1434 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 14:42:32.476  1035  1434 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 14:42:32.476  1035  1377 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:32.476  1035  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 14:42:32.477  1586  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 14:42:32.477  8114  8114 E dhcpcd  : get_duid: m
08-30 14:42:32.477  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:32.477  8114  8114 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 14:42:32.477  8114  8114 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 14:42:32.478  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:32.478  8066  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 14:42:32.478  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 14:42:32.478  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:32.487  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 14:42:32.491  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:42:32.495  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:42:32.500  6717  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:42:32.500  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:32.500  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:32.500  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:32.500  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:32.500  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:32.500  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:42:32.500  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:42:32.501  6717  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:32.502  6717  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:42:32.502  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:42:32.502  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23b8ac99 added. We now have 3 listener(s)
08-30 14:42:32.502  1035  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:32.503  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:32.506  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:42:32.506  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:42:32.506  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:42:32.506  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:32.506  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@118e4b5e added. We now have 10 listener(s)
08-30 14:42:32.506  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:32.506  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:42:32.506  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:42:32.506  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:42:32.506  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:42:32.506  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:42:32.507  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:32.512  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 14:42:32.513  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:32.514  1586  1586 D StatusBar.Ne,tworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:42:32.516  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 14:42:32.516  1035  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 14:42:32.520  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:32.524  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 14:42:32.526  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 14:42:32.527  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 14:42:32.529  8114  8114 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-30 14:42:32.529  8114  8114 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 14:42:32.529  8114  8114 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 14:42:32.529  8114  8114 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 14:42:32.529  8114  8114 D dhcpcd  : wlan0: sending REQUEST (xid 0x3d9d68c3), next in 3.75 seconds
08-30 14:42:32.574  1035  2033 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8125 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-30 14:42:32.575  1035  2033 I ActivityManager: Killing 7165:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-30 14:42:32.594  8114  8114 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 14:42:32.624  8066  8115 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 14:42:32.630  8114  8114 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 14:42:32.630  8114  8114 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 14:42:32.631  8114  8114 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 14:42:32.631  8114  8114 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 14:42:32.631  8114  8114 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 14:42:32.631  8114  8114 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 14:42:32.631  8114  8114 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 14:42:32.631  8114  8114 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 14:42:32.786  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 14:42:32.799  6717  6772 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 14:42:32.799  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:32.799  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 14:42:32.803  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 14:42:32.803  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:32.803  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:32.803  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 14:42:32.803  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.803  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:42:32.803  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:42:32.803  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff04012 removed from the list
08-30 14:42:32.803  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:32.803  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cbcf3e3 removed from the list
08-30 14:42:32.803  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:32.803  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.806  1035  1057 W libprocessgroup: failed to open /acct/uid_10093/pid_7165/cgroup.procs: No such file or directory
08-30 14:42:32.810  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.810  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.811  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:32.811  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:32.811  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:32.811  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cbcf3e3 not in the list
08-30 14:42:32.811  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.811  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.812  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:32.813  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:32.813  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:32.813  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:32.813  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:32.813  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@118e4b5e removed from the list
08-30 14:42:32.813  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:32.813  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.813  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.813  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:42:32.813  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23b8ac99 removed from the list
08-30 14:42:32.814  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:42:32.814  6717  6772 V org.thaliproj,ect.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cde7955 added. We now have 2 listener(s)
08-30 14:42:32.815  1035  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:32.818  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:42:32.818  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:42:32.818  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:42:32.819  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:32.819  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fbf6a added. We now have 9 listener(s)
08-30 14:42:32.819  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:32.822  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 14:42:32.828  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:42:32.833  6717  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:42:32.833  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:32.833  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:32.833  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:32.833  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:32.833  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:32.833  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:42:32.833  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:42:32.834  6717  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:32.835  6717  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:42:32.835  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:42:32.835  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2feb5cf8 added. We now have 3 listener(s)
08-30 14:42:32.835  1035  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 14:42:32.837  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:42:32.838  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:42:32.838  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:42:32.838  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:42:32.838  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:32.839  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5a55d1 added. We now have 10 listener(s)
08-30 14:42:32.839  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:32.839  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:42:32.839  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:42:32.840  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:42:32.840  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:42:32.840  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:42:32.840  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:42:32.843  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:32.844  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 14:42:32.844  1035  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:32.848  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 14:42:32.850  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 14:42:32.851  8125  8125 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 14:42:32.853  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 14:42:32.854  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:42:32.855  6717  6772 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 14:42:32.856  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:32.856  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:32.856  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:32.856  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:32.856  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.856  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:42:32.856  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:42:32.856  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cde7955 removed from the list
08-30 14:42:32.856  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:32.856  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fbf6a removed from the list
08-30 14:42:32.856  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:32.857  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.857  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.857  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.858  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:32.858  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:32.858  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:32.858  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fbf6a not in the list
08-30 14:42:32.858  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.858  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.859  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:32.860  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:32.860  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:32.860  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:32.860  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:32.860  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5a55d1 removed from the list
08-30 1,4:42:32.860  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:32.860  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.860  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.860  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:42:32.860  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2feb5cf8 removed from the list
08-30 14:42:32.861  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:42:32.861  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f550a4 added. We now have 2 listener(s)
08-30 14:42:32.861  1035  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 14:42:32.867  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:42:32.867  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:42:32.867  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:42:32.867  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:32.867  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@add7e0d added. We now have 9 listener(s)
08-30 14:42:32.868  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:32.868  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 14:42:32.870  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:42:32.873  6717  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:42:32.873  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:32.873  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:32.873  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:32.873  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:32.873  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:32.873  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:42:32.873  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:42:32.874  6717  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:32.874  6717  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:42:32.874  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:42:32.875  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24c29bd3 added. We now have 3 listener(s)
08-30 14:42:32.875  1035  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 14:42:32.877  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:32.879  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:42:32.879  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 14:42:32.879  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:42:32.879  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:32.879  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a88d310 added. We now have 10 listener(s)
08-30 14:42:32.880  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:32.880  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:42:32.880  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:42:32.880  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:42:32.880  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:42:32.880  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:42:32.881  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:32.883  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 14:42:32.883  1035  1722 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:32.888  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 14:42:32.888  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 14:42:32.890  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 14:42:32.890  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 14:42:32.894  8125  8125 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-30 14:42:32.895  6717  6772 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 14:42:32.896  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:32.896  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:32.896  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:32.896  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:32.896  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.897  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:42:32.897  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:42:32.897  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f550a4 removed from the list
08-30 14:42:32.897  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:32.897  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@add7e0d removed from the list
08-30 14:42:32.897  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:32.897  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.897  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.897  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.898  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:32.898  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:32.898  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:32.898  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@add7e0d not in the list
08-30 14:42:32.898  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.898  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.898  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:32.899  6717  6772 D BluetoothLeScanner: could not find callback wrapper
08-30 14:42:32.899  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:42:32.899  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:32.899  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:32.899  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a88d310 removed from the list
08-30 14:42:32.899  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:32.899  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.b,luetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.899  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.899  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:42:32.899  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24c29bd3 removed from the list
08-30 14:42:32.899  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:42:32.899  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2391222f added. We now have 2 listener(s)
08-30 14:42:32.901  1035  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 14:42:32.903  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:42:32.903  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:42:32.903  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:42:32.903  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:32.903  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c90103c added. We now have 9 listener(s)
08-30 14:42:32.903  6717  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:32.904  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 14:42:32.905  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:42:32.907  6717  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:42:32.907  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:42:32.907  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:42:32.907  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:42:32.907  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:42:32.907  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:32.907  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:42:32.907  6717  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:42:32.908  6717  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:42:32.908  6717  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:42:32.908  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:42:32.908  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12aed71a added. We now have 3 listener(s)
08-30 14:42:32.909  1035  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:42:32.910  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:32.910  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:42:32.910  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:42:32.910  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:42:32.911  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:42:32.911  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3217b24b added. We now have 10 listener(s)
08-30 14:42:32.911  6717  6772 D, org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:42:32.911  6717  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:42:32.911  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:32.911  6717  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:42:32.911  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:32.911  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.911  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:42:32.911  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:42:32.911  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2391222f removed from the list
08-30 14:42:32.911  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:32.911  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c90103c removed from the list
08-30 14:42:32.912  6717  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:42:32.912  6717  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:42:32.912  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.912  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.912  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.913  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 14:42:32.913  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:32.913  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:32.913  6717  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c90103c not in the list
08-30 14:42:32.913  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.913  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.913  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:42:32.913  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:42:32.913  6717  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:42:32.913  6717  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3217b24b removed from the list
08-30 14:42:32.913  6717  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:42:32.913  6717  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:42:32.913  6717  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:42:32.913  6717  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:42:32.913  6717  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12aed71a removed from the list
08-30 14:42:32.914  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 14:42:32.914  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 14:42:32.914  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 14:42:32.914  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:42:32.914  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 14:42:32.914  6717  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 14:42:32.922  6717  8170 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 880, name: My test thread name)
08-30 14:42:32.922  6717  8170 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 880, thread name: My test thread name)
08-30 14:42:32.922  6717  8170 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 880, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 14:42:32.924  8125  8125 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-30 14:42:32.924  6717  8171 D io.jxcore.node.StreamCopyi,ngThread: Entering thread (ID: 882, name: My test thread name)
08-30 14:42:32.924  8125  8125 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 14:42:32.924  6717  8171 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 882, thread name: My test thread name)
08-30 14:42:32.924  6717  8171 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 882, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 14:42:32.924  8125  8125 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-30 14:42:32.925  8125  8125 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 14:42:32.925  8125  8125 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 14:42:32.925  6717  6772 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 14:42:32.926  6717  6772 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 14:42:32.926  6717  6772 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 14:42:32.926  6717  6772 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 14:42:32.926  6717  6772 D com.test.thalitest.ThaliTestRunner: Total duration: 23266 ms
08-30 14:42:32.926  8125  8125 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 14:42:32.927  6717  6772 I jxcore-log: *Native tests were executed*
08-30 14:42:32.927  6717  6772 I jxcore-log: 
08-30 14:42:32.927  6717  6772 I jxcore-log: Total number of executed tests:  80
08-30 14:42:32.927  6717  6772 I jxcore-log: 
08-30 14:42:32.927  6717  6772 I jxcore-log: Number of passed tests:  80
08-30 14:42:32.927  6717  6772 I jxcore-log: 
08-30 14:42:32.927  6717  6772 I jxcore-log: Number of failed tests:  0
08-30 14:42:32.927  6717  6772 I jxcore-log: 
08-30 14:42:32.927  6717  6772 I jxcore-log: Number of ignored tests:  0
08-30 14:42:32.927  6717  6772 I jxcore-log: 
08-30 14:42:32.927  6717  6772 I jxcore-log: Total duration:  23266
08-30 14:42:32.927  6717  6772 I jxcore-log: 
08-30 14:42:32.927  6717  6772 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 14:42:32.927  6717  6772 I jxcore-log: 
08-30 14:42:32.929  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:42:32.929  6717  6772 I jxcore-log: 
08-30 14:42:32.931  8125  8125 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 14:42:32.932  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:42:32.932  6717  6772 I jxcore-log: 
08-30 14:42:32.933  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:42:32.933  6717  6772 I jxcore-log: 
08-30 14:42:32.933  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:42:32.933  6717  6772 I jxcore-log: 
08-30 14:42:32.934  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:42:32.934  6717  6772 I jxcore-log: 
08-30 14:42:32.935  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 14:42:32.935  6717  6772 I jxcore-log: 
08-30 14:42:32.936  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 14:42:32.936  6717  6772 I jxcore-log: 
,08-30 14:42:32.937  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:42:32.937  6717  6772 I jxcore-log: 
08-30 14:42:32.938  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:42:32.938  6717  6772 I jxcore-log: 
08-30 14:42:32.939  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 14:42:32.939  6717  6772 I jxcore-log: 
08-30 14:42:32.939  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 14:42:32.939  6717  6772 I jxcore-log: 
08-30 14:42:32.940  6717  6717 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 14:42:32.940  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 14:42:32.940  6717  6772 I jxcore-log: 
08-30 14:42:32.941  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:42:32.941  6717  6772 I jxcore-log: 
08-30 14:42:32.941  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:42:32.941  6717  6772 I jxcore-log: 
08-30 14:42:32.942  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:42:32.942  6717  6772 I jxcore-log: 
08-30 14:42:32.942  8125  8125 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:32.942  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:42:32.942  6717  6772 I jxcore-log: 
08-30 14:42:32.943  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:42:32.943  6717  6772 I jxcore-log: 
08-30 14:42:32.943  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:42:32.943  6717  6772 I jxcore-log: 
08-30 14:42:32.944  8125  8125 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:32.944  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:42:32.944  6717  6772 I jxcore-log: 
08-30 14:42:32.944  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:42:32.944  6717  6772 I jxcore-log: 
08-30 14:42:32.945  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 14:42:32.945  6717  6772 I jxcore-log: 
08-30 14:42:32.945  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 14:42:32.945  6717  6772 I jxcore-log: 
08-30 14:42:32.946  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:42:32.946  6717  6772 I jxcore-log: 
08-30 14:42:32.946  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:42:32.946  6717  6772 I jxcore-log: 
08-30 14:42:32.946  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:42:32.946  6717  6772 I jxcore-log: 
08-30 14:42:32.947  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:42:32.947  6717  6772 I jxcore-log: 
08-30 14:42:32.947  6717  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:42:32.947  6717  6772 I jxcore-log: 
,08-30 14:42:32.952  8125  8125 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 14:42:32.953  8125  8125 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 14:42:32.954  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 14:42:32.956  6823  6823 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 14:42:32.957  8125  8125 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 14:42:32.958  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:32.958  8066  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 14:42:32.960  8066  8115 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 14:42:32.960  8066  8115 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 14:42:32.963  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:42:32.968  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:32.973  8125  8125 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 14:42:32.973  8125  8125 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:32.974  8125  8125 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 14:42:32.975  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:32.975  8066  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 14:42:32.980  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:32.983  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:32.987  8125  8125 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:32.988  8125  8125 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:32.988  8125  8125 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:42:32.989  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:32.989  8066  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 14:42:32.995  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:33.000  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:33.006  8125  8125 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:33.007  8125  8125 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:33.007  8125  8125 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:42:33.008  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 14:42:33.008  6823  6823 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 14:42:33.008  6823  6823 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-30 14:42:33.008  6823  6823 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 14:42:33.009  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 14:42:33.009  6823  6823 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 14:42:33.009  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 14:42:33.009  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 14:42:33.009  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 14:42:33.009  6823  6823 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 14:42:33.009  6823  6823 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 14:42:33.010  6823  6823 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 14:42:33.014  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:33.014  8066  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 14:42:33.019  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:33.025  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:33.028  8125  8125 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:33.029  8125  8125 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:33.029  8125  8125 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:42:33.031  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:33.031  8066  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 14:42:33.036  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:42:33.040  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:33.045  8125  8125 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 14:42:33.045  8125  8125 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:33.045  8125  8125 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:42:33.047  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:33.047  8066  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 14:42:33.052  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:33.056  1035  8090 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-30 14:42:33.057  1035  8090 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 14:42:33.057  1035  8090 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 14:42:33.057  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:33.057  1035  8090 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 14:42:33.057  1035  8090 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 14:42:33.057  1035  8090 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 14:42:33.057  1035  8090 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 14:42:33.057  1035  8090 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 14:42:33.058  1035  8090 D DhcpStateMachine: RunningState
08-30 14:42:33.061  8125  8125 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:33.062  8125  8125 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:33.062  8125  8125 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:42:33.062  8066  8115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-30 14:42:33.073  8066  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 14:42:33.073  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:33.080  1800  8178 I CheckinService: active receiver: enabled
08-30 14:42:33.081  8066  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-30 14:42:33.095  1800  8178 I CheckinService: Preparing to send checkin request
08-30 14:42:33.095  1800  8178 I EventLogService: Accumulating logs since 1472560935201
08-30 14:42:33.099  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:42:33.104  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:33.110  8125  8125 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 14:42:33.110  8125  8125 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:33.115  8125  8125 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:42:33.119  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:33.120  8066  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-30 14:42:33.120  8066  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 14:42:33.122  8066  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 14:42:33.123  8066  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 14:42:33.124  8066  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-30 14:42:33.124  8066  8115 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-30 14:42:33.125  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:42:33.127  8066  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-30 14:42:33.129  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 14:42:33.133  1800  8178 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-30 14:42:33.134  8066  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-30 14:42:33.139  8125  8125 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:33.139  8125  8125 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:33.139  8125  8125 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:42:33.142  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:33.142  8066  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 14:42:33.147  8019  8019 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 14:42:33.150  8019  8019 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:42:33.153  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:33.158  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:33.164  8125  8125 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:33.164  8125  8125 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:33.165  8125  8125 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 14:42:33.166  8125  8125 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 14:42:33.166  8125  8125 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 14:42:33.169  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:33.170  8066  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 14:42:33.172  8019  8019 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 14:42:33.173  8019  8019 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:42:33.175  6823  6823 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:42:33.181  6823  6823 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:42:33.187  8125  8125 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:42:33.188  8125  8125 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:42:33.188  8125  8125 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 14:42:33.189  8125  8125 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 14:42:33.189  8125  8125 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 14:42:33.193  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 14:42:33.194  8175  8175 D AndroidRuntime: 
08-30 14:42:33.194  8175  8175 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 14:42:33.196  8175  8175 D AndroidRuntime: CheckJNI is OFF
08-30 14:42:33.197  8125  8125 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 14:42:33.198  8125  8125 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 14:42:33.198  8125  8125 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-30 14:42:33.236  8125  8125 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:42:33.236  8125  8125 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:42:33.244  8125  8125 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 14:42:33.246  8125  8125 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 14:42:33.246  8125  8125 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
08-30 14:42:33.246  8125  8125 V SoundPool: doLoad: loading sample sampleID=1
08-30 14:42:33.246  8125  8125 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 14:42:33.248  8125  8196 V SoundPool: Start decode
,08-30 14:42:33.248  8125  8196 V MediaPlayer[Native]: decode(32, 10857164, 17813)
08-30 14:42:33.249  7644  7644 D UEI.SmartControl: QS Service created
08-30 14:42:33.250   323  2144 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 14:42:33.250   323  2144 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 14:42:33.250   323  2144 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 14:42:33.250   323  2144 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 14:42:33.250   323  2144 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 14:42:33.251   323  2144 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 14:42:33.251   323  2144 V MediaPlayerService: player type = 3
08-30 14:42:33.251   323  2144 V AwesomePlayer: AwesomePlayer create()
08-30 14:42:33.251   323  2144 V AwesomePlayer: reset_l() 
08-30 14:42:33.251   323  2144 V AwesomePlayer: cancelPlayerEvents
08-30 14:42:33.251   323  2144 V AwesomePlayer: setAudioSink() 
08-30 14:42:33.251   323  2144 V AwesomePlayer: reset_l() 
08-30 14:42:33.251   323  2144 V AudioCache: notify(0xb1432ec0, 8, 0, 0)
08-30 14:42:33.251   323  2144 V AudioCache: ignored
08-30 14:42:33.251   323  2144 V AwesomePlayer: cancelPlayerEvents
08-30 14:42:33.251   323  2144 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 14:42:33.251   323  2144 V AwesomePlayer: setDataSource_l dataSource
08-30 14:42:33.251   323  2144 V LGParserOSAL: SniffLGParser start
08-30 14:42:33.251   323  2144 V LGParserOSAL: MainType:5, SubType=0
08-30 14:42:33.251   323  2144 V LGParserOSAL: #### check Mime : application/ogg
08-30 14:42:33.251   323  2144 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 14:42:33.251   323  2144 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 14:42:33.261  8125  8125 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 14:42:33.262  8125  8125 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 14:42:33.262  8125  8125 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 14:42:33.265  7644  7644 I UEI.SmartControl: Service initServices...
08-30 14:42:33.266  7644  7644 D UEI.SmartControl: QS start get config
08-30 14:42:33.273  8125  8125 V LGMDMManager: Create singleton instance
08-30 14:42:33.295   323  2144 V LGParserOSAL: supported mime: application/ogg
08-30 14:42:33.295   323  2144 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 14:42:33.295   323  2144 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 14:42:33.295   323  2144 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 14:42:33.295   323  2144 V AwesomePlayer: AudioTrack Setting
08-30 14:42:33.296   323  2144 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 14:42:33.296   323  2144 V AwesomePlayer: setAudioSource() 
08-30 14:42:33.296   323  2144 V MediaPlayerService: prepare
08-30 14:42:33.296   323  2144 V AwesomePlayer: prepareAsync_l() 
08-30 14:42:33.296   323  2144 V MediaPlayerService: wait for prepare
,08-30 14:42:33.296  8175  8175 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-30 14:42:33.297   323  8197 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 14:42:33.297   323  8197 V AwesomePlayer: initAudioDecoder() 
08-30 14:42:33.297   323  8197 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 14:42:33.297   323  8197 V AudioSystem: isOffloadSupported()
08-30 14:42:33.297   323  8197 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 14:42:33.297   323  8197 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 14:42:33.297   323  8197 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 14:42:33.297   323  8197 V AwesomePlayer: getUseOffload() = 0 
08-30 14:42:33.297   323  8197 V OMXCodec: OMXCodec::Create
08-30 14:42:33.297   323  8197 V OMXCodec: findMatchingCodecs()
08-30 14:42:33.297   323  8197 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 14:42:33.297   323  8197 V OMXCodec: matchingCodecs.size()=1
08-30 14:42:33.297   323  8197 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-30 14:42:33.298   323  8197 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 14:42:33.298   323  8197 V LGCodecAdapter: LG Codec Adapter start
08-30 14:42:33.298   323  8197 V OMXCodec: OMXCodec Createtor
08-30 14:42:33.298   323  8197 V OMXCodec: setComponentRole
08-30 14:42:33.298   323  8197 V OMXCodec: configureCodec protected=0
08-30 14:42:33.298   323  8197 V LGCodecAdapter: called getLGCodecSpecificData
08-30 14:42:33.298   323  8197 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 14:42:33.298   323  8197 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 14:42:33.299   323  8197 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 14:42:33.299   323  8197 V LGCodecOSAL: Not support LGCodec
08-30 14:42:33.299   323  8197 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 14:42:33.299   323  8197 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 14:42:33.299   323  8197 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 14:42:33.299   323  8197 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 14:42:33.299   323  8197 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 14:42:33.299   323  8197 V AudioSystem: isOffloadSupported()
08-30 14:42:33.299   323  8197 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 14:42:33.299   323  8197 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 14:42:33.299   323  8197 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
,08-30 14:42:33.299   323  8197 V OMXCodec: init()
08-30 14:42:33.299   323  8197 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 14:42:33.299   323  8197 V OMXCodec: allocateBuffers
08-30 14:42:33.299   323  8197 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 14:42:33.299   323  8197 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 14:42:33.299   323  8197 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-30 14:42:33.299   323  8197 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-30 14:42:33.299   323  8197 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-30 14:42:33.299   323  8197 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-30 14:42:33.299   323  8197 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 14:42:33.299   323  8197 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 14:42:33.299   323  8197 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-30 14:42:33.299   323  8197 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-30 14:42:33.299   323  8197 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-30 14:42:33.299   323  8197 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-30 14:42:33.299   323  8197 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 14:42:33.299   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 14:42:33.299   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 14:42:33.300   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 14:42:33.300   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 14:42:33.300   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 14:42:33.300   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 14:42:33.300   323  8197 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 14:42:33.300   323  8197 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 14:42:33.300   323  8197 V AudioCache: notify(0xb1432ec0, 5, 0, 0)
08-30 14:42:33.300   323  8197 V AudioCache: ignored
08-30 14:42:33.300   323  8197 V AudioCache: notify(0xb1432ec0, 1, 0, 0)
08-30 14:42:33.300   323  8197 V AudioCache: prepared
08-30 14:42:33.300   323  2144 V AudioCache: wait - success
08-30 14:42:33.300   323  2144 V MediaPlayerService: start
08-30 14:42:33.300   323  2144 V AwesomePlayer: play_l() 
08-30 14:42:33.300   323  2144 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 14:42:33.300   323  2144 V AwesomePlayer: createAudioPlayer_l
08-30 14:42:33.300   323  2144 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 14:42:33.300   323  2144 V AwesomePlayer: startAudioPlayer_l() 
08-30 14:42:33.300   323  2144 D AudioPlayer: start of Playback, useOffload 0
08-30 14:42:33.300   323  2144 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 14:42:33.300   323  2144 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 14:42:33.302   323  8201 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 14:42:33.302   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 14:42:33.303   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-30 14:42:33.303   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-30 14:42:33.303   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-30 14:42:33.303   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on output port
08-30 14:42:33.303   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 14:42:33.303   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 14:42:33.303   323  2144 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 14:42:33.304   323  2144 V AudioCache: notify(0xb1432ec0, 6, 0, 0)
08-30 14:42:33.304   323  2144 V AudioCache: ignored
08-30 14:42:33.304   323  2144 V MediaPlayerService: wait for playback complete
08-30 14:42:33.304   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.304   323  8202 V AudioCache: memcpy(0xac100000, 0xb1786000, 4096)
08-30 14:42:33.305   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.305   323  8202 V AudioCache: memcpy(0xac101000, 0xb1786000, 4096)
08-30 14:42:33.305   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.305   323  8202 V AudioCache: memcpy(0xac102000, 0xb1786000, 4096)
08-30 14:42:33.306   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.306   323  8202 V AudioCache: memcpy(0xac103000, 0xb1786000, 4096)
08-30 14:42:33.306   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.306   323  8202 V AudioCache: memcpy(0xac104000, 0xb1786000, 4096)
08-30 14:42:33.306   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.306   323  8202 V AudioCache: memcpy(0xac105000, 0xb1786000, 4096)
08-30 14:42:33.306   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.306   323  8202 V AudioCache: memcpy(0xac106000, 0xb1786000, 4096)
08-30 14:42:33.307   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.307   323  8202 V AudioCache: memcpy(0xac107000, 0xb1786000, 4096)
08-30 14:42:33.307   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.307   323  8202 V AudioCache: memcpy(0xac108000, 0xb1786000, 4096)
08-30 14:42:33.307   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.307   323  8202 V AudioCache: memcpy(0xac109000, 0xb1786000, 4096)
08-30 14:42:33.307   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.307   323  8202 V AudioCache: memcpy(0xac10a000, 0xb1786000, 4096)
08-30 14:42:33.308   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.308   323  8202 V AudioCache: memcpy(0xac10b000, 0xb1786000, 4096)
08-30 14:42:33.308   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.308   323  8202 V AudioCache: memcpy(0xac10c000, 0xb1786000, 4096)
08-30 14:42:33.308   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.308   323  8202 V AudioCache: memcpy(0xac10d000, 0xb1786000, 4096)
08-30 14:42:33.308   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.308   323  8202 V AudioCache: memcpy(0xac10e000, 0xb1786000, 4096)
08-30 14:42:33.309   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.309   323  8202 V AudioCache: memcpy(0xac10f000, 0xb1786000, 4096)
08-30 14:42:33.309   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.309   323  8202 V AudioCache: memcpy(0xac110000, 0xb1786000, 4096)
08-30 14:42:33.310   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.310   323  8202 V AudioCache: memcpy(0xac111000, 0xb1786000, 4096)
08-30 14:42:33.310   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.310   323  8202 V AudioCache: memcpy(0xac112000, 0xb1786000, 4096)
08-30 14:42:33.311   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.311   323  8202 V AudioCache: memcpy(0xac113000, 0xb1786000, 4096)
08-30 14:42:33.311   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.311   323  8202 V AudioCache: memcpy(0xac114000, 0xb1786000, 4096)
08-30 14:42:33.312   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.312   323  8202 V AudioCache: memcpy(0xac115000, 0xb1786000, 4096)
08-30 14:42:33.312   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.312   323  8202 V AudioCache: memcpy(0xac116000, 0xb1786000, 4096)
08-30 14:42:33.312   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.312   323  8202 V AudioCache: memcpy(0xac117000, 0xb1786000, 4096)
08-30 14:42:33.313   323  8202 V AudioCache: write(0xb1786000, 4096)
,08-30 14:42:33.313   323  8202 V AudioCache: memcpy(0xac118000, 0xb1786000, 4096)
08-30 14:42:33.313   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.313   323  8202 V AudioCache: memcpy(0xac119000, 0xb1786000, 4096)
08-30 14:42:33.314   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.314   323  8202 V AudioCache: memcpy(0xac11a000, 0xb1786000, 4096)
08-30 14:42:33.314   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.314   323  8202 V AudioCache: memcpy(0xac11b000, 0xb1786000, 4096)
08-30 14:42:33.315   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.315   323  8202 V AudioCache: memcpy(0xac11c000, 0xb1786000, 4096)
08-30 14:42:33.315   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.315   323  8202 V AudioCache: memcpy(0xac11d000, 0xb1786000, 4096)
08-30 14:42:33.316   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.316   323  8202 V AudioCache: memcpy(0xac11e000, 0xb1786000, 4096)
08-30 14:42:33.316   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.316   323  8202 V AudioCache: memcpy(0xac11f000, 0xb1786000, 4096)
08-30 14:42:33.316   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.316   323  8202 V AudioCache: memcpy(0xac120000, 0xb1786000, 4096)
08-30 14:42:33.317   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.317   323  8202 V AudioCache: memcpy(0xac121000, 0xb1786000, 4096)
08-30 14:42:33.317   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.317   323  8202 V AudioCache: memcpy(0xac122000, 0xb1786000, 4096)
08-30 14:42:33.318   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.318   323  8202 V AudioCache: memcpy(0xac123000, 0xb1786000, 4096)
08-30 14:42:33.318   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.318   323  8202 V AudioCache: memcpy(0xac124000, 0xb1786000, 4096)
08-30 14:42:33.319   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.319   323  8202 V AudioCache: memcpy(0xac125000, 0xb1786000, 4096)
08-30 14:42:33.319   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.319   323  8202 V AudioCache: memcpy(0xac126000, 0xb1786000, 4096)
08-30 14:42:33.320   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.320   323  8202 V AudioCache: memcpy(0xac127000, 0xb1786000, 4096)
08-30 14:42:33.320   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.320   323  8202 V AudioCache: memcpy(0xac128000, 0xb1786000, 4096)
08-30 14:42:33.321   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.321   323  8202 V AudioCache: memcpy(0xac129000, 0xb1786000, 4096)
08-30 14:42:33.321   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.321   323  8202 V AudioCache: memcpy(0xac12a000, 0xb1786000, 4096)
08-30 14:42:33.322   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.322   323  8202 V AudioCache: memcpy(0xac12b000, 0xb1786000, 4096)
08-30 14:42:33.322   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.322   323  8202 V AudioCache: memcpy(0xac12c000, 0xb1786000, 4096)
08-30 14:42:33.322   323  8202 V AudioCache: write(0xb1786000, 4096)
,08-30 14:42:33.322   323  8202 V AudioCache: memcpy(0xac12d000, 0xb1786000, 4096)
08-30 14:42:33.323   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.323   323  8202 V AudioCache: memcpy(0xac12e000, 0xb1786000, 4096)
08-30 14:42:33.323   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 14:42:33.323   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.323   323  8202 V AudioCache: memcpy(0xac12f000, 0xb1786000, 4096)
08-30 14:42:33.323   323  8202 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 14:42:33.323   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.323   323  8202 V AudioCache: memcpy(0xac130000, 0xb1786000, 4096)
08-30 14:42:33.323   323  8202 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 14:42:33.323   323  8202 V AudioCache: write(0xb1786000, 4096)
08-30 14:42:33.323   323  8202 V AudioCache: memcpy(0xac131000, 0xb1786000, 4096)
08-30 14:42:33.323   323  8202 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 14:42:33.323   323  8202 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 14:42:33.323   323  8202 V AwesomePlayer: postAudioEOS() 
08-30 14:42:33.323   323  8202 V AudioCache: write(0xb1786000, 280)
08-30 14:42:33.323   323  8202 V AudioCache: memcpy(0xac132000, 0xb1786000, 280)
08-30 14:42:33.325   323  8197 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 14:42:33.325   323  8197 V AwesomePlayer: onStreamDone
08-30 14:42:33.325   323  8197 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 14:42:33.325   323  8197 V AudioCache: notify(0xb1432ec0, 2, 0, 0)
08-30 14:42:33.325   323  8197 V AudioCache: playback complete
08-30 14:42:33.325   323  8197 V AwesomePlayer: pause_l() 
08-30 14:42:33.325   323  8197 V AudioCache: notify(0xb1432ec0, 7, 0, 0)
08-30 14:42:33.325   323  8197 V AudioCache: ignored
08-30 14:42:33.325   323  8197 V AwesomePlayer: cancelPlayerEvents
08-30 14:42:33.325   323  2144 V AudioCache: wait - success
08-30 14:42:33.325   323  2144 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
,08-30 14:42:33.325   323  8197 D AudioPlayer: Pause Playback at 1068125
08-30 14:42:33.326   323  2144 V AwesomePlayer: reset_l() 
08-30 14:42:33.326   323  2144 V AudioCache: notify(0xb1432ec0, 8, 0, 0)
08-30 14:42:33.326   323  2144 V AudioCache: ignored
08-30 14:42:33.326   323  2144 V AwesomePlayer: cancelPlayerEvents
08-30 14:42:33.326   323  2144 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 14:42:33.326   323  2144 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 14:42:33.326   323  2144 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 14:42:33.326   323  2144 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 14:42:33.326   323  2144 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 1
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
08-30 14:42:33.327   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 14:42:33.328   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-30 14:42:33.328   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 14:42:33.328   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-30 14:42:33.328   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:42:33.328   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 14:42:33.328   323  2144 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 14:42:33.328   323  2144 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 14:42:33.328   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 14:42:33.328   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 14:42:33.328   323  8201 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 14:42:33.328   323  2144 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 14:42:33.328   323  2144 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 14:42:33.328   323  2144 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 14:42:33.329   323  2144 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 14:42:33.329   323  2144 D AudioPlayer: AudioPlayer releasing audio source
08-30 14:42:33.329   323  2144 D AudioPlayer: AudioPlayer done releasing audio source
08-30 14:42:33.329   323  2144 V AwesomePlayer: reset_l() 
08-30 14:42:33.329   323  2144 V AwesomePlayer: cancelPlayerEvents
08-30 14:42:33.329   323  2144 V AwesomePlayer: ~AwesomePlayer call
08-30 14:42:33.329   323  2144 V AwesomePlayer: reset_l() 
08-30 14:42:33.329   323  2144 V AwesomePlayer: cancelPlayerEvents
08-30 14:42:33.329  8125  8196 V SoundPool: close(32)
08-30 14:42:33.329  8125  8196 V SoundPool: pointer = 0xa0039000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 14:42:33.330  1035  1113 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-30 14:42:33.331  1035  1113 I ActivityManager: Killing 6717:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-30 14:42:33.364  1035  1560 I WindowState: WIN DEATH: Window{e23c9ef u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 14:42:33.365  1035  1430 D WifiService: Client connection lost with reason: 4
,08-30 14:42:33.370  1035  1560 D InputDispatcher: Window went away: Window{e23c9ef u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 14:42:33.371  8125  8125 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-30 14:42:33.394  8125  8125 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-30 14:42:33.534  7218  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 14:42:33.534  7218  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 14:42:33.534  7218  7235 I Adreno-EGL: Build Date: 12/12/14 금
08-30 14:42:33.534  7218  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 14:42:33.534  7218  7235 I Adreno-EGL: Remote Branch: 
08-30 14:42:33.534  7218  7235 I Adreno-EGL: Local Patches: 
08-30 14:42:33.534  7218  7235 I Adreno-EGL: Reconstruct Branch: 
,08-30 14:42:33.535  7644  7644 I UEI.SmartControl: Supports setup maps: true
08-30 14:42:33.537  7644  7644 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 14:42:33.537  7644  7644 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 14:42:33.537  7644  7644 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 14:42:33.537  7644  7644 I UEI.SmartControl: ### init IR Blaster...
08-30 14:42:33.539  1035  1113 E libprocessgroup: failed to kill 1 processes for processgroup 6717
08-30 14:42:33.540  1035  1113 I ActivityManager:   Force finishing activity ActivityRecord{9988a88 u0 com.test.thalitest/.MainActivity t6}
08-30 14:42:33.541  7644  7644 D serial_port: Configuring serial port
08-30 14:42:33.541  7644  7644 E UEI.SmartControl: UEIBLaster setting for 616
08-30 14:42:33.541  7644  7644 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 14:42:33.541  7644  7644 I UEI.SmartControl: configuring settings for MAXQ616
08-30 14:42:33.541  7644  7644 I UEI.SmartControl: Get version...
,08-30 14:42:33.560  7644  8203 D UEI.SmartControl: serial port data available: 21
08-30 14:42:33.561   346   419 E GBMv2   : DFP En is all cleared set to be enabled
08-30 14:42:33.563  1035  1926 W ActivityManager: Spurious death for ProcessRecord{18ec159e 6717:com.test.thalitest/u0a118}, curProc for 6717: null
08-30 14:42:33.563  1035  1142 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-30 14:42:33.564  1035  1142 I ActivityManager:   Force finishing activity ActivityRecord{9988a88 u0 com.test.thalitest/.MainActivity t6 f}
08-30 14:42:33.564  1035  1142 W ActivityManager: Duplicate finish request for ActivityRecord{9988a88 u0 com.test.thalitest/.MainActivity t6 f}
08-30 14:42:33.571  8125  8125 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5807
,08-30 14:42:33.579  2017  2017 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-30 14:42:33.580  2017  2017 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-30 14:42:33.581  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 14:42:33.585  1981  1981 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-30 14:42:33.585  3840  3840 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 14:42:33.586  7644  7644 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 14:42:33.586  7644  7644 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 14:42:33.586  7644  7644 I UEI.SmartControl: QS saving settings...
08-30 14:42:33.590  7617  7617 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 14:42:33.590  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 14:42:33.592  2492  2663 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 14:42:33.596  1035  1366 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 14:42:33.601  4481  4481 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 14:42:33.602  4481  4481 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 14:42:33.602  7218  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 14:42:33.602  7218  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 14:42:33.602  7218  7235 I Adreno-EGL: Build Date: 12/12/14 금
08-30 14:42:33.602  7218  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 14:42:33.602  7218  7235 I Adreno-EGL: Remote Branch: 
08-30 14:42:33.602  7218  7235 I Adreno-EGL: Local Patches: 
08-30 14:42:33.602  7218  7235 I Adreno-EGL: Reconstruct Branch: 
08-30 14:42:33.602  4481  4481 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 14:42:33.602  4481  4481 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 14:42:33.602  4481  4481 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 14:42:33.602  4481  4481 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 14:42:33.602  4481  4481 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 14:42:33.602  4481  4481 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 14:42:33.602  4481  4481 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:42:33.602  4481  4481 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 14:42:33.602  4481  4481 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 14:42:33.602  4481  4481 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 14:42:33.602  7644  7644 D UEI.SmartControl: IR Blaster version: 25672567
08-30 14:42:33.627  1035  1722 V SIM_STK : Menu title from STK is T-Mobile
,08-30 14:42:33.634  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-30 14:42:33.635  2017  2122 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-30 14:42:33.637  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-30 14:42:33.637  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3afaed64 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 14:42:33.639  1927  4008 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 14:42:33.639  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:33.639  1927  4008 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1083bbcd co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 14:42:33.653  1891  1891 D ActionManagerService: notifyUserLog: 1000003
08-30 14:42:33.653  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-30 14:42:33.653  3840  4505 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 14:42:33.654  1586  1635 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 14:42:33.654  1586  1635 D KeyguardModel: createShortcutInfo...
,08-30 14:42:33.655  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-30 14:42:33.656  1586  1635 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 14:42:33.656  1586  1635 D KeyguardModel: createShortcutInfo...
08-30 14:42:33.657  7644  8203 D UEI.SmartControl: serial port data available: 4
08-30 14:42:33.662  1586  1635 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 14:42:33.662  1586  1635 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 14:42:33.663  1586  1635 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 14:42:33.668  1586  1635 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 14:42:33.671  2017  2017 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 14:42:33.672  4596  4596 I art     : Explicit concurrent mark sweep GC freed 8199(470KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 607us total 96.299ms
08-30 14:42:33.672  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 14:42:33.672  1586  1635 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 14:42:33.675  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,08-30 14:42:33.683  1586  1635 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 14:42:33.683  1586  1635 D KeyguardModel: createShortcutInfo...
08-30 14:42:33.687  1035  1035 D administrator: Handling package changes for user 0
08-30 14:42:33.689  1586  1635 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 14:42:33.689  1586  1635 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 14:42:33.690  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 14:42:33.690  1586  1635 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 14:42:33.691  7218  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 14:42:33.691  7218  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 14:42:33.691  7218  7235 I Adreno-EGL: Build Date: 12/12/14 금
08-30 14:42:33.691  7218  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 14:42:33.691  7218  7235 I Adreno-EGL: Remote Branch: 
08-30 14:42:33.691  7218  7235 I Adreno-EGL: Local Patches: 
08-30 14:42:33.691  7218  7235 I Adreno-EGL: Reconstruct Branch: 
08-30 14:42:33.691  7644  7644 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 14:42:33.692  1586  1635 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 14:42:33.692  1586  1635 D KeyguardModel: createShortcutInfo...
08-30 14:42:33.699  1586  1635 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 14:42:33.699  1586  1635 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 14:42:33.699  1586  1635 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 14:42:33.699  1586  1635 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 14:42:33.700  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 14:42:33.700  1586  1635 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-30 14:42:33.703  1586  1635 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 14:42:33.703  1586  1635 D KeyguardModel: createShortcutInfo...
08-30 14:42:33.705  1035  1998 V SIM_STK : Menu title from STK is T-Mobile
08-30 14:42:33.705  1035  1998 V SIM_STK : Menu title from STK is T-Mobile
08-30 14:42:33.708  2017  2017 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-30 14:42:33.711  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 14:42:33.711  7644  7644 E UEI.SmartControl: Services init done
08-30 14:42:33.711  7644  7644 D UEI.SmartControl: QS Service init finished
,08-30 14:42:33.712  2017  2017 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-30 14:42:33.716  1891  1891 D ActionManagerService: notifyUserLog: 1000004
08-30 14:42:33.717  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-30 14:42:33.717  3840  4505 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 14:42:33.717  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-30 14:42:33.717  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 14:42:33.720  3840  3856 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 14:42:33.725  1586  1635 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 14:42:33.725  1586  1635 D KeyguardModel: createShortcutInfo...
08-30 14:42:33.729  1586  1635 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 14:42:33.729  1586  1635 D KeyguardModel: createShortcutInfo...
,08-30 14:42:33.731  7644  7644 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 14:42:33.731  7644  7644 D UEI.SmartControl: QS Service version code: 201091
08-30 14:42:33.731  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 14:42:33.731  1586  1635 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , expire_time: 0
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , display: false
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , animation: false }
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , expire_time: 0
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , display: false
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , animation: false }
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , expire_time: 0
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , display: false
08-30 14:42:33.731  2017  2017 I GBoardWebViewUtils: , animation: false }
08-30 14:42:33.737  1586  1635 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 14:42:33.737  1586  1635 D KeyguardModel: createShortcutInfo...
08-30 14:42:33.738  7644  8207 I UEI.SmartControl: Device manager: loading config....
08-30 14:42:33.739  7644  8207 D UEI.SmartControl: ----------- loading internal config...
08-30 14:42:33.744  1854  1854 D SplitUIManager: split_name #11 / not available #0
08-30 14:42:33.745  1854  1854 D SplitUIService: removed split : 
,08-30 14:42:33.753  1035  1057 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 14:42:33.753  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 14:42:33.753  1586  1635 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 14:42:33.753  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 14:42:33.754  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 14:42:33.754  2017  8209 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-30 14:42:33.754  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 14:42:33.754  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 14:42:33.754  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 14:42:33.754  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 14:42:33.754  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 14:42:33.754  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 14:42:33.754  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 14:42:33.754  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 14:42:33.754  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 14:42:33.754  7644  7644 D UEI.SmartControl: Service requested: Control
08-30 14:42:33.757  1035  1871 V SIM_STK : Menu title from STK is T-Mobile
08-30 14:42:33.767  1586  1635 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 14:42:33.767  1586  1635 D KeyguardModel: createShortcutInfo...
,08-30 14:42:33.771  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 14:42:33.771  1586  1635 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 14:42:33.772  7644  8207 E UEI.SmartControl: Loading SETTINGS...
08-30 14:42:33.772  7644  7644 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 14:42:33.774  8125  8125 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 14:42:33.776  1586  1635 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 14:42:33.776  1586  1635 D KeyguardModel: createShortcutInfo...
08-30 14:42:33.778  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 14:42:33.778  7644  7644 D UEI.SmartControl: Internal service binding...
08-30 14:42:33.778  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-30 14:42:33.784  7644  7660 I UEI.SmartControl: ------ IControl API: 11
08-30 14:42:33.784  7644  7660 D UEI.SmartControl: File observer start...
08-30 14:42:33.785  7644  7660 E UEI.SmartControl: IR Port is disabled: false
08-30 14:42:33.785  7644  7660 D UEI.SmartControl: Starting file observer...
,08-30 14:42:33.785  7644  7660 I UEI.SmartControl: Registering callback...
08-30 14:42:33.786  7644  7667 I UEI.SmartControl: ------ IControl API: 19
08-30 14:42:33.787  7644  7667 I UEI.SmartControl: Registering Services Ready callback...
08-30 14:42:33.791  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-30 14:42:33.791  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 14:42:33.799  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 14:42:33.799  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 14:42:33.799  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 14:42:33.801  1035  1562 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-30 14:42:33.802  1035  1112 W InputMethodInfo: Duplicated subtype definition found: , voice
08-30 14:42:33.803  1854  1854 D SplitUIManager: split_name #11 / not available #0
08-30 14:42:33.803  1854  1854 I SplitUIService: split app #11
,08-30 14:42:33.814  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:33.826  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:42:33.829  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:33.832  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:33.835  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:33.841  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:42:33.843  7644  8207 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 14:42:33.846  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:33.847   336   396 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-30 14:42:33.847  3183  8212 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 14:42:33.849  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:33.852  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:42:33.853  2017  2017 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-30 14:42:33.856  8066  8066 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 14:42:33.861  1800  1800 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 14:42:33.863  7644  8206 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 14:42:33.863  7644  8206 D UEI.SmartControl: -----service ready thread exits
08-30 14:42:33.863  8125  8141 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 14:42:33.864  8125  8194 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 14:42:33.864  8125  8194 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 14:42:33.869  2195  2195 I ConfigService: onCreate
08-30 14:42:33.869  2195  2195 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 14:42:33.870  1800  1800 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-30 14:42:33.879  8125  8125 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 14:42:33.880  8125  8125 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 14:42:33.880  7644  7660 I UEI.SmartControl: ------ IControl API: 8
08-30 14:42:33.881  8125  8125 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 14:42:33.881  8125  8125 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 14:42:33.881  8125  8125 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 14:42:33.881  2195  2195 I ConfigService: onBind returning update interface
08-30 14:42:33.881  8125  8125 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 14:42:33.882  2195  2195 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 14:42:33.882  2195  2195 I ConfigService: onBind returning config service
08-30 14:42:33.882  8125  8125 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 14:42:33.882  8125  8125 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-30 14:42:33.884  2195  2195 I ConfigService: onDestroy
08-30 14:42:33.886  8125  8125 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-30 14:42:33.887  1800  8214 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 14:42:33.888  8125  8125 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 14:42:33.914  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-30 14:42:33.918  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 14:42:33.919  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 14:42:33.921  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 14:42:33.922  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 14:42:33.923  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-30 14:42:33.925  6994  6994 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-30 14:42:33.940  5903  8220 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-30 14:42:33.943  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 14:42:33.943  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 14:42:33.943  1800  8221 I PeopleContactsSync: CP2 sync disabled
08-30 14:42:33.943  2017  2249 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,08-30 14:42:33.943  2017  2249 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-30 14:42:33.947  2318  8223 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-30 14:42:33.958  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-30 14:42:33.961  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,08-30 14:42:33.961  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 14:42:33.968  1035  1926 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8226 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-30 14:42:33.968  2017  2017 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-30 14:42:33.971  2580  2580 D [Concierge]Service: onStartCommand(). Type : 8
08-30 14:42:33.971  2580  2580 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-30 14:42:33.973  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1d10062e u0 com.lge.launcher2/.Launcher t5} time:225732
08-30 14:42:33.973  2580  2580 D [Concierge]Service: Update widget ID : 11
,08-30 14:42:33.973  2017  2017 D [Concierge]WidgetView: change position of spinner
,08-30 14:42:33.974  2017  2017 I [Concierge]WidgetView: initWebView(). Time : 1472560953974
08-30 14:42:33.974  2580  2580 D [Concierge]Service: onStartCommand(). Type : 0
08-30 14:42:33.984  1800  8219 W GmsApplication: Using Auth Proxy for data requests.
08-30 14:42:33.984  1800  4763 I Icing   : doRemovePackageData com.test.thalitest
,08-30 14:42:33.986  2017  2017 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 1037736303
08-30 14:42:33.987  2017  2017 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 14:42:33.987  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 14:42:33.990  2017  2017 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2f5cc0ef
,08-30 14:42:33.990  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 14:42:33.992  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 14:42:33.992  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 14:42:33.994  1800  8219 W GmsApplication: Using Auth Proxy for data requests.
08-30 14:42:33.997  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-30 14:42:33.997  2017  2017 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 14:42:33.998  2017  2017 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 14:42:33.998  2017  2017 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472560756671, New one : 1472560953974
08-30 14:42:33.998  2017  2017 D [Concierge]WidgetView: Unregister all receivers
08-30 14:42:33.998  2017  2017 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 14:42:33.999  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 14:42:34.000  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 14:42:34.001  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 14:42:34.002  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 14:42:34.003  2195  2327 I art     : Explicit concurrent mark sweep GC freed 6737(393KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 814us total 20.240ms
08-30 14:42:34.003  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 14:42:34.004  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-30 14:42:34.011  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 14:42:34.011  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 14:42:34.032   319  8245 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 14:42:34.032   319  8245 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-30 14:42:34.037  1035  1112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 14:42:34.047  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-30 14:42:34.054  8226  8226 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 14:42:34.054  8226  8226 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 14:42:34.055  8226  8226 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 14:42:34.055  8226  8226 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 14:42:34.058  2017  2017 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-30 14:42:34.058  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 14:42:34.059  1035  1112 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 14:42:34.060  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 14:42:34.073   319  8245 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-30 14:42:34.076  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 14:42:34.080  2017  2017 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@223ca358 time:225839
08-30 14:42:34.121  1035  1377 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 14:42:34.121  1035  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 14:42:34.121  1035  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 14:42:34.122  1035  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 14:42:34.122  1035  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 14:42:34.122  1035  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 14:42:34.123  1035  1434 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-30 14:42:34.123  1035  1434 D ConnectivityService: identical MTU - not setting
08-30 14:42:34.123  1035  1434 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 14:42:34.123  1035  1434 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 14:42:34.123  1035  1434 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:42:34.123  1035  1434 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:42:34.123  1035  1434 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:42:34.124  1586  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-30 14:42:34.128  8226  8226 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-30 14:42:34.130  1035  1142 I art     : Explicit concurrent mark sweep GC freed 88635(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 43MB/65MB, paused 1.165ms total 394.566ms
08-30 14:42:34.136  8226  8226 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 14:42:34.148  1800  8178 I CheckinTask: Sending checkin request (7829 bytes)
08-30 14:42:34.156  8175  8175 D AndroidRuntime: Shutting down VM
08-30 14:42:34.187  8226  8226 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 14:42:34.203  2017  2017 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-30 14:42:34.205  8226  8226 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:42:34.205  8226  8226 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:42:34.238  2017  2892 I GBoardtInterface: onReloaded()
08-30 14:42:34.240  2017  2017 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-30 14:42:34.241  3840  3856 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 14:42:34.243  3840  3855 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 14:42:34.248  1891  1891 D ActionManagerService: notifyUserLog: 1000001
08-30 14:42:34.249  3840  4505 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,08-30 14:42:34.249  3840  4505 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-30 14:42:34.252  1891  1891 D ActionManagerService: notifyUserLog: 1000001
08-30 14:42:34.253  3840  4505 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 14:42:34.253  3840  4505 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 14:42:34.253  3840  4505 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 14:42:34.253  3840  4505 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 14:42:34.254  3840  3856 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 14:42:34.254  8226  8226 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-30 14:42:34.257  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-30 14:42:34.257  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 14:42:34.259  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-30 14:42:34.259  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 14:42:34.261  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-30 14:42:34.261  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-30 14:42:34.266  1035  1890 I ActivityManager: Killing 7683:com.google.android.talk/u0a72 (adj 15): empty #17
08-30 14:42:34.324  1981  1981 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-30 14:42:34.324  1981  1981 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-30 14:42:34.325  1035  2033 W libprocessgroup: failed to open /acct/uid_10072/pid_7683/cgroup.procs: No such file or directory
08-30 14:42:34.325  1981  1981 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,08-30 14:42:34.345  8066  8066 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 14:42:34.348  7436  7436 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-30 14:42:34.350  6823  6823 D PackageIntentReceiver: Not supported Hotkey customization function 
08-30 14:42:34.356  6823  6823 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-30 14:42:34.356  6823  6823 D HideNavigationAppsReceiver: replacing : false
08-30 14:42:34.358  6823  6823 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-30 14:42:34.360  1800  8178 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-30 14:42:34.361  6823  6823 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-30 14:42:34.361  6823  6823 D ButtonCombinationReceiver: replacing : false
08-30 14:42:34.392  1035  1142 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8252 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-30 14:42:34.392  1800  8178 I CheckinService: active receiver: disabled
08-30 14:42:34.411  4596  8269 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-30 14:42:34.428  1035  1058 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8271 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 14:42:34.437  1035  1890 V SIM_STK : Menu title from STK is T-Mobile
,08-30 14:42:34.458  1035  1871 I ActivityManager: Killing 7275:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-30 14:42:34.522  1035  1560 W libprocessgroup: failed to open /acct/uid_10097/pid_7275/cgroup.procs: No such file or directory
,08-30 14:42:34.525  8271  8271 D DocsApplication: Installing DEX configuration.
08-30 14:42:34.530  4596  8269 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-30 14:42:34.532  8271  8271 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: Exception thrown from notifyTableChanged
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at beg.a(PG:301)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at beg.c(PG:222)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at cun.b(PG:660)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at cun.a(PG:651)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at cun.g(PG:597)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at cuw.Tg(PG:368)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at cuy.ub(PG:301)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at android.os.Looper.loop(Looper.java:135)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at bea.a(PG:382)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at beg.i(PG:325)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at beh.call(PG:215)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	at beg.a(PG:299)
08-30 14:42:34.533  4596  8269 E IcingCorporaProvider: 	... 15 more
08-30 14:42:34.533  4596  8269 W IcingCorporaProvider: notifyTableChanged failed.
08-30 14:42:34.533  4596  8269 W IcingCorporaProvider: Table change notification failed for TableStorageSpec[applications]
08-30 14:42:34.533  4596  8269 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 123 ms] updated apps [took 123 ms] 
08-30 14:42:34.535  2195  2725 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only, file system)
08-30 14:42:34.535  2195  2725 W ServiceConnection: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
08-30 14:42:34.535  2195  2725 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 14:42:34.535  2195  2725 W ServiceConnection: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 14:42:34.535  2195  2725 W ServiceConnection: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-30 14:42:34.535  2195  2725 W ServiceConnection: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-30 14:42:34.535  2195  2725 W ServiceConnection: 	at com.google.android.gms.common.internal.bf.b(SourceFile:56)
08-30 14:42:34.535  2195  2725 W ServiceConnection: 	at com.google.android.gms.common.internal.bf.a(SourceFile:48)
08-30 14:42:34.535  2195  2725 W ServiceConnection: 	at com.google.android.gms.common.internal.be.a(SourceFile:45)
08-30 14:42:34.535  2195  2725 W ServiceConnection: 	at com.google.android.gms.icing.service.n.b(SourceFile:118)
08-30 14:42:34.535  2195  2725 W ServiceConnection: 	at com.google.android.gms.common.internal.bd.b(SourceFile:218)
08-30 14:42:34.535  2195  2725 W ServiceConnection: 	at com.google.android.gms.common.internal.ao.onTransact(SourceFile:460)
08-30 14:42:34.535  2195  2725 W ServiceConnection: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 14:42:34.535  2195  2725 W ServiceConnection: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 14:42:34.535  2195  2725 W ServiceConnection: 	at libcore.io.Posix.open(Native Method)
08-30 14:42:34.535  2195  2725 W ServiceConnection: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 14:42:34.535  2195  2725 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 14:42:34.535  2195  2725 W ServiceConnection: 	... 10 more
,08-30 14:42:34.538  8271  8271 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{12f6e94e com.google.android.apps.docs}
08-30 14:42:34.541  8271  8271 D TAG     : onCreate()
08-30 14:42:34.541  1800  4763 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
08-30 14:42:34.541  1800  4763 E Icing   : Could not init tag ds.tag.corpusid-1
08-30 14:42:34.541  1800  4763 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-13 for write failed: Read-only file system
08-30 14:42:34.541  1800  4763 E Icing   : Could not init tag ds.tag.corpusid-13
08-30 14:42:34.541  1800  4763 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-7 for write failed: Read-only file system
08-30 14:42:34.541  1800  4763 E Icing   : Could not init tag ds.tag.corpusid-7
08-30 14:42:34.541  1800  4763 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-8 for write failed: Read-only file system
08-30 14:42:34.541  1800  4763 E Icing   : Could not init tag ds.tag.corpusid-8
08-30 14:42:34.541  1800  4763 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-9 for write failed: Read-only file system
08-30 14:42:34.541  1800  4763 E Icing   : Could not init tag ds.tag.corpusid-9
08-30 14:42:34.541  1800  4763 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
08-30 14:42:34.541  1800  4763 E Icing   : Could not init tag ds.tag.deleted
08-30 14:42:34.542  1800  4763 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
08-30 14:42:34.542  1800  4763 E Icing   : Writing status failed
08-30 14:42:34.544  2017  2892 I GBoardtInterface: exportHTML()
08-30 14:42:34.547  8271  8271 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,08-30 14:42:34.571  2017  2892 I GBoardtInterface: exportHTML()

```
