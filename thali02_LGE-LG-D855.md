#### Test 797638306af5278_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-12 18:23:48.979  1601  1601 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-12 18:23:48.979  1601  1601 I [SystemUI]LGPowerUI: On Skip Timer : true
,--------- beginning of system
08-12 18:23:48.997  1940  2122 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-12 18:23:48.997  1940  2122 D LEDHandler: Battery Level Remaining: 100%
08-12 18:23:48.997  1940  2122 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
08-12 18:23:49.000  1601  1601 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
08-12 18:23:49.000  1601  1601 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-12 18:23:49.002  1033  1542 D WifiController: battery changed pluggedType: 2
08-12 18:23:49.002  1601  1601 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-12 18:23:49.005  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 18:23:49.005  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 18:23:49.007  3839  3957 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 18:23:49.012  6607  6607 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-12 18:23:49.291  6710  6710 D AndroidRuntime: 
08-12 18:23:49.291  6710  6710 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 18:23:49.295  6710  6710 D AndroidRuntime: CheckJNI is OFF
08-12 18:23:49.500  6710  6710 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 18:23:49.511  1033  2008 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 18:23:49.526  1940  2749 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-12 18:23:49.532  1033  2008 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-12 18:23:49.533  1033  2008 D ActivityManager: setTaskToReturnTo : TaskRecord{13dac4a7 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 18:23:49.533  1033  2008 D ActivityManager: setTaskToReturnTo : TaskRecord{13dac4a7 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 18:23:49.535  1033  2008 D WindowStateEx: AppWindowTokenEx init.. 
08-12 18:23:49.536   344   361 E GBMv2   : DFP En is all cleared set to be enabled
08-12 18:23:49.564  1033  2008 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6725 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 18:23:49.567  6710  6710 D AndroidRuntime: Shutting down VM
08-12 18:23:49.624  1940  2749 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-12 18:23:49.624  1940  2749 D SplitWindowPolicy: topRunningActivity=ActivityInfo{33b6fec7 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 18:23:49.627  1940  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-12 18:23:49.627  1940  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1b754cf4 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 18:23:49.676  6725  6725 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-12 18:23:49.783  6725  6725 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-12 18:23:49.791  6725  6725 I LibraryLoader: Loading: webviewchromium
,08-12 18:23:49.794  6725  6725 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9173-9177)
08-12 18:23:49.795  6725  6725 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-12 18:23:49.811  6725  6725 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3809b30d}
,08-12 18:23:49.812  6725  6725 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 18:23:49.813  6725  6725 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 18:23:49.822  6725  6725 I BrowserStartupController: Initializing chromium process, renderers=0
,08-12 18:23:49.823  6725  6725 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 18:23:49.837  6725  6725 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-12 18:23:49.838  6725  6725 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-12 18:23:49.839  6725  6725 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-12 18:23:49.844   325  1380 V AudioPolicyService: registerClient() client 0xb558a860, uid 10118
08-12 18:23:49.850  1033  1099 D BluetoothManagerService: Message: 20
08-12 18:23:49.850  1033  1099 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f4123f9:true
,08-12 18:23:49.868  6725  6725 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 18:23:49.868  6725  6725 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 18:23:49.868  6725  6725 I Adreno-EGL: Build Date: 12/12/14 금
08-12 18:23:49.868  6725  6725 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-12 18:23:49.868  6725  6725 I Adreno-EGL: Remote Branch: 
08-12 18:23:49.868  6725  6725 I Adreno-EGL: Local Patches: 
08-12 18:23:49.868  6725  6725 I Adreno-EGL: Reconstruct Branch: 
,08-12 18:23:49.958  6725  6770 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-12 18:23:49.963  6725  6725 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-12 18:23:49.983  6725  6725 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 18:23:49.989  6725  6725 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 18:23:49.996  6725  6725 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-12 18:23:49.999  6725  6725 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 18:23:49.999  6725  6725 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-12 18:23:50.012  6725  6725 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 18:23:50.018  6725  6725 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 18:23:50.018  6725  6725 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 18:23:50.057  6725  6789 D OpenGLRenderer: Render dirty regions requested: true
08-12 18:23:50.057  6725  6789 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 18:23:50.061  6725  6789 D OpenGLRenderer: Enabling debug mode 0
08-12 18:23:50.068  6725  6725 D Atlas   : Validating map...
,08-12 18:23:50.073  1033  1048 D SplitWindow: check instance of lgWin Window{97d46ab u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 18:23:50.109  6725  6784 D LgDataFeature: LgDataFeature() Constructor: none
,08-12 18:23:50.110  6725  6784 D LgDataFeature: LgDataFeature() Constructor Done, null
08-12 18:23:50.210  1033  1100 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +590ms (total +673ms)
08-12 18:23:50.211  1033  1100 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1c3acd54 u0 com.test.thalitest/.MainActivity t6} time:189594
08-12 18:23:50.215  6725  6725 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1f3cd940 time:189598
,08-12 18:23:50.324  6725  6725 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 18:23:50.502  6725  6801 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435169792
,08-12 18:23:50.520  6725  6801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 18:23:50.520  6725  6801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 18:23:50.520  6725  6801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 18:23:50.520  6725  6801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 18:23:50.520  6725  6801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 18:23:50.520  6725  6801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14ce5a04 added. We now have 1 listener(s)
,08-12 18:23:50.527  1033  1774 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 18:23:50.530  6725  6801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-12 18:23:50.532  6725  6801 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-12 18:23:50.534  6725  6801 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 18:23:50.534  6725  6801 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 18:23:50.543  6725  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 18:23:50.543  6725  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 18:23:50.543  6725  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 18:23:50.543  6725  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-12 18:23:50.543  6725  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 18:23:50.543  6725  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 18:23:50.543  6725  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 18:23:50.543  6725  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 18:23:50.543  6725  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 18:23:50.543  6725  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 18:23:50.543  6725  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 18:23:50.543  6725  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 18:23:50.543  6725  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 18:23:50.543  6725  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 18:23:50.543  6725  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1af8bcb3 added. We now have 1 listener(s)
08-12 18:23:50.544  6725  6801 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 18:23:50.551  1033  1542 D WifiService: New client listening to asynchronous messages
,08-12 18:23:50.561  6725  6801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 18:23:50.562  6725  6801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-12 18:23:50.564  6725  6801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 18:23:50.564  6725  6801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 18:23:50.564  6725  6801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 18:23:50.570  6725  6801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 18:23:50.570  1033  1551 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 18:23:50.571  6725  6801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-12 18:23:50.582  6725  6801 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 18:23:50.582  6725  6801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 18:23:50.582  6725  6801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 18:23:50.582  6725  6801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 18:23:50.582  6725  6801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 18:23:50.582  6725  6801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 18:23:50.582  6725  6801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 18:23:50.582  6725  6801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 18:23:50.582  6725  6801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 18:23:50.582  6725  6801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 18:23:50.583  6725  6801 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 18:23:50.585  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 18:23:50.587  6725  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 18:23:50.589  6725  6801 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 18:23:50.626  6725  6784 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-12 18:23:50.626  6725  6784 I chromium: 
,08-12 18:23:50.688  6725  6725 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 18:23:50.773  6725  6725 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-12 18:23:50.773  6725  6725 I chromium: 
,08-12 18:23:51.469  6725  6804 W jxcore-log: Initializing JXcore engine
08-12 18:23:51.469  6725  6804 W jxcore-log: JXcore engine is ready
,08-12 18:23:51.502  6804  6804 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10382]" dev="sockfs" ino=10382 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 18:23:51.502  6804  6804 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-12 18:23:51.502  6804  6804 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10556]" dev="sockfs" ino=10556 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 18:23:51.502  6804  6804 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-12 18:23:51.502  6804  6804 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32853]" dev="sockfs" ino=32853 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-12 18:23:51.510   344   363 E GBMv2   : Set value is all cleared set the max
08-12 18:23:51.510   344   363 I GBMv2   : DFP Enabled. Ignore VFP set
08-12 18:23:51.519  6725  6804 W jxcore-log: Starting JXcore engine
08-12 18:23:51.598  6725  6804 W jxcore-log: Platform android
08-12 18:23:51.598  6725  6804 W jxcore-log: 
08-12 18:23:51.598  6725  6804 W jxcore-log: Process ARCH arm
08-12 18:23:51.598  6725  6804 W jxcore-log: 
,08-12 18:23:51.767  6725  6804 I jxcore-log: JXcore Cordova bridge is ready!
08-12 18:23:51.767  6725  6804 I jxcore-log: 
08-12 18:23:51.768  6725  6804 W jxcore-log: JXcore engine is started
,08-12 18:23:51.776  6725  6801 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 18:23:51.781  6725  6725 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 18:24:00.050  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 18:24:00.050  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 18:24:00.050  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 18:24:00.050  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-12 18:24:00.059  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 18:24:00.059  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-12 18:24:00.063  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-12 18:24:00.064  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 18:24:01.599  6725  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 18:24:01.599  6725  6804 I jxcore-log: 
,08-12 18:24:01.601  6725  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 18:24:01.601  6725  6804 I jxcore-log: 
08-12 18:24:01.605  6725  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 18:24:01.605  6725  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 18:24:01.605  6725  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 18:24:01.605  6725  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 18:24:01.605  6725  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 18:24:01.605  6725  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 18:24:01.605  6725  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 18:24:01.605  6725  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 18:24:01.608  6725  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 18:24:01.610  6725  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 18:24:01.610  6725  6804 I jxcore-log: 
08-12 18:24:01.612  6725  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 18:24:01.612  6725  6804 I jxcore-log: 
,08-12 18:24:01.938  6725  6804 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-12 18:24:01.938  6725  6804 I jxcore-log: Failed to execute UT.
08-12 18:24:01.938  6725  6804 I jxcore-log: 
08-12 18:24:01.938  6725  6804 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 18:24:01.938  6725  6804 I jxcore-log: 
,08-12 18:24:01.945  6725  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 18:24:01.945  6725  6804 I jxcore-log: 
08-12 18:24:01.951  6725  6725 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-12 18:24:02.302  6805  6805 D AndroidRuntime: 
08-12 18:24:02.302  6805  6805 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 18:24:02.309  6805  6805 D AndroidRuntime: CheckJNI is OFF
08-12 18:24:02.514  6805  6805 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 18:24:02.531  1033  1090 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-12 18:24:02.532  1033  1090 I ActivityManager: Killing 6725:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-12 18:24:02.609  1033  1551 I WindowState: WIN DEATH: Window{97d46ab u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 18:24:02.612  1033  1542 D WifiService: Client connection lost with reason: 4
08-12 18:24:02.624  1033  1551 D InputDispatcher: Window went away: Window{97d46ab u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 18:24:02.750  1033  1090 I ActivityManager:   Force finishing activity ActivityRecord{1c3acd54 u0 com.test.thalitest/.MainActivity t6}
,08-12 18:24:02.799   344   361 E GBMv2   : DFP En is all cleared set to be enabled
,08-12 18:24:02.807  1033  1734 W ActivityManager: Spurious death for ProcessRecord{148c12d9 6725:com.test.thalitest/u0a118}, curProc for 6725: null
,08-12 18:24:02.808  1033  1115 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-12 18:24:02.814  1033  1115 I ActivityManager:   Force finishing activity ActivityRecord{1c3acd54 u0 com.test.thalitest/.MainActivity t6 f}
08-12 18:24:02.815  1033  1115 W ActivityManager: Duplicate finish request for ActivityRecord{1c3acd54 u0 com.test.thalitest/.MainActivity t6 f}
,08-12 18:24:02.856  1940  2749 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-12 18:24:02.857  2032  2032 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-12 18:24:02.858  2032  2032 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-12 18:24:02.861  1940  2749 D SplitWindowPolicy: topRunningActivity=ActivityInfo{271c4c1d co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 18:24:02.862  1940  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
,08-12 18:24:02.863  1940  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1ab6e92 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 18:24:02.863  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-12 18:24:02.865  2032  2143 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-12 18:24:02.872  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 18:24:02.881  1033  1480 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 18:24:02.887  1033  1089 W InputMethodInfo: Duplicated subtype definition found: , voice
08-12 18:24:02.915  2508  2669 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 18:24:02.920  3839  3839 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-12 18:24:02.920  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-12 18:24:02.921  1994  1994 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 18:24:02.921  4463  4463 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 18:24:02.921  4463  4463 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 18:24:02.922  4463  4463 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 18:24:02.922  4463  4463 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-12 18:24:02.922  4463  4463 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 18:24:02.922  4463  4463 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 18:24:02.922  4463  4463 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 18:24:02.922  4463  4463 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 18:24:02.922  4463  4463 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 18:24:02.922  4463  4463 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 18:24:02.922  4463  4463 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 18:24:02.922  4463  4463 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-12 18:24:02.923  3781  3781 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-12 18:24:02.934  6415  6415 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-12 18:24:02.934  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-12 18:24:02.935  1904  1904 D ActionManagerService: notifyUserLog: 1000003
,08-12 18:24:02.936  3781  4451 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-12 18:24:02.969  4574  4574 I art     : Explicit concurrent mark sweep GC freed 470(32KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 816us total 145.939ms
,08-12 18:24:02.982  2032  2032 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-12 18:24:02.987  1816  1816 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-12 18:24:02.997  2032  2032 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-12 18:24:02.998  2032  2032 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-12 18:24:02.999  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-12 18:24:03.023  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-12 18:24:03.023  1869  1869 D SplitUIService: removed split : 
,08-12 18:24:03.025  1033  1033 I art     : Explicit concurrent mark sweep GC freed 37606(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 6.330ms total 188.900ms
08-12 18:24:03.025  1033  1049 I art     : WaitForGcToComplete blocked for 45.378ms for cause Explicit
08-12 18:24:03.029  1904  1904 D ActionManagerService: notifyUserLog: 1000004
08-12 18:24:03.029  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-12 18:24:03.030  3781  4451 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-12 18:24:03.031  3781  4447 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 18:24:03.037  1601  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 18:24:03.037  1601  1649 D KeyguardModel: createShortcutInfo...
,08-12 18:24:03.043  1601  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 18:24:03.043  1601  1649 D KeyguardModel: createShortcutInfo...
08-12 18:24:03.049  2234  2234 I ConfigService: onCreate
,08-12 18:24:03.050  2234  2234 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-12 18:24:03.052  1601  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 18:24:03.052  1601  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 18:24:03.052  1601  1649 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-12 18:24:03.053  1601  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 18:24:03.056  2234  2234 I ConfigService: onBind returning update interface
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262123
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , display: false
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , animation: false }
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262287
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , display: false
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , animation: false }
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , create_time: 1471007226523
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , display: false
08-12 18:24:03.058  2032  2032 I GBoardWebViewUtils: , animation: false }
08-12 18:24:03.058  1601  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:24:03.058  1601  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 18:24:03.062  2032  6843 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-12 18:24:03.064  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 18:24:03.064  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-12 18:24:03.085  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 18:24:03.085  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-12 18:24:03.086  1816  1816 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-12 18:24:03.086  2234  2234 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-12 18:24:03.087  2234  2234 I ConfigService: onBind returning config service
08-12 18:24:03.087  1601  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 18:24:03.087  1601  1649 D KeyguardModel: createShortcutInfo...
08-12 18:24:03.095  1816  1816 I ConfigFetchService: service connected
,08-12 18:24:03.103  1601  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 18:24:03.103  1601  1649 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 18:24:03.106  1601  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:24:03.106  1601  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 18:24:03.109  1601  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 18:24:03.109  1601  1649 D KeyguardModel: createShortcutInfo...
08-12 18:24:03.112  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-12 18:24:03.112  1869  1869 I SplitUIService: split app #11
08-12 18:24:03.115  1601  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 18:24:03.115  1601  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-12 18:24:03.115  1601  1649 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-12 18:24:03.115  1601  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-12 18:24:03.116  1601  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:24:03.116  1601  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 18:24:03.118  1601  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 18:24:03.118  1601  1649 D KeyguardModel: createShortcutInfo...
08-12 18:24:03.128  2234  2234 I ConfigService: onDestroy
,08-12 18:24:03.135  1816  6845 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-12 18:24:03.139  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-12 18:24:03.139  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-12 18:24:03.172  1601  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 18:24:03.172  1601  1649 D KeyguardModel: createShortcutInfo...
,08-12 18:24:03.180  1601  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 18:24:03.180  1601  1649 D KeyguardModel: createShortcutInfo...
,08-12 18:24:03.192  1601  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:24:03.192  1601  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 18:24:03.211  1033  1937 V SIM_STK : Menu title from STK is T-Mobile
08-12 18:24:03.211  1033  1937 V SIM_STK : Menu title from STK is T-Mobile
08-12 18:24:03.212  1033  1033 D administrator: Handling package changes for user 0
,08-12 18:24:03.214  1601  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 18:24:03.214  1601  1649 D KeyguardModel: createShortcutInfo...
08-12 18:24:03.215  5906  6851 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-12 18:24:03.217  2032  2032 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-12 18:24:03.217  1033  1049 I art     : Explicit concurrent mark sweep GC freed 8410(659KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.929ms total 191.515ms
08-12 18:24:03.221  1033  1115 I art     : WaitForGcToComplete blocked for 365.609ms for cause Explicit
08-12 18:24:03.223  1601  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:24:03.223  1601  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 18:24:03.231  1033  1551 V SIM_STK : Menu title from STK is T-Mobile
,08-12 18:24:03.238  1816  6852 I PeopleContactsSync: CP2 sync disabled
08-12 18:24:03.239  1601  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 18:24:03.239  1601  1649 D KeyguardModel: createShortcutInfo...
08-12 18:24:03.239  5979  5979 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-12 18:24:03.248  1601  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:24:03.248  1601  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 18:24:03.249  1601  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 18:24:03.249  1601  1649 D KeyguardModel: createShortcutInfo...
,08-12 18:24:03.261  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-12 18:24:03.261  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-12 18:24:03.286  1033  2031 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-12 18:24:03.286  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-12 18:24:03.286  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-12 18:24:03.286  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-12 18:24:03.286  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-12 18:24:03.286  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-12 18:24:03.286  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 18:24:03.287  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-12 18:24:03.287  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-12 18:24:03.287  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-12 18:24:03.287  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 18:24:03.287  3839  3839 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-12 18:24:03.288  1816  4706 I Icing   : doRemovePackageData com.test.thalitest
08-12 18:24:03.290  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-12 18:24:03.292  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 18:24:03.293  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-12 18:24:03.294  6522  6522 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-12 18:24:03.294  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-12 18:24:03.295  2357  6853 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-12 18:24:03.295  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-12 18:24:03.296  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-12 18:24:03.304  1816  6850 W GmsApplication: Using Auth Proxy for data requests.
,08-12 18:24:03.315  1994  1994 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 18:24:03.315  1994  1994 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-12 18:24:03.317  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-12 18:24:03.317  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 18:24:03.320  2032  2166 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-12 18:24:03.321  2032  2166 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-12 18:24:03.334  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-12 18:24:03.335  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 18:24:03.335  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 18:24:03.336  1033  1100 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3ade94ec u0 com.lge.launcher2/.Launcher t5} time:202719
08-12 18:24:03.338  1994  1994 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-12 18:24:03.343  2032  2032 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-12 18:24:03.344  1816  6850 W GmsApplication: Using Auth Proxy for data requests.
08-12 18:24:03.347  6415  6415 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-12 18:24:03.350  2597  2597 D [Concierge]Service: onStartCommand(). Type : 8
08-12 18:24:03.350  2597  2597 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-12 18:24:03.351  2597  2597 D [Concierge]Service: Update widget ID : 11
08-12 18:24:03.352  2032  2032 D [Concierge]WidgetView: change position of spinner
08-12 18:24:03.357  1033  1780 V SIM_STK : Menu title from STK is T-Mobile
08-12 18:24:03.372  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 18:24:03.372  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 18:24:03.372  1033  1033 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 18:24:03.375  1033  1993 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6859 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-12 18:24:03.379  2032  2032 I [Concierge]WidgetView: initWebView(). Time : 1471019043379
08-12 18:24:03.379  2597  2597 D [Concierge]Service: onStartCommand(). Type : 0
08-12 18:24:03.379  1033  1576 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-12 18:24:03.399  2032  2032 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 997771512
08-12 18:24:03.399  2032  2032 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-12 18:24:03.400  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-12 18:24:03.402  2032  2032 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@27125278
08-12 18:24:03.402  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-12 18:24:03.403  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 18:24:03.403  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 18:24:03.408  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-12 18:24:03.409  2032  2032 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-12 18:24:03.409  2032  2032 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 18:24:03.412  2032  2032 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471018869000, New one : 1471019043379
08-12 18:24:03.412  2032  2032 D [Concierge]WidgetView: Unregister all receivers
08-12 18:24:03.412  2032  2032 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 18:24:03.414  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 18:24:03.415  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-12 18:24:03.416  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,08-12 18:24:03.417  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-12 18:24:03.418  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-12 18:24:03.419  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-12 18:24:03.420  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 18:24:03.420  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 18:24:03.450  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-12 18:24:03.460  2032  2032 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-12 18:24:03.460  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-12 18:24:03.461  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 18:24:03.481  2032  2032 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@14646b3d time:202864
,08-12 18:24:03.503  1033  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 18:24:03.509  1033  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-12 18:24:03.514  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-12 18:24:03.518  6859  6859 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-12 18:24:03.518  6859  6859 W LG Account v2.2: No ProfileInfo entries
08-12 18:24:03.518  6859  6859 I LG Account v2.2: isEnabled: false
08-12 18:24:03.519  6859  6859 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-12 18:24:03.519  6859  6859 I Feature : [Lifetracker]Country: EU
08-12 18:24:03.519  6859  6859 I Feature : [Lifetracker]Operator: OPEN
08-12 18:24:03.519  6859  6859 I Feature : [Lifetracker]Ranking support: false
08-12 18:24:03.519  6859  6859 I Feature : [Lifetracker]Comfort support: false
08-12 18:24:03.519  6859  6859 I Feature : [Lifetracker]Accessory: true
08-12 18:24:03.519  6859  6859 I Feature : [Lifetracker]Health device: true
08-12 18:24:03.519  6859  6859 I Feature : [Lifetracker]Extra Pedometer: false
08-12 18:24:03.519  6859  6859 I Feature : [Lifetracker]Blood glucose device: false
08-12 18:24:03.519  6859  6859 I Feature : [Lifetracker]Device Number: 3
08-12 18:24:03.520  6859  6859 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-12 18:24:03.528  1033  1115 I art     : Explicit concurrent mark sweep GC freed 6154(307KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.212ms total 305.238ms
08-12 18:24:03.570  1033  1993 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6879 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-12 18:24:03.570  1033  1993 I ActivityManager: Killing 6177:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-12 18:24:03.605  6805  6805 D AndroidRuntime: Shutting down VM
,08-12 18:24:03.614  2032  2032 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-12 18:24:03.648  1033  2050 W libprocessgroup: failed to open /acct/uid_10014/pid_6177/cgroup.procs: No such file or directory
,08-12 18:24:03.650  2032  2888 I GBoardtInterface: onReloaded()
08-12 18:24:03.652  2032  2032 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-12 18:24:03.660  3781  4447 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-12 18:24:03.666  3781  3796 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 18:24:03.677  1904  1904 D ActionManagerService: notifyUserLog: 1000001
,08-12 18:24:03.679  3781  4451 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 18:24:03.679  3781  4451 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 18:24:03.682  1904  1904 D ActionManagerService: notifyUserLog: 1000001
08-12 18:24:03.683  3781  4451 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 18:24:03.683  3781  4451 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 18:24:03.683  3781  4451 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-12 18:24:03.684  3781  4451 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-12 18:24:03.684  3781  4447 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 18:24:03.686  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
,08-12 18:24:03.686  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-12 18:24:03.688  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-12 18:24:03.688  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 18:24:03.690  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-12 18:24:03.690  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-12 18:24:03.694  6879  6879 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 18:24:03.695  6879  6879 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-12 18:24:03.696  6879  6879 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 18:24:03.697  6879  6879 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-12 18:24:03.698  6879  6879 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 18:24:03.699  6879  6879 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-12 18:24:03.804  6879  6879 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-12 18:24:03.818  6879  6879 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
,08-12 18:24:03.818  6879  6879 D HideNavigationAppsReceiver: replacing : false
,08-12 18:24:03.823  6879  6879 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-12 18:24:03.830  6879  6879 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-12 18:24:03.830  6879  6879 D ButtonCombinationReceiver: replacing : false
,08-12 18:24:03.840  1033  1048 I ActivityManager: Killing 6476:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-12 18:24:03.931  1033  1780 W libprocessgroup: failed to open /acct/uid_10008/pid_6476/cgroup.procs: No such file or directory
,08-12 18:24:03.941  4574  6898 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-12 18:24:03.984  1033  2050 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6899 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a

```
