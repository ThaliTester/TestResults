#### Test 78968685940d272_thali05_LGE-LG-D855 Logs


```
--------- beginning of system
07-27 09:39:21.259  1049  1885 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6627 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
--------- beginning of main
07-27 09:39:21.269  1049  2028 V SIM_STK : Menu title from STK is T-Mobile
,07-27 09:39:21.471  4576  6626 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 259 ms] updated apps [took 259 ms] 
07-27 09:39:21.538  6627  6627 D DocsApplication: Installing DEX configuration.
07-27 09:39:21.558  6627  6627 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
07-27 09:39:21.563  6627  6627 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{3c53c566 com.google.android.apps.docs}
07-27 09:39:21.579  6627  6627 D TAG     : onCreate()
07-27 09:39:21.604  6627  6627 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
07-27 09:39:21.689  6655  6655 D AndroidRuntime: 
07-27 09:39:21.689  6655  6655 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 09:39:21.694  6655  6655 D AndroidRuntime: CheckJNI is OFF
07-27 09:39:21.901  6655  6655 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 09:39:21.909  1049  2047 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 09:39:21.925  1957  1972 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-27 09:39:21.929  1049  2047 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-27 09:39:21.930  1049  2047 D ActivityManager: setTaskToReturnTo : TaskRecord{348aca4b #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-27 09:39:21.931  1049  2047 D ActivityManager: setTaskToReturnTo : TaskRecord{348aca4b #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-27 09:39:21.932  1049  2047 D WindowStateEx: AppWindowTokenEx init.. 
07-27 09:39:21.933   333   355 E GBMv2   : DFP En is all cleared set to be enabled
07-27 09:39:21.983  1049  2047 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6674 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-27 09:39:21.985  6655  6655 D AndroidRuntime: Shutting down VM
07-27 09:39:22.003  6417  6445 D AlertService: Beginning updateAlertNotification
07-27 09:39:22.048  1957  1972 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-27 09:39:22.048  1957  1972 D SplitWindowPolicy: topRunningActivity=ActivityInfo{361311c2 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-27 09:39:22.049  1957  1973 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-27 09:39:22.049  1957  1973 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1393dbd3 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-27 09:39:22.050  6417  6445 D AlertService: No fired or scheduled alerts
07-27 09:39:22.074  6417  6445 D AlertService: Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
07-27 09:39:22.100  6417  6445 D AlarmScheduler: No events found starting within 1 week.
07-27 09:39:22.102  6674  6674 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-27 09:39:22.117  1049  1939 I ActivityManager: Killing 5383:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,07-27 09:39:22.206  6674  6674 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
07-27 09:39:22.218  1049  1921 W libprocessgroup: failed to open /acct/uid_10046/pid_5383/cgroup.procs: No such file or directory
07-27 09:39:22.229  6674  6674 I LibraryLoader: Loading: webviewchromium
07-27 09:39:22.233  6674  6674 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 651-656)
07-27 09:39:22.233  6674  6674 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 09:39:22.265  6674  6674 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d57c6c0}
07-27 09:39:22.267  6674  6674 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 09:39:22.267  6674  6674 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 09:39:22.279  6674  6674 I BrowserStartupController: Initializing chromium process, renderers=0
07-27 09:39:22.280  6674  6674 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 09:39:22.293   306  1401 V AudioPolicyService: registerClient() client 0xb1025e40, uid 10118
07-27 09:39:22.298  6674  6674 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-27 09:39:22.300  1049  1125 D BluetoothManagerService: Message: 20
07-27 09:39:22.300  1049  1125 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f80a772:true
07-27 09:39:22.300  6674  6674 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
07-27 09:39:22.301  6674  6674 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
07-27 09:39:22.316  6674  6674 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 09:39:22.316  6674  6674 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 09:39:22.316  6674  6674 I Adreno-EGL: Build Date: 12/12/14 금
07-27 09:39:22.316  6674  6674 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 09:39:22.316  6674  6674 I Adreno-EGL: Remote Branch: 
07-27 09:39:22.316  6674  6674 I Adreno-EGL: Local Patches: 
07-27 09:39:22.316  6674  6674 I Adreno-EGL: Reconstruct Branch: 
07-27 09:39:22.422  6674  6710 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-27 09:39:22.430  6674  6674 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-27 09:39:22.448  6674  6674 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 09:39:22.453  6674  6674 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-27 09:39:22.456  6674  6674 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-27 09:39:22.459  6674  6674 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-27 09:39:22.460  6674  6674 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-27 09:39:22.471  1832  4737 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
07-27 09:39:22.474  6674  6674 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-27 09:39:22.481  6674  6674 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 09:39:22.481  6674  6674 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 09:39:22.508  1832  4737 D Icing   : Loaded CLD2 Version V2.0 - 20140131
07-27 09:39:22.518  6674  6722 D OpenGLRenderer: Render dirty regions requested: true
07-27 09:39:22.518  6674  6722 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 09:39:22.525  6674  6722 D OpenGLRenderer: Enabling debug mode 0
07-27 09:39:22.532  6674  6674 D Atlas   : Validating map...
07-27 09:39:22.537  1049  2048 D SplitWindow: check instance of lgWin Window{1d3a149c u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 09:39:22.547  1049  1106 W ActivityManager: Activity pause timeout for ActivityRecord{29bd2c28 u0 com.test.thalitest/.MainActivity t40}
07-27 09:39:22.553  1832  4737 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
07-27 09:39:22.582  6674  6720 D LgDataFeature: LgDataFeature() Constructor: none
07-27 09:39:22.583  6674  6720 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 09:39:22.654  1049  1126 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +607ms (total +717ms)
07-27 09:39:22.655  1049  1126 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{29bd2c28 u0 com.test.thalitest/.MainActivity t40} time:91078
07-27 09:39:22.655  6674  6674 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@143e3c8f time:91078
07-27 09:39:22.773  6674  6674 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-27 09:39:22.793  6674  6674 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-27 09:39:22.793  6674  6674 I chromium: 
07-27 09:39:22.827  6674  6720 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-27 09:39:22.827  6674  6720 I chromium: 
07-27 09:39:22.970  6674  6733 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435058176
07-27 09:39:22.983  6674  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 09:39:22.983  6674  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 09:39:22.983  6674  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 09:39:22.983  6674  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 09:39:22.983  6674  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 09:39:22.984  6674  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d6e2c23 added. We now have 1 listener(s)
07-27 09:39:22.985  1049  2048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 09:39:22.990  6674  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-27 09:39:22.991  6674  6733 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 09:39:22.992  6674  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 09:39:22.993  6674  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 09:39:22.999  6674  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 09:39:22.999  6674  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 09:39:22.999  6674  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 09:39:22.999  6674  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-27 09:39:22.999  6674  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 09:39:22.999  6674  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 09:39:22.999  6674  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 09:39:22.999  6674  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 09:39:22.999  6674  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 09:39:22.999  6674  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 09:39:22.999  6674  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 09:39:22.999  6674  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6a109e added. We now have 1 listener(s)
07-27 09:39:23.000  6674  6733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 09:39:23.005  1049  1558 D WifiService: New client listening to asynchronous messages
07-27 09:39:23.009  6674  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-27 09:39:23.013  6674  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-27 09:39:23.013  6674  6733 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-27 09:39:23.016  6674  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 09:39:23.018  1049  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 09:39:23.019  6674  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-27 09:39:23.026  6674  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 09:39:23.026  6674  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 09:39:23.026  6674  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 09:39:23.026  6674  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 09:39:23.026  6674  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 09:39:23.026  6674  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 09:39:23.026  6674  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 09:39:23.026  6674  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 09:39:23.026  6674  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 09:39:23.026  6674  6733 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 09:39:23.027  6674  6733 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 09:39:23.032  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 09:39:23.034  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 09:39:23.081  6674  6674 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 09:39:23.405   333   357 E GBMv2   : DFP En is all cleared set to be enabled
07-27 09:39:23.405   333   357 E GBMv2   : Set value is all cleared set the max
,07-27 09:39:23.405   333   357 I GBMv2   : DFP Enabled. Ignore VFP set
07-27 09:39:23.437   321   321 E ThermalEngine: out low battery limit. 
,07-27 09:39:23.491  6627  6627 D LgDataFeature: LgDataFeature() Constructor: none
,07-27 09:39:23.491  6627  6627 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 09:39:23.704  6246  6246 I LockScreenSettings: New app installed broadcast received ..
07-27 09:39:23.707  6246  6246 I LockScreenSettings: Number of installed packages  1
,07-27 09:39:23.711  6627  6627 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-27 09:39:23.773  1049  2028 V SIM_STK : Menu title from STK is T-Mobile
,07-27 09:39:23.825  1049  1975 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6759 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-27 09:39:23.904  6759  6759 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
07-27 09:39:23.904  6759  6759 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,07-27 09:39:23.939  1049  2047 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6776 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-27 09:39:23.940  1049  2047 I ActivityManager: Killing 5803:com.google.android.gm/u0a64 (adj 15): empty #17
07-27 09:39:23.997  1049  1975 W libprocessgroup: failed to open /acct/uid_10064/pid_5803/cgroup.procs: No such file or directory
,07-27 09:39:24.001  6674  6739 W jxcore-log: Initializing JXcore engine
07-27 09:39:24.002  6674  6739 W jxcore-log: JXcore engine is ready
07-27 09:39:24.037  6739  6739 W Thread-767: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9331]" dev="sockfs" ino=9331 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-27 09:39:24.037  6739  6739 W Thread-767: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-27 09:39:24.037  6739  6739 W Thread-767: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[9410]" dev="sockfs" ino=9410 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-27 09:39:24.037  6739  6739 W Thread-767: type=1400 audit(0.0:169): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-27 09:39:24.037  6739  6739 W Thread-767: type=1400 audit(0.0:170): avc: denied { ioctl } for path="socket:[32017]" dev="sockfs" ino=32017 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,07-27 09:39:24.059  6776  6776 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
07-27 09:39:24.060  6674  6739 W jxcore-log: Starting JXcore engine
07-27 09:39:24.082  6776  6776 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-27 09:39:24.087  6497  6497 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
07-27 09:39:24.121  6371  6371 D CalendarProviderBroadcastReceiver: Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
07-27 09:39:24.122  6371  6371 D CalendarProviderBroadcastReceiver: [IntentService] WakeLock acquire, start IntentSerivce
,07-27 09:39:24.129  6497  6497 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
07-27 09:39:24.131  6371  6371 D CalendarProvider2: CalendarProviderIntentService.onCreate()
07-27 09:39:24.131  6371  6794 D CalendarProvider2: Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
07-27 09:39:24.132  6371  6794 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
07-27 09:39:24.137  6371  6794 E SQLiteLog: (284) automatic index on view_events(_id)
,07-27 09:39:24.143  6674  6739 W jxcore-log: Platform android
07-27 09:39:24.143  6674  6739 W jxcore-log: 
07-27 09:39:24.143  6674  6739 W jxcore-log: Process ARCH arm
07-27 09:39:24.143  6674  6739 W jxcore-log: 
07-27 09:39:24.156  6371  6794 D CalendarProvider2: [IntentService] Release Lock
,07-27 09:39:24.158  6371  6371 D CalendarProvider2: CalendarProviderIntentService.onDestroy()
07-27 09:39:24.159  1049  1975 I ActivityManager: Killing 5648:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
07-27 09:39:24.177  5623  5623 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,07-27 09:39:24.178  5623  5623 W System.err: android.os.DeadObjectException
07-27 09:39:24.178  5623  5623 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 09:39:24.178  5623  5623 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 09:39:24.178  5623  5623 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-27 09:39:24.178  5623  5623 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-27 09:39:24.178  5623  5623 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-27 09:39:24.178  5623  5623 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-27 09:39:24.178  5623  5623 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 09:39:24.178  5623  5623 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 09:39:24.178  5623  5623 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 09:39:24.178  5623  5623 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 09:39:24.178  5623  5623 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 09:39:24.179  5623  5623 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 09:39:24.179  5623  5623 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 09:39:24.179  5623  5623 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 09:39:24.179  5623  5623 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-27 09:39:24.179  5623  5623 W System.err: android.os.DeadObjectException
07-27 09:39:24.179  5623  5623 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 09:39:24.179  5623  5623 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 09:39:24.179  5623  5623 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-27 09:39:24.180  5623  5623 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-27 09:39:24.180  5623  5623 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-27 09:39:24.180  5623  5623 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-27 09:39:24.180  5623  5623 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 09:39:24.180  5623  5623 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 09:39:24.180  5623  5623 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 09:39:24.180  5623  5623 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 09:39:24.180  5623  5623 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 09:39:24.180  5623  5623 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 09:39:24.180  5623  5623 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 09:39:24.180  5623  5623 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 09:39:24.180  5623  5623 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-27 09:39:24.181  5623  5623 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
07-27 09:39:24.306  6674  6739 I jxcore-log: JXcore Cordova bridge is ready!
07-27 09:39:24.306  6674  6739 I jxcore-log: 
07-27 09:39:24.307  6674  6739 W jxcore-log: JXcore engine is started
,07-27 09:39:24.322  6674  6733 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 09:39:24.329  6674  6674 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-27 09:39:24.458  1049  1396 W libprocessgroup: failed to open /acct/uid_1000/pid_5648/cgroup.procs: No such file or directory
,07-27 09:39:24.458  1049  1396 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
07-27 09:39:24.462  5623  5623 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-27 09:39:24.462  5623  5623 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-27 09:39:24.513  1049  1921 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6799 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 09:39:24.513  5623  5623 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-27 09:39:24.586  6799  6799 D UEI.SmartControl: Quickset Services start...
,07-27 09:39:24.594  6799  6799 I UEI.SmartControl: Manufacture = LGE
07-27 09:39:24.595  6799  6799 D UEI.SmartControl: Id = LGNevo
07-27 09:39:24.596  6799  6799 D UEI.SmartControl: File observer start...
07-27 09:39:24.596  6799  6799 E UEI.SmartControl: IR Port is disabled: false
07-27 09:39:24.596  6799  6799 D UEI.SmartControl: Starting file observer...
07-27 09:39:24.597  6799  6799 D UEI.SmartControl: Extracting JNI libs...
07-27 09:39:24.597  6799  6799 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-27 09:39:24.654  6799  6799 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-27 09:39:24.654  6799  6799 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-27 09:39:24.654  6799  6799 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-27 09:39:24.681  6799  6799 I UEI.SmartControl: --- Selecting new region: 6
07-27 09:39:24.683  6799  6799 I UEI.SmartControl: Model = LG-D855
,07-27 09:39:24.685  6799  6799 D UEI.SmartControl: QS Service created
07-27 09:39:24.700  6799  6799 I UEI.SmartControl: Service initServices...
,07-27 09:39:24.705  6799  6799 D UEI.SmartControl: QS start get config
07-27 09:39:24.756  6799  6799 D UEI.SmartControl: Loading JNI Libs...
,07-27 09:39:24.777  1049  2047 I art     : Explicit concurrent mark sweep GC freed 17200(881KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.301ms total 123.321ms
,07-27 09:39:25.034  6799  6799 I UEI.SmartControl: Supports setup maps: true
07-27 09:39:25.038  6799  6799 D UEI.SmartControl: QS start statue = true Error code = 0
,07-27 09:39:25.038  6799  6799 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-27 09:39:25.038  6799  6799 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-27 09:39:25.038  6799  6799 I UEI.SmartControl: ### init IR Blaster...
07-27 09:39:25.044  6799  6799 D serial_port: Configuring serial port
07-27 09:39:25.047  6799  6799 E UEI.SmartControl: UEIBLaster setting for 616
07-27 09:39:25.047  6799  6799 I UEI.SmartControl: Setting serial record hearder size = 2
07-27 09:39:25.047  6799  6799 I UEI.SmartControl: configuring settings for MAXQ616
07-27 09:39:25.048  6799  6799 I UEI.SmartControl: Get version...
07-27 09:39:25.065  6799  6831 D UEI.SmartControl: serial port data available: 21
,07-27 09:39:25.093  6799  6799 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-27 09:39:25.094  6799  6799 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-27 09:39:25.094  6799  6799 I UEI.SmartControl: QS saving settings...
,07-27 09:39:25.096  6799  6799 D UEI.SmartControl: IR Blaster version: 25672567
07-27 09:39:25.113  6799  6831 D UEI.SmartControl: serial port data available: 4
,07-27 09:39:25.149  6799  6837 I UEI.SmartControl: Device manager: loading config....
07-27 09:39:25.150  6799  6837 D UEI.SmartControl: ----------- loading internal config...
07-27 09:39:25.151  6799  6799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-27 09:39:25.153  6799  6799 E UEI.SmartControl: Services init done
07-27 09:39:25.154  6799  6799 D UEI.SmartControl: QS Service init finished
07-27 09:39:25.157  6799  6799 D UEI.SmartControl: QS Service version name: 2.1.91
07-27 09:39:25.158  6799  6799 D UEI.SmartControl: QS Service version code: 201091
07-27 09:39:25.164  6799  6799 D UEI.SmartControl: Service requested: Control
07-27 09:39:25.169  6799  6837 E UEI.SmartControl: Loading SETTINGS...
,07-27 09:39:25.169  6799  6799 D UEI.SmartControl: Request IControl service: devices are loaded...
07-27 09:39:25.171  1049  2028 I ActivityManager: Killing 5623:com.lge.qremote/u0a112 (adj 15): empty #17
07-27 09:39:25.178  6799  6837 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-27 09:39:25.187  6799  6836 I UEI.SmartControl: Notify AllClients services are ready: 0
07-27 09:39:25.187  6799  6836 D UEI.SmartControl: -----service ready thread exits
,07-27 09:39:25.292  1049  1884 W libprocessgroup: failed to open /acct/uid_10112/pid_5623/cgroup.procs: No such file or directory
,07-27 09:39:25.293  6799  6799 D UEI.SmartControl: Internal service binding...
07-27 09:39:27.604  6627  6627 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,07-27 09:39:27.605  1049  1974 I ActivityManager: Killing 5846:com.google.android.talk/u0a72 (adj 15): empty #17
07-27 09:39:27.687  1049  2010 W libprocessgroup: failed to open /acct/uid_10072/pid_5846/cgroup.procs: No such file or directory
,07-27 09:39:28.587  6627  6745 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-27 09:39:30.150  6799  6838 D UEI.SmartControl: Internal timer expired: 1
07-27 09:39:30.151  6799  6838 D UEI.SmartControl: unbind internal service
,07-27 09:39:30.163  6799  6799 D UEI.SmartControl: Service.onUnbind: IControl
07-27 09:39:30.164  6799  6799 D UEI.SmartControl: Service.onDestroy
07-27 09:39:30.165  6799  6799 D UEI.SmartControl: Lock is in USE false
07-27 09:39:30.165  6799  6799 D UEI.SmartControl: unbind internal service
07-27 09:39:30.165  6799  6799 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3d528eec
07-27 09:39:30.166  6799  6799 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
07-27 09:39:30.166  6799  6799 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
07-27 09:39:30.177  6799  6799 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
07-27 09:39:30.177  6799  6799 W System.err: 	at com.uei.control.Service.c(Unknown Source)
07-27 09:39:30.177  6799  6799 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-27 09:39:30.177  6799  6799 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
07-27 09:39:30.177  6799  6799 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
07-27 09:39:30.177  6799  6799 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
07-27 09:39:30.177  6799  6799 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:39:30.177  6799  6799 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 09:39:30.177  6799  6799 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 09:39:30.177  6799  6799 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 09:39:30.177  6799  6799 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 09:39:30.177  6799  6799 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 09:39:30.178  6799  6799 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 09:39:30.178  6799  6799 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3d528eec
07-27 09:39:30.181  6799  6799 D serial_port: close(fd = 25)
07-27 09:39:30.183  6799  6799 I UEI.SmartControl: Serial port is closed.
07-27 09:39:30.183  6799  6799 I UEI.SmartControl: Serial port is closed.
07-27 09:39:30.183  6799  6799 D UEI.SmartControl: Blaster closed
07-27 09:39:30.183  6799  6799 D UEI.SmartControl: Shut down QS...
07-27 09:39:30.183  6799  6799 D UEI.SmartControl: Stopping QS lib
07-27 09:39:30.183  6799  6799 D UEI.SmartControl: QS lib stop result = true
07-27 09:39:30.183  6799  6799 D UEI.SmartControl: Stopped QS lib
07-27 09:39:30.184  6799  6799 D UEI.SmartControl: Stopped file observer...
07-27 09:39:30.184  6799  6799 D UEI.SmartControl: QS shutdown complete
,07-27 09:39:30.477  1832  6553 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
07-27 09:39:30.480   302  6881 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-27 09:39:30.480   302  6881 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-27 09:39:30.481   302  6881 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-27 09:39:30.678  1832  1832 I ConfigFetchService: fetch service done; releasing wakelock
,07-27 09:39:30.681  1832  1832 I ConfigFetchService: stopping self
07-27 09:39:30.688  2189  2189 I ConfigService: onDestroy
,07-27 09:39:32.811   299   299 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
07-27 09:39:32.811   299   299 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
07-27 09:39:32.811   299   299 I rmt_storage: wakelock acquired: 1, error no: 42
,07-27 09:39:32.812   299   927 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
07-27 09:39:32.892   299   927 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
07-27 09:39:32.892   299   927 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
07-27 09:39:32.892   299   927 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
07-27 09:39:32.892   299   927 I rmt_storage: 
,07-27 09:39:32.895   299   299 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,07-27 09:39:32.895   919   926 E Diag_Lib: [IMS_FATAL]| 3347 | 926 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,07-27 09:39:35.584  1049  1106 I ActivityManager: Waited long enough for: ServiceRecord{332774b0 u0 com.google.android.gms/.wearable.service.WearableService}
,07-27 09:39:35.596  6674  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 09:39:35.596  6674  6739 I jxcore-log: 
,07-27 09:39:35.599  6674  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 09:39:35.599  6674  6739 I jxcore-log: 
,07-27 09:39:35.602  6674  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 09:39:35.602  6674  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 09:39:35.602  6674  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 09:39:35.602  6674  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 09:39:35.602  6674  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 09:39:35.602  6674  6739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 09:39:35.602  6674  6739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 09:39:35.602  6674  6739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 09:39:35.603  6674  6739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 09:39:35.605  6674  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 09:39:35.605  6674  6739 I jxcore-log: 
07-27 09:39:35.607  6674  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 09:39:35.607  6674  6739 I jxcore-log: 
07-27 09:39:35.937  6674  6739 I jxcore-log: Unit Test app is loaded
07-27 09:39:35.937  6674  6739 I jxcore-log: 
,07-27 09:39:35.949  6674  6674 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74),
07-27 09:39:35.949  6674  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 09:39:35.949  6674  6739 I jxcore-log: 
07-27 09:39:35.952  6674  6739 I jxcore-log: My device name is: LGE-LG-D855
07-27 09:39:35.952  6674  6739 I jxcore-log: 
07-27 09:39:35.954  6674  6739 I jxcore-log: WARN testUtils: myNameCallback not set!
07-27 09:39:35.954  6674  6739 I jxcore-log: 
,07-27 09:39:36.530  2814  2814 I MusicWidget: mDelayedStopHandler : unbind
,07-27 09:39:36.536  2170  2170 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
,07-27 09:39:36.537  2170  2170 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
07-27 09:39:36.538  2170  2170 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
07-27 09:39:36.541  2170  2170 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
07-27 09:39:36.542  2170  2170 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
07-27 09:39:36.542  2170  2170 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
07-27 09:39:36.546  2170  2170 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
,07-27 09:39:36.550  2170  2170 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
07-27 09:39:36.552  1049  1939 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@ff3cfeecom.lge.music.MediaPlaybackService$5@143e3c8f
07-27 09:39:36.553  2170  2170 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
07-27 09:39:36.554  2170  2170 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 09:39:36.554  2170  2170 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 09:39:36.557  2170  2170 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 09:39:36.558  2170  2170 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@3d528eec
07-27 09:39:36.558  2170  2170 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 09:39:36.559  2170  2170 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
07-27 09:39:36.559  2170  2170 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 09:39:36.567  2170  2170 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,07-27 09:39:36.567  2170  2170 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
07-27 09:39:36.567  2170  2170 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 09:39:36.577  2170  2170 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 09:39:36.578  2170  2170 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,07-27 09:39:36.587  2170  2170 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 09:39:36.597  2170  2170 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,07-27 09:39:36.609  2170  2170 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
,07-27 09:39:36.615  2170  2170 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
07-27 09:39:36.615  2170  2170 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
07-27 09:39:36.616  2170  2170 V MediaPlayer[Native]: reset
07-27 09:39:36.629  2170  2170 V MediaPlayer[Native]: setListener
07-27 09:39:36.629  2170  2170 V MediaPlayer[Native]: disconnect
07-27 09:39:36.629  2170  2170 V MediaPlayer[Native]: destructor
07-27 09:39:36.629   306  1402 V AudioFlinger: releasing 18 from 2170 for -1
07-27 09:39:36.629   306  1402 V AudioFlinger:  decremented refcount to 0
07-27 09:39:36.629   306  1402 V AudioFlinger: purging stale effects
07-27 09:39:36.630  2170  2170 V MediaPlayer[Native]: disconnect
,07-27 09:39:36.637  2170  2170 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
07-27 09:39:36.648  2170  2170 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
,07-27 09:39:36.650  2170  2170 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
07-27 09:39:36.657  2170  2170 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
07-27 09:39:36.657  2170  2170 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
07-27 09:39:36.658  2170  2170 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
07-27 09:39:36.658  2170  2170 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 982354716
07-27 09:39:36.658  2170  2170 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 982354716
07-27 09:39:36.665  2170  2170 I SmartShareClient: [SmartShareManagerClient] terminate service: 2170/MediaPlaybackService/457626098
,07-27 09:39:36.672  2170  2170 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
07-27 09:39:36.672  2170  2170 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@24ef325
07-27 09:39:36.674  2170  2170 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
07-27 09:39:36.674  2170  2170 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
07-27 09:39:36.675  2170  2170 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
07-27 09:39:36.676  2170  2170 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
07-27 09:39:36.677  1049  1884 I ActivityManager: Killing 6417:com.android.calendar/u0a13 (adj 15): empty #17
07-27 09:39:36.692  2170  2170 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29984
,07-27 09:39:36.768  1049  2048 W libprocessgroup: failed to open /acct/uid_10013/pid_6417/cgroup.procs: No such file or directory
,07-27 09:39:37.003  1049  1393 V AlarmManager: RTC_WAKEUP set : Alarm{b0cdf83 type 0 when 1469605176189 com.android.vending} when 1469605176189
,07-27 09:39:37.055  4467  6882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,07-27 09:39:37.108  1049  1921 V SIM_STK : Menu title from STK is T-Mobile
,07-27 09:39:37.289  6197  6197 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,07-27 09:39:40.140  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-27 09:39:40.140  6674  6739 I jxcore-log: 
,07-27 09:39:40.533  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-27 09:39:40.533  6674  6739 I jxcore-log: 
,07-27 09:39:40.559  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-27 09:39:40.559  6674  6739 I jxcore-log: 
,07-27 09:39:40.565  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-27 09:39:40.565  6674  6739 I jxcore-log: 
07-27 09:39:40.581  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-27 09:39:40.581  6674  6739 I jxcore-log: 
,07-27 09:39:40.585  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-27 09:39:40.585  6674  6739 I jxcore-log: 
07-27 09:39:42.699  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-27 09:39:42.699  6674  6739 I jxcore-log: 
,07-27 09:39:42.714  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-27 09:39:42.714  6674  6739 I jxcore-log: 
07-27 09:39:42.723  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-27 09:39:42.723  6674  6739 I jxcore-log: 
,07-27 09:39:42.876  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-27 09:39:42.876  6674  6739 I jxcore-log: 
,07-27 09:39:43.675  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-27 09:39:43.675  6674  6739 I jxcore-log: 
,07-27 09:39:43.733  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-27 09:39:43.733  6674  6739 I jxcore-log: 
,07-27 09:39:43.741  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-27 09:39:43.741  6674  6739 I jxcore-log: 
07-27 09:39:43.935  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-27 09:39:43.935  6674  6739 I jxcore-log: 
,07-27 09:39:43.958  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-27 09:39:43.958  6674  6739 I jxcore-log: 
,07-27 09:39:43.963  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-27 09:39:43.963  6674  6739 I jxcore-log: 
07-27 09:39:43.969  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-27 09:39:43.969  6674  6739 I jxcore-log: 
07-27 09:39:43.984  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-27 09:39:43.984  6674  6739 I jxcore-log: 
,07-27 09:39:44.003  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-27 09:39:44.003  6674  6739 I jxcore-log: 
,07-27 09:39:44.087  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-27 09:39:44.087  6674  6739 I jxcore-log: 
,07-27 09:39:44.093  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-27 09:39:44.093  6674  6739 I jxcore-log: 
,07-27 09:39:44.120  6674  6739 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-27 09:39:44.120  6674  6739 I jxcore-log: 
,07-27 09:39:44.132  6674  6739 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-27 09:39:44.133  6674  6739 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-27 09:39:44.133  6674  6739 I jxcore-log: 
,07-27 09:39:46.694  2170  2170 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19983
,07-27 09:40:00.037  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:40:00.038  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:40:00.038  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:40:00.038  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:40:00.051  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:40:00.051  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:40:00.054  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:40:00.056  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:40:06.678  2170  2170 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,07-27 09:40:06.692  2170  2170 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,07-27 09:40:59.939  1616  1616 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:40:59.940  1616  1616 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:40:59.954  1049  1558 D WifiController: battery changed pluggedType: 2
,07-27 09:40:59.957  1616  1616 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 302
07-27 09:40:59.958  1616  1616 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:40:59.958  1957  2087 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:40:59.959  1957  2087 D LEDHandler: Battery Level Remaining: 100%
07-27 09:40:59.959  1957  2087 D LEDHandler: Battery Temp: 302, mChargingStatus=5, mChargingStop=false
07-27 09:40:59.963  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:40:59.963  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:40:59.964  3888  3999 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:40:59.965  1616  1616 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:40:59.970  6776  6776 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-27 09:41:00.051  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:41:00.051  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:41:00.051  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-27 09:41:00.052  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:41:00.065  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:41:00.066  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:41:00.069  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:41:00.073  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:42:00.107  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:42:00.107  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:42:00.107  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:42:00.107  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:42:00.116  1957  2087 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:42:00.116  1957  2087 D LEDHandler: Battery Level Remaining: 100%
07-27 09:42:00.116  1957  2087 D LEDHandler: Battery Temp: 298, mChargingStatus=5, mChargingStop=false
07-27 09:42:00.118  1049  1558 D WifiController: battery changed pluggedType: 2
07-27 09:42:00.119  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:42:00.119  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:42:00.120  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:42:00.120  1616  1616 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:42:00.121  1616  1616 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:42:00.121  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:42:00.121  1616  1616 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
07-27 09:42:00.121  1616  1616 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:42:00.124  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:42:00.124  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:42:00.130  3888  3999 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:42:00.133  1616  1616 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,07-27 09:42:00.134  6776  6776 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-27 09:42:46.458  1049  1393 D PowerManagerServiceEx: acquireWakeLockInternal: lock=296334357, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1049
,07-27 09:42:46.471  1049  1393 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2e74500 type 2 when 210431 android} when 210431
07-27 09:42:46.511  2660  2660 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 09:42:46.545  1049  1049 D PowerManagerServiceEx: releaseWakeLockInternal: lock=296334357 [*alarm*], flags=0x0
,07-27 09:43:00.047  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:43:00.047  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:43:00.047  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:43:00.048  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:43:00.061  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:43:00.061  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:43:00.063  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:43:00.065  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:43:26.210  1049  3536 I LocationManagerService: remove 304d3b84
07-27 09:43:26.211  1049  3536 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
07-27 09:43:26.211  1049  3536 D LocationManagerService: getAllProviders()=[passive, gps, network]
,07-27 09:43:26.212  1049  3536 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1],
07-27 09:43:26.214  1049  3536 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1],
07-27 09:43:26.215  1049  3536 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1],
,07-27 09:43:36.988  1049  1393 D PowerManagerServiceEx: acquireWakeLockInternal: lock=296334357, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1049
,07-27 09:43:37.040  2660  2660 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 09:43:37.075  1049  1049 D PowerManagerServiceEx: releaseWakeLockInternal: lock=296334357 [*alarm*], flags=0x0
,07-27 09:44:00.052  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:44:00.052  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:44:00.052  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:44:00.053  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:44:00.066  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:44:00.066  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:44:00.069  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:44:00.071  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:45:00.052  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:45:00.052  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated(),
07-27 09:45:00.053  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-27 09:45:00.053  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:45:00.070  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:45:00.070  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:45:00.072  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:45:00.074  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:45:01.862  1049  1393 D PowerManagerServiceEx: acquireWakeLockInternal: lock=296334357, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1049
,07-27 09:45:01.920  1049  1106 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6932 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,07-27 09:45:01.962  2660  2660 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 09:45:02.109  6932  6932 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,07-27 09:45:02.113  6932  6932 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3603a0fd
,07-27 09:45:02.114  1049  1049 D PowerManagerServiceEx: releaseWakeLockInternal: lock=296334357 [*alarm*], flags=0x0
07-27 09:45:02.115  1049  2048 I ActivityManager: Killing 6337:com.android.defcontainer/u0a4 (adj 15): empty #17
07-27 09:45:02.179  1049  1065 W libprocessgroup: failed to open /acct/uid_10004/pid_6337/cgroup.procs: No such file or directory
,07-27 09:46:00.057  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:46:00.057  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:46:00.058  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:46:00.058  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:46:00.072  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:46:00.072  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:46:00.075  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:46:00.078  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:46:00.739  1616  1616 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,07-27 09:46:00.739  1616  1616 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:46:00.757  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:46:00.757  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:46:00.759  1049  1558 D WifiController: battery changed pluggedType: 2
07-27 09:46:00.760  3888  3999 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:46:00.763  1957  2087 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:46:00.763  1957  2087 D LEDHandler: Battery Level Remaining: 100%
07-27 09:46:00.763  1957  2087 D LEDHandler: Battery Temp: 292, mChargingStatus=5, mChargingStop=false
07-27 09:46:00.765  1616  1616 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
07-27 09:46:00.765  1616  1616 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:46:00.766  1616  1616 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:46:00.771  6776  6776 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-27 09:47:00.053  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:47:00.053  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:47:00.054  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:47:00.054  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:47:00.059  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:47:00.059  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:47:00.060  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:47:00.061  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:48:00.042  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:48:00.042  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:48:00.042  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:48:00.043  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:48:00.058  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:48:00.059  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:48:00.061  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:48:00.063  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:49:00.054  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:49:00.055  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:49:00.055  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:49:00.055  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:49:00.070  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:49:00.070  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:49:00.073  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:49:00.075  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:49:28.596  1049  1975 I ActivityManager: Killing 6556:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,07-27 09:49:28.630  1049  2028 W libprocessgroup: failed to open /acct/uid_10008/pid_6556/cgroup.procs: No such file or directory
,07-27 09:50:00.055  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:50:00.056  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:50:00.056  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:50:00.056  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:50:00.070  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:50:00.070  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:50:00.072  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:50:00.074  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:51:00.052  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:51:00.052  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:51:00.052  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-27 09:51:00.053  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:51:00.068  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:51:00.069  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:51:00.071  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:51:00.073  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:52:00.055  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:52:00.055  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:52:00.056  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:52:00.056  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:52:00.072  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:52:00.072  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:52:00.075  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:52:00.076  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:53:00.055  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:53:00.055  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:53:00.056  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:53:00.056  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:53:00.071  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:53:00.072  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:53:00.074  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:53:00.076  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:53:26.702  1049  1393 D PowerManagerServiceEx: acquireWakeLockInternal: lock=296334357, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1049
,07-27 09:53:26.719  1049  1393 V AlarmManager: RTC_WAKEUP set : Alarm{117e9139 type 0 when 1469605679794 com.google.android.gms} when 1469605679794
,07-27 09:53:26.735  1049  1393 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3c33f0df type 2 when 929166 com.google.android.gms} when 929166
,07-27 09:53:26.782  2660  2660 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 09:53:26.811  1049  1049 D PowerManagerServiceEx: releaseWakeLockInternal: lock=296334357 [*alarm*], flags=0x0
,07-27 09:53:26.831  1832  2375 I EventLogService: Aggregate from 1469605128532 (log), 1469603879732 (data)
,07-27 09:53:26.837  2189  2966 D GCM     : Message class com.google.e.a.a.h
07-27 09:53:26.860  1832  2375 W EventLogAggregator: Unknown tag: snet_gcore
,07-27 09:53:26.863  1832  2375 W EventLogAggregator: Unknown tag: snet_launch_service
,07-27 09:53:33.367  1049  1393 V AlarmManager: ELAPSED_WAKEUP set : Alarm{20fbb12c type 2 when 941764 com.android.bluetooth} when 941764
,07-27 09:53:33.389  3888  4075 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 09:53:33.389  3888  4075 W bt-smp  : Plain text(LSB ~ MSB) = 3f d5 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 09:53:33.389  3888  4075 W bt-smp  : Encrypted text(LSB ~ MSB) = a4 e9 dc e0 e3 38 6b 34 17 03 47 39 10 b7 b1 98 
07-27 09:53:33.389  3888  4075 W bt-btm  : Stopping oneshot timer
,07-27 09:54:00.054  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:54:00.054  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:54:00.054  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:54:00.055  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:54:00.068  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:54:00.068  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:54:00.070  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:54:00.072  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:55:00.052  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:55:00.052  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:55:00.053  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:55:00.053  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:55:00.068  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:55:00.068  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:55:00.070  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:55:00.072  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:56:00.054  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:56:00.054  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:56:00.054  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:56:00.055  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:56:00.071  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:56:00.071  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:56:00.073  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:56:00.075  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:56:02.338  1616  1616 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:56:02.338  1616  1616 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:56:02.348  1616  1616 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
07-27 09:56:02.348  1049  1558 D WifiController: battery changed pluggedType: 2
07-27 09:56:02.351  1957  2087 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:56:02.351  1957  2087 D LEDHandler: Battery Level Remaining: 100%
07-27 09:56:02.351  1957  2087 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,07-27 09:56:02.353  1616  1616 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:56:02.358  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:56:02.358  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:56:02.359  3888  3999 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:56:02.359  1616  1616 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:56:02.364  6776  6776 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-27 09:57:00.074  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:57:00.074  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:57:00.074  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:57:00.075  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:57:00.088  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:57:00.088  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:57:00.090  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:57:00.092  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:58:00.107  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:58:00.107  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:58:00.107  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:58:00.108  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:58:00.122  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:58:00.123  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:58:00.125  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:58:00.129  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:58:11.652  1049  1105 I UsageStatsService: User[0] Flushing usage stats to disk
,07-27 09:59:00.056  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:59:00.056  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:59:00.056  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-27 09:59:00.065  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:59:00.071  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:59:00.072  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:59:00.074  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:59:00.076  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 10:00:00.054  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 10:00:00.054  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 10:00:00.054  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-27 10:00:00.055  1616  1616 I [SystemUI]Clock: called onTimeUpdated(),
,07-27 10:00:00.072  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 10:00:00.072  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 10:00:00.074  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 10:00:00.076  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 10:00:01.112  1049  1393 D PowerManagerServiceEx: acquireWakeLockInternal: lock=296334357, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1049
,07-27 10:00:01.142  6932  6932 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,07-27 10:00:01.149  6932  6932 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3603a0fd
07-27 10:00:01.172  2660  2660 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 10:00:01.202  1049  1049 D PowerManagerServiceEx: releaseWakeLockInternal: lock=296334357 [*alarm*], flags=0x0
,07-27 10:01:00.055  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 10:01:00.056  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 10:01:00.056  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 10:01:00.056  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,07-27 10:01:00.070  1616  1616 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 10:01:00.071  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
,07-27 10:01:00.073  1616  1616 I [SystemUI]DateView: called onTimeUpdated()
07-27 10:01:00.075  1616  1616 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 10:02:00.054  1616  1616 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 10:02:00.054  1616  1616 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 10:02:00.054  1616  1616 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 10:02:00.055  1616  1616 I [SystemUI]Clock: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1400000ms)
```
