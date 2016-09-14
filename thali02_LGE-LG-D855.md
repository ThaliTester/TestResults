#### Test 83627337e0b549f_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-14 09:29:00.046  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-14 09:29:00.046  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
09-14 09:29:00.046  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-14 09:29:00.047  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,09-14 09:29:00.060  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
09-14 09:29:00.060  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
09-14 09:29:00.065  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
09-14 09:29:00.066  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
09-14 09:29:00.374  6843  6843 D AndroidRuntime: 
09-14 09:29:00.374  6843  6843 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-14 09:29:00.378  6843  6843 D AndroidRuntime: CheckJNI is OFF
09-14 09:29:00.584  6843  6843 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-14 09:29:00.595  1034  1935 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-14 09:29:00.611  1924  1941 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-14 09:29:00.617  1034  1935 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-14 09:29:00.618  1034  1935 D ActivityManager: setTaskToReturnTo : TaskRecord{3fa15c42 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-14 09:29:00.618  1034  1935 D ActivityManager: setTaskToReturnTo : TaskRecord{3fa15c42 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-14 09:29:00.620  1034  1935 D WindowStateEx: AppWindowTokenEx init.. 
09-14 09:29:00.621   327   386 E GBMv2   : DFP En is all cleared set to be enabled
09-14 09:29:00.664  1034  1935 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6858 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-14 09:29:00.667  6843  6843 D AndroidRuntime: Shutting down VM
09-14 09:29:00.707  1924  2254 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-14 09:29:00.708  1924  2254 D SplitWindowPolicy: topRunningActivity=ActivityInfo{17dfd330 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-14 09:29:00.708  1924  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-14 09:29:00.709  1924  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{23c5bba9 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-14 09:29:00.789  6858  6858 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-14 09:29:00.857  6858  6858 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-14 09:29:00.865  6858  6858 I LibraryLoader: Loading: webviewchromium
09-14 09:29:00.868  6858  6858 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6873-6876)
,09-14 09:29:00.869  6858  6858 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-14 09:29:00.907  6858  6858 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c35705e}
09-14 09:29:00.908  6858  6858 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-14 09:29:00.909  6858  6858 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-14 09:29:00.920  6858  6858 I BrowserStartupController: Initializing chromium process, renderers=0
09-14 09:29:00.921  6858  6858 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-14 09:29:00.963   308   308 V AudioPolicyService: registerClient() client 0xb558a2c0, uid 10118
09-14 09:29:00.963  6858  6858 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-14 09:29:00.972  6858  6858 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-14 09:29:00.972  6858  6858 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-14 09:29:00.975  1034  1116 D BluetoothManagerService: Message: 20
09-14 09:29:00.976  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b2446bc:true
,09-14 09:29:00.989  6858  6858 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-14 09:29:00.989  6858  6858 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-14 09:29:00.989  6858  6858 I Adreno-EGL: Build Date: 12/12/14 금
09-14 09:29:00.989  6858  6858 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-14 09:29:00.989  6858  6858 I Adreno-EGL: Remote Branch: 
09-14 09:29:00.989  6858  6858 I Adreno-EGL: Local Patches: 
09-14 09:29:00.989  6858  6858 I Adreno-EGL: Reconstruct Branch: 
,09-14 09:29:01.088  6858  6905 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
09-14 09:29:01.090  6858  6858 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,09-14 09:29:01.106  6858  6858 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-14 09:29:01.112  6858  6858 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-14 09:29:01.115  6858  6858 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-14 09:29:01.118  6858  6858 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-14 09:29:01.118  6858  6858 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-14 09:29:01.133  6858  6858 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-14 09:29:01.139  6858  6858 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-14 09:29:01.139  6858  6858 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-14 09:29:01.173  6858  6920 D OpenGLRenderer: Render dirty regions requested: true
,09-14 09:29:01.173  6858  6920 I OpenGLRenderer: Initialized EGL, version 1.4
,09-14 09:29:01.183  6858  6920 D OpenGLRenderer: Enabling debug mode 0
09-14 09:29:01.191  6858  6858 D Atlas   : Validating map...
,09-14 09:29:01.195  1034  1587 D SplitWindow: check instance of lgWin Window{60e5c16 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-14 09:29:01.206  1034  1102 W ActivityManager: Activity pause timeout for ActivityRecord{1edc9453 u0 com.test.thalitest/.MainActivity t6}
,09-14 09:29:01.278  6858  6918 D LgDataFeature: LgDataFeature() Constructor: none
09-14 09:29:01.278  6858  6918 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-14 09:29:01.314  1034  1117 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +608ms (total +692ms)
09-14 09:29:01.314  6858  6858 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@226cac5 time:167322
09-14 09:29:01.316  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1edc9453 u0 com.test.thalitest/.MainActivity t6} time:167324
09-14 09:29:01.436  6858  6858 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-14 09:29:01.436  6858  6858 I chromium: 
,09-14 09:29:01.447  6858  6858 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-14 09:29:01.516  6858  6918 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-14 09:29:01.516  6858  6918 I chromium: 
,09-14 09:29:01.660  6858  6934 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435171328
,09-14 09:29:01.678  6858  6934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-14 09:29:01.678  6858  6934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-14 09:29:01.678  6858  6934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-14 09:29:01.678  6858  6934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-14 09:29:01.678  6858  6934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-14 09:29:01.678  6858  6934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@265d8479 added. We now have 1 listener(s)
,09-14 09:29:01.687  1034  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:01.690  6858  6934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-14 09:29:01.693  6858  6934 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-14 09:29:01.695  6858  6934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 09:29:01.695  6858  6934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-14 09:29:01.706  6858  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-14 09:29:01.706  6858  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-14 09:29:01.706  6858  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-14 09:29:01.706  6858  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-14 09:29:01.706  6858  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-14 09:29:01.706  6858  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-14 09:29:01.706  6858  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-14 09:29:01.706  6858  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-14 09:29:01.706  6858  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-14 09:29:01.706  6858  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-14 09:29:01.706  6858  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-14 09:29:01.706  6858  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-14 09:29:01.706  6858  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-14 09:29:01.706  6858  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-14 09:29:01.706  6858  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2380ad6c added. We now have 1 listener(s)
09-14 09:29:01.706  6858  6934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 09:29:01.712  1034  1528 D WifiService: New client listening to asynchronous messages
09-14 09:29:01.717  6858  6934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 09:29:01.717  6858  6934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-14 09:29:01.720  6858  6934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-14 09:29:01.720  6858  6934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-14 09:29:01.720  6858  6934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-14 09:29:01.726  6858  6934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:01.726  1034  1765 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:01.727  6858  6934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-14 09:29:01.737  6858  6934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-14 09:29:01.737  6858  6934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:29:01.737  6858  6934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:01.737  6858  6934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:01.737  6858  6934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:01.737  6858  6934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:01.737  6858  6934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:01.737  6858  6934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:01.737  6858  6934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:01.738  6858  6934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-14 09:29:01.738  6858  6934 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 09:29:01.741  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:01.743  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:01.746  6858  6934 I io.jxcore.node.LifeCycleMonitor: start: OK
09-14 09:29:01.790  6858  6858 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-14 09:29:01.833   327   388 E GBMv2   : DFP En is all cleared set to be enabled
09-14 09:29:01.834   327   388 E GBMv2   : Set value is all cleared set the max
09-14 09:29:01.834   327   388 I GBMv2   : DFP Enabled. Ignore VFP set
,09-14 09:29:02.815  6858  6937 W jxcore-log: Initializing JXcore engine
09-14 09:29:02.815  6858  6937 W jxcore-log: JXcore engine is ready
,09-14 09:29:02.892  6937  6937 W Thread-777: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9904]" dev="sockfs" ino=9904 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-14 09:29:02.892  6937  6937 W Thread-777: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,09-14 09:29:02.892  6937  6937 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10504]" dev="sockfs" ino=10504 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-14 09:29:02.892  6937  6937 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,09-14 09:29:02.892  6937  6937 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31553]" dev="sockfs" ino=31553 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket,
,09-14 09:29:02.929  6858  6937 W jxcore-log: Starting JXcore engine
,09-14 09:29:03.051  6858  6937 W jxcore-log: Platform android
09-14 09:29:03.051  6858  6937 W jxcore-log: 
09-14 09:29:03.051  6858  6937 W jxcore-log: Process ARCH arm
09-14 09:29:03.051  6858  6937 W jxcore-log: 
,09-14 09:29:03.269  6858  6937 I jxcore-log: JXcore Cordova bridge is ready!
09-14 09:29:03.269  6858  6937 I jxcore-log: 
09-14 09:29:03.269  6858  6937 W jxcore-log: JXcore engine is started
,09-14 09:29:03.278  6858  6934 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-14 09:29:03.282  6858  6858 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-14 09:29:12.806  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-14 09:29:12.806  6858  6937 I jxcore-log: 
,09-14 09:29:12.809  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-14 09:29:12.809  6858  6937 I jxcore-log: 
,09-14 09:29:12.814  6858  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:29:12.814  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:12.814  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:12.814  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:12.814  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:12.814  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:12.814  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:12.814  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:12.817  6858  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:12.820  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-14 09:29:12.820  6858  6937 I jxcore-log: 
09-14 09:29:12.822  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-14 09:29:12.822  6858  6937 I jxcore-log: 
,09-14 09:29:13.329  6858  6937 I jxcore-log: Unit Test app is loaded
09-14 09:29:13.329  6858  6937 I jxcore-log: 
,09-14 09:29:13.339  6858  6858 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-14 09:29:13.347  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:13.347  6858  6937 I jxcore-log: 
09-14 09:29:13.364  6858  6937 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 09:29:13.364  6858  6937 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c1e655 added. We now have 2 listener(s)
,09-14 09:29:13.365  1034  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:13.367  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-14 09:29:13.367  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 09:29:13.367  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 09:29:13.367  6858  6937 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 09:29:13.367  6858  6937 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7b286a added. We now have 2 listener(s)
09-14 09:29:13.367  6858  6937 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 09:29:13.367  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 09:29:13.369  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:13.371  6858  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:29:13.371  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:13.371  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:13.371  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:13.371  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:13.371  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:13.371  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:13.371  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:13.372  6858  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:13.372  6858  6937 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 09:29:13.373  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:13.374  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:13.375  6858  6937 D ExecuteNativeTests: Running unit tests
09-14 09:29:13.375  6858  6937 D BluetoothAdapter: enable(): BT is already enabled..!
09-14 09:29:13.376  1034  1560 D WifiServiceImplEx: setWifiEnabled: true pid=6858, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-14 09:29:13.377  1034  1560 D WifiService: setWifiEnabled: true pid=6858, uid=10118
09-14 09:29:13.377  1034  1560 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-14 09:29:13.380  6858  6937 I System.out: Running UT
09-14 09:29:23.537  6858  6937 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 09:29:23.537  6858  6937 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 added. We now have 3 listener(s)
,09-14 09:29:23.540  1034  1056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:23.543  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-14 09:29:23.543  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 09:29:23.543  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 09:29:23.543  6858  6937 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 09:29:23.543  6858  6937 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 added. We now have 3 listener(s)
09-14 09:29:23.543  6858  6937 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 09:29:23.544  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 09:29:23.547  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:23.551  6858  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:29:23.551  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:23.551  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:23.551  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:23.551  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:23.551  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:23.551  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:23.551  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 09:29:23.555  6858  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:23.555  6858  6937 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 09:29:23.558  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:23.560  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:23.566  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-14 09:29:23.571  6858  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 09:29:23.571  6858  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 09:29:23.571  6858  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 09:29:23.574  6858  6937 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-14 09:29:23.575  6858  6937 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-14 09:29:23.575  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 09:29:23.575  6858  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 09:29:23.575  6858  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 09:29:23.575  6858  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 09:29:23.576  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.576  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.576  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 09:29:23.576  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 09:29:23.577  6858  6937 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 removed from the list
09-14 09:29:23.577  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.577  6858  6937 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 removed from the list
09-14 09:29:23.577  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.577  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.580  6858  6937 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-14 09:29:23.580  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 09:29:23.584  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.584  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.584  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.584  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.584  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.585  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.585  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.585  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-14 09:29:23.596  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-14 09:29:23.597  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-14 09:29:23.597  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710,:1710]
09-14 09:29:23.597  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-14 09:29:23.597  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-14 09:29:23.597  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-14 09:29:23.597  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-14 09:29:23.597  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-14 09:29:23.597  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-14 09:29:23.597  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-14 09:29:23.597  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-14 09:29:23.597  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-14 09:29:23.597  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-14 09:29:23.597  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-14 09:29:23.597  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-14 09:29:23.597  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.597  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.597  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.597  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.597  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.597  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.597  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.597  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.597  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.598  6858  6937 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-14 09:29:23.609  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:23.613  6858  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:29:23.613  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:23.613  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:23.613  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:23.613  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:23.613  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:23.613  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:23.613  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:23.615  6858  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:23.615  6858  6937 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 09:29:23.618  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:23.619  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:23.621  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 09:29:23.621  6858  6937 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 09:29:23.621  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 09:29:23.621  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:23.621  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 09:29:23.626  6858  6937 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 09:29:23.628  1034  1883 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:23.635  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 09:29:23.642  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 09:29:23.646  6858  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-14 09:29:23.648  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 09:29:23.648  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 09:29:23.650  6858  6937 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-14 09:29:23.651  6858  6937 I io.jxcore.node.ConnectionHelper: start: OK
09-14 09:29:23.652  6858  6937 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-14 09:29:23.652  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 09:29:23.652  6858  6937 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 09:29:23.655  6858  6937 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-14 09:29:23.655  6858  6937 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-14 09:29:23.658  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 09:29:23.658  6858  6937 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 09:29:23.658  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 09:29:23.658  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:23.658  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 09:29:23.664  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 09:29:23.665  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 09:29:23.666  6858  6937 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-14 09:29:23.667  6858  6937 I io.jxcore.node.ConnectionHelper: start: OK
09-14 09:29:23.668  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.668  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.668  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 09:29:23.668  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.668  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.668  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.668  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.668  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:29:23.672  6858  6937 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-14 09:29:23.674  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:23.677  6858  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:29:23.677  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:23.677  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:23.677  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:23.677  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:23.677  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:23.677  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:23.677  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:23.679  6858  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:23.679  6858  6937 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 09:29:23.683  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 09:29:23.684  6858  6937 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 09:29:23.684  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 09:29:23.684  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:23.684  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 09:29:23.692  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:23.694  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:23.699  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 09:29:23.700  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 09:29:23.703  6858  6937 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-14 09:29:23.703  6858  6937 I io.jxcore.node.ConnectionHelper: start: OK
09-14 09:29:23.703  6858  6937 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-14 09:29:23.703  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 09:29:23.703  6858  6937 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 09:29:23.707  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.708  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.708  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 09:29:23.708  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.708  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.708  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.708  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.708  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.710  6858  6937 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-14 09:29:23.711  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.711  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.711  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.711  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.711  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.711  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.711  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.711  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.711  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.713  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-14 09:29:23.713  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.713  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.713  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.713  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.713  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.713  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.713  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.713  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.713  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.714  6858  6937 I io.jxcore.node.ConnectionHelper: o,nConnectionManagerStateChanged: null
09-14 09:29:23.714  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.714  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.714  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.715  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.715  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.715  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.715  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.715  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.715  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.716  6858  6937 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-14 09:29:23.716  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.716  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 09:29:23.716  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.716  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.716  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.716  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.716  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.716  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.716  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:29:23.717  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-14 09:29:23.717  6858  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 09:29:23.717  6858  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 09:29:23.717  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 09:29:23.717  6858  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 09:29:23.717  6858  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 09:29:23.717  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-14 09:29:23.717  6858  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 09:29:23.718  6858  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 09:29:23.718  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.718  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.718  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.718  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.718  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.718  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.718  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.718  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.718  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:29:23.719  6858  6937 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 09:29:23.719  6858  6937 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-14 09:29:23.719  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-14 09:29:23.723  6858  6937 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 09:29:23.724  6858  6937 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-14 09:29:23.724  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-14 09:29:23.724  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-14 09:29:23.724  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-14 09:29:23.724  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-14 09:29:23.724  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-14 09:29:23.724  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-14 09:29:23.724  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-14 09:29:23.724  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-14 09:29:23.724  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-14 09:29:23.724  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-14 09:29:23.724  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-14 09:29:23.724  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-14 09:29:23.724  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-14 09:29:23.724  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-14 09:29:23.724  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-14 09:29:23.725  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-14 09:29:23.725  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-14 09:29:23.725  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-14 09:29:23.725  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-14 09:29:23.725  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-14 09:29:23.725  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-14 09:29:23.725  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-14 09:29:23.725  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-14 09:29:23.725  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-14 09:29:23.725  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-14 09:29:23.725  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510],
09-14 09:29:23.725  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-14 09:29:23.725  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-14 09:29:23.725  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-14 09:29:23.725  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-14 09:29:23.725  6858  6937 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-14 09:29:23.725  6858  6937 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 09:29:23.726  6858  6937 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,09-14 09:29:23.726  6858  6937 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 09:29:23.726  6858  6937 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 09:29:23.726  6858  6937 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-14 09:29:23.726  6858  6937 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 09:29:23.726  6858  6937 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 09:29:23.726  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-14 09:29:23.729  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-14 09:29:23.730  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-14 09:29:23.730  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-14 09:29:23.731  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-14 09:29:23.732  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-14 09:29:23.732  6858  6937 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-14 09:29:23.732  6858  6937 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 09:29:23.732  6858  6937 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-14 09:29:23.732  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.733  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.733  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.733  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-14 09:29:23.733  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.733  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.733  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.733  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.733  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.733  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.734  6858  6937 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-14 09:29:23.738  6858  6951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 875
09-14 09:29:23.740  6858  6950 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 875)
09-14 09:29:23.740  6858  6950 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 875)
09-14 09:29:23.741  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.741  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.741  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.741  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.741  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.741  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.741  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.741  6858  6937 W org.th,aliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.741  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.743  6858  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-14 09:29:23.747  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.747  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.747  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.747  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.747  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.748  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.748  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.748  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.748  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.749  6858  6937 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-14 09:29:23.749  6858  6937 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-14 09:29:23.750  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 09:29:23.750  6858  6937 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-14 09:29:23.750  6858  6937 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-14 09:29:23.750  6858  6937 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-14 09:29:23.750  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 09:29:23.750  6858  6937 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-14 09:29:23.750  6858  6937 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-14 09:29:23.750  6858  6937 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-14 09:29:23.750  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 09:29:23.750  6858  6937 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-14 09:29:23.751  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.751  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.751  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.751  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.751  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.751  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.752  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.752  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.752  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.752  6858  6937 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-14 09:29:23.756  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:23.759  6858  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:29:23.759  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:23.759  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:23.759  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:23.759  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:23.759  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:23.759  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:23.759  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:23.761  6858  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:23.761  6858  6937 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 09:29:23.761  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 09:29:23.761  6858  6937 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 09:29:23.761  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 09:29:23.762  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:23.762  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 09:29:23.764  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:23.767  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:29:23.770  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 09:29:23.770  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 09:29:23.772  6858  6937 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-14 09:29:23.772  6858  6937 I io.jxcore.node.ConnectionHelper: start: OK
09-14 09:29:23.772  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.772  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.772  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 09:29:23.772  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.772  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.772  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.773  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.773  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.775  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.775  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.775  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.775  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.775  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.775  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.775  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.776  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.776  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.778  6858  6937 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-14 09:29:23.778  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:23.779  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-14 09:29:23.780  6858  6937 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-14 09:29:23.780  6858  6937 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-14 09:29:23.781  6858  6858 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-14 09:29:23.782  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-14 09:29:23.782  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 09:29:23.784  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.784  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-14 09:29:23.784  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-14 09:29:23.784  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-14 09:29:23.784  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.784  6858  6937 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 09:29:23.784  6858  6953 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-14 09:29:23.784  6858  6953 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-14 09:29:23.785  6858  6858 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-14 09:29:23.785  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.785  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.785  6858  6858 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-14 09:29:23.785  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 09:29:23.785  6858  6937 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 09:29:23.785  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 09:29:23.786  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 09:29:23.788  6858  6937 D BluetoothLeScanner: could not find callback wrapper
09-14 09:29:23.788  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 09:29:23.788  6858  6937 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 09:29:23.789  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.789  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.790  6858  6937 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 09:29:23.790  6858  6858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 09:29:23.790  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.790  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.790  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.790  6858  6858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 09:29:23.790  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.790  6858  6858 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 09:29:23.792  6858  6937 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-14 09:29:23.792  6858  6937 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-14 09:29:23.792  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 09:29:23.792  6858  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 09:29:23.792  6858  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 09:29:23.792  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.792  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.792  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.792  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.792  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.793  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.793  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.793  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.793  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.795  1034  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:23.796  1034  1587 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:23.797  1034  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:23.798  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.798  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.798  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.798  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.798  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.798  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.798  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.798  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.798  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.799  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:23.800  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.800  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.800  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fea4528 not in the list
09-14 09:29:23.800  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:23.800  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1d241 not in the list
09-14 09:29:23.800  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:23.800  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:23.800  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:23.801  6858  6937 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-14 09:29:23.801  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 09:29:23.802  6858  6937 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-14 09:29:23.802  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 09:29:23.802  6858  6937 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-14 09:29:23.802  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 09:29:23.805  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-14 09:29:23.805  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-14 09:29:23.806  6858  6937 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-14 09:29:23.806  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-14 09:29:23.806  6858  6937 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-14 09:29:23.806  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-14 09:29:23.806  6858  6937 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-14 09:29:23.807  6858  6937 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-14 09:29:23.807  6858  6937 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-14 09:29:23.808  6858  6937 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-14 09:29:23.810  6858  6937 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-14 09:29:23.810  6858  6937 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-14 09:29:23.810  6858  6937 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-14 09:29:23.811  6858  6937 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-14 09:29:23.812  6858  6937 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 09:29:23.812  6858  6937 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2de3da1f added. We now have 3 listener(s)
09-14 09:29:23.813  1034  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:23.815  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-14 09:29:23.815  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 09:29:23.815  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 09:29:23.815  6858  6937 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 09:29:23.815  6858  6937 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@973816c added. We now have 3 listener(s)
09-14 09:29:23.815  6858  6937 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 09:29:23.816  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 09:29:23.817  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:23.822  6858  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:29:23.822  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:23.822  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:23.822  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:23.822  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:23.822  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:23.822  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:23.822  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:23.823  6858  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:23.824  6858  6937 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 09:29:23.825  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:23.827  6858  6937 D BluetoothAdapter: enable(): BT is already enabled..!
09-14 09:29:23.827  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:23.828  1034  1993 D WifiServiceImplEx: setWifiEnabled: true pid=6858, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-14 09:29:23.828  1034  1993 D WifiService: setWifiEnabled: true pid=6858, uid=10118
09-14 09:29:23.828  1034  1993 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-14 09:29:23.836  1034  1888 D WifiServiceImplEx: setWifiEnabled: false pid=6858, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-14 09:29:23.836  1034  1888 D WifiService: setWifiEnabled: false pid=6858, uid=10118
09-14 09:29:23.836  1034  1888 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 09:29:23.858  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-14 09:29:23.859  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-14 09:29:23.859  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-14 09:29:23.860  1034  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-14 09:29:23.861  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-14 09:29:23.861  1034  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-14 09:29:23.862  1034  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-14 09:29:23.863  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-14 09:29:23.863  1034  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-14 09:29:23.863  1034  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-14 09:29:23.863  1034  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-14 09:29:23.865  1034  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-14 09:29:23.865  1034  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-14 09:29:23.879  1034  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-14 09:29:23.879  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-14 09:29:23.879  1034  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:23.880  2668  2668 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-14 09:29:23.880  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:23.880  1034  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-14 09:29:23.880  1034  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-14 09:29:23.880  1034  1523 D WifiNative-wlan0: SET ps 1: returned true
,09-14 09:29:23.882  1034  2821 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:23.884   303   892 D CommandListener: Clearing all IP addresses on wlan0
,09-14 09:29:23.927  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-14 09:29:23.927  1034  1529 D ConnectivityService: ignoring duplicate network state non-change
09-14 09:29:23.927  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-14 09:29:23.929  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-14 09:29:23.929  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:23.929  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:23.930  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-14 09:29:23.946  1924  1924 V WfdStateTracker: handleWifiStateChangedEvent: 0
,09-14 09:29:23.947  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:23.947  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:23.954  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:23.959  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:23.960  1034  1034 D WifiHS20: hidePasspointNotification off =false
,09-14 09:29:23.963  1034  1522 D LGWifiP2pService: InactiveState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:23.963  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:23.963  1034  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3223b42c
09-14 09:29:23.964  1034  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:23.965  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:23.965  1034  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:23.966  1034  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:23.966  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:23.966  1034  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:23.967  1034  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-14 09:29:23.973  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:23.973  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:23.973  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-14 09:29:23.974  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
09-14 09:29:23.979  1034  1541 D WifiScanningService: DefaultState got{ when=-6ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:23.980  1034  1034 D RttService: SCAN_AVAILABLE : 1
09-14 09:29:23.980  1034  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-14 09:29:23.981  1034  1522 D LGWifiP2pService: P2pDisablingState
09-14 09:29:23.981  1034  1522 D LGWifiP2pService: P2pDisablingState{ when=-17ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:23.981  1034  1522 D LGWifiP2pService: p2p socket connection lost
09-14 09:29:23.982  1034  1522 D LGWifiP2pService: P2pDisabledState
09-14 09:29:23.983  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-14 09:29:23.983  1034  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-14 09:29:23.983  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-14 09:29:23.983  2668  2668 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-14 09:29:23.984  1924  1924 D WfdsService: WifiP2pState is changed : false
09-14 09:29:23.984  1924  2221 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-14 09:29:23.984  1924  2221 D WfdsService: Set the WFDS Monitor: false
09-14 09:29:23.984  1034  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-14 09:29:23.984  1034  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-14 09:29:23.985  1034  1523 D WifiNative-wlan0: SET ps 1: returned true
09-14 09:29:23.985  1924  2221 D WfdsMonitor: WFDS Monitor is stopped
09-14 09:29:23.985  1924  2221 D WfdsService: STATE : WfdsDisabledState - enter
09-14 09:29:23.985  1924  2737 D CtrlSupplicant: Received on exit socket, terminate
09-14 09:29:23.985  1924  2737 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-14 09:29:23.985  1924  2737 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-14 09:29:23.985  1924  2737 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-14 09:29:23.986  1924  2234 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-14 09:29:23.986  1924  2221 W WfdsService: DefaultState - msg [9445378] is not handled
09-14 09:29:23.987  1034  1522 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:23.987  1034  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:23.990  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:23.990  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:23.991  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:24.001   303   892 D CommandListener: Clearing all IP addresses on wlan0
09-14 09:29:24.002  1034  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
,09-14 09:29:24.002  1034  1529 D DSQN    : disableDataServiceNotify
09-14 09:29:24.002  1034  1529 D DSQN    : stop dsqn bin
09-14 09:29:24.006  1034  1523 D WifiNative-p2p0: doBoolean: TERMINATE
09-14 09:29:24.006  1034  1523 D WifiNative-p2p0: TERMINATE: returned true
09-14 09:29:24.006  1034  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-14 09:29:24.006  1034  1523 E WifiStateMachine: useWiFiOffloading() : false
09-14 09:29:24.006  1034  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-14 09:29:24.007  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-14 09:29:24.008  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:24.009  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:24.009  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-14 09:29:24.011  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-14 09:29:24.011  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:24.011  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-14 09:29:24.012  1034  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-14 09:29:24.012  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:24.012  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:24.012  1034  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:24.012  1034  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-14 09:29:24.012  1588  2102 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-14 09:29:24.013  1034  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-14 09:29:24.013  1034  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-14 09:29:24.013  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-14 09:29:24.013  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-14 09:29:24.014  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-14 09:29:24.014  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-14 09:29:24.014  1034  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:24.014  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-14 09:29:24.014  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon, / Roaming
09-14 09:29:24.014  1034  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:24.014  1034  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:24.014  1034  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-14 09:29:24.015  1034  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:24.015  1034  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:24.015  1034  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-14 09:29:24.016  1034  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:24.016  1034  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-14 09:29:24.017  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:24.017  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-14 09:29:24.017  1034  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-14 09:29:24.017  1034  1529 D NetworkManagementService: Removing idletimer
09-14 09:29:24.018  1034  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:24.019  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:24.019  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:24.019  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:24.019  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 09:29:24.019  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:24.019  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:24.019  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:24.019  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:24.020  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-14 09:29:24.020  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-14 09:29:24.020  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-14 09:29:24.020  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-14 09:29:24.020  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-14 09:29:24.020  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-14 09:29:24.020  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-14 09:29:24.020  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-14 09:29:24.021  1034  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-14 09:29:24.023  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 09:29:24.027  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:24.027  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:24.027  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:24.027  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 09:29:24.027  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:24.027  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:24.027  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:24.027  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 09:29:24.028  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 09:29:24.032  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:24.032  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:24.032  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:24.032  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 09:29:24.032  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:24.032  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:24.032  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:24.032  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 09:29:24.034  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 09:29:24.066  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-14 09:29:24.091  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-14 09:29:24.092  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:24.093  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:24.093  1034  1935 I art     : Explicit concurrent mark sweep GC freed 45313(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.710ms total 196.626ms
,09-14 09:29:24.111  1034  2821 D DhcpStateMachine: StoppedState
09-14 09:29:24.111  1034  2821 D DhcpStateMachine: StoppedState{ when=-126ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:24.133  2668  2668 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-14 09:29:24.133  2668  2668 I wpa_supplicant: monitor socket send errors count : 1
09-14 09:29:24.133  2668  2668 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1924-2\x00 that cannot receive messages
,09-14 09:29:24.135  1034  1560 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6973 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-14 09:29:24.135  1034  2732 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-14 09:29:24.135  1034  2732 D WifiMonitor: Dropping event because (p2p0) is stopped
09-14 09:29:24.137  1034  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-14 09:29:24.137  1034  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-14 09:29:24.154  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-14 09:29:24.156  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:24.156  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:24.169  2668  2668 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-14 09:29:24.169  2668  2668 W wpa_supplicant: USIM:  scard_deinit function
09-14 09:29:24.170  1034  1116 D Tethering: InitialState.processMessage what=4
09-14 09:29:24.171  1034  2732 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-14 09:29:24.171  1034  2732 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-14 09:29:24.171  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-14 09:29:24.171  1034  2732 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-14 09:29:24.171  1034  2732 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-14 09:29:24.171  1034  2732 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-14 09:29:24.171  1034  2732 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-14 09:29:24.172  1034  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:24.172  1034  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:24.173  1034  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=190167
09-14 09:29:24.174  1034  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=190167
09-14 09:29:24.174  1034  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=190168  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-14 09:29:24.175  1034  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=190168  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-14 09:29:24.213  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-14 09:29:24.225  6973  6973 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-14 09:29:24.226  2668  2668 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-14 09:29:24.227  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-14 09:29:24.227  1034  2732 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-14 09:29:24.227  1034  2732 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-14 09:29:24.227  1034  2732 D WifiMonitor: Disconnecting from the supplicant, no more events
09-14 09:29:24.230  1034  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-14 09:29:24.282  1034  1916 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6993 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-14 09:29:24.283  1034  1916 I ActivityManager: Killing 6287:com.android.providers.calendar/u0a14 (adj 15): empty #17
,09-14 09:29:24.291  6858  6858 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-14 09:29:24.353  1034  1057 W libprocessgroup: failed to open /acct/uid_10014/pid_6287/cgroup.procs: No such file or directory
,09-14 09:29:24.363  6858  6959 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:24.364  1034  1523 D WifiOffDelayIfNotUsed: stopMonitoring
09-14 09:29:24.364  1034  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-14 09:29:24.364  1034  1523 E WifiStateMachine: useWiFiOffloading() : false
09-14 09:29:24.364  1034  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-14 09:29:24.365  1924  1924 D WfdsService: Supplicant Connection state is changed : false
09-14 09:29:24.365  1924  2221 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-14 09:29:24.365  1924  2221 D WfdsService: Set the WFDS Monitor: false
09-14 09:29:24.365  1924  2221 D WfdsMonitor: WFDS Monitor is stopped
,09-14 09:29:24.369  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:24.369  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-14 09:29:24.371  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-14 09:29:24.371  1034  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-14 09:29:24.371  1034  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-14 09:29:24.372  1034  1916 D WifiServiceImplEx: setWifiEnabled: true pid=6858, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-14 09:29:24.373  1034  1916 D WifiService: setWifiEnabled: true pid=6858, uid=10118
09-14 09:29:24.373  1034  1916 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-14 09:29:24.374  2439  2439 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:24.379  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:24.379  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:24.379  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:24.379  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 09:29:24.379  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:24.379  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:24.379  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:24.379  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 09:29:24.382  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:24.383  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:24.385  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-14 09:29:24.385  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-14 09:29:24.385  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-14 09:29:24.405  6993  6993 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-14 09:29:24.405  6993  6993 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-14 09:29:24.406  6993  6993 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-14 09:29:24.406  6993  6993 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,09-14 09:29:24.407  6993  6993 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-14 09:29:24.408  6993  6993 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-14 09:29:24.520  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:24.559  6993  6993 D LgDataFeature: LgDataFeature() Constructor: none
09-14 09:29:24.559  6993  6993 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-14 09:29:24.567  1034  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-14 09:29:24.567  1034  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-14 09:29:24.570  1034  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-14 09:29:24.570  1034  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-14 09:29:24.570  1034  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-14 09:29:24.570  1034  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-14 09:29:24.570  1034  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-14 09:29:24.570  1034  1523 E WifiHW  : unknown target_country: EU , set to default
09-14 09:29:24.570  1034  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-14 09:29:24.571  1034  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-14 09:29:24.571  1034  1523 I WifiUtil: gEnableBmps=1
,09-14 09:29:24.573  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:24.664  1034  1888 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7013 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-14 09:29:24.669  1034  1888 I ActivityManager: Killing 6382:com.android.defcontainer/u0a4 (adj 15): empty #17
,09-14 09:29:24.690   332   332 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 488us total 26.589ms
,09-14 09:29:24.711   332   332 I art     : Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 407us total 20.334ms
,09-14 09:29:24.730   332   332 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 360us total 18.128ms
,09-14 09:29:24.746  1034  1935 W libprocessgroup: failed to open /acct/uid_10004/pid_6382/cgroup.procs: No such file or directory
09-14 09:29:24.765  7013  7013 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-14 09:29:24.787  7013  7013 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-14 09:29:24.818  7013  7013 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-14 09:29:24.818  7013  7013 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-14 09:29:24.818  7013  7013 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-14 09:29:24.818  7013  7013 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-14 09:29:24.819  7013  7013 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-14 09:29:24.820  7013  7013 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-14 09:29:24.825  7013  7013 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-14 09:29:24.830  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-14 09:29:24.836  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:24.879  7013  7013 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-14 09:29:24.889  1034  2001 D WifiServiceImplEx: setWifiEnabled: true pid=6858, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-14 09:29:24.890  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:24.890  1034  2001 D WifiService: setWifiEnabled: true pid=6858, uid=10118
09-14 09:29:24.890  1034  2001 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-14 09:29:24.894  7013  7013 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-14 09:29:24.895  1034  1528 D WifiController: Mismatch in the state 1
,09-14 09:29:24.903  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-14 09:29:24.903  6973  6973 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-14 09:29:24.903  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-14 09:29:24.907  7013  7013 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-14 09:29:24.912  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:24.928  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:24.938  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:24.938  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-14 09:29:24.941  7013  7013 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-14 09:29:24.945  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:24.950  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-14 09:29:24.950  6973  6973 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-14 09:29:24.950  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-14 09:29:24.955  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:24.967  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:24.982  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:24.983  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-14 09:29:24.986  7013  7013 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-14 09:29:25.042  1034  1916 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7036 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-14 09:29:25.120  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-14 09:29:25.123  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-14 09:29:25.134  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-14 09:29:25.158  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-14 09:29:25.158  6993  6993 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-14 09:29:25.158  6993  6993 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-14 09:29:25.159  6993  6993 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-14 09:29:25.162  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-14 09:29:25.164  7036  7055 W FormManager: Network not available. Please check & try again.
09-14 09:29:25.173  7036  7062 V FormManager: Network unavailable.
,09-14 09:29:25.175  6993  6993 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-14 09:29:25.175  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-14 09:29:25.175  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-14 09:29:25.175  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-14 09:29:25.175  7036  7062 V FormManager: Network unavailable.
09-14 09:29:25.176  6993  6993 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-14 09:29:25.176  6993  6993 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-14 09:29:25.179  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-14 09:29:25.179  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-14 09:29:25.181  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-14 09:29:25.183  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-14 09:29:25.189  4320  7065 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-14 09:29:25.190  4320  7066 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-14 09:29:25.190  4320  7066 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-14 09:29:25.191  6973  6973 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-14 09:29:25.191  6973  6973 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-14 09:29:25.191  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-14 09:29:25.195  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-14 09:29:25.200  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:25.207  7036  7067 W FormManager: Network not available. Please check & try again.
,09-14 09:29:25.214  7036  7068 V FormManager: Network unavailable.
09-14 09:29:25.219  7036  7068 V FormManager: Network unavailable.
09-14 09:29:25.220  7013  7013 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-14 09:29:25.222  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-14 09:29:25.222  7013  7013 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-14 09:29:25.224  1034  1883 I ActivityManager: Killing 6562:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-14 09:29:25.255  7013  7013 D LgDataFeature: LgDataFeature() Constructor: none
09-14 09:29:25.255  7013  7013 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-14 09:29:25.263  7013  7013 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-14 09:29:25.264  7013  7013 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-14 09:29:25.264  7013  7013 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-14 09:29:25.264  7013  7013 V SoundPool: doLoad: loading sample sampleID=1
09-14 09:29:25.265  7013  7013 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-14 09:29:25.268  7013  7071 V SoundPool: Start decode
09-14 09:29:25.268  7013  7071 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,09-14 09:29:25.271   308  2174 V MediaPlayerService: decode(23, 10857164, 17813)
09-14 09:29:25.271   308  2174 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-14 09:29:25.271   308  2174 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-14 09:29:25.271   308  2174 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-14 09:29:25.271   308  2174 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-14 09:29:25.271   308  2174 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-14 09:29:25.272   308  2174 V MediaPlayerService: player type = 3
09-14 09:29:25.272   308  2174 V AwesomePlayer: AwesomePlayer create()
09-14 09:29:25.273   308  2174 V AwesomePlayer: reset_l() 
09-14 09:29:25.273   308  2174 V AwesomePlayer: cancelPlayerEvents
09-14 09:29:25.273   308  2174 V AwesomePlayer: setAudioSink() 
09-14 09:29:25.273   308  2174 V AwesomePlayer: reset_l() 
09-14 09:29:25.273   308  2174 V AudioCache: notify(0xb1007280, 8, 0, 0)
09-14 09:29:25.273   308  2174 V AudioCache: ignored
09-14 09:29:25.273   308  2174 V AwesomePlayer: cancelPlayerEvents
09-14 09:29:25.273   308  2174 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-14 09:29:25.273   308  2174 V AwesomePlayer: setDataSource_l dataSource
09-14 09:29:25.273   308  2174 V LGParserOSAL: SniffLGParser start
09-14 09:29:25.273   308  2174 V LGParserOSAL: MainType:5, SubType=0
09-14 09:29:25.273   308  2174 V LGParserOSAL: #### check Mime : application/ogg
09-14 09:29:25.273   308  2174 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-14 09:29:25.273   308  2174 E MediaExtractor: Use LGExtractor :application/ogg 
09-14 09:29:25.293  1034  1056 W libprocessgroup: failed to open /acct/uid_10008/pid_6562/cgroup.procs: No such file or directory
,09-14 09:29:25.297  7013  7013 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-14 09:29:25.298  6776  6776 D UEI.SmartControl: QS Service created
09-14 09:29:25.313  6776  6776 I UEI.SmartControl: Service initServices...
,09-14 09:29:25.315  6776  6776 D UEI.SmartControl: QS start get config
09-14 09:29:25.323   308  2174 V LGParserOSAL: supported mime: application/ogg
09-14 09:29:25.323   308  2174 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-14 09:29:25.323   308  2174 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-14 09:29:25.323   308  2174 V AwesomePlayer: mBitrate = -1 bits/sec
09-14 09:29:25.323   308  2174 V AwesomePlayer: AudioTrack Setting
09-14 09:29:25.323   308  2174 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-14 09:29:25.323   308  2174 V AwesomePlayer: setAudioSource() 
09-14 09:29:25.323   308  2174 V MediaPlayerService: prepare
09-14 09:29:25.323   308  2174 V AwesomePlayer: prepareAsync_l() 
09-14 09:29:25.324   308  2174 V MediaPlayerService: wait for prepare
09-14 09:29:25.324   308  7072 V AwesomePlayer: onPrepareAsyncEvent() 
,09-14 09:29:25.324   308  7072 V AwesomePlayer: initAudioDecoder() 
09-14 09:29:25.324   308  7072 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-14 09:29:25.324   308  7072 V AudioSystem: isOffloadSupported()
09-14 09:29:25.324   308  7072 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-14 09:29:25.324   308  7072 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
,09-14 09:29:25.324   308  7072 I AudioFlinger: isAudioPlaybackHookOn() false
09-14 09:29:25.324   308  7072 V AwesomePlayer: getUseOffload() = 0 
09-14 09:29:25.324   308  7072 V OMXCodec: OMXCodec::Create
09-14 09:29:25.324   308  7072 V OMXCodec: findMatchingCodecs()
09-14 09:29:25.324   308  7072 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-14 09:29:25.324   308  7072 V OMXCodec: matchingCodecs.size()=1
09-14 09:29:25.324   308  7072 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-14 09:29:25.326   308  7072 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-14 09:29:25.326   308  7072 V LGCodecAdapter: LG Codec Adapter start
09-14 09:29:25.326   308  7072 V OMXCodec: OMXCodec Createtor
09-14 09:29:25.326   308  7072 V OMXCodec: setComponentRole
09-14 09:29:25.326   308  7072 V OMXCodec: configureCodec protected=0
09-14 09:29:25.326   308  7072 V LGCodecAdapter: called getLGCodecSpecificData
09-14 09:29:25.326   308  7072 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-14 09:29:25.326   308  7072 V LGCodecOSAL: Called LGconfigureCodecMETA
09-14 09:29:25.326   308  7072 V LGCodecOSAL: Called LGconfigureCodecMSG
09-14 09:29:25.326   308  7072 V LGCodecOSAL: Not support LGCodec
09-14 09:29:25.326   308  7072 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-14 09:29:25.326   308  7072 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-14 09:29:25.326   308  7072 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-14 09:29:25.326   308  7072 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-14 09:29:25.326   308  7072 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-14 09:29:25.326   308  7072 V AudioSystem: isOffloadSupported()
09-14 09:29:25.326   308  7072 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-14 09:29:25.326   308  7072 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-14 09:29:25.326   308  7072 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-14 09:29:25.326   308  7072 V OMXCodec: init()
09-14 09:29:25.326   308  7072 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-14 09:29:25.326   308  7072 V OMXCodec: allocateBuffers
09-14 09:29:25.326   308  7072 V OMXCodec: allocateBuffersOnPort portIndex=0
09-14 09:29:25.326   308  7072 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-14 09:29:25.328  7013  7013 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-14 09:29:25.328  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-14 09:29:25.335  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-14 09:29:25.335  1034  1116 D Tethering: InitialState.processMessage what=4
09-14 09:29:25.335   308  7072 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14341a0 on input port
09-14 09:29:25.335   308  7072 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on input port
09-14 09:29:25.335   308  7072 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on input port
09-14 09:29:25.335   308  7072 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
09-14 09:29:25.335   308  7072 V OMXCodec: allocateBuffersOnPort portIndex=1
09-14 09:29:25.335   308  7072 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-14 09:29:25.335   308  7072 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c01f0 on output port
09-14 09:29:25.335 ,  308  7072 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c08d0 on output port
09-14 09:29:25.338   303   892 D SoftapController: Softap fwReload - Ok
,09-14 09:29:25.340  1034  1523 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (763ms)
09-14 09:29:25.346   303   892 D CommandListener: Setting iface cfg
,09-14 09:29:25.346   303   892 D CommandListener: Trying to bring down wlan0
09-14 09:29:25.347   303   892 D CommandListener: Clearing all IP addresses on wlan0
09-14 09:29:25.348  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-14 09:29:25.351  1034  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-14 09:29:25.352   308  7072 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0920 on output port
09-14 09:29:25.352   308  7072 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0ce0 on output port
09-14 09:29:25.352   308  7072 V OMXCodec: init() mAsyncCompletion wait!!! 
09-14 09:29:25.352   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
,09-14 09:29:25.352   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-14 09:29:25.352   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-14 09:29:25.353   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-14 09:29:25.353   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-14 09:29:25.353   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-14 09:29:25.353   308  7072 V OMXCodec: init() mAsyncCompletion wait free! 
09-14 09:29:25.353   308  7072 V AwesomePlayer: finishAsyncPrepare_l() 
09-14 09:29:25.353   308  7072 V AudioCache: notify(0xb1007280, 5, 0, 0)
09-14 09:29:25.353   308  7072 V AudioCache: ignored
09-14 09:29:25.353   308  7072 V AudioCache: notify(0xb1007280, 1, 0, 0)
09-14 09:29:25.353   308  7072 V AudioCache: prepared
09-14 09:29:25.353   308  2174 V AudioCache: wait - success
09-14 09:29:25.353   308  2174 V MediaPlayerService: start
09-14 09:29:25.353   308  2174 V AwesomePlayer: play_l() 
09-14 09:29:25.353   308  2174 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-14 09:29:25.353   308  2174 V AwesomePlayer: createAudioPlayer_l
09-14 09:29:25.353   308  2174 V AwesomePlayer: seekAudioIfNecessary_l() 
09-14 09:29:25.353   308  2174 V AwesomePlayer: startAudioPlayer_l() 
09-14 09:29:25.353   308  2174 D AudioPlayer: start of Playback, useOffload 0
09-14 09:29:25.353   308  2174 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-14 09:29:25.353   308  2174 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-14 09:29:25.356   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-14 09:29:25.356   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-14 09:29:25.356   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-14 09:29:25.356   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-14 09:29:25.356   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-14 09:29:25.356   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-14 09:29:25.357   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974548464
09-14 09:29:25.357   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-14 09:29:25.357   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974550224
09-14 09:29:25.357   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,09-14 09:29:25.357   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974550304
09-14 09:29:25.357   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-14 09:29:25.357   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974551264
09-14 09:29:25.357   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-14 09:29:25.357   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-14 09:29:25.357   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,09-14 09:29:25.357   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-14 09:29:25.357   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-14 09:29:25.357   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-14 09:29:25.358   308  7074 V OMXCodec: allocateBuffersOnPort portIndex=1
09-14 09:29:25.358   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-14 09:29:25.358   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0920 on output port
09-14 09:29:25.358   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c08d0 on output port
09-14 09:29:25.358   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c01f0 on output port
09-14 09:29:25.358   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
09-14 09:29:25.359   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-14 09:29:25.359   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-14 09:29:25.362   308  2174 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-14 09:29:25.362   308  2174 V AudioCache: notify(0xb1007280, 6, 0, 0)
09-14 09:29:25.362   308  2174 V AudioCache: ignored
09-14 09:29:25.362   308  2174 V MediaPlayerService: wait for playback complete
09-14 09:29:25.352  7076  7076 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:25.352  7076  7076 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:25.363   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.363   308  7077 V AudioCache: memcpy(0xaf004000, 0xb57f4000, 4096)
09-14 09:29:25.365   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.365   308  7077 V AudioCache: memcpy(0xaf005000, 0xb57f4000, 4096)
09-14 09:29:25.365   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.365   308  7077 V AudioCache: memcpy(0xaf006000, 0xb57f4000, 4096)
09-14 09:29:25.365   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.365   308  7077 V AudioCache: memcpy(0xaf007000, 0xb57f4000, 4096)
09-14 09:29:25.366   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.366   308  7077 V AudioCache: memcpy(0xaf008000, 0xb57f4000, 4096)
09-14 09:29:25.366   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.366   308  7077 V AudioCache: memcpy(0xaf009000, 0xb57f4000, 4096)
09-14 09:29:25.367   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.367   308  7077 V AudioCache: memcpy(0xaf00a000, 0xb57f4000, 4096)
09-14 09:29:25.367   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.368   308  7077 V AudioCache: memcpy(0xaf00b000, 0xb57f4000, 4096)
09-14 09:29:25.368   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.368   308  7077 V AudioCache: memcpy(0xaf00c000, 0xb57f4000, 4096)
09-14 09:29:25.369   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.369   308  7077 V AudioCache: memcpy(0xaf00d000, 0xb57f4000, 4096)
09-14 09:29:25.369   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.369   308  7077 V AudioCache: memcpy(0xaf00e000, 0xb57f4000, 4096)
09-14 09:29:25.370   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.370   308  7077 V AudioCache: memcpy(0xaf00f000, 0xb57f4000, 4096)
09-14 09:29:25.370   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.370   308  7077 V AudioCache: memcpy(0xaf010000, 0xb57f4000, 4096)
09-14 09:29:25.370   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.370   308  7077 V AudioCache: memcpy(0xaf011000, 0xb57f4000, 4096)
09-14 09:29:25.371   308  7077 V AudioCach,e: write(0xb57f4000, 4096)
09-14 09:29:25.371   308  7077 V AudioCache: memcpy(0xaf012000, 0xb57f4000, 4096)
09-14 09:29:25.371   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.371   308  7077 V AudioCache: memcpy(0xaf013000, 0xb57f4000, 4096)
09-14 09:29:25.373   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.373   308  7077 V AudioCache: memcpy(0xaf014000, 0xb57f4000, 4096)
09-14 09:29:25.373   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.373   308  7077 V AudioCache: memcpy(0xaf015000, 0xb57f4000, 4096)
09-14 09:29:25.374   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.374   308  7077 V AudioCache: memcpy(0xaf016000, 0xb57f4000, 4096)
09-14 09:29:25.374   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.374   308  7077 V AudioCache: memcpy(0xaf017000, 0xb57f4000, 4096)
09-14 09:29:25.375   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.375   308  7077 V AudioCache: memcpy(0xaf018000, 0xb57f4000, 4096)
09-14 09:29:25.375   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.375   308  7077 V AudioCache: memcpy(0xaf019000, 0xb57f4000, 4096)
09-14 09:29:25.376   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.376   308  7077 V AudioCache: memcpy(0xaf01a000, 0xb57f4000, 4096)
09-14 09:29:25.376   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.376   308  7077 V AudioCache: memcpy(0xaf01b000, 0xb57f4000, 4096)
09-14 09:29:25.377   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.377   308  7077 V AudioCache: memcpy(0xaf01c000, 0xb57f4000, 4096)
09-14 09:29:25.377   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.377   308  7077 V AudioCache: memcpy(0xaf01d000, 0xb57f4000, 4096)
,09-14 09:29:25.378   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.378   308  7077 V AudioCache: memcpy(0xaf01e000, 0xb57f4000, 4096)
09-14 09:29:25.379   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.379   308  7077 V AudioCache: memcpy(0xaf01f000, 0xb57f4000, 4096)
09-14 09:29:25.379   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.379   308  7077 V AudioCache: memcpy(0xaf020000, 0xb57f4000, 4096)
09-14 09:29:25.380   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.380   308  7077 V AudioCache: memcpy(0xaf021000, 0xb57f4000, 4096)
09-14 09:29:25.380   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.380   308  7077 V AudioCache: memcpy(0xaf022000, 0xb57f4000, 4096)
09-14 09:29:25.381   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.381   308  7077 V AudioCache: memcpy(0xaf023000, 0xb57f4000, 4096)
09-14 09:29:25.382   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.382   308  7077 V AudioCache: memcpy(0xaf024000, 0xb57f4000, 4096)
09-14 09:29:25.382   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.382   308  7077 V AudioCache: memcpy(0xaf025000, 0xb57f4000, 4096)
09-14 09:29:25.383   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.383   308  7077 V AudioCache: memcpy(0xaf026000, 0xb57f4000, 4096)
09-14 09:29:25.385   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.385   308  7077 V AudioCache: memcpy(0xaf027000, 0xb57f4000, 4096)
09-14 09:29:25.385   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.385   308  7077 V AudioCache: memcpy(0xaf028000, 0xb57f4000, 4096)
09-14 09:29:25.386   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.386   308  7077 V AudioCache: memcpy(0xaf029000, 0xb57f4000, 4096)
09-14 09:29:25.386   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.386   308  7077 V AudioCache: memcpy(0xaf02a000, 0xb57f4000, 4096)
09-14 09:29:25.387   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.387   308  7077 V AudioCache: memcpy(0xaf02b000, 0xb57f4000, 4096)
09-14 09:29:25.387   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.387   308  7077 V AudioCache: memcpy(0xaf02c000, 0xb57f4000, 4096)
09-14 09:29:25.387   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.387   308  7077 V AudioCache: memcpy(0xaf02d000, 0xb57f4000, 4096)
09-14 09:29:25.388   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.388   308  7077 V AudioCache: memcpy(0xaf02e000, 0xb57f4000, 4096)
09-14 09:29:25.388   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.388   308  7077 V AudioCache: memcpy(0xaf02f000, 0xb57f4000, 4096)
09-14 09:29:25.389   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.389   308  7077 V AudioCache: memcpy(0xaf030000, 0xb57f4000, 4096)
09-14 09:29:25.389   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.389   308  7077 V AudioCache: memcpy(0xaf031000, 0xb57f4000, 4096)
09-14 09:29:25.389   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.389   308  7077 V AudioCache: memcpy(0xaf032000, 0xb57f4000, 4096)
09-14 09:29:25.390   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.390   308  7077 V AudioCache: memcpy(0xaf033000, 0xb57f4000, 4096)
09-14 09:29:25.391   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-14 09:29:25.391   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.391   308  7077 V AudioCache: memcpy(0xaf034000, 0xb57f4000, 4096)
09-14 09:29:25.391   308  7077 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-14 09:29:25.391   308  7077 V AudioCache: write(0xb57f4000, 4096)
09-14 09:29:25.391   308  7077 V AudioCache: memcpy(0xaf035000, 0xb57f4000, 4096)
09-14 09:29:25.391   308  7077 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-14 09:29:25.391   308  7077 V OMXCodec: [OMX.g,oogle.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-14 09:29:25.391   308  7077 V AwesomePlayer: postAudioEOS() 
09-14 09:29:25.391   308  7077 V AudioCache: write(0xb57f4000, 280)
09-14 09:29:25.391   308  7077 V AudioCache: memcpy(0xaf036000, 0xb57f4000, 280)
09-14 09:29:25.393   308  7072 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-14 09:29:25.393   308  7072 V AwesomePlayer: onStreamDone
09-14 09:29:25.393   308  7072 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-14 09:29:25.393   308  7072 V AudioCache: notify(0xb1007280, 2, 0, 0)
09-14 09:29:25.393   308  7072 V AudioCache: playback complete
09-14 09:29:25.393   308  7072 V AwesomePlayer: pause_l() 
09-14 09:29:25.393   308  7072 V AudioCache: notify(0xb1007280, 7, 0, 0)
09-14 09:29:25.393   308  7072 V AudioCache: ignored
09-14 09:29:25.393   308  7072 V AwesomePlayer: cancelPlayerEvents
09-14 09:29:25.393   308  2174 V AudioCache: wait - success
09-14 09:29:25.393   308  2174 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-14 09:29:25.393   308  7072 D AudioPlayer: Pause Playback at 1068125
09-14 09:29:25.393   308  2174 V AwesomePlayer: reset_l() 
09-14 09:29:25.393   308  2174 V AudioCache: notify(0xb1007280, 8, 0, 0)
09-14 09:29:25.393   308  2174 V AudioCache: ignored
09-14 09:29:25.393   308  2174 V AwesomePlayer: cancelPlayerEvents
09-14 09:29:25.393   308  2174 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-14 09:29:25.393   308  2174 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-14 09:29:25.393   308  2174 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-14 09:29:25.393   308  2174 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-14 09:29:25.393  7076  7076 I wpa_supplicant: Successfully initialized wpa_supplicant
09-14 09:29:25.393   308  2174 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 0
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 0
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14341a0 on port 0
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f60 on port 1
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c01f0 on port 1
09-14 09:29:25.394   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-14 09:29:25.395   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c08d0 on port 1
09-14 09:29:25.395   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-14 09:29:25.395   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c0920 on port 1
09-14 09:29:25.395   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,09-14 09:29:25.395   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-14 09:29:25.397   308  2174 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-14 09:29:25.397   308  2174 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-14 09:29:25.397  1034  1888 D WifiServiceImplEx: setWifiEnabled: true pid=6858, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-14 09:29:25.398  1034  1888 D WifiService: setWifiEnabled: true pid=6858, uid=10118
09-14 09:29:25.398  1034  1888 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-14 09:29:25.398   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-14 09:29:25.398   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-14 09:29:25.398   308  7074 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-14 09:29:25.399   308  2174 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-14 09:29:25.399   308  2174 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-14 09:29:25.399   308  2174 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-14 09:29:25.399   308  2174 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-14 09:29:25.399   308  2174 D AudioPlayer: AudioPlayer releasing audio source
09-14 09:29:25.399   308  2174 D AudioPlayer: AudioPlayer done releasing audio source
09-14 09:29:25.400   308  2174 V AwesomePlayer: reset_l() 
09-14 09:29:25.400   308  2174 V AwesomePlayer: cancelPlayerEvents
09-14 09:29:25.400   308  2174 V AwesomePlayer: ~AwesomePlayer call
09-14 09:29:25.400   308  2174 V AwesomePlayer: reset_l() 
09-14 09:29:25.400   308  2174 V AwesomePlayer: cancelPlayerEvents
09-14 09:29:25.400  1034  1528 D WifiController: Mismatch in the state 1
09-14 09:29:25.400  7013  7071 V SoundPool: close(31)
09-14 09:29:25.400  7013  7071 V SoundPool: pointer = 0x9fe78000, size = 205080, sampleRate = 48000, numChannels = 2
09-14 09:29:25.410  7013  7013 V LGMDMManager: Create singleton instance
09-14 09:29:25.427  7076  7076 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-14 09:29:25.428  7076  7076 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-14 09:29:25.452  1034  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-14 09:29:25.452  1034  1523 E WifiStateMachine: useWiFiOffloading() : false
09-14 09:29:25.452  1034  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-14 09:29:25.453  1034  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-14 09:29:25.453  1034  1523 D WifiMonitor: connecting to supplicant
09-14 09:29:25.455  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-14 09:29:25.456  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-14 09:29:25.456  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:25.458  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:25.459  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:25.459  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:25.469  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,09-14 09:29:25.471  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-14 09:29:25.473  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4944
09-14 09:29:25.478  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-14 09:29:25.478  6993  6993 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-14 09:29:25.478  6993  6993 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-14 09:29:25.478  6993  6993 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-14 09:29:25.478  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-14 09:29:25.478  6993  6993 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-14 09:29:25.479  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-14 09:29:25.479  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-14 09:29:25.479  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-14 09:29:25.479  6993  6993 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-14 09:29:25.479  6993  6993 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-14 09:29:25.484  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-14 09:29:25.486  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-14 09:29:25.489  7036  7085 W FormManager: Network not available. Please check & try again.
09-14 09:29:25.490  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:25.497  7036  7086 V FormManager: Network unavailable.
,09-14 09:29:25.498  7036  7086 V FormManager: Network unavailable.
09-14 09:29:25.499  7076  7076 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-14 09:29:25.573  7076  7076 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-14 09:29:25.581  1034  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-14 09:29:25.582  7076  7076 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-14 09:29:25.582  1034  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,09-14 09:29:25.582  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-14 09:29:25.582  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-14 09:29:25.582  1034  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-14 09:29:25.583  1034  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-14 09:29:25.583  1034  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-14 09:29:25.584  1034  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-14 09:29:25.585  1034  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-14 09:29:25.586  1034  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:25.587  1034  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:25.588  1034  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-14 09:29:25.590  1034  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-14 09:29:25.590  1034  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,09-14 09:29:25.592  1034  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-14 09:29:25.593  1034  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-14 09:29:25.593  1034  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-14 09:29:25.594  1034  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-14 09:29:25.594  1034  1523 E WifiStateMachine: useWiFiOffloading() : false
09-14 09:29:25.594  1034  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-14 09:29:25.594  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:25.594  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:25.594  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:25.594  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:25.595  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-14 09:29:25.595  1034  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
09-14 09:29:25.596  1034  1523 D WifiNative-wlan0: SET update_config 1: returned true
09-14 09:29:25.596  1034  1523 D WifiConfigStore: Loading config and enabling all networks 
09-14 09:29:25.596  1034  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-14 09:29:25.597  1924  1924 D WfdService: Waiting for WifiP2p enabling
09-14 09:29:25.598  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:25.600  1034  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-14 09:29:25.601  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-14 09:29:25.602  1034  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-14 09:29:25.605  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:25.605  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:25.605  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:25.605  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:25.605  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:25.605  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:25.605  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:25.605  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 09:29:25.605  1034  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-14 09:29:25.607  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 09:29:25.610  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:25.610  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:25.610  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:25.610  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:25.610  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:25.610  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:25.610  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:25.610  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 09:29:25.613  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 09:29:25.613  1034  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-14 09:29:25.613  1034  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-14 09:29:25.614  1034  1523 D WifiStateMachine: enableVerboseLogging : level 2
09-14 09:29:25.614  1034  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-14 09:29:25.614  1034  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-14 09:29:25.614  1034  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-14 09:29:25.614  1034  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-14 09:29:25.614  1034  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-14 09:29:25.615  1034  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-14 09:29:25.615  1034  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-14 09:29:25.615  1034  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-14 09:29:25.615  1034  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-14 09:29:25.615  1034  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-14 09:29:25.615  1034  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-14 09:29:25.615  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:25.615  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:25.615  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:25.615  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:25.615  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:25.615  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:25.615  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:25.615  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 09:29:25.615  1034  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-14 09:29:25.615  1034  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-14 09:29:25.616  1034  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-14 09:29:25.616  1034  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-14 09:29:25.616  1924  1924 D WfdsService: Supplicant Connection state is changed : true
09-14 09:29:25.616  1034  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-14 09:29:25.617  1034  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-14 09:29:25.617  1034  1523 D WifiNative-HAL: Setting external_sim to 1
09-14 09,:29:25.617  1034  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-14 09:29:25.617  1924  2221 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-14 09:29:25.617  1034  1523 D WifiNative-wlan0: SET external_sim 1: returned true
09-14 09:29:25.617  1034  1523 I WifiNative-HAL: startHal
09-14 09:29:25.617  1034  1523 D wifi    : setting scan oui 0xaf5a1d40
09-14 09:29:25.617  1924  2221 D WfdsService: Set the WFDS Monitor: true
09-14 09:29:25.617  1924  2221 D WfdsMonitor: WfdsMonitorThread create
09-14 09:29:25.617  1034  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-14 09:29:25.617  1034  1523 I WifiNative-HAL: startHal
09-14 09:29:25.617  1034  1523 D wifi    : setting scan oui 0xaf5a1d40
09-14 09:29:25.618  1034  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-14 09:29:25.618  1034  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-14 09:29:25.618  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-14 09:29:25.618  7076  7076 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-14 09:29:25.618  1924  2221 D WfdsMonitor: WFDS Monitor is created and started
09-14 09:29:25.618  1924  2221 D WfdsService: WiFi: Supplicant connection re-established
09-14 09:29:25.618  1034  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-14 09:29:25.618  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 09:29:25.618  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-14 09:29:25.618  7076  7076 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-14 09:29:25.619  1034  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-14 09:29:25.619  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-14 09:29:25.619  7076  7076 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-14 09:29:25.619  1924  7088 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-14 09:29:25.619  1034  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-14 09:29:25.619  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-14 09:29:25.619  7076  7076 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-14 09:29:25.619  1034  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-14 09:29:25.619  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-14 09:29:25.619  1924  7088 E CtrlSupplicant: Succeed to open control connection
09-14 09:29:25.619  7076  7076 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-14 09:29:25.619  1034  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-14 09:29:25.619  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-14 09:29:25.619  1924  7088 E CtrlSupplicant: Succeed to open monitor connection
09-14 09:29:25.619  7076  7076 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-14 09:29:25.620  1924  7088 D WfdsMonitor: Supplicant connection established
09-14 09:29:25.620  1034  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-14 09:29:25.620  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-14 09:29:25.620  1924  2221 D WfdsService: Connected to the supplicant for wfds
09-14 09:29:25.620  7076  7076 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-14 09:29:25.620  1034  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-14 09:29:25.621  1034  1523 E WifiNative: : [191,614,022 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-14 09:29:25.621  1034  1523 D WifiNative-wlan0: doBoolean: RECONNECT
09-14 09:29:25.621  1034  1523 D WifiNative-wlan0: RECONNECT: returned true
09-14 09:29:25.621  1034  1523 D WifiNative-wlan0: doString: [STATUS]
09-14 09:29:25.621  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-14 09:29:25.621  1034  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-14 09:29:25.621  1034  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-14 09:29:25.621  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-14 09:29:25.622  1034  1523 D WifiNative-wlan0: SET ps 1: returned true
09-14 09:29:25.622  1034  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.626   303   892 D CommandListener: Setting iface cfg
09-14 09:29:25.626   303   892 D CommandListener: Trying to bring up p2p0
09-14 09:29:25.627  1034  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-14 09:29:25.627  1034  1522 D LGWifiP2pService: P2pEnablingState
09-14 09:29:25.627  1034  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.627  1034  1522 D LGWifiP2pService: P2p socket connection successful
09-14 09:29:25.627  1034  1522 D LGWifiP2pService: P2pEnabledState
09-14 09:29:25.627  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
09-14 09:29:25.627  1034  1034 D RttService: SCAN_AVAILABLE : 3
09-14 09:29:25.627  1034  1541 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.628  1034  1541 I WifiNative-HAL: startHal
09-14 09:29:25.628  1034  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.628  1034  1541 D wifi    : getting scan capabilities on interface[1] = 0xaf5a1d40
09-14 09:29:25.628  1034  1541 D wifi    : failed to get capabilities : -3
09-14 09:29:25.628  1034  1541 E WifiScanningService: could not get scan capabilities
09-14 09:29:25.628  1034  1522 D LGWifiP2pService: sending p2p connection changed broadcast
09-14 09:29:25.629  1034  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-14 09:29:25.629  1034  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-14 09:29:25.630  1034  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-14 09:29:25.630  1034  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
09-14 09:29:25.630  1034  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-14 09:29:25.630  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-14 09:29:25.630  1924  1924 D WfdsService: WifiP2pState is changed : true
09-14 09:29:25.631  1924  1924 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-14 09:29:25.631  1924  1924 D WfdsService: isConnected: false
09-14 09:29:25.631  1924  2221 D WfdsService: Receive the WFDS_ENABLE Method
09-14 09:29:25.631  1924  2221 D WfdsService: Set the WFDS Monitor: true
09-14 09:29:25.631  1924  2221 D WfdsService: Connected to the supplicant for wfds
09-14 09:29:25.631  1924  2221 D WfdsJNI : doCommand: WFDS_SET TRUE
09-14 09:29:25.631  7076  7076 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-14 09:29:25.632  1924  2221 D WfdsService: selectPreferredScanChannel [36]
09-14 09:29:25.632  1924  2221 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-14 09:29:25.632  1034  1522 D WifiNative-p2p0: SET device_name G3: returned true
09-14 09:29:25.632  1034  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-14 09:29:25.632  1034  1522 D LGWifiP2pService: before postfix = G3
09-14 09:29:25.632  1034  1522 D WifiServerServiceExt: postfix byte check : 2
09-14 09:29:25.632  1034  1522 D LGWifiP2pService: after postfix = G3
09-14 09:29:25.632  1034  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-14 09:29:25.632  1034  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-14 09:29:25.632  1034  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-14 09:29:25.632  1034  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-14 09:29:25.632  1034  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-14 09:29:25.632  1034  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-14 09:29:25.633  1034  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-14 09:29:25.633  1034  1523 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-14 09:29:25.633  1034  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-14 09:29:25.633  1034  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-14 09:29:25.633  1034  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-14 09:29:25.633  1034  1522 D WifiNative-HAL: p2pGetDeviceAddress
09-14 09:29:25.633  1034  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-14 09:29:25.634  1034  1523 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-14 09:29:25.634  1034  1523 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-14 09:29:25.634  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-14 09:29:25.635  1034  1523 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-14 09:29:25.635  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-14 09:29:25.635  1034  1523 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-14 09:29:25.636  1034  1523 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-14 09:29:25.636  1034  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-14 09:29:25.636  1034  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-14 09:29:25.636  1034  1523 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-14 09:29:25.636  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-14 09:29:25.636  1924  1924 I WfdStateTracker: handleP2pThisDeviceChanged
09-14 09:29:25.636  1924  1924 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-14 09:29:25.636  1924  1924 D WfdsService: Update P2p Interface State: 3
09-14 09:29:25.637  1034  1523 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-14 09:29:25.637  1034  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
09-14 09:29:25.637  1034  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-14 09:29:25.637  1034  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-14 09:29:25.637  1034  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-14 09:29:25.638  1034  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-14 09:29:25.638  1034  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-14 09:29:25.638  1034  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-14 09:29:25.638  1034  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-14 09:29:25.638  7076  7076 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-14 09:29:25.638  1034  1522 D WifiNative-p2p0:    returned OK
09-14 09:29:25.638  1034  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-14 09:29:25.638  1034  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-14 09:29:25.639  1034  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-14 09:29:25.639  1034  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-14 09:29:25.639  1034  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-14 09:29:25.642  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-14 09:29:25.643  7036  7090 W FormManager: Network not available. Please check & try again.
09-14 09:29:25.647  7036  7091 V FormManager: Network unavailable.
09-14 09:29:25.647  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:25.650  7076  7076 E wpa_supplicant: disconnect_rssi_lvl: -100
09-14 09:29:25.651  1034  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-14 09:29:25.651  1034  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-14 09:29:25.651  1034  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-14 09:29:25.651  1034  1522 D LGWifiP2pService: InactiveState
,09-14 09:29:25.651  1034  1522 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.651  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.651  1034  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-14 09:29:25.651  1034  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-14 09:29:25.652  1034  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-14 09:29:25.652  7076  7076 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-14 09:29:25.652  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-14 09:29:25.652  7076  7076 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-14 09:29:25.653  7076  7076 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-14 09:29:25.653  7076  7076 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.653  7076  7076 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.656  1034  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-14 09:29:25.656  1034  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.656  1034  7087 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-14 09:29:25.656  1034  7087 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-14 09:29:25.656  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.656  1034  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-14 09:29:25.656  1034  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.656  1034  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-14 09:29:25.656  1034  7087 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:25.656  1034  7087 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.656  1034  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.656  1034  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.656  1034  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.656  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.656  1034  7087 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:25.656  1034  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.656  1034  7087 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.656  1034  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.656  1034  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.656  1034  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.656  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.656  1034  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.657  1924  2221 W WfdsService: DefaultState - msg [9441285] is not handled
09-14 09:29:25.657  1924  7088 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-14 09:29:25.657  1924  7088 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:25.657  1924  7088 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:25.657  7076  7076 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-14 09:29:25.657  7036  7091 V FormManager: Network unavailable.
09-14 09:29:25.657  7076  7076 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-14 09:29:25.658  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-14 09:29:25.658  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-14 09:29:25.658  1034  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-14 09:29:25.658  1034  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-14 09:29:25.658  7076  7076 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-14 09:29:25.658  7076  7076 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.658  1924  7088 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:25.658  1034  7087 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:25.658  1034  7087 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.658  1034  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.658  1034  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.659  1034  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-14 09:29:25.659  7076  7076 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.659  1034  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-14 09:29:25.659  1034  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-14 09:29:25.659  1034  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-14 09:29:25.659  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-14 09:29:25.659  1924  7088 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:25.660  7076  7076 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-14 09:29:25.660  1034  7087 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:25.660  7076  7076 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-14 09:29:25.660  1034  7087 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.660  1034  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.660  1034  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:25.660  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-14 09:29:25.660  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-14 09:29:25.660  1034  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-14 09:29:25.660  1034  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-14 09:29:25.660  1034  1522 D LGWifiP2pService: InactiveState{ when=-9ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.660  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.660  1034  1522 D LGWifiP2pService: DefaultState{ when=-9ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.660  1034  1034 E WifiServerServiceExt: No p2p device connected
09-14 09:29:25.660  1034  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.660  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:25.660  1034  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-14 09:29:25.660  1034  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-14 09:29:25.661  1034  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-14 09:29:25.661  1034  1523 D WifiNative-wlan0: doBoolean: SCAN
09-14 09:29:25.661  1034  1523 D WifiNative-wlan0: SCAN: returned false
09-14 09:29:25.661  1034  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=191655  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-14 09:29:25.665  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-14 09:29:25.665  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-14 09:29:25.666  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-14 09:29:25.666  1034  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=191660  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-14 09:29:25.667  1034  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-14 09:29:25.667  1034  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-14 09:29:25.667  1034  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-14 09:29:25.668  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-14 09:29:25.668  1034  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-14 09:29:25.668  1034  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-14 09:29:25.670  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:25.670  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:25.670  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-14 09:29:25.670  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-14 09:29:25.670  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
09-14 09:29:25.671  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:25.671  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:25.672  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:25.674  4320  7092 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-14 09:29:25.674  6748  6748 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-14 09:29:25.674  6748  6748 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-14 09:29:25.675  4320  7093 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-14 09:29:25.675  4320  7093 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-14 09:29:25.678  6748  6748 V [BNRBootReceiver]: Boot Receiver Return
09-14 09:29:25.680  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:25.687  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-14 09:29:25.691  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:25.696  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:25.696  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-14 09:29:25.697  7013  7013 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-14 09:29:25.762  6776  6776 I UEI.SmartControl: Supports setup maps: true
,09-14 09:29:25.766  6776  6776 D UEI.SmartControl: QS start statue = true Error code = 0
09-14 09:29:25.766  6776  6776 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-14 09:29:25.766  6776  6776 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-14 09:29:25.766  6776  6776 I UEI.SmartControl: ### init IR Blaster...
09-14 09:29:25.769  6776  6776 D serial_port: Configuring serial port
09-14 09:29:25.770  6776  6776 E UEI.SmartControl: UEIBLaster setting for 616
09-14 09:29:25.770  6776  6776 I UEI.SmartControl: Setting serial record hearder size = 2
09-14 09:29:25.770  6776  6776 I UEI.SmartControl: configuring settings for MAXQ616
09-14 09:29:25.770  6776  6776 I UEI.SmartControl: Get version...
09-14 09:29:25.788  6776  7095 D UEI.SmartControl: serial port data available: 21
,09-14 09:29:25.814  6776  6776 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-14 09:29:25.815  6776  6776 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-14 09:29:25.815  6776  6776 I UEI.SmartControl: QS saving settings...
,09-14 09:29:25.816  6776  6776 D UEI.SmartControl: IR Blaster version: 25672567
09-14 09:29:25.833  6776  7095 D UEI.SmartControl: serial port data available: 4
,09-14 09:29:25.866  6776  7098 I UEI.SmartControl: Device manager: loading config....
,09-14 09:29:25.870  6776  7098 D UEI.SmartControl: ----------- loading internal config...
,09-14 09:29:25.872  6776  6776 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-14 09:29:25.875  6776  6776 E UEI.SmartControl: Services init done
09-14 09:29:25.876  6776  6776 D UEI.SmartControl: QS Service init finished
09-14 09:29:25.878  6776  6776 D UEI.SmartControl: QS Service version name: 2.1.91
09-14 09:29:25.878  6776  6776 D UEI.SmartControl: QS Service version code: 201091
09-14 09:29:25.879  6776  6776 D UEI.SmartControl: Service requested: Control
09-14 09:29:25.885  6776  7098 E UEI.SmartControl: Loading SETTINGS...
09-14 09:29:25.888  6776  6776 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-14 09:29:25.894  6776  6776 D UEI.SmartControl: Internal service binding...
09-14 09:29:25.894  7013  7013 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-14 09:29:25.897  6776  6792 I UEI.SmartControl: ------ IControl API: 11
09-14 09:29:25.897  6776  6792 D UEI.SmartControl: File observer start...
09-14 09:29:25.898  6776  6792 E UEI.SmartControl: IR Port is disabled: false
09-14 09:29:25.898  6776  6792 D UEI.SmartControl: Starting file observer...
09-14 09:29:25.898  6776  6792 I UEI.SmartControl: Registering callback...
09-14 09:29:25.899  6776  6791 I UEI.SmartControl: ------ IControl API: 19
09-14 09:29:25.900  6776  6791 I UEI.SmartControl: Registering Services Ready callback...
09-14 09:29:25.903  6858  7010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:29:25.904  6776  7098 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-14 09:29:25.913  1034  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:25.914  1034  1888 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@18ebe844 mBinding = false
09-14 09:29:25.924  6776  7097 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-14 09:29:25.924  6776  7097 D UEI.SmartControl: -----service ready thread exits
09-14 09:29:25.925  7013  7031 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,09-14 09:29:25.926  7013  7069 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-14 09:29:25.926  7013  7069 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-14 09:29:25.927  7013  7013 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-14 09:29:25.927  7013  7013 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-14 09:29:25.927  6776  6792 I UEI.SmartControl: ------ IControl API: 8
09-14 09:29:25.929  7013  7013 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-14 09:29:25.929  7013  7013 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-14 09:29:25.929  7013  7013 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-14 09:29:25.930  7013  7013 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-14 09:29:25.931  7013  7013 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-14 09:29:25.931  7013  7013 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-14 09:29:25.935  7013  7013 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-14 09:29:25.937  7013  7013 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-14 09:29:25.938  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-14 09:29:25.940  7013  7013 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-14 09:29:25.941  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-14 09:29:25.943  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-14 09:29:25.945  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-14 09:29:25.945  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-14 09:29:25.945  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-14 09:29:25.947  1034  1116 D BluetoothManagerService: Message: 2
09-14 09:29:25.948  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-14 09:29:25.949  1034  1116 D BluetoothManagerService: Sending off request.
09-14 09:29:25.949  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,09-14 09:29:25.950  3891  3910 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-14 09:29:25.951  3891  3970 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-14 09:29:25.951  3891  3970 D BluetoothAdapterProperties: Setting state to 13
09-14 09:29:25.952  3891  3970 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-14 09:29:25.952  3891  3970 D BluetoothAdapterProperties: onBluetoothDisable()
09-14 09:29:25.953  7013  7013 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473838165951]
09-14 09:29:25.953  3891  3970 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-14 09:29:25.954  7013  7013 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-14 09:29:25.957  1034  1116 D BluetoothManagerService: Message: 60
09-14 09:29:25.957  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-14 09:29:25.957  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-14 09:29:25.958  1034  1765 I ActivityManager: Killing 6084:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-14 09:29:25.977  7013  7102 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-14 09:29:26.012  3891  3981 D BluetoothAdapterProperties: Scan Mode:20
,09-14 09:29:26.013  3891  3970 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-14 09:29:26.014  3891  4229 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-14 09:29:26.015  3891  3970 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-14 09:29:26.015  3891  4227 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-14 09:29:26.015  3891  4224 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-14 09:29:26.015  3891  4207 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-14 09:29:26.016  1034  1883 W libprocessgroup: failed to open /acct/uid_10011/pid_6084/cgroup.procs: No such file or directory
09-14 09:29:26.016  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-14 09:29:26.016  3891  4077 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-14 09:29:26.020  3891  4203 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-14 09:29:26.020  3891  4203 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-14 09:29:26.020  3891  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-14 09:29:26.020  3891  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-14 09:29:26.020  3891  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-14 09:29:26.020  3891  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-14 09:29:26.020  3891  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-14 09:29:26.020  3891  4203 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-14 09:29:26.020  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,09-14 09:29:26.020  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-14 09:29:26.020  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-14 09:29:26.020  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-14 09:29:26.020  3891  4077 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 09:29:26.020  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-14 09:29:26.020  3891  4077 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 09:29:26.020  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-14 09:29:26.020  3891  4077 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-14 09:29:26.020  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-14 09:29:26.020  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-14 09:29:26.020  3891  4077 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-14 09:29:26.022  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:26.023  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-14 09:29:26.024  3891  3891 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:26.024  3891  3891 D BluetoothMapService: STATE_TURNING_OFF
09-14 09:29:26.024  3891  3891 V BluetoothMapService: Handler(): got msg=4
09-14 09:29:26.024  3891  3891 D BluetoothMapService: MAP Service closeService in
09-14 09:29:26.025  3891  3891 D BluetoothMapMasInstance: MAP Service shutdown
09-14 09:29:26.025  3891  3891 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-14 09:29:26.025  3891  3891 V BluetoothMapService: MAP Service closeService out
09-14 09:29:26.026  3891  3891 V BtOppService: Receiver DISABLED_ACTION 
09-14 09:29:26.026  3891  3891 I BtOppRfcommListener: stopping Accept Thread
09-14 09:29:26.026  3891  3891 V BtOppRfcommListener: close mBtServerSocket
09-14 09:29:26.026  3891  3891 V BtOppRfcommListener: waiting for thread to terminate
09-14 09:29:26.027  3891  4224 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-14 09:29:26.027  3891  3891 V BtOppRfcommListener: done waiting for thread to terminate
,09-14 09:29:26.033  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:26.033  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:26.033  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:26.033  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:26.033  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:26.033  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 09:29:26.033  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:26.033  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:26.033  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 09:29:26.034  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:26.034  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 09:29:26.037  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:26.037  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:26.037  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:26.037  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:26.037  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:26.037  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 09:29:26.037  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:26.037  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:26.037  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 09:29:26.038  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:26.039  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 09:29:26.052  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:26.052  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:26.052  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:26.052  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:26.052  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:26.052  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 09:29:26.052  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:26.052  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:26.052  6858  6858 V io.jxcore.node.,ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 09:29:26.058  6993  6993 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-14 09:29:26.061  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:26.061  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 09:29:26.063  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:26.065  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:29:26.070  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:26.081  1034  1102 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7103 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-14 09:29:26.083  3891  3891 V BtOppService: onDestroy
09-14 09:29:26.085  3891  3891 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-14 09:29:26.085  3891  3891 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-14 09:29:26.085  3891  3891 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:26.085  3891  3891 V BluetoothPbapReceiver: ***********state = 13
09-14 09:29:26.087  3891  3891 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-14 09:29:26.087  3891  3891 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:26.087  3891  3891 V BluetoothPbapService: state: 13
09-14 09:29:26.088  3891  3891 V BluetoothPbapService: Pbap Service closeService in
09-14 09:29:26.090  2063  2063 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-14 09:29:26.090  3891  3891 V BluetoothPbapService: successfully stopped pbap service
09-14 09:29:26.090  3891  3891 V BluetoothPbapService: Pbap Service closeService out
09-14 09:29:26.090  3891  3891 V BluetoothPbapService: Pbap Service onDestroy
09-14 09:29:26.090  3891  3891 V BluetoothPbapService: Pbap Service closeService in
09-14 09:29:26.090  3891  3891 V BluetoothPbapService: Pbap Service closeService out
09-14 09:29:26.090  3891  3891 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-14 09:29:26.094  1034  1116 D BluetoothManagerService: Message: 20
09-14 09:29:26.094  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d954ff3:true
,09-14 09:29:26.103  1034  1116 D BluetoothManagerService: Message: 30
09-14 09:29:26.107  1034  1116 D BluetoothManagerService: Message: 30
09-14 09:29:26.108  6993  6993 D LocalBluetoothProfileManager: Adding local MAP profile
09-14 09:29:26.109  6993  6993 D BluetoothMap: Create BluetoothMap proxy object
09-14 09:29:26.112  1034  1116 D BluetoothManagerService: Message: 30
,09-14 09:29:26.119  1034  1116 D BluetoothManagerService: Message: 30
09-14 09:29:26.121  6993  6993 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-14 09:29:26.122  6993  6993 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-14 09:29:26.135  6993  6993 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-14 09:29:26.138  6993  6993 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-14 09:29:26.144  6993  6993 D DockEventReceiver: finishStartingService: stopping service
09-14 09:29:26.145  6993  6993 D BluetoothInputDevice: Proxy object connected
09-14 09:29:26.146  6993  6993 D HidProfile: Bluetooth service connected
,09-14 09:29:26.146  6993  6993 D BluetoothPan: BluetoothPAN Proxy object connected
09-14 09:29:26.147  6993  6993 D PanProfile: Bluetooth service connected
09-14 09:29:26.147  6993  6993 D BluetoothMap: Proxy object connected
09-14 09:29:26.148  6993  6993 D MapProfile: Bluetooth service connected
09-14 09:29:26.148  6993  6993 D BluetoothMap: getConnectedDevices()
09-14 09:29:26.149  6993  6993 D BluetoothMap: Bluetooth is Not enabled
09-14 09:29:26.149  6993  6993 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-14 09:29:26.162  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-14 09:29:26.163  1034  7087 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-14 09:29:26.163  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-14 09:29:26.163  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-14 09:29:26.163  1034  7087 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-14 09:29:26.163  7076  7076 E wpa_supplicant: USIM:  scard_init function
09-14 09:29:26.163  7076  7076 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-14 09:29:26.163  1034  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-14 09:29:26.164  1034  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-14 09:29:26.164  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-14 09:29:26.164  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,09-14 09:29:26.166  1034  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-14 09:29:26.166  1034  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-14 09:29:26.166  1034  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-14 09:29:26.169  7103  7103 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-14 09:29:26.170  7103  7103 W LG Account v2.2: No ProfileInfo entries
09-14 09:29:26.170  7103  7103 I LG Account v2.2: isEnabled: false
09-14 09:29:26.170  7103  7103 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-14 09:29:26.170  7103  7103 I Feature : [Lifetracker]Country: EU
09-14 09:29:26.170  7103  7103 I Feature : [Lifetracker]Operator: OPEN
09-14 09:29:26.170  7103  7103 I Feature : [Lifetracker]Ranking support: false
09-14 09:29:26.171  7103  7103 I Feature : [Lifetracker]Comfort support: false
09-14 09:29:26.171  7103  7103 I Feature : [Lifetracker]Accessory: true
09-14 09:29:26.171  7103  7103 I Feature : [Lifetracker]Health device: true
09-14 09:29:26.171  1034  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=192164  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-14 09:29:26.171  7103  7103 I Feature : [Lifetracker]Extra Pedometer: false
09-14 09:29:26.171  7103  7103 I Feature : [Lifetracker]Blood glucose device: false
09-14 09:29:26.172  7103  7103 I Feature : [Lifetracker]Device Number: 3
09-14 09:29:26.174  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.174  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.174  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-14 09:29:26.175  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:26.175  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-14 09:29:26.177  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:26.181  1034  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=192175  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-14 09:29:26.184  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.184  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.184  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-14 09:29:26.187  7013  7013 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-14 09:29:26.188  7013  7013 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-14 09:29:26.188  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,09-14 09:29:26.188  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-14 09:29:26.189  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-14 09:29:26.189  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:26.189  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:26.189  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-14 09:29:26.189  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-14 09:29:26.190  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:26.191  6993  6993 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-14 09:29:26.196  6993  6993 D BluetoothPermissionRequest: onReceive
09-14 09:29:26.196  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-14 09:29:26.196  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-14 09:29:26.198  6993  6993 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-14 09:29:26.200  7013  7013 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
09-14 09:29:26.206  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-14 09:29:26.209  6993  6993 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-14 09:29:26.213  1034  1916 I ActivityManager: Killing 6106:com.android.contacts/u0a19 (adj 15): empty #17
,09-14 09:29:26.215  6993  6993 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-14 09:29:26.254  3891  3891 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-14 09:29:26.254  3891  3891 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-14 09:29:26.256  3891  3891 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-14 09:29:26.257  1034  1970 W libprocessgroup: failed to open /acct/uid_10019/pid_6106/cgroup.procs: No such file or directory
09-14 09:29:26.258  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:26.262  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:26.262  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-14 09:29:26.266  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:26.266  3891  3891 V BluetoothFtpService: Ftp Service onStartCommand
09-14 09:29:26.267  3891  3891 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:26.267  3891  3891 V BluetoothFtpService: Ftp Service closeService
09-14 09:29:26.267  3891  3891 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-14 09:29:26.269  3891  3891 V BluetoothFtpService: successfully stopped ftp service
09-14 09:29:26.270  3891  3891 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-14 09:29:26.270  3891  3891 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-14 09:29:26.270  3891  3891 V BluetoothSapReceiver: SapReceiver onReceive 
09-14 09:29:26.271  3891  3891 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:26.271  3891  3891 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-14 09:29:26.271  3891  3891 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-14 09:29:26.273  3891  3891 V BluetoothFtpService: Ftp Service onDestroy
09-14 09:29:26.273  3891  3891 V BluetoothFtpService: Ftp Service closeService
09-14 09:29:26.274  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:26.280  7076  7076 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-14 09:29:26.280  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-14 09:29:26.280  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-14 09:29:26.280  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-14 09:29:26.280  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-14 09:29:26.280  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-14 09:29:26.281  1034  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=192274  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,09-14 09:29:26.281  1034  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=192275  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,09-14 09:29:26.280  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-14 09:29:26.286  1034  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=192280
09-14 09:29:26.287  1034  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=192280
09-14 09:29:26.287  1034  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=192281
09-14 09:29:26.287  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=192281
09-14 09:29:26.288  1034  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=192281
09-14 09:29:26.291  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-14 09:29:26.291  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-14 09:29:26.292  7076  7076 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-14 09:29:26.292  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-14 09:29:26.292  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-14 09:29:26.292  1034  7087 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-14 09:29:26.292  7076  7076 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-14 09:29:26.292  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-14 09:29:26.292  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-14 09:29:26.292  1034  7087 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-14 09:29:26.293  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-14 09:29:26.293  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-14 09:29:26.341  1034  1587 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7129 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-14 09:29:26.342  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-14 09:29:26.343  3891  3891 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:26.343  3891  3891 V BluetoothSapService: state: 13
09-14 09:29:26.343  3891  3891 V BluetoothSapService: Stopping SAP server process
09-14 09:29:26.344  3891  3891 V BluetoothSapService: Sap Service closeSapService in
09-14 09:29:26.344  3891  3891 V BluetoothSapService: Close listen Socket : 
09-14 09:29:26.344  3891  3891 V BluetoothSapService: Close rfcomm Socket : 
,09-14 09:29:26.345  3891  3891 V BluetoothSapService: Close sapd  Socket : 
09-14 09:29:26.350  3891  3891 V BluetoothSapService: Sap Service closeSapService out
09-14 09:29:26.350  3891  3891 V BluetoothSapService: Sap Service onDestroy
09-14 09:29:26.350  3891  3891 V BluetoothSapService: Sap Service closeSapService in
09-14 09:29:26.350  3891  3891 V BluetoothSapService: Close listen Socket : 
09-14 09:29:26.350  3891  3891 V BluetoothSapService: Close rfcomm Socket : 
09-14 09:29:26.350  1034  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=192343  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-14 09:29:26.350  3891  3891 V BluetoothSapService: Close sapd  Socket : 
09-14 09:29:26.351  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-14 09:29:26.351  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-14 09:29:26.352  3891  3891 V BluetoothSapService: Sap Service closeSapService out
09-14 09:29:26.358  1034  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=192352  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-14 09:29:26.359  1034  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=192353  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-14 09:29:26.360  1034  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=192354  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-14 09:29:26.361  1034  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=192354
09-14 09:29:26.363  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:26.363  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:26.363  1034  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=192357
09-14 09:29:26.364  1034  1523 D WifiNative-wlan0: doString: [STATUS]
,09-14 09:29:26.365  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-14 09:29:26.365  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-14 09:29:26.366  1034  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-14 09:29:26.366  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:26.366  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.366  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.366  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-14 09:29:26.368  1034  1523 I WifiServiceExtension: setVHTCapabilityType  : false
09-14 09:29:26.370  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.370  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.370  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-14 09:29:26.370  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:26.371  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:26.372  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:26.374  1034  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-14 09:29:26.374  1034  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-14 09:29:26.381  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:26.381  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:26.381  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.382  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.382  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-14 09:29:26.385  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.385  7013  7013 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-14 09:29:26.385  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.385  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-14 09:29:26.388  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:26.389  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:26.389  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:26.391  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:26.391  1034  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-14 09:29:26.391  1034  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-14 09:29:26.391  1034  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-14 09:29:26.392  1034  1529 D ConnectivityService: Got NetworkAgent Messenger
09-14 09:29:26.392  1034  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-14 09:29:26.392  1034  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-14 09:29:26.392  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-14 09:29:26.392  1034  1529 D ConnectivityService: NetworkAgent connected
09-14 09:29:26.393  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:26.393  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:26.397  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:26.397  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-14 09:29:26.398  1034  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-14 09:29:26.398  1034  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-14 09:29:26.398  1034  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-14 09:29:26.399  1034  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-14 09:29:26.399  1034  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-14 09:29:26.402  1034  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-14 09:29:26.404   303   892 D CommandListener: Setting iface cfg
09-14 09:29:26.406  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:26.409  1034  1523 E WifiStateMachine: Start Dhcp Watchdog 2
09-14 09:29:26.409  1034  7147 D DhcpStateMachine: StoppedState
09-14 09:29:26.409  1034  7147 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:26.409  1034  7147 D DhcpStateMachine: WaitBeforeStartState
09-14 09:29:26.410  1034  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=192403  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-14 09:29:26.410  1034  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=192404  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-14 09:29:26.412  1034  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=192405  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-14 09:29:26.413  1034  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:26.413  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:26.414  1034  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:26.414  1034  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:26.415  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:26.415  1034  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:26.416  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:26.416  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:26.417  1034  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=192410  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-14 09:29:26.417  7013  7013 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-14 09:29:26.417  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-14 09:29:26.417  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-14 09:29:26.418  1034  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=192411  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-14 09:29:26.418  1034  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=192412  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-14 09:29:26.420  1034  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:147076] from screen [on:0 period:664383892] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-14 09:29:26.421  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-14 09:29:26.421  6993  6993 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-14 09:29:26.421  6993  6993 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-14 09:29:26.421  6993  6993 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-14 09:29:26.421  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:664383893] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-14 09:29:26.421  1034  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-14 09:29:26.424  7129  7129 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-14 09:29:26.425  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-14 09:29:26.426  6993  6993 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-14 09:29:26.426  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-14 09:29:26.426  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-14 09:29:26.426  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-14 09:29:26.426  6993  6993 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-14 09:29:26.426  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-14 09:29:26.426  6993  6993 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-14 09:29:26.427  1034  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:26.427  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:26.428  1034  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:26.428  1034  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:26.429  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:26.429  1034  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:26.430  1034  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=150,0,0
09-14 09:29:26.430  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=150,0,0
09-14 09:29:26.430  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:26.430  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-14 09:29:26.430  1034  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-14 09:29:26.430  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-14 09:29:26.430  7076  7076 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-14 09:29:26.431  1034  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-14 09:29:26.431  1034  1523 D WifiNative-wlan0: doBoolean: SET ps 0
09-14 09:29:26.431  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:26.431  1034  1523 D WifiNative-wlan0: SET ps 0: returned true
09-14 09:29:26.431  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-14 09:29:26.432  7076  7076 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-14 09:29:26.432  1034  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-14 09:29:26.432  1034  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-14 09:29:26.432  1034  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-14 09:29:26.432  1034  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@6a018be target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:26.432  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@6a018be target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:26.432  1034  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-14 09:29:26.433  1034  7147 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:26.433  1034  7147 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-14 09:29:26.433   303   892 D CommandListener: Setting iface cfg
09-14 09:29:26.433   303   892 D CommandListener:, Trying to bring up wlan0
,09-14 09:29:26.435  1034  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-14 09:29:26.435  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-14 09:29:26.435  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-14 09:29:26.436  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-14 09:29:26.436  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-14 09:29:26.436  1034  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:26.437  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:26.437  1034  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:26.438  1034  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:26.438  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:26.438  1034  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:26.439  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-14 09:29:26.439  1034  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-14 09:29:26.439  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-14 09:29:26.439  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-14 09:29:26.439  1034  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:26.439  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:26.439  7076  7076 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-14 09:29:26.440  1034  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-14 09:29:26.440  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-14 09:29:26.440  7076  7076 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-14 09:29:26.441  1034  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-14 09:29:26.441  1034  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-14 09:29:26.446  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:26.450  6858  7100 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:26.453  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:26.454  1034  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:26.455  1034  1888 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@18ebe844 mBinding = false
09-14 09:29:26.457  1034  1523 D WifiNative-wlan0: SET ps 1: returned true
09-14 09:29:26.458  1034  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,09-14 09:29:26.458  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-14 09:29:26.458  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:26.458  1034  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-14 09:29:26.458  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:26.459  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-14 09:29:26.459  1034  1529 D ConnectivityService: ignoring duplicate network state non-change
09-14 09:29:26.459  7013  7013 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-14 09:29:26.460  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:26.461  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:26.462  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.462  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.462  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-14 09:29:26.462  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:26.464  1034  1116 D BluetoothManagerService: Message: 1
09-14 09:29:26.464  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@18ebe844
09-14 09:29:26.464  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-14 09:29:26.466  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-14 09:29:26.466  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-14 09:29:26.466  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-14 09:29:26.466  3891  3909 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-14 09:29:26.466  1034  1529 D ConnectivityService: Adding iface wlan0 to network 101
09-14 09:29:26.467  1034  1116 E BluetoothManagerService: IBluetooth.enable() returned false
09-14 09:29:26.467  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.468  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.468  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-14 09:29:26.472  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:26.473  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-14 09:29:26.473  1034  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-14 09:29:26.474  1924  1924 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-14 09:29:26.476  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.476  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.476  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-14 09:29:26.478  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-14 09:29:26.480  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.480  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:26.480  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-14 09:29:26.483  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:26.483  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-14 09:29:26.484  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:26.486  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-14 09:29:26.487  1034  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-14 09:29:26.487  1034  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-14 09:29:26.487  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:26.487  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
09-14 09:29:26.487  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:26.488  1034  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-14 09:29:26.488   303   892 E Netd    : netlink response contains error (File exists)
09-14 09:29:26.489  1034  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-14 09:29:26.489  1034  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-14 09:29:26.489  1034  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-14 09:29:26.489  1034  1529 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-14 09:29:26.490  1034  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,09-14 09:29:26.490  1034  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-14 09:29:26.490  1034  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-14 09:29:26.490  1034  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-14 09:29:26.490  1034  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-14 09:29:26.490  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:26.490  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-14 09:29:26.491  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:26.491  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-14 09:29:26.491  1034  1529 D ConnectivityService: currentScore = 0, newScore = 20
09-14 09:29:26.491  1034  1529 D ConnectivityService:    accepting network in place of null
09-14 09:29:26.491  1034  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:26.492  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:26.492  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-14 09:29:26.492  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:26.492  1034  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:26.492  1034  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-14 09:29:26.492  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-14 09:29:26.494  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:26.494  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-14 09:29:26.494  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:26.494  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:26.495  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
09-14 09:29:26.495  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-14 09:29:26.495  1034  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-14 09:29:26.496  1034  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-14 09:29:26.496  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-14 09:29:26.498   303  7153 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-14 09:29:26.499  1034  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:26.500  1034  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-14 09:29:26.500  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-14 09:29:26.500  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-14 09:29:26.500  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-14 09:29:26.500  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-14 09:29:26.501  1034  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-14 09:29:26.504  1034  1529 D ConnectivityService: validation of new default Network = false
09-14 09:29:26.504  1034  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-14 09:29:26.504  1034  1529 D DSQN    : enableDataServiceNotify 
09-14 09:29:26.504  1034  1529 D DSQN    : start dsqn bin
09-14 09:29:26.507  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:26.508  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:26.508  7013  7013 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-14 09:29:26.509  1034  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-14 09:29:26.509  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:26.509  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:26.509  1034  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:26.510  1588  2102 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-14 09:29:26.492  7154  7154 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:26.492  7154  7154 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:26.516  1034  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-14 09:29:26.517  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:26.523  7154  7154 E DSQN    : DSQN ssw
,09-14 09:29:26.527  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:26.532  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:26.536  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:26.536  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:26.537  7013  7013 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-14 09:29:26.538  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.,
09-14 09:29:26.541  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-14 09:29:26.542  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:26.542  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-14 09:29:26.543  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:26.545  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:26.547   303  7153 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-14 09:29:26.549  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:26.550  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:26.550  7013  7013 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-14 09:29:26.555  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-14 09:29:26.561  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:26.565  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:26.570  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:26.570  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:26.573  7013  7013 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-14 09:29:26.576  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:26.581   303  7153 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-14 09:29:26.581  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:26.586  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:26.592  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:26.592  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:26.593  7013  7013 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-14 09:29:26.597  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-14 09:29:26.604  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-14 09:29:26.605   303   891 D LGDataListener: argv[0]=dsqncommand
09-14 09:29:26.605   303   891 D LGDataListener: argv[1]=wlan0
09-14 09:29:26.605   303   891 D LGDataListener: argv[2]=1
09-14 09:29:26.605   303   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-14 09:29:26.606  1034  1114 D DSQN    : DSQM DsqnNotification wlan0  1
09-14 09:29:26.606  1034  1114 D DSQN    : start to monitor internet connection
09-14 09:29:26.614  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-14 09:29:26.619  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:26.626  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:26.630  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 14 Sep 2016 07:29:26 GMT], X-Android-Received-Millis=[1473838166629], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473838166605]}
09-14 09:29:26.630  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-14 09:29:26.631  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-14 09:29:26.631  1034  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-14 09:29:26.632  1034  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-14 09:29:26.632  1034  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-14 09:29:26.632  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:26.632  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-14 09:29:26.632  1034  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-14 09:29:26.633  1034  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-14 09:29:26.633  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:26.633  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:26.634  1034  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:26.636  1034  7147 D DhcpStateMachine: DHCPV4 request on wlan0
09-14 09:29:26.637  1588  2102 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-14 09:29:26.639  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:26.639  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:26.639  1034  7147 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-14 09:29:26.639  1034  7147 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-14 09:29:26.640  1034  1529 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:26.640  7013  7013 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-14 09:29:26.643  7013  7013 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-14 09:29:26.643  1034  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:26.643  1034  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-14 09:29:26.645  7013  7013 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-14 09:29:26.645  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:26.646  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-14 09:29:26.646  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-14 09:29:26.632  7160  7160 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:26.632  7160  7160 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:26.652  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-14 09:29:26.659  7160  7160 I dhcpcd  : version 5.5.6 starting
09-14 09:29:26.660  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-14 09:29:26.661  7160  7160 E dhcpcd  : get_duid: m
09-14 09:29:26.661  7160  7160 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-14 09:29:26.661  7160  7160 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-14 09:29:26.662  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-14 09:29:26.667  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:26.677  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:26.692  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:26.693  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:26.694  7013  7013 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-14 09:29:26.695  7013  7013 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,09-14 09:29:26.698  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-14 09:29:26.699  7013  7013 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-14 09:29:26.700  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:26.701  1034  2025 I ActivityManager: Killing 6619:com.lge.email/u0a23 (adj 15): empty #17
09-14 09:29:26.702  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:26.736  7160  7160 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-14 09:29:26.736  7160  7160 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-14 09:29:26.736  7160  7160 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-14 09:29:26.736  7160  7160 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-14 09:29:26.736  7160  7160 D dhcpcd  : wlan0: sending REQUEST (xid 0xf6941919), next in 3.35 seconds
09-14 09:29:26.743  1034  1935 W libprocessgroup: failed to open /acct/uid_10023/pid_6619/cgroup.procs: No such file or directory
09-14 09:29:26.785  7160  7160 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-14 09:29:26.792  7160  7160 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-14 09:29:26.792  7160  7160 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,09-14 09:29:26.792  7160  7160 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-14 09:29:26.793  7160  7160 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-14 09:29:26.793  7160  7160 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-14 09:29:26.794  7160  7160 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-14 09:29:26.794  7160  7160 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-14 09:29:26.794  7160  7160 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-14 09:29:26.969  1034  1057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:26.970  1034  1057 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@18ebe844 mBinding = false
09-14 09:29:26.971  1034  1116 D BluetoothManagerService: Message: 1
09-14 09:29:26.971  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@18ebe844
,09-14 09:29:26.985  3891  4201 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-14 09:29:26.986  1034  1116 E BluetoothManagerService: IBluetooth.enable() returned false
,09-14 09:29:27.014  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:27.017  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-14 09:29:27.021  1034  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:27.028  1034  1116 D Tethering: MasterInitialState.processMessage what=3
09-14 09:29:27.033  3891  3981 D bt_hci_bdroid: cleanup
,09-14 09:29:27.035  3891  4080 I bt_lpm  : LPM is already off!!!
09-14 09:29:27.036  3891  4191 I bt_userial_mct: exiting userial_read_thread
09-14 09:29:27.036  3891  4191 D bt_userial_mct: Leaving userial_evt_read_thread()
,09-14 09:29:27.037  3891  4077 W bt-btif : ag scb idx 1 not allocated
09-14 09:29:27.037  3891  4077 E bt-btif : BTA AG is already disabled, ignoring ...
09-14 09:29:27.037  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-14 09:29:27.037  3891  4077 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 09:29:27.037  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-14 09:29:27.037  3891  4077 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 09:29:27.037  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-14 09:29:27.037  1034  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:27.037  3891  4077 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-14 09:29:27.037  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-14 09:29:27.037  3891  4077 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 09:29:27.037  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-14 09:29:27.037  3891  4077 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 09:29:27.037  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-14 09:29:27.037  3891  4077 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-14 09:29:27.037  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-14 09:29:27.037  3891  4077 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 09:29:27.038  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-14 09:29:27.038  3891  4077 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 09:29:27.038  3891  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-14 09:29:27.038  3891  4077 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-14 09:29:27.038  3891  4077 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-14 09:29:27.039  3891  3981 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-14 09:29:27.039  3891  4080 I bt_vendor: hw_epilog_process
09-14 09:29:27.039  3891  3981 D bt_hci_bdroid: cleanup Finalizing cleanup
09-14 09:29:27.039  3891  3981 D bt_userial_mct: userial_close
09-14 09:29:27.039  3891  3981 E bt_userial_mct: pthread_join() FAILED result:3
09-14 09:29:27.039  3891  3981 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-14 09:29:27.044  1034  1116 D Tethering: MasterInitialState.processMessage what=3
09-14 09:29:27.050  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:27.050  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:27.050  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:27.050  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:27.050  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:27.050  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 09:29:27.050  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:27.050  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:27.050  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 09:29:27.051  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:27.055  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:27.060  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:27.060  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:27.060  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:27.060  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:27.060  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:27.060  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 09:29:27.060  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:27.060  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:27.060  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:27.062  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:27.062  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:27.067  1034  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:27.068  1034  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-14 09:29:27.069  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:27.070  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:27.070  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:27.070  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:27.070  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:27.070  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 09:29:27.070  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:27.070  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:27.070  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:27.070  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:27.070  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:27.074  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:27.077  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-14 09:29:27.080  6521  6967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-14 09:29:27.080  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:29:27.086  5836  5836 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-14 09:29:27.093  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:29:27.100  5836  5836 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-14 09:29:27.120  2063  2063 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-14 09:29:27.128  1034  1993 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-14 09:29:27.129  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:27.129  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:27.129  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-14 09:29:27.129  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:27.129  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-14 09:29:27.131   303  7202 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-14 09:29:27.131   303  7202 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,09-14 09:29:27.142  3891  3981 D bt_hci_bdroid: set_power 0
,09-14 09:29:27.142  3891  3981 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-14 09:29:27.142  3891  3981 I bt_vendor: bluetooth satus is on
09-14 09:29:27.142  3891  3981 I bt_vendor: bt-vendor : resetting BT status
09-14 09:29:27.142  3891  3981 I bt_vendor: Starting hciattach daemon
09-14 09:29:27.142  3891  3981 I bt_vendor: try to set false
09-14 09:29:27.143  3891  3981 I bt_vendor: Starting hciattach daemon
09-14 09:29:27.143  3891  3981 I bt_vendor: try to set false
09-14 09:29:27.143  3891  3981 I bt_vendor: cleanup
09-14 09:29:27.144  3891  4077 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-14 09:29:27.144  3891  3981 I GKI_LINUX: GKI_exit_task 0 done
09-14 09:29:27.144  3891  3981 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-14 09:29:27.152  3891  3970 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-14 09:29:27.161  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 14 Sep 2016 07:29:27 GMT], X-Android-Received-Millis=[1473838167160], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473838167130]}
09-14 09:29:27.161  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-14 09:29:27.161  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-14 09:29:27.161  1034  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-14 09:29:27.161  1034  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-14 09:29:27.161  1034  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-14 09:29:27.161  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:27.161  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-14 09:29:27.161  1034  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-14 09:29:27.162  1034  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-14 09:29:27.162  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:27.162  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:27.162  1034  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:27.163  1588  2102 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-14 09:29:27.167   303  7202 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,09-14 09:29:27.180  1034  2025 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7203 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-14 09:29:27.184  3891  3891 D HeadsetService: Received stop request...Stopping profile...
09-14 09:29:27.185  3891  3891 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-14 09:29:27.185  3891  3891 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-14 09:29:27.185  3891  4000 D HeadsetStateMachine: Exit Disconnected: -1
09-14 09:29:27.185  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.186  1034  1034 D BluetoothHeadset: Proxy object disconnected
09-14 09:29:27.186  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-14 09:29:27.187  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-14 09:29:27.188  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-14 09:29:27.188  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-14 09:29:27.189  3891  3891 D A2dpService: Received stop request...Stopping profile...
09-14 09:29:27.190  3891  4060 D A2dpStateMachine: Exit Disconnected: -1
09-14 09:29:27.191  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-14 09:29:27.191  3891  3970 D BluetoothAdapterState: Stopping profile services that were post enabled
09-14 09:29:27.192  3891  3891 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-14 09:29:27.192  3891  3891 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-14 09:29:27.192  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.193  1034  1034 D BluetoothA2dp: Proxy object disconnected
09-14 09:29:27.193  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-14 09:29:27.195  3891  3891 D HidService: Received stop request...Stopping profile...
09-14 09:29:27.195  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.197  6993  6993 D BluetoothInputDevice: Proxy object disconnected
09-14 09:29:27.197  6993  6993 D HidProfile: Bluetooth service disconnected
09-14 09:29:27.197  3891  3891 D HealthService: Received stop request...Stopping profile...
09-14 09:29:27.198  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.200  3891  3891 D HeadsetStateMachine: Unbinding service...
09-14 09:29:27.201  3891  3891 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-14 09:29:27.201  3891  3891 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-14 09:29:27.201  3891  3891 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-14 09:29:27.201  3891  3891 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-14 09:29:27.201  3891  3891 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-14 09:29:27.201  3891  3891 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-14 09:29:27.201  3891  3891 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-14 09:29:27.202  3891  3891 D PanService: Received stop request...Stopping profile...
09-14 09:29:27.203  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.204  6993  6993 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-14 09:29:27.204  6993  6993 D PanProfile: Bluetooth service disconnected
09-14 09:29:27.204  3891  3891 D BtGatt.DebugUtils: handleDebugAction() action=null
09-14 09:29:27.205  3891  3891 D BtGatt.GattService: Received stop request...Stopping profile...
09-14 09:29:27.205  3891  3891 D BtGatt.GattService: stop()
09-14 09:29:27.205  3891  3891 D BtGatt.AdvertiseManager: advertise clients cleared
09-14 09:29:27.207  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
,09-14 09:29:27.209  3891  3891 D BluetoothMapService: Received stop request...Stopping profile...
09-14 09:29:27.209  3891  3891 D BluetoothMapService: stop()
09-14 09:29:27.210  3891  3891 D BluetoothMapEmailAppObserver: deinitObservers()
,09-14 09:29:27.210  3891  3891 D BluetoothMapEmailAppObserver: removeReceiver()
09-14 09:29:27.211  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.213  3891  3891 I BluetoothA2dpServiceJni: cleanupNative
09-14 09:29:27.213  3891  4062 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-14 09:29:27.215  3891  3891 I GKI_LINUX: GKI_exit_task 2 done
09-14 09:29:27.215  3891  3891 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-14 09:29:27.216  6993  6993 D BluetoothMap: Proxy object disconnected
09-14 09:29:27.216  6993  6993 D MapProfile: Bluetooth service disconnected
09-14 09:29:27.216  3891  3891 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-14 09:29:27.216  3891  3891 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-14 09:29:27.218  3891  3891 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-14 09:29:27.218  3891  3891 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-14 09:29:27.218  3891  3891 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-14 09:29:27.219  3891  3891 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-14 09:29:27.219  3891  3891 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-14 09:29:27.220  3891  3891 V BluetoothMapService: Handler(): got msg=4
09-14 09:29:27.220  3891  3891 D BluetoothMapService: MAP Service closeService in
09-14 09:29:27.220  3891  3891 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-14 09:29:27.220  3891  3891 V BluetoothMapService: MAP Service closeService out
,09-14 09:29:27.220  3891  3891 D BluetoothMapService: cleanup()
09-14 09:29:27.220  3891  3891 D BluetoothMapService: MAP Service closeService in
09-14 09:29:27.220  3891  3891 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-14 09:29:27.220  3891  3891 V BluetoothMapService: MAP Service closeService out
09-14 09:29:27.220  3891  3970 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-14 09:29:27.221  3891  3970 D BluetoothAdapterProperties: Setting state to 10
09-14 09:29:27.221  3891  3970 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-14 09:29:27.221  1034  1116 D BluetoothManagerService: Message: 60
09-14 09:29:27.221  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-14 09:29:27.221  3891  3970 I BluetoothAdapterState: Entering OffState
09-14 09:29:27.221  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-14 09:29:27.221  6993  7009 D BluetoothMap: onBluetoothStateChange: up=false
09-14 09:29:27.222  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 09:29:27.222  1836  2457 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:29:27.223  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:29:27.223  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:29:27.223  6993  7008 D BluetoothPbap: onBluetoothStateChange: up=false
09-14 09:29:27.224  6993  7009 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-14 09:29:27.225  1836  3999 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:29:27.225  6993  7008 D BluetoothPan: onBluetoothStateChange on: false
09-14 09:29:27.226  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-14 09:29:27.230  6993  6993 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-14 09:29:27.230  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-14 09:29:27.230  6993  6993 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-14 09:29:27.231  6993  6993 D LGBluetoothEventManager: [BTUI] clear device connection state
09-14 09:29:27.232  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-14 09:29:27.232  1924  2105 D LGBluetoothAPIService: Message: 2
09-14 09:29:27.232  1924  2105 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@814952e mBinding = false
09-14 09:29:27.232  1924  2105 D LGBluetoothAPIService: Sending unbind request.
09-14 09:29:27.236  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:27.238  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:27.238  3891  3891 D LGBluetoothAPIServer: [BTUI] onUnbind()
09-14 09:29:27.238  3891  3891 D LGBluetoothAPIServer: [BTUI] cleanup() done
09-14 09:29:27.239  3891  3891 D LGBluetoothAPIServer: [BTUI] onDestroy()
09-14 09:29:27.241  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:27.242  6993  6993 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-14 09:29:27.250  1034  7147 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-14 09:29:27.250  3891  3891 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-14 09:29:27.250  3891  3891 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:27.250  3891  3891 V BluetoothPbapReceiver: ***********state = 10
09-14 09:29:27.251  1034  7147 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-14 09:29:27.251  1034  7147 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-14 09:29:27.252  1034  7147 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-14 09:29:27.252  1034  7147 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-14 09:29:27.252  1034  7147 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-14 09:29:27.252  1034  7147 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-14 09:29:27.252  1034  7147 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-14 09:29:27.253  6993  6993 D DockEventReceiver: finishStartingService: stopping service
09-14 09:29:27.253  1034  7147 D DhcpStateMachine: RunningState
09-14 09:29:27.255  2063  2063 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 09:29:27.269  6993  6993 D BluetoothPermissionRequest: onReceive
,09-14 09:29:27.272  6993  6993 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-14 09:29:27.273  6993  6993 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-14 09:29:27.276  6993  6993 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-14 09:29:27.284  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-14 09:29:27.287  3891  3891 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-14 09:29:27.287  3891  3891 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-14 09:29:27.287  3891  3891 V BluetoothSapReceiver: SapReceiver onReceive 
09-14 09:29:27.287  3891  3891 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:27.287  3891  3891 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-14 09:29:27.294  7129  7129 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-14 09:29:27.295  7203  7203 I AppUp4:AppBoxCP: onCreate
09-14 09:29:27.296  7203  7203 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-14 09:29:27.305  7203  7203 I AppUp4:DB:  setFingerPrint start
09-14 09:29:27.306  7203  7203 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-14 09:29:27.313  7203  7203 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,09-14 09:29:27.314  7203  7203 I AppUp4:DB:  SDK version = 21
09-14 09:29:27.314  7203  7203 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-14 09:29:27.315  7203  7203 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-14 09:29:27.316  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-14 09:29:27.317  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:27.320  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-14 09:29:27.320  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-14 09:29:27.327  7203  7203 I AppUp4:CustModeStarterReceiver: onReceive
,09-14 09:29:27.368  7203  7203 D LgDataFeature: LgDataFeature() Constructor: none
09-14 09:29:27.368  7203  7203 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-14 09:29:27.379  7203  7203 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c35705e
,09-14 09:29:27.380  7203  7203 D AppUp4:CustFacade: isCustomizationCompleted : false
09-14 09:29:27.380  7203  7203 D AppUp4:CustFacade: isPhone : true
09-14 09:29:27.380  7203  7203 D AppUp4:CustModeStarterReceiver: begin check event
09-14 09:29:27.381  7203  7203 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-14 09:29:27.381  7203  7203 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-14 09:29:27.382  7203  7224 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-14 09:29:27.382  7203  7224 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-14 09:29:27.383  7203  7224 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,09-14 09:29:27.386  1034  1993 I ActivityManager: Killing 6128:com.android.gallery3d/u0a27 (adj 15): empty #17
09-14 09:29:27.447  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:27.449  1034  1056 W libprocessgroup: failed to open /acct/uid_10027/pid_6128/cgroup.procs: No such file or directory
,09-14 09:29:27.453  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-14 09:29:27.457  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-14 09:29:27.463  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-14 09:29:27.471  4320  7226 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-14 09:29:27.476  1034  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:27.476  3483  3483 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:27.476  1034  1943 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@18ebe844 mBinding = false
,09-14 09:29:27.478  1034  1116 D BluetoothManagerService: Message: 1
09-14 09:29:27.479  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@18ebe844
09-14 09:29:27.479  4320  7226 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-14 09:29:27.482  4320  7227 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:27.482  4320  7227 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-14 09:29:27.485  3483  3483 V DownloadManager: DownloadService onCreate
09-14 09:29:27.487  3891  3970 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-14 09:29:27.487  3891  3970 D BluetoothAdapterProperties: Setting state to 11
09-14 09:29:27.487  3891  3970 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-14 09:29:27.487  3891  3970 D BluetoothBondStateMachine: make
09-14 09:29:27.488  1034  1116 D BluetoothManagerService: Message: 60
09-14 09:29:27.488  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-14 09:29:27.488  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-14 09:29:27.489  3483  7228 I DownloadManager: in removeSpuriousFiles
09-14 09:29:27.490  3483  7228 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-14 09:29:27.491  3891  3970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.491  3891  3970 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-14 09:29:27.491  3891  3970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.491  3891  3970 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,09-14 09:29:27.491  3891  3970 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-14 09:29:27.493  3483  7228 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2c34ee22 on behalf of 3483
09-14 09:29:27.494  3483  7228 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-14 09:29:27.495  3483  7228 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-14 09:29:27.495  3483  7228 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-14 09:29:27.495  3483  7228 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-14 09:29:27.495  3483  7228 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-14 09:29:27.495  3891  7229 I BluetoothBondStateMachine: StableState(): Entering Off State
09-14 09:29:27.495  3483  7228 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-14 09:29:27.495  3483  7228 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-14 09:29:27.496  3483  7228 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-14 09:29:27.496  3483  7228 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-14 09:29:27.496  3483  7228 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-14 09:29:27.496  3891  3970 E BluetoothAdapterService: File transfer profiles supported!!
09-14 09:29:27.496  3483  7228 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-14 09:29:27.499  3483  7228 I DownloadManager: in trimDatabase
09-14 09:29:27.500  3483  7228 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-14 09:29:27.501  3483  7228 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2563670 on behalf of 3483
09-14 09:29:27.510  1034  1529 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-14 09:29:27.531  1034  1056 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7232 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-14 09:29:27.535  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-14 09:29:27.537  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:27.538  6993  6993 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-14 09:29:27.539  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:27.541  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:27.544  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:29:27.550  3891  3891 D HeadsetService: Received start request. Starting profile...
09-14 09:29:27.550  3891  3891 D HeadsetStateMachine: make
09-14 09:29:27.552  3891  3970 E BluetoothAdapterService: File transfer profiles supported!!
09-14 09:29:27.553  3483  3483 V DownloadManager: DownloadService onStartCommand
,09-14 09:29:27.556  3483  7230 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-14 09:29:27.558  3483  7230 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@38d7ca6e on behalf of 3483
09-14 09:29:27.564  3483  7230 V DownloadManager: processing inserted download 1
09-14 09:29:27.565  3891  3970 E BluetoothAdapterService: File transfer profiles supported!!
09-14 09:29:27.565  3891  3891 D HeadsetStateMachine: max_hf_connections = 1
09-14 09:29:27.565  3891  3891 I bluedroid-qcom: get_profile_interface handsfree
09-14 09:29:27.565  3891  3891 E LGBluetoothDtmfAdapter: LGBluetoothDtmfLocalPlay is not null
09-14 09:29:27.566  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.566  3891  7247 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-14 09:29:27.566  3483  7230 V DownloadManager: processing inserted download 4
09-14 09:29:27.566  3891  7247 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-14 09:29:27.566  3891  7247 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-14 09:29:27.566  3891  7247 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-14 09:29:27.567   308   308 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 3891
09-14 09:29:27.568  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.569  3483  7230 V DownloadManager: processing inserted download 7
09-14 09:29:27.569  3891  3891 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-14 09:29:27.569  4320  7226 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-14 09:29:27.569  3891  3891 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:27.569  3891  3891 V BluetoothPbapReceiver: ***********state = 11
09-14 09:29:27.569   308   308 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-14 09:29:27.569   308   308 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-14 09:29:27.569   308   308 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-14 09:29:27.569   308   308 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-14 09:29:27.569   308   308 V voice   : voice_set_parameters: exit with code(0)
09-14 09:29:27.569   308   308 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-14 09:29:27.569   308   308 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-14 09:29:27.570  3483  7230 V DownloadManager: processing inserted download 8
09-14 09:29:27.570   308   308 V msm8974_platform: platform_set_parameters: exit with code(0)
09-14 09:29:27.570   308   308 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-14 09:29:27.570   308   308 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-14 09:29:27.570   308   308 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-14 09:29:27.571  3483  7230 V DownloadManager: processing inserted download 9
09-14 09:29:27.571  3891  3891 D A2dpService: Received start request. Starting profile...
09-14 09:29:27.571  3891  3891 V Avrcp   : make
09-14 09:29:27.572  3891  3891 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-14 09:29:27.572  3891  3891 I bluedroid-qcom: get_profile_interface avrcp
09-14 09:29:27.572  3483  7230 V DownloadManager: processing inserted download 10
09-14 09:29:27.573  3483  7230 V DownloadManager,: processing inserted download 11
09-14 09:29:27.574  3483  7230 V DownloadManager: processing inserted download 12
09-14 09:29:27.576  3483  7230 V DownloadManager: processing inserted download 13
,09-14 09:29:27.577  3891  3970 E BluetoothAdapterService: File transfer profiles supported!!
09-14 09:29:27.577  3483  7230 V DownloadManager: processing inserted download 14
09-14 09:29:27.578  3483  7230 V DownloadManager: processing inserted download 16
09-14 09:29:27.583  3891  3891 V AudioManager: registerRemoteController: size of Media player list: 0
09-14 09:29:27.583  4320  4320 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-14 09:29:27.583  4320  4320 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-14 09:29:27.584  4320  4320 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-14 09:29:27.584  2063  2063 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-14 09:29:27.585  3891  3891 E AudioManager: No RCC entry present to update
09-14 09:29:27.585  3891  3891 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-14 09:29:27.585  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-14 09:29:27.585  3891  3891 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-14 09:29:27.585  4320  4320 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,09-14 09:29:27.588  3891  3970 E BluetoothAdapterService: File transfer profiles supported!!
09-14 09:29:27.594  4320  4320 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-14 09:29:27.601  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-14 09:29:27.604  3483  3483 V DownloadManager: DownloadService onDestroy
09-14 09:29:27.605  3891  3970 E BluetoothAdapterService: File transfer profiles supported!!
09-14 09:29:27.670  7232  7232 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-14 09:29:27.671  7232  7232 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-14 09:29:27.673  7232  7232 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-14 09:29:27.673  7232  7232 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-14 09:29:27.673  3891  3970 E BluetoothAdapterService: File transfer profiles supported!!
,09-14 09:29:27.678  3891  3970 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-14 09:29:27.680  6993  6993 D BluetoothPermissionRequest: onReceive
09-14 09:29:27.686  6993  6993 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-14 09:29:27.722  1034  1587 V SIM_STK : Menu title from STK is T-Mobile
09-14 09:29:27.722  1034  1587 V SIM_STK : Menu title from STK is T-Mobile
,09-14 09:29:27.762  7232  7232 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-14 09:29:27.775  1034  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-14 09:29:27.775  7232  7232 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-14 09:29:27.776  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-14 09:29:27.777  1034  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-14 09:29:27.778  1034  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-14 09:29:27.779  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-14 09:29:27.781  1034  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-14 09:29:27.782  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-14 09:29:27.782  1034  1529 D ConnectivityService: identical MTU - not setting
09-14 09:29:27.782  1034  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-14 09:29:27.783  1034  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-14 09:29:27.783  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:27.783  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:27.785  1034  1765 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-14 09:29:27.785  1034  1529 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:27.785  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-14 09:29:27.785  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-14 09:29:27.785  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-14 09:29:27.785  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-14 09:29:27.785  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-14 09:29:27.785  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-14 09:29:27.785  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-14 09:29:27.785  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-14 09:29:27.785  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-14 09:29:27.785  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-14 09:29:27.785  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,09-14 09:29:27.785  3891  3891 D A2dpStateMachine: make
09-14 09:29:27.786  1588  2102 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-14 09:29:27.788  3891  3891 I bluedroid-qcom: get_profile_interface a2dp
09-14 09:29:27.788  3891  7254 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-14 09:29:27.789  3891  3891 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-14 09:29:27.789  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.789  3891  7253 D A2dpStateMachine: Enter Disconnected: -2
09-14 09:29:27.791  3891  3891 D HeadsetStateMachine: Proxy object connected
09-14 09:29:27.791  3891  3891 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-14 09:29:27.791  3891  3891 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-14 09:29:27.795  3891  3891 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-14 09:29:27.795  3891  7247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-14 09:29:27.795  3891  7247 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-14 09:29:27.795  3891  7247 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-14 09:29:27.796  3891  3891 D HidService: Received start request. Starting profile...
09-14 09:29:27.796  3891  3891 I bluedroid-qcom: get_profile_interface hidhost
09-14 09:29:27.796  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.797  3891  3891 D HealthService: Received start request. Starting profile...
09-14 09:29:27.798  3891  3891 I bluedroid-qcom: get_profile_interface health
09-14 09:29:27.798  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.799  3891  3891 D PanService: Received start request. Starting profile...
09-14 09:29:27.799  3891  3891 D BluetoothPanServiceJni: initializeNative(L110): pan
09-14 09:29:27.799  3891  3891 I bluedroid-qcom: get_profile_interface pan
,09-14 09:29:27.800  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.801  3891  3891 D BtGatt.DebugUtils: handleDebugAction() action=null
09-14 09:29:27.801  3891  3891 D BtGatt.GattService: Received start request. Starting profile...
09-14 09:29:27.801  3891  3891 D BtGatt.GattService: start()
09-14 09:29:27.801  3891  3891 D BtGatt.AdvertiseManager: advertise manager created
09-14 09:29:27.806  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.806  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.806  3891  3891 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-14 09:29:27.806  3891  3891 V BluetoothMapService: BluetoothMapBinder()
09-14 09:29:27.806  3891  3891 D BluetoothMapService: Received start request. Starting profile...
09-14 09:29:27.806  3891  3891 D BluetoothMapService: start()
09-14 09:29:27.808  3891  3891 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-14 09:29:27.808  3891  3891 D BluetoothMapEmailAppObserver: createReceiver()
09-14 09:29:27.809  3891  3891 D BluetoothMapEmailAppObserver: initObservers()
09-14 09:29:27.809  3891  3891 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-14 09:29:27.809  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:27.812  3891  3891 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-14 09:29:27.814  3891  3891 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-14 09:29:27.817  3891  3891 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-14 09:29:27.817  3891  3891 V PanService: [BTUI] SIM Extra State :ABSENT
09-14 09:29:27.819  3891  3891 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-14 09:29:27.822  3891  3891 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-14 09:29:27.822  3891  3891 V BluetoothMapService: Handler(): got msg=1
,09-14 09:29:27.823  3891  3970 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,09-14 09:29:27.823  3891  3970 I bluedroid-qcom: enable
09-14 09:29:27.823  3891  7260 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-14 09:29:27.823  3891  7260 I bt-btu  : btu_task pending for preload complete event
09-14 09:29:27.824  3891  3970 I bt_hci_bdroid: init
09-14 09:29:27.825  3891  3970 I bt_vendor: bt-vendor : init
09-14 09:29:27.825  3891  3970 I bt_vendor: bt-vendor : get_bt_soc_type
09-14 09:29:27.825  3891  3970 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-14 09:29:27.825  3891  3970 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-14 09:29:27.825  3891  3970 D bt_userial_mct: userial_init
09-14 09:29:27.825  3891  3970 D bt_hci_bdroid: set_power 1
09-14 09:29:27.825  3891  3970 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-14 09:29:27.825  3891  3970 I bt_vendor: Starting hciattach daemon
09-14 09:29:27.825  3891  3970 I bt_vendor: try to set true
09-14 09:29:27.826  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:27.812  7263  7263 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:27.812  7263  7263 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:27.828  3891  3891 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-14 09:29:27.828  3891  3891 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-14 09:29:27.828  3891  3891 V BluetoothSapReceiver: SapReceiver onReceive 
09-14 09:29:27.828  3891  3891 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:27.828  3891  3891 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-14 09:29:27.835  7232  7232 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-14 09:29:27.849  7264  7264 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-14 09:29:27.872  7232  7232 D LgDataFeature: LgDataFeature() Constructor: none
09-14 09:29:27.873  7232  7232 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-14 09:29:27.926  7276  7276 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-14 09:29:27.938  7277  7277 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-14 09:29:27.958  7279  7279 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-14 09:29:27.968  7280  7280 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-14 09:29:27.977  7281  7281 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-14 09:29:27.981  1034  1056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:27.981  1034  1056 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@18ebe844 mBinding = false
09-14 09:29:27.981  1034  1116 D BluetoothManagerService: Message: 1
09-14 09:29:27.981  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@18ebe844
,09-14 09:29:27.983  3891  4201 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-14 09:29:27.983  1034  1116 E BluetoothManagerService: IBluetooth.enable() returned false
09-14 09:29:27.989  7282  7282 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-14 09:29:28.007  7232  7232 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
09-14 09:29:28.008  7284  7284 I libmdmdetect: ESOC framework not supported
09-14 09:29:28.008  7284  7284 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-14 09:29:28.020  7284  7284 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-14 09:29:28.020  7284  7284 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,09-14 09:29:28.020  7284  7284 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-14 09:29:28.020  7284  7284 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-14 09:29:28.020  7284  7284 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-14 09:29:28.020  7284  7284 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-14 09:29:28.020  7284  7284 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-14 09:29:28.037  3426  3426 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-14 09:29:28.037  3426  3426 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:28.037  3426  3426 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-14 09:29:28.038  7232  7232 I HubEmail: JNI_OnLoad()
09-14 09:29:28.038  7232  7232 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-14 09:29:28.038  7232  7232 I HubEmail: registerNatives()
09-14 09:29:28.038  7232  7232 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-14 09:29:28.038  7232  7232 I HubEmail: registerNativeMethods()
09-14 09:29:28.038  7232  7232 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-14 09:29:28.038  7232  7232 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-14 09:29:28.056  7284  7285 E QC-QMI  : qmi_client [7284] 14: failed to locate client data
,09-14 09:29:28.058   485   485 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-14 09:29:28.058   485   485 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-14 09:29:28.080   303  7292 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-14 09:29:28.080   303  7292 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
09-14 09:29:28.091  1034  1916 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7293 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-14 09:29:28.094  7232  7290 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:28.116  7308  7308 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-14 09:29:28.128  7311  7311 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-14 09:29:28.132   303  7292 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
09-14 09:29:28.179  3891  3970 I bt_vendor: bluetooth satus is on
09-14 09:29:28.179  3891  3970 D bt_hci_bdroid: preload
09-14 09:29:28.179  3891  7262 D bt_userial_mct: userial_open(port:0)
09-14 09:29:28.179  3891  7262 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-14 09:29:28.180  3891  7262 I bt_vendor: Done intiailizing UART
09-14 09:29:28.181  3891  7262 I bt_vendor: Done intiailizing UART
09-14 09:29:28.181  3891  7262 I bt_userial_mct: CMD=82, EVT=82, ACL_Out=83, ACL_In=83
09-14 09:29:28.182  3891  7262 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-14 09:29:28.182  3891  7313 D bt_userial_mct: Entering userial_read_thread()
09-14 09:29:28.182  3891  7260 I bt-btu  : btu_task received preload complete event
09-14 09:29:28.183  3891  7260 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-14 09:29:28.183  3891  7260 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-14 09:29:28.183  3891  7260 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_HCI
09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_AVDT
09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_AVRC
09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_A2D
09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_BTM
09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_GAP
09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_PAN
09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_SDP
09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_GATT
09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_SMP
09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-14 09:29:28.186  3891  7260 I         : BTE_InitTraceLevels -- TRC_BTIF
09-14 09:29:28.191  7036  7289 V FormManager: There are no updated forms. The schedule will be deleted.
09-14 09:29:28.194  7036  7289 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-14 09:29:28.212  7293  7293 D LgDataFeature: LgDataFeature() Constructor: none
09-14 09:29:28.212  7293  7293 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-14 09:29:28.223  3891  7260 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-14 09:29:28.223  3891  7260 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0184061 
09-14 09:29:28.223  3891  7260 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0184061 
09-14 09:29:28.225  1034  1888 I ActivityManager: Killing 6192:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-14 09:29:28.229  7293  7293 D PhoneMonitor: Register our PhoneStateListener
09-14 09:29:28.231  3891  3981 E bt-btif : Calling BTA_HhEnable
09-14 09:29:28.231  3891  3981 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-14 09:29:28.231  3891  3981 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-14 09:29:28.231  3891  7260 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-14 09:29:28.232  3891  7260 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-14 09:29:28.232  3891  7260 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-14 09:29:28.232  3891  7260 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-14 09:29:28.232  3891  7260 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-14 09:29:28.238  3891  7260 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,09-14 09:29:28.238  3891  7260 W bt-smp  : Plain text(LSB ~ MSB) = 32 f9 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-14 09:29:28.238  3891  7260 W bt-smp  : Encrypted text(LSB ~ MSB) = 37 a1 f4 6f db 5d 31 88 0a f6 75 21 27 c6 7a c4 
09-14 09:29:28.238  3891  7260 W bt-btm  : Stopping oneshot timer
09-14 09:29:28.263  3891  3981 D BluetoothAdapterProperties: Name is: G3
09-14 09:29:28.263  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,09-14 09:29:28.263  1034  1935 W libprocessgroup: failed to open /acct/uid_10080/pid_6192/cgroup.procs: No such file or directory
09-14 09:29:28.263  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
09-14 09:29:28.267  3891  3981 D BluetoothAdapterProperties: Scan Mode:20
09-14 09:29:28.267  3891  3981 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 09:29:28.267  3891  3981 D bt_hci_bdroid: postload
09-14 09:29:28.268  3891  7260 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-14 09:29:28.268  3891  3981 D bte_conf: Device ID record 1 : primary
09-14 09:29:28.268  3891  3981 D bte_conf:   vendorId            = 00c4
09-14 09:29:28.268  3891  3981 D bte_conf:   vendorIdSource      = 0001
09-14 09:29:28.268  3891  3981 D bte_conf:   product             = 13a1
09-14 09:29:28.268  3891  3981 D bte_conf:   version             = 1000
09-14 09:29:28.268  3891  3981 D bte_conf:   clientExecutableURL = 
09-14 09:29:28.268  3891  3981 D bte_conf:   serviceDescription  = 
09-14 09:29:28.268  3891  3981 D bte_conf:   documentationURL    = 
09-14 09:29:28.268  3891  3981 D bte_conf: bte_load_did_conf no section named DID2.
09-14 09:29:28.269  3891  7262 D bt_hci_bdroid: Used up Tx Cmd credits
09-14 09:29:28.269  3891  7262 D bt_hci_bdroid: Used up Tx Cmd credits
09-14 09:29:28.269  3891  7262 D bt_hci_bdroid: Used up Tx Cmd credits
09-14 09:29:28.269  3891  7262 D bt_hci_bdroid: Used up Tx Cmd credits
09-14 09:29:28.269  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:28.269  3891  7313 E bt_mct  : hci lib postload completed
09-14 09:29:28.272  3891  3970 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-14 09:29:28.272  3891  3970 D BluetoothAdapterProperties: ScanMode =  20
09-14 09:29:28.272  3891  3970 D BluetoothAdapterProperties: State =  11
09-14 09:29:28.272  3891  3970 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-14 09:29:28.272  3891  3970 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-14 09:29:28.272  3891  3970 D BluetoothAdapterProperties: Setting state to 12
09-14 09:29:28.272  3891  3970 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-14 09:29:28.273  3891  3981 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-14 09:29:28.273  3891  3981 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-14 09:29:28.273  1034  1116 D BluetoothManagerService: Message: 60
,09-14 09:29:28.274  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-14 09:29:28.274  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-14 09:29:28.275  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:29:28.262  7315  7315 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:28.262  7315  7315 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-14 09:29:28.284  3891  3970 I BluetoothAdapterState: Entering On State
09-14 09:29:28.286  3891  3970 D LGBluetoothServiceAdapter: [BTUI] OnState
09-14 09:29:28.286  3891  3970 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-14 09:29:28.286  3891  3970 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-14 09:29:28.287  3891  3970 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-14 09:29:28.288  6993  7008 D BluetoothMap: onBluetoothStateChange: up=true
09-14 09:29:28.294  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 09:29:28.294  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:28.294  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:28.294  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:28.294  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:28.294  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:28.294  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:28.294  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:28.294  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 09:29:28.300  1836  2457 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 09:29:28.304  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:28.306  6993  6993 D BluetoothMap: Proxy object connected
09-14 09:29:28.306  6993  6993 D MapProfile: Bluetooth service connected
09-14 09:29:28.306  6993  6993 D BluetoothMap: getConnectedDevices()
09-14 09:29:28.307  1034  1034 D BluetoothA2dp: Proxy object connected
,09-14 09:29:28.310  1836  1836 D BluetoothHeadset: Proxy object connected
09-14 09:29:28.315  3891  3981 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 09:29:28.315  3891  3981 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,09-14 09:29:28.322  1836  2457 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 09:29:28.322  3891  3910 V BluetoothMapService: getConnectedDevices()
,09-14 09:29:28.325  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 09:29:28.325  1836  1836 D BluetoothHeadset: Proxy object connected
09-14 09:29:28.326  6993  7008 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 09:29:28.328  6993  7009 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-14 09:29:28.329  1034  1034 D BluetoothHeadset: Proxy object connected
09-14 09:29:28.330  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 09:29:28.332  6993  6993 D BluetoothInputDevice: Proxy object connected
09-14 09:29:28.332  6993  6993 D HidProfile: Bluetooth service connected
09-14 09:29:28.332  7293  7293 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-14 09:29:28.333  1836  1836 D BluetoothHeadset: Proxy object connected
09-14 09:29:28.333  6993  7009 D BluetoothPan: onBluetoothStateChange on: true
09-14 09:29:28.333  6993  7009 D BluetoothPan: onBluetoothStateChange call bindService
09-14 09:29:28.334  3891  3970 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-14 09:29:28.338  6993  6993 D BluetoothPan: BluetoothPAN Proxy object connected
09-14 09:29:28.338  6993  6993 D PanProfile: Bluetooth service connected
09-14 09:29:28.339  1034  1116 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-14 09:29:28.339  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-14 09:29:28.342  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-14 09:29:28.343  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:28.343  7322  7322 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-14 09:29:28.344  1924  2105 D LGBluetoothAPIService: Message: 1
09-14 09:29:28.344  1924  2105 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-14 09:29:28.351  6858  6858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,09-14 09:29:28.355  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:28.355  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:28.355  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:28.355  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:28.355  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:28.355  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:28.355  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:28.355  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:28.358  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:28.360  3891  3891 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:28.360  3891  3891 D BluetoothMapService: STATE_ON
09-14 09:29:28.361  3891  3891 D LGBluetoothAPIServer: [BTUI] onCreate()
09-14 09:29:28.361  3891  3891 D LGBluetoothAPIServer: [BTUI] onBind()
09-14 09:29:28.362  1924  2105 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-14 09:29:28.362  7293  7293 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-14 09:29:28.363  3891  3891 V BluetoothMapService: Handler(): got msg=1
,09-14 09:29:28.363  3891  3891 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-14 09:29:28.365  1924  1924 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-14 09:29:28.365  1924  2105 D LGBluetoothAPIService: Message: 100
09-14 09:29:28.365  1924  2105 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-14 09:29:28.366  6993  6993 D LocalBluetoothProfileManager: Adding local A2DP profile
09-14 09:29:28.366  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:28.366  3891  3891 V BluetoothPbapService: Pbap Service onCreate
09-14 09:29:28.366  3891  3891 V BluetoothPbapService: Starting PBAP service
09-14 09:29:28.367  3891  3891 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-14 09:29:28.367  3891  3891 V BluetoothPbapService: Pbap Service onBind
09-14 09:29:28.368  3891  7327 D BluetoothMapMasInstance: MAS initSocket()
09-14 09:29:28.368  3891  7327 D BluetoothMapMasInstance:   masId = 00
09-14 09:29:28.368  3891  7327 D BluetoothMapMasInstance:   msgTypes = 0e
09-14 09:29:28.368  3891  7327 D BluetoothMapMasInstance:   masName = SMS/MMS
09-14 09:29:28.368  3891  7327 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-14 09:29:28.369  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:28.369  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:28.369  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:28.369  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:28.369  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:28.369  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:28.369  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:28.369  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:28.372  1034  1116 D BluetoothManagerService: Message: 30
09-14 09:29:28.372  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:28.374  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:29:28.387  7293  7293 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-14 09:29:28.388  7293  7293 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-14 09:29:28.388  7293  7293 D TelephonyAutoProfiling: [parse] Load xml
09-14 09:29:28.393  7293  7293 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-14 09:29:28.394  7293  7293 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-14 09:29:28.394  7293  7293 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-14 09:29:28.394  7293  7293 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-14 09:29:28.394  7293  7293 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-14 09:29:28.394  7293  7293 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-14 09:29:28.394  7293  7293 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-14 09:29:28.394  7293  7293 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-14 09:29:28.394  7293  7293 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-14 09:29:28.394  7293  7293 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-14 09:29:28.394  7293  7293 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-14 09:29:28.394  7293  7293 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-14 09:29:28.394  7293  7293 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-14 09:29:28.394  7293  7293 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-14 09:29:28.394  7293  7293 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-14 09:29:28.394  7293  7293 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-14 09:29:28.394  7293  7293 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-14 09:29:28.400  7293  7293 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-14 09:29:28.415  1034  2001 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7331 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-14 09:29:28.418  1034  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:28.419  3891  3891 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:28.419  3891  3891 V BluetoothPbapService: state: 12
09-14 09:29:28.420  3891  3891 V BluetoothPbapService: Handler(): got msg=1
09-14 09:29:28.420  3891  3891 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-14 09:29:28.422  6993  6993 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-14 09:29:28.422  3891  7327 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 09:29:28.423  3891  7327 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=87 mFd=82
09-14 09:29:28.423  3891  7327 V BluetoothMapMasInstance: Succeed to create listening socket 
09-14 09:29:28.423  3891  7327 D BluetoothMapMasInstance: Accepting socket connection...
09-14 09:29:28.425  3891  7340 V BluetoothPbapService: Pbap Service initSocket
,09-14 09:29:28.426  1034  1116 D BluetoothManagerService: Message: 30
09-14 09:29:28.426  3891  3981 D BluetoothAdapterProperties: Scan Mode:21
09-14 09:29:28.426  3891  3981 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-14 09:29:28.426  1034  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:28.429  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:29:28.431  3891  7340 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 09:29:28.433  3891  7340 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=89 mFd=87
09-14 09:29:28.433  3891  7340 V BluetoothPbapService: Succeed to create listening socket 
09-14 09:29:28.433  3891  7340 V BluetoothPbapService: Accepting socket connection...
09-14 09:29:28.434  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:28.443  6993  6993 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,09-14 09:29:28.444  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:28.445  6993  6993 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-14 09:29:28.448  6993  6993 D BluetoothA2dp: Proxy object connected
09-14 09:29:28.449  6993  6993 D A2dpProfile: Bluetooth service connected
,09-14 09:29:28.451  3891  3891 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-14 09:29:28.451  3891  3891 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:28.451  3891  3891 V BluetoothPbapReceiver: ***********state = 12
,09-14 09:29:28.452  6993  6993 D BluetoothPbap: Proxy object connected
09-14 09:29:28.453  6993  6993 D PbapServerProfile: Bluetooth service connected
09-14 09:29:28.453  6993  6993 D BluetoothHeadset: Proxy object connected
09-14 09:29:28.454  2063  2063 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-14 09:29:28.455  2063  2063 D c       : Getting all permits...
09-14 09:29:28.455  2063  2063 D a       : Opening database...
,09-14 09:29:28.456  6993  6993 D HeadsetProfile: Bluetooth service connected
09-14 09:29:28.460  2063  2063 D a       : Opening database auth.proximity.permit_store...
09-14 09:29:28.461  2063  2063 D a       : Closing database...
09-14 09:29:28.469  6993  6993 D DockEventReceiver: finishStartingService: stopping service
,09-14 09:29:28.478  6993  6993 D BluetoothPermissionRequest: onReceive
09-14 09:29:28.480  6993  6993 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-14 09:29:28.482  6993  6993 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-14 09:29:28.484  1034  1943 I ActivityManager: Killing 6654:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-14 09:29:28.484  6858  7148 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:28.486  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:28.486  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:28.554  1034  1916 W libprocessgroup: failed to open /acct/uid_10061/pid_6654/cgroup.procs: No such file or directory
09-14 09:29:28.555  3891  3891 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,09-14 09:29:28.561  3891  3891 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-14 09:29:28.561  1034  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:28.561  1034  1888 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@18ebe844 mBinding = false
09-14 09:29:28.566  3891  3891 V BtOppService: onCreate
09-14 09:29:28.566  3891  3891 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-14 09:29:28.568  3891  3891 V BluetoothOppNotification: send message
09-14 09:29:28.575  3891  3891 V BtOppService: Starting RfcommListener
09-14 09:29:28.575  3891  3891 D BluetoothOppPreference: Dumping Names:  
09-14 09:29:28.575  3891  3891 D BluetoothOppPreference: {}
09-14 09:29:28.575  3891  3891 D BluetoothOppPreference: Dumping Channels:  
09-14 09:29:28.575  3891  3891 D BluetoothOppPreference: {}
09-14 09:29:28.575  3891  7352 V BtOppService: Deleted complete outbound shares, number =  0
09-14 09:29:28.575  3891  3891 V BtOppService: onStartCommand
09-14 09:29:28.578  3891  7352 V BtOppService: Deleted complete inbound failed shares, number = 0
09-14 09:29:28.578  3891  7353 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-14 09:29:28.578  3891  3891 V BluetoothOppNotification: new notify threadi!
,09-14 09:29:28.578  1034  1116 D BluetoothManagerService: Message: 2
09-14 09:29:28.579  3891  3891 V BluetoothOppNotification: send delay message
09-14 09:29:28.579  3891  7352 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-14 09:29:28.580  1034  1116 D BluetoothManagerService: Sending off request.
09-14 09:29:28.580  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-14 09:29:28.580  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-14 09:29:28.580  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-14 09:29:28.584  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:28.584  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-14 09:29:28.584  3891  7352 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ff836e1 on behalf of 
09-14 09:29:28.585  3891  7318 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-14 09:29:28.585  3891  3970 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-14 09:29:28.585  3891  3970 D BluetoothAdapterProperties: Setting state to 13
09-14 09:29:28.586  3891  3970 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-14 09:29:28.586  1034  1116 D BluetoothManagerService: Message: 60
09-14 09:29:28.586  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-14 09:29:28.586  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-14 09:29:28.586  3891  3970 D BluetoothAdapterProperties: onBluetoothDisable()
09-14 09:29:28.586  3891  3891 V BtOppService: ContentObserver received notification
09-14 09:29:28.586  3891  3970 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-14 09:29:28.588  3891  3891 V BtOppService: ContentObserver received notification
09-14 09:29:28.589  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-14 09:29:28.590  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:28.591  3891  3981 D BluetoothAdapterProperties: Scan Mode:20
09-14 09:29:28.591  3891  3970 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-14 09:29:28.592  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-14 09:29:28.592  3891  7260 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-14 09:29:28.593  3891  3970 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-14 09:29:28.593  3891  7327 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-14 09:29:28.593  3891  7327 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-14 09:29:28.593  3891  7327 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-14 09:29:28.593  3891  7327 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-14 09:29:28.593  3891  7327 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-14 09:29:28.593  3891  7327 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-14 09:29:28.593  3891  7327 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-14 09:29:28.593  3891  7327 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-14 09:29:28.593  3891  7340 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-14 09:29:28.594  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:28.594  3891  3891 V BluetoothFtpService: Ftp Service onCreate
09-14 09:29:28.594  3891  3891 I BluetoothFtpService: Ftp Service onCreate
09-14 09:29:28.594  3891  3891 V BluetoothFtpService: Ftp Service onStartCommand
09-14 09:29:28.594  3891  3891 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-14 09:29:28.594  3891  3891 V BluetoothFtpService: Starting Listening on sockets
09-14 09:29:28.595  3891  3891 V BluetoothFtpService: Handler(): got msg=1
09-14 09:29:28.597  3891  3891 V BluetoothFtpService: Ftp Service closeService
09-14 09:29:28.598  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:28.598  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:28.598  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:28.598  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:28.598  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:28.598  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 09:29:28.598  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:28.598  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:28.598  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:28.598  3891  7353 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-14 09:29:28.599  3891  3891 V BluetoothFtpService: successfully stopped ftp service
09-14 09:29:28.599  3891  3891 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:28.599  3891  3891 D BluetoothMapService: STATE_TURNING_OFF
09-14 09:29:28.599  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:28.599  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:28.599  3891  3891 V BtOppService: Receiver DISABLED_ACTION 
09-14 09:29:28.600  3891  3891 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-14 09:29:28.600  3891  3891 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-14 09:29:28.600  3891  3891 V BluetoothSapReceiver: SapReceiver onReceive 
09-14 09:29:28.600  3891  3891 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:28.600  3891  3891 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-14 09:29:28.601  3891  3891 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-14 09:29:28.602  3891  3891 V BluetoothMapService: Handler(): got msg=4
09-14 09:29:28.602  3891  3891 D BluetoothMapService: MAP Service closeService in
09-14 09:29:28.602  3891  3891 D BluetoothMapMasInstance: MAP Service shutdown
09-14 09:29:28.604  3891  3891 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-14 09:29:28.604  3891  3891 V BluetoothMapService: MAP Service closeService out
09-14 09:29:28.604  3891  3891 V BluetoothFtpService: Ftp Service onDestroy
09-14 09:29:28.604  3891  3891 V BluetoothFtpService: Ftp Service closeService
09-14 09:29:28.604  3891  7355 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-14 09:29:28.604  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-14 09:29:28.604  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-14 09:29:28.605  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-14 09:29:28.605  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-14 09:29:,28.605  3891  7260 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 09:29:28.605  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-14 09:29:28.605  3891  7260 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 09:29:28.605  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:28.605  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-14 09:29:28.605  3891  7260 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-14 09:29:28.605  3891  3891 V BluetoothSapService: Sap Service onCreate
09-14 09:29:28.605  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-14 09:29:28.605  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-14 09:29:28.605  3891  7260 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-14 09:29:28.605  6993  6993 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-14 09:29:28.606  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:28.606  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:28.606  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:28.606  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:28.606  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:28.606  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 09:29:28.606  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:28.606  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:28.606  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:28.607  3891  3891 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:28.607  3891  3891 V BluetoothSapService: state: 12
09-14 09:29:28.607  3891  3891 V BluetoothSapService: Starting SAP server process
,09-14 09:29:28.592  7356  7356 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:28.592  7356  7356 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:28.612  6858  6858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:28.613  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:28.613  3891  7355 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18ef463 on behalf of 
09-14 09:29:28.614  3891  7355 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-14 09:29:28.615  3891  7353 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fe66860 on behalf of 
09-14 09:29:28.617  7356  7356 V BT_SAP  : Event pipe created
09-14 09:29:28.617  7356  7356 V BT_SAP  : create_server_socket qcom.sap.server
09-14 09:29:28.617  7356  7356 V BT_SAP  : created socket fd 6
09-14 09:29:28.620  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:29:28.622  3891  7353 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is false
09-14 09:29:28.622  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:29:28.622  3891  7353 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-14 09:29:28.622  3891  7355 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-14 09:29:28.630  3891  7353 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2327e119 on behalf of 
09-14 09:29:28.630  3891  7353 V BluetoothOppNotification: update too frequent, put in queue
09-14 09:29:28.632  3891  7355 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10e6a5de on behalf of 
09-14 09:29:28.632  3891  7355 V BluetoothOppNotification: outbound: succ-0  fail-0
09-14 09:29:28.638  3891  7353 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is false
09-14 09:29:28.640  3891  7355 V BluetoothOppNotification: outbound notification was removed.
09-14 09:29:28.640  3891  7355 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-14 09:29:28.641  3891  7355 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@207273bf on behalf of 
,09-14 09:29:28.641  3891  7355 V BluetoothOppNotification: inbound: succ-0  fail-0
09-14 09:29:28.643  3891  7355 V BluetoothOppNotification: inbound notification was removed.
09-14 09:29:28.643  3891  7355 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-14 09:29:28.644  3891  7355 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34b9aa8c on behalf of 
09-14 09:29:28.675  1034  1993 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7357 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-14 09:29:28.676  1034  1993 I ActivityManager: Killing 6212:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-14 09:29:28.715  1034  1888 I art     : Explicit concurrent mark sweep GC freed 102759(4MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.742ms total 105.142ms
,09-14 09:29:28.740  1034  1056 W libprocessgroup: failed to open /acct/uid_10097/pid_6212/cgroup.procs: No such file or directory
09-14 09:29:28.740  3891  3891 V BtOppService: onDestroy
,09-14 09:29:28.746  3891  3891 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,09-14 09:29:28.752  6993  6993 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-14 09:29:28.756  3891  3891 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-14 09:29:28.756  3891  3891 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:28.756  3891  3891 V BluetoothPbapReceiver: ***********state = 13
09-14 09:29:28.757  3891  3891 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-14 09:29:28.757  6993  6993 D DockEventReceiver: finishStartingService: stopping service
09-14 09:29:28.758  1801  7375 I CheckinService: active receiver: enabled
09-14 09:29:28.758  3891  3891 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:28.758  3891  3891 V BluetoothPbapService: state: 13
09-14 09:29:28.758  3891  3891 V BluetoothPbapService: Pbap Service closeService in
09-14 09:29:28.761  6993  6993 D BluetoothPbap: Proxy object disconnected
09-14 09:29:28.761  6993  6993 D PbapServerProfile: Bluetooth service disconnected
09-14 09:29:28.761  3891  3891 V BluetoothPbapService: successfully stopped pbap service
,09-14 09:29:28.761  3891  3891 V BluetoothPbapService: Pbap Service closeService out
09-14 09:29:28.762  3891  3891 V BluetoothPbapService: Pbap Service onDestroy
09-14 09:29:28.762  3891  3891 V BluetoothPbapService: Pbap Service closeService in
09-14 09:29:28.762  3891  3891 V BluetoothPbapService: Pbap Service closeService out
09-14 09:29:28.762  3891  3891 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-14 09:29:28.767  1801  7375 I CheckinService: Preparing to send checkin request
09-14 09:29:28.767  1801  7375 I EventLogService: Accumulating logs since 1473838032511
09-14 09:29:28.768  2063  2063 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 09:29:28.778  6993  6993 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-14 09:29:28.817  1034  1993 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7378 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-14 09:29:28.820  6993  6993 D BluetoothPermissionRequest: onReceive
09-14 09:29:28.820  6993  6993 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-14 09:29:28.821  1801  7375 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-14 09:29:28.827  6993  6993 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-14 09:29:28.828  1034  2001 I ActivityManager: Killing 6727:com.lge.eula/1000 (adj 15): empty #17
09-14 09:29:28.874  3891  3891 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-14 09:29:28.874  3891  3891 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-14 09:29:28.875  3891  3891 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-14 09:29:28.875  1034  1057 W libprocessgroup: failed to open /acct/uid_1000/pid_6727/cgroup.procs: No such file or directory
,09-14 09:29:28.890  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:28.890  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-14 09:29:28.894  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:28.895  3891  3891 V BluetoothFtpService: Ftp Service onCreate
09-14 09:29:28.895  3891  3891 I BluetoothFtpService: Ftp Service onCreate
09-14 09:29:28.895  3891  3891 V BluetoothFtpService: Ftp Service onStartCommand
09-14 09:29:28.895  3891  3891 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:28.895  3891  3891 V BluetoothFtpService: Ftp Service closeService
09-14 09:29:28.896  3891  3891 V BluetoothFtpService: successfully stopped ftp service
09-14 09:29:28.896  3891  3891 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-14 09:29:28.897  3891  3891 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-14 09:29:28.897  3891  3891 V BluetoothSapReceiver: SapReceiver onReceive 
09-14 09:29:28.897  3891  3891 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:28.897  3891  3891 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-14 09:29:28.897  3891  3891 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-14 09:29:28.899  3891  3891 V BluetoothFtpService: Ftp Service onDestroy
09-14 09:29:28.899  3891  3891 V BluetoothFtpService: Ftp Service closeService
,09-14 09:29:28.909  3891  3891 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:28.909  3891  3891 V BluetoothSapService: state: 13
09-14 09:29:28.909  3891  3891 V BluetoothSapService: Stopping SAP server process
09-14 09:29:28.910  3891  3891 V BluetoothSapService: Sap Service closeSapService in
09-14 09:29:28.911  3891  3891 V BluetoothSapService: Close listen Socket : 
09-14 09:29:28.911  3891  3891 V BluetoothSapService: Close rfcomm Socket : 
09-14 09:29:28.911  3891  3891 V BluetoothSapService: Close sapd  Socket : 
09-14 09:29:28.913  3891  3891 V BluetoothSapService: Sap Service closeSapService out
,09-14 09:29:28.914  7378  7378 I art     : Almond Protected OAT
09-14 09:29:28.914  3891  3891 V BluetoothSapService: Sap Service onDestroy
09-14 09:29:28.914  3891  3891 V BluetoothSapService: Sap Service closeSapService in
09-14 09:29:28.914  3891  3891 V BluetoothSapService: Close listen Socket : 
09-14 09:29:28.915  3891  3891 V BluetoothSapService: Close rfcomm Socket : 
09-14 09:29:28.915  3891  3891 V BluetoothSapService: Close sapd  Socket : 
09-14 09:29:28.918  3891  3891 V BluetoothSapService: Sap Service closeSapService out
09-14 09:29:28.964  7378  7378 D WeatherApplication: removeAccount
09-14 09:29:28.965  7378  7378 D WeatherApplication: Account.length = 0
,09-14 09:29:28.965  7378  7378 E WeatherApplication: OPERATOR:OPEN
,09-14 09:29:28.969  7378  7378 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:29:28
09-14 09:29:28.972  7378  7378 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-14 09:29:28.972  7378  7378 D Weather.Utils: 2 : All the weather widget is gone.
09-14 09:29:28.974  7378  7378 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-14 09:29:28.975  7378  7378 D WeatherAncestor: connectivity changed - connection : true
09-14 09:29:28.976  7378  7378 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,09-14 09:29:28.982  1034  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-14 09:29:28.982  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:28.982  1034  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:28.982  7378  7378 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-14 09:29:28.982  7378  7378 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-14 09:29:28.983  7378  7378 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,09-14 09:29:28.997  7378  7378 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-14 09:29:28.997  7378  7378 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:29:28
09-14 09:29:29.009  1034  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-14 09:29:29.010  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-14 09:29:29.011  1034  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-14 09:29:29.013  1034  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-14 09:29:29.014  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-14 09:29:29.015  1034  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-14 09:29:29.024  1034  1587 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7396 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
09-14 09:29:29.076  1034  1916 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7413 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-14 09:29:29.077  1034  1993 I ActivityManager: Killing 2157:com.lge.music/u0a34 (adj 15): empty #17
09-14 09:29:29.081  6858  7351 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:29.081  6858  7351 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:29.081  6858  7351 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:29.081  6858  7351 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:29.081  6858  7351 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:29.081  6858  7351 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 09:29:29.081  6858  7351 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:29.081  6858  7351 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:29.081  6858  7351 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:29.081  6858  7351 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:29:29.081  6858  7351 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:29.087  6858  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:29.098   308  1369 V AudioFlinger: 2157 died, releasing its sessions
09-14 09:29:29.098   308  1369 V AudioFlinger:  pid 1836 @ 0
09-14 09:29:29.098   308  1369 V AudioFlinger:  pid 3426 @ 1
09-14 09:29:29.098   308  1369 V AudioFlinger:  pid 3426 @ 2
,09-14 09:29:29.108   332   332 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 500us total 31.689ms
09-14 09:29:29.127   332   332 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 400us total 18.649ms
,09-14 09:29:29.146   332   332 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 401us total 18.712ms
,09-14 09:29:29.154  1034  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:29.154  1034  1942 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@18ebe844 mBinding = false
,09-14 09:29:29.154  1034  1057 W libprocessgroup: failed to open /acct/uid_10034/pid_2157/cgroup.procs: No such file or directory
,09-14 09:29:29.167  1034  1116 D BluetoothManagerService: Message: 1
09-14 09:29:29.167  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@18ebe844
09-14 09:29:29.168  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-14 09:29:29.168  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-14 09:29:29.168  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-14 09:29:29.170  3891  7318 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-14 09:29:29.170  1034  1116 E BluetoothManagerService: IBluetooth.enable() returned false
09-14 09:29:29.182  7396  7396 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-14 09:29:29.183  7396  7396 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-14 09:29:29.223  7396  7396 I MultiDex: VM with version 2.1.0 has multidex support
09-14 09:29:29.223  7396  7396 I MultiDex: install
09-14 09:29:29.223  7396  7396 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-14 09:29:29.237  7396  7396 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,09-14 09:29:29.286   278   465 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-14 09:29:29.286   278   465 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-14 09:29:29.286   278   465 W Vold    : Returning OperationFailed - no handler for errno 0
09-14 09:29:29.286  7413  7436 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-14 09:29:29.288   278   465 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-14 09:29:29.288   278   465 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-14 09:29:29.288   278   465 W Vold    : Returning OperationFailed - no handler for errno 0
,09-14 09:29:29.289  7413  7436 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-14 09:29:29.297   278   465 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-14 09:29:29.297   278   465 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-14 09:29:29.297   278   465 W Vold    : Returning OperationFailed - no handler for errno 0
09-14 09:29:29.298  7413  7439 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-14 09:29:29.300   278   465 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-14 09:29:29.300   278   465 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-14 09:29:29.300   278   465 W Vold    : Returning OperationFailed - no handler for errno 0
09-14 09:29:29.300  7413  7439 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-14 09:29:29.427  1034  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-59 f=2437 sc=60 link=72 tx=75.0, 0.0, 0.0  rx=81.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:664386899] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-14 09:29:29.427  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-59 f=2437 sc=60 link=72 tx=75.0, 0.0, 0.0  rx=81.5 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:664386899] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-14 09:29:29.427  1034  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-14 09:29:29.442  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-14 09:29:29.476  1034  1524 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-14 09:29:29.495  7413  7413 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-14 09:29:29.501  7413  7413 I LibraryLoader: Loading: webviewchromium
09-14 09:29:29.501  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:29.503  7413  7413 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5509-5511)
09-14 09:29:29.503  1034  1116 D Tethering: MasterInitialState.processMessage what=3
09-14 09:29:29.503  7413  7413 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-14 09:29:29.503  1034  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:29.508  5836  5836 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-14 09:29:29.511  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:29.513  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:29.516  7413  7413 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {202e4e41}
09-14 09:29:29.517  7413  7413 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-14 09:29:29.517  7413  7413 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-14 09:29:29.523  1034  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-14 09:29:29.524  7413  7413 I BrowserStartupController: Initializing chromium process, renderers=0
09-14 09:29:29.524  7413  7413 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-14 09:29:29.532  7413  7413 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-14 09:29:29.533  7413  7413 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-14 09:29:29.533  7413  7413 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-14 09:29:29.535   308  1370 V AudioPolicyService: registerClient() client 0xb1427800, uid 10093
09-14 09:29:29.536  7413  7463 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-14 09:29:29.546  7413  7413 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-14 09:29:29.546  7413  7413 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-14 09:29:29.546  7413  7413 I Adreno-EGL: Build Date: 12/12/14 금
09-14 09:29:29.546  7413  7413 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-14 09:29:29.546  7413  7413 I Adreno-EGL: Remote Branch: 
09-14 09:29:29.546  7413  7413 I Adreno-EGL: Local Patches: 
09-14 09:29:29.546  7413  7413 I Adreno-EGL: Reconstruct Branch: 
09-14 09:29:29.580  3891  3891 V BluetoothOppNotification: previous thread is not finished yet
,09-14 09:29:29.588  7413  7413 I NSApplication: Starting up...
09-14 09:29:29.609  3891  3981 D bt_hci_bdroid: cleanup
,09-14 09:29:29.609  3891  7262 I bt_lpm  : LPM is already off!!!
09-14 09:29:29.609  3891  7313 I bt_userial_mct: exiting userial_read_thread
09-14 09:29:29.609  3891  7313 D bt_userial_mct: Leaving userial_evt_read_thread()
09-14 09:29:29.609  3891  7260 W bt-btif : ag scb idx 1 not allocated
09-14 09:29:29.609  3891  7260 E bt-btif : BTA AG is already disabled, ignoring ...
09-14 09:29:29.609  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-14 09:29:29.609  3891  7260 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-14 09:29:29.610  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-14 09:29:29.610  3891  7260 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 09:29:29.611  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-14 09:29:29.611  3891  7260 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-14 09:29:29.611  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-14 09:29:29.611  3891  7260 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 09:29:29.611  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-14 09:29:29.611  3891  7260 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 09:29:29.611  3891  3981 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-14 09:29:29.611  3891  7262 I bt_vendor: hw_epilog_process
09-14 09:29:29.612  3891  3981 D bt_hci_bdroid: cleanup Finalizing cleanup
09-14 09:29:29.612  3891  3981 D bt_userial_mct: userial_close
09-14 09:29:29.612  3891  3981 E bt_userial_mct: pthread_join() FAILED result:3
09-14 09:29:29.612  3891  3981 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-14 09:29:29.612  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-14 09:29:29.612  3891  7260 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-14 09:29:29.612  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-14 09:29:29.612  3891  7260 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 09:29:29.612  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-14 09:29:29.612  3891  7260 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 09:29:29.612  3891  7260 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-14 09:29:29.613  3891  7260 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-14 09:29:29.613  3891  7260 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-14 09:29:29.641  1034  1056 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7477 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-14 09:29:29.643  1034  1056 I ActivityManager: Killing 6154:com.android.vending/u0a44 (adj 15): empty #17
09-14 09:29:29.732  3891  3981 D bt_hci_bdroid: set_power 0
09-14 09:29:29.732  3891  3981 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-14 09:29:29.732  3891  3981 I bt_vendor: bluetooth satus is on
09-14 09:29:29.732  3891  3981 I bt_vendor: bt-vendor : resetting BT status
09-14 09:29:29.732  3891  3981 I bt_vendor: Starting hciattach daemon
09-14 09:29:29.732  3891  3981 I bt_vendor: try to set false
,09-14 09:29:29.734  1034  2001 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:29.734  1034  2001 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@18ebe844 mBinding = false
09-14 09:29:29.734  1034  1970 W libprocessgroup: failed to open /acct/uid_10044/pid_6154/cgroup.procs: No such file or directory
09-14 09:29:29.735  1034  1116 D BluetoothManagerService: Message: 1
09-14 09:29:29.735  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@18ebe844
09-14 09:29:29.735  3891  3981 I bt_vendor: Starting hciattach daemon
09-14 09:29:29.735  3891  3981 I bt_vendor: try to set false
09-14 09:29:29.737  3891  3981 I bt_vendor: cleanup
,09-14 09:29:29.738  3891  7260 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-14 09:29:29.739  3891  3981 I GKI_LINUX: GKI_exit_task 0 done
09-14 09:29:29.739  3891  3981 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-14 09:29:29.740  3891  7318 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-14 09:29:29.740  1034  1116 E BluetoothManagerService: IBluetooth.enable() returned false
09-14 09:29:29.742  3891  3970 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-14 09:29:29.744  3891  3891 D HeadsetService: Received stop request...Stopping profile...
09-14 09:29:29.744  3891  3891 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-14 09:29:29.744  3891  3891 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-14 09:29:29.744  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:29.745  3891  7247 D HeadsetStateMachine: Exit Disconnected: -1
09-14 09:29:29.745  1034  1034 D BluetoothHeadset: Proxy object disconnected
09-14 09:29:29.745  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-14 09:29:29.746  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-14 09:29:29.746  3891  3891 D A2dpService: Received stop request...Stopping profile...
09-14 09:29:29.746  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-14 09:29:29.746  3891  7253 D A2dpStateMachine: Exit Disconnected: -1
09-14 09:29:29.746  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-14 09:29:29.747  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-14 09:29:29.751  3891  3891 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-14 09:29:29.751  3891  3891 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-14 09:29:29.751  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:29.752  1034  1034 D BluetoothA2dp: Proxy object disconnected
09-14 09:29:29.752  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-14 09:29:29.755  3891  3891 D HeadsetStateMachine: Unbinding service...
09-14 09:29:29.757  3891  3970 D BluetoothAdapterState: Stopping profile services that were post enabled
09-14 09:29:29.757  6993  6993 D BluetoothHeadset: Proxy object disconnected
09-14 09:29:29.757  6993  6993 D HeadsetProfile: Bluetooth service disconnected
09-14 09:29:29.757  6993  6993 D BluetoothA2dp: Proxy object disconnected
09-14 09:29:29.757  6993  6993 D A2dpProfile: Bluetooth service disconnected
09-14 09:29:29.761  3891  3891 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-14 09:29:29.761  3891  3891 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-14 09:29:29.761  3891  3891 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-14 09:29:29.761  3891  3891 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,09-14 09:29:29.761  3891  3891 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-14 09:29:29.761  3891  3891 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-14 09:29:29.761  3891  3891 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-14 09:29:29.761  3891  3891 D HidService: Received stop request...Stopping profile...
09-14 09:29:29.762  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:29.763  6993  6993 D BluetoothInputDevice: Proxy object disconnected
09-14 09:29:29.763  6993  6993 D HidProfile: Bluetooth service disconnected
09-14 09:29:29.763  3891  3891 D HealthService: Received stop request...Stopping profile...
09-14 09:29:29.763  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:29.765  3891  3891 D PanService: Received stop request...Stopping profile...
09-14 09:29:29.766  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:29.767  3891  3891 I BluetoothA2dpServiceJni: cleanupNative
,09-14 09:29:29.767  3891  7254 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-14 09:29:29.767  3891  3891 I GKI_LINUX: GKI_exit_task 2 done
09-14 09:29:29.767  3891  3891 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-14 09:29:29.768  3891  3891 D BtGatt.DebugUtils: handleDebugAction() action=null
09-14 09:29:29.768  3891  3891 D BtGatt.GattService: Received stop request...Stopping profile...
09-14 09:29:29.768  3891  3891 D BtGatt.GattService: stop()
09-14 09:29:29.768  3891  3891 D BtGatt.AdvertiseManager: advertise clients cleared
09-14 09:29:29.770  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:29.771  3891  3891 D BluetoothMapService: Received stop request...Stopping profile...
09-14 09:29:29.771  3891  3891 D BluetoothMapService: stop()
09-14 09:29:29.771  3891  3891 D BluetoothMapEmailAppObserver: deinitObservers()
09-14 09:29:29.771  3891  3891 D BluetoothMapEmailAppObserver: removeReceiver()
09-14 09:29:29.771  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:29.772  6993  6993 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-14 09:29:29.772  6993  6993 D PanProfile: Bluetooth service disconnected
09-14 09:29:29.772  3891  3891 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-14 09:29:29.772  3891  3891 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-14 09:29:29.772  6993  6993 D BluetoothMap: Proxy object disconnected
09-14 09:29:29.772  6993  6993 D MapProfile: Bluetooth service disconnected
09-14 09:29:29.772  3891  3891 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-14 09:29:29.772  3891  3891 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-14 09:29:29.772  3891  3891 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-14 09:29:29.773  3891  3891 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-14 09:29:29.773  3891  3891 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-14 09:29:29.773  3891  3891 V BluetoothMapService: Handler(): got msg=4
09-14 09:29:29.773  3891  3891 D BluetoothMapService: MAP Service closeService in
09-14 09:29:29.774  3891  3891 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-14 09:29:29.774  3891  3891 V BluetoothMapService: MAP Service closeService out
09-14 09:29:29.774  3891  3970 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-14 09:29:29.774  3891  3970 D BluetoothAdapterProperties: Setting state to 10
09-14 09:29:29.774  3891  3970 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-14 09:29:29.774  3891  3891 D BluetoothMapService: cleanup()
09-14 09:29:29.774  3891  3891 D BluetoothMapService: MAP Service closeService in
09-14 09:29:29.774  3891  3891 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-14 09:29:29.774  3891  3891 V BluetoothMapService: MAP Service closeService out
09-14 09:29:29.774  1034  1116 D BluetoothManagerService: Message: 60
09-14 09:29:29.774  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-14 09:29:29.774  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-14 09:29:29.774  3891  3970 I BluetoothAdapterState: Entering OffState
09-14 09:29:29.774  6993  7009 D BluetoothMap: onBluetoothStateChange: up=false
09-14 09:29:29.775  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 09:29:29.775  1836  3999 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:29:29.775  1836  4001 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:29:29.775  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:29:29.776  6993  7008 D BluetoothPbap: onBluetoothStateChange: up=false
09-14 09:29:29.776  6993  7009 D ,BluetoothHeadset: onBluetoothStateChange: up=false
,09-14 09:29:29.777  6993  7008 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-14 09:29:29.777  6993  7009 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 09:29:29.777  1836  4007 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:29:29.778  6993  7008 D BluetoothPan: onBluetoothStateChange on: false
09-14 09:29:29.778  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-14 09:29:29.779  7477  7477 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-14 09:29:29.780  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-14 09:29:29.781  6993  6993 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-14 09:29:29.781  6993  6993 D LGBluetoothEventManager: [BTUI] clear device connection state
09-14 09:29:29.782  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:29.782  1924  2105 D LGBluetoothAPIService: Message: 2
09-14 09:29:29.783  1924  2105 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@5cbb8cf mBinding = false
09-14 09:29:29.783  1924  2105 D LGBluetoothAPIService: Sending unbind request.
09-14 09:29:29.784  3891  3891 D LGBluetoothAPIServer: [BTUI] onUnbind()
09-14 09:29:29.784  3891  3891 D LGBluetoothAPIServer: [BTUI] cleanup() done
09-14 09:29:29.784  3891  3891 D LGBluetoothAPIServer: [BTUI] onDestroy()
09-14 09:29:29.785  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:29.785  6993  6993 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-14 09:29:29.787  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:29.788  3891  3891 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-14 09:29:29.788  3891  3891 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:29.788  3891  3891 V BluetoothPbapReceiver: ***********state = 10
09-14 09:29:29.789  6993  6993 D DockEventReceiver: finishStartingService: stopping service
09-14 09:29:29.790  2063  2063 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-14 09:29:29.794  7499  7499 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-14 09:29:29.804  6993  6993 D BluetoothPermissionRequest: onReceive
09-14 09:29:29.807  6993  6993 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-14 09:29:29.807  6993  6993 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-14 09:29:29.809  6993  6993 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-14 09:29:29.814  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:29.817  3891  3891 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-14 09:29:29.817  3891  3891 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-14 09:29:29.817  3891  3891 V BluetoothSapReceiver: SapReceiver onReceive 
09-14 09:29:29.817  3891  3891 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:29.817  3891  3891 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-14 09:29:29.819  7129  7129 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-14 09:29:29.858  7499  7499 I dex2oat : dex2oat took 63.493ms (threads: 4)
,09-14 09:29:29.870  7396  7411 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-14 09:29:29.870  7396  7411 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-14 09:29:29.870  7396  7411 I Adreno-EGL: Build Date: 12/12/14 금
09-14 09:29:29.870  7396  7411 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-14 09:29:29.870  7396  7411 I Adreno-EGL: Remote Branch: 
09-14 09:29:29.870  7396  7411 I Adreno-EGL: Local Patches: 
09-14 09:29:29.870  7396  7411 I Adreno-EGL: Reconstruct Branch: 
,09-14 09:29:29.983  7396  7411 D LgDataFeature: LgDataFeature() Constructor: none
,09-14 09:29:29.983  7396  7411 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-14 09:29:30.010  7396  7411 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-14 09:29:30.010  7396  7411 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-14 09:29:30.010  7396  7411 I Adreno-EGL: Build Date: 12/12/14 금
09-14 09:29:30.010  7396  7411 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-14 09:29:30.010  7396  7411 I Adreno-EGL: Remote Branch: 
09-14 09:29:30.010  7396  7411 I Adreno-EGL: Local Patches: 
09-14 09:29:30.010  7396  7411 I Adreno-EGL: Reconstruct Branch: 
,09-14 09:29:30.035  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-14 09:29:30.036  6521  6967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-14 09:29:30.049  7396  7411 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-14 09:29:30.049  7396  7411 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-14 09:29:30.049  7396  7411 I Adreno-EGL: Build Date: 12/12/14 금
09-14 09:29:30.049  7396  7411 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-14 09:29:30.049  7396  7411 I Adreno-EGL: Remote Branch: 
09-14 09:29:30.049  7396  7411 I Adreno-EGL: Local Patches: 
09-14 09:29:30.049  7396  7411 I Adreno-EGL: Reconstruct Branch: 
,09-14 09:29:30.057  2063  2063 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:30.065  1034  1916 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-14 09:29:30.065  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:30.065  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:30.065  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-14 09:29:30.065  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:30.065  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,09-14 09:29:30.070  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-14 09:29:30.070  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:30.070  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-14 09:29:30.070  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-14 09:29:30.072  7203  7203 I AppUp4:CustModeStarterReceiver: onReceive
09-14 09:29:30.073  1034  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=187076053, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
09-14 09:29:30.074   303  7517 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-14 09:29:30.075   303  7517 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-14 09:29:30.075   303  7517 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-14 09:29:30.079  7203  7203 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c35705e
09-14 09:29:30.079  7203  7203 D AppUp4:CustFacade: isCustomizationCompleted : false
09-14 09:29:30.079  7203  7203 D AppUp4:CustFacade: isPhone : true
09-14 09:29:30.079  7203  7203 D AppUp4:CustModeStarterReceiver: begin check event
,09-14 09:29:30.080  7203  7203 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-14 09:29:30.084  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:30.085  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-14 09:29:30.087  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-14 09:29:30.090  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-14 09:29:30.095  3483  3483 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-14 09:29:30.098  3483  3483 V DownloadManager: DownloadService onCreate
09-14 09:29:30.099  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 14 Sep 2016 07:29:30 GMT], X-Android-Received-Millis=[1473838170099], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473838170066]}
09-14 09:29:30.100  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-14 09:29:30.100  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-14 09:29:30.100  1034  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-14 09:29:30.100  1034  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-14 09:29:30.100  1034  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-14 09:29:30.100  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:30.100  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-14 09:29:30.100  1034  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-14 09:29:30.100  1034  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-14 09:29:30.100  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:30.100  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:30.101  1034  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:30.102  1588  2102 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-14 09:29:30.104  3483  7521 I DownloadManager: in removeSpuriousFiles
,09-14 09:29:30.105  3483  7521 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-14 09:29:30.106  4320  7520 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-14 09:29:30.110  4320  7520 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-14 09:29:30.110  2615  2615 D [Concierge]Service: onStartCommand(). Type : 9
09-14 09:29:30.110  4320  7523 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:30.111  3483  7521 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@29c0499c on behalf of 3483
09-14 09:29:30.114  4320  7523 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-14 09:29:30.115  3483  7521 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-14 09:29:30.115  3483  7521 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-14 09:29:30.115  3483  7521 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-14 09:29:30.115  3483  7521 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-14 09:29:30.115  3483  7521 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-14 09:29:30.115  3483  7521 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-14 09:29:30.115  3483  7521 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-14 09:29:30.115  3483  7521 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-14 09:29:30.116  3483  7521 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-14 09:29:30.116  3483  7521 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-14 09:29:30.116  3483  7521 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-14 09:29:30.121  3483  3483 V DownloadManager: DownloadService onStartCommand
09-14 09:29:30.122  3483  7522 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,09-14 09:29:30.123  3483  7522 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1332c32b on behalf of 3483
09-14 09:29:30.124  3483  7522 V DownloadManager: processing inserted download 1
09-14 09:29:30.124  3483  7522 V DownloadManager: processing inserted download 4
09-14 09:29:30.125  3483  7522 V DownloadManager: processing inserted download 7
09-14 09:29:30.126  3483  7522 V DownloadManager: processing inserted download 8
09-14 09:29:30.126  3483  7522 V DownloadManager: processing inserted download 9
09-14 09:29:30.127  3483  7522 V DownloadManager: processing inserted download 10
09-14 09:29:30.127  3483  7522 V DownloadManager: processing inserted download 11
09-14 09:29:30.128  3483  7522 V DownloadManager: processing inserted download 12
09-14 09:29:30.128  3483  7522 V DownloadManager: processing inserted download 13
09-14 09:29:30.129  3483  7522 V DownloadManager: processing inserted download 14
09-14 09:29:30.130  3483  7522 V DownloadManager: processing inserted download 16
09-14 09:29:30.130  3483  7521 I DownloadManager: in trimDatabase
09-14 09:29:30.130  3483  7521 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-14 09:29:30.133  3483  7521 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2566388 on behalf of 3483
,09-14 09:29:30.136  4320  7520 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-14 09:29:30.141  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=187076053 [*alarm*], flags=0x0
09-14 09:29:30.143  4320  4320 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-14 09:29:30.143  4320  4320 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-14 09:29:30.143  4320  4320 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-14 09:29:30.144  4320  4320 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,09-14 09:29:30.145  3483  3483 V DownloadManager: DownloadService onDestroy
09-14 09:29:30.146  4320  4320 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-14 09:29:30.146  7232  7527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:30.160  3426  3426 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-14 09:29:30.161  3426  3426 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-14 09:29:30.161  3426  3426 I LgeMiscReceiver: networkInfo.isConnected() = false
09-14 09:29:30.165  7293  7293 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-14 09:29:30.165  7293  7293 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-14 09:29:30.167   303  7534 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-14 09:29:30.167   303  7534 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
09-14 09:29:30.174  7378  7378 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:29:30
,09-14 09:29:30.176  7378  7378 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-14 09:29:30.176  7378  7378 D Weather.Utils: 2 : All the weather widget is gone.
09-14 09:29:30.176  7378  7378 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-14 09:29:30.176  7378  7378 D WeatherAncestor: connectivity changed - connection : true
09-14 09:29:30.176  7378  7378 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@22dbb90c
09-14 09:29:30.177  7378  7378 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-14 09:29:30.177  7378  7378 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-14 09:29:30.177  7378  7378 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-14 09:29:30.177  7378  7378 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-14 09:29:30.177  7378  7378 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:29:30
09-14 09:29:30.196  7036  7532 V FormManager: There are no updated forms. The schedule will be deleted.
,09-14 09:29:30.199  7036  7532 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-14 09:29:30.200   303  7534 D libc-netbsd: res_queryN name = android.clients.google.com succeed
09-14 09:29:30.202  2063  2063 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-14 09:29:30.213  2063  2063 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-14 09:29:30.214  2063  2063 D c       : Getting all permits...
09-14 09:29:30.214  2063  2063 D a       : Opening database...
,09-14 09:29:30.217  2063  2063 D a       : Opening database auth.proximity.permit_store...
09-14 09:29:30.217  2063  2063 D a       : Closing database...
09-14 09:29:30.226  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-14 09:29:30.228  6521  6967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-14 09:29:30.238  1034  1057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:30.238  1034  1057 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@18ebe844 mBinding = false
09-14 09:29:30.238  1034  1116 D BluetoothManagerService: Message: 1
09-14 09:29:30.238  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@18ebe844
09-14 09:29:30.240  3891  3970 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,09-14 09:29:30.241  3891  3970 D BluetoothAdapterProperties: Setting state to 11
09-14 09:29:30.241  3891  3970 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-14 09:29:30.241  1034  1116 D BluetoothManagerService: Message: 60
09-14 09:29:30.241  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-14 09:29:30.241  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-14 09:29:30.241  3891  3970 D BluetoothBondStateMachine: make
09-14 09:29:30.243  3891  3970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:30.243  3891  7539 I BluetoothBondStateMachine: StableState(): Entering Off State
09-14 09:29:30.243  3891  3970 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-14 09:29:30.243  3891  3970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:30.243  3891  3970 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-14 09:29:30.243  3891  3970 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-14 09:29:30.245  3891  3970 E BluetoothAdapterService: File transfer profiles supported!!
09-14 09:29:30.249  3891  3891 D HeadsetService: Received start request. Starting profile...
09-14 09:29:30.250  3891  3891 D HeadsetStateMachine: make
09-14 09:29:30.250  3891  3970 E BluetoothAdapterService: File transfer profiles supported!!
09-14 09:29:30.252  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-14 09:29:30.252  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:30.253  6993  6993 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-14 09:29:30.254  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:30.256  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:30.260  3891  3891 D HeadsetStateMachine: max_hf_connections = 1
09-14 09:29:30.260  3891  3891 I bluedroid-qcom: get_profile_interface handsfree
09-14 09:29:30.260  3891  3891 E LGBluetoothDtmfAdapter: LGBluetoothDtmfLocalPlay is not null
09-14 09:29:30.260  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:30.260  3891  7540 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-14 09:29:30.260  3891  7540 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-14 09:29:30.260  3891  7540 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-14 09:29:30.260  3891  7540 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-14 09:29:30.260   308  1369 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 3891
09-14 09:29:30.261   308  1369 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-14 09:29:30.261   308  1369 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-14 09:29:30.261   308  1369 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-14 09:29:30.261   308  1369 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-14 09:29:30.261   308  1369 V voice   : voice_set_parameters: exit with code(0)
09-14 09:29:30.261   308  1369 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-14 09:29:30.261   308  1369 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-14 09:29:30.261   308  1369 V msm8974_platform: platform_set_parameters: exit with code(0)
09-14 09:29:30.261   308  1369 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-14 09:29:30.261   308  1369 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-14 09:29:30.261   308  1369 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-14 09:29:30.262  3891  3970 E BluetoothAdapterService: File transfer profiles supported!!
09-14 09:29:30.267  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
,09-14 09:29:30.268  3891  3891 D A2dpService: Received start request. Starting profile...
09-14 09:29:30.268  3891  3891 V Avrcp   : make
09-14 09:29:30.268  3891  3891 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-14 09:29:30.268  3891  3891 I bluedroid-qcom: get_profile_interface avrcp
09-14 09:29:30.269  3891  3970 E BluetoothAdapterService: File transfer profiles supported!!
09-14 09:29:30.271  2063  2063 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:30.273  3891  3891 V AudioManager: registerRemoteController: size of Media player list: 0
09-14 09:29:30.274  3891  3891 E AudioManager: No RCC entry present to update
09-14 09:29:30.274  3891  3891 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-14 09:29:30.274  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-14 09:29:30.274  3891  3891 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-14 09:29:30.276  1034  1587 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-14 09:29:30.277  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:30.277  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:30.277  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-14 09:29:30.277  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:30.277  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-14 09:29:30.279  3891  3970 E BluetoothAdapterService: File transfer profiles supported!!
,09-14 09:29:30.280  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-14 09:29:30.286  3891  3970 E BluetoothAdapterService: File transfer profiles supported!!
09-14 09:29:30.298  1801  7375 I CheckinTask: Sending checkin request (7840 bytes)
,09-14 09:29:30.308  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 14 Sep 2016 07:29:30 GMT], X-Android-Received-Millis=[1473838170308], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473838170279]}
09-14 09:29:30.308  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-14 09:29:30.308  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-14 09:29:30.309  1034  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-14 09:29:30.309  1034  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-14 09:29:30.309  1034  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-14 09:29:30.309  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:30.309  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-14 09:29:30.309  1034  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-14 09:29:30.309  1034  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-14 09:29:30.309  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:30.309  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:30.310  1034  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:30.310  1588  2102 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-14 09:29:30.337  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-14 09:29:30.337  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:30.337  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-14 09:29:30.337  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-14 09:29:30.339  7203  7203 I AppUp4:CustModeStarterReceiver: onReceive
09-14 09:29:30.344  7203  7203 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c35705e
09-14 09:29:30.344  7203  7203 D AppUp4:CustFacade: isCustomizationCompleted : false
09-14 09:29:30.344  7203  7203 D AppUp4:CustFacade: isPhone : true
09-14 09:29:30.345  7203  7203 D AppUp4:CustModeStarterReceiver: begin check event
09-14 09:29:30.345  7203  7203 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-14 09:29:30.346  3891  3970 E BluetoothAdapterService: File transfer profiles supported!!
,09-14 09:29:30.348  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:30.348  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-14 09:29:30.350  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-14 09:29:30.353  3891  3970 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-14 09:29:30.355  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-14 09:29:30.359  3483  3483 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-14 09:29:30.364  3483  3483 V DownloadManager: DownloadService onCreate
09-14 09:29:30.364  4320  7545 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-14 09:29:30.365  3483  7547 I DownloadManager: in removeSpuriousFiles
09-14 09:29:30.365  3483  7547 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-14 09:29:30.369  3483  7547 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@d3ab946 on behalf of 3483
09-14 09:29:30.370  4320  7545 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,09-14 09:29:30.374  3483  7547 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-14 09:29:30.374  3483  7547 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-14 09:29:30.374  3483  7547 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-14 09:29:30.374  3483  7547 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-14 09:29:30.374  3483  7547 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-14 09:29:30.374  3483  7547 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-14 09:29:30.374  3483  7547 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-14 09:29:30.374  3483  7547 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-14 09:29:30.374  3483  7547 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-14 09:29:30.374  3483  7547 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-14 09:29:30.374  3483  7547 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-14 09:29:30.375  4320  7546 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:30.375  4320  7546 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-14 09:29:30.377  3483  7547 I DownloadManager: in trimDatabase
09-14 09:29:30.377  3483  7547 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-14 09:29:30.379  3483  7547 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1eb23034 on behalf of 3483
09-14 09:29:30.379  1034  1993 V SIM_STK : Menu title from STK is T-Mobile
09-14 09:29:30.379  1034  1993 V SIM_STK : Menu title from STK is T-Mobile
09-14 09:29:30.384  3483  3483 V DownloadManager: DownloadService onStartCommand
,09-14 09:29:30.385  4320  7545 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-14 09:29:30.387  3483  7548 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-14 09:29:30.390  3483  7548 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@4d923d2 on behalf of 3483
09-14 09:29:30.392  4320  4320 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-14 09:29:30.392  4320  4320 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-14 09:29:30.392  4320  4320 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-14 09:29:30.393  4320  4320 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-14 09:29:30.396  3483  7548 V DownloadManager: processing inserted download 1
09-14 09:29:30.396  3483  7548 V DownloadManager: processing inserted download 4
09-14 09:29:30.396  3426  3426 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-14 09:29:30.396  3426  3426 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:30.397  3426  3426 I LgeMiscReceiver: networkInfo.isConnected() = true
09-14 09:29:30.397  3426  3426 D PhoneState: setPdpRejectCasuse : false
09-14 09:29:30.397  3483  7548 V DownloadManager: processing inserted download 7
09-14 09:29:30.397  4320  4320 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-14 09:29:30.398  3483  7548 V DownloadManager: processing inserted download 8
,09-14 09:29:30.399  3483  7548 V DownloadManager: processing inserted download 9
09-14 09:29:30.399  3483  7548 V DownloadManager: processing inserted download 10
09-14 09:29:30.400  3483  7548 V DownloadManager: processing inserted download 11
09-14 09:29:30.400  3483  7548 V DownloadManager: processing inserted download 12
09-14 09:29:30.401  3483  7548 V DownloadManager: processing inserted download 13
09-14 09:29:30.402  3483  7548 V DownloadManager: processing inserted download 14
09-14 09:29:30.402  3483  7548 V DownloadManager: processing inserted download 16
09-14 09:29:30.403  7293  7293 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-14 09:29:30.403  7293  7293 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-14 09:29:30.410  7232  7553 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:30.411  3483  3483 V DownloadManager: DownloadService onDestroy
,09-14 09:29:30.414  7378  7378 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:29:30
09-14 09:29:30.415  7378  7378 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-14 09:29:30.415  7378  7378 D Weather.Utils: 2 : All the weather widget is gone.
09-14 09:29:30.415  7378  7378 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-14 09:29:30.415  7378  7378 D WeatherAncestor: connectivity changed - connection : true
09-14 09:29:30.415  7378  7378 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@22dbb90c
09-14 09:29:30.416  7378  7378 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-14 09:29:30.416  7378  7378 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-14 09:29:30.416  7378  7378 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-14 09:29:30.416  7378  7378 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-14 09:29:30.416  7378  7378 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:29:30
,09-14 09:29:30.442  7036  7552 V FormManager: There are no updated forms. The schedule will be deleted.
,09-14 09:29:30.445  7036  7552 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-14 09:29:30.459  1801  7375 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,09-14 09:29:30.467  1034  1970 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-14 09:29:30.467  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-14 09:29:30.467  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-14 09:29:30.467  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-14 09:29:30.467  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-14 09:29:30.467  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-14 09:29:30.468  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-14 09:29:30.468  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-14 09:29:30.468  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-14 09:29:30.468  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-14 09:29:30.468  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-14 09:29:30.468  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-14 09:29:30.468  3891  3891 D A2dpStateMachine: make
09-14 09:29:30.469  1801  7375 I CheckinService: active receiver: disabled
09-14 09:29:30.469  3891  3891 I bluedroid-qcom: get_profile_interface a2dp
09-14 09:29:30.470  3891  7557 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-14 09:29:30.470  3891  3891 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-14 09:29:30.470  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:30.470  3891  7556 D A2dpStateMachine: Enter Disconnected: -2
09-14 09:29:30.470  3891  3891 D HeadsetStateMachine: Proxy object connected
09-14 09:29:30.470  3891  3891 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-14 09:29:30.471  3891  3891 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,09-14 09:29:30.477  3891  3891 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-14 09:29:30.477  3891  3891 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:30.477  3891  3891 V BluetoothPbapReceiver: ***********state = 11
09-14 09:29:30.481  3891  3891 D HidService: Received start request. Starting profile...
09-14 09:29:30.481  3891  3891 I bluedroid-qcom: get_profile_interface hidhost
09-14 09:29:30.481  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:30.481  2063  2063 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-14 09:29:30.484  3891  3891 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-14 09:29:30.484  3891  7540 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-14 09:29:30.484  3891  7540 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-14 09:29:30.484  3891  7540 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-14 09:29:30.485  3891  3891 D HealthService: Received start request. Starting profile...
09-14 09:29:30.486  3891  3891 I bluedroid-qcom: get_profile_interface health
09-14 09:29:30.486  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:30.487  3891  3891 D PanService: Received start request. Starting profile...
09-14 09:29:30.487  3891  3891 D BluetoothPanServiceJni: initializeNative(L110): pan
09-14 09:29:30.487  3891  3891 I bluedroid-qcom: get_profile_interface pan
,09-14 09:29:30.489  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:30.489  3891  3891 D BtGatt.DebugUtils: handleDebugAction() action=null
09-14 09:29:30.489  3891  3891 D BtGatt.GattService: Received start request. Starting profile...
09-14 09:29:30.489  3891  3891 D BtGatt.GattService: start()
09-14 09:29:30.489  3891  3891 D BtGatt.AdvertiseManager: advertise manager created
09-14 09:29:30.493  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:30.494  6993  6993 D BluetoothPermissionRequest: onReceive
09-14 09:29:30.494  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:30.494  3891  3891 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-14 09:29:30.494  3891  3891 V BluetoothMapService: BluetoothMapBinder()
09-14 09:29:30.495  3891  3891 D BluetoothMapService: Received start request. Starting profile...
09-14 09:29:30.495  3891  3891 D BluetoothMapService: start()
09-14 09:29:30.498  6993  6993 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-14 09:29:30.499  1801  7561 I CheckinService: active receiver: disabled
,09-14 09:29:30.503  3891  3891 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-14 09:29:30.503  3891  3891 D BluetoothMapEmailAppObserver: createReceiver()
09-14 09:29:30.504  3891  3891 D BluetoothMapEmailAppObserver: initObservers()
09-14 09:29:30.504  3891  3891 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-14 09:29:30.504  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:30.507  3891  3891 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-14 09:29:30.509  2063  2063 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-14 09:29:30.510  3891  3891 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-14 09:29:30.514  3891  3891 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-14 09:29:30.517  3891  3891 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-14 09:29:30.517  3891  3891 V PanService: [BTUI] SIM Extra State :ABSENT
09-14 09:29:30.521  3891  3891 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-14 09:29:30.521  3891  3891 V BluetoothMapService: Handler(): got msg=1
09-14 09:29:30.522  3891  3970 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,09-14 09:29:30.522  3891  3970 I bluedroid-qcom: enable
09-14 09:29:30.522  3891  7564 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-14 09:29:30.522  3891  7564 I bt-btu  : btu_task pending for preload complete event
09-14 09:29:30.522  3891  3970 I bt_hci_bdroid: init
09-14 09:29:30.523  3891  3970 I bt_vendor: bt-vendor : init
09-14 09:29:30.523  3891  3970 I bt_vendor: bt-vendor : get_bt_soc_type
09-14 09:29:30.524  3891  3970 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-14 09:29:30.524  3891  3970 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-14 09:29:30.524  3891  3970 D bt_userial_mct: userial_init
09-14 09:29:30.524  3891  3970 D bt_hci_bdroid: set_power 1
09-14 09:29:30.524  3891  3970 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-14 09:29:30.524  3891  3970 I bt_vendor: Starting hciattach daemon
09-14 09:29:30.524  3891  3970 I bt_vendor: try to set true
09-14 09:29:30.525  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:30.512  7568  7568 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:30.512  7568  7568 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:30.526  3891  3891 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-14 09:29:30.527  3891  3891 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-14 09:29:30.527  3891  3891 V BluetoothSapReceiver: SapReceiver onReceive 
09-14 09:29:30.527  3891  3891 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:30.527  3891  3891 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-14 09:29:30.530  2063  2063 I GCM     : GCM config loaded
09-14 09:29:30.546  7293  7293 V SetupWizard: Connected to Gservices successfully
09-14 09:29:30.547  7570  7570 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-14 09:29:30.581  3891  3891 V BluetoothOppNotification: previous thread is not finished yet
,09-14 09:29:30.643  7577  7577 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-14 09:29:30.657  7578  7578 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-14 09:29:30.682  7580  7580 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-14 09:29:30.683   303  7581 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-14 09:29:30.684   303  7581 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,09-14 09:29:30.707  7582  7582 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-14 09:29:30.716   303  7581 D libc-netbsd: res_queryN name = www.google.com succeed
09-14 09:29:30.719   303  7587 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-14 09:29:30.719   303  7587 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-14 09:29:30.720   303  7587 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-14 09:29:30.721  7585  7585 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-14 09:29:30.740  7588  7588 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-14 09:29:30.742  1034  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:30.742  1034  2025 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@18ebe844 mBinding = false
09-14 09:29:30.743  1034  1116 D BluetoothManagerService: Message: 1
09-14 09:29:30.743  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@18ebe844
,09-14 09:29:30.748  3891  3910 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-14 09:29:30.748  1034  1116 E BluetoothManagerService: IBluetooth.enable() returned false
09-14 09:29:30.759  7590  7590 I libmdmdetect: ESOC framework not supported
09-14 09:29:30.760  7590  7590 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-14 09:29:30.766  7590  7590 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-14 09:29:30.766  7590  7590 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-14 09:29:30.767  7590  7590 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-14 09:29:30.767  7590  7590 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-14 09:29:30.767  7590  7590 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-14 09:29:30.767  7590  7590 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-14 09:29:30.767  7590  7590 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-14 09:29:30.798  7590  7591 E QC-QMI  : qmi_client [7590] 15: failed to locate client data
09-14 09:29:30.798   485   485 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-14 09:29:30.798   485   485 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-14 09:29:30.805  1034  1525 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-14 09:29:30.848  2063  7584 D GCM     : Connected
,09-14 09:29:30.857  7592  7592 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
09-14 09:29:30.868  6776  7099 D UEI.SmartControl: Internal timer expired: 2
09-14 09:29:30.868  6776  7099 D UEI.SmartControl: unbind internal service
,09-14 09:29:30.877   301   301 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
09-14 09:29:30.877   301   301 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
09-14 09:29:30.878   301   301 I rmt_storage: wakelock acquired: 1, error no: 42
09-14 09:29:30.878   301   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
09-14 09:29:30.889  7593  7593 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-14 09:29:30.896  6776  7096 D serial_port: close(fd = 24)
09-14 09:29:30.903  2063  7584 D GCM     : Message class com.google.e.a.a.q
09-14 09:29:30.915  6776  7096 I UEI.SmartControl: Serial port is closed.
,09-14 09:29:30.926  3891  3970 I bt_vendor: bluetooth satus is on
09-14 09:29:30.926  3891  3970 D bt_hci_bdroid: preload
09-14 09:29:30.926  3891  7567 D bt_userial_mct: userial_open(port:0)
09-14 09:29:30.926  3891  7567 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-14 09:29:30.926  3891  7567 I bt_vendor: Done intiailizing UART
09-14 09:29:30.926  3891  7567 I bt_vendor: Done intiailizing UART
09-14 09:29:30.926  3891  7567 I bt_userial_mct: CMD=94, EVT=94, ACL_Out=95, ACL_In=95
09-14 09:29:30.927  3891  7567 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-14 09:29:30.927  3891  7564 I bt-btu  : btu_task received preload complete event
09-14 09:29:30.927  3891  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-14 09:29:30.927  3891  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-14 09:29:30.927  3891  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-14 09:29:30.927  3891  7598 D bt_userial_mct: Entering userial_read_thread()
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_HCI
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_AVDT
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_AVRC
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_A2D
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_BNEP
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_BTM
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_GAP
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_PAN
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_SDP
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_GATT
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_SMP
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-14 09:29:30.929  3891  7564 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-14 09:29:30.950   301   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
09-14 09:29:30.950   301   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-14 09:29:30.950   301   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
09-14 09:29:30.950   301   902 I rmt_storage: 
,09-14 09:29:30.953   901   912 E Diag_Lib: [IMS_FATAL]| 3347 | 912 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,09-14 09:29:30.953   301   301 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
09-14 09:29:30.966  3891  7564 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-14 09:29:30.966  3891  7564 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0184061 
09-14 09:29:30.966  3891  7564 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0184061 
,09-14 09:29:30.973  3891  3981 E bt-btif : Calling BTA_HhEnable
09-14 09:29:30.973  3891  3981 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-14 09:29:30.974  3891  3981 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-14 09:29:30.974  3891  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-14 09:29:30.974  3891  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-14 09:29:30.974  3891  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-14 09:29:30.974  3891  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-14 09:29:30.974  3891  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-14 09:29:30.975  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-14 09:29:30.976  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
09-14 09:29:30.976  3891  3981 D BluetoothAdapterProperties: Name is: G3
09-14 09:29:30.978  3891  3981 D BluetoothAdapterProperties: Scan Mode:20
09-14 09:29:30.978  3891  3981 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 09:29:30.978  3891  3981 D bt_hci_bdroid: postload
09-14 09:29:30.978  3891  7567 D bt_hci_bdroid: Used up Tx Cmd credits
09-14 09:29:30.979  3891  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-14 09:29:30.979  3891  3981 D bte_conf: Device ID record 1 : primary
09-14 09:29:30.979  3891  3981 D bte_conf:   vendorId            = 00c4
09-14 09:29:30.979  3891  3981 D bte_conf:   vendorIdSource      = 0001
09-14 09:29:30.979  3891  3981 D bte_conf:   product             = 13a1
09-14 09:29:30.979  3891  3981 D bte_conf:   version             = 1000
09-14 09:29:30.980  3891  3981 D bte_conf:   clientExecutableURL = 
09-14 09:29:30.980  3891  3981 D bte_conf:   serviceDescription  = 
09-14 09:29:30.980  3891  3981 D bte_conf:   documentationURL    = 
09-14 09:29:30.980  3891  3981 D bte_conf: bte_load_did_conf no section named DID2.
,09-14 09:29:30.983  3891  7564 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-14 09:29:30.983  3891  7564 W bt-smp  : Plain text(LSB ~ MSB) = 50 cd 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-14 09:29:30.983  3891  7564 W bt-smp  : Encrypted text(LSB ~ MSB) = ff 01 1e 75 ec 9d 92 10 5d a9 d6 30 4c 8e cc 86 
09-14 09:29:30.983  3891  7567 D bt_hci_bdroid: Used up Tx Cmd credits
09-14 09:29:30.983  3891  7564 W bt-btm  : Stopping oneshot timer
09-14 09:29:30.984  3891  7567 D bt_hci_bdroid: Used up Tx Cmd credits
09-14 09:29:30.984  3891  7567 D bt_hci_bdroid: Used up Tx Cmd credits
09-14 09:29:30.985  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:30.985  3891  3970 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-14 09:29:30.985  3891  7598 E bt_mct  : hci lib postload completed
,09-14 09:29:30.986  3891  3970 D BluetoothAdapterProperties: ScanMode =  20
09-14 09:29:30.986  3891  3970 D BluetoothAdapterProperties: State =  11
09-14 09:29:30.986  3891  3970 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-14 09:29:30.986  3891  3970 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-14 09:29:30.986  3891  3970 D BluetoothAdapterProperties: Setting state to 12
09-14 09:29:30.986  3891  3970 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-14 09:29:30.988  1034  1116 D BluetoothManagerService: Message: 60
09-14 09:29:30.988  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-14 09:29:30.988  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-14 09:29:30.989  3891  3981 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-14 09:29:30.990  3891  3981 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-14 09:29:30.972  7600  7600 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-14 09:29:30.972  7600  7600 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:30.996  3891  3970 I BluetoothAdapterState: Entering On State
09-14 09:29:30.998  3891  7564 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-14 09:29:30.998  3891  7564 W bt-smp  : Plain text(LSB ~ MSB) = 17 19 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-14 09:29:30.998  3891  7564 W bt-smp  : Encrypted text(LSB ~ MSB) = a7 81 f9 9a 85 da f9 23 2a 1c 52 18 78 3f 80 c8 
09-14 09:29:30.998  3891  7564 W bt-btm  : Stopping oneshot timer
09-14 09:29:31.000  3891  3970 D LGBluetoothServiceAdapter: [BTUI] OnState
09-14 09:29:31.000  3891  3970 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-14 09:29:31.000  6993  7008 D BluetoothMap: onBluetoothStateChange: up=true
09-14 09:29:31.000  3891  3970 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-14 09:29:31.001  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:31.001  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:31.001  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:31.001  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:31.001  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:31.001  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:31.001  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:31.001  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:31.005  3891  3970 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,09-14 09:29:31.009  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:31.009  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 09:29:31.009  6993  6993 D BluetoothMap: Proxy object connected
,09-14 09:29:31.009  6993  6993 D MapProfile: Bluetooth service connected
09-14 09:29:31.009  6993  6993 D BluetoothMap: getConnectedDevices()
09-14 09:29:31.009  3891  7564 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-14 09:29:31.009  3891  7564 W bt-smp  : Plain text(LSB ~ MSB) = e2 08 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-14 09:29:31.009  3891  7564 W bt-smp  : Encrypted text(LSB ~ MSB) = 91 00 cd 4a 06 c4 b8 9a c4 21 d6 96 e0 b9 96 e6 
09-14 09:29:31.009  3891  7564 W bt-btm  : Stopping oneshot timer
09-14 09:29:31.016  1836  4007 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 09:29:31.019  3891  7564 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-14 09:29:31.019  3891  7564 W bt-smp  : Plain text(LSB ~ MSB) = 6f 65 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-14 09:29:31.019  3891  7564 W bt-smp  : Encrypted text(LSB ~ MSB) = d4 ba 33 0d 0c 3b 02 d3 7d 70 67 d1 87 04 5a d6 
09-14 09:29:31.019  3891  7564 W bt-btm  : Stopping oneshot timer
09-14 09:29:31.019  3891  4201 V BluetoothMapService: getConnectedDevices()
,09-14 09:29:31.025  3891  3981 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-14 09:29:31.025  3891  3981 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-14 09:29:31.028  3891  7564 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-14 09:29:31.028  3891  7564 W bt-smp  : Plain text(LSB ~ MSB) = b3 55 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
,09-14 09:29:31.028  3891  7564 W bt-smp  : Encrypted text(LSB ~ MSB) = c4 82 b7 4b a3 84 95 55 da 92 10 7e f0 c9 4b 71 
09-14 09:29:31.028  3891  7564 W bt-btm  : Stopping oneshot timer
09-14 09:29:31.046  3891  3970 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-14 09:29:31.070  7606  7606 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-14 09:29:31.156  1034  1942 I art     : Explicit concurrent mark sweep GC freed 35392(1780KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.061ms total 142.964ms
,09-14 09:29:31.157  1034  1034 D BluetoothA2dp: Proxy object connected
09-14 09:29:31.158  1836  2457 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 09:29:31.160  1836  1836 D BluetoothHeadset: Proxy object connected
09-14 09:29:31.160  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 09:29:31.161  1836  1836 D BluetoothHeadset: Proxy object connected
09-14 09:29:31.161  1034  1034 D BluetoothHeadset: Proxy object connected
09-14 09:29:31.161  6993  7009 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 09:29:31.162  6993  7008 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 09:29:31.164  6993  6993 D BluetoothHeadset: Proxy object connected
09-14 09:29:31.164  6993  6993 D HeadsetProfile: Bluetooth service connected
09-14 09:29:31.166  6993  7008 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-14 09:29:31.172  6993  7009 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-14 09:29:31.174  6993  6993 D BluetoothInputDevice: Proxy object connected
09-14 09:29:31.174  6993  6993 D HidProfile: Bluetooth service connected
09-14 09:29:31.175  1836  4001 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 09:29:31.177  6993  6993 D BluetoothA2dp: Proxy object connected
09-14 09:29:31.177  6993  6993 D A2dpProfile: Bluetooth service connected
09-14 09:29:31.177  1836  1836 D BluetoothHeadset: Proxy object connected
09-14 09:29:31.177  6993  7009 D BluetoothPan: onBluetoothStateChange on: true
09-14 09:29:31.177  6993  7009 D BluetoothPan: onBluetoothStateChange call bindService
09-14 09:29:31.179  1034  1116 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-14 09:29:31.180  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-14 09:29:31.181  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:31.181  1924  2105 D LGBluetoothAPIService: Message: 1
09-14 09:29:31.181  1924  2105 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-14 09:29:31.182  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-14 09:29:31.185  1924  2105 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,09-14 09:29:31.186  3891  3891 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:31.187  3891  3891 D BluetoothMapService: STATE_ON
09-14 09:29:31.187  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:31.187  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:31.187  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:31.187  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:31.187  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:31.187  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:31.187  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:31.187  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:31.187  3891  3891 D LGBluetoothAPIServer: [BTUI] onCreate()
09-14 09:29:31.187  3891  3891 D LGBluetoothAPIServer: [BTUI] onBind()
09-14 09:29:31.188  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:31.188  3891  3891 V BluetoothPbapService: Pbap Service onCreate
09-14 09:29:31.188  3891  3891 V BluetoothPbapService: Starting PBAP service
09-14 09:29:31.189  1924  1924 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-14 09:29:31.189  1924  2105 D LGBluetoothAPIService: Message: 100
09-14 09:29:31.189  1924  2105 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-14 09:29:31.189  3891  3891 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-14 09:29:31.189  6993  6993 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-14 09:29:31.190  3891  3891 V BluetoothPbapService: Pbap Service onBind
09-14 09:29:31.190  6993  6993 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-14 09:29:31.190  3891  3891 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:31.190  3891  3891 V BluetoothPbapService: state: 12
09-14 09:29:31.191  3891  3891 V BluetoothMapService: Handler(): got msg=1
09-14 09:29:31.191  3891  3891 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-14 09:29:31.191  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:31.191  3891  3891 V BluetoothPbapService: Handler(): got msg=1
09-14 09:29:31.192  3891  3891 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-14 09:29:31.192  6993  6993 D BluetoothPan: BluetoothPAN Proxy object connected
09-14 09:29:31.192  6993  6993 D PanProfile: Bluetooth service connected
09-14 09:29:31.193  3891  7616 D BluetoothMapMasInstance: MAS initSocket()
09-14 09:29:31.193  3891  7616 D BluetoothMapMasInstance:   masId = 00
09-14 09:29:31.193  3891  7616 D BluetoothMapMasInstance:   msgTypes = 0e
09-14 09:29:31.193  3891  7616 D BluetoothMapMasInstance:   masName = SMS/MMS
09-14 09:29:31.193  3891  7616 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-14 09:29:31.193  1034  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:31.193  3891  7617 V BluetoothPbapService: Pbap Service initSocket
09-14 09:29:31.194  1034  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroun,dUser=0
09-14 09:29:31.194  3891  3891 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-14 09:29:31.194  3891  3891 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:31.195  3891  3891 V BluetoothPbapReceiver: ***********state = 12
09-14 09:29:31.195  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:31.197  2063  2063 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 09:29:31.198  2063  2063 D c       : Getting all permits...
09-14 09:29:31.198  2063  2063 D a       : Opening database...
09-14 09:29:31.198  3891  7616 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 09:29:31.198  3891  7617 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 09:29:31.199  3891  7616 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=99 mFd=89
09-14 09:29:31.199  3891  7616 V BluetoothMapMasInstance: Succeed to create listening socket 
09-14 09:29:31.199  3891  7616 D BluetoothMapMasInstance: Accepting socket connection...
09-14 09:29:31.200  3891  3981 D BluetoothAdapterProperties: Scan Mode:21
09-14 09:29:31.200  3891  3981 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-14 09:29:31.202  3891  7617 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=101 mFd=99
09-14 09:29:31.202  3891  7617 V BluetoothPbapService: Succeed to create listening socket 
09-14 09:29:31.202  3891  7617 V BluetoothPbapService: Accepting socket connection...
09-14 09:29:31.203  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:31.204  6993  6993 D BluetoothPbap: Proxy object connected
09-14 09:29:31.204  6993  6993 D PbapServerProfile: Bluetooth service connected
09-14 09:29:31.205  2063  2063 D a       : Opening database auth.proximity.permit_store...
09-14 09:29:31.205  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:31.206  2063  2063 D a       : Closing database...
09-14 09:29:31.214  6993  6993 D DockEventReceiver: finishStartingService: stopping service
,09-14 09:29:31.218  6993  6993 D BluetoothPermissionRequest: onReceive
,09-14 09:29:31.220  6993  6993 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-14 09:29:31.221  6993  6993 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-14 09:29:31.225  3891  3891 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-14 09:29:31.226  3891  3891 I LGBluetoothOppAdapter: [BTUI] startOppService()
,09-14 09:29:31.228  3891  3891 V BtOppService: onCreate
,09-14 09:29:31.228  3891  3891 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-14 09:29:31.229  3891  3891 V BluetoothOppNotification: send message
09-14 09:29:31.232  3891  3891 V BtOppService: Starting RfcommListener
09-14 09:29:31.232  3891  7620 V BtOppService: Deleted complete outbound shares, number =  0
09-14 09:29:31.232  3891  3891 D BluetoothOppPreference: Dumping Names:  
09-14 09:29:31.232  3891  3891 D BluetoothOppPreference: {}
09-14 09:29:31.232  3891  3891 D BluetoothOppPreference: Dumping Channels:  
09-14 09:29:31.232  3891  3891 D BluetoothOppPreference: {}
09-14 09:29:31.232  3891  3891 V BtOppService: onStartCommand
09-14 09:29:31.233  3891  7620 V BtOppService: Deleted complete inbound failed shares, number = 0
09-14 09:29:31.233  3891  7620 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-14 09:29:31.233  3891  7621 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-14 09:29:31.234  3891  7621 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-14 09:29:31.235  3891  7620 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c45b1c on behalf of 
09-14 09:29:31.235  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:31.235  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-14 09:29:31.237  3891  7621 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2058325 on behalf of 
09-14 09:29:31.237  3891  3891 V BluetoothOppNotification: new notify threadi!
09-14 09:29:31.237  3891  3891 V BluetoothOppNotification: send delay message
09-14 09:29:31.237  3891  3891 V BtOppService: ContentObserver received notification
09-14 09:29:31.237  3891  7621 V BluetoothOppNotification: update too frequent, put in queue
09-14 09:29:31.238  3891  3891 V BtOppService: start RfcommListener
09-14 09:29:31.238  3891  3891 V BtOppService: RfcommListener started
09-14 09:29:31.238  3891  3891 V BtOppService: ContentObserver received notification
09-14 09:29:31.238  3891  7622 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-14 09:29:31.239  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:31.239  3891  3891 V BluetoothFtpService: Ftp Service onCreate
09-14 09:29:31.239  3891  7623 V BtOppRfcommListener: Starting RFCOMM listener....
09-14 09:29:31.239  3891  3891 I BluetoothFtpService: Ftp Service onCreate
09-14 09:29:31.239  3891  3891 V BluetoothFtpService: Ftp Service onStartCommand
09-14 09:29:31.239  3891  3891 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:31.239  3891  3891 V BluetoothFtpService: Starting Listening on sockets
09-14 09:29:31.239  1034  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:31.239  3891  3891 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-14 09:29:31.239  3891  3891 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-14 09:29:31.239  3891  3891 V BluetoothSapReceiver: SapReceiver onReceive 
09-14 09:29:31.239  3891  3891 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:31.239  3891  7622 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6d22ab on behalf of 
09-14 09:29:31.239  3891  7621 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-14 09:29:31.239  3891  3891 V BluetoothSapReceiver:  Bluetooth Adapter state =, 12
09-14 09:29:31.240  3891  3891 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-14 09:29:31.240  3891  7621 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-14 09:29:31.240  3891  7623 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 09:29:31.240  3891  7622 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-14 09:29:31.242  3891  7622 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-14 09:29:31.242  3891  7623 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=103 mFd=101
09-14 09:29:31.242  3891  7621 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a4a0d08 on behalf of 
09-14 09:29:31.243  3891  7623 V BtOppRfcommListener: Started RFCOMM listener....
09-14 09:29:31.243  3891  7623 I BtOppRfcommListener: Accept thread started.
09-14 09:29:31.243  3891  7623 V BtOppRfcommListener: Accepting connection...
09-14 09:29:31.243  3891  3891 V BluetoothFtpService: Handler(): got msg=1
09-14 09:29:31.243  3891  3891 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-14 09:29:31.243  3891  3891 V BluetoothFtpService: Ftp Service initSocket
09-14 09:29:31.244  3891  7621 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-14 09:29:31.245  3891  7622 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2db02ca1 on behalf of 
09-14 09:29:31.246  3891  7622 V BluetoothOppNotification: outbound: succ-0  fail-0
09-14 09:29:31.247  1034  1883 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:31.247  6858  7430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:31.247  6858  7430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:31.247  6858  7430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:31.247  6858  7430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:31.247  6858  7430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:31.247  6858  7430 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:31.247  6858  7430 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:31.247  6858  7430 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:31.248  3891  3891 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 09:29:31.248  3891  7622 V BluetoothOppNotification: outbound notification was removed.
,09-14 09:29:31.248  3891  7622 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-14 09:29:31.249  6858  7430 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:31.250  3891  7622 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7223ec6 on behalf of 
09-14 09:29:31.251  6858  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:31.252  3891  7622 V BluetoothOppNotification: inbound: succ-0  fail-0
09-14 09:29:31.252  3891  3891 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=106 mFd=103
09-14 09:29:31.252  3891  3891 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-14 09:29:31.252  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11b1ac3f
09-14 09:29:31.252  3891  3891 V BluetoothSapService: Sap Service onCreate
09-14 09:29:31.253  3891  7624 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-14 09:29:31.253  3891  3891 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:29:31.253  3891  3891 V BluetoothSapService: state: 12
09-14 09:29:31.254  3891  3891 V BluetoothSapService: Starting SAP server process
,09-14 09:29:31.255  3891  7622 V BluetoothOppNotification: inbound notification was removed.
09-14 09:29:31.255  3891  7622 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-14 09:29:31.242  7625  7625 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:31.242  7625  7625 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:31.256  1034  1970 D WifiServiceImplEx: setWifiEnabled: false pid=6858, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-14 09:29:31.256  1034  1970 D WifiService: setWifiEnabled: false pid=6858, uid=10118
09-14 09:29:31.256  1034  1970 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-14 09:29:31.257  3891  3891 V BluetoothSapService: SAP Service startRfcommListenerThread
09-14 09:29:31.258  3891  7622 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19738152 on behalf of 
09-14 09:29:31.258  3891  7626 V BluetoothSapService: Sap Service initRfcommSocket
09-14 09:29:31.258  1034  1883 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:31.259  3891  7626 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 09:29:31.260  3891  7626 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=107 mFd=106
09-14 09:29:31.260  3891  7626 V BluetoothSapService: Succeed to create listening socket 
09-14 09:29:31.260  3891  7626 V BluetoothSapService: Accepting socket connection...
09-14 09:29:31.266  7625  7625 V BT_SAP  : Event pipe created
09-14 09:29:31.266  7625  7625 V BT_SAP  : create_server_socket qcom.sap.server
09-14 09:29:31.266  7625  7625 V BT_SAP  : created socket fd 6
,09-14 09:29:31.271  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-14 09:29:31.271  1034  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-14 09:29:31.271  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-14 09:29:31.271  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-14 09:29:31.271  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-14 09:29:31.271  1034  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-14 09:29:31.272  1034  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-14 09:29:31.272  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-14 09:29:31.272  1034  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-14 09:29:31.272  1034  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-14 09:29:31.272  1034  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-14 09:29:31.273  1034  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-14 09:29:31.273  1034  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-14 09:29:31.274  1034  1057 D WifiServiceImplEx: setWifiEnabled: false pid=6858, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-14 09:29:31.275  1034  1057 D WifiService: setWifiEnabled: false pid=6858, uid=10118
09-14 09:29:31.275  1034  1057 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-14 09:29:31.277  1034  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-14 09:29:31.277  1034  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:31.277  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:31.277  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-14 09:29:31.277  7076  7076 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-14 09:29:31.278  1034  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-14 09:29:31.278  1034  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-14 09:29:31.278  1034  1523 D WifiNative-wlan0: SET ps 1: returned true
09-14 09:29:31.278  1034  7147 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:31.278   303   892 D CommandListener: Clearing all IP addresses on wlan0
,09-14 09:29:31.297  1034  1587 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,09-14 09:29:31.298  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:31.298  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:31.298  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-14 09:29:31.298  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:31.298  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-14 09:29:31.300   303  7629 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-14 09:29:31.301  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-14 09:29:31.301  1034  1114 D DSQN    : Dns fail occured do internet check.
09-14 09:29:31.301  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
09-14 09:29:31.302  1034  1034 D DSQN    : try Internet connection check
09-14 09:29:31.307  1034  7631 D DSQN    : ThreadTCPConnectionCheck connect try to216.58.214.238
09-14 09:29:31.307  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-14 09:29:31.307  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-14 09:29:31.308  1034  7631 D DSQN    : ThreadTCPConnectionCheck conn fail internet is not possible
,09-14 09:29:31.309  1034  7630 D DSQN    : ThreadInternetCheck internet check NOK 
09-14 09:29:31.309  1034  7630 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
09-14 09:29:31.309  1034  7630 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
09-14 09:29:31.310  1924  1924 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-14 09:29:31.314  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:31.314  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:31.314  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-14 09:29:31.315  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:31.315  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:31.315  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-14 09:29:31.316  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:31.319  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:31.322  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-14 09:29:31.322  1034  1522 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:31.322  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:31.322  1034  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3223b42c
09-14 09:29:31.323  1034  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:31.323  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-14 09:29:31.324  1034  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:31.325  1034  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:31.326  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:31.327  1034  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:31.327  1034  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-14 09:29:31.332  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:31.332  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:31.332  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-14 09:29:31.333  1034  1034 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
09-14 09:29:31.337  1924  1940 D WifiServiceExtension: isInternetCheckAvailable return false
09-14 09:29:31.338  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:31.338  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:31.339  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
09-14 09:29:31.339  1034  1034 D RttService: SCAN_AVAILABLE : 1
09-14 09:29:31.339  1034  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-14 09:29:31.339  1034  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:31.342  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:31.344  1034  1522 D LGWifiP2pService: P2pDisablingState
09-14 09:29:31.345  1034  1522 D LGWifiP2pService: P2pDisablingState{ when=-23ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:31.345  1034  1522 D LGWifiP2pService: p2p socket connection lost
09-14 09:29:31.345  1034  1522 D LGWifiP2pService: P2pDisabledState
09-14 09:29:31.345  1034  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-14 09:29:31.346  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-14 09:29:31.346  1034  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:31.346  1034  1522 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:31.346  7076  7076 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-14 09:29:31.346  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-14 09:29:31.346  1034  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-14 09:29:31.346  1034  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-14 09:29:31.347  1034  1523 D WifiNative-wlan0: SET ps 1: returned true
09-14 09:29:31.348  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-14 09:29:31.348  6973  6973 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-14 09:29:31.348  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-14 09:29:31.348  1924  1924 D WfdsService: WifiP2pState is changed : false
09-14 09:29:31.348  1924  2221 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-14 09:29:31.348  1924  2221 D WfdsService: Set the WFDS Monitor: false
09-14 09:29:31.349  1924  2221 D WfdsMonitor: WFDS Monitor is stopped
09-14 09:29:31.349  1924  2221 D WfdsService: STATE : WfdsDisabledState - enter
09-14 09:29:31.350  1924  7088 D CtrlSupplicant: Received on exit socket, terminate
09-14 09:29:31.350  1924  7088 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-14 09:29:31.350  1924  7088 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-14 09:29:31.350  1924  7088 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-14 09:29:31.351  1924  2234 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-14 09:29:31.351  1924  2221 W WfdsService: DefaultState - msg [9445378] is not handled
09-14 09:29:31.351  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:31.357  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:31.363   303   892 D CommandListener: Clearing all IP addresses on wlan0
,09-14 09:29:31.363  1034  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-14 09:29:31.363  1034  1529 D DSQN    : disableDataServiceNotify
09-14 09:29:31.363  1034  1529 D DSQN    : stop dsqn bin
09-14 09:29:31.366  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:31.366  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:31.366  1034  1523 D WifiNative-p2p0: doBoolean: TERMINATE
09-14 09:29:31.367  1034  1523 D WifiNative-p2p0: TERMINATE: returned true
09-14 09:29:31.367  1034  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-14 09:29:31.367  1034  1523 E WifiStateMachine: useWiFiOffloading() : false
09-14 09:29:31.367  1034  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-14 09:29:31.367  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-14 09:29:31.368  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:31.369  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:31.369  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-14 09:29:31.369  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-14 09:29:31.369  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:31.370  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-14 09:29:31.371  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:31.372  1034  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-14 09:29:31.372  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:31.372  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:31.373  1034  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:31.373  1034  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-14 09:29:31.373  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:31.373  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:31.373  1034  7146 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,09-14 09:29:31.373  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:31.373  1034  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-14 09:29:31.373  1034  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-14 09:29:31.373  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-14 09:29:31.374  1034  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:31.374  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-14 09:29:31.374  1034  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:31.374  1034  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:31.374  1034  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:31.374  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-14 09:29:31.374  1588  2102 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-14 09:29:31.374  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-14 09:29:31.374  1034  1529 D NetworkManagementService: Removing idletimer
09-14 09:29:31.374  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-14 09:29:31.374  1034  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:31.375  1034  1529 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-14 09:29:31.375  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:31.375  1034  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:31.375  1034  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-14 09:29:31.376  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-14 09:29:31.376  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-14 09:29:31.376  1034  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-14 09:29:31.376  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-14 09:29:31.377  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-14 09:29:31.377  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-14 09:29:31.378  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:31.378  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:31.378  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:31.378  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 09:29:31.378  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:31.378  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:31.378  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:31.378  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 09:29:31.379  7013  7013 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-14 09:29:31.379  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 09:29:31.380  1034  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-14 09:29:31.381  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-14 09:29:31.381  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-14 09:29:31.381  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-14 09:29:31.381  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-14 09:29:31.382  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:31.382  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:31.382  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:31.382  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 09:29:31.382  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:31.382  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:31.382  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:31.382  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 09:29:31.384  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 09:29:31.385  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:31.388  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-14 09:29:31.388  6973  6973 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-14 09:29:31.388  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-14 09:29:31.391  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:31.397  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:31.403  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:31.403  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-14 09:29:31.407  7013  7013 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-14 09:29:31.410  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:31.413  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-14 09:29:31.413  6973  6973 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-14 09:29:31.413  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-14 09:29:31.416  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:31.425  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-14 09:29:31.428  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-14 09:29:31.429  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:31.430  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:31.431  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:31.432  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:31.433  7076  7076 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-14 09:29:31.433  7076  7076 I wpa_supplicant: monitor socket send errors count : 1
09-14 09:29:31.433  7076  7076 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1924-4\x00 that cannot receive messages
09-14 09:29:31.434  1034  7087 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-14 09:29:31.434  1034  7087 D WifiMonitor: Dropping event because (p2p0) is stopped
09-14 09:29:31.434  7013  7013 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-14 09:29:31.442  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-14 09:29:31.446  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-14 09:29:31.448  7036  7637 W FormManager: Network not available. Please check & try again.
09-14 09:29:31.452  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-14 09:29:31.453  7036  7638 V FormManager: Network unavailable.
09-14 09:29:31.459  7036  7638 V FormManager: Network unavailable.
,09-14 09:29:31.465  7076  7076 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-14 09:29:31.467  7076  7076 W wpa_supplicant: USIM:  scard_deinit function
09-14 09:29:31.467  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-14 09:29:31.467  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-14 09:29:31.467  1034  7087 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-14 09:29:31.467  1034  7087 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-14 09:29:31.467  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-14 09:29:31.468  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-14 09:29:31.468  1034  1116 D Tethering: InitialState.processMessage what=4
09-14 09:29:31.468  1034  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=197462
09-14 09:29:31.469  1034  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=197462
09-14 09:29:31.469  1034  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=197463  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-14 09:29:31.470  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-14 09:29:31.470  1034  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=197464  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-14 09:29:31.471  1034  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
,09-14 09:29:31.472  1034  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:31.477  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-14 09:29:31.478  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:31.478  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:31.479  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-14 09:29:31.479  6993  6993 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-14 09:29:31.479  6993  6993 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-14 09:29:31.479  6993  6993 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-14 09:29:31.479  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-14 09:29:31.480  6993  6993 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-14 09:29:31.480  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-14 09:29:31.480  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-14 09:29:31.480  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-14 09:29:31.480  6993  6993 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-14 09:29:31.480  6993  6993 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-14 09:29:31.489  1034  7147 D DhcpStateMachine: StoppedState
,09-14 09:29:31.489  1034  7147 D DhcpStateMachine: StoppedState{ when=-142ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-14 09:29:31.489  1034  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-14 09:29:31.490  1034  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-14 09:29:31.494  7076  7076 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-14 09:29:31.494  1034  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-14 09:29:31.494  1034  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-14 09:29:31.495  1034  7087 D WifiMonitor: Disconnecting from the supplicant, no more events
09-14 09:29:31.497  1034  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
09-14 09:29:31.583  3891  3891 V BluetoothOppNotification: new notify threadi!
09-14 09:29:31.583  3891  3891 V BluetoothOppNotification: send delay message
09-14 09:29:31.589  3891  7639 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-14 09:29:31.592  3891  7639 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f013c23 on behalf of 
09-14 09:29:31.594  3891  7639 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-14 09:29:31.597  3891  7639 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-14 09:29:31.600  3891  7639 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39eb7520 on behalf of 
09-14 09:29:31.603  1924  1924 D WfdsService: Supplicant Connection state is changed : false
09-14 09:29:31.603  1924  2221 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-14 09:29:31.603  3891  7639 V BluetoothOppNotification: outbound: succ-0  fail-0
09-14 09:29:31.603  1924  2221 D WfdsService: Set the WFDS Monitor: false
09-14 09:29:31.603  1924  2221 D WfdsMonitor: WFDS Monitor is stopped
,09-14 09:29:31.607  3891  7639 V BluetoothOppNotification: outbound notification was removed.
09-14 09:29:31.608  1034  1523 D WifiOffDelayIfNotUsed: stopMonitoring
09-14 09:29:31.608  3891  7639 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-14 09:29:31.608  1034  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-14 09:29:31.608  1034  1523 E WifiStateMachine: useWiFiOffloading() : false
09-14 09:29:31.608  1034  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-14 09:29:31.611  3891  7639 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1db0ced9 on behalf of 
09-14 09:29:31.612  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-14 09:29:31.612  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-14 09:29:31.612  3891  7639 V BluetoothOppNotification: inbound: succ-0  fail-0
09-14 09:29:31.613  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-14 09:29:31.613  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:31.614  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-14 09:29:31.618  2439  2439 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:31.618  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-14 09:29:31.619  1034  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-14 09:29:31.619  1034  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,09-14 09:29:31.624  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-14 09:29:31.627  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:31.627  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:31.627  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:31.627  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 09:29:31.627  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:31.627  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:31.627  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:31.627  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 09:29:31.629  4320  7640 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-14 09:29:31.631  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:31.631  3891  7639 V BluetoothOppNotification: inbound notification was removed.
09-14 09:29:31.632  3891  7639 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-14 09:29:31.635  3891  7639 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1824609e on behalf of 
09-14 09:29:31.636  4320  7641 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-14 09:29:31.636  4320  7641 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-14 09:29:31.645  6973  6973 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-14 09:29:31.645  6973  6973 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-14 09:29:31.645  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-14 09:29:31.650  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-14 09:29:31.653  7036  7643 W FormManager: Network not available. Please check & try again.
09-14 09:29:31.656  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:31.660  7036  7644 V FormManager: Network unavailable.
,09-14 09:29:31.668  7036  7644 V FormManager: Network unavailable.
09-14 09:29:31.784  6858  7628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:31.784  6858  7628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:31.784  6858  7628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:31.784  6858  7628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 09:29:31.784  6858  7628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:31.784  6858  7628 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:31.784  6858  7628 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:31.784  6858  7628 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 09:29:31.789  6858  7628 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 09:29:31.795  6858  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:31.798  1034  1883 D WifiServiceImplEx: setWifiEnabled: true pid=6858, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-14 09:29:31.799  1034  1883 D WifiService: setWifiEnabled: true pid=6858, uid=10118
09-14 09:29:31.799  1034  1883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 09:29:31.824  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-14 09:29:31.825  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-14 09:29:31.825  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-14 09:29:31.829  1034  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-14 09:29:31.829  1034  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-14 09:29:31.833  1034  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,09-14 09:29:31.833  1034  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-14 09:29:31.833  1034  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-14 09:29:31.833  1034  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-14 09:29:31.834  1034  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-14 09:29:31.834  1034  1523 E WifiHW  : unknown target_country: EU , set to default
09-14 09:29:31.834  1034  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-14 09:29:31.834  1034  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-14 09:29:31.834  1034  1523 I WifiUtil: gEnableBmps=1
09-14 09:29:31.837  1034  1970 D WifiServiceImplEx: setWifiEnabled: true pid=6858, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-14 09:29:31.838  1034  1970 D WifiService: setWifiEnabled: true pid=6858, uid=10118
,09-14 09:29:31.838  1034  1970 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-14 09:29:31.841  1034  1528 D WifiController: Mismatch in the state 1
09-14 09:29:32.240  3891  3891 V BluetoothOppNotification: new notify threadi!
09-14 09:29:32.240  3891  3891 V BluetoothOppNotification: send delay message
,09-14 09:29:32.272  3891  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-14 09:29:32.308  3891  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3521777f on behalf of 
,09-14 09:29:32.320  3891  7656 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-14 09:29:32.325  3891  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-14 09:29:32.328  3891  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ce2c34c on behalf of 
09-14 09:29:32.329  3891  7656 V BluetoothOppNotification: outbound: succ-0  fail-0
09-14 09:29:32.331  3891  7656 V BluetoothOppNotification: outbound notification was removed.
09-14 09:29:32.331  3891  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-14 09:29:32.332  3891  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1cd67f95 on behalf of 
09-14 09:29:32.332  3891  7656 V BluetoothOppNotification: inbound: succ-0  fail-0
09-14 09:29:32.334  3891  7656 V BluetoothOppNotification: inbound notification was removed.
09-14 09:29:32.334  3891  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-14 09:29:32.335  3891  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2471e8aa on behalf of 
09-14 09:29:32.343  1034  1765 D WifiServiceImplEx: setWifiEnabled: true pid=6858, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-14 09:29:32.343  1034  1765 D WifiService: setWifiEnabled: true pid=6858, uid=10118
09-14 09:29:32.343  1034  1765 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 09:29:32.347  1034  1528 D WifiController: Mismatch in the state 1
09-14 09:29:32.501   303   892 D SoftapController: Softap fwReload - Ok
,09-14 09:29:32.516  1034  1523 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (674ms)
09-14 09:29:32.531  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-14 09:29:32.532  1034  1116 D Tethering: InitialState.processMessage what=4
,09-14 09:29:32.534   303   892 D CommandListener: Setting iface cfg
09-14 09:29:32.534   303   892 D CommandListener: Trying to bring down wlan0
09-14 09:29:32.537   303   892 D CommandListener: Clearing all IP addresses on wlan0
09-14 09:29:32.538  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-14 09:29:32.541  1034  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-14 09:29:32.542  7664  7664 W wpa_supplicant: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:32.555  1034  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-14 09:29:32.555  1034  1523 E WifiStateMachine: useWiFiOffloading() : false
09-14 09:29:32.555  1034  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-14 09:29:32.552  7664  7664 W wpa_supplicant: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-14 09:29:32.573  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:32.575  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-14 09:29:32.599  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:29:32.613  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-14 09:29:32.616  1034  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-14 09:29:32.616  1034  1523 D WifiMonitor: connecting to supplicant
09-14 09:29:32.617  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:29:32.633  7664  7664 I wpa_supplicant: Successfully initialized wpa_supplicant
09-14 09:29:32.646  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-14 09:29:32.647  6993  6993 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-14 09:29:32.647  6993  6993 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-14 09:29:32.647  6993  6993 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-14 09:29:32.648  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-14 09:29:32.650  6993  6993 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-14 09:29:32.650  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-14 09:29:32.650  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-14 09:29:32.650  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-14 09:29:32.650  6993  6993 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-14 09:29:32.651  6993  6993 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-14 09:29:32.657  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-14 09:29:32.657  6993  6993 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-14 09:29:32.657  6993  6993 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-14 09:29:32.657  6993  6993 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-14 09:29:32.661  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-14 09:29:32.663  6993  6993 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-14 09:29:32.663  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-14 09:29:32.663  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-14 09:29:32.663  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-14 09:29:32.663  6993  6993 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-14 09:29:32.663  6993  6993 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-14 09:29:32.670  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-14 09:29:32.674  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-14 09:29:32.679  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:32.693  7036  7680 W FormManager: Network not available. Please check & try again.
,09-14 09:29:32.700  7036  7681 V FormManager: Network unavailable.
09-14 09:29:32.702  7036  7681 V FormManager: Network unavailable.
09-14 09:29:32.727  7664  7664 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-14 09:29:32.727  7664  7664 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-14 09:29:32.836  7664  7664 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-14 09:29:32.850  1034  2025 D WifiServiceImplEx: setWifiEnabled: true pid=6858, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-14 09:29:32.851  1034  2025 D WifiService: setWifiEnabled: true pid=6858, uid=10118
,09-14 09:29:32.851  1034  2025 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-14 09:29:32.855  7664  7664 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-14 09:29:32.862  1034  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-14 09:29:32.863  1034  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-14 09:29:32.863  1034  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-14 09:29:32.864  1034  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-14 09:29:32.865  1034  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-14 09:29:32.866  1034  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-14 09:29:32.868  1034  1523 E WifiStateMachine:  SupplicantStartingState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3427] from screen [on:0 period:664390340] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-14 09:29:32.870  1034  1523 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:664390342] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-14 09:29:32.872  1034  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,09-14 09:29:32.873  1034  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:32.874  1034  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:32.877  1034  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-14 09:29:32.878  1034  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-14 09:29:32.878  1034  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-14 09:29:32.879  1034  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,09-14 09:29:32.879  1034  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-14 09:29:32.879  1034  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-14 09:29:32.880  1034  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
,09-14 09:29:32.880  1034  1523 E WifiStateMachine: useWiFiOffloading() : false
09-14 09:29:32.880  1034  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-14 09:29:32.881  1034  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
,09-14 09:29:32.882  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:32.882  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 09:29:32.882  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 09:29:32.882  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:32.882  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-14 09:29:32.882  1034  1523 D WifiNative-wlan0: SET update_config 1: returned true
,09-14 09:29:32.882  1034  1523 D WifiConfigStore: Loading config and enabling all networks 
09-14 09:29:32.883  1034  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
,09-14 09:29:32.883  1034  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	,any	
,09-14 09:29:32.893  1924  1924 D WfdService: Waiting for WifiP2p enabling
09-14 09:29:32.895  1034  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-14 09:29:32.896  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-14 09:29:32.905  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,09-14 09:29:32.905  1034  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-14 09:29:32.907  1034  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-14 09:29:32.907  1034  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-14 09:29:32.908  1034  1523 D WifiStateMachine: enableVerboseLogging : level 2
09-14 09:29:32.908  1034  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-14 09:29:32.908  1034  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-14 09:29:32.908  1034  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-14 09:29:32.909  1034  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-14 09:29:32.909  1034  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-14 09:29:32.911  1034  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-14 09:29:32.911  1034  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,09-14 09:29:32.913  1034  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-14 09:29:32.913  1034  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-14 09:29:32.914  7664  7664 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-14 09:29:32.914  1034  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-14 09:29:32.914  1034  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-14 09:29:32.915  1034  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-14 09:29:32.915  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-14 09:29:32.915  1034  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-14 09:29:32.915  1034  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-14 09:29:32.915  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-14 09:29:32.915  1034  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-14 09:29:32.915  1034  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-14 09:29:32.916  1034  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-14 09:29:32.916  1034  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-14 09:29:32.918  1034  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-14 09:29:32.918  1034  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-14 09:29:32.918  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:32.918  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:32.918  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:32.918  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:32.918  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:32.918  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:32.918  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:32.918  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 09:29:32.918  1924  1924 D WfdsService: Supplicant Connection state is changed : true
09-14 09:29:32.919  1924  2221 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-14 09:29:32.919  1924  2221 D WfdsService: Set the WFDS Monitor: true
09-14 09:29:32.919  1924  2221 D WfdsMonitor: WfdsMonitorThread create
09-14 09:29:32.919  1924  2221 D WfdsMonitor: WFDS Monitor is created and started
09-14 09:29:32.919  1924  2221 D WfdsService: WiFi: Supplicant connection re-established
09-14 09:29:32.919  1034  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-14 09:29:32.919  1034  1523 D WifiNative-HAL: Setting external_sim to 1
09-14 09:29:32.919  1034  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-14 09:29:32.920  1034  1523 D WifiNative-wlan0: SET external_sim 1: returned true
09-14 09:29:32.920  1034  1523 I WifiNative-HAL: startHal
09-14 09:29:32.920  1034  1523 D wifi    : setting scan oui 0xaf5a1d40
09-14 09:29:32.920  1034  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-14 09:29:32.920  1034  1523 I WifiNative-HAL: startHal
09-14 09:29:32.921  1034  1523 D wifi    : setting scan oui 0xaf5a1d40
09-14 09:29:32.921  1034  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-14 09:29:32.922  1034  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-14 09:29:32.923  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 09:29:32.923  1034  1523 D WifiNative-wlan0: doBoolean: DRI,VER BTCOEXSCAN-STOP
09-14 09:29:32.923  7664  7664 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
,09-14 09:29:32.927  1034  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-14 09:29:32.927  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-14 09:29:32.927  7664  7664 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-14 09:29:32.928  1034  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-14 09:29:32.928  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-14 09:29:32.928  7664  7664 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-14 09:29:32.928  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:32.928  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:32.928  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:32.928  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:32.928  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:32.928  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:32.928  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:32.928  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 09:29:32.928  1034  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-14 09:29:32.929  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-14 09:29:32.929  7664  7664 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-14 09:29:32.929  1034  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-14 09:29:32.929  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-14 09:29:32.929  7664  7664 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-14 09:29:32.930  1034  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-14 09:29:32.930  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-14 09:29:32.930  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 09:29:32.930  7664  7664 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-14 09:29:32.930  1034  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-14 09:29:32.930  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-14 09:29:32.930  7664  7664 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-14 09:29:32.931  1034  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-14 09:29:32.931  1924  7689 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-14 09:29:32.932  1034  1523 E WifiNative: : [198,924,961 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-14 09:29:32.932  1034  1523 D WifiNative-wlan0: doBoolean: RECONNECT
09-14 09:29:32.932  1924  7689 E CtrlSupplicant: Succeed to open control connection
09-14 09:29:32.932  1924  7689 E CtrlSupplicant: Succeed to open monitor connection
09-14 09:29:32.932  1034  1523 D WifiNative-wlan0: RECONNECT: returned true
09-14 09:29:32.932  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-14 09:29:32.933  1034  1523 D WifiNative-wlan0: doString: [STATUS]
09-14 09:29:32.933  1034  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-14 09:29:32.933  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-14 09:29:32.933  1924  7689 D WfdsMonitor: Supplicant connection established
09-14 09:29:32.933  1034  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-845,7-5827-b861-ec7a05ef48b4
09-14 09:29:32.933  1034  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-14 09:29:32.934  1924  2221 D WfdsService: Connected to the supplicant for wfds
09-14 09:29:32.934  1034  1523 D WifiNative-wlan0: SET ps 1: returned true
09-14 09:29:32.935  1034  1522 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.937  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
09-14 09:29:32.937   303   892 D CommandListener: Setting iface cfg
09-14 09:29:32.937   303   892 D CommandListener: Trying to bring up p2p0
,09-14 09:29:32.938  1034  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-14 09:29:32.938  1034  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-14 09:29:32.938  1034  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-14 09:29:32.938  1034  1522 D LGWifiP2pService: P2pEnablingState
09-14 09:29:32.939  1034  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.939  1034  1522 D LGWifiP2pService: P2p socket connection successful
09-14 09:29:32.939  1034  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-14 09:29:32.939  1034  1522 D LGWifiP2pService: P2pEnabledState
09-14 09:29:32.939  1034  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-14 09:29:32.939  1034  1523 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-14 09:29:32.940  1034  1523 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-14 09:29:32.941  1034  1523 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-14 09:29:32.941  1034  1034 D RttService: SCAN_AVAILABLE : 3
09-14 09:29:32.941  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-14 09:29:32.941  1034  1542 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.941  1034  1541 D WifiScanningService: DefaultState got{ when=-5ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.942  1034  1541 I WifiNative-HAL: startHal
09-14 09:29:32.942  1034  1541 D wifi    : getting scan capabilities on interface[1] = 0xaf5a1d40
09-14 09:29:32.942  1034  1541 D wifi    : failed to get capabilities : -3
09-14 09:29:32.942  1034  1541 E WifiScanningService: could not get scan capabilities
09-14 09:29:32.942  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-14 09:29:32.942  1034  1523 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-14 09:29:32.943  1034  1523 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-14 09:29:32.943  1034  1523 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-14 09:29:32.943  1034  1522 D LGWifiP2pService: sending p2p connection changed broadcast
09-14 09:29:32.944  1034  1523 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-14 09:29:32.944  1924  1924 D WfdsService: WifiP2pState is changed : true
09-14 09:29:32.944  1924  2221 D WfdsService: Receive the WFDS_ENABLE Method
09-14 09:29:32.944  1924  2221 D WfdsService: Set the WFDS Monitor: true
09-14 09:29:32.944  1034  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-14 09:29:32.944  1924  2221 D WfdsService: Connected to the supplicant for wfds
09-14 09:29:32.944  1924  2221 D WfdsJNI : doCommand: WFDS_SET TRUE
09-14 09:29:32.944  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-14 09:29:32.944  7664  7664 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-14 09:29:32.944  1034  1523 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-14 09:29:32.945  1034  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-14 09:29:32.945  1034  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
09-14 09:29:32.945  1924  2221 D WfdsService: selectPreferredScanChannel [36]
09-14 09:29:32.945  1924  2221 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-14 09:29:32.945  1034  1522 D WifiNative-p2p0: SET device_name G3: returned true
09-14 09:29:32.945  1034  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-14 09:29:32.945  1034  1522 D LGWifiP2pService: before postfix = G3
09-14 09:29:32.945  1034  1522 D WifiServerServiceExt: postfix byte check : 2
09-14 09:29:32.945  1034  1522 D LGWifiP2pService: after postfix = G3
09-14 09:29:32.945  1034  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postf,ix -G3
09-14 09:29:32.946  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-14 09:29:32.947  1034  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-14 09:29:32.947  1034  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-14 09:29:32.947  1034  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-14 09:29:32.947  1034  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-14 09:29:32.947  1034  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-14 09:29:32.947  1034  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-14 09:29:32.947  1034  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-14 09:29:32.947  1034  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-14 09:29:32.948  7664  7664 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-14 09:29:32.948  1034  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-14 09:29:32.948  1924  1924 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-14 09:29:32.948  1034  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-14 09:29:32.948  1034  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-14 09:29:32.948  1034  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-14 09:29:32.948  1034  1522 D WifiNative-HAL: p2pGetDeviceAddress
09-14 09:29:32.948  1924  1924 D WfdsService: isConnected: false
,09-14 09:29:32.948  1034  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-14 09:29:32.948  1034  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-14 09:29:32.949  1034  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-14 09:29:32.949  1034  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-14 09:29:32.949  1034  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-14 09:29:32.949  1034  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-14 09:29:32.949  7664  7664 E wpa_supplicant: disconnect_rssi_lvl: -100
09-14 09:29:32.949  1034  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
09-14 09:29:32.950  1034  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-14 09:29:32.950  1034  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-14 09:29:32.950  1034  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-14 09:29:32.951  1034  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=198944  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-14 09:29:32.951  1034  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-14 09:29:32.951  1034  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-14 09:29:32.952  1034  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=198946  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-14 09:29:32.953  1034  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-14 09:29:32.953  1034  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-14 09:29:32.954  1034  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-14 09:29:32.954  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-14 09:29:32.955  1924  1924 I WfdStateTracker: handleP2pThisDeviceChanged
09-14 09:29:32.955  1924  1924 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-14 09:29:32.955  1924  1924 D WfdsService: Update P2p Interface State: 3
09-14 09:29:32.956  7036  7692 W FormManager: Network not available. Please check & try again.
09-14 09:29:32.957  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:32.957  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:32.957  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-14 09:29:32.958  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:32.959  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:32.961  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:32.961  1034  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-14 09:29:32.962  1034  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-14 09:29:32.962  1034  1522 D LGWifiP2pService: InactiveState
09-14 09:29:32.962  1034  1522 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.962  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.962  1034  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,09-14 09:29:32.963  7664  7664 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-14 09:29:32.963  7664  7664 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-14 09:29:32.963  1924  7689 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-14 09:29:32.964  7664  7664 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-14 09:29:32.964  7664  7664 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:32.964  1924  7689 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:32.965  7664  7664 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:32.965  1924  7689 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:32.966  1034  7685 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-14 09:29:32.966  1034  7685 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-14 09:29:32.966  1034  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-14 09:29:32.966  1034  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-14 09:29:32.966  1034  7685 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:32.966  1034  7685 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:32.966  1034  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:32.966  1034  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:32.966  1034  7685 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:32.967  1034  7685 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:32.967  1034  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:32.967  1034  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:32.967  1034  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-14 09:29:32.967  1034  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.967  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.967  1034  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler },
09-14 09:29:32.968  1034  1522 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.968  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.968  1034  1522 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.968  7664  7664 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-14 09:29:32.968  1034  1522 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.969  1924  2221 W WfdsService: DefaultState - msg [9441285] is not handled
09-14 09:29:32.969  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.969  7664  7664 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-14 09:29:32.969  7036  7693 V FormManager: Network unavailable.
09-14 09:29:32.969  1034  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-14 09:29:32.969  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-14 09:29:32.969  1034  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-14 09:29:32.969  1034  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-14 09:29:32.969  7664  7664 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-14 09:29:32.969  7664  7664 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-14 09:29:32.970  1924  7689 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:32.970  1034  7685 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:32.970  1034  7685 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:32.970  1034  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:32.970  1034  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:32.970  7664  7664 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:32.970  1034  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-14 09:29:32.971  1034  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-14 09:29:32.971  1034  1522 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.971  1034  1522 D LGWifiP2pService: InactiveState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.971  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.971  1034  1522 D LGWifiP2pService: DefaultState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.971  1034  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-14 09:29:32.972  1034  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-14 09:29:32.972  1034  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.972  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-14 09:29:32.972  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:32.972  1924  7689 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:32.972  7664  7664 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-14 09:29:32.972  7664  7664 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-14 09:29:32.972  1034  7685 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-14 09:29:32.972  1034  7685 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:32.973  1034  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:32.973  1034  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-14 09:29:32.973  1034  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-14 09:29:32.973  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-14 09:29:32.973  1034  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-14 09:29:32.973  1034  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-14 09:29:32.973  7036  7693 V FormManager: Network unavailable.
09-14 09:29:32.973  1034  1034 E WifiServerServiceExt: No p2p device connected
09-14 09:29:32.973  1034  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-14 09:29:32.973  1034  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-14 09:29:32.974  1034  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-14 09:29:32.974  1034  1523 D WifiNative-wlan0: doBoolean: SCAN
09-14 09:29:32.974  1034  1523 D WifiNative-wlan0: SCAN: returned false
09-14 09:29:32.975  1034  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=198968  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-14 09:29:32.979  1034  1034 W Sett,ings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:32.979  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:32.979  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-14 09:29:32.979  1034  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=198973  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-14 09:29:32.980  1034  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-14 09:29:32.981  1034  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-14 09:29:32.981  1034  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-14 09:29:32.985  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:32.985  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:32.986  1034  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-14 09:29:32.987  1034  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-14 09:29:32.988  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-14 09:29:32.988  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
09-14 09:29:32.988  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:32.989  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:32.993  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-14 09:29:32.993  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
09-14 09:29:33.009  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-14 09:29:33.010  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-14 09:29:33.012  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-14 09:29:33.014  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-14 09:29:33.017  6748  6748 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-14 09:29:33.017  6748  6748 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-14 09:29:33.017  6748  6748 V [BNRBootReceiver]: Boot Receiver Return
09-14 09:29:33.020  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:33.022  4320  7699 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-14 09:29:33.026  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:33.030  4320  7700 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-14 09:29:33.030  4320  7700 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-14 09:29:33.034  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:33.042  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-14 09:29:33.042  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:33.045  7013  7013 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-14 09:29:33.048  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:33.054  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:33.061  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:33.066  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:33.067  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-14 09:29:33.068  7013  7013 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-14 09:29:33.368  6858  7646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:33.368  6858  7646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:33.368  6858  7646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:33.368  6858  7646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:33.368  6858  7646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:33.368  6858  7646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:29:33.368  6858  7646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:29:33.368  6858  7646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 09:29:33.375  6858  7646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 09:29:33.379  6858  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:33.381  6858  6937 D BluetoothAdapter: enable(): BT is already enabled..!
09-14 09:29:33.383  1034  1560 D WifiServiceImplEx: setWifiEnabled: true pid=6858, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-14 09:29:33.385  1034  1560 D WifiService: setWifiEnabled: true pid=6858, uid=10118
09-14 09:29:33.385  1034  1560 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 09:29:33.405  6858  7707 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-14 09:29:33.405  6858  7707 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-14 09:29:33.429  6858  7707 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-14 09:29:33.429  6858  7707 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-14 09:29:33.430  6858  7707 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 09:29:33.430  6858  7707 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 09:29:33.430  6858  7707 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-14 09:29:33.434  6858  7709 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-14 09:29:33.434  6858  7709 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-14 09:29:33.438  6858  7715 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 935, name: OutgoingSocketThread/Sender)
09-14 09:29:33.439  6858  7716 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 936, name: OutgoingSocketThread/Receiver)
09-14 09:29:33.440  6858  7716 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 936, thread name: OutgoingSocketThread/Receiver)
09-14 09:29:33.440  6858  7716 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-14 09:29:33.440  6858  7716 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 936, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-14 09:29:33.442  6858  7709 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 09:29:33.442  6858  7709 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 09:29:33.443  6858  7709 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-14 09:29:33.445  6858  7718 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 938, name: IncomingSocketThread/Receiver)
09-14 09:29:33.445  6858  7718 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 938, thread name: IncomingSocketThread/Receiver)
09-14 09:29:33.445  6858  7718 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-14 09:29:33.445  6858  7718 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 938, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-14 09:29:33.448  6858  7717 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 937, name: IncomingSocketThread/Sender)
,09-14 09:29:33.559  7664  7664 E wpa_supplicant: USIM:  scard_init function
,09-14 09:29:33.560  7664  7664 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-14 09:29:33.571  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-14 09:29:33.572  1034  7685 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-14 09:29:33.572  1034  7685 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-14 09:29:33.572  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
09-14 09:29:33.572  1034  7685 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-14 09:29:33.573  1034  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-14 09:29:33.573  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-14 09:29:33.580  1034  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-14 09:29:33.581  1034  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
,09-14 09:29:33.588  1034  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-14 09:29:33.588  1034  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-14 09:29:33.588  1034  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-14 09:29:33.619  1034  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=199613  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-14 09:29:33.639  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:33.639  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:33.642  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:33.647  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.647  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.647  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-14 09:29:33.648  1034  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=199642  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-14 09:29:33.650  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-14 09:29:33.650  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,09-14 09:29:33.654  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-14 09:29:33.694  7664  7664 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-14 09:29:33.699  1034  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-14 09:29:33.699  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-14 09:29:33.700  1034  7685 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-14 09:29:33.700  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-14 09:29:33.700  1034  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-14 09:29:33.700  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-14 09:29:33.704  1034  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=199698  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-14 09:29:33.706  7664  7664 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-14 09:29:33.706  7664  7664 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-14 09:29:33.710  1034  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-14 09:29:33.710  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-14 09:29:33.710  1034  7685 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-14 09:29:33.710  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-14 09:29:33.710  1034  7685 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-14 09:29:33.710  1034  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-14 09:29:33.710  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-14 09:29:33.711  1034  7685 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-14 09:29:33.714  1034  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-14 09:29:33.714  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-14 09:29:33.724  1034  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=199717  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-14 09:29:33.726  6993  6993 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-14 09:29:33.726  1034  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199719
09-14 09:29:33.729  1034  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199723
,09-14 09:29:33.731  1034  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199725
09-14 09:29:33.732  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199725
09-14 09:29:33.732  1034  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199726
09-14 09:29:33.733  1034  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=199726  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-14 09:29:33.733  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-14 09:29:33.734  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:33.740  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:33.740  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:33.741  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:33.741  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.741  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.741  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-14 09:29:33.742  1034  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=199736  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-14 09:29:33.743  1034  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=199737  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,09-14 09:29:33.746  1034  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=199739  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-14 09:29:33.747  1034  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=199740
09-14 09:29:33.747  1034  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=199741
09-14 09:29:33.749  1034  1523 D WifiNative-wlan0: doString: [STATUS]
09-14 09:29:33.749  1034  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-14 09:29:33.749  1034  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-14 09:29:33.750  1034  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-14 09:29:33.751  1034  1523 I WifiServiceExtension: setVHTCapabilityType  : false
09-14 09:29:33.752  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.752  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.752  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-14 09:29:33.754  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:33.760  1034  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-14 09:29:33.760  1034  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-14 09:29:33.765  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:33.766  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:33.766  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:33.768  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.768  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.768  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-14 09:29:33.772  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:33.774  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.774  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.774  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-14 09:29:33.775  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:33.775  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:33.776  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:33.778  1034  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-14 09:29:33.778  1034  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-14 09:29:33.778  1034  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-14 09:29:33.779  1034  1529 D ConnectivityService: Got NetworkAgent Messenger
09-14 09:29:33.779  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:33.779  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-14 09:29:33.779  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:33.779  1034  1529 D ConnectivityService: NetworkAgent connected
09-14 09:29:33.779  1034  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-14 09:29:33.779  1034  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-14 09:29:33.781  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:33.782  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:33.782  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-14 09:29:33.783  7013  7013 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-14 09:29:33.785  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-14 09:29:33.785  6993  6993 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-14 09:29:33.785  6993  6993 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-14 09:29:33.785  6993  6993 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-14 09:29:33.786  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-14 09:29:33.787  1034  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-14 09:29:33.787  1034  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-14 09:29:33.787  1034  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-14 09:29:33.787  1034  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-14 09:29:33.787  1034  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-14 09:29:33.788  6993  6993 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-14 09:29:33.788  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-14 09:29:33.788  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-14 09:29:33.788  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-14 09:29:33.788  6993  6993 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-14 09:29:33.788  6993  6993 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-14 09:29:33.789  6993  6993 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-14 09:29:33.791  1034  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-14 09:29:33.792   303   892 D CommandListener: Setting iface cfg
09-14 09:29:33.793  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:33.801  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:33.803  1034  7737 D DhcpStateMachine: StoppedState
09-14 09:29:33.803  1034  7737 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:33.804  1034  7737 D DhcpStateMachine: WaitBeforeStartState
09-14 09:29:33.804  1034  1523 E WifiStateMachine: Start Dhcp Watchdog 3
09-14 09:29:33.805  1034  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=199798  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-14 09:29:33.805  1034  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=199799  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-14 09:29:33.806  1034  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=199799  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-14 09:29:33.807  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-14 09:29:33.807  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-14 09:29:33.807  1034  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:33.808  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:33.808  1034  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:33.809  1034  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:33.809  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:33.809  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:33.809  1034  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-14 09:29:33.811  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-14 09:29:33.811  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-14 09:29:33.814  1034  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=199808  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-14 09:29:33.814  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-14 09:29:33.814  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-14 09:29:33.815  1034  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=199808  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-14 09:29:33.815  1034  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=199809  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-14 09:29:33.816  1034  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:946] from screen [on:0 period:664391288] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-14 09:29:33.818  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:664391290] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-14 09:29:33.818  1034  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-14 09:29:33.818  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:33.818  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:33.819  7013  7013 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-14 09:29:33.821  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:33.823  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:33.823  1034  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-14 09:29:33.823  1034  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:33.824  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:33.824  1034  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:33.825  1034  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:33.825  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:33.826  1034  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:33.826  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-14 09:29:33.827  1034  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=224,0,0
09-14 09:29:33.827  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-14 09:29:33.827  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=224,0,0
09-14 09:29:33.827  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-14 09:29:33.827  7664  7664 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-14 09:29:33.828  1034  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-14 09:29:33.828  1034  1523 D WifiNative-wlan0: doBoolean: SET ps 0
,09-14 09:29:33.828  1034  1523 D WifiNative-wlan0: SET ps 0: returned true
09-14 09:29:33.829  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-14 09:29:33.829  7664  7664 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-14 09:29:33.829  1034  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-14 09:29:33.829  1034  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-14 09:29:33.829  1034  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-14 09:29:33.829  1034  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-14 09:29:33.829  1034  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1e45b959 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:33.829  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1e45b959 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:33.830  1034  7737 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:33.830  1034  7737 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-14 09:29:33.830   303   892 D CommandListener: Setting iface cfg
09-14 09:29:33.831   303   892 D CommandListener: Trying to bring up wlan0
09-14 09:29:33.832  1034  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-14 09:29:33.833  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-14 09:29:33.833  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-14 09:29:33.834  1034  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-14 09:29:33.834  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:33.834  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:33.834  1034  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:33.835  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-14 09:29:33.835  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-14 09:29:33.835  1034  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:33.835  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:33.836  1034  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-14 09:29:33.836  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-14 09:29:33.836  1034  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-14 09:29:33.837  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-14 09:29:33.837  1034  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:33.837  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:33.837  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-14 09:29:33.837  7664  7664 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-14 09:29:33.838  1034  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-14 09:29:33.838  1034  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-14 09:29:33.838  7664  7664 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-14 09:29:33.838  1034  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-14 09:29:33.838  1034  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-14 09:29:33.840  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:33.840  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:33.841  7013  7013 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-14 09:29:33.844  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:33.851  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:33.854  1034  1523 D WifiNative-wlan0: SET ps 1: returned true
09-14 09:29:33.854  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,09-14 09:29:33.855  1034  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-14 09:29:33.855  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-14 09:29:33.855  1034  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-14 09:29:33.856  1034  1529 D ConnectivityService: ignoring duplicate network state non-change
09-14 09:29:33.856  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:33.858  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:33.858  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-14 09:29:33.859  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:33.859  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.859  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.859  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-14 09:29:33.864  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-14 09:29:33.865  1034  1529 D ConnectivityService: Adding iface wlan0 to network 102
09-14 09:29:33.867  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.867  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.867  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-14 09:29:33.872  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:33.873  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:33.873  7013  7013 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-14 09:29:33.876  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-14 09:29:33.876  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.876  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.876  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-14 09:29:33.876  1924  1924 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-14 09:29:33.878  1034  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-14 09:29:33.880  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-14 09:29:33.881  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:33.881  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-14 09:29:33.884  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:33.886  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.886  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:33.886  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-14 09:29:33.894  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:33.894  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:33.894  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-14 09:29:33.895  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-14 09:29:33.900  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:33.900  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-14 09:29:33.900  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:33.902  1034  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-14 09:29:33.902  1034  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-14 09:29:33.903  1034  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-14 09:29:33.903   303   892 E Netd    : netlink response contains error (File exists)
09-14 09:29:33.903  1034  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-14 09:29:33.904  1034  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-14 09:29:33.904  1034  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-14 09:29:33.904  1034  1529 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-14 09:29:33.908  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-14 09:29:33.910  1034  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-14 09:29:33.910  1034  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-14 09:29:33.910  1034  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-14 09:29:33.910  1034  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-14 09:29:33.911  1034  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-14 09:29:33.911  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:33.911  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:33.911  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
,09-14 09:29:33.911  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-14 09:29:33.911  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:33.911  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:33.911  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-14 09:29:33.911  1034  1529 D ConnectivityService: currentScore = 0, newScore = 20
09-14 09:29:33.911  1034  1529 D ConnectivityService:    accepting network in place of null
09-14 09:29:33.911  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-14 09:29:33.911  1034  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:33.911  1034  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:33.911  1034  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-14 09:29:33.916  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:33.916  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-14 09:29:33.917   303  7742 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-14 09:29:33.917  1034  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-14 09:29:33.917  1034  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-14 09:29:33.918  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-14 09:29:33.918  1034  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:33.918  1034  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-14 09:29:33.918  1034  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=10,48576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-14 09:29:33.919  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-14 09:29:33.920  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-14 09:29:33.920  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-14 09:29:33.920  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-14 09:29:33.923  1034  1529 D ConnectivityService: validation of new default Network = false
09-14 09:29:33.923  1034  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-14 09:29:33.923  1034  1529 D DSQN    : enableDataServiceNotify 
09-14 09:29:33.923  1034  1529 D DSQN    : start dsqn bin
,09-14 09:29:33.928  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:33.929  1034  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-14 09:29:33.929  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:33.929  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:33.929  1034  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:33.929  1588  2102 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-14 09:29:33.922  7743  7743 W dsqn    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:33.922  7743  7743 W dsqn    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:33.933  6858  6937 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-14 09:29:33.934  6858  6937 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-14 09:29:33.935  1034  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-14 09:29:33.936  6858  6937 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5d17010 Bundle[{}]
09-14 09:29:33.937  6858  6937 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-14 09:29:33.937  6858  6937 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-14 09:29:33.939  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:33.940  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:33.940  6858  6937 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-14 09:29:33.940  7013  7013 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-14 09:29:33.941  6858  6937 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-14 09:29:33.945  7743  7743 E DSQN    : DSQN ssw
09-14 09:29:33.945  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:33.946  6858  6937 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-14 09:29:33.947  6858  6937 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-14 09:29:33.956  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:33.956  6858  7747 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-14 09:29:33.956  6858  7747 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-14 09:29:33.963  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:33.966  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-14 09:29:33.966  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:33.967  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-14 09:29:33.968  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:33.968   303  7742 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-14 09:29:33.968  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:33.969  7013  7013 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-14 09:29:33.971  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:33.977  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:33.980  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:33.984  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:33.985  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:33.985  7013  7013 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-14 09:29:33.988  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:33.990  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-14 09:29:33.990  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-14 09:29:33.993  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-14 09:29:33.997  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:34.002  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-14 09:29:34.002  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-14 09:29:34.002   303  7742 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-14 09:29:34.003  7013  7013 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-14 09:29:34.003  7013  7013 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,09-14 09:29:34.004  7013  7013 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-14 09:29:34.009  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-14 09:29:34.012  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-14 09:29:34.012  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-14 09:29:34.015  6993  6993 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-14 09:29:34.019  6993  6993 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-14 09:29:34.024  7013  7013 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-14 09:29:34.024  7013  7013 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-14 09:29:34.025  7013  7013 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-14 09:29:34.026  7013  7013 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-14 09:29:34.026  7013  7013 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-14 09:29:34.031   303   891 D LGDataListener: argv[0]=dsqncommand
09-14 09:29:34.031   303   891 D LGDataListener: argv[1]=wlan0
09-14 09:29:34.031   303   891 D LGDataListener: argv[2]=1
09-14 09:29:34.031   303   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-14 09:29:34.031  1034  7737 D DhcpStateMachine: DHCPV4 request on wlan0
09-14 09:29:34.031  1034  1114 D DSQN    : DSQM DsqnNotification wlan0  1
09-14 09:29:34.031  1034  1114 D DSQN    : start to monitor internet connection
09-14 09:29:34.032  1034  7737 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-14 09:29:34.032  1034  7737 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-14 09:29:34.022  7751  7751 W dhcpcd  : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:34.022  7751  7751 W dhcpcd  : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-14 09:29:34.042  7751  7751 I dhcpcd  : version 5.5.6 starting
09-14 09:29:34.044  7751  7751 E dhcpcd  : get_duid: m
09-14 09:29:34.044  7751  7751 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-14 09:29:34.044  7751  7751 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-14 09:29:34.074  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 14 Sep 2016 07:29:34 GMT], X-Android-Received-Millis=[1473838174073], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473838174030]}
,09-14 09:29:34.074  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,09-14 09:29:34.074  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-14 09:29:34.074  1034  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-14 09:29:34.074  1034  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-14 09:29:34.074  1034  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-14 09:29:34.075  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:34.075  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-14 09:29:34.075  1034  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-14 09:29:34.075  1034  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-14 09:29:34.075  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:34.075  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:34.075  1034  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:34.076  1034  1529 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:34.076  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-14 09:29:34.076  1588  2102 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-14 09:29:34.076  1034  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:34.076  1034  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-14 09:29:34.077  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:34.077  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-14 09:29:34.114  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-14 09:29:34.115  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-14 09:29:34.117  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-14 09:29:34.123  7751  7751 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-14 09:29:34.123  7751  7751 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,09-14 09:29:34.124  7751  7751 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-14 09:29:34.124  7751  7751 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-14 09:29:34.125  7751  7751 D dhcpcd  : wlan0: sending REQUEST (xid 0xab440d7f), next in 4.02 seconds
09-14 09:29:34.140  7751  7751 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-14 09:29:34.151  7751  7751 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-14 09:29:34.151  7751  7751 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-14 09:29:34.152  7751  7751 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-14 09:29:34.152  7751  7751 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-14 09:29:34.152  7751  7751 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-14 09:29:34.153  7751  7751 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-14 09:29:34.153  7751  7751 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-14 09:29:34.153  7751  7751 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-14 09:29:34.296  7413  7438 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-14 09:29:34.375  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-14 09:29:34.385  1034  1116 D Tethering: MasterInitialState.processMessage what=3
09-14 09:29:34.410  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:34.410  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:34.410  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:34.410  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:34.410  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:34.410  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:34.410  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:34.410  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 09:29:34.414  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:34.417  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:34.417  5836  5836 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-14 09:29:34.418  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:29:34.418  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:34.418  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:34.418  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:34.418  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:34.418  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:34.418  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:34.418  6858  6858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:29:34.420  6858  6858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:34.423  1034  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:34.428  1034  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-14 09:29:34.430  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-14 09:29:34.431  1034  1116 D Tethering: MasterInitialState.processMessage what=3
09-14 09:29:34.432  6521  6967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-14 09:29:34.435  1034  7737 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-14 09:29:34.439  1034  7737 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-14 09:29:34.439  1034  7737 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-14 09:29:34.439  1034  7737 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-14 09:29:34.439  1034  7737 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-14 09:29:34.439  1034  7737 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-14 09:29:34.439  1034  7737 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-14 09:29:34.439  1034  7737 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-14 09:29:34.441  1034  7737 D DhcpStateMachine: RunningState
,09-14 09:29:34.446  1034  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:34.446  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:34.448  1034  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:34.449  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:34.451  5836  5836 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-14 09:29:34.466  6858  7786 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-14 09:29:34.466  6858  7786 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-14 09:29:34.467  6858  7786 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 09:29:34.467  6858  7786 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 09:29:34.467  6858  7786 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-14 09:29:34.468  2063  2063 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:34.470  6858  7747 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-14 09:29:34.470  6858  7747 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-14 09:29:34.470  6858  7747 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 09:29:34.470  6858  7747 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 09:29:34.470  6858  7747 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-14 09:29:34.475  6858  7791 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 951, name: OutgoingSocketThread/Sender)
09-14 09:29:34.477  6858  7792 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 952, name: OutgoingSocketThread/Receiver)
09-14 09:29:34.477  6858  7792 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 952, thread name: OutgoingSocketThread/Receiver)
09-14 09:29:34.477  6858  7792 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-14 09:29:34.477  6858  7792 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 952, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-14 09:29:34.479   303  7795 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-14 09:29:34.479   303  7795 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-14 09:29:34.482  1034  1993 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,09-14 09:29:34.485  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:34.485  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:34.485  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-14 09:29:34.485  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:34.485  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-14 09:29:34.489  6858  7790 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 950, name: IncomingSocketThread/Receiver)
09-14 09:29:34.490  6858  7790 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 950, thread name: IncomingSocketThread/Receiver)
09-14 09:29:34.490  6858  7790 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-14 09:29:34.490  6858  7790 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 950, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-14 09:29:34.493  6858  7789 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 949, name: IncomingSocketThread/Sender)
,09-14 09:29:34.494  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-14 09:29:34.494  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:34.495  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-14 09:29:34.495  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-14 09:29:34.499  7203  7203 I AppUp4:CustModeStarterReceiver: onReceive
09-14 09:29:34.501  7203  7203 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c35705e
09-14 09:29:34.501  7203  7203 D AppUp4:CustFacade: isCustomizationCompleted : false
09-14 09:29:34.501  7203  7203 D AppUp4:CustFacade: isPhone : true
09-14 09:29:34.502  7203  7203 D AppUp4:CustModeStarterReceiver: begin check event
09-14 09:29:34.502  7203  7203 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-14 09:29:34.506  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:34.506  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-14 09:29:34.507  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-14 09:29:34.513  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-14 09:29:34.513  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 14 Sep 2016 07:29:34 GMT], X-Android-Received-Millis=[1473838174513], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473838174486]}
09-14 09:29:34.513  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-14 09:29:34.513  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-14 09:29:34.513  1034  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-14 09:29:34.513  1034  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-14 09:29:34.514  1034  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-14 09:29:34.514  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:34.514  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-14 09:29:34.514  1034  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-14 09:29:34.514  1034  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-14 09:29:34.514  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:34.514  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:34.514  1034  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:34.515  1588  2102 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-14 09:29:34.519   303  7795 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-14 09:29:34.522  3483  3483 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-14 09:29:34.528  3483  3483 V DownloadManager: DownloadService onCreate
09-14 09:29:34.534  4320  7804 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-14 09:29:34.536  3483  7806 I DownloadManager: in removeSpuriousFiles
09-14 09:29:34.538  4320  7804 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,09-14 09:29:34.546  3426  3426 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-14 09:29:34.546  3426  3426 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:34.546  3426  3426 I LgeMiscReceiver: networkInfo.isConnected() = false
09-14 09:29:34.548  7293  7293 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-14 09:29:34.549  7293  7293 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-14 09:29:34.549  4320  7804 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-14 09:29:34.550  3483  7806 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-14 09:29:34.552  3483  7806 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3f5c1ba0 on behalf of 3483
09-14 09:29:34.553  7232  7809 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 09:29:34.553  3483  7806 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-14 09:29:34.553  3483  7806 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-14 09:29:34.553  3483  7806 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-14 09:29:34.553  3483  7806 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-14 09:29:34.553  3483  7806 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-14 09:29:34.553  3483  7806 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-14 09:29:34.553  3483  7806 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-14 09:29:34.553  3483  7806 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-14 09:29:34.553  3483  7806 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-14 09:29:34.553  3483  7806 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-14 09:29:34.554  3483  7806 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-14 09:29:34.556  4320  4320 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-14 09:29:34.556  4320  4320 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-14 09:29:34.556  4320  4320 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-14 09:29:34.557  3483  7806 I DownloadManager: in trimDatabase
09-14 09:29:34.557  3483  7806 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-14 09:29:34.558  3483  7806 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@862b359 on behalf of 3483
09-14 09:29:34.558  4320  4320 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-14 09:29:34.560  4320  7810 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:34.560  4320  7810 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-14 09:29:34.561  4320  4320 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-14 09:29:34.564  7378  7378 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:29:34
09-14 09:29:34.565  3483  3483 V DownloadManager: DownloadService onStartCommand
,09-14 09:29:34.566  7378  7378 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-14 09:29:34.566  7378  7378 D Weather.Utils: 2 : All the weather widget is gone.
09-14 09:29:34.566  3483  7807 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-14 09:29:34.566  7378  7378 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-14 09:29:34.566  7378  7378 D WeatherAncestor: connectivity changed - connection : true
09-14 09:29:34.566  7378  7378 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@22dbb90c
09-14 09:29:34.568  7378  7378 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-14 09:29:34.568  7378  7378 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-14 09:29:34.568  7378  7378 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-14 09:29:34.568  7378  7378 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-14 09:29:34.568  7378  7378 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:29:34
09-14 09:29:34.569   303  7818 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-14 09:29:34.569   303  7818 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
09-14 09:29:34.570  3483  7807 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@22f751cc on behalf of 3483
09-14 09:29:34.573  3483  7807 V DownloadManager: processing inserted download 1
09-14 09:29:34.574  3483  7807 V DownloadManager: processing inserted download 4
09-14 09:29:34.575  3483  7807 V DownloadManager: processing inserted download 7
09-14 09:29:34.576  3483  7807 V DownloadManager: processing inserted download 8
,09-14 09:29:34.577  3483  7807 V DownloadManager: processing inserted download 9
09-14 09:29:34.579  3483  7807 V DownloadManager: processing inserted download 10
09-14 09:29:34.580  3483  7807 V DownloadManager: processing inserted download 11
09-14 09:29:34.581  3483  7807 V DownloadManager: processing inserted download 12
,09-14 09:29:34.584  3483  7807 V DownloadManager: processing inserted download 13
09-14 09:29:34.584  3483  7807 V DownloadManager: processing inserted download 14
09-14 09:29:34.585  3483  7807 V DownloadManager: processing inserted download 16
09-14 09:29:34.590  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-14 09:29:34.591  3483  3483 V DownloadManager: DownloadService onDestroy
,09-14 09:29:34.592  6521  6967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-14 09:29:34.602  2063  2063 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-14 09:29:34.606  1034  1970 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
09-14 09:29:34.607  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:34.607  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:34.607  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-14 09:29:34.607  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:34.607  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-14 09:29:34.609  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-14 09:29:34.609  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:34.609  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-14 09:29:34.609  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-14 09:29:34.610  7203  7203 I AppUp4:CustModeStarterReceiver: onReceive
09-14 09:29:34.613  7203  7203 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c35705e
09-14 09:29:34.613  7203  7203 D AppUp4:CustFacade: isCustomizationCompleted : false
09-14 09:29:34.613  7203  7203 D AppUp4:CustFacade: isPhone : true
09-14 09:29:34.614  7203  7203 D AppUp4:CustModeStarterReceiver: begin check event
09-14 09:29:34.614  7203  7203 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,09-14 09:29:34.619  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:34.619  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-14 09:29:34.620  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-14 09:29:34.622  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-14 09:29:34.625  3483  3483 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:34.626  4320  7821 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-14 09:29:34.627  4320  7821 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,09-14 09:29:34.630  4320  7822 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-14 09:29:34.630  4320  7822 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-14 09:29:34.630  3483  3483 V DownloadManager: DownloadService onCreate
09-14 09:29:34.631  4320  7821 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-14 09:29:34.632  3483  7823 I DownloadManager: in removeSpuriousFiles
09-14 09:29:34.633  3483  7823 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-14 09:29:34.635  3483  7823 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@d995b2a on behalf of 3483
09-14 09:29:34.635  3483  7823 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-14 09:29:34.635  3483  7823 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-14 09:29:34.636  3483  7823 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-14 09:29:34.636  3483  7823 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-14 09:29:34.636  3483  7823 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-14 09:29:34.636  3483  7823 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-14 09:29:34.636  3483  7823 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-14 09:29:34.636  3483  7823 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-14 09:29:34.636  3483  7823 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-14 09:29:34.636  3483  7823 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-14 09:29:34.636  3483  7823 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-14 09:29:34.637  3483  7823 I DownloadManager: in trimDatabase
09-14 09:29:34.637  3483  7823 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-14 09:29:34.637   303  7818 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
09-14 09:29:34.638  4320  4320 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-14 09:29:34.638  3483  7823 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2d2dbeb8 on behalf of 3483
09-14 09:29:34.638  4320  4320 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,09-14 09:29:34.641  4320  4320 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-14 09:29:34.646  3483  3483 V DownloadManager: DownloadService onStartCommand
09-14 09:29:34.648  4320  4320 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-14 09:29:34.651  3483  7824 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-14 09:29:34.653  3483  7824 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@c9fff6 on behalf of 3483
09-14 09:29:34.654  7232  7827 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 09:29:34.656  4320  4320 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-14 09:29:34.659  3483  7824 V DownloadManager: processing inserted download 1
09-14 09:29:34.659  3426  3426 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-14 09:29:34.659  3426  3426 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:34.660  3426  3426 I LgeMiscReceiver: networkInfo.isConnected() = false
09-14 09:29:34.662  7293  7293 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-14 09:29:34.662  7293  7293 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-14 09:29:34.662  3483  7824 V DownloadManager: processing inserted download 4
09-14 09:29:34.663  3483  7824 V DownloadManager: processing inserted download 7
09-14 09:29:34.664  3483  7824 V DownloadManager: processing inserted download 8
,09-14 09:29:34.666  3483  7824 V DownloadManager: processing inserted download 9
09-14 09:29:34.667  3483  7824 V DownloadManager: processing inserted download 10
09-14 09:29:34.668  3483  7824 V DownloadManager: processing inserted download 11
09-14 09:29:34.669  3483  7824 V DownloadManager: processing inserted download 12
09-14 09:29:34.672  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 14 Sep 2016 07:29:34 GMT], X-Android-Received-Millis=[1473838174671], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473838174607]}
09-14 09:29:34.672  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-14 09:29:34.672  1034  7736 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-14 09:29:34.672  1034  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-14 09:29:34.672  1034  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-14 09:29:34.672  1034  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-14 09:29:34.672  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:34.672  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-14 09:29:34.673  1034  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-14 09:29:34.673  1034  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-14 09:29:34.673  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:34.673  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:34.673  1034  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:34.674  1588  2102 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-14 09:29:34.675  7378  7378 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:29:34
09-14 09:29:34.677  3483  7824 V DownloadManager: processing inserted download 13
09-14 09:29:34.679  3483  7824 V DownloadManager: processing inserted download 14
09-14 09:29:34.680  3483  7824 V DownloadManager: processing inserted download 16
,09-14 09:29:34.686  3483  3483 V DownloadManager: DownloadService onDestroy
,09-14 09:29:34.687  7378  7378 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-14 09:29:34.687  7378  7378 D Weather.Utils: 2 : All the weather widget is gone.
09-14 09:29:34.687  7378  7378 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-14 09:29:34.688  7378  7378 D WeatherAncestor: connectivity changed - connection : true
09-14 09:29:34.688  7378  7378 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@22dbb90c
09-14 09:29:34.688  7378  7378 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-14 09:29:34.688  7378  7378 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-14 09:29:34.688  7378  7378 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-14 09:29:34.688  7378  7378 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-14 09:29:34.688  7378  7378 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:29:34
09-14 09:29:34.932  1034  1529 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-14 09:29:34.982  6858  6937 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 961)
,09-14 09:29:34.985  6858  6937 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-14 09:29:34.985  6858  6937 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 962)
,09-14 09:29:34.993  6858  6937 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 09:29:34.993  6858  6937 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e6f23ca added. We now have 4 listener(s)
,09-14 09:29:34.994  1034  2001 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:34.997  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-14 09:29:34.997  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 09:29:34.997  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 09:29:34.997  6858  6937 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 09:29:34.997  6858  6937 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a75f93b added. We now have 4 listener(s)
09-14 09:29:34.997  6858  6937 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 09:29:34.998  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 09:29:35.000  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 09:29:35.006  6858  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:29:35.006  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:29:35.006  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-14 09:29:35.006  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:29:35.006  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:29:35.006  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:35.006  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:29:35.006  6858  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 09:29:35.008  6858  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:29:35.008  6858  6937 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 09:29:35.011  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:35.013  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:35.016  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:35.017  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:35.017  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 09:29:35.017  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 09:29:35.017  6858  6937 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e6f23ca removed from the list
09-14 09:29:35.017  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:35.017  6858  6937 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a75f93b removed from the list
09-14 09:29:35.017  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:35.017  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:35.018  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 09:29:35.018  6858  6937 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 09:29:35.018  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 09:29:35.018  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:35.019  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 09:29:35.024  6858  6937 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 09:29:35.024  1034  1056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-14 09:29:35.032  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 09:29:35.033  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 09:29:35.035  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 09:29:35.036  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:29:35.038  6858  6937 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-14 09:29:35.131  1034  1942 I ActivityManager: Killing 7103:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-14 09:29:35.148  7036  7813 V FormManager: There are no updated forms. The schedule will be deleted.
,09-14 09:29:35.156  7036  7813 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-14 09:29:35.168  1034  1765 W libprocessgroup: failed to open /acct/uid_10037/pid_7103/cgroup.procs: No such file or directory
,09-14 09:29:35.241  7036  7839 V FormManager: There are no updated forms. The schedule will be deleted.
,09-14 09:29:35.250  7036  7839 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-14 09:29:35.273  1034  1883 I ActivityManager: Killing 7129:com.lge.settings.easy/1000 (adj 15): empty #17
,09-14 09:29:35.305  1034  1056 W libprocessgroup: failed to open /acct/uid_1000/pid_7129/cgroup.procs: No such file or directory
,09-14 09:29:35.489  1034  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-14 09:29:35.490  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-14 09:29:35.491  1034  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-14 09:29:35.502  1034  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-14 09:29:35.503  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-14 09:29:35.505  1034  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-14 09:29:35.507  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-14 09:29:35.507  1034  1529 D ConnectivityService: identical MTU - not setting
09-14 09:29:35.508  1034  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-14 09:29:35.508  1034  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-14 09:29:35.508  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-14 09:29:35.509  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:35.510  1034  1529 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-14 09:29:35.515  1588  2102 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-14 09:29:36.348  1034  1522 D LGWifiP2pService: InactiveState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:36.348  1034  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-14 09:29:36.348  1034  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-14 09:29:36.369  1034  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-14 09:29:36.370  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-14 09:29:36.378  1034  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-14 09:29:36.379  1034  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-14 09:29:36.381  1034  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-14 09:29:36.383  1034  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-14 09:29:36.827  1034  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=112.0, 0.0, 0.0  rx=109.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:664394298] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-14 09:29:36.830  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=112.0, 0.0, 0.0  rx=109.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:664394301] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-14 09:29:36.830  1034  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-14 09:29:36.852  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-14 09:29:36.875  1034  1524 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-14 09:29:36.920  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-14 09:29:36.935  1034  1116 D Tethering: MasterInitialState.processMessage what=3
09-14 09:29:36.962  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:29:36.972  6858  6858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:29:36.975  1034  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-14 09:29:36.980  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-14 09:29:36.982  6521  6967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-14 09:29:36.992  5836  5836 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-14 09:29:37.011  2063  2063 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-14 09:29:37.027  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-14 09:29:37.027  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:37.028  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-14 09:29:37.028  7203  7203 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-14 09:29:37.033  7203  7203 I AppUp4:CustModeStarterReceiver: onReceive
09-14 09:29:37.037  7203  7203 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c35705e
09-14 09:29:37.037  7203  7203 D AppUp4:CustFacade: isCustomizationCompleted : false
09-14 09:29:37.037  7203  7203 D AppUp4:CustFacade: isPhone : true
09-14 09:29:37.037  7203  7203 D AppUp4:CustModeStarterReceiver: begin check event
09-14 09:29:37.037  7203  7203 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-14 09:29:37.042  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:37.042  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-14 09:29:37.044  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-14 09:29:37.050  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-14 09:29:37.054  3483  3483 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:37.063  3483  3483 V DownloadManager: DownloadService onCreate
,09-14 09:29:37.081  3483  7842 I DownloadManager: in removeSpuriousFiles
09-14 09:29:37.081  3483  7842 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-14 09:29:37.091   303  7848 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-14 09:29:37.091   303  7848 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-14 09:29:37.091   303  7848 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-14 09:29:37.099  3426  3426 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-14 09:29:37.099  3426  3426 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:37.100  3426  3426 I LgeMiscReceiver: networkInfo.isConnected() = true
09-14 09:29:37.100  3426  3426 D PhoneState: setPdpRejectCasuse : false
,09-14 09:29:37.105  7293  7293 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-14 09:29:37.105  7293  7293 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-14 09:29:37.117  7378  7378 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:29:37
,09-14 09:29:37.121  7378  7378 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-14 09:29:37.121  7378  7378 D Weather.Utils: 2 : All the weather widget is gone.
09-14 09:29:37.136  7378  7378 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-14 09:29:37.137  7378  7378 D WeatherAncestor: connectivity changed - connection : true
09-14 09:29:37.137  7378  7378 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@22dbb90c
09-14 09:29:37.140  1034  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-14 09:29:37.140  7378  7378 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-14 09:29:37.141  7378  7378 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-14 09:29:37.141  7378  7378 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-14 09:29:37.141  7378  7378 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-14 09:29:37.141  7378  7378 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:29:37
09-14 09:29:37.142  4320  7846 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-14 09:29:37.143  4320  7858 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-14 09:29:37.144  4320  7858 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-14 09:29:37.146  4320  7846 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-14 09:29:37.152  3483  7842 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@105c0e64 on behalf of 3483
09-14 09:29:37.153  3483  7842 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-14 09:29:37.153  3483  7842 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-14 09:29:37.153  3483  7842 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-14 09:29:37.153  3483  7842 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-14 09:29:37.153  3483  7842 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-14 09:29:37.153  3483  7842 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-14 09:29:37.153  3483  7842 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-14 09:29:37.153  3483  7842 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-14 09:29:37.153  3483  7842 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-14 09:29:37.154  3483  7842 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
,09-14 09:29:37.154  3483  7842 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-14 09:29:37.155  3483  7842 I DownloadManager: in trimDatabase
09-14 09:29:37.155  3483  7842 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-14 09:29:37.156  3483  7842 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@8ecc8cd on behalf of 3483
09-14 09:29:37.160  7232  7845 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 09:29:37.161  4320  7846 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-14 09:29:37.171  4320  4320 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,09-14 09:29:37.172  3483  3483 V DownloadManager: DownloadService onStartCommand
09-14 09:29:37.173  4320  4320 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-14 09:29:37.173  4320  4320 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-14 09:29:37.175  4320  4320 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-14 09:29:37.176  3483  7843 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-14 09:29:37.182  3483  7843 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@25fdacd0 on behalf of 3483
09-14 09:29:37.187  4320  4320 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,09-14 09:29:37.190  3483  7843 V DownloadManager: processing inserted download 1
09-14 09:29:37.192  3483  7843 V DownloadManager: processing inserted download 4
09-14 09:29:37.193  3483  7843 V DownloadManager: processing inserted download 7
09-14 09:29:37.194  3483  7843 V DownloadManager: processing inserted download 8
09-14 09:29:37.195  3483  7843 V DownloadManager: processing inserted download 9
09-14 09:29:37.197  3483  7843 V DownloadManager: processing inserted download 10
09-14 09:29:37.198  3483  7843 V DownloadManager: processing inserted download 11
09-14 09:29:37.199  3483  7843 V DownloadManager: processing inserted download 12
,09-14 09:29:37.200  3483  7843 V DownloadManager: processing inserted download 13
09-14 09:29:37.201  3483  7843 V DownloadManager: processing inserted download 14
09-14 09:29:37.202  3483  7843 V DownloadManager: processing inserted download 16
09-14 09:29:37.205  3483  3483 V DownloadManager: DownloadService onDestroy
09-14 09:29:37.214  7036  7865 V FormManager: There are no updated forms. The schedule will be deleted.
,09-14 09:29:37.216  7036  7865 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-14 09:29:37.388  2063  7870 D GCM     : Connected
,09-14 09:29:37.437  2063  7870 D GCM     : Message class com.google.e.a.a.q
,09-14 09:29:38.040  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-14 09:29:38.040  6858  6937 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 09:29:38.054  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:38.054  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:38.055  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:38.055  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e6f23ca not in the list
,09-14 09:29:38.055  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:38.055  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a75f93b not in the list
09-14 09:29:38.055  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:38.055  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:38.055  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:38.060  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 09:29:38.061  6858  6937 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-14 09:29:38.061  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-14 09:29:38.066  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 09:29:38.066  6858  6937 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-14 09:29:38.066  6858  6937 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-14 09:29:38.066  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:38.068  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-14 09:29:38.072  6858  6937 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-14 09:29:38.073  6858  6937 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-14 09:29:38.073  6858  6858 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-14 09:29:38.076  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-14 09:29:38.076  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-14 09:29:38.076  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:38.076  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 09:29:38.085  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 09:29:38.090  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 09:29:38.092  6858  6937 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-14 09:29:38.093  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:38.093  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-14 09:29:38.093  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-14 09:29:38.093  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-14 09:29:38.093  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:38.093  6858  6937 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 09:29:38.093  6858  6858 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-14 09:29:38.093  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e6f23ca not in the list
09-14 09:29:38.093  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:38.093  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a75f93b not in the list
09-14 09:29:38.093  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:38.094  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:38.094  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:38.094  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 09:29:38.094  6858  6937 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 09:29:38.095  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 09:29:38.095  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:29:38.095  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 09:29:38.096   303  7883 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-14 09:29:38.096   303  7883 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
09-14 09:29:38.102  1034  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-14 09:29:38.109  6858  6937 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 09:29:38.111  6858  7882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 09:29:38.112  3891  7618 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=109 mFd=107
09-14 09:29:38.113  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:38.114  6858  6937 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-14 09:29:38.117  6858  7882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-14 09:29:38.117  6858  7882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-14 09:29:38.117  6858  7882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-14 09:29:38.118  6858  6858 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-14 09:29:38.146   303  7883 D libc-netbsd: res_queryN name = www.google.com succeed
,09-14 09:29:38.166   303  7885 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-14 09:29:38.168   303  7885 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-14 09:29:38.169   303  7885 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-14 09:29:38.284  1034  1525 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-14 09:29:38.845  1588  1588 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-14 09:29:38.877  1034  1405 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-14 09:29:38.950  1034  1034 D administrator: Handling package changes for user 0
,09-14 09:29:38.965  1034  1102 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7886 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-14 09:29:38.982  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,09-14 09:29:38.988  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-14 09:29:38.989  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-14 09:29:39.040  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-14 09:29:39.057  7886  7886 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-14 09:29:39.109  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-14 09:29:39.110  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-14 09:29:39.149  7886  7886 D LgDataFeature: LgDataFeature() Constructor: none
,09-14 09:29:39.149  7886  7886 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-14 09:29:39.177  1034  1100 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-14 09:29:39.188  1034  1100 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-14 09:29:39.201  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-14 09:29:39.203  2439  2439 V GmsNetworkLocationProvi: DISABLE
,09-14 09:29:39.243  1034  1100 D LocationProviderProxy: applying state to connected service
09-14 09:29:39.247  2439  2439 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-14 09:29:39.273  7886  7932 I Babel   : MmsConfig: mnc/mcc: 0/0
09-14 09:29:39.273  7886  7932 I Babel   : MmsConfig.loadMmsSettings
09-14 09:29:39.279  7886  7932 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-14 09:29:39.279  7886  7932 I Babel   : MmsConfig.loadFromDatabase
,09-14 09:29:39.293  7886  7932 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-14 09:29:39.293  7886  7932 I Babel   : MmsConfig.loadFromResources
09-14 09:29:39.295  7886  7932 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-14 09:29:39.296  7886  7932 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-14 09:29:39.298  7886  7886 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 09:29:39.323  7886  7930 W AudioCapabilities: Unsupported mime audio/evrc
,09-14 09:29:39.325  1801  7934 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-14 09:29:39.326  1801  7934 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-14 09:29:39.329  7203  7203 I AppUp4:CustModeStarterReceiver: onReceive
09-14 09:29:39.330  7886  7930 W AudioCapabilities: Unsupported mime audio/qcelp
09-14 09:29:39.336  7203  7203 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c35705e
,09-14 09:29:39.336  7203  7203 D AppUp4:CustFacade: isCustomizationCompleted : false
09-14 09:29:39.336  7203  7203 D AppUp4:CustFacade: isPhone : true
09-14 09:29:39.336  7203  7203 D AppUp4:CustModeStarterReceiver: begin check event
09-14 09:29:39.337  7203  7203 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-14 09:29:39.337  7886  7930 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-14 09:29:39.342  1801  4776 I Icing   : updateResources: need to parse e{com.google.android.gms}
,09-14 09:29:39.364  7886  7930 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-14 09:29:39.365  7886  7930 W AudioCapabilities: Unsupported mime audio/qcelp
09-14 09:29:39.366  7886  7930 W AudioCapabilities: Unsupported mime audio/evrc
,09-14 09:29:39.374  1034  1935 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7937 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-14 09:29:39.377  1034  1057 I ActivityManager: Killing 6748:com.lge.bnr/1000 (adj 15): empty #17
09-14 09:29:39.389  7886  7930 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-14 09:29:39.390  7886  7930 W VideoCapabilities: Unsupported mime video/divx
,09-14 09:29:39.392  7886  7930 W VideoCapabilities: Unsupported mime video/divx311
,09-14 09:29:39.394  7886  7930 W VideoCapabilities: Unsupported mime video/divx4
09-14 09:29:39.397  7886  7930 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-14 09:29:39.410  7886  7930 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-14 09:29:39.415  7886  7930 W AudioCapabilities: Unsupported mime audio/eac3
09-14 09:29:39.416  7886  7930 W AudioCapabilities: Unsupported mime audio/ac3
09-14 09:29:39.417  7886  7930 W AudioCapabilities: Unsupported mime audio/g726
09-14 09:29:39.417  7886  7930 W AudioCapabilities: Unsupported mime audio/wma-voice
09-14 09:29:39.418  7886  7930 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-14 09:29:39.419  7886  7930 W AudioCapabilities: Unsupported mime audio/adpcm
09-14 09:29:39.420  7886  7930 W VideoCapabilities: Unsupported mime video/theora
09-14 09:29:39.421  7886  7930 W VideoCapabilities: Unsupported mime video/mjpg
09-14 09:29:39.474  1034  1993 W libprocessgroup: failed to open /acct/uid_1000/pid_6748/cgroup.procs: No such file or directory
,09-14 09:29:39.526  7937  7937 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-14 09:29:39.527  7937  7937 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-14 09:29:39.527  7937  7937 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-14 09:29:39.528  7937  7937 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-14 09:29:39.529  7937  7937 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-14 09:29:39.607  7937  7937 I SystemConfig: BUILD Country: EU
09-14 09:29:39.607  7937  7937 I SystemConfig: BUILD Operator: OPEN
,09-14 09:29:39.650  1034  1765 I ActivityManager: Killing 6973:com.lge.sync/1000 (adj 15): empty #17
,09-14 09:29:39.740  1034  2001 W libprocessgroup: failed to open /acct/uid_1000/pid_6973/cgroup.procs: No such file or directory
,09-14 09:29:39.753  7937  7955 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-14 09:29:39.754  7937  7955 I SystemConfig: existFile = false
,09-14 09:29:39.754  7937  7955 I SystemConfig: canReadFile = false
09-14 09:29:39.754  7937  7955 I SystemConfig: systemFeature RCS result false
09-14 09:29:39.755  7937  7955 D SystemConfig: refreshRcsSupport() :false
09-14 09:29:39.814  1034  1765 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7960 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-14 09:29:39.861  1034  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=74.0, 0.0, 0.0  rx=68.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:664397333] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-14 09:29:39.862  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=74.0, 0.0, 0.0  rx=68.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:664397334] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-14 09:29:39.863  1034  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-14 09:29:39.878  7960  7960 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-14 09:29:39.878  7960  7960 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-14 09:29:39.878  7960  7960 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,09-14 09:29:39.879  7960  7960 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-14 09:29:39.983  7960  7960 I AppConfig: Total System Memory = 2995761152
,09-14 09:29:39.995  7960  7960 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-14 09:29:40.103  1034  1942 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7982 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-14 09:29:40.105  1034  1942 I ActivityManager: Killing 6776:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-14 09:29:40.131  7013  7013 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,09-14 09:29:40.133  7013  7013 W System.err: android.os.DeadObjectException
,09-14 09:29:40.133  7013  7013 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-14 09:29:40.134  7013  7013 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-14 09:29:40.134  7013  7013 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-14 09:29:40.134  7013  7013 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-14 09:29:40.134  7013  7013 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-14 09:29:40.134  7013  7013 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-14 09:29:40.134  7013  7013 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-14 09:29:40.134  7013  7013 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-14 09:29:40.134  7013  7013 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-14 09:29:40.134  7013  7013 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-14 09:29:40.134  7013  7013 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 09:29:40.134  7013  7013 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-14 09:29:40.134  7013  7013 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-14 09:29:40.134  7013  7013 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-14 09:29:40.134  7013  7013 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-14 09:29:40.136  7013  7013 W System.err: android.os.DeadObjectException
09-14 09:29:40.136  7013  7013 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-14 09:29:40.136  7013  7013 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-14 09:29:40.136  7013  7013 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-14 09:29:40.136  7013  7013 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-14 09:29:40.136  7013  7013 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-14 09:29:40.136  7013  7013 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-14 09:29:40.136  7013  7013 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-14 09:29:40.136  7013  7013 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-14 09:29:40.136  7013  7013 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-14 09:29:40.136  7013  7013 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-14 09:29:40.136  7013  7013 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 09:29:40.136  7013  7013 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-14 09:29:40.136  7013  7013 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-14 09:29:40.137  7013  7013 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-14 09:29:40.137  7013  7013 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-14 09:29:40.137  7013  7013 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-14 09:29:40.318  1034  1883 W libprocessgroup: failed to open /acct/uid_1000/pid_6776/cgroup.procs: No such file or directory
,09-14 09:29:40.319  1034  1883 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-14 09:29:40.333  7013  7013 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,09-14 09:29:40.336  7013  7013 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-14 09:29:40.399  1034  1883 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8000 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-14 09:29:40.413  7013  7013 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-14 09:29:40.579  1034  1970 I art     : Explicit concurrent mark sweep GC freed 138860(6MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.548ms total 170.325ms
,09-14 09:29:40.651  8000  8000 D UEI.SmartControl: Quickset Services start...
09-14 09:29:40.654  8000  8000 I UEI.SmartControl: Manufacture = LGE
09-14 09:29:40.654  8000  8000 D UEI.SmartControl: Id = LGNevo
09-14 09:29:40.655  8000  8000 D UEI.SmartControl: File observer start...
09-14 09:29:40.656  8000  8000 E UEI.SmartControl: IR Port is disabled: false
09-14 09:29:40.656  8000  8000 D UEI.SmartControl: Starting file observer...
09-14 09:29:40.657  8000  8000 D UEI.SmartControl: Extracting JNI libs...
09-14 09:29:40.657  8000  8000 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,09-14 09:29:40.740  7982  7982 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-14 09:29:40.766  8000  8000 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,09-14 09:29:40.766  8000  8000 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-14 09:29:40.766  8000  8000 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-14 09:29:40.804  8000  8000 I UEI.SmartControl: --- Selecting new region: 6
09-14 09:29:40.806  8000  8000 I UEI.SmartControl: Model = LG-D855
09-14 09:29:40.808  8000  8000 D UEI.SmartControl: QS Service created
09-14 09:29:40.809  7982  7982 D LgDataFeature: LgDataFeature() Constructor: none
09-14 09:29:40.809  7982  7982 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-14 09:29:40.826  8000  8000 I UEI.SmartControl: Service initServices...
,09-14 09:29:40.830  8000  8000 D UEI.SmartControl: QS start get config
,09-14 09:29:40.868  7982  7982 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-14 09:29:40.881  8000  8000 D UEI.SmartControl: Loading JNI Libs...
09-14 09:29:40.898  7982  7982 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-14 09:29:40.899  7982  7982 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-14 09:29:40.916  7982  7982 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-14 09:29:40.916  7982  7982 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-14 09:29:40.935  1034  1993 I ActivityManager: Killing 6993:com.android.settings/1000 (adj 15): empty #17
,09-14 09:29:41.067  1034  1943 W libprocessgroup: failed to open /acct/uid_1000/pid_6993/cgroup.procs: No such file or directory
,09-14 09:29:41.086  4602  8043 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-14 09:29:41.097  3483  7431 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,09-14 09:29:41.100  3483  7431 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3e7d17ce on behalf of 7982
,09-14 09:29:41.117  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:41.117  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:41.117  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:41.117  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e6f23ca not in the list
09-14 09:29:41.117  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:29:41.117  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a75f93b not in the list
09-14 09:29:41.117  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:41.117  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:29:41.117  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:41.119  6858  6937 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:29:41.119  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 09:29:41.119  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-14 09:29:41.119  6858  6937 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e6f23ca not in the list
09-14 09:29:41.119  6858  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,09-14 09:29:41.120  6858  6937 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a75f93b not in the list
09-14 09:29:41.120  6858  6937 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:29:41.120  6858  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 09:29:41.120  6858  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:29:41.121  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-14 09:29:41.122  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-14 09:29:41.122  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-14 09:29:41.122  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 09:29:41.122  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 09:29:41.123  6858  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-14 09:29:41.126  8000  8000 I UEI.SmartControl: Supports setup maps: true
,09-14 09:29:41.128  8000  8000 D UEI.SmartControl: QS start statue = true Error code = 0
09-14 09:29:41.128  8000  8000 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-14 09:29:41.129  8000  8000 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-14 09:29:41.129  8000  8000 I UEI.SmartControl: ### init IR Blaster...
09-14 09:29:41.135  8000  8000 D serial_port: Configuring serial port
,09-14 09:29:41.140  1034  1993 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8044 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-14 09:29:41.145  8000  8000 E UEI.SmartControl: UEIBLaster setting for 616
09-14 09:29:41.145  8000  8000 I UEI.SmartControl: Setting serial record hearder size = 2
09-14 09:29:41.145  8000  8000 I UEI.SmartControl: configuring settings for MAXQ616
09-14 09:29:41.146  8000  8000 I UEI.SmartControl: Get version...
09-14 09:29:41.152  6858  8054 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 981, name: My test thread name)
,09-14 09:29:41.162  8000  8045 D UEI.SmartControl: serial port data available: 21
09-14 09:29:41.167  7982  7982 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-14 09:29:41.185  7982  7982 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-14 09:29:41.192  8000  8000 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-14 09:29:41.192  8000  8000 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-14 09:29:41.192  8000  8000 I UEI.SmartControl: QS saving settings...
09-14 09:29:41.193  8000  8000 D UEI.SmartControl: IR Blaster version: 25672567
09-14 09:29:41.196  8044  8044 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-14 09:29:41.209  8000  8045 D UEI.SmartControl: serial port data available: 4
09-14 09:29:41.211  8044  8044 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,09-14 09:29:41.211  8044  8044 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-14 09:29:41.211  8044  8044 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-14 09:29:41.211  8044  8044 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-14 09:29:41.211  8044  8044 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-14 09:29:41.212  8044  8044 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-14 09:29:41.230  1034  1943 I ActivityManager: Killing 7013:com.lge.qremote/u0a112 (adj 15): empty #17
,09-14 09:29:41.240  8000  8075 I UEI.SmartControl: Device manager: loading config....
09-14 09:29:41.240  8000  8075 D UEI.SmartControl: ----------- loading internal config...
09-14 09:29:41.241  8000  8000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-14 09:29:41.248  8000  8075 E UEI.SmartControl: Loading SETTINGS...
09-14 09:29:41.254  8000  8075 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-14 09:29:41.259  8000  8074 I UEI.SmartControl: Notify AllClients services are ready: 0
09-14 09:29:41.259  8000  8074 D UEI.SmartControl: -----service ready thread exits
09-14 09:29:41.273  8000  8000 E UEI.SmartControl: Services init done
,09-14 09:29:41.273  8000  8000 D UEI.SmartControl: QS Service init finished
09-14 09:29:41.274  8000  8000 D UEI.SmartControl: QS Service version name: 2.1.91
09-14 09:29:41.274  8000  8000 D UEI.SmartControl: QS Service version code: 201091
09-14 09:29:41.274  8000  8000 D UEI.SmartControl: Service requested: Control
09-14 09:29:41.275  1034  1765 W libprocessgroup: failed to open /acct/uid_10112/pid_7013/cgroup.procs: No such file or directory
09-14 09:29:41.280  1034  1888 I ActivityManager: Killing 7396:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-14 09:29:41.336  8000  8000 D UEI.SmartControl: Internal service binding...
,09-14 09:29:41.341  1034  1943 W libprocessgroup: failed to open /acct/uid_10005/pid_7396/cgroup.procs: No such file or directory
,09-14 09:29:41.579  1034  1993 V SIM_STK : Menu title from STK is T-Mobile
,09-14 09:29:41.601  4602  8043 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 515 ms] updated apps [took 515 ms] 
,09-14 09:29:42.873  1034  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=45.5, 0.0, 0.0  rx=41.2 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:664400345] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-14 09:29:42.876  1034  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=45.5, 0.0, 0.0  rx=41.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:664400348] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-14 09:29:42.876  1034  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-14 09:29:43.146  6858  6937 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 981
,09-14 09:29:43.146  6858  6937 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 981, name: My test thread name)
,09-14 09:29:43.163  6858  8086 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 982, name: My test thread name)
09-14 09:29:43.163  6858  8086 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 982, thread name: My test thread name)
09-14 09:29:43.163  6858  8086 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 982, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-14 09:29:43.167  6858  6937 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 09:29:43.171  6858  8087 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 986, name: My test thread name)
09-14 09:29:43.171  6858  8087 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 986, thread name: My test thread name): Test exception.
09-14 09:29:43.171  6858  8087 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 986, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-14 09:29:43.177  6858  6937 I jxcore-log: Total number of executed tests:  82
09-14 09:29:43.177  6858  6937 I jxcore-log: 
09-14 09:29:43.177  6858  6937 I jxcore-log: Number of passed tests:  82
09-14 09:29:43.177  6858  6937 I jxcore-log: 
09-14 09:29:43.177  6858  6937 I jxcore-log: Number of failed tests:  0
09-14 09:29:43.177  6858  6937 I jxcore-log: 
09-14 09:29:43.178  6858  6937 I jxcore-log: Number of ignored tests:  0
09-14 09:29:43.178  6858  6937 I jxcore-log: 
09-14 09:29:43.178  6858  6937 I jxcore-log: Total duration:  19643
09-14 09:29:43.178  6858  6937 I jxcore-log: 
09-14 09:29:43.180  6858  6937 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-14 09:29:43.180  6858  6937 I jxcore-log: 
09-14 09:29:43.181  6858  6937 I jxcore-log: My device name is: LGE-LG-D855
09-14 09:29:43.181  6858  6937 I jxcore-log: 
09-14 09:29:43.195  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.195  6858  6937 I jxcore-log: 
09-14 09:29:43.196  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.196  6858  6937 I jxcore-log: 
09-14 09:29:43.197  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.197  6858  6937 I jxcore-log: 
09-14 09:29:43.199  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.199  6858  6937 I jxcore-log: 
09-14 09:29:43.200  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.200  6858  6937 I jxcore-log: 
,09-14 09:29:43.215  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.215  6858  6937 I jxcore-log: 
09-14 09:29:43.217  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 09:29:43.217  6858  6937 I jxcore-log: 
09-14 09:29:43.218  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 09:29:43.218  6858  6937 I jxcore-log: 
09-14 09:29:43.219  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 09:29:43.219  6858  6937 I jxcore-log: 
09-14 09:29:43.220  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 09:29:43.220  6858  6937 I jxcore-log: 
09-14 09:29:43.221  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 09:29:43.221  6858  6937 I jxcore-log: 
,09-14 09:29:43.225  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 09:29:43.225  6858  6937 I jxcore-log: 
09-14 09:29:43.226  6858  8054 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 981, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
09-14 09:29:43.228  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 09:29:43.228  6858  6937 I jxcore-log: 
09-14 09:29:43.229  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 09:29:43.229  6858  6937 I jxcore-log: 
09-14 09:29:43.230  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 09:29:43.230  6858  6937 I jxcore-log: 
09-14 09:29:43.231  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 09:29:43.231  6858  6937 I jxcore-log: 
09-14 09:29:43.232  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.232  6858  6937 I jxcore-log: 
09-14 09:29:43.233  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.233  6858  6937 I jxcore-log: 
09-14 09:29:43.234  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.234  6858  6937 I jxcore-log: 
09-14 09:29:43.234  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.234  6858  6937 I jxcore-log: 
09-14 09:29:43.235  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.235  6858  6937 I jxcore-log: 
09-14 09:29:43.236  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.236  6858  6937 I jxcore-log: 
09-14 09:29:43.237  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.237  6858  6937 I jxcore-log: 
09-14 09:29:43.238  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.238  6858  6937 I jxcore-log: 
09-14 09:29:43.238  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.238  6858  6937 I jxcore-log: 
09-14 09:29:43.239  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.239  6858  6937 I jxcore-log: 
09-14 09:29:43.240  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"o,n","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.240  6858  6937 I jxcore-log: 
09-14 09:29:43.241  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.241  6858  6937 I jxcore-log: 
09-14 09:29:43.245  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 09:29:43.245  6858  6937 I jxcore-log: 
09-14 09:29:43.246  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 09:29:43.246  6858  6937 I jxcore-log: 
09-14 09:29:43.246  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 09:29:43.246  6858  6937 I jxcore-log: 
09-14 09:29:43.247  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 09:29:43.247  6858  6937 I jxcore-log: 
09-14 09:29:43.248  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 09:29:43.248  6858  6937 I jxcore-log: 
09-14 09:29:43.249  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 09:29:43.249  6858  6937 I jxcore-log: 
09-14 09:29:43.249  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.249  6858  6937 I jxcore-log: 
09-14 09:29:43.250  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.250  6858  6937 I jxcore-log: 
09-14 09:29:43.251  6858  6937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:29:43.251  6858  6937 I jxcore-log: 
,09-14 09:29:43.533  8088  8088 D AndroidRuntime: 
09-14 09:29:43.533  8088  8088 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-14 09:29:43.536  8088  8088 D AndroidRuntime: CheckJNI is OFF
09-14 09:29:43.683  8088  8088 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-14 09:29:43.701  1034  1102 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-14 09:29:43.702  1034  1102 I ActivityManager: Killing 6858:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-14 09:29:43.745  1034  2001 I WindowState: WIN DEATH: Window{60e5c16 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-14 09:29:43.745  1034  1528 D WifiService: Client connection lost with reason: 4
,09-14 09:29:43.753  1034  2001 D InputDispatcher: Window went away: Window{60e5c16 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-14 09:29:43.826  1034  1102 I ActivityManager:   Force finishing activity ActivityRecord{1edc9453 u0 com.test.thalitest/.MainActivity t6}
,09-14 09:29:43.859   327   386 E GBMv2   : DFP En is all cleared set to be enabled
,09-14 09:29:43.867  1034  1057 W ActivityManager: Spurious death for ProcessRecord{373f71ba 6858:com.test.thalitest/u0a118}, curProc for 6858: null
,09-14 09:29:43.868  1034  1122 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-14 09:29:43.877  1034  1122 I ActivityManager:   Force finishing activity ActivityRecord{1edc9453 u0 com.test.thalitest/.MainActivity t6 f}
09-14 09:29:43.878  1034  1122 W ActivityManager: Duplicate finish request for ActivityRecord{1edc9453 u0 com.test.thalitest/.MainActivity t6 f}
,09-14 09:29:43.898  2016  2016 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,09-14 09:29:43.900  2016  2016 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-14 09:29:43.902  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-14 09:29:43.902  1924  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-14 09:29:43.903  1924  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{18d8d63a co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-14 09:29:43.904  1924  2254 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-14 09:29:43.904  1924  2254 D SplitWindowPolicy: topRunningActivity=ActivityInfo{107512eb co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-14 09:29:43.904  2016  2062 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
09-14 09:29:43.910  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-14 09:29:43.917  1034  1405 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-14 09:29:43.923  3837  3837 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-14 09:29:43.927  1979  1979 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-14 09:29:43.930  2439  2591 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-14 09:29:43.936  4502  4502 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-14 09:29:43.937  4502  4502 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-14 09:29:43.937  4502  4502 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-14 09:29:43.937  4502  4502 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-14 09:29:43.937  4502  4502 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-14 09:29:43.937  4502  4502 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-14 09:29:43.937  4502  4502 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-14 09:29:43.937  4502  4502 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-14 09:29:43.937  4502  4502 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 09:29:43.937  4502  4502 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-14 09:29:43.937  4502  4502 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-14 09:29:43.937  4502  4502 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-14 09:29:43.939  3891  3891 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-14 09:29:43.939  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-14 09:29:43.995  1034  1942 V SIM_STK : Menu title from STK is T-Mobile
09-14 09:29:44.008  4602  4602 I art     : Explicit concurrent mark sweep GC freed 8193(469KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 578us total 118.711ms
09-14 09:29:44.010  1034  1034 D administrator: Handling package changes for user 0
,09-14 09:29:44.014  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,09-14 09:29:44.016  1889  1889 D ActionManagerService: notifyUserLog: 1000003
09-14 09:29:44.018  3837  4472 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-14 09:29:44.018  6521  6521 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-14 09:29:44.019  2016  2016 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-14 09:29:44.020  2016  2016 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-14 09:29:44.030  2016  2016 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,09-14 09:29:44.039  1801  1801 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-14 09:29:44.040  1889  1889 D ActionManagerService: notifyUserLog: 1000004
09-14 09:29:44.040  3837  4472 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-14 09:29:44.041  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-14 09:29:44.047  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,09-14 09:29:44.054  1588  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-14 09:29:44.054  1588  1649 D KeyguardModel: createShortcutInfo...
09-14 09:29:44.054  3837  3855 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-14 09:29:44.058  1588  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-14 09:29:44.058  1588  1649 D KeyguardModel: createShortcutInfo...
09-14 09:29:44.066  1588  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,09-14 09:29:44.066  1588  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-14 09:29:44.066  1588  1649 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-14 09:29:44.067  1588  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-14 09:29:44.069  1853  1853 D SplitUIManager: split_name #11 / not available #0
09-14 09:29:44.069  1853  1853 D SplitUIService: removed split : 
09-14 09:29:44.071  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-14 09:29:44.071  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-14 09:29:44.071  1588  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-14 09:29:44.071  1588  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-14 09:29:44.073  1588  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-14 09:29:44.073  1588  1649 D KeyguardModel: createShortcutInfo...
09-14 09:29:44.077  1588  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-14 09:29:44.077  1588  1649 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-14 09:29:44.078  1588  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-14 09:29:44.078  1588  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,09-14 09:29:44.089  1588  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-14 09:29:44.089  1588  1649 D KeyguardModel: createShortcutInfo...
,09-14 09:29:44.091  1853  1853 D SplitUIManager: split_name #11 / not available #0
09-14 09:29:44.091  1853  1853 I SplitUIService: split app #11
,09-14 09:29:44.094  1588  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-14 09:29:44.094  1588  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-14 09:29:44.094  1588  1649 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-14 09:29:44.094  1588  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-14 09:29:44.095  1588  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-14 09:29:44.095  1588  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-14 09:29:44.096  1588  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-14 09:29:44.096  1588  1649 D KeyguardModel: createShortcutInfo...
09-14 09:29:44.103  1034  1587 V SIM_STK : Menu title from STK is T-Mobile
09-14 09:29:44.103  1034  1587 V SIM_STK : Menu title from STK is T-Mobile
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , create_time: 1430832262123
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , expire_time: 0
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , display: false
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , animation: false }
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , create_time: 1430832262287
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , expire_time: 0
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , display: false
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , animation: false }
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , create_time: 1473420113195
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , expire_time: 0
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , display: false
09-14 09:29:44.113  2016  2016 I GBoardWebViewUtils: , animation: false }
,09-14 09:29:44.115  2063  2063 I ConfigService: onCreate
09-14 09:29:44.115  1588  1588 D KeyguardModel: handleShortcutListChanged...
09-14 09:29:44.115  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-14 09:29:44.115  2063  2063 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-14 09:29:44.120  2016  8122 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-14 09:29:44.121  1801  1801 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-14 09:29:44.128  2063  2063 I ConfigService: onBind returning update interface
09-14 09:29:44.129  2063  2063 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-14 09:29:44.129  2063  2063 I ConfigService: onBind returning config service
,09-14 09:29:44.138  1588  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-14 09:29:44.138  1588  1649 D KeyguardModel: createShortcutInfo...
09-14 09:29:44.140  2063  2063 I ConfigService: onDestroy
09-14 09:29:44.141  1588  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-14 09:29:44.141  1588  1649 D KeyguardModel: createShortcutInfo...
09-14 09:29:44.142  1588  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-14 09:29:44.142  1588  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-14 09:29:44.143  1588  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-14 09:29:44.143  1588  1649 D KeyguardModel: createShortcutInfo...
09-14 09:29:44.147  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-14 09:29:44.147  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,09-14 09:29:44.155  1034  1942 V SIM_STK : Menu title from STK is T-Mobile
09-14 09:29:44.169  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-14 09:29:44.169  1588  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-14 09:29:44.169  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-14 09:29:44.169  1588  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-14 09:29:44.169  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-14 09:29:44.170  1034  1562 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-14 09:29:44.171  1034  1100 W InputMethodInfo: Duplicated subtype definition found: , voice
,09-14 09:29:44.171  1588  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-14 09:29:44.172  1588  1649 D KeyguardModel: createShortcutInfo...
09-14 09:29:44.175  1034  1587 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-14 09:29:44.175  1801  8124 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-14 09:29:44.176  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-14 09:29:44.176  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-14 09:29:44.176  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-14 09:29:44.176  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-14 09:29:44.176  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-14 09:29:44.176  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-14 09:29:44.176  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-14 09:29:44.176  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-14 09:29:44.176  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-14 09:29:44.176  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-14 09:29:44.176  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-14 09:29:44.177  1588  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-14 09:29:44.177  1588  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-14 09:29:44.180  1588  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-14 09:29:44.180  1588  1649 D KeyguardModel: createShortcutInfo...
,09-14 09:29:44.212  2016  2016 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,09-14 09:29:44.219  1588  1588 D KeyguardModel: handleShortcutListChanged...
09-14 09:29:44.219  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-14 09:29:44.232  6017  8129 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-14 09:29:44.245  1801  8131 I PeopleContactsSync: CP2 sync disabled
,09-14 09:29:44.247  1801  4776 I Icing   : doRemovePackageData com.test.thalitest
09-14 09:29:44.258  7203  7203 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-14 09:29:44.262   321   402 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-14 09:29:44.263  3191  8134 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-14 09:29:44.272  7232  7232 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
09-14 09:29:44.276  2063  2082 I art     : Explicit concurrent mark sweep GC freed 11596(771KB) AllocSpace objects, 8(128KB) LOS objects, 52% free, 29MB/61MB, paused 3.794ms total 35.568ms
,09-14 09:29:44.284  2351  8136 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-14 09:29:44.290  1801  8130 W GmsApplication: Using Auth Proxy for data requests.
09-14 09:29:44.298  1979  1979 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-14 09:29:44.299  1979  1979 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,09-14 09:29:44.300  1801  8130 W GmsApplication: Using Auth Proxy for data requests.
09-14 09:29:44.300  1979  1979 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-14 09:29:44.307  6521  6521 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-14 09:29:44.311  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-14 09:29:44.315  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-14 09:29:44.316  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-14 09:29:44.318  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-14 09:29:44.319  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-14 09:29:44.320  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-14 09:29:44.331  1034  1056 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8139 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-14 09:29:44.344  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-14 09:29:44.344  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-14 09:29:44.352  2016  2155 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-14 09:29:44.352  2016  2155 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-14 09:29:44.354  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{30c96606 u0 com.lge.launcher2/.Launcher t5} time:210362
09-14 09:29:44.358  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-14 09:29:44.359  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-14 09:29:44.359  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-14 09:29:44.368  2016  2016 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-14 09:29:44.370  2615  2615 D [Concierge]Service: onStartCommand(). Type : 8
09-14 09:29:44.370  2615  2615 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-14 09:29:44.370  2615  2615 D [Concierge]Service: Update widget ID : 11
09-14 09:29:44.372  2016  2016 D [Concierge]WidgetView: change position of spinner
09-14 09:29:44.373  2615  2615 D [Concierge]Service: onStartCommand(). Type : 0
09-14 09:29:44.374  2016  2016 I [Concierge]WidgetView: initWebView(). Time : 1473838184374
,09-14 09:29:44.378  1034  1122 I art     : Explicit concurrent mark sweep GC freed 33770(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 9.960ms total 466.071ms
09-14 09:29:44.390  2016  2016 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 40584093
09-14 09:29:44.390  2016  2016 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-14 09:29:44.390  2016  2016 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-14 09:29:44.394  2016  2016 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@e95271d
09-14 09:29:44.394  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,09-14 09:29:44.396  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-14 09:29:44.397  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-14 09:29:44.402  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-14 09:29:44.402  2016  2016 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-14 09:29:44.403  2016  2016 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-14 09:29:44.403  2016  2016 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473838001652, New one : 1473838184374
09-14 09:29:44.403  2016  2016 D [Concierge]WidgetView: Unregister all receivers
09-14 09:29:44.403  2016  2016 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-14 09:29:44.404  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-14 09:29:44.407  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-14 09:29:44.408  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-14 09:29:44.410  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-14 09:29:44.411  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-14 09:29:44.411  8139  8139 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-14 09:29:44.411  8139  8139 W LG Account v2.2: No ProfileInfo entries
09-14 09:29:44.411  8139  8139 I LG Account v2.2: isEnabled: false
09-14 09:29:44.412  8139  8139 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-14 09:29:44.412  8139  8139 I Feature : [Lifetracker]Country: EU
09-14 09:29:44.412  8139  8139 I Feature : [Lifetracker]Operator: OPEN
09-14 09:29:44.412  8139  8139 I Feature : [Lifetracker]Ranking support: false
09-14 09:29:44.412  8139  8139 I Feature : [Lifetracker]Comfort support: false
09-14 09:29:44.412  8139  8139 I Feature : [Lifetracker]Accessory: true
09-14 09:29:44.412  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-14 09:29:44.412  8139  8139 I Feature : [Lifetracker]Health device: true
09-14 09:29:44.412  8139  8139 I Feature : [Lifetracker]Extra Pedometer: false
09-14 09:29:44.412  8139  8139 I Feature : [Lifetracker]Blood glucose device: false
09-14 09:29:44.412  8139  8139 I Feature : [Lifetracker]Device Number: 3
09-14 09:29:44.413  8139  8139 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,09-14 09:29:44.417  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-14 09:29:44.418  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-14 09:29:44.442  1034  1993 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8161 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-14 09:29:44.444  1034  1993 I ActivityManager: Killing 7036:com.lge.formmanager/u0a26 (adj 15): empty #17
09-14 09:29:44.472  2016  2016 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-14 09:29:44.477  8088  8088 D AndroidRuntime: Shutting down VM
09-14 09:29:44.485  2016  2016 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-14 09:29:44.485  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-14 09:29:44.487  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-14 09:29:44.502  1034  1100 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-14 09:29:44.506  1034  1100 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-14 09:29:44.508  2016  2016 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3e7d17ce time:210517
09-14 09:29:44.523  1034  1560 W libprocessgroup: failed to open /acct/uid_10026/pid_7036/cgroup.procs: No such file or directory
,09-14 09:29:44.537  8161  8161 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-14 09:29:44.537  8161  8161 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-14 09:29:44.538  8161  8161 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-14 09:29:44.538  8161  8161 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,09-14 09:29:44.539  8161  8161 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-14 09:29:44.539  8161  8161 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-14 09:29:44.555  1034  1122 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8178 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-14 09:29:44.557  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-14 09:29:44.598  1034  1916 I ActivityManager: Killing 7293:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-14 09:29:44.620  2016  2016 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-14 09:29:44.625  8161  8161 D PackageIntentReceiver: Not supported Hotkey customization function 
09-14 09:29:44.654  2016  2888 I GBoardtInterface: onReloaded()
,09-14 09:29:44.656  2016  2016 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,09-14 09:29:44.663  1034  1943 W libprocessgroup: failed to open /acct/uid_10046/pid_7293/cgroup.procs: No such file or directory
09-14 09:29:44.665  3837  3855 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-14 09:29:44.667  3837  4466 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-14 09:29:44.669  8161  8161 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
09-14 09:29:44.669  8161  8161 D HideNavigationAppsReceiver: replacing : false
09-14 09:29:44.670  8161  8161 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
09-14 09:29:44.672  8161  8161 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
09-14 09:29:44.672  8161  8161 D ButtonCombinationReceiver: replacing : false
09-14 09:29:44.672  1889  1889 D ActionManagerService: notifyUserLog: 1000001
09-14 09:29:44.674  3837  4472 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,09-14 09:29:44.674  3837  4472 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-14 09:29:44.676  1889  1889 D ActionManagerService: notifyUserLog: 1000001
09-14 09:29:44.677  3837  4472 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,09-14 09:29:44.677  3837  4472 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-14 09:29:44.677  3837  4472 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-14 09:29:44.677  3837  4472 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-14 09:29:44.677  3837  3855 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-14 09:29:44.680  1034  1883 I ActivityManager: Killing 7331:com.android.chrome/u0a57 (adj 15): empty #17
09-14 09:29:44.744  1034  1587 W libprocessgroup: failed to open /acct/uid_10057/pid_7331/cgroup.procs: No such file or directory
09-14 09:29:44.745  2016  2016 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-14 09:29:44.745  2016  2016 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,09-14 09:29:44.746  2016  2016 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-14 09:29:44.746  2016  2016 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-14 09:29:44.749  4602  8197 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-14 09:29:44.749  2016  2016 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-14 09:29:44.749  2016  2016 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-14 09:29:44.771  1034  1942 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8198 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-14 09:29:44.775  1034  1970 V SIM_STK : Menu title from STK is T-Mobile
,09-14 09:29:44.778   332   332 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 204us total 9.352ms
09-14 09:29:44.787   332   332 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 188us total 8.952ms
,09-14 09:29:44.796   332   332 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 181us total 8.784ms
09-14 09:29:44.824  4602  8197 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 76 ms] updated apps [took 76 ms] 
,09-14 09:29:44.842  8198  8198 D DocsApplication: Installing DEX configuration.
,09-14 09:29:44.847  8198  8198 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-14 09:29:44.849  8198  8198 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1e45ef74 com.google.android.apps.docs}
09-14 09:29:44.851  8198  8198 D TAG     : onCreate()
09-14 09:29:44.855  8198  8198 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer

```
