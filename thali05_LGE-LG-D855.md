#### Test 79751015abe04ee_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-05 11:27:00.093  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
08-05 11:27:00.102  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 11:27:00.102  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:27:00.104  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:27:00.106  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 11:27:12.957  6962  6962 D AndroidRuntime: 
08-05 11:27:12.957  6962  6962 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-05 11:27:12.963  6962  6962 D AndroidRuntime: CheckJNI is OFF
08-05 11:27:13.088  6962  6962 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-05 11:27:13.093  1036  1643 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 11:27:13.104  1939  1954 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-05 11:27:13.107  1036  1643 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-05 11:27:13.108  1036  1643 D ActivityManager: setTaskToReturnTo : TaskRecord{9aa3ea0 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 11:27:13.108  1036  1643 D ActivityManager: setTaskToReturnTo : TaskRecord{9aa3ea0 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 11:27:13.109  1036  1643 D WindowStateEx: AppWindowTokenEx init.. 
08-05 11:27:13.110   342   384 E GBMv2   : DFP En is all cleared set to be enabled
08-05 11:27:13.147  1036  1643 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6981 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-05 11:27:13.149  6962  6962 D AndroidRuntime: Shutting down VM
08-05 11:27:13.197  1939  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-05 11:27:13.197  1939  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{5e06844 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 11:27:13.199  1939  2771 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-05 11:27:13.199  1939  2771 D SplitWindowPolicy: topRunningActivity=ActivityInfo{8e94d2d co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 11:27:13.280  6981  6981 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-05 11:27:13.381  6981  6981 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-05 11:27:13.391  6981  6981 I LibraryLoader: Loading: webviewchromium
08-05 11:27:13.395  6981  6981 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 1671-1676)
08-05 11:27:13.395  6981  6981 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 11:27:13.412  6981  6981 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {22e5aa92}
08-05 11:27:13.414  6981  6981 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 11:27:13.415  6981  6981 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 11:27:13.426  6981  6981 I BrowserStartupController: Initializing chromium process, renderers=0
08-05 11:27:13.427  6981  6981 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 11:27:13.445   309  1384 V AudioPolicyService: registerClient() client 0xb1025d40, uid 10118
08-05 11:27:13.449  1036  1118 D BluetoothManagerService: Message: 20
08-05 11:27:13.449  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@357e662a:true
08-05 11:27:13.450  6981  6981 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-05 11:27:13.451  6981  6981 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-05 11:27:13.451  6981  6981 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-05 11:27:13.464  6981  6981 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 11:27:13.464  6981  6981 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 11:27:13.464  6981  6981 I Adreno-EGL: Build Date: 12/12/14 금
08-05 11:27:13.464  6981  6981 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 11:27:13.464  6981  6981 I Adreno-EGL: Remote Branch: 
08-05 11:27:13.464  6981  6981 I Adreno-EGL: Local Patches: 
08-05 11:27:13.464  6981  6981 I Adreno-EGL: Reconstruct Branch: 
08-05 11:27:13.559  6981  7017 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-05 11:27:13.561  6981  6981 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-05 11:27:13.586  6981  6981 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 11:27:13.591  6981  6981 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-05 11:27:13.595  6981  6981 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-05 11:27:13.599  6981  6981 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-05 11:27:13.599  6981  6981 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-05 11:27:13.614  6981  6981 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-05 11:27:13.621  6981  6981 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 11:27:13.621  6981  6981 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 11:27:13.655  6981  7030 D OpenGLRenderer: Render dirty regions requested: true
08-05 11:27:13.655  6981  7030 I OpenGLRenderer: Initialized EGL, version 1.4
08-05 11:27:13.659  6981  7030 D OpenGLRenderer: Enabling debug mode 0
08-05 11:27:13.667  6981  6981 D Atlas   : Validating map...
08-05 11:27:13.671  1036  1957 D SplitWindow: check instance of lgWin Window{25a94b94 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 11:27:13.740  6981  7028 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:27:13.740  6981  7028 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 11:27:13.803  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +607ms (total +692ms)
08-05 11:27:13.805  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c519a59 u0 com.test.thalitest/.MainActivity t40} time:312086
08-05 11:27:13.806  6981  6981 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@30975a89 time:312087
08-05 11:27:13.914  6981  6981 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-05 11:27:13.914  6981  6981 I chromium: 
08-05 11:27:13.978  6981  6981 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-05 11:27:14.156  6981  7044 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435182080
,08-05 11:27:14.171  6981  7044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 11:27:14.171  6981  7044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 11:27:14.171  6981  7044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 11:27:14.171  6981  7044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 11:27:14.171  6981  7044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-05 11:27:14.172  6981  7044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28e9c8fd added. We now have 1 listener(s)
,08-05 11:27:14.179  1036  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:14.183  6981  7044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-05 11:27:14.187  6981  7044 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-05 11:27:14.191  6981  7044 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:27:14.192  6981  7044 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:27:14.200  6981  7044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 11:27:14.200  6981  7044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 11:27:14.200  6981  7044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 11:27:14.200  6981  7044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-05 11:27:14.200  6981  7044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 11:27:14.200  6981  7044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 11:27:14.200  6981  7044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 11:27:14.200  6981  7044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 11:27:14.200  6981  7044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 11:27:14.200  6981  7044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 11:27:14.200  6981  7044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 11:27:14.200  6981  7044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 11:27:14.200  6981  7044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 11:27:14.200  6981  7044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-05 11:27:14.200  6981  7044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27720ec0 added. We now have 1 listener(s)
08-05 11:27:14.201  6981  7044 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 11:27:14.207  1036  1543 D WifiService: New client listening to asynchronous messages
08-05 11:27:14.212  6981  7044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 11:27:14.212  6981  7044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-05 11:27:14.212  6981  7044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 11:27:14.212  6981  7044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 11:27:14.212  6981  7044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-05 11:27:14.217  6981  7044 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:27:14.218  1036  1643 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:14.221  6981  7044 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-05 11:27:14.234  6981  7044 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 11:27:14.235  6981  7044 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:27:14.235  6981  7044 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:14.235  6981  7044 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:14.235  6981  7044 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:14.235  6981  7044 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:14.235  6981  7044 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:27:14.235  6981  7044 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:27:14.235  6981  7044 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:27:14.235  6981  7044 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 11:27:14.235  6981  7044 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 11:27:14.241  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:14.243  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:14.245  6981  7044 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-05 11:27:14.285  6981  7028 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-05 11:27:14.285  6981  7028 I chromium: 
,08-05 11:27:14.335  6981  6981 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 11:27:14.609   342   386 E GBMv2   : DFP En is all cleared set to be enabled
08-05 11:27:14.609   342   386 E GBMv2   : Set value is all cleared set the max
08-05 11:27:14.609   342   386 I GBMv2   : DFP Enabled. Ignore VFP set
,08-05 11:27:15.197  6981  7047 W jxcore-log: Initializing JXcore engine
08-05 11:27:15.197  6981  7047 W jxcore-log: JXcore engine is ready
,08-05 11:27:15.223  7047  7047 W Thread-827: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8349]" dev="sockfs" ino=8349 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-05 11:27:15.223  7047  7047 W Thread-827: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-05 11:27:15.223  7047  7047 W Thread-827: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10031]" dev="sockfs" ino=10031 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-05 11:27:15.223  7047  7047 W Thread-827: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-05 11:27:15.223  7047  7047 W Thread-827: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31517]" dev="sockfs" ino=31517 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-05 11:27:15.251  6981  7047 W jxcore-log: Starting JXcore engine
,08-05 11:27:15.325  6981  7047 W jxcore-log: Platform android
08-05 11:27:15.325  6981  7047 W jxcore-log: 
,08-05 11:27:15.325  6981  7047 W jxcore-log: Process ARCH arm
08-05 11:27:15.325  6981  7047 W jxcore-log: 
08-05 11:27:15.541  6981  7047 I jxcore-log: JXcore Cordova bridge is ready!
08-05 11:27:15.541  6981  7047 I jxcore-log: 
08-05 11:27:15.541  6981  7047 W jxcore-log: JXcore engine is started
,08-05 11:27:15.550  6981  7044 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-05 11:27:15.554  6981  6981 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 11:27:24.464  1036  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=846547016, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-05 11:27:24.476  1036  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2264418a type 2 when 322731 com.google.android.gms} when 322731
08-05 11:27:24.508  2079  2079 I ConfigService: onCreate
,08-05 11:27:24.508  2079  2079 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-05 11:27:24.511  2610  2610 D [Concierge]Service: onStartCommand(). Type : 9
08-05 11:27:24.524  1815  1815 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-05 11:27:24.524  2079  2079 I ConfigService: onBind returning update interface
08-05 11:27:24.525  2079  2079 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-05 11:27:24.525  2079  2079 I ConfigService: onBind returning config service
08-05 11:27:24.526  1815  1815 I ConfigFetchService: service connected
08-05 11:27:24.527  1815  1815 I ConfigClient: service connected
08-05 11:27:24.530  1815  7049 I ConfigFetchService: running network task: configservice_periodic
08-05 11:27:24.535  1815  7049 I ConfigFetchService: launchTask
08-05 11:27:24.541  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=846547016 [*alarm*], flags=0x0
,08-05 11:27:24.607  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
,08-05 11:27:24.618  1815  4577 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-05 11:27:24.621   303  7062 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-05 11:27:24.622   303  7062 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-05 11:27:24.663   303  7062 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-05 11:27:24.913  1815  4577 W ConfigFetchTask: bad response from server: 401 Unauthorized
,08-05 11:27:24.917  1815  1815 I ConfigFetchService: fetch service done; releasing wakelock
08-05 11:27:24.920  1815  1815 I ConfigFetchService: stopping self
08-05 11:27:24.958  2079  2079 I ConfigService: onDestroy
,08-05 11:27:31.773  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 11:27:31.773  6981  7047 I jxcore-log: 
08-05 11:27:31.775  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 11:27:31.775  6981  7047 I jxcore-log: 
,08-05 11:27:31.779  6981  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:27:31.779  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:31.779  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:31.779  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-05 11:27:31.779  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:31.779  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:27:31.779  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:27:31.779  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:27:31.782  6981  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:27:31.784  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 11:27:31.784  6981  7047 I jxcore-log: 
08-05 11:27:31.786  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 11:27:31.786  6981  7047 I jxcore-log: 
,08-05 11:27:32.126  6981  7047 D ExecuteNativeTests: Running unit tests
,08-05 11:27:32.209  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:27:32.210  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd added. We now have 2 listener(s)
,08-05 11:27:32.210  1036  1695 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:32.212  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:27:32.212  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:27:32.212  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:27:32.212  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:32.212  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 added. We now have 2 listener(s)
08-05 11:27:32.212  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:27:32.213  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 11:27:32.215  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:27:32.217  6981  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:27:32.217  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:32.217  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:32.217  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:32.217  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:32.217  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:27:32.217  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:27:32.217  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:27:32.218  6981  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:27:32.219  6981  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 11:27:32.220  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:32.221  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:32.228  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-05 11:27:32.235  6981  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 11:27:32.235  6981  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 11:27:32.241  6981  7047 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-05 11:27:32.243  6981  7047 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 11:27:32.243  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 11:27:32.244  6981  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 11:27:32.244  6981  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 11:27:32.246  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.247  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.247  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.247  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.247  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.248  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:27:32.248  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:27:32.248  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd removed from the list
08-05 11:27:32.248  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.248  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 removed from the list
08-05 11:27:32.248  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.248  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.249  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.249  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.249  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.249  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.249  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.250  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.252  6981  7047 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-05 11:27:32.252  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 11:27:32.252  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.252  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.252  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.252  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.252  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.253  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.253  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.253  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.253  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.253  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.253  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.253  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.253  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.254  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.254  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.254  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.254  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.261  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 11:27:32.261  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 11:27:32.261  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 11:27:32.261  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 11:27:32.261  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 11:27:32.261  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 11:27:32.261  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 11:27:32.261  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 11:27:32.261  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 11:27:32.261  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 11:27:32.261  6981  7047 D io.jxcore.node.C,onnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 11:27:32.261  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 11:27:32.261  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 11:27:32.261  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 11:27:32.262  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 11:27:32.262  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.262  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.262  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.263  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.263  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.263  6981  7047 D org.thaliproject.p2p.btconnectorlib.intern,al.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.263  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.263  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.263  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.263  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.263  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.263  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.264  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.264  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:27:32.266  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.266  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.266  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.266  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.267  6981  7047 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 11:27:32.268  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:27:32.270  6981  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:27:32.270  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:32.270  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:32.270  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:32.270  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:32.270  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:27:32.270  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:27:32.270  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:27:32.271  6981  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:27:32.271  6981  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:27:32.272  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:27:32.273  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:32.273  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:27:32.273  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:27:32.274  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 11:27:32.274  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:27:32.274  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 11:27:32.276  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 11:27:32.277  1036  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:32.281  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 11:27:32.285  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 11:27:32.286  6981  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 11:27:32.287  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 11:27:32.287  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:27:32.288  6981  7047 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-05 11:27:32.288  6981  7047 I io.jxcore.node.ConnectionHelper: start: OK
08-05 11:27:32.291  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.291  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.291  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.291  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.291  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.291  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:27:32.291  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.291  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.292  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.292  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.292  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.292  6981  7047 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 11:27:32.294  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:27:32.296  6981  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:27:32.296  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:32.296  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:32.296  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:32.296  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:32.296  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:27:32.296  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:27:32.296  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:27:32.297  6981  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:27:32.297  6981  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:27:32.297  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:27:32.297  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:27:32.297  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 11:27:32.297  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:27:32.297  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 11:27:32.299  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnect,ivityInfo: No relevant state changes
08-05 11:27:32.300  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:27:32.304  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 11:27:32.304  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:27:32.305  6981  7047 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 11:27:32.305  6981  7047 I io.jxcore.node.ConnectionHelper: start: OK
08-05 11:27:32.306  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.306  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.306  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.307  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.307  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.307  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:27:32.307  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.307  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.307  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.307  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.307  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.307  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.307  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.307  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.307  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.309  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:32.309  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:32.309  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.309  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.309  6981  7047 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 11:27:32.310  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:27:32.312  6981  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:27:32.312  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:32.312  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:32.312  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:32.312  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:32.312  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name,: f4:f2:6d:22:99:3e
08-05 11:27:32.312  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:27:32.312  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:27:32.313  6981  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:27:32.313  6981  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:27:32.314  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:32.315  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:32.315  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:27:32.315  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:27:32.316  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 11:27:32.316  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:27:32.316  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 11:27:32.318  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 11:27:32.319  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:27:32.320  6981  7047 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 11:27:32.320  6981  7047 I io.jxcore.node.ConnectionHelper: start: OK
08-05 11:27:32.320  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.320  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.320  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.321  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.321  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.321  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.321  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.321  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.321  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:27:32.321  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.321  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.321  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.321  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.321  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.321  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.321  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.322  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.322  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.322  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:32.322  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:32.322  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.322  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.323  6981  7047 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-05 11:27:32.323  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.323  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.323  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.323  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.323  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.323  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.323  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.323  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.324  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.324  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.324  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.324  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.324  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.324  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.324  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.324  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.325  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:32.325  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:32.325  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.325  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.326  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 11:27:32.326  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.326  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.326  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.326  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.326  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.326  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.326  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.326  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.326  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.326  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.326  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.326  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.326  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.326  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.327  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.327  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.327  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:32.327  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:32.327  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.327  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.328  6981  7047 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-05 11:27:32.328  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.328  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.328  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.328  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.329  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.329  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.329  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.329  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.329  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.329  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.329  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.329  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.329  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.329  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.329  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.329  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.330  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:32.330  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:32.330  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.330  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.330  6981  7047 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-05 11:27:32.330  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.330  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.330  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.331  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.331  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.331  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.331  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.331  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.331  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.331  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.331  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.331  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.331  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.331  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:27:32.332  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.332  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.332  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:32.332  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:32.332  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.332  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.332  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 11:27:32.333  6981  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 11:27:32.333  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 11:27:32.333  6981  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 11:27:32.333  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 11:27:32.333  6981  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 11:27:32.333  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.333  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.333  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.333  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.333  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.333  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.333  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.333  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.333  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.333  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.333  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.333  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.333  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.333  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.334  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.334  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.335  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:32.335  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:32.335  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.335  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.335  6981  7047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 11:27:32.335  6981  7047 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 11:27:32.335  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 11:27:32.338  6981  7047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 11:27:32.338  6981  7047 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 11:27:32.338  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 11:27:32.339  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 11:27:32.339  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 11:27:32.339  6981  7047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-05 11:27:32.339  6981  7047 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 11:27:32.339  6981  7047 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-05 11:27:32.340  6981  7047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 11:27:32.340  6981  7047 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 11:27:32.340  6981  7047 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-05 11:27:32.340  6981  7047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 11:27:32.340  6981  7047 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 11:27:32.340  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-05 11:27:32.341  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-05 11:27:32.342  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-05 11:27:32.342  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-05 11:27:32.342  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-05 11:27:32.342  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-05 11:27:32.343  6981  7047 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-05 11:27:32.343  6981  7047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 11:27:32.343  6981  7047 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-05 11:27:32.343  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.343  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.343  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.343  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.343  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.343  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.344  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-05 11:27:32.344  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.344  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.344  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.344  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.344  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.344  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.344  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.344  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.345  6981  7070 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 891)
08-05 11:27:32.350  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.350  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.350  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:32.350  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:32.350  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.350  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.351  6981  7047 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-05 11:27:32.351  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.351  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.351  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.352  6981  7071 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 891
08-05 11:27:32.352  6981  7071 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 891)
08-05 11:27:32.352  6981  7071 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 891)
08-05 11:27:32.352  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.352  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.352  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.352  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.352  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.353  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.353  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.353  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.353  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.353  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.353  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.353  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.353  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.354  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:32.354  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:32.354  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.354  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.354  6981  7047 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-05 11:27:32.355  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.355  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.355  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.355  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.355  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.355  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.355  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.355  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.355  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.355  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.355  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.355  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.355  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.355  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.356  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.356  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.357  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:32.357  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:32.357  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.357  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.357  6981  7047 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-05 11:27:32.357  6981  7047 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-05 11:27:32.357  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 11:27:32.358  6981  7047 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-05 11:27:32.358  6981  7047 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 11:27:32.358  6981  7047 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-05 11:27:32.358  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 11:27:32.358  6981  7047 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-05 11:27:32.358  6981  7047 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 11:27:32.358  6981  7047 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 11:27:32.358  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 11:27:32.358  6981  7047 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-05 11:27:32.358  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.358  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.358  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.360  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.360  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.360  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.360  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.360  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.360  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.360  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.360  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.360  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.361  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.361  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.362  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.362  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.362  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:32.362  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:32.362  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.362  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.363  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.363  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.363  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.363  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.363  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.363  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.363  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.363  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.363  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.369  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.369  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.369  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.369  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.369  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.369  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.369  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.369  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.369  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.370  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.370  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.370  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.370  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.370  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.370  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.370  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.370  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.371  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.371  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.371  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.371  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.371  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 11:27:32.372  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:32.372  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:32.372  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.372  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.374  6981  7047 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-05 11:27:32.374  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:27:32.375  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-05 11:27:32.375  6981  7047 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-05 11:27:32.376  6981  7047 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-05 11:27:32.376  6981  6981 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-05 11:27:32.376  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-05 11:27:32.376  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 11:27:32.382  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.382  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-05 11:27:32.382  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-05 11:27:32.382  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-05 11:27:32.382  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.382  6981  7047 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-05 11:27:32.382  6981  6981 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-05 11:27:32.382  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.382  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.383  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 11:27:32.383  6981  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 11:27:32.383  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 11:27:32.383  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 11:27:32.384  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:32.384  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:32.384  6981  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 11:27:32.384  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.384  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.385  6981  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 11:27:32.385  6981  6981 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 11:27:32.385  6981  6981 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 11:27:32.385  6981  6981 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 11:27:32.385  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.385  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.385  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.385  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.386  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.386  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.386  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.386  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.386  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.386  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.386  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.386  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.386  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.386  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.386  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.387  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.387  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.387  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.387  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.387  6981  7047 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-05 11:27:32.393  6981  7047 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 11:27:32.393  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 11:27:32.394  6981  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 11:27:32.394  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.394  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.394  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.394  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.394  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.394  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.394  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.394  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.394  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.394  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.394  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.394  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.394  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.394  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.395  1036  2049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:32.396  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.396  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.396  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.396  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.397  6981  7072 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:27:32.398  4325  4344 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-05 11:27:32.399  6981  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-05 11:27:32.399  6981  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-05 11:27:32.399  6981  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-05 11:27:32.400  1036  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:32.401  6981  6981 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-05 11:27:32.407  1036  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:32.409  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:32.410  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.410  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.410  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.411  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.411  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.411  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.411  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.411  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.411  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.411  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.411  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.411  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.411  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.411  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.413  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.414  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.414  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.414  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.416  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:32.416  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:32.416  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:32.416  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:32.416  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.416  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.416  6981  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b61bd not in the list
08-05 11:27:32.416  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.416  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
08-05 11:27:32.416  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:32.416  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.416  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.417  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:32.417  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:32.420  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:32.420  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:32.420  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:32.420  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13de63b2 not in the list
,08-05 11:27:32.426  6981  7047 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-05 11:27:32.426  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 11:27:32.429  6981  7047 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-05 11:27:32.429  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 11:27:32.429  6981  7047 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-05 11:27:32.429  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 11:27:32.440  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 11:27:32.440  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-05 11:27:32.441  6981  7047 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-05 11:27:32.441  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 11:27:32.441  6981  7047 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-05 11:27:32.441  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 11:27:32.441  6981  7047 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-05 11:27:32.442  6981  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-05 11:27:32.442  6981  7047 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-05 11:27:32.442  6981  7047 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-05 11:27:32.443  6981  7047 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-05 11:27:32.443  6981  7047 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-05 11:27:32.443  6981  7047 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-05 11:27:32.443  6981  7047 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-05 11:27:32.444  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:32.445  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3512b7b added. We now have 2 listener(s)
08-05 11:27:32.445  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 11:27:32.450  6981  7047 D BluetoothAdapter: enable(): BT is already enabled..!
08-05 11:27:32.452  1036  1938 D WifiServiceImplEx: setWifiEnabled: true pid=6981, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 11:27:32.454  1036  1938 D WifiService: setWifiEnabled: true pid=6981, uid=10118
08-05 11:27:32.454  1036  1938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 11:27:32.460  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:32.460  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f12d98 added. We now have 3 listener(s)
08-05 11:27:32.460  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 11:27:32.464  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:32.464  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e24e9f1 added. We now have 4 listener(s)
08-05 11:27:32.464  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:27:32.466  6981  7070 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-05 11:27:32.466  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:32.466  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@166539d6 added. We now have 5 listener(s)
08-05 11:27:32.466  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:27:32.467  6981  7070 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 891)
08-05 11:27:32.468  1036  1920 D WifiServiceImplEx: setWifiEnabled: false pid=6981, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 11:27:32.468  1036  1920 D WifiService: setWifiEnabled: false pid=6981, uid=10118
08-05 11:27:32.468  1036  1920 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 11:27:32.479  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-05 11:27:32.480  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 11:27:32.480  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-05 11:27:32.481  1036  1695 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:32.481  1036  1535 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 11:27:32.481  1036  1695 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@27594db6 mBinding = false
08-05 11:27:32.481  1036  1535 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 11:27:32.481  1036  1535 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-05 11:27:32.482  1036  1535 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-05 11:27:32.482  1036  1535 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-05 11:27:32.482  1036  1535 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-05 11:27:32.482  1036  1535 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 11:27:32.483  1036  1535 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 11:27:32.484  1036  1535 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 11:27:32.484  1036  1535 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 11:27:32.488  1036  1535 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 11:27:32.488  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 11:27:32.488  1036  1534 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:32.488  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 11:27:32.488  2729  2729 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 11:27:32.489  1036  1535 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 11:27:32.489  1036  1535 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 11:27:32.490  1036  1535 D WifiNative-wlan0: SET ps 1: returned true
08-05 11:27:32.491  1036  2851 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:32.492  1036  1118 D BluetoothManagerService: Message: 2
08-05 11:27:32.493  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:27:32.493  1036  1118 D BluetoothManagerService: Sending off request.
08-05 11:27:32.494  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 11:27:32.494  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 11:27:32.494  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-05 11:27:32.494  4325  4345 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-05 11:27:32.495  4325  4397 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-05 11:27:32.495  4325  4397 D BluetoothAdapterProperties: Setting state to 13
08-05 11:27:32.495  4325  4397 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 11:27:32.495  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:32.495  6981  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:27:32.495  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:32.495  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:32.495  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:32.495  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:32.495  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:27:32.495  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:27:32.495  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:27:32.496  4325  4397 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 11:27:32.496  4325  4397 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-05 11:27:32.496  1036  1118 D BluetoothManagerService: Message: 60
08-05 11:27:32.496  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-05 11:27:32.496  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-05 11:27:32.497  4325  4404 D BluetoothAdapterProperties: Scan Mode:20
08-05 11:27:32.497  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:32.497  6981  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:27:32.497  4325  4397 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 11:27:32.497  6981  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:27:32.498   303   881 D CommandListener: Clearing all IP addresses on wlan0
08-05 11:27:32.499  4325  4702 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
,08-05 11:27:32.499  4325  4702 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:27:32.499  4325  4702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-05 11:27:32.499  4325  4702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-05 11:27:32.499  4325  4702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-05 11:27:32.499  4325  4702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-05 11:27:32.499  4325  4702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-05 11:27:32.499  4325  4702 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-05 11:27:32.504  4325  4397 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 11:27:32.504  4325  4704 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:27:32.504  4325  4738 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:27:32.505  4325  4751 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:27:32.505  4325  4735 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:27:32.505  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-05 11:27:32.505  4325  4511 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-05 11:27:32.506  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:32.506  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:32.506  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:32.506  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:32.506  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:32.506  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:27:32.506  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:27:32.506  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:27:32.506  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:27:32.506  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:27:32.506  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:27:32.506  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:27:32.507  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:27:32.507  4325  4511 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:27:32.507  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:27:32.507  4325  4511 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:27:32.507  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:27:32.507  4325  4511 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:27:32.507  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-05 11:27:32.507  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-05 11:27:32.507  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:32.507  4325  4511 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 11:27:32.507  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:27:32.508  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:32.511  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:32.511  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 ,11:27:32.511  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:32.511  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:32.511  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:32.511  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:27:32.511  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:27:32.511  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:27:32.511  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:27:32.511  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:32.511  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 11:27:32.515  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:32.525  1036  1695 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-05 11:27:32.525  1036  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:32.525  1036  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:32.525  1036  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-05 11:27:32.525  1036  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:32.525  1036  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 11:27:32.528   303  7088 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-05 11:27:32.529  1036  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-05 11:27:32.530  1036  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-05 11:27:32.535  1036  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-05 11:27:32.537  1036  1111 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7090 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-05 11:27:32.539  1036  1116 D DSQN    : Dns fail occured do internet check.
08-05 11:27:32.539  1036  1036 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-05 11:27:32.539  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:32.539  1036  1036 D DSQN    : try Internet connection check
08-05 11:27:32.542  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-05 11:27:32.544  4325  4325 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:32.544  4325  4325 D BluetoothMapService: STATE_TURNING_OFF
08-05 11:27:32.544  4325  4325 V BluetoothMapService: Handler(): got msg=4
08-05 11:27:32.544  4325  4325 D BluetoothMapService: MAP Service closeService in
08-05 11:27:32.545  4325  4325 D BluetoothMapMasInstance: MAP Service shutdown
08-05 11:27:32.545  4325  4325 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 11:27:32.545  4325  4325 V BluetoothMapService: MAP Service closeService out
08-05 11:27:32.547  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:32.547  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:32.547  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:32.547  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:32.547  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:32.547  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:27:32.547  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:32.547  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:32.547  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:27:32.548  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:32.548  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:32.550  4325  4325 V BtOppService: Receiver DISABLED_ACTION 
08-05 11:27:32.550  4325  4325 I BtOppRfcommListener: stopping Accept Thread
08-05 11:27:32.550  4325  4325 V BtOppRfcommListener: close mBtServerSocket
08-05 11:27:32.550  4325  4325 V BtOppRfcommListener: waiting for thread to terminate
08-05 11:27:32.550  4325  4735 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-05 11:27:32.551  4325  4325 V BtOppRfcommListener: done waiting for thread to terminate
08-05 11:27:32.552  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:32.552  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:32.552  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:32.552  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:32.552  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:32.552  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:27:32.552  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:32.552  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:32.552  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:27:32.552  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:32.553  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi,: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:32.571  1036  1111 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7110 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 11:27:32.572  4325  4325 V BtOppService: onDestroy
,08-05 11:27:32.573  1036  1535 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-05 11:27:32.574  1036  1535 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:32.574  1036  1535 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:32.574  1036  1535 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:32.574  1036  1535 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:32.575  1036  1535 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:32.575  1036  1535 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:32.575  4325  4325 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-05 11:27:32.576  1036  1535 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:32.576  1036  1535 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:32.576  1036  1535 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:32.577  1036  1534 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:32.577  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:32.578  1036  1534 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1b37a980
08-05 11:27:32.578  1036  1534 D LGWifiP2pService: P2pDisablingState
08-05 11:27:32.578  1036  1534 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:32.578  1036  1534 D LGWifiP2pService: p2p socket connection lost
08-05 11:27:32.578  1036  1534 D LGWifiP2pService: P2pDisabledState
08-05 11:27:32.579  1036  1036 D WifiHS20: hidePasspointNotification off =false
,08-05 11:27:32.580  1036  1544 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-05 11:27:32.580  1036  1544 D DSQN    : disableDataServiceNotify
08-05 11:27:32.580  1036  1544 D DSQN    : stop dsqn bin
08-05 11:27:32.580  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:32.580  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:32.580  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 11:27:32.581  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-05 11:27:32.581  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-05 11:27:32.584  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:32.584  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:32.584  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 11:27:32.585  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-05 11:27:32.585  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-05 11:27:32.585  1036  1555 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:32.585  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 11:27:32.585  1036  1556 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:32.585  1939  1939 D WfdsService: WifiP2pState is changed : false
08-05 11:27:32.585  1939  2249 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-05 11:27:32.586  1939  2249 D WfdsService: Set the WFDS Monitor: false
08-05 11:27:32.586  1036  1544 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-05 11:27:32.586  1036  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:32.586  1036  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:27:32.587  1939  2249 D WfdsMonitor: WFDS Monitor is stopped
08-05 11:27:32.587  1939  2249 D WfdsService: STATE : WfdsDisabledState - enter
08-05 11:27:32.587  1939  2769 D CtrlSupplicant: Received on exit socket, terminate
08-05 11:27:32.587  1939  2769 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-05 11:27:32.587  1939  2769 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-05 11:27:32.587  1939  2769 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-05 11:27:32.587  1939  2250 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-05 11:27:32.587  1036  1544 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:27:32.588  1036  1544 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-05 11:27:32.588  1036  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:32.588  1036  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:32.588  1036  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-05 11:27:32.588  1036  1544 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unk,nown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-05 11:27:32.588  1036  1544 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-05 11:27:32.588  1036  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 11:27:32.588  1036  1535 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-05 11:27:32.588  1036  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:32.589  1036  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 11:27:32.589  1036  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:32.589  1036  1534 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:32.589  1036  1544 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:32.589  1036  1534 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:32.589  1036  1544 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:32.589   303  7120 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 11:27:32.589  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 11:27:32.589  1939  2249 W WfdsService: DefaultState - msg [9445378] is not handled
08-05 11:27:32.589  2729  2729 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 11:27:32.589  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 11:27:32.589  1036  1535 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 11:27:32.589  1036  1535 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 11:27:32.590  1036  1535 D WifiNative-wlan0: SET ps 1: returned true
08-05 11:27:32.590   303   881 D CommandListener: Clearing all IP addresses on wlan0
08-05 11:27:32.590  1036  7103 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
,08-05 11:27:32.591  1036  7099 D DSQN    : ThreadInternetCheck internet check NOK 
08-05 11:27:32.591  1036  7099 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
08-05 11:27:32.591  1036  1544 D NetworkManagementService: Removing idletimer
08-05 11:27:32.592  1036  1544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:32.592  1036  1544 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-05 11:27:32.592  1602  2121 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-05 11:27:32.592  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:32.593  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 11:27:32.593  1036  1533 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 11:27:32.594  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 11:27:32.594  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 11:27:32.594  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 11:27:32.594  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 11:27:32.594  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 11:27:32.595  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 11:27:32.595  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 11:27:32.595  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 11:27:32.595  1036  1535 D WifiNative-p2p0: doBoolean: TERMINATE
08-05 11:27:32.595  1036  1533 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 11:27:32.595  1036  1535 D WifiNative-p2p0: TERMINATE: returned true
08-05 11:27:32.595  1036  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:27:32.595  1036  1535 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:27:32.595  1036  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 11:27:32.596  1036  1535 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:32.596  1036  1535 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 11:27:32.597  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-05 11:27:32.597  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:32.597  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:32.597  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 11:27:32.600  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-05 11:27:32.601  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-05 11:27:32.602  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:27:32.602  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,08-05 11:27:32.604  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:32.604  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:27:32.604  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:32.604  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:32.604  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:32.604  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:32.604  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:32.604  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:27:32.604  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:27:32.604  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:32.604  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:32.604  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:27:32.605  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:32.605  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:32.608  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:32.608  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:32.608  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:32.608  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:32.608  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:27:32.608  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:27:32.608  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:32.608  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:32.608  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:27:32.608  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:32.608  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:32.620  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:32.620  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:27:32.621  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 11:27:32.639  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-05 11:27:32.640  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:32.640  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:32.651  7110  7110 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 11:27:32.651  7110  7110 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-05 11:27:32.651  7110  7110 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 11:27:32.651  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 11:27:32.651  7110  7110 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-05 11:27:32.652  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:32.652  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:32.652  7110  7110 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 11:27:32.652  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 11:27:32.652  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:27:32.652  7110  7110 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 11:27:32.653  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 11:27:32.654  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:32.660  7090  7090 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 11:27:32.661  7090  7090 W LG Account v2.2: No ProfileInfo entries
08-05 11:27:32.661  7090  7090 I LG Account v2.2: isEnabled: false
08-05 11:27:32.661  7090  7090 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 11:27:32.661  7090  7090 I Feature : [Lifetracker]Country: EU
08-05 11:27:32.661  7090  7090 I Feature : [Lifetracker]Operator: OPEN
08-05 11:27:32.661  7090  7090 I Feature : [Lifetracker]Ranking support: false
08-05 11:27:32.661  7090  7090 I Feature : [Lifetracker]Comfort support: false
08-05 11:27:32.661  7090  7090 I Feature : [Lifetracker]Accessory: true
08-05 11:27:32.661  7090  7090 I Feature : [Lifetracker]Health device: true
08-05 11:27:32.661  7090  7090 I Feature : [Lifetracker]Extra Pedometer: false
08-05 11:27:32.661  7090  7090 I Feature : [Lifetracker]Blood glucose device: false
08-05 11:27:32.661  7090  7090 I Feature : [Lifetracker]Device Number: 3
08-05 11:27:32.667  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 11:27:32.671  2729  2729 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-05 11:27:32.671  2729  2729 I wpa_supplicant: monitor socket send errors count : 1
08-05 11:27:32.671  2729  2729 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1939-2\x00 that cannot receive messages
,08-05 11:27:32.672  1036  2768 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-05 11:27:32.672  1036  2768 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 11:27:32.699  1036  2851 D DhcpStateMachine: StoppedState
08-05 11:27:32.699  1036  2851 D DhcpStateMachine: StoppedState{ when=-109ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 11:27:32.708  2729  2729 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 11:27:32.708  1036  2768 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-05 11:27:32.708  1036  2768 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 11:27:32.708  1036  2768 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 11:27:32.708  1036  2768 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-05 11:27:32.709  2729  2729 W wpa_supplicant: USIM:  scard_deinit function
08-05 11:27:32.709  1036  1535 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=330978
08-05 11:27:32.710  1036  1535 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=330978
,08-05 11:27:32.710  1036  1118 D Tethering: InitialState.processMessage what=4
08-05 11:27:32.710  1036  2768 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:27:32.710  1036  2768 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 11:27:32.711  1036  1535 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=330979  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 11:27:32.711  1036  1535 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=330980  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 11:27:32.712  1036  1051 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7133 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 11:27:32.713  1036  1051 I ActivityManager: Killing 6256:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-05 11:27:32.750  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-05 11:27:32.751  1036  1535 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-05 11:27:32.751  1036  1535 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-05 11:27:32.752  1036  1535 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:32.753  1036  1535 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:32.761  1036  1643 W libprocessgroup: failed to open /acct/uid_10014/pid_6256/cgroup.procs: No such file or directory
,08-05 11:27:32.779  2729  2729 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-05 11:27:32.780  1036  2768 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-05 11:27:32.780  1036  2768 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-05 11:27:32.780  1036  2768 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-05 11:27:32.781  1036  1535 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-05 11:27:32.814  7133  7133 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-05 11:27:32.824  7133  7133 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 11:27:32.825  7133  7133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:27:32.830  1036  2030 I ActivityManager: Killing 2144:com.lge.music/u0a34 (adj 15): empty #17
,08-05 11:27:32.841  7110  7110 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 11:27:32.866   309  2164 V AudioFlinger: 2144 died, releasing its sessions
,08-05 11:27:32.866   309  2164 V AudioFlinger:  pid 1850 @ 0
08-05 11:27:32.866   309  2164 V AudioFlinger:  pid 3391 @ 1
08-05 11:27:32.866   309  2164 V AudioFlinger:  pid 3391 @ 2
08-05 11:27:32.886  6981  6981 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 11:27:32.896  1036  1994 W libprocessgroup: failed to open /acct/uid_10034/pid_2144/cgroup.procs: No such file or directory
,08-05 11:27:32.903  4325  4325 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 11:27:32.903  4325  4325 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:32.904  4325  4325 V BluetoothPbapReceiver: ***********state = 13
08-05 11:27:32.904  1939  1939 D WfdsService: Supplicant Connection state is changed : false
08-05 11:27:32.904  1036  1535 D WifiOffDelayIfNotUsed: stopMonitoring
08-05 11:27:32.905  1036  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:27:32.905  1036  1535 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:27:32.905  1036  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 11:27:32.906  1939  2249 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-05 11:27:32.906  1939  2249 D WfdsService: Set the WFDS Monitor: false
08-05 11:27:32.906  1939  2249 D WfdsMonitor: WFDS Monitor is stopped
08-05 11:27:32.907  4325  4325 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-05 11:27:32.915  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:32.915  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 11:27:32.921  2448  2448 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 11:27:32.923  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-05 11:27:32.924  4325  4325 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:32.924  4325  4325 V BluetoothPbapService: state: 13
08-05 11:27:32.924  4325  4325 V BluetoothPbapService: Pbap Service closeService in
08-05 11:27:32.925  1036  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-05 11:27:32.925  1036  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-05 11:27:32.926  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:32.928  2079  2079 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 11:27:32.929  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:32.929  4325  4325 V BluetoothPbapService: successfully stopped pbap service
08-05 11:27:32.929  4325  4325 V BluetoothPbapService: Pbap Service closeService out
08-05 11:27:32.930  4325  4325 V BluetoothPbapService: Pbap Service onDestroy
08-05 11:27:32.930  4325  4325 V BluetoothPbapService: Pbap Service closeService in
08-05 11:27:32.930  4325  4325 V BluetoothPbapService: Pbap Service closeService out
08-05 11:27:32.930  4325  4325 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-05 11:27:32.940  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:27:32.976  7110  7110 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 11:27:32.976  7110  7110 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 11:27:32.985  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:32.994  1036  1118 D BluetoothManagerService: Message: 20
08-05 11:27:32.994  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4be989:true
,08-05 11:27:33.009  1036  1118 D BluetoothManagerService: Message: 30
,08-05 11:27:33.016  1036  1118 D BluetoothManagerService: Message: 30
,08-05 11:27:33.019  7110  7110 D LocalBluetoothProfileManager: Adding local MAP profile
08-05 11:27:33.021  7110  7110 D BluetoothMap: Create BluetoothMap proxy object
08-05 11:27:33.021  1036  1118 D BluetoothManagerService: Message: 30
08-05 11:27:33.027  1036  1118 D BluetoothManagerService: Message: 30
,08-05 11:27:33.031  7110  7110 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-05 11:27:33.034  7110  7110 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-05 11:27:33.065  7110  7110 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-05 11:27:33.070  7110  7110 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-05 11:27:33.085  7110  7110 D DockEventReceiver: finishStartingService: stopping service
,08-05 11:27:33.102  7110  7110 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-05 11:27:33.107  7110  7110 D BluetoothInputDevice: Proxy object connected
08-05 11:27:33.109  7110  7110 D HidProfile: Bluetooth service connected
08-05 11:27:33.111  7110  7110 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 11:27:33.113  7110  7110 D PanProfile: Bluetooth service connected
08-05 11:27:33.114  7110  7110 D BluetoothMap: Proxy object connected
08-05 11:27:33.115  7110  7110 D MapProfile: Bluetooth service connected
08-05 11:27:33.115  7110  7110 D BluetoothMap: getConnectedDevices()
,08-05 11:27:33.116  7110  7110 D BluetoothMap: Bluetooth is Not enabled
08-05 11:27:33.117  7110  7110 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-05 11:27:33.123  7110  7110 D BluetoothPermissionRequest: onReceive
08-05 11:27:33.126  7110  7110 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-05 11:27:33.138  1036  1938 I ActivityManager: Killing 6430:com.android.defcontainer/u0a4 (adj 15): empty #17
08-05 11:27:33.143  7110  7110 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-05 11:27:33.176  4325  4325 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-05 11:27:33.176  4325  4325 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-05 11:27:33.177  4325  4325 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-05 11:27:33.178  1036  1643 W libprocessgroup: failed to open /acct/uid_10004/pid_6430/cgroup.procs: No such file or directory
,08-05 11:27:33.255  1036  1957 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7165 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-05 11:27:33.262  4325  4325 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:33.262  4325  4325 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 11:27:33.266  4325  4325 V BluetoothFtpService: Ftp Service onStartCommand
08-05 11:27:33.266  4325  4325 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:33.267  4325  4325 V BluetoothFtpService: Ftp Service closeService
08-05 11:27:33.267  4325  4325 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-05 11:27:33.274  4325  4325 V BluetoothFtpService: successfully stopped ftp service
08-05 11:27:33.275  4325  4325 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:27:33.275  4325  4325 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 11:27:33.275  4325  4325 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 11:27:33.276  4325  4325 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:33.276  4325  4325 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-05 11:27:33.276  4325  4325 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-05 11:27:33.279   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 469us total 25.070ms
08-05 11:27:33.280  4325  4325 V BluetoothFtpService: Ftp Service onDestroy
08-05 11:27:33.280  4325  4325 V BluetoothFtpService: Ftp Service closeService
08-05 11:27:33.281  4325  4325 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:33.281  4325  4325 V BluetoothSapService: state: 13
08-05 11:27:33.281  4325  4325 V BluetoothSapService: Stopping SAP server process
08-05 11:27:33.283  4325  4325 V BluetoothSapService: Sap Service closeSapService in
08-05 11:27:33.283  4325  4325 V BluetoothSapService: Close listen Socket : 
08-05 11:27:33.283  4325  4325 V BluetoothSapService: Close rfcomm Socket : 
08-05 11:27:33.283  4325  4325 V BluetoothSapService: Close sapd  Socket : 
08-05 11:27:33.284  4325  4325 V BluetoothSapService: Sap Service closeSapService out
08-05 11:27:33.285  4325  4325 V BluetoothSapService: Sap Service onDestroy
08-05 11:27:33.285  4325  4325 V BluetoothSapService: Sap Service closeSapService in
08-05 11:27:33.285  4325  4325 V BluetoothSapService: Close listen Socket : 
08-05 11:27:33.285  4325  4325 V BluetoothSapService: Close rfcomm Socket : 
08-05 11:27:33.285  4325  4325 V BluetoothSapService: Close sapd  Socket : 
08-05 11:27:33.285  4325  4325 V BluetoothSapService: Sap Service closeSapService out
08-05 11:27:33.301   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 469us total 20.913ms
,08-05 11:27:33.321   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 18.845ms
,08-05 11:27:33.358  1036  2030 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7182 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 11:27:33.391  7165  7165 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 11:27:33.416  7165  7165 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-05 11:27:33.444  7182  7182 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 11:27:33.455  7165  7165 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-05 11:27:33.455  7165  7165 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-05 11:27:33.455  7165  7165 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-05 11:27:33.456  7165  7165 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-05 11:27:33.456  7165  7165 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-05 11:27:33.458  7165  7165 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-05 11:27:33.463  7165  7165 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-05 11:27:33.469  1036  1051 I ActivityManager: Killing 6548:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-05 11:27:33.472  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 11:27:33.476  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:27:33.508  4325  4404 D bt_hci_bdroid: cleanup
08-05 11:27:33.509  4325  4513 I bt_lpm  : LPM is already off!!!
,08-05 11:27:33.509  4325  4676 I bt_userial_mct: exiting userial_read_thread
08-05 11:27:33.509  4325  4676 D bt_userial_mct: Leaving userial_evt_read_thread()
08-05 11:27:33.509  4325  4511 W bt-btif : ag scb idx 1 not allocated
08-05 11:27:33.509  4325  4511 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 11:27:33.509  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:27:33.509  4325  4511 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:27:33.509  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:27:33.509  4325  4511 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:27:33.509  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:27:33.509  4325  4511 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:27:33.509  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:27:33.509  4325  4511 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:27:33.509  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:27:33.509  4325  4511 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:27:33.509  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:27:33.509  4325  4511 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:27:33.509  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:27:33.510  4325  4511 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:27:33.510  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:27:33.510  4325  4404 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-05 11:27:33.510  4325  4513 I bt_vendor: hw_epilog_process
08-05 11:27:33.510  4325  4511 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:27:33.510  4325  4511 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:27:33.510  4325  4511 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:27:33.510  4325  4511 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 11:27:33.511  4325  4404 D bt_hci_bdroid: cleanup Finalizing cleanup
08-05 11:27:33.511  4325  4404 D bt_userial_mct: userial_close
08-05 11:27:33.511  4325  4404 E bt_userial_mct: pthread_join() FAILED result:3
08-05 11:27:33.511  4325  4404 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-05 11:27:33.513  1036  2030 W libprocessgroup: failed to open /acct/uid_10008/pid_6548/cgroup.procs: No such file or directory
08-05 11:27:33.517  7165  7165 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 11:27:33.519  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:27:33.520  7165  7165 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-05 11:27:33.525  7133  7133 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 11:27:33.525  7133  7133 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 11:27:33.525  7133  7133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:27:33.526  7165  7165 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-05 11:27:33.529  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:27:33.537  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:33.547  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 11:27:33.548  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:27:33.551  7165  7165 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 11:27:33.555  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:27:33.561  7133  7133 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 11:27:33.561  7133  7133 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 11:27:33.562  7133  7133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 11:27:33.567  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 11:27:33.569  4325  4404 D bt_hci_bdroid: set_power 0
08-05 11:27:33.569  4325  4404 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-05 11:27:33.569  4325  4404 I bt_vendor: bluetooth satus is on
08-05 11:27:33.569  4325  4404 I bt_vendor: bt-vendor : resetting BT status
08-05 11:27:33.569  4325  4404 I bt_vendor: Starting hciattach daemon
08-05 11:27:33.569  4325  4404 I bt_vendor: try to set false
08-05 11:27:33.570  4325  4404 I bt_vendor: Starting hciattach daemon
08-05 11:27:33.570  4325  4404 I bt_vendor: try to set false
,08-05 11:27:33.571  4325  4404 I bt_vendor: cleanup
08-05 11:27:33.571  4325  4511 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-05 11:27:33.572  4325  4404 I GKI_LINUX: GKI_exit_task 0 done
08-05 11:27:33.572  4325  4404 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-05 11:27:33.573  4325  4397 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 11:27:33.580  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 11:27:33.582  4325  4325 D HeadsetService: Received stop request...Stopping profile...
08-05 11:27:33.588  4325  4325 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 11:27:33.588  4325  4325 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 11:27:33.588  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14ae4c63
08-05 11:27:33.589  4325  4446 D HeadsetStateMachine: Exit Disconnected: -1
08-05 11:27:33.591  4325  4325 D A2dpService: Received stop request...Stopping profile...
,08-05 11:27:33.592  4325  4499 D A2dpStateMachine: Exit Disconnected: -1
08-05 11:27:33.594  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-05 11:27:33.594  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-05 11:27:33.594  1036  1036 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
08-05 11:27:33.595  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-05 11:27:33.595  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-05 11:27:33.596  4325  4325 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-05 11:27:33.597  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-05 11:27:33.599  4325  4397 D BluetoothAdapterState: Stopping profile services that were post enabled
08-05 11:27:33.600  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:27:33.600  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:27:33.601  4325  4325 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-05 11:27:33.602  4325  4325 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 11:27:33.602  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14ae4c63
08-05 11:27:33.602  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-05 11:27:33.602  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-05 11:27:33.603  4325  4325 D HidService: Received stop request...Stopping profile...
08-05 11:27:33.603  7165  7165 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 11:27:33.603  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14ae4c63
,08-05 11:27:33.658  1036  2030 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7203 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-05 11:27:33.662  4325  4325 D HealthService: Received stop request...Stopping profile...
08-05 11:27:33.662  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14ae4c63
08-05 11:27:33.665  7110  7110 D BluetoothInputDevice: Proxy object disconnected
08-05 11:27:33.665  7110  7110 D HidProfile: Bluetooth service disconnected
,08-05 11:27:33.666  4325  4325 D PanService: Received stop request...Stopping profile...
08-05 11:27:33.667  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14ae4c63
08-05 11:27:33.668  7110  7110 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 11:27:33.668  7110  7110 D PanProfile: Bluetooth service disconnected
08-05 11:27:33.669  4325  4325 D HeadsetStateMachine: Unbinding service...
08-05 11:27:33.671  4325  4325 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 11:27:33.671  4325  4325 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 11:27:33.671  4325  4325 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 11:27:33.671  4325  4325 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 11:27:33.671  4325  4325 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 11:27:33.671  4325  4325 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 11:27:33.671  4325  4325 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 11:27:33.672  4325  4325 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 11:27:33.673  4325  4325 D BtGatt.GattService: Received stop request...Stopping profile...
08-05 11:27:33.673  4325  4325 D BtGatt.GattService: stop()
08-05 11:27:33.673  4325  4325 D BtGatt.AdvertiseManager: advertise clients cleared
,08-05 11:27:33.679  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14ae4c63
08-05 11:27:33.680  4325  4325 D BluetoothMapService: Received stop request...Stopping profile...
08-05 11:27:33.680  4325  4325 D BluetoothMapService: stop()
08-05 11:27:33.681  4325  4325 D BluetoothMapEmailAppObserver: deinitObservers()
08-05 11:27:33.681  4325  4325 D BluetoothMapEmailAppObserver: removeReceiver()
08-05 11:27:33.682  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14ae4c63
08-05 11:27:33.683  4325  4325 I BluetoothA2dpServiceJni: cleanupNative
08-05 11:27:33.683  4325  4500 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 11:27:33.683  7110  7110 D BluetoothMap: Proxy object disconnected
08-05 11:27:33.683  7110  7110 D MapProfile: Bluetooth service disconnected
08-05 11:27:33.683  4325  4325 I GKI_LINUX: GKI_exit_task 2 done
08-05 11:27:33.683  4325  4325 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-05 11:27:33.684  4325  4325 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 11:27:33.684  4325  4325 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 11:27:33.684  4325  4325 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 11:27:33.684  4325  4325 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 11:27:33.684  4325  4325 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 11:27:33.684  4325  4325 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 11:27:33.684  4325  4325 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 11:27:33.686  4325  4325 V BluetoothMapService: Handler(): got msg=4
08-05 11:27:33.686  4325  4325 D BluetoothMapService: MAP Service closeService in
08-05 11:27:33.686  4325  4325 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 11:27:33.686  4325  4325 V BluetoothMapService: MAP Service closeService out
08-05 11:27:33.686  4325  4325 D BluetoothMapService: cleanup()
08-05 11:27:33.686  4325  4325 D BluetoothMapService: MAP Service closeService in
08-05 11:27:33.686  4325  4325 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 11:27:33.686  4325  4325 V BluetoothMapService: MAP Service closeService out
08-05 11:27:33.686  4325  4397 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-05 11:27:33.686  4325  4397 D BluetoothAdapterProperties: Setting state to 10
08-05 11:27:33.686  4325  4397 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-05 11:27:33.687  1036  1118 D BluetoothManagerService: Message: 60
08-05 11:27:33.687  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-05 11:27:33.687  4325  4397 I BluetoothAdapterState: Entering OffState
08-05 11:27:33.687  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-05 11:27:33.687  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:27:33.687  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 11:27:33.687  7110  7129 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 11:27:33.688  7110  7128 D BluetoothPan: onBluetoothStateChange on: false
08-05 11:27:33.688  7110  7129 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-05 11:27:33.689  7110  7128 D BluetoothMap: onBluetoothStateChange: up=false
08-05 11:27:33.692  1850  4887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:27:33.693  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:27:33.694  1850  4883 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:27:33.695  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-05 11:27:33.695  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-05 11:27:33.697  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-05 11:27:33.697  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-05 11:27:33.698  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@27594db6 mBinding = false
08-05 11:27:33.698  1036  1118 D BluetoothManagerService: Sending unbind request.
08-05 11:27:33.700  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-05 11:27:33.703  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:27:33.704  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:27:33.705  7110  7110 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 11:27:33.706  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:33.706  1939  2117 D LGBluetoothAPIService: Message: 2
08-05 11:27:33.706  7110  7110 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-05 11:27:33.706  7110  7110 D LGBluetoothEventManager: [BTUI] clear device connection state
08-05 11:27:33.706  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 11:27:33.707  1939  2117 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3ea7c262 mBinding = false
08-05 11:27:33.707  1939  2117 D LGBluetoothAPIService: Sending unbind request.
08-05 11:27:33.709  4325  4404 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-05 11:27:33.709  4325  4325 I GKI_LINUX: GKI_exit_task 1 done
08-05 11:27:33.709  4325  4325 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-05 11:27:33.710  4325  4325 I BluetoothServiceJni: cleanupNative: return from cleanup
08-05 11:27:33.710  4325  4325 I art     : --- WEIRD: removing null entry 246
08-05 11:27:33.710  4325  4325 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-05 11:27:33.710  4325  4325 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-05 11:27:33.714  4325  4325 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-05 11:27:33.714  1602  1602 D BluetoothAdapter: 117580635: getState() :  mService = null. Returning STATE_OFF
08-05 11:27:33.714  1602  1602 D BluetoothAdapter: 117580635: getState() :  mService = null. Returning STATE_OFF
08-05 11:27:33.715  7110  7110 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 11:27:33.717  4325  4325 I art     : System.exit called, status: 0
08-05 11:27:33.717  4325  4325 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-05 11:27:33.730  7110  7110 D DockEventReceiver: finishStartingService: stopping service
,08-05 11:27:33.741   309  1383 V AudioFlinger: 4325 died, releasing its sessions
08-05 11:27:33.741   309  1383 V AudioFlinger:  pid 1850 @ 0
08-05 11:27:33.741   309  1383 V AudioFlinger:  pid 3391 @ 1
08-05 11:27:33.741   309  1383 V AudioFlinger:  pid 3391 @ 2
08-05 11:27:33.742  7110  7110 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-05 11:27:33.759  1036  1993 I ActivityManager: Process com.android.bluetooth (pid 4325) has died
,08-05 11:27:33.759  1036  1993 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-05 11:27:33.764  2079  2079 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 11:27:33.777  7110  7110 D BluetoothPermissionRequest: onReceive
08-05 11:27:33.780  7110  7110 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 11:27:33.780  7110  7110 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-05 11:27:33.783  7110  7110 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 11:27:33.844  1036  1884 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7227 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-05 11:27:33.856  7133  7133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:27:33.860  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 11:27:33.872  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:33.892  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-05 11:27:33.893  7110  7110 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 11:27:33.893  7110  7110 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 11:27:33.893  7110  7110 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 11:27:33.895  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-05 11:27:33.906  7203  7247 W FormManager: Network not available. Please check & try again.
,08-05 11:27:33.908  7110  7110 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 11:27:33.908  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 11:27:33.908  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 11:27:33.908  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 11:27:33.908  7110  7110 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 11:27:33.909  7110  7110 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 11:27:33.919  7203  7248 V FormManager: Network unavailable.
,08-05 11:27:33.922  7203  7248 V FormManager: Network unavailable.
08-05 11:27:34.052  1036  1574 I art     : Explicit concurrent mark sweep GC freed 51105(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.032ms total 144.732ms
,08-05 11:27:34.055  1036  2049 I ActivityManager: Killing 6580:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-05 11:27:34.060  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:27:34.065  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 11:27:34.066  7227  7227 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-05 11:27:34.066  7227  7227 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 11:27:34.067  7227  7227 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-05 11:27:34.067  7227  7227 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 11:27:34.069  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:27:34.082  7227  7227 D BluetoothAdapterApp: Loading JNI Library
,08-05 11:27:34.105  7227  7227 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1dd05048 Instance Count = 1
,08-05 11:27:34.122  1036  2031 W libprocessgroup: failed to open /acct/uid_10011/pid_6580/cgroup.procs: No such file or directory
,08-05 11:27:34.122  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:27:34.125  7227  7227 D BluetoothAdapterApp: onCreate
08-05 11:27:34.136  7133  7133 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-05 11:27:34.136  7133  7133 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 11:27:34.136  7133  7133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 11:27:34.140  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 11:27:34.149  4787  7256 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:27:34.151  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 11:27:34.154  4787  7256 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 11:27:34.154  4787  7254 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 11:27:34.159  7203  7257 W FormManager: Network not available. Please check & try again.
,08-05 11:27:34.166  7227  7227 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-05 11:27:34.166  7227  7227 D ProfileConfigQcom: Adding HeadsetService
,08-05 11:27:34.166  7227  7227 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-05 11:27:34.167  7227  7227 D ProfileConfigQcom: Adding A2dpService
08-05 11:27:34.167  7227  7227 D ProfileConfigQcom: [BTUI] HidService is supported
08-05 11:27:34.167  7227  7227 D ProfileConfigQcom: Adding HidService
,08-05 11:27:34.167  7227  7227 D ProfileConfigQcom: [BTUI] HealthService is supported
08-05 11:27:34.167  7227  7227 D ProfileConfigQcom: Adding HealthService
08-05 11:27:34.168  7227  7227 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-05 11:27:34.168  7227  7227 D ProfileConfigQcom: [BTUI] PanService is supported
08-05 11:27:34.169  7227  7227 D ProfileConfigQcom: Adding PanService
08-05 11:27:34.169  7227  7227 D ProfileConfigQcom: [BTUI] GattService is supported
08-05 11:27:34.169  7227  7227 D ProfileConfigQcom: Adding GattService
08-05 11:27:34.169  7227  7227 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-05 11:27:34.169  7227  7227 D ProfileConfigQcom: Adding BluetoothMapService
08-05 11:27:34.170  7227  7227 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-05 11:27:34.171  7203  7258 V FormManager: Network unavailable.
,08-05 11:27:34.172  7227  7227 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-05 11:27:34.179  7203  7258 V FormManager: Network unavailable.
08-05 11:27:34.180  7165  7165 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 11:27:34.181  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 11:27:34.181  7165  7165 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-05 11:27:34.182  7110  7110 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-05 11:27:34.186  7227  7227 V LGMDMManagerInternal: Create singleton instance
08-05 11:27:34.219  7165  7165 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:27:34.219  7165  7165 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 11:27:34.231  7165  7165 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-05 11:27:34.233  7165  7165 V SoundPool: load: fd=31, offset=10857164, length=17813, priority=1
08-05 11:27:34.233  7165  7165 V SoundPool: create sampleID=1, fd=30, offset=17813 length=10857164
,08-05 11:27:34.233  7165  7165 V SoundPool: doLoad: loading sample sampleID=1
08-05 11:27:34.235  7165  7165 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 11:27:34.235  7165  7263 V SoundPool: Start decode
08-05 11:27:34.235  7165  7263 V MediaPlayer[Native]: decode(30, 10857164, 17813)
08-05 11:27:34.237   309  2164 V MediaPlayerService: decode(23, 10857164, 17813)
08-05 11:27:34.237   309  2164 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-05 11:27:34.237   309  2164 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-05 11:27:34.237   309  2164 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-05 11:27:34.237   309  2164 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-05 11:27:34.237   309  2164 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-05 11:27:34.237   309  2164 V MediaPlayerService: player type = 3
08-05 11:27:34.237   309  2164 V AwesomePlayer: AwesomePlayer create()
08-05 11:27:34.238   309  2164 V AwesomePlayer: reset_l() 
08-05 11:27:34.238   309  2164 V AwesomePlayer: cancelPlayerEvents
08-05 11:27:34.238   309  2164 V AwesomePlayer: setAudioSink() 
08-05 11:27:34.238   309  2164 V AwesomePlayer: reset_l() 
08-05 11:27:34.238   309  2164 V AudioCache: notify(0xb54748c0, 8, 0, 0)
08-05 11:27:34.238   309  2164 V AudioCache: ignored
08-05 11:27:34.238   309  2164 V AwesomePlayer: cancelPlayerEvents
08-05 11:27:34.239   309  2164 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-05 11:27:34.239   309  2164 V AwesomePlayer: setDataSource_l dataSource
08-05 11:27:34.239   309  2164 V LGParserOSAL: SniffLGParser start
08-05 11:27:34.239   309  2164 V LGParserOSAL: MainType:5, SubType=0
08-05 11:27:34.239   309  2164 V LGParserOSAL: #### check Mime : application/ogg
08-05 11:27:34.239   309  2164 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-05 11:27:34.239   309  2164 E MediaExtractor: Use LGExtractor :application/ogg 
08-05 11:27:34.243  6875  6875 D UEI.SmartControl: QS Service created
,08-05 11:27:34.250  7165  7165 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-05 11:27:34.262  6875  6875 I UEI.SmartControl: Service initServices...
08-05 11:27:34.262  7165  7165 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 11:27:34.262  6875  6875 D UEI.SmartControl: QS start get config
08-05 11:27:34.263  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 11:27:34.280  7227  7227 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:34.281  7165  7165 V LGMDMManager: Create singleton instance
,08-05 11:27:34.286  7227  7227 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:27:34.287  7227  7227 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 11:27:34.287  7227  7227 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 11:27:34.288  7227  7227 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:34.288  7227  7227 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-05 11:27:34.297  7182  7182 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-05 11:27:34.300   309  2164 V LGParserOSAL: supported mime: application/ogg
08-05 11:27:34.300   309  2164 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-05 11:27:34.300   309  2164 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-05 11:27:34.300   309  2164 V AwesomePlayer: mBitrate = -1 bits/sec
08-05 11:27:34.300   309  2164 V AwesomePlayer: AudioTrack Setting
08-05 11:27:34.300   309  2164 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-05 11:27:34.300   309  2164 V AwesomePlayer: setAudioSource() 
08-05 11:27:34.300   309  2164 V MediaPlayerService: prepare
08-05 11:27:34.300   309  2164 V AwesomePlayer: prepareAsync_l() 
08-05 11:27:34.301   309  2164 V MediaPlayerService: wait for prepare
08-05 11:27:34.301   309  7265 V AwesomePlayer: onPrepareAsyncEvent() 
08-05 11:27:34.301   309  7265 V AwesomePlayer: initAudioDecoder() 
08-05 11:27:34.301   309  7265 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 11:27:34.301   309  7265 V AudioSystem: isOffloadSupported()
08-05 11:27:34.301   309  7265 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 11:27:34.301   309  7265 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 11:27:34.301   309  7265 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 11:27:34.302   309  7265 V AwesomePlayer: getUseOffload() = 0 
08-05 11:27:34.302   309  7265 V OMXCodec: OMXCodec::Create
08-05 11:27:34.302   309  7265 V OMXCodec: findMatchingCodecs()
08-05 11:27:34.302   309  7265 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-05 11:27:34.302   309  7265 V OMXCodec: matchingCodecs.size()=1
08-05 11:27:34.302   309  7265 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-05 11:27:34.304   309  7265 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-05 11:27:34.304   309  7265 V LGCodecAdapter: LG Codec Adapter start
08-05 11:27:34.304   309  7265 V OMXCodec: OMXCodec Createtor
08-05 11:27:34.304   309  7265 V OMXCodec: setComponentRole
08-05 11:27:34.304   309  7265 V OMXCodec: configureCodec protected=0
08-05 11:27:34.304   309  7265 V LGCodecAdapter: called getLGCodecSpecificData
08-05 11:27:34.304   309  7265 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-05 11:27:34.304   309  7265 V LGCodecOSAL: Called LGconfigureCodecMETA
08-05 11:27:34.304   309  7265 V LGCodecOSAL: Called LGconfigureCodecMSG
08-05 11:27:34.304   309  7265 V LGCodecOSAL: Not support LGCodec
08-05 11:27:34.304   309  7265 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 11:27:34.304   309  7265 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-05 11:27:34.304   309  7265 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-05 11:27:34.304   309  7265 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-05 11:27:34.304   309  7265 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 11:27:34.304   309  7265 V AudioSystem: isOffloadSupported()
08-05 11:27:34.304   309  7265 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 11:27:34.304   309  7265 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 11:27:34.304   309  7265 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-05 11:27:34.304   309  7265 V OMXCodec: init()
08-05 11:27:34.304   309  7265 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-05 11:27:34.304   309  7265 V OMXCodec: allocateBuffers
08-05 11:27:34.304   309  7265 V OMXCodec: allocateBuffersOnPort portIndex=0
08-05 11:27:34.304   309  7265 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-05 11:27:34.305   309  7265 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
08-05 11:27:34.305   309  7265 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
08-05 11:27:34.305   309  7265 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-05 11:27:34.305   309  7265 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-05 11:27:34.305   309  7265 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 11:27:34.305   309  7265 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 11:27:34.305   309  7265 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
08-05 11:27:34.305   309  7265 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-05 11:27:34.305   309  7265 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-05 11:27:34.305   309  7265 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
08-05 11:27:34.305   309  7265 V OMXCodec: init() mAsyncCompletion wait!!! 
08-05 11:27:34.305   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 11:27:34.305   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 11:27:34.305   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-05 11:27:34.305   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-05 11:27:34.305   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-05 11:27:34.305   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-05 11:27:34.305   309  7265 V OMXCodec: init() mAsyncCompletion wait free! 
08-05 11:27:34.305   309  7265 V AwesomePlayer: finishAsyncPrepare_l() 
08-05 11:27:34.305   309  7265 V AudioCache: notify(0xb54748c0, 5, 0, 0)
08-05 11:27:34.305   309  7265 V AudioCache: ignored
08-05 11:27:34.305   309  7265 V AudioCache: notify(0xb54748c0, 1, 0, 0)
08-05 11:27:34.305   309  7265 V AudioCache: prepared
08-05 11:27:34.305   309  2164 V AudioCache: wait - success
08-05 11:27:34.305   309  2164 V MediaPlayerService: start
08-05 11:27:34.305   309  2164 V AwesomePlayer: play_l() 
08-05 11:27:34.305   309  2164 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-05 11:27:34.305   309  2164 V AwesomePlayer: createAudioPlayer_l
08-05 11:27:34.305   309  2164 V AwesomePlayer: seekAudioIfNecessary_l() 
,08-05 11:27:34.305   309  2164 V AwesomePlayer: startAudioPlayer_l() 
08-05 11:27:34.305   309  2164 D AudioPlayer: start of Playback, useOffload 0
08-05 11:27:34.306   309  2164 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 11:27:34.306   309  2164 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 11:27:34.307   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-05 11:27:34.307   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-05 11:27:34.307   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884528
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886048
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-05 11:27:34.308   309  7267 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-05 11:27:34.308   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
08-05 11:27:34.309   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
,08-05 11:27:34.309   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1),
08-05 11:27:34.309   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-05 11:27:34.310   309  2164 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-05 11:27:34.310   309  2164 V AudioCache: notify(0xb54748c0, 6, 0, 0)
08-05 11:27:34.310   309  2164 V AudioCache: ignored
08-05 11:27:34.310   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.310   309  7268 V AudioCache: memcpy(0xaf006000, 0xb178a000, 4096)
08-05 11:27:34.311   309  7268 V AudioCache: write(0xb178a000, 4096),
08-05 11:27:34.311   309  7268 V AudioCache: memcpy(0xaf007000, 0xb178a000, 4096)
08-05 11:27:34.311   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.311   309  7268 V AudioCache: memcpy(0xaf008000, 0xb178a000, 4096)
08-05 11:27:34.312   309  7268 V AudioCache: write(0xb178a000, 4096)
,08-05 11:27:34.312   309  7268 V AudioCache: memcpy(0xaf009000, 0xb178a000, 4096)
08-05 11:27:34.312   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.312   309  7268 V AudioCache: memcpy(0xaf00a000, 0xb178a000, 4096)
08-05 11:27:34.312   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.312   309  7268 V AudioCache: memcpy(0xaf00b000, 0xb178a000, 4096),
08-05 11:27:34.313   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.313   309  7268 V AudioCache: memcpy(0xaf00c000, 0xb178a000, 4096)
08-05 11:27:34.313   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.313   309  7268 V AudioCache: memcpy(0xaf00d000, 0xb178a000, 4096)
08-05 11:27:34.313   309  7268 V AudioCache: write(0xb178a000, 4096)
,08-05 11:27:34.313   309  7268 V AudioCache: memcpy(0xaf00e000, 0xb178a000, 4096)
08-05 11:27:34.314   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.314   309  7268 V AudioCache: memcpy(0xaf00f000, 0xb178a000, 4096)
08-05 11:27:34.314   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.314   309  7268 V AudioCache: memcpy(0xaf010000, 0xb178a000, 4096)
08-05 11:27:34.314   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.314   309  7268 V AudioCache: memcpy(0xaf011000, 0xb178a000, 4096)
,08-05 11:27:34.315   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.315   309  7268 V AudioCache: memcpy(0xaf012000, 0xb178a000, 4096)
08-05 11:27:34.315   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.315   309  7268 V AudioCache: memcpy(0xaf013000, 0xb178a000, 4096)
08-05 11:27:34.315   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.315   309  7268 V AudioCache: memcpy(0xaf014000, 0xb178a000, 4096)
08-05 11:27:34.316   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.316   309  7268 V AudioCache: memcpy(0xaf015000, 0xb178a000, 4096),
08-05 11:27:34.316   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.316   309  7268 V AudioCache: memcpy(0xaf016000, 0xb178a000, 4096)
08-05 11:27:34.316   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.316   309  7268 V AudioCache: memcpy(0xaf017000, 0xb178a000, 4096)
08-05 11:27:34.316   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.316   309  7268 V AudioCache: memcpy(0xaf018000, 0xb178a000, 4096)
08-05 11:27:34.317   309  7268 V AudioCache: write(0xb178a000, 4096)
,08-05 11:27:34.317   309  7268 V AudioCache: memcpy(0xaf019000, 0xb178a000, 4096)
08-05 11:27:34.317   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.317   309  7268 V AudioCache: memcpy(0xaf01a000, 0xb178a000, 4096)
08-05 11:27:34.317   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.317   309  7268 V AudioCache: memcpy(0xaf01b000, 0xb178a000, 4096)
08-05 11:27:34.318   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.318   309  7268 V AudioCache: memcpy(0xaf01c000, 0xb178a000, 4096)
08-05 11:27:34.318   309  7268 V AudioCache: write(0xb178a000, 4096)
,08-05 11:27:34.318   309  7268 V AudioCache: memcpy(0xaf01d000, 0xb178a000, 4096)
08-05 11:27:34.318   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.318   309  7268 V AudioCache: memcpy(0xaf01e000, 0xb178a000, 4096)
08-05 11:27:34.319   309  2164 V MediaPlayerService: wait for playback complete
08-05 11:27:34.319   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.319   309  7268 V AudioCache: memcpy(0xaf01f000, 0xb178a000, 4096)
08-05 11:27:34.319   309  7268 V AudioCache: write(0xb178a000, 4096)
,08-05 11:27:34.319   309  7268 V AudioCache: memcpy(0xaf020000, 0xb178a000, 4096)
08-05 11:27:34.319   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.320   309  7268 V AudioCache: memcpy(0xaf021000, 0xb178a000, 4096)
08-05 11:27:34.326   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.326   309  7268 V AudioCache: memcpy(0xaf022000, 0xb178a000, 4096)
08-05 11:27:34.326   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.326   309  7268 V AudioCache: memcpy(0xaf023000, 0xb178a000, 4096)
08-05 11:27:34.326   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.326   309  7268 V AudioCache: memcpy(0xaf024000, 0xb178a000, 4096)
08-05 11:27:34.327   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.327   309  7268 V AudioCache: memcpy(0xaf025000, 0xb178a000, 4096)
08-05 11:27:34.327   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.327   309  7268 V AudioCache: memcpy(0xaf026000, 0xb178a000, 4096)
08-05 11:27:34.327   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.327   309  7268 V AudioCache: memcpy(0xaf027000, 0xb178a000, 4096)
08-05 11:27:34.328   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.328   309  7268 V AudioCache: memcpy(0xaf028000, 0xb178a000, 4096)
08-05 11:27:34.328   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.328   309  7268 V AudioCache: memcpy(0xaf029000, 0xb178a000, 4096)
08-05 11:27:34.328   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.328   309  7268 V AudioCache: memcpy(0xaf02a000, 0xb178a000, 4096)
08-05 11:27:34.329   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.329   309  7268 V AudioCache: memcpy(0xaf02b000, 0xb178a000, 4096)
08-05 11:27:34.329   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.329   309  7268 V AudioCache: memcpy(0xaf02c000, 0xb178a000, 4096)
08-05 11:27:34.330   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.330   309  7268 V AudioCache: memcpy(0xaf02d000, 0xb178a000, 4096)
08-05 11:27:34.330   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.330   309  7268 V AudioCache: memcpy(0xaf02e000, 0xb178a000, 4096)
08-05 11:27:34.330   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.330   309  7268 V AudioCache: memcpy(0xaf02f000, 0xb178a000, 4096)
08-05 11:27:34.331   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.331   309  7268 V AudioCache: memcpy(0xaf030000, 0xb178a000, 4096)
08-05 11:27:34.331   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.331   309  7268 V AudioCache: memcpy(0xaf031000, 0xb178a000, 4096)
08-05 11:27:34.332   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.332   309  7268 V AudioCache: memcpy(0xaf032000, 0xb178a000, 4096)
08-05 11:27:34.332   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.332   309  7268 V AudioCache: memcpy(0xaf033000, 0xb178a000, 4096)
08-05 11:27:34.333   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.333   309  7268 V AudioCache: memcpy(0xaf034000, 0xb178a000, 4096)
08-05 11:27:34.333   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.333   309  7268 V AudioCache: memcpy(0xaf035000, 0xb178a000, 4096)
08-05 11:27:34.334   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.334   309  7268 V AudioCache: memcpy(0xaf036000, 0xb178a000, 4096)
08-05 11:27:34.334   309  7268 V AudioCache: write(0xb178a000, 4096)
08-05 11:27:34.334   309  7268 V AudioCache: memcpy(0xaf037000, 0xb178a000, 4096)
08-05 11:27:34.334   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-05 11:27:34.334   309  7268 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-05 11:27:34.334   309  7268 V AwesomePlayer: postAudioEOS() 
08-05 11:27:34.334   309  7268 V AudioCache: write(0xb178a000, 280)
08-05 11:27:34.334   309  7268 V AudioCache: memcpy(0xaf038000, 0xb178a000, 280)
08-05 11:27:34.338   309  7265 V AwesomePlay,er: postStreamDoneEvent_l() -> status:-1011 
08-05 11:27:34.339   309  7265 V AwesomePlayer: onStreamDone
08-05 11:27:34.339   309  7265 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-05 11:27:34.339   309  7265 V AudioCache: notify(0xb54748c0, 2, 0, 0)
08-05 11:27:34.339   309  7265 V AudioCache: playback complete
08-05 11:27:34.339   309  7265 V AwesomePlayer: pause_l() 
08-05 11:27:34.339   309  7265 V AudioCache: notify(0xb54748c0, 7, 0, 0)
08-05 11:27:34.339   309  7265 V AudioCache: ignored
08-05 11:27:34.339   309  7265 V AwesomePlayer: cancelPlayerEvents
08-05 11:27:34.339   309  2164 V AudioCache: wait - success
08-05 11:27:34.339   309  2164 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-05 11:27:34.339   309  7265 D AudioPlayer: Pause Playback at 1068125
08-05 11:27:34.340   309  2164 V AwesomePlayer: reset_l() 
08-05 11:27:34.340   309  2164 V AudioCache: notify(0xb54748c0, 8, 0, 0)
08-05 11:27:34.340   309  2164 V AudioCache: ignored
08-05 11:27:34.340   309  2164 V AwesomePlayer: cancelPlayerEvents
08-05 11:27:34.340   309  2164 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-05 11:27:34.340   309  2164 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-05 11:27:34.340   309  2164 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-05 11:27:34.340   309  2164 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-05 11:27:34.340   309  2164 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 11:27:34.340   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 11:27:34.340   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 11:27:34.340   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
,08-05 11:27:34.340   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-05 11:27:34.340   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 1
08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
,08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 11:27:34.341   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-05 11:27:34.342   309  2164 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 11:27:34.342   309  2164 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 11:27:34.342   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-05 11:27:34.342   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-05 11:27:34.342   309  7267 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-05 11:27:34.342   309  2164 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 11:27:34.342   309  2164 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-05 11:27:34.342   309  2164 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-05 11:27:34.343   309  2164 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-05 11:27:34.343   309  2164 D AudioPlayer: AudioPlayer releasing audio source
08-05 11:27:34.343   309  2164 D AudioPlayer: AudioPlayer done releasing audio source
08-05 11:27:34.343   309  2164 V AwesomePlayer: reset_l() 
,08-05 11:27:34.343   309  2164 V AwesomePlayer: cancelPlayerEvents
08-05 11:27:34.343   309  2164 V AwesomePlayer: ~AwesomePlayer call
08-05 11:27:34.343   309  2164 V AwesomePlayer: reset_l() 
08-05 11:27:34.343   309  2164 V AwesomePlayer: cancelPlayerEvents
08-05 11:27:34.344  7165  7263 V SoundPool: close(30)
08-05 11:27:34.344  7165  7263 V SoundPool: pointer = 0xa0023000, size = 205080, sampleRate = 48000, numChannels = 2
,08-05 11:27:34.357  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view,
08-05 11:27:34.357  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-05 11:27:34.359  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9317,
,08-05 11:27:34.565  6875  6875 I UEI.SmartControl: Supports setup maps: true
,08-05 11:27:34.568  6875  6875 D UEI.SmartControl: QS start statue = true Error code = 0
,08-05 11:27:34.568  6875  6875 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 11:27:34.568  6875  6875 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 11:27:34.568  6875  6875 I UEI.SmartControl: ### init IR Blaster...
08-05 11:27:34.571  6875  6875 D serial_port: Configuring serial port
,08-05 11:27:34.571  6875  6875 E UEI.SmartControl: UEIBLaster setting for 616
08-05 11:27:34.571  6875  6875 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 11:27:34.571  6875  6875 I UEI.SmartControl: configuring settings for MAXQ616
08-05 11:27:34.571  6875  6875 I UEI.SmartControl: Get version...
08-05 11:27:34.589  6875  7269 D UEI.SmartControl: serial port data available: 21
,08-05 11:27:34.616  6875  6875 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-05 11:27:34.616  6875  6875 I UEI.SmartControl: IR Blaster version: 256702256704300002,
08-05 11:27:34.616  6875  6875 I UEI.SmartControl: QS saving settings...
,08-05 11:27:34.619  6875  6875 D UEI.SmartControl: IR Blaster version: 25672567
,08-05 11:27:34.635  6875  7269 D UEI.SmartControl: serial port data available: 4
,08-05 11:27:34.663  6875  7275 I UEI.SmartControl: Device manager: loading config....
08-05 11:27:34.665  6875  6875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-05 11:27:34.666  6875  7275 D UEI.SmartControl: ----------- loading internal config...
08-05 11:27:34.667  6875  6875 E UEI.SmartControl: Services init done
08-05 11:27:34.667  6875  6875 D UEI.SmartControl: QS Service init finished
08-05 11:27:34.670  6875  6875 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 11:27:34.670  6875  6875 D UEI.SmartControl: QS Service version code: 201091
08-05 11:27:34.671  6875  6875 D UEI.SmartControl: Service requested: Control
08-05 11:27:34.674  6875  7275 E UEI.SmartControl: Loading SETTINGS...
08-05 11:27:34.677  6875  6875 D UEI.SmartControl: Request IControl service: devices are loaded...
08-05 11:27:34.680  7165  7165 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-05 11:27:34.681  6875  6875 D UEI.SmartControl: Internal service binding...
08-05 11:27:34.682  6875  6891 I UEI.SmartControl: ------ IControl API: 11
08-05 11:27:34.682  6875  6891 D UEI.SmartControl: File observer start...
,08-05 11:27:34.685  6875  6891 E UEI.SmartControl: IR Port is disabled: false
08-05 11:27:34.685  6875  6891 D UEI.SmartControl: Starting file observer...
08-05 11:27:34.688  6875  6891 I UEI.SmartControl: Registering callback...
08-05 11:27:34.688  6875  7275 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 11:27:34.690  6875  6890 I UEI.SmartControl: ------ IControl API: 19
08-05 11:27:34.692  6875  6890 I UEI.SmartControl: Registering Services Ready callback...
08-05 11:27:34.703  6875  7274 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 11:27:34.703  6875  7274 D UEI.SmartControl: -----service ready thread exits
,08-05 11:27:34.704  7165  7180 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-05 11:27:34.705  7165  7261 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-05 11:27:34.705  7165  7261 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-05 11:27:34.706  7165  7165 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-05 11:27:34.707  7165  7165 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-05 11:27:34.707  6875  6891 I UEI.SmartControl: ------ IControl API: 8
08-05 11:27:34.711  7165  7165 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-05 11:27:34.712  7165  7165 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-05 11:27:34.713  7165  7165 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-05 11:27:34.713  7165  7165 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-05 11:27:34.715  7165  7165 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-05 11:27:34.716  7165  7165 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-05 11:27:34.720  7165  7165 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-05 11:27:34.725  7165  7165 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 11:27:34.726  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 11:27:34.727  7165  7165 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 11:27:34.728  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 11:27:34.729  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 11:27:34.733  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-05 11:27:34.734  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,08-05 11:27:34.736  7165  7165 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470389254735]
08-05 11:27:34.737  7165  7165 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-05 11:27:34.744  1036  1574 I ActivityManager: Killing 6607:com.lge.email/u0a23 (adj 15): empty #17
08-05 11:27:34.763  7165  7277 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-05 11:27:34.789  1036  1574 I ActivityManager: Killing 6054:com.android.contacts/u0a19 (adj 15): empty #18
,08-05 11:27:34.825  1036  1885 W libprocessgroup: failed to open /acct/uid_10019/pid_6054/cgroup.procs: No such file or directory
,08-05 11:27:34.827  7165  7165 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-05 11:27:34.828  1036  2031 W libprocessgroup: failed to open /acct/uid_10023/pid_6607/cgroup.procs: No such file or directory
08-05 11:27:34.829  7165  7165 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 11:27:34.830  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-05 11:27:34.831  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-05 11:27:34.832  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-05 11:27:34.833  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-05 11:27:34.834  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-05 11:27:34.853  7165  7165 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-05 11:27:35.512  1036  1920 D WifiServiceImplEx: setWifiEnabled: true pid=6981, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-05 11:27:35.514  1036  1920 D WifiService: setWifiEnabled: true pid=6981, uid=10118
,08-05 11:27:35.514  1036  1920 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 11:27:35.539  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 11:27:35.540  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 11:27:35.540  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-05 11:27:35.541  1036  1535 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-05 11:27:35.541  1036  1535 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-05 11:27:35.544  1036  1535 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-05 11:27:35.544  1036  1535 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 11:27:35.544  1036  1535 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-05 11:27:35.544  1036  1535 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 11:27:35.544  1036  1535 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-05 11:27:35.544  1036  1535 E WifiHW  : unknown target_country: EU , set to default
08-05 11:27:35.544  1036  1535 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-05 11:27:35.544  1036  1535 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-05 11:27:35.544  1036  1535 I WifiUtil: gEnableBmps=1
08-05 11:27:35.594  1036  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:27:35.613  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-05 11:27:35.624  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:27:35.627  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:27:35.631  1036  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:35.632  1036  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:35.634  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 11:27:35.637  6496  7132 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-05 11:27:35.648  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-05 11:27:35.655  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:27:35.658  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:35.666  5810  5810 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 11:27:35.686  5810  5810 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 11:27:35.719  2079  2079 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:27:35.773  1036  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:27:35.801  1036  1052 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7299 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-05 11:27:35.805  1036  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 11:27:35.805  1036  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 11:27:35.897  7299  7299 I AppUp4:AppBoxCP: onCreate
08-05 11:27:35.898  7299  7299 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-05 11:27:35.909  7299  7299 I AppUp4:DB:  setFingerPrint start
,08-05 11:27:35.909  7299  7299 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-05 11:27:35.918  7299  7299 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-05 11:27:35.918  7299  7299 I AppUp4:DB:  SDK version = 21
,08-05 11:27:35.918  7299  7299 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-05 11:27:35.920  7299  7299 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-05 11:27:35.922  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 11:27:35.922  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:27:35.926  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 11:27:35.926  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 11:27:35.933  7299  7299 I AppUp4:CustModeStarterReceiver: onReceive
08-05 11:27:35.989  7299  7299 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:27:35.989  7299  7299 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 11:27:35.999  7299  7299 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@22e5aa92
08-05 11:27:35.999  7299  7299 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 11:27:35.999  7299  7299 D AppUp4:CustFacade: isPhone : true
08-05 11:27:36.000  7299  7299 D AppUp4:CustModeStarterReceiver: begin check event
,08-05 11:27:36.001  7299  7299 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-05 11:27:36.001  7299  7299 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-05 11:27:36.002  7299  7319 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-05 11:27:36.003  7299  7319 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-05 11:27:36.003  7299  7319 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-05 11:27:36.006  1036  1052 I ActivityManager: Killing 6633:com.android.gallery3d/u0a27 (adj 15): empty #17
08-05 11:27:36.090  1036  1993 W libprocessgroup: failed to open /acct/uid_10027/pid_6633/cgroup.procs: No such file or directory
,08-05 11:27:36.092  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:36.094  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 11:27:36.097  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:27:36.100  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:27:36.106  4787  7331 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 11:27:36.112  4787  7332 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:36.113  4787  7332 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 11:27:36.161  1036  2031 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7336 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-05 11:27:36.253  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 11:27:36.253  1036  1118 D Tethering: InitialState.processMessage what=4
08-05 11:27:36.253  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-05 11:27:36.260   303   881 D SoftapController: Softap fwReload - Ok
08-05 11:27:36.271  1036  1535 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (722ms)
,08-05 11:27:36.276   303   881 D CommandListener: Setting iface cfg
08-05 11:27:36.276   303   881 D CommandListener: Trying to bring down wlan0
08-05 11:27:36.277   303   881 D CommandListener: Clearing all IP addresses on wlan0
08-05 11:27:36.280  1036  1535 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-05 11:27:36.283  7354  7354 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 11:27:36.283  7354  7354 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:36.293  1036  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:27:36.293  1036  1535 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:27:36.293  1036  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 11:27:36.299  1036  1535 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-05 11:27:36.299  1036  1535 D WifiMonitor: connecting to supplicant
08-05 11:27:36.312  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 11:27:36.314  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-05 11:27:36.314  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-05 11:27:36.316  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:36.323  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:27:36.333  7354  7354 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-05 11:27:36.353  7336  7336 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 11:27:36.354  7336  7336 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 11:27:36.357  7336  7336 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 11:27:36.358  7336  7336 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 11:27:36.367  7354  7354 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-05 11:27:36.367  7354  7354 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-05 11:27:36.442  7336  7336 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 11:27:36.456  7336  7336 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-05 11:27:36.472  7354  7354 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 11:27:36.494  7336  7336 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 11:27:36.512  7354  7354 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-05 11:27:36.519  7354  7354 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-05 11:27:36.519  7336  7336 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:27:36.519  7336  7336 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 11:27:36.521  1036  1535 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-05 11:27:36.521  1036  1535 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-05 11:27:36.522  1036  1535 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-05 11:27:36.522  1036  1535 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-05 11:27:36.522  1036  1535 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:36.523  1036  7367 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
,08-05 11:27:36.523  1036  1535 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:36.523  1036  7367 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 11:27:36.523  1036  1535 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-05 11:27:36.523  1036  1535 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-05 11:27:36.525  1036  1535 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-05 11:27:36.526  1036  1535 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-05 11:27:36.526  1036  1535 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-05 11:27:36.526  1036  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:27:36.526  1036  1535 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:27:36.526  1036  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 11:27:36.527  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:36.527  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:36.527  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:36.528  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:36.528  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 11:27:36.529  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 11:27:36.529  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 11:27:36.529  7354  7354 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-05 11:27:36.530  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-05 11:27:36.530  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-05 11:27:36.530  1036  7367 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-05 11:27:36.530  1036  7367 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-05 11:27:36.531  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-05 11:27:36.533  1939  1939 D WfdService: Waiting for WifiP2p enabling
08-05 11:27:36.533  1036  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-05 11:27:36.534  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:36.534  1036  1535 D WifiNative-wlan0: doBoolean: SET update_config 1
08-05 11:27:36.535  1036  1535 D WifiNative-wlan0: SET update_config 1: returned true
08-05 11:27:36.535  1036  1535 D WifiConfigStore: Loading config and enabling all networks 
08-05 11:27:36.535  1036  1535 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-05 11:27:36.535  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:36.535  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:36.535  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:36.535  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:36.535  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:36.535  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:27:36.535  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID ,name: null
08-05 11:27:36.535  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:36.535  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:27:36.535  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:36.535  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:36.536  1036  1535 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-05 11:27:36.537  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:36.537  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:36.537  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:36.537  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:36.537  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:36.537  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:27:36.537  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:36.537  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:36.537  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:27:36.537  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 11:27:36.537  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:36.549  1036  1535 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-05 11:27:36.557  1036  1535 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-05 11:27:36.558  1036  1535 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-05 11:27:36.558  1036  1535 D WifiStateMachine: enableVerboseLogging : level 2
08-05 11:27:36.558  1036  1535 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-05 11:27:36.559  1036  1535 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-05 11:27:36.559  1036  1535 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-05 11:27:36.559  1036  1535 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-05 11:27:36.559  1036  1535 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-05 11:27:36.560  1036  1535 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-05 11:27:36.560  1036  1535 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-05 11:27:36.560  1036  1535 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-05 11:27:36.560  1036  1535 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-05 11:27:36.561  1036  1535 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-05 11:27:36.561  1036  1535 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-05 11:27:36.561  1036  1535 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-05 11:27:36.561  1036  1535 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-05 11:27:36.561  1036  1535 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-05 11:27:36.562  1036  1535 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 11:27:36.562  1036  1535 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-05 11:27:36.563  1036  1535 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-05 11:27:36.563  1036  1535 D WifiNative-HAL: Setting external_sim to 1
08-05 11:27:36.563  1036  1535 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-05 11:27:36.563  1036  1535 D WifiNative-wlan0: SET external_sim 1: returned true
08-05 11:27:36.563  1036  1535 I WifiNative-HAL: startHal
08-05 11:27:36.563  1036  1535 D wifi    : setting scan oui 0xaf6a7f20
08-05 11:27:36.563  1036  1535 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 11:27:36.563  1036  1535 I WifiNative-HAL: startHal
08-05 11:27:36.564  1036  1535 D wifi    : setting scan oui 0xaf6a7f20
08-05 11:27:36.564  1036  1535 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-05 11:27:36.564  1036  1535 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-05 11:27:36.564  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
,08-05 11:27:36.564  1939  1939 D WfdsService: Supplicant Connection state is changed : true
08-05 11:27:36.564  7354  7354 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-05 11:27:36.564  1939  2249 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-05 11:27:36.564  1939  2249 D WfdsService: Set the WFDS Monitor: true
08-05 11:27:36.564  1939  2249 D WfdsMonitor: WfdsMonitorThread create
08-05 11:27:36.565  1939  2249 D WfdsMonitor: WFDS Monitor is created and started
08-05 11:27:36.565  1939  2249 D WfdsService: WiFi: Supplicant connection re-established
08-05 11:27:36.565  1036  1535 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-05 11:27:36.565  1939  7372 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-05 11:27:36.566  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 11:27:36.566  7354  7354 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 11:27:36.566  1939  7372 E CtrlSupplicant: Succeed to open control connection
08-05 11:27:36.566  1036  1535 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 11:27:36.566  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-05 11:27:36.566  7354  7354 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-05 11:27:36.566  1939  7372 E CtrlSupplicant: Succeed to open monitor connection
08-05 11:27:36.567  1939  7372 D WfdsMonitor: Supplicant connection established
08-05 11:27:36.567  1939  2249 D WfdsService: Connected to the supplicant for wfds
,08-05 11:27:36.567  1036  1535 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-05 11:27:36.567  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 11:27:36.567  7354  7354 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 11:27:36.568  1036  1535 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 11:27:36.568  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 11:27:36.568  7354  7354 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 11:27:36.568  1036  1535 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 11:27:36.568  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-05 11:27:36.568  7354  7354 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-05 11:27:36.569  1036  1535 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-05 11:27:36.569  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 11:27:36.569  7354  7354 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 11:27:36.569  1036  1535 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 11:27:36.570  1036  1535 E WifiNative: : [334,838,462 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-05 11:27:36.570  1036  1535 D WifiNative-wlan0: doBoolean: RECONNECT
,08-05 11:27:36.571  1036  1535 D WifiNative-wlan0: RECONNECT: returned true
08-05 11:27:36.571  1036  1535 D WifiNative-wlan0: doString: [STATUS]
08-05 11:27:36.571  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 11:27:36.571  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 11:27:36.572  1036  1535 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 11:27:36.572  1036  1535 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 11:27:36.572  1036  1535 D WifiNative-wlan0: SET ps 1: returned true
08-05 11:27:36.572  1036  1534 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.573  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 11:27:36.574  1036  1036 D RttService: SCAN_AVAILABLE : 3
,08-05 11:27:36.574  1036  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.574  1036  1555 I WifiNative-HAL: startHal
08-05 11:27:36.574  1036  1535 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-05 11:27:36.574  1036  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.574  1036  1535 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-05 11:27:36.575  1036  1535 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-05 11:27:36.575  1036  1535 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-05 11:27:36.576  1036  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=334844  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 11:27:36.576  1036  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=334845  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 11:27:36.577  1036  1535 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-05 11:27:36.577  1036  1535 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-05 11:27:36.578  1036  1535 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-05 11:27:36.578  1036  1535 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-05 11:27:36.578  7354  7354 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-05 11:27:36.578  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:36.578  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:27:36.579  1036  1535 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-05 11:27:36.579  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:36.579  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:36.579  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 11:27:36.579  1036  1535 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-05 11:27:36.579  1036  1535 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-05 11:27:36.579  1036  1535 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-05 11:27:36.579  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:36.580  7354  7354 E wpa_supplicant: disconnect_rssi_lvl: -100
08-05 11:27:36.580  1036  1535 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
,08-05 11:27:36.581  1036  1535 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 11:27:36.581  1036  1535 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 11:27:36.581  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-05 11:27:36.581  1036  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf6a7f20
08-05 11:27:36.581  1036  1555 D wifi    : failed to get capabilities : -3
08-05 11:27:36.582  1036  1555 E WifiScanningService: could not get scan capabilities
08-05 11:27:36.582  7354  7354 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 11:27:36.582  7354  7354 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:36.583  7354  7354 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 11:27:36.583   303   881 D CommandListener: Setting iface cfg
08-05 11:27:36.583  7354  7354 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.583   303   881 D CommandListener: Trying to bring up p2p0
08-05 11:27:36.583  1939  7372 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:27:36.583  7354  7354 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.584  1939  7372 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:27:36.584  1036  1534 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 11:27:36.584  1036  1534 D LGWifiP2pService: P2pEnablingState
08-05 11:27:36.585  1036  1534 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.585  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 11:27:36.585  1036  1534 D LGWifiP2pService: P2p socket connection successful
08-05 11:27:36.585  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:36.585  1036  7367 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:36.585  1036  1534 D LGWifiP2pService: P2pEnabledState
08-05 11:27:36.585  1036  7367 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:36.585  1036  7367 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:27:36.585  1036  7367 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.585  1036  7367 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.585  1036  7367 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.585  1036  7367 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:27:36.585  1036  7367 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.585  1036  7367 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.585  1036  7367 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.585  1036  1535 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-05 11:27:36.586  1036  1535 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-05 11:27:36.586  1036  1535 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-05 11:27:36.586  1036  1535 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-05 11:27:36.587  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-05 11:27:36.587  7354  7354 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-05 11:27:36.587  7354  7354 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 11:27:36.587  1036  1534 D LGWifiP2pService: sending p2p connection ,changed broadcast
08-05 11:27:36.587  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-05 11:27:36.587  1939  1939 D WfdsService: WifiP2pState is changed : true
08-05 11:27:36.588  1939  2249 D WfdsService: Receive the WFDS_ENABLE Method
08-05 11:27:36.588  1939  2249 D WfdsService: Set the WFDS Monitor: true
08-05 11:27:36.588  1939  2249 D WfdsService: Connected to the supplicant for wfds
08-05 11:27:36.588  1939  2249 D WfdsJNI : doCommand: WFDS_SET TRUE
08-05 11:27:36.588  7354  7354 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-05 11:27:36.588  1939  2249 D WfdsService: selectPreferredScanChannel [36]
08-05 11:27:36.588  1939  2249 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-05 11:27:36.588  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-05 11:27:36.588  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 11:27:36.588  1036  1535 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-05 11:27:36.588  1036  1535 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,08-05 11:27:36.589  1036  7367 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 11:27:36.589  1036  7367 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 11:27:36.589  1036  1535 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-05 11:27:36.589  1036  1535 D WifiNative-wlan0: doBoolean: SCAN
08-05 11:27:36.590  1036  1535 D WifiNative-wlan0: SCAN: returned false
08-05 11:27:36.590  1036  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=334859  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 11:27:36.591  1036  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=334859  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 11:27:36.593  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:36.593  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:36.593  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 11:27:36.593  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:27:36.593  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-05 11:27:36.594  1036  1534 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-05 11:27:36.594  1036  1535 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:27:36.594  1036  1535 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:27:36.595  1036  1535 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:27:36.595  1036  1535 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:27:36.595  1939  1939 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-05 11:27:36.595  1036  1534 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-05 11:27:36.595  1036  1535 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:27:36.595  1939  1939 D WfdsService: isConnected: false
08-05 11:27:36.596  1036  1534 D WifiNative-p2p0: doBoolean: SET device_name G3
08-05 11:27:36.597  1036  1534 D WifiNative-p2p0: SET device_name G3: returned true
08-05 11:27:36.597  1036  1534 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-05 11:27:36.597  1036  1534 D LGWifiP2pService: before postfix = G3
08-05 11:27:36.597  1036  1534 D WifiServerServiceExt: postfix byte check : 2
08-05 11:27:36.597  1036  1534 D LGWifiP2pService: after postfix = G3
08-05 11:27:36.597  1036  1534 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-05 11:27:36.598  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:36.598  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:27:36.598  1036  1534 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-05 11:27:36.598  1036  1534 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-05 11:27:36.598  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:36.599  1036  1534 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-05 11:27:36.600  1036  1534 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-05 11:27:36.600  1036  1534 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-05 11:27:36.601  1036  1534 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-05 11:27:36.602  1036  1534 D WifiNative-p,2p0: P2P_SET conc_pref p2p: returned true
,08-05 11:27:36.602  1036  1534 D WifiNative-HAL: p2pGetDeviceAddress
08-05 11:27:36.602  1036  1534 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-05 11:27:36.604  1939  1939 I WfdStateTracker: handleP2pThisDeviceChanged
08-05 11:27:36.605  1939  1939 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-05 11:27:36.605  1939  1939 D WfdsService: Update P2p Interface State: 3
08-05 11:27:36.606  1036  1534 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-05 11:27:36.606  1036  1534 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-05 11:27:36.607  1036  1534 D WifiNative-p2p0: P2P_FLUSH: returned true
08-05 11:27:36.607  1036  1534 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-05 11:27:36.607  1036  1534 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-05 11:27:36.607  1036  1534 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-05 11:27:36.607  1036  1534 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-05 11:27:36.607  1036  1534 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-05 11:27:36.613  1036  1534 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-05 11:27:36.613  1036  1534 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-05 11:27:36.613  1036  1534 D LGWifiP2pService: InactiveState
08-05 11:27:36.613  1036  1534 D LGWifiP2pService: InactiveState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.613  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.613  1036  1534 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-05 11:27:36.613  7354  7354 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 11:27:36.614  7354  7354 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:36.614  1939  7372 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 11:27:36.614  1036  7367 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 11:27:36.614  1036  7367 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:36.614  1036  7367 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:36.614  1036  7367 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:36.614  7354  7354 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 11:27:36.614  7354  7354 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.614  1939  7372 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:27:36.614  1036  7367 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:27:36.614  1036  7367 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.614  1036  7367 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.614  1036  7367 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.614  7354  7354 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.615  1036  1534 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-05 11:27:36.615  1036  1534 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.615  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.615  1036  1534 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.615  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHan,dler }
08-05 11:27:36.615  1036  1534 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.615  1036  1534 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.615  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.615  1036  1534 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.615  1036  1534 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.615  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.615  1036  1534 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.616  1036  1534 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.616  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.616  1036  1534 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:36.616  1036  1036 E WifiServerServiceExt: No p2p device connected
,08-05 11:27:36.617  1939  7372 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD],
08-05 11:27:36.617  1036  7367 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:27:36.617  1036  7367 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.617  1036  7367 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.617  1036  7367 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:36.618  1939  2249 W WfdsService: DefaultState - msg [9441285] is not handled
08-05 11:27:36.629  7336  7336 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 11:27:36.652  7336  7336 I HubEmail: JNI_OnLoad()
08-05 11:27:36.652  7336  7336 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-05 11:27:36.652  7336  7336 I HubEmail: registerNatives()
08-05 11:27:36.652  7336  7336 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-05 11:27:36.652  7336  7336 I HubEmail: registerNativeMethods()
08-05 11:27:36.652  7336  7336 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 11:27:36.652  7336  7336 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-05 11:27:36.654  3391  3391 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 11:27:36.654  3391  3391 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:36.654  3391  3391 I LgeMiscReceiver: networkInfo.isConnected() = false
08-05 11:27:36.659  7203  7375 W FormManager: Network not available. Please check & try again.
08-05 11:27:36.708  1036  1574 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7378 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-05 11:27:36.712  7336  7377 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 11:27:36.716  7203  7376 V FormManager: Network unavailable.
08-05 11:27:36.718  7203  7376 V FormManager: Network unavailable.
08-05 11:27:36.731  1036  2049 I ActivityManager: Killing 6721:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-05 11:27:36.787  1036  1956 W libprocessgroup: failed to open /acct/uid_10061/pid_6721/cgroup.procs: No such file or directory
,08-05 11:27:36.879  7378  7378 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:27:36.880  7378  7378 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 11:27:36.891  1036  3523 I LocationManagerService: remove 108fb7
08-05 11:27:36.892  1036  3523 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-05 11:27:36.892  1036  3523 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 11:27:36.893  1036  3523 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-05 11:27:36.895  1036  3523 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-05 11:27:36.895  7378  7378 D PhoneMonitor: Register our PhoneStateListener
08-05 11:27:36.897  1036  3523 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-05 11:27:36.937  7378  7378 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 11:27:36.943  7378  7378 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-05 11:27:36.967  7378  7378 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-05 11:27:36.968  7378  7378 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-05 11:27:36.969  7378  7378 D TelephonyAutoProfiling: [parse] Load xml
08-05 11:27:36.973  7378  7378 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-05 11:27:36.973  7378  7378 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,08-05 11:27:36.973  7378  7378 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-05 11:27:36.973  7378  7378 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-05 11:27:36.973  7378  7378 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-05 11:27:36.973  7378  7378 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-05 11:27:36.973  7378  7378 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-05 11:27:36.973  7378  7378 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-05 11:27:36.973  7378  7378 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-05 11:27:36.973  7378  7378 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-05 11:27:36.973  7378  7378 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-05 11:27:36.973  7378  7378 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-05 11:27:36.973  7378  7378 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-05 11:27:36.973  7378  7378 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-05 11:27:36.973  7378  7378 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-05 11:27:36.974  7378  7378 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-05 11:27:36.974  7378  7378 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-05 11:27:36.983  7378  7378 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-05 11:27:37.021  1036  1920 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7400 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 11:27:37.023  1036  1920 I ActivityManager: Killing 6765:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-05 11:27:37.079  1036  1643 W libprocessgroup: failed to open /acct/uid_10080/pid_6765/cgroup.procs: No such file or directory
,08-05 11:27:37.216  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-05 11:27:37.216  1036  7367 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-05 11:27:37.217  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-05 11:27:37.217  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-05 11:27:37.217  1036  7367 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-05 11:27:37.217  7354  7354 E wpa_supplicant: USIM:  scard_init function
08-05 11:27:37.218  7354  7354 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-05 11:27:37.221  1036  1535 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-05 11:27:37.221  1036  1535 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-05 11:27:37.221  1036  1535 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-05 11:27:37.222  1036  1535 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-05 11:27:37.222  1036  1535 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-05 11:27:37.222  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-05 11:27:37.222  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-05 11:27:37.233  1036  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=335501  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-05 11:27:37.234  1036  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=335502  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-05 11:27:37.235  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:37.235  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 11:27:37.237  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.237  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.237  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 11:27:37.239  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:37.244  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:27:37.244  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-05 11:27:37.325  1036  1695 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7418 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-05 11:27:37.326  1036  1695 I ActivityManager: Killing 6816:com.lge.eula/1000 (adj 15): empty #17
,08-05 11:27:37.350  7354  7354 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 11:27:37.353  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-05 11:27:37.353  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-05 11:27:37.354  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-05 11:27:37.354  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-05 11:27:37.354  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:27:37.354  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 11:27:37.354  1036  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=335622  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 11:27:37.355  1036  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=335623  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 11:27:37.355  1036  1535 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=335624
08-05 11:27:37.356  1036  1535 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=335624
08-05 11:27:37.356  1036  1535 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=335625
08-05 11:27:37.357  1036  1535 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=335625
08-05 11:27:37.357  1036  1535 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=335626
08-05 11:27:37.359  7354  7354 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 11:27:37.359  7354  7354 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 11:27:37.359  1036  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=335627  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 11:27:37.360  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:27:37.360  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-05 11:27:37.360  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-05 11:27:37.360  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 11:27:37.360  1036  7367 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 11:27:37.360  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
,08-05 11:27:37.360  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 11:27:37.360  1036  7367 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 11:27:37.361  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:27:37.361  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-05 11:27:37.442  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 11:27:37.444  1036  1885 W libprocessgroup: failed to open /acct/uid_1000/pid_6816/cgroup.procs: No such file or directory
,08-05 11:27:37.471  1036  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=335739  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 11:27:37.472  1036  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=335741  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 11:27:37.473  1036  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=335741  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 11:27:37.474  1036  1535 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=335742
08-05 11:27:37.477  1036  1535 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=335745
,08-05 11:27:37.478  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.478  1036  1535 D WifiNative-wlan0: doString: [STATUS]
08-05 11:27:37.478  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.478  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 11:27:37.479  1036  1535 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 11:27:37.480  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:27:37.480  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 11:27:37.481  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:37.481  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:27:37.481  1036  1535 I WifiServiceExtension: setVHTCapabilityType  : false
08-05 11:27:37.482  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:37.485  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.485  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.485  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-05 11:27:37.486  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:27:37.486  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-05 11:27:37.489  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:37.489  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:27:37.492  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:37.492  1036  1535 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-05 11:27:37.492  1036  1535 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-05 11:27:37.500  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.500  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.500  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-05 11:27:37.507  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:37.507  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:27:37.508  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.508  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.508  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 11:27:37.517  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 11:27:37.520  1036  1535 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-05 11:27:37.520  1036  1544 D ConnectivityService: Got NetworkAgent Messenger
08-05 11:27:37.520  1036  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-05 11:27:37.520  1036  1544 D ConnectivityService: NetworkAgent connected
08-05 11:27:37.520  1036  1535 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 11:27:37.520  1036  1535 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 11:27:37.521  1036  1535 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 11:27:37.521  1036  1535 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-05 11:27:37.525  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:37.526  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:27:37.527  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:37.538  1036  1535 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 11:27:37.538  1036  1535 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 11:27:37.538  1036  1535 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 11:27:37.539  1036  1535 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 11:27:37.539  1036  1535 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-05 11:27:37.555  1036  1535 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-05 11:27:37.559   303   881 D CommandListener: Setting iface cfg
08-05 11:27:37.579  1036  1534 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:37.579  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:37.579  1036  1534 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 11:27:37.595  1036  1957 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7441 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 11:27:37.597  1036  1957 I ActivityManager: Killing 6787:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-05 11:27:37.667  1036  2049 W libprocessgroup: failed to open /acct/uid_10097/pid_6787/cgroup.procs: No such file or directory
,08-05 11:27:37.680  1036  1535 E WifiStateMachine: Start Dhcp Watchdog 2
,08-05 11:27:37.681  1036  7440 D DhcpStateMachine: StoppedState
08-05 11:27:37.681  1036  1535 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=335949  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:27:37.681  1036  7440 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:37.681  1036  7440 D DhcpStateMachine: WaitBeforeStartState
08-05 11:27:37.681  1036  1535 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=335950  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:27:37.682  1036  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=335950  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:27:37.683  1036  1535 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:37.683  1036  1535 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:37.683  1036  1535 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:37.684  1036  1535 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:37.685  1036  1535 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:37.686  1036  1535 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:37.687  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:27:37.687  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-05 11:27:37.688  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:27:37.688  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-05 11:27:37.690  1036  1535 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=335958  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:27:37.691  1036  1535 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=335959  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:27:37.693  1036  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=335961  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:27:37.696  1036  1535 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:289885] from screen [on:0 period:1510442464] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 11:27:37.699  1036  1535 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1510442467] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 11:27:37.699  1036  1535 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 11:27:37.704  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:37.708  1036  1544 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-05 11:27:37.709  1036  1535 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:37.710  7441  7441 I art     : Almond Protected OAT
08-05 11:27:37.711  1036  1535 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:37.712  1036  1535 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:37.713  1036  1535 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:37.714  1036  1535 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:37.715  1036  1535 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:37.716  1036  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 11:27:37.718  1036  1535 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 11:27:37.719  1036  1535 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-05 11:27:37.720  1036  1535 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 11:27:37.720  1036  1535 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 11:27:37.721  1036  1535 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 11:27:37.721  1036  1535 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 11:27:37.722  1036  1535 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=135,0,0
08-05 11:27:37.722  1036  1535 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=135,0,0
08-05 11:27:37.722  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-05 11:27:37.723  7354  7354 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-05 11:27:37.723  1036  1535 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-05 11:27:37.724  1036  1535 D WifiNative-wlan0: doBoolean: SET ps 0
08-05 11:27:37.724  1036  1535 D WifiNative-wlan0: SET ps 0: returned true
08-05 11:27:37.724  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-05 11:27:37.724  7354  7354 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-05 11:27:37.725  1036  1535 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-05 11:27:37.725  1036  1535 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-05 11:27:37.725  1036  1535 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 11:27:37.725  1036  1534 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@12a61c86 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:37.725  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@12a61c86 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:37.725  1036  1535 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 11:27:37.725  1036  7440 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:37.725  1036  7440 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-05 11:27:37.726   303   881 D CommandListener: Setting iface cfg
08-05 11:27:37.727   303   881 D CommandListener: Trying to bring up wlan0
08-05 11:27:37.728  1036  1535 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-05 11:27:37.729  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:27:37.729  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 11:27:37.730  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:27:37.730  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-05 11:27:37.732  1036  1535 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:37.732  1036  1535 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:37.733  1036  1535 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:37.733  1036  1535 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:37.734  1036  1535 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:37.734  1036  1535 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:37.735  1036  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 11:27:37.735  1036  1535 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-05 11:27:37.736  1036  1535 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-05 11:27:37.736  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 11:27:37.736  1036  1534 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:37.736  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:37.736  7354  7354 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 11:27:37.736  1036  1535 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 11:27:37.736  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-05 11:27:37.737  7354  7354 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-05 11:27:37.737  1036  1535 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-05 11:27:37.737  1036  1535 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 11:27:37.780  1036  1535 D WifiNative-wlan0: SET ps 1: returned true
08-05 11:27:37.781  1036  1535 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 11:27:37.782  1036  1535 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 11:27:37.782  1036  1535 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-05 11:27:37.783  1036  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 11:27:37.783  1036  1544 D ConnectivityService: ignoring duplicate network state non-change
,08-05 11:27:37.789  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:37.789  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:27:37.790  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.790  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.790  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-05 11:27:37.791  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:37.793  1036  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-05 11:27:37.794  1036  1535 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-05 11:27:37.794  1036  1544 D ConnectivityService: Adding iface wlan0 to network 101
08-05 11:27:37.796  7441  7441 D WeatherApplication: removeAccount
08-05 11:27:37.800  7441  7441 D WeatherApplication: Account.length = 0
,08-05 11:27:37.801  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.801  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.801  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-05 11:27:37.803  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 11:27:37.804  7441  7441 E WeatherApplication: OPERATOR:OPEN
08-05 11:27:37.807  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-05 11:27:37.808  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.808  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.808  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 11:27:37.809  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-05 11:27:37.814  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:37.814  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:27:37.816  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.816  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:37.816  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 11:27:37.816  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:37.817  7441  7441 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:27:37
08-05 11:27:37.819  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:37.819  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 11:27:37.819  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:37.821  7441  7441 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 11:27:37.821  7441  7441 D Weather.Utils: 2 : All the weather widget is gone.
08-05 11:27:37.824  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:37.824  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 11:27:37.824  7441  7441 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 11:27:37.824  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:37.827  7441  7441 D WeatherAncestor: connectivity changed - connection : true
,08-05 11:27:37.829  7441  7441 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-05 11:27:37.835  1036  1544 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-05 11:27:37.835  1036  1544 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-05 11:27:37.837  1036  1544 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-05 11:27:37.838   303   881 E Netd    : netlink response contains error (File exists)
08-05 11:27:37.838  1036  1544 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-05 11:27:37.839  7441  7441 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 11:27:37.839  7441  7441 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 11:27:37.839  7441  7441 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-05 11:27:37.839  1036  1544 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-05 11:27:37.839  1036  1544 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-05 11:27:37.839  1036  1544 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-05 11:27:37.845  1036  1544 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 11:27:37.845  1036  1544 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-05 11:27:37.845  1036  1544 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-05 11:27:37.846  1036  7435 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:37.846  1036  7435 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-05 11:27:37.846  1036  7435 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:37.846  1036  7435 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 11:27:37.848  1036  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 11:27:37.848  1036  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 11:27:37.848  1036  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:27:37.848  1036  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 11:27:37.848  1036  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:37.848  1036  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-05 11:27:37.848   303  7464 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-05 11:27:37.848  1036  1544 D ConnectivityService: currentScore = 0, newScore = 20
08-05 11:27:37.848  1036  1544 D ConnectivityService:    accepting network in place of null
08-05 11:27:37.848  1036  1544 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:37.849  1036  1535 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:37.849  1036  1535 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 11:27:37.849  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:37.849  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 11:27:37.850  1036  1544 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-05 11:27:37.850  1036  1544 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI (,) - 101] isDefaultNetwork=true
08-05 11:27:37.850  1036  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 11:27:37.852  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-05 11:27:37.852  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 11:27:37.852  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 11:27:37.852  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 11:27:37.854  1036  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:37.854  1036  1544 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-05 11:27:37.854  1036  1544 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-05 11:27:37.855  1036  1544 D ConnectivityService: validation of new default Network = false
08-05 11:27:37.855  1036  1544 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-05 11:27:37.855  1036  1544 D DSQN    : enableDataServiceNotify 
08-05 11:27:37.855  1036  1544 D DSQN    : start dsqn bin
,08-05 11:27:37.859  1036  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 11:27:37.859  1036  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:37.859  1036  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:27:37.860  1036  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:27:37.860  1602  2121 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 11:27:37.853  7465  7465 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:37.853  7465  7465 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:37.864  7441  7441 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 11:27:37.865  7441  7441 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:27:37
08-05 11:27:37.874  7465  7465 E DSQN    : DSQN ssw
,08-05 11:27:37.895  1036  1957 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7470 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 11:27:37.896  1036  1957 I ActivityManager: Killing 6843:com.lge.bnr/1000 (adj 15): empty #17
,08-05 11:27:37.898   303  7464 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-05 11:27:37.927  1036  7440 D DhcpStateMachine: DHCPV4 request on wlan0
,08-05 11:27:37.927  1036  7440 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-05 11:27:37.927  1036  7440 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-05 11:27:37.931   303  7464 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-05 11:27:37.923  7487  7487 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:37.933  1815  7469 I CheckinService: active receiver: enabled
08-05 11:27:37.923  7487  7487 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:37.939  7487  7487 I dhcpcd  : version 5.5.6 starting
08-05 11:27:37.941  7487  7487 E dhcpcd  : get_duid: m
08-05 11:27:37.941  7487  7487 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-05 11:27:37.941  7487  7487 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-05 11:27:37.946  1036  2031 W libprocessgroup: failed to open /acct/uid_1000/pid_6843/cgroup.procs: No such file or directory
08-05 11:27:37.952  1815  7469 I CheckinService: Preparing to send checkin request
08-05 11:27:37.952  1815  7469 I EventLogService: Accumulating logs since 1470388965557
,08-05 11:27:37.963  1036  1533 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-05 11:27:37.971  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 11:27:37.971  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:37.972  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:37.976   303   880 D LGDataListener: argv[0]=dsqncommand
08-05 11:27:37.976   303   880 D LGDataListener: argv[1]=wlan0
08-05 11:27:37.976   303   880 D LGDataListener: argv[2]=1
08-05 11:27:37.976   303   880 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-05 11:27:37.977  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-05 11:27:37.977  1036  1116 D DSQN    : start to monitor internet connection
08-05 11:27:38.014  1815  7469 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-05 11:27:38.016  7487  7487 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 11:27:38.017  7487  7487 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 11:27:38.017  7487  7487 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 11:27:38.017  7487  7487 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-05 11:27:38.017  7487  7487 D dhcpcd  : wlan0: sending REQUEST (xid 0x481bf3d6), next in 3.64 seconds
08-05 11:27:38.020  1036  7435 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 09:27:38 GMT], X-Android-Received-Millis=[1470389258019], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470389257976]}
08-05 11:27:38.020  1036  7435 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-05 11:27:38.020  1036  7435 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-05 11:27:38.020  1036  1544 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
,08-05 11:27:38.020  1036  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 11:27:38.020  1036  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 11:27:38.020  1036  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:27:38.020  1036  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 11:27:38.020  1036  1544 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-05 11:27:38.020  1036  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 11:27:38.021  1036  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:38.021  1036  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:27:38.021  1036  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:27:38.023  1036  1544 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:38.023  1602  2121 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 11:27:38.023  1036  1535 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:38.023  1036  1535 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 11:27:38.023  1036  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-05 11:27:38.023  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:38.024  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 11:27:38.024   277   445 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 11:27:38.024   277   445 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 11:27:38.024   277   445 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 11:27:38.024  7470  7498 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-05 11:27:38.026   277   445 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 11:27:38.026   277   445 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 11:27:38.026   277   445 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 11:27:38.027  7470  7498 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 11:27:38.036   277   445 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 11:27:38.036   277   445 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 11:27:38.036   277   445 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 11:27:38.036  7470  7500 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-05 11:27:38.038  7487  7487 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-05 11:27:38.043   277   445 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 11:27:38.043   277   445 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 11:27:38.043   277   445 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 11:27:38.043  7470  7500 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 11:27:38.045  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 11:27:38.045  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:38.046  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:38.049  7487  7487 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-05 11:27:38.049  7487  7487 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-05 11:27:38.049  7487  7487 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-05 11:27:38.049  7487  7487 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-05 11:27:38.049  7487  7487 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 11:27:38.050  7487  7487 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 11:27:38.050  7487  7487 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 11:27:38.050  7487  7487 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-05 11:27:38.109  1036  1885 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7510 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-05 11:27:38.115   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 208us total 10.311ms
08-05 11:27:38.125   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 189us total 9.764ms
,08-05 11:27:38.135   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 189us total 8.776ms
,08-05 11:27:38.172  7510  7510 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-05 11:27:38.172  7510  7510 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-05 11:27:38.190  7470  7470 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-05 11:27:38.196  7470  7470 I LibraryLoader: Loading: webviewchromium
08-05 11:27:38.198  7470  7470 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6477-6479)
08-05 11:27:38.198  7470  7470 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 11:27:38.202  7510  7510 I MultiDex: VM with version 2.1.0 has multidex support
08-05 11:27:38.202  7510  7510 I MultiDex: install
08-05 11:27:38.202  7470  7470 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23921645}
08-05 11:27:38.202  7510  7510 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-05 11:27:38.203  7470  7470 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 11:27:38.204  7470  7470 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 11:27:38.208  1036  1377 V AlarmManager: RTC_WAKEUP set : Alarm{32f0c610 type 0 when 1470389215421 com.google.android.gms} when 1470389215421
,08-05 11:27:38.210  1036  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{d3d6509 type 2 when 336474 com.google.android.gms} when 336474
,08-05 11:27:38.212  7510  7510 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-05 11:27:38.221  7470  7470 I BrowserStartupController: Initializing chromium process, renderers=0
,08-05 11:27:38.224  7470  7470 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 11:27:38.234  7470  7470 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-05 11:27:38.234  7470  7470 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-05 11:27:38.235  7470  7470 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-05 11:27:38.237   309  1383 V AudioPolicyService: registerClient() client 0xb558a600, uid 10093
08-05 11:27:38.239  7470  7560 W AudioManagerAndroid: Requires BLUETOOTH permission
08-05 11:27:38.246  7470  7470 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 11:27:38.246  7470  7470 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 11:27:38.246  7470  7470 I Adreno-EGL: Build Date: 12/12/14 금
08-05 11:27:38.246  7470  7470 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 11:27:38.246  7470  7470 I Adreno-EGL: Remote Branch: 
08-05 11:27:38.246  7470  7470 I Adreno-EGL: Local Patches: 
08-05 11:27:38.246  7470  7470 I Adreno-EGL: Reconstruct Branch: 
,08-05 11:27:38.323  7470  7470 I NSApplication: Starting up...
,08-05 11:27:38.336  1036  7440 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-05 11:27:38.341  1036  7440 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-05 11:27:38.341  1036  7440 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 11:27:38.341  1036  7440 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-05 11:27:38.342  1036  7440 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-05 11:27:38.342  1036  7440 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 11:27:38.343  1036  7440 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-05 11:27:38.343  1036  7440 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-05 11:27:38.347  1036  7440 D DhcpStateMachine: RunningState
08-05 11:27:38.378  1036  1885 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7575 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-05 11:27:38.379  1036  1885 I ActivityManager: Killing 6662:com.android.vending/u0a44 (adj 15): empty #17
,08-05 11:27:38.451  1036  1993 W libprocessgroup: failed to open /acct/uid_10044/pid_6662/cgroup.procs: No such file or directory
,08-05 11:27:38.473  7575  7575 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 11:27:38.544  1036  1643 D WifiServiceImplEx: setWifiEnabled: false pid=6981, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-05 11:27:38.544  1036  1643 D WifiService: setWifiEnabled: false pid=6981, uid=10118
08-05 11:27:38.544  1036  1643 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 11:27:38.551  7594  7594 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-05 11:27:38.562  1036  1535 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 11:27:38.562  1036  1535 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 11:27:38.562  1036  1535 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-05 11:27:38.563  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 11:27:38.563  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 11:27:38.563  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-05 11:27:38.563  1036  1535 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-05 11:27:38.564  1036  1535 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-05 11:27:38.564  1036  1535 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-05 11:27:38.564  1036  1535 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 11:27:38.564  1036  1535 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 11:27:38.564  1036  1535 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 11:27:38.564  1036  1535 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 11:27:38.571  1036  1535 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 11:27:38.571  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 11:27:38.572  7354  7354 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 11:27:38.572  1036  1534 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:38.572  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:38.572  1036  1535 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 11:27:38.572  1036  1535 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 11:27:38.572  1036  1535 D WifiNative-wlan0: SET ps 1: returned true
,08-05 11:27:38.572  1036  7440 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:38.573   303   881 D CommandListener: Clearing all IP addresses on wlan0
08-05 11:27:38.588  1036  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-05 11:27:38.588  1036  1544 D ConnectivityService: ignoring duplicate network state non-change
08-05 11:27:38.588  1036  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-05 11:27:38.591  1036  1535 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:38.591  1036  1535 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:38.591  1036  1535 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:38.592  1036  1535 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:38.592  1036  1535 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:38.594  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-05 11:27:38.595  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-05 11:27:38.595  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 11:27:38.596  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:38.596  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 11:27:38.596  1036  1534 D LGWifiP2pService: InactiveState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:38.596  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:38.596  1036  1534 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1b37a980
08-05 11:27:38.597  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:38.597  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:27:38.598  1036  1534 D LGWifiP2pService: P2pDisablingState
08-05 11:27:38.598  1036  1534 D LGWifiP2pService: P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:38.598  1036  1534 D LGWifiP2pService: p2p socket connection lost
08-05 11:27:38.598  1036  1534 D LGWifiP2pService: P2pDisabledState
08-05 11:27:38.599  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-05 11:27:38.599  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:38.599  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:38.599  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 11:27:38.599  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-05 11:27:38.599  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-05 11:27:38.599  1036  1555 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:38.600  1036  1556 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:38.600  1036  1535 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:27:38.600  1036  1535 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-05 11:27:38.600  1036  1535 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-05 11:27:38.601  1036  1534 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:38.601  1036  1534 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 11:27:38.601  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 11:27:38.601  7354  7354 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 11:27:38.602  1036  1535 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 11:27:38.602  1036  1535 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 11:27:38.602  1036  1535 D WifiNative-wlan0: SET ps 1: returned true
08-05 11:27:38.608  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 11:27:38.608  1939  1939 D WfdsService: WifiP2pState is changed : false
08-05 11:27:38.608  1939  2249 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-05 11:27:38.608  1939  2249 D WfdsService: Set the WFDS Monitor: false
08-05 11:27:38.609  1939  2249 D WfdsMonitor: WFDS Monitor is stopped
08-05 11:27:38.609  1939  2249 D WfdsService: STATE : WfdsDisabledState - enter
08-05 11:27:38.609  1939  2250 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-05 11:27:38.609  1939  7372 D CtrlSupplicant: Received on exit socket, terminate
08-05 11:27:38.609  1939  7372 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-05 11:27:38.609  1939  7372 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-05 11:27:38.609  1939  7372 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-05 11:27:38.609  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:38.611  1939  2249 W WfdsService: DefaultState - msg [9445378] is not handled
,08-05 11:27:38.619  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:38.619  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:27:38.620  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:38.635  1036  1544 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-05 11:27:38.635   303   881 D CommandListener: Clearing all IP addresses on wlan0
08-05 11:27:38.635  1036  1544 D DSQN    : disableDataServiceNotify
08-05 11:27:38.635  1036  1544 D DSQN    : stop dsqn bin
08-05 11:27:38.636  1036  1535 D WifiNative-p2p0: doBoolean: TERMINATE
,08-05 11:27:38.637  1036  1535 D WifiNative-p2p0: TERMINATE: returned true
08-05 11:27:38.637  1036  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:27:38.637  1036  1535 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:27:38.637  1036  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 11:27:38.637  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 11:27:38.637  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:27:38.638  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-05 11:27:38.638  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:38.639  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:38.638  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:38.639  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 11:27:38.640  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-05 11:27:38.641  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-05 11:27:38.641  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:27:38.641  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-05 11:27:38.641  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:38.641  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:38.641  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:38.641  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:38.641  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:27:38.641  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:27:38.641  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:38.641  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:38.641  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:27:38.641  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:38.641  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:38.642  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:38.642  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:38.642  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:38.642  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:38.642  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:27:38.642  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:27:38.642  6981  6981 V io.jxcore.node,.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:38.642  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:38.642  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:27:38.642  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:38.642  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:38.659  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 11:27:38.685  7594  7594 I dex2oat : dex2oat took 133.573ms (threads: 4)
,08-05 11:27:38.689  1036  1544 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-05 11:27:38.689  1036  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:38.689  1036  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:27:38.690  1036  1544 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:27:38.691  1036  1544 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-05 11:27:38.692  1036  1544 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-05 11:27:38.692  1036  1544 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-05 11:27:38.692  1036  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 11:27:38.694  1602  2121 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-05 11:27:38.695  7510  7528 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 11:27:38.695  7510  7528 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 11:27:38.695  7510  7528 I Adreno-EGL: Build Date: 12/12/14 금
08-05 11:27:38.695  7510  7528 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 11:27:38.695  7510  7528 I Adreno-EGL: Remote Branch: 
08-05 11:27:38.695  7510  7528 I Adreno-EGL: Local Patches: 
08-05 11:27:38.695  7510  7528 I Adreno-EGL: Reconstruct Branch: 
08-05 11:27:38.697  1036  7435 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-6ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:38.697  1036  7435 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-6ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:38.697  1036  7435 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-05 11:27:38.697  1036  1533 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 11:27:38.699  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 11:27:38.699  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 11:27:38.699  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 11:27:38.699  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-05 11:27:38.703  1036  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:38.703  1036  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 11:27:38.704  1036  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:38.704  1036  1544 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:38.704  1036  1544 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:38.704  1036  1544 D NetworkManagementService: Removing idletimer
08-05 11:27:38.704  1036  1544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:38.704  1036  1535 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:38.704  1036  1535 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 11:27:38.705  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:27:38.705  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 11:27:38.705  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 11:27:38.705  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 11:27:38.705  1036  1533 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 11:27:38.705  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 11:27:38.705  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 11:27:38.715  7354  7354 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-05 11:27:38.715  7354  7354 I wpa_supplicant: monitor socket send errors count : 1
08-05 11:27:38.716  7354  7354 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1939-4\x00 that cannot receive messages
,08-05 11:27:38.716  1036  7367 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-05 11:27:38.716  1036  7367 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 11:27:38.723  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 11:27:38.724  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:38.724  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:38.736  7354  7354 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 11:27:38.737  7354  7354 W wpa_supplicant: USIM:  scard_deinit function
08-05 11:27:38.737  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-05 11:27:38.737  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 11:27:38.737  1036  7367 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1,
08-05 11:27:38.738  1036  7367 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-05 11:27:38.738  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:27:38.738  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 11:27:38.738  1036  1118 D Tethering: InitialState.processMessage what=4
,08-05 11:27:38.740  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 11:27:38.740  1036  1535 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=337008
08-05 11:27:38.740  1036  1535 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=337009
08-05 11:27:38.741  1036  1535 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=337009  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 11:27:38.741  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-05 11:27:38.742  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:38.742  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:38.742  1036  1535 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=337011  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 11:27:38.743  1036  1535 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:38.744  1036  1535 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:38.753  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-05 11:27:38.756  6496  7132 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 11:27:38.763  2079  2079 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:38.768  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 11:27:38.768  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:38.768  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 11:27:38.768  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-05 11:27:38.771  7299  7299 I AppUp4:CustModeStarterReceiver: onReceive
08-05 11:27:38.773  7299  7299 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@22e5aa92
08-05 11:27:38.773  7299  7299 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 11:27:38.773  7299  7299 D AppUp4:CustFacade: isPhone : true
08-05 11:27:38.773  7299  7299 D AppUp4:CustModeStarterReceiver: begin check event
08-05 11:27:38.773  7299  7299 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 11:27:38.776  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:38.776  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 11:27:38.777  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:27:38.778  1036  7440 D DhcpStateMachine: StoppedState
08-05 11:27:38.778  1036  7440 D DhcpStateMachine: StoppedState{ when=-176ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:38.779  1036  1535 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-05 11:27:38.780  1036  1535 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-05 11:27:38.780  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:27:38.781  7510  7528 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 11:27:38.781  7510  7528 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 11:27:38.781  7510  7528 I Adreno-EGL: Build Date: 12/12/14 금
08-05 11:27:38.781  7510  7528 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 11:27:38.781  7510  7528 I Adreno-EGL: Remote Branch: 
08-05 11:27:38.781  7510  7528 I Adreno-EGL: Local Patches: 
08-05 11:27:38.781  7510  7528 I Adreno-EGL: Reconstruct Branch: 
,08-05 11:27:38.784  4787  7612 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 11:27:38.785  4787  7613 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:38.785  4787  7613 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 11:27:38.789  7336  7336 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-05 11:27:38.803  3391  3391 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 11:27:38.803  3391  3391 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:27:38.803  3391  3391 I LgeMiscReceiver: networkInfo.isConnected() = false
08-05 11:27:38.805  7203  7617 W FormManager: Network not available. Please check & try again.
08-05 11:27:38.809  7378  7378 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 11:27:38.809  7378  7378 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 11:27:38.811  7336  7615 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:38.816  7441  7441 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:27:38
,08-05 11:27:38.817  7203  7618 V FormManager: Network unavailable.
08-05 11:27:38.818  7441  7441 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 11:27:38.818  7441  7441 D Weather.Utils: 2 : All the weather widget is gone.
,08-05 11:27:38.818  7441  7441 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 11:27:38.818  7441  7441 D WeatherAncestor: connectivity changed - connection : true
08-05 11:27:38.818  7441  7441 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@210ee060
08-05 11:27:38.819  7441  7441 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 11:27:38.819  7441  7441 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 11:27:38.819  7441  7441 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,08-05 11:27:38.819  7441  7441 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 11:27:38.819  7441  7441 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:27:38
08-05 11:27:38.823  7203  7618 V FormManager: Network unavailable.
08-05 11:27:38.837  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 11:27:38.837  7110  7110 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 11:27:38.837  7110  7110 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 11:27:38.839  7110  7110 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-05 11:27:38.839  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 11:27:38.842  7110  7110 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 11:27:38.842  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 11:27:38.842  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 11:27:38.842  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 11:27:38.842  7110  7110 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 11:27:38.842  7110  7110 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 11:27:38.848  7133  7133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:27:38.850  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 11:27:38.852  7203  7624 W FormManager: Network not available. Please check & try again.
,08-05 11:27:38.855  7203  7625 V FormManager: Network unavailable.
08-05 11:27:38.857  7203  7625 V FormManager: Network unavailable.
08-05 11:27:38.858  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:38.859  7354  7354 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-05 11:27:38.859  1036  7367 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-05 11:27:38.860  1036  7367 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-05 11:27:38.860  1036  7367 D WifiMonitor: Disconnecting from the supplicant, no more events
08-05 11:27:38.860  1036  1535 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-05 11:27:38.861  1036  1544 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-05 11:27:38.872  7133  7133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 11:27:38.875  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 11:27:38.880  7203  7627 W FormManager: Network not available. Please check & try again.
08-05 11:27:38.881  7203  7628 V FormManager: Network unavailable.
08-05 11:27:38.883  7203  7628 V FormManager: Network unavailable.
,08-05 11:27:38.885  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:38.898  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:27:38.898  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 11:27:38.900  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 11:27:38.902  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:27:38.905  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:27:38.906  4787  7629 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 11:27:38.913  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 11:27:38.920  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 11:27:38.929  4787  7630 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:27:38.929  4787  7630 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 11:27:38.929  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:27:38.929  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:27:38.931  7165  7165 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 11:27:38.933  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:27:38.938  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 11:27:38.943  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 11:27:38.948  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 11:27:38.948  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:27:38.950  7165  7165 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 11:27:38.990  1036  1885 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7632 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-05 11:27:38.992  1036  1535 D WifiOffDelayIfNotUsed: stopMonitoring
08-05 11:27:38.992  1036  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:27:38.992  1036  1535 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:27:38.992  1036  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 11:27:38.994  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:38.996  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-05 11:27:38.996  1036  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-05 11:27:38.996  1036  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-05 11:27:38.996  2448  2448 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:38.999  1939  1939 D WfdsService: Supplicant Connection state is changed : false
08-05 11:27:38.999  1939  2249 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-05 11:27:38.999  1939  2249 D WfdsService: Set the WFDS Monitor: false
08-05 11:27:38.999  1939  2249 D WfdsMonitor: WFDS Monitor is stopped
08-05 11:27:39.000  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 11:27:39.000  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:39.000  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:39.000  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:39.000  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:39.000  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:27:39.000  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:27:39.000  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:39.000  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:39.000  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:27:39.002  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:39.002  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:39.002  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:39.002  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:39.002  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:27:39.002  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:27:39.002  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:39.002  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:39.002  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:27:39.050  7632  7632 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-05 11:27:39.051  7632  7632 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-05 11:27:39.057  7632  7632 V [BNRBootReceiver]: Boot Receiver Return
08-05 11:27:39.057  7632  7632 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-05 11:27:39.063  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-05 11:27:39.066  7110  7110 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-05 11:27:39.070  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:27:39.076  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:27:39.079  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:39.091  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:27:39.091  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:27:39.092  7165  7165 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 11:27:39.097  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:27:39.099  7510  7528 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:27:39.099  7510  7528 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 11:27:39.111  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:27:39.118  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:39.128  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 11:27:39.128  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:27:39.130  7165  7165 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 11:27:39.133  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:27:39.141  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:27:39.148  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:39.156  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:27:39.156  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 11:27:39.157  7165  7165 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 11:27:39.163  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:27:39.173  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:27:39.179  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:39.187  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:27:39.187  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 11:27:39.188  7165  7165 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 11:27:39.192  7510  7528 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 11:27:39.192  7510  7528 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 11:27:39.192  7510  7528 I Adreno-EGL: Build Date: 12/12/14 금
08-05 11:27:39.192  7510  7528 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 11:27:39.192  7510  7528 I Adreno-EGL: Remote Branch: 
08-05 11:27:39.192  7510  7528 I Adreno-EGL: Local Patches: 
08-05 11:27:39.192  7510  7528 I Adreno-EGL: Reconstruct Branch: 
08-05 11:27:39.193  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:27:39.214  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:27:39.223  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:39.233  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 11:27:39.234  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:27:39.235  7165  7165 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 11:27:39.248  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 11:27:39.264  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:27:39.277  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:39.280   303  7651 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 11:27:39.281  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-05 11:27:39.284  1815  7469 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-05 11:27:39.292  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:27:39.293  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:27:39.300  7165  7165 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 11:27:39.308  1815  7469 I CheckinService: active receiver: disabled
,08-05 11:27:39.310  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 11:27:39.328  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:27:39.336  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:39.347  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:27:39.347  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:27:39.348  7165  7165 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 11:27:39.354  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 11:27:39.360  7133  7133 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 11:27:39.498  1036  1993 I art     : Explicit concurrent mark sweep GC freed 115470(5MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.749ms total 137.066ms
,08-05 11:27:39.503  1036  1543 D WifiService: New client listening to asynchronous messages
08-05 11:27:39.504  7133  7133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:27:39.507  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:27:39.510  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:39.515  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:27:39.515  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:27:39.515  7165  7165 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 11:27:39.516  7165  7165 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 11:27:39.516  7165  7165 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 11:27:39.522  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:27:39.525  7133  7133 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 11:27:39.526  7133  7133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 11:27:39.529  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 11:27:39.532  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:39.537  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:27:39.537  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:27:39.538  7165  7165 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 11:27:39.538  7165  7165 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 11:27:39.538  7165  7165 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-05 11:27:39.540  1036  1884 I ActivityManager: Killing 7090:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-05 11:27:39.568  1036  1574 W libprocessgroup: failed to open /acct/uid_10037/pid_7090/cgroup.procs: No such file or directory
,08-05 11:27:39.576  2079  2079 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-05 11:27:39.576  1815  6362 I EventLogService: Aggregate from 1470389257953 (log), 1470387415347 (data)
08-05 11:27:39.577   303  7655 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 11:27:39.578  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 11:27:39.586  2079  2079 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-05 11:27:39.587  2079  2079 D c       : Getting all permits...
08-05 11:27:39.587  2079  2079 D a       : Opening database...
,08-05 11:27:39.593  2079  2079 D a       : Opening database auth.proximity.permit_store...
08-05 11:27:39.594  2079  2079 D a       : Closing database...
08-05 11:27:39.607  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 11:27:39.614  7133  7133 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-05 11:27:39.614  7133  7133 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 11:27:39.614  7133  7133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:27:39.622  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:27:39.629  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 11:27:39.635  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:27:39.635  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 11:27:39.637  7165  7165 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 11:27:39.641  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:27:39.647  7133  7133 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 11:27:39.647  7133  7133 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-05 11:27:39.647  7133  7133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:27:39.657  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:27:39.664  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:39.664  6875  7276 D UEI.SmartControl: Internal timer expired: 2
08-05 11:27:39.664  6875  7276 D UEI.SmartControl: unbind internal service
08-05 11:27:39.671  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 11:27:39.671  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:27:39.673  7165  7165 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 11:27:39.676  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:27:39.679  7133  7133 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 11:27:39.679  7133  7133 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 11:27:39.679  7133  7133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:27:39.683  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:27:39.691  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:39.698  7165  7165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:27:39.698  7165  7165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 11:27:39.700  7165  7165 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 11:27:39.708  7133  7133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 11:27:39.711  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 11:27:39.715  6875  7270 D serial_port: close(fd = 24)
08-05 11:27:39.718  6875  7270 I UEI.SmartControl: Serial port is closed.
08-05 11:27:39.719  7203  7660 W FormManager: Network not available. Please check & try again.
08-05 11:27:39.721  7203  7661 V FormManager: Network unavailable.
08-05 11:27:39.721  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:39.728  7203  7661 V FormManager: Network unavailable.
,08-05 11:27:39.738  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:27:39.738  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 11:27:39.741  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:27:39.744  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 11:27:39.754  4787  7662 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 11:27:39.756  7133  7133 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-05 11:27:39.756  7133  7133 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 11:27:39.756  7133  7133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 11:27:39.760  4787  7663 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:27:39.760  4787  7663 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 11:27:39.762  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 11:27:39.773  7203  7665 W FormManager: Network not available. Please check & try again.
08-05 11:27:39.775  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:39.784  7203  7666 V FormManager: Network unavailable.
08-05 11:27:39.788  7203  7666 V FormManager: Network unavailable.
,08-05 11:27:39.807  2079  2079 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-05 11:27:40.710  1036  1535 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1510445478] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 11:27:40.712  1036  1535 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1510445480] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 11:27:40.859  1036  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:27:40.875  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-05 11:27:40.881  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:27:40.885  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:40.889  1036  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:40.893  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 11:27:40.894  6496  7132 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-05 11:27:40.907  5810  5810 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 11:27:40.926  2079  2079 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:27:40.964  1036  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 11:27:40.976  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 11:27:40.976  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:40.976  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 11:27:40.976  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 11:27:40.979  7299  7299 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 11:27:40.985  7299  7299 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@22e5aa92
08-05 11:27:40.985  7299  7299 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 11:27:40.986  7299  7299 D AppUp4:CustFacade: isPhone : true
08-05 11:27:40.987  7299  7299 D AppUp4:CustModeStarterReceiver: begin check event
08-05 11:27:40.988  7299  7299 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 11:27:40.992  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:40.993  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 11:27:40.994  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 11:27:41.005  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:27:41.012  7336  7336 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 11:27:41.014  4787  7684 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 11:27:41.019  4787  7685 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:41.019  4787  7685 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 11:27:41.040  3391  3391 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 11:27:41.040  3391  3391 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:41.041  3391  3391 I LgeMiscReceiver: networkInfo.isConnected() = true
08-05 11:27:41.041  3391  3391 D PhoneState: setPdpRejectCasuse : false
,08-05 11:27:41.045  7203  7690 W FormManager: Network not available. Please check & try again.
08-05 11:27:41.046  7336  7687 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:41.052  7378  7378 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-05 11:27:41.052  7378  7378 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 11:27:41.059  7203  7691 V FormManager: Network unavailable.
,08-05 11:27:41.064  7441  7441 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:27:41
,08-05 11:27:41.065  7441  7441 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 11:27:41.065  7441  7441 D Weather.Utils: 2 : All the weather widget is gone.
08-05 11:27:41.065  7203  7691 V FormManager: Network unavailable.
,08-05 11:27:41.065  7441  7441 D UpdateThreadPoolManager: 2 : This is isUpdating : false,
08-05 11:27:41.065  7441  7441 D WeatherAncestor: connectivity changed - connection : true
08-05 11:27:41.066  7441  7441 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@210ee060
08-05 11:27:41.066  7441  7441 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-05 11:27:41.066  7441  7441 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 11:27:41.066  7441  7441 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 11:27:41.066  7441  7441 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 11:27:41.066  7441  7441 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:27:41
08-05 11:27:41.564  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:41.565  1036  1051 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-05 11:27:41.598  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 11:27:41.599  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 11:27:41.599  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-05 11:27:41.600  1036  1118 D BluetoothManagerService: Message: 1
08-05 11:27:41.600  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-05 11:27:41.626  1036  1118 D BluetoothManagerService: Message: 20
08-05 11:27:41.627  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@216789d2:true
,08-05 11:27:41.631  7227  7227 D BluetoothAdapterState: make
08-05 11:27:41.636  7227  7227 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-05 11:27:41.636  7227  7227 I bluedroid-qcom: init
08-05 11:27:41.638  7227  7708 I BluetoothAdapterState: Entering OffState
08-05 11:27:41.638  7227  7227 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 11:27:41.638  7227  7227 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 11:27:41.639  7227  7227 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 11:27:41.639  7227  7227 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 11:27:41.639  7227  7227 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-05 11:27:41.641  7227  7227 I bluedroid-qcom: get_profile_interface socket
08-05 11:27:41.641  7227  7227 I bluedroid-qcom: get_profile_interface map_client
,08-05 11:27:41.646  7227  7712 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-05 11:27:41.633  7711  7711 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:41.643  7711  7711 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:41.653  7227  7712 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-05 11:27:41.661  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-05 11:27:41.662  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 11:27:41.662  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-05 11:27:41.665  1036  1118 D BluetoothManagerService: Message: 40
08-05 11:27:41.665  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-05 11:27:41.667  7711  7711 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-05 11:27:41.667  7711  7711 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-05 11:27:41.667  7711  7711 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-05 11:27:41.669  7227  7245 I bluedroid-qcom: config_hci_snoop_log
08-05 11:27:41.671  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-05 11:27:41.671  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-05 11:27:41.672  7711  7711 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-05 11:27:41.676  7711  7711 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-05 11:27:41.676  7711  7711 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-05 11:27:41.684  7227  7708 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-05 11:27:41.684  7227  7712 D BluetoothAdapterProperties: Name is: G3
08-05 11:27:41.685  7227  7708 D BluetoothAdapterProperties: Setting state to 11
08-05 11:27:41.685  7227  7708 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-05 11:27:41.686  1036  1118 D BluetoothManagerService: Message: 60
08-05 11:27:41.686  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-05 11:27:41.686  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-05 11:27:41.687  7227  7708 I LGBluetoothServiceJni: classInitNative: succeeds
08-05 11:27:41.692  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-05 11:27:41.696  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 11:27:41.701  7110  7110 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-05 11:27:41.703  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:41.704  1036  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:41.706  1036  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:27:41.722  1036  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:27:41.729  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:41.734  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-05 11:27:41.735  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:41.737  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:41.738  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-05 11:27:41.746  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:41.748  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:41.748  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 11:27:41.750  6496  7132 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 11:27:41.751  7227  7227 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 11:27:41.752  7227  7227 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:41.752  7227  7227 V BluetoothPbapReceiver: ***********state = 11
,08-05 11:27:41.756  7227  7708 D BluetoothBondStateMachine: make
08-05 11:27:41.757  5810  5810 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-05 11:27:41.760  7227  7708 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:41.760  7227  7708 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-05 11:27:41.760  7227  7708 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:41.760  7227  7708 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-05 11:27:41.760  7227  7708 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-05 11:27:41.761  7227  7724 I BluetoothBondStateMachine: StableState(): Entering Off State
08-05 11:27:41.763  1036  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:41.763  1036  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:41.763  1036  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:41.766  2079  2079 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 11:27:41.771  7227  7708 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:27:41.823  1036  1884 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7730 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-05 11:27:41.829  7227  7227 D HeadsetService: Received start request. Starting profile...
08-05 11:27:41.830  7227  7227 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 11:27:41.830  7227  7227 D LGBluetoothHfpAdapter: Version 1.6
08-05 11:27:41.831  7227  7708 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:27:41.833  7227  7227 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 11:27:41.835  7227  7227 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 11:27:41.835  7227  7227 D HeadsetStateMachine: make
08-05 11:27:41.835  5810  5810 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 11:27:41.846  7227  7708 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:27:41.852  2079  2079 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:41.856  7227  7708 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 11:27:41.865  7227  7708 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:27:41.868  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 11:27:41.868  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:41.868  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 11:27:41.868  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 11:27:41.872  7299  7299 I AppUp4:CustModeStarterReceiver: onReceive
08-05 11:27:41.872  7227  7708 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 11:27:41.877  7227  7708 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:27:41.879  7227  7227 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:27:41.879  7227  7227 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 11:27:41.890  7299  7299 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@22e5aa92
08-05 11:27:41.890  7299  7299 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-05 11:27:41.890  7299  7299 D AppUp4:CustFacade: isPhone : true
08-05 11:27:41.890  7227  7227 D HeadsetStateMachine: max_hf_connections = 1
08-05 11:27:41.890  7227  7227 I bluedroid-qcom: get_profile_interface handsfree
08-05 11:27:41.890  7299  7299 D AppUp4:CustModeStarterReceiver: begin check event
08-05 11:27:41.891  7299  7299 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 11:27:41.891  7227  7708 V LGMDMManager: Create singleton instance
,08-05 11:27:41.892  7227  7227 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-05 11:27:41.894  7227  7708 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-05 11:27:41.894   309  2163 V AudioPolicyService: registerClient() client 0xb0410560, uid 1002
08-05 11:27:41.894   309  2163 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-05 11:27:41.894   309  2163 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 11:27:41.894   309  2163 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 11:27:41.894  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:41.894  7227  7227 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 11:27:41.894  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 11:27:41.895  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:27:41.897  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:27:41.897   309  1383 V AudioFlinger: registerClient() client 0xb55814f0, pid 7227
08-05 11:27:41.898  7227  7227 V ToneGenerator: Create Track: 0xb4928080
,08-05 11:27:41.898  7227  7227 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-05 11:27:41.898  7227  7227 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-05 11:27:41.899   309   309 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 11:27:41.899   309   309 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-05 11:27:41.899   309   309 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 11:27:41.899   309   309 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 11:27:41.899   309  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:27:41.899  7227  7227 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 11:27:41.899   309  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:27:41.899  1850  2477 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:27:41.899  1850  2477 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:27:41.900  7227  7244 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:27:41.900  7227  7244 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-05 11:27:41.900   309  1383 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 11:27:41.902  1602  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:27:41.902  1602  1620 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:27:41.903   309  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:27:41.903  1036  2031 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:27:41.903   309  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:27:41.903  1036  2031 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:27:41.903  1036  2031 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:27:41.903  1036  2031 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-05 11:27:41.903  1850  4887 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:27:41.903  1850  4887 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:27:41.903  7227  7244 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:27:41.903  7227  7244 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-05 11:27:41.904  3391  3407 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:27:41.904  3391  3407 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:27:41.904  3391  3407 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:27:41.904  3391  3407 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:27:41.905   309  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 11:27:41.905   309  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-05 11:27:41.905   309  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 11:27:41.905   309  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 11:27:41.905  7227  7227 V AudioSystem: getLatency() output 2, latency 50
08-05 11:27:41.905  7227  7227 V AudioSystem: getFrameCount() output 2, frameCount 960
08-05 11:27:41.905  7227  7227 V AudioTrack: createTrack_l() output 2 afLatency 50
08-05 11:27:41.905   309   309 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 11:27:41.905   309   309 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 11:27:41.905   309   309 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 11:27:41.905   309   309 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 11:27:41.905   309   309 V AudioFlinger: createTrack() lSessionId: 22
08-05 11:27:41.907  7336  7336 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-05 11:27:41.907  1602  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:27:41.907  1602  1622 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:27:41.907  7227  7227 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-05 11:27:41.907   309  2163 V AudioFlinger: acquiring 22 from 7227, for 7227
08-05 11:27:41.907   309  2163 V AudioFlinger:  added new entry for 22
08-05 11:27:41.907  7227  7227 V ToneGenerator: ToneGenerator INIT OK, time: 340189
08-05 11:27:41.908  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:41.908  7227  7742 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-05 11:27:41.909  7227  7742 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 11:27:41.909  7227  7742 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 11:27:41.909  7227  7742 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-05 11:27:41.909  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:41.910   309  2164 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7227
08-05 11:27:41.910   309  2164 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-05 11:27:41.910   309  2164 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-05 11:27:41.910   309  2164 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-05 11:27:41.910   309  2164 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 11:27:41.910   309  2164 V voice   : voice_set_parameters: exit with code(0)
08-05 11:27:41.910   309  2164 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-05 11:27:41.910   309,  2164 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-05 11:27:41.911   309  2164 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 11:27:41.911   309  2164 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 11:27:41.911   309  2164 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 11:27:41.911   309  2164 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-05 11:27:41.911  7227  7742 V ToneGenerator: ToneGenerator destructor
08-05 11:27:41.911  7227  7227 D A2dpService: Received start request. Starting profile...
08-05 11:27:41.911  7227  7742 V ToneGenerator: stopTone
08-05 11:27:41.911  7227  7742 V ToneGenerator: Delete Track: 0xb4928080
08-05 11:27:41.911  7227  7742 V AudioTrack: ~AudioTrack, releasing session id from 7227 on behalf of 7227
08-05 11:27:41.911   309  1383 V AudioFlinger: releasing 22 from 7227 for 7227
08-05 11:27:41.911   309  1383 V AudioFlinger:  decremented refcount to 0
08-05 11:27:41.911   309  1383 V AudioFlinger: purging stale effects
08-05 11:27:41.911   309  1383 V AudioPolicyService: AudioCommandThread() adding release output 2
08-05 11:27:41.912   309  1383 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-05 11:27:41.912  7227  7227 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 11:27:41.912   309  1274 V AudioPolicyService: AudioCommandThread() waking up
08-05 11:27:41.912   309  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
08-05 11:27:41.912   309  1274 V AudioPolicyManager: releaseOutput() 2
08-05 11:27:41.912   309  1274 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 11:27:41.912   309  1383 V AudioFlinger: PlaybackThread::Track destructor
08-05 11:27:41.912   309  1383 V AudioFlinger: removeClient_l() pid 7227, calling pid 309
08-05 11:27:41.912  7227  7227 V Avrcp   : make
08-05 11:27:41.913  7227  7227 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-05 11:27:41.913  7227  7227 I bluedroid-qcom: get_profile_interface avrcp
08-05 11:27:41.914  1036  1643 W Process : Unable to open /proc/7750/status
,08-05 11:27:41.916  4787  7749 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 11:27:41.929  7227  7227 V AudioManager: registerRemoteController: size of Media player list: 0
,08-05 11:27:41.931  3391  3391 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 11:27:41.931  3391  3391 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:41.931  3391  3391 I LgeMiscReceiver: networkInfo.isConnected() = false
08-05 11:27:41.933  7227  7227 E AudioManager: No RCC entry present to update
08-05 11:27:41.933  7227  7227 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-05 11:27:41.935  7227  7227 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-05 11:27:41.936  7227  7227 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-05 11:27:41.936  7227  7227 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-05 11:27:41.941  7336  7756 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:41.941  4787  7755 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:27:41.941  4787  7755 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 11:27:41.941  7203  7752 W FormManager: Network not available. Please check & try again.
08-05 11:27:41.942  7227  7227 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-05 11:27:41.948  7378  7378 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-05 11:27:41.948  7378  7378 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 11:27:41.978  7730  7730 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 11:27:41.979  7730  7730 W LG Account v2.2: No ProfileInfo entries
08-05 11:27:41.979  7730  7730 I LG Account v2.2: isEnabled: false
,08-05 11:27:41.979  7730  7730 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 11:27:41.979  7730  7730 I Feature : [Lifetracker]Country: EU
08-05 11:27:41.979  7730  7730 I Feature : [Lifetracker]Operator: OPEN
08-05 11:27:41.979  7730  7730 I Feature : [Lifetracker]Ranking support: false
08-05 11:27:41.980  7730  7730 I Feature : [Lifetracker]Comfort support: false
08-05 11:27:41.980  7730  7730 I Feature : [Lifetracker]Accessory: true
08-05 11:27:41.980  7730  7730 I Feature : [Lifetracker]Health device: true
08-05 11:27:41.980  7730  7730 I Feature : [Lifetracker]Extra Pedometer: false
08-05 11:27:41.980  7730  7730 I Feature : [Lifetracker]Blood glucose device: false
08-05 11:27:41.980  7730  7730 I Feature : [Lifetracker]Device Number: 3
08-05 11:27:41.984  7441  7441 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:27:41
08-05 11:27:41.985  7203  7753 V FormManager: Network unavailable.
08-05 11:27:41.989  7110  7110 D BluetoothPermissionRequest: onReceive
08-05 11:27:41.989  7441  7441 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 11:27:41.989  7441  7441 D Weather.Utils: 2 : All the weather widget is gone.
08-05 11:27:41.989  7203  7753 V FormManager: Network unavailable.
08-05 11:27:41.990  7441  7441 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 11:27:41.990  7441  7441 D WeatherAncestor: connectivity changed - connection : true
08-05 11:27:41.990  7441  7441 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@210ee060
08-05 11:27:41.991  7441  7441 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 11:27:41.991  7441  7441 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 11:27:41.991  7441  7441 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 11:27:41.991  7441  7441 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 11:27:41.991  7441  7441 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:27:41
,08-05 11:27:41.992  7110  7110 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 11:27:42.009  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 11:27:42.010  6496  7132 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-05 11:27:42.019  1036  1957 V SIM_STK : Menu title from STK is T-Mobile
08-05 11:27:42.020  1036  1957 V SIM_STK : Menu title from STK is T-Mobile
08-05 11:27:42.023  2079  2079 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:27:42.032  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-05 11:27:42.032  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:42.032  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 11:27:42.032  7299  7299 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 11:27:42.033  7299  7299 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 11:27:42.035  7299  7299 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@22e5aa92
08-05 11:27:42.035  7299  7299 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 11:27:42.035  7299  7299 D AppUp4:CustFacade: isPhone : true
08-05 11:27:42.036  7299  7299 D AppUp4:CustModeStarterReceiver: begin check event
08-05 11:27:42.036  7299  7299 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 11:27:42.039  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:42.039  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 11:27:42.040  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:27:42.041  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:27:42.046  7336  7336 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 11:27:42.049  4787  7761 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 11:27:42.055  4787  7762 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:42.056  4787  7762 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 11:27:42.060  7336  7763 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 11:27:42.064  7203  7765 W FormManager: Network not available. Please check & try again.
08-05 11:27:42.067  3391  3391 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 11:27:42.067  3391  3391 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 11:27:42.068  1036  1885 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-05 11:27:42.067  3391  3391 I LgeMiscReceiver: networkInfo.isConnected() = false
08-05 11:27:42.070  7203  7766 V FormManager: Network unavailable.
08-05 11:27:42.070  7378  7378 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 11:27:42.070  7378  7378 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 11:27:42.072  7227  7227 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 11:27:42.073  7203  7766 V FormManager: Network unavailable.
,08-05 11:27:42.075  7227  7227 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 11:27:42.075  7227  7227 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 11:27:42.075  7227  7227 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 11:27:42.075  7227  7227 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 11:27:42.075  7227  7227 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 11:27:42.075  7227  7227 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 11:27:42.075  7227  7227 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 11:27:42.075  7227  7227 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 11:27:42.075  7227  7227 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 11:27:42.076  7227  7227 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 11:27:42.076  7227  7227 I BluetoothA2dpServiceJni: classInitNative
08-05 11:27:42.076  7227  7227 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 11:27:42.076  7227  7227 D A2dpStateMachine: make
08-05 11:27:42.077  7227  7227 I bluedroid-qcom: get_profile_interface a2dp
08-05 11:27:42.077  7227  7769 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-05 11:27:42.079  7227  7227 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-05 11:27:42.079  7441  7441 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:27:42
08-05 11:27:42.079  7227  7227 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-05 11:27:42.080  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:42.080  7227  7768 D A2dpStateMachine: Enter Disconnected: -2
08-05 11:27:42.081  7227  7227 I BluetoothHidServiceJni: classInitNative: succeeds
08-05 11:27:42.082  7441  7441 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 11:27:42.082  7227  7227 D HidService: Received start request. Starting profile...
08-05 11:27:42.082  7441  7441 D Weather.Utils: 2 : All the weather widget is gone.
08-05 11:27:42.082  7227  7227 I bluedroid-qcom: get_profile_interface hidhost
08-05 11:27:42.082  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:42.082  7441  7441 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 11:27:42.082  7441  7441 D WeatherAncestor: connectivity changed - connection : true
08-05 11:27:42.082  7441  7441 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@210ee060
08-05 11:27:42.082  7227  7227 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 11:27:42.083  7441  7441 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 11:27:42.083  7441  7441 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 11:27:42.083  7441  7441 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 11:27:42.083  7441  7441 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 11:27:42.083  7441  7441 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:27:42
08-05 11:27:42.085  7227  7227 D HealthService: Received start request. Starting profile...
,08-05 11:27:42.086  7227  7227 I bluedroid-qcom: get_profile_interface health
08-05 11:27:42.086  7227  7227 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-05 11:27:42.086  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:42.087  7227  7227 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-05 11:27:42.088  7227  7227 D PanService: Received start request. Starting profile...
08-05 11:27:42.088  7227  7227 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 11:27:42.088  7227  7227 I bluedroid-qcom: get_profile_interface pan
08-05 11:27:42.095  7227  7227 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-05 11:27:42.095  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:42.096  7227  7227 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-05 11:27:42.101  7227  7227 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 11:27:42.102  7227  7227 D BtGatt.GattService: Received start request. Starting profile...
08-05 11:27:42.102  7227  7227 D BtGatt.GattService: start()
08-05 11:27:42.102  7227  7227 I bluedroid-qcom: get_profile_interface gatt
08-05 11:27:42.102  7227  7227 D BtGatt.AdvertiseManager: advertise manager created
08-05 11:27:42.106  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:42.107  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:42.107  7227  7227 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-05 11:27:42.108  7227  7227 V BluetoothMapService: BluetoothMapBinder()
08-05 11:27:42.108  7227  7227 D BluetoothMapService: Received start request. Starting profile...
08-05 11:27:42.108  7227  7227 D BluetoothMapService: start()
08-05 11:27:42.110  7227  7227 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-05 11:27:42.110  7227  7227 D BluetoothMapEmailAppObserver: createReceiver()
08-05 11:27:42.111  7227  7227 D BluetoothMapEmailAppObserver: initObservers()
08-05 11:27:42.111  7227  7227 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-05 11:27:42.116  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:42.116  7227  7227 D HeadsetStateMachine: Proxy object connected
08-05 11:27:42.116  7227  7227 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-05 11:27:42.117  7227  7227 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-05 11:27:42.119  7227  7227 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 11:27:42.120  7227  7742 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 11:27:42.120  7227  7742 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 11:27:42.120  7227  7742 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-05 11:27:42.121  7227  7227 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 11:27:42.123  7227  7227 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 11:27:42.125  7227  7227 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 11:27:42.125  7227  7227 V PanService: [BTUI] SIM Extra State :ABSENT
08-05 11:27:42.127  7227  7227 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 11:27:42.129  7227  7227 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-05 11:27:42.129  7227  7227 V BluetoothMapService: Handler(): got msg=1
08-05 11:27:42.130  7227  7708 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-05 11:27:42.130  7227  7708 I bluedroid-qcom: enable
,08-05 11:27:42.130  7227  7776 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-05 11:27:42.130  7227  7776 I bt-btu  : btu_task pending for preload complete event
08-05 11:27:42.130  7227  7708 I bt_hci_bdroid: init
08-05 11:27:42.131  7227  7708 I bt_vendor: bt-vendor : init
08-05 11:27:42.131  7227  7708 I bt_vendor: bt-vendor : get_bt_soc_type
08-05 11:27:42.131  7227  7708 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-05 11:27:42.131  7227  7708 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-05 11:27:42.131  7227  7708 D bt_userial_mct: userial_init
08-05 11:27:42.132  7227  7708 D bt_hci_bdroid: set_power 1
08-05 11:27:42.132  7227  7708 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-05 11:27:42.132  7227  7708 I bt_vendor: Starting hciattach daemon
08-05 11:27:42.132  7227  7708 I bt_vendor: try to set true
08-05 11:27:42.132  7227  7227 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:42.133  7227  7227 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:27:42.133  7227  7227 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 11:27:42.133  7227  7227 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 11:27:42.133  7227  7227 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:42.133  7227  7227 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-05 11:27:42.123  7779  7779 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:42.123  7779  7779 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 11:27:42.149  7781  7781 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-05 11:27:42.214  7787  7787 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-05 11:27:42.241  7788  7788 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 11:27:42.276  7790  7790 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 11:27:42.290  7791  7791 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-05 11:27:42.305  7792  7792 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 11:27:42.330  7793  7793 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-05 11:27:42.371  7795  7795 I libmdmdetect: ESOC framework not supported
,08-05 11:27:42.372  7795  7795 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-05 11:27:42.383  7795  7795 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-05 11:27:42.383  7795  7795 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-05 11:27:42.383  7795  7795 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-05 11:27:42.383  7795  7795 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-05 11:27:42.383  7795  7795 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-05 11:27:42.383  7795  7795 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-05 11:27:42.383  7795  7795 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-05 11:27:42.422  7795  7796 E QC-QMI  : qmi_client [7795] 14: failed to locate client data
08-05 11:27:42.423   468   468 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-05 11:27:42.423   468   468 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-05 11:27:42.456  7803  7803 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-05 11:27:42.474  7804  7804 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-05 11:27:42.535  7227  7708 I bt_vendor: bluetooth satus is on
08-05 11:27:42.535  7227  7708 D bt_hci_bdroid: preload
,08-05 11:27:42.538  7227  7778 D bt_userial_mct: userial_open(port:0)
08-05 11:27:42.538  7227  7778 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-05 11:27:42.542  7227  7778 I bt_vendor: Done intiailizing UART
08-05 11:27:42.543  7227  7778 I bt_vendor: Done intiailizing UART
08-05 11:27:42.543  7227  7778 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-05 11:27:42.544  7227  7778 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-05 11:27:42.544  7227  7806 D bt_userial_mct: Entering userial_read_thread()
08-05 11:27:42.544  7227  7776 I bt-btu  : btu_task received preload complete event
08-05 11:27:42.545  7227  7776 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-05 11:27:42.545  7227  7776 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-05 11:27:42.547  7227  7776 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-05 11:27:42.553  7227  7776 I         : BTE_InitTraceLevels -- TRC_HCI
,08-05 11:27:42.553  7227  7776 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 11:27:42.553  7227  7776 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 11:27:42.553  7227  7776 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 11:27:42.553  7227  7776 I         : BTE_InitTraceLevels -- TRC_AVRC
08-05 11:27:42.553  7227  7776 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 11:27:42.553  7227  7776 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-05 11:27:42.554  7227  7776 I         : BTE_InitTraceLevels -- TRC_BTM,
08-05 11:27:42.554  7227  7776 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-05 11:27:42.554  7227  7776 I         : BTE_InitTraceLevels -- TRC_GAP
,08-05 11:27:42.554  7227  7776 I         : BTE_InitTraceLevels -- TRC_PAN
,08-05 11:27:42.554  7227  7776 I         : BTE_InitTraceLevels -- TRC_SDP
,08-05 11:27:42.554  7227  7776 I         : BTE_InitTraceLevels -- TRC_GATT
,08-05 11:27:42.554  7227  7776 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 11:27:42.554  7227  7776 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 11:27:42.554  7227  7776 I         : BTE_InitTraceLevels -- TRC_BTIF
08-05 11:27:42.652  7227  7776 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-05 11:27:42.652  7227  7776 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0231061 
08-05 11:27:42.652  7227  7776 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0231061 
,08-05 11:27:42.689  7227  7712 E bt-btif : Calling BTA_HhEnable
08-05 11:27:42.689  7227  7712 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-05 11:27:42.690  7227  7712 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 11:27:42.693  7227  7776 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-05 11:27:42.693  7227  7776 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-05 11:27:42.694  7227  7776 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-05 11:27:42.694  7227  7776 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-05 11:27:42.694  7227  7776 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-05 11:27:42.695  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 11:27:42.696  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 11:27:42.696  7227  7712 D BluetoothAdapterProperties: Name is: G3
08-05 11:27:42.697  7227  7712 D BluetoothAdapterProperties: Scan Mode:20
08-05 11:27:42.698  7227  7712 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 11:27:42.698  7227  7712 D bt_hci_bdroid: postload
08-05 11:27:42.699  7227  7778 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 11:27:42.699  7227  7776 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-05 11:27:42.700  7227  7712 D bte_conf: Device ID record 1 : primary
08-05 11:27:42.700  7227  7712 D bte_conf:   vendorId            = 00c4
08-05 11:27:42.700  7227  7712 D bte_conf:   vendorIdSource      = 0001
08-05 11:27:42.700  7227  7712 D bte_conf:   product             = 13a1
08-05 11:27:42.700  7227  7712 D bte_conf:   version             = 1000
08-05 11:27:42.700  7227  7712 D bte_conf:   clientExecutableURL = 
08-05 11:27:42.700  7227  7712 D bte_conf:   serviceDescription  = 
08-05 11:27:42.700  7227  7712 D bte_conf:   documentationURL    = 
08-05 11:27:42.701  7227  7712 D bte_conf: bte_load_did_conf no section named DID2.
08-05 11:27:42.701  7227  7778 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 11:27:42.701  7227  7778 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 11:27:42.702  7227  7778 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 11:27:42.706  7227  7806 E bt_mct  : hci lib postload completed
,08-05 11:27:42.712  7227  7708 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-05 11:27:42.712  7227  7708 D BluetoothAdapterProperties: ScanMode =  20
08-05 11:27:42.712  7227  7708 D BluetoothAdapterProperties: State =  11
08-05 11:27:42.712  7227  7708 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-05 11:27:42.712  7227  7708 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-05 11:27:42.712  7227  7708 D BluetoothAdapterProperties: Setting state to 12
08-05 11:27:42.712  7227  7708 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 11:27:42.713  7227  7712 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-05 11:27:42.713  7227  7712 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 11:27:42.703  7811  7811 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:42.703  7811  7811 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:42.719  1036  1118 D BluetoothManagerService: Message: 60
08-05 11:27:42.719  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-05 11:27:42.719  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-05 11:27:42.719  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 11:27:42.723  7227  7708 I BluetoothAdapterState: Entering On State
08-05 11:27:42.729  7227  7776 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:27:42.729  7227  7776 W bt-smp  : Plain text(LSB ~ MSB) = 86 be 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:27:42.729  7227  7776 W bt-smp  : Encrypted text(LSB ~ MSB) = 1b 8e 73 e7 fd 17 a1 a5 70 7d 55 21 89 3d e6 6e 
08-05 11:27:42.730  7227  7776 W bt-btm  : Stopping oneshot timer
08-05 11:27:42.740  7227  7708 D LGBluetoothServiceAdapter: [BTUI] OnState
08-05 11:27:42.740  7227  7708 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-05 11:27:42.740  7227  7708 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-05 11:27:42.751  7227  7708 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-05 11:27:42.762  7227  7776 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:27:42.762  7227  7776 W bt-smp  : Plain text(LSB ~ MSB) = c2 9e 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:27:42.762  7227  7776 W bt-smp  : Encrypted text(LSB ~ MSB) = f7 52 c7 f4 72 a3 c4 a8 e1 46 14 ca 80 c3 02 6f 
08-05 11:27:42.763  7227  7776 W bt-btm  : Stopping oneshot timer
08-05 11:27:42.768  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:42.768  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:42.768  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:42.768  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:27:42.768  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:42.768  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:42.768  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:42.768  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:27:42.773  7227  7712 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 11:27:42.773  7227  7712 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-05 11:27:42.774  7227  7708 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-05 11:27:42.775  7227  7776 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:27:42.775  7227  7776 W bt-smp  : Plain text(LSB ~ MSB) = 76 b4 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:27:42.775  7227  7776 W bt-smp  : Encrypted text(LSB ~ MSB) = d3 65 8a 9b 21 4e ca a4 ed 01 6b 85 f0 ec d3 90 
08-05 11:27:42.776  7227  7776 W bt-btm  : Stopping oneshot timer
08-05 11:27:42.784  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 11:27:42.788  7227  7776 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:27:42.788  7227  7776 W bt-smp  : Plain text(LSB ~ MSB) = e0 b8 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:27:42.789  7227  7776 W bt-smp  : Encrypted text(LSB ~ MSB) = d6 03 a3 79 6f 64 4a 2b 60 52 65 c9 25 7a d7 e8 
08-05 11:27:42.790  7227  7776 W bt-btm  : Stopping oneshot timer
08-05 11:27:42.794  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:42.794  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:42.794  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:42.794  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:27:42.794  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:42.794  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:42.794  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:42.794  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:27:42.807  7227  7776 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:27:42.807  7227  7776 W bt-smp  : Plain text(LSB ~ MSB) = be 09 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:27:42.807  7227  7776 W bt-smp  : Encrypted text(LSB ~ MSB) = de 90 3d 65 00 fd f5 88 36 ce 23 c9 41 9a 72 de 
08-05 11:27:42.809  7227  7776 W bt-btm  : Stopping oneshot timer
,08-05 11:27:42.816  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:42.820  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 11:27:42.824  7110  7251 D BluetoothPbap: onBluetoothStateChange: up=true
,08-05 11:27:42.827  1036  1036 D BluetoothHeadset: Proxy object connected
08-05 11:27:42.835  1036  1036 D BluetoothA2dp: Proxy object connected
08-05 11:27:42.845  7828  7828 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-05 11:27:42.849  7110  7129 D BluetoothPan: onBluetoothStateChange on: true
08-05 11:27:42.849  7110  7129 D BluetoothPan: onBluetoothStateChange call bindService
08-05 11:27:42.854  7110  7128 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 11:27:42.854  7110  7110 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 11:27:42.854  7110  7110 D PanProfile: Bluetooth service connected
08-05 11:27:42.860  7110  7110 D BluetoothInputDevice: Proxy object connected
08-05 11:27:42.861  7110  7110 D HidProfile: Bluetooth service connected
,08-05 11:27:42.861  7110  7129 D BluetoothMap: onBluetoothStateChange: up=true
08-05 11:27:42.869  1850  4887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:27:42.872  1850  1850 D BluetoothHeadset: Proxy object connected
08-05 11:27:42.872  7110  7110 D BluetoothMap: Proxy object connected
08-05 11:27:42.872  7110  7110 D MapProfile: Bluetooth service connected
08-05 11:27:42.872  7110  7110 D BluetoothMap: getConnectedDevices()
08-05 11:27:42.872  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:27:42.873  7227  7824 V BluetoothMapService: getConnectedDevices()
08-05 11:27:42.874  1850  1850 D BluetoothHeadset: Proxy object connected
08-05 11:27:42.874  1850  2477 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 11:27:42.876  1036  1111 W ProcessCpuTracker: Skipping unknown process pid 7811
08-05 11:27:42.876  1036  1111 W ProcessCpuTracker: Skipping unknown process pid 7814
08-05 11:27:42.878  1850  1850 D BluetoothHeadset: Proxy object connected
08-05 11:27:42.880  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-05 11:27:42.880  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-05 11:27:42.880  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-05 11:27:42.881  1036  1118 D BluetoothManagerService: Message: 40
08-05 11:27:42.881  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-05 11:27:42.881  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:42.882  1939  2117 D LGBluetoothAPIService: Message: 1
08-05 11:27:42.882  1939  2117 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-05 11:27:42.884  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 11:27:42.888  6981  6981 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-05 11:27:42.890  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:42.891  1939  2117 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-05 11:27:42.892  7110  7110 D LocalBluetoothProfileManager: Adding local A2DP profile
08-05 11:27:42.892  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:42.892  7227  7227 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:42.892  7227  7227 D BluetoothMapService: STATE_ON
08-05 11:27:42.894  1036  1118 D BluetoothManagerService: Message: 30
08-05 11:27:42.894  7227  7227 D LGBluetoothAPIServer: [BTUI] onCreate()
08-05 11:27:42.894  7227  7227 D LGBluetoothAPIServer: [BTUI] onBind()
08-05 11:27:42.895  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-05 11:27:42.895  1939  2117 D LGBluetoothAPIService: Message: 100
08-05 11:27:42.895  1939  2117 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-05 11:27:42.896  7110  7110 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-05 11:27:42.898  1036  1118 D BluetoothManagerService: Message: 30
08-05 11:27:42.903  7110  7110 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-05 11:27:42.904  7110  7110 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 11:27:42.908  7110  7110 D BluetoothA2dp: Proxy object connected
08-05 11:27:42.909  7110  7110 D A2dpProfile: Bluetooth service connected
08-05 11:27:42.910  7110  7110 D BluetoothHeadset: Proxy object connected
08-05 11:27:42.911  7110  7110 D HeadsetProfile: Bluetooth service connected
08-05 11:27:42.911  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:42.911  7227  7227 V BluetoothPbapService: Pbap Service onCreate
08-05 11:27:42.911  7227  7227 V BluetoothPbapService: Starting PBAP service
08-05 11:27:42.912  7227  7227 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-05 11:27:42.912  7227  7227 V BluetoothMapService: Handler(): got msg=1
08-05 11:27:42.913  7227  7227 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-05 11:27:42.913  7227  7227 V BluetoothPbapService: Pbap Service onBind
08-05 11:27:42.914  7227  7227 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-05 11:27:42.914  7227  7227 V BluetoothPbapService: state: 12
,08-05 11:27:42.914  7227  7227 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 11:27:42.915  7227  7227 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:42.915  7227  7227 V BluetoothPbapReceiver: ***********state = 12
08-05 11:27:42.915  7227  7836 D BluetoothMapMasInstance: MAS initSocket()
08-05 11:27:42.915  7227  7836 D BluetoothMapMasInstance:   masId = 00
08-05 11:27:42.915  7227  7836 D BluetoothMapMasInstance:   msgTypes = 0e
08-05 11:27:42.915  7227  7836 D BluetoothMapMasInstance:   masName = SMS/MMS
08-05 11:27:42.915  7227  7836 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-05 11:27:42.916  7227  7227 V BluetoothPbapService: Handler(): got msg=1
08-05 11:27:42.916  7227  7227 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-05 11:27:42.918  2079  2079 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 11:27:42.918  2079  2079 D c       : Getting all permits...
08-05 11:27:42.918  2079  2079 D a       : Opening database...
08-05 11:27:42.919  1036  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:42.919  7110  7110 D DockEventReceiver: finishStartingService: stopping service
08-05 11:27:42.920  7110  7110 D BluetoothPbap: Proxy object connected
08-05 11:27:42.920  7227  7836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:27:42.921  7110  7110 D PbapServerProfile: Bluetooth service connected
08-05 11:27:42.921  7227  7838 V BluetoothPbapService: Pbap Service initSocket
08-05 11:27:42.922  2079  2079 D a       : Opening database auth.proximity.permit_store...
08-05 11:27:42.923  1036  2049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:42.924  7227  7838 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:27:42.924  2079  2079 D a       : Closing database...
08-05 11:27:42.925  7227  7838 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-05 11:27:42.925  7227  7838 V BluetoothPbapService: Succeed to create listening socket 
08-05 11:27:42.925  7227  7838 V BluetoothPbapService: Accepting socket connection...
08-05 11:27:42.925  7227  7836 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-05 11:27:42.925  7227  7836 V BluetoothMapMasInstance: Succeed to create listening socket 
08-05 11:27:42.925  7227  7836 D BluetoothMapMasInstance: Accepting socket connection...
08-05 11:27:42.928  7227  7712 D BluetoothAdapterProperties: Scan Mode:21
08-05 11:27:42.929  7227  7712 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-05 11:27:42.932  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:27:42.933  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:42.940  7110  7110 D BluetoothPermissionRequest: onReceive
08-05 11:27:42.942  7110  7110 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-05 11:27:42.943  7110  7110 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 11:27:42.947  7227  7227 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-05 11:27:42.948  7227  7227 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-05 11:27:42.954  7227  7227 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-05 11:27:42.980  7227  7227 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-05 11:27:42.981  7227  7227 V BtOppService: onCreate
08-05 11:27:42.985  7227  7227 V BluetoothOppNotification: send message
08-05 11:27:42.989  7227  7227 V BtOppService: Starting RfcommListener
08-05 11:27:42.993  7227  7227 D BluetoothOppPreference: Dumping Names:  
08-05 11:27:42.993  7227  7227 D BluetoothOppPreference: {}
08-05 11:27:42.993  7227  7227 D BluetoothOppPreference: Dumping Channels:  
,08-05 11:27:42.993  7227  7227 D BluetoothOppPreference: {}
08-05 11:27:42.994  7227  7227 V BtOppService: onStartCommand
08-05 11:27:42.997  7227  7841 V BtOppService: Deleted complete outbound shares, number =  0
08-05 11:27:42.997  7227  7844 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 11:27:43.000  7227  7227 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:43.000  7227  7841 V BtOppService: Deleted complete inbound failed shares, number = 0
08-05 11:27:43.000  7227  7227 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 11:27:43.005  7227  7227 V BluetoothOppNotification: new notify threadi!
,08-05 11:27:43.005  7227  7227 V BluetoothOppNotification: send delay message
08-05 11:27:43.006  7227  7227 V BtOppService: start RfcommListener
08-05 11:27:43.006  7227  7844 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 11:27:43.005  7227  7841 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-05 11:27:43.009  7227  7841 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31ec1b25 on behalf of 
08-05 11:27:43.010  7227  7227 V BtOppService: RfcommListener started
08-05 11:27:43.010  7227  7844 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@156b04fa on behalf of 
08-05 11:27:43.010  7227  7845 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 11:27:43.010  7227  7227 V BtOppService: ContentObserver received notification
08-05 11:27:43.010  7227  7227 V BtOppService: ContentObserver received notification
08-05 11:27:43.017  7227  7846 V BtOppRfcommListener: Starting RFCOMM listener....
,08-05 11:27:43.017  1036  1643 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:43.019  7227  7846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:27:43.019  7227  7846 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
,08-05 11:27:43.020  7227  7846 V BtOppRfcommListener: Started RFCOMM listener....
08-05 11:27:43.020  7227  7846 I BtOppRfcommListener: Accept thread started.
08-05 11:27:43.020  7227  7846 V BtOppRfcommListener: Accepting connection...
08-05 11:27:43.022  7227  7844 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 11:27:43.022  7227  7844 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 11:27:43.022  7227  7845 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d717aab on behalf of 
08-05 11:27:43.023  7227  7844 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17f38508 on behalf of 
08-05 11:27:43.024  7227  7845 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 11:27:43.024  7227  7844 V BluetoothOppNotification: update too frequent, put in queue
08-05 11:27:43.024  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
,08-05 11:27:43.025  7227  7227 V BluetoothFtpService: Ftp Service onCreate
08-05 11:27:43.025  7227  7227 I BluetoothFtpService: Ftp Service onCreate
08-05 11:27:43.025  7227  7227 V BluetoothFtpService: Ftp Service onStartCommand
08-05 11:27:43.025  7227  7227 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:43.025  7227  7844 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 11:27:43.025  7227  7227 V BluetoothFtpService: Starting Listening on sockets
,08-05 11:27:43.026  7227  7227 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:27:43.026  7227  7227 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 11:27:43.026  7227  7227 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 11:27:43.026  7227  7227 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:43.028  7227  7845 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 11:27:43.028  7227  7227 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-05 11:27:43.028  7227  7227 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 11:27:43.030  7227  7845 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23d476c6 on behalf of 
08-05 11:27:43.031  7227  7845 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 11:27:43.031  7227  7227 V BluetoothFtpService: Handler(): got msg=1
,08-05 11:27:43.033  7227  7227 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-05 11:27:43.033  7227  7227 V BluetoothFtpService: Ftp Service initSocket
08-05 11:27:43.036  7227  7845 V BluetoothOppNotification: outbound notification was removed.
08-05 11:27:43.036  7227  7845 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 11:27:43.037  7227  7845 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20cb1687 on behalf of 
08-05 11:27:43.038  7227  7845 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 11:27:43.041  7227  7845 V BluetoothOppNotification: inbound notification was removed.
08-05 11:27:43.041  7227  7845 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 11:27:43.043  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 11:27:43.043  7227  7845 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@abfe9b4 on behalf of 
08-05 11:27:43.043  7227  7227 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:27:43.044  7227  7227 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=80
08-05 11:27:43.045  7227  7227 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-05 11:27:43.048  7227  7848 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-05 11:27:43.053  7470  7501 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-05 11:27:43.064  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
,08-05 11:27:43.065  7227  7227 V BluetoothSapService: Sap Service onCreate
08-05 11:27:43.067  7227  7227 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-05 11:27:43.067  7227  7227 V BluetoothSapService: state: 12
08-05 11:27:43.067  7227  7227 V BluetoothSapService: Starting SAP server process
08-05 11:27:43.069  7227  7227 V BluetoothSapService: SAP Service startRfcommListenerThread
08-05 11:27:43.063  7850  7850 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:43.063  7850  7850 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:43.071  7227  7851 V BluetoothSapService: Sap Service initRfcommSocket
08-05 11:27:43.071  1036  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:43.072  7227  7851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:27:43.073  7227  7851 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-05 11:27:43.073  7227  7851 V BluetoothSapService: Succeed to create listening socket 
08-05 11:27:43.074  7227  7851 V BluetoothSapService: Accepting socket connection...
08-05 11:27:43.083  7850  7850 V BT_SAP  : Event pipe created
08-05 11:27:43.083  7850  7850 V BT_SAP  : create_server_socket qcom.sap.server
08-05 11:27:43.083  7850  7850 V BT_SAP  : created socket fd 6
,08-05 11:27:43.603  1036  1534 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 11:27:43.604  1036  1534 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 11:27:43.642  1036  1535 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-05 11:27:43.643  1036  1535 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-05 11:27:43.761  1036  1695 I ActivityManager: Killing 7632:com.lge.bnr/1000 (adj 15): empty #17
,08-05 11:27:43.793  1036  1938 W libprocessgroup: failed to open /acct/uid_1000/pid_7632/cgroup.procs: No such file or directory
,08-05 11:27:44.007  7227  7227 V BluetoothOppNotification: new notify threadi!
,08-05 11:27:44.008  7227  7227 V BluetoothOppNotification: send delay message
,08-05 11:27:44.020  7227  7861 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-05 11:27:44.024  7227  7861 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@144bed20 on behalf of 
,08-05 11:27:44.033  7227  7861 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 11:27:44.037  7227  7861 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 11:27:44.040  7227  7861 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d53e6d9 on behalf of 
08-05 11:27:44.043  7227  7861 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-05 11:27:44.046  7227  7861 V BluetoothOppNotification: outbound notification was removed.
08-05 11:27:44.046  7227  7861 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 11:27:44.048  7227  7861 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21e5989e on behalf of 
08-05 11:27:44.048  7227  7861 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 11:27:44.050  7227  7861 V BluetoothOppNotification: inbound notification was removed.
08-05 11:27:44.050  7227  7861 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 11:27:44.051  7227  7861 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b764f7f on behalf of 
08-05 11:27:44.261  1036  1994 I ActivityManager: Killing 6875:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-05 11:27:44.286  7165  7165 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-05 11:27:44.286  7165  7165 W System.err: android.os.DeadObjectException
08-05 11:27:44.286  7165  7165 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 11:27:44.286  7165  7165 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 11:27:44.286  7165  7165 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-05 11:27:44.286  7165  7165 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-05 11:27:44.286  7165  7165 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 11:27:44.287  7165  7165 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 11:27:44.287  7165  7165 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 11:27:44.287  7165  7165 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,08-05 11:27:44.290  7165  7165 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 11:27:44.290  7165  7165 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 11:27:44.290  7165  7165 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:27:44.290  7165  7165 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 11:27:44.291  7165  7165 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 11:27:44.291  7165  7165 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 11:27:44.291  7165  7165 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-05 11:27:44.291  7165  7165 W System.err: android.os.DeadObjectException
08-05 11:27:44.292  7165  7165 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 11:27:44.292  7165  7165 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 11:27:44.292  7165  7165 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-05 11:27:44.292  7165  7165 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-05 11:27:44.292  7165  7165 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 11:27:44.292  7165  7165 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 11:27:44.292  7165  7165 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 11:27:44.292  7165  7165 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 11:27:44.292  7165  7165 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 11:27:44.292  7165  7165 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 11:27:44.292  7165  7165 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:27:44.292  7165  7165 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 11:27:44.292  7165  7165 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 11:27:44.292  7165  7165 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 11:27:44.292  7165  7165 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-05 11:27:44.293  7165  7165 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-05 11:27:44.321  1036  1695 W libprocessgroup: failed to open /acct/uid_1000/pid_6875/cgroup.procs: No such file or directory
08-05 11:27:44.321  1036  1695 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-05 11:27:44.331  7165  7165 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-05 11:27:44.331  7165  7165 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 11:27:44.373  1036  1643 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7862 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 11:27:44.433  7165  7165 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-05 11:27:44.460  7862  7862 D UEI.SmartControl: Quickset Services start...
08-05 11:27:44.462  7862  7862 I UEI.SmartControl: Manufacture = LGE
08-05 11:27:44.463  7862  7862 D UEI.SmartControl: Id = LGNevo
08-05 11:27:44.464  7862  7862 D UEI.SmartControl: File observer start...
08-05 11:27:44.464  7862  7862 E UEI.SmartControl: IR Port is disabled: false
08-05 11:27:44.465  7862  7862 D UEI.SmartControl: Starting file observer...
08-05 11:27:44.465  7862  7862 D UEI.SmartControl: Extracting JNI libs...
08-05 11:27:44.465  7862  7862 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-05 11:27:44.578  7862  7862 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-05 11:27:44.578  7862  7862 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-05 11:27:44.578  7862  7862 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-05 11:27:44.611  1036  1643 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 11:27:44.611  1036  1643 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@190c80b5 mBinding = false
08-05 11:27:44.621  7862  7862 I UEI.SmartControl: --- Selecting new region: 6
08-05 11:27:44.624  7862  7862 I UEI.SmartControl: Model = LG-D855
08-05 11:27:44.626  7862  7862 D UEI.SmartControl: QS Service created
,08-05 11:27:44.634  1036  1118 D BluetoothManagerService: Message: 2
08-05 11:27:44.634  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 11:27:44.635  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 11:27:44.636  1036  1118 D BluetoothManagerService: Sending off request.
08-05 11:27:44.636  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-05 11:27:44.637  7227  7245 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-05 11:27:44.637  7227  7708 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-05 11:27:44.637  7227  7708 D BluetoothAdapterProperties: Setting state to 13
08-05 11:27:44.637  7227  7708 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 11:27:44.638  7227  7708 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 11:27:44.638  7227  7708 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-05 11:27:44.639  1036  1118 D BluetoothManagerService: Message: 60
08-05 11:27:44.639  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-05 11:27:44.639  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-05 11:27:44.643  7227  7712 D BluetoothAdapterProperties: Scan Mode:20
08-05 11:27:44.643  7227  7708 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 11:27:44.644  7227  7708 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 11:27:44.644  7227  7838 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:27:44.645  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:44.645  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-05 11:27:44.646  7227  7776 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-05 11:27:44.647  7227  7846 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:27:44.648  7227  7848 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:27:44.649  7227  7851 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:27:44.649  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 11:27:44.649  7227  7836 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-05 11:27:44.649  7227  7836 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:27:44.649  7227  7836 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-05 11:27:44.649  7227  7836 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-05 11:27:44.649  7227  7836 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-05 11:27:44.649  7227  7836 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-05 11:27:44.649  7227  7836 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-05 11:27:44.649  7227  7836 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-05 11:27:44.651  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:27:44.651  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:27:44.651  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:27:44.651  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:27:44.651  7227  7776 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:27:44.651  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:27:44.651  7227  7776 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:27:44.651  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:27:44.651  7227  7776 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:27:44.651  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-05 11:27:44.651  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-05 11:27:44.651  7227  7776 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 11:27:44.654  7110  7110 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-05 11:27:44.657  7862  7862 I UEI.SmartControl: Service initServices...
08-05 11:27:44.659  7110  7110 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 11:27:44.663  7862  7862 D UEI.SmartControl: QS start get config
08-05 11:27:44.663  7227  7227 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:44.663  7227  7227 D BluetoothMapService: STATE_TURNING_OFF
08-05 11:27:44.663  7227  7227 V BluetoothMapService: Handler(): got msg=4
08-05 11:27:44.663  7227  7227 D BluetoothMapService: MAP Service closeService in
08-05 11:27:44.663  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:44.663  7227  7227 D BluetoothMapMasInstance: MAP Service shutdown
08-05 11:27:44.663  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:44.663  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:44.663  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:44.663  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:27:44.663  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:27:44.663  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:44.663  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:44.663  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:27:44.664  7227  7227 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 11:27:44.664  7227  7227 V BluetoothMapService: MAP Service closeService out
08-05 11:27:44.664  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:44.664  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:44.665  7227  7227 V BtOppService: Receiver DISABLED_ACTION 
08-05 11:27:44.665  7227  7227 I BtOppRfcommListener: stopping Accept Thread
08-05 11:27:44.666  7227  7227 V BtOppRfcommListener: close mBtServerSocket
08-05 11:27:44.666  7227  7227 V BtOppRfcommListener: waiting for thread to terminate
08-05 11:27:44.666  7227  7846 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-05 11:27:44.666  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:44.666  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:44.666  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:44.666  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:44.666  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:27:44.666  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:27:44.666  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:44.666  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:44.6,66  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:27:44.666  7227  7227 V BtOppRfcommListener: done waiting for thread to terminate
08-05 11:27:44.667  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:27:44.667  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:44.677  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:44.679  7227  7227 V BtOppService: onDestroy
,08-05 11:27:44.682  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:44.682  7227  7227 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-05 11:27:44.683  7110  7110 D DockEventReceiver: finishStartingService: stopping service
08-05 11:27:44.686  7227  7227 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 11:27:44.686  7227  7227 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-05 11:27:44.686  7227  7227 V BluetoothPbapReceiver: ***********state = 13
08-05 11:27:44.687  7227  7227 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-05 11:27:44.691  7227  7227 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:44.691  7227  7227 V BluetoothPbapService: state: 13
08-05 11:27:44.691  7227  7227 V BluetoothPbapService: Pbap Service closeService in
08-05 11:27:44.692  7227  7227 V BluetoothPbapService: successfully stopped pbap service
08-05 11:27:44.692  2079  2079 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 11:27:44.692  7227  7227 V BluetoothPbapService: Pbap Service closeService out
08-05 11:27:44.692  7227  7227 V BluetoothPbapService: Pbap Service onDestroy
08-05 11:27:44.692  7227  7227 V BluetoothPbapService: Pbap Service closeService in
08-05 11:27:44.693  7227  7227 V BluetoothPbapService: Pbap Service closeService out
08-05 11:27:44.693  7227  7227 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-05 11:27:44.693  7110  7110 D BluetoothPbap: Proxy object disconnected
08-05 11:27:44.693  7110  7110 D PbapServerProfile: Bluetooth service disconnected
,08-05 11:27:44.702  7110  7110 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-05 11:27:44.707  7110  7110 D BluetoothPermissionRequest: onReceive
08-05 11:27:44.707  7110  7110 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-05 11:27:44.711  7110  7110 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 11:27:44.714  7227  7227 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-05 11:27:44.714  7227  7227 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-05 11:27:44.714  7227  7227 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-05 11:27:44.719  7227  7227 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:44.719  7227  7227 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 11:27:44.720  7227  7227 V BluetoothFtpService: Ftp Service onStartCommand
08-05 11:27:44.720  7227  7227 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:44.720  7227  7227 V BluetoothFtpService: Ftp Service closeService
08-05 11:27:44.720  7227  7227 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-05 11:27:44.723  7227  7227 V BluetoothFtpService: successfully stopped ftp service
08-05 11:27:44.723  7227  7227 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:27:44.723  7227  7227 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 11:27:44.723  7227  7227 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 11:27:44.724  7227  7227 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:44.724  7227  7227 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-05 11:27:44.724  7227  7227 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 11:27:44.724  7862  7862 D UEI.SmartControl: Loading JNI Libs...
08-05 11:27:44.724  7227  7227 V BluetoothFtpService: Ftp Service onDestroy
08-05 11:27:44.724  7227  7227 V BluetoothFtpService: Ftp Service closeService
08-05 11:27:44.729  7227  7227 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:44.729  7227  7227 V BluetoothSapService: state: 13
08-05 11:27:44.729  7227  7227 V BluetoothSapService: Stopping SAP server process
,08-05 11:27:44.730  7227  7227 V BluetoothSapService: Sap Service closeSapService in
08-05 11:27:44.730  7227  7227 V BluetoothSapService: Close listen Socket : 
,08-05 11:27:44.730  7227  7227 V BluetoothSapService: Close rfcomm Socket : 
08-05 11:27:44.730  7227  7227 V BluetoothSapService: Close sapd  Socket : 
08-05 11:27:44.733  7227  7227 V BluetoothSapService: Sap Service closeSapService out
08-05 11:27:44.733  7227  7227 V BluetoothSapService: Sap Service onDestroy
08-05 11:27:44.733  7227  7227 V BluetoothSapService: Sap Service closeSapService in
08-05 11:27:44.733  7227  7227 V BluetoothSapService: Close listen Socket : 
08-05 11:27:44.733  7227  7227 V BluetoothSapService: Close rfcomm Socket : 
08-05 11:27:44.733  7227  7227 V BluetoothSapService: Close sapd  Socket : 
08-05 11:27:44.734  7227  7227 V BluetoothSapService: Sap Service closeSapService out
08-05 11:27:44.970  7862  7862 I UEI.SmartControl: Supports setup maps: true
08-05 11:27:44.973  7862  7862 D UEI.SmartControl: QS start statue = true Error code = 0
08-05 11:27:44.973  7862  7862 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 11:27:44.973  7862  7862 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 11:27:44.973  7862  7862 I UEI.SmartControl: ### init IR Blaster...
,08-05 11:27:44.979  7862  7862 D serial_port: Configuring serial port
,08-05 11:27:44.987  7862  7862 E UEI.SmartControl: UEIBLaster setting for 616
08-05 11:27:44.987  7862  7862 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 11:27:44.989  7862  7862 I UEI.SmartControl: configuring settings for MAXQ616
08-05 11:27:44.989  7862  7862 I UEI.SmartControl: Get version...
,08-05 11:27:45.007  7862  7895 D UEI.SmartControl: serial port data available: 21
,08-05 11:27:45.040  7862  7862 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-05 11:27:45.040  7862  7862 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 11:27:45.041  7862  7862 I UEI.SmartControl: QS saving settings...
08-05 11:27:45.043  7862  7862 D UEI.SmartControl: IR Blaster version: 25672567
,08-05 11:27:45.063  7862  7895 D UEI.SmartControl: serial port data available: 4
,08-05 11:27:45.096  7862  7901 I UEI.SmartControl: Device manager: loading config....
,08-05 11:27:45.114  7862  7901 D UEI.SmartControl: ----------- loading internal config...
,08-05 11:27:45.120  7862  7862 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-05 11:27:45.125  7862  7862 E UEI.SmartControl: Services init done
08-05 11:27:45.125  7862  7862 D UEI.SmartControl: QS Service init finished
08-05 11:27:45.126  7862  7862 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 11:27:45.126  7862  7862 D UEI.SmartControl: QS Service version code: 201091
08-05 11:27:45.127  7862  7862 D UEI.SmartControl: Service requested: Control
08-05 11:27:45.130  7862  7901 E UEI.SmartControl: Loading SETTINGS...
,08-05 11:27:45.135  7862  7862 D UEI.SmartControl: Request IControl service: devices are loaded...
08-05 11:27:45.138  1036  1956 I ActivityManager: Killing 7165:com.lge.qremote/u0a112 (adj 15): empty #17
08-05 11:27:45.146  7862  7901 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-05 11:27:45.156  7862  7900 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-05 11:27:45.156  7862  7900 D UEI.SmartControl: -----service ready thread exits
08-05 11:27:45.202  1036  2031 W libprocessgroup: failed to open /acct/uid_10112/pid_7165/cgroup.procs: No such file or directory
,08-05 11:27:45.216  7862  7862 D UEI.SmartControl: Internal service binding...
,08-05 11:27:45.558  7227  7712 D bt_hci_bdroid: cleanup
,08-05 11:27:45.567  7227  7806 I bt_userial_mct: exiting userial_read_thread
08-05 11:27:45.568  7227  7806 D bt_userial_mct: Leaving userial_evt_read_thread()
08-05 11:27:45.569  7227  7778 I bt_lpm  : LPM is already off!!!
08-05 11:27:45.570  7227  7776 W bt-btif : ag scb idx 1 not allocated
08-05 11:27:45.570  7227  7776 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 11:27:45.570  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:27:45.570  7227  7776 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:27:45.570  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:27:45.570  7227  7776 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:27:45.570  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:27:45.570  7227  7776 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:27:45.570  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:27:45.570  7227  7776 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:27:45.570  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:27:45.571  7227  7776 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:27:45.571  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:27:45.571  7227  7776 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:27:45.571  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:27:45.571  7227  7776 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:27:45.571  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:27:45.571  7227  7776 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:27:45.571  7227  7776 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:27:45.571  7227  7776 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:27:45.571  7227  7776 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 11:27:45.574  7227  7712 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-05 11:27:45.578  7227  7778 I bt_vendor: hw_epilog_process
,08-05 11:27:45.583  7227  7712 D bt_hci_bdroid: cleanup Finalizing cleanup
08-05 11:27:45.583  7227  7712 D bt_userial_mct: userial_close
08-05 11:27:45.583  7227  7712 E bt_userial_mct: pthread_join() FAILED result:3
08-05 11:27:45.583  7227  7712 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-05 11:27:45.589  7227  7712 D bt_hci_bdroid: set_power 0
08-05 11:27:45.591  7227  7712 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-05 11:27:45.592  7227  7712 I bt_vendor: bluetooth satus is on
08-05 11:27:45.592  7227  7712 I bt_vendor: bt-vendor : resetting BT status
08-05 11:27:45.592  7227  7712 I bt_vendor: Starting hciattach daemon
08-05 11:27:45.592  7227  7712 I bt_vendor: try to set false
,08-05 11:27:45.595  7227  7712 I bt_vendor: Starting hciattach daemon
08-05 11:27:45.595  7227  7712 I bt_vendor: try to set false
08-05 11:27:45.596  7227  7712 I bt_vendor: cleanup
08-05 11:27:45.597  7227  7776 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-05 11:27:45.597  7227  7712 I GKI_LINUX: GKI_exit_task 0 done
08-05 11:27:45.597  7227  7712 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-05 11:27:45.599  7227  7708 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 11:27:45.606  7227  7227 D HeadsetService: Received stop request...Stopping profile...
,08-05 11:27:45.612  7227  7227 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 11:27:45.612  7227  7227 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 11:27:45.612  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:45.613  7227  7708 D BluetoothAdapterState: Stopping profile services that were post enabled
08-05 11:27:45.615  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-05 11:27:45.615  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-05 11:27:45.615  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-05 11:27:45.616  7227  7742 D HeadsetStateMachine: Exit Disconnected: -1
08-05 11:27:45.617  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-05 11:27:45.617  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-05 11:27:45.619  7227  7227 D A2dpService: Received stop request...Stopping profile...
,08-05 11:27:45.622  7227  7768 D A2dpStateMachine: Exit Disconnected: -1
08-05 11:27:45.623  7227  7227 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-05 11:27:45.625  7227  7227 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-05 11:27:45.625  7227  7227 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 11:27:45.625  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:45.627  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-05 11:27:45.627  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-05 11:27:45.628  7227  7227 D HidService: Received stop request...Stopping profile...
08-05 11:27:45.628  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:45.630  7227  7227 D HealthService: Received stop request...Stopping profile...
08-05 11:27:45.630  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:45.632  7227  7227 D PanService: Received stop request...Stopping profile...
,08-05 11:27:45.636  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:45.637  7227  7227 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 11:27:45.638  7227  7227 D BtGatt.GattService: Received stop request...Stopping profile...
08-05 11:27:45.639  7227  7227 D BtGatt.GattService: stop()
08-05 11:27:45.639  7227  7227 D BtGatt.AdvertiseManager: advertise clients cleared
08-05 11:27:45.640  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:45.642  7227  7227 D BluetoothMapService: Received stop request...Stopping profile...
08-05 11:27:45.642  7227  7227 D BluetoothMapService: stop()
08-05 11:27:45.642  7227  7227 D BluetoothMapEmailAppObserver: deinitObservers()
08-05 11:27:45.643  7227  7227 D BluetoothMapEmailAppObserver: removeReceiver()
08-05 11:27:45.643  7227  7227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@210ee060
08-05 11:27:45.644  7227  7227 D HeadsetStateMachine: Unbinding service...
,08-05 11:27:45.649  7227  7227 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 11:27:45.649  7227  7227 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 11:27:45.649  7227  7227 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 11:27:45.649  7227  7227 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 11:27:45.649  7227  7227 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 11:27:45.649  7227  7227 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 11:27:45.649  7227  7227 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 11:27:45.650  7227  7227 I BluetoothA2dpServiceJni: cleanupNative
08-05 11:27:45.650  7227  7769 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 11:27:45.651  7227  7227 I GKI_LINUX: GKI_exit_task 2 done
08-05 11:27:45.651  7227  7227 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-05 11:27:45.651  7227  7227 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 11:27:45.651  7227  7227 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 11:27:45.651  7227  7227 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 11:27:45.652  7227  7227 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 11:27:45.652  7227  7227 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 11:27:45.652  7227  7227 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 11:27:45.652  7227  7227 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 11:27:45.657  7227  7227 V BluetoothMapService: Handler(): got msg=4
08-05 11:27:45.658  7227  7227 D BluetoothMapService: MAP Service closeService in
08-05 11:27:45.658  7227  7227 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 11:27:45.658  7227  7227 V BluetoothMapService: MAP Service closeService out
,08-05 11:27:45.663  7227  7708 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-05 11:27:45.663  7227  7708 D BluetoothAdapterProperties: Setting state to 10
08-05 11:27:45.663  7227  7708 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-05 11:27:45.664  7227  7227 D BluetoothMapService: cleanup()
08-05 11:27:45.664  7227  7227 D BluetoothMapService: MAP Service closeService in
08-05 11:27:45.664  7227  7227 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 11:27:45.664  7227  7227 V BluetoothMapService: MAP Service closeService out
08-05 11:27:45.665  1036  1118 D BluetoothManagerService: Message: 60
08-05 11:27:45.665  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-05 11:27:45.665  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-05 11:27:45.665  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:27:45.665  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 11:27:45.666  7227  7708 I BluetoothAdapterState: Entering OffState
08-05 11:27:45.666  7110  7128 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:27:45.667  7110  7128 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 11:27:45.667  7110  7128 D BluetoothPan: onBluetoothStateChange on: false
08-05 11:27:45.668  7110  7128 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-05 11:27:45.669  7110  7128 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 11:27:45.669  7110  7128 D BluetoothMap: onBluetoothStateChange: up=false
08-05 11:27:45.670  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:27:45.671  1850  2477 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:27:45.671  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-05 11:27:45.675  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-05 11:27:45.675  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-05 11:27:45.678  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-05 11:27:45.678  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-05 11:27:45.678  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@190c80b5 mBinding = false
08-05 11:27:45.679  1036  1118 D BluetoothManagerService: Sending unbind request.
08-05 11:27:45.683  7227  7712 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-05 11:27:45.685  7227  7227 I GKI_LINUX: GKI_exit_task 1 done
08-05 11:27:45.685  7227  7227 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-05 11:27:45.686  7227  7227 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-05 11:27:45.686  7227  7227 I art     : --- WEIRD: removing null entry 248
08-05 11:27:45.686  7227  7227 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-05 11:27:45.686  7227  7227 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-05 11:27:45.688  7227  7227 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-05 11:27:45.689  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-05 11:27:45.691  7227  7227 I art     : System.exit called, status: 0
08-05 11:27:45.691  7227  7227 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-05 11:27:45.717   309  1384 V AudioFlinger: 7227 died, releasing its sessions
08-05 11:27:45.717   309  1384 V AudioFlinger:  pid 1850 @ 0
08-05 11:27:45.717   309  1384 V AudioFlinger:  pid 3391 @ 1
08-05 11:27:45.717   309  1384 V AudioFlinger:  pid 3391 @ 2
08-05 11:27:45.717  7110  7110 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-05 11:27:45.718  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-05 11:27:45.718  1939  2117 D LGBluetoothAPIService: Message: 101
08-05 11:27:45.719  1939  2117 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-05 11:27:45.719  1939  2117 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-05 11:27:45.719  1939  2117 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
,08-05 11:27:45.829  1036  1957 I ActivityManager: Process com.android.bluetooth (pid 7227) has died
08-05 11:27:45.830  1036  1957 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
,08-05 11:27:45.830  1036  1957 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,08-05 11:27:45.839  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-05 11:27:45.840  1939  2117 D LGBluetoothAPIService: Message: 2
08-05 11:27:45.840  1939  2117 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-05 11:27:45.842  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 11:27:45.843  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:27:45.844  7110  7110 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-05 11:27:45.844  7110  7110 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-05 11:27:45.845  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:45.853  1602  1602 D BluetoothAdapter: 117580635: getState() :  mService = null. Returning STATE_OFF
08-05 11:27:45.854  1602  1602 D BluetoothAdapter: 117580635: getState() :  mService = null. Returning STATE_OFF
08-05 11:27:45.854  7110  7110 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 11:27:45.909  1036  1956 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7926 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-05 11:27:45.913  7110  7110 D DockEventReceiver: finishStartingService: stopping service
,08-05 11:27:45.992  7926  7926 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-05 11:27:45.993  7926  7926 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 11:27:45.994  7926  7926 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-05 11:27:45.996  7926  7926 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 11:27:46.017  7926  7926 D BluetoothAdapterApp: Loading JNI Library
,08-05 11:27:46.054  7926  7926 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1dd05048 Instance Count = 1
,08-05 11:27:46.060  7926  7926 D BluetoothAdapterApp: onCreate
08-05 11:27:46.085  7926  7926 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-05 11:27:46.085  7926  7926 D ProfileConfigQcom: Adding HeadsetService
08-05 11:27:46.086  7926  7926 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-05 11:27:46.086  7926  7926 D ProfileConfigQcom: Adding A2dpService
,08-05 11:27:46.086  7926  7926 D ProfileConfigQcom: [BTUI] HidService is supported
08-05 11:27:46.086  7926  7926 D ProfileConfigQcom: Adding HidService
08-05 11:27:46.087  7926  7926 D ProfileConfigQcom: [BTUI] HealthService is supported
08-05 11:27:46.087  7926  7926 D ProfileConfigQcom: Adding HealthService
08-05 11:27:46.087  7926  7926 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-05 11:27:46.088  7926  7926 D ProfileConfigQcom: [BTUI] PanService is supported
,08-05 11:27:46.088  7926  7926 D ProfileConfigQcom: Adding PanService
,08-05 11:27:46.088  7926  7926 D ProfileConfigQcom: [BTUI] GattService is supported
08-05 11:27:46.089  7926  7926 D ProfileConfigQcom: Adding GattService
08-05 11:27:46.089  7926  7926 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-05 11:27:46.089  7926  7926 D ProfileConfigQcom: Adding BluetoothMapService
08-05 11:27:46.089  7926  7926 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-05 11:27:46.090  7926  7926 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 11:27:46.091  7926  7926 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:46.092  7926  7926 V BluetoothPbapReceiver: ***********state = 10
08-05 11:27:46.093  7926  7926 V LGMDMManagerInternal: Create singleton instance
,08-05 11:27:46.201  2079  2079 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 11:27:46.201  7926  7926 D LGBluetoothAPIServer: [BTUI] onCreate()
08-05 11:27:46.201  7926  7926 D LGBluetoothAPIServer: [BTUI] onBind()
,08-05 11:27:46.209  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-05 11:27:46.209  1939  2117 D LGBluetoothAPIService: Message: 100
,08-05 11:27:46.209  1939  2117 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-05 11:27:46.217  7110  7110 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-05 11:27:46.219  7110  7110 D BluetoothPermissionRequest: onReceive
08-05 11:27:46.222  7110  7110 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 11:27:46.222  7110  7110 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-05 11:27:46.226  7110  7110 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 11:27:46.233  7926  7926 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-05 11:27:46.238  7926  7926 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:46.241  7926  7926 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:27:46.242  7926  7926 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 11:27:46.242  7926  7926 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 11:27:46.243  7926  7926 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:46.244  7926  7926 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-05 11:27:46.247  7182  7182 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-05 11:27:47.637  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 11:27:47.637  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:27:48.039  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-05 11:27:48.057  1036  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 11:27:48.079  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-05 11:27:48.092  1036  1036 D administrator: Handling package changes for user 0
,08-05 11:27:48.168  1036  1111 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7966 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-05 11:27:48.174  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-05 11:27:48.177  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-05 11:27:48.183  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 11:27:48.223  7966  7966 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-05 11:27:48.240  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-05 11:27:48.240  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-05 11:27:48.292  7966  7966 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:27:48.292  7966  7966 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 11:27:48.293  1036  1109 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 11:27:48.297  1036  1109 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-05 11:27:48.303  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-05 11:27:48.305  2448  2448 V GmsNetworkLocationProvi: DISABLE
,08-05 11:27:48.326  1036  1109 D LocationProviderProxy: applying state to connected service
08-05 11:27:48.327  2448  2448 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-05 11:27:48.380  7966  8000 I Babel   : MmsConfig: mnc/mcc: 0/0
08-05 11:27:48.380  7966  8000 I Babel   : MmsConfig.loadMmsSettings
08-05 11:27:48.382  7966  8000 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 11:27:48.382  7966  8000 I Babel   : MmsConfig.loadFromDatabase
08-05 11:27:48.393  7966  7998 W AudioCapabilities: Unsupported mime audio/evrc
08-05 11:27:48.394  7966  7998 W AudioCapabilities: Unsupported mime audio/qcelp
,08-05 11:27:48.396  7966  7998 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-05 11:27:48.405  7966  8000 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-05 11:27:48.405  7966  8000 I Babel   : MmsConfig.loadFromResources
,08-05 11:27:48.410  7966  7998 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-05 11:27:48.410  7966  8000 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-05 11:27:48.411  7966  7998 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 11:27:48.412  7966  7998 W AudioCapabilities: Unsupported mime audio/evrc
08-05 11:27:48.412  7966  8000 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 11:27:48.418  7966  7998 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-05 11:27:48.419  7966  7998 W VideoCapabilities: Unsupported mime video/divx
08-05 11:27:48.421  7966  7998 W VideoCapabilities: Unsupported mime video/divx311
08-05 11:27:48.423  7966  7998 W VideoCapabilities: Unsupported mime video/divx4
,08-05 11:27:48.426  7966  7966 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:48.428  7966  7998 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-05 11:27:48.441  7966  7998 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-05 11:27:48.443  7966  7998 W AudioCapabilities: Unsupported mime audio/eac3
08-05 11:27:48.444  7966  7998 W AudioCapabilities: Unsupported mime audio/ac3
08-05 11:27:48.445  7966  7998 W AudioCapabilities: Unsupported mime audio/g726
,08-05 11:27:48.445  7966  7998 W AudioCapabilities: Unsupported mime audio/wma-voice
08-05 11:27:48.446  7966  7998 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-05 11:27:48.447  7966  7998 W AudioCapabilities: Unsupported mime audio/adpcm
08-05 11:27:48.448  7966  7998 W VideoCapabilities: Unsupported mime video/theora
,08-05 11:27:48.449  7966  7998 W VideoCapabilities: Unsupported mime video/mjpg
,08-05 11:27:48.541  1036  2031 I art     : Explicit concurrent mark sweep GC freed 57327(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.825ms total 101.736ms
,08-05 11:27:48.559  1815  8001 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-05 11:27:48.559  1815  8001 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-05 11:27:48.562  7299  7299 I AppUp4:CustModeStarterReceiver: onReceive
08-05 11:27:48.570  7299  7299 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@22e5aa92
08-05 11:27:48.570  7299  7299 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 11:27:48.570  7299  7299 D AppUp4:CustFacade: isPhone : true
08-05 11:27:48.570  7299  7299 D AppUp4:CustModeStarterReceiver: begin check event
08-05 11:27:48.570  7299  7299 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-05 11:27:48.575  1815  5221 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-05 11:27:48.620  1036  1993 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8006 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-05 11:27:48.628  1036  1993 I ActivityManager: Killing 7133:com.lge.sync/1000 (adj 15): empty #17
08-05 11:27:48.641  1036  1543 D WifiService: Client connection lost with reason: 4
,08-05 11:27:48.771  1036  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_7133/cgroup.procs: No such file or directory
,08-05 11:27:48.822  8006  8006 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 11:27:48.823  8006  8006 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 11:27:48.824  8006  8006 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-05 11:27:48.825  8006  8006 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-05 11:27:48.826  8006  8006 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 11:27:48.907  8006  8006 I SystemConfig: BUILD Country: EU
08-05 11:27:48.907  8006  8006 I SystemConfig: BUILD Operator: OPEN
,08-05 11:27:48.949  1036  1956 I ActivityManager: Killing 7336:com.lge.email/u0a23 (adj 15): empty #17
,08-05 11:27:49.016  1036  1956 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8028 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-05 11:27:49.020  1036  2031 W libprocessgroup: failed to open /acct/uid_10023/pid_7336/cgroup.procs: No such file or directory
08-05 11:27:49.038  8006  8026 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-05 11:27:49.038  8006  8026 I SystemConfig: existFile = false
,08-05 11:27:49.038  8006  8026 I SystemConfig: canReadFile = false
08-05 11:27:49.038  8006  8026 I SystemConfig: systemFeature RCS result false
08-05 11:27:49.038  8006  8026 D SystemConfig: refreshRcsSupport() :false
,08-05 11:27:49.077  8028  8028 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 11:27:49.077  8028  8028 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 11:27:49.078  8028  8028 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-05 11:27:49.078  8028  8028 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 11:27:49.179  8028  8028 I AppConfig: Total System Memory = 2995761152
08-05 11:27:49.189  8028  8028 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-05 11:27:49.284  1036  2030 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8047 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 11:27:49.285  1036  2030 I ActivityManager: Killing 7203:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-05 11:27:49.361  1036  1695 W libprocessgroup: failed to open /acct/uid_10026/pid_7203/cgroup.procs: No such file or directory
,08-05 11:27:49.561  8047  8047 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-05 11:27:49.695  8047  8047 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:27:49.696  8047  8047 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 11:27:49.771  8047  8047 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-05 11:27:49.792  8047  8047 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-05 11:27:49.794  8047  8047 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-05 11:27:49.808  8047  8047 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-05 11:27:49.808  8047  8047 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-05 11:27:49.825  1036  1574 I ActivityManager: Killing 6496:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-05 11:27:49.858  1036  1643 W libprocessgroup: failed to open /acct/uid_1000/pid_6496/cgroup.procs: No such file or directory
,08-05 11:27:49.866  3492  4224 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-05 11:27:49.868  3492  4224 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@16a69997 on behalf of 8047
08-05 11:27:49.871  5053  8087 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-05 11:27:49.921  1036  1957 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8088 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-05 11:27:49.970  8047  8047 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-05 11:27:50.009  8047  8047 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-05 11:27:50.041  8088  8088 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-05 11:27:50.064  8088  8088 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-05 11:27:50.064  8088  8088 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-05 11:27:50.065  8088  8088 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-05 11:27:50.065  8088  8088 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-05 11:27:50.065  8088  8088 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-05 11:27:50.065  8088  8088 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-05 11:27:50.084  1036  1957 I ActivityManager: Killing 7378:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-05 11:27:50.113  7862  7905 D UEI.SmartControl: Internal timer expired: 1
,08-05 11:27:50.114  7862  7905 D UEI.SmartControl: unbind internal service
08-05 11:27:50.174  1036  2031 W libprocessgroup: failed to open /acct/uid_10046/pid_7378/cgroup.procs: No such file or directory
,08-05 11:27:50.188  7862  7862 D UEI.SmartControl: Service.onUnbind: IControl
,08-05 11:27:50.189  7862  7862 D UEI.SmartControl: Service.onDestroy
08-05 11:27:50.190  7862  7862 D UEI.SmartControl: Lock is in USE false
08-05 11:27:50.190  7862  7862 D UEI.SmartControl: unbind internal service
08-05 11:27:50.198  7862  7862 D serial_port: close(fd = 25)
,08-05 11:27:50.203  7862  7862 I UEI.SmartControl: Serial port is closed.
08-05 11:27:50.203  7862  7862 I UEI.SmartControl: Serial port is closed.
08-05 11:27:50.204  7862  7862 D UEI.SmartControl: Blaster closed
08-05 11:27:50.204  7862  7862 D UEI.SmartControl: Shut down QS...
08-05 11:27:50.204  7862  7862 D UEI.SmartControl: Stopping QS lib
08-05 11:27:50.205  7862  7862 D UEI.SmartControl: QS lib stop result = true
08-05 11:27:50.205  7862  7862 D UEI.SmartControl: Stopped QS lib
08-05 11:27:50.206  7862  7862 D UEI.SmartControl: Stopped file observer...
08-05 11:27:50.207  7862  7862 D UEI.SmartControl: QS shutdown complete
,08-05 11:27:50.424  1036  1574 V SIM_STK : Menu title from STK is T-Mobile
,08-05 11:27:50.471  5053  8087 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 601 ms] updated apps [took 600 ms] 
,08-05 11:27:50.649  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 11:27:50.650  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d978b44 added. We now have 6 listener(s)
08-05 11:27:50.650  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 11:27:50.655  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:50.655  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@108d342d added. We now have 7 listener(s)
08-05 11:27:50.655  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:27:50.656  6981  7047 I System.out: IsBluetoothEnabled
08-05 11:27:50.657  1036  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:50.657  1036  1993 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-05 11:27:50.657  1036  1118 D BluetoothManagerService: Message: 2
08-05 11:27:50.663  6981  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:27:50.666  1036  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:50.666  1036  1938 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-05 11:27:50.683  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 11:27:50.684  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 11:27:50.684  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-05 11:27:50.684  1036  1118 D BluetoothManagerService: Message: 1
08-05 11:27:50.684  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-05 11:27:50.707  1036  1118 D BluetoothManagerService: Message: 20
08-05 11:27:50.708  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35a65d58:true
,08-05 11:27:50.712  7926  7926 D BluetoothAdapterState: make
08-05 11:27:50.716  7926  7926 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-05 11:27:50.716  7926  7926 I bluedroid-qcom: init
08-05 11:27:50.717  7926  8133 I BluetoothAdapterState: Entering OffState
08-05 11:27:50.718  7926  7926 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 11:27:50.718  7926  7926 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 11:27:50.718  7926  7926 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 11:27:50.718  7926  7926 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 11:27:50.718  7926  7926 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-05 11:27:50.720  7926  7926 I bluedroid-qcom: get_profile_interface socket
08-05 11:27:50.720  7926  7926 I bluedroid-qcom: get_profile_interface map_client
,08-05 11:27:50.724  7926  8137 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-05 11:27:50.713  8136  8136 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:50.713  8136  8136 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:50.732  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-05 11:27:50.732  1036  1118 D BluetoothManagerService: Message: 40
08-05 11:27:50.732  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-05 11:27:50.733  7926  7941 I bluedroid-qcom: config_hci_snoop_log
,08-05 11:27:50.739  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-05 11:27:50.740  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-05 11:27:50.744  8136  8136 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-05 11:27:50.744  8136  8136 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-05 11:27:50.744  8136  8136 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-05 11:27:50.748  8136  8136 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-05 11:27:50.753  7926  8133 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-05 11:27:50.754  7926  8133 D BluetoothAdapterProperties: Setting state to 11
08-05 11:27:50.754  7926  8133 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-05 11:27:50.757  8136  8136 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-05 11:27:50.757  8136  8136 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-05 11:27:50.759  7926  8137 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-05 11:27:50.761  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 11:27:50.761  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-05 11:27:50.764  7926  8137 D BluetoothAdapterProperties: Name is: G3
08-05 11:27:50.765  1036  1118 D BluetoothManagerService: Message: 60
08-05 11:27:50.765  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-05 11:27:50.765  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-05 11:27:50.769  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:50.769  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 11:27:50.772  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:50.775  7110  7110 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-05 11:27:50.783  7926  7926 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 11:27:50.783  7926  7926 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:50.783  7926  7926 V BluetoothPbapReceiver: ***********state = 11
08-05 11:27:50.786  2079  2079 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 11:27:50.805  7926  8133 I LGBluetoothServiceJni: classInitNative: succeeds
,08-05 11:27:50.814  7926  8133 D BluetoothBondStateMachine: make
08-05 11:27:50.814  7110  7110 D BluetoothPermissionRequest: onReceive
,08-05 11:27:50.816  7926  8133 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2f919
08-05 11:27:50.816  7926  8133 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-05 11:27:50.816  7926  8133 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2f919
08-05 11:27:50.816  7926  8133 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-05 11:27:50.817  7926  8133 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-05 11:27:50.818  7926  8147 I BluetoothBondStateMachine: StableState(): Entering Off State
08-05 11:27:50.820  7926  8133 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:27:50.821  7110  7110 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 11:27:50.830  7926  7926 D HeadsetService: Received start request. Starting profile...
08-05 11:27:50.831  7926  7926 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 11:27:50.831  7926  7926 D LGBluetoothHfpAdapter: Version 1.6
08-05 11:27:50.831  7926  8133 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:27:50.833  7926  7926 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 11:27:50.834  7926  7926 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 11:27:50.834  7926  7926 D HeadsetStateMachine: make
,08-05 11:27:50.838  7926  8133 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:27:50.851  7926  8133 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 11:27:50.857  7926  8133 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:27:50.863  7926  8133 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:27:50.868  7926  7926 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:27:50.868  7926  7926 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 11:27:50.868  7926  8133 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 11:27:50.873  7926  7926 D HeadsetStateMachine: max_hf_connections = 1
08-05 11:27:50.873  7926  7926 I bluedroid-qcom: get_profile_interface handsfree
08-05 11:27:50.875  7926  7926 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-05 11:27:50.876   309  1384 V AudioPolicyService: registerClient() client 0xb558a7c0, uid 1002
08-05 11:27:50.876   309   309 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-05 11:27:50.876   309   309 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 11:27:50.876   309   309 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 11:27:50.876  7926  7926 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 11:27:50.877   309  2163 V AudioFlinger: registerClient() client 0xb5581598, pid 7926
08-05 11:27:50.877   309  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:27:50.877   309  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:27:50.877  1036  1956 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:27:50.877  1036  1956 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:27:50.878   309  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:27:50.878   309  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:27:50.878  1602  2568 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:27:50.878  1602  2568 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:27:50.878  1850  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:27:50.878  1850  1865 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:27:50.878  3391  3406 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:27:50.878  3391  3406 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:27:50.878  7926  7941 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-05 11:27:50.878  7926  7941 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-05 11:27:50.878  7926  7942 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:27:50.878  1036  1052 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:27:50.878  1036  1052 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:27:50.878  7926  7942 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-05 11:27:50.878  1602  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:27:50.878  1602  1620 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:27:50.879  1850  4883 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:27:50.879  1850  4883 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:27:50.879  3391  3407 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:27:50.879  3391  3407 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:27:50.879  7926  7926 V ToneGenerator: Create Track: 0xb4928a80
08-05 11:27:50.879  7926  7926 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-05 11:27:50.879  7926  7926 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-05 11:27:50.879   309   309 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 11:27:50.879   309   309 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-05 11:27:50.879   309   309 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 11:27:50.879   309   309 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 11:27:50.879   309  1383 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 11:27:50.880   309  2164 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 11:27:50.880   309  2164 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-05 11:27:50.880   309  2164 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 11:27:50.880   309  2164 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 11:27:50.880  7926  7926 V AudioSystem: getLatency() output 2, latency 50
08-05 11:27:50.880  7926  7926 V AudioSystem: getFrameCount() output 2, frameCount 960
08-05 11:27:50.880  7926  7926 V AudioTrack: createTrack_l() output 2 afLatency 50
08-05 11:27:50.880   309  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 11:27:50.880   309  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 11:27:50.880   309  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 11:27:50.880   309  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 11:27:50.880   309  1384 V AudioFlinger: createTrack() lSessionId: 23
08-05 11:27:50.881  7926  7926 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-05 11:27:50.881   309  1384 V AudioFlinger: acquiring 23 from 7926, for 7926
08-05 11:27:50.881   309  1384 V AudioFlinger:  added new entry for 23
08-05 11:27:50.881  7926  7926 V ToneGenerator: ToneGenerator INIT OK, time: 349162
08-05 11:27:50.881  7926  7926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2f919
08-05 11:27:50.882  7926  8150 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-05 11:27:50.882  7926  8150 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 11:27:50.882  7926  8150 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 11:27:50.882  7926  8150 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is ,disconnected
08-05 11:27:50.882   309  2163 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7926
08-05 11:27:50.882   309  2163 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-05 11:27:50.882   309  2163 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-05 11:27:50.882   309  2163 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-05 11:27:50.882   309  2163 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 11:27:50.882   309  2163 V voice   : voice_set_parameters: exit with code(0)
08-05 11:27:50.883   309  2163 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-05 11:27:50.883   309  2163 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-05 11:27:50.883   309  2163 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 11:27:50.883   309  2163 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 11:27:50.883   309  2163 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 11:27:50.883   309  2163 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-05 11:27:50.883  7926  8150 V ToneGenerator: ToneGenerator destructor
08-05 11:27:50.883  7926  8150 V ToneGenerator: stopTone
08-05 11:27:50.883  7926  8150 V ToneGenerator: Delete Track: 0xb4928a80
08-05 11:27:50.884  7926  7926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2f919
08-05 11:27:50.885  7926  8150 V AudioTrack: ~AudioTrack, releasing session id from 7926 on behalf of 7926
08-05 11:27:50.885   309  2164 V AudioFlinger: releasing 23 from 7926 for 7926
08-05 11:27:50.885   309  2164 V AudioFlinger:  decremented refcount to 0
08-05 11:27:50.885   309  2164 V AudioFlinger: purging stale effects
08-05 11:27:50.885   309  2164 V AudioPolicyService: AudioCommandThread() adding release output 2
08-05 11:27:50.885   309  2164 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-05 11:27:50.886   309  1274 V AudioPolicyService: AudioCommandThread() waking up
08-05 11:27:50.886   309  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
08-05 11:27:50.886   309  1274 V AudioPolicyManager: releaseOutput() 2
08-05 11:27:50.886   309  1274 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 11:27:50.886   309  2164 V AudioFlinger: PlaybackThread::Track destructor
08-05 11:27:50.886   309  2164 V AudioFlinger: removeClient_l() pid 7926, calling pid 309
08-05 11:27:50.886  7926  7926 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:50.888  7926  7926 D A2dpService: Received start request. Starting profile...
08-05 11:27:50.889  7926  7926 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 11:27:50.889  1036  1957 W Process : Unable to open /proc/8156/status
08-05 11:27:50.890  7926  7926 V Avrcp   : make
08-05 11:27:50.890  7926  7926 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-05 11:27:50.890  7926  7926 I bluedroid-qcom: get_profile_interface avrcp
,08-05 11:27:50.902  7926  7926 V AudioManager: registerRemoteController: size of Media player list: 0
08-05 11:27:50.904  7926  7926 E AudioManager: No RCC entry present to update
,08-05 11:27:50.904  7926  7926 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-05 11:27:50.906  7926  7926 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-05 11:27:50.907  7926  7926 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
,08-05 11:27:50.907  7926  7926 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-05 11:27:50.911  7926  7926 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-05 11:27:50.912  7926  8133 V LGMDMManager: Create singleton instance
08-05 11:27:50.914  7926  8133 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-05 11:27:51.042  1036  1884 V SIM_STK : Menu title from STK is T-Mobile
08-05 11:27:51.042  1036  1884 V SIM_STK : Menu title from STK is T-Mobile
,08-05 11:27:51.115  1036  2030 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-05 11:27:51.125  7926  7926 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 11:27:51.130  7926  7926 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 11:27:51.130  7926  7926 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 11:27:51.130  7926  7926 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,08-05 11:27:51.131  7926  7926 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 11:27:51.131  7926  7926 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 11:27:51.131  7926  7926 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 11:27:51.131  7926  7926 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 11:27:51.131  7926  7926 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 11:27:51.131  7926  7926 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 11:27:51.131  7926  7926 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 11:27:51.131  7926  7926 I BluetoothA2dpServiceJni: classInitNative
08-05 11:27:51.131  7926  7926 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 11:27:51.132  7926  7926 D A2dpStateMachine: make
08-05 11:27:51.135  7926  7926 I bluedroid-qcom: get_profile_interface a2dp
08-05 11:27:51.135  7926  8162 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-05 11:27:51.137  7926  7926 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-05 11:27:51.137  7926  7926 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-05 11:27:51.138  7926  7926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2f919
08-05 11:27:51.138  7926  8161 D A2dpStateMachine: Enter Disconnected: -2
08-05 11:27:51.139  7926  7926 I BluetoothHidServiceJni: classInitNative: succeeds
08-05 11:27:51.141  7926  7926 D HidService: Received start request. Starting profile...
08-05 11:27:51.141  7926  7926 I bluedroid-qcom: get_profile_interface hidhost
08-05 11:27:51.141  7926  7926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2f919
08-05 11:27:51.141  7926  7926 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 11:27:51.142  7926  7926 D HealthService: Received start request. Starting profile...
08-05 11:27:51.146  7926  7926 I bluedroid-qcom: get_profile_interface health
08-05 11:27:51.146  7926  7926 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-05 11:27:51.146  7926  7926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2f919
08-05 11:27:51.146  7926  7926 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-05 11:27:51.147  7926  7926 D PanService: Received start request. Starting profile...
08-05 11:27:51.148  7926  7926 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-05 11:27:51.148  7926  7926 I bluedroid-qcom: get_profile_interface pan
,08-05 11:27:51.157  7926  7926 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-05 11:27:51.157  7926  7926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2f919
08-05 11:27:51.158  7926  7926 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-05 11:27:51.170  7926  7926 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 11:27:51.171  7926  7926 D BtGatt.GattService: Received start request. Starting profile...
08-05 11:27:51.171  7926  7926 D BtGatt.GattService: start()
08-05 11:27:51.171  7926  7926 I bluedroid-qcom: get_profile_interface gatt
08-05 11:27:51.171  7926  7926 D BtGatt.AdvertiseManager: advertise manager created
08-05 11:27:51.179  7926  7926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2f919
08-05 11:27:51.181  7926  7926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2f919
08-05 11:27:51.181  7926  7926 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-05 11:27:51.182  7926  7926 V BluetoothMapService: BluetoothMapBinder()
,08-05 11:27:51.183  7926  7926 D BluetoothMapService: Received start request. Starting profile...
08-05 11:27:51.183  7926  7926 D BluetoothMapService: start()
08-05 11:27:51.188  7926  7926 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-05 11:27:51.188  7926  7926 D BluetoothMapEmailAppObserver: createReceiver()
08-05 11:27:51.189  7926  7926 D BluetoothMapEmailAppObserver: initObservers()
08-05 11:27:51.189  7926  7926 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-05 11:27:51.199  7926  7926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2f919
,08-05 11:27:51.200  7926  7926 D HeadsetStateMachine: Proxy object connected
08-05 11:27:51.200  7926  7926 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-05 11:27:51.201  7926  7926 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-05 11:27:51.206  7926  7926 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 11:27:51.207  7926  7926 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:27:51.207  7926  8150 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 11:27:51.207  7926  7926 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 11:27:51.207  7926  7926 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 11:27:51.207  7926  7926 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:51.207  7926  7926 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-05 11:27:51.208  7926  8150 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 11:27:51.208  7926  8150 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-05 11:27:51.215  7926  7926 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 11:27:51.220  7926  7926 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 11:27:51.223  7926  7926 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 11:27:51.227  7926  7926 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 11:27:51.228  7926  7926 V PanService: [BTUI] SIM Extra State :ABSENT
08-05 11:27:51.231  7926  7926 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-05 11:27:51.232  7926  7926 V BluetoothMapService: Handler(): got msg=1
08-05 11:27:51.233  7926  8133 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-05 11:27:51.233  7926  8133 I bluedroid-qcom: enable
08-05 11:27:51.233  7926  8172 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-05 11:27:51.233  7926  8133 I bt_hci_bdroid: init
08-05 11:27:51.233  7926  8172 I bt-btu  : btu_task pending for preload complete event
08-05 11:27:51.235  7926  8133 I bt_vendor: bt-vendor : init
08-05 11:27:51.235  7926  8133 I bt_vendor: bt-vendor : get_bt_soc_type
08-05 11:27:51.235  7926  8133 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-05 11:27:51.235  7926  8133 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-05 11:27:51.235  7926  8133 D bt_userial_mct: userial_init
08-05 11:27:51.235  7926  8133 D bt_hci_bdroid: set_power 1
08-05 11:27:51.235  7926  8133 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-05 11:27:51.235  7926  8133 I bt_vendor: Starting hciattach daemon
08-05 11:27:51.235  7926  8133 I bt_vendor: try to set true
08-05 11:27:51.223  8175  8175 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:51.223  8175  8175 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 11:27:51.274  8177  8177 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-05 11:27:51.419  8183  8183 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-05 11:27:51.445  8184  8184 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 11:27:51.480  8186  8186 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 11:27:51.506  8187  8187 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-05 11:27:51.540  8188  8188 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 11:27:51.553  8192  8192 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-05 11:27:51.577  8194  8194 I libmdmdetect: ESOC framework not supported
08-05 11:27:51.580  8194  8194 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-05 11:27:51.590  8194  8194 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-05 11:27:51.590  8194  8194 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-05 11:27:51.590  8194  8194 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-05 11:27:51.591  8194  8194 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-05 11:27:51.591  8194  8194 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-05 11:27:51.591  8194  8194 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-05 11:27:51.591  8194  8194 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-05 11:27:51.637  8194  8195 E QC-QMI  : qmi_client [8194] 15: failed to locate client data
,08-05 11:27:51.639   468   468 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-05 11:27:51.639   468   468 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-05 11:27:51.690  8196  8196 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-05 11:27:51.706  8200  8200 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 11:27:51.739  7926  8133 I bt_vendor: bluetooth satus is on
08-05 11:27:51.739  7926  8133 D bt_hci_bdroid: preload
,08-05 11:27:51.741  7926  8174 D bt_userial_mct: userial_open(port:0)
08-05 11:27:51.741  7926  8174 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-05 11:27:51.745  7926  8174 I bt_vendor: Done intiailizing UART
08-05 11:27:51.746  7926  8174 I bt_vendor: Done intiailizing UART
08-05 11:27:51.746  7926  8174 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-05 11:27:51.746  7926  8174 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-05 11:27:51.746  7926  8172 I bt-btu  : btu_task received preload complete event
08-05 11:27:51.747  7926  8172 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-05 11:27:51.747  7926  8172 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-05 11:27:51.749  7926  8172 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-05 11:27:51.751  7926  8202 D bt_userial_mct: Entering userial_read_thread()
,08-05 11:27:51.756  7926  8172 I         : BTE_InitTraceLevels -- TRC_HCI
08-05 11:27:51.756  7926  8172 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 11:27:51.756  7926  8172 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 11:27:51.756  7926  8172 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 11:27:51.756  7926  8172 I         : BTE_InitTraceLevels -- TRC_AVRC
08-05 11:27:51.756  7926  8172 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 11:27:51.756  7926  8172 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 11:27:51.756  7926  8172 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 11:27:51.756  7926  8172 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-05 11:27:51.756  7926  8172 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 11:27:51.756  7926  8172 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 11:27:51.756  7926  8172 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 11:27:51.756  7926  8172 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 11:27:51.757  7926  8172 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 11:27:51.757  7926  8172 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 11:27:51.757  7926  8172 I         : BTE_InitTraceLevels -- TRC_BTIF
08-05 11:27:51.829  7926  8172 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-05 11:27:51.829  7926  8172 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0231061 
08-05 11:27:51.829  7926  8172 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0231061 
,08-05 11:27:51.876  7926  8137 E bt-btif : Calling BTA_HhEnable
,08-05 11:27:51.876  7926  8137 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-05 11:27:51.877  7926  8137 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 11:27:51.890  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 11:27:51.891  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 11:27:51.891  7926  8137 D BluetoothAdapterProperties: Name is: G3
08-05 11:27:51.896  7926  8137 D BluetoothAdapterProperties: Scan Mode:20
,08-05 11:27:51.899  7926  8137 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 11:27:51.900  7926  8137 D bt_hci_bdroid: postload
08-05 11:27:51.901  7926  8137 D bte_conf: Device ID record 1 : primary
08-05 11:27:51.901  7926  8137 D bte_conf:   vendorId            = 00c4
08-05 11:27:51.901  7926  8137 D bte_conf:   vendorIdSource      = 0001
08-05 11:27:51.901  7926  8137 D bte_conf:   product             = 13a1
08-05 11:27:51.901  7926  8137 D bte_conf:   version             = 1000
08-05 11:27:51.901  7926  8137 D bte_conf:   clientExecutableURL = 
08-05 11:27:51.901  7926  8137 D bte_conf:   serviceDescription  = 
08-05 11:27:51.901  7926  8137 D bte_conf:   documentationURL    = 
08-05 11:27:51.901  7926  8137 D bte_conf: bte_load_did_conf no section named DID2.
08-05 11:27:51.908  7926  8133 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-05 11:27:51.912  7926  8133 D BluetoothAdapterProperties: ScanMode =  20
08-05 11:27:51.913  7926  8133 D BluetoothAdapterProperties: State =  11
08-05 11:27:51.913  7926  8133 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-05 11:27:51.903  8204  8204 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:51.915  7926  8133 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-05 11:27:51.915  7926  8133 D BluetoothAdapterProperties: Setting state to 12
08-05 11:27:51.915  7926  8133 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 11:27:51.916  7926  8137 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 11:27:51.913  8204  8204 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:51.921  1036  1118 D BluetoothManagerService: Message: 60
08-05 11:27:51.921  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-05 11:27:51.921  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-05 11:27:51.922  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 11:27:51.928  7926  8133 I BluetoothAdapterState: Entering On State
08-05 11:27:51.938  7926  8133 D LGBluetoothServiceAdapter: [BTUI] OnState
08-05 11:27:51.938  7926  8133 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-05 11:27:51.938  7926  8133 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-05 11:27:51.941  7926  8133 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-05 11:27:51.968  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 11:27:51.978  7926  8133 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-05 11:27:51.990  1036  1036 D BluetoothHeadset: Proxy object connected
,08-05 11:27:51.993  7926  8137 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 11:27:51.993  7926  8137 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-05 11:27:51.996  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:51.996  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:51.996  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:51.996  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:27:51.996  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:51.996  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:51.996  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:51.996  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:27:51.999  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:52.000  1036  1036 D BluetoothA2dp: Proxy object connected
08-05 11:27:52.004  7926  8174 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 11:27:52.004  7926  8174 D bt_hci_bdroid: Used up Tx Cmd credits
,08-05 11:27:52.007  7110  7128 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:27:52.013  7926  8202 E bt_mct  : hci lib postload completed
08-05 11:27:52.028  7110  7128 D BluetoothPbap: onBluetoothStateChange: up=true
,08-05 11:27:52.031  7110  7110 D BluetoothHeadset: Proxy object connected
08-05 11:27:52.031  7110  7110 D HeadsetProfile: Bluetooth service connected
08-05 11:27:52.046  7926  8172 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-05 11:27:52.046  7926  8172 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-05 11:27:52.047  7926  8172 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-05 11:27:52.047  7926  8172 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-05 11:27:52.047  7926  8172 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-05 11:27:52.047  7926  8172 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-05 11:27:52.047  7110  7251 D BluetoothPan: onBluetoothStateChange on: true
08-05 11:27:52.047  7110  7251 D BluetoothPan: onBluetoothStateChange call bindService
08-05 11:27:52.048  7926  8137 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-05 11:27:52.054  7110  7110 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 11:27:52.054  7110  7110 D PanProfile: Bluetooth service connected
08-05 11:27:52.055  7110  7251 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 11:27:52.057  7110  7128 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 11:27:52.061  8223  8223 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-05 11:27:52.062  7110  7128 D BluetoothMap: onBluetoothStateChange: up=true
08-05 11:27:52.065  1850  4458 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:27:52.065  7926  8172 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:27:52.065  7926  8172 W bt-smp  : Plain text(LSB ~ MSB) = 97 9a 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:27:52.065  7926  8172 W bt-smp  : Encrypted text(LSB ~ MSB) = 16 6c 00 c4 df 79 42 72 90 47 65 dd 2d 83 c6 c5 
08-05 11:27:52.065  7926  8172 W bt-btm  : Stopping oneshot timer
,08-05 11:27:52.067  1850  1850 D BluetoothHeadset: Proxy object connected
08-05 11:27:52.068  1850  4887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:27:52.070  7110  7110 D BluetoothA2dp: Proxy object connected
08-05 11:27:52.070  7110  7110 D A2dpProfile: Bluetooth service connected
08-05 11:27:52.072  1850  1850 D BluetoothHeadset: Proxy object connected
08-05 11:27:52.072  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 11:27:52.074  1850  1850 D BluetoothHeadset: Proxy object connected
08-05 11:27:52.075  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-05 11:27:52.075  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-05 11:27:52.076  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-05 11:27:52.080  1036  1118 D BluetoothManagerService: Message: 40
08-05 11:27:52.080  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-05 11:27:52.081  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 11:27:52.081  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:52.081  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:52.081  1939  2117 D LGBluetoothAPIService: Message: 1
08-05 11:27:52.081  1939  2117 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-05 11:27:52.081  1939  2117 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-05 11:27:52.081  1939  2117 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-05 11:27:52.082  7110  7110 D BluetoothInputDevice: Proxy object connected
08-05 11:27:52.082  7110  7110 D HidProfile: Bluetooth service connected
08-05 11:27:52.085  7110  7110 D BluetoothMap: Proxy object connected
08-05 11:27:52.085  7110  7110 D MapProfile: Bluetooth service connected
08-05 11:27:52.085  7110  7110 D BluetoothMap: getConnectedDevices()
,08-05 11:27:52.086  7926  8207 V BluetoothMapService: getConnectedDevices()
08-05 11:27:52.087  7926  7926 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:52.087  7926  7926 D BluetoothMapService: STATE_ON
08-05 11:27:52.088  7926  8172 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:27:52.088  7926  8172 W bt-smp  : Plain text(LSB ~ MSB) = d9 98 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:27:52.088  7926  8172 W bt-smp  : Encrypted text(LSB ~ MSB) = cc 4c 40 13 0e 9f b1 6c 44 c5 8b e5 c3 fa d1 09 
08-05 11:27:52.088  7926  8172 W bt-btm  : Stopping oneshot timer
08-05 11:27:52.095  7110  7110 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-05 11:27:52.096  7110  7110 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 11:27:52.099  7926  8172 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:27:52.099  7926  8172 W bt-smp  : Plain text(LSB ~ MSB) = d0 63 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:27:52.099  7926  8172 W bt-smp  : Encrypted text(LSB ~ MSB) = 9c a5 fd 25 d0 b8 27 d8 8f 8b 86 30 f8 87 9a 15 
08-05 11:27:52.099  7926  8172 W bt-btm  : Stopping oneshot timer
,08-05 11:27:52.104  7110  7110 D DockEventReceiver: finishStartingService: stopping service
08-05 11:27:52.104  7926  7926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2f919
08-05 11:27:52.105  7926  7926 V BluetoothPbapService: Pbap Service onCreate
08-05 11:27:52.105  7926  7926 V BluetoothPbapService: Starting PBAP service
08-05 11:27:52.106  7926  7926 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-05 11:27:52.106  7926  7926 V BluetoothMapService: Handler(): got msg=1
08-05 11:27:52.107  7926  7926 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-05 11:27:52.107  7926  7926 V BluetoothPbapService: Pbap Service onBind
08-05 11:27:52.108  7926  8230 D BluetoothMapMasInstance: MAS initSocket()
08-05 11:27:52.109  7926  7926 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:52.109  7926  7926 V BluetoothPbapService: state: 12
,08-05 11:27:52.109  7926  7926 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 11:27:52.109  7926  7926 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:52.109  7926  7926 V BluetoothPbapReceiver: ***********state = 12
08-05 11:27:52.109  7926  8230 D BluetoothMapMasInstance:   masId = 00
08-05 11:27:52.109  7926  8230 D BluetoothMapMasInstance:   msgTypes = 0e
08-05 11:27:52.109  7926  8230 D BluetoothMapMasInstance:   masName = SMS/MMS
08-05 11:27:52.109  7926  8230 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-05 11:27:52.110  7110  7110 D BluetoothPbap: Proxy object connected
08-05 11:27:52.110  7110  7110 D PbapServerProfile: Bluetooth service connected
08-05 11:27:52.110  7926  7926 V BluetoothPbapService: Handler(): got msg=1
08-05 11:27:52.111  7926  7926 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-05 11:27:52.112  7926  8231 V BluetoothPbapService: Pbap Service initSocket
08-05 11:27:52.112  7926  8172 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:27:52.113  7926  8172 W bt-smp  : Plain text(LSB ~ MSB) = f3 71 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:27:52.113  7926  8172 W bt-smp  : Encrypted text(LSB ~ MSB) = 4d 98 57 71 fa 57 ab a6 21 52 da 62 eb ab cc cc 
08-05 11:27:52.113  7926  8172 W bt-btm  : Stopping oneshot timer
,08-05 11:27:52.114  1036  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:52.115  2079  2079 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 11:27:52.115  2079  2079 D c       : Getting all permits...
08-05 11:27:52.115  2079  2079 D a       : Opening database...
08-05 11:27:52.119  2079  2079 D a       : Opening database auth.proximity.permit_store...
08-05 11:27:52.120  7926  8230 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:27:52.120  1036  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:52.120  2079  2079 D a       : Closing database...
08-05 11:27:52.121  7926  8230 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-05 11:27:52.121  7926  8230 V BluetoothMapMasInstance: Succeed to create listening socket 
08-05 11:27:52.121  7926  8230 D BluetoothMapMasInstance: Accepting socket connection...
08-05 11:27:52.121  7926  8231 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:27:52.122  7926  8172 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:27:52.122  7926  8172 W bt-smp  : Plain text(LSB ~ MSB) = af 98 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:27:52.122  7926  8172 W bt-smp  : Encrypted text(LSB ~ MSB) = bc 13 d5 bc c1 aa 7f e2 15 6d d2 e5 f0 a2 95 b2 
08-05 11:27:52.122  7926  8172 W bt-btm  : Stopping oneshot timer
08-05 11:27:52.125  7926  8137 D BluetoothAdapterProperties: Scan Mode:21
08-05 11:27:52.125  7926  8137 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-05 11:27:52.126  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:52.126  7926  8231 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-05 11:27:52.126  7926  8231 V BluetoothPbapService: Succeed to create listening socket 
08-05 11:27:52.126  7926  8231 V BluetoothPbapService: Accepting socket connection...
,08-05 11:27:52.133  7110  7110 D BluetoothPermissionRequest: onReceive
08-05 11:27:52.134  7110  7110 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 11:27:52.136  7110  7110 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 11:27:52.139  7926  7926 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-05 11:27:52.142  7926  7926 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-05 11:27:52.147  7926  7926 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-05 11:27:52.163  7926  7926 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-05 11:27:52.163  7926  7926 V BtOppService: onCreate
08-05 11:27:52.167  7926  7926 V BluetoothOppNotification: send message
08-05 11:27:52.169  7926  7926 V BtOppService: Starting RfcommListener
08-05 11:27:52.178  7926  7926 D BluetoothOppPreference: Dumping Names:  
,08-05 11:27:52.178  7926  7926 D BluetoothOppPreference: {}
08-05 11:27:52.178  7926  7926 D BluetoothOppPreference: Dumping Channels:  
08-05 11:27:52.178  7926  7926 D BluetoothOppPreference: {}
,08-05 11:27:52.185  7926  7926 V BtOppService: onStartCommand
08-05 11:27:52.185  7926  8235 V BtOppService: Deleted complete outbound shares, number =  0
08-05 11:27:52.188  7926  8238 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 11:27:52.188  7926  8235 V BtOppService: Deleted complete inbound failed shares, number = 0
08-05 11:27:52.190  7926  8238 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 11:27:52.190  7926  8235 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-05 11:27:52.191  7926  7926 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:52.191  7926  7926 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 11:27:52.195  7926  7926 V BluetoothOppNotification: new notify threadi!
08-05 11:27:52.196  7926  8238 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31ec1b25 on behalf of 
,08-05 11:27:52.197  7926  8235 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@156b04fa on behalf of 
08-05 11:27:52.199  7926  7926 V BluetoothOppNotification: send delay message
08-05 11:27:52.200  7926  8239 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 11:27:52.201  7926  7926 V BtOppService: start RfcommListener
08-05 11:27:52.208  7926  7926 V BtOppService: RfcommListener started
,08-05 11:27:52.209  7926  7926 V BtOppService: ContentObserver received notification
08-05 11:27:52.209  7926  7926 V BtOppService: ContentObserver received notification
08-05 11:27:52.210  7926  8239 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d717aab on behalf of 
08-05 11:27:52.211  7926  8239 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 11:27:52.211  7926  8238 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 11:27:52.211  7926  8238 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 11:27:52.212  7926  8240 V BtOppRfcommListener: Starting RFCOMM listener....
08-05 11:27:52.212  7926  8239 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 11:27:52.213  7926  8238 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17f38508 on behalf of 
08-05 11:27:52.213  1036  1643 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:52.213  7926  8238 V BluetoothOppNotification: update too frequent, put in queue
08-05 11:27:52.214  7926  8239 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@116844a1 on behalf of 
08-05 11:27:52.214  7926  8239 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 11:27:52.215  7926  8238 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 11:27:52.215  7926  8240 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:27:52.216  7926  8240 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-05 11:27:52.216  7926  8240 V BtOppRfcommListener: Started RFCOMM listener....
08-05 11:27:52.216  7926  8240 I BtOppRfcommListener: Accept thread started.
08-05 11:27:52.216  7926  8240 V BtOppRfcommListener: Accepting connection...
08-05 11:27:52.218  7926  8239 V BluetoothOppNotification: outbound notification was removed.
08-05 11:27:52.218  7926  8239 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 11:27:52.219  7926  8239 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23d476c6 on behalf of 
08-05 11:27:52.220  7926  8239 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-05 11:27:52.222  7926  8239 V BluetoothOppNotification: inbound notification was removed.
08-05 11:27:52.222  7926  8239 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 11:27:52.223  7926  8239 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20cb1687 on behalf of 
08-05 11:27:52.237  7926  7926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2f919
08-05 11:27:52.237  7926  7926 V BluetoothFtpService: Ftp Service onCreate
08-05 11:27:52.237  7926  7926 I BluetoothFtpService: Ftp Service onCreate
08-05 11:27:52.238  7926  7926 V BluetoothFtpService: Ftp Service onStartCommand
,08-05 11:27:52.238  7926  7926 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:52.238  7926  7926 V BluetoothFtpService: Starting Listening on sockets
08-05 11:27:52.238  7926  7926 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:27:52.238  7926  7926 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 11:27:52.238  7926  7926 V BluetoothSapReceiver: SapReceiver onReceive 
,08-05 11:27:52.239  7926  7926 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:52.239  7926  7926 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-05 11:27:52.239  7926  7926 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 11:27:52.242  7926  7926 V BluetoothFtpService: Handler(): got msg=1
08-05 11:27:52.242  7926  7926 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-05 11:27:52.242  7926  7926 V BluetoothFtpService: Ftp Service initSocket
08-05 11:27:52.245  1036  2049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:52.246  7926  7926 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:27:52.251  7926  7926 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-05 11:27:52.251  7926  7926 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-05 11:27:52.252  7926  8241 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-05 11:27:52.266  7926  7926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2f919
08-05 11:27:52.266  7926  7926 V BluetoothSapService: Sap Service onCreate
,08-05 11:27:52.269  7926  7926 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:27:52.269  7926  7926 V BluetoothSapService: state: 12
08-05 11:27:52.269  7926  7926 V BluetoothSapService: Starting SAP server process
08-05 11:27:52.271  7926  7926 V BluetoothSapService: SAP Service startRfcommListenerThread
08-05 11:27:52.263  8242  8242 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:52.263  8242  8242 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:52.274  7926  8243 V BluetoothSapService: Sap Service initRfcommSocket
08-05 11:27:52.274  1036  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:52.275  7926  8243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:27:52.276  7926  8243 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-05 11:27:52.277  7926  8243 V BluetoothSapService: Succeed to create listening socket 
08-05 11:27:52.277  7926  8243 V BluetoothSapService: Accepting socket connection...
08-05 11:27:52.295  8242  8242 V BT_SAP  : Event pipe created
08-05 11:27:52.295  8242  8242 V BT_SAP  : create_server_socket qcom.sap.server
08-05 11:27:52.295  8242  8242 V BT_SAP  : created socket fd 6
,08-05 11:27:52.724  6981  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:52.724  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:52.724  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:52.724  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:27:52.724  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:52.724  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:52.724  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:52.724  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:27:52.738  6981  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:52.743  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:52.743  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19d31d62 added. We now have 8 listener(s)
,08-05 11:27:52.743  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 11:27:52.749  1036  1884 D WifiServiceImplEx: setWifiEnabled: false pid=6981, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 11:27:52.749  1036  1884 D WifiService: setWifiEnabled: false pid=6981, uid=10118
08-05 11:27:52.749  1036  1884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 11:27:52.754  6981  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:52.758  1036  1993 D WifiServiceImplEx: setWifiEnabled: true pid=6981, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 11:27:52.759  1036  1993 D WifiService: setWifiEnabled: true pid=6981, uid=10118
08-05 11:27:52.759  1036  1993 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 11:27:52.778  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 11:27:52.779  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 11:27:52.779  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-05 11:27:52.781  1036  1535 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-05 11:27:52.781  1036  1535 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-05 11:27:52.783  1036  1535 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-05 11:27:52.783  1036  1535 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 11:27:52.784  1036  1535 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-05 11:27:52.784  1036  1535 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 11:27:52.784  1036  1535 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-05 11:27:52.784  1036  1535 E WifiHW  : unknown target_country: EU , set to default
08-05 11:27:52.784  1036  1535 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-05 11:27:52.784  1036  1535 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-05 11:27:52.784  1036  1535 I WifiUtil: gEnableBmps=1
08-05 11:27:53.201  7926  7926 V BluetoothOppNotification: new notify threadi!
,08-05 11:27:53.205  7926  7926 V BluetoothOppNotification: send delay message
08-05 11:27:53.213  7926  8262 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 11:27:53.226  7926  8262 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@144bed20 on behalf of 
08-05 11:27:53.227  7926  8262 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-05 11:27:53.247  7926  8262 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-05 11:27:53.256  7926  8262 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d53e6d9 on behalf of 
08-05 11:27:53.257  7926  8262 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-05 11:27:53.269  7926  8262 V BluetoothOppNotification: outbound notification was removed.
08-05 11:27:53.270  7926  8262 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 11:27:53.279  7926  8262 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21e5989e on behalf of 
08-05 11:27:53.280  7926  8262 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-05 11:27:53.300  7926  8262 V BluetoothOppNotification: inbound notification was removed.
08-05 11:27:53.300  7926  8262 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 11:27:53.307  7926  8262 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b764f7f on behalf of 
08-05 11:27:53.370  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 11:27:53.370  1036  1118 D Tethering: InitialState.processMessage what=4
08-05 11:27:53.371  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-05 11:27:53.374   303   881 D SoftapController: Softap fwReload - Ok
08-05 11:27:53.375  1036  1535 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (587ms)
08-05 11:27:53.376   303   881 D CommandListener: Setting iface cfg
08-05 11:27:53.376   303   881 D CommandListener: Trying to bring down wlan0
08-05 11:27:53.376   303   881 D CommandListener: Clearing all IP addresses on wlan0
08-05 11:27:53.378  1036  1535 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-05 11:27:53.379  1036  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:27:53.379  1036  1535 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:27:53.379  1036  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 11:27:53.380  1036  1535 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-05 11:27:53.380  1036  1535 D WifiMonitor: connecting to supplicant
08-05 11:27:53.380  1036  1535 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
08-05 11:27:53.397  8274  8274 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-05 11:27:53.373  8274  8274 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:53.373  8274  8274 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6845 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:27:53.406  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:53.412  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:53.415  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-05 11:27:53.419  8274  8274 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-05 11:27:53.419  8274  8274 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-05 11:27:53.419  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-05 11:27:53.422  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 11:27:53.422  7110  7110 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 11:27:53.422  7110  7110 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 11:27:53.422  7110  7110 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 11:27:53.422  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 11:27:53.422  7110  7110 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 11:27:53.423  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 11:27:53.423  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 11:27:53.423  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 11:27:53.423  7110  7110 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 11:27:53.423  7110  7110 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 11:27:53.424  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 11:27:53.424  7110  7110 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 11:27:53.424  7110  7110 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 11:27:53.424  7110  7110 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 11:27:53.424  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 11:27:53.425  7110  7110 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 11:27:53.425  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 11:27:53.425  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 11:27:53.425  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 11:27:53.425  7110  7110 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 11:27:53.425  7110  7110 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 11:27:53.460  1036  1920 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8276 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-05 11:27:53.477   347   347 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 268us total 17.654ms
08-05 11:27:53.483  8274  8274 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-05 11:27:53.498   347   347 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 426us total 20.597ms
,08-05 11:27:53.519   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 423us total 19.758ms
,08-05 11:27:53.551  8274  8274 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-05 11:27:53.558  8274  8274 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-05 11:27:53.578  1036  2049 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8304 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 11:27:53.584  8276  8302 W FormManager: Network not available. Please check & try again.
08-05 11:27:53.593  8276  8303 V FormManager: Network unavailable.
08-05 11:27:53.594  8276  8303 V FormManager: Network unavailable.
,08-05 11:27:53.611  1036  1956 I ActivityManager: Killing 7400:com.android.chrome/u0a57 (adj 15): empty #17
,08-05 11:27:53.635  8304  8304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 11:27:53.649  1036  2030 W libprocessgroup: failed to open /acct/uid_10057/pid_7400/cgroup.procs: No such file or directory
,08-05 11:27:53.653  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 11:27:53.658  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 11:27:53.659  1036  1957 I ActivityManager: Killing 7418:com.lge.drmservice/u0a62 (adj 15): empty #17
08-05 11:27:53.689  1036  1938 W libprocessgroup: failed to open /acct/uid_10062/pid_7418/cgroup.procs: No such file or directory
,08-05 11:27:54.156  8274  8274 E wpa_supplicant: USIM:  scard_init function
,08-05 11:27:54.157  8274  8274 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-05 11:27:54.301  8274  8274 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 11:27:54.327  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-05 11:27:54.339  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 11:27:54.339  7110  7110 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 11:27:54.339  7110  7110 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 11:27:54.339  7110  7110 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-05 11:27:54.346  8274  8274 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 11:27:54.346  8274  8274 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 11:27:54.352  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 11:27:54.354  7110  7110 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 11:27:54.354  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-05 11:27:54.354  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 11:27:54.354  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 11:27:54.354  7110  7110 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 11:27:54.354  7110  7110 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-05 11:27:54.355  7110  7110 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-05 11:27:54.383  1036  1535 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-05 11:27:54.383  1036  1535 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-05 11:27:54.384  1036  1535 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-05 11:27:54.384  1036  1535 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-05 11:27:54.385  1036  1535 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:54.385  1036  1535 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:54.385  1036  1535 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:54.386  1036  1535 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:27:54.386  1036  1535 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-05 11:27:54.386  1036  1535 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,08-05 11:27:54.396  1036  1535 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-05 11:27:54.397  1036  1535 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-05 11:27:54.397  1036  1535 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-05 11:27:54.399  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:54.400  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:54.400  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:54.400  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:54.400  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-05 11:27:54.403  1036  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:27:54.403  1036  1535 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:27:54.403  1036  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 11:27:54.408  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:54.409  1939  1939 D WfdService: Waiting for WifiP2p enabling
08-05 11:27:54.413  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:54.413  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:54.413  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:54.413  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:54.413  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:54.413  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:54.413  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:54.413  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:27:54.418  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:54.428  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,08-05 11:27:54.431  1036  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-05 11:27:54.431  1036  1535 D WifiNative-wlan0: doBoolean: SET update_config 1
08-05 11:27:54.432  1036  1535 D WifiNative-wlan0: SET update_config 1: returned true
08-05 11:27:54.432  1036  1535 D WifiConfigStore: Loading config and enabling all networks 
08-05 11:27:54.432  1036  1535 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-05 11:27:54.432  1036  1535 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
08-05 11:27:54.439  1036  1535 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-05 11:27:54.447  1036  1535 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-05 11:27:54.447  1036  1535 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-05 11:27:54.452  1036  1535 D WifiStateMachine: enableVerboseLogging : level 2
08-05 11:27:54.452  1036  1535 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-05 11:27:54.455  1036  1535 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-05 11:27:54.455  1036  1535 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-05 11:27:54.456  1036  1535 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-05 11:27:54.456  1036  1535 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-05 11:27:54.456  1036  1535 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-05 11:27:54.456  1036  1535 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-05 11:27:54.457  1036  1535 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-05 11:27:54.457  1036  1535 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-05 11:27:54.457  1036  1535 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-05 11:27:54.457  1036  1535 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-05 11:27:54.458  1036  1535 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-05 11:27:54.458  1036  1535 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-05 11:27:54.458  1036  1535 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-05 11:27:54.461  1939  1939 D WfdsService: Supplicant Connection state is changed : true
08-05 11:27:54.461  1939  2249 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-05 11:27:54.461  1939  2249 D WfdsService: Set the WFDS Monitor: true
08-05 11:27:54.461  1939  2249 D WfdsMonitor: WfdsMonitorThread create
08-05 11:27:54.461  1939  2249 D WfdsMonitor: WFDS Monitor is created and started
08-05 11:27:54.461  1939  2249 D WfdsService: WiFi: Supplicant connection re-established
08-05 11:27:54.462  1036  1535 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 11:27:54.462  1036  1535 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-05 11:27:54.462  1036  1535 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-05 11:27:54.462  1036  1535 D WifiNative-HAL: Setting external_sim to 1
08-05 11:27:54.462  1036  1535 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-05 11:27:54.463  1036  1535 D WifiNative-wlan0: SET external_sim 1: returned true
08-05 11:27:54.463  1036  1535 I WifiNative-HAL: startHal
08-05 11:27:54.463  1036  1535 D wifi    : setting scan oui 0xaf6a7f20
08-05 11:27:54.464  1036  1535 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 11:27:54.464  1036  1535 I WifiNative-HAL: startHal
08-05 11:27:54.464  1036  1535 D wifi    : setting scan oui 0xaf6a7f20
08-05 11:27:54.464  1036  1535 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-05 11:27:54.465  1939  8334 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-05 11:27:54.466  1939  8334 E CtrlSupplicant: Succeed to open control connection
08-05 11:27:54.466  1939  8334 E CtrlSupplicant: Succeed to open monitor connection
,08-05 11:27:54.471  1036  1535 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-05 11:27:54.471  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-05 11:27:54.472  8274  8274 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-05 11:27:54.472  1036  1535 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-05 11:27:54.472  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 11:27:54.472  8274  8274 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 11:27:54.473  1939  8334 D WfdsMonitor: Supplicant connection established
08-05 11:27:54.473  1036  1535 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 11:27:54.473  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-05 11:27:54.473  8274  8274 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-05 11:27:54.474  1939  2249 D WfdsService: Connected to the supplicant for wfds
08-05 11:27:54.474  1036  1535 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-05 11:27:54.474  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 11:27:54.489  8274  8274 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-05 11:27:54.492  1036  1535 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,08-05 11:27:54.492  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 11:27:54.493  8274  8274 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 11:27:54.493  1036  1535 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 11:27:54.493  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-05 11:27:54.493  8274  8274 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-05 11:27:54.494  1036  1535 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-05 11:27:54.494  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 11:27:54.494  8274  8274 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 11:27:54.494  1036  1535 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 11:27:54.495  1036  1535 E WifiNative: : [352,763,092 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-05 11:27:54.495  1036  1535 D WifiNative-wlan0: doBoolean: RECONNECT
08-05 11:27:54.510  7966  7966 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:54.514  1036  1535 D WifiNative-wlan0: RECONNECT: returned true
08-05 11:27:54.514  1036  1535 D WifiNative-wlan0: doString: [STATUS]
08-05 11:27:54.515  1036  8333 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:27:54.515  1036  8333 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 11:27:54.516  1036  1535 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 11:27:54.516  1036  1535 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 11:27:54.518  1036  1535 D WifiNative-wlan0: SET ps 1: returned true
08-05 11:27:54.520  1036  1534 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 11:27:54.523   303   881 D CommandListener: Setting iface cfg
08-05 11:27:54.523   303   881 D CommandListener: Trying to bring up p2p0
08-05 11:27:54.524  1036  1534 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 11:27:54.524  1036  1535 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-05 11:27:54.524  1036  1534 D LGWifiP2pService: P2pEnablingState
08-05 11:27:54.524  1036  1534 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.524  1036  1534 D LGWifiP2pService: P2p socket connection successful
08-05 11:27:54.524  1036  1534 D LGWifiP2pService: P2pEnabledState
08-05 11:27:54.524  1036  1534 D LGWifiP2pService: sending p2p connection changed broadcast
08-05 11:27:54.524  1036  1535 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-05 11:27:54.525  1036  1534 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-05 11:27:54.525  1036  1535 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-05 11:27:54.525  1036  1535 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-05 11:27:54.525  1036  1534 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-05 11:27:54.525  1036  1534 D WifiNative-p2p0: doBoolean: SET device_name G3
08-05 11:27:54.525  1036  1535 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-05 11:27:54.526  1036  1534 D WifiNative-p2p0: SET device_name G3: returned true
08-05 11:27:54.526  1036  1534 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-05 11:27:54.526  1036  1534 D LGWifiP2pService: before postfix = G3
08-05 11:27:54.526  1036  1534 D WifiServerServiceExt: postfix byte check : 2
08-05 11:27:54.526  1036  1534 D LGWifiP2pService: after postfix = G3
08-05 11:27:54.526  1036  1534 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-05 11:27:54.526  1036  1535 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-05 11:27:54.526  1036  1534 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-05 11:27:54.526  1036  1534 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-05 11:27:54.526  1036  1535 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-05 11:27:54.526  1036  1535 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-05 11:27:54.526  8274  8274 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-05 11:27:54.527  1036  1535 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-05 11:27:54.527  1036  1535 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-05 11:27:54.528  1036  1535 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-05 11:27:54.528  1036  1535 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-05 11:27:54.528  8274  8274 E wpa_supplicant: disconnect_rssi_lvl: -100
08-05 11:27:54.528  1036  1534 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-05 11:27:54.528  1036  1534 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-05 11:27:54.530  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 11:27:54.530  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-05 11:27:54.530  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-05 11:27:54.530  1939  1939 D WfdsService: WifiP2pState is changed : true
08-05 11:27:54.530  1939  1939 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-05 11:27:54.531  1939  1939 D WfdsService: isConnected: false
08-05 11:27:54.531  1036  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.531  1036  1555 I WifiNative-HAL: startHal
08-05 11:27:54.531  1939  2249 D WfdsService: Receive the WFDS_ENABLE Method
08-05 11:27:54.531  8304  8304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:27:54.531  1939  2249 D WfdsService: Set the WFDS Monitor: true
08-05 11:27:54.531  1939  2,249 D WfdsService: Connected to the supplicant for wfds
08-05 11:27:54.531  1939  2249 D WfdsJNI : doCommand: WFDS_SET TRUE
08-05 11:27:54.531  8274  8274 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-05 11:27:54.531  1036  1556 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 11:27:54.534  1939  2249 D WfdsService: selectPreferredScanChannel [36]
08-05 11:27:54.534  1939  2249 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-05 11:27:54.539  1036  1534 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-05 11:27:54.539  1036  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf6a7f20
08-05 11:27:54.539  1036  1555 D wifi    : failed to get capabilities : -3
08-05 11:27:54.540  1036  1555 E WifiScanningService: could not get scan capabilities
08-05 11:27:54.540  1036  1534 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-05 11:27:54.540  1036  1534 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-05 11:27:54.540  1036  1534 D WifiNative-HAL: p2pGetDeviceAddress
08-05 11:27:54.540  1036  1534 D WifiNative-HAL: p2pGetDeviceAddress returning 
,08-05 11:27:54.541  1036  1534 D LGWifiP2pService: DeviceAddress: 
08-05 11:27:54.541  1036  1534 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-05 11:27:54.542  1036  1535 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 11:27:54.542  1036  1535 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 11:27:54.542  1939  1939 I WfdStateTracker: handleP2pThisDeviceChanged
08-05 11:27:54.543  1939  1939 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-05 11:27:54.543  1036  1535 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 11:27:54.543  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-05 11:27:54.543  1939  1939 D WfdsService: Update P2p Interface State: 3
08-05 11:27:54.543  1036  1534 D WifiNative-p2p0: P2P_FLUSH: returned true
08-05 11:27:54.543  1036  1534 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-05 11:27:54.543  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 11:27:54.543  1036  1534 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-05 11:27:54.544  1036  1534 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-05 11:27:54.544  1036  1534 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
,08-05 11:27:54.544  1036  1534 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-05 11:27:54.550  8276  8352 W FormManager: Network not available. Please check & try again.
08-05 11:27:54.552  8276  8353 V FormManager: Network unavailable.
08-05 11:27:54.554  1036  1534 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-05 11:27:54.554  1036  1534 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-05 11:27:54.554  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:54.554  1036  1534 D LGWifiP2pService: InactiveState
08-05 11:27:54.555  1036  1534 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.555  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.555  1036  1534 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-05 11:27:54.555  8274  8274 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 11:27:54.556  8274  8274 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:54.556  8274  8274 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 11:27:54.556  8274  8274 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.557  8274  8274 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.558  1939  8334 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 11:27:54.558  1939  8334 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:27:54.558  1939  8334 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:27:54.559  1036  1534 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-05 11:27:54.559  1036  8333 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 11:27:54.559  1036  8333 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:54.559  1036  8333 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:54.559  1036  8333 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:54.559  1036  8333 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:27:54.559  1036  8333 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.559  1036  8333 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.560  1036  8333 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.560  1036  8333 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:27:54.560  1036  8333 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.560  1036  8333 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.560  1036  8333 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.560  8274  8274 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-05 11:27:54.562  8274  8274 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:54.562  8274  8274 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 11:27:54.562  8274  8274 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.563  8274  8274 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.563  1036  1534 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.564  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.564  1036  1534 D LGWifiP2pService: DefaultState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.564  1036  1535 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
,08-05 11:27:54.564  1036  1534 D LGWifiP2pService: InactiveState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 11:27:54.564  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.564  1036  1534 D LGWifiP2pService: DefaultState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.565  1036  1534 D LGWifiP2pService: InactiveState{ when=-11ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.565  1036  1535 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-05 11:27:54.565  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.565  1036  1534 D LGWifiP2pService: DefaultState{ when=-11ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.565  1036  1535 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-05 11:27:54.565  1939  2249 W WfdsService: DefaultState - msg [9441285] is not handled
08-05 11:27:54.565  1036  1535 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-05 11:27:54.565  1036  1535 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-05 11:27:54.566  8274  8274 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-05 11:27:54.566  8274  8274 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 11:27:54.565  1036  1534 D LGWifiP2pService: InactiveState{ when=-10ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.566  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.566  1036  1534 D LGWifiP2pService: DefaultState{ when=-11ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.566  1036  1036 E WifiServerServiceExt: No p2p device connected
08-05 11:27:54.566  1036  1534 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.566  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:54.567  1036  1535 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-05 11:27:54.567  1036  1535 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-05 11:27:54.567  1939  8334 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:27:54.567  1036  1535 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-05 11:27:54.567  1036  1535 D WifiNative-wlan0: doBoolean: SCAN
08-05 11:27:54.567  1939  8334 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:27:54.567  1036  8333 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 11:27:54.567  1036  8333 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:54.568  1036  8333 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:54.568  1036  8333 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:27:54.568  1036  8333 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:27:54.568  1036  8333 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.568  8274  8274 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-05 11:27:54.568  1036  8333 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.568  1036  8333 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.568  1036  8333 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:27:54.568  1036  8333 E WifiMonitor: WifiMonitor:p2p0 cn,t=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.568  1036  8333 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.568  1036  8333 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:27:54.568  1036  8333 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-05 11:27:54.568  8276  8353 V FormManager: Network unavailable.
08-05 11:27:54.568  1036  1535 D WifiNative-wlan0: SCAN: returned true
08-05 11:27:54.568  1036  8333 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 11:27:54.568  1036  8333 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 11:27:54.568  1036  8333 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 11:27:54.568  1036  8333 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-05 11:27:54.568  1036  8333 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-05 11:27:54.568  1036  8333 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-05 11:27:54.568  1036  8333 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-05 11:27:54.569  1036  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=352837  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:27:54.571  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:54.571  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:27:54.571  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 11:27:54.571  1036  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=352840  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:27:54.572  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:27:54.572  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:27:54.572  1036  1535 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:27:54.572  1036  1535 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:27:54.572  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:27:54.573  1036  1535 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:27:54.573  1036  1535 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:27:54.574  1036  1535 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:27:54.574  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:27:54.574  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 11:27:54.575  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:27:54.575  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 11:27:54.578  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleRec,eiver:2586 
,08-05 11:27:54.581  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 11:27:54.586  4787  8355 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 11:27:54.589  4787  8356 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:27:54.589  4787  8356 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 11:27:54.626  1036  1956 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8358 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-05 11:27:54.730  8358  8358 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-05 11:27:54.730  8358  8358 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-05 11:27:54.741  8358  8358 V [BNRBootReceiver]: Boot Receiver Return
,08-05 11:27:54.742  8358  8358 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-05 11:27:54.806  6981  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:27:54.806  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:54.806  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:54.806  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:54.806  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:54.806  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:54.806  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:54.806  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:27:54.811  6981  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:54.814  1036  1695 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8376 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 11:27:54.815  1036  1695 I ActivityManager: Killing 7441:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-05 11:27:54.823  6981  7047 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-05 11:27:54.824  6981  7047 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-05 11:27:54.826  6981  7047 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3ab7b724 Bundle[{}]
08-05 11:27:54.827  6981  7047 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 11:27:54.827  6981  7047 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-05 11:27:54.828  6981  7047 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-05 11:27:54.828  6981  7047 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-05 11:27:54.831  6981  7047 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-05 11:27:54.832  6981  7047 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-05 11:27:54.838  6981  7047 I System.out: Running OutgoingSocketThread
08-05 11:27:54.840  6981  8387 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 921)
08-05 11:27:54.841  6981  8387 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 51716
08-05 11:27:54.842  6981  8387 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-05 11:27:54.952  1036  1574 W libprocessgroup: failed to open /acct/uid_10085/pid_7441/cgroup.procs: No such file or directory
,08-05 11:27:55.018  8376  8376 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 11:27:55.045  8376  8376 D PluginManager: init()
,08-05 11:27:55.441  8376  8376 W ExternalStrings: load override strings
08-05 11:27:55.441  8376  8376 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 11:27:55.441  8376  8376 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-05 11:27:55.444  8376  8376 D StatusProvider: onCreate
,08-05 11:27:55.488  8376  8376 V Signer  : override build config not found
,08-05 11:27:55.489  8376  8376 D Signer  : value of property debug is false
,08-05 11:27:55.516  8376  8376 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-05 11:27:55.516  8376  8376 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-05 11:27:55.516  8376  8376 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,08-05 11:27:55.516  8376  8376 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-05 11:27:55.517  8376  8376 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-05 11:27:55.517  8376  8376 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-05 11:27:55.517  8376  8376 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-05 11:27:55.517  8376  8376 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-05 11:27:55.517  8376  8376 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-05 11:27:55.517  8376  8376 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-05 11:27:55.517  8376  8376 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-05 11:27:55.518  8376  8376 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-05 11:27:55.518  8376  8376 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-05 11:27:55.526  8376  8376 V LGMDMManager: Create singleton instance
08-05 11:27:55.567  8376  8376 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-05 11:27:55.626  8376  8402 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 11:27:55.626  8376  8376 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 11:27:55.652  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:27:55.658  7110  7110 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:27:55.692  1036  1938 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8405 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-05 11:27:55.693  1036  1938 I ActivityManager: Killing 7470:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-05 11:27:55.758  8376  8401 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-05 11:27:55.839  6981  7047 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 922)
08-05 11:27:55.839  6981  7047 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 922)
,08-05 11:27:55.842  6981  7047 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 927)
,08-05 11:27:55.842  6981  7047 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-05 11:27:55.842  6981  7047 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 928)
,08-05 11:27:55.844  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:27:55.844  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2da38ef3 added. We now have 2 listener(s)
08-05 11:27:55.906  1036  1052 W libprocessgroup: failed to open /acct/uid_10093/pid_7470/cgroup.procs: No such file or directory
,08-05 11:27:55.923  1036  1695 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 11:27:55.929  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:27:55.929  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:27:55.929  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:27:55.929  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:55.930  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72417b0 added. We now have 9 listener(s)
08-05 11:27:55.930  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:27:55.933  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 11:27:55.939  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:27:55.944  6981  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:27:55.944  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:55.944  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:55.944  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:55.944  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:55.944  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:55.944  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:55.944  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:27:55.946  6981  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:55.946  6981  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:27:55.946  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:27:55.946  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1549adae added. We now have 3 listener(s)
08-05 11:27:55.947  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:55.948  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:27:55.950  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:27:55.950  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:27:55.950  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:27:55.950  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:55.950  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5de274f added. We now have 10 listener(s)
08-05 11:27:55.950  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:27:55.950  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:55.951  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:55.951  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:55.951  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:55.951  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:55.951  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:27:55.951  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:27:55.951  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2da38ef3 removed from the list
08-05 11:27:55.951  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:55.951  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72417b0 removed from the list
08-05 11:27:55.952  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:55.952  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:55.952  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:55.953  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:55.953  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:55.954  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:55.954  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:55.954  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:55.954  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72417b0 not in the list
08-05 11:27:55.954  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:55.954  6981  7047 D org.thaliproject.p2p.btconnecto,rlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:55.955  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:55.955  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:55.955  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:55.955  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5de274f removed from the list
08-05 11:27:55.955  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:55.955  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:55.955  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:55.955  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:27:55.955  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1549adae removed from the list
08-05 11:27:55.956  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:27:55.956  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25aafedc added. We now have 2 listener(s)
08-05 11:27:55.957  1036  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:55.960  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:27:55.960  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:27:55.960  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:27:55.960  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:55.960  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d9dbbe5 added. We now have 9 listener(s)
08-05 11:27:55.960  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:27:55.960  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 11:27:55.963  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:27:55.966  6981  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:27:55.966  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:55.966  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:55.966  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:55.966  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:55.966  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:55.966  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:55.966  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:27:55.967  8405  8405 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 11:27:55.968  6981  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:55.968  6981  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:27:55.968  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:27:55.968  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7fe96b added. We now have 3 listener(s)
08-05 11:27:55.969  1036  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:55.970  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:55.972  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:55.973  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:27:55.974  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:27:55.974  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:27:55.974  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:55.974  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c572cc8 added. We now have 10 listener(s)
08-05 11:27:55.974  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:27:55.974  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:27:55.974  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:27:55.974  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 11:27:55.974  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:27:55.974  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 11:27:55.978  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 11:27:55.978  1036  1695 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:55.983  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 11:27:55.985  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 11:27:55.986  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 11:27:55.987  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 11:27:55.989  6981  7047 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 11:27:55.989  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:55.989  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:55.991  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:55.991  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:55.991  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:55.991  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:55.991  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:55.991  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:27:55.991  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:27:55.991  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25aafedc removed from the list
08-05 11:27:55.991  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:55.991  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d9dbbe5 removed from the list
08-05 11:27:55.991  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:55.992  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:55.992  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:55.992  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:55.993  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:55.993  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:55.993  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:55.993  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d9dbbe5 not in the list
08-05 11:27:55.993  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:55.993  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:55.994  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:55.994  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:55.994  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:55.994  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:55.994  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:55.994  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c572cc8 removed from the list
08-05 11:27:55.994  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:55.995  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:55.995  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:55.995  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:27:55.995  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7fe96b removed from the list
08-05 11:27:55.995  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:27:55.996  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2331b147 added. We now have 2 listener(s)
08-05 11:27:55.996  1036  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:55.998  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:27:55.998  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:27:55.999  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:27:55.999  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:55.999  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4164d74 added. We now have 9 listener(s)
08-05 11:27:55.999  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:27:55.999  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 11:27:56.003  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:27:56.011  6981  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:27:56.011  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:56.011  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:56.011  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:56.011  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:56.011  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:56.011  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:56.011  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:27:56.013  6981  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:56.013  6981  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 11:27:56.013  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:27:56.014  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1701a312 added. We now have 3 listener(s)
08-05 11:27:56.014  1036  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:56.014  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:56.016  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:56.017  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:27:56.018  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:27:56.018  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:27:56.018  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:56.018  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d4e1ae3 added. We now have 10 listener(s)
08-05 11:27:56.018  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:27:56.018  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:27:56.019  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:27:56.019  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:27:56.019  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 11:27:56.019  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:27:56.019  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 11:27:56.132  1036  1643 I art     : Explicit concurrent mark sweep GC freed 46036(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.945ms total 128.381ms
,08-05 11:27:56.137  8405  8405 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-05 11:27:56.139  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 11:27:56.140  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:56.144  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 11:27:56.146  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 11:27:56.147  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 11:27:56.148  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:27:56.151  6981  7047 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 11:27:56.151  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:56.151  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:56.151  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:56.152  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:56.152  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:56.152  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:27:56.152  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:27:56.152  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2331b147 removed from the list
08-05 11:27:56.152  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:56.152  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4164d74 removed from the list
08-05 11:27:56.152  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:56.152  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:56.153  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:56.154  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:56.154  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:56.154  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:56.154  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:56.154  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4164d74 not in the list
08-05 11:27:56.154  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:56.154  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:56.155  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:56.155  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:56.155  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:56.155  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:56.155  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:56.155  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d4e1ae3 removed from the list
08-05 11:27:56.155  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:56.155  6981  7047 W org.thaliproject.p2p.btco,nnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:56.155  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:56.155  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:27:56.155  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1701a312 removed from the list
08-05 11:27:56.156  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:27:56.156  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bd2de5e added. We now have 2 listener(s)
08-05 11:27:56.160  1036  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 11:27:56.162  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:27:56.162  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:27:56.162  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:27:56.162  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:56.162  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@133d823f added. We now have 9 listener(s)
08-05 11:27:56.162  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:27:56.162  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 11:27:56.164  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:27:56.167  6981  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:27:56.167  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:56.167  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:56.167  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:56.167  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:56.167  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:56.167  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:56.167  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:27:56.168  6981  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:56.168  6981  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:27:56.168  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:27:56.168  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@224e6855 added. We now have 3 listener(s)
08-05 11:27:56.168  1036  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:56.169  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:56.170  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:56.171  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:27:56.171  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:27:56.171  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:27:56.171  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:56.171  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorl,ib.DiscoveryManager@5ea826a added. We now have 10 listener(s)
08-05 11:27:56.171  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:27:56.172  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:27:56.172  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:27:56.172  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 11:27:56.172  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:27:56.172  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 11:27:56.176  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 11:27:56.177  1036  1695 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:56.179  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 11:27:56.180  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 11:27:56.181  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 11:27:56.181  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:27:56.182  6981  7047 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 11:27:56.185  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:56.185  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:56.185  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 11:27:56.187  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:56.187  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:56.187  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:27:56.187  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:27:56.187  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bd2de5e removed from the list
08-05 11:27:56.187  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:56.187  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@133d823f removed from the list
08-05 11:27:56.187  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:56.187  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:56.187  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:56.187  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:56.188  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:56.188  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:56.188  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:56.188  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@133d823f not in the list
08-05 11:27:56.188  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:56.188  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:56.189  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:56.189  6981  7047 D BluetoothLeScanner: could not find callback wrapper
08-05 11:27:56.189  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:27:56.189  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:56.189  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:56.189  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ea826a removed from the list
08-05 11:27:56.189  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:56.189  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:56.189  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:56.189  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:27:56.189  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@224e6855 removed from the list
08-05 11:27:56.190  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:27:56.190  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionM,anagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5a34d1 added. We now have 2 listener(s)
08-05 11:27:56.190  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:56.192  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:27:56.192  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:27:56.192  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:27:56.192  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:56.192  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c265b36 added. We now have 9 listener(s)
08-05 11:27:56.192  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:27:56.192  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 11:27:56.194  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:27:56.197  6981  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:27:56.197  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:27:56.197  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:27:56.197  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:27:56.197  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:27:56.197  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:27:56.197  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:27:56.197  6981  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:27:56.200  6981  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:27:56.200  6981  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:27:56.200  8405  8405 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-05 11:27:56.200  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:27:56.200  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26a1fba4 added. We now have 3 listener(s)
08-05 11:27:56.200  8405  8405 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-05 11:27:56.201  1036  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:27:56.201  8405  8405 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-05 11:27:56.201  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:56.201  8405  8405 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-05 11:27:56.202  8405  8405 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-05 11:27:56.202  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:27:56.203  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:27:56.203  8405  8405 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-05 11:27:56.203  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:27:56.203  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:27:56.203  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:27:56.203  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@127c4d0d added. We now have 10 listener(s)
08-05 11:27:56.204  6981  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:27:56.204  6981  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:27:56.204  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:56.204  6981  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:27:56.204  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:56.204  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:56.204  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:27:56.204  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:27:56.204  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5a34d1 removed from the list
08-05 11:27:,56.204  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:56.204  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c265b36 removed from the list
08-05 11:27:56.204  6981  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:27:56.204  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:56.205  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:56.205  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:56.206  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:56.206  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:56.206  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:56.206  6981  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c265b36 not in the list
08-05 11:27:56.206  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:56.206  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:56.206  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:27:56.206  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:27:56.206  6981  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:27:56.206  6981  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@127c4d0d removed from the list
08-05 11:27:56.206  6981  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:27:56.206  6981  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:27:56.206  6981  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:27:56.206  6981  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:27:56.207  6981  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26a1fba4 removed from the list
08-05 11:27:56.207  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-05 11:27:56.208  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-05 11:27:56.208  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-05 11:27:56.208  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:27:56.208  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 11:27:56.208  6981  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-05 11:27:56.209  8405  8405 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-05 11:27:56.212  8376  8401 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:27:56.212  8376  8401 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 11:27:56.220  6981  8442 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 936, name: My test thread name)
08-05 11:27:56.220  6981  8442 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 936, thread name: My test thread name)
08-05 11:27:56.220  6981  8442 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 936, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 11:27:56.222  8405  8405 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 11:27:56.224  6981  8443 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 938, name: My test thread name)
08-05 11:27:56.224  6981  8443 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 938, thread name: My test thread name)
08-05 11:27:56.224  6981  8443 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 938, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 11:27:56.225  8405  8405 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:27:56.226  6981  7047 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-05 11:27:56.226  6981  7047 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-05 11:27:56.226  6981  7047 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-05 11:27:56.226  6981  7047 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-05 11:27:56.226  6981  7047 D com.test.thalitest.ThaliTestRunner: Total duration: 24019 ms
08-05 11:27:56.227  8405  8405 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 11:27:56.227  6981  7047 I jxcore-log: Total number of executed tests:  80
08-05 11:27:56.227  6981  7047 I jxcore-log: 
08-05 11:27:56.228  6981  7047 I jxcore-log: Number of passed tests:  80
08-05 11:27:56.228  6981  7047 I jxcore-log: 
08-05 11:27:56.228  6981  7047 I jxcore-log: Number of failed tests:  0
08-05 11:27:56.228  6981  7047 I jxcore-log: 
08-05 11:27:56.228  6981  7047 I jxcore-log: Number of ignored tests:  0
08-05 11:27:56.228  6981  7047 I jxcore-log: 
08-05 11:27:56.228  6981  7047 I jxcore-log: Total duration:  24019
08-05 11:27:56.228  6981  7047 I jxcore-log: 
08-05 11:27:56.229  8376  8376 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-05 11:27:56.230  8405  8405 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-05 11:27:56.231  6981  7047 I jxcore-log: Unit Test app is loaded
08-05 11:27:56.231  6981  7047 I jxcore-log: 
08-05 11:27:56.233  8405  8405 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-05 11:27:56.236  8405  8405 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 11:27:56.236  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 11:27:56.237  8405  8405 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-05 11:27:56.241  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:27:56.241  6981  7047 I jxcore-log: 
08-05 11:27:56.246  6981  6981 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-05 11:27:56.247  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:27:56.247  6981  7047 I jxcore-log: 
08-05 11:27:56.249  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:27:56.249  6981  7047 I jxcore-log: 
08-05 11:27:56.250  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:27:56.250  6981  7047 I jxcore-log: 
08-05 11:27:56.251  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:27:56.251  6981  7047 I jxcore-log: 
08-05 11:27:56.254  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:27:56.254  6981  7047 I jxcore-log: 
08-05 11:27:56.257  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:27:56.257  6981  7047 I jxcore-log: 
,08-05 11:27:56.261  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:27:56.261  6981  7047 I jxcore-log: 
08-05 11:27:56.262  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 11:27:56.262  6981  7047 I jxcore-log: 
08-05 11:27:56.263  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 11:27:56.263  6981  7047 I jxcore-log: 
08-05 11:27:56.264  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:27:56.264  6981  7047 I jxcore-log: 
08-05 11:27:56.265  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:27:56.265  6981  7047 I jxcore-log: 
08-05 11:27:56.266  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 11:27:56.266  6981  7047 I jxcore-log: 
08-05 11:27:56.267  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 11:27:56.267  6981  7047 I jxcore-log: 
08-05 11:27:56.268  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 11:27:56.268  6981  7047 I jxcore-log: 
08-05 11:27:56.269  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:27:56.269  6981  7047 I jxcore-log: 
08-05 11:27:56.269  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:27:56.269  6981  7047 I jxcore-log: 
08-05 11:27:56.270  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 11:27:56.270  6981  7047 I jxcore-log: 
08-05 11:27:56.271  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 11:27:56.271  6981  7047 I jxcore-log: 
,08-05 11:27:56.271  8405  8405 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:27:56.271  8405  8405 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 11:27:56.272  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:27:56.272  6981  7047 I jxcore-log: 
08-05 11:27:56.273  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:27:56.273  6981  7047 I jxcore-log: 
08-05 11:27:56.273  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 11:27:56.273  6981  7047 I jxcore-log: 
08-05 11:27:56.276  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 11:27:56.276  6981  7047 I jxcore-log: 
08-05 11:27:56.277  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:27:56.277  6981  7047 I jxcore-log: 
08-05 11:27:56.278  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:27:56.278  6981  7047 I jxcore-log: 
08-05 11:27:56.278  8405  8405 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-05 11:27:56.279  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:27:56.279  6981  7047 I jxcore-log: 
08-05 11:27:56.279  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:27:56.279  6981  7047 I jxcore-log: 
08-05 11:27:56.280  8405  8405 V SoundPool: load: fd=31, offset=10857164, length=17813, priority=1
08-05 11:27:56.280  8405  8405 V SoundPool: create sampleID=1, fd=30, offset=17813 length=10857164
08-05 11:27:56.280  8405  8405 V SoundPool: doLoad: loading sample sampleID=1
08-05 11:27:56.280  8405  8448 V SoundPool: Start decode
08-05 11:27:56.280  8405  8448 V MediaPlayer[Native]: decode(30, 10857164, 17813)
08-05 11:27:56.280  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:27:56.280  6981  7047 I jxcore-log: 
08-05 11:27:56.280   309   309 V MediaPlayerService: decode(23, 10857164, 17813)
08-05 11:27:56.280   309   309 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-05 11:27:56.280   309   309 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-05 11:27:56.280   309   309 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-05 11:27:56.280   309   309 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-05 11:27:56.280   309   309 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-05 11:27:56.280   309   309 V MediaPlayerService: player type = 3
08-05 11:27:56.280   309   309 V AwesomePlayer: AwesomePlayer create()
08-05 11:27:56.281  8405  8405 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 11:27:56.281   309   309 V AwesomePlayer: reset_l() 
08-05 11:27:56.281   309   309 V AwesomePlayer: cancelPlayerEvents
08-05 11:27:56.281   309   309 V AwesomePlayer: setAudioSink() 
08-05 11:27:56.281   309   309 V AwesomePlayer: reset_l() 
08-05 11:27:56.281   309   309 V AudioCache: notify(0xb5474cc0, 8, 0, 0)
08-05 11:27:56.281   309   309 V AudioCache: ignored
08-05 11:27:56.281   309   309 V AwesomePlayer: cancelPlayerEvents
08-05 11:27:56.281  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {,"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:27:56.281  6981  7047 I jxcore-log: 
08-05 11:27:56.281   309   309 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-05 11:27:56.281   309   309 V AwesomePlayer: setDataSource_l dataSource
08-05 11:27:56.281   309   309 V LGParserOSAL: SniffLGParser start
08-05 11:27:56.281   309   309 V LGParserOSAL: MainType:5, SubType=0
08-05 11:27:56.281   309   309 V LGParserOSAL: #### check Mime : application/ogg
08-05 11:27:56.281   309   309 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-05 11:27:56.281   309   309 E MediaExtractor: Use LGExtractor :application/ogg 
08-05 11:27:56.282  6981  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:27:56.282  6981  7047 I jxcore-log: 
08-05 11:27:56.283  8405  8405 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-05 11:27:56.283  7862  7862 D UEI.SmartControl: QS Service created
08-05 11:27:56.284  8405  8405 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 11:27:56.284  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 11:27:56.285  6981  7047 I jxcore-log: My device name is: LGE-LG-D855
08-05 11:27:56.285  6981  7047 I jxcore-log: 
08-05 11:27:56.294  7862  7862 I UEI.SmartControl: Service initServices...
08-05 11:27:56.294  7862  7862 D UEI.SmartControl: QS start get config
08-05 11:27:56.296  8405  8405 V LGMDMManager: Create singleton instance
08-05 11:27:56.304  8376  8401 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-05 11:27:56.315   309   309 V LGParserOSAL: supported mime: application/ogg
08-05 11:27:56.315   309   309 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-05 11:27:56.315   309   309 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-05 11:27:56.315   309   309 V AwesomePlayer: mBitrate = -1 bits/sec
08-05 11:27:56.315   309   309 V AwesomePlayer: AudioTrack Setting
08-05 11:27:56.315   309   309 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-05 11:27:56.315   309   309 V AwesomePlayer: setAudioSource() 
08-05 11:27:56.315   309   309 V MediaPlayerService: prepare
08-05 11:27:56.315   309   309 V AwesomePlayer: prepareAsync_l() 
08-05 11:27:56.315   309   309 V MediaPlayerService: wait for prepare
08-05 11:27:56.315   309  8450 V AwesomePlayer: onPrepareAsyncEvent() 
08-05 11:27:56.315   309  8450 V AwesomePlayer: initAudioDecoder() 
08-05 11:27:56.315   309  8450 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 11:27:56.315   309  8450 V AudioSystem: isOffloadSupported()
08-05 11:27:56.315   309  8450 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 11:27:56.315   309  8450 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 11:27:56.315   309  8450 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 11:27:56.315   309  8450 V AwesomePlayer: getUseOffload() = 0 
08-05 11:27:56.315   309  8450 V OMXCodec: OMXCodec::Create
08-05 11:27:56.315   309  8450 V OMXCodec: findMatchingCodecs()
08-05 11:27:56.315   309  8450 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-05 11:27:56.315   309  8450 V OMXCodec: matchingCodecs.size()=1
08-05 11:27:56.315   309  8450 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-05 11:27:56.316   309  8450 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-05 11:27:56.316   309  8450 V LGCodecAdapter: LG Codec Adapter start
08-05 11:27:56.316   309  8450 V OMXCodec: OMXCodec Createtor
08-05 11:27:56.316   309  8450 V OMXCodec: setComponentRole
08-05 11:27:56.316   309  8450 V OMXCodec: configureCodec protected=0
08-05 11:27:56.316   309  8450 V LGCodecAdapter: called getLGCodecSpecificData
08-05 11:27:56.316   309  8450 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-05 11:27:56.316   309  8450 V LGCodecOSAL: Called LGconfigureCodecMETA
08-05 11:27:56.316   309  8450 V LGCodecOSAL: Called LGconfigureCodecMSG
08-05 11:27:56.316   309  8450 V LGCodecOSAL: Not support LGCodec
08-05 11:27:56.316   309  8450 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 11:27:56.316   309  8450 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-05 11:27:56.316   309  8450 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-05 11:27:56.316   309  8450 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-05 11:27:56.316   309  8450 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
,08-05 11:27:56.316   309  8450 V AudioSystem: isOffloadSupported()
08-05 11:27:56.316   309  8450 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 11:27:56.316   309  8450 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 11:27:56.316   309  8450 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-05 11:27:56.316   309  8450 V OMXCodec: init()
08-05 11:27:56.316   309  8450 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-05 11:27:56.316   309  8450 V OMXCodec: allocateBuffers
08-05 11:27:56.316   309  8450 V OMXCodec: allocateBuffersOnPort portIndex=0
08-05 11:27:56.316   309  8450 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-05 11:27:56.316   309  8450 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
08-05 11:27:56.316   309  8450 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
08-05 11:27:56.316   309  8450 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-05 11:27:56.317   309  8450 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-05 11:27:56.317   309  8450 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 11:27:56.317   309  8450 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 11:27:56.317   309  8450 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
08-05 11:27:56.317   309  8450 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-05 11:27:56.317   309  8450 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-05 11:27:56.317   309  8450 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-05 11:27:56.317   309  8450 V OMXCodec: init() mAsyncCompletion wait!!! 
08-05 11:27:56.319   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 11:27:56.319   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 11:27:56.319   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-05 11:27:56.319   309  8450 V OMXCodec: init() mAsyncCompletion wait!!! 
08-05 11:27:56.319   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-05 11:27:56.319   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-05 11:27:56.319   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-05 11:27:56.319   309  8450 V OMXCodec: init() mAsyncCompletion wait free! 
08-05 11:27:56.319   309  8450 V AwesomePlayer: finishAsyncPrepare_l() 
08-05 11:27:56.319   309  8450 V AudioCache: notify(0xb5474cc0, 5, 0, 0)
08-05 11:27:56.319   309  8450 V AudioCache: ignored
08-05 11:27:56.319   309  8450 V AudioCache: notify(0xb5474cc0, 1, 0, 0)
08-05 11:27:56.319   309  8450 V AudioCache: prepared
08-05 11:27:56.319   309   309 V AudioCache: wait - success
08-05 11:27:56.319   309   309 V MediaPlayerService: start
08-05 11:27:56.319   309   309 V AwesomePlayer: play_l() 
08-05 11:27:56.319   309   309 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-05 11:27:56.319   309   309 V AwesomePlayer: createAudioPlayer_l
08-05 11:27:56.319   309   309 V AwesomePlayer: seekAudioIfNecessary_l() 
08-05 11:27:56.319   309   309 V AwesomePlayer: startAudioPlayer_l() 
08-05 11:27:56.319   309   309 D AudioPlayer: start of Playback, useOffload 0
08-05 11:27:56.320   309   309 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 11:27:56.320   309   309 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 11:27:56.321   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-05 11:27:56.321   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_,CHANGED(1)
08-05 11:27:56.321   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-05 11:27:56.321   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-05 11:27:56.321   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-05 11:27:56.321   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 11:27:56.321   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884528
08-05 11:27:56.321   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 11:27:56.322   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-05 11:27:56.322   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 11:27:56.322   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
08-05 11:27:56.322   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 11:27:56.322   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-05 11:27:56.322   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 11:27:56.322   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-05 11:27:56.322   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 11:27:56.322   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-05 11:27:56.322   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-05 11:27:56.322   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-05 11:27:56.322  8376  8401 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-05 11:27:56.322   309  8452 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 11:27:56.322   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 11:27:56.322   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-05 11:27:56.322   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-05 11:27:56.322   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
08-05 11:27:56.323   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1420 on output port
08-05 11:27:56.323   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-05 11:27:56.323   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-05 11:27:56.324   309   309 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-05 11:27:56.325   309   309 V AudioCache: notify(0xb5474cc0, 6, 0, 0)
08-05 11:27:56.325   309   309 V AudioCache: ignored
08-05 11:27:56.325   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.325   309   309 V MediaPlayerService: wait for playback complete
08-05 11:27:56.325   309  8453 V AudioCache: memcpy(0xaf006000, 0xb0407000, 4096)
08-05 11:27:56.327   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.327   309  8453 V AudioCache: memcpy(0xaf007000, 0xb0407000, 4096)
08-05 11:27:56.327   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.327   309  8453 V AudioCache: memcpy(0xaf008000, 0xb0407000, 4096)
08-05 11:27:56.328   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.328   309  8453 V AudioCache: memcpy(0xaf009000, 0xb0407000, 4096)
08-05 11:27:56.328   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.328   309  8453 V AudioCache: memcpy(0xaf00a000, 0xb0407000, 4096)
08-05 11:27:56.328   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.328   309  8453 V AudioCache: memcpy(0xaf00b000, 0xb0407000, 4096)
08-05 11:27:,56.328   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.328   309  8453 V AudioCache: memcpy(0xaf00c000, 0xb0407000, 4096)
08-05 11:27:56.329   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.329   309  8453 V AudioCache: memcpy(0xaf00d000, 0xb0407000, 4096)
08-05 11:27:56.330   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.330   309  8453 V AudioCache: memcpy(0xaf00e000, 0xb0407000, 4096)
08-05 11:27:56.330   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.330   309  8453 V AudioCache: memcpy(0xaf00f000, 0xb0407000, 4096)
08-05 11:27:56.330   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.330   309  8453 V AudioCache: memcpy(0xaf010000, 0xb0407000, 4096)
08-05 11:27:56.330   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.330   309  8453 V AudioCache: memcpy(0xaf011000, 0xb0407000, 4096)
08-05 11:27:56.332   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.332   309  8453 V AudioCache: memcpy(0xaf012000, 0xb0407000, 4096)
08-05 11:27:56.332   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.332   309  8453 V AudioCache: memcpy(0xaf013000, 0xb0407000, 4096)
08-05 11:27:56.332   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.332   309  8453 V AudioCache: memcpy(0xaf014000, 0xb0407000, 4096)
08-05 11:27:56.332   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.332   309  8453 V AudioCache: memcpy(0xaf015000, 0xb0407000, 4096)
08-05 11:27:56.333  8376  8401 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-05 11:27:56.333   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.333   309  8453 V AudioCache: memcpy(0xaf016000, 0xb0407000, 4096)
08-05 11:27:56.333   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.333   309  8453 V AudioCache: memcpy(0xaf017000, 0xb0407000, 4096)
08-05 11:27:56.333   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.333   309  8453 V AudioCache: memcpy(0xaf018000, 0xb0407000, 4096)
08-05 11:27:56.333   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.333   309  8453 V AudioCache: memcpy(0xaf019000, 0xb0407000, 4096)
08-05 11:27:56.333  8376  8401 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-05 11:27:56.334   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.334   309  8453 V AudioCache: memcpy(0xaf01a000, 0xb0407000, 4096)
08-05 11:27:56.334   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.334   309  8453 V AudioCache: memcpy(0xaf01b000, 0xb0407000, 4096)
08-05 11:27:56.334   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.334   309  8453 V AudioCache: memcpy(0xaf01c000, 0xb0407000, 4096)
08-05 11:27:56.334   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.334   309  8453 V AudioCache: memcpy(0xaf01d000, 0xb0407000, 4096)
08-05 11:27:56.335   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.335   309  8453 V AudioCache: memcpy(0xaf01e000, 0xb0407000, 4096)
08-05 11:27:56.335   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.335   309  8453 V AudioCache: memcpy(0xaf01f000, 0xb0407000, 4096)
08-05 11:27:56.335   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.335   309  8453 V AudioCache: memcpy(0xaf020000, 0xb0407000, 4096)
08-05 11:27:56.335   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.335   309  8453 V AudioCache: memcpy(0xaf021000, 0xb0407000, 4096)
08-05 11:27:56.336   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.336   309  8453 V AudioCache: memcpy(0xaf022000, 0xb0407000, 4096)
08-05 11:27:56.336   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.336   309  8453 V AudioCache: memcpy(0xaf023000, 0xb0407000, 4096)
08-05 11:27:56.336   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.336   309  8453 V AudioCache: memcpy(0xaf024000, 0xb0407000, 4096)
08-05 11:27:56.336   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.336   309  8453 V AudioCache: memcpy(0xaf025000, 0xb0407000, 4096)
08-05 11:27:56.337   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.337   309  8453 V AudioCache: memcpy(0xaf026000, 0xb0407000, 4096)
08-05 11:27:56.337   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.337   309  8453 V AudioCache: memcpy(0xaf027000, 0xb0407000, 4096)
08-05 11:27:56.337   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.337   309  8453 V AudioCache: memcpy(0xaf028000, 0xb0407000, 4096)
08-05 11:27:56.338   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.338   309  8453 V AudioCache: memcpy(0xaf029000, 0xb0407000, 4096)
08-05 11:27:56.338   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.338   309  8453 V AudioCache: memcpy(0xaf02a000, 0xb0407000, 4096)
08-05 11:27:56.338   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.338   309  8453 V AudioCache: memcpy(0xaf02b000, 0xb0407000, 4096)
08-05 11:27:56.339   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.339   309  8453 V AudioCache: memcpy(0xaf02c000, 0xb0407000, 4096)
08-05 11:27:56.339   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.339   309  8453 V AudioCache: memcpy(0xaf02d000, 0xb0407000, 4096)
08-05 11:27:56.340   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.340   309  8453 V AudioCache: memcpy(0xaf02e000, 0xb0407000, 4096)
08-05 11:27:56.340   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.340   309  8453 V AudioCache: memcpy(0xaf02f000, 0xb0407000, 4096)
08-05 11:27:56.340   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.340   309  8453 V AudioCache: memcpy(0xaf030000, 0xb0407000, 4096)
08-05 11:27:56.341   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.341   309  8453 V AudioCache: memcpy(0xaf031000, 0xb0407000, 4096)
08-05 11:27:56.341   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.341   309  8453 V AudioCache: memcpy(0xaf032000, 0xb0407000, 4096)
08-05 11:27:56.341   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.341   309  8453 V AudioCache: memcpy(0xaf033000, 0xb0407000, 4096)
08-05 11:27:56.342   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.342   309  8453 V AudioCache: memcpy(0xaf034000, 0xb0407000, 4096)
08-05 11:27:56.342   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.342   309  8453 V AudioCache: memcpy(0xaf035000, 0xb0407000, 4096)
08-05 11:27:56.342   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.342   309  8453 V AudioCache: memcpy(0xaf036000, 0xb0407000, 4096)
08-05 11:27:56.343   309  8453 V AudioCache: write(0xb0407000, 4096)
08-05 11:27:56.343   309  8453 V AudioCache: memcpy(0xaf037000, 0xb0407000, 4096)
08-05 11:27:56.343   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-05 11:27:56.343   309  8453 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-05 11:27:56.343   309  8453 V AwesomePlayer: postAudioEOS() 
08-05 11:27:56.343   309  8453 V AudioCache: write(0xb0407000, 280)
08-05 11:27:56.343   309  8453 V AudioCache: memcpy(0xaf038000, 0xb0407000, 280)
08-05 11:27:56.344   309  8450 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-05 11:27:56.344   309  8450 V AwesomePlayer: onStreamDone
08-05 11:27:56.344   309  8450 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-05 11:27:56.344   309  8450 V AudioCache: notify(0xb5474cc0, 2, 0, 0)
08-05 11:27:56.344   309  8450 V AudioCache: playback complete
08-05 11:27:56.344   309  8450 V AwesomePlayer: pause_l() 
08-05 11:27:56.344   309   309 V AudioCache: wait - success
08-05 11:27:56.344   309  8450 V AudioCache: notify(0xb5474cc0, 7, 0, 0)
08-05 11:27:56.344   309  8450 V AudioCache: ignored
08-05 11:27:56.344   309   309 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-05 11:27:56.344   309  8450 V AwesomePlayer: cancelPlayerEvents
08-05 11:27:56.344   309  8450 D AudioPlayer: Pause Playback at 1068125
08-05 11:27:56.345   309   309 V AwesomePlayer: reset_l() 
08-05 11:27:56.345   309   309 V AudioCache: notify(0xb5474cc0, 8, 0, 0)
08-05 11:27:56.345   309   309 V AudioCache: ignored
08-05 11:27:56.345   309   309 V AwesomePlayer: cancelPlayerEvents
08-05 11:27:56.345   309   309 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-05 11:27:56.345   309   309 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-05 11:27:56.345   309   309 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-05 11:27:56.345   309   309 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-05 11:27:56.345   309   309 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 11:27:56.345  8376  8401 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c1420 on port 1
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 1
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-05 11:27:56.345   309   309 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 11:27:56.345   309   309 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 11:27:56.345  8376  8401 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-05 11:27:56.345   309  8452 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-05 11:27:56.345   309   309 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 11:27:56.345   309   309 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-05 11:27:56.346   309   309 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-05 11:27:56.346   309   309 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-05 11:27:56.346   309   309 D AudioPlayer: AudioPlayer releasing audio source
08-05 11:27:56.346   309   309 D AudioPlayer: AudioPlayer done releasing audio source
08-05 11:27:56.346   309   309 V AwesomePlayer: reset_l() 
08-05 11:27:56.346   309   309 V AwesomePlayer: cancelPlayerEvents
08-05 11:27:56.346   309   309 V AwesomePlayer: ~AwesomePlayer call
08-05 11:27:56.346   309   309 V AwesomePlayer: reset_l() 
08-05 11:27:56.346   309   309 V AwesomePlayer: cancelPlayerEvents
08-05 11:27:56.347  8405  8448 V SoundPool: close(30)
08-05 11:27:56.347  8405  8448 V SoundPool: pointer = 0xa0023000, size = 205080, sampleRate = 48000, numChannels = 2
08-05 11:27:56.347  8376  8401 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-05 11:27:56.349  8376  8401 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-05 11:27:56.350  8376  8401 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-05 11:27:56.366  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 11:27:56.366  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-05 11:27:56.368  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2702
,08-05 11:27:56.558  7862  7862 I UEI.SmartControl: Supports setup maps: true
,08-05 11:27:56.561  7862  7862 D UEI.SmartControl: QS start statue = true Error code = 0
08-05 11:27:56.561  7862  7862 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 11:27:56.561  7862  7862 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 11:27:56.562  7862  7862 I UEI.SmartControl: ### init IR Blaster...
,08-05 11:27:56.565  7862  7862 D serial_port: Configuring serial port
,08-05 11:27:56.565  7862  7862 E UEI.SmartControl: UEIBLaster setting for 616
,08-05 11:27:56.565  7862  7862 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 11:27:56.565  7862  7862 I UEI.SmartControl: configuring settings for MAXQ616
08-05 11:27:56.565  7862  7862 I UEI.SmartControl: Get version...
08-05 11:27:56.584  7862  8458 D UEI.SmartControl: serial port data available: 21
,08-05 11:27:56.611  7862  7862 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-05 11:27:56.611  7862  7862 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-05 11:27:56.611  7862  7862 I UEI.SmartControl: QS saving settings...
08-05 11:27:56.613  7862  7862 D UEI.SmartControl: IR Blaster version: 25672567
08-05 11:27:56.629  7862  8458 D UEI.SmartControl: serial port data available: 4
,08-05 11:27:56.660  7862  8464 I UEI.SmartControl: Device manager: loading config....
08-05 11:27:56.661  7862  8464 D UEI.SmartControl: ----------- loading internal config...
08-05 11:27:56.661  7862  7862 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-05 11:27:56.664  7862  7862 E UEI.SmartControl: Services init done
08-05 11:27:56.664  7862  7862 D UEI.SmartControl: QS Service init finished
,08-05 11:27:56.670  7862  7862 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 11:27:56.670  7862  7862 D UEI.SmartControl: QS Service version code: 201091
08-05 11:27:56.670  7862  7862 D UEI.SmartControl: Service requested: Control
08-05 11:27:56.675  7862  8464 E UEI.SmartControl: Loading SETTINGS...
08-05 11:27:56.676  7862  7862 D UEI.SmartControl: Request IControl service: devices are loaded...
08-05 11:27:56.677  7862  7862 D UEI.SmartControl: Internal service binding...
,08-05 11:27:56.678  8405  8405 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-05 11:27:56.680  7862  7878 I UEI.SmartControl: ------ IControl API: 11
08-05 11:27:56.680  7862  7878 D UEI.SmartControl: File observer start...
08-05 11:27:56.681  7862  7878 E UEI.SmartControl: IR Port is disabled: false
08-05 11:27:56.681  7862  7878 D UEI.SmartControl: Starting file observer...
08-05 11:27:56.681  7862  7878 I UEI.SmartControl: Registering callback...
08-05 11:27:56.689  7862  7877 I UEI.SmartControl: ------ IControl API: 19
08-05 11:27:56.694  7862  7877 I UEI.SmartControl: Registering Services Ready callback...
08-05 11:27:56.694  7862  8464 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-05 11:27:56.721  7862  8463 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 11:27:56.722  7862  8463 D UEI.SmartControl: -----service ready thread exits
08-05 11:27:56.722  8405  8425 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-05 11:27:56.723  8405  8446 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-05 11:27:56.724  8405  8446 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-05 11:27:56.725  8405  8405 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-05 11:27:56.726  8405  8405 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-05 11:27:56.726  7862  7878 I UEI.SmartControl: ------ IControl API: 8
08-05 11:27:56.727  8405  8405 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-05 11:27:56.727  8405  8405 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-05 11:27:56.727  8405  8405 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-05 11:27:56.728  8405  8405 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-05 11:27:56.730  8405  8405 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-05 11:27:56.730  8405  8405 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-05 11:27:56.734  8405  8405 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-05 11:27:56.738  8405  8405 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 11:27:56.742  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 11:27:56.743  8405  8405 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 11:27:56.744  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 11:27:56.746  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 11:27:56.748  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,08-05 11:27:56.749  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-05 11:27:56.751  8405  8405 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470389276750]
08-05 11:27:56.754  8405  8405 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-05 11:27:56.772  1036  1994 I ActivityManager: Killing 7510:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-05 11:27:56.779  8405  8466 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-05 11:27:56.851  1036  1920 W libprocessgroup: failed to open /acct/uid_10005/pid_7510/cgroup.procs: No such file or directory
,08-05 11:27:56.857  8405  8405 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-05 11:27:56.858  8405  8405 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 11:27:56.859  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-05 11:27:56.859  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-05 11:27:56.859  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-05 11:27:56.859  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-05 11:27:56.860  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-05 11:27:56.870  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-05 11:27:58.056  1036  8333 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-05 11:27:58.056  1036  8333 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-05 11:27:58.063  1939  8334 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-05 11:27:58.063  1939  8334 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
08-05 11:27:58.065  1036  1535 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-05 11:27:58.066  1036  1535 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-05 11:27:58.067  1036  1535 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-05 11:27:58.069  1036  8333 E WifiMonitor: WifiMonitor:p2p0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-05 11:27:58.069  1036  8333 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-05 11:27:58.069  1036  8333 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
,08-05 11:27:58.069  1036  8333 E WifiMonitor: WifiMonitor:p2p0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
08-05 11:27:58.069  1036  8333 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-05 11:27:58.070  1036  1534 D LGWifiP2pService: InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:58.070  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:58.070  1036  1534 D LGWifiP2pService: DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:27:58.070  1036  1535 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-05 11:27:58.070  1036  1535 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-05 11:27:58.092  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-05 11:27:58.110  7110  7110 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-05 11:27:58.896  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-05 11:27:58.896  6981  7047 I jxcore-log: 
,08-05 11:27:59.541  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-05 11:27:59.541  6981  7047 I jxcore-log: 
,08-05 11:27:59.568  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-05 11:27:59.568  6981  7047 I jxcore-log: 
,08-05 11:28:00.058  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 11:28:00.058  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:28:00.058  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:28:00.058  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:28:00.059  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 11:28:00.059  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:28:00.060  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:28:00.060  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 11:28:00.936  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-05 11:28:00.936  6981  7047 I jxcore-log: 
,08-05 11:28:01.167  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-05 11:28:01.167  6981  7047 I jxcore-log: 
,08-05 11:28:01.174  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-05 11:28:01.174  6981  7047 I jxcore-log: 
,08-05 11:28:01.191  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-05 11:28:01.191  6981  7047 I jxcore-log: 
,08-05 11:28:01.195  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-05 11:28:01.195  6981  7047 I jxcore-log: 
08-05 11:28:01.669  7862  8465 D UEI.SmartControl: Internal timer expired: 2
08-05 11:28:01.669  7862  8465 D UEI.SmartControl: unbind internal service
,08-05 11:28:01.683  7862  8459 D serial_port: close(fd = 24)
,08-05 11:28:01.687  7862  8459 I UEI.SmartControl: Serial port is closed.
08-05 11:28:02.126  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-05 11:28:02.126  6981  7047 I jxcore-log: 
,08-05 11:28:02.141  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-05 11:28:02.141  6981  7047 I jxcore-log: 
,08-05 11:28:02.151  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-05 11:28:02.151  6981  7047 I jxcore-log: 
,08-05 11:28:02.158  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-05 11:28:02.158  6981  7047 I jxcore-log: 
,08-05 11:28:02.206  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-05 11:28:02.206  6981  7047 I jxcore-log: ,
,08-05 11:28:02.262  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-05 11:28:02.262  6981  7047 I jxcore-log: 
,08-05 11:28:02.271  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-05 11:28:02.271  6981  7047 I jxcore-log: 
,08-05 11:28:02.439  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-05 11:28:02.439  6981  7047 I jxcore-log: 
,08-05 11:28:02.466  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-05 11:28:02.466  6981  7047 I jxcore-log: 
,08-05 11:28:02.472  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-05 11:28:02.472  6981  7047 I jxcore-log: 
,08-05 11:28:02.477  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-05 11:28:02.477  6981  7047 I jxcore-log: 
,08-05 11:28:02.495  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-05 11:28:02.495  6981  7047 I jxcore-log: 
,08-05 11:28:02.578  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-05 11:28:02.578  6981  7047 I jxcore-log: 
,08-05 11:28:02.591  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-05 11:28:02.591  6981  7047 I jxcore-log: 
,08-05 11:28:02.619  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-05 11:28:02.619  6981  7047 I jxcore-log: 
,08-05 11:28:02.631  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-05 11:28:02.631  6981  7047 I jxcore-log: 
,08-05 11:28:02.649  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-05 11:28:02.649  6981  7047 I jxcore-log: 
,08-05 11:28:02.684  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-05 11:28:02.684  6981  7047 I jxcore-log: 
,08-05 11:28:02.690  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-05 11:28:02.690  6981  7047 I jxcore-log: 
,08-05 11:28:02.896  6981  7047 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-05 11:28:02.896  6981  7047 I jxcore-log: 
,08-05 11:28:02.905  6981  7047 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-05 11:28:02.906  6981  7047 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-05 11:28:02.906  6981  7047 I jxcore-log: 
,08-05 11:28:04.716  1036  1535 E WifiStateMachine:  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):4 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:24002] from screen [on:0 period:1510469483]
08-05 11:28:04.718  1036  1535 E WifiStateMachine:  ConnectModeState CMD_START_SCAN -2 -2 ic=1 proc(ms):7 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1510469486]
,08-05 11:28:04.733  1036  1377 V AlarmManager: RTC_WAKEUP set : Alarm{201e1a1 type 0 when 1470389274723 android} when 1470389274723
08-05 11:28:04.750  1036  1377 V AlarmManager: RTC_WAKEUP set : Alarm{123e7b87 type 0 when 1470389269284 com.google.android.gms} when 1470389269284
,08-05 11:28:04.769  1036  1535 E WifiStateMachine:  DriverStartedState CMD_START_SCAN -2 -2 ic=1 proc(ms):58 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:51] from screen [on:0 period:1510469537]
08-05 11:28:04.769  1036  1535 D WifiNative-wlan0: doBoolean: SCAN
08-05 11:28:04.770  8274  8274 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-05 11:28:04.773  1036  8333 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-05 11:28:04.774  1036  8333 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-05 11:28:04.774  1036  8333 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-05 11:28:04.774  1036  8333 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-05 11:28:04.775  1036  1535 D WifiNative-wlan0: SCAN: returned true
08-05 11:28:04.777  8405  8405 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-05 11:28:04.777  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2702
08-05 11:28:04.807  2610  2610 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 11:28:04.844  8405  8405 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-05 11:28:04.846  8405  8405 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2702
,08-05 11:28:04.869  1815  8473 I CheckinService: active receiver: enabled
,08-05 11:28:05.057  2079  2079 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-05 11:28:05.098  1036  1884 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8485 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-05 11:28:05.173  8485  8485 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:28:05.173  8485  8485 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 11:28:05.175  8485  8485 D PhoneMonitor: Register our PhoneStateListener
,08-05 11:28:05.187  1036  1051 I ActivityManager: Killing 7966:com.google.android.talk/u0a72 (adj 15): empty #17
,08-05 11:28:05.196  8485  8485 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-05 11:28:05.197  8485  8485 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-05 11:28:05.197  8485  8485 D TelephonyAutoProfiling: [parse] Load xml
08-05 11:28:05.199  8485  8485 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-05 11:28:05.199  8485  8485 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,08-05 11:28:05.199  8485  8485 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
,08-05 11:28:05.199  8485  8485 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-05 11:28:05.199  8485  8485 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-05 11:28:05.199  8485  8485 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
,08-05 11:28:05.199  8485  8485 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-05 11:28:05.199  8485  8485 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-05 11:28:05.199  8485  8485 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-05 11:28:05.199  8485  8485 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-05 11:28:05.199  8485  8485 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-05 11:28:05.199  8485  8485 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-05 11:28:05.199  8485  8485 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-05 11:28:05.199  8485  8485 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-05 11:28:05.199  8485  8485 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-05 11:28:05.199  8485  8485 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-05 11:28:05.199  8485  8485 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-05 11:28:05.204  8485  8485 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-05 11:28:05.253  1036  1885 W libprocessgroup: failed to open /acct/uid_10072/pid_7966/cgroup.procs: No such file or directory
,08-05 11:28:08.331  1036  8333 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-05 11:28:08.331  1036  8333 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-05 11:28:08.343  1036  1535 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=9 known=0 got=9 bcn=0
,08-05 11:28:08.345  1036  1535 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=9 known=0 got=9 bcn=0
08-05 11:28:08.346  1036  1535 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=9 known=0 got=9 bcn=0
08-05 11:28:08.348  1036  1535 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=9 known=0 got=9 bcn=0
08-05 11:28:08.348  1036  1535 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-05 11:28:08.355  1939  8334 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-05 11:28:08.355  1939  8334 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
08-05 11:28:08.357  1036  8333 E WifiMonitor: WifiMonitor:p2p0 cnt=59 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-05 11:28:08.357  1036  8333 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-05 11:28:08.357  1036  8333 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
08-05 11:28:08.357  1036  8333 E WifiMonitor: WifiMonitor:p2p0 cnt=60 dispatchEvent: WPS-AP-AVAILABLE 
08-05 11:28:08.357  1036  8333 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-05 11:28:08.358  1036  1534 D LGWifiP2pService: InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:28:08.358  1036  1534 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:28:08.358  1036  1534 D LGWifiP2pService: DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:28:08.359  1036  1535 D WifiNative-wlan0: doString: [BSS RANGE=48- MASK=0x21987]
08-05 11:28:08.378  7110  7110 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-05 11:28:08.387  7110  7110 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-05 11:28:10.561  1602  1602 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-05 11:28:10.562  1602  1602 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-05 11:28:10.583  1939  2073 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-05 11:28:10.583  1939  2073 D LEDHandler: Battery Level Remaining: 100%
08-05 11:28:10.583  1939  2073 D LEDHandler: Battery Temp: 293, mChargingStatus=5, mChargingStop=false
,08-05 11:28:10.585  1602  1602 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
08-05 11:28:10.586  1602  1602 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-05 11:28:10.586  1036  1543 D WifiController: battery changed pluggedType: 2
08-05 11:28:10.588  1602  1602 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-05 11:28:10.591  7926  8150 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 11:28:10.592  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:28:10.592  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:28:10.594  8358  8358 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-05 11:28:15.087  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-05 11:28:15.111  1036  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 11:28:15.195  1036  1111 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8516 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-05 11:28:15.204  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-05 11:28:15.205  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-05 11:28:15.218  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-05 11:28:15.230  1036  1036 D administrator: Handling package changes for user 0
,08-05 11:28:15.254  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 11:28:15.280  8516  8516 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-05 11:28:15.355  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-05 11:28:15.355  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-05 11:28:15.359  8516  8516 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:28:15.359  8516  8516 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 11:28:15.413  1036  1109 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 11:28:15.421  1036  1109 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-05 11:28:15.429  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-05 11:28:15.430  2448  2448 V GmsNetworkLocationProvi: DISABLE
08-05 11:28:15.453  8516  8559 I Babel   : MmsConfig: mnc/mcc: 0/0
08-05 11:28:15.453  8516  8559 I Babel   : MmsConfig.loadMmsSettings
,08-05 11:28:15.459  2448  2448 E GCoreFlp: Bound FusedProviderService with LocationManager
08-05 11:28:15.465  8516  8559 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 11:28:15.465  8516  8559 I Babel   : MmsConfig.loadFromDatabase
,08-05 11:28:15.472  8516  8559 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-05 11:28:15.473  8516  8559 I Babel   : MmsConfig.loadFromResources
08-05 11:28:15.474  8516  8559 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-05 11:28:15.475  8516  8559 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-05 11:28:15.488  8516  8516 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 11:28:15.497  8516  8558 W AudioCapabilities: Unsupported mime audio/evrc
08-05 11:28:15.500  8516  8558 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 11:28:15.502  8516  8558 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-05 11:28:15.503  1815  8563 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-05 11:28:15.503  1815  8563 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-05 11:28:15.503  7299  7299 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 11:28:15.510  7299  7299 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@22e5aa92
08-05 11:28:15.510  7299  7299 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 11:28:15.510  7299  7299 D AppUp4:CustFacade: isPhone : true
08-05 11:28:15.511  7299  7299 D AppUp4:CustModeStarterReceiver: begin check event
08-05 11:28:15.511  7299  7299 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-05 11:28:15.513  1815  5221 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-05 11:28:15.516  1036  1109 D LocationProviderProxy: applying state to connected service
08-05 11:28:15.522  8516  8558 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-05 11:28:15.529  8516  8558 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 11:28:15.534  8516  8558 W AudioCapabilities: Unsupported mime audio/evrc
08-05 11:28:15.535  1036  1643 I ActivityManager: Killing 8088:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-05 11:28:15.547  8516  8558 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-05 11:28:15.548  8516  8558 W VideoCapabilities: Unsupported mime video/divx
,08-05 11:28:15.550  8516  8558 W VideoCapabilities: Unsupported mime video/divx311
08-05 11:28:15.551  8516  8558 W VideoCapabilities: Unsupported mime video/divx4
08-05 11:28:15.553  8516  8558 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-05 11:28:15.563  8516  8558 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-05 11:28:15.565  8516  8558 W AudioCapabilities: Unsupported mime audio/eac3
08-05 11:28:15.566  8516  8558 W AudioCapabilities: Unsupported mime audio/ac3
08-05 11:28:15.567  8516  8558 W AudioCapabilities: Unsupported mime audio/g726
08-05 11:28:15.567  8516  8558 W AudioCapabilities: Unsupported mime audio/wma-voice
08-05 11:28:15.568  8516  8558 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-05 11:28:15.569  8516  8558 W AudioCapabilities: Unsupported mime audio/adpcm
08-05 11:28:15.570  8516  8558 W VideoCapabilities: Unsupported mime video/theora
08-05 11:28:15.571  8516  8558 W VideoCapabilities: Unsupported mime video/mjpg
08-05 11:28:15.581  1036  1993 W libprocessgroup: failed to open /acct/uid_10080/pid_8088/cgroup.procs: No such file or directory
,08-05 11:28:15.582  5053  8566 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-05 11:28:15.611  1036  2030 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8567 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-05 11:28:15.663  8567  8567 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-05 11:28:15.677  8567  8567 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-05 11:28:15.677  8567  8567 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-05 11:28:15.677  8567  8567 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-05 11:28:15.677  8567  8567 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-05 11:28:15.677  8567  8567 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-05 11:28:15.677  8567  8567 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-05 11:28:15.688  1036  1052 I ActivityManager: Killing 7730:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-05 11:28:15.772  1036  1695 W libprocessgroup: failed to open /acct/uid_10037/pid_7730/cgroup.procs: No such file or directory
,08-05 11:28:15.919  1036  1994 V SIM_STK : Menu title from STK is T-Mobile
,08-05 11:28:15.927  5053  8566 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 344 ms] updated apps [took 344 ms] 
,08-05 11:28:17.683  1036  1535 E WifiStateMachine:  DisconnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 11:28:17.684  1036  1535 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 11:28:17.685  1036  1535 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 11:28:17.686  1036  1535 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 11:28:17.688  1036  1535 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-05 11:29:00.036  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 11:29:00.036  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-05 11:29:00.036  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:29:00.037  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:29:00.052  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 11:29:00.053  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:29:00.060  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:29:00.061  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 11:29:10.723  1602  1602 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-05 11:29:10.723  1602  1602 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-05 11:29:10.748  1036  1543 D WifiController: battery changed pluggedType: 2
,08-05 11:29:10.751  1602  1602 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
08-05 11:29:10.752  1939  2073 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-05 11:29:10.753  1939  2073 D LEDHandler: Battery Level Remaining: 100%
08-05 11:29:10.753  1939  2073 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
08-05 11:29:10.755  1602  1602 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-05 11:29:10.756  1602  1602 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-05 11:29:10.759  7926  8150 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 11:29:10.760  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:29:10.760  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:29:10.763  8358  8358 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-05 11:30:00.060  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 11:30:00.060  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:30:00.060  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-05 11:30:00.061  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:30:00.077  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 11:30:00.077  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:30:00.082  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-05 11:30:00.084  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 11:30:01.834  1036  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=846547016, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-05 11:30:01.901  1036  1111 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8599 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-05 11:30:01.940  2610  2610 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 11:30:02.078  8599  8599 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-05 11:30:02.088  8599  8599 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2969cac7
08-05 11:30:02.088  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=846547016 [*alarm*], flags=0x0
08-05 11:30:02.090  1036  2030 I ActivityManager: Killing 7182:com.lge.settings.easy/1000 (adj 15): empty #17
,08-05 11:30:02.110  1036  1885 W libprocessgroup: failed to open /acct/uid_1000/pid_7182/cgroup.procs: No such file or directory
,08-05 11:31:00.058  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 11:31:00.058  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:31:00.058  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-05 11:31:00.067  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
08-05 11:31:00.075  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 11:31:00.075  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:31:00.077  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:31:00.082  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 11:31:24.931  1036  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=846547016, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-05 11:31:24.960  1036  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{32827270 type 2 when 563196 com.google.android.gms} when 563196
,08-05 11:31:24.997  2610  2610 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 11:31:25.031  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=846547016 [*alarm*], flags=0x0
,08-05 11:32:00.057  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 11:32:00.057  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:32:00.057  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:32:00.058  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:32:00.074  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-05 11:32:00.074  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:32:00.076  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-05 11:32:00.078  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 11:32:54.783  1036  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=846547016, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-05 11:32:54.853  2610  2610 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 11:32:54.886  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=846547016 [*alarm*], flags=0x0
,08-05 11:33:00.054  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 11:33:00.055  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:33:00.055  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:33:00.055  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:33:00.070  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 11:33:00.070  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:33:00.072  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:33:00.074  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 11:33:00.800  1036  1052 I ActivityManager: Killing 8276:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-05 11:33:00.833  1036  2049 W libprocessgroup: failed to open /acct/uid_10026/pid_8276/cgroup.procs: No such file or directory
,08-05 11:34:00.052  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 11:34:00.052  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:34:00.053  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-05 11:34:00.053  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:34:00.070  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-05 11:34:00.070  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:34:00.072  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:34:00.074  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 11:35:00.056  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 11:35:00.056  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:35:00.056  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:35:00.057  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:35:00.072  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-05 11:35:00.072  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:35:00.075  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:35:00.077  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 11:36:00.091  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 11:36:00.091  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:36:00.091  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:36:00.092  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:36:00.107  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 11:36:00.108  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:36:00.110  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:36:00.112  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 11:36:11.840  1602  1602 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-05 11:36:11.840  1602  1602 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-05 11:36:11.858  1939  2073 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-05 11:36:11.858  1939  2073 D LEDHandler: Battery Level Remaining: 100%
08-05 11:36:11.858  1939  2073 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,08-05 11:36:11.861  1602  1602 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
08-05 11:36:11.861  1602  1602 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-05 11:36:11.864  1036  1543 D WifiController: battery changed pluggedType: 2
08-05 11:36:11.865  1602  1602 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-05 11:36:11.869  7926  8150 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 11:36:11.870  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:36:11.870  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 11:36:11.875  8358  8358 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-05 11:37:00.099  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 11:37:00.099  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:37:00.099  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:37:00.100  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:37:00.115  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 11:37:00.115  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:37:00.117  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:37:00.121  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 11:38:00.114  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 11:38:00.114  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:38:00.114  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:38:00.115  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:38:00.130  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-05 11:38:00.130  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:38:00.134  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-05 11:38:00.141  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 11:39:00.061  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 11:39:00.061  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:39:00.061  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:39:00.062  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:39:00.077  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 11:39:00.077  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:39:00.081  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-05 11:39:00.084  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 11:40:00.056  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 11:40:00.057  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:40:00.057  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:40:00.057  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:40:00.073  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-05 11:40:00.073  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:40:00.075  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:40:00.077  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 11:41:00.054  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 11:41:00.055  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:41:00.055  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:41:00.055  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:41:00.071  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 11:41:00.071  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:41:00.078  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-05 11:41:00.082  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 11:41:22.946  1036  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=846547016, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-05 11:41:22.962  1036  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{330909e9 type 2 when 999876 com.google.android.gms} when 999876
08-05 11:41:22.991   303  8658 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-05 11:41:22.995  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 11:41:23.009  2610  2610 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 11:41:23.040  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=846547016 [*alarm*], flags=0x0
,08-05 11:42:00.062  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 11:42:00.063  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:42:00.063  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:42:00.063  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:42:00.078  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-05 11:42:00.078  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:42:00.084  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-05 11:42:00.090  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 11:42:21.795  1036  1109 I UsageStatsService: User[0] Flushing usage stats to disk
,08-05 11:42:51.764  1036  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=846547016, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-05 11:42:51.786  1036  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{f14666e type 2 when 1250029 com.android.bluetooth} when 1250029
,08-05 11:42:51.792  7926  8172 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:42:51.792  7926  8172 W bt-smp  : Plain text(LSB ~ MSB) = 6f 6f 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:42:51.792  7926  8172 W bt-smp  : Encrypted text(LSB ~ MSB) = 9a ed 66 88 41 4b f6 f9 63 f3 dc 3b c1 4f eb a8 
08-05 11:42:51.793  7926  8172 W bt-btm  : Stopping oneshot timer
08-05 11:42:51.827  2610  2610 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 11:42:51.857  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=846547016 [*alarm*], flags=0x0
,08-05 11:43:00.062  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 11:43:00.062  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:43:00.062  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-05 11:43:00.063  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:43:00.079  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-05 11:43:00.080  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:43:00.085  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-05 11:43:00.091  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 11:44:00.063  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 11:44:00.063  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-05 11:44:00.063  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:44:00.064  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:44:00.080  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-05 11:44:00.080  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:44:00.082  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-05 11:44:00.084  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 11:45:00.055  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 11:45:00.055  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:45:00.055  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:45:00.056  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:45:00.071  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-05 11:45:00.071  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:45:00.073  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:45:00.075  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 11:45:01.083  1036  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=846547016, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-05 11:45:01.108  8599  8599 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-05 11:45:01.113  8599  8599 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2969cac7
08-05 11:45:01.136  2610  2610 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 11:45:01.167  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=846547016 [*alarm*], flags=0x0
,08-05 11:46:00.054  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 11:46:00.054  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:46:00.055  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:46:00.055  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:46:00.070  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 11:46:00.075  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:46:00.077  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-05 11:46:00.082  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 11:47:00.062  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 11:47:00.063  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-05 11:47:00.063  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:47:00.063  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:47:00.079  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-05 11:47:00.080  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-05 11:47:00.082  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:47:00.084  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 11:48:00.094  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 11:48:00.094  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-05 11:48:00.094  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-05 11:48:00.095  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:48:00.116  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 11:48:00.116  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:48:00.118  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:48:00.122  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 11:49:00.061  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 11:49:00.061  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:49:00.062  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:49:00.062  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:49:00.080  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-05 11:49:00.080  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:49:00.081  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-05 11:49:00.081  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 11:50:00.053  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 11:50:00.053  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:50:00.053  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:50:00.054  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1400000ms)
```
