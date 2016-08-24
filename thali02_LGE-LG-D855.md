#### Test 79763830cb90817_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-24 16:37:00.077  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 16:37:00.077  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 16:37:00.077  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 16:37:00.078  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-24 16:37:00.091  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 16:37:00.091  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-24 16:37:00.097  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-24 16:37:00.099  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 16:37:00.404  6752  6752 D AndroidRuntime: 
08-24 16:37:00.404  6752  6752 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 16:37:00.409  6752  6752 D AndroidRuntime: CheckJNI is OFF
08-24 16:37:00.612  6752  6752 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 16:37:00.623  1035  2341 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 16:37:00.638  1968  3950 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-24 16:37:00.644  1035  2341 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-24 16:37:00.645  1035  2341 D ActivityManager: setTaskToReturnTo : TaskRecord{1dac98e3 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 16:37:00.645  1035  2341 D ActivityManager: setTaskToReturnTo : TaskRecord{1dac98e3 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 16:37:00.647  1035  2341 D WindowStateEx: AppWindowTokenEx init.. 
08-24 16:37:00.648   345   360 E GBMv2   : DFP En is all cleared set to be enabled
08-24 16:37:00.676  1035  2341 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6767 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 16:37:00.679  6752  6752 D AndroidRuntime: Shutting down VM
08-24 16:37:00.738  1968  1983 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-24 16:37:00.738  1968  1983 D SplitWindowPolicy: topRunningActivity=ActivityInfo{34f8175 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-24 16:37:00.739  1968  1984 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-24 16:37:00.739  1968  1984 D SplitWindowPolicy: topRunningActivity=ActivityInfo{37c9f50a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-24 16:37:00.789  6767  6767 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-24 16:37:00.890  6767  6767 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-24 16:37:00.898  6767  6767 I LibraryLoader: Loading: webviewchromium
08-24 16:37:00.901  6767  6767 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3664-3667)
08-24 16:37:00.901  6767  6767 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 16:37:00.918  6767  6767 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {306efeb}
,08-24 16:37:00.919  6767  6767 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 16:37:00.919  6767  6767 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 16:37:00.928  6767  6767 I BrowserStartupController: Initializing chromium process, renderers=0
,08-24 16:37:00.929  6767  6767 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 16:37:00.943  6767  6767 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-24 16:37:00.944  6767  6767 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-24 16:37:00.944  6767  6767 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-24 16:37:00.957  6767  6767 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 16:37:00.957  6767  6767 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 16:37:00.957  6767  6767 I Adreno-EGL: Build Date: 12/12/14 금
08-24 16:37:00.957  6767  6767 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 16:37:00.957  6767  6767 I Adreno-EGL: Remote Branch: 
08-24 16:37:00.957  6767  6767 I Adreno-EGL: Local Patches: 
08-24 16:37:00.957  6767  6767 I Adreno-EGL: Reconstruct Branch: 
,08-24 16:37:00.957   327  1397 V AudioPolicyService: registerClient() client 0xb558ac20, uid 10118
08-24 16:37:00.964  1035  1117 D BluetoothManagerService: Message: 20
08-24 16:37:00.964  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@308f655:true
08-24 16:37:01.028  6767  6812 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-24 16:37:01.036  6767  6767 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-24 16:37:01.060  6767  6767 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 16:37:01.067  6767  6767 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-24 16:37:01.071  6767  6767 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-24 16:37:01.074  6767  6767 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-24 16:37:01.074  6767  6767 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-24 16:37:01.091  6767  6767 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-24 16:37:01.099  6767  6767 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 16:37:01.099  6767  6767 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 16:37:01.135  6767  6830 D OpenGLRenderer: Render dirty regions requested: true
08-24 16:37:01.135  6767  6830 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 16:37:01.141  6767  6830 D OpenGLRenderer: Enabling debug mode 0
08-24 16:37:01.148  6767  6767 D Atlas   : Validating map...
,08-24 16:37:01.152  1035  1985 D SplitWindow: check instance of lgWin Window{2e4afd27 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 16:37:01.189  6767  6825 D LgDataFeature: LgDataFeature() Constructor: none
08-24 16:37:01.189  6767  6825 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 16:37:01.280  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +543ms (total +631ms)
08-24 16:37:01.281  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1ba472e0 u0 com.test.thalitest/.MainActivity t6} time:174047
,08-24 16:37:01.284  6767  6767 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2abb13b6 time:174050
08-24 16:37:01.392  6767  6767 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-24 16:37:01.392  6767  6767 I chromium: 
,08-24 16:37:01.442  6767  6767 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 16:37:01.511  6767  6825 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-24 16:37:01.511  6767  6825 I chromium: 
,08-24 16:37:01.640  6767  6841 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434975744
,08-24 16:37:01.658  6767  6841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 16:37:01.658  6767  6841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 16:37:01.658  6767  6841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 16:37:01.658  6767  6841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 16:37:01.658  6767  6841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 16:37:01.658  6767  6841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86faa9a added. We now have 1 listener(s)
08-24 16:37:01.667  1035  2250 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:37:01.670  6767  6841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-24 16:37:01.674  6767  6841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-24 16:37:01.678  6767  6841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 16:37:01.678  6767  6841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:37:01.687  6767  6841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 16:37:01.687  6767  6841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 16:37:01.687  6767  6841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 16:37:01.687  6767  6841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-24 16:37:01.687  6767  6841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 16:37:01.687  6767  6841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 16:37:01.687  6767  6841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 16:37:01.687  6767  6841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 16:37:01.687  6767  6841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 16:37:01.687  6767  6841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 16:37:01.687  6767  6841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 16:37:01.687  6767  6841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 16:37:01.687  6767  6841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 16:37:01.687  6767  6841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 16:37:01.687  6767  6841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c72dec1 added. We now have 1 listener(s)
08-24 16:37:01.688  6767  6841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 16:37:01.695  1035  1475 D WifiService: New client listening to asynchronous messages
08-24 16:37:01.700  6767  6841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 16:37:01.700  6767  6841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-24 16:37:01.704  6767  6841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 16:37:01.704  6767  6841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 16:37:01.705  6767  6841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-24 16:37:01.715  6767  6841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:37:01.716  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 16:37:01.718  6767  6841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-24 16:37:01.735  6767  6841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-24 16:37:01.736  6767  6841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:37:01.736  6767  6841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:37:01.736  6767  6841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:37:01.736  6767  6841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:37:01.736  6767  6841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:37:01.736  6767  6841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:37:01.736  6767  6841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:37:01.736  6767  6841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:37:01.736  6767  6841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 16:37:01.736  6767  6841 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 16:37:01.740  6767  6841 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 16:37:01.741  6767  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:37:01.744  6767  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:37:01.808  6767  6767 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 16:37:02.077   345   362 E GBMv2   : DFP En is all cleared set to be enabled
08-24 16:37:02.077   345   362 E GBMv2   : Set value is all cleared set the max
08-24 16:37:02.077   345   362 I GBMv2   : DFP Enabled. Ignore VFP set
,08-24 16:37:02.944  6767  6844 W jxcore-log: Initializing JXcore engine
08-24 16:37:02.944  6767  6844 W jxcore-log: JXcore engine is ready
,08-24 16:37:03.009  6844  6844 W Thread-771: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7434]" dev="sockfs" ino=7434 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-24 16:37:03.009  6844  6844 W Thread-771: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-24 16:37:03.009  6844  6844 W Thread-771: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10039]" dev="sockfs" ino=10039 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-24 16:37:03.009  6844  6844 W Thread-771: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-24 16:37:03.009  6844  6844 W Thread-771: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33314]" dev="sockfs" ino=33314 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-24 16:37:03.044  6767  6844 W jxcore-log: Starting JXcore engine
,08-24 16:37:03.198  6767  6844 W jxcore-log: Platform android
08-24 16:37:03.198  6767  6844 W jxcore-log: 
08-24 16:37:03.198  6767  6844 W jxcore-log: Process ARCH arm
08-24 16:37:03.198  6767  6844 W jxcore-log: 
,08-24 16:37:03.580  6767  6844 I jxcore-log: JXcore Cordova bridge is ready!
08-24 16:37:03.580  6767  6844 I jxcore-log: 
08-24 16:37:03.580  6767  6844 W jxcore-log: JXcore engine is started
,08-24 16:37:03.590  6767  6841 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-24 16:37:03.597  6767  6767 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 16:37:18.119  6767  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 16:37:18.119  6767  6844 I jxcore-log: 
,08-24 16:37:18.122  6767  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-24 16:37:18.122  6767  6844 I jxcore-log: 
08-24 16:37:18.127  6767  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:37:18.127  6767  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:37:18.127  6767  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 16:37:18.127  6767  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:37:18.127  6767  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:37:18.127  6767  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,08-24 16:37:18.127  6767  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:37:18.127  6767  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:37:18.130  6767  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:37:18.132  6767  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 16:37:18.132  6767  6844 I jxcore-log: 
,08-24 16:37:18.135  6767  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 16:37:18.135  6767  6844 I jxcore-log: 
,08-24 16:37:18.631  6767  6844 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests,
08-24 16:37:18.631  6767  6844 I jxcore-log: Failed to execute UT.
,08-24 16:37:18.631  6767  6844 I jxcore-log: 
08-24 16:37:18.631  6767  6844 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
08-24 16:37:18.631  6767  6844 I jxcore-log: 
,08-24 16:37:18.642  6767  6767 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-24 16:37:18.644  6767  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:37:18.644  6767  6844 I jxcore-log: 
08-24 16:37:18.988  6862  6862 D AndroidRuntime: 
08-24 16:37:18.988  6862  6862 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-24 16:37:18.995  6862  6862 D AndroidRuntime: CheckJNI is OFF
08-24 16:37:19.205  6862  6862 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 16:37:19.223  1035  1113 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-24 16:37:19.224  1035  1113 I ActivityManager: Killing 6767:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-24 16:37:19.291  1035  1949 I WindowState: WIN DEATH: Window{2e4afd27 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 16:37:19.296  1035  1475 D WifiService: Client connection lost with reason: 4
08-24 16:37:19.301  1035  1949 D InputDispatcher: Window went away: Window{2e4afd27 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 16:37:19.469  1035  1113 I ActivityManager:   Force finishing activity ActivityRecord{1ba472e0 u0 com.test.thalitest/.MainActivity t6}
,08-24 16:37:19.521   345   360 E GBMv2   : DFP En is all cleared set to be enabled
,08-24 16:37:19.530  1035  1577 W ActivityManager: Spurious death for ProcessRecord{9344335 6767:com.test.thalitest/u0a118}, curProc for 6767: null
08-24 16:37:19.530  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-24 16:37:19.538  1035  1123 I ActivityManager:   Force finishing activity ActivityRecord{1ba472e0 u0 com.test.thalitest/.MainActivity t6 f}
08-24 16:37:19.538  1035  1123 W ActivityManager: Duplicate finish request for ActivityRecord{1ba472e0 u0 com.test.thalitest/.MainActivity t6 f}
,08-24 16:37:19.572  1968  1983 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-24 16:37:19.572  1968  1983 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1962917b co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-24 16:37:19.573  2089  2089 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-24 16:37:19.574  1968  3950 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-24 16:37:19.574  2089  2089 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-24 16:37:19.574  1968  3950 D SplitWindowPolicy: topRunningActivity=ActivityInfo{176d9b98 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-24 16:37:19.578  2089  2089 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-24 16:37:19.580  2089  2197 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-24 16:37:19.586  3839  3839 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-24 16:37:19.586  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-24 16:37:19.587  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-24 16:37:19.588  2040  2040 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-24 16:37:19.590  1035  1380 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-24 16:37:19.591  3788  3788 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-24 16:37:19.592  2506  2612 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-24 16:37:19.631  1035  1770 V SIM_STK : Menu title from STK is T-Mobile
,08-24 16:37:19.652  4607  4607 I art     : Explicit concurrent mark sweep GC freed 480(32KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 471us total 106.303ms
,08-24 16:37:19.660  6434  6434 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-24 16:37:19.663  1931  1931 D ActionManagerService: notifyUserLog: 1000003
08-24 16:37:19.665  3788  4476 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-24 16:37:19.667  1035  1112 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-24 16:37:19.682  2089  2089 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-24 16:37:19.686  2089  2089 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-24 16:37:19.686  1839  1839 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-24 16:37:19.687  4487  4487 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-24 16:37:19.688  4487  4487 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-24 16:37:19.688  4487  4487 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-24 16:37:19.688  4487  4487 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-24 16:37:19.688  4487  4487 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 16:37:19.688  4487  4487 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 16:37:19.688  4487  4487 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 16:37:19.688  4487  4487 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 16:37:19.688  4487  4487 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:37:19.688  4487  4487 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 16:37:19.688  4487  4487 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 16:37:19.688  4487  4487 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-24 16:37:19.696  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-24 16:37:19.696  2089  2089 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-24 16:37:19.699  2089  2089 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-24 16:37:19.700  1603  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-24 16:37:19.700  1603  1656 D KeyguardModel: createShortcutInfo...
08-24 16:37:19.706  1931  1931 D ActionManagerService: notifyUserLog: 1000004
08-24 16:37:19.706  1603  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-24 16:37:19.706  1603  1656 D KeyguardModel: createShortcutInfo...
08-24 16:37:19.706  2089  2089 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-24 16:37:19.707  3788  4476 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-24 16:37:19.712  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-24 16:37:19.712  1603  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 16:37:19.712  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-24 16:37:19.713  3788  3803 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 16:37:19.715  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 16:37:19.715  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 16:37:19.716  1603  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-24 16:37:19.717  1603  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-24 16:37:19.718  1603  1656 D KeyguardModel: createShortcutInfo...
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , create_time: 1430832262123
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , expire_time: 0
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , display: false
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , animation: false }
,08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , create_time: 1430832262287
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , expire_time: 0
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , display: false
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , animation: false }
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , create_time: 1471602816196
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , expire_time: 0
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , display: false
08-24 16:37:19.718  2089  2089 I GBoardWebViewUtils: , animation: false }
08-24 16:37:19.719  1897  1897 D SplitUIManager: split_name #11 / not available #0
08-24 16:37:19.720  1897  1897 D SplitUIService: removed split : 
08-24 16:37:19.722  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-24 16:37:19.722  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-24 16:37:19.728  2089  6899 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-24 16:37:19.732  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-24 16:37:19.732  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 16:37:19.734  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 16:37:19.738  1603  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-24 16:37:19.744  1035  1769 V SIM_STK : Menu title from STK is T-Mobile
08-24 16:37:19.744  1035  1769 V SIM_STK : Menu title from STK is T-Mobile
08-24 16:37:19.744  1603  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 16:37:19.744  1603  1656 D KeyguardModel: createShortcutInfo...
,08-24 16:37:19.755  1603  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 16:37:19.755  1603  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-24 16:37:19.756  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-24 16:37:19.756  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 16:37:19.759  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 16:37:19.759  1603  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-24 16:37:19.761  1603  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 16:37:19.761  1603  1656 D KeyguardModel: createShortcutInfo...
,08-24 16:37:19.762  1035  1035 I art     : Explicit concurrent mark sweep GC freed 45257(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 3.661ms total 195.265ms
08-24 16:37:19.764  1035  1985 I art     : WaitForGcToComplete blocked for 63.689ms for cause Explicit
08-24 16:37:19.764  1897  1897 D SplitUIManager: split_name #11 / not available #0
08-24 16:37:19.764  1897  1897 I SplitUIService: split app #11
08-24 16:37:19.784  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-24 16:37:19.784  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-24 16:37:19.789  1603  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,08-24 16:37:19.789  1603  1656 D KeyguardModel: createShortcutInfo...
08-24 16:37:19.791  1603  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-24 16:37:19.791  1603  1656 D KeyguardModel: createShortcutInfo...
08-24 16:37:19.801  1035  2033 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-24 16:37:19.801  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-24 16:37:19.801  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-24 16:37:19.801  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-24 16:37:19.801  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-24 16:37:19.801  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-24 16:37:19.801  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 16:37:19.801  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-24 16:37:19.801  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-24 16:37:19.801  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-24 16:37:19.801  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 16:37:19.801  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-24 16:37:19.802  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 16:37:19.802  1603  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-24 16:37:19.818  1603  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,08-24 16:37:19.818  1603  1656 D KeyguardModel: createShortcutInfo...
,08-24 16:37:19.827  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 16:37:19.827  1603  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-24 16:37:19.830  1603  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 16:37:19.830  1603  1656 D KeyguardModel: createShortcutInfo...
08-24 16:37:19.831  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 16:37:19.831  1603  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-24 16:37:19.832  1603  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 16:37:19.832  1603  1656 D KeyguardModel: createShortcutInfo...
,08-24 16:37:19.840  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-24 16:37:19.840  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-24 16:37:19.841  1035  1035 D administrator: Handling package changes for user 0
08-24 16:37:19.882  1035  1985 I art     : Explicit concurrent mark sweep GC freed 5479(404KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.176ms total 116.911ms
08-24 16:37:19.882  1035  1123 I art     : WaitForGcToComplete blocked for 201.160ms for cause Explicit
,08-24 16:37:19.890  1035  2088 V SIM_STK : Menu title from STK is T-Mobile
08-24 16:37:19.896  2243  2243 I ConfigService: onCreate
08-24 16:37:19.898  2243  2243 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-24 16:37:19.901  1839  1839 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-24 16:37:19.906  2089  2089 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 16:37:19.907  2089  2089 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-24 16:37:19.919  2243  2243 I ConfigService: onBind returning update interface
,08-24 16:37:19.920  2243  2243 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-24 16:37:19.920  2243  2243 I ConfigService: onBind returning config service
08-24 16:37:19.923  2243  2243 I ConfigService: onDestroy
08-24 16:37:19.927  1839  6902 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-24 16:37:19.951  5927  6907 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-24 16:37:19.961  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-24 16:37:19.961  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 16:37:19.961  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-24 16:37:19.963  1035  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-24 16:37:19.978  1839  6909 I PeopleContactsSync: CP2 sync disabled
,08-24 16:37:19.988  1839  6908 W GmsApplication: Using Auth Proxy for data requests.
08-24 16:37:19.990  2089  2089 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-24 16:37:19.995  1839  4752 I Icing   : doRemovePackageData com.test.thalitest
,08-24 16:37:19.996  1839  6908 W GmsApplication: Using Auth Proxy for data requests.
08-24 16:37:19.996  5999  5999 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-24 16:37:20.009  6534  6534 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-24 16:37:20.015  2223  6911 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-24 16:37:20.023  2040  2040 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-24 16:37:20.023  2040  2040 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-24 16:37:20.024  2040  2040 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,08-24 16:37:20.028  6434  6434 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-24 16:37:20.057  1035  2341 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6914 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-24 16:37:20.085  2089  2089 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-24 16:37:20.088  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-24 16:37:20.090  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-24 16:37:20.090  1035  1112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 16:37:20.091  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-24 16:37:20.092  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-24 16:37:20.093  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-24 16:37:20.096  1035  1112 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-24 16:37:20.108  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{17ade5e6 u0 com.lge.launcher2/.Launcher t5} time:192874
08-24 16:37:20.111  2089  2089 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-24 16:37:20.112  2089  2326 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-24 16:37:20.112  2089  2326 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-24 16:37:20.114  2089  2089 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-24 16:37:20.114  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 16:37:20.129  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-24 16:37:20.129  2089  2089 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-24 16:37:20.130  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 16:37:20.137  2089  2089 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-24 16:37:20.138  2633  2633 D [Concierge]Service: onStartCommand(). Type : 8
08-24 16:37:20.138  2633  2633 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-24 16:37:20.139  2633  2633 D [Concierge]Service: Update widget ID : 11
08-24 16:37:20.140  1035  1123 I art     : Explicit concurrent mark sweep GC freed 8294(443KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.118ms total 247.911ms
08-24 16:37:20.140  2089  2089 D [Concierge]WidgetView: change position of spinner
,08-24 16:37:20.141  2089  2089 I [Concierge]WidgetView: initWebView(). Time : 1472049440141
08-24 16:37:20.141  2633  2633 D [Concierge]Service: onStartCommand(). Type : 0
08-24 16:37:20.153  6914  6914 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-24 16:37:20.153  6914  6914 W LG Account v2.2: No ProfileInfo entries
08-24 16:37:20.153  6914  6914 I LG Account v2.2: isEnabled: false
08-24 16:37:20.153  6914  6914 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-24 16:37:20.153  6914  6914 I Feature : [Lifetracker]Country: EU
08-24 16:37:20.153  6914  6914 I Feature : [Lifetracker]Operator: OPEN
,08-24 16:37:20.153  6914  6914 I Feature : [Lifetracker]Ranking support: false
08-24 16:37:20.153  6914  6914 I Feature : [Lifetracker]Comfort support: false
08-24 16:37:20.153  6914  6914 I Feature : [Lifetracker]Accessory: true
08-24 16:37:20.153  6914  6914 I Feature : [Lifetracker]Health device: true
08-24 16:37:20.153  6914  6914 I Feature : [Lifetracker]Extra Pedometer: false
08-24 16:37:20.153  6914  6914 I Feature : [Lifetracker]Blood glucose device: false
08-24 16:37:20.153  6914  6914 I Feature : [Lifetracker]Device Number: 3
08-24 16:37:20.154  6914  6914 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-24 16:37:20.187  1035  1577 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6936 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-24 16:37:20.187  1035  1577 I ActivityManager: Killing 6202:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-24 16:37:20.211  6862  6862 D AndroidRuntime: Shutting down VM
,08-24 16:37:20.288  1035  2088 W libprocessgroup: failed to open /acct/uid_10014/pid_6202/cgroup.procs: No such file or directory
,08-24 16:37:20.325  2089  2089 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 799891758
,08-24 16:37:20.328  2089  2089 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-24 16:37:20.329  2089  2089 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-24 16:37:20.345  2089  2089 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3b79f329
08-24 16:37:20.346  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-24 16:37:20.350  2089  2089 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-24 16:37:20.350  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 16:37:20.360  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,08-24 16:37:20.361  2089  2089 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-24 16:37:20.361  2089  2089 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-24 16:37:20.362  2089  2089 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472049275843, New one : 1472049440141
08-24 16:37:20.362  2089  2089 D [Concierge]WidgetView: Unregister all receivers
08-24 16:37:20.362  2089  2089 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-24 16:37:20.364  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 16:37:20.370  6936  6936 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 16:37:20.370  6936  6936 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-24 16:37:20.370  6936  6936 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 16:37:20.371  6936  6936 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-24 16:37:20.371  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-24 16:37:20.372  6936  6936 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 16:37:20.373  6936  6936 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-24 16:37:20.376  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-24 16:37:20.380  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,08-24 16:37:20.384  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-24 16:37:20.386  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-24 16:37:20.387  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 16:37:20.388  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 16:37:20.440  2089  2089 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-24 16:37:20.450  2089  2089 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-24 16:37:20.451  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-24 16:37:20.452  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-24 16:37:20.479  2089  2089 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2b08299b time:193245
,08-24 16:37:20.522  6936  6936 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-24 16:37:20.528  6936  6936 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-24 16:37:20.528  6936  6936 D HideNavigationAppsReceiver: replacing : false
08-24 16:37:20.531  6936  6936 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-24 16:37:20.532  6936  6936 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-24 16:37:20.533  6936  6936 D ButtonCombinationReceiver: replacing : false
,08-24 16:37:20.545  1035  1051 I ActivityManager: Killing 6481:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-24 16:37:20.606   282   800 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
