#### Test 832760828839a22_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-31 11:31:00.107  1600  1600 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-31 11:31:00.107  1600  1600 I KeyguardUpdateMonitor: called onTimeUpdated()
08-31 11:31:00.107  1600  1600 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-31 11:31:00.108  1600  1600 I [SystemUI]Clock: called onTimeUpdated()
,08-31 11:31:00.120  1600  1600 I LgeClockWidgetControlView: called onTimeUpdated()
08-31 11:31:00.120  1600  1600 I [SystemUI]DateView: called onTimeUpdated()
08-31 11:31:00.124  1600  1600 I [SystemUI]DateView: called onTimeUpdated()
08-31 11:31:00.126  1600  1600 D KeyguardUpdateMonitor: handleTimeUpdate
08-31 11:31:00.435  6806  6806 D AndroidRuntime: 
08-31 11:31:00.435  6806  6806 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 11:31:00.443  6806  6806 D AndroidRuntime: CheckJNI is OFF
08-31 11:31:00.644  6806  6806 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 11:31:00.655  1030  1956 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 11:31:00.670  1939  3998 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-31 11:31:00.676  1030  1956 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-31 11:31:00.677  1030  1956 D ActivityManager: setTaskToReturnTo : TaskRecord{2e188a22 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 11:31:00.678  1030  1956 D ActivityManager: setTaskToReturnTo : TaskRecord{2e188a22 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 11:31:00.679  1030  1956 D WindowStateEx: AppWindowTokenEx init.. 
08-31 11:31:00.680   335   349 E GBMv2   : DFP En is all cleared set to be enabled
08-31 11:31:00.708  1030  1956 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6821 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 11:31:00.711  6806  6806 D AndroidRuntime: Shutting down VM
08-31 11:31:00.772  1939  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-31 11:31:00.772  1939  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3ebe92e0 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 11:31:00.773  1939  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-31 11:31:00.773  1939  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{124f999 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 11:31:00.844  6821  6821 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-31 11:31:00.910  6821  6821 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-31 11:31:00.932  6821  6821 I LibraryLoader: Loading: webviewchromium
,08-31 11:31:00.941  6821  6821 I LibraryLoader: Time to load native libraries: 11 ms (timestamps 6173-6184)
08-31 11:31:00.942  6821  6821 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:31:00.966  6821  6821 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {21dabb8e}
,08-31 11:31:00.967  6821  6821 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:31:00.968  6821  6821 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 11:31:00.981  6821  6821 I BrowserStartupController: Initializing chromium process, renderers=0
08-31 11:31:00.982  6821  6821 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:31:01.000  6821  6821 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-31 11:31:01.001  6821  6821 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-31 11:31:01.002  6821  6821 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-31 11:31:01.011   311  1396 V AudioPolicyService: registerClient() client 0xb101de20, uid 10118
08-31 11:31:01.017  1030  1094 D BluetoothManagerService: Message: 20
08-31 11:31:01.017  1030  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a27059c:true
,08-31 11:31:01.039  6821  6821 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:31:01.039  6821  6821 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:31:01.039  6821  6821 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:31:01.039  6821  6821 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:31:01.039  6821  6821 I Adreno-EGL: Remote Branch: 
08-31 11:31:01.039  6821  6821 I Adreno-EGL: Local Patches: 
08-31 11:31:01.039  6821  6821 I Adreno-EGL: Reconstruct Branch: 
,08-31 11:31:01.160  6821  6867 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-31 11:31:01.164  6821  6821 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-31 11:31:01.185  6821  6821 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:31:01.190  6821  6821 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-31 11:31:01.193  6821  6821 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-31 11:31:01.196  6821  6821 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-31 11:31:01.196  6821  6821 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-31 11:31:01.211  6821  6821 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-31 11:31:01.217  6821  6821 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 11:31:01.217  6821  6821 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:31:01.246  6821  6885 D OpenGLRenderer: Render dirty regions requested: true
08-31 11:31:01.247  6821  6885 I OpenGLRenderer: Initialized EGL, version 1.4
08-31 11:31:01.253  6821  6885 D OpenGLRenderer: Enabling debug mode 0
,08-31 11:31:01.263  6821  6821 D Atlas   : Validating map...
08-31 11:31:01.267  1030  1883 D SplitWindow: check instance of lgWin Window{1289dbf6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 11:31:01.272  1030  1089 W ActivityManager: Activity pause timeout for ActivityRecord{12d55cb3 u0 com.test.thalitest/.MainActivity t6}
,08-31 11:31:01.306  6821  6883 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 11:31:01.306  6821  6883 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:31:01.409  1030  1095 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +638ms (total +728ms)
,08-31 11:31:01.410  1030  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{12d55cb3 u0 com.test.thalitest/.MainActivity t6} time:206653
08-31 11:31:01.416  6821  6821 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@17104fb5 time:206660
08-31 11:31:01.529  6821  6821 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-31 11:31:01.529  6821  6821 I chromium: 
,08-31 11:31:01.542  6821  6821 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 11:31:01.599  6821  6883 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-31 11:31:01.599  6821  6883 I chromium: 
,08-31 11:31:01.742  6821  6896 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435155968
,08-31 11:31:01.764  6821  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 11:31:01.764  6821  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 11:31:01.764  6821  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 11:31:01.764  6821  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 11:31:01.764  6821  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 11:31:01.765  6821  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bccf669 added. We now have 1 listener(s)
08-31 11:31:01.771  1030  1865 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:01.775  6821  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-31 11:31:01.776  6821  6896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-31 11:31:01.777  6821  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:31:01.778  6821  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:31:01.786  6821  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 11:31:01.786  6821  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 11:31:01.786  6821  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 11:31:01.786  6821  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-31 11:31:01.786  6821  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 11:31:01.786  6821  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 11:31:01.786  6821  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 11:31:01.786  6821  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 11:31:01.786  6821  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 11:31:01.786  6821  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 11:31:01.786  6821  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 11:31:01.786  6821  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 11:31:01.786  6821  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 11:31:01.786  6821  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 11:31:01.786  6821  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35287c1c added. We now have 1 listener(s)
,08-31 11:31:01.788  6821  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:31:01.803  6821  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:31:01.803  6821  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 11:31:01.804  6821  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 11:31:01.804  6821  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 11:31:01.804  6821  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-31 11:31:01.955  1030  1046 I art     : Explicit concurrent mark sweep GC freed 32110(1472KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 3.021ms total 156.545ms
,08-31 11:31:01.957  6821  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:01.958  1030  1045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:01.959  1030  1443 D WifiService: New client listening to asynchronous messages
08-31 11:31:01.959  6821  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-31 11:31:01.969  6821  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 11:31:01.969  6821  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:31:01.969  6821  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:01.969  6821  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:01.969  6821  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:01.969  6821  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:01.969  6821  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:01.969  6821  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:31:01.969  6821  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:31:01.969  6821  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 11:31:01.969  6821  6896 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:31:01.974  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:01.975  6821  6896 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 11:31:01.978  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:02.030  6821  6821 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 11:31:02.588   335   377 E GBMv2   : DFP En is all cleared set to be enabled
08-31 11:31:02.588   335   377 E GBMv2   : Set value is all cleared set the max
08-31 11:31:02.588   335   377 I GBMv2   : DFP Enabled. Ignore VFP set
,08-31 11:31:02.982  6821  6899 W jxcore-log: Initializing JXcore engine
08-31 11:31:02.982  6821  6899 W jxcore-log: JXcore engine is ready
,08-31 11:31:03.050  6899  6899 W Thread-781: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7469]" dev="sockfs" ino=7469 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-31 11:31:03.050  6899  6899 W Thread-781: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-31 11:31:03.050  6899  6899 W Thread-781: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7683]" dev="sockfs" ino=7683 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-31 11:31:03.050  6899  6899 W Thread-781: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-31 11:31:03.050  6899  6899 W Thread-781: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32305]" dev="sockfs" ino=32305 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-31 11:31:03.077  6821  6899 W jxcore-log: Starting JXcore engine
,08-31 11:31:03.232  6821  6899 W jxcore-log: Platform android
08-31 11:31:03.232  6821  6899 W jxcore-log: 
08-31 11:31:03.232  6821  6899 W jxcore-log: Process ARCH arm
08-31 11:31:03.232  6821  6899 W jxcore-log: 
,08-31 11:31:03.625  6821  6899 I jxcore-log: JXcore Cordova bridge is ready!
08-31 11:31:03.625  6821  6899 I jxcore-log: 
08-31 11:31:03.626  6821  6899 W jxcore-log: JXcore engine is started
,08-31 11:31:03.636  6821  6896 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-31 11:31:03.640  6821  6821 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 11:31:14.163  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 11:31:14.163  6821  6899 I jxcore-log: 
08-31 11:31:14.166  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 11:31:14.166  6821  6899 I jxcore-log: 
,08-31 11:31:14.170  6821  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:31:14.170  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:14.170  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:14.170  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:14.170  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:14.170  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:14.170  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:31:14.170  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:31:14.172  6821  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:14.174  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 11:31:14.174  6821  6899 I jxcore-log: 
08-31 11:31:14.176  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 11:31:14.176  6821  6899 I jxcore-log: 
08-31 11:31:14.673  6821  6899 I jxcore-log: Unit Test app is loaded
08-31 11:31:14.673  6821  6899 I jxcore-log: 
,08-31 11:31:14.684  6821  6821 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 11:31:14.692  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:31:14.692  6821  6899 I jxcore-log: 
,08-31 11:31:14.703  6821  6899 D executeNativeTests: Running unit tests
,08-31 11:31:14.851  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:31:14.851  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 added. We now have 2 listener(s)
08-31 11:31:14.853  1030  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:31:14.856  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:31:14.856  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:31:14.856  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:31:14.856  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:14.857  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e added. We now have 2 listener(s)
08-31 11:31:14.857  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:31:14.857  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:31:14.859  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:14.865  6821  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:31:14.865  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:14.865  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:14.865  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:14.865  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:14.865  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:14.865  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:31:14.865  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:31:14.868  6821  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:14.868  6821  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:31:14.870  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:14.872  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:14.879  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 11:31:14.883  6821  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:31:14.883  6821  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:31:14.888  6821  6899 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-31 11:31:14.890  6821  6899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-31 11:31:14.890  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:31:14.891  6821  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:31:14.891  6821  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-31 11:31:14.892  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:14.894  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:14.894  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:14.896  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:14.896  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:14.897  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:31:14.897  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:31:14.897  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 removed from the list
08-31 11:31:14.897  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:14.897  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e removed from the list
08-31 11:31:14.897  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:14.898  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:14.898  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:14.898  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:14.900  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:14.900  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:14.900  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:14.900  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:14.902  6821  6899 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 11:31:14.903  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:14.903  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:14.903  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:14.903  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:14.903  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:14.903  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:14.903  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:14.904  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:14.904  6821  6899 E org.thaliproject.p2p.btconnectorl,ib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:14.904  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:14.904  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:14.904  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:14.904  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:14.904  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:31:14.905  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:14.905  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:14.905  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:14.905  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310],
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:31:14.912  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:31:14.913  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:31:14.913  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:31:14.913  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:31:14.913  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:31:14.913  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 11:31:14.913  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 11:31:14.913  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:31:14.913  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-31 11:31:14.913  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:31:14.913  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:14.913  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:14.913  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:14.913  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:14.913  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:14.913  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:14.913  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:14.913  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 11:31:14.914  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:14.914  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:14.914  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:14.914  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:14.914  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:14.914  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:31:14.916  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:14.916  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-31 11:31:14.916  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:14.916  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:14.917  6821  6899 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:31:14.920  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:14.923  6821  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:31:14.923  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:14.923  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:14.923  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:14.923  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:14.923  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:14.923  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:31:14.923  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:31:14.925  6821  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:31:14.925  6821  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:31:14.929  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:31:14.931  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-31 11:31:14.931  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:31:14.931  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:31:14.932  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:31:14.932  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:14.932  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:31:14.936  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:31:14.937  1030  1865 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:14.945  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:31:14.952  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:31:14.955  6821  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 11:31:14.956  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:31:14.956  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:31:14.958  6821  6899 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-31 11:31:14.959  6821  6899 I io.jxcore.node.ConnectionHelper: start: OK
08-31 11:31:14.963  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:14.963  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:14.963  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:14.963  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:14.963  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:14.963  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:31:14.963  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:14.963  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:14.963  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:14.963  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:14.963  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:14.964  6821  6899 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:31:14.965  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:14.969  6821  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:31:14.969  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:14.969  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:14.969  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:14.969  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:14.969  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:14.969  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:31:14.969  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:31:14.971  6821  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:14.971  6821  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:31:14.973  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:14.973  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:31:14.973  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:31:14.973  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:31:14.973  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:14.973  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:31:14.975  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:14.978  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:31:14.979  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:31:14.980  6821  6899 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 11:31:14.981  6821  6899 I io.jxcore.node.ConnectionHelper: start: OK
08-31 11:31:14.982  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:31:14.983  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:14.983  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:14.983  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:14.983  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:14.983  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:31:14.983  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:14.983  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:14.983  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:14.983  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:14.983  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:14.984  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:14.984  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:14.985  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:14.985  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:14.987  6821  6899 D BluetoothLeScanner: could not find callback wrapper
08-31 11:31:14.987  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:14.987  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:14.987  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:14.988  6821  6899 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:31:14.989  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:14.993  6821  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:31:14.993  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:14.993  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:14.993  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:14.993  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:14.993  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:14.993  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:31:14.993  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:31:14.995  6821  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:14.995  6821  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:31:14.997  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:31:14.997  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:31:14.997  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:31:14.997  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:14.998  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:31:14.999  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:15.003  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:15.003  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:31:15.004  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:31:15.005  6821  6899 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 11:31:15.005  6821  6899 I io.jxcore.node.ConnectionHelper: start: OK
08-31 11:31:15.005  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.005  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.005  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:15.007  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.007  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.007  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:31:15.007  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.007  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.007  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:31:15.007  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
,08-31 11:31:15.007  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.007  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.007  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.007  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.008  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.008  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.009  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:15.009  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:15.010  6821  6899 D BluetoothLeScanner: could not find callback wrapper
08-31 11:31:15.010  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:15.010  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.010  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.011  6821  6899 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 11:31:15.011  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.011  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.011  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:15.012  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.012  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.012  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.012  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.012  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.012  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.012  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.012  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.012  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.012  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.012  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.013  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:15.013  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:15.014  6821  6899 D BluetoothLeScan,ner: could not find callback wrapper
08-31 11:31:15.014  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:15.014  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.014  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.015  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 11:31:15.016  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.016  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.016  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:15.016  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.016  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.016  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.016  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.016  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.016  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.016  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.016  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.016  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.016  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.017  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.018  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:15.018  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:15.019  6821  6899 D BluetoothLeScanner: could not find callback wrapper
08-31 11:31:15.019  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:15.019  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.019  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.020  6821  6899 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 11:31:15.020  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.020  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.020  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:15.020  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.020  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.020  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.020  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.020  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.020  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.020  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.020  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.021  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.021  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.021  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.022  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:15.022  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:15.023  6821  6899 D BluetoothLeScanner: could not find callback wrapper
08-31 11:31:15.023  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:15.023  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.023  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.024  6821  6899 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 11:31:15.024  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.024  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.024  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:15.024  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.024  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.024  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.024  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.024  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.024  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.024  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.024  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.024  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.024  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.025  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.026  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:15.026  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:15.028  6821  6899 D BluetoothLeScanner: could not find callback wrapper
08-31 11:31:15.028  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:15.028  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.028  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.029  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:31:15.029  6821  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:31:15.029  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:31:15.029  6821  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:31:15.029  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:31:15.029  6821  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:31:15.029  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.029  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.029  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:15.030  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.030  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.030  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.030  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.030  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.030  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.030  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.030  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.030  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.030  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.031  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.032  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:15.032  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:15.033  6821  6899 D BluetoothLeScanner: could not find callback wrapper
08-31 11:31:15.033  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:15.033  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.033  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.034  6821  6899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:31:15.034  6821  6899 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:31:15.034  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 11:31:15.038  6821  6899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:31:15.038  6821  6899 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 11:31:15.038  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 11:31:15.038  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:31:15.038  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:31:15.038  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 11:31:15.038  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:31:15.038  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:31:15.038  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:31:15.038  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:31:15.038  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 11:31:15.038  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:31:15.038  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 11:31:15.038  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:31:15.038  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:31:15.038  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:31:15.038  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 11:31:15.039  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:31:15.039  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:31:15.039  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 11:31:15.039  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:31:15.039  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:31:15.039  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:31:15.039  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:31:15.039  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:31:15.039  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:31:15.039  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:31:15.039  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 11:31:15.039  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 11:31:15.039  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:31:15.039  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 11:31:15.039  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:31:15.039  6821  6899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 11:31:15.039  6821  6899 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:31:15.040  6821  6899 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 11:31:15.040  6821  6899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:31:15.040  6821  6899 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:31:15.040  6821  6899 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 11:31:15.040  6821  6899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:31:15.040  6821  6899 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:31:15.040  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 11:31:15.045  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-31 11:31:15.047  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 11:31:15.047  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 11:31:15.048  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 11:31:15.048  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 11:31:15.048  6821  6899 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 11:31:15.048  6821  6899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:31:15.048  6821  6899 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 11:31:15.049  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.049  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.049  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:15.051  6821  6910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 845)
08-31 11:31:15.055  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.055  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.055  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.055  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 11:31:15.058  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.058  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.058  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.058  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.058  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.058  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.058  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.058  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.059  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:15.059  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:15.060  6821  6899 D BluetoothLeScanner: could not find callback wrapper
08-31 11:31:15.060  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:15.060  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.060  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.062  6821  6899 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 11:31:15.062  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.062  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.062  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:15.063  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.063  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.063  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.063  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.063  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.063  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.063  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.063  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.063  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.063  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.063  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.064  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:15.064  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:15.065  6821  6899 D BluetoothLeScanner: could not find callback wrapper
08-31 11:31:15.065  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:15.065  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.065  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.066  6821  6899 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 11:31:15.067  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.067  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.067  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:15.067  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.067  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.067  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.067  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.067  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.068  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.068  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.068  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.068  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.068  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.068  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.070  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:15.070  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:15.070  6821  6899 D BluetoothLeScanner: could not find callback wrapper
08-31 11:31:15.070  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:15.070  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.070  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.071  6821  6899 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 11:31:15.071  6821  6899 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 11:31:15.072  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:31:15.077  6821  6899 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 11:31:15.077  6821  6899 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:31:15.077  6821  6899 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 11:31:15.077  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:31:15.077  6821  6899 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 11:31:15.077  6821  6899 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:31:15.077  6821  6899 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:31:15.077  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:31:15.077  6821  6899 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 11:31:15.078  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.078  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.078  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:15.078  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.078  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.078  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.078  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.078  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.078  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.078  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.078  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.078  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.078  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.078  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.079  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:15.079  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:15.079  6821  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 845
08-31 11:31:15.080  6821  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 845)
08-31 11:31:15.080  6821  6899 D BluetoothLeScanner: could not find callback wrapper
08-31 11:31:15.080  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:15.080  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.080  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.080  6821  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 845)
08-31 11:31:15.080  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.080  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.080  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.080  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.080  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.080  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.081  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.081  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.081  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.081  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.081  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.081  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.081  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.081  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.081  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.081  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.081  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.081  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:15.082  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.082  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.082  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.082  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.082  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.082  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.082  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.082  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.082  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.082  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.082  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.084  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:15.084  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:15.088  6821  6899 D BluetoothLeScanner: could not find callback wrapper
08-31 11:31:15.088  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:15.088  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.088  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.090  6821  6899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 11:31:15.091  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:15.092  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 11:31:15.093  6821  6899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 11:31:15.093  6821  6899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 11:31:15.093  6821  6821 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 11:31:15.093  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 11:31:15.093  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:31:15.095  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.095  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 11:31:15.095  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-31 11:31:15.095  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 11:31:15.096  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.096  6821  6899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 11:31:15.096  1030  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:15.099  6821  6917 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:31:15.099  6821  6821 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 11:31:15.099  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.099  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.099  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:31:15.099  6821  6899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:31:15.099  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:31:15.101  3908  3926 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-31 11:31:15.101  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:31:15.101  6821  6899 D BluetoothLeScanner: could not find callback wrapper
08-31 11:31:15.102  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:15.102  6821  6899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:31:15.102  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.102  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.103  6821  6899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:31:15.103  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.103  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.103  6821  6917 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-31 11:31:15.103  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.103  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:15.103  6821  6917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 11:31:15.103  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.103  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.103  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.103  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.103  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.103  6821  6917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 11:31:15.103  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.103  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.103  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.104  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.104  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.104  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.105  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:15.105  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:15.105  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.105  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.106  6821  6899 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 11:31:15.106  6821  6899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 11:31:15.106  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:31:15.106  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:31:15.106  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:31:15.106  6821  6821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:31:15.106  6821  6821 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 11:31:15.108  6821  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:31:15.108  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.108  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.108  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:15.110  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.110  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.110  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.110  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.110  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.110  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.110  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.110  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.110  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.110  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.110  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.111  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:15.111  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:15.111  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.112  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.114  1030  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:15.115  1030  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:15.116  1030  1883 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:15.117  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.117  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.117  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:15.117  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.117  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.117  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.117  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.117  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.117  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.117  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.117  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.117  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.117  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.117  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.119  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:15.119  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:15.119  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.119  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.120  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:15.120  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:15.120  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:15.120  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:15.120  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.120  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.120  6821  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2fe0f9 not in the list
08-31 11:31:15.122  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.122  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.122  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:15.122  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.122  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.122  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:15.122  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:15.123  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:15.123  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:15.123  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:15.123  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3384d83e not in the list
08-31 11:31:15.124  6821  6899 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 11:31:15.125  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:31:15.125  6821  6899 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 11:31:15.125  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:31:15.125  6821  6899 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 11:31:15.125  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:31:15.127  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 11:31:15.127  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 11:31:15.128  6821  6899 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 11:31:15.128  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:31:15.129  6821  6899 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 11:31:15.129  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:31:15.129  6821  6899 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 11:31:15.129  6821  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 11:31:15.129  6821  6899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 11:31:15.130  6821  6899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 11:31:15.130  6821  6899 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 11:31:15.130  6821  6899 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 11:31:15.131  6821  6899 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 11:31:15.131  6821  6899 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 11:31:15.132  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:15.133  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24514a97 added. We now have 2 listener(s)
08-31 11:31:15.133  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:31:15.134  6821  6899 D BluetoothAdapter: enable(): BT is already enabled..!
,08-31 11:31:15.138  1030  1989 D WifiServiceImplEx: setWifiEnabled: true pid=6821, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 11:31:15.139  1030  1989 D WifiService: setWifiEnabled: true pid=6821, uid=10118
08-31 11:31:15.139  1030  1989 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 11:31:15.140  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:15.140  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@320f484 added. We now have 3 listener(s)
08-31 11:31:15.140  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:31:15.144  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:15.144  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a0846d added. We now have 4 listener(s)
08-31 11:31:15.144  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:31:15.146  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:15.147  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32ffc8a2 added. We now have 5 listener(s)
,08-31 11:31:15.147  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:31:15.149  1030  1989 D WifiServiceImplEx: setWifiEnabled: false pid=6821, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 11:31:15.150  1030  1989 D WifiService: setWifiEnabled: false pid=6821, uid=10118
08-31 11:31:15.150  1030  1989 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:31:15.164  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:31:15.165  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:31:15.165  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-31 11:31:15.166  1030  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:31:15.166  1030  1389 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 11:31:15.166  1030  1046 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@36f15b71 mBinding = false
08-31 11:31:15.166  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 11:31:15.167  1030  1389 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 11:31:15.167  1030  1389 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-31 11:31:15.167  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-31 11:31:15.168  1030  1389 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 11:31:15.168  1030  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:31:15.168  1030  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:31:15.168  1030  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,08-31 11:31:15.168  1030  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:31:15.173  6821  6910 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-31 11:31:15.173  6821  6910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 845)
08-31 11:31:15.174  1030  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 11:31:15.174  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 11:31:15.174  1030  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.174  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.174  2711  2711 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:31:15.175  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:31:15.175  1030  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:31:15.176  1030  1389 D WifiNative-wlan0: SET ps 1: returned true
,08-31 11:31:15.176   304   890 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:31:15.183  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:31:15.183  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:31:15.184  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-31 11:31:15.185  1030  1094 D BluetoothManagerService: Message: 2
08-31 11:31:15.187  1030  2856 D DhcpStateMachine: RunningState{ when=-11ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.187  1030  1094 D BluetoothManagerService: Sending off request.
,08-31 11:31:15.189  3908  3926 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-31 11:31:15.191  3908  3983 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-31 11:31:15.191  3908  3983 D BluetoothAdapterProperties: Setting state to 13
08-31 11:31:15.191  3908  3983 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 11:31:15.192  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:15.192  3908  3983 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 11:31:15.192  3908  3983 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 11:31:15.193  3908  3988 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:31:15.193  3908  3983 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 11:31:15.195  3908  4250 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 11:31:15.195  3908  4250 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:31:15.195  3908  4250 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 11:31:15.195  3908  4250 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 11:31:15.195  3908  4250 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 11:31:15.195  3908  4250 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 11:31:15.195  3908  4250 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 11:31:15.195  3908  4250 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-31 11:31:15.196  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:15.196  6821  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:31:15.196  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:15.196  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:15.196  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:15.196  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:31:15.196  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:15.196  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:31:15.196  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:31:15.197  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 11:31:15.197  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:15.197  6821  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:15.197  1030  1094 D BluetoothManagerService: Message: 60
08-31 11:31:15.197  3908  3983 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 11:31:15.197  6821  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:31:15.198  3908  4095 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-31 11:31:15.198  1030  1094 D BluetoothManagerService: ME,SSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 11:31:15.198  3908  4307 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:31:15.198  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-31 11:31:15.199  3908  4251 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:31:15.200  3908  4310 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:31:15.200  3908  4305 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:31:15.202  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:31:15.202  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:31:15.202  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:31:15.202  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:31:15.202  3908  4095 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:31:15.202  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:31:15.202  3908  4095 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:31:15.202  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:31:15.202  3908  4095 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:31:15.202  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-31 11:31:15.202  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 11:31:15.202  3908  4095 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 11:31:15.203  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:15.205  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:15.207  1030  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 11:31:15.208  1030  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-31 11:31:15.208  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:15.208  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:15.208  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:15.208  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:15.208  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:15.208  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:31:15.208  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:15.208  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:31:15.208  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:31:15.209  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:15.209  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:15.218  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:15.218  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:15.218  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported:, true
08-31 11:31:15.218  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:15.218  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:15.218  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:31:15.218  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:15.218  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:15.218  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:31:15.220  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:15.220  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:31:15.228  1030  1974 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-31 11:31:15.231  1030  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.231  1030  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.231  1030  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-31 11:31:15.231  1030  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.231  1030  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,08-31 11:31:15.236  1030  1089 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6929 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-31 11:31:15.239  1030  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:15.239  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:15.239  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:15.240  1030  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:15.240  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:15.241  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:15.241  1030  1388 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.241  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.241  1030  1389 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 11:31:15.241  1030  1388 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1dd532dc
08-31 11:31:15.242  1030  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:15.242  1030  1388 D LGWifiP2pService: P2pDisablingState
08-31 11:31:15.242  1030  1388 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.242  1030  1388 D LGWifiP2pService: p2p socket connection lost
08-31 11:31:15.242  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:15.242  1030  1388 D LGWifiP2pService: P2pDisabledState
08-31 11:31:15.242  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:15.243  1030  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,08-31 11:31:15.246  1030  1388 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.246  1030  1388 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.247  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:15.247  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 11:31:15.247  2711  2711 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:31:15.247  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:31:15.248  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:31:15.248  1030  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:31:15.248  1030  1389 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:31:15.248  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:15.248  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:15.248  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:15.248  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:15.248  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:15.248  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:31:15.248  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:15.248  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:15.248  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:31:15.248   304   890 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:31:15.248  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:15.248  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:31:15.249  1030  1444 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-31 11:31:15.249  1030  1444 D DSQN    : disableDataServiceNotify
08-31 11:31:15.249  3908  3908 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:15.249  1030  1444 D DSQN    : stop dsqn bin
08-31 11:31:15.249  3908  3908 D BluetoothMapService: STATE_TURNING_OFF
08-31 11:31:15.249   304  6941 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 11:31:15.250  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:15.250  1030  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-31 11:31:15.250  3908  3908 V BluetoothMapService: Handler(): got msg=4
08-31 11:31:15.250  3908  3908 D BluetoothMapService: MAP Service closeService in
08-31 11:31:15.250  3908  3908 D BluetoothMapMasInstance: MAP Service shutdown
08-31 11:31:15.250  3908  3908 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:31:15.251  3908  3908 V BluetoothMapService: MAP Service closeService out
08-31 11:31:15.251  1030  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 11:31:15.251  3908  3908 V BtOppService: Receiver DISABLED_ACTION 
08-31 11:31:15.251  3908  3908 I BtOppRfcommListener: stopping Accept Thread
08-31 11:31:15.251  3,908  3908 V BtOppRfcommListener: close mBtServerSocket
08-31 11:31:15.251  3908  3908 V BtOppRfcommListener: waiting for thread to terminate
08-31 11:31:15.252  3908  4305 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 11:31:15.252  3908  3908 V BtOppRfcommListener: done waiting for thread to terminate
08-31 11:31:15.256  1030  1444 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-31 11:31:15.256  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:15.256  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:15.256  1030  1444 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-31 11:31:15.258  1030  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.258  1030  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.258  1030  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 11:31:15.258  1030  1444 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-31 11:31:15.259  1030  1444 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-31 11:31:15.259  1030  1444 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 11:31:15.259  1030  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:31:15.261  1600  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 11:31:15.298  1030  1089 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6950 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 11:31:15.300  1030  1389 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 11:31:15.300  1030  1444 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:15.300  1030  1389 D WifiNative-p2p0: TERMINATE: returned true
08-31 11:31:15.300  1030  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:31:15.300  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:31:15.300  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:31:15.300  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:31:15.301  1030  1444 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:15.301  3908  3908 V BtOppService: onDestroy
08-31 11:31:15.301  1030  1444 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:15.301  1030  1444 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:15.301  1030  1444 D NetworkManagementService: Removing idletimer
08-31 11:31:15.301  1848  1848 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:15.301  1030  1444 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:15.302  1848  1848 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 11:31:15.302  3908  3908 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-31 11:31:15.302  1030  1444 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 11:31:15.305  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-31 11:31:15.307  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-31 11:31:15.309  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:15.310  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:15.310  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:31:15.310  1030  1030 D WifiHS20: hidePasspointNotification off =false
,08-31 11:31:15.312  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:31:15.312  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:15.313  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:31:15.313  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 11:31:15.313  1030  1030 D RttService: SCAN_AVAILABLE : 1
08-31 11:31:15.313  1030  1555 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.313  1030  1556 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.314  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:15.314  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:15.315  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-31 11:31:15.315  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 11:31:15.315  1939  1939 D WfdsService: WifiP2pState is changed : false
08-31 11:31:15.316  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:15.316  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:15.316  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:31:15.317  1939  2290 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 11:31:15.317  1939  2290 D WfdsService: Set the WFDS Monitor: false
08-31 11:31:15.318  1939  2290 D WfdsMonitor: WFDS Monitor is stopped
08-31 11:31:15.318  1939  2290 D WfdsService: STATE : WfdsDisabledState - enter
08-31 11:31:15.318  1939  2771 D CtrlSupplicant: Received on exit socket, terminate
08-31 11:31:15.318  1939  2771 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 11:31:15.318  1939  2771 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 11:31:15.318  1939  2771 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-31 11:31:15.318  1939  2290 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 11:31:15.318  1939  2298 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 11:31:15.318  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:15.321   339   339 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 22.363ms
08-31 11:31:15.321  1030  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 11:31:15.322  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 11:31:15.322  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:31:15.322  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:31:15.322  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:31:15.323  1030  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 11:31:15.324  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 11:31:15.324  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:31:15.324  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (,unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:31:15.324  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:31:15.325  1030  1389 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:15.325  1030  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:31:15.334  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 11:31:15.334  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:15.334  1030  1030 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-31 11:31:15.336  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,08-31 11:31:15.335  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:15.337  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:15.337  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:15.337  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:15.337  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:15.337  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:15.337  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:31:15.337  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:31:15.337  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:15.337  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:15.337  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:31:15.338  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:15.338  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:31:15.338  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:15.340  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:15.340  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:15.340  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:15.340  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:15.340  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:31:15.340  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:31:15.340  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:15.340  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:15.340  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:31:15.341  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:15.341  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:31:15.341  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 11:31:15.341  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:15.342  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:15.343   339   339 I art     : Explicit concurren,t mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 399us total 21.429ms
,08-31 11:31:15.361   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 354us total 17.543ms
08-31 11:31:15.364  6950  6950 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:31:15.364  6950  6950 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-31 11:31:15.365  6950  6950 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:31:15.365  6950  6950 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-31 11:31:15.366  6950  6950 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 11:31:15.366  6950  6950 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 11:31:15.369  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:31:15.369  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:15.370  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:15.382  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:31:15.383  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:31:15.384  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:15.384  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:15.417  2711  2711 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-31 11:31:15.417  2711  2711 I wpa_supplicant: monitor socket send errors count : 1
08-31 11:31:15.417  2711  2711 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1939-2\x00 that cannot receive messages
08-31 11:31:15.419  1030  2757 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-31 11:31:15.419  1030  2757 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 11:31:15.426  6929  6929 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-31 11:31:15.427  6929  6929 W LG Account v2.2: No ProfileInfo entries
08-31 11:31:15.427  6929  6929 I LG Account v2.2: isEnabled: false
08-31 11:31:15.427  6929  6929 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 11:31:15.427  6929  6929 I Feature : [Lifetracker]Country: EU
08-31 11:31:15.427  6929  6929 I Feature : [Lifetracker]Operator: OPEN
08-31 11:31:15.427  6929  6929 I Feature : [Lifetracker]Ranking support: false
,08-31 11:31:15.427  6929  6929 I Feature : [Lifetracker]Comfort support: false
08-31 11:31:15.427  6929  6929 I Feature : [Lifetracker]Accessory: true
08-31 11:31:15.427  6929  6929 I Feature : [Lifetracker]Health device: true
08-31 11:31:15.427  6929  6929 I Feature : [Lifetracker]Extra Pedometer: false
08-31 11:31:15.427  6929  6929 I Feature : [Lifetracker]Blood glucose device: false
08-31 11:31:15.427  6929  6929 I Feature : [Lifetracker]Device Number: 3
08-31 11:31:15.431  1030  2856 D DhcpStateMachine: StoppedState
08-31 11:31:15.431  1030  2856 D DhcpStateMachine: StoppedState{ when=-183ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:15.432  1030  1389 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-31 11:31:15.433  1030  1389 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-31 11:31:15.434  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:15.456  2711  2711 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 11:31:15.457  1030  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-31 11:31:15.457  1030  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:31:15.457  1030  1094 D Tethering: InitialState.processMessage what=4
08-31 11:31:15.457  1030  2757 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:31:15.458  1030  2757 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 11:31:15.458  2711  2711 W wpa_supplicant: USIM:  scard_deinit function
08-31 11:31:15.459  1030  1389 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=220687
08-31 11:31:15.459  1030  1389 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=220687
08-31 11:31:15.460  1030  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:31:15.460  1030  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:31:15.460  1030  1389 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=220689  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 11:31:15.461  1030  1389 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=220689  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 11:31:15.487  6950  6950 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-31 11:31:15.488  1030  1956 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6970 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 11:31:15.491  1030  1956 I ActivityManager: Killing 6330:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-31 11:31:15.541  2711  2711 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 11:31:15.542  1030  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-31 11:31:15.542  1030  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 11:31:15.542  1030  2757 D WifiMonitor: Disconnecting from the supplicant, no more events
08-31 11:31:15.545  1030  1389 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-31 11:31:15.556  1030  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:31:15.557  1030  2048 W libprocessgroup: failed to open /acct/uid_10004/pid_6330/cgroup.procs: No such file or directory
,08-31 11:31:15.564  1030  1094 D BluetoothManagerService: Message: 20
08-31 11:31:15.564  1030  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b6ecf30:true
,08-31 11:31:15.576  3908  3908 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:31:15.576  3908  3908 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:15.576  3908  3908 V BluetoothPbapReceiver: ***********state = 13
08-31 11:31:15.579  3908  3908 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-31 11:31:15.580  3908  3908 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:15.580  3908  3908 V BluetoothPbapService: state: 13
08-31 11:31:15.581  3908  3908 V BluetoothPbapService: Pbap Service closeService in
08-31 11:31:15.582  3908  3908 V BluetoothPbapService: successfully stopped pbap service
,08-31 11:31:15.582  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:31:15.582  3908  3908 V BluetoothPbapService: Pbap Service closeService out
08-31 11:31:15.582  3908  3908 V BluetoothPbapService: Pbap Service onDestroy
08-31 11:31:15.582  3908  3908 V BluetoothPbapService: Pbap Service closeService in
08-31 11:31:15.582  3908  3908 V BluetoothPbapService: Pbap Service closeService out
08-31 11:31:15.583  3908  3908 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-31 11:31:15.589  1030  1094 D BluetoothManagerService: Message: 30
08-31 11:31:15.593  1030  1094 D BluetoothManagerService: Message: 30
08-31 11:31:15.595  6950  6950 D LocalBluetoothProfileManager: Adding local MAP profile
08-31 11:31:15.597  6950  6950 D BluetoothMap: Create BluetoothMap proxy object
,08-31 11:31:15.598  1030  1094 D BluetoothManagerService: Message: 30
08-31 11:31:15.603  1030  1094 D BluetoothManagerService: Message: 30
08-31 11:31:15.605  6950  6950 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-31 11:31:15.606  6950  6950 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-31 11:31:15.607  6821  6821 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-31 11:31:15.622  6950  6950 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-31 11:31:15.627  6950  6950 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-31 11:31:15.631  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:31:15.637  6950  6950 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:31:15.640  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:31:15.648  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:31:15.648  6950  6950 D BluetoothInputDevice: Proxy object connected
08-31 11:31:15.649  6950  6950 D HidProfile: Bluetooth service connected
,08-31 11:31:15.649  1030  1389 D WifiOffDelayIfNotUsed: stopMonitoring
08-31 11:31:15.649  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:31:15.649  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:31:15.649  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:31:15.650  6950  6950 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:31:15.650  6950  6950 D PanProfile: Bluetooth service connected
08-31 11:31:15.651  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:15.652  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-31 11:31:15.652  1939  1939 D WfdsService: Supplicant Connection state is changed : false
08-31 11:31:15.652  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 11:31:15.653  1030  1438 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-31 11:31:15.653  1030  1438 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-31 11:31:15.653  1939  2290 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-31 11:31:15.653  1939  2290 D WfdsService: Set the WFDS Monitor: false
08-31 11:31:15.653  1939  2290 D WfdsMonitor: WFDS Monitor is stopped
08-31 11:31:15.653  2478  2478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:15.654  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:15.654  1030  2009 I ActivityManager: Killing 6542:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-31 11:31:15.656  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:15.656  6950  6950 D BluetoothMap: Proxy object connected
08-31 11:31:15.658  6950  6950 D MapProfile: Bluetooth service connected
08-31 11:31:15.659  6950  6950 D BluetoothMap: getConnectedDevices()
08-31 11:31:15.659  6950  6950 D BluetoothMap: Bluetooth is Not enabled
08-31 11:31:15.660  6950  6950 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 11:31:15.662  6950  6950 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-31 11:31:15.690  1030  1884 W libprocessgroup: failed to open /acct/uid_10008/pid_6542/cgroup.procs: No such file or directory
,08-31 11:31:15.701  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:31:15.758  6950  6950 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:31:15.759  6950  6950 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:31:15.771  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:31:15.774  6950  6950 D BluetoothPermissionRequest: onReceive
08-31 11:31:15.778  6950  6950 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 11:31:15.787  1030  1915 I ActivityManager: Killing 6037:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-31 11:31:15.789  6950  6950 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:31:15.852  1030  1389 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:15.854  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-31 11:31:15.862  3908  3908 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-31 11:31:15.862  3908  3908 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-31 11:31:15.862  1030  1648 W libprocessgroup: failed to open /acct/uid_10011/pid_6037/cgroup.procs: No such file or directory
08-31 11:31:15.865  3908  3908 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-31 11:31:15.885  3908  3908 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:15.885  3908  3908 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-31 11:31:15.971  1030  2047 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6998 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-31 11:31:15.976  3908  3908 V BluetoothFtpService: Ftp Service onStartCommand
08-31 11:31:15.976  3908  3908 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:15.977  3908  3908 V BluetoothFtpService: Ftp Service closeService
08-31 11:31:15.977  3908  3908 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-31 11:31:15.979  3908  3908 V BluetoothFtpService: successfully stopped ftp service
08-31 11:31:15.979  3908  3908 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:31:15.980  3908  3908 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:31:15.980  3908  3908 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:31:15.980  3908  3908 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:15.980  3908  3908 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-31 11:31:15.980  3908  3908 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 11:31:15.981  3908  3908 V BluetoothFtpService: Ftp Service onDestroy
08-31 11:31:15.981  3908  3908 V BluetoothFtpService: Ftp Service closeService
08-31 11:31:16.046  1030  1884 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7015 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 11:31:16.047  3908  3908 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:31:16.047  3908  3908 V BluetoothSapService: state: 13
08-31 11:31:16.047  3908  3908 V BluetoothSapService: Stopping SAP server process
08-31 11:31:16.049  3908  3908 V BluetoothSapService: Sap Service closeSapService in
08-31 11:31:16.049  3908  3908 V BluetoothSapService: Close listen Socket : 
08-31 11:31:16.049  3908  3908 V BluetoothSapService: Close rfcomm Socket : 
08-31 11:31:16.049  3908  3908 V BluetoothSapService: Close sapd  Socket : 
08-31 11:31:16.055  3908  3908 V BluetoothSapService: Sap Service closeSapService out
08-31 11:31:16.055  3908  3908 V BluetoothSapService: Sap Service onDestroy
08-31 11:31:16.055  3908  3908 V BluetoothSapService: Sap Service closeSapService in
08-31 11:31:16.055  3908  3908 V BluetoothSapService: Close listen Socket : 
08-31 11:31:16.055  3908  3908 V BluetoothSapService: Close rfcomm Socket : 
08-31 11:31:16.055  3908  3908 V BluetoothSapService: Close sapd  Socket : 
08-31 11:31:16.056  3908  3908 V BluetoothSapService: Sap Service closeSapService out
08-31 11:31:16.075  6998  6998 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 11:31:16.098  6998  6998 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-31 11:31:16.115  7015  7015 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 11:31:16.131  1030  1045 I ActivityManager: Killing 6060:com.android.contacts/u0a19 (adj 15): empty #17
,08-31 11:31:16.141  6998  6998 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-31 11:31:16.142  6998  6998 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-31 11:31:16.142  6998  6998 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-31 11:31:16.142  6998  6998 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-31 11:31:16.143  6998  6998 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-31 11:31:16.145  6998  6998 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-31 11:31:16.151  6998  6998 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-31 11:31:16.207  3908  3988 D bt_hci_bdroid: cleanup
,08-31 11:31:16.207  3908  4097 I bt_lpm  : LPM is already off!!!
08-31 11:31:16.207  3908  4223 I bt_userial_mct: exiting userial_read_thread
08-31 11:31:16.207  3908  4223 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-31 11:31:16.207  3908  4095 W bt-btif : ag scb idx 1 not allocated
08-31 11:31:16.208  3908  4095 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 11:31:16.208  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:31:16.208  3908  4095 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:31:16.208  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:31:16.208  3908  4095 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:31:16.208  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:31:16.208  3908  4095 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:31:16.208  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:31:16.208  3908  4095 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:31:16.208  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:31:16.208  3908  4095 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:31:16.208  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:31:16.208  3908  3988 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 11:31:16.208  3908  4095 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:31:16.208  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:31:16.208  3908  4095 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:31:16.209  3908  4097 I bt_vendor: hw_epilog_process
08-31 11:31:16.209  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:31:16.209  3908  4095 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:31:16.209  3908  4095 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:31:16.209  3908  4095 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:31:16.209  3908  4095 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 11:31:16.210  3908  3988 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 11:31:16.210  3908  3988 D bt_userial_mct: userial_close
08-31 11:31:16.210  3908  3988 E bt_userial_mct: pthread_join() FAILED result:3
08-31 11:31:16.210  3908  3988 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-31 11:31:16.222  1030  1883 W libprocessgroup: failed to open /acct/uid_10019/pid_6060/cgroup.procs: No such file or directory
,08-31 11:31:16.250  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:31:16.256  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:16.290  6998  6998 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 11:31:16.295  6998  6998 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-31 11:31:16.297  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:16.298  3908  3988 D bt_hci_bdroid: set_power 0
08-31 11:31:16.298  3908  3988 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 11:31:16.298  3908  3988 I bt_vendor: bluetooth satus is on
08-31 11:31:16.298  3908  3988 I bt_vendor: bt-vendor : resetting BT status
08-31 11:31:16.298  3908  3988 I bt_vendor: Starting hciattach daemon
08-31 11:31:16.298  3908  3988 I bt_vendor: try to set false
08-31 11:31:16.300  3908  3988 I bt_vendor: Starting hciattach daemon
08-31 11:31:16.300  3908  3988 I bt_vendor: try to set false
08-31 11:31:16.301  3908  3988 I bt_vendor: cleanup
08-31 11:31:16.302  3908  4095 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 11:31:16.303  6998  6998 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-31 11:31:16.303  3908  3988 I GKI_LINUX: GKI_exit_task 0 done
08-31 11:31:16.303  3908  3988 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-31 11:31:16.306  3908  3983 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-31 11:31:16.311  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-31 11:31:16.312  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:31:16.312  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:31:16.314  3908  3908 D HeadsetService: Received stop request...Stopping profile...
08-31 11:31:16.317  3908  3908 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 11:31:16.317  3908  3908 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:31:16.317  3908  4021 D HeadsetStateMachine: Exit Disconnected: -1
08-31 11:31:16.317  3908  3908 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d1b4faf
08-31 11:31:16.320  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:31:16.322  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-31 11:31:16.322  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-31 11:31:16.322  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-31 11:31:16.323  1030  1030 D BluetoothHeadset: Proxy object disconnected
,08-31 11:31:16.323  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-31 11:31:16.327  3908  3908 D A2dpService: Received stop request...Stopping profile...
08-31 11:31:16.327  3908  4072 D A2dpStateMachine: Exit Disconnected: -1
08-31 11:31:16.328  3908  3908 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-31 11:31:16.330  3908  3983 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 11:31:16.331  3908  3908 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 11:31:16.331  3908  3908 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:31:16.331  3908  3908 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d1b4faf
08-31 11:31:16.332  1030  1030 D BluetoothA2dp: Proxy object disconnected
08-31 11:31:16.332  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-31 11:31:16.332  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:16.332  3908  3908 D HeadsetStateMachine: Unbinding service...
08-31 11:31:16.333  3908  3908 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:31:16.333  3908  3908 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:31:16.333  3908  3908 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:31:16.334  3908  3908 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:31:16.334  3908  3908 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 11:31:16.334  3908  3908 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:31:16.334  3908  3908 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 11:31:16.334  3908  3908 D HidService: Received stop request...Stopping profile...
08-31 11:31:16.334  3908  3908 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d1b4faf
08-31 11:31:16.338  3908  3908 D HealthService: Received stop request...Stopping profile...
08-31 11:31:16.338  3908  3908 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d1b4faf
08-31 11:31:16.340  3908  3908 D PanService: Received stop request...Stopping profile...
,08-31 11:31:16.340  3908  3908 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d1b4faf
08-31 11:31:16.343  6950  6950 D BluetoothInputDevice: Proxy object disconnected
08-31 11:31:16.343  6950  6950 D HidProfile: Bluetooth service disconnected
08-31 11:31:16.344  6950  6950 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 11:31:16.344  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:16.344  6950  6950 D PanProfile: Bluetooth service disconnected
08-31 11:31:16.344  3908  3908 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:31:16.344  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:16.345  3908  3908 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 11:31:16.345  3908  3908 D BtGatt.GattService: stop()
08-31 11:31:16.345  3908  3908 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 11:31:16.346  3908  3908 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d1b4faf
08-31 11:31:16.347  6998  6998 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:31:16.347  3908  3908 D BluetoothMapService: Received stop request...Stopping profile...
08-31 11:31:16.347  3908  3908 D BluetoothMapService: stop()
08-31 11:31:16.350  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:16.350  3908  3908 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 11:31:16.350  3908  3908 D BluetoothMapEmailAppObserver: removeReceiver()
,08-31 11:31:16.353  3908  3908 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d1b4faf
08-31 11:31:16.354  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:31:16.354  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:31:16.354  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:31:16.355  6950  6950 D BluetoothMap: Proxy object disconnected
08-31 11:31:16.355  6950  6950 D MapProfile: Bluetooth service disconnected
08-31 11:31:16.355  3908  3908 I BluetoothA2dpServiceJni: cleanupNative
08-31 11:31:16.355  3908  4076 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 11:31:16.356  3908  3908 I GKI_LINUX: GKI_exit_task 2 done
08-31 11:31:16.356  3908  3908 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 11:31:16.356  3908  3908 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:31:16.356  3908  3908 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 11:31:16.356  3908  3908 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:31:16.356  3908  3908 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:31:16.356  3908  3908 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:31:16.357  3908  3908 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:31:16.357  3908  3908 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 11:31:16.358  3908  3908 V BluetoothMapService: Handler(): got msg=4
08-31 11:31:16.358  3908  3908 D BluetoothMapService: MAP Service closeService in
08-31 11:31:16.358  3908  3908 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:31:16.358  3908  3908 V BluetoothMapService: MAP Service closeService out
08-31 11:31:16.358  3908  3908 D BluetoothMapService: cleanup()
08-31 11:31:16.358  3908  3908 D BluetoothMapService: MAP Service closeService in
08-31 11:31:16.358  3908  3908 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:31:16.358  3908  3908 V BluetoothMapService: MAP Service closeService out
08-31 11:31:16.358  3908  3983 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 11:31:16.358  3908  3983 D BluetoothAdapterProperties: Setting state to 10
08-31 11:31:16.358  3908  3983 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 11:31:16.359  1030  1094 D BluetoothManagerService: Message: 60
08-31 11:31:16.359  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 11:31:16.359  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-31 11:31:16.359  3908  3983 I BluetoothAdapterState: Entering OffState
08-31 11:31:16.359  1848  1864 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:31:16.363  1848  2573 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:31:16.363  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:16.365  6950  6965 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 11:31:16.365  6950  6966 D BluetoothPan: onBluetoothStateChange on: false
08-31 11:31:16.366  1030  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:31:16.366  1848  1864 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:31:16.367  1030  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:31:16.367  6950  7036 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 11:31:16.369  6950  6965 D BluetoothMap: onBluetoothStateChange: up=false
08-31 11:31:16.370  1030  1094 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 11:31:16.370  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-31 11:31:16.372  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:16.374  1030  1094 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-31 11:31:16.374  1030  1094 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 11:31:16.374  1030  1094 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@36f15b71 mBinding = false
08-31 11:31:16.375  1030  1094 D BluetoothManagerService: Sending unbind request.
,08-31 11:31:16.376  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-31 11:31:16.383  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:16.383  6950  6950 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 11:31:16.383  1939  2123 D LGBluetoothAPIService: Message: 2
08-31 11:31:16.383  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:31:16.383  1939  2123 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2621145e mBinding = false
08-31 11:31:16.384  1939  2123 D LGBluetoothAPIService: Sending unbind request.
08-31 11:31:16.384  6950  6950 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-31 11:31:16.384  6950  6950 D LGBluetoothEventManager: [BTUI] clear device connection state
08-31 11:31:16.385  3908  3988 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-31 11:31:16.386  3908  3908 I GKI_LINUX: GKI_exit_task 1 done
08-31 11:31:16.386  3908  3908 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 11:31:16.386  3908  3908 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 11:31:16.387  3908  3908 I art     : --- WEIRD: removing null entry 246
,08-31 11:31:16.387  3908  3908 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-31 11:31:16.387  3908  3908 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 11:31:16.388  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:16.388  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:16.391  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:16.391  6950  6950 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 11:31:16.391  3908  3908 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-31 11:31:16.391  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:16.394  3908  3908 I art     : System.exit called, status: 0
08-31 11:31:16.394  3908  3908 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 11:31:16.396  1600  1600 D BluetoothAdapter: 846515239: getState() :  mService = null. Returning STATE_OFF
08-31 11:31:16.396  1600  1600 D BluetoothAdapter: 846515239: getState() :  mService = null. Returning STATE_OFF
08-31 11:31:16.398  6998  6998 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:31:16.398  6950  6950 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:31:16.417   311  2151 V AudioFlinger: 3908 died, releasing its sessions
08-31 11:31:16.417   311  2151 V AudioFlinger:  pid 1848 @ 0
08-31 11:31:16.418   311  2151 V AudioFlinger:  pid 3475 @ 1
08-31 11:31:16.418   311  2151 V AudioFlinger:  pid 3475 @ 2
08-31 11:31:16.418  6950  6950 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-31 11:31:16.460  1030  1045 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7039 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-31 11:31:16.477  1030  1865 I ActivityManager: Process com.android.bluetooth (pid 3908) has died
,08-31 11:31:16.477  1030  1865 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-31 11:31:16.486  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:31:16.518  6950  6950 D BluetoothPermissionRequest: onReceive
08-31 11:31:16.525  6950  6950 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-31 11:31:16.526  6950  6950 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-31 11:31:16.530  6950  6950 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:31:16.601  1030  1956 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7056 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-31 11:31:16.616  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:31:16.621  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:31:16.631  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:31:16.653  7039  7073 W FormManager: Network not available. Please check & try again.
,08-31 11:31:16.653  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:31:16.654  6950  6950 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:31:16.654  6950  6950 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:31:16.654  6950  6950 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-31 11:31:16.655  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 11:31:16.658  7039  7076 V FormManager: Network unavailable.
08-31 11:31:16.665  6950  6950 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:31:16.666  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,08-31 11:31:16.666  7039  7076 V FormManager: Network unavailable.
08-31 11:31:16.666  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:31:16.667  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-31 11:31:16.667  6950  6950 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:31:16.668  6950  6950 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:31:16.671  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:31:16.672  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:31:16.673  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:31:16.675  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:31:16.678  7056  7056 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-31 11:31:16.678  7056  7056 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:31:16.679  7056  7056 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 11:31:16.679  7056  7056 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 11:31:16.681  6970  6970 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-31 11:31:16.681  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:31:16.681  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:31:16.682  4340  7079 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:31:16.687  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:31:16.689  4340  7080 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:31:16.689  4340  7080 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 11:31:16.694  7039  7081 W FormManager: Network not available. Please check & try again.
08-31 11:31:16.698  7056  7056 D BluetoothAdapterApp: Loading JNI Library
08-31 11:31:16.698  7039  7082 V FormManager: Network unavailable.
08-31 11:31:16.701  7039  7082 V FormManager: Network unavailable.
08-31 11:31:16.705  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:31:16.709  1030  1956 I ActivityManager: Killing 6576:com.lge.email/u0a23 (adj 15): empty #17
08-31 11:31:16.725  7056  7056 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1f094024 Instance Count = 1
,08-31 11:31:16.759  1030  1574 W libprocessgroup: failed to open /acct/uid_10023/pid_6576/cgroup.procs: No such file or directory
,08-31 11:31:16.762  7056  7056 D BluetoothAdapterApp: onCreate
,08-31 11:31:16.782  6998  6998 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-31 11:31:16.784  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 11:31:16.786  6998  6998 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-31 11:31:16.793  7056  7056 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-31 11:31:16.793  7056  7056 D ProfileConfigQcom: Adding HeadsetService
08-31 11:31:16.793  7056  7056 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 11:31:16.793  7056  7056 D ProfileConfigQcom: Adding A2dpService
08-31 11:31:16.794  7056  7056 D ProfileConfigQcom: [BTUI] HidService is supported
08-31 11:31:16.794  7056  7056 D ProfileConfigQcom: Adding HidService
08-31 11:31:16.794  7056  7056 D ProfileConfigQcom: [BTUI] HealthService is supported
08-31 11:31:16.794  7056  7056 D ProfileConfigQcom: Adding HealthService
08-31 11:31:16.795  7056  7056 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-31 11:31:16.796  7056  7056 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 11:31:16.796  7056  7056 D ProfileConfigQcom: Adding PanService
08-31 11:31:16.796  7056  7056 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 11:31:16.796  7056  7056 D ProfileConfigQcom: Adding GattService
,08-31 11:31:16.796  7056  7056 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 11:31:16.797  7056  7056 D ProfileConfigQcom: Adding BluetoothMapService
08-31 11:31:16.797  7056  7056 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 11:31:16.799  7056  7056 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-31 11:31:16.805  6950  6950 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 11:31:16.807  7056  7056 V LGMDMManagerInternal: Create singleton instance
08-31 11:31:16.836  6998  6998 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 11:31:16.837  6998  6998 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:31:16.850  6998  6998 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-31 11:31:16.851  6998  6998 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-31 11:31:16.851  6998  6998 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-31 11:31:16.851  6998  6998 V SoundPool: doLoad: loading sample sampleID=1
08-31 11:31:16.853  6998  6998 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 11:31:16.853  6998  7086 V SoundPool: Start decode
08-31 11:31:16.853  6998  7086 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-31 11:31:16.854   311  2152 V MediaPlayerService: decode(23, 10857164, 17813)
08-31 11:31:16.854   311  2152 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-31 11:31:16.854   311  2152 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-31 11:31:16.854   311  2152 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-31 11:31:16.854   311  2152 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-31 11:31:16.854   311  2152 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-31 11:31:16.854   311  2152 V MediaPlayerService: player type = 3
08-31 11:31:16.854   311  2152 V AwesomePlayer: AwesomePlayer create()
08-31 11:31:16.855   311  2152 V AwesomePlayer: reset_l() 
08-31 11:31:16.855   311  2152 V AwesomePlayer: cancelPlayerEvents
08-31 11:31:16.855   311  2152 V AwesomePlayer: setAudioSink() 
08-31 11:31:16.855   311  2152 V AwesomePlayer: reset_l() 
08-31 11:31:16.855   311  2152 V AudioCache: notify(0xb5474480, 8, 0, 0)
08-31 11:31:16.855   311  2152 V AudioCache: ignored
08-31 11:31:16.855   311  2152 V AwesomePlayer: cancelPlayerEvents
08-31 11:31:16.855   311  2152 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-31 11:31:16.855   311  2152 V AwesomePlayer: setDataSource_l dataSource
08-31 11:31:16.855   311  2152 V LGParserOSAL: SniffLGParser start
08-31 11:31:16.855   311  2152 V LGParserOSAL: MainType:5, SubType=0
08-31 11:31:16.855   311  2152 V LGParserOSAL: #### check Mime : application/ogg
08-31 11:31:16.855   311  2152 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-31 11:31:16.855   311  2152 E MediaExtractor: Use LGExtractor :application/ogg 
08-31 11:31:16.861  6697  6697 D UEI.SmartControl: QS Service created
08-31 11:31:16.862  6998  6998 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-31 11:31:16.866  6998  6998 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-31 11:31:16.876  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 11:31:16.880  6697  6697 I UEI.SmartControl: Service initServices...
,08-31 11:31:16.881  6697  6697 D UEI.SmartControl: QS start get config
08-31 11:31:16.882  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:16.885  7056  7056 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:31:16.885  7056  7056 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:31:16.885  7056  7056 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:31:16.886  7056  7056 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:16.886  7056  7056 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-31 11:31:16.890  6998  6998 V LGMDMManager: Create singleton instance
08-31 11:31:16.896   311  2152 V LGParserOSAL: supported mime: application/ogg
08-31 11:31:16.896   311  2152 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-31 11:31:16.897   311  2152 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-31 11:31:16.897   311  2152 V AwesomePlayer: mBitrate = -1 bits/sec
08-31 11:31:16.897   311  2152 V AwesomePlayer: AudioTrack Setting
08-31 11:31:16.897   311  2152 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-31 11:31:16.897   311  2152 V AwesomePlayer: setAudioSource() 
08-31 11:31:16.897   311  2152 V MediaPlayerService: prepare
08-31 11:31:16.897   311  2152 V AwesomePlayer: prepareAsync_l() 
08-31 11:31:16.897   311  2152 V MediaPlayerService: wait for prepare
08-31 11:31:16.897   311  7088 V AwesomePlayer: onPrepareAsyncEvent() 
08-31 11:31:16.897   311  7088 V AwesomePlayer: initAudioDecoder() 
08-31 11:31:16.897   311  7088 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 11:31:16.897   311  7088 V AudioSystem: isOffloadSupported()
08-31 11:31:16.897   311  7088 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 11:31:16.897   311  7088 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 11:31:16.897   311  7088 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 11:31:16.897   311  7088 V AwesomePlayer: getUseOffload() = 0 
08-31 11:31:16.897   311  7088 V OMXCodec: OMXCodec::Create
08-31 11:31:16.897   311  7088 V OMXCodec: findMatchingCodecs()
08-31 11:31:16.897   311  7088 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-31 11:31:16.897   311  7088 V OMXCodec: matchingCodecs.size()=1
08-31 11:31:16.897   311  7088 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-31 11:31:16.897  7015  7015 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-31 11:31:16.899   311  7088 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-31 11:31:16.899   311  7088 V LGCodecAdapter: LG Codec Adapter start
08-31 11:31:16.899   311  7088 V OMXCodec: OMXCodec Createtor
08-31 11:31:16.899   311  7088 V OMXCodec: setComponentRole
08-31 11:31:16.899   311  7088 V OMXCodec: configureCodec protected=0
08-31 11:31:16.899   311  7088 V LGCodecAdapter: called getLGCodecSpecificData
08-31 11:31:16.899   311  7088 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-31 11:31:16.899   311  7088 V LGCodecOSAL: Called LGconfigureCodecMETA
08-31 11:31:16.899   311  7088 V LGCodecOSAL: Called LGconfigureCodecMSG
08-31 11:31:16.899   311  7088 V LGCodecOSAL: Not support LGCodec
08-31 11:31:16.899   311  7088 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 11:31:16.899   311  7088 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-31 11:31:16.899   311  7088 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-31 11:31:,16.899   311  7088 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-31 11:31:16.899   311  7088 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 11:31:16.899   311  7088 V AudioSystem: isOffloadSupported()
08-31 11:31:16.899   311  7088 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 11:31:16.899   311  7088 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 11:31:16.899   311  7088 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-31 11:31:16.899   311  7088 V OMXCodec: init()
08-31 11:31:16.899   311  7088 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-31 11:31:16.899   311  7088 V OMXCodec: allocateBuffers
08-31 11:31:16.899   311  7088 V OMXCodec: allocateBuffersOnPort portIndex=0
08-31 11:31:16.899   311  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-31 11:31:16.899   311  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
08-31 11:31:16.899   311  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-31 11:31:16.899   311  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-31 11:31:16.899   311  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-31 11:31:16.899   311  7088 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 11:31:16.899   311  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 11:31:16.900   311  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
08-31 11:31:16.900   311  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-31 11:31:16.900   311  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-31 11:31:16.900   311  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-31 11:31:16.900   311  7088 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 11:31:16.900   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 11:31:16.900   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 11:31:16.900   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
,08-31 11:31:16.906   311  7088 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 11:31:16.906   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-31 11:31:16.906   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-31 11:31:16.906   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-31 11:31:16.907   311  7088 V OMXCodec: init() mAsyncCompletion wait free! 
08-31 11:31:16.907   311  7088 V AwesomePlayer: finishAsyncPrepare_l() 
08-31 11:31:16.907   311  7088 V AudioCache: notify(0xb5474480, 5, 0, 0)
08-31 11:31:16.907   311  7088 V AudioCache: ignored
08-31 11:31:16.907   311  7088 V AudioCache: notify(0xb5474480, 1, 0, 0)
08-31 11:31:16.907   311  7088 V AudioCache: prepared
08-31 11:31:16.907   311  2152 V AudioCache: wait - success
08-31 11:31:16.907   311  2152 V MediaPlayerService: start
08-31 11:31:16.907   311  2152 V AwesomePlayer: play_l() 
08-31 11:31:16.907   311  2152 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-31 11:31:16.907   311  2152 V AwesomePlayer: createAudioPlayer_l
08-31 11:31:16.907   311  2152 V AwesomePlayer: seekAudioIfNecessary_l() 
08-31 11:31:16.907   311  2152 V AwesomePlayer: startAudioPlayer_l() 
08-31 11:31:16.907   311  2152 D AudioPlayer: start of Playback, useOffload 0
08-31 11:31:16.907   311  2152 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 11:31:16.907   311  2152 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 11:31:16.909   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-31 11:31:16.909   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-31 11:31:16.909   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-31 11:31:16.909   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-31 11:31:16.909   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-31 11:31:16.909   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884448
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-31 11:31:16.910   311  7090 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-31 11:31:16.910   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-31 11:31:16.911   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] allocated b,uffer 0xb54f7920 on output port
08-31 11:31:16.911   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb3d0 on output port
08-31 11:31:16.911   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-31 11:31:16.911   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-31 11:31:16.911   311  2152 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-31 11:31:16.911   311  2152 V AudioCache: notify(0xb5474480, 6, 0, 0)
08-31 11:31:16.912   311  2152 V AudioCache: ignored
08-31 11:31:16.912   311  2152 V MediaPlayerService: wait for playback complete
,08-31 11:31:16.917   311  7091 V AudioCache: write(0xb17fd000, 4096)
,08-31 11:31:16.917   311  7091 V AudioCache: memcpy(0xac300000, 0xb17fd000, 4096)
08-31 11:31:16.918   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.918   311  7091 V AudioCache: memcpy(0xac301000, 0xb17fd000, 4096)
08-31 11:31:16.919   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.919   311  7091 V AudioCache: memcpy(0xac302000, 0xb17fd000, 4096)
08-31 11:31:16.919   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.919   311  7091 V AudioCache: memcpy(0xac303000, 0xb17fd000, 4096)
08-31 11:31:16.920   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.920   311  7091 V AudioCache: memcpy(0xac304000, 0xb17fd000, 4096)
08-31 11:31:16.920   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.920   311  7091 V AudioCache: memcpy(0xac305000, 0xb17fd000, 4096)
08-31 11:31:16.920   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.920   311  7091 V AudioCache: memcpy(0xac306000, 0xb17fd000, 4096)
08-31 11:31:16.921   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.921   311  7091 V AudioCache: memcpy(0xac307000, 0xb17fd000, 4096)
08-31 11:31:16.921   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.921   311  7091 V AudioCache: memcpy(0xac308000, 0xb17fd000, 4096)
08-31 11:31:16.922   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.922   311  7091 V AudioCache: memcpy(0xac309000, 0xb17fd000, 4096)
08-31 11:31:16.922   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.922   311  7091 V AudioCache: memcpy(0xac30a000, 0xb17fd000, 4096)
,08-31 11:31:16.923   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.923   311  7091 V AudioCache: memcpy(0xac30b000, 0xb17fd000, 4096)
08-31 11:31:16.923   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.923   311  7091 V AudioCache: memcpy(0xac30c000, 0xb17fd000, 4096)
08-31 11:31:16.923   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.924   311  7091 V AudioCache: memcpy(0xac30d000, 0xb17fd000, 4096)
08-31 11:31:16.924   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.924   311  7091 V AudioCache: memcpy(0xac30e000, 0xb17fd000, 4096)
08-31 11:31:16.924   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.924   311  7091 V AudioCache: memcpy(0xac30f000, 0xb17fd000, 4096)
08-31 11:31:16.925   311  7091 V AudioCache: write(0xb17fd000, 4096)
,08-31 11:31:16.925   311  7091 V AudioCache: memcpy(0xac310000, 0xb17fd000, 4096)
08-31 11:31:16.925   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.925   311  7091 V AudioCache: memcpy(0xac311000, 0xb17fd000, 4096)
08-31 11:31:16.926   311  7091 V AudioCache: write(0xb17fd000, 4096)
,08-31 11:31:16.926   311  7091 V AudioCache: memcpy(0xac312000, 0xb17fd000, 4096)
,08-31 11:31:16.926   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.926   311  7091 V AudioCache: memcpy(0xac313000, 0xb17fd000, 4096)
08-31 11:31:16.927   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.927   311  7091 V AudioCache: memcpy(0xac314000, 0xb17fd000, 4096)
08-31 11:31:16.927   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.927   311  7091 V AudioCache: memcpy(0xac315000, 0xb17fd000, 4096)
08-31 11:31:16.928   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.928   311  7091 V AudioCache: memcpy(0xac316000, 0xb17fd000, 4096)
08-31 11:31:16.928   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.928   311  7091 V AudioCache: memcpy(0xac317000, 0xb17fd000, 4096)
08-31 11:31:16.928   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.928   311  7091 V AudioCache: memcpy(0xac318000, 0xb17fd000, 4096)
08-31 11:31:16.929   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.929   311  7091 V AudioCache: memcpy(0xac319000, 0xb17fd000, 4096)
08-31 11:31:16.929   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.929   311  7091 V AudioCache: memcpy(0xac31a000, 0xb17fd000, 4096)
08-31 11:31:16.930   311  7091 V AudioCache: write(0xb17fd000, 4096)
,08-31 11:31:16.930   311  7091 V AudioCache: memcpy(0xac31b000, 0xb17fd000, 4096)
08-31 11:31:16.930   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.930   311  7091 V AudioCache: memcpy(0xac31c000, 0xb17fd000, 4096)
08-31 11:31:16.931   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.931   311  7091 V AudioCache: memcpy(0xac31d000, 0xb17fd000, 4096)
08-31 11:31:16.931   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.931   311  7091 V AudioCache: memcpy(0xac31e000, 0xb17fd000, 4096)
08-31 11:31:16.931   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.931   311  7091 V AudioCache: memcpy(0xac31f000, 0xb17fd000, 4096)
08-31 11:31:16.932   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.932   311  7091 V AudioCache: memcpy(0xac320000, 0xb17fd000, 4096)
08-31 11:31:16.932   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.932   311  7091 V AudioCache: memcpy(0xac321000, 0xb17fd000, 4096)
08-31 11:31:16.933   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.933   311  7091 V AudioCache: memcpy(0xac322000, 0xb17fd000, 4096)
08-31 11:31:16.933   311  7091 V AudioCache: write(0xb17fd000, 4096)
,08-31 11:31:16.933   311  7091 V AudioCache: memcpy(0xac323000, 0xb17fd000, 4096)
08-31 11:31:16.934   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.934   311  7091 V AudioCache: memcpy(0xac324000, 0xb17fd000, 4096)
08-31 11:31:16.934   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.934   311  7091 V AudioCache: memcpy(0xac325000, 0xb17fd000, 4096)
08-31 11:31:16.935   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.935   311  7091 V AudioCache: memcpy(0xac326000, 0xb17fd000, 4096)
08-31 11:31:16.935   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.935   311  7091 V AudioCache: memcpy(0xac327000, 0xb17fd000, 4096)
08-31 11:31:16.935   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.935   311  7091 V AudioCache: memcpy(0xac328000, 0xb17fd000, 4096)
08-31 11:31:16.936   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.936   311  7091 V AudioCache: memcpy(0xac329000, 0xb17fd000, 4096)
08-31 11:31:16.936   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.936   311  7091 V AudioCache: memcpy(0xac32a000, 0xb17fd000, 4096)
,08-31 11:31:16.947   311  7091 V AudioCache: write(0xb17fd000, 4096)
,08-31 11:31:16.947   311  7091 V AudioCache: memcpy(0xac32b000, 0xb17fd000, 4096)
08-31 11:31:16.947   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.947   311  7091 V AudioCache: memcpy(0xac32c000, 0xb17fd000, 4096)
08-31 11:31:16.948   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.948   311  7091 V AudioCache: memcpy(0xac32d000, 0xb17fd000, 4096)
08-31 11:31:16.948   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.948   311  7091 V AudioCache: memcpy(0xac32e000, 0xb17fd000, 4096)
08-31 11:31:16.948  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 11:31:16.948   311  7091 V AudioCache: write(0xb17fd000, 4096)
,08-31 11:31:16.948   311  7091 V AudioCache: memcpy(0xac32f000, 0xb17fd000, 4096)
,08-31 11:31:16.949   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.949   311  7091 V AudioCache: memcpy(0xac330000, 0xb17fd000, 4096)
08-31 11:31:16.949  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-31 11:31:16.949   311  7091 V AudioCache: write(0xb17fd000, 4096)
08-31 11:31:16.949   311  7091 V AudioCache: memcpy(0xac331000, 0xb17fd000, 4096)
08-31 11:31:16.949   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
,08-31 11:31:16.949   311  7091 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 11:31:16.949   311  7091 V AwesomePlayer: postAudioEOS() 
08-31 11:31:16.949   311  7091 V AudioCache: write(0xb17fd000, 280)
08-31 11:31:16.950   311  7091 V AudioCache: memcpy(0xac332000, 0xb17fd000, 280)
08-31 11:31:16.950  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9159
08-31 11:31:16.951   311  7088 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-31 11:31:16.951   311  7088 V AwesomePlayer: onStreamDone
08-31 11:31:16.951   311  7088 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-31 11:31:16.951   311  7088 V AudioCache: notify(0xb5474480, 2, 0, 0)
08-31 11:31:16.951   311  7088 V AudioCache: playback complete
08-31 11:31:16.951   311  7088 V AwesomePlayer: pause_l() 
08-31 11:31:16.951   311  7088 V AudioCache: notify(0xb5474480, 7, 0, 0)
08-31 11:31:16.951   311  7088 V AudioCache: ignored
08-31 11:31:16.951   311  7088 V AwesomePlayer: cancelPlayerEvents
08-31 11:31:16.951   311  7088 D AudioPlayer: Pause Playback at 1068125
08-31 11:31:16.952   311  2152 V AudioCache: wait - success
08-31 11:31:16.952   311  2152 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-31 11:31:16.952   311  2152 V AwesomePlayer: reset_l() 
08-31 11:31:16.952   311  2152 V AudioCache: notify(0xb5474480, 8, 0, 0)
08-31 11:31:16.952   311  2152 V AudioCache: ignored
08-31 11:31:16.952   311  2152 V AwesomePlayer: cancelPlayerEvents
08-31 11:31:16.952   311  2152 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-31 11:31:16.952   311  2152 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-31 11:31:16.952   311  2152 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-31 11:31:16.952   311  2152 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-31 11:31:16.952   311  2152 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 11:31:16.952   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 11:31:16.952   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 11:31:16.952   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
,08-31 11:31:16.952   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-31 11:31:16.952   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-31 11:31:16.952   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bb3d0 on port 1
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 1
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-31 11:31:16.953   311  2152 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 11:31:16.953   311  2152 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-31 11:31:16.953   311  7090 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-31 11:31:16.953   311  2152 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 11:31:16.953   311  2152 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-31 11:31:16.953   311  2152 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,08-31 11:31:16.957   311  2152 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-31 11:31:16.957   311  2152 D AudioPlayer: AudioPlayer releasing audio source
08-31 11:31:16.957   311  2152 D AudioPlayer: AudioPlayer done releasing audio source
08-31 11:31:16.957   311  2152 V AwesomePlayer: reset_l() 
08-31 11:31:16.957   311  2152 V AwesomePlayer: cancelPlayerEvents
08-31 11:31:16.957   311  2152 V AwesomePlayer: ~AwesomePlayer call
08-31 11:31:16.958   311  2152 V AwesomePlayer: reset_l() 
08-31 11:31:16.958   311  2152 V AwesomePlayer: cancelPlayerEvents
,08-31 11:31:16.958  6998  7086 V SoundPool: close(31)
08-31 11:31:16.958  6998  7086 V SoundPool: pointer = 0x9fe70000, size = 205080, sampleRate = 48000, numChannels = 2
08-31 11:31:17.175  6697  6697 I UEI.SmartControl: Supports setup maps: true
08-31 11:31:17.178  6697  6697 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 11:31:17.178  6697  6697 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 11:31:17.178  6697  6697 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 11:31:17.178  6697  6697 I UEI.SmartControl: ### init IR Blaster...
,08-31 11:31:17.182  6697  6697 D serial_port: Configuring serial port
08-31 11:31:17.182  6697  6697 E UEI.SmartControl: UEIBLaster setting for 616
08-31 11:31:17.182  6697  6697 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 11:31:17.182  6697  6697 I UEI.SmartControl: configuring settings for MAXQ616
08-31 11:31:17.182  6697  6697 I UEI.SmartControl: Get version...
08-31 11:31:17.201  6697  7092 D UEI.SmartControl: serial port data available: 21
,08-31 11:31:17.227  6697  6697 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-31 11:31:17.227  6697  6697 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-31 11:31:17.227  6697  6697 I UEI.SmartControl: QS saving settings...
08-31 11:31:17.229  6697  6697 D UEI.SmartControl: IR Blaster version: 25672567
08-31 11:31:17.246  6697  7092 D UEI.SmartControl: serial port data available: 4
,08-31 11:31:17.282  6697  6697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-31 11:31:17.286  6697  6697 E UEI.SmartControl: Services init done
08-31 11:31:17.287  6697  6697 D UEI.SmartControl: QS Service init finished
08-31 11:31:17.289  6697  6697 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 11:31:17.289  6697  6697 D UEI.SmartControl: QS Service version code: 201091
08-31 11:31:17.290  6697  6697 D UEI.SmartControl: Service requested: Control
08-31 11:31:17.294  6998  6998 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-31 11:31:17.296  6697  7101 I UEI.SmartControl: Device manager: loading config....
08-31 11:31:17.297  6697  6697 D UEI.SmartControl: Internal service binding...
,08-31 11:31:17.298  6697  7101 D UEI.SmartControl: ----------- loading internal config...
08-31 11:31:17.300  6697  6713 I UEI.SmartControl: ------ IControl API: 11
08-31 11:31:17.300  6697  6713 D UEI.SmartControl: File observer start...
08-31 11:31:17.301  6697  6713 E UEI.SmartControl: IR Port is disabled: false
08-31 11:31:17.301  6697  6713 D UEI.SmartControl: Starting file observer...
08-31 11:31:17.302  6697  6713 I UEI.SmartControl: Registering callback...
08-31 11:31:17.304  6697  6712 I UEI.SmartControl: ------ IControl API: 19
08-31 11:31:17.305  6697  6712 I UEI.SmartControl: Registering Services Ready callback...
08-31 11:31:17.305  6697  7101 E UEI.SmartControl: Loading SETTINGS...
08-31 11:31:17.310  6697  7101 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-31 11:31:17.316  6697  7100 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 11:31:17.317  6697  7100 D UEI.SmartControl: -----service ready thread exits
08-31 11:31:17.318  6998  7013 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-31 11:31:17.318  6998  7084 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-31 11:31:17.319  6998  7084 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-31 11:31:17.319  6998  6998 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-31 11:31:17.319  6998  6998 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-31 11:31:17.320  6697  6713 I UEI.SmartControl: ------ IControl API: 8
08-31 11:31:17.322  6998  6998 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-31 11:31:17.322  6998  6998 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-31 11:31:17.323  6998  6998 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-31 11:31:17.323  6998  6998 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-31 11:31:17.326  6998  6998 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-31 11:31:17.327  6998  6998 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-31 11:31:17.330  6998  6998 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-31 11:31:17.331  6998  6998 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 11:31:17.332  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 11:31:17.333  6998  6998 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 11:31:17.333  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 11:31:17.334  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-31 11:31:17.335  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-31 11:31:17.336  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-31 11:31:17.337  6998  6998 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472635877337]
08-31 11:31:17.339  6998  6998 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-31 11:31:17.342  1030  1937 I ActivityManager: Killing 6623:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-31 11:31:17.360  6998  7103 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-31 11:31:17.387  1030  1937 I ActivityManager: Killing 6086:com.android.gallery3d/u0a27 (adj 15): empty #18
,08-31 11:31:17.420  1030  2009 W libprocessgroup: failed to open /acct/uid_10027/pid_6086/cgroup.procs: No such file or directory
08-31 11:31:17.421  6998  6998 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-31 11:31:17.424  6998  6998 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-31 11:31:17.425  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-31 11:31:17.425  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-31 11:31:17.426  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-31 11:31:17.426  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-31 11:31:17.427  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-31 11:31:17.428  1030  1574 W libprocessgroup: failed to open /acct/uid_10061/pid_6623/cgroup.procs: No such file or directory
08-31 11:31:17.440  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-31 11:31:18.208  1030  1883 D WifiServiceImplEx: setWifiEnabled: true pid=6821, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-31 11:31:18.218  1030  1883 D WifiService: setWifiEnabled: true pid=6821, uid=10118
08-31 11:31:18.218  1030  1883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:31:18.235  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:31:18.235  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:31:18.236  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-31 11:31:18.237  1030  1389 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-31 11:31:18.237  1030  1389 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-31 11:31:18.240  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-31 11:31:18.240  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 11:31:18.240  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-31 11:31:18.240  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 11:31:18.240  1030  1389 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-31 11:31:18.240  1030  1389 E WifiHW  : unknown target_country: EU , set to default
08-31 11:31:18.240  1030  1389 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-31 11:31:18.240  1030  1389 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-31 11:31:18.240  1030  1389 I WifiUtil: gEnableBmps=1
08-31 11:31:18.304  1030  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:31:18.323  1030  1094 D Tethering: MasterInitialState.processMessage what=3
,08-31 11:31:18.338  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:31:18.342  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:18.344  1030  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:18.352  1030  1094 D Tethering: MasterInitialState.processMessage what=3
,08-31 11:31:18.364  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:18.366  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:31:18.371  1030  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:18.373  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 11:31:18.382  5788  5788 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 11:31:18.389  5788  5788 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 11:31:18.389  6502  6969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 11:31:18.419  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:31:18.451  1030  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:31:18.499  1030  1956 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7122 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-31 11:31:18.506  1030  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:18.507  1030  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 11:31:18.601  7122  7122 I AppUp4:AppBoxCP: onCreate
,08-31 11:31:18.602  7122  7122 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-31 11:31:18.613  7122  7122 I AppUp4:DB:  setFingerPrint start
08-31 11:31:18.613  7122  7122 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-31 11:31:18.622  7122  7122 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-31 11:31:18.622  7122  7122 I AppUp4:DB:  SDK version = 21
08-31 11:31:18.622  7122  7122 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-31 11:31:18.624  7122  7122 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-31 11:31:18.626  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 11:31:18.626  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:18.628  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 11:31:18.629  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 11:31:18.638  7122  7122 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 11:31:18.702  7122  7122 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:31:18.702  7122  7122 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:31:18.713  7122  7122 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@21dabb8e
08-31 11:31:18.713  7122  7122 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:31:18.714  7122  7122 D AppUp4:CustFacade: isPhone : true
08-31 11:31:18.715  7122  7122 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:31:18.715  7122  7122 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-31 11:31:18.716  7122  7122 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-31 11:31:18.717  7122  7141 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-31 11:31:18.718  7122  7141 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-31 11:31:18.718  7122  7141 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-31 11:31:18.724  1030  1648 I ActivityManager: Killing 6146:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-31 11:31:18.770  1030  2047 W libprocessgroup: failed to open /acct/uid_10080/pid_6146/cgroup.procs: No such file or directory
08-31 11:31:18.770  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:18.771  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-31 11:31:18.775  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:31:18.779  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:31:18.784  4340  7154 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:31:18.791  4340  7155 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:18.791  4340  7155 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 11:31:18.832  1030  1974 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7156 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-31 11:31:18.907  1030  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:31:18.907  1030  1094 D Tethering: InitialState.processMessage what=4
08-31 11:31:18.909  1030  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:31:18.912   304   890 D SoftapController: Softap fwReload - Ok
08-31 11:31:18.916  1030  1389 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (669ms)
,08-31 11:31:18.920   304   890 D CommandListener: Setting iface cfg
08-31 11:31:18.920   304   890 D CommandListener: Trying to bring down wlan0
08-31 11:31:18.921   304   890 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:31:18.923  1030  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1004699867, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
08-31 11:31:18.923  1030  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3ea192c0 type 2 when 224150 com.google.android.gms} when 224150
08-31 11:31:18.927  1030  1389 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-31 11:31:18.928  7156  7156 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:31:18.929  7156  7156 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:31:18.920  7174  7174 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:18.920  7174  7174 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:18.933  7156  7156 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 11:31:18.933  7156  7156 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 11:31:18.947  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:31:18.947  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:31:18.947  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:31:18.947  1030  1389 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 11:31:18.947  1030  1389 D WifiMonitor: connecting to supplicant
,08-31 11:31:18.953  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-31 11:31:18.953  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:18.954  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:18.955  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 11:31:18.966  2576  2576 D [Concierge]Service: onStartCommand(). Type : 9
,08-31 11:31:18.966  7174  7174 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 11:31:18.976  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:18.999  7174  7174 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 11:31:18.999  7174  7174 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-31 11:31:19.081  7156  7156 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-31 11:31:19.095  7156  7156 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-31 11:31:19.100  7174  7174 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 11:31:19.142  7156  7156 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 11:31:19.155  7174  7174 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-31 11:31:19.175  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-31 11:31:19.177  7174  7174 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-31 11:31:19.177  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 11:31:19.177  7174  7174 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 11:31:19.178  1030  7181 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-31 11:31:19.178  1030  7181 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 11:31:19.178  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 11:31:19.178  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,08-31 11:31:19.178  1030  7181 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 11:31:19.178  1030  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-31 11:31:19.178  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-31 11:31:19.179  1030  1389 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 11:31:19.180  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:19.182  7156  7156 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:31:19.182  7156  7156 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:31:19.183  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:19.184  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:19.185  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:19.186  1030  1389 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 11:31:19.186  1030  1389 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 11:31:19.188  1030  1389 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 11:31:19.188  1030  1389 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 11:31:19.188  1030  1389 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-31 11:31:19.190  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:31:19.190  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:31:19.190  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:31:19.190  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:31:19.190  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:19.190  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:19.190  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:19.190  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:31:19.191  1030  1389 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-31 11:31:19.192  1030  1389 D WifiNative-wlan0: SET update_config 1: returned true
08-31 11:31:19.192  1030  1389 D WifiConfigStore: Loading config and enabling all networks 
,08-31 11:31:19.192  1030  1389 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 11:31:19.193  1030  1389 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-31 11:31:19.195  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:19.195  1939  1939 D WfdService: Waiting for WifiP2p enabling
08-31 11:31:19.196  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 11:31:19.196  1030  1438 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 11:31:19.198  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:19.198  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:19.198  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:19.198  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:19.198  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:19.198  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:31:19.198  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:19.198  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:19.198  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:31:19.198  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:19.198  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:31:19.200  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:19.200  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:19.200  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:19.200  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:19.200  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:19.200  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:31:19.200  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:19.200  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:19.200  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:31:19.200  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:19.200  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:31:19.204  1030  1389 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-31 11:31:19.214  1030  1389 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 11:31:19.214  1030  1389 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 11:31:19.215  1030  1389 D WifiStateMachine: enableVerboseLogging : level 2
08-31 11:31:19.215  1030  1389 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 11:31:19.216  1030  1389 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-31 11:31:19.216  1030  1389 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 11:31:19.217  1030  1389 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-31 11:31:19.217  1030  1389 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 11:31:19.217  1030  1389 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 11:31:19.217  1030  1389 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 11:31:19.218  1030  1389 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 11:31:19.218  1030  1389 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-31 11:31:19.218  1030  1389 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 11:31:19.218  1030  1389 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-31 11:31:19.219  1030  1389 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 11:31:19.219  1030  1389 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
,08-31 11:31:19.219  1030  1389 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 11:31:19.220  1030  1389 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:31:19.220  1030  1389 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 11:31:19.220  1939  1939 D WfdsService: Supplicant Connection state is changed : true
08-31 11:31:19.220  1939  2290 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
,08-31 11:31:19.221  1939  2290 D WfdsService: Set the WFDS Monitor: true
08-31 11:31:19.221  1939  2290 D WfdsMonitor: WfdsMonitorThread create
08-31 11:31:19.221  1939  2290 D WfdsMonitor: WFDS Monitor is created and started
08-31 11:31:19.221  1939  2290 D WfdsService: WiFi: Supplicant connection re-established
08-31 11:31:19.221  1030  1389 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true,
08-31 11:31:19.221  1030  1389 D WifiNative-HAL: Setting external_sim to 1
08-31 11:31:19.221  1030  1389 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 11:31:19.222  1939  7184 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-31 11:31:19.222  1030  1389 D WifiNative-wlan0: SET external_sim 1: returned true
,08-31 11:31:19.222  1030  1389 I WifiNative-HAL: startHal
08-31 11:31:19.222  1030  1389 D wifi    : setting scan oui 0xaf72a340
08-31 11:31:19.222  1939  7184 E CtrlSupplicant: Succeed to open control connection,
,08-31 11:31:19.222  1030  1389 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:31:19.222  1030  1389 I WifiNative-HAL: startHal
08-31 11:31:19.223  1939  7184 E CtrlSupplicant: Succeed to open monitor connection
08-31 11:31:19.223  1030  1389 D wifi    : setting scan oui 0xaf72a340
08-31 11:31:19.223  1030  1389 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 11:31:19.223  1939  7184 D WfdsMonitor: Supplicant connection established,
08-31 11:31:19.223  1939  2290 D WfdsService: Connected to the supplicant for wfds
,08-31 11:31:19.224  1030  1389 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 11:31:19.224  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 11:31:19.224  7174  7174 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 11:31:19.224  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 11:31:19.224  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 11:31:19.225  7174  7174 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-31 11:31:19.225  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 11:31:19.225  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 11:31:19.225  7174  7174 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 11:31:19.225  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 11:31:19.225  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 11:31:19.226  7174  7174 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 11:31:19.226  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 11:31:19.226  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 11:31:19.226  7174  7174 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 11:31:19.228  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 11:31:19.228  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
,08-31 11:31:19.228  7174  7174 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 11:31:19.228  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 11:31:19.228  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 11:31:19.228  7174  7174 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 11:31:19.229  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 11:31:19.230  1030  1389 E WifiNative: : [224,457,560 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 11:31:19.230  1030  1389 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 11:31:19.230  1030  1389 D WifiNative-wlan0: RECONNECT: returned true
08-31 11:31:19.230  1030  1389 D WifiNative-wlan0: doString: [STATUS]
,08-31 11:31:19.231  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 11:31:19.231  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 11:31:19.231  1030  1389 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 11:31:19.231  1030  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:31:19.232  1030  1389 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:31:19.232  1030  1388 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.234   304   890 D CommandListener: Setting iface cfg
08-31 11:31:19.234   304   890 D CommandListener: Trying to bring up p2p0
08-31 11:31:19.234  1030  1388 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 11:31:19.235  1030  1388 D LGWifiP2pService: P2pEnablingState
08-31 11:31:19.235  1030  1388 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.235  1030  1388 D LGWifiP2pService: P2p socket connection successful
08-31 11:31:19.235  1030  1388 D LGWifiP2pService: P2pEnabledState
08-31 11:31:19.238  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
,08-31 11:31:19.238  1939  1939 D WfdsService: WifiP2pState is changed : true
08-31 11:31:19.239  1030  1388 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 11:31:19.239  1939  2290 D WfdsService: Receive the WFDS_ENABLE Method
08-31 11:31:19.239  1939  2290 D WfdsService: Set the WFDS Monitor: true
08-31 11:31:19.239  1939  2290 D WfdsService: Connected to the supplicant for wfds
08-31 11:31:19.239  1939  2290 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 11:31:19.240  7174  7174 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 11:31:19.240  1939  2290 D WfdsService: selectPreferredScanChannel [36]
08-31 11:31:19.240  1939  2290 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 11:31:19.242  1030  1388 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 11:31:19.242  1030  1388 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 11:31:19.243  1030  1388 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 11:31:19.243  1030  1388 D WifiNative-p2p0: SET device_name G3: returned true
08-31 11:31:19.243  1030  1388 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 11:31:19.243  1030  1388 D LGWifiP2pService: before postfix = G3
08-31 11:31:19.243  1030  1388 D WifiServerServiceExt: postfix byte check : 2
08-31 11:31:19.243  1030  1388 D LGWifiP2pService: after postfix = G3
08-31 11:31:19.243  1030  1388 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 11:31:19.244  1030  1388 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 11:31:19.244  1030  1388 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 11:31:19.244  1939  1939 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 11:31:19.244  1030  1388 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 11:31:19.244  1030  1388 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-31 11:31:19.244  1939  1939 D WfdsService: isConnected: false
08-31 11:31:19.245  1030  1388 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 11:31:19.245  1030  1388 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-31 11:31:19.245  1030  1388 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 11:31:19.245  1030  1388 D WifiNative-HAL: p2pGetDeviceAddress
08-31 11:31:19.246  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 11:31:19.246  1030  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.246  1030  1388 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-31 11:31:19.246  1030  1555 I WifiNative-HAL: startHal
08-31 11:31:19.246  1030  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf72a340
08-31 11:31:19.246  1030  1030 D RttService: SCAN_AVAILABLE : 3
08-31 11:31:19.246  1030  1555 D wifi    : failed to get capabilities : -3
08-31 11:31:19.246  1030  1555 E WifiScanningService: could not get scan capabilities
08-31 11:31:19.246  1030  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.247  1030  1389 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 11:31:19.247  1030  1388 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-31 11:31:19.247  1030  1388 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-31 11:31:19.248  1030  1389 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 11:31:19.248  1030  1388 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 11:31:19.248  1030  1388 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-31 11:31:19.248  1030  1388 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 11:31:19.248  1030  1388 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 11:31:19.249  1939  1939 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 11:31:19.249  1939  1939 D WfdsService: WIFI_P2P_T,HIS_DEVICE_CHANGED_ATCION
08-31 11:31:19.249  1030  1388 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-31 11:31:19.249  1030  1388 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 11:31:19.249  1939  1939 D WfdsService: Update P2p Interface State: 3
,08-31 11:31:19.250  1030  1389 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
,08-31 11:31:19.250  1030  1389 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 11:31:19.251  1030  1389 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 11:31:19.251  1030  1389 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 11:31:19.251  1030  1389 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 11:31:19.251  1030  1389 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 11:31:19.262  7174  7174 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-31 11:31:19.262  1030  1388 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-31 11:31:19.262  1030  1388 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 11:31:19.263  1030  1388 D LGWifiP2pService: InactiveState
08-31 11:31:19.263  1030  1388 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.263  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.263  1030  1388 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-31 11:31:19.264  7174  7174 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 11:31:19.264  1030  1389 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-31 11:31:19.264  1030  1389 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 11:31:19.265  7174  7174 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:19.265  1030  7181 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:31:19.265  1030  7181 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:19.265  1030  7181 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:19.265  1030  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:19.265  1030  1389 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 11:31:19.265  1030  1389 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-31 11:31:19.265  7174  7174 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 11:31:19.265  1939  7184 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:31:19.265  7174  7174 E wpa_supplicant: disconnect_rssi_lvl: -100
08-31 11:31:19.265  7174  7174 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:19.266  1030  1388 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 11:31:19.266  1030  7181 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:31:19.266  1030  1388 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.266  1030  7181 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:19.266  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.266  1030  7181 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:19.266  1030  1388 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.266  1030  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:19.266  1030  1388 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.266  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.266  1030  1388 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.266  7174  7174 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:19.266  1030  1388 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.266  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.266  1030  1388 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 ,arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.267  1030  7181 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:31:19.267  1030  7181 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:19.267  1030  7181 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:19.267  1030  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:19.267  1939  2290 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 11:31:19.267  1939  7184 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:31:19.267  1939  7184 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:31:19.267  1030  1388 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.268  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.268  1030  1389 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 11:31:19.268  1030  1388 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.268  1030  1030 E WifiServerServiceExt: No p2p device connected
08-31 11:31:19.268  1030  1389 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 11:31:19.268  1030  1389 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 11:31:19.268  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-31 11:31:19.269  7174  7174 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 11:31:19.270  7174  7174 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:19.270  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:31:19.270  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:19.270  1030  7181 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:19.270  1030  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:19.270  7174  7174 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 11:31:19.270  7174  7174 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:19.270  1939  7184 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:31:19.270  1030  7181 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:31:19.270  1030  7181 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:19.271  1030  7181 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:19.271  1030  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:19.271  7174  7174 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:19.271  1939  7184 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:31:19.271  1030  7181 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:31:19.271  1030  7181 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-31 11:31:19.271  1030  7181 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:19.271  1030  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:19.272  1030  1389 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 11:31:19.272  1030  1388 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.272  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:19.272  1030  1389 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:31:19.272  1030  1389 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:31:19.273  1030  1389 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:31:19.273  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-31 11:31:19.273  7174  7174 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 11:31:19.273  7174  7174 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:31:19.273  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 11:31:19.273  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:31:19.273  1030  7181 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:31:19.273  1030  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:31:19.274  1030  1389 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-31 11:31:19.274  1030  1389 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 11:31:19.274  1030  1389 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 11:31:19.274  1030  1389 D WifiNative-wlan0: doBoolean: SCAN
08-31 11:31:19.275  1030  1389 D WifiNative-wlan0: SCAN: returned false
08-31 11:31:19.275  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=224503  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 11:31:19.277  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:19.277  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:19.278  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:19.280  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:19.280  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:19.280  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 11:31:19.280  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=224509  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 11:31:19.281  1030  1389 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:31:19.281  1030  1389 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:31:19.282  1030  1389 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:31:19.282  1030  1389 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:31:19.282  1030  1389 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:31:19.284  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:19.284  1030  1030 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-31 11:31:19.329  7156  7156 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 11:31:19.366  7156  7156 I HubEmail: JNI_OnLoad()
08-31 11:31:19.366  7156  7156 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-31 11:31:19.366  7156  7156 I HubEmail: registerNatives()
08-31 11:31:19.366  7156  7156 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 11:31:19.366  7156  7156 I HubEmail: registerNativeMethods()
08-31 11:31:19.366  7156  7156 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 11:31:19.367  7156  7156 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-31 11:31:19.384  3475  3475 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 11:31:19.384  3475  3475 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:19.385  3475  3475 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 11:31:19.385  7156  7189 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:31:19.395  7039  7188 W FormManager: Network not available. Please check & try again.
08-31 11:31:19.443  1030  2009 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7192 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-31 11:31:19.452  7039  7190 V FormManager: Network unavailable.
,08-31 11:31:19.457  7039  7190 V FormManager: Network unavailable.
,08-31 11:31:19.470  1030  1956 I ActivityManager: Killing 6176:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-31 11:31:19.528  1030  1974 W libprocessgroup: failed to open /acct/uid_10097/pid_6176/cgroup.procs: No such file or directory
,08-31 11:31:19.663  7192  7192 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 11:31:19.665  7192  7192 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:31:19.671  7192  7192 D PhoneMonitor: Register our PhoneStateListener
,08-31 11:31:19.699  7192  7192 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-31 11:31:19.704  7192  7192 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-31 11:31:19.728  7192  7192 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-31 11:31:19.730  7192  7192 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-31 11:31:19.733  7192  7192 D TelephonyAutoProfiling: [parse] Load xml
08-31 11:31:19.741  7192  7192 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-31 11:31:19.741  7192  7192 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-31 11:31:19.742  7192  7192 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-31 11:31:19.742  7192  7192 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-31 11:31:19.742  7192  7192 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-31 11:31:19.742  7192  7192 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-31 11:31:19.742  7192  7192 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-31 11:31:19.742  7192  7192 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-31 11:31:19.742  7192  7192 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-31 11:31:19.742  7192  7192 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-31 11:31:19.742  7192  7192 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-31 11:31:19.742  7192  7192 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-31 11:31:19.743  7192  7192 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-31 11:31:19.743  7192  7192 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-31 11:31:19.743  7192  7192 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-31 11:31:19.743  7192  7192 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-31 11:31:19.743  7192  7192 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-31 11:31:19.757  7192  7192 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-31 11:31:19.774  1030  1974 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7217 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:31:19.775  1030  1974 I ActivityManager: Killing 6659:com.lge.eula/1000 (adj 15): empty #17
,08-31 11:31:19.849  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-31 11:31:19.849  1030  7181 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-31 11:31:19.850  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-31 11:31:19.850  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-31 11:31:19.850  1030  7181 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-31 11:31:19.850  7174  7174 E wpa_supplicant: USIM:  scard_init function
,08-31 11:31:19.850  1030  1389 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-31 11:31:19.850  1030  1389 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-31 11:31:19.851  7174  7174 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-31 11:31:19.851  1030  1389 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-31 11:31:19.851  1030  1389 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-31 11:31:19.852  1030  1389 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-31 11:31:19.852  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 11:31:19.853  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-31 11:31:19.878  1030  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_6659/cgroup.procs: No such file or directory
,08-31 11:31:19.889  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=225117  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-31 11:31:19.891  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=225119  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-31 11:31:19.895  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:19.895  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:19.900  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:31:19.900  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:19.900  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:19.900  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 11:31:19.903  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:19.903  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:19.904  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:19.904  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:19.904  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 11:31:19.905  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:19.905  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-31 11:31:19.908  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:19.973  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 11:31:19.973  7174  7174 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 11:31:19.973  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-31 11:31:19.973  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 11:31:19.973  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-31 11:31:19.974  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=225202  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-31 11:31:19.975  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=225203  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 11:31:19.976  1030  1389 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=225204
08-31 11:31:19.976  1030  1389 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=225204
08-31 11:31:19.976  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:31:19.976  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:31:19.977  1030  1389 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=225205
08-31 11:31:19.977  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=225205
08-31 11:31:19.978  1030  1389 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=225206
08-31 11:31:19.982  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:19.982  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-31 11:31:19.983  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=225211  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 11:31:19.986  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:19.987  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:19.987  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 11:31:19.987  1030  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 11:31:19.989  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:19.989  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:19.990  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:19.993  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:31:19.993  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:31:19.994  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=225221  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 11:31:19.994  7174  7174 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:31:19.994  7174  7174 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:31:19.995  1030  1389 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:19.995  1030  1389 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:19.995  1030  1389 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:19.996  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:19.996  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:19.997  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 11:31:19.997  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent:, WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:31:19.997  1030  7181 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:31:19.997  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 11:31:19.997  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:31:19.997  1030  7181 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:31:19.999  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=225227  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 11:31:19.999  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:31:19.999  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:31:20.000  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=225228  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 11:31:20.003  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:20.003  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:20.003  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 11:31:20.004  1030  1389 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=225233
08-31 11:31:20.005  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:20.005  1030  1030 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-31 11:31:20.007  1030  1389 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=225235
08-31 11:31:20.007  1030  1389 D WifiNative-wlan0: doString: [STATUS]
08-31 11:31:20.008  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:31:20.008  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:31:20.008  1030  1389 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 11:31:20.010  1030  1389 I WifiServiceExtension: setVHTCapabilityType  : false
08-31 11:31:20.011  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:20.011  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:20.013  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:20.016  1030  1389 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 11:31:20.016  1030  1389 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-31 11:31:20.019  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:20.019  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
08-31 11:31:20.019  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 11:31:20.029  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:20.029  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:20.029  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 11:31:20.029  1030  1389 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-31 11:31:20.030  1030  1444 D ConnectivityService: Got NetworkAgent Messenger
08-31 11:31:20.030  1030  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 11:31:20.030  1030  1444 D ConnectivityService: NetworkAgent connected
08-31 11:31:20.031  1030  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:31:20.031  1030  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:31:20.032  1030  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:31:20.032  1030  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:31:20.033  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:20.033  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:20.034  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:20.036  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:20.037  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:20.037  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:20.041  1030  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 11:31:20.041  1030  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:31:20.041  1030  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:31:20.042  1030  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:31:20.042  1030  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:31:20.058  1030  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 11:31:20.060   304   890 D CommandListener: Setting iface cfg
08-31 11:31:20.063  1030  1389 E WifiStateMachine: Start Dhcp Watchdog 2
08-31 11:31:20.063  1030  1389 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=225291  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:31:20.064  1030  1389 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=225292  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:31:20.064  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=225292  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:31:20.065  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:20.065  1030  1389 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=225293  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:31:20.065  1030  1030 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-31 11:31:20.066  1030  1389 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=225294  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:31:20.066  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=225294  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:31:20.067  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:179458] from screen [on:0 period:-537902461] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 11:31:20.068  1030  7247 D DhcpStateMachine: StoppedState
08-31 11:31:20.068  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-537902460] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 11:31:20.068  1030  1389 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 11:31:20.068  1030  7247 D DhcpStateMachine: StoppedState{ when=-5ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:20.069  1030  7247 D DhcpStateMachine: WaitBeforeStartState
08-31 11:31:20.071  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:20.073  1030  1444 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-31 11:31:20.074  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:20.074  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:20.074  1030  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:20.075  1030  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:20.075  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:20.076  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:20.077  1030  1444 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 11:31:20.078  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:20.078  1030  1030 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 11:31:20.079  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:20.079  1030  1030 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 11:31:20.079  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=114,0,0
08-31 11:31:20.080  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=114,0,0
08-31 11:31:20.080  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 11:31:20.080  7174  7174 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-31 11:31:20.081  1030  1389 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 11:31:20.081  1030  1389 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 11:31:20.081  1030  1389 D WifiNative-wlan0: SET ps 0: returned true
08-31 11:31:20.081  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-31 11:31:20.081  7174  7174 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 11:31:20.082  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 11:31:20.082  1030  1389 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 11:31:20.082  1030  1389 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 11:31:20.082  1030  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@17655b81 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:20.082  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@17655b81 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:20.082  1030  1389 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 11:31:20.082  1030  7247 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:20.082  1030  7247 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 11:31:20.083   304   890 D CommandListener: Setting iface cfg
08-31 11:31:20.083   304   890 D CommandListener: Trying to bring up wlan0
08-31 11:31:20.083  1030  1389 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-31 11:31:20.084  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-31 11:31:20.084  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-31 11:31:20.084  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 11:31:20.085  1030  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:20.085  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:20.085  7174  7174 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:31:20.085  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:31:20.085  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 11:31:20.085  7174  7174 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 11:31:20.086  1030  1389 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 11:31:20.086  1030  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:31:20.113  1030  1389 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:31:20.114  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-31 11:31:20.114  1030  1444 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 11:31:20.114  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:20.115  1030  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:20.115  1030  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:20.115  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:20.116  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:20.117  1030  1444 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 11:31:20.117  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 11:31:20.118  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 11:31:20.118  1030  1389 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 11:31:20.118  1030  1444 D ConnectivityService: ignoring duplicate network state non-change
08-31 11:31:20.161  1030  1884 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7249 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-31 11:31:20.162  1030  1884 I ActivityManager: Killing 2126:com.lge.music/u0a34 (adj 15): empty #17
08-31 11:31:20.183   311  2151 V AudioFlinger: 2126 died, releasing its sessions
08-31 11:31:20.183   311  2151 V AudioFlinger:  pid 1848 @ 0
,08-31 11:31:20.183   311  2151 V AudioFlinger:  pid 3475 @ 1
08-31 11:31:20.183   311  2151 V AudioFlinger:  pid 3475 @ 2
08-31 11:31:20.229  1030  1377 V AlarmManager: RTC_WAKEUP set : Alarm{1ecf7426 type 0 when 1472635846041 com.google.android.gms} when 1472635846041
08-31 11:31:20.229  1030  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{f1c3867 type 2 when 225380 android} when 225380
08-31 11:31:20.232  1030  2009 W libprocessgroup: failed to open /acct/uid_10034/pid_2126/cgroup.procs: No such file or directory
08-31 11:31:20.238  1030  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 11:31:20.239  1030  1444 D ConnectivityService: Adding iface wlan0 to network 101
,08-31 11:31:20.242  1030  1388 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:20.242  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:20.242  1030  1388 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:31:20.252  1030  1389 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 11:31:20.279  1030  1444 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 11:31:20.279  1030  1444 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-31 11:31:20.280  1030  1444 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-31 11:31:20.281   304   890 E Netd    : netlink response contains error (File exists)
,08-31 11:31:20.282  1030  1444 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-31 11:31:20.284  1030  1444 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-31 11:31:20.284  1030  1444 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-31 11:31:20.284  1030  1444 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-31 11:31:20.284  1030  7247 D DhcpStateMachine: DHCPV4 request on wlan0
08-31 11:31:20.284  1030  7247 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-31 11:31:20.284  1030  7247 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-31 11:31:20.285  1030  1444 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 11:31:20.285  1030  1444 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 11:31:20.285  1030  1444 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-31 11:31:20.285  1030  1444 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-31 11:31:20.285  1030  7241 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:20.285  1030  1444 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:31:20.285  1030  7241 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 11:31:20.285  1030  1444 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:20.285  1030  1444 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 11:31:20.285  1030  7241 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:20.285  1030  1444 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:20.286  1030  7241 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 11:31:20.286  1030  1444 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 11:31:20.286  1030  1444 D ConnectivityService: currentScore = 0, newScore = 20
08-31 11:31:20.286  1030  1444 D ConnectivityService:    accepting network in place of null
08-31 11:31:20.286  1030  1444 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:20.287  1848  1848 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:20.288  1848  1848 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 11:31:20.288  1030  1389 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:20.280  7269  7269 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:20.280  7269  7269 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:20.289   304  7271 D libc-n,etbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-31 11:31:20.288  1030  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:31:20.291  1030  1444 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 11:31:20.291  1030  1444 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 11:31:20.291  1030  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:31:20.292  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:20.293  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:20.294  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:31:20.296  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:20.296  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:20.296  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 11:31:20.297  7269  7269 I dhcpcd  : version 5.5.6 starting
08-31 11:31:20.299  7269  7269 E dhcpcd  : get_duid: m
08-31 11:31:20.299  7269  7269 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 11:31:20.299  7269  7269 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-31 11:31:20.302  1030  1389 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-31 11:31:20.303  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 11:31:20.303  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:20.304  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:20.304  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 11:31:20.304  1030  1389 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 11:31:20.304  1030  1389 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 11:31:20.305  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 11:31:20.305  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 11:31:20.305  1030  1389 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-31 11:31:20.310  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-31 11:31:20.314  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:20.314  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:31:20.314  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 11:31:20.315  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 11:31:20.320  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:20.320  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:20.326  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:20.326  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:20.326  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 11:31:20.326  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:31:20.329  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:20.329  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 11:31:20.330  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:20.332  1030  1444 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:20.332  1030  1444 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 11:31:20.333  1030  1444 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 11:31:20.334  1030  1444 D ConnectivityService: validation of new default Network = false
08-31 11:31:20.334  1030  1444 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 11:31:20.334  1030  1444 D DSQN    : enableDataServiceNotify 
08-31 11:31:20.334  1030  1444 D DSQN    : start dsqn bin
08-31 11:31:20.337  1030  1030 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 11:31:20.338  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:31:20.338  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:31:20.338  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-31 11:31:20.340  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:20.340  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 11:31:20.341  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:20.341  1030  1444 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-31 11:31:20.341  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:20.341  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:20.342   304  7271 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-31 11:31:20.330  7276  7276 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:20.330  7276  7276 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:20.347  1030  1444 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:20.347  1600  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 11:31:20.353  7276  7276 E DSQN    : DSQN ssw
08-31 11:31:20.367  7269  7269 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 11:31:20.367  7269  7269 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-31 11:31:20.367  7269  7269 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 11:31:20.368  7269  7269 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-31 11:31:20.368  7269  7269 D dhcpcd  : wlan0: sending REQUEST (xid 0x97cb1b17), next in 4.33 seconds
08-31 11:31:20.375   304  7271 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-31 11:31:20.378  1030  2048 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7282 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:31:20.379  1030  2048 I ActivityManager: Killing 6676:com.lge.bnr/1000 (adj 15): empty #17
,08-31 11:31:20.398   304   889 D LGDataListener: argv[0]=dsqncommand
08-31 11:31:20.398   304   889 D LGDataListener: argv[1]=wlan0
,08-31 11:31:20.398   304   889 D LGDataListener: argv[2]=1
08-31 11:31:20.398   304   889 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-31 11:31:20.399  1030  1092 D DSQN    : DSQM DsqnNotification wlan0  1
08-31 11:31:20.399  1030  1092 D DSQN    : start to monitor internet connection
08-31 11:31:20.402   339   339 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 449us total 20.168ms
08-31 11:31:20.419  7269  7269 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-31 11:31:20.421   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 397us total 18.628ms
,08-31 11:31:20.423  1030  7241 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 09:31:20 GMT], X-Android-Received-Millis=[1472635880422], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472635880397]}
08-31 11:31:20.423  1030  7241 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 11:31:20.423  1030  7241 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-31 11:31:20.423  1030  1444 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-31 11:31:20.423  1030  1444 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-31 11:31:20.423  1030  1444 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:31:20.423  1030  1444 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:20.423  1030  1444 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 11:31:20.423  1030  1444 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-31 11:31:20.423  1030  1444 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-31 11:31:20.423  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:20.423  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:20.423  1030  1444 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:20.423  1030  1444 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:20.424  1030  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-31 11:31:20.424  1600  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 11:31:20.424  1030  1389 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:20.424  1848  1848 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:20.424  1030  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:31:20.424  1848  1848 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 11:31:20.439   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 361us total 16.933ms
,08-31 11:31:20.446  7269  7269 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 11:31:20.447  7269  7269 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-31 11:31:20.447  7269  7269 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 11:31:20.447  7269  7269 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-31 11:31:20.448  7269  7269 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 11:31:20.448  7269  7269 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 11:31:20.448  7269  7269 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 11:31:20.448  7269  7269 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-31 11:31:20.448  1030  1989 W libprocessgroup: failed to open /acct/uid_1000/pid_6676/cgroup.procs: No such file or directory
,08-31 11:31:20.465  1030  1387 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-31 11:31:20.489  1813  7304 I CheckinService: active receiver: enabled
,08-31 11:31:20.508  1813  7304 I CheckinService: Preparing to send checkin request
08-31 11:31:20.508  1813  7304 I EventLogService: Accumulating logs since 1472635712161
,08-31 11:31:20.508  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:31:20.509  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:20.510  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:20.510  7282  7282 I art     : Almond Protected OAT
08-31 11:31:20.535  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:31:20.537  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:20.538  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:31:20.546  1813  7304 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-31 11:31:20.569  7282  7282 D WeatherApplication: removeAccount
,08-31 11:31:20.571  7282  7282 D WeatherApplication: Account.length = 0
08-31 11:31:20.571  7282  7282 E WeatherApplication: OPERATOR:OPEN
08-31 11:31:20.576  7282  7282 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:31:20
08-31 11:31:20.580  7282  7282 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 11:31:20.580  7282  7282 D Weather.Utils: 2 : All the weather widget is gone.
08-31 11:31:20.582  7282  7282 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-31 11:31:20.585  7282  7282 D WeatherAncestor: connectivity changed - connection : true
08-31 11:31:20.586  7282  7282 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-31 11:31:20.594  7282  7282 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-31 11:31:20.594  7282  7282 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 11:31:20.594  7282  7282 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-31 11:31:20.621  7282  7282 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 11:31:20.621  7282  7282 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:31:20
,08-31 11:31:20.637  1030  1989 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7324 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-31 11:31:20.674  1030  1046 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7341 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:31:20.675  1030  1956 I ActivityManager: Killing 6108:com.android.vending/u0a44 (adj 15): empty #17
08-31 11:31:20.688  1030  7247 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-31 11:31:20.690  1030  7247 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-31 11:31:20.690  1030  7247 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 11:31:20.690  1030  7247 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-31 11:31:20.690  1030  7247 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-31 11:31:20.690  1030  7247 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 11:31:20.690  1030  7247 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-31 11:31:20.690  1030  7247 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 11:31:20.690  1030  7247 D DhcpStateMachine: RunningState
,08-31 11:31:20.731  1030  1883 W libprocessgroup: failed to open /acct/uid_10044/pid_6108/cgroup.procs: No such file or directory
,08-31 11:31:20.761  7324  7324 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 11:31:20.761  7324  7324 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 11:31:20.794  7324  7324 I MultiDex: VM with version 2.1.0 has multidex support
,08-31 11:31:20.794  7324  7324 I MultiDex: install
08-31 11:31:20.794  7324  7324 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 11:31:20.808  7324  7324 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-31 11:31:20.893   278   370 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 11:31:20.893   278   370 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 11:31:20.893   278   370 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:31:20.894  7341  7360 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-31 11:31:20.898   278   370 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 11:31:20.898   278   370 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 11:31:20.898   278   370 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 11:31:20.899  7341  7360 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-31 11:31:20.904   278   370 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 11:31:20.904   278   370 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 11:31:20.904   278   370 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 11:31:20.904  7341  7364 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-31 11:31:20.912   278   370 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 11:31:20.912   278   370 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 11:31:20.912   278   370 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 11:31:20.912  7341  7364 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-31 11:31:21.064  7324  7339 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:31:21.065  7324  7339 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:31:21.106  7382  7382 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-31 11:31:21.142  7382  7382 I dex2oat : dex2oat took 36.155ms (threads: 4)
08-31 11:31:21.152  7324  7339 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:31:21.152  7324  7339 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:31:21.152  7324  7339 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:31:21.152  7324  7339 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:31:21.152  7324  7339 I Adreno-EGL: Remote Branch: 
08-31 11:31:21.152  7324  7339 I Adreno-EGL: Local Patches: 
08-31 11:31:21.152  7324  7339 I Adreno-EGL: Reconstruct Branch: 
,08-31 11:31:21.185  7341  7341 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-31 11:31:21.234  7324  7339 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:31:21.234  7324  7339 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:31:21.234  7324  7339 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:31:21.234  7324  7339 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:31:21.234  7324  7339 I Adreno-EGL: Remote Branch: 
08-31 11:31:21.234  7324  7339 I Adreno-EGL: Local Patches: 
08-31 11:31:21.234  7324  7339 I Adreno-EGL: Reconstruct Branch: 
,08-31 11:31:21.239  1030  1389 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:21.240  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:21.240  1030  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:21.240  1030  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:21.241  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:21.241  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:21.242  1030  1444 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-31 11:31:21.242  1030  1444 D ConnectivityService: identical MTU - not setting
08-31 11:31:21.242  1030  1444 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 11:31:21.242  1030  1444 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 11:31:21.242  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:21.242  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:21.243  1030  1444 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:21.243  1600  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-31 11:31:21.273  1030  1046 I art     : Explicit concurrent mark sweep GC freed 106818(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.657ms total 138.079ms
,08-31 11:31:21.277  1030  1884 D WifiServiceImplEx: setWifiEnabled: false pid=6821, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 11:31:21.278  1030  1884 D WifiService: setWifiEnabled: false pid=6821, uid=10118
08-31 11:31:21.278  1030  1884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 11:31:21.278  7324  7339 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:31:21.278  7324  7339 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:31:21.278  7324  7339 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:31:21.278  7324  7339 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:31:21.278  7324  7339 I Adreno-EGL: Remote Branch: 
08-31 11:31:21.278  7324  7339 I Adreno-EGL: Local Patches: 
08-31 11:31:21.278  7324  7339 I Adreno-EGL: Reconstruct Branch: 
08-31 11:31:21.284  7341  7341 I LibraryLoader: Loading: webviewchromium
08-31 11:31:21.288  1030  1389 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 11:31:21.288  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 11:31:21.288  1030  1389 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 11:31:21.288  1030  1389 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-31 11:31:21.289  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-31 11:31:21.289  1030  1389 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 11:31:21.289  1030  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:31:21.289  1030  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:31:21.289  1030  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:31:21.289  1030  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:31:21.289  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:31:21.290  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:31:21.290  1030  1030 D Ulp_jni : JNI:system_update. Event-4
,08-31 11:31:21.291  7341  7341 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 6527-6534)
08-31 11:31:21.291  7341  7341 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 11:31:21.292  1030  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 11:31:21.292  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-31 11:31:21.292  7174  7174 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:31:21.292  1030  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:31:21.292  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:21.292  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,08-31 11:31:21.292  1030  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:31:21.293  1030  1389 D WifiNative-wlan0: SET ps 1: returned true
,08-31 11:31:21.293  1030  7247 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:31:21.293   304   890 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:31:21.300  7341  7341 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1a433231}
08-31 11:31:21.301  7341  7341 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:31:21.301  7341  7341 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 11:31:21.308  7341  7341 I BrowserStartupController: Initializing chromium process, renderers=0
08-31 11:31:21.309  7341  7341 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:31:21.323  1030  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 11:31:21.323  1030  1444 D ConnectivityService: ignoring duplicate network state non-change
08-31 11:31:21.323  1030  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-31 11:31:21.324  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:21.324  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:21.325  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-31 11:31:21.325  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:21.325  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-31 11:31:21.326  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:21.326  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:21.326  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:31:21.327  1030  1388 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:21.327  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:21.327  1030  1388 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1dd532dc
08-31 11:31:21.327  1030  1388 D LGWifiP2pService: P2pDisablingState
08-31 11:31:21.327  1030  1388 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:21.327  1030  1388 D LGWifiP2pService: p2p socket connection lost
08-31 11:31:21.327  1030  1388 D LGWifiP2pService: P2pDisabledState
,08-31 11:31:21.327  1030  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:21.327  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:21.328  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:21.328  1030  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:21.329  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:21.329  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:21.330  1030  1389 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 11:31:21.330  1030  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-31 11:31:21.330  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 11:31:21.330  1030  1388 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:21.330  7174  7174 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:31:21.330  1030  1388 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:21.330  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:31:21.331  1030  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:31:21.331  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-31 11:31:21.331  1030  1389 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:31:21.333  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:21.333  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:21.333  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:31:21.333  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 11:31:21.333  1030  1555 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:21.334  1030  1030 D RttService: SCAN_AVAILABLE : 1
08-31 11:31:21.334  1030  1556 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:21.342  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 11:31:21.342  1939  1939 D WfdsService: WifiP2pState is changed : false
08-31 11:31:21.342  1939  2290 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 11:31:21.342  1939  2290 D WfdsService: Set the WFDS Monitor: false
08-31 11:31:21.343  1939  2290 D WfdsMonitor: WFDS Monitor is stopped
08-31 11:31:21.343  1939  2290 D WfdsService: STATE : WfdsDisabledState - enter
08-31 11:31:21.343  1939  7184 D CtrlSupplicant: Received on exit socket, terminate
08-31 11:31:21.343  1939  7184 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 11:31:21.343  1939  7184 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 11:31:21.343  1939  7184 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-31 11:31:21.344  1939  2298 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 11:31:21.344  1939  2290 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 11:31:21.345  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:21.345  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 11:31:21.348  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:21.351  7341  7341 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-31 11:31:21.352  7341  7341 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-31 11:31:21.352  7341  7341 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-31 11:31:21.355   311  1397 V AudioPolicyService: registerClient() client 0xb558a280, uid 10093
08-31 11:31:21.357  7341  7402 W AudioManagerAndroid: Requires BLUETOOTH permission
08-31 11:31:21.363  7341  7341 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:31:21.363  7341  7341 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:31:21.363  7341  7341 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:31:21.363  7341  7341 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:31:21.363  7341  7341 I Adreno-EGL: Remote Branch: 
08-31 11:31:21.363  7341  7341 I Adreno-EGL: Local Patches: 
08-31 11:31:21.363  7341  7341 I Adreno-EGL: Reconstruct Branch: 
,08-31 11:31:21.377   304   890 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:31:21.378  1030  1444 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-31 11:31:21.378  1030  1444 D DSQN    : disableDataServiceNotify
08-31 11:31:21.378  1030  1444 D DSQN    : stop dsqn bin
08-31 11:31:21.379  1030  1389 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 11:31:21.380  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-31 11:31:21.381  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:21.381  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:21.381  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:31:21.381  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 11:31:21.381  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:21.382  1030  1389 D WifiNative-p2p0: TERMINATE: returned true
08-31 11:31:21.382  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:31:21.382  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:31:21.382  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:31:21.382  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:21.384  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 11:31:21.384  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:21.384  1030  1030 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-31 11:31:21.384  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-31 11:31:21.385  1030  1444 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-31 11:31:21.386  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:21.386  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:21.386  1030  1444 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:21.386  1030  1444 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-31 11:31:21.386  1600  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 11:31:21.387  1030  1444 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-31 11:31:21.387  1030  1444 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 11:31:21.387  1030  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:31:21.387  1030  7241 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.St,ateMachine$SmHandler }
08-31 11:31:21.387  1030  7241 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:21.387  1030  7241 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 11:31:21.387  1030  1444 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:21.388  1030  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:31:21.388  1030  1444 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:21.388  1030  1444 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:21.388  1030  1444 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:21.389  1030  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 11:31:21.389  1030  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 11:31:21.389  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 11:31:21.389  1848  1848 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:21.390  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:21.390  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:31:21.390  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:21.390  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:21.390  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:21.390  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:31:21.390  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:31:21.390  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:21.390  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:21.390  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:31:21.390  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:31:21.390  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:31:21.390  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:21.390  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:31:21.390  1848  1848 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-31 11:31:21.393  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:21.393  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:21.393  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:21.393  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:21.393  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:31:21.393  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:31:21.393  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:21.393  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:21.393  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:31:21.393  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:21.393  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:31:21.394  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 11:31:21.395  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:31:21.395  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:31:21.395  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:31:21.396  1030  1389 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:21.396  1030  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:31:21.397  1030  1444 D NetworkManagementService: Removing idletimer
08-31 11:31:21.397  1030  1444 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:21.397  1030  1444 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-31 11:31:21.402  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:31:21.417  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:31:21.418  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:31:21.418  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:21.429  7341  7341 I NSApplication: Starting up...
,08-31 11:31:21.431  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:31:21.432  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:21.432  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:21.467  7174  7174 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 11:31:21.468  7174  7174 I wpa_supplicant: monitor socket send errors count : 1
08-31 11:31:21.468  7174  7174 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1939-4\x00 that cannot receive messages
,08-31 11:31:21.468  1030  7181 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-31 11:31:21.469  1030  7181 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 11:31:21.488  1030  1046 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7419 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-31 11:31:21.489  1030  1046 I ActivityManager: Killing 6757:com.lge.clock/u0a10 (adj 15): empty #17
,08-31 11:31:21.497  1030  7247 D DhcpStateMachine: StoppedState
08-31 11:31:21.497  1030  7247 D DhcpStateMachine: StoppedState{ when=-166ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:31:21.509  7174  7174 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:31:21.510  7174  7174 W wpa_supplicant: USIM:  scard_deinit function
08-31 11:31:21.510  1030  1094 D Tethering: InitialState.processMessage what=4
08-31 11:31:21.511  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-31 11:31:21.512  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:31:21.512  1030  7181 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:31:21.512  1030  7181 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 11:31:21.512  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:31:21.512  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:31:21.512  1030  1389 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=226741
08-31 11:31:21.513  1030  1389 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=226741
,08-31 11:31:21.513  1030  1389 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=226741  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 11:31:21.514  1030  1389 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=226742  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 11:31:21.549  1030  1883 W libprocessgroup: failed to open /acct/uid_10010/pid_6757/cgroup.procs: No such file or directory
08-31 11:31:21.549  1030  1389 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-31 11:31:21.550  1030  1389 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-31 11:31:21.552  1030  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:31:21.552  1030  1389 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:21.553  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:21.584  7419  7419 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:31:21.601   304  7437 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 11:31:21.602  1030  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 11:31:21.602  1813  7304 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-31 11:31:21.613  1813  7304 I CheckinService: active receiver: disabled
,08-31 11:31:21.699  7174  7174 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-31 11:31:21.701  1030  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,08-31 11:31:21.701  1030  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 11:31:21.701  1030  7181 D WifiMonitor: Disconnecting from the supplicant, no more events
08-31 11:31:21.702  1030  1389 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-31 11:31:21.804  1030  1389 D WifiOffDelayIfNotUsed: stopMonitoring
08-31 11:31:21.805  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:31:21.805  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:31:21.805  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:31:21.805  1939  1939 D WfdsService: Supplicant Connection state is changed : false
08-31 11:31:21.805  1939  2290 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-31 11:31:21.805  1939  2290 D WfdsService: Set the WFDS Monitor: false
,08-31 11:31:21.805  1939  2290 D WfdsMonitor: WFDS Monitor is stopped
08-31 11:31:21.808  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:21.810  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 11:31:21.814  2478  2478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:21.817  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-31 11:31:21.817  1030  1438 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-31 11:31:21.817  1030  1438 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-31 11:31:21.818  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:21.818  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:21.818  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:21.818  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:21.818  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:31:21.818  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:31:21.818  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:21.818  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:21.818  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:31:21.819  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:21.819  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:21.819  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:21.819  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:21.819  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:31:21.819  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:31:21.819  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:21.819  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:21.819  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:31:21.889  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-31 11:31:21.892  6502  6969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 11:31:21.911  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:31:21.921  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 11:31:21.921  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:21.921  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 11:31:21.921  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 11:31:21.923  7122  7122 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 11:31:21.927  7122  7122 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@21dabb8e
08-31 11:31:21.927  7122  7122 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:31:21.927  7122  7122 D AppUp4:CustFacade: isPhone : true
08-31 11:31:21.927  7122  7122 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:31:21.928  7122  7122 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 11:31:21.931  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:21.932  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:31:21.934  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:31:21.936  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 11:31:21.945  7156  7156 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 11:31:21.949  4340  7447 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 11:31:21.953  4340  7450 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:21.953  4340  7450 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:31:21.977  7039  7454 W FormManager: Network not available. Please check & try again.
08-31 11:31:21.977  7156  7452 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:21.978  7039  7455 V FormManager: Network unavailable.
,08-31 11:31:21.983  3475  3475 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 11:31:21.983  3475  3475 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:21.984  3475  3475 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 11:31:21.986  7192  7192 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 11:31:21.987  7192  7192 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 11:31:21.992  7039  7455 V FormManager: Network unavailable.
,08-31 11:31:21.999  7282  7282 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:31:21
08-31 11:31:22.003  7282  7282 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 11:31:22.003  7282  7282 D Weather.Utils: 2 : All the weather widget is gone.
08-31 11:31:22.003  7282  7282 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 11:31:22.003  7282  7282 D WeatherAncestor: connectivity changed - connection : true
08-31 11:31:22.004  7282  7282 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@17426fbc
08-31 11:31:22.004  7282  7282 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-31 11:31:22.004  7282  7282 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 11:31:22.004  7282  7282 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 11:31:22.005  7282  7282 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 11:31:22.005  7282  7282 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:31:22
08-31 11:31:22.034  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:31:22.034  6950  6950 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:31:22.034  6950  6950 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:31:22.034  6950  6950 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-31 11:31:22.036  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 11:31:22.037  6950  6950 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:31:22.037  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 11:31:22.037  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:31:22.037  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 11:31:22.037  6950  6950 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:31:22.038  6950  6950 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:31:22.044   304  7458 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 11:31:22.045  1030  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 11:31:22.048  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:31:22.052  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:31:22.060  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:22.070  7039  7460 W FormManager: Network not available. Please check & try again.
,08-31 11:31:22.077  7039  7461 V FormManager: Network unavailable.
,08-31 11:31:22.082  7039  7461 V FormManager: Network unavailable.
,08-31 11:31:22.099  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:31:22.105  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:31:22.109  7039  7463 W FormManager: Network not available. Please check & try again.
08-31 11:31:22.111  7039  7464 V FormManager: Network unavailable.
,08-31 11:31:22.114  7039  7464 V FormManager: Network unavailable.
08-31 11:31:22.114  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:22.135  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:31:22.135  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-31 11:31:22.138  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 11:31:22.141  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:31:22.153  4340  7465 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 11:31:22.165  4340  7466 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-31 11:31:22.166  4340  7466 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 11:31:22.224  1030  1937 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7467 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 11:31:22.279  6697  7102 D UEI.SmartControl: Internal timer expired: 2
,08-31 11:31:22.280  6697  7102 D UEI.SmartControl: unbind internal service
,08-31 11:31:22.369  7467  7467 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 11:31:22.369  7467  7467 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-31 11:31:22.377  6697  7096 D serial_port: close(fd = 24)
08-31 11:31:22.381  6697  7096 I UEI.SmartControl: Serial port is closed.
08-31 11:31:22.381  7467  7467 V [BNRBootReceiver]: Boot Receiver Return
08-31 11:31:22.385  7467  7467 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-31 11:31:22.390  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:31:22.399  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:22.413  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:22.439  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:22.440  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:22.443  6998  6998 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 11:31:22.449  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-31 11:31:22.458  6950  6950 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 11:31:22.468  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:22.486  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:22.495  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:31:22.507  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:31:22.507  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:31:22.511  6998  6998 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:31:22.518  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:22.541  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:22.555  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:31:22.571  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:22.572  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:31:22.573  6998  6998 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:31:22.580  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:22.596  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:22.613  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:22.624  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:22.625  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:22.625  6998  6998 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 11:31:22.632  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:31:22.647  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:22.655  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:31:22.664  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:31:22.665  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:22.667  6998  6998 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:31:22.673  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:22.683  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:22.689  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:22.697  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:31:22.698  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:22.699  6998  6998 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:31:22.703  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:22.714  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:22.726  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:31:22.737  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:22.738  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:31:22.739  6998  6998 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:31:22.743  1030  2021 I ActivityManager: Killing 6929:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-31 11:31:22.785  1030  2047 W libprocessgroup: failed to open /acct/uid_10037/pid_6929/cgroup.procs: No such file or directory
,08-31 11:31:22.801  1813  2366 I EventLogService: Aggregate from 1472635880508 (log), 1472634045874 (data)
,08-31 11:31:22.810  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:22.830  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:22.837  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:22.844  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:31:22.844  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:22.849  6998  6998 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:31:22.853  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:22.865  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:22.875  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:22.886  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:31:22.888  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:22.891  6998  6998 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:31:22.898  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:22.903  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-31 11:31:22.911  1030  1443 D WifiService: New client listening to asynchronous messages
08-31 11:31:22.911  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:31:22.915  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:22.921  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:22.927  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:22.927  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:22.928  6998  6998 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-31 11:31:22.929  6998  6998 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 11:31:22.930  6998  6998 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 11:31:22.935  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:22.939  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 11:31:22.940  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:31:22.945  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:31:22.950  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:22.957  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:22.957  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:31:22.958  6998  6998 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 11:31:22.959  6998  6998 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 11:31:22.960  6998  6998 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 11:31:22.965  2194  2194 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-31 11:31:22.974  2194  2194 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-31 11:31:22.974  2194  2194 D c       : Getting all permits...
,08-31 11:31:22.974  2194  2194 D a       : Opening database...
08-31 11:31:22.979  2194  2194 D a       : Opening database auth.proximity.permit_store...
08-31 11:31:22.981  2194  2194 D a       : Closing database...
08-31 11:31:22.996  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:31:23.002  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-31 11:31:23.002  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:31:23.002  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:31:23.006  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:23.013  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:31:23.024  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:23.024  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:31:23.027  6998  6998 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 11:31:23.033  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:23.042  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:31:23.043  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-31 11:31:23.043  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:31:23.051  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:23.061  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:23.072  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:31:23.075  1030  1389 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-537899453] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 11:31:23.076  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:23.077  1030  1389 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-537899451] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 11:31:23.079  6998  6998 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:31:23.086  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:31:23.100  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:31:23.100  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:31:23.100  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:31:23.104  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:23.115  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:23.127  6998  6998 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:23.127  6998  6998 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:23.129  6998  6998 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 11:31:23.145  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:31:23.148  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:31:23.165  7039  7499 W FormManager: Network not available. Please check & try again.
08-31 11:31:23.167  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:23.185  7039  7500 V FormManager: Network unavailable.
,08-31 11:31:23.205  7039  7500 V FormManager: Network unavailable.
,08-31 11:31:23.225  2194  2194 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-31 11:31:23.248  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:31:23.248  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:31:23.250  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 11:31:23.252  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:31:23.257  4340  7504 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:31:23.259  4340  7505 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:31:23.260  4340  7505 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:31:23.265  6970  6970 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-31 11:31:23.265  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:31:23.265  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:31:23.270  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:31:23.273  7039  7507 W FormManager: Network not available. Please check & try again.
08-31 11:31:23.279  7039  7508 V FormManager: Network unavailable.
08-31 11:31:23.280  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:31:23.286  7039  7508 V FormManager: Network unavailable.
08-31 11:31:23.312  6998  6998 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-31 11:31:23.312  6998  6998 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9159
08-31 11:31:23.315  1030  1030 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1004699867 [*alarm*], flags=0x0
08-31 11:31:23.334  1030  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:31:23.337  1030  1094 D Tethering: MasterInitialState.processMessage what=3
08-31 11:31:23.337  1030  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:23.342  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:23.343  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:23.348  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 11:31:23.348  5788  5788 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 11:31:23.350  6502  6969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 11:31:23.351  1030  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:23.372  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:31:23.384  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 11:31:23.384  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:31:23.384  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 11:31:23.384  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 11:31:23.387  7122  7122 I AppUp4:CustModeStarterReceiver: onReceive
08-31 11:31:23.391  7122  7122 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@21dabb8e
08-31 11:31:23.392  7122  7122 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:31:23.392  7122  7122 D AppUp4:CustFacade: isPhone : true
08-31 11:31:23.392  7122  7122 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:31:23.392  7122  7122 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 11:31:23.397  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:31:23.397  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:31:23.400  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:31:23.403  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:31:23.415  7156  7156 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 11:31:23.418  4340  7514 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:31:23.424  4340  7515 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:23.425  4340  7515 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:31:23.446  7156  7516 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:31:23.456  3475  3475 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 11:31:23.456  3475  3475 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:23.456  3475  3475 I LgeMiscReceiver: networkInfo.isConnected() = true
08-31 11:31:23.456  3475  3475 D PhoneState: setPdpRejectCasuse : false
08-31 11:31:23.461  7192  7192 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-31 11:31:23.461  7192  7192 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 11:31:23.473  7039  7518 W FormManager: Network not available. Please check & try again.
,08-31 11:31:23.477  7282  7282 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:31:23
08-31 11:31:23.479  7282  7282 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 11:31:23.479  7282  7282 D Weather.Utils: 2 : All the weather widget is gone.
08-31 11:31:23.479  7282  7282 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 11:31:23.479  7282  7282 D WeatherAncestor: connectivity changed - connection : true
08-31 11:31:23.479  7282  7282 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@17426fbc
08-31 11:31:23.481  7039  7519 V FormManager: Network unavailable.
08-31 11:31:23.481  7282  7282 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 11:31:23.481  7282  7282 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 11:31:23.481  7282  7282 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 11:31:23.481  7282  7282 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 11:31:23.481  7282  7282 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:31:23
08-31 11:31:23.497  7039  7519 V FormManager: Network unavailable.
,08-31 11:31:24.289  1030  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:31:24.290  1030  1956 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-31 11:31:24.322  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:31:24.322  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:31:24.322  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-31 11:31:24.323  1030  1094 D BluetoothManagerService: Message: 1
08-31 11:31:24.323  1030  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-31 11:31:24.350  1030  1094 D BluetoothManagerService: Message: 20
08-31 11:31:24.350  1030  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cec607d:true
,08-31 11:31:24.354  7056  7056 D BluetoothAdapterState: make
08-31 11:31:24.360  7056  7056 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 11:31:24.360  7056  7056 I bluedroid-qcom: init
08-31 11:31:24.361  7056  7531 I BluetoothAdapterState: Entering OffState
08-31 11:31:24.362  7056  7056 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 11:31:24.362  7056  7056 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 11:31:24.362  7056  7056 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 11:31:24.362  7056  7056 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 11:31:24.362  7056  7056 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 11:31:24.366  7056  7056 I bluedroid-qcom: get_profile_interface socket
08-31 11:31:24.366  7056  7056 I bluedroid-qcom: get_profile_interface map_client
,08-31 11:31:24.370  7056  7535 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 11:31:24.372  7056  7535 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 11:31:24.360  7534  7534 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:24.360  7534  7534 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:24.380  1030  1030 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 11:31:24.380  1030  1030 D BluetoothManagerService: Stored Bluetooth name: G3
,08-31 11:31:24.388  1030  1030 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-31 11:31:24.389  1030  1094 D BluetoothManagerService: Message: 40
08-31 11:31:24.389  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 11:31:24.390  1030  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:24.393  7534  7534 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 11:31:24.393  7534  7534 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 11:31:24.393  7534  7534 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-31 11:31:24.395  1030  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:24.396  7534  7534 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-31 11:31:24.403  7534  7534 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 11:31:24.403  7534  7534 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-31 11:31:24.409  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:31:24.411  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:24.413  7056  7075 I bluedroid-qcom: config_hci_snoop_log
08-31 11:31:24.414  1030  1094 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 11:31:24.414  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 11:31:24.428  7056  7531 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-31 11:31:24.431  1030  1094 D Tethering: MasterInitialState.processMessage what=3
08-31 11:31:24.431  1030  1094 D Tethering: MasterInitialState.processMessage what=3
08-31 11:31:24.431  1030  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:24.432  7056  7535 D BluetoothAdapterProperties: Name is: G3
08-31 11:31:24.433  7056  7531 D BluetoothAdapterProperties: Setting state to 11
08-31 11:31:24.434  7056  7531 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 11:31:24.434  1030  1094 D BluetoothManagerService: Message: 60
08-31 11:31:24.434  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 11:31:24.435  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 11:31:24.435  7056  7531 I LGBluetoothServiceJni: classInitNative: succeeds
08-31 11:31:24.439  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:24.441  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:31:24.454  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-31 11:31:24.459  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:24.464  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:24.465  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:24.467  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 11:31:24.468  6950  6950 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-31 11:31:24.471  6502  6969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 11:31:24.471  7056  7531 D BluetoothBondStateMachine: make
,08-31 11:31:24.474  7056  7056 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:31:24.478  7056  7056 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:24.478  7056  7056 V BluetoothPbapReceiver: ***********state = 11
08-31 11:31:24.479  7056  7531 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
08-31 11:31:24.479  7056  7531 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 11:31:24.479  7056  7531 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
08-31 11:31:24.479  7056  7531 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 11:31:24.480  7056  7531 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-31 11:31:24.480  7056  7549 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 11:31:24.482  5788  5788 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 11:31:24.487  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:31:24.491  7056  7531 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:31:24.529  1030  1883 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7554 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-31 11:31:24.536  7056  7531 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:31:24.539  7056  7056 D HeadsetService: Received start request. Starting profile...
08-31 11:31:24.540  7056  7056 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 11:31:24.540  7056  7056 D LGBluetoothHfpAdapter: Version 1.6
,08-31 11:31:24.543  7056  7056 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 11:31:24.547  7056  7056 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 11:31:24.547  7056  7056 D HeadsetStateMachine: make
08-31 11:31:24.548  5788  5788 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 11:31:24.550  1030  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:31:24.557  7056  7531 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:31:24.571  7056  7531 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:31:24.580  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:24.581  7056  7056 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:31:24.581  7056  7056 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:31:24.582  1030  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:24.582  1030  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:24.583  7056  7531 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:31:24.585  7056  7056 D HeadsetStateMachine: max_hf_connections = 1
08-31 11:31:24.585  7056  7056 I bluedroid-qcom: get_profile_interface handsfree
08-31 11:31:24.587  7056  7056 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 11:31:24.588   311  2152 V AudioPolicyService: registerClient() client 0xb101dda0, uid 1002
08-31 11:31:24.588   311  2151 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 11:31:24.588   311  2151 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:31:24.588   311  2151 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:31:24.589  7056  7056 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 11:31:24.589   311  1397 V AudioFlinger: registerClient() client 0xb101bb80, pid 7056
08-31 11:31:24.589  7056  7056 V ToneGenerator: Create Track: 0xb4928080
08-31 11:31:24.589  7056  7056 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 11:31:24.589  7056  7056 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 11:31:24.590   311   311 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 11:31:24.590   311   311 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 11:31:24.590   311   311 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:31:24.590   311   311 V AudioPolicyManagerEx: getOutput() returns output 2
,08-31 11:31:24.590  7056  7056 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 11:31:24.591   311  1390 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:31:24.591   311  1390 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:31:24.591  1600  3240 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:31:24.591  1600  3240 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:31:24.591  7056  7075 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:31:24.592  7056  7075 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 11:31:24.592  1848  1863 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:31:24.592  1848  1863 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:31:24.592   311  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:31:24.592   311  1392 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:31:24.592  1600  1617 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:31:24.592  7056  7075 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:31:24.592  1600  1617 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:31:24.592  7056  7075 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 11:31:24.592  1848  2573 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:31:24.592  1848  2573 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:31:24.592  1030  2048 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:31:24.592  1030  2048 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:31:24.592  1030  2048 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:31:24.592  1030  2048 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:31:24.593  7056  7531 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:31:24.593  3475  3490 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:31:24.593  3475  3490 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:31:24.593  3475  3490 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:31:24.593  3475  3490 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:31:24.593   311  2151 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 11:31:24.593   311  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 11:31:24.593   311  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 11:31:24.593   311  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:31:24.593   311  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:31:24.593  7056  7056 V AudioSystem: getLatency() output 2, latency 50
08-31 11:31:24.593  7056  7056 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 11:31:24.593  7056  7056 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 11:31:24.594   311  1396 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 11:31:24.594   311  1396 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 11:31:24.594   311  1396 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 11:31:24.594   311  1396 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 11:31:24.594   311  1396 V AudioFlinger: createTrack() lSessionId: 20
08-31 11:31:24.595  7056  7056 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 11:31:24.595   311  1396 V AudioFlinger: acquiring 20 from 7056, for 7056
08-31 11:31:24.595   311  1396 V AudioFlinger:  added new entry for 20
08-31 11:31:24.596  7,056  7056 V ToneGenerator: ToneGenerator INIT OK, time: 229839
08-31 11:31:24.596  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
,08-31 11:31:24.596  7056  7563 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 11:31:24.597  7056  7563 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:31:24.597  7056  7563 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:31:24.597  7056  7563 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 11:31:24.597   311   311 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7056
08-31 11:31:24.598  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
08-31 11:31:24.598   311   311 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 11:31:24.598   311   311 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 11:31:24.598   311   311 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 11:31:24.598   311   311 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 11:31:24.598   311   311 V voice   : voice_set_parameters: exit with code(0)
08-31 11:31:24.598   311   311 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 11:31:24.598   311   311 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 11:31:24.598   311   311 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 11:31:24.598   311   311 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 11:31:24.598   311   311 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 11:31:24.598   311   311 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 11:31:24.598  7056  7563 V ToneGenerator: ToneGenerator destructor
08-31 11:31:24.598  7056  7563 V ToneGenerator: stopTone
08-31 11:31:24.598  7056  7563 V ToneGenerator: Delete Track: 0xb4928080
08-31 11:31:24.598  7056  7563 V AudioTrack: ~AudioTrack, releasing session id from 7056 on behalf of 7056
08-31 11:31:24.599   311  2152 V AudioFlinger: releasing 20 from 7056 for 7056
08-31 11:31:24.599   311  2152 V AudioFlinger:  decremented refcount to 0
08-31 11:31:24.599   311  2152 V AudioFlinger: purging stale effects
08-31 11:31:24.599   311  2152 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 11:31:24.599   311  2152 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 11:31:24.599   311  1209 V AudioPolicyService: AudioCommandThread() waking up
08-31 11:31:24.599   311  1209 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 11:31:24.599   311  1209 V AudioPolicyManager: releaseOutput() 2
08-31 11:31:24.599   311  1209 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 11:31:24.599   311  2152 V AudioFlinger: PlaybackThread::Track destructor
08-31 11:31:24.599   311  2152 V AudioFlinger: removeClient_l() pid 7056, calling pid 311
08-31 11:31:24.599  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 11:31:24.599  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:24.599  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 11:31:24.599  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 11:31:24.600  7056  7056 D A2dpService: Received start request. Starting profile...
08-31 11:31:24.601  7056  7531 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:31:24.602  7056  7056 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 11:31:24.602  7122  7122 I AppUp4:CustModeStarterReceiver: onReceive
08-31 11:31:24.603  7056  7056 V Avrcp   : make
08-31 11:31:24.603  1030  2048 W Process : Unable to open /proc/7573/status
08-31 11:31:24.603  7056  7056 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-31 11:31:24.603  7056  7056 I bluedroid-qcom: get_profile,_interface avrcp
08-31 11:31:24.608  7122  7122 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@21dabb8e
08-31 11:31:24.608  7122  7122 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:31:24.608  7122  7122 D AppUp4:CustFacade: isPhone : true
08-31 11:31:24.608  7122  7122 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:31:24.609  7122  7122 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 11:31:24.612  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:24.612  7056  7531 V LGMDMManager: Create singleton instance
,08-31 11:31:24.612  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:31:24.613  7056  7056 V AudioManager: registerRemoteController: size of Media player list: 0
08-31 11:31:24.614  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:31:24.614  7056  7531 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 11:31:24.615  7056  7056 E AudioManager: No RCC entry present to update
08-31 11:31:24.615  7056  7056 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 11:31:24.618  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:31:24.619  7056  7056 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-31 11:31:24.620  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 11:31:24.620  7056  7056 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 11:31:24.623  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 11:31:24.624  7156  7156 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 11:31:24.625  4340  7576 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 11:31:24.629  4340  7577 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:24.629  4340  7577 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:31:24.678  3475  3475 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 11:31:24.678  3475  3475 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:24.679  3475  3475 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-31 11:31:24.680  7156  7578 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:24.682  7192  7192 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 11:31:24.682  7192  7192 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 11:31:24.689  7282  7282 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:31:24
08-31 11:31:24.690  7282  7282 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-31 11:31:24.690  7282  7282 D Weather.Utils: 2 : All the weather widget is gone.
08-31 11:31:24.691  7282  7282 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 11:31:24.691  7282  7282 D WeatherAncestor: connectivity changed - connection : true
08-31 11:31:24.691  7282  7282 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@17426fbc
,08-31 11:31:24.692  7039  7581 W FormManager: Network not available. Please check & try again.
08-31 11:31:24.692  7282  7282 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 11:31:24.692  7282  7282 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 11:31:24.692  7282  7282 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 11:31:24.692  7282  7282 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 11:31:24.692  7282  7282 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:31:24
08-31 11:31:24.701  7039  7582 V FormManager: Network unavailable.
,08-31 11:31:24.706  7039  7582 V FormManager: Network unavailable.
08-31 11:31:24.710  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 11:31:24.711  6502  6969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 11:31:24.719  1030  2048 V SIM_STK : Menu title from STK is T-Mobile
08-31 11:31:24.719  1030  2048 V SIM_STK : Menu title from STK is T-Mobile
08-31 11:31:24.720  7554  7554 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-31 11:31:24.720  7554  7554 W LG Account v2.2: No ProfileInfo entries
08-31 11:31:24.720  7554  7554 I LG Account v2.2: isEnabled: false
08-31 11:31:24.720  7554  7554 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 11:31:24.721  7554  7554 I Feature : [Lifetracker]Country: EU
08-31 11:31:24.721  7554  7554 I Feature : [Lifetracker]Operator: OPEN
08-31 11:31:24.721  7554  7554 I Feature : [Lifetracker]Ranking support: false
08-31 11:31:24.721  7554  7554 I Feature : [Lifetracker]Comfort support: false
08-31 11:31:24.721  7554  7554 I Feature : [Lifetracker]Accessory: true
08-31 11:31:24.721  7554  7554 I Feature : [Lifetracker]Health device: true
08-31 11:31:24.721  7554  7554 I Feature : [Lifetracker]Extra Pedometer: false
08-31 11:31:24.721  7554  7554 I Feature : [Lifetracker]Blood glucose device: false
08-31 11:31:24.721  7554  7554 I Feature : [Lifetracker]Device Number: 3
,08-31 11:31:24.728  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:24.733  6950  6950 D BluetoothPermissionRequest: onReceive
08-31 11:31:24.737  6950  6950 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 11:31:24.744  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-31 11:31:24.744  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:24.744  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 11:31:24.744  7122  7122 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 11:31:24.745  7122  7122 I AppUp4:CustModeStarterReceiver: onReceive
08-31 11:31:24.747  7122  7122 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@21dabb8e
08-31 11:31:24.747  7122  7122 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:31:24.747  7122  7122 D AppUp4:CustFacade: isPhone : true
08-31 11:31:24.747  7122  7122 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:31:24.747  7122  7122 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 11:31:24.750  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:24.750  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:31:24.752  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 11:31:24.754  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:31:24.759  7156  7156 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 11:31:24.761  4340  7585 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:31:24.763  4340  7586 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:24.763  4340  7586 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 11:31:24.772  7156  7587 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:24.779  1030  1884 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-31 11:31:24.779  3475  3475 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-31 11:31:24.779  3475  3475 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:24.779  3475  3475 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 11:31:24.780  7039  7589 W FormManager: Network not available. Please check & try again.
08-31 11:31:24.782  7192  7192 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 11:31:24.782  7192  7192 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 11:31:24.784  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 11:31:24.787  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 11:31:24.788  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 11:31:24.788  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 11:31:24.788  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 11:31:24.788  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:31:24.788  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 11:31:24.788  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 11:31:24.788  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 11:31:24.788  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:31:24.788  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 11:31:24.788  7056  7056 I BluetoothA2dpServiceJni: classInitNative
08-31 11:31:24.788  7056  7056 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:31:24.788  7056  7056 D A2dpStateMachine: make
08-31 11:31:24.790  7056  7056 I bluedroid-qcom: get_profile_interface a2dp
08-31 11:31:24.790  7056  7593 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 11:31:24.790  7282  7282 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:31:24
,08-31 11:31:24.792  7282  7282 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 11:31:24.792  7282  7282 D Weather.Utils: 2 : All the weather widget is gone.
08-31 11:31:24.792  7056  7056 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:31:24.792  7056  7056 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 11:31:24.792  7282  7282 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 11:31:24.792  7282  7282 D WeatherAncestor: connectivity changed - connection : true
08-31 11:31:24.792  7282  7282 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@17426fbc
08-31 11:31:24.793  7282  7282 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 11:31:24.793  7282  7282 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 11:31:24.793  7282  7282 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 11:31:24.793  7282  7282 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 11:31:24.793  7039  7591 V FormManager: Network unavailable.
08-31 11:31:24.793  7282  7282 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:31:24
08-31 11:31:24.794  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
08-31 11:31:24.795  7056  7056 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 11:31:24.796  7056  7592 D A2dpStateMachine: Enter Disconnected: -2
08-31 11:31:24.798  7056  7056 D HidService: Received start request. Starting profile...
08-31 11:31:24.798  7056  7056 I bluedroid-qcom: get_profile_interface hidhost
08-31 11:31:24.798  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
08-31 11:31:24.798  7039  7591 V FormManager: Network unavailable.
08-31 11:31:24.799  7056  7056 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 11:31:24.802  7056  7056 D HealthService: Received start request. Starting profile...
,08-31 11:31:24.805  7056  7056 I bluedroid-qcom: get_profile_interface health
08-31 11:31:24.805  7056  7056 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 11:31:24.805  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
08-31 11:31:24.806  7056  7056 D HeadsetStateMachine: Proxy object connected
08-31 11:31:24.806  7056  7056 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 11:31:24.807  7056  7056 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-31 11:31:24.809  7056  7056 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 11:31:24.811  7056  7056 D PanService: Received start request. Starting profile...
08-31 11:31:24.811  7056  7056 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:31:24.811  7056  7056 I bluedroid-qcom: get_profile_interface pan
08-31 11:31:24.816  7056  7056 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-31 11:31:24.816  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
,08-31 11:31:24.817  7056  7056 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 11:31:24.823  7056  7056 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:31:24.823  7056  7056 D BtGatt.GattService: Received start request. Starting profile...
08-31 11:31:24.823  7056  7056 D BtGatt.GattService: start()
08-31 11:31:24.823  7056  7056 I bluedroid-qcom: get_profile_interface gatt
08-31 11:31:24.823  7056  7056 D BtGatt.AdvertiseManager: advertise manager created
08-31 11:31:24.828  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
,08-31 11:31:24.830  7056  7563 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 11:31:24.830  7056  7563 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 11:31:24.831  7056  7563 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 11:31:24.832  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:31:24.833  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
08-31 11:31:24.834  7056  7056 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 11:31:24.835  7056  7056 V BluetoothMapService: BluetoothMapBinder()
08-31 11:31:24.835  7056  7056 D BluetoothMapService: Received start request. Starting profile...
08-31 11:31:24.835  7056  7056 D BluetoothMapService: start()
08-31 11:31:24.837  7056  7056 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 11:31:24.837  7056  7056 D BluetoothMapEmailAppObserver: createReceiver()
08-31 11:31:24.838  7056  7056 D BluetoothMapEmailAppObserver: initObservers()
08-31 11:31:24.838  7056  7056 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 11:31:24.843  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
,08-31 11:31:24.846  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:31:24.848  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:31:24.851  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:31:24.851  7056  7056 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 11:31:24.853  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:31:24.856  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 11:31:24.856  7056  7056 V BluetoothMapService: Handler(): got msg=1
,08-31 11:31:24.857  7056  7531 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,08-31 11:31:24.857  7056  7531 I bluedroid-qcom: enable
08-31 11:31:24.858  7056  7600 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 11:31:24.859  7056  7600 I bt-btu  : btu_task pending for preload complete event
08-31 11:31:24.859  7056  7531 I bt_hci_bdroid: init
08-31 11:31:24.860  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:24.860  7056  7531 I bt_vendor: bt-vendor : init
08-31 11:31:24.860  7056  7531 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 11:31:24.860  7056  7531 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 11:31:24.860  7056  7531 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 11:31:24.860  7056  7531 D bt_userial_mct: userial_init
08-31 11:31:24.860  7056  7531 D bt_hci_bdroid: set_power 1
08-31 11:31:24.860  7056  7531 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 11:31:24.861  7056  7531 I bt_vendor: Starting hciattach daemon
08-31 11:31:24.861  7056  7531 I bt_vendor: try to set true
08-31 11:31:24.861  7056  7056 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:31:24.861  7056  7056 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-31 11:31:24.861  7056  7056 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:31:24.861  7056  7056 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:24.861  7056  7056 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 11:31:24.850  7603  7603 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:24.850  7603  7603 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:24.902  7604  7604 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 11:31:25.012  7610  7610 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 11:31:25.026  7611  7611 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 11:31:25.060  7613  7613 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 11:31:25.072  7617  7617 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-31 11:31:25.092  7618  7618 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 11:31:25.103  7619  7619 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-31 11:31:25.126  7621  7621 I libmdmdetect: ESOC framework not supported
,08-31 11:31:25.128  7621  7621 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-31 11:31:25.139  7621  7621 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-31 11:31:25.139  7621  7621 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-31 11:31:25.139  7621  7621 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-31 11:31:25.139  7621  7621 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 11:31:25.139  7621  7621 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 11:31:25.139  7621  7621 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 11:31:25.139  7621  7621 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-31 11:31:25.191  7621  7622 E QC-QMI  : qmi_client [7621] 14: failed to locate client data
,08-31 11:31:25.194   468   468 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-31 11:31:25.194   468   468 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-31 11:31:25.255  7626  7626 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 11:31:25.280  7627  7627 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 11:31:25.318  7056  7531 I bt_vendor: bluetooth satus is on
08-31 11:31:25.318  7056  7531 D bt_hci_bdroid: preload
,08-31 11:31:25.322  7056  7602 D bt_userial_mct: userial_open(port:0)
,08-31 11:31:25.322  7056  7602 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-31 11:31:25.326  7056  7602 I bt_vendor: Done intiailizing UART
08-31 11:31:25.327  7056  7602 I bt_vendor: Done intiailizing UART
08-31 11:31:25.327  7056  7602 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-31 11:31:25.328  7056  7602 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 11:31:25.328  7056  7629 D bt_userial_mct: Entering userial_read_thread()
08-31 11:31:25.329  7056  7600 I bt-btu  : btu_task received preload complete event
08-31 11:31:25.330  7056  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-31 11:31:25.330  7056  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-31 11:31:25.341  7056  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-31 11:31:25.349  7056  7600 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 11:31:25.349  7056  7600 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 11:31:25.349  7056  7600 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 11:31:25.349  7056  7600 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 11:31:25.349  7056  7600 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 11:31:25.349  7056  7600 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 11:31:25.349  7056  7600 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 11:31:25.349  7056  7600 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 11:31:25.349  7056  7600 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-31 11:31:25.349  7056  7600 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 11:31:25.350  7056  7600 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 11:31:25.350  7056  7600 I         : BTE_InitTraceLevels -- TRC_SDP
,08-31 11:31:25.350  7056  7600 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 11:31:25.350  7056  7600 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 11:31:25.350  7056  7600 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 11:31:25.350  7056  7600 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 11:31:25.410  7056  7600 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-31 11:31:25.410  7056  7600 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa017c061 
08-31 11:31:25.410  7056  7600 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa017c061 
,08-31 11:31:25.438  7056  7535 E bt-btif : Calling BTA_HhEnable
08-31 11:31:25.438  7056  7535 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-31 11:31:25.439  7056  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-31 11:31:25.439  7056  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-31 11:31:25.439  7056  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-31 11:31:25.439  7056  7535 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 11:31:25.439  7056  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 11:31:25.439  7056  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,08-31 11:31:25.443  7056  7535 D BluetoothAdapterProperties: Name is: G3
08-31 11:31:25.447  7056  7535 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:31:25.447  1030  1030 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 11:31:25.448  1030  1030 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 11:31:25.448  7056  7535 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:31:25.448  7056  7535 D bt_hci_bdroid: postload
08-31 11:31:25.449  7056  7602 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:31:25.449  7056  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-31 11:31:25.451  7056  7602 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:31:25.451  7056  7535 D bte_conf: Device ID record 1 : primary
08-31 11:31:25.451  7056  7535 D bte_conf:   vendorId            = 00c4
08-31 11:31:25.451  7056  7535 D bte_conf:   vendorIdSource      = 0001
08-31 11:31:25.451  7056  7535 D bte_conf:   product             = 13a1
08-31 11:31:25.451  7056  7535 D bte_conf:   version             = 1000
08-31 11:31:25.451  7056  7535 D bte_conf:   clientExecutableURL = 
08-31 11:31:25.451  7056  7535 D bte_conf:   serviceDescription  = 
08-31 11:31:25.451  7056  7535 D bte_conf:   documentationURL    = 
08-31 11:31:25.451  7056  7535 D bte_conf: bte_load_did_conf no section named DID2.
08-31 11:31:25.454  7056  7602 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:31:25.457  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:31:25.458  7056  7531 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 11:31:25.459  7056  7531 D BluetoothAdapterProperties: ScanMode =  20
08-31 11:31:25.459  7056  7531 D BluetoothAdapterProperties: State =  11
08-31 11:31:25.459  7056  7531 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 11:31:25.460  7056  7531 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 11:31:25.460  7056  7531 D BluetoothAdapterProperties: Setting state to 12
08-31 11:31:25.460  7056  7531 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 11:31:25.461  1030  1094 D BluetoothManagerService: Message: 60
08-31 11:31:25.461  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 11:31:25.461  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-31 11:31:25.450  7631  7631 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:25.450  7631  7631 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:25.464  7056  7531 I BluetoothAdapterState: Entering On State
08-31 11:31:25.468  7056  7600 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:31:25.468  7056  7600 W bt-smp  : Plain text(LSB ~ MSB) = 03 ef 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:31:25.468  7056  7600 W bt-smp  : Encrypted text(LSB ~ MSB) = 5f a2 09 6d aa 44 1e 55 93 59 fd e2 94 23 36 90 
08-31 11:31:25.468  7056  7600 W bt-btm  : Stopping oneshot timer
08-31 11:31:25.468  7056  7602 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:31:25.468  7056  7535 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 11:31:25.469  7056  7535 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 11:31:25.472  7056  7629 E bt_mct  : hci lib postload completed
08-31 11:31:25.485  7056  7535 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:31:25.485  7056  7535 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-31 11:31:25.489  1848  2573 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:31:25.489  7056  7531 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 11:31:25.490  7056  7531 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 11:31:25.490  7056  7531 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-31 11:31:25.490  7056  7531 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 11:31:25.491  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:25.491  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:25.491  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:25.491  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:31:25.491  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:25.491  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:25.491  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:25.491  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:31:25.492  7056  7600 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:31:25.492  7056  7600 W bt-smp  : Plain text(LSB ~ MSB) = 47 d6 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:31:25.492  7056  7600 W bt-smp  : Encrypted text(LSB ~ MSB) = 80 27 23 23 f2 05 f6 a2 d8 a8 8a 02 7f 3b 4e a5 
08-31 11:31:25.492  7056  7600 W bt-btm  : Stopping oneshot timer
08-31 11:31:25.497  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:31:25.500  1848  1848 D BluetoothHeadset: Proxy object connected
,08-31 11:31:25.502  1848  4022 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:31:25.505  1848  1848 D BluetoothHeadset: Proxy object connected
08-31 11:31:25.510  6950  7036 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 11:31:25.510  7056  7600 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:31:25.510  7056  7600 W bt-smp  : Plain text(LSB ~ MSB) = 97 f2 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:31:25.510  7056  7600 W bt-smp  : Encrypted text(LSB ~ MSB) = d3 53 50 3d 6b 4c 75 3d 33 ab 88 90 56 82 d9 cc 
08-31 11:31:25.510  7056  7600 W bt-btm  : Stopping oneshot timer
08-31 11:31:25.512  7056  7531 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-31 11:31:25.516  6950  6965 D BluetoothPan: onBluetoothStateChange on: true
08-31 11:31:25.516  6950  6965 D BluetoothPan: onBluetoothStateChange call bindService
08-31 11:31:25.524  6950  6950 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:31:25.524  6950  6950 D PanProfile: Bluetooth service connected
,08-31 11:31:25.526  7056  7600 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:31:25.526  7056  7600 W bt-smp  : Plain text(LSB ~ MSB) = bb 94 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-31 11:31:25.526  7056  7600 W bt-smp  : Encrypted text(LSB ~ MSB) = 1f b7 5f 64 34 c5 6e 3c 1f 87 1d 4d e3 73 8b 62 
08-31 11:31:25.526  7056  7600 W bt-btm  : Stopping oneshot timer
,08-31 11:31:25.527  1030  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:31:25.529  1030  1030 D BluetoothHeadset: Proxy object connected
08-31 11:31:25.533  1848  1863 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:31:25.537  1848  1848 D BluetoothHeadset: Proxy object connected
08-31 11:31:25.538  1030  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:31:25.540  7056  7600 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:31:25.540  7056  7600 W bt-smp  : Plain text(LSB ~ MSB) = e0 3d 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:31:25.540  7056  7600 W bt-smp  : Encrypted text(LSB ~ MSB) = 60 45 b8 54 35 37 d3 06 e9 6c dc 67 58 04 52 d7 
08-31 11:31:25.540  7056  7600 W bt-btm  : Stopping oneshot timer
,08-31 11:31:25.543  1030  1030 D BluetoothA2dp: Proxy object connected
08-31 11:31:25.548  6950  7036 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 11:31:25.552  6950  6950 D BluetoothInputDevice: Proxy object connected
08-31 11:31:25.552  6950  6950 D HidProfile: Bluetooth service connected
08-31 11:31:25.552  6950  6965 D BluetoothMap: onBluetoothStateChange: up=true
08-31 11:31:25.553  7646  7646 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-31 11:31:25.557  6950  6950 D BluetoothMap: Proxy object connected
08-31 11:31:25.557  6950  6950 D MapProfile: Bluetooth service connected
08-31 11:31:25.557  6950  6950 D BluetoothMap: getConnectedDevices()
08-31 11:31:25.557  7056  7075 V BluetoothMapService: getConnectedDevices()
08-31 11:31:25.558  1030  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 11:31:25.559  1030  1030 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-31 11:31:25.559  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 11:31:25.561  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:31:25.563  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:25.564  1939  2123 D LGBluetoothAPIService: Message: 1
08-31 11:31:25.564  1939  2123 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 11:31:25.564  1030  1094 D BluetoothManagerService: Message: 40
08-31 11:31:25.565  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-31 11:31:25.568  7056  7056 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:25.568  6821  6821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 11:31:25.568  7056  7056 D BluetoothMapService: STATE_ON
08-31 11:31:25.569  1939  2123 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-31 11:31:25.572  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:25.572  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:25.572  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:25.572  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:31:25.572  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:25.572  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:25.572  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:25.572  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:31:25.576  6950  6950 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 11:31:25.577  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:31:25.579  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:31:25.580  1030  1094 D BluetoothManagerService: Message: 30
08-31 11:31:25.584  6950  6950 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 11:31:25.585  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
08-31 11:31:25.585  7056  7056 V BluetoothPbapService: Pbap Service onCreate
08-31 11:31:25.585  7056  7056 V BluetoothPbapService: Starting PBAP service
08-31 11:31:25.587  7056  7056 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 11:31:25.587  7056  7056 V BluetoothMapService: Handler(): got msg=1
08-31 11:31:25.588  7056  7056 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 11:31:25.588  1030  1094 D BluetoothManagerService: Message: 30
08-31 11:31:25.588  7056  7056 V BluetoothPbapService: Pbap Service onBind
08-31 11:31:25.589  7056  7056 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:25.590  7056  7056 V BluetoothPbapService: state: 12
08-31 11:31:25.590  7056  7650 D BluetoothMapMasInstance: MAS initSocket()
08-31 11:31:25.590  7056  7650 D BluetoothMapMasInstance:   masId = 00
08-31 11:31:25.590  7056  7650 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 11:31:25.590  7056  7650 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 11:31:25.590  7056  7650 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 11:31:25.591  7056  7056 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-31 11:31:25.591  1030  1989 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:25.591  7056  7056 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 11:31:25.596  7056  7056 V BluetoothPbapService: Handler(): got msg=1
08-31 11:31:25.597  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-31 11:31:25.597  1939  2123 D LGBluetoothAPIService: Message: 100
08-31 11:31:25.597  1939  2123 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 11:31:25.597  7056  7056 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 11:31:25.597  7056  7650 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:31:25.598  6950  6950 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 11:31:25.599  7056  7650 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 11:31:25.599  7056  7650 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 11:31:25.599  7056  7650 D BluetoothMapMasInstance: Accepting socket connection...
08-31 11:31:25.600  7056  7651 V BluetoothPbapService: Pbap Service initSocket
08-31 11:31:25.600  7056  7535 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:31:25.601  7056  7535 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-31 11:31:25.601  6950  6950 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 11:31:25.601  1030  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:25.601  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:25.602  7056  7651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:31:25.603  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:31:25.607  6950  6950 D BluetoothA2dp: Proxy object connected
08-31 11:31:25.608  6950  6950 D A2dpProfile: Bluetooth service connected
08-31 11:31:25.609  7056  7056 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:31:25.609  7056  7651 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 11:31:25.609  7056  7056 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:25.609  7056  7056 V BluetoothPbapReceiver: ***********state = 12
08-31 11:31:25.609  7056  7651 V BluetoothPbapService: Succeed to create listening socket 
08-31 11:31:25.609  7056  7651 V BluetoothPbapService: Accepting socket connection...
08-31 11:31:25.610  6950  6950 D BluetoothPbap: Proxy object connected
08-31 11:31:25.610  6950  6950 D PbapServerProfile: Bluetooth service connected
08-31 11:31:25.610  6950  6950 D BluetoothHeadset: Proxy object connected
08-31 11:31:25.612  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:31:25.612  6950  6950 D HeadsetProfile: Bluetooth service connected
08-31 11:31:25.612  2194  2194 D c       : Getting all permits...
08-31 11:31:25.612  2194  2194 D a       : Opening database...
08-31 11:31:25.616  2194  2194 D a       : Opening database auth.proximity.permit_store...
08-31 11:31:25.617  6950  6950 D DockEventReceiver: finishStartingService: stopping service
08-31 11:31:25.617  2194  2194 D a       : Closing database...
,08-31 11:31:25.631  6950  6950 D BluetoothPermissionRequest: onReceive
,08-31 11:31:25.633  6950  6950 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-31 11:31:25.635  6950  6950 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:31:25.639  7056  7056 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-31 11:31:25.640  7056  7056 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-31 11:31:25.647  7056  7056 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-31 11:31:25.674  7056  7056 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-31 11:31:25.675  7056  7056 V BtOppService: onCreate
08-31 11:31:25.681  7056  7056 V BluetoothOppNotification: send message
08-31 11:31:25.686  7056  7056 V BtOppService: Starting RfcommListener
08-31 11:31:25.694  7056  7056 D BluetoothOppPreference: Dumping Names:  
08-31 11:31:25.694  7056  7056 D BluetoothOppPreference: {}
08-31 11:31:25.694  7056  7056 D BluetoothOppPreference: Dumping Channels:  
,08-31 11:31:25.694  7056  7056 D BluetoothOppPreference: {}
,08-31 11:31:25.696  7056  7056 V BtOppService: onStartCommand
08-31 11:31:25.705  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:25.705  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 11:31:25.705  7056  7656 V BtOppService: Deleted complete outbound shares, number =  0
08-31 11:31:25.708  7056  7656 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 11:31:25.708  7056  7659 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 11:31:25.709  7056  7656 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-31 11:31:25.712  7056  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fc19d11 on behalf of 
,08-31 11:31:25.712  7056  7659 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 11:31:25.714  7056  7056 V BluetoothOppNotification: new notify threadi!
08-31 11:31:25.716  7056  7056 V BluetoothOppNotification: send delay message
08-31 11:31:25.716  7056  7659 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f713e76 on behalf of 
08-31 11:31:25.717  7056  7660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-31 11:31:25.717  7056  7056 V BtOppService: start RfcommListener
08-31 11:31:25.719  7056  7660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3983bc77 on behalf of 
08-31 11:31:25.720  7056  7660 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 11:31:25.721  7056  7659 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 11:31:25.721  7056  7660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 11:31:25.723  7056  7056 V BtOppService: RfcommListener started
08-31 11:31:25.724  7056  7056 V BtOppService: ContentObserver received notification
08-31 11:31:25.725  7056  7056 V BtOppService: ContentObserver received notification
08-31 11:31:25.727  7056  7662 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 11:31:25.727  7056  7662 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 11:31:25.731  7056  7661 V BtOppRfcommListener: Starting RFCOMM listener....
08-31 11:31:25.732  1030  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:25.734  7056  7661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:31:25.735  7056  7661 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-31 11:31:25.736  7056  7661 V BtOppRfcommListener: Started RFCOMM listener....
08-31 11:31:25.736  7056  7661 I BtOppRfcommListener: Accept thread started.
08-31 11:31:25.736  7056  7661 V BtOppRfcommListener: Accepting connection...
,08-31 11:31:25.742  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
08-31 11:31:25.742  7056  7056 V BluetoothFtpService: Ftp Service onCreate
08-31 11:31:25.742  7056  7056 I BluetoothFtpService: Ftp Service onCreate
08-31 11:31:25.743  7056  7056 V BluetoothFtpService: Ftp Service onStartCommand
08-31 11:31:25.743  7056  7056 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:25.743  7056  7056 V BluetoothFtpService: Starting Listening on sockets
08-31 11:31:25.743  7056  7056 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:31:25.743  7056  7056 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:31:25.743  7056  7056 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:31:25.744  7056  7056 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:25.744  7056  7056 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 11:31:25.744  7056  7056 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 11:31:25.878  1030  2021 I art     : Explicit concurrent mark sweep GC freed 94784(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 3.356ms total 154.616ms
08-31 11:31:25.879  7056  7662 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b91f94d on behalf of 
08-31 11:31:25.880  7056  7056 V BluetoothFtpService: Handler(): got msg=1
08-31 11:31:25.882  7056  7056 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 11:31:25.882  7056  7056 V BluetoothFtpService: Ftp Service initSocket
,08-31 11:31:25.882  7056  7662 V BluetoothOppNotification: update too frequent, put in queue
08-31 11:31:25.885  1030  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:25.886  7056  7662 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 11:31:25.887  7056  7056 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:31:25.888  7056  7056 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-31 11:31:25.888  7056  7056 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 11:31:25.890  7056  7663 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-31 11:31:25.891  7056  7660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15aacc02 on behalf of 
08-31 11:31:25.894  7056  7660 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-31 11:31:25.900  7056  7660 V BluetoothOppNotification: outbound notification was removed.
08-31 11:31:25.901  7056  7660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 11:31:25.905  7056  7660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f6da913 on behalf of 
08-31 11:31:25.906  7056  7660 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 11:31:25.907  7341  7362 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-31 11:31:25.908  7056  7660 V BluetoothOppNotification: inbound notification was removed.
08-31 11:31:25.908  7056  7660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 11:31:25.910  7056  7660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12e6f750 on behalf of 
08-31 11:31:25.917  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
08-31 11:31:25.917  7056  7056 V BluetoothSapService: Sap Service onCreate
08-31 11:31:25.919  7056  7056 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:25.919  7056  7056 V BluetoothSapService: state: 12
08-31 11:31:25.919  7056  7056 V BluetoothSapService: Starting SAP server process
08-31 11:31:25.921  7056  7056 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-31 11:31:25.922  7056  7667 V BluetoothSapService: Sap Service initRfcommSocket
08-31 11:31:25.923  1030  2021 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:25.924  7056  7667 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:31:25.910  7666  7666 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:25.910  7666  7666 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:25.925  7056  7667 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-31 11:31:25.925  7056  7667 V BluetoothSapService: Succeed to create listening socket 
08-31 11:31:25.925  7056  7667 V BluetoothSapService: Accepting socket connection...
08-31 11:31:25.932  7666  7666 V BT_SAP  : Event pipe created
08-31 11:31:25.932  7666  7666 V BT_SAP  : create_server_socket qcom.sap.server
08-31 11:31:25.932  7666  7666 V BT_SAP  : created socket fd 6
,08-31 11:31:26.332  1030  1388 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:31:26.332  1030  1388 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:31:26.389  1030  1389 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-31 11:31:26.390  1030  1389 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-31 11:31:26.600  1030  2009 I ActivityManager: Killing 7467:com.lge.bnr/1000 (adj 15): empty #17
,08-31 11:31:26.658  1030  2048 W libprocessgroup: failed to open /acct/uid_1000/pid_7467/cgroup.procs: No such file or directory
,08-31 11:31:26.718  7056  7056 V BluetoothOppNotification: new notify threadi!
,08-31 11:31:26.719  7056  7056 V BluetoothOppNotification: send delay message
,08-31 11:31:26.730  7056  7677 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 11:31:26.732  7056  7677 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@184c387c on behalf of 
08-31 11:31:26.732  7056  7677 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 11:31:26.735  7056  7677 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-31 11:31:26.738  7056  7677 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d920505 on behalf of 
08-31 11:31:26.739  7056  7677 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 11:31:26.741  7056  7677 V BluetoothOppNotification: outbound notification was removed.
08-31 11:31:26.741  7056  7677 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 11:31:26.742  7056  7677 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b91d95a on behalf of 
08-31 11:31:26.743  7056  7677 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 11:31:26.746  7056  7677 V BluetoothOppNotification: inbound notification was removed.
08-31 11:31:26.747  7056  7677 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 11:31:26.748  7056  7677 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22ef278b on behalf of 
,08-31 11:31:26.904  1030  2009 I ActivityManager: Killing 6970:com.lge.sync/1000 (adj 15): empty #17
,08-31 11:31:26.929  1030  1443 D WifiService: Client connection lost with reason: 4
,08-31 11:31:26.938  1030  2048 W libprocessgroup: failed to open /acct/uid_1000/pid_6970/cgroup.procs: No such file or directory
,08-31 11:31:27.340  1030  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:31:27.340  1030  1046 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@21a66419 mBinding = false
,08-31 11:31:27.379  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:31:27.379  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:31:27.379  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-31 11:31:27.380  1030  1094 D BluetoothManagerService: Message: 2
08-31 11:31:27.381  1030  1094 D BluetoothManagerService: Sending off request.
08-31 11:31:27.381  7056  7644 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-31 11:31:27.382  7056  7531 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-31 11:31:27.382  7056  7531 D BluetoothAdapterProperties: Setting state to 13
08-31 11:31:27.382  7056  7531 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 11:31:27.383  7056  7531 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 11:31:27.383  7056  7531 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 11:31:27.385  7056  7535 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:31:27.387  7056  7531 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-31 11:31:27.392  7056  7531 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 11:31:27.394  7056  7651 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:31:27.395  7056  7661 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:31:27.395  7056  7663 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:31:27.395  7056  7667 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:31:27.396  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 11:31:27.396  7056  7600 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-31 11:31:27.398  7056  7650 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 11:31:27.398  7056  7650 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:31:27.398  7056  7650 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 11:31:27.398  7056  7650 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 11:31:27.398  7056  7650 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 11:31:27.398  7056  7650 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 11:31:27.398  7056  7650 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 11:31:27.398  7056  7650 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-31 11:31:27.404  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:31:27.404  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:31:27.404  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:31:27.404  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:31:27.404  7056  7600 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:31:27.404  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:31:27.404  7056  7600 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:31:27.404  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:31:27.404  7056  7600 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:31:27.405  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
,08-31 11:31:27.405  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 11:31:27.409  7056  7600 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 11:31:27.413  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:27.413  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:27.413  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:27.413  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:27.413  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:31:27.413  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:31:27.413  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:27.413  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:27.413  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:31:27.414  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:27.414  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:31:27.421  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:27.421  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:27.421  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:27.421  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:27.421  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:31:27.421  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:31:27.421  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:27.421  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:27.421  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:31:27.425  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:31:27.425  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:31:27.426  1030  1094 D BluetoothManagerService: Message: 60
08-31 11:31:27.426  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 11:31:27.426  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-31 11:31:27.430  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:27.431  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:31:27.435  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:31:27.439  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:27.441  7056  7056 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:27.441  7056  7056 D BluetoothMapService: STATE_TURNING_OFF
08-31 11:31:27.441  7056  7056 V BluetoothMapService: Handler(): got msg=4
08-31 11:31:27.441  7056  7056 D BluetoothMapService: MAP Service closeService in
08-31 11:31:27.441  7056  7056 D BluetoothMapMasInstance: MAP Service shutdown
08-31 11:31:27.441  7056  7056 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:31:27.441  7056  7056 V BluetoothMapService: MAP Service closeService out
08-31 11:31:27.442  7056  7056 V BtOppService: Receiver DISABLED_ACTION 
08-31 11:31:27.443  7056  7056 I BtOppRfcommListener: stopping Accept Thread
08-31 11:31:27.443  7056  7056 V BtOppRfcommListener: close mBtServerSocket
08-31 11:31:27.443  7056  7661 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 11:31:27.444  7056  7056 V BtOppRfcommListener: waiting for thread to terminate
08-31 11:31:27.444  7056  7056 V BtOppRfcommListener: done waiting for thread to terminate
08-31 11:31:27.447  6950  6950 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-31 11:31:27.460  6950  6950 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-31 11:31:27.463  7056  7056 V BtOppService: onDestroy
08-31 11:31:27.465  7056  7056 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-31 11:31:27.470  7056  7056 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:31:27.470  7056  7056 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:27.470  7056  7056 V BluetoothPbapReceiver: ***********state = 13
08-31 11:31:27.471  7056  7056 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-31 11:31:27.475  7056  7056 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:27.475  7056  7056 V BluetoothPbapService: state: 13
08-31 11:31:27.475  7056  7056 V BluetoothPbapService: Pbap Service closeService in
,08-31 11:31:27.479  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:31:27.481  7056  7056 V BluetoothPbapService: successfully stopped pbap service
08-31 11:31:27.481  7056  7056 V BluetoothPbapService: Pbap Service closeService out
08-31 11:31:27.482  7056  7056 V BluetoothPbapService: Pbap Service onDestroy
08-31 11:31:27.482  7056  7056 V BluetoothPbapService: Pbap Service closeService in
08-31 11:31:27.482  7056  7056 V BluetoothPbapService: Pbap Service closeService out
08-31 11:31:27.482  7056  7056 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-31 11:31:27.504  6950  6950 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:31:27.509  6950  6950 D BluetoothPbap: Proxy object disconnected
08-31 11:31:27.509  6950  6950 D PbapServerProfile: Bluetooth service disconnected
08-31 11:31:27.514  6950  6950 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-31 11:31:27.522  6950  6950 D BluetoothPermissionRequest: onReceive
08-31 11:31:27.522  6950  6950 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 11:31:27.528  6950  6950 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:31:27.531  7056  7056 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-31 11:31:27.531  7056  7056 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-31 11:31:27.532  7056  7056 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-31 11:31:27.537  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:27.537  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 11:31:27.538  7056  7056 V BluetoothFtpService: Ftp Service onStartCommand
08-31 11:31:27.539  7056  7056 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:27.539  7056  7056 V BluetoothFtpService: Ftp Service closeService
08-31 11:31:27.539  7056  7056 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-31 11:31:27.541  7056  7056 V BluetoothFtpService: successfully stopped ftp service
08-31 11:31:27.541  7056  7056 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:31:27.541  7056  7056 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:31:27.541  7056  7056 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:31:27.541  7056  7056 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:27.541  7056  7056 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-31 11:31:27.542  7056  7056 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 11:31:27.542  7056  7056 V BluetoothFtpService: Ftp Service onDestroy
08-31 11:31:27.542  7056  7056 V BluetoothFtpService: Ftp Service closeService
08-31 11:31:27.547  7056  7056 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:27.547  7056  7056 V BluetoothSapService: state: 13
,08-31 11:31:27.547  7056  7056 V BluetoothSapService: Stopping SAP server process
,08-31 11:31:27.552  7056  7056 V BluetoothSapService: Sap Service closeSapService in
08-31 11:31:27.552  7056  7056 V BluetoothSapService: Close listen Socket : 
08-31 11:31:27.552  7056  7056 V BluetoothSapService: Close rfcomm Socket : 
08-31 11:31:27.552  7056  7056 V BluetoothSapService: Close sapd  Socket : 
08-31 11:31:27.553  7056  7056 V BluetoothSapService: Sap Service closeSapService out
08-31 11:31:27.554  7056  7056 V BluetoothSapService: Sap Service onDestroy
08-31 11:31:27.554  7056  7056 V BluetoothSapService: Sap Service closeSapService in
08-31 11:31:27.554  7056  7056 V BluetoothSapService: Close listen Socket : 
,08-31 11:31:27.554  7056  7056 V BluetoothSapService: Close rfcomm Socket : ,
08-31 11:31:27.554  7056  7056 V BluetoothSapService: Close sapd  Socket : 
,08-31 11:31:27.555  7056  7056 V BluetoothSapService: Sap Service closeSapService out
,08-31 11:31:28.362  7056  7535 D bt_hci_bdroid: cleanup
,08-31 11:31:28.377  7056  7602 I bt_lpm  : LPM is already off!!!
08-31 11:31:28.378  7056  7629 I bt_userial_mct: exiting userial_read_thread
08-31 11:31:28.378  7056  7629 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 11:31:28.381  7056  7600 W bt-btif : ag scb idx 1 not allocated
08-31 11:31:28.381  7056  7600 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 11:31:28.381  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:31:28.381  7056  7600 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:31:28.381  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:31:28.381  7056  7600 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:31:28.381  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:31:28.382  7056  7600 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:31:28.382  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:31:28.382  7056  7600 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:31:28.382  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:31:28.382  7056  7600 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:31:28.382  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:31:28.382  7056  7600 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:31:28.382  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:31:28.382  7056  7600 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:31:28.382  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:31:28.382  7056  7600 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:31:28.382  7056  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:31:28.382  7056  7600 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:31:28.382  7056  7600 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 11:31:28.385  7056  7535 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-31 11:31:28.390  7056  7602 I bt_vendor: hw_epilog_process
08-31 11:31:28.390  7056  7535 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 11:31:28.390  7056  7535 D bt_userial_mct: userial_close
08-31 11:31:28.390  7056  7535 E bt_userial_mct: pthread_join() FAILED result:3
,08-31 11:31:28.390  7056  7535 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-31 11:31:28.397  7056  7535 D bt_hci_bdroid: set_power 0
08-31 11:31:28.397  7056  7535 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 11:31:28.397  7056  7535 I bt_vendor: bluetooth satus is on
08-31 11:31:28.397  7056  7535 I bt_vendor: bt-vendor : resetting BT status
08-31 11:31:28.397  7056  7535 I bt_vendor: Starting hciattach daemon
08-31 11:31:28.397  7056  7535 I bt_vendor: try to set false
08-31 11:31:28.401  7056  7535 I bt_vendor: Starting hciattach daemon
08-31 11:31:28.401  7056  7535 I bt_vendor: try to set false
,08-31 11:31:28.405  7056  7535 I bt_vendor: cleanup
08-31 11:31:28.405  7056  7600 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 11:31:28.406  7056  7535 I GKI_LINUX: GKI_exit_task 0 done
08-31 11:31:28.406  7056  7535 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-31 11:31:28.408  7056  7531 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 11:31:28.412  7056  7056 D HeadsetService: Received stop request...Stopping profile...
08-31 11:31:28.414  7056  7056 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 11:31:28.415  7056  7056 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:31:28.415  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
,08-31 11:31:28.418  7056  7563 D HeadsetStateMachine: Exit Disconnected: -1
08-31 11:31:28.421  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-31 11:31:28.421  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-31 11:31:28.421  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-31 11:31:28.423  1030  1030 D BluetoothHeadset: Proxy object disconnected
08-31 11:31:28.423  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 11:31:28.424  7056  7056 D A2dpService: Received stop request...Stopping profile...
08-31 11:31:28.425  7056  7592 D A2dpStateMachine: Exit Disconnected: -1
08-31 11:31:28.428  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-31 11:31:28.431  7056  7531 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 11:31:28.432  7056  7056 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 11:31:28.432  7056  7056 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:31:28.433  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
08-31 11:31:28.434  1030  1030 D BluetoothA2dp: Proxy object disconnected
08-31 11:31:28.434  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-31 11:31:28.435  7056  7056 D HidService: Received stop request...Stopping profile...
08-31 11:31:28.435  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
08-31 11:31:28.437  7056  7056 D HeadsetStateMachine: Unbinding service...
08-31 11:31:28.439  7056  7056 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:31:28.439  7056  7056 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:31:28.439  7056  7056 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:31:28.439  7056  7056 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:31:28.439  7056  7056 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 11:31:28.439  7056  7056 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:31:28.439  7056  7056 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 11:31:28.440  7056  7056 D HealthService: Received stop request...Stopping profile...
08-31 11:31:28.440  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
,08-31 11:31:28.445  7056  7056 D PanService: Received stop request...Stopping profile...
08-31 11:31:28.446  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
08-31 11:31:28.448  7056  7056 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:31:28.448  7056  7056 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 11:31:28.448  7056  7056 D BtGatt.GattService: stop()
08-31 11:31:28.448  7056  7056 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 11:31:28.450  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
08-31 11:31:28.452  7056  7056 D BluetoothMapService: Received stop request...Stopping profile...
08-31 11:31:28.452  7056  7056 D BluetoothMapService: stop()
,08-31 11:31:28.455  7056  7056 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 11:31:28.455  7056  7056 D BluetoothMapEmailAppObserver: removeReceiver()
08-31 11:31:28.455  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17426fbc
08-31 11:31:28.456  7056  7056 V BluetoothMapService: Handler(): got msg=4
08-31 11:31:28.457  7056  7056 D BluetoothMapService: MAP Service closeService in
08-31 11:31:28.457  7056  7056 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:31:28.457  7056  7056 V BluetoothMapService: MAP Service closeService out
08-31 11:31:28.457  7056  7531 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 11:31:28.457  7056  7531 D BluetoothAdapterProperties: Setting state to 10
08-31 11:31:28.457  7056  7531 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 11:31:28.458  1030  1094 D BluetoothManagerService: Message: 60
08-31 11:31:28.458  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 11:31:28.459  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-31 11:31:28.461  7056  7531 I BluetoothAdapterState: Entering OffState
08-31 11:31:28.462  6950  6966 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:31:28.463  1848  2573 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 11:31:28.466  1848  1864 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:31:28.468  7056  7056 I BluetoothA2dpServiceJni: cleanupNative
08-31 11:31:28.468  7056  7593 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 11:31:28.469  7056  7056 I GKI_LINUX: GKI_exit_task 2 done
08-31 11:31:28.469  7056  7056 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 11:31:28.470  6950  6966 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 11:31:28.470  6950  6966 D BluetoothPan: onBluetoothStateChange on: false
08-31 11:31:28.471  7056  7056 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:31:28.472  7056  7056 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 11:31:28.472  7056  7056 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:31:28.473  7056  7056 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:31:28.473  7056  7056 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:31:28.474  1030  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:31:28.475  1848  4020 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 11:31:28.477  1030  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:31:28.477  6950  6966 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 11:31:28.478  7056  7056 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:31:28.478  7056  7056 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 11:31:28.480  6950  6966 D BluetoothMap: onBluetoothStateChange: up=false
08-31 11:31:28.481  7056  7056 D BluetoothMapService: cleanup()
08-31 11:31:28.481  7056  7056 D BluetoothMapService: MAP Service closeService in
08-31 11:31:28.481  7056  7056 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:31:28.481  7056  7056 V BluetoothMapService: MAP Service closeService out
08-31 11:31:28.482  6950  6966 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:31:28.483  1030  1094 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 11:31:28.483  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-31 11:31:28.485  1030  1094 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-31 11:31:28.485  1030  1094 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 11:31:28.485  1030  1094 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@21a66419 mBinding = false
08-31 11:31:28.487  1030  1094 D BluetoothManagerService: Sending unbind request.
,08-31 11:31:28.494  7056  7535 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-31 11:31:28.494  7056  7056 I GKI_LINUX: GKI_exit_task 1 done
08-31 11:31:28.494  7056  7056 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 11:31:28.495  7056  7056 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 11:31:28.495  7056  7056 I art     : --- WEIRD: removing null entry 248
08-31 11:31:28.495  7056  7056 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-31 11:31:28.495  7056  7056 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 11:31:28.496  7056  7056 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-31 11:31:28.497  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-31 11:31:28.501  7056  7056 I art     : System.exit called, status: 0
08-31 11:31:28.501  7056  7056 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 11:31:28.530   311  1397 V AudioFlinger: 7056 died, releasing its sessions
08-31 11:31:28.530   311  1397 V AudioFlinger:  pid 1848 @ 0
08-31 11:31:28.530   311  1397 V AudioFlinger:  pid 3475 @ 1
08-31 11:31:28.530   311  1397 V AudioFlinger:  pid 3475 @ 2
,08-31 11:31:28.534  6950  6950 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-31 11:31:28.534  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-31 11:31:28.534  1939  2123 D LGBluetoothAPIService: Message: 101
08-31 11:31:28.535  1939  2123 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-31 11:31:28.535  1939  2123 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-31 11:31:28.535  1939  2123 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-31 11:31:28.637  1030  1574 I ActivityManager: Process com.android.bluetooth (pid 7056) has died
08-31 11:31:28.638  1030  1574 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-31 11:31:28.638  1030  1574 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-31 11:31:28.645  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:28.646  1939  2123 D LGBluetoothAPIService: Message: 2
08-31 11:31:28.646  1939  2123 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-31 11:31:28.647  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:31:28.651  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:28.652  6950  6950 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-31 11:31:28.652  6950  6950 D LGBluetoothEventManager: [BTUI] clear device connection state
08-31 11:31:28.653  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:31:28.660  6950  6950 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-31 11:31:28.661  1600  1600 D BluetoothAdapter: 846515239: getState() :  mService = null. Returning STATE_OFF
08-31 11:31:28.661  1600  1600 D BluetoothAdapter: 846515239: getState() :  mService = null. Returning STATE_OFF
08-31 11:31:28.733  1030  2048 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7726 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-31 11:31:28.735  6950  6950 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:31:28.818  7726  7726 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 11:31:28.818  7726  7726 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:31:28.819  7726  7726 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 11:31:28.819  7726  7726 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 11:31:28.841  7726  7726 D BluetoothAdapterApp: Loading JNI Library
,08-31 11:31:28.879  7726  7726 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1f094024 Instance Count = 1
,08-31 11:31:28.885  7726  7726 D BluetoothAdapterApp: onCreate
,08-31 11:31:28.913  7726  7726 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-31 11:31:28.914  7726  7726 D ProfileConfigQcom: Adding HeadsetService
08-31 11:31:28.914  7726  7726 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 11:31:28.915  7726  7726 D ProfileConfigQcom: Adding A2dpService
08-31 11:31:28.915  7726  7726 D ProfileConfigQcom: [BTUI] HidService is supported
08-31 11:31:28.917  7726  7726 D ProfileConfigQcom: Adding HidService
,08-31 11:31:28.918  7726  7726 D ProfileConfigQcom: [BTUI] HealthService is supported
08-31 11:31:28.918  7726  7726 D ProfileConfigQcom: Adding HealthService
08-31 11:31:28.919  7726  7726 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-31 11:31:28.921  7726  7726 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 11:31:28.921  7726  7726 D ProfileConfigQcom: Adding PanService
08-31 11:31:28.922  7726  7726 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 11:31:28.923  7726  7726 D ProfileConfigQcom: Adding GattService
08-31 11:31:28.927  7726  7726 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-31 11:31:28.927  7726  7726 D ProfileConfigQcom: Adding BluetoothMapService
08-31 11:31:28.929  7726  7726 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 11:31:28.931  7726  7726 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:31:28.934  7726  7726 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:28.934  7726  7726 V BluetoothPbapReceiver: ***********state = 10
08-31 11:31:28.939  7726  7726 V LGMDMManagerInternal: Create singleton instance
08-31 11:31:29.057  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:31:29.065  6950  6950 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 11:31:29.067  7726  7726 D LGBluetoothAPIServer: [BTUI] onCreate()
08-31 11:31:29.067  7726  7726 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 11:31:29.074  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-31 11:31:29.075  1939  2123 D LGBluetoothAPIService: Message: 100
,08-31 11:31:29.076  1939  2123 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 11:31:29.084  6950  6950 D BluetoothPermissionRequest: onReceive
08-31 11:31:29.087  6950  6950 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 11:31:29.087  6950  6950 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-31 11:31:29.092  6950  6950 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:31:29.100  7726  7726 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-31 11:31:29.105  7726  7726 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:31:29.110  7726  7726 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:31:29.110  7726  7726 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:31:29.111  7726  7726 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:31:29.113  7726  7726 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:29.113  7726  7726 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-31 11:31:29.118  7015  7015 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-31 11:31:30.459  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:31:30.459  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:31:30.587  1600  1600 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-31 11:31:30.616  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-31 11:31:30.657  1030  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 11:31:30.690  1030  1089 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7753 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-31 11:31:30.696  1600  1600 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-31 11:31:30.697  1600  1600 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-31 11:31:30.746  1030  1030 D administrator: Handling package changes for user 0
,08-31 11:31:30.752  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:31:30.781  7753  7753 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 11:31:30.878  1030  1030 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-31 11:31:30.878  1030  1030 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-31 11:31:30.882  7753  7753 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:31:30.882  7753  7753 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:31:30.914  1030  1088 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:31:30.920  1030  1088 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-31 11:31:30.927  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-31 11:31:30.928  2478  2478 V GmsNetworkLocationProvi: DISABLE
08-31 11:31:30.963  2478  2478 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-31 11:31:31.013  7753  7798 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-31 11:31:31.013  7753  7798 I Babel   : MmsConfig.loadMmsSettings
08-31 11:31:31.024  7753  7798 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-31 11:31:31.024  7753  7798 I Babel   : MmsConfig.loadFromDatabase
,08-31 11:31:31.050  7753  7798 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-31 11:31:31.050  7753  7798 I Babel   : MmsConfig.loadFromResources
08-31 11:31:31.053  7753  7798 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-31 11:31:31.054  7753  7798 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-31 11:31:31.064  7753  7753 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:31:31.067  7753  7796 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 11:31:31.077  7753  7796 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 11:31:31.084  7753  7796 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-31 11:31:31.087  1813  7800 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-31 11:31:31.087  1813  7800 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-31 11:31:31.090  7122  7122 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 11:31:31.095  7122  7122 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@21dabb8e
08-31 11:31:31.095  7122  7122 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:31:31.095  7122  7122 D AppUp4:CustFacade: isPhone : true
08-31 11:31:31.095  7122  7122 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:31:31.096  7122  7122 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-31 11:31:31.117  7753  7796 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-31 11:31:31.118  7753  7796 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 11:31:31.119  7753  7796 W AudioCapabilities: Unsupported mime audio/evrc
08-31 11:31:31.131  1030  1884 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7804 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-31 11:31:31.133  1030  1088 D LocationProviderProxy: applying state to connected service
,08-31 11:31:31.135  1813  4783 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-31 11:31:31.138  1030  1865 I ActivityManager: Killing 6697:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-31 11:31:31.140  7753  7796 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-31 11:31:31.141  7753  7796 W VideoCapabilities: Unsupported mime video/divx
08-31 11:31:31.143  7753  7796 W VideoCapabilities: Unsupported mime video/divx311
08-31 11:31:31.145  7753  7796 W VideoCapabilities: Unsupported mime video/divx4
08-31 11:31:31.148  7753  7796 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-31 11:31:31.151  6998  6998 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-31 11:31:31.151  6998  6998 W System.err: android.os.DeadObjectException
08-31 11:31:31.151  6998  6998 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:31:31.152  6998  6998 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 11:31:31.152  6998  6998 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-31 11:31:31.152  6998  6998 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-31 11:31:31.152  6998  6998 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 11:31:31.152  6998  6998 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 11:31:31.152  6998  6998 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:31:31.152  6998  6998 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:31:31.152  6998  6998 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:31:31.152  6998  6998 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:31:31.152  6998  6998 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:31:31.152  6998  6998 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:31:31.152  6998  6998 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:31:31.152  6998  6998 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:31:31.152  6998  6998 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,08-31 11:31:31.152  6998  6998 W System.err: android.os.DeadObjectException
,08-31 11:31:31.153  6998  6998 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:31:31.153  6998  6998 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 11:31:31.153  6998  6998 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-31 11:31:31.153  6998  6998 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-31 11:31:31.153  6998  6998 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 11:31:31.153  6998  6998 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 11:31:31.153  6998  6998 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:31:31.153  6998  6998 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:31:31.153  6998  6998 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:31:31.153  6998  6998 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:31:31.153  6998  6998 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:31:31.153  6998  6998 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:31:31.153  6998  6998 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:31:31.153  6998  6998 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:31:31.153  6998  6998 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-31 11:31:31.154  6998  6998 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-31 11:31:31.162  7753  7796 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-31 11:31:31.164  7753  7796 W AudioCapabilities: Unsupported mime audio/eac3
08-31 11:31:31.165  7753  7796 W AudioCapabilities: Unsupported mime audio/ac3
08-31 11:31:31.166  7753  7796 W AudioCapabilities: Unsupported mime audio/g726
,08-31 11:31:31.167  7753  7796 W AudioCapabilities: Unsupported mime audio/wma-voice
08-31 11:31:31.168  7753  7796 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-31 11:31:31.169  7753  7796 W AudioCapabilities: Unsupported mime audio/adpcm
08-31 11:31:31.170  7753  7796 W VideoCapabilities: Unsupported mime video/theora
08-31 11:31:31.172  7753  7796 W VideoCapabilities: Unsupported mime video/mjpg
08-31 11:31:31.377  1030  2021 W libprocessgroup: failed to open /acct/uid_1000/pid_6697/cgroup.procs: No such file or directory
,08-31 11:31:31.378  1030  2021 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-31 11:31:31.393  6998  6998 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-31 11:31:31.393  6998  6998 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-31 11:31:31.416  7804  7804 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:31:31.416  7804  7804 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 11:31:31.417  7804  7804 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-31 11:31:31.419  7804  7804 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-31 11:31:31.419  7804  7804 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 11:31:31.443  1030  1045 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7821 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 11:31:31.443  6998  6998 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-31 11:31:31.478  7821  7821 D UEI.SmartControl: Quickset Services start...
,08-31 11:31:31.480  7821  7821 I UEI.SmartControl: Manufacture = LGE
08-31 11:31:31.480  7821  7821 D UEI.SmartControl: Id = LGNevo
08-31 11:31:31.481  7821  7821 D UEI.SmartControl: File observer start...
08-31 11:31:31.482  7821  7821 E UEI.SmartControl: IR Port is disabled: false
08-31 11:31:31.482  7821  7821 D UEI.SmartControl: Starting file observer...
08-31 11:31:31.482  7821  7821 D UEI.SmartControl: Extracting JNI libs...
08-31 11:31:31.482  7821  7821 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-31 11:31:31.499  7804  7804 I SystemConfig: BUILD Country: EU
08-31 11:31:31.499  7804  7804 I SystemConfig: BUILD Operator: OPEN
,08-31 11:31:31.534  1030  1865 I ActivityManager: Killing 6998:com.lge.qremote/u0a112 (adj 15): empty #17
,08-31 11:31:31.547  7821  7821 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-31 11:31:31.548  7821  7821 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-31 11:31:31.548  7821  7821 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-31 11:31:31.573  7821  7821 I UEI.SmartControl: --- Selecting new region: 6
,08-31 11:31:31.575  7821  7821 I UEI.SmartControl: Model = LG-D855
08-31 11:31:31.576  7821  7821 D UEI.SmartControl: QS Service created
08-31 11:31:31.690  1030  1956 W libprocessgroup: failed to open /acct/uid_10112/pid_6998/cgroup.procs: No such file or directory
,08-31 11:31:31.721  7821  7821 I UEI.SmartControl: Service initServices...
,08-31 11:31:31.730  7821  7821 D UEI.SmartControl: QS start get config
08-31 11:31:31.757  1030  2009 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7842 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-31 11:31:31.764  7804  7840 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-31 11:31:31.764  7804  7840 I SystemConfig: existFile = false
08-31 11:31:31.764  7804  7840 I SystemConfig: canReadFile = false
08-31 11:31:31.764  7804  7840 I SystemConfig: systemFeature RCS result false
08-31 11:31:31.765  7804  7840 D SystemConfig: refreshRcsSupport() :false
,08-31 11:31:31.791  7821  7821 D UEI.SmartControl: Loading JNI Libs...
08-31 11:31:31.806  7842  7842 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:31:31.807  7842  7842 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 11:31:31.807  7842  7842 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-31 11:31:31.807  7842  7842 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 11:31:31.904  7842  7842 I AppConfig: Total System Memory = 2995761152
,08-31 11:31:31.915  7842  7842 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-31 11:31:32.016  1030  1574 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7861 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:31:32.023  1030  1574 I ActivityManager: Killing 7156:com.lge.email/u0a23 (adj 15): empty #17
08-31 11:31:32.033   339   339 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 462us total 21.226ms
,08-31 11:31:32.053   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 399us total 18.838ms
,08-31 11:31:32.070   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 364us total 17.212ms
,08-31 11:31:32.141  7821  7821 I UEI.SmartControl: Supports setup maps: true
08-31 11:31:32.141  1030  1883 W libprocessgroup: failed to open /acct/uid_10023/pid_7156/cgroup.procs: No such file or directory
,08-31 11:31:32.145  7821  7821 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 11:31:32.145  7821  7821 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 11:31:32.145  7821  7821 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 11:31:32.145  7821  7821 I UEI.SmartControl: ### init IR Blaster...
08-31 11:31:32.151  7821  7821 D serial_port: Configuring serial port
08-31 11:31:32.154  7821  7821 E UEI.SmartControl: UEIBLaster setting for 616
08-31 11:31:32.155  7821  7821 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 11:31:32.155  7821  7821 I UEI.SmartControl: configuring settings for MAXQ616
08-31 11:31:32.155  7821  7821 I UEI.SmartControl: Get version...
,08-31 11:31:32.172  7821  7878 D UEI.SmartControl: serial port data available: 21
,08-31 11:31:32.199  7821  7821 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 11:31:32.199  7821  7821 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 11:31:32.199  7821  7821 I UEI.SmartControl: QS saving settings...
,08-31 11:31:32.200  7821  7821 D UEI.SmartControl: IR Blaster version: 25672567
08-31 11:31:32.219  7821  7878 D UEI.SmartControl: serial port data available: 4
,08-31 11:31:32.258  7821  7885 I UEI.SmartControl: Device manager: loading config....
,08-31 11:31:32.259  7821  7821 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-31 11:31:32.259  7821  7885 D UEI.SmartControl: ----------- loading internal config...
08-31 11:31:32.263  7821  7821 E UEI.SmartControl: Services init done
08-31 11:31:32.263  7821  7821 D UEI.SmartControl: QS Service init finished
08-31 11:31:32.264  7821  7821 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 11:31:32.264  7821  7821 D UEI.SmartControl: QS Service version code: 201091
08-31 11:31:32.264  7821  7821 D UEI.SmartControl: Service requested: Control
08-31 11:31:32.270  7821  7885 E UEI.SmartControl: Loading SETTINGS...
08-31 11:31:32.270  7821  7821 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 11:31:32.270  7821  7821 D UEI.SmartControl: Service.onUnbind: IControl
08-31 11:31:32.271  7821  7821 D UEI.SmartControl: Service.onDestroy
08-31 11:31:32.271  7821  7821 D UEI.SmartControl: Lock is in USE false
08-31 11:31:32.271  7821  7821 D UEI.SmartControl: unbind internal service
,08-31 11:31:32.273  7821  7821 D serial_port: close(fd = 25)
,08-31 11:31:32.277  7821  7884 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 11:31:32.277  7821  7884 D UEI.SmartControl: -----service ready thread exits
08-31 11:31:32.278  7821  7821 I UEI.SmartControl: Serial port is closed.
08-31 11:31:32.278  7821  7821 I UEI.SmartControl: Serial port is closed.
08-31 11:31:32.279  7821  7821 D UEI.SmartControl: Blaster closed
08-31 11:31:32.279  7821  7821 D UEI.SmartControl: Shut down QS...
08-31 11:31:32.279  7821  7821 D UEI.SmartControl: Stopping QS lib
08-31 11:31:32.280  7821  7821 D UEI.SmartControl: QS lib stop result = true
08-31 11:31:32.280  7821  7821 D UEI.SmartControl: Stopped QS lib
08-31 11:31:32.280  7821  7885 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 11:31:32.280  7821  7821 D UEI.SmartControl: Stopped file observer...
08-31 11:31:32.280  7821  7821 D UEI.SmartControl: QS shutdown complete
08-31 11:31:32.281  7821  7821 D UEI.SmartControl: QS Service created
08-31 11:31:32.294  7821  7821 I UEI.SmartControl: Service initServices...
08-31 11:31:32.294  7821  7821 D UEI.SmartControl: QS start get config
,08-31 11:31:32.316  7861  7861 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-31 11:31:32.388  7861  7861 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:31:32.388  7861  7861 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:31:32.435  7861  7861 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-31 11:31:32.455  7861  7861 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 11:31:32.456  7861  7861 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 11:31:32.475  7861  7861 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:31:32.475  7861  7861 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-31 11:31:32.487  1030  2048 I ActivityManager: Killing 7039:com.lge.formmanager/u0a26 (adj 15): empty #17
08-31 11:31:32.563  1030  1989 W libprocessgroup: failed to open /acct/uid_10026/pid_7039/cgroup.procs: No such file or directory
,08-31 11:31:32.577  4603  7907 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-31 11:31:32.627  1030  2021 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7908 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-31 11:31:32.647  3526  3875 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-31 11:31:32.660  3526  3875 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@28272a52 on behalf of 7861
,08-31 11:31:32.672  7861  7861 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-31 11:31:32.689  7861  7861 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-31 11:31:32.731  7908  7908 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-31 11:31:32.753  7908  7908 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-31 11:31:32.753  7908  7908 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-31 11:31:32.753  7908  7908 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-31 11:31:32.753  7908  7908 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-31 11:31:32.753  7908  7908 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-31 11:31:32.753  7908  7908 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-31 11:31:32.765  7821  7821 I UEI.SmartControl: Supports setup maps: true
,08-31 11:31:32.768  7821  7821 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 11:31:32.768  7821  7821 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 11:31:32.768  7821  7821 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 11:31:32.768  7821  7821 I UEI.SmartControl: ### init IR Blaster...
08-31 11:31:32.773  7821  7821 D serial_port: Configuring serial port
08-31 11:31:32.773  7821  7821 E UEI.SmartControl: UEIBLaster setting for 616
08-31 11:31:32.773  7821  7821 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 11:31:32.773  7821  7821 I UEI.SmartControl: configuring settings for MAXQ616
08-31 11:31:32.773  7821  7821 I UEI.SmartControl: Get version...
08-31 11:31:32.775  1030  1045 I ActivityManager: Killing 6502:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-31 11:31:32.790  7821  7934 D UEI.SmartControl: serial port data available: 21
,08-31 11:31:32.809  1030  1648 W libprocessgroup: failed to open /acct/uid_1000/pid_6502/cgroup.procs: No such file or directory
,08-31 11:31:32.816  7821  7821 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 11:31:32.816  7821  7821 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 11:31:32.817  7821  7821 I UEI.SmartControl: QS saving settings...
08-31 11:31:32.818  7821  7821 D UEI.SmartControl: IR Blaster version: 25672567
08-31 11:31:32.834  7821  7934 D UEI.SmartControl: serial port data available: 4
,08-31 11:31:32.865  7821  7938 I UEI.SmartControl: Device manager: loading config....
08-31 11:31:32.866  7821  7938 D UEI.SmartControl: ----------- loading internal config...
08-31 11:31:32.867  7821  7821 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-31 11:31:32.869  7821  7821 E UEI.SmartControl: Services init done
08-31 11:31:32.869  7821  7821 D UEI.SmartControl: QS Service init finished
08-31 11:31:32.871  7821  7821 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 11:31:32.871  7821  7821 D UEI.SmartControl: QS Service version code: 201091
08-31 11:31:32.872  7821  7821 D UEI.SmartControl: Service requested: Control
08-31 11:31:32.881  7821  7938 E UEI.SmartControl: Loading SETTINGS...
,08-31 11:31:32.882  7821  7821 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 11:31:32.888  1030  1974 I ActivityManager: Killing 7192:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-31 11:31:32.891  7821  7938 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 11:31:32.903  7821  7937 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 11:31:32.903  7821  7937 D UEI.SmartControl: -----service ready thread exits
,08-31 11:31:32.947  1030  1956 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:31:32.988  4603  7907 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 411 ms] updated apps [took 411 ms] 
,08-31 11:31:33.080  1030  2047 W libprocessgroup: failed to open /acct/uid_10046/pid_7192/cgroup.procs: No such file or directory
08-31 11:31:33.081  7821  7821 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@24b029a that was originally bound here
08-31 11:31:33.081  7821  7821 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@24b029a that was originally bound here
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:31:33.081  7821  7821 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-31 11:31:33.091  7821  7821 D UEI.SmartControl: Internal service binding...
08-31 11:31:33.271  7821  7887 D UEI.SmartControl: Internal timer expired: 2
,08-31 11:31:33.474  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:31:33.474  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17fad4f0 added. We now have 6 listener(s)
,08-31 11:31:33.474  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:31:33.488  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-31 11:31:33.488  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@44dfa69 added. We now have 7 listener(s)
08-31 11:31:33.489  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:31:33.493  6821  6899 I System.out: IsBluetoothEnabled
,08-31 11:31:33.500  1030  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:33.500  1030  1574 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-31 11:31:33.500  1030  1094 D BluetoothManagerService: Message: 2
08-31 11:31:33.504  6821  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:33.506  1030  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:33.506  1030  1046 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-31 11:31:33.523  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 11:31:33.526  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:31:33.526  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-31 11:31:33.527  1030  1094 D BluetoothManagerService: Message: 1
08-31 11:31:33.527  1030  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-31 11:31:33.554  1030  1094 D BluetoothManagerService: Message: 20
08-31 11:31:33.554  1030  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9cb08d1:true
,08-31 11:31:33.558  7726  7726 D BluetoothAdapterState: make
08-31 11:31:33.563  7726  7726 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 11:31:33.563  7726  7726 I bluedroid-qcom: init
08-31 11:31:33.564  7726  7952 I BluetoothAdapterState: Entering OffState
08-31 11:31:33.565  7726  7726 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 11:31:33.565  7726  7726 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 11:31:33.565  7726  7726 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 11:31:33.565  7726  7726 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 11:31:33.565  7726  7726 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 11:31:33.567  7726  7726 I bluedroid-qcom: get_profile_interface socket
08-31 11:31:33.567  7726  7726 I bluedroid-qcom: get_profile_interface map_client
,08-31 11:31:33.572  7726  7956 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 11:31:33.574  7726  7956 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 11:31:33.560  7955  7955 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:33.560  7955  7955 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:33.585  7955  7955 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 11:31:33.585  7955  7955 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 11:31:33.585  7955  7955 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-31 11:31:33.590  1030  1030 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 11:31:33.590  1030  1030 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 11:31:33.592  1030  1030 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-31 11:31:33.592  1030  1094 D BluetoothManagerService: Message: 40
08-31 11:31:33.592  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 11:31:33.593  7726  7741 I bluedroid-qcom: config_hci_snoop_log
08-31 11:31:33.594  1030  1094 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 11:31:33.594  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 11:31:33.595  7955  7955 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-31 11:31:33.598  7726  7956 D BluetoothAdapterProperties: Name is: G3
,08-31 11:31:33.605  7955  7955 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 11:31:33.605  7955  7955 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-31 11:31:33.608  7726  7952 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-31 11:31:33.608  7726  7952 D BluetoothAdapterProperties: Setting state to 11
08-31 11:31:33.608  7726  7952 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 11:31:33.609  1030  1094 D BluetoothManagerService: Message: 60
08-31 11:31:33.609  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 11:31:33.609  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 11:31:33.610  7726  7952 I LGBluetoothServiceJni: classInitNative: succeeds
,08-31 11:31:33.620  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:33.620  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:31:33.623  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:33.638  6950  6950 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-31 11:31:33.648  7726  7952 D BluetoothBondStateMachine: make
08-31 11:31:33.650  7726  7726 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:31:33.650  7726  7726 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:31:33.650  7726  7726 V BluetoothPbapReceiver: ***********state = 11
08-31 11:31:33.653  7726  7952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd0b45
08-31 11:31:33.653  7726  7952 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 11:31:33.653  7726  7952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd0b45
08-31 11:31:33.653  7726  7952 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 11:31:33.654  7726  7952 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-31 11:31:33.656  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:31:33.659  7726  7971 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 11:31:33.661  7726  7952 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:31:33.669  7726  7952 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:31:33.671  7726  7726 D HeadsetService: Received start request. Starting profile...
,08-31 11:31:33.672  7726  7726 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 11:31:33.673  7726  7726 D LGBluetoothHfpAdapter: Version 1.6
08-31 11:31:33.674  6950  6950 D BluetoothPermissionRequest: onReceive
08-31 11:31:33.676  7726  7726 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 11:31:33.677  7726  7726 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 11:31:33.678  7726  7726 D HeadsetStateMachine: make
08-31 11:31:33.679  6950  6950 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:31:33.684  7726  7952 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:31:33.691  7726  7952 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:31:33.697  7726  7952 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:31:33.703  7726  7952 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:31:33.708  7726  7952 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:31:33.719  7726  7726 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:31:33.719  7726  7726 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:31:33.724  7726  7726 D HeadsetStateMachine: max_hf_connections = 1
08-31 11:31:33.724  7726  7726 I bluedroid-qcom: get_profile_interface handsfree
08-31 11:31:33.724  7726  7952 V LGMDMManager: Create singleton instance
08-31 11:31:33.725  7726  7952 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 11:31:33.726  7726  7726 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 11:31:33.727   311   311 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 1002
08-31 11:31:33.727   311  2151 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 11:31:33.727   311  2151 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:31:33.727   311  2151 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:31:33.727  7726  7726 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 11:31:33.727   311  2152 V AudioFlinger: registerClient() client 0xb1433280, pid 7726
08-31 11:31:33.728   311  1390 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:31:33.728   311  1390 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:31:33.728  7726  7726 V ToneGenerator: Create Track: 0xb4928080
08-31 11:31:33.728  7726  7726 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 11:31:33.728  7726  7726 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 11:31:33.728   311  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 11:31:33.728   311  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 11:31:33.728   311  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:31:33.728   311  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:31:33.728   311  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:31:33.728   311  1392 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:31:33.729  1030  2048 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:31:33.729  1030  2048 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:31:33.729  7726  7726 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 11:31:33.729  1030  2048 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:31:33.729  1030  2048 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:31:33.729  1600  2076 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:31:33.729  1600  2076 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:31:33.729  1600  2076 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:31:33.729  1600  2076 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:31:33.729   311  1396 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 11:31:33.729  1848  1864 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:31:33.729  1848  1864 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:31:33.729   311  2152 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 11:31:33.729  1848  1864 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:31:33.729  1848  1864 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:31:33.729   311  2152 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 11:31:33.729   311  2152 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:31:33.729   311  2152 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:31:33.729  3475  3491 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31, 11:31:33.729  3475  3491 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:31:33.729  3475  3491 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:31:33.729  3475  3491 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:31:33.729  7726  7726 V AudioSystem: getLatency() output 2, latency 50
08-31 11:31:33.729  7726  7742 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:31:33.729  7726  7742 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 11:31:33.730  7726  7742 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:31:33.730  7726  7742 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 11:31:33.730  7726  7726 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 11:31:33.730  7726  7726 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 11:31:33.730   311  2151 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 11:31:33.730   311  2151 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 11:31:33.730   311  2151 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 11:31:33.730   311  2151 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 11:31:33.730   311  2151 V AudioFlinger: createTrack() lSessionId: 21
08-31 11:31:33.731  7726  7726 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 11:31:33.731   311  2151 V AudioFlinger: acquiring 21 from 7726, for 7726
08-31 11:31:33.731   311  2151 V AudioFlinger:  added new entry for 21
08-31 11:31:33.731  7726  7726 V ToneGenerator: ToneGenerator INIT OK, time: 238975
08-31 11:31:33.732  7726  7726 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd0b45
08-31 11:31:33.732  7726  7974 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 11:31:33.733  7726  7974 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:31:33.733  7726  7726 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd0b45
08-31 11:31:33.735  7726  7726 D A2dpService: Received start request. Starting profile...
,08-31 11:31:33.736  7726  7726 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 11:31:33.737  7726  7726 V Avrcp   : make
08-31 11:31:33.737  7726  7726 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-31 11:31:33.737  7726  7726 I bluedroid-qcom: get_profile_interface avrcp
08-31 11:31:33.738  7726  7974 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:31:33.738  7726  7974 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 11:31:33.739   311  1396 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7726
08-31 11:31:33.739   311  1396 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 11:31:33.739   311  1396 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 11:31:33.739   311  1396 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 11:31:33.739   311  1396 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 11:31:33.739   311  1396 V voice   : voice_set_parameters: exit with code(0)
08-31 11:31:33.742   311  1396 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 11:31:33.742   311  1396 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 11:31:33.742   311  1396 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 11:31:33.742   311  1396 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 11:31:33.742   311  1396 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 11:31:33.742   311  1396 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 11:31:33.742  7726  7974 V ToneGenerator: ToneGenerator destructor
08-31 11:31:33.742  7726  7974 V ToneGenerator: stopTone
08-31 11:31:33.742  7726  7974 V ToneGenerator: Delete Track: 0xb4928080
08-31 11:31:33.743  7726  7974 V AudioTrack: ~AudioTrack, releasing session id from 7726 on behalf of 7726
08-31 11:31:33.743   311  2152 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 11:31:33.743   311  2152 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 11:31:33.743   311  2151 V AudioFlinger: releasing 21 from 7726 for 7726
08-31 11:31:33.743   311  2151 V AudioFlinger:  decremented refcount to 0
08-31 11:31:33.743   311  2152 V AudioFlinger: PlaybackThread::Track destructor
08-31 11:31:33.743   311  2151 V AudioFlinger: purging stale effects
08-31 11:31:33.743   311  1209 V AudioPolicyService: AudioCommandThread() waking up
08-31 11:31:33.743   311  2152 V AudioFlinger: removeClient_l() pid 7726, calling pid 311
08-31 11:31:33.743   311  1209 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 11:31:33.743   311  1209 V AudioPolicyManager: releaseOutput() 2
08-31 11:31:33.743   311  1209 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 11:31:33.747  7726  7726 V AudioManager: registerRemoteController: size of Media player list: 0
08-31 11:31:33.749  7726  7726 E AudioManager: No RCC entry present to update
08-31 11:31:33.749  7726  7726 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 11:31:33.752  7726  7726 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-31 11:31:33.753  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 11:31:33.753  7726  7726 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 11:31:33.757  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 11:31:33.908  1030  1883 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:31:33.908  1030  1883 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:31:34.041  1030  1574 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-31 11:31:34.069  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-31 11:31:34.075  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 11:31:34.076  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 11:31:34.077  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 11:31:34.077  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 11:31:34.077  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-31 11:31:34.077  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 11:31:34.077  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
,08-31 11:31:34.077  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 11:31:34.077  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:31:34.077  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 11:31:34.078  7726  7726 I BluetoothA2dpServiceJni: classInitNative
,08-31 11:31:34.078  7726  7726 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:31:34.078  7726  7726 D A2dpStateMachine: make
08-31 11:31:34.081  7726  7726 I bluedroid-qcom: get_profile_interface a2dp
,08-31 11:31:34.081  7726  7987 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 11:31:34.084  7726  7726 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:31:34.085  7726  7726 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 11:31:34.086  7726  7726 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd0b45
,08-31 11:31:34.087  7726  7986 D A2dpStateMachine: Enter Disconnected: -2
,08-31 11:31:34.091  7726  7726 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 11:31:34.097  7726  7726 D HidService: Received start request. Starting profile...
08-31 11:31:34.097  7726  7726 I bluedroid-qcom: get_profile_interface hidhost
08-31 11:31:34.097  7726  7726 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd0b45
08-31 11:31:34.098  7726  7726 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 11:31:34.100  7726  7726 D HealthService: Received start request. Starting profile...
,08-31 11:31:34.102  7726  7726 I bluedroid-qcom: get_profile_interface health
,08-31 11:31:34.102  7726  7726 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 11:31:34.102  7726  7726 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd0b45
08-31 11:31:34.103  7726  7726 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 11:31:34.106  7726  7726 D PanService: Received start request. Starting profile...
08-31 11:31:34.106  7726  7726 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:31:34.106  7726  7726 I bluedroid-qcom: get_profile_interface pan
08-31 11:31:34.116  7726  7726 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-31 11:31:34.116  7726  7726 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd0b45
,08-31 11:31:34.118  7726  7726 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 11:31:34.130  7726  7726 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:31:34.132  7726  7726 D BtGatt.GattService: Received start request. Starting profile...
08-31 11:31:34.132  7726  7726 D BtGatt.GattService: start()
08-31 11:31:34.132  7726  7726 I bluedroid-qcom: get_profile_interface gatt
,08-31 11:31:34.133  7726  7726 D BtGatt.AdvertiseManager: advertise manager created
08-31 11:31:34.141  7726  7726 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd0b45
08-31 11:31:34.143  7726  7726 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd0b45
,08-31 11:31:34.144  7726  7726 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 11:31:34.145  7726  7726 V BluetoothMapService: BluetoothMapBinder()
08-31 11:31:34.146  7726  7726 D BluetoothMapService: Received start request. Starting profile...
,08-31 11:31:34.146  7726  7726 D BluetoothMapService: start()
08-31 11:31:34.150  7726  7726 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 11:31:34.150  7726  7726 D BluetoothMapEmailAppObserver: createReceiver()
08-31 11:31:34.152  7726  7726 D BluetoothMapEmailAppObserver: initObservers()
08-31 11:31:34.152  7726  7726 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 11:31:34.161  7726  7726 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd0b45
08-31 11:31:34.161  7726  7726 D HeadsetStateMachine: Proxy object connected
08-31 11:31:34.162  7726  7726 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 11:31:34.162  7726  7726 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-31 11:31:34.165  7726  7974 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 11:31:34.166  7726  7974 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 11:31:34.167  7726  7974 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 11:31:34.169  7726  7726 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:31:34.173  7726  7726 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:31:34.175  7726  7726 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:31:34.180  7726  7726 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:31:34.183  7726  7726 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:31:34.186  7726  7726 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:31:34.187  7726  7726 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 11:31:34.190  7726  7726 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 11:31:34.190  7726  7726 V BluetoothMapService: Handler(): got msg=1
,08-31 11:31:34.193  7726  7952 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 11:31:34.193  7726  7726 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:31:34.193  7726  7952 I bluedroid-qcom: enable
08-31 11:31:34.193  7726  7726 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:31:34.193  7726  7726 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:31:34.193  7726  7726 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:34.193  7726  7952 I bt_hci_bdroid: init
08-31 11:31:34.193  7726  7726 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 11:31:34.195  7726  7952 I bt_vendor: bt-vendor : init
08-31 11:31:34.195  7726  7952 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 11:31:34.195  7726  7952 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 11:31:34.195  7726  7952 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 11:31:34.195  7726  7952 D bt_userial_mct: userial_init
08-31 11:31:34.196  7726  7952 D bt_hci_bdroid: set_power 1
08-31 11:31:34.196  7726  7952 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 11:31:34.196  7726  7952 I bt_vendor: Starting hciattach daemon
08-31 11:31:34.196  7726  7952 I bt_vendor: try to set true
08-31 11:31:34.198  7726  7994 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 11:31:34.198  7726  7994 I bt-btu  : btu_task pending for preload complete event
08-31 11:31:34.190  7997  7997 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:34.190  7997  7997 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 11:31:34.225  7998  7998 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 11:31:34.296  8004  8004 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 11:31:34.309  8005  8005 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 11:31:34.334  8007  8007 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 11:31:34.347  8008  8008 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-31 11:31:34.360  8009  8009 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 11:31:34.385  8010  8010 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-31 11:31:34.407  8012  8012 I libmdmdetect: ESOC framework not supported
,08-31 11:31:34.408  8012  8012 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-31 11:31:34.416  8012  8012 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-31 11:31:34.416  8012  8012 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-31 11:31:34.416  8012  8012 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-31 11:31:34.416  8012  8012 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 11:31:34.416  8012  8012 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 11:31:34.416  8012  8012 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 11:31:34.416  8012  8012 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-31 11:31:34.456  8012  8013 E QC-QMI  : qmi_client [8012] 15: failed to locate client data
,08-31 11:31:34.462   468   468 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-31 11:31:34.462   468   468 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-31 11:31:34.505  8014  8014 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 11:31:34.519  8015  8015 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-31 11:31:34.550  7726  7952 I bt_vendor: bluetooth satus is on
08-31 11:31:34.550  7726  7952 D bt_hci_bdroid: preload
08-31 11:31:34.550  7726  7996 D bt_userial_mct: userial_open(port:0)
08-31 11:31:34.550  7726  7996 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-31 11:31:34.554  7726  7996 I bt_vendor: Done intiailizing UART
,08-31 11:31:34.555  7726  7996 I bt_vendor: Done intiailizing UART
08-31 11:31:34.555  7726  7996 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 11:31:34.555  7726  7996 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 11:31:34.555  7726  7994 I bt-btu  : btu_task received preload complete event
08-31 11:31:34.557  7726  7994 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-31 11:31:34.557  7726  7994 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-31 11:31:34.562  7726  7994 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-31 11:31:34.566  7726  8017 D bt_userial_mct: Entering userial_read_thread()
,08-31 11:31:34.567  7726  7994 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 11:31:34.567  7726  7994 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 11:31:34.567  7726  7994 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 11:31:34.567  7726  7994 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 11:31:34.568  7726  7994 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 11:31:34.568  7726  7994 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 11:31:34.568  7726  7994 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 11:31:34.568  7726  7994 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 11:31:34.568  7726  7994 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-31 11:31:34.568  7726  7994 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 11:31:34.568  7726  7994 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 11:31:34.568  7726  7994 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 11:31:34.568  7726  7994 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 11:31:34.568  7726  7994 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 11:31:34.568  7726  7994 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 11:31:34.568  7726  7994 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 11:31:34.625  7726  7994 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-31 11:31:34.625  7726  7994 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa017c061 
08-31 11:31:34.625  7726  7994 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa017c061 
,08-31 11:31:34.650  7726  7956 E bt-btif : Calling BTA_HhEnable
08-31 11:31:34.650  7726  7956 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-31 11:31:34.650  7726  7956 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-31 11:31:34.656  7726  7994 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-31 11:31:34.656  7726  7994 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-31 11:31:34.656  7726  7994 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-31 11:31:34.656  7726  7994 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,08-31 11:31:34.656  7726  7994 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-31 11:31:34.658  7726  7956 D BluetoothAdapterProperties: Name is: G3
08-31 11:31:34.659  1030  1030 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 11:31:34.659  1030  1030 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 11:31:34.661  7726  7956 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:31:34.661  7726  7956 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:31:34.661  7726  7956 D bt_hci_bdroid: postload
08-31 11:31:34.662  7726  7996 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:31:34.663  7726  7996 D bt_hci_bdroid: Used up Tx Cmd credits
,08-31 11:31:34.669  7726  7996 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:31:34.670  7726  7994 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-31 11:31:34.671  7726  7956 D bte_conf: Device ID record 1 : primary
08-31 11:31:34.671  7726  7956 D bte_conf:   vendorId            = 00c4
08-31 11:31:34.671  7726  7956 D bte_conf:   vendorIdSource      = 0001
08-31 11:31:34.671  7726  7956 D bte_conf:   product             = 13a1
08-31 11:31:34.671  7726  7956 D bte_conf:   version             = 1000
08-31 11:31:34.671  7726  7956 D bte_conf:   clientExecutableURL = 
08-31 11:31:34.671  7726  7956 D bte_conf:   serviceDescription  = 
08-31 11:31:34.671  7726  7956 D bte_conf:   documentationURL    = 
08-31 11:31:34.671  7726  7956 D bte_conf: bte_load_did_conf no section named DID2.
08-31 11:31:34.674  7726  7996 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:31:34.670  8022  8022 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 11:31:34.682  7726  8017 E bt_mct  : hci lib postload completed
08-31 11:31:34.683  7726  7952 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 11:31:34.683  7726  7952 D BluetoothAdapterProperties: ScanMode =  20
08-31 11:31:34.683  7726  7952 D BluetoothAdapterProperties: State =  11
08-31 11:31:34.683  7726  7952 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 11:31:34.684  7726  7952 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 11:31:34.684  7726  7952 D BluetoothAdapterProperties: Setting state to 12
08-31 11:31:34.684  7726  7952 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 11:31:34.684  7726  7956 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 11:31:34.685  7726  7956 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 11:31:34.680  8022  8022 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 11:31:34.707  7726  7952 I BluetoothAdapterState: Entering On State
,08-31 11:31:34.710  7726  7994 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:31:34.710  7726  7994 W bt-smp  : Plain text(LSB ~ MSB) = cc af 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:31:34.710  7726  7994 W bt-smp  : Encrypted text(LSB ~ MSB) = 58 3b b1 19 d4 2c 2c 00 b6 85 67 db 4f b5 27 b6 
08-31 11:31:34.710  7726  7994 W bt-btm  : Stopping oneshot timer
08-31 11:31:34.706  1030  1094 D BluetoothManagerService: Message: 60
08-31 11:31:34.711  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 11:31:34.711  1030  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-31 11:31:34.731  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:34.731  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:34.731  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:34.731  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:31:34.731  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:34.731  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:34.731  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:34.731  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:31:34.752  7726  7956 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:31:34.752  7726  7956 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-31 11:31:34.757  7726  7952 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 11:31:34.757  7726  7952 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 11:31:34.757  7726  7952 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-31 11:31:34.760  7726  7952 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 11:31:34.760  7726  7952 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-31 11:31:34.760  7726  7994 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:31:34.760  7726  7994 W bt-smp  : Plain text(LSB ~ MSB) = 4e e9 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:31:34.760  7726  7994 W bt-smp  : Encrypted text(LSB ~ MSB) = 6b cc 06 60 33 3a fe 9f 8c 24 78 68 b4 9e 59 16 
08-31 11:31:34.761  7726  7994 W bt-btm  : Stopping oneshot timer
08-31 11:31:34.763  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:31:34.770  6950  6965 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:31:34.779  7726  7994 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:31:34.779  7726  7994 W bt-smp  : Plain text(LSB ~ MSB) = 14 c5 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:31:34.779  7726  7994 W bt-smp  : Encrypted text(LSB ~ MSB) = fe ae ad 1c c5 6a 79 e3 cd 62 4a 48 87 bb fa 1d 
,08-31 11:31:34.779  7726  7994 W bt-btm  : Stopping oneshot timer
08-31 11:31:34.797  7726  7994 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:31:34.797  7726  7994 W bt-smp  : Plain text(LSB ~ MSB) = 53 79 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:31:34.797  7726  7994 W bt-smp  : Encrypted text(LSB ~ MSB) = a3 fa 61 36 80 93 8d df 5e 0e 41 14 85 97 5c aa 
08-31 11:31:34.797  7726  7994 W bt-btm  : Stopping oneshot timer
,08-31 11:31:34.807  1848  1863 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:31:34.811  1848  1848 D BluetoothHeadset: Proxy object connected
08-31 11:31:34.812  1848  2573 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:31:34.813  8037  8037 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-31 11:31:34.813  7726  7994 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:31:34.813  7726  7994 W bt-smp  : Plain text(LSB ~ MSB) = 62 41 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:31:34.813  7726  7994 W bt-smp  : Encrypted text(LSB ~ MSB) = ce 75 d7 66 b6 96 45 4f 50 be af 84 ee b1 af 38 
08-31 11:31:34.814  7726  7994 W bt-btm  : Stopping oneshot timer
,08-31 11:31:34.814  1848  1848 D BluetoothHeadset: Proxy object connected
,08-31 11:31:34.815  6950  6966 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 11:31:34.817  6950  6950 D BluetoothA2dp: Proxy object connected
08-31 11:31:34.817  6950  6950 D A2dpProfile: Bluetooth service connected
08-31 11:31:34.817  6950  7036 D BluetoothPan: onBluetoothStateChange on: true
08-31 11:31:34.817  6950  7036 D BluetoothPan: onBluetoothStateChange call bindService
08-31 11:31:34.821  6950  6950 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:31:34.821  6950  6950 D PanProfile: Bluetooth service connected
08-31 11:31:34.822  1030  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:31:34.822  1030  1030 D BluetoothHeadset: Proxy object connected
08-31 11:31:34.823  1848  4020 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:31:34.825  1848  1848 D BluetoothHeadset: Proxy object connected
08-31 11:31:34.826  1030  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:31:34.827  1030  1030 D BluetoothA2dp: Proxy object connected
,08-31 11:31:34.828  6950  6966 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 11:31:34.833  6950  7036 D BluetoothMap: onBluetoothStateChange: up=true
08-31 11:31:34.957  1030  1937 I art     : Explicit concurrent mark sweep GC freed 26855(1311KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.792ms total 122.838ms
,08-31 11:31:34.961  6950  6950 D BluetoothInputDevice: Proxy object connected
08-31 11:31:34.961  6950  6950 D HidProfile: Bluetooth service connected
08-31 11:31:34.962  6950  6965 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:31:34.964  6950  6950 D BluetoothMap: Proxy object connected
08-31 11:31:34.964  6950  6950 D MapProfile: Bluetooth service connected
08-31 11:31:34.965  6950  6950 D BluetoothMap: getConnectedDevices()
08-31 11:31:34.966  7726  7741 V BluetoothMapService: getConnectedDevices()
08-31 11:31:34.967  1030  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 11:31:34.968  1030  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 11:31:34.968  1030  1030 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-31 11:31:34.969  6950  6950 D BluetoothHeadset: Proxy object connected
08-31 11:31:34.969  6950  6950 D HeadsetProfile: Bluetooth service connected
08-31 11:31:34.971  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:31:34.972  1939  2123 D LGBluetoothAPIService: Message: 1
08-31 11:31:34.972  1939  2123 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 11:31:34.972  1939  2123 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-31 11:31:34.972  1939  2123 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 11:31:34.976  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:34.977  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:31:34.978  1030  1094 D BluetoothManagerService: Message: 40
08-31 11:31:34.979  1030  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 11:31:34.981  7726  7726 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:34.981  7726  7726 D BluetoothMapService: STATE_ON
08-31 11:31:34.984  6950  6950 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 11:31:34.986  6950  6950 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 11:31:34.990  7726  7726 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd0b45
08-31 11:31:34.991  7726  7726 V BluetoothPbapService: Pbap Service onCreate
08-31 11:31:34.991  7726  7726 V BluetoothPbapService: Starting PBAP service
08-31 11:31:34.992  7726  7726 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 11:31:34.992  7726  7726 V BluetoothPbapService: Pbap Service onBind
08-31 11:31:34.993  7726  7726 V BluetoothMapService: Handler(): got msg=1
,08-31 11:31:34.993  7726  7726 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 11:31:34.994  7726  7726 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:34.994  7726  7726 V BluetoothPbapService: state: 12
08-31 11:31:34.994  7726  7726 V BluetoothPbapService: Handler(): got msg=1
08-31 11:31:34.995  7726  8047 D BluetoothMapMasInstance: MAS initSocket()
08-31 11:31:34.995  7726  8047 D BluetoothMapMasInstance:   masId = 00
08-31 11:31:34.995  7726  8047 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 11:31:34.995  7726  8047 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 11:31:34.995  7726  8047 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 11:31:34.995  7726  7726 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 11:31:34.996  7726  7726 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:31:34.996  6950  6950 D DockEventReceiver: finishStartingService: stopping service
08-31 11:31:34.996  7726  7726 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:34.996  7726  7726 V BluetoothPbapReceiver: ***********state = 12
08-31 11:31:34.997  6950  6950 D BluetoothPbap: Proxy object connected
08-31 11:31:34.997  6950  6950 D PbapServerProfile: Bluetooth service connected
08-31 11:31:34.998  1030  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:34.999  7726  8047 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:31:35.000  7726  8048 V BluetoothPbapService: Pbap Service initSocket
08-31 11:31:35.005  1030  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:35.006  7726  8047 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 11:31:35.006  7726  8048 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:31:35.007  7726  8047 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 11:31:35.007  7726  8047 D BluetoothMapMasInstance: Accepting socket connection...
08-31 11:31:35.012  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:31:35.012  2194  2194 D c       : Getting all permits...
08-31 11:31:35.012  2194  2194 D a       : Opening database...
08-31 11:31:35.014  2194  2194 D a       : Opening database auth.proximity.permit_store...
08-31 11:31:35.015  2194  2194 D a       : Closing database...
08-31 11:31:35.016  7726  7956 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:31:35.016  7726  7956 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-31 11:31:35.018  7726  8048 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 11:31:35.018  7726  8048 V BluetoothPbapService: Succeed to create listening socket 
08-31 11:31:35.018  7726  8048 V BluetoothPbapService: Accepting socket connection...
08-31 11:31:35.019  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:31:35.024  6950  6950 D BluetoothPermissionRequest: onReceive
08-31 11:31:35.026  6950  6950 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 11:31:35.027  6950  6950 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:31:35.030  7726  7726 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-31 11:31:35.031  7726  7726 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-31 11:31:35.035  7726  7726 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-31 11:31:35.055  7726  7726 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 11:31:35.055  7726  7726 V BtOppService: onCreate
,08-31 11:31:35.061  7726  7726 V BluetoothOppNotification: send message
08-31 11:31:35.067  7726  7726 V BtOppService: Starting RfcommListener
08-31 11:31:35.075  7726  7726 D BluetoothOppPreference: Dumping Names:  
08-31 11:31:35.075  7726  7726 D BluetoothOppPreference: {}
,08-31 11:31:35.075  7726  7726 D BluetoothOppPreference: Dumping Channels:  
08-31 11:31:35.075  7726  7726 D BluetoothOppPreference: {}
08-31 11:31:35.076  7726  7726 V BtOppService: onStartCommand
08-31 11:31:35.080  7726  8052 V BtOppService: Deleted complete outbound shares, number =  0
08-31 11:31:35.080  7726  7726 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:35.080  7726  8055 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 11:31:35.081  7726  7726 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 11:31:35.082  7726  8055 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 11:31:35.082  7726  8052 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 11:31:35.083  7726  8052 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 11:31:35.084  7726  7726 V BluetoothOppNotification: new notify threadi!
08-31 11:31:35.084  7726  8052 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fc19d11 on behalf of 
08-31 11:31:35.085  7726  7726 V BluetoothOppNotification: send delay message
08-31 11:31:35.087  7726  8056 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 11:31:35.087  7726  7726 V BtOppService: start RfcommListener
,08-31 11:31:35.091  7726  8056 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f713e76 on behalf of 
08-31 11:31:35.093  7726  7726 V BtOppService: RfcommListener started
08-31 11:31:35.094  7726  7726 V BtOppService: ContentObserver received notification
08-31 11:31:35.094  7726  8055 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3983bc77 on behalf of 
08-31 11:31:35.094  7726  7726 V BtOppService: ContentObserver received notification
08-31 11:31:35.095  7726  8057 V BtOppRfcommListener: Starting RFCOMM listener....
08-31 11:31:35.095  1030  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:35.097  7726  8057 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:31:35.098  7726  8057 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=75
,08-31 11:31:35.099  7726  8057 V BtOppRfcommListener: Started RFCOMM listener....
08-31 11:31:35.099  7726  8057 I BtOppRfcommListener: Accept thread started.
08-31 11:31:35.099  7726  8057 V BtOppRfcommListener: Accepting connection...
08-31 11:31:35.100  7726  8056 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 11:31:35.101  7726  8055 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 11:31:35.101  7726  8055 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 11:31:35.103  7726  8056 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 11:31:35.106  7726  8055 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b8db0e4 on behalf of 
08-31 11:31:35.107  7726  8056 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b91f94d on behalf of 
08-31 11:31:35.107  7726  8055 V BluetoothOppNotification: update too frequent, put in queue
08-31 11:31:35.108  7726  8055 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 11:31:35.110  7726  8056 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 11:31:35.111  7726  8056 V BluetoothOppNotification: outbound notification was removed.
08-31 11:31:35.111  7726  8056 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 11:31:35.113  7726  8056 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15aacc02 on behalf of 
,08-31 11:31:35.114  7726  8056 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 11:31:35.116  7726  8056 V BluetoothOppNotification: inbound notification was removed.
08-31 11:31:35.116  7726  7726 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd0b45
08-31 11:31:35.116  7726  7726 V BluetoothFtpService: Ftp Service onCreate
08-31 11:31:35.116  7726  8056 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 11:31:35.116  7726  7726 I BluetoothFtpService: Ftp Service onCreate
08-31 11:31:35.117  7726  7726 V BluetoothFtpService: Ftp Service onStartCommand
08-31 11:31:35.117  7726  7726 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:35.117  7726  7726 V BluetoothFtpService: Starting Listening on sockets
08-31 11:31:35.117  7726  7726 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:31:35.117  7726  7726 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:31:35.117  7726  7726 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:31:35.118  7726  7726 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:35.118  7726  7726 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 11:31:35.118  7726  7726 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 11:31:35.118  7726  8056 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12e6f750 on behalf of 
08-31 11:31:35.120  7726  7726 V BluetoothFtpService: Handler(): got msg=1
08-31 11:31:35.120  7726  7726 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 11:31:35.120  7726  7726 V BluetoothFtpService: Ftp Service initSocket
08-31 11:31:35.125  1030  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:35.126  7726  7726 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:31:35.128  7726  7726 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 11:31:35.131  7726  8058 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-31 11:31:35.147  7726  7726 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd0b45
08-31 11:31:35.147  7726  7726 V BluetoothSapService: Sap Service onCreate
,08-31 11:31:35.150  7726  7726 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:31:35.150  7726  7726 V BluetoothSapService: state: 12
,08-31 11:31:35.150  7726  7726 V BluetoothSapService: Starting SAP server process
08-31 11:31:35.152  7726  7726 V BluetoothSapService: SAP Service startRfcommListenerThread
08-31 11:31:35.140  8059  8059 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:35.140  8059  8059 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 11:31:35.155  7726  8060 V BluetoothSapService: Sap Service initRfcommSocket
08-31 11:31:35.156  1030  2048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:35.158  7726  8060 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:31:35.159  7726  8060 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-31 11:31:35.159  7726  8060 V BluetoothSapService: Succeed to create listening socket 
08-31 11:31:35.159  7726  8060 V BluetoothSapService: Accepting socket connection...
,08-31 11:31:35.165  8059  8059 V BT_SAP  : Event pipe created
,08-31 11:31:35.165  8059  8059 V BT_SAP  : create_server_socket qcom.sap.server
,08-31 11:31:35.165  8059  8059 V BT_SAP  : created socket fd 6
08-31 11:31:35.557  6821  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:35.557  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:35.557  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:35.557  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:31:35.557  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:35.557  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:35.557  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:35.557  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:31:35.579  6821  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:31:35.584  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:35.584  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2db5ccee added. We now have 8 listener(s)
08-31 11:31:35.584  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:31:35.588  1030  2048 D WifiServiceImplEx: setWifiEnabled: false pid=6821, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 11:31:35.588  1030  2048 D WifiService: setWifiEnabled: false pid=6821, uid=10118
08-31 11:31:35.588  1030  2048 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 11:31:35.593  6821  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:31:35.598  1030  2047 D WifiServiceImplEx: setWifiEnabled: true pid=6821, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 11:31:35.599  1030  2047 D WifiService: setWifiEnabled: true pid=6821, uid=10118
08-31 11:31:35.599  1030  2047 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:31:35.619  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:31:35.619  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:31:35.619  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-31 11:31:35.621  1030  1389 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-31 11:31:35.621  1030  1389 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-31 11:31:35.624  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-31 11:31:35.624  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 11:31:35.624  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-31 11:31:35.624  1030  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 11:31:35.625  1030  1389 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-31 11:31:35.625  1030  1389 E WifiHW  : unknown target_country: EU , set to default
08-31 11:31:35.625  1030  1389 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-31 11:31:35.625  1030  1389 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-31 11:31:35.625  1030  1389 I WifiUtil: gEnableBmps=1
08-31 11:31:36.098  7726  7726 V BluetoothOppNotification: new notify threadi!
,08-31 11:31:36.102  7726  7726 V BluetoothOppNotification: send delay message
08-31 11:31:36.113  7726  8073 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-31 11:31:36.131  7726  8073 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@184c387c on behalf of 
08-31 11:31:36.132  7726  8073 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-31 11:31:36.136  7726  8073 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 11:31:36.137  7726  8073 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d920505 on behalf of 
08-31 11:31:36.138  7726  8073 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 11:31:36.140  7726  8073 V BluetoothOppNotification: outbound notification was removed.
08-31 11:31:36.140  7726  8073 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 11:31:36.141  7726  8073 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b91d95a on behalf of 
08-31 11:31:36.142  7726  8073 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 11:31:36.143  7726  8073 V BluetoothOppNotification: inbound notification was removed.
08-31 11:31:36.143  7726  8073 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 11:31:36.146  7726  8073 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22ef278b on behalf of 
,08-31 11:31:36.310   304   890 D SoftapController: Softap fwReload - Ok
,08-31 11:31:36.324  1030  1389 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (690ms)
,08-31 11:31:36.336   304   890 D CommandListener: Setting iface cfg
08-31 11:31:36.336   304   890 D CommandListener: Trying to bring down wlan0
08-31 11:31:36.337  1030  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:31:36.337  1030  1094 D Tethering: InitialState.processMessage what=4
,08-31 11:31:36.342   304   890 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:31:36.351  1030  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 11:31:36.358  1030  1389 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-31 11:31:36.360  8081  8081 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:36.375  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:31:36.375  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:31:36.375  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:31:36.360  8081  8081 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:36.395  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:31:36.399  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 11:31:36.407  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-31 11:31:36.422  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:31:36.427  1030  1389 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 11:31:36.427  1030  1389 D WifiMonitor: connecting to supplicant
08-31 11:31:36.439  8081  8081 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 11:31:36.448  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:31:36.448  6950  6950 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:31:36.448  6950  6950 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:31:36.448  6950  6950 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 11:31:36.448  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 11:31:36.449  6950  6950 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:31:36.449  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 11:31:36.449  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:31:36.449  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 11:31:36.449  6950  6950 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:31:36.449  6950  6950 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:31:36.452  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:31:36.452  6950  6950 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:31:36.452  6950  6950 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:31:36.452  6950  6950 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 11:31:36.452  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 11:31:36.453  6950  6950 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:31:36.453  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 11:31:36.453  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:31:36.453  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-31 11:31:36.453  6950  6950 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:31:36.453  6950  6950 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:31:36.481  8081  8081 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 11:31:36.481  8081  8081 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-31 11:31:36.489  7821  7831 E UEI.SmartControl: file observer is disposed!
08-31 11:31:36.508  1030  2047 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8099 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-31 11:31:36.555  8081  8081 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 11:31:36.589  8081  8081 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-31 11:31:36.593  8081  8081 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-31 11:31:36.595  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-31 11:31:36.595  1030  8120 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-31 11:31:36.595  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 11:31:36.595  1030  8120 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 11:31:36.595  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-31 11:31:36.596  1030  1389 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 11:31:36.596  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:36.596  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:36.597  1030  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:36.597  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:36.597  1030  1389 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 11:31:36.597  1030  1389 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 11:31:36.598  1030  1389 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 11:31:36.598  1030  1389 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 11:31:36.598  1030  1389 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-31 11:31:36.619  1030  8120 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 11:31:36.619  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 11:31:36.620  8081  8081 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 11:31:36.620  1030  8120 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 11:31:36.620  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-31 11:31:36.621  1030  8120 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 11:31:36.621  1030  8120 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-31 11:31:36.641  6821  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:36.641  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:36.641  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:36.641  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:36.641  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:36.641  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:36.641  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:36.641  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:31:36.645  6821  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:31:36.647  1030  1915 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8121 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 11:31:36.652  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:31:36.652  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:36.653  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:36.653  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:36.653  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:31:36.653  1030  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:31:36.653  1030  1389 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:31:36.653  1030  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:31:36.655  1030  1389 D WifiNative-wlan0: doBoolean: SET update_config 1
08-31 11:31:36.657  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:36.659  1939  1939 D WfdService: Waiting for WifiP2p enabling
,08-31 11:31:36.661  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 11:31:36.662  1030  1438 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 11:31:36.662  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:31:36.662  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:36.662  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:36.662  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:36.662  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:36.662  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:31:36.662  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:31:36.662  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:31:36.663  1030  1389 D WifiNative-wlan0: SET update_config 1: returned true
08-31 11:31:36.663  1030  1389 D WifiConfigStore: Loading config and enabling all networks 
08-31 11:31:36.663  1030  1389 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 11:31:36.664  1030  1389 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-31 11:31:36.664  6821  6899 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-31 11:31:36.664  8099  8118 W FormManager: Network not available. Please check & try again.
08-31 11:31:36.665  6821  6899 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-31 11:31:36.668  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:31:36.669  6821  6899 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@34cb67c0 Bundle[{}]
08-31 11:31:36.670  6821  6899 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 11:31:36.670  6821  6899 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-31 11:31:36.671  6821  6899 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-31 11:31:36.672  6821  6899 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 11:31:36.672  1030  1389 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-31 11:31:36.673  6821  6899 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-31 11:31:36.673  8099  8119 V FormManager: Network unavailable.
08-31 11:31:36.674  6821  6899 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 11:31:36.679  8099  8119 V FormManager: Network unavailable.
08-31 11:31:36.680  6821  6899 I System.out: Running OutgoingSocketThread
08-31 11:31:36.682  6821  8138 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 875)
08-31 11:31:36.683  1030  1389 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 11:31:36.683  6821  8138 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39859
08-31 11:31:36.683  1030  1389 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 11:31:36.683  6821  8138 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-31 11:31:36.685  1030  1389 D WifiStateMachine: enableVerboseLogging : level 2
08-31 11:31:36.685  1030  1389 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 11:31:36.686  1030  1389 D WifiNative-wlan0: SET device_name g3_global_com: returned true
,08-31 11:31:36.686  1030  1389 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 11:31:36.686  1030  1389 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-31 11:31:36.686  1030  1389 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 11:31:36.687  1030  1389 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 11:31:36.687  1030  1389 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 11:31:36.687  1030  1389 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 11:31:36.687  1030  1389 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,08-31 11:31:36.687  1030  1389 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 11:31:36.688  1030  1389 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,08-31 11:31:36.688  1030  1389 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 11:31:36.688  1030  1389 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 11:31:36.689  1030  1389 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 11:31:36.690  7753  7753 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:36.690  1030  1389 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:31:36.690  1030  1389 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 11:31:36.690  1939  1939 D WfdsService: Supplicant Connection state is changed : true
08-31 11:31:36.691  1939  2290 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 11:31:36.691  1939  2290 D WfdsService: Set the WFDS Monitor: true
08-31 11:31:36.691  1939  2290 D WfdsMonitor: WfdsMonitorThread create
08-31 11:31:36.691  1030  1389 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 11:31:36.691  1939  2290 D WfdsMonitor: WFDS Monitor is created and started
08-31 11:31:36.691  1030  1389 D WifiNative-HAL: Setting external_sim to 1
08-31 11:31:36.691  1939  2290 D WfdsService: WiFi: Supplicant connection re-established
08-31 11:31:36.691  1030  1389 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 11:31:36.691  1030  1389 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 11:31:36.691  1030  1389 I WifiNative-HAL: startHal
08-31 11:31:36.691  1030  1389 D wifi    : setting scan oui 0xaf72a340
08-31 11:31:36.692  1030  1389 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:31:36.692  1030  1389 I WifiNative-HAL: startHal
08-31 11:31:36.692  1030  1389 D wifi    : setting scan oui 0xaf72a340
08-31 11:31:36.692  1939  8141 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-31 11:31:36.692  1030  1389 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 11:31:36.692  1939  8141 E CtrlSupplicant: Succeed to open control connection
08-31 11:31:36.692  1939  8141 E CtrlSupplicant: Succeed to open monitor connection
08-31 11:31:36.693  1030  1389 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 11:31:36.693  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 11:31:36.693  8081  8081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 11:31:36.693  1939  8141 D WfdsMonitor: Supplicant connection established
08-31 11:31:36.693  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 11:31:36.694  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 11:31:36.694  8081  8081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 11:31:36.694  1939  2290 D WfdsService: Connected to the supplicant for wfds
08-31 11:31:36.694  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 11:31:36.694  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 11:31:36.694  8081  8081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 11:31:36.695  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 11:31:36.695  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 11:31:36.695  8081  8081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 11:31:36.695  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 11:31:36.695  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 11:31:36.695  8081  8081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 11:31:36.695  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 11:31:36.695  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 11:31:36.696  8081  8081 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 11:31:36.698  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 11:31:36.698  1030  1389 D Wifi,Native-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 11:31:36.698  8081  8081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 11:31:36.698  1030  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 11:31:36.699  1030  1389 E WifiNative: : [241,927,179 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 11:31:36.699  1030  1389 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 11:31:36.700  1030  1389 D WifiNative-wlan0: RECONNECT: returned true
08-31 11:31:36.701  1030  1389 D WifiNative-wlan0: doString: [STATUS]
08-31 11:31:36.701  1030  8120 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 11:31:36.701  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 11:31:36.701  1030  1389 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 11:31:36.701  1030  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:31:36.702  1030  1389 D WifiNative-wlan0: SET ps 1: returned true
,08-31 11:31:36.702  1030  1388 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.703  1030  2047 I ActivityManager: Killing 7217:com.android.chrome/u0a57 (adj 15): empty #17
08-31 11:31:36.704   304   890 D CommandListener: Setting iface cfg
,08-31 11:31:36.704   304   890 D CommandListener: Trying to bring up p2p0
08-31 11:31:36.704  1030  1388 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 11:31:36.705  1030  1388 D LGWifiP2pService: P2pEnablingState
08-31 11:31:36.705  1030  1388 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.705  1030  1388 D LGWifiP2pService: P2p socket connection successful
08-31 11:31:36.705  1030  1388 D LGWifiP2pService: P2pEnabledState
08-31 11:31:36.731  1030  1388 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 11:31:36.734  1030  1389 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 11:31:36.734  1030  1389 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
,08-31 11:31:36.735  1030  1389 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-31 11:31:36.735  1030  1389 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 11:31:36.735  1030  2009 W libprocessgroup: failed to open /acct/uid_10057/pid_7217/cgroup.procs: No such file or directory
08-31 11:31:36.736  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=241964  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 11:31:36.738  1030  1388 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 11:31:36.739  1030  1388 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 11:31:36.739  1030  1388 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 11:31:36.739  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-31 11:31:36.739  1939  1939 D WfdsService: WifiP2pState is changed : true
08-31 11:31:36.739  1030  1388 D WifiNative-p2p0: SET device_name G3: returned true
08-31 11:31:36.739  1030  1388 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 11:31:36.740  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 11:31:36.739  1030  1388 D LGWifiP2pService: before postfix = G3
08-31 11:31:36.740  1030  1388 D WifiServerServiceExt: postfix byte check : 2
08-31 11:31:36.740  1030  1030 D RttService: SCAN_AVAILABLE : 3
08-31 11:31:36.740  1030  1388 D LGWifiP2pService: after postfix = G3
08-31 11:31:36.740  1939  1939 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 11:31:36.740  1030  1388 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 11:31:36.740  1030  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.740  1939  2290 D WfdsService: Receive the WFDS_ENABLE Method
08-31 11:31:36.740  1939  2290 D WfdsService: Set the WFDS Monitor: true
08-31 11:31:36.740  1939  1939 D WfdsService: isConnected: false
08-31 11:31:36.740  1939  2290 D WfdsService: Connected to the supplicant for wfds
08-31 11:31:36.740  1939  2290 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 11:31:36.740  8081  8081 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 11:31:36.741  1030  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.741  1030  1555 I WifiNative-HAL: startHal
08-31 11:31:36.741  1939  2290 D WfdsService: selectPreferredScanChannel [36]
08-31 11:31:36.741  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=241969  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 11:31:36.741  1939  2290 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 11:31:36.741  1030  1388 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 11:31:36.741  1030  1388 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 11:31:36.741  1030  1389 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 11:31:36.742  1030  1388 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 11:31:36.742  1030  1389 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 11:31:36.742  1030  1388 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-31 11:31:36.742  1030  1389 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 11:31:36.742  1030  1389 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 11:31:36.742  8081  8081 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 11:31:36.742  1030  1388 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 11:31:36.742  1030  1388 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-31 11:31:36.743  1030  1388 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 11:31:36.743  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to ,android.provider.Settings.Global, returning read-only value.
08-31 11:31:36.743  1030  1389 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-31 11:31:36.743  1030  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf72a340
08-31 11:31:36.743  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:36.743  1030  1555 D wifi    : failed to get capabilities : -3
08-31 11:31:36.743  1030  1555 E WifiScanningService: could not get scan capabilities
08-31 11:31:36.743  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 11:31:36.743  1030  1388 D WifiNative-HAL: p2pGetDeviceAddress
08-31 11:31:36.743  1030  1388 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-31 11:31:36.744  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:36.744  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:36.745  1030  1388 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-31 11:31:36.745  1030  1388 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-31 11:31:36.745  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:36.745  1030  1388 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 11:31:36.745  1030  1388 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-31 11:31:36.746  1939  1939 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 11:31:36.746  1939  1939 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 11:31:36.746  1030  1388 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 11:31:36.746  1939  1939 D WfdsService: Update P2p Interface State: 3
08-31 11:31:36.746  1030  1388 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 11:31:36.746  1030  1389 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 11:31:36.746  1030  1388 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-31 11:31:36.746  1030  1388 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 11:31:36.747  1030  1389 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 11:31:36.747  1030  1389 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-31 11:31:36.757  8081  8081 E wpa_supplicant: disconnect_rssi_lvl: -100
08-31 11:31:36.758  1030  1388 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-31 11:31:36.758  1030  1388 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 11:31:36.758  1030  1388 D LGWifiP2pService: InactiveState
08-31 11:31:36.758  1030  1388 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.758  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.758  1030  1388 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-31 11:31:36.758  1030  1389 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 11:31:36.759  1030  1389 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 11:31:36.759  8081  8081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 11:31:36.759  1030  1389 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 11:31:36.759  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-31 11:31:36.759  8081  8081 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:36.760  8081  8081 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 11:31:36.760  8081  8081 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.761  8081  8081 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.761  1030  1388 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 11:31:36.761  1030  1388 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.761  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.761  1030  1388 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.761  1030  1388 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.762  1939  8141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:31:36.762  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.762  1939  8141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:31:36.762  1030  1388 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.762  1939  8141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:31:36.762  1030  8120 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:31:36.762  1030  1388 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.762  1030  8120 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:36.762  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.762  8081  8081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 11:31:36.762  1030  1388 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.762  1030  1388 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.762  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.762  1030  1388 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.762  1030  8120 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:36.762  1030  8120 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:36.762  1030  8120 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:31:36.762  1030  8120 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.763  8081  8081 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:36.763  1030  1030 E WifiServerServiceExt: No p2p device connected
08-31 11:31:36.763  1939  2290 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 11:31:36.764  8081  8081 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 11:31:36.764  8081  8081 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.764  1939  8141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER typ,e=WORLD]
08-31 11:31:36.764  1030  1389 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 11:31:36.765  1030  1389 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:31:36.765  8081  8081 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.765  1939  8141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:31:36.765  1030  8120 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.765  1030  1389 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:31:36.765  1030  8120 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.765  1030  8120 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:31:36.765  1030  8120 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.765  1030  8120 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.765  1030  8120 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.765  1030  8120 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:31:36.765  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:36.765  1030  1389 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:31:36.765  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-31 11:31:36.765  1030  8120 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:36.765  1030  8120 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:31:36.766  1030  8120 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:31:36.766  1030  8120 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.766  1030  1388 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.766  8081  8081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 11:31:36.766  1030  8120 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.766  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:36.766  8081  8081 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:31:36.766  1030  8120 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.766  1030  8120 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:31:36.766  1030  8120 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.766  1030  8120 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.766  1030  8120 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:31:36.766  1030  8120 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 11:31:36.766  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:31:36.766  1030  8120 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:31:36.766  1030  8120 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:31:36.767  1030  1389 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-31 11:31:36.767  1030  1389 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 11:31:36.767  1030  1389 D WifiNative-wlan0: BSS,_FLUSH 0: returned true
08-31 11:31:36.767  1030  1389 D WifiNative-wlan0: doBoolean: SCAN
08-31 11:31:36.768  1030  1389 D WifiNative-wlan0: SCAN: returned false
08-31 11:31:36.769  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=241997  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 11:31:36.771  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=241999  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 11:31:36.771  1030  1389 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:31:36.771  1030  1389 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:31:36.772  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:36.772  1030  1389 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:31:36.772  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:36.772  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 11:31:36.772  1030  1389 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:31:36.772  1030  1389 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:31:36.773  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:36.773  1030  1030 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 11:31:36.773  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:36.773  1030  1030 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 11:31:36.774  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:36.774  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:36.775  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:36.800  8121  8121 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:31:36.802  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:31:36.806  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:36.807  1030  1045 I ActivityManager: Killing 7249:com.lge.drmservice/u0a62 (adj 15): empty #17
08-31 11:31:36.838  1030  1648 W libprocessgroup: failed to open /acct/uid_10062/pid_7249/cgroup.procs: No such file or directory
,08-31 11:31:36.855  8121  8121 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:31:36.860  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:31:36.870  8099  8145 W FormManager: Network not available. Please check & try again.
08-31 11:31:36.870  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:36.878  8099  8146 V FormManager: Network unavailable.
08-31 11:31:36.883  8099  8146 V FormManager: Network unavailable.
,08-31 11:31:36.896  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-31 11:31:36.898  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-31 11:31:36.903  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:31:36.910  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:31:36.917  4340  8147 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 11:31:36.925  4340  8148 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:31:36.926  4340  8148 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:31:36.992  1030  1974 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8149 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 11:31:37.135  8149  8149 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 11:31:37.136  8149  8149 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-31 11:31:37.158  8149  8149 V [BNRBootReceiver]: Boot Receiver Return
,08-31 11:31:37.162  8149  8149 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-31 11:31:37.217  1030  1574 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8170 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 11:31:37.218  1030  1574 I ActivityManager: Killing 7282:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-31 11:31:37.257  1030  1046 W libprocessgroup: failed to open /acct/uid_10085/pid_7282/cgroup.procs: No such file or directory
,08-31 11:31:37.268  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-31 11:31:37.268  1030  8120 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-31 11:31:37.268  1030  8120 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-31 11:31:37.268  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-31 11:31:37.268  8081  8081 E wpa_supplicant: USIM:  scard_init function
08-31 11:31:37.268  1030  8120 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-31 11:31:37.269  8081  8081 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-31 11:31:37.269  1030  8120 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 11:31:37.269  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-31 11:31:37.272  1030  1389 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
,08-31 11:31:37.272  1030  1389 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-31 11:31:37.272  1030  1389 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-31 11:31:37.273  1030  1389 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-31 11:31:37.273  1030  1389 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-31 11:31:37.280  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=242508  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 11:31:37.285  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=242513  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-31 11:31:37.287  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:37.287  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:37.289  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.289  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.289  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 11:31:37.290  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:37.290  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-31 11:31:37.291  8170  8170 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:31:37.291  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:37.322  8170  8170 D PluginManager: init()
,08-31 11:31:37.391  8081  8081 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 11:31:37.392  1030  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-31 11:31:37.394  1030  1389 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:37.394  1030  1389 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:37.395  1030  1389 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:37.395  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:37.396  1030  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:31:37.397  1030  8120 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 11:31:37.397  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-31 11:31:37.397  1030  8120 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 11:31:37.397  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-31 11:31:37.398  1030  8120 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:31:37.398  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:31:37.400  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=242628  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 11:31:37.401  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=242629  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 11:31:37.403  1030  1389 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=242631
08-31 11:31:37.404  1030  1389 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=242632
08-31 11:31:37.405  1030  1389 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=242634
08-31 11:31:37.407  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=242635
,08-31 11:31:37.407  1030  1389 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=242635
08-31 11:31:37.409  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=242636  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 11:31:37.409  8081  8081 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:31:37.409  8081  8081 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:31:37.410  1030  8120 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:31:37.410  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:31:37.411  1030  8120 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 11:31:37.411  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:31:37.411  1030  8120 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:31:37.411  1030  8120 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 11:31:37.411  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:31:37.411  1030  8120 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:31:37.411  1030  8120 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:31:37.411  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:31:37.412  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=242640  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 11:31:37.414  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:37.414  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:37.415  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.415  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.415  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 11:31:37.417  1030  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=242645  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 11:31:37.418  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=242646  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 11:31:37.419  1030  1389 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=242647
08-31 11:31:37.419  1030  1389 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=242647
08-31 11:31:37.419  1030  1389 D WifiNative-wlan0: doString: [STATUS]
,08-31 11:31:37.421  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:37.423  1030  8120 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:31:37.423  1030  8120 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:31:37.424  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.424  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.424  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 11:31:37.425  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:37.425  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-31 11:31:37.426  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:37.426  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:37.427  1030  1389 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 11:31:37.428  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:37.428  1030  1389 I WifiServiceExtension: setVHTCapabilityType  : false
08-31 11:31:37.435  1030  1389 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 11:31:37.435  1030  1389 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-31 11:31:37.442  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.442  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.442  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 11:31:37.444  1030  1389 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-31 11:31:37.444  1030  1444 D ConnectivityService: Got NetworkAgent Messenger
08-31 11:31:37.444  1030  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:31:37.444  1030  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:31:37.444  1030  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 11:31:37.444  1030  1444 D ConnectivityService: NetworkAgent connected
08-31 11:31:37.445  1030  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:31:37.445  1030  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:31:37.448  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:31:37.448  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.449  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 11:31:37.449  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:37.449  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:37.451  1030  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 11:31:37.451  1030  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:31:37.451  1030  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:31:37.452  1030  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:31:37.452  1030  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:31:37.454  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:37.455  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:37.455  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:37.457  1030  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 11:31:37.458  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:37.458   304   890 D CommandListener: Setting iface cfg
08-31 11:31:37.461  1030  1389 E WifiStateMachine: Start Dhcp Watchdog 3
08-31 11:31:37.461  1030  8188 D DhcpStateMachine: StoppedState
08-31 11:31:37.461  1030  8188 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:37.461  1030  8188 D DhcpStateMachine: WaitBeforeStartState
08-31 11:31:37.461  1030  1389 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=242690  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-31 11:31:37.462  1030  1389 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=242690  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:31:37.462  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=242691  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:31:37.465  1030  1389 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=242693  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:31:37.465  1030  1389 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=242693  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:31:37.466  1030  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=242694  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:31:37.466  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:37.467  1030  1030 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-31 11:31:37.467  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:37.467  1030  1030 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-31 11:31:37.467  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14389] from screen [on:0 period:-537885061] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 11:31:37.468  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-537885060] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 11:31:37.468  1030  1389 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 11:31:37.475  1030  1444 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-31 11:31:37.476  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:37.476  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:31:37.477  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:37.478  1030  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:37.478  1030  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:37.478  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:37.479  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:37.479  1030  1444 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 11:31:37.479  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=124,0,0
08-31 11:31:37.480  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=124,0,0
08-31 11:31:37.480  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 11:31:37.481  8081  8081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-31 11:31:37.481  1030  1389 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 11:31:37.481  1030  1389 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 11:31:37.482  1030  1389 D WifiNative-wlan0: SET ps 0: returned true
08-31 11:31:37.482  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-31 11:31:37.482  8081  8081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 11:31:37.483  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 11:31:37.483  1030  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@38b5d7de target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:37.483  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@38b5d7de target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:37.484  1030  1389 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 11:31:37.484  1030  1389 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 11:31:37.484  1030  8188 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:37.484  1030  8188 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 11:31:37.484  1030  1389 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 11:31:37.485   304   890 D CommandListener: Setting iface cfg
08-31 11:31:37.485   304   890 D CommandListener: Trying to bring up wlan0
08-31 11:31:37.486  1030  1389 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-31 11:31:37.487  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:37.487  1030  1030 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 11:31:37.488  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:31:37.488  1030  1030 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 11:31:37.489  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:37.490  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:37.490  1030  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:37.490  1030  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:37.491  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:37.491  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:31:37.491  1030  1444 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 11:31:37.492  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_POST,_DHCP_ACTION 1 0 OK  v4
08-31 11:31:37.492  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 11:31:37.493  1030  1388 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:37.493  1030  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:37.493  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 11:31:37.493  8081  8081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:31:37.496  1030  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:31:37.496  1030  1389 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 11:31:37.496  8081  8081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 11:31:37.496  1030  1389 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 11:31:37.496  1030  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:31:37.512  1030  1389 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:31:37.512  1030  1444 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 11:31:37.513  1030  1389 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 11:31:37.513  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 11:31:37.513  1030  1389 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 11:31:37.514  1030  1444 D ConnectivityService: ignoring duplicate network state non-change
,08-31 11:31:37.519  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:37.519  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:37.520  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.520  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.520  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 11:31:37.521  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:37.522  1030  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 11:31:37.523  1030  1444 D ConnectivityService: Adding iface wlan0 to network 102
08-31 11:31:37.525  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.525  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.525  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 11:31:37.527  1030  1389 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 11:31:37.527  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-31 11:31:37.530  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.530  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.530  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 11:31:37.530  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 11:31:37.535  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-31 11:31:37.536  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.536  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:31:37.536  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 11:31:37.545  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 11:31:37.545  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:31:37.546  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:37.548  1030  1444 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 11:31:37.549  1030  1444 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-31 11:31:37.549  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:37.550  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 11:31:37.550  1030  1444 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-31 11:31:37.550  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:37.550   304   890 E Netd    : netlink response contains error (File exists)
08-31 11:31:37.551  1030  1444 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-31 11:31:37.552  1030  1444 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-31 11:31:37.552  1030  1444 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-31 11:31:37.552  1030  1444 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-31 11:31:37.552  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:31:37.552  1030  1444 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 11:31:37.552  1030  1444 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-31 11:31:37.552  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 11:31:37.552  1030  1444 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-31 11:31:37.553  1030  8187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:37.553  1030  8187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 11:31:37.553  1030  8187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:31:37.553  1030  8187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 11:31:37.553  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:37.555  1030  1444 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-31 11:31:37.555  1030  1444 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:31:37.555  1030  1444 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:37.555  1030  1444 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 11:31:37.555  1030  1444 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:37.555  1030  1444 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 11:31:37.555  1030  1444 D ConnectivityService: currentScore = 0, newScore = 20
08-31 11:31:37.555  1030  1444 D ConnectivityService:    accept,ing network in place of null
08-31 11:31:37.556  1030  1444 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:37.556  1848  1848 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:37.557   304  8196 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-31 11:31:37.557  1848  1848 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 11:31:37.557  1030  1389 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:37.557  1030  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:31:37.558  1030  1444 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 11:31:37.558  1030  1444 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-31 11:31:37.558  1030  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:31:37.559  1030  1030 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 11:31:37.560  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:31:37.560  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:31:37.560  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:31:37.561  1030  1444 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:31:37.561  1030  1444 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 11:31:37.561  1030  1444 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 11:31:37.562  1030  1444 D ConnectivityService: validation of new default Network = false
08-31 11:31:37.562  1030  1444 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 11:31:37.562  1030  1444 D DSQN    : enableDataServiceNotify 
08-31 11:31:37.562  1030  1444 D DSQN    : start dsqn bin
08-31 11:31:37.569  1030  1444 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-31 11:31:37.569  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:37.569  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:37.570  1030  1444 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:37.560  8199  8199 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:37.572  1600  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 11:31:37.560  8199  8199 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:37.585  8199  8199 E DSQN    : DSQN ssw
,08-31 11:31:37.590  1030  1387 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-31 11:31:37.601  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:31:37.602   304  8196 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-31 11:31:37.602  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:31:37.602  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:37.633   304  8196 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-31 11:31:37.664   304   889 D LGDataListener: argv[0]=dsqncommand
08-31 11:31:37.664   304   889 D LGDataListener: argv[1]=wlan0
08-31 11:31:37.664   304   889 D LGDataListener: argv[2]=1
08-31 11:31:37.664   304   889 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-31 11:31:37.665  1030  1092 D DSQN    : DSQM DsqnNotification wlan0  1
08-31 11:31:37.665  1030  1092 D DSQN    : start to monitor internet connection
08-31 11:31:37.682  6821  6899 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 876)
08-31 11:31:37.682  6821  6899 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 876)
08-31 11:31:37.685  6821  6899 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 881)
08-31 11:31:37.686  6821  6899 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-31 11:31:37.686  6821  6899 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 882)
08-31 11:31:37.688  1030  8188 D DhcpStateMachine: DHCPV4 request on wlan0
08-31 11:31:37.689  1030  8188 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-31 11:31:37.689  1030  8188 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-31 11:31:37.689  1030  8187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 09:31:37 GMT], X-Android-Received-Millis=[1472635897689], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472635897663]}
08-31 11:31:37.690  1030  8187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 11:31:37.690  1030  8187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-31 11:31:37.692  1030  1444 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-31 11:31:37.692  1030  1444 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-31 11:31:37.692  1030  1444 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:31:37.692  1030  1444 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:37.692  1030  1444 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 11:31:37.692  1030  1444 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-31 11:31:37.692  1030  1444 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-31 11:31:37.692  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:37.692  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:37.693  1030  1444 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:37.693  1030  1444 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:37.693  1030  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-31 11:31:37.680  8205  8205 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:37.680  8205  8205 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:31:37.698  1030  1389 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:37.698  1030  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:31:37.698  1848  1848 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:37.698  1848  1848 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 11:31:37.698  1600  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 11:31:37.704  8205  8205 I dhcpcd  : version 5.5.6 starting
08-31 11:31:37.706  8205  8205 E dhcpcd  : get_duid: m
08-31 11:31:37.706  8205  8205 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 11:31:37.706  8205  8205 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-31 11:31:37.711  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:31:37.711  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ecf58f added. We now have 2 listener(s)
08-31 11:31:37.712  1030  1937 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:37.718  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:31:37.718  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-31 11:31:37.718  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:31:37.718  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:31:37.719  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:37.719  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b50501c added. We now have 9 listener(s)
08-31 11:31:37.719  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:31:37.719  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:37.719  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:31:37.719  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:31:37.721  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:31:37.727  6821  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:31:37.727  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:37.727  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:37.727  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:37.727  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:37.727  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:37.727  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:31:37.727  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:31:37.728  6821  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:37.728  6821  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:31:37.728  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:31:37.729  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21b5c9fa added. We now have 3 listener(s)
08-31 11:31:37.729  1030  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:37.730  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:37.731  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:31:37.732  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:31:37.732  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:31:37.732  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:37.732  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f4d5bab added. We now have 10 listener(s)
08-31 11:31:37.732  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:31:37.732  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:37.732  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:37.732  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:37.732  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:37.732  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.732  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:31:37.732  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:31:37.732  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Con,nectionManager@8ecf58f removed from the list
08-31 11:31:37.732  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:37.732  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b50501c removed from the list
08-31 11:31:37.733  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:37.733  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:31:37.733  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.733  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.734  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.734  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:37.734  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:37.734  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:37.734  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b50501c not in the list
08-31 11:31:37.734  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.734  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.735  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:37.735  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:37.735  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:37.735  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f4d5bab removed from the list
08-31 11:31:37.735  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:37.735  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.735  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.735  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:31:37.735  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21b5c9fa removed from the list
08-31 11:31:37.736  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:31:37.736  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7205208 added. We now have 2 listener(s)
08-31 11:31:37.737  1030  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:37.739  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:31:37.739  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:31:37.739  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:31:37.739  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:37.739  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bf18da1 added. We now have 9 listener(s)
08-31 11:31:37.739  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listen,ers is now 1
08-31 11:31:37.740  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:31:37.742  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:37.745  6821  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:31:37.745  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:37.745  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:37.745  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:37.745  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:37.745  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:37.745  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:31:37.745  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:31:37.746  6821  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:37.746  6821  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:31:37.748  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:37.750  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:37.750  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:31:37.750  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b040787 added. We now have 3 listener(s)
08-31 11:31:37.750  1030  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:37.752  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:31:37.752  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:31:37.752  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:31:37.752  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:37.753  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@346c86b4 added. We now have 10 listener(s)
08-31 11:31:37.753  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:31:37.753  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:31:37.753  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:31:37.753  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:31:37.753  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:37.753  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:31:37.756  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:31:37.756  1030  2048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:37.760  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:31:37.760  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:31:37.763  8205  8205 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 11:31:37.763  8205  8205 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 11:31:37.763  8205  8205 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 11:31:37.763  8205  8205 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-31 11:31:37.763  8205  8205 D dhcpcd  : wlan0: sending REQUEST (xid 0xd3f0e86a), next in 4.43 seconds
08-31 11:31:37.763  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:31:37.764  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:31:37.765  6821  6899 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 11:31:37.765  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:37.765  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:37.767  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:37.767  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:37.767  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:37.767  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:37.767  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.767  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:31:37.767  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:31:37.768  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7205208 removed from the list
08-31 11:31:37.768  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:37.768  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bf18da1 removed from the list
08-31 11:31:37.768  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:37.768  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.768  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.768  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.769  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:37.769  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:37.769  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:37.769  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bf18da1 not in the list
08-31 11:31:37.769  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bl,uetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.769  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.770  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:37.770  6821  6899 D BluetoothLeScanner: could not find callback wrapper
08-31 11:31:37.770  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:37.770  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:37.770  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:37.770  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@346c86b4 removed from the list
08-31 11:31:37.770  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:37.770  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.770  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.770  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:31:37.770  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b040787 removed from the list
08-31 11:31:37.771  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:31:37.771  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@308f9523 added. We now have 2 listener(s)
08-31 11:31:37.771  1030  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:37.774  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:31:37.774  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:31:37.774  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:31:37.774  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:37.774  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28a55a20 added. We now have 9 listener(s)
08-31 11:31:37.774  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:31:37.774  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:31:37.777  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:37.780  6821  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:31:37.780  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:37.780  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:37.780  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:37.780  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:37.780  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:37.780  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:31:37.780  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:31:37.781  6821  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:37.782  6821  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:31:37.782  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:31:37.782  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@254d9e added. We now have 3 listener(s)
08-31 11:31:37.783  1030  1865 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:37.783  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:37.785  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:37.785  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:31:37.785  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:31:37.785  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:31:37.785  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:37.785  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13bc607f added. We now have 10 listener(s)
08-31 11:31:37.785  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:31:37.785  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:31:37.786  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:31:37.786  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:31:37.786  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:31:37.786  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:37.786  6821  6899, I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:31:37.790  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:31:37.790  1030  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:37.794  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:31:37.794  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:31:37.795  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:31:37.796  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:31:37.797  8205  8205 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-31 11:31:37.797  6821  6899 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 11:31:37.798  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:37.798  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:37.798  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:37.798  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:37.798  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.798  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:31:37.798  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:31:37.798  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@308f9523 removed from the list
08-31 11:31:37.798  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:37.798  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28a55a20 removed from the list
08-31 11:31:37.798  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:31:37.798  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.799  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.799  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.799  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:37.799  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:37.800  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:37.800  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28a55a20 not in the list
08-31 11:31:37.800  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.800  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.801  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:37.801  6821  6899 D BluetoothLeScanner: could not find callback wrapper
08-31 11:31:37.801  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:37.801  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:37.801  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:37.801  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13bc607f removed from the list
08-31 11:31:37.801  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:37.801  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.801  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.801  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:31:37.801  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@254d9e removed from the list
08-31 11:31:37.802  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:31:37.802  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1014a5aa added. We now have 2 listener(s)
08-31 11:31:37.802  1030  2047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:37.804  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:31:37.805  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:31:37.805  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:31:37.805  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:37.805  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorl,ib.DiscoveryManager@2ec0859b added. We now have 9 listener(s)
08-31 11:31:37.805  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:31:37.805  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:31:37.808  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:37.811  6821  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:31:37.811  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:37.811  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:37.811  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:37.811  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:37.811  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:37.811  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:31:37.811  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:31:37.812  6821  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:37.813  6821  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:31:37.813  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:31:37.813  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13482111 added. We now have 3 listener(s)
08-31 11:31:37.813  1030  2047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:37.815  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:37.817  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:37.817  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:31:37.818  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:31:37.818  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:31:37.818  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:37.818  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13ef7276 added. We now have 10 listener(s)
08-31 11:31:37.818  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:31:37.818  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:31:37.818  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:31:37.818  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:31:37.818  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:37.818  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:31:37.821  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:31:37.821  1030  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:37.825  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:31:37.826  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:31:37.827  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:31:37.827  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:31:37.829  6821  6899 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 11:31:37.830  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:37.830  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:37.830  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:37.831  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:37.831  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.831  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:31:37.831  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:31:37.831  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1014a5aa removed from the list
08-31 11:31:37.831  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:37.831  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ec0859b removed from the list
08-31 11:31:37.831  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:37.831  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.831  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.831  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.832  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:37.832  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:37.832  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:37.832  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ec0859b not in the list
08-31 11:31:37.832  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.832  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.833  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:37.833  6821  6899 D BluetoothLeScanner: could not find callback wrapper
08-31 11:31:37.833  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:31:37.833  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:37.833  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:37.834  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13ef7276 removed from the list
08-31 11:31:37.834  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:37.834  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08,-31 11:31:37.834  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.834  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:31:37.834  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13482111 removed from the list
08-31 11:31:37.834  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:31:37.834  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3afcbd4d added. We now have 2 listener(s)
08-31 11:31:37.835  1030  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:37.837  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:31:37.837  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:31:37.837  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:31:37.837  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:37.837  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15d84002 added. We now have 9 listener(s)
08-31 11:31:37.837  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:31:37.838  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:31:37.841  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:31:37.844  6821  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:31:37.844  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:31:37.844  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:31:37.844  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:31:37.844  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:31:37.844  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:37.844  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:31:37.844  6821  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:31:37.845  6821  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:31:37.845  6821  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:31:37.846  8205  8205 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 11:31:37.847  8205  8205 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-31 11:31:37.847  8205  8205 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 11:31:37.847  8205  8205 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-31 11:31:37.847  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:37.847  8205  8205 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 11:31:37.848  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:31:37.848  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25538b50 added. We now have 3 listener(s)
,08-31 11:31:37.848  8205  8205 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 11:31:37.848  1030  1989 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:31:37.848  8205  8205 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 11:31:37.848  8205  8205 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-31 11:31:37.849  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:31:37.852  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:31:37.852  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:31:37.852  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:31:37.852  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:31:37.853  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28e4e149 added. We now have 10 listener(s)
08-31 11:31:37.853  6821  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:31:37.853  6821  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:31:37.853  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:37.853  6821  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:31:37.854  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:37.854  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.854  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:31:37.854  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:31:37.854  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3afcbd4d removed from the list
08-31 11:31:37.854  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:37.854  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15d84002 removed from the list
08-31 11:31:37.854  6821  6899 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:31:37.854  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.854  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.855  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:31:37.856  8170  8170 W ExternalStrings: load override strings
08-31 11:31:37.856  8170  8170 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:31:37.856  8170  8170 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:31:37.856  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:37.856  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:37.856  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:37.856  6821  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15d84002 not in the list
08-31 11:31:37.856  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.856  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.857  8170  8170 D StatusProvider: onCreate
08-31 11:31:37.862  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:31:37.862  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:31:37.862  6821  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:31:37.862  6821  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28e4e149 removed from the list
08-31 11:31:37.862  6821  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:31:37.862  6821  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:31:37.862  6821  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:31:37.862  6821  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:31:37.863  6821  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionMana,gerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25538b50 removed from the list
08-31 11:31:37.863  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 11:31:37.863  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 11:31:37.863  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 11:31:37.863  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:31:37.864  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 11:31:37.864  6821  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:31:37.869  7821  7939 D UEI.SmartControl: Internal timer expired: 3
08-31 11:31:37.870  7821  7939 D UEI.SmartControl: unbind internal service
,08-31 11:31:37.871  6821  8215 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 889, name: My test thread name)
08-31 11:31:37.872  6821  8215 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 889, thread name: My test thread name)
08-31 11:31:37.872  7821  7821 D UEI.SmartControl: Service.onUnbind: IControl
08-31 11:31:37.872  6821  8215 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 889, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 11:31:37.875  6821  8216 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 891, name: My test thread name)
08-31 11:31:37.875  6821  8216 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 891, thread name: My test thread name)
08-31 11:31:37.875  6821  8216 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 891, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 11:31:37.877  7821  7821 D UEI.SmartControl: Service.onDestroy
08-31 11:31:37.877  7821  7821 D UEI.SmartControl: Lock is in USE false
08-31 11:31:37.877  7821  7821 D UEI.SmartControl: unbind internal service
08-31 11:31:37.877  7821  7821 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@23de5dfd
08-31 11:31:37.877  7821  7821 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-31 11:31:37.877  7821  7821 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-31 11:31:37.877  7821  7821 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-31 11:31:37.877  7821  7821 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-31 11:31:37.877  7821  7821 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-31 11:31:37.878  7821  7821 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-31 11:31:37.878  7821  7821 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-31 11:31:37.878  7821  7821 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-31 11:31:37.878  7821  7821 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:31:37.878  7821  7821 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:31:37.878  7821  7821 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:31:37.878  7821  7821 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:31:37.878  7821  7821 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:31:37.878  7821  7821 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:31:37.878  7821  7821 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:31:37.878  7821  7821 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@23de5dfd
08-31 11:31:37.878  7821  7821 D serial_port: close(fd = 24)
08-31 11:31:37.878  6821  6899 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-31 11:31:37.878  6821  6899 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 11:31:37.878  6821  6899 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 11:31:37.878  6821  6899 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-31 11:31:37.879  6821  6899 D com.test.thalitest.ThaliTestRunner: Total duration: 23032 ms
08-31 11:31:37.880  6821  6899 I jxcore-log: Total number of executed tests:  80
08-31 11:31:37.880  6821  6899 I jxcore-log: 
08-31 11:31:37.881  6821  6899 I jxcore-log: Number of passed tests:  80
08-31 11:31:37.881  6821  6899 I jxcore-log: 
,08-31 11:31:37.881  6821  6899 I jxcore-log: Number of failed tests:  0
08-31 11:31:37.881  6821  6899 I jxcore-log: 
08-31 11:31:37.882  6821  6899 I jxcore-log: Number of ignored tests:  0
08-31 11:31:37.882  6821  6899 I jxcore-log: 
08-31 11:31:37.882  6821  6899 I jxcore-log: Total duration:  23032
08-31 11:31:37.882  6821  6899 I jxcore-log: 
08-31 11:31:37.883  7821  7821 I UEI.SmartControl: Serial port is closed.
08-31 11:31:37.883  7821  7821 I UEI.SmartControl: Serial port is closed.
08-31 11:31:37.883  7821  7821 D UEI.SmartControl: Blaster closed
08-31 11:31:37.883  7821  7821 D UEI.SmartControl: Shut down QS...
08-31 11:31:37.883  7821  7821 D UEI.SmartControl: Stopping QS lib
08-31 11:31:37.883  7821  7821 D UEI.SmartControl: QS lib stop result = true
08-31 11:31:37.883  7821  7821 D UEI.SmartControl: Stopped QS lib
08-31 11:31:37.883  7821  7821 D UEI.SmartControl: QS shutdown complete
08-31 11:31:37.884  6821  6899 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 11:31:37.884  6821  6899 I jxcore-log: 
08-31 11:31:37.886  6821  6899 I jxcore-log: My device name is: LGE-LG-D855
08-31 11:31:37.886  6821  6899 I jxcore-log: 
08-31 11:31:37.892  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:31:37.892  6821  6899 I jxcore-log: 
,08-31 11:31:37.894  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:31:37.894  6821  6899 I jxcore-log: 
08-31 11:31:37.896  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:31:37.896  6821  6899 I jxcore-log: 
08-31 11:31:37.901  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:31:37.901  6821  6899 I jxcore-log: 
08-31 11:31:37.905  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:31:37.905  6821  6899 I jxcore-log: 
,08-31 11:31:37.910  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:31:37.910  6821  6899 I jxcore-log: 
08-31 11:31:37.913  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:31:37.913  6821  6899 I jxcore-log: 
08-31 11:31:37.914  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:31:37.914  6821  6899 I jxcore-log: 
08-31 11:31:37.915  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:31:37.915  6821  6899 I jxcore-log: 
08-31 11:31:37.917  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:31:37.917  6821  6899 I jxcore-log: 
08-31 11:31:37.918  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 11:31:37.918  6821  6899 I jxcore-log: 
,08-31 11:31:37.920  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:31:37.920  6821  6899 I jxcore-log: 
08-31 11:31:37.921  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:31:37.921  6821  6899 I jxcore-log: 
08-31 11:31:37.922  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:31:37.922  6821  6899 I jxcore-log: 
08-31 11:31:37.923  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:31:37.923  6821  6899 I jxcore-log: 
08-31 11:31:37.923  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:31:37.923  6821  6899 I jxcore-log: 
08-31 11:31:37.924  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:31:37.924  6821  6899 I jxcore-log: 
08-31 11:31:37.925  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:31:37.925  6821  6899 I jxcore-log: 
08-31 11:31:37.926  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:31:37.926  6821  6899 I jxcore-log: 
08-31 11:31:37.927  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:31:37.927  6821  6899 I jxcore-log: 
08-31 11:31:37.927  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:31:37.927  6821  6899 I jxcore-log: 
08-31 11:31:37.928  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:31:37.928  6821  6899 I jxcore-log: 
08-31 11:31:37.929  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:31:37.929  6821  6899 I jxcore-log: 
08-31 11:31:37.930  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:31:37.930  6821  6899 I jxcore-log: 
08-31 11:31:37.931  8170  8170 V Signer  : override build config not found
08-31 11:31:37.931  8170  8170 D Signer  : value of property debug is false
08-31 11:31:37.931  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:31:37.931  6821  6899 I jxcore-log: 
08-31 11:31:37.932  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:31:37.932  6821  6899 I jxcore-log: 
08-31 11:31:37.933  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:31:37.933  6821  6899 I jxcore-log: 
08-31 11:31:37.933  6821  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidNa,me":"f4:f2:6d:22:99:3e"}
08-31 11:31:37.933  6821  6899 I jxcore-log: 
,08-31 11:31:37.965  8170  8170 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-31 11:31:37.965  8170  8170 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-31 11:31:37.965  8170  8170 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-31 11:31:37.965  8170  8170 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-31 11:31:37.965  8170  8170 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-31 11:31:37.966  8170  8170 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-31 11:31:37.966  8170  8170 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-31 11:31:37.966  8170  8170 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-31 11:31:37.966  8170  8170 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-31 11:31:37.966  8170  8170 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
,08-31 11:31:37.968  8170  8170 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-31 11:31:37.968  8170  8170 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-31 11:31:37.968  8170  8170 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-31 11:31:37.979  8170  8170 V LGMDMManager: Create singleton instance
08-31 11:31:38.025  8170  8170 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-31 11:31:38.062  8170  8170 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:38.065  8170  8238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 11:31:38.077  8231  8231 D AndroidRuntime: 
08-31 11:31:38.077  8231  8231 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 11:31:38.079  8231  8231 D AndroidRuntime: CheckJNI is OFF
08-31 11:31:38.084  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:38.092  1030  8188 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-31 11:31:38.094  1030  8188 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-31 11:31:38.094  1030  8188 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 11:31:38.094  1030  8188 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-31 11:31:38.094  1030  8188 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-31 11:31:38.094  1030  8188 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 11:31:38.094  1030  8188 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-31 11:31:38.094  1030  8188 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 11:31:38.094  1030  8188 D DhcpStateMachine: RunningState
,08-31 11:31:38.097  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:38.131  1030  1956 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8251 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-31 11:31:38.133  1030  1956 I ActivityManager: Killing 7341:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-31 11:31:38.180  8231  8231 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 11:31:38.230  8170  8237 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-31 11:31:38.345  1030  1956 E libprocessgroup: failed to kill 1 processes for processgroup 7341
,08-31 11:31:38.348  1030  1089 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-31 11:31:38.349  1030  1089 I ActivityManager: Killing 6821:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-31 11:31:38.392  1030  1937 I WindowState: WIN DEATH: Window{1289dbf6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 11:31:38.394  1030  1443 D WifiService: Client connection lost with reason: 4
,08-31 11:31:38.396  1030  1937 D InputDispatcher: Window went away: Window{1289dbf6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 11:31:38.580  1030  1089 I ActivityManager:   Force finishing activity ActivityRecord{12d55cb3 u0 com.test.thalitest/.MainActivity t6}
,08-31 11:31:38.626   335   349 E GBMv2   : DFP En is all cleared set to be enabled
,08-31 11:31:38.636  1030  1101 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-31 11:31:38.638  1030  1101 I ActivityManager:   Force finishing activity ActivityRecord{12d55cb3 u0 com.test.thalitest/.MainActivity t6 f}
08-31 11:31:38.638  1030  1101 W ActivityManager: Duplicate finish request for ActivityRecord{12d55cb3 u0 com.test.thalitest/.MainActivity t6 f}
,08-31 11:31:38.708  4603  4603 I art     : Explicit concurrent mark sweep GC freed 8177(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 703us total 56.246ms
,08-31 11:31:38.718  1030  1974 W ActivityManager: Spurious death for ProcessRecord{f170a43 6821:com.test.thalitest/u0a118}, curProc for 6821: null
08-31 11:31:38.719  2030  2030 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-31 11:31:38.721  2030  2030 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-31 11:31:38.725  1939  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,08-31 11:31:38.729  1939  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{19429655 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 11:31:38.730  1939  3998 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-31 11:31:38.730  1939  3998 D SplitWindowPolicy: topRunningActivity=ActivityInfo{25e6186a co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 11:31:38.732  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-31 11:31:38.735  2030  2124 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-31 11:31:38.753  1600  1600 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-31 11:31:38.778  1030  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 11:31:38.781  1993  1993 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-31 11:31:38.781  3846  3846 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-31 11:31:38.791  2478  2646 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 11:31:38.803  7726  7726 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
,08-31 11:31:38.803  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 11:31:38.804  4498  4498 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-31 11:31:38.805  4498  4498 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-31 11:31:38.805  4498  4498 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-31 11:31:38.805  4498  4498 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-31 11:31:38.805  4498  4498 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:31:38.806  4498  4498 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:31:38.806  4498  4498 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:31:38.806  4498  4498 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:31:38.806  4498  4498 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:31:38.806  4498  4498 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:31:38.806  4498  4498 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:31:38.806  4498  4498 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:31:38.833  1030  1088 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-31 11:31:38.844  1030  1883 V SIM_STK : Menu title from STK is T-Mobile
08-31 11:31:38.856  1902  1902 D ActionManagerService: notifyUserLog: 1000003
,08-31 11:31:38.858  2030  2030 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-31 11:31:38.859  1030  1030 D administrator: Handling package changes for user 0
08-31 11:31:38.862  3846  4496 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-31 11:31:38.864  1600  1600 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-31 11:31:38.865  2030  2030 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-31 11:31:38.872  8251  8251 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 11:31:38.878  2030  2030 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-31 11:31:38.883  2030  2030 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-31 11:31:38.885  1600  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 11:31:38.885  1600  1652 D KeyguardModel: createShortcutInfo...
08-31 11:31:38.890  1902  1902 D ActionManagerService: notifyUserLog: 1000004
08-31 11:31:38.891  3846  4496 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,08-31 11:31:38.895  2030  2030 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-31 11:31:38.895  1600  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
,08-31 11:31:38.895  1600  1652 D KeyguardModel: createShortcutInfo...
08-31 11:31:38.898  1600  1600 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-31 11:31:38.898  1600  1600 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-31 11:31:38.898  3846  4492 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 11:31:38.904  1600  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 11:31:38.904  1600  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:31:38.904  1600  1652 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-31 11:31:38.905  1600  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 11:31:38.907  1600  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:31:38.907  1600  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-31 11:31:38.916  1600  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 11:31:38.916  1600  1652 D KeyguardModel: createShortcutInfo...
08-31 11:31:38.921  1600  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 11:31:38.921  1600  1652 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:31:38.923  1600  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:31:38.923  1600  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-31 11:31:38.929  8251  8251 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-31 11:31:38.937  1600  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 11:31:38.937  1600  1652 D KeyguardModel: createShortcutInfo...
,08-31 11:31:38.940  2030  2030 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-31 11:31:38.940  2030  2030 I GBoardWebViewUtils: , create_time: 1430832262123
08-31 11:31:38.940  2030  2030 I GBoardWebViewUtils: , expire_time: 0
08-31 11:31:38.940  2030  2030 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-31 11:31:38.940  2030  2030 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-31 11:31:38.940  2030  2030 I GBoardWebViewUtils: , display: false
08-31 11:31:38.940  2030  2030 I GBoardWebViewUtils: , animation: false }
08-31 11:31:38.941  2030  2030 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-31 11:31:38.941  2030  2030 I GBoardWebViewUtils: , create_time: 1430832262287
08-31 11:31:38.941  2030  2030 I GBoardWebViewUtils: , expire_time: 0
08-31 11:31:38.941  2030  2030 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-31 11:31:38.941  2030  2030 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 11:31:38.941  2030  2030 I GBoardWebViewUtils: , display: false
08-31 11:31:38.941  2030  2030 I GBoardWebViewUtils: , animation: false }
08-31 11:31:38.941  2030  2030 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-31 11:31:38.941  2030  2030 I GBoardWebViewUtils: , create_time: 1472216588858
08-31 11:31:38.941  2030  2030 I GBoardWebViewUtils: , expire_time: 0
08-31 11:31:38.941  2030  2030 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-31 11:31:38.941  2030  2030 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 11:31:38.941  2030  2030 I GBoardWebViewUtils: , display: false
08-31 11:31:38.941  2030  2030 I GBoardWebViewUtils: , animation: false }
08-31 11:31:38.941  1866  1866 D SplitUIManager: split_name #11 / not available #0
08-31 11:31:38.942  1866  1866 D SplitUIService: removed split : 
08-31 11:31:38.949  1600  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:31:38.950  1600  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 11:31:38.950  1600  1652 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-31 11:31:38.950  1600  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-31 11:31:38.954  1600  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:31:38.954  1600  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 11:31:38.955  2030  8303 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-31 11:31:38.958  1600  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 11:31:38.958  1600  1652 D KeyguardModel: createShortcutInfo...
08-31 11:31:38.959  1030  1989 V SIM_STK : Menu title from STK is T-Mobile
08-31 11:31:38.959  1030  1989 V SIM_STK : Menu title from STK is T-Mobile
08-31 11:31:38.962  1600  1600 D KeyguardModel: handleShortcutListChanged...
08-31 11:31:38.962  1600  1600 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-31 11:31:38.965  1600  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 11:31:38.965  1600  1652 D KeyguardModel: createShortcutInfo...
08-31 11:31:38.975  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 11:31:38.975  2030  2030 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-31 11:31:39.006  1600  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 11:31:39.006  1600  1652 D KeyguardModel: createShortcutInfo...
08-31 11:31:39.010  1600  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:31:39.010  1600  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 11:31:39.013  1600  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 11:31:39.013  1600  1652 D KeyguardModel: createShortcutInfo...
,08-31 11:31:39.022  1600  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:31:39.022  1600  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 11:31:39.023  1866  1866 D SplitUIManager: split_name #11 / not available #0
08-31 11:31:39.023  1866  1866 I SplitUIService: split app #11
08-31 11:31:39.025  1600  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 11:31:39.025  1600  1652 D KeyguardModel: createShortcutInfo...
08-31 11:31:39.030  8251  8251 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-31 11:31:39.031  8251  8251 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-31 11:31:39.031  8251  8251 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-31 11:31:39.031  8251  8251 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-31 11:31:39.031  8251  8251 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-31 11:31:39.032  1030  1865 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-31 11:31:39.032  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 11:31:39.032  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 11:31:39.032  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 11:31:39.032  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 11:31:39.032  8251  8251 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-31 11:31:39.032  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 11:31:39.032  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:31:39.033  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 11:31:39.033  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 11:31:39.033  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 11:31:39.033  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:31:39.033  7726  7726 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 11:31:39.033  1600  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:31:39.033  1600  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 11:31:39.033  1600  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 11:31:39.034  1600  1652 D KeyguardModel: createShortcutInfo...
,08-31 11:31:39.037  1030  1389 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:39.038  1030  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:39.038  1030  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:39.038  8251  8251 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-31 11:31:39.038  1030  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:39.039  1030  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:39.040  2030  2044 I art     : Background sticky concurrent mark sweep GC freed 2772(151KB) AllocSpace objects, 3(176KB) LOS objects, 0% free, 80MB/80MB, paused 17.632ms total 22.638ms
08-31 11:31:39.040  2030  2030 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-31 11:31:39.041  1030  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:31:39.042  1030  1444 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-31 11:31:39.042  1030  1444 D ConnectivityService: identical MTU - not setting
08-31 11:31:39.042  1030  1444 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 11:31:39.042  1030  1444 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-31 11:31:39.042  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:31:39.042  1030  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:39.042  1030  1444 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:31:39.043  1600  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-31 11:31:39.045  1030  1574 V SIM_STK : Menu title from STK is T-Mobile
08-31 11:31:39.052  1600  1600 D KeyguardModel: handleShortcutListChanged...
08-31 11:31:39.052  1600  1600 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-31 11:31:39.057  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:39.060  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:39.075  8251  8251 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 11:31:39.078  8251  8251 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-31 11:31:39.079  8251  8251 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-31 11:31:39.082  8170  8170 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:39.084  8170  8238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:31:39.087  1030  1030 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-31 11:31:39.087  1030  1030 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 11:31:39.087  1030  1030 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 11:31:39.089  1030  1576 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,08-31 11:31:39.092  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:31:39.094  8170  8237 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:31:39.094  8170  8237 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:31:39.096  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:39.104  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:39.104  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:39.105  8251  8251 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 11:31:39.109  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-31 11:31:39.110  6950  6950 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 11:31:39.114  8170  8170 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:39.116  8170  8238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:31:39.120  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:31:39.123  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:39.127  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:39.127  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:39.128  8251  8251 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 11:31:39.129  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:31:39.129  6950  6950 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:31:39.129  6950  6950 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:31:39.129  6950  6950 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 11:31:39.134  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 11:31:39.135  6950  6950 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:31:39.135  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 11:31:39.135  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:31:39.135  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 11:31:39.138  6950  6950 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:31:39.138  6950  6950 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 11:31:39.138  6950  6950 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:31:39.141  8170  8170 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:39.141  8170  8238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 11:31:39.147  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:31:39.150  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:39.155  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:39.156  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:31:39.156  8251  8251 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:31:39.158  8170  8170 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:39.159  8170  8238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:31:39.166  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-31 11:31:39.167  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:31:39.169  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:31:39.171  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-31 11:31:39.173  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-31 11:31:39.174  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-31 11:31:39.175  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-31 11:31:39.180  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:39.184  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:39.184  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:39.185  8251  8251 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:31:39.188  1030  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{10511a1a u0 com.lge.launcher2/.Launcher t5} time:244431
08-31 11:31:39.191  8170  8170 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:39.194  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-31 11:31:39.194  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 11:31:39.194  8170  8238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:31:39.198  2030  2204 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-31 11:31:39.198  2030  2204 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-31 11:31:39.200  8170  8237 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-31 11:31:39.202  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:31:39.205  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:39.208  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:31:39.208  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:39.208  8251  8251 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:31:39.211  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-31 11:31:39.212  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 11:31:39.212  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:31:39.216  8170  8170 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:39.217  8170  8238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:31:39.220  2030  2030 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-31 11:31:39.220  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:39.221  2576  2576 D [Concierge]Service: onStartCommand(). Type : 8
08-31 11:31:39.221  2576  2576 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-31 11:31:39.222  2576  2576 D [Concierge]Service: Update widget ID : 11
08-31 11:31:39.223  2030  2030 D [Concierge]WidgetView: change position of spinner
08-31 11:31:39.224  1030  1101 I art     : Explicit concurrent mark sweep GC freed 84659(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 4.391ms total 296.507ms
08-31 11:31:39.225  8170  8237 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-31 11:31:39.225  2030  2030 I [Concierge]WidgetView: initWebView(). Time : 1472635899225
08-31 11:31:39.226  2576  2576 D [Concierge]Service: onStartCommand(). Type : 0
08-31 11:31:39.226  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:39.230  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:39.230  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:39.231  8251  8251 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:31:39.234  8170  8237 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-31 11:31:39.235  8170  8237 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-31 11:31:39.235  8170  8237 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-31 11:31:39.236  8170  8237 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-31 11:31:39.236  8170  8237 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-31 11:31:39.243  8170  8237 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-31 11:31:39.243  8170  8238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:31:39.244  8170  8170 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:31:39.248  8170  8237 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-31 11:31:39.257  8231  8231 D AndroidRuntime: Shutting down VM
,08-31 11:31:39.278  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:39.282  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:39.326  1030  1088 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:31:39.330  1030  1088 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-31 11:31:39.331  1030  1101 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8317 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-31 11:31:39.335  2030  2030 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 341437889
08-31 11:31:39.337  2030  2030 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-31 11:31:39.339  2030  2030 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-31 11:31:39.349  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:39.349  2030  2030 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1f0ec20d
08-31 11:31:39.349  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:39.350  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-31 11:31:39.352  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,08-31 11:31:39.352  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:31:39.356  8251  8251 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:31:39.358  8170  8170 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:39.358  8170  8238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:31:39.360  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-31 11:31:39.361  2030  2030 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-31 11:31:39.361  2030  2030 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 11:31:39.362  2030  2030 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472635682205, New one : 1472635899225
08-31 11:31:39.362  2030  2030 D [Concierge]WidgetView: Unregister all receivers
08-31 11:31:39.362  2030  2030 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-31 11:31:39.364  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:31:39.370  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-31 11:31:39.371  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:31:39.373  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-31 11:31:39.374  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-31 11:31:39.376  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-31 11:31:39.376  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:39.377  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-31 11:31:39.378  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-31 11:31:39.379  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:31:39.379  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 11:31:39.391  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:39.391  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:39.391  8251  8251 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:31:39.394  8170  8170 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:31:39.396  8170  8238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:31:39.397  8121  8121 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 11:31:39.401  8121  8121 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:31:39.403  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:39.418  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:31:39.421  1030  1883 I ActivityManager: Killing 7324:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-31 11:31:39.423  2030  2030 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-31 11:31:39.433  2030  2030 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-31 11:31:39.433  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-31 11:31:39.435  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 11:31:39.454  2030  2030 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@26463efe time:244697
,08-31 11:31:39.478  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:31:39.478  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:39.479  1030  2047 W libprocessgroup: failed to open /acct/uid_10005/pid_7324/cgroup.procs: No such file or directory
08-31 11:31:39.479  8251  8251 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-31 11:31:39.481  8251  8251 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 11:31:39.481  8251  8251 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 11:31:39.485  8170  8170 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:31:39.485  8170  8238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:31:39.488  8121  8121 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 11:31:39.488  8121  8121 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:31:39.490  6950  6950 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:31:39.499  6950  6950 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:31:39.503  8251  8251 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:31:39.503  8251  8251 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:31:39.503  8251  8251 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 11:31:39.504  8251  8251 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 11:31:39.504  8251  8251 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 11:31:39.507  8170  8170 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 11:31:39.510  8170  8170 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-31 11:31:39.510  8170  8238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:31:39.512  1813  1813 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-31 11:31:39.521  2194  2194 I ConfigService: onCreate
08-31 11:31:39.521  2194  2194 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-31 11:31:39.522  1813  1813 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-31 11:31:39.543  2194  2194 I ConfigService: onBind returning update interface
,08-31 11:31:39.544  2194  2194 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
,08-31 11:31:39.544  2194  2194 I ConfigService: onBind returning config service
08-31 11:31:39.595  2030  2030 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-31 11:31:39.629  2194  2194 I ConfigService: onDestroy
,08-31 11:31:39.634  1813  8339 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-31 11:31:39.634  2030  2917 I GBoardtInterface: onReloaded()
08-31 11:31:39.637  2030  2030 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-31 11:31:39.638  3846  4492 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 11:31:39.643  3846  3864 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 11:31:39.653  5961  8343 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-31 11:31:39.656  1902  1902 D ActionManagerService: notifyUserLog: 1000001
08-31 11:31:39.659  3846  4496 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-31 11:31:39.659  3846  4496 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-31 11:31:39.661  1902  1902 D ActionManagerService: notifyUserLog: 1000001
08-31 11:31:39.663  3846  4496 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-31 11:31:39.663  3846  4496 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-31 11:31:39.663  3846  4496 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-31 11:31:39.663  3846  4496 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-31 11:31:39.664  7122  7122 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
08-31 11:31:39.664  3846  4492 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: Error inserting package=com.test.thalitest
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Meth,od)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:31:39.665  7122  7122 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:31:39.670  2030  2030 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-31 11:31:39.670  2030  2030 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,08-31 11:31:39.671  1813  8345 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:31:39.671  1813  8345 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android,.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:31:39.672  1813  8345 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:31:39.673  1813  8345 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-31 11:31:39.673  1813  4783 I Icing   : doRemovePackageData com.test.thalitest
08-31 11:31:39.674  1813  8345 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
--------- beginning of crash
08-31 11:31:39.674  1813  8345 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-31 11:31:39.674  1813  8345 E AndroidRuntime: Process: com.google.android.gms, PID: 1813
08-31 11:31:39.674  1813  8345 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-31 11:31:39.674  1813  8345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 11:31:39.674  1813  8345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-31 11:31:39.674  1813  8345 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-31 11:31:39.674  1813  8345 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 11:31:39.674  1813  8345 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-31 11:31:39.674  1813  8345 E AndroidRuntime: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:215)
08-31 11:31:39.674  1813  8345 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-31 11:31:39.674  1813  8345 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 11:31:39.674  1813  8345 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:31:39.674  1813  8345 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:31:39.674  1813  8345 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:31:39.675  1813  8347 I PeopleContactsSync: CP2 sync disabled
08-31 11:31:39.675  2030  2030 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-31 11:31:39.675  2030  2030 D GBoardWebViewUtils: changeCardUriByCategoryNum() c,hard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-31 11:31:39.678  2341  2458 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-31 11:31:39.678  2030  2030 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-31 11:31:39.678  2030  2030 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:31:39.679  2341  2458 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:31:39.681  1813  4783 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
08-31 11:31:39.681  1813  4783 E Icing   : Could not init tag ds.tag.corpusid-1
08-31 11:31:39.681  1813  4783 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-13 for write failed: Read-only file system
08-31 11:31:39.681  1813  4783 E Icing   : Could not init tag ds.tag.corpusid-13
08-31 11:31:39.681  1813  4783 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-7 for write failed: Read-only file system
08-31 11:31:39.681  1813  4783 E Icing   : Could not init tag ds.tag.corpusid-7
08-31 11:31:39.681  1813  4783 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-8 for write failed: Read-only file system
08-31 11:31:39.681  1813  4783 E Icing   : Could not init tag ds.tag.corpusid-8
08-31 11:31:39.681  1813  4783 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-9 for write failed: Read-only file system
08-31 11:31:39.681  1813  4783 E Icing   : Could not init tag ds.tag.corpusid-9
08-31 11:31:39.681  1813  4783 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
08-31 11:31:39.681  1813  4783 E Icing   : Could not init tag ds.tag.deleted
08-31 11:31:39.681  1813  4783 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
08-31 11:31:39.681  1813  4783 E Icing   : Writing status failed
08-31 11:31:39.685  2341  8349 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-31 11:31:39.689  1030  8348 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:31:39.689  1030  8348 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-31 11:31:39.689  1030  8348 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 11:31:39.689  1030  8348 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:31:39.689  1030  8348 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:31:39.689  1030  8348 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:31:39.689  1030  8348 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-31 11:31:39.689  1030  8348 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-31 11:31:39.689  1030  8348 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:31:39.689  1030  8348 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:31:39.689  1030  8348 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:31:39.689  1030  8348 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 11:31:39.689  1030  8348 E DropBoxManagerService: 	... 5 more
08-31 11:31:39.689  2341  8349 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-31 11:31:39.690  2341  8349 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-31 11:31:39.690  2341  8349 E AndroidRuntime: Process: android.process.acore, PID: 2341
08-31 11:31:39.690  2341  8349 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:31:39.690  2341  8349 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.b(SourceFile:502)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:496)
08-31 11:31:39.700  1813  8350 E SQLiteDatabase: 	at com.google.android.gms.drive.database.l.run(SourceFile:519)
08-31 11:31:39.700  1813  8350 I Process : Sending signal. PID: 1813 SIG: 9
08-31 11:31:39.704  4498  4541 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error

```
