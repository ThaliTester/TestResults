#### Test 797510157fdac7f_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-12 09:51:00.112  1590  1590 I [SystemUI]Clock: called onTimeUpdated()
08-12 09:51:00.121  1590  1590 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 09:51:00.121  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
08-12 09:51:00.123  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
08-12 09:51:00.125  1590  1590 D KeyguardUpdateMonitor: handleTimeUpdate
--------- beginning of system
08-12 09:51:15.538  1038  1366 D PowerManagerServiceEx: acquireWakeLockInternal: lock=588097582, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
08-12 09:51:15.546  1038  1366 V AlarmManager: ELAPSED_WAKEUP set : Alarm{abb2019 type 2 when 230071 android} when 230071
08-12 09:51:15.606  2614  2614 D [Concierge]Service: onStartCommand(). Type : 9
08-12 09:51:15.645  1038  1038 D PowerManagerServiceEx: releaseWakeLockInternal: lock=588097582 [*alarm*], flags=0x0
,08-12 09:51:16.892  6778  6778 D AndroidRuntime: 
08-12 09:51:16.892  6778  6778 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 09:51:16.896  6778  6778 D AndroidRuntime: CheckJNI is OFF
08-12 09:51:17.106  6778  6778 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 09:51:17.116  1038  1054 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 09:51:17.134  1928  4417 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-12 09:51:17.140  1038  1054 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-12 09:51:17.142  1038  1054 D ActivityManager: setTaskToReturnTo : TaskRecord{1ca78de #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 09:51:17.142  1038  1054 D ActivityManager: setTaskToReturnTo : TaskRecord{1ca78de #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 09:51:17.143  1038  1054 D WindowStateEx: AppWindowTokenEx init.. 
08-12 09:51:17.144   346   355 E GBMv2   : DFP En is all cleared set to be enabled
08-12 09:51:17.172  1038  1054 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6793 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 09:51:17.174  6778  6778 D AndroidRuntime: Shutting down VM
08-12 09:51:17.227  1928  1945 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-12 09:51:17.227  1928  1945 D SplitWindowPolicy: topRunningActivity=ActivityInfo{257e392c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 09:51:17.228  1928  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-12 09:51:17.228  1928  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1031eff5 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
,08-12 09:51:17.323  6793  6793 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-12 09:51:17.422  6793  6793 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-12 09:51:17.431  6793  6793 I LibraryLoader: Loading: webviewchromium
08-12 09:51:17.435  6793  6793 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7609-7613)
,08-12 09:51:17.435  6793  6793 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 09:51:17.452  6793  6793 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {eb333ba}
,08-12 09:51:17.454  6793  6793 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 09:51:17.454  6793  6793 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 09:51:17.464  6793  6793 I BrowserStartupController: Initializing chromium process, renderers=0
,08-12 09:51:17.466  6793  6793 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 09:51:17.480   324  1385 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
,08-12 09:51:17.484  6793  6793 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-12 09:51:17.485  1038  1120 D BluetoothManagerService: Message: 20
08-12 09:51:17.485  1038  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27ea1e78:true
08-12 09:51:17.486  6793  6793 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-12 09:51:17.486  6793  6793 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-12 09:51:17.509  6793  6793 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 09:51:17.509  6793  6793 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 09:51:17.509  6793  6793 I Adreno-EGL: Build Date: 12/12/14 금
08-12 09:51:17.509  6793  6793 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-12 09:51:17.509  6793  6793 I Adreno-EGL: Remote Branch: 
08-12 09:51:17.509  6793  6793 I Adreno-EGL: Local Patches: 
08-12 09:51:17.509  6793  6793 I Adreno-EGL: Reconstruct Branch: 
,08-12 09:51:17.607  6793  6833 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-12 09:51:17.614  6793  6793 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-12 09:51:17.633  6793  6793 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 09:51:17.639  6793  6793 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 09:51:17.642  6793  6793 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 09:51:17.646  6793  6793 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 09:51:17.646  6793  6793 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-12 09:51:17.662  6793  6793 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 09:51:17.726  1038  1116 W ActivityManager: Activity pause timeout for ActivityRecord{dbd4abf u0 com.test.thalitest/.MainActivity t6}
,08-12 09:51:17.789  1038  1964 I art     : Explicit concurrent mark sweep GC freed 31623(1474KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.524ms total 120.962ms
,08-12 09:51:17.792  6793  6793 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 09:51:17.792  6793  6793 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 09:51:17.821  6793  6849 D OpenGLRenderer: Render dirty regions requested: true
08-12 09:51:17.821  6793  6849 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 09:51:17.842  6793  6849 D OpenGLRenderer: Enabling debug mode 0
,08-12 09:51:17.853  6793  6793 D Atlas   : Validating map...
08-12 09:51:17.857  1038  1905 D SplitWindow: check instance of lgWin Window{245e44f2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 09:51:17.904  6793  6847 D LgDataFeature: LgDataFeature() Constructor: none
,08-12 09:51:17.905  6793  6847 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-12 09:51:17.976  1038  1121 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +750ms (total +831ms)
08-12 09:51:17.977  6793  6793 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@36f795d1 time:308156
08-12 09:51:17.977  1038  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{dbd4abf u0 com.test.thalitest/.MainActivity t6} time:308156
,08-12 09:51:18.094  6793  6793 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-12 09:51:18.094  6793  6793 I chromium: 
,08-12 09:51:18.136  6793  6793 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 09:51:18.201  6793  6847 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-12 09:51:18.201  6793  6847 I chromium: 
,08-12 09:51:18.340  6793  6859 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435137024
,08-12 09:51:18.354  6793  6859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 09:51:18.354  6793  6859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 09:51:18.354  6793  6859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 09:51:18.354  6793  6859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 09:51:18.354  6793  6859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 09:51:18.355  6793  6859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bcaa1c5 added. We now have 1 listener(s)
08-12 09:51:18.360  1038  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 09:51:18.364  6793  6859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-12 09:51:18.365  6793  6859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-12 09:51:18.376  6793  6859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 09:51:18.377  6793  6859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 09:51:18.385  6793  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 09:51:18.385  6793  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 09:51:18.385  6793  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 09:51:18.385  6793  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-12 09:51:18.385  6793  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 09:51:18.385  6793  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 09:51:18.385  6793  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 09:51:18.385  6793  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 09:51:18.385  6793  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 09:51:18.385  6793  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 09:51:18.385  6793  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 09:51:18.385  6793  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 09:51:18.385  6793  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 09:51:18.385  6793  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 09:51:18.385  6793  6859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39463428 added. We now have 1 listener(s)
08-12 09:51:18.385  6793  6859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 09:51:18.389  1038  1480 D WifiService: New client listening to asynchronous messages
,08-12 09:51:18.394  6793  6859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 09:51:18.395  6793  6859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 09:51:18.395  6793  6859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 09:51:18.395  6793  6859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 09:51:18.395  6793  6859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 09:51:18.399  6793  6859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 09:51:18.400  1038  1563 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 09:51:18.401  6793  6859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-12 09:51:18.411  6793  6859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-12 09:51:18.412  6793  6859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 09:51:18.412  6793  6859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 09:51:18.412  6793  6859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 09:51:18.412  6793  6859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 09:51:18.412  6793  6859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 09:51:18.412  6793  6859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 09:51:18.412  6793  6859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 09:51:18.412  6793  6859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 09:51:18.412  6793  6859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 09:51:18.412  6793  6859 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 09:51:18.414  6793  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 09:51:18.417  6793  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 09:51:18.418  6793  6859 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 09:51:18.455  6793  6793 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 09:51:18.755   346   357 E GBMv2   : DFP En is all cleared set to be enabled
,08-12 09:51:18.755   346   357 E GBMv2   : Set value is all cleared set the max
08-12 09:51:18.755   346   357 I GBMv2   : DFP Enabled. Ignore VFP set
08-12 09:51:19.711  6793  6862 W jxcore-log: Initializing JXcore engine
08-12 09:51:19.711  6793  6862 W jxcore-log: JXcore engine is ready
,08-12 09:51:19.773  6862  6862 W Thread-797: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7455]" dev="sockfs" ino=7455 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-12 09:51:19.773  6862  6862 W Thread-797: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-12 09:51:19.773  6862  6862 W Thread-797: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10456]" dev="sockfs" ino=10456 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 09:51:19.773  6862  6862 W Thread-797: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-12 09:51:19.773  6862  6862 W Thread-797: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33361]" dev="sockfs" ino=33361 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-12 09:51:19.812  6793  6862 W jxcore-log: Starting JXcore engine
,08-12 09:51:19.971  6793  6862 W jxcore-log: Platform android
08-12 09:51:19.971  6793  6862 W jxcore-log: 
08-12 09:51:19.972  6793  6862 W jxcore-log: Process ARCH arm
08-12 09:51:19.972  6793  6862 W jxcore-log: 
,08-12 09:51:20.452  6793  6862 I jxcore-log: JXcore Cordova bridge is ready!
08-12 09:51:20.452  6793  6862 I jxcore-log: 
,08-12 09:51:20.456  6793  6862 W jxcore-log: JXcore engine is started
08-12 09:51:20.467  6793  6859 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 09:51:20.474  6793  6793 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 09:51:37.260  6793  6862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 09:51:37.260  6793  6862 I jxcore-log: 
,08-12 09:51:37.264  6793  6862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 09:51:37.264  6793  6862 I jxcore-log: ,
08-12 09:51:37.267  6793  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 09:51:37.267  6793  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 09:51:37.267  6793  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 09:51:37.267  6793  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 09:51:37.267  6793  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 09:51:37.267  6793  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 09:51:37.267  6793  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 09:51:37.267  6793  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 09:51:37.269  6793  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 09:51:37.272  6793  6862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 09:51:37.272  6793  6862 I jxcore-log: 
08-12 09:51:37.274  6793  6862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 09:51:37.274  6793  6862 I jxcore-log: 
,08-12 09:51:37.609  6793  6862 I jxcore-log: Unit Test app is loaded
08-12 09:51:37.609  6793  6862 I jxcore-log: 
08-12 09:51:37.616  6793  6862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 09:51:37.616  6793  6862 I jxcore-log: 
08-12 09:51:37.619  6793  6862 I jxcore-log: My device name is: LGE-LG-D855
08-12 09:51:37.619  6793  6862 I jxcore-log: 
08-12 09:51:37.620  6793  6862 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 09:51:37.620  6793  6862 I jxcore-log: 
,08-12 09:51:37.635  6793  6793 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-12 09:51:39.867  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 09:51:39.867  6793  6862 I jxcore-log: 
,08-12 09:51:40.501  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 09:51:40.501  6793  6862 I jxcore-log: 
,08-12 09:51:40.527  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 09:51:40.527  6793  6862 I jxcore-log: 
,08-12 09:51:41.870  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 09:51:41.870  6793  6862 I jxcore-log: 
,08-12 09:51:42.098  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 09:51:42.098  6793  6862 I jxcore-log: 
,08-12 09:51:42.104  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 09:51:42.104  6793  6862 I jxcore-log: 
,08-12 09:51:42.109  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 09:51:42.109  6793  6862 I jxcore-log: 
,08-12 09:51:42.126  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 09:51:42.126  6793  6862 I jxcore-log: 
,08-12 09:51:42.131  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 09:51:42.131  6793  6862 I jxcore-log: 
08-12 09:51:42.791  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 09:51:42.791  6793  6862 I jxcore-log: 
,08-12 09:51:42.805  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 09:51:42.805  6793  6862 I jxcore-log: 
,08-12 09:51:42.815  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 09:51:42.815  6793  6862 I jxcore-log: 
,08-12 09:51:42.822  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 09:51:42.822  6793  6862 I jxcore-log: 
,08-12 09:51:42.870  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 09:51:42.870  6793  6862 I jxcore-log: 
,08-12 09:51:42.927  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 09:51:42.927  6793  6862 I jxcore-log: 
,08-12 09:51:42.936  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 09:51:42.936  6793  6862 I jxcore-log: 
,08-12 09:51:43.099  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 09:51:43.099  6793  6862 I jxcore-log: 
,08-12 09:51:43.127  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 09:51:43.127  6793  6862 I jxcore-log: 
,08-12 09:51:43.133  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 09:51:43.133  6793  6862 I jxcore-log: 
,08-12 09:51:43.139  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 09:51:43.139  6793  6862 I jxcore-log: 
08-12 09:51:43.157  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 09:51:43.157  6793  6862 I jxcore-log: 
,08-12 09:51:43.239  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 09:51:43.239  6793  6862 I jxcore-log: 
,08-12 09:51:43.253  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 09:51:43.253  6793  6862 I jxcore-log: 
,08-12 09:51:43.281  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 09:51:43.281  6793  6862 I jxcore-log: 
,08-12 09:51:43.293  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 09:51:43.293  6793  6862 I jxcore-log: 
,08-12 09:51:43.311  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 09:51:43.311  6793  6862 I jxcore-log: 
,08-12 09:51:43.348  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 09:51:43.348  6793  6862 I jxcore-log: 
,08-12 09:51:43.354  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 09:51:43.354  6793  6862 I jxcore-log: 
,08-12 09:51:43.559  6793  6862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 09:51:43.559  6793  6862 I jxcore-log: 
,08-12 09:51:43.568  6793  6862 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-12 09:51:43.569  6793  6862 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-12 09:51:43.569  6793  6862 I jxcore-log: 
08-12 09:51:45.356  1038  3507 I LocationManagerService: remove afda899
08-12 09:51:45.357  1038  3507 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
,08-12 09:51:45.364  1038  3507 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-12 09:51:45.366  1038  3507 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-12 09:51:45.368  1038  3507 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-12 09:51:45.370  1038  3507 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-12 09:51:56.139  6793  6862 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-12 09:51:56.139  6793  6862 I jxcore-log: 
,08-12 09:51:56.502  6884  6884 D AndroidRuntime: 
08-12 09:51:56.502  6884  6884 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 09:51:56.506  6884  6884 D AndroidRuntime: CheckJNI is OFF
08-12 09:51:56.674  6884  6884 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 09:51:56.695  1038  1116 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-12 09:51:56.697  1038  1116 I ActivityManager: Killing 6793:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-12 09:51:56.769  1038  2022 I WindowState: WIN DEATH: Window{245e44f2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 09:51:56.776  1038  1480 D WifiService: Client connection lost with reason: 4
08-12 09:51:56.781  1038  2022 D InputDispatcher: Window went away: Window{245e44f2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 09:51:56.912  1038  1116 I ActivityManager:   Force finishing activity ActivityRecord{dbd4abf u0 com.test.thalitest/.MainActivity t6}
,08-12 09:51:56.950   346   355 E GBMv2   : DFP En is all cleared set to be enabled
,08-12 09:51:56.955  1038  1963 W ActivityManager: Spurious death for ProcessRecord{2d1638d8 6793:com.test.thalitest/u0a118}, curProc for 6793: null
08-12 09:51:56.958  1928  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-12 09:51:56.958  1928  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{28de018a co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 09:51:56.960  1928  4417 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-12 09:51:56.960  1928  4417 D SplitWindowPolicy: topRunningActivity=ActivityInfo{5bae3fb co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-12 09:51:56.972  2019  2019 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-12 09:51:56.974  2019  2019 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-12 09:51:56.975  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-12 09:51:56.976  2019  2110 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-12 09:51:56.977  1038  1126 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-12 09:51:57.005  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-12 09:51:57.006  1892  1892 D ActionManagerService: notifyUserLog: 1000003
08-12 09:51:57.007  3793  4902 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-12 09:51:57.009  2019  2019 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-12 09:51:57.011  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 09:51:57.019  1038  1368 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 09:51:57.022  2466  2593 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 09:51:57.034  4287  4287 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-12 09:51:57.034  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-12 09:51:57.035  1982  1982 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-12 09:51:57.071  3793  3793 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-12 09:51:57.105  2019  2019 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-12 09:51:57.107  1590  1590 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-12 09:51:57.108  2019  2019 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-12 09:51:57.111  1590  1643 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 09:51:57.111  1590  1643 D KeyguardModel: createShortcutInfo...
08-12 09:51:57.112  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-12 09:51:57.112  1892  1892 D ActionManagerService: notifyUserLog: 1000004
08-12 09:51:57.113  3793  4902 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-12 09:51:57.114  3793  3809 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 09:51:57.114  1590  1643 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 09:51:57.114  1590  1643 D KeyguardModel: createShortcutInfo...
08-12 09:51:57.116  4904  4904 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 09:51:57.116  6415  6415 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-12 09:51:57.117  4904  4904 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 09:51:57.117  4904  4904 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 09:51:57.117  4904  4904 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-12 09:51:57.117  4904  4904 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 09:51:57.117  4904  4904 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 09:51:57.117  4904  4904 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 09:51:57.117  4904  4904 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 09:51:57.117  4904  4904 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 09:51:57.117  4904  4904 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 09:51:57.117  4904  4904 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 09:51:57.117  4904  4904 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262123
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , display: false
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , animation: false }
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262287
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , display: false
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , animation: false }
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , create_time: 1470393743569
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , display: false
08-12 09:51:57.124  2019  2019 I GBoardWebViewUtils: , animation: false }
08-12 09:51:57.126  1803  1803 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-12 09:51:57.127  1590  1590 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 09:51:57.127  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-12 09:51:57.147  1590  1643 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 09:51:57.148  1590  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 09:51:57.148  1590  1643 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-12 09:51:57.149  1590  1643 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 09:51:57.154  2019  6917 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-12 09:51:57.159  1590  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:51:57.159  1590  1643 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 09:51:57.164  2171  2171 I ConfigService: onCreate
08-12 09:51:57.169  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-12 09:51:57.171  1590  1643 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 09:51:57.171  1590  1643 D KeyguardModel: createShortcutInfo...
,08-12 09:51:57.175  1590  1643 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 09:51:57.175  1590  1643 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 09:51:57.177  5013  5013 I art     : Explicit concurrent mark sweep GC freed 468(31KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 409us total 189.725ms
08-12 09:51:57.178  1590  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:51:57.178  1590  1643 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 09:51:57.181  1590  1643 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 09:51:57.181  1590  1643 D KeyguardModel: createShortcutInfo...
08-12 09:51:57.182  2171  2171 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-12 09:51:57.182  2171  2171 I ConfigService: onBind returning update interface
08-12 09:51:57.189  1038  1884 V SIM_STK : Menu title from STK is T-Mobile
08-12 09:51:57.189  1038  1884 V SIM_STK : Menu title from STK is T-Mobile
08-12 09:51:57.209  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-12 09:51:57.209  1856  1856 D SplitUIService: removed split : 
,08-12 09:51:57.223  2171  2171 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-12 09:51:57.223  2171  2171 I ConfigService: onBind returning config service
08-12 09:51:57.224  1803  1803 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-12 09:51:57.228  1590  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 09:51:57.228  1590  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-12 09:51:57.234  1803  1803 I ConfigFetchService: service connected
08-12 09:51:57.234  1803  1803 I ConfigClient: service connected
08-12 09:51:57.241  1590  1643 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-12 09:51:57.241  1590  1643 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 09:51:57.251  1038  2015 V SIM_STK : Menu title from STK is T-Mobile
08-12 09:51:57.251  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 09:51:57.256  2171  2171 I ConfigService: onDestroy
08-12 09:51:57.258  1590  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:51:57.258  1590  1643 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 09:51:57.260  1038  1115 W InputMethodInfo: Duplicated subtype definition found: , voice
08-12 09:51:57.263  1803  6922 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-12 09:51:57.270  1038  1884 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-12 09:51:57.270  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-12 09:51:57.271  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-12 09:51:57.271  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-12 09:51:57.271  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-12 09:51:57.271  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-12 09:51:57.271  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 09:51:57.271  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-12 09:51:57.271  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-12 09:51:57.271  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-12 09:51:57.271  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 09:51:57.271  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-12 09:51:57.274  1590  1643 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 09:51:57.274  1590  1643 D KeyguardModel: createShortcutInfo...
08-12 09:51:57.274  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-12 09:51:57.274  1856  1856 I SplitUIService: split app #11
,08-12 09:51:57.283  1590  1590 D KeyguardModel: handleShortcutListChanged...
08-12 09:51:57.284  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 09:51:57.296  1590  1643 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 09:51:57.296  1590  1643 D KeyguardModel: createShortcutInfo...
,08-12 09:51:57.312  1038  1038 I art     : Explicit concurrent mark sweep GC freed 16970(1418KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/64MB, paused 4.351ms total 311.509ms
,08-12 09:51:57.313  1590  1643 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 09:51:57.313  1590  1643 D KeyguardModel: createShortcutInfo...
08-12 09:51:57.315  1038  1126 I art     : WaitForGcToComplete blocked for 195.253ms for cause Explicit
08-12 09:51:57.315  1590  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:51:57.315  1590  1643 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 09:51:57.317  1590  1643 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 09:51:57.317  1590  1643 D KeyguardModel: createShortcutInfo...
08-12 09:51:57.318  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-12 09:51:57.320  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 09:51:57.321  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-12 09:51:57.323  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-12 09:51:57.323  1590  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:51:57.323  1590  1643 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 09:51:57.324  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-12 09:51:57.325  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-12 09:51:57.327  1590  1643 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 09:51:57.327  1590  1643 D KeyguardModel: createShortcutInfo...
,08-12 09:51:57.329  1590  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:51:57.329  1590  1643 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 09:51:57.330  1803  5201 I Icing   : doRemovePackageData com.test.thalitest
08-12 09:51:57.331  1803  6929 I PeopleContactsSync: CP2 sync disabled
08-12 09:51:57.332  1590  1643 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 09:51:57.332  1590  1643 D KeyguardModel: createShortcutInfo...
08-12 09:51:57.339  2019  2019 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-12 09:51:57.343  5882  6928 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-12 09:51:57.353  5998  5998 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-12 09:51:57.357  1590  1590 D KeyguardModel: handleShortcutListChanged...
08-12 09:51:57.357  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-12 09:51:57.360  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-12 09:51:57.361  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 09:51:57.362  2019  2195 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-12 09:51:57.362  2019  2195 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-12 09:51:57.364  1038  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2d6ed351 u0 com.lge.launcher2/.Launcher t5} time:347543
08-12 09:51:57.366  1803  6927 W GmsApplication: Using Auth Proxy for data requests.
08-12 09:51:57.371  1803  6927 W GmsApplication: Using Auth Proxy for data requests.
08-12 09:51:57.375  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-12 09:51:57.376  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 09:51:57.376  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 09:51:57.385  2019  2019 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-12 09:51:57.385  6515  6515 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-12 09:51:57.387  2614  2614 D [Concierge]Service: onStartCommand(). Type : 8
08-12 09:51:57.387  2614  2614 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-12 09:51:57.388  2614  2614 D [Concierge]Service: Update widget ID : 11
,08-12 09:51:57.398  2335  6931 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-12 09:51:57.399  2019  2019 D [Concierge]WidgetView: change position of spinner
08-12 09:51:57.403  2019  2019 I [Concierge]WidgetView: initWebView(). Time : 1470988317403
,08-12 09:51:57.406  2614  2614 D [Concierge]Service: onStartCommand(). Type : 0
08-12 09:51:57.413  1038  1964 V SIM_STK : Menu title from STK is T-Mobile
08-12 09:51:57.416  1982  1982 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 09:51:57.416  1982  1982 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-12 09:51:57.424  1038  1038 D administrator: Handling package changes for user 0
,08-12 09:51:57.431  1982  1982 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-12 09:51:57.441  2019  2019 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 502685225
,08-12 09:51:57.441  6415  6415 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-12 09:51:57.442  2019  2019 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-12 09:51:57.442  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-12 09:51:57.450  2019  2019 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@134fe930
08-12 09:51:57.450  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-12 09:51:57.452  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 09:51:57.452  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 09:51:57.463  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,08-12 09:51:57.464  2019  2019 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 09:51:57.474  1038  1719 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6936 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-12 09:51:57.478  2019  2019 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470987998253, New one : 1470988317403
08-12 09:51:57.478  2019  2019 D [Concierge]WidgetView: Unregister all receivers
08-12 09:51:57.478  2019  2019 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 09:51:57.479  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 09:51:57.480  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-12 09:51:57.481  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-12 09:51:57.482  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-12 09:51:57.483  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-12 09:51:57.484  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-12 09:51:57.485  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 09:51:57.485  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 09:51:57.513  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-12 09:51:57.515  1038  1038 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 09:51:57.515  1038  1038 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 09:51:57.515  1038  1038 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 09:51:57.517  1038  1565 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-12 09:51:57.521  2019  2019 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-12 09:51:57.521  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-12 09:51:57.522  2019  2019 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-12 09:51:57.522  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 09:51:57.543  2019  2019 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2c18262a time:347722
,08-12 09:51:57.583  6936  6936 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-12 09:51:57.584  6936  6936 W LG Account v2.2: No ProfileInfo entries
08-12 09:51:57.584  6936  6936 I LG Account v2.2: isEnabled: false
08-12 09:51:57.584  6936  6936 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-12 09:51:57.584  6936  6936 I Feature : [Lifetracker]Country: EU
08-12 09:51:57.584  6936  6936 I Feature : [Lifetracker]Operator: OPEN
08-12 09:51:57.584  6936  6936 I Feature : [Lifetracker]Ranking support: false
08-12 09:51:57.584  6936  6936 I Feature : [Lifetracker]Comfort support: false
08-12 09:51:57.584  6936  6936 I Feature : [Lifetracker]Accessory: true
08-12 09:51:57.584  6936  6936 I Feature : [Lifetracker]Health device: true
08-12 09:51:57.584  6936  6936 I Feature : [Lifetracker]Extra Pedometer: false
08-12 09:51:57.584  6936  6936 I Feature : [Lifetracker]Blood glucose device: false
08-12 09:51:57.584  6936  6936 I Feature : [Lifetracker]Device Number: 3
08-12 09:51:57.585  6936  6936 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-12 09:51:57.589  1038  1126 I art     : Explicit concurrent mark sweep GC freed 6858(366KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.353ms total 273.239ms
08-12 09:51:57.614  1038  1883 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6956 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-12 09:51:57.615  1038  1883 I ActivityManager: Killing 6218:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-12 09:51:57.673  6884  6884 D AndroidRuntime: Shutting down VM
,08-12 09:51:57.685  1038  1115 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 09:51:57.689  1038  1115 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-12 09:51:57.751  2019  2019 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-12 09:51:57.754  1038  1053 W libprocessgroup: failed to open /acct/uid_10014/pid_6218/cgroup.procs: No such file or directory
08-12 09:51:57.781  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-12 09:51:57.807  2019  2879 I GBoardtInterface: onReloaded()
,08-12 09:51:57.810  2019  2019 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-12 09:51:57.812  3793  3809 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 09:51:57.818  3793  3808 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 09:51:57.821  6956  6956 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 09:51:57.821  6956  6956 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-12 09:51:57.823  6956  6956 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 09:51:57.824  6956  6956 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-12 09:51:57.828  6956  6956 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 09:51:57.829  1892  1892 D ActionManagerService: notifyUserLog: 1000001
08-12 09:51:57.831  3793  4902 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 09:51:57.831  3793  4902 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 09:51:57.831  6956  6956 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-12 09:51:57.835  1892  1892 D ActionManagerService: notifyUserLog: 1000001
08-12 09:51:57.836  3793  4902 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 09:51:57.837  3793  4902 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 09:51:57.837  3793  4902 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-12 09:51:57.837  3793  4902 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
,08-12 09:51:57.840  3793  3809 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 09:51:57.843  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-12 09:51:57.843  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-12 09:51:57.847  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-12 09:51:57.847  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 09:51:57.850  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-12 09:51:57.850  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-12 09:51:58.018  6956  6956 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-12 09:51:58.029  6956  6956 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-12 09:51:58.029  6956  6956 D HideNavigationAppsReceiver: replacing : false
,08-12 09:51:58.036  6956  6956 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-12 09:51:58.038  6956  6956 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-12 09:51:58.038  6956  6956 D ButtonCombinationReceiver: replacing : false
,08-12 09:51:58.050  1038  1613 I ActivityManager: Killing 6475:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-12 09:51:58.063   280   802 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
