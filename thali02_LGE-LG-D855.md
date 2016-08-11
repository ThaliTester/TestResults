#### Test 797638305bc0289_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-11 13:30:46.986  5532  5532 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-11 13:30:55.868  6888  6888 D AndroidRuntime: 
08-11 13:30:55.868  6888  6888 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-11 13:30:55.875  6888  6888 D AndroidRuntime: CheckJNI is OFF
08-11 13:30:56.077  6888  6888 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 13:30:56.088  1035  2024 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 13:30:56.103  1954  1970 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-11 13:30:56.108  1035  2024 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-11 13:30:56.110  1035  2024 D ActivityManager: setTaskToReturnTo : TaskRecord{1675be7e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 13:30:56.110  1035  2024 D ActivityManager: setTaskToReturnTo : TaskRecord{1675be7e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 13:30:56.111  1035  2024 D WindowStateEx: AppWindowTokenEx init.. 
08-11 13:30:56.112   332   346 E GBMv2   : DFP En is all cleared set to be enabled
08-11 13:30:56.155  1035  2024 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6903 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-11 13:30:56.158  6888  6888 D AndroidRuntime: Shutting down VM
08-11 13:30:56.198  1954  1969 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-11 13:30:56.198  1954  1969 D SplitWindowPolicy: topRunningActivity=ActivityInfo{144d4291 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-11 13:30:56.200  1954  3335 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-11 13:30:56.200  1954  3335 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3c53b5f6 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-11 13:30:56.234  6903  6903 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-11 13:30:56.336  6903  6903 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-11 13:30:56.343  6903  6903 I LibraryLoader: Loading: webviewchromium
08-11 13:30:56.346  6903  6903 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7761-7764)
08-11 13:30:56.346  6903  6903 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 13:30:56.362  6903  6903 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9e05b67}
,08-11 13:30:56.363  6903  6903 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 13:30:56.364  6903  6903 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 13:30:56.381  6903  6903 I BrowserStartupController: Initializing chromium process, renderers=0
,08-11 13:30:56.382  6903  6903 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 13:30:56.398   315  1367 V AudioPolicyService: registerClient() client 0xb558a560, uid 10118
,08-11 13:30:56.404  6903  6903 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-11 13:30:56.405  6903  6903 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-11 13:30:56.405  6903  6903 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-11 13:30:56.408  1035  1117 D BluetoothManagerService: Message: 20
08-11 13:30:56.408  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2caa3718:true
08-11 13:30:56.422  6903  6903 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 13:30:56.422  6903  6903 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 13:30:56.422  6903  6903 I Adreno-EGL: Build Date: 12/12/14 금
08-11 13:30:56.422  6903  6903 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 13:30:56.422  6903  6903 I Adreno-EGL: Remote Branch: 
08-11 13:30:56.422  6903  6903 I Adreno-EGL: Local Patches: 
08-11 13:30:56.422  6903  6903 I Adreno-EGL: Reconstruct Branch: 
,08-11 13:30:56.509  6903  6944 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-11 13:30:56.513  6903  6903 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-11 13:30:56.531  6903  6903 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 13:30:56.537  6903  6903 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-11 13:30:56.540  6903  6903 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-11 13:30:56.542  6903  6903 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-11 13:30:56.542  6903  6903 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-11 13:30:56.555  6903  6903 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-11 13:30:56.566  6903  6903 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 13:30:56.566  6903  6903 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 13:30:56.601  6903  6959 D OpenGLRenderer: Render dirty regions requested: true
08-11 13:30:56.602  6903  6959 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 13:30:56.612  6903  6959 D OpenGLRenderer: Enabling debug mode 0
,08-11 13:30:56.621  6903  6903 D Atlas   : Validating map...
08-11 13:30:56.625  1035  2041 D SplitWindow: check instance of lgWin Window{1da0c092 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 13:30:56.695  6903  6954 D LgDataFeature: LgDataFeature() Constructor: none
,08-11 13:30:56.696  6903  6954 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 13:30:56.737  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +543ms (total +623ms)
,08-11 13:30:56.738  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3a0afdf u0 com.test.thalitest/.MainActivity t6} time:198157
08-11 13:30:56.739  6903  6903 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1f562562 time:198157
08-11 13:30:56.887  6903  6903 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-11 13:30:56.887  6903  6903 I chromium: 
,08-11 13:30:56.952  6903  6903 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 13:30:57.093  6903  6970 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435150848
,08-11 13:30:57.111  6903  6970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 13:30:57.111  6903  6970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 13:30:57.111  6903  6970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 13:30:57.111  6903  6970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 13:30:57.111  6903  6970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-11 13:30:57.112  6903  6970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b24c86 added. We now have 1 listener(s)
08-11 13:30:57.125  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 13:30:57.128  6903  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-11 13:30:57.130  6903  6970 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 13:30:57.131  6903  6970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 13:30:57.131  6903  6970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 13:30:57.138  6903  6970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 13:30:57.138  6903  6970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 13:30:57.138  6903  6970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 13:30:57.138  6903  6970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-11 13:30:57.138  6903  6970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 13:30:57.138  6903  6970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 13:30:57.138  6903  6970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 13:30:57.138  6903  6970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 13:30:57.138  6903  6970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 13:30:57.138  6903  6970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 13:30:57.138  6903  6970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 13:30:57.138  6903  6970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 13:30:57.138  6903  6970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 13:30:57.138  6903  6970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 13:30:57.138  6903  6970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cb4aa9d added. We now have 1 listener(s)
,08-11 13:30:57.139  6903  6970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 13:30:57.143  1035  1530 D WifiService: New client listening to asynchronous messages
08-11 13:30:57.146  6903  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 13:30:57.146  6903  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-11 13:30:57.147  6903  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 13:30:57.147  6903  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 13:30:57.147  6903  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 13:30:57.150  6903  6970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 13:30:57.151  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 13:30:57.153  6903  6970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-11 13:30:57.161  6903  6970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-11 13:30:57.161  6903  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 13:30:57.161  6903  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 13:30:57.161  6903  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 13:30:57.161  6903  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 13:30:57.161  6903  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 13:30:57.161  6903  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 13:30:57.161  6903  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 13:30:57.161  6903  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 13:30:57.161  6903  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 13:30:57.162  6903  6970 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 13:30:57.163  6903  6970 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 13:30:57.164  6903  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 13:30:57.166  6903  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 13:30:57.197  6903  6954 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-11 13:30:57.197  6903  6954 I chromium: 
,08-11 13:30:57.237  6903  6903 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 13:30:57.392   332   348 E GBMv2   : DFP En is all cleared set to be enabled
08-11 13:30:57.392   332   348 E GBMv2   : Set value is all cleared set the max
08-11 13:30:57.392   332   348 I GBMv2   : DFP Enabled. Ignore VFP set
,08-11 13:30:58.123  6903  6973 W jxcore-log: Initializing JXcore engine
08-11 13:30:58.123  6903  6973 W jxcore-log: JXcore engine is ready
,08-11 13:30:58.194  6973  6973 W Thread-802: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10320]" dev="sockfs" ino=10320 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-11 13:30:58.204  6973  6973 W Thread-802: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-11 13:30:58.204  6973  6973 W Thread-802: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7774]" dev="sockfs" ino=7774 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-11 13:30:58.204  6973  6973 W Thread-802: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-11 13:30:58.204  6973  6973 W Thread-802: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31342]" dev="sockfs" ino=31342 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-11 13:30:58.250  6903  6973 W jxcore-log: Starting JXcore engine
,08-11 13:30:58.403  6903  6973 W jxcore-log: Platform android
08-11 13:30:58.403  6903  6973 W jxcore-log: 
08-11 13:30:58.403  6903  6973 W jxcore-log: Process ARCH arm
08-11 13:30:58.403  6903  6973 W jxcore-log: 
,08-11 13:30:58.610  6903  6973 I jxcore-log: JXcore Cordova bridge is ready!
08-11 13:30:58.610  6903  6973 I jxcore-log: 
08-11 13:30:58.611  6903  6973 W jxcore-log: JXcore engine is started
,08-11 13:30:58.619  6903  6970 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-11 13:30:58.622  6903  6903 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-11 13:31:00.051  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-11 13:31:00.051  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
08-11 13:31:00.051  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-11 13:31:00.052  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,08-11 13:31:00.056  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
08-11 13:31:00.056  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-11 13:31:00.057  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-11 13:31:00.058  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,08-11 13:31:09.788  6903  6973 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 13:31:09.788  6903  6973 I jxcore-log: 
,08-11 13:31:09.790  6903  6973 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 13:31:09.790  6903  6973 I jxcore-log: 
08-11 13:31:09.794  6903  6973 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 13:31:09.794  6903  6973 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 13:31:09.794  6903  6973 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 13:31:09.794  6903  6973 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 13:31:09.794  6903  6973 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 13:31:09.794  6903  6973 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 13:31:09.794  6903  6973 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 13:31:09.794  6903  6973 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 13:31:09.797  6903  6973 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 13:31:09.799  6903  6973 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 13:31:09.799  6903  6973 I jxcore-log: 
08-11 13:31:09.801  6903  6973 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 13:31:09.801  6903  6973 I jxcore-log: 
,08-11 13:31:10.123  6903  6973 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-11 13:31:10.123  6903  6973 I jxcore-log: Failed to execute UT.,
08-11 13:31:10.123  6903  6973 I jxcore-log: 
08-11 13:31:10.124  6903  6973 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 13:31:10.124  6903  6973 I jxcore-log: 
,08-11 13:31:10.133  6903  6903 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-11 13:31:10.135  6903  6973 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 13:31:10.135  6903  6973 I jxcore-log: 
08-11 13:31:10.442  6983  6983 D AndroidRuntime: 
08-11 13:31:10.442  6983  6983 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-11 13:31:10.446  6983  6983 D AndroidRuntime: CheckJNI is OFF
08-11 13:31:10.598  6983  6983 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 13:31:10.614  1035  1098 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-11 13:31:10.616  1035  1098 I ActivityManager: Killing 6903:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-11 13:31:10.681  1035  1729 I WindowState: WIN DEATH: Window{1da0c092 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 13:31:10.682  1035  1530 D WifiService: Client connection lost with reason: 4
08-11 13:31:10.692  1035  1729 D InputDispatcher: Window went away: Window{1da0c092 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 13:31:10.881  1035  1098 I ActivityManager:   Force finishing activity ActivityRecord{3a0afdf u0 com.test.thalitest/.MainActivity t6}
,08-11 13:31:10.907   332   346 E GBMv2   : DFP En is all cleared set to be enabled
08-11 13:31:10.913  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-11 13:31:10.920  1035  1123 I ActivityManager:   Force finishing activity ActivityRecord{3a0afdf u0 com.test.thalitest/.MainActivity t6 f}
08-11 13:31:10.921  1035  1123 W ActivityManager: Duplicate finish request for ActivityRecord{3a0afdf u0 com.test.thalitest/.MainActivity t6 f}
,08-11 13:31:10.951  1954  1970 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-11 13:31:10.951  1954  1970 D SplitWindowPolicy: topRunningActivity=ActivityInfo{23599df7 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-11 13:31:10.952  1035  2010 W ActivityManager: Spurious death for ProcessRecord{208f2178 6903:com.test.thalitest/u0a118}, curProc for 6903: null
08-11 13:31:10.953  1954  1969 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-11 13:31:10.953  2075  2075 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-11 13:31:10.954  1954  1969 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3f53b464 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-11 13:31:10.955  2075  2075 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-11 13:31:10.959  2075  2075 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-11 13:31:10.960  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-11 13:31:10.962  2075  2164 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-11 13:31:10.970  4148  4148 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-11 13:31:10.970  4148  4148 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-11 13:31:10.971  2015  2015 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-11 13:31:10.972  3824  3824 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-11 13:31:10.975  2443  2615 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-11 13:31:10.976  4815  4815 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-11 13:31:10.976  4815  4815 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-11 13:31:10.976  4815  4815 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-11 13:31:10.976  4815  4815 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-11 13:31:10.976  4815  4815 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 13:31:10.976  4815  4815 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 13:31:10.977  4815  4815 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 13:31:10.977  4815  4815 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 13:31:10.977  4815  4815 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 13:31:10.977  4815  4815 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 13:31:10.978  4815  4815 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 13:31:10.978  4815  4815 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 13:31:10.982  1035  1454 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 13:31:11.008  1035  1097 W InputMethodInfo: Duplicated subtype definition found: , voice
08-11 13:31:11.039  2075  2075 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-11 13:31:11.042  1917  1917 D ActionManagerService: notifyUserLog: 1000003
08-11 13:31:11.042  2075  2075 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-11 13:31:11.043  3824  4802 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-11 13:31:11.044  2075  2075 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-11 13:31:11.045  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-11 13:31:11.046  2075  2075 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-11 13:31:11.049  1588  1638 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 13:31:11.049  1588  1638 D KeyguardModel: createShortcutInfo...
08-11 13:31:11.050  2075  2075 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-11 13:31:11.051  1917  1917 D ActionManagerService: notifyUserLog: 1000004
08-11 13:31:11.052  3824  4802 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-11 13:31:11.053  3824  3840 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , create_time: 1430832262123
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , expire_time: 0
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , display: false
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , animation: false }
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , create_time: 1430832262287
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , expire_time: 0
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , display: false
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , animation: false }
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , create_time: 1470393743569
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , expire_time: 0
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , display: false
08-11 13:31:11.057  2075  2075 I GBoardWebViewUtils: , animation: false }
08-11 13:31:11.058  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-11 13:31:11.058  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-11 13:31:11.061  1588  1638 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 13:31:11.061  1588  1638 D KeyguardModel: createShortcutInfo...
08-11 13:31:11.067  2075  7009 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-11 13:31:11.082  1883  1883 D SplitUIManager: split_name #11 / not available #0
08-11 13:31:11.083  1883  1883 D SplitUIService: removed split : 
08-11 13:31:11.083  2075  2075 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 13:31:11.083  2075  2075 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-11 13:31:11.084  1588  1638 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-11 13:31:11.085  1588  1638 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 13:31:11.085  1588  1638 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-11 13:31:11.086  1588  1638 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-11 13:31:11.089  1588  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 13:31:11.089  1588  1638 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 13:31:11.091  1588  1638 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 13:31:11.091  1588  1638 D KeyguardModel: createShortcutInfo...
08-11 13:31:11.092  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-11 13:31:11.097  1805  1805 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-11 13:31:11.106  2212  2212 I ConfigService: onCreate
08-11 13:31:11.106  2212  2212 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-11 13:31:11.110  1805  1805 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-11 13:31:11.110  1588  1638 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-11 13:31:11.110  1588  1638 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 13:31:11.116  1588  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 13:31:11.116  1588  1638 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 13:31:11.123  2212  2212 I ConfigService: onBind returning update interface
,08-11 13:31:11.142  1588  1638 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 13:31:11.142  1588  1638 D KeyguardModel: createShortcutInfo...
08-11 13:31:11.142  2212  2212 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-11 13:31:11.142  2212  2212 I ConfigService: onBind returning config service
,08-11 13:31:11.154  1588  1638 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 13:31:11.154  1588  1638 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-11 13:31:11.154  1588  1638 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-11 13:31:11.154  1588  1638 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-11 13:31:11.157  1035  1729 V SIM_STK : Menu title from STK is T-Mobile
08-11 13:31:11.159  4923  4923 I art     : Explicit concurrent mark sweep GC freed 498(33KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 20.552ms total 227.855ms
08-11 13:31:11.163  1588  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 13:31:11.163  1588  1638 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 13:31:11.164  1588  1638 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 13:31:11.164  1588  1638 D KeyguardModel: createShortcutInfo...
08-11 13:31:11.171  2212  2212 I ConfigService: onDestroy
08-11 13:31:11.171  2075  2075 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-11 13:31:11.172  1035  1760 V SIM_STK : Menu title from STK is T-Mobile
08-11 13:31:11.172  1035  1760 V SIM_STK : Menu title from STK is T-Mobile
,08-11 13:31:11.180  1805  7014 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-11 13:31:11.190  1883  1883 D SplitUIManager: split_name #11 / not available #0
08-11 13:31:11.190  1883  1883 I SplitUIService: split app #11
08-11 13:31:11.200  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-11 13:31:11.200  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-11 13:31:11.207  1588  1638 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 13:31:11.207  1588  1638 D KeyguardModel: createShortcutInfo...
08-11 13:31:11.209  1588  1638 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 13:31:11.209  1588  1638 D KeyguardModel: createShortcutInfo...
08-11 13:31:11.211  1588  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 13:31:11.211  1588  1638 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 13:31:11.212  1588  1638 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 13:31:11.212  1588  1638 D KeyguardModel: createShortcutInfo...
,08-11 13:31:11.221  1035  1035 I art     : Explicit concurrent mark sweep GC freed 29650(1920KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 5.557ms total 276.263ms
08-11 13:31:11.221  1588  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 13:31:11.222  1588  1638 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 13:31:11.224  6195  7020 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-11 13:31:11.228  1035  1123 I art     : WaitForGcToComplete blocked for 278.296ms for cause Explicit
,08-11 13:31:11.231  1588  1638 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 13:31:11.232  1588  1638 D KeyguardModel: createShortcutInfo...
08-11 13:31:11.234  1805  7022 I PeopleContactsSync: CP2 sync disabled
08-11 13:31:11.234  1588  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 13:31:11.234  1588  1638 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-11 13:31:11.236  1588  1638 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 13:31:11.236  1588  1638 D KeyguardModel: createShortcutInfo...
08-11 13:31:11.236  1035  1611 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-11 13:31:11.236  4148  4148 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-11 13:31:11.236  4148  4148 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-11 13:31:11.236  4148  4148 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-11 13:31:11.236  4148  4148 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-11 13:31:11.236  4148  4148 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-11 13:31:11.236  4148  4148 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 13:31:11.236  4148  4148 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-11 13:31:11.236  4148  4148 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-11 13:31:11.236  4148  4148 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-11 13:31:11.236  4148  4148 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 13:31:11.236  4148  4148 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-11 13:31:11.242  1805  5094 I Icing   : doRemovePackageData com.test.thalitest
08-11 13:31:11.261  6467  6467 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-11 13:31:11.270  1035  1035 D administrator: Handling package changes for user 0
08-11 13:31:11.270  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-11 13:31:11.270  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-11 13:31:11.290  1805  7019 W GmsApplication: Using Auth Proxy for data requests.
,08-11 13:31:11.292  2192  7025 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-11 13:31:11.295  6522  6522 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-11 13:31:11.296  2075  2075 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-11 13:31:11.299  2075  2075 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 13:31:11.301  2075  2075 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-11 13:31:11.302  2075  2075 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-11 13:31:11.302  1805  7019 W GmsApplication: Using Auth Proxy for data requests.
08-11 13:31:11.303  2075  2075 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-11 13:31:11.304  2075  2075 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-11 13:31:11.315  2015  2015 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-11 13:31:11.315  2015  2015 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-11 13:31:11.316  2015  2015 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-11 13:31:11.320  6378  6378 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-11 13:31:11.323  2075  2075 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-11 13:31:11.323  2075  2075 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 13:31:11.323  2075  2277 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-11 13:31:11.324  2075  2277 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-11 13:31:11.332  1035  1989 V SIM_STK : Menu title from STK is T-Mobile
08-11 13:31:11.333  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2b97292 u0 com.lge.launcher2/.Launcher t5} time:212752
,08-11 13:31:11.346  2075  2075 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-11 13:31:11.346  2075  2075 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-11 13:31:11.346  2075  2075 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 13:31:11.355  2075  2075 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-11 13:31:11.364  1035  1950 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7030 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-11 13:31:11.366  2636  2636 D [Concierge]Service: onStartCommand(). Type : 8
08-11 13:31:11.366  2636  2636 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-11 13:31:11.367  2636  2636 D [Concierge]Service: Update widget ID : 11
08-11 13:31:11.370  2075  2075 D [Concierge]WidgetView: change position of spinner
08-11 13:31:11.371  2636  2636 D [Concierge]Service: onStartCommand(). Type : 0
08-11 13:31:11.371  2075  2075 I [Concierge]WidgetView: initWebView(). Time : 1470915071371
08-11 13:31:11.384  2075  2075 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 104179290
08-11 13:31:11.385  2075  2075 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-11 13:31:11.385  2075  2075 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-11 13:31:11.388  2075  2075 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3eac1985
08-11 13:31:11.388  2075  2075 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-11 13:31:11.391  2075  2075 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-11 13:31:11.391  2075  2075 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 13:31:11.400  2075  2075 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-11 13:31:11.400  2075  2075 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-11 13:31:11.401  2075  2075 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470914887097, New one : 1470915071371
08-11 13:31:11.401  2075  2075 D [Concierge]WidgetView: Unregister all receivers
,08-11 13:31:11.402  2075  2075 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-11 13:31:11.403  2075  2075 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 13:31:11.404  2075  2075 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-11 13:31:11.405  2075  2075 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-11 13:31:11.406  2075  2075 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-11 13:31:11.408  2075  2075 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-11 13:31:11.409  2075  2075 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-11 13:31:11.410  2075  2075 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 13:31:11.410  2075  2075 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 13:31:11.413  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-11 13:31:11.413  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 13:31:11.413  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-11 13:31:11.418  1035  1564 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-11 13:31:11.446  2075  2075 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-11 13:31:11.456  2075  2075 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-11 13:31:11.456  2075  2075 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-11 13:31:11.457  2075  2075 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-11 13:31:11.458  2075  2075 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-11 13:31:11.478  2075  2075 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d464817 time:212896
08-11 13:31:11.503  7030  7030 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-11 13:31:11.503  7030  7030 W LG Account v2.2: No ProfileInfo entries
08-11 13:31:11.503  7030  7030 I LG Account v2.2: isEnabled: false
08-11 13:31:11.503  7030  7030 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-11 13:31:11.503  7030  7030 I Feature : [Lifetracker]Country: EU
08-11 13:31:11.503  7030  7030 I Feature : [Lifetracker]Operator: OPEN
08-11 13:31:11.503  7030  7030 I Feature : [Lifetracker]Ranking support: false
08-11 13:31:11.503  7030  7030 I Feature : [Lifetracker]Comfort support: false
08-11 13:31:11.503  7030  7030 I Feature : [Lifetracker]Accessory: true
08-11 13:31:11.503  7030  7030 I Feature : [Lifetracker]Health device: true
08-11 13:31:11.503  7030  7030 I Feature : [Lifetracker]Extra Pedometer: false
08-11 13:31:11.503  7030  7030 I Feature : [Lifetracker]Blood glucose device: false
08-11 13:31:11.503  7030  7030 I Feature : [Lifetracker]Device Number: 3
08-11 13:31:11.504  7030  7030 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-11 13:31:11.512  1035  1123 I art     : Explicit concurrent mark sweep GC freed 10228(601KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.625ms total 284.076ms
08-11 13:31:11.536  1035  2041 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7050 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-11 13:31:11.537  1035  2041 I ActivityManager: Killing 6257:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-11 13:31:11.573  1035  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 13:31:11.578  1035  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-11 13:31:11.581  6983  6983 D AndroidRuntime: Shutting down VM
08-11 13:31:11.600  2075  2075 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-11 13:31:11.633  1035  1760 W libprocessgroup: failed to open /acct/uid_10004/pid_6257/cgroup.procs: No such file or directory
,08-11 13:31:11.637  2075  2929 I GBoardtInterface: onReloaded()
08-11 13:31:11.639  2075  2075 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-11 13:31:11.653  3824  3840 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-11 13:31:11.658  3824  3984 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 13:31:11.675  1917  1917 D ActionManagerService: notifyUserLog: 1000001
,08-11 13:31:11.675  7050  7050 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 13:31:11.676  7050  7050 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-11 13:31:11.676  7050  7050 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 13:31:11.676  7050  7050 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-11 13:31:11.677  3824  4802 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-11 13:31:11.677  3824  4802 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-11 13:31:11.678  7050  7050 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-11 13:31:11.679  7050  7050 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-11 13:31:11.689  1917  1917 D ActionManagerService: notifyUserLog: 1000001
,08-11 13:31:11.691  3824  4802 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-11 13:31:11.691  3824  4802 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-11 13:31:11.692  3824  4802 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-11 13:31:11.692  3824  4802 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-11 13:31:11.695  3824  3840 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 13:31:11.702  2075  2075 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-11 13:31:11.702  2075  2075 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,08-11 13:31:11.707  2075  2075 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-11 13:31:11.707  2075  2075 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-11 13:31:11.712  2075  2075 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-11 13:31:11.712  2075  2075 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-11 13:31:11.718  2075  2075 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-11 13:31:11.847  1035  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7067 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-11 13:31:11.854  7050  7050 D PackageIntentReceiver: Not supported Hotkey customization function 
08-11 13:31:11.861  7050  7050 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
,08-11 13:31:11.861  7050  7050 D HideNavigationAppsReceiver: replacing : false
08-11 13:31:11.864  7050  7050 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-11 13:31:11.871  7050  7050 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-11 13:31:11.871  7050  7050 D ButtonCombinationReceiver: replacing : false
,08-11 13:31:11.882  1035  1971 I ActivityManager: Killing 6422:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-11 13:31:11.951  1035  1989 W libprocessgroup: failed to open /acct/uid_10008/pid_6422/cgroup.procs: No such file or directory
08-11 13:31:11.956  4923  7085 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE

```
