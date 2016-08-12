#### Test 79751015f24a8ad_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-12 17:17:42.040  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1031150550 [*alarm*], flags=0x0
,--------- beginning of main
08-12 17:17:44.169  6750  6750 D AndroidRuntime: 
08-12 17:17:44.169  6750  6750 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 17:17:44.175  6750  6750 D AndroidRuntime: CheckJNI is OFF
08-12 17:17:44.300  6750  6750 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 17:17:44.305  1034  1698 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 17:17:44.316  1939  3993 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-12 17:17:44.319  1034  1698 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-12 17:17:44.320  1034  1698 D ActivityManager: setTaskToReturnTo : TaskRecord{3e354ec6 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 17:17:44.320  1034  1698 D ActivityManager: setTaskToReturnTo : TaskRecord{3e354ec6 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 17:17:44.321  1034  1698 D WindowStateEx: AppWindowTokenEx init.. 
08-12 17:17:44.322   336   345 E GBMv2   : DFP En is all cleared set to be enabled
08-12 17:17:44.356  1034  1698 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6769 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 17:17:44.357  6750  6750 D AndroidRuntime: Shutting down VM
08-12 17:17:44.423  1939  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-12 17:17:44.423  1939  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{395fb645 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 17:17:44.424  1939  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-12 17:17:44.425  1939  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{15a7d19a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 17:17:44.488  6769  6769 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-12 17:17:44.562  6769  6769 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-12 17:17:44.577  6769  6769 I LibraryLoader: Loading: webviewchromium
08-12 17:17:44.579  6769  6769 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8024-8027)
08-12 17:17:44.580  6769  6769 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-12 17:17:44.611  6769  6769 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2de30d3b}
,08-12 17:17:44.613  6769  6769 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 17:17:44.614  6769  6769 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 17:17:44.625  6769  6769 I BrowserStartupController: Initializing chromium process, renderers=0
,08-12 17:17:44.626  6769  6769 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 17:17:44.636  6769  6769 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-12 17:17:44.637  6769  6769 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-12 17:17:44.637  6769  6769 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-12 17:17:44.648  6769  6769 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 17:17:44.648  6769  6769 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 17:17:44.648  6769  6769 I Adreno-EGL: Build Date: 12/12/14 금
08-12 17:17:44.648  6769  6769 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-12 17:17:44.648  6769  6769 I Adreno-EGL: Remote Branch: 
08-12 17:17:44.648  6769  6769 I Adreno-EGL: Local Patches: 
08-12 17:17:44.648  6769  6769 I Adreno-EGL: Reconstruct Branch: 
08-12 17:17:44.674   312  2187 V AudioPolicyService: registerClient() client 0xb1006200, uid 10118
,08-12 17:17:44.680  1034  1095 D BluetoothManagerService: Message: 20
08-12 17:17:44.680  1034  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5e60520:true
08-12 17:17:44.742  6769  6800 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-12 17:17:44.745  6769  6769 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-12 17:17:44.764  6769  6769 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 17:17:44.770  6769  6769 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 17:17:44.774  6769  6769 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-12 17:17:44.777  6769  6769 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 17:17:44.777  6769  6769 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-12 17:17:44.794  6769  6769 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 17:17:44.801  6769  6769 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 17:17:44.802  6769  6769 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 17:17:44.836  6769  6812 D OpenGLRenderer: Render dirty regions requested: true
08-12 17:17:44.836  6769  6812 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 17:17:44.844  6769  6812 D OpenGLRenderer: Enabling debug mode 0
,08-12 17:17:44.856  6769  6769 D Atlas   : Validating map...
,08-12 17:17:44.862  1034  1938 D SplitWindow: check instance of lgWin Window{c77e05a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 17:17:44.917  6769  6810 D LgDataFeature: LgDataFeature() Constructor: none
08-12 17:17:44.917  6769  6810 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-12 17:17:44.963  1034  1096 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +542ms (total +640ms)
08-12 17:17:44.963  6769  6769 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ccc1146 time:298411
,08-12 17:17:44.963  1034  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2dd70e87 u0 com.test.thalitest/.MainActivity t6} time:298411
08-12 17:17:45.092  6769  6769 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 17:17:45.156  6769  6810 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-12 17:17:45.156  6769  6810 I chromium: 
,08-12 17:17:45.316  6769  6823 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,08-12 17:17:45.326  6769  6769 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-12 17:17:45.326  6769  6769 I chromium: 
08-12 17:17:45.343  6769  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 17:17:45.343  6769  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 17:17:45.343  6769  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 17:17:45.343  6769  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 17:17:45.343  6769  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 17:17:45.343  6769  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20eb332a added. We now have 1 listener(s)
08-12 17:17:45.351  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 17:17:45.355  6769  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-12 17:17:45.356  6769  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-12 17:17:45.358  6769  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 17:17:45.359  6769  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 17:17:45.374  6769  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 17:17:45.374  6769  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 17:17:45.374  6769  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 17:17:45.374  6769  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-12 17:17:45.374  6769  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 17:17:45.374  6769  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 17:17:45.374  6769  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 17:17:45.374  6769  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 17:17:45.374  6769  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 17:17:45.374  6769  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 17:17:45.374  6769  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 17:17:45.374  6769  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 17:17:45.374  6769  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 17:17:45.374  6769  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-12 17:17:45.374  6769  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22642c91 added. We now have 1 listener(s)
,08-12 17:17:45.375  6769  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 17:17:45.375   336   347 E GBMv2   : DFP En is all cleared set to be enabled
08-12 17:17:45.375   336   347 E GBMv2   : Set value is all cleared set the max
08-12 17:17:45.375   336   347 I GBMv2   : DFP Enabled. Ignore VFP set
08-12 17:17:45.380  1034  1405 D WifiService: New client listening to asynchronous messages
08-12 17:17:45.388  6769  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 17:17:45.388  6769  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 17:17:45.389  6769  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 17:17:45.389  6769  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 17:17:45.389  6769  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 17:17:45.551  1034  1957 I art     : Explicit concurrent mark sweep GC freed 29925(1420KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.579ms total 150.665ms
,08-12 17:17:45.556  6769  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 17:17:45.557  1034  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 17:17:45.558  6769  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-12 17:17:45.569  6769  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 17:17:45.570  6769  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 17:17:45.570  6769  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 17:17:45.570  6769  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 17:17:45.570  6769  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 17:17:45.570  6769  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 17:17:45.570  6769  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 17:17:45.570  6769  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 17:17:45.570  6769  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 17:17:45.570  6769  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 17:17:45.570  6769  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 17:17:45.576  6769  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 17:17:45.578  6769  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 17:17:45.580  6769  6823 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 17:17:45.632  6769  6769 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 17:17:46.519  6769  6826 W jxcore-log: Initializing JXcore engine
08-12 17:17:46.519  6769  6826 W jxcore-log: JXcore engine is ready
,08-12 17:17:46.550  6826  6826 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8327]" dev="sockfs" ino=8327 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 17:17:46.550  6826  6826 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-12 17:17:46.550  6826  6826 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8470]" dev="sockfs" ino=8470 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 17:17:46.550  6826  6826 W Thread-777: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-12 17:17:46.550  6826  6826 W Thread-777: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33053]" dev="sockfs" ino=33053 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-12 17:17:46.569  6769  6826 W jxcore-log: Starting JXcore engine
08-12 17:17:46.642  6769  6826 W jxcore-log: Platform android
08-12 17:17:46.642  6769  6826 W jxcore-log: 
08-12 17:17:46.642  6769  6826 W jxcore-log: Process ARCH arm
08-12 17:17:46.642  6769  6826 W jxcore-log: 
,08-12 17:17:46.854  6769  6826 I jxcore-log: JXcore Cordova bridge is ready!
08-12 17:17:46.854  6769  6826 I jxcore-log: 
08-12 17:17:46.854  6769  6826 W jxcore-log: JXcore engine is started
,08-12 17:17:46.866  6769  6823 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 17:17:46.874  6769  6769 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 17:18:00.064  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 17:18:00.064  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 17:18:00.064  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 17:18:00.065  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-12 17:18:00.066  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 17:18:00.066  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-12 17:18:00.067  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-12 17:18:00.068  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 17:18:02.719  6769  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 17:18:02.719  6769  6826 I jxcore-log: 
08-12 17:18:02.721  6769  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 17:18:02.721  6769  6826 I jxcore-log: 
,08-12 17:18:02.726  6769  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 17:18:02.726  6769  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 17:18:02.726  6769  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 17:18:02.726  6769  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 17:18:02.726  6769  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 17:18:02.726  6769  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 17:18:02.726  6769  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 17:18:02.726  6769  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 17:18:02.729  6769  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 17:18:02.731  6769  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 17:18:02.731  6769  6826 I jxcore-log: 
08-12 17:18:02.732  6769  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 17:18:02.732  6769  6826 I jxcore-log: 
08-12 17:18:03.065  6769  6826 I jxcore-log: Unit Test app is loaded
08-12 17:18:03.065  6769  6826 I jxcore-log: 
,08-12 17:18:03.071  6769  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 17:18:03.071  6769  6826 I jxcore-log: 
08-12 17:18:03.075  6769  6826 I jxcore-log: My device name is: LGE-LG-D855
08-12 17:18:03.075  6769  6826 I jxcore-log: 
08-12 17:18:03.076  6769  6826 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 17:18:03.076  6769  6826 I jxcore-log: 
08-12 17:18:03.086  6769  6769 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 17:18:05.302  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 17:18:05.302  6769  6826 I jxcore-log: 
,08-12 17:18:05.932  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 17:18:05.932  6769  6826 I jxcore-log: 
,08-12 17:18:05.958  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 17:18:05.958  6769  6826 I jxcore-log: 
,08-12 17:18:07.284  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 17:18:07.284  6769  6826 I jxcore-log: 
,08-12 17:18:07.510  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 17:18:07.510  6769  6826 I jxcore-log: 
,08-12 17:18:07.517  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 17:18:07.517  6769  6826 I jxcore-log: 
,08-12 17:18:07.522  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 17:18:07.522  6769  6826 I jxcore-log: 
,08-12 17:18:07.538  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 17:18:07.538  6769  6826 I jxcore-log: 
,08-12 17:18:07.544  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 17:18:07.544  6769  6826 I jxcore-log: 
,08-12 17:18:08.197  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 17:18:08.197  6769  6826 I jxcore-log: 
,08-12 17:18:08.211  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 17:18:08.211  6769  6826 I jxcore-log: 
,08-12 17:18:08.220  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 17:18:08.220  6769  6826 I jxcore-log: 
,08-12 17:18:08.226  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 17:18:08.226  6769  6826 I jxcore-log: 
,08-12 17:18:08.274  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 17:18:08.274  6769  6826 I jxcore-log: 
,08-12 17:18:08.327  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 17:18:08.327  6769  6826 I jxcore-log: 
,08-12 17:18:08.335  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 17:18:08.335  6769  6826 I jxcore-log: 
,08-12 17:18:08.494  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 17:18:08.494  6769  6826 I jxcore-log: 
,08-12 17:18:08.523  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 17:18:08.523  6769  6826 I jxcore-log: 
,08-12 17:18:08.529  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 17:18:08.529  6769  6826 I jxcore-log: 
,08-12 17:18:08.534  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 17:18:08.534  6769  6826 I jxcore-log: 
08-12 17:18:08.552  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 17:18:08.552  6769  6826 I jxcore-log: 
,08-12 17:18:08.633  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 17:18:08.633  6769  6826 I jxcore-log: 
,08-12 17:18:08.646  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 17:18:08.646  6769  6826 I jxcore-log: 
,08-12 17:18:08.674  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 17:18:08.674  6769  6826 I jxcore-log: 
,08-12 17:18:08.688  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 17:18:08.688  6769  6826 I jxcore-log: 
,08-12 17:18:08.706  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 17:18:08.706  6769  6826 I jxcore-log: 
,08-12 17:18:08.741  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 17:18:08.741  6769  6826 I jxcore-log: 
,08-12 17:18:08.747  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 17:18:08.747  6769  6826 I jxcore-log: 
,08-12 17:18:08.950  6769  6826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 17:18:08.950  6769  6826 I jxcore-log: 
,08-12 17:18:08.959  6769  6826 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-12 17:18:08.960  6769  6826 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-12 17:18:08.960  6769  6826 I jxcore-log: 
08-12 17:18:20.635  1034  3497 I LocationManagerService: remove 4511222
,08-12 17:18:20.643  1034  3497 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0],
08-12 17:18:20.643  1034  3497 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-12 17:18:20.645  1034  3497 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-12 17:18:20.647  1034  3497 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-12 17:18:20.649  1034  3497 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-12 17:18:23.222  6769  6826 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-12 17:18:23.222  6769  6826 I jxcore-log: 
,08-12 17:18:23.548  6839  6839 D AndroidRuntime: 
08-12 17:18:23.548  6839  6839 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 17:18:23.553  6839  6839 D AndroidRuntime: CheckJNI is OFF
08-12 17:18:23.679  6839  6839 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 17:18:23.689  1034  1091 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-12 17:18:23.689  1034  1091 I ActivityManager: Killing 6769:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-12 17:18:23.735  1034  2008 I WindowState: WIN DEATH: Window{c77e05a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 17:18:23.737  1034  1405 D WifiService: Client connection lost with reason: 4
08-12 17:18:23.740  1034  2008 D InputDispatcher: Window went away: Window{c77e05a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 17:18:23.915  1034  1091 I ActivityManager:   Force finishing activity ActivityRecord{2dd70e87 u0 com.test.thalitest/.MainActivity t6}
,08-12 17:18:23.946   336   345 E GBMv2   : DFP En is all cleared set to be enabled
,08-12 17:18:23.952  1034  1698 W ActivityManager: Spurious death for ProcessRecord{213a9380 6769:com.test.thalitest/u0a118}, curProc for 6769: null
08-12 17:18:23.953  1034  1116 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-12 17:18:23.960  1034  1116 I ActivityManager:   Force finishing activity ActivityRecord{2dd70e87 u0 com.test.thalitest/.MainActivity t6 f}
,08-12 17:18:23.960  1034  1116 W ActivityManager: Duplicate finish request for ActivityRecord{2dd70e87 u0 com.test.thalitest/.MainActivity t6 f}
,08-12 17:18:23.987  2032  2032 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-12 17:18:23.989  2032  2032 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-12 17:18:23.990  1939  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-12 17:18:23.992  1939  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{116d5acb co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 17:18:23.994  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-12 17:18:23.995  1939  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-12 17:18:23.996  1939  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{13bb2a8 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 17:18:23.996  2032  2128 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-12 17:18:24.009  1903  1903 D ActionManagerService: notifyUserLog: 1000003
08-12 17:18:24.010  3847  4493 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-12 17:18:24.012  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 17:18:24.013  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-12 17:18:24.019  1034  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 17:18:24.023  4613  4613 I art     : Explicit concurrent mark sweep GC freed 461(31KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 561us total 49.578ms
08-12 17:18:24.030  3899  3899 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-12 17:18:24.030  3899  3899 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-12 17:18:24.030  3847  3847 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-12 17:18:24.030  1993  1993 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 17:18:24.036  2485  2617 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 17:18:24.046  6398  6398 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-12 17:18:24.067  1034  1992 V SIM_STK : Menu title from STK is T-Mobile
,08-12 17:18:24.075  1034  1090 W InputMethodInfo: Duplicated subtype definition found: , voice
08-12 17:18:24.108  4502  4502 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 17:18:24.108  4502  4502 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 17:18:24.108  4502  4502 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 17:18:24.108  4502  4502 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-12 17:18:24.109  4502  4502 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 17:18:24.109  4502  4502 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 17:18:24.109  4502  4502 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 17:18:24.109  4502  4502 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 17:18:24.109  4502  4502 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 17:18:24.109  4502  4502 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 17:18:24.109  4502  4502 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 17:18:24.109  4502  4502 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-12 17:18:24.111  1815  1815 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-12 17:18:24.113  2032  2032 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-12 17:18:24.115  1034  1034 I art     : Explicit concurrent mark sweep GC freed 12064(960KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 2.511ms total 136.500ms
08-12 17:18:24.120  2032  2032 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-12 17:18:24.125  2032  2032 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-12 17:18:24.126  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-12 17:18:24.134  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-12 17:18:24.135  1903  1903 D ActionManagerService: notifyUserLog: 1000004
08-12 17:18:24.135  3847  4493 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-12 17:18:24.138  1601  1648 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 17:18:24.138  1601  1648 D KeyguardModel: createShortcutInfo...
08-12 17:18:24.139  3847  3862 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 17:18:24.144  1601  1648 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 17:18:24.144  1601  1648 D KeyguardModel: createShortcutInfo...
,08-12 17:18:24.145  2196  2196 I ConfigService: onCreate
08-12 17:18:24.145  2196  2196 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-12 17:18:24.146  1868  1868 D SplitUIManager: split_name #11 / not available #0
08-12 17:18:24.147  1868  1868 D SplitUIService: removed split : 
08-12 17:18:24.151  1601  1648 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 17:18:24.152  1601  1648 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 17:18:24.152  1601  1648 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-12 17:18:24.153  1601  1648 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 17:18:24.153  2196  2196 I ConfigService: onBind returning update interface
08-12 17:18:24.154  1601  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:18:24.154  1601  1648 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 17:18:24.158  1601  1648 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 17:18:24.158  1601  1648 D KeyguardModel: createShortcutInfo...
,08-12 17:18:24.161  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 17:18:24.161  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-12 17:18:24.180  2196  2196 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-12 17:18:24.180  2196  2196 I ConfigService: onBind returning config service
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262123
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , display: false
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , animation: false }
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262287
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , display: false
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , animation: false }
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , create_time: 1471007226523
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , display: false
08-12 17:18:24.182  2032  2032 I GBoardWebViewUtils: , animation: false }
08-12 17:18:24.182  1815  1815 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-12 17:18:24.186  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-12 17:18:24.186  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-12 17:18:24.187  1601  1648 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 17:18:24.187  1601  1648 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-12 17:18:24.188  1601  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:18:24.188  1601  1648 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 17:18:24.189  2032  6873 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-12 17:18:24.189  1601  1648 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 17:18:24.189  1601  1648 D KeyguardModel: createShortcutInfo...
08-12 17:18:24.197  1601  1648 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 17:18:24.197  1601  1648 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-12 17:18:24.197  1601  1648 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-12 17:18:24.197  1601  1648 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 17:18:24.198  1601  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:18:24.198  1601  1648 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 17:18:24.202  1868  1868 D SplitUIManager: split_name #11 / not available #0
08-12 17:18:24.202  1868  1868 I SplitUIService: split app #11
08-12 17:18:24.208  1034  1034 D administrator: Handling package changes for user 0
08-12 17:18:24.209  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-12 17:18:24.209  1601  1648 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 17:18:24.210  1601  1648 D KeyguardModel: createShortcutInfo...
08-12 17:18:24.214  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-12 17:18:24.214  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-12 17:18:24.216  1815  1815 I ConfigFetchService: service connected
08-12 17:18:24.245  2196  2196 I ConfigService: onDestroy
,08-12 17:18:24.246  1815  6876 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-12 17:18:24.254  1034  1957 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-12 17:18:24.255  3899  3899 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-12 17:18:24.255  3899  3899 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-12 17:18:24.255  3899  3899 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-12 17:18:24.255  3899  3899 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-12 17:18:24.255  3899  3899 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-12 17:18:24.255  3899  3899 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 17:18:24.255  3899  3899 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-12 17:18:24.255  3899  3899 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-12 17:18:24.255  3899  3899 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-12 17:18:24.255  3899  3899 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 17:18:24.255  3899  3899 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-12 17:18:24.258  1034  1938 V SIM_STK : Menu title from STK is T-Mobile
08-12 17:18:24.258  1601  1648 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 17:18:24.258  1601  1648 D KeyguardModel: createShortcutInfo...
,08-12 17:18:24.270  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 17:18:24.272  1601  1648 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 17:18:24.272  1601  1648 D KeyguardModel: createShortcutInfo...
,08-12 17:18:24.275  1601  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:18:24.275  1601  1648 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 17:18:24.275  2032  2032 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-12 17:18:24.281  1601  1648 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 17:18:24.281  1601  1648 D KeyguardModel: createShortcutInfo...
08-12 17:18:24.283  1601  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:18:24.283  1601  1648 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 17:18:24.285  1601  1648 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 17:18:24.285  1601  1648 D KeyguardModel: createShortcutInfo...
,08-12 17:18:24.286  1601  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:18:24.286  1601  1648 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 17:18:24.287  1601  1648 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 17:18:24.287  1601  1648 D KeyguardModel: createShortcutInfo...
08-12 17:18:24.287  5920  6881 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-12 17:18:24.292  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-12 17:18:24.292  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 17:18:24.296   323   417 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-12 17:18:24.297  3238  6883 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-12 17:18:24.308  1815  6884 I PeopleContactsSync: CP2 sync disabled
,08-12 17:18:24.313  1815  4746 I Icing   : doRemovePackageData com.test.thalitest
08-12 17:18:24.341  1815  6882 W GmsApplication: Using Auth Proxy for data requests.
,08-12 17:18:24.348  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 17:18:24.348  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-12 17:18:24.349  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 17:18:24.349  1815  6882 W GmsApplication: Using Auth Proxy for data requests.
08-12 17:18:24.350  1034  1576 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-12 17:18:24.350  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-12 17:18:24.353  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 17:18:24.354  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-12 17:18:24.362  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-12 17:18:24.363  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-12 17:18:24.364  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-12 17:18:24.376  1034  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{23b07cab u0 com.lge.launcher2/.Launcher t5} time:337824
,08-12 17:18:24.384  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-12 17:18:24.384  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 17:18:24.390  2032  2309 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-12 17:18:24.390  2032  2309 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-12 17:18:24.398  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-12 17:18:24.399  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 17:18:24.399  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 17:18:24.407  2032  2032 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-12 17:18:24.410  2032  2032 D [Concierge]WidgetView: change position of spinner
08-12 17:18:24.411  2647  2647 D [Concierge]Service: onStartCommand(). Type : 8
08-12 17:18:24.411  2647  2647 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-12 17:18:24.411  2032  2032 I [Concierge]WidgetView: initWebView(). Time : 1471015104411
08-12 17:18:24.412  2647  2647 D [Concierge]Service: Update widget ID : 11
,08-12 17:18:24.412  2647  2647 D [Concierge]Service: onStartCommand(). Type : 0
08-12 17:18:24.413  5990  5990 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-12 17:18:24.415  1034  1116 I art     : Explicit concurrent mark sweep GC freed 10966(747KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 5.158ms total 257.012ms
08-12 17:18:24.430  2032  2032 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 592689342
08-12 17:18:24.430  2032  2032 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-12 17:18:24.431  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-12 17:18:24.434  2032  2032 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1dc3ae3e
08-12 17:18:24.434  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-12 17:18:24.435  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 17:18:24.435  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 17:18:24.436  6493  6493 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-12 17:18:24.437  2341  6889 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-12 17:18:24.442  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-12 17:18:24.443  2032  2032 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-12 17:18:24.443  2032  2032 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 17:18:24.444  1993  1993 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 17:18:24.444  1993  1993 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-12 17:18:24.445  1993  1993 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,08-12 17:18:24.445  2032  2032 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471014795127, New one : 1471015104411
08-12 17:18:24.445  2032  2032 D [Concierge]WidgetView: Unregister all receivers
08-12 17:18:24.445  2032  2032 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 17:18:24.447  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 17:18:24.448  6398  6398 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-12 17:18:24.448  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-12 17:18:24.449  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-12 17:18:24.450  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-12 17:18:24.452  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-12 17:18:24.453  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-12 17:18:24.453  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 17:18:24.454  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 17:18:24.478  1034  1920 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6891 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-12 17:18:24.502  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-12 17:18:24.510  2032  2032 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-12 17:18:24.511  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-12 17:18:24.512  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 17:18:24.531  2032  2032 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@29280aeb time:337979
,08-12 17:18:24.552  6839  6839 D AndroidRuntime: Shutting down VM
,08-12 17:18:24.571  6891  6891 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-12 17:18:24.572  6891  6891 W LG Account v2.2: No ProfileInfo entries
08-12 17:18:24.572  6891  6891 I LG Account v2.2: isEnabled: false
08-12 17:18:24.572  6891  6891 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-12 17:18:24.572  6891  6891 I Feature : [Lifetracker]Country: EU
08-12 17:18:24.573  6891  6891 I Feature : [Lifetracker]Operator: OPEN
08-12 17:18:24.573  6891  6891 I Feature : [Lifetracker]Ranking support: false
08-12 17:18:24.573  6891  6891 I Feature : [Lifetracker]Comfort support: false
08-12 17:18:24.573  6891  6891 I Feature : [Lifetracker]Accessory: true
08-12 17:18:24.573  6891  6891 I Feature : [Lifetracker]Health device: true
08-12 17:18:24.573  6891  6891 I Feature : [Lifetracker]Extra Pedometer: false
08-12 17:18:24.573  6891  6891 I Feature : [Lifetracker]Blood glucose device: false
08-12 17:18:24.573  6891  6891 I Feature : [Lifetracker]Device Number: 3
,08-12 17:18:24.573  1034  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 17:18:24.573  6891  6891 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-12 17:18:24.578  1034  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-12 17:18:24.603  1034  1957 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6912 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-12 17:18:24.603  1034  1957 I ActivityManager: Killing 6446:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-12 17:18:24.650  2032  2032 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-12 17:18:24.682  1034  1698 W libprocessgroup: failed to open /acct/uid_10008/pid_6446/cgroup.procs: No such file or directory
,08-12 17:18:24.685  2032  2949 I GBoardtInterface: onReloaded()
08-12 17:18:24.687  2032  2032 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-12 17:18:24.688  3847  3862 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 17:18:24.690  3847  4489 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 17:18:24.695  1903  1903 D ActionManagerService: notifyUserLog: 1000001
,08-12 17:18:24.696  3847  4493 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,08-12 17:18:24.696  3847  4493 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 17:18:24.699  1903  1903 D ActionManagerService: notifyUserLog: 1000001
08-12 17:18:24.699  6912  6912 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 17:18:24.699  6912  6912 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-12 17:18:24.700  6912  6912 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 17:18:24.700  6912  6912 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-12 17:18:24.700  3847  4493 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 17:18:24.700  3847  4493 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 17:18:24.700  3847  4493 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-12 17:18:24.700  3847  4493 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-12 17:18:24.701  6912  6912 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 17:18:24.701  3847  3862 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 17:18:24.701  6912  6912 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-12 17:18:24.703  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-12 17:18:24.703  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-12 17:18:24.704  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-12 17:18:24.704  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 17:18:24.706  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-12 17:18:24.706  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 17:18:24.708  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-12 17:18:24.774  6912  6912 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-12 17:18:24.781  6912  6912 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
,08-12 17:18:24.781  6912  6912 D HideNavigationAppsReceiver: replacing : false
08-12 17:18:24.782  6912  6912 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-12 17:18:24.784  6912  6912 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-12 17:18:24.784  6912  6912 D ButtonCombinationReceiver: replacing : false
,08-12 17:18:24.789  1034  1726 I ActivityManager: Killing 2129:com.lge.music/u0a34 (adj 15): empty #17
08-12 17:18:24.798   312  2186 V AudioFlinger: 2129 died, releasing its sessions
08-12 17:18:24.798   312  2186 V AudioFlinger:  pid 1851 @ 0
08-12 17:18:24.798   312  2186 V AudioFlinger:  pid 3347 @ 1
08-12 17:18:24.798   312  2186 V AudioFlinger:  pid 3347 @ 2
,08-12 17:18:24.894  1034  1049 W libprocessgroup: failed to open /acct/uid_10034/pid_2129/cgroup.procs: No such file or directory

```
