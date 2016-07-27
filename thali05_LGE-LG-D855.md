#### Test 757892684714826_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
07-27 11:04:10.305  4595  6670 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 174 ms] updated apps [took 173 ms] 
07-27 11:04:10.469  6671  6671 D DocsApplication: Installing DEX configuration.
07-27 11:04:10.489  6671  6671 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
07-27 11:04:10.494  6671  6671 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{12d6ee37 com.google.android.apps.docs}
07-27 11:04:10.512  6671  6671 D TAG     : onCreate()
07-27 11:04:10.534  6671  6671 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
07-27 11:04:10.997   331   413 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,07-27 11:04:11.001  3199  6700 I Thermal-Lib: Thermal-Lib-Client: Client request sent
07-27 11:04:11.305  1803  4768 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
07-27 11:04:11.349  1803  4768 D Icing   : Loaded CLD2 Version V2.0 - 20140131
07-27 11:04:11.408  1803  4768 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
07-27 11:04:11.461  6701  6701 D AndroidRuntime: 
07-27 11:04:11.461  6701  6701 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 11:04:11.464  6701  6701 D AndroidRuntime: CheckJNI is OFF
07-27 11:04:11.605  6701  6701 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-27 11:04:11.609  1036  1366 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 11:04:11.643  1926  1943 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-27 11:04:11.648  1036  1366 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-27 11:04:11.649  1036  1366 D ActivityManager: setTaskToReturnTo : TaskRecord{24517354 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-27 11:04:11.649  1036  1366 D ActivityManager: setTaskToReturnTo : TaskRecord{24517354 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-27 11:04:11.650  1036  1366 D WindowStateEx: AppWindowTokenEx init.. 
07-27 11:04:11.651   340   353 E GBMv2   : DFP En is all cleared set to be enabled
07-27 11:04:11.699  1036  1366 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6733 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-27 11:04:11.700  6701  6701 D AndroidRuntime: Shutting down VM
07-27 11:04:11.741  1926  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-27 11:04:11.741  1926  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{a3f1e63 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-27 11:04:11.743  1926  2793 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-27 11:04:11.744  1926  2793 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3bb44a60 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-27 11:04:11.801  6733  6733 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-27 11:04:11.892  6733  6733 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
07-27 11:04:11.900  6733  6733 I LibraryLoader: Loading: webviewchromium
07-27 11:04:11.903  6733  6733 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2882-2885)
07-27 11:04:11.903  6733  6733 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 11:04:11.920  6733  6733 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2c658109}
,07-27 11:04:11.921  6733  6733 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 11:04:11.922  6733  6733 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 11:04:11.931  6733  6733 I BrowserStartupController: Initializing chromium process, renderers=0
07-27 11:04:11.932  6733  6733 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 11:04:11.941  6733  6733 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-27 11:04:11.942  6733  6733 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
07-27 11:04:11.942  6733  6733 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
07-27 11:04:11.944   317  2135 V AudioPolicyService: registerClient() client 0xb558ac20, uid 10118
,07-27 11:04:11.948  1036  1118 D BluetoothManagerService: Message: 20
07-27 11:04:11.948  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1bb9d53e:true
07-27 11:04:11.960  6733  6733 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 11:04:11.960  6733  6733 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 11:04:11.960  6733  6733 I Adreno-EGL: Build Date: 12/12/14 금
07-27 11:04:11.960  6733  6733 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 11:04:11.960  6733  6733 I Adreno-EGL: Remote Branch: 
07-27 11:04:11.960  6733  6733 I Adreno-EGL: Local Patches: 
07-27 11:04:11.960  6733  6733 I Adreno-EGL: Reconstruct Branch: 
,07-27 11:04:12.039  6733  6765 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,07-27 11:04:12.043  6733  6733 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-27 11:04:12.057  6733  6733 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 11:04:12.060  6733  6733 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-27 11:04:12.063  6733  6733 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-27 11:04:12.065  6733  6733 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-27 11:04:12.065  6733  6733 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-27 11:04:12.078  6733  6733 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-27 11:04:12.084  6733  6733 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 11:04:12.084  6733  6733 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 11:04:12.123  6733  6777 D OpenGLRenderer: Render dirty regions requested: true
07-27 11:04:12.124  6733  6777 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 11:04:12.131  6733  6777 D OpenGLRenderer: Enabling debug mode 0
,07-27 11:04:12.152  6733  6733 D Atlas   : Validating map...
07-27 11:04:12.159  1036  2017 D SplitWindow: check instance of lgWin Window{a94a708 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-27 11:04:12.183  6733  6775 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:04:12.183  6733  6775 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:04:12.313  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +572ms (total +661ms)
,07-27 11:04:12.314  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ec9e2fd u0 com.test.thalitest/.MainActivity t40} time:103297
07-27 11:04:12.317  6733  6733 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2cfaf6c time:103300
07-27 11:04:12.360  6671  6671 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:04:12.360  6671  6671 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:04:12.393  6733  6733 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 11:04:12.543  6733  6791 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435141120
,07-27 11:04:12.546  6239  6239 I LockScreenSettings: New app installed broadcast received ..
07-27 11:04:12.552  6239  6239 I LockScreenSettings: Number of installed packages  1
07-27 11:04:12.558  6733  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 11:04:12.558  6733  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 11:04:12.558  6733  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 11:04:12.558  6733  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 11:04:12.558  6733  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 11:04:12.558  6733  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36d59870 added. We now have 1 listener(s)
,07-27 11:04:12.564  6671  6671 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-27 11:04:12.565  1036  1366 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:12.568  6733  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,07-27 11:04:12.569  6733  6791 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:04:12.570  6733  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:04:12.573  6733  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:04:12.580  6733  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 11:04:12.580  6733  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 11:04:12.580  6733  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 11:04:12.580  6733  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-27 11:04:12.580  6733  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 11:04:12.580  6733  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 11:04:12.580  6733  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-27 11:04:12.580  6733  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-27 11:04:12.580  6733  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-27 11:04:12.580  6733  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 11:04:12.580  6733  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 11:04:12.580  6733  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 11:04:12.580  6733  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 11:04:12.580  6733  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 11:04:12.580  6733  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ab2f0f added. We now have 1 listener(s)
07-27 11:04:12.581  6733  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:12.584  1036  1530 D WifiService: New client listening to asynchronous messages
,07-27 11:04:12.588  6733  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:04:12.589  6733  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 11:04:12.589  6733  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 11:04:12.589  6733  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-27 11:04:12.593  6733  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:04:12.593  1036  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:12.595  6733  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,07-27 11:04:12.603  6733  6791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
07-27 11:04:12.603  6733  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:04:12.603  6733  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:12.603  6733  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:12.603  6733  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:12.603  6733  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:12.603  6733  6791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:12.603  6733  6791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:04:12.603  6733  6791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:04:12.603  6733  6791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 11:04:12.603  6733  6791 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:04:12.604  6733  6791 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 11:04:12.605  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:12.607  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:12.631  1036  1897 V SIM_STK : Menu title from STK is T-Mobile
,07-27 11:04:12.648  6733  6775 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-27 11:04:12.648  6733  6775 I chromium: 
,07-27 11:04:12.680  1036  1922 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6807 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-27 11:04:12.707  6733  6733 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 11:04:12.762  6807  6807 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
07-27 11:04:12.762  6807  6807 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,07-27 11:04:12.770   340   355 E GBMv2   : DFP En is all cleared set to be enabled
07-27 11:04:12.770   340   355 E GBMv2   : Set value is all cleared set the max
07-27 11:04:12.770   340   355 I GBMv2   : DFP Enabled. Ignore VFP set
07-27 11:04:12.799  6733  6733 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-27 11:04:12.799  6733  6733 I chromium: 
,07-27 11:04:12.833  1036  1757 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6826 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-27 11:04:12.834  1036  1757 I ActivityManager: Killing 5808:com.google.android.gm/u0a64 (adj 15): empty #17
07-27 11:04:12.908  1036  1051 W libprocessgroup: failed to open /acct/uid_10064/pid_5808/cgroup.procs: No such file or directory
,07-27 11:04:12.980  6826  6826 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,07-27 11:04:13.027  6826  6826 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-27 11:04:13.032  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
07-27 11:04:13.067  1036  1763 I ActivityManager: Killing 5854:com.google.android.talk/u0a72 (adj 15): empty #17
,07-27 11:04:13.162  1036  1052 W libprocessgroup: failed to open /acct/uid_10072/pid_5854/cgroup.procs: No such file or directory
,07-27 11:04:13.388  6733  6802 W jxcore-log: Initializing JXcore engine
07-27 11:04:13.388  6733  6802 W jxcore-log: JXcore engine is ready
,07-27 11:04:13.426  6802  6802 W Thread-772: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8383]" dev="sockfs" ino=8383 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,07-27 11:04:13.426  6802  6802 W Thread-772: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-27 11:04:13.426  6802  6802 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7541]" dev="sockfs" ino=7541 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-27 11:04:13.426  6802  6802 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-27 11:04:13.426  6802  6802 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32397]" dev="sockfs" ino=32397 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-27 11:04:13.438  6733  6802 W jxcore-log: Starting JXcore engine
07-27 11:04:13.515  6733  6802 W jxcore-log: Platform android
07-27 11:04:13.515  6733  6802 W jxcore-log: 
07-27 11:04:13.515  6733  6802 W jxcore-log: Process ARCH arm
07-27 11:04:13.515  6733  6802 W jxcore-log: 
,07-27 11:04:13.574  2773  2773 I MusicWidget: mDelayedStopHandler : unbind
,07-27 11:04:13.580  2118  2118 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
07-27 11:04:13.580  2118  2118 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
07-27 11:04:13.581  2118  2118 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
07-27 11:04:13.584  2118  2118 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
07-27 11:04:13.585  2118  2118 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
07-27 11:04:13.586  2118  2118 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
07-27 11:04:13.595  2118  2118 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
07-27 11:04:13.596  2118  2118 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,07-27 11:04:13.598  1036  1929 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@20e727becom.lge.music.MediaPlaybackService$5@2b7c001f
07-27 11:04:13.603  2118  2118 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
07-27 11:04:13.604  2118  2118 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 11:04:13.605  2118  2118 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 11:04:13.618  2118  2118 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,07-27 11:04:13.620  2118  2118 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@85c24c5
07-27 11:04:13.621  2118  2118 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 11:04:13.621  2118  2118 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
07-27 11:04:13.622  2118  2118 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 11:04:13.622  2118  2118 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
07-27 11:04:13.622  2118  2118 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
07-27 11:04:13.623  2118  2118 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 11:04:13.623  2118  2118 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 11:04:13.624  2118  2118 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 11:04:13.624  2118  2118 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 11:04:13.625  2118  2118 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 11:04:13.626  2118  2118 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
07-27 11:04:13.627  2118  2118 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
07-27 11:04:13.627  2118  2118 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
07-27 11:04:13.628  2118  2118 V MediaPlayer[Native]: reset
07-27 11:04:13.634  2118  2118 V MediaPlayer[Native]: setListener
07-27 11:04:13.634  2118  2118 V MediaPlayer[Native]: disconnect
07-27 11:04:13.634  2118  2118 V MediaPlayer[Native]: destructor
07-27 11:04:13.634   317   317 V AudioFlinger: releasing 18 from 2118 for -1
07-27 11:04:13.634   317   317 V AudioFlinger:  decremented refcount to 0
07-27 11:04:13.634   317   317 V AudioFlinger: purging stale effects
07-27 11:04:13.634  2118  2118 V MediaPlayer[Native]: disconnect
07-27 11:04:13.635  2118  2118 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
07-27 11:04:13.636  2118  2118 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
07-27 11:04:13.637  2118  2118 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
07-27 11:04:13.639  2118  2118 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
07-27 11:04:13.639  2118  2118 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
07-27 11:04:13.639  2118  2118 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
07-27 11:04:13.639  2118  2118 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 47165292
07-27 11:04:13.639  2118  2118 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 47165292
,07-27 11:04:13.649  2118  2118 I SmartShareClient: [SmartShareManagerClient] terminate service: 2118/MediaPlaybackService/773994195
07-27 11:04:13.653  2118  2118 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
07-27 11:04:13.653  2118  2118 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@1368c935
07-27 11:04:13.655  2118  2118 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
07-27 11:04:13.655  2118  2118 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
07-27 11:04:13.656  2118  2118 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
07-27 11:04:13.656  2118  2118 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
,07-27 11:04:13.660  1036  1366 I ActivityManager: Killing 5669:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
07-27 11:04:13.661  2118  2118 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29995
07-27 11:04:13.689  6733  6802 I jxcore-log: JXcore Cordova bridge is ready!
07-27 11:04:13.689  6733  6802 I jxcore-log: 
07-27 11:04:13.689  6733  6802 W jxcore-log: JXcore engine is started
,07-27 11:04:13.691  5643  5643 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-27 11:04:13.691  5643  5643 W System.err: android.os.DeadObjectException
07-27 11:04:13.692  5643  5643 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 11:04:13.692  5643  5643 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 11:04:13.692  5643  5643 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-27 11:04:13.692  5643  5643 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-27 11:04:13.693  5643  5643 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-27 11:04:13.693  5643  5643 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-27 11:04:13.693  5643  5643 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 11:04:13.693  5643  5643 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 11:04:13.693  5643  5643 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 11:04:13.695  5643  5643 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 11:04:13.695  5643  5643 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:04:13.695  5643  5643 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:04:13.695  5643  5643 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 11:04:13.695  5643  5643 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 11:04:13.695  5643  5643 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-27 11:04:13.696  5643  5643 W System.err: android.os.DeadObjectException
07-27 11:04:13.696  5643  5643 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 11:04:13.696  6733  6791 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-27 11:04:13.696  5643  5643 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 11:04:13.696  5643  5643 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-27 11:04:13.696  5643  5643 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-27 11:04:13.696  5643  5643 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-27 11:04:13.696  5643  5643 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-27 11:04:13.696  5643  5643 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 11:04:13.696  5643  5643 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 11:04:13.696  5643  5643 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 11:04:13.696  5643  5643 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 11:04:13.696  5643  5643 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:04:13.696  5643  5643 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:04:13.696  5643  5643 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 11:04:13.696  5643  5643 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 11:04:13.696  5643  5643 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-27 11:04:13.697  5643  5643 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
07-27 11:04:13.698  6733  6733 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-27 11:04:13.871  1036  1366 E libproce,ssgroup: failed to kill 1 processes for processgroup 5669
,07-27 11:04:14.018  1036  1757 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,07-27 11:04:14.021  5643  5643 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-27 11:04:14.022  5643  5643 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-27 11:04:14.074  1036  1922 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6859 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-27 11:04:14.076  5643  5643 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-27 11:04:14.189  6859  6859 D UEI.SmartControl: Quickset Services start...
,07-27 11:04:14.192  6859  6859 I UEI.SmartControl: Manufacture = LGE
07-27 11:04:14.192  6859  6859 D UEI.SmartControl: Id = LGNevo
07-27 11:04:14.193  6859  6859 D UEI.SmartControl: File observer start...
07-27 11:04:14.194  6859  6859 E UEI.SmartControl: IR Port is disabled: false
07-27 11:04:14.194  6859  6859 D UEI.SmartControl: Starting file observer...
07-27 11:04:14.195  6859  6859 D UEI.SmartControl: Extracting JNI libs...
07-27 11:04:14.195  6859  6859 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-27 11:04:14.282  6859  6859 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-27 11:04:14.282  6859  6859 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-27 11:04:14.282  6859  6859 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-27 11:04:14.318  6859  6859 I UEI.SmartControl: --- Selecting new region: 6,
,07-27 11:04:14.320  6859  6859 I UEI.SmartControl: Model = LG-D855
07-27 11:04:14.322  6859  6859 D UEI.SmartControl: QS Service created
07-27 11:04:14.338  6859  6859 I UEI.SmartControl: Service initServices...
07-27 11:04:14.342  6859  6859 D UEI.SmartControl: QS start get config
,07-27 11:04:14.384  1036  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=103759950, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,07-27 11:04:14.384  6859  6859 D UEI.SmartControl: Loading JNI Libs...
,07-27 11:04:14.422  2564  2564 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 11:04:14.438  4482  6881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
07-27 11:04:14.439  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=103759950 [*alarm*], flags=0x0
,07-27 11:04:14.727  6859  6859 I UEI.SmartControl: Supports setup maps: true
,07-27 11:04:14.740  6859  6859 D UEI.SmartControl: QS start statue = true Error code = 0
07-27 11:04:14.740  6859  6859 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-27 11:04:14.740  6859  6859 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-27 11:04:14.741  6859  6859 I UEI.SmartControl: ### init IR Blaster...
07-27 11:04:14.747  6859  6859 D serial_port: Configuring serial port
,07-27 11:04:14.760  6859  6859 E UEI.SmartControl: UEIBLaster setting for 616
,07-27 11:04:14.760  6859  6859 I UEI.SmartControl: Setting serial record hearder size = 2
07-27 11:04:14.761  6859  6859 I UEI.SmartControl: configuring settings for MAXQ616
07-27 11:04:14.761  6859  6859 I UEI.SmartControl: Get version...
,07-27 11:04:14.779  6859  6895 D UEI.SmartControl: serial port data available: 21
,07-27 11:04:14.810  6859  6859 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-27 11:04:14.810  6859  6859 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-27 11:04:14.810  6859  6859 I UEI.SmartControl: QS saving settings...
,07-27 11:04:14.815  6859  6859 D UEI.SmartControl: IR Blaster version: 25672567
,07-27 11:04:14.832  6859  6895 D UEI.SmartControl: serial port data available: 4
,07-27 11:04:14.865  6859  6901 I UEI.SmartControl: Device manager: loading config....
,07-27 11:04:14.866  6859  6901 D UEI.SmartControl: ----------- loading internal config...
07-27 11:04:14.872  6859  6859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-27 11:04:14.875  6859  6859 E UEI.SmartControl: Services init done
07-27 11:04:14.876  6859  6859 D UEI.SmartControl: QS Service init finished
07-27 11:04:14.878  6859  6859 D UEI.SmartControl: QS Service version name: 2.1.91
07-27 11:04:14.878  6859  6859 D UEI.SmartControl: QS Service version code: 201091
,07-27 11:04:14.884  6859  6859 D UEI.SmartControl: Service requested: Control
07-27 11:04:14.891  6859  6901 E UEI.SmartControl: Loading SETTINGS...
,07-27 11:04:14.894  6859  6859 D UEI.SmartControl: Request IControl service: devices are loaded...
07-27 11:04:14.897  1036  1051 I ActivityManager: Killing 5643:com.lge.qremote/u0a112 (adj 15): empty #17
07-27 11:04:14.897  5643  5643 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-27 11:04:14.898  6859  6874 I UEI.SmartControl: ------ IControl API: 11
07-27 11:04:14.899  6859  6874 I UEI.SmartControl: Registering callback...
07-27 11:04:14.903  6859  6901 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-27 11:04:14.927  6859  6900 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-27 11:04:14.927  6859  6900 D UEI.SmartControl: -----service ready thread exits
,07-27 11:04:14.970  1036  1929 W libprocessgroup: failed to open /acct/uid_10112/pid_5643/cgroup.procs: No such file or directory
07-27 11:04:14.971  6859  6859 D UEI.SmartControl: Internal service binding...
,07-27 11:04:16.462  6671  6671 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,07-27 11:04:16.466  1036  1897 I ActivityManager: Killing 6330:com.android.calendar/u0a13 (adj 15): empty #17
07-27 11:04:16.569  1036  1922 W libprocessgroup: failed to open /acct/uid_10013/pid_6330/cgroup.procs: No such file or directory
,07-27 11:04:17.424  6671  6788 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-27 11:04:19.869  6859  6902 D UEI.SmartControl: Internal timer expired: 1
07-27 11:04:19.870  6859  6902 D UEI.SmartControl: unbind internal service
,07-27 11:04:19.878  6859  6859 D UEI.SmartControl: Service.onUnbind: IControl
07-27 11:04:19.883  6859  6859 D UEI.SmartControl: Service.onDestroy
07-27 11:04:19.884  6859  6859 D UEI.SmartControl: Lock is in USE false
07-27 11:04:19.884  6859  6859 D UEI.SmartControl: unbind internal service
07-27 11:04:19.884  6859  6859 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@85c24c5
07-27 11:04:19.885  6859  6859 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
,07-27 11:04:19.887  6859  6859 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
07-27 11:04:19.887  6859  6859 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
07-27 11:04:19.888  6859  6859 W System.err: 	at com.uei.control.Service.c(Unknown Source)
07-27 11:04:19.888  6859  6859 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-27 11:04:19.888  6859  6859 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
07-27 11:04:19.888  6859  6859 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
07-27 11:04:19.888  6859  6859 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
07-27 11:04:19.888  6859  6859 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:04:19.888  6859  6859 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 11:04:19.888  6859  6859 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 11:04:19.888  6859  6859 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,07-27 11:04:19.888  6859  6859 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:04:19.888  6859  6859 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 11:04:19.888  6859  6859 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 11:04:19.888  6859  6859 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@85c24c5
07-27 11:04:19.890  6859  6859 D serial_port: close(fd = 25)
07-27 11:04:19.894  6859  6859 I UEI.SmartControl: Serial port is closed.
07-27 11:04:19.894  6859  6859 I UEI.SmartControl: Serial port is closed.
07-27 11:04:19.894  6859  6859 D UEI.SmartControl: Blaster closed
07-27 11:04:19.894  6859  6859 D UEI.SmartControl: Shut down QS...
07-27 11:04:19.895  6859  6859 D UEI.SmartControl: Stopping QS lib
07-27 11:04:19.895  6859  6859 D UEI.SmartControl: QS lib stop result = true
07-27 11:04:19.895  6859  6859 D UEI.SmartControl: Stopped QS lib
07-27 11:04:19.895  6859  6859 D UEI.SmartControl: Stopped file observer...
07-27 11:04:19.895  6859  6859 D UEI.SmartControl: QS shutdown complete
,07-27 11:04:23.667  2118  2118 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19990
,07-27 11:04:24.613  1036  1099 I ActivityManager: Waited long enough for: ServiceRecord{a447f2e u0 com.google.android.gms/.wearable.service.WearableService}
,07-27 11:04:25.133  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 11:04:25.133  6733  6802 I jxcore-log: 
,07-27 11:04:25.136  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 11:04:25.136  6733  6802 I jxcore-log: 
,07-27 11:04:25.141  6733  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:04:25.141  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:25.141  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:25.141  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:25.141  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:25.141  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:25.141  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:04:25.141  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:04:25.144  6733  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 11:04:25.146  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 11:04:25.146  6733  6802 I jxcore-log: 
,07-27 11:04:25.148  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 11:04:25.148  6733  6802 I jxcore-log: 
07-27 11:04:25.480  6733  6802 D ExecuteNativeTests: Running unit tests
,07-27 11:04:25.566  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:04:25.566  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 added. We now have 2 listener(s)
,07-27 11:04:25.567  1036  1990 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:25.570  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:04:25.570  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:04:25.570  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:04:25.570  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:25.570  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda added. We now have 2 listener(s)
07-27 11:04:25.570  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:25.570  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:04:25.572  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:04:25.574  6733  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:04:25.574  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:25.574  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:25.574  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:25.574  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:25.574  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:25.574  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:04:25.574  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:04:25.576  6733  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:25.576  6733  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:04:25.577  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:25.579  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:25.584  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 11:04:25.585  6733  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 11:04:25.585  6733  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 11:04:25.592  6733  6802 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-27 11:04:25.595  6733  6802 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-27 11:04:25.595  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 11:04:25.596  6733  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 11:04:25.596  6733  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 11:04:25.598  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.599  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.599  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.599  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.599  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.600  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:04:25.600  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:04:25.600  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 removed from the list
07-27 11:04:25.600  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.600  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda removed from the list
07-27 11:04:25.600  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.600  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.601  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.601  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.602  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.602  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.602  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.603  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.604  6733  6802 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-27 11:04:25.605  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.605  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.605  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.605  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.605  6733  6802 W org.tha,liproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.605  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.605  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.605  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.605  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.605  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.605  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.605  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.605  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.605  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:04:25.607  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.607  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.607  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.607  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-27 11:04:25.612  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-27 11:04:25.612  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.612  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.613  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.613  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.613  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.613  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.613  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.614  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.614  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.614  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.614  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.614  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.614  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.614  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.615  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.615  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.615  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.615  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.615  6733  6802 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 11:04:25.616  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:0,4:25.619  6733  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:04:25.619  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:25.619  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:25.619  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:25.619  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:25.619  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:25.619  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:04:25.619  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 11:04:25.622  6733  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:25.622  6733  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:04:25.624  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:25.625  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:04:25.625  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:04:25.625  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:04:25.625  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:04:25.625  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:25.628  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 11:04:25.629  1036  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 11:04:25.634  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-27 11:04:25.637  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 11:04:25.639  6733  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
07-27 11:04:25.640  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-27 11:04:25.641  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:04:25.643  6733  6802 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:04:25.643  6733  6802 I io.jxcore.node.ConnectionHelper: start: OK
07-27 11:04:25.645  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.645  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.645  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.645  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.645  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.645  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:04:25.645  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.645  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.645  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.646  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.646  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.646  6733  6802 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 11:04:25.647  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:04:25.650  6733  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:04:25.650  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:25.650  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:25.650  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:25.650  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:25.650  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:25.650  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:04:25.650  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:04:25.650  6733  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:25.650  6733  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:04:25.651  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:04:25.651  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:04:25.651  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:04:25.651  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Bi,nding a new listener
07-27 11:04:25.653  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:25.656  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:25.657  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:04:25.657  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:04:25.658  6733  6802 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:04:25.658  6733  6802 I io.jxcore.node.ConnectionHelper: start: OK
07-27 11:04:25.659  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.659  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.660  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.660  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.660  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.660  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:04:25.660  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.660  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.660  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.660  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.660  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.660  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.660  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.661  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.661  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.662  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:25.662  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:25.663  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.663  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.663  6733  6802 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 11:04:25.665  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:04:25.668  6733  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:04:25.668  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:25.668  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:25.668  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:25.668  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:25.668  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:25.668  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:04:25.668  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:04:25.669  6733  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:25.669  6733  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:04:25.670  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:04:25.670  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:04:25.670  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:04:25.670  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:04:25.670  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:25.673  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:25.673  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:04:25.674  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:04:25.674  6733  6802 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:04:25.675  6733  6802 I io.jxcore.node.ConnectionHelper: start: OK
07-27 11:04:25.675  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.675  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.675  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.675  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.675  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.675  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.675  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.675  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.675  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:04:2,5.675  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.675  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.676  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.676  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.676  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.677  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.678  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.679  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.679  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.679  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:25.679  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:25.679  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.679  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.680  6733  6802 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-27 11:04:25.680  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.680  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.680  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.681  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.681  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.681  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.681  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.681  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.681  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.681  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.681  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.681  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.681  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.681  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.681  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.681  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.682  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:25.682  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:25.682  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.682  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.682  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-27 11:04:25.682  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.682  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.682  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.683  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.683  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.683  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.683  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.683  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.683  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.683  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.683  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.683  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.683  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.683  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.683  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.683  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.684  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:25.684  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:25.684  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.684  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.684  6733  6802 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-27 11:04:25.684  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.684  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.684  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.684  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.685  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.685  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.685  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.685  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.685  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.685  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.685  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.685  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.685  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.685  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.685  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.685  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.685  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:25.685  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:25.686  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.686  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.686  6733  6802 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-27 11:04:25.686  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.686  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.686  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.686  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.686  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.686  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.686  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.686  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.686  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.686  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.686  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.686  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.686  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.686  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.689  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.689  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.690  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:25.690  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:25.690  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.690  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.691  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 11:04:25.691  6733  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 11:04:25.691  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 11:04:25.691  6733  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 11:04:25.691  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 11:04:25.692  6733  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 11:04:25.692  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.692  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.692  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.692  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.692  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.692  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.692  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.692  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.692  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.692  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.692  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.692  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.692  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.692  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.693  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.693  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.693  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:25.693  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:25.693  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.693  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.694  6733  6802 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:04:25.694  6733  6802 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-27 11:04:25.694  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-27 11:04:25.696  6733  6802 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:04:25.696  6733  6802 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-27 11:04:25.696  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-27 11:04:25.697  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-27 11:04:25.697  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-27 11:04:25.697  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-27 11:04:25.697  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-27 11:04:25.697  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-27 11:04:25.697  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-27 11:04:25.697  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-27 11:04:25.697  6733  6802 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-27 11:04:25.697  6733  6802 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 11:04:25.697  6733  6802 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-27 11:04:25.698  6733  6802 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:04:25.698  6733  6802 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 11:04:25.698  6733  6802 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-27 11:04:25.698  6733  6802 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:04:25.698  6733  6802 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 11:04:25.698  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,07-27 11:04:25.700  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-27 11:04:25.701  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-27 11:04:25.703  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-27 11:04:25.704  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-27 11:04:25.704  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-27 11:04:25.704  6733  6802 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-27 11:04:25.705  6733  6802 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:04:25.705  6733  6802 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-27 11:04:25.705  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.705  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.705  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.705  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.705  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.705  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.705  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-27 11:04:25.705  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.705  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.706  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.706  6733  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
07-27 11:04:25.706  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.706  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.706  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.706  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.706  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.706  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.706  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.706  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:25.706  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:25.707  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.707  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.707  6733  6802 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-27 11:04:25.707  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.707  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.707  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.707  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.707  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.707  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.708  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.708  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.708  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.708  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.708  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.708  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.708  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.708  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.708  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.708  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.708  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:25.708  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:25.708  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.708  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.709  6733  6802 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-27 11:04:25.709  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.710  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.710  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.710  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.710  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.710  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.710  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.710  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.710  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.710  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.710  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.710  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.710  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.710  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.713  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.713  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.714  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:25.714  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:25.714  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.714  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.714  6733  6802 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-27 11:04:25.714  6733  6802 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-27 11:04:25.714  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 11:04:25.715  6733  6802 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-27 11:04:25.715  6733  6802 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-27 11:04:25.715  6733  6802 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-27 11:04:25.715  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 11:04:25.715  6733  6802 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-27 11:04:25.715  6733  6802 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-27 11:04:25.715  6733  6802 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-27 11:04:25.715  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 11:04:25.715  6733  6802 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-27 11:04:25.715  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.715  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.715  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.716  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.716  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.716  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.716  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.716  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.716  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.716  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.716  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.716  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.716  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.716  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.717  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.717  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.717  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:25.717  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:25.717  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.717  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.717  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.717  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.718  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.718  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.718  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.718  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.718  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.718  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.718  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.718  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.718  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.718  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.718  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.718  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.719  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.719  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.720  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.720  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.720  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.720  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.720  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.720  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.720  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.720  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.720  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.720  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.720  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.720  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.720  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.721  6733  6927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
07-27 11:04:25.721  6733  6927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 836)
07-27 11:04:25.721  6733  6927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 836)
07-27 11:04:25.722  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.722  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.725  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:25.725  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:25.725  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.725  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.726  6733  6802 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-27 11:04:25.726  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:04:25.728  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-27 11:04:25.730  6733  6802 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-27 11:04:25.731  6733  6802 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-27 11:04:25.731  6733  6733 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-27 11:04:25.732  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-27 11:04:25.732  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-27 11:04:25.734  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.734  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-27 11:04:25.734  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-27 11:04:25.734  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-27 11:04:25.734  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.734  6733  6802 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-27 11:04:25.736  6733  6733 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-27 11:04:25.736  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.736  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.736  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 11:04:25.736  6733  6802 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 11:04:25.736  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-27 11:04:25.738  1036  1897 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:25.739  6733  6928 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:04:25.739  3871  3890 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
07-27 11:04:25.740  6733  6928 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-27 11:04:25.740  6733  6928 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-27 11:04:25.740  6733  6928 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-27 11:04:25.741  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-27 11:04:25.742  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:25.742  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:25.742  6733  6802 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-27 11:04:25.742  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.742  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.743  6733  6802 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 11:04:25.744  6733  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:04:25.744  6733  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:04:25.744  6733  6733 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-27 11:04:25.744  6733  6733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 11:04:25.744  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.744  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.744  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.744  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.744  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.744  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.744  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.744  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.744  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.744  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.744  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.744  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.745  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.745  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.745  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.745  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.745  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.745  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.745  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.746  6733  6802 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-27 11:04:25.747  6733  6802 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-27 11:04:25.747  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 11:04:25.750  6733  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 11:04:25.750  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.750  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.750  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.751  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.751  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.751  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.751  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.751  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.751  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.751  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.751  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.751  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.751  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.751  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.752  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.752  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.752  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.752  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.753  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:25.754  1036  1990 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:25.755  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:25.755  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.755  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.755  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.756  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.756  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.756  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.756  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.756  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.756  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.756  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.756  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.756  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.756  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.756  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.757  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.757  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.757  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.757  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.759  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:25.759  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:25.759  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:25.775  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:25.775  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.775  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.775  6733  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13084685 not in the list
07-27 11:04:25.775  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.775  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.775  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:25.775  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.775  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:25.775  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:25.775  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:04:25.776  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:25.776  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:25.776  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:25.776  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe0bcda not in the list
07-27 11:04:25.777  6733  6802 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-27 11:04:25.777  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 11:04:25.777  6733  6802 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-27 11:04:25.777  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 11:04:25.777  6733  6802 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-27 11:04:25.777  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 11:04:25.779  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-27 11:04:25.779  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-27 11:04:25.779  6733  6802 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-27 11:04:25.779  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-27 11:04:25.779  6733  6802 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-27 11:04:25.779  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-27 11:04:25.779  6733  6802 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-27 11:04:25.779  6733  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-27 11:04:25.780  6733  6802 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-27 11:04:25.780  6733  6802 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-27 11:04:25.780  6733  6802 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-27 11:04:25.780  6733  6802 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-27 11:04:25.780  6733  6802 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-27 11:04:25.780  6733  6802 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-27 11:04:25.787  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:25.787  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bb90a83 added. We now have 2 listener(s)
07-27 11:04:25.787  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:25.788  6733  6926 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
07-27 11:04:25.788  6733  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting, thread (thread ID: 836)
,07-27 11:04:25.790  6733  6802 D BluetoothAdapter: enable(): BT is already enabled..!
07-27 11:04:25.791  1036  1990 D WifiServiceImplEx: setWifiEnabled: true pid=6733, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-27 11:04:25.791  1036  1990 D WifiService: setWifiEnabled: true pid=6733, uid=10118
07-27 11:04:25.791  1036  1990 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-27 11:04:25.792  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:25.792  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@334f9400 added. We now have 3 listener(s)
07-27 11:04:25.792  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:25.795  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:25.795  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ffa3439 added. We now have 4 listener(s)
07-27 11:04:25.795  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:25.798  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:25.798  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2687ca7e added. We now have 5 listener(s)
07-27 11:04:25.798  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:04:25.804  1036  1052 D WifiServiceImplEx: setWifiEnabled: false pid=6733, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,07-27 11:04:25.804  1036  1052 D WifiService: setWifiEnabled: false pid=6733, uid=10118
07-27 11:04:25.804  1036  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-27 11:04:25.825  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 11:04:25.826  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 11:04:25.826  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,07-27 11:04:25.827  1036  1525 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-27 11:04:25.827  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-27 11:04:25.828  1036  1525 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-27 11:04:25.828  1036  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:25.828  1036  1963 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1b1cdc98 mBinding = false
07-27 11:04:25.828  1036  1525 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-27 11:04:25.828  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-27 11:04:25.828  1036  1525 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-27 11:04:25.829  1036  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:04:25.829  1036  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 11:04:25.829  1036  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 11:04:25.829  1036  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 11:04:25.840  1036  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 11:04:25.840  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,07-27 11:04:25.840  1036  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 11:04:25.840  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:25.840  2752  2752 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 11:04:25.841  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 11:04:25.841  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 11:04:25.841  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
07-27 11:04:25.841  1036  2851 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:25.845   313   891 D CommandListener: Clearing all IP addresses on wlan0
07-27 11:04:25.845  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 11:04:25.846  1036  1118 D BluetoothManagerService: Message: 2
,07-27 11:04:25.846  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 11:04:25.846  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-27 11:04:25.847  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:04:25.847  1036  1118 D BluetoothManagerService: Sending off request.
07-27 11:04:25.848  3871  3892 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-27 11:04:25.848  3871  3959 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-27 11:04:25.848  3871  3959 D BluetoothAdapterProperties: Setting state to 13
07-27 11:04:25.848  3871  3959 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-27 11:04:25.849  3871  3959 D BluetoothAdapterProperties: onBluetoothDisable()
07-27 11:04:25.849  3871  3959 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-27 11:04:25.850  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:25.850  6733  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:04:25.850  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:25.850  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:25.850  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:25.850  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:04:25.850  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:25.850  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:04:25.850  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:04:25.850  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:25.850  6733  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:25.851  6733  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:04:25.851  3871  3966 D BluetoothAdapterProperties: Scan Mode:20
07-27 11:04:25.851  3871  3959 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-27 11:04:25.851  3871  4281 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:04:25.851  3871  3959 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-27 11:04:25.852  3871  4322 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:04:25.852  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
,07-27 11:04:25.853  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:25.853  3871  4323 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:04:25.853  3871  4328 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:04:25.854  3871  4088 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-27 11:04:25.854  3871  4278 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-27 11:04:25.854  3871  4278 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:04:25.854  3871  4278 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-27 11:04:25.854  3871  4278 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-27 11:04:25.854  3871  4278 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-27 11:04:25.854  3871  4278 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-27 11:04:25.854  3871  4278 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-27 11:04:25.854  3871  4278 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-27 11:04:25.855  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:25.856  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:04:25.856  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:04:25.856  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:04:25.856  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:04:25.856  3871  4088 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:04:25.856  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:04:25.856  3871  4088 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:04:25.856  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:04:25.856  3871  4088 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:04:25.856  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-27 11:04:25.856  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-27 11:04:25.856  3871  4088 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-27 11:04:25.858  1036  1118 D BluetoothManagerService: Message: 60
07-27 11:04:25.858  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-27 11:04:25.858  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
07-27 11:04:25.860  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:25.860  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:25.860  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:25.860  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:25.860  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:25.860  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:04:25.860  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:25.860  6733,  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:04:25.860  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:04:25.861  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:25.861  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:25.862  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:25.879  1036  1099 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6941 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,07-27 11:04:25.882  3871  3871 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:25.883  3871  3871 D BluetoothMapService: STATE_TURNING_OFF
07-27 11:04:25.883  3871  3871 V BluetoothMapService: Handler(): got msg=4
07-27 11:04:25.883  3871  3871 D BluetoothMapService: MAP Service closeService in
07-27 11:04:25.883  3871  3871 D BluetoothMapMasInstance: MAP Service shutdown
07-27 11:04:25.883  3871  3871 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 11:04:25.883  3871  3871 V BluetoothMapService: MAP Service closeService out
07-27 11:04:25.884  3871  3871 V BtOppService: Receiver DISABLED_ACTION 
07-27 11:04:25.884  3871  3871 I BtOppRfcommListener: stopping Accept Thread
07-27 11:04:25.884  3871  3871 V BtOppRfcommListener: close mBtServerSocket
07-27 11:04:25.884  3871  3871 V BtOppRfcommListener: waiting for thread to terminate
07-27 11:04:25.885  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:25.885  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 11:04:25.886  3871  4322 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-27 11:04:25.886  3871  3871 V BtOppRfcommListener: done waiting for thread to terminate
07-27 11:04:25.887  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:25.888  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:25.890   351   351 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 239us total 11.183ms
,07-27 11:04:25.897  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-27 11:04:25.897  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
07-27 11:04:25.900  1036  1757 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
07-27 11:04:25.900  1036  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:25.900  1036  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:25.900  1036  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-27 11:04:25.900  1036  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:25.901  1036  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
07-27 11:04:25.901   351   351 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 201us total 10.296ms
07-27 11:04:25.911   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 9.468ms
,07-27 11:04:25.944  1036  1099 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6964 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-27 11:04:25.946  1036  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,07-27 11:04:25.947  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:25.947  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:25.947  1036  1524 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:25.947  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:25.947  1036  1524 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@8708cf
07-27 11:04:25.947  1036  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:25.948  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:25.948  3871  3871 V BtOppService: onDestroy
07-27 11:04:25.948  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:25.948  1036  1531 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-27 11:04:25.948  1036  1525 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-27 11:04:25.948  1036  1531 D DSQN    : disableDataServiceNotify
07-27 11:04:25.948  1036  1531 D DSQN    : stop dsqn bin
07-27 11:04:25.949   313  6974 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-27 11:04:25.949  1036  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:25.949  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:25.949  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-27 11:04:25.950  1036  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
07-27 11:04:25.950  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:25.950  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-27 11:04:25.951  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-27 11:04:25.952  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:25.952  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:25.952  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:25.953  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:25.954  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:25.954  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 11:04:25.956  1036  1036 D WifiHS20: hidePasspointNotification off =false
,07-27 11:04:25.960  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:25.960  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:25.960  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 11:04:25.961  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
07-27 11:04:25.961  1036  1543 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:25.961  1036  1036 D RttService: SCAN_AVAILABLE : 1
07-27 11:04:25.961  1036  1544 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:25.962  1036  1524 D LGWifiP2pService: P2pDisablingState
07-27 11:04:25.963  1036  1524 D LGWifiP2pService: P2pDisablingState{ when=-15ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:25.963  1036  1524 D LGWifiP2pService: p2p socket connection lost
07-27 11:04:25.963  1036  1524 D LGWifiP2pService: P2pDisabledState
07-27 11:04:25.963  1036  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-27 11:04:25.963  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 11:04:25.963  1036  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:25.963  1036  1524 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:25.963  2752  2752 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 11:04:25.964  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 11:04:25.964  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 11:04:25.964  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
07-27 11:04:25.964   313   891 D CommandListener: Clearing all IP addresses on wlan0
07-27 11:04:25.964  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-27 11:04:25.964  1926  1926 D WfdsService: WifiP2pState is changed : false
07-27 11:04:25.965  1926  2309 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-27 11:04:25.965  1926  2309 D WfdsService: Set the WFDS Monitor: false
07-27 11:04:25.965  1926  2309 D WfdsMonitor: WFDS Monitor is stopped
07-27 11:04:25.966  1926  2309 D WfdsService: STATE : WfdsDisabledState - enter
07-27 11:04:25.966  1036  1525 D WifiNative-p2p0: doBoolean: TERMINATE
07-27 11:04:25.966  1926  2311 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-27 11:04:25.966  1926  2789 D CtrlSupplicant: Received on exit socket, terminate
07-27 11:04:25.966  1926  2789 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-27 11:04:25.966  1926  2789 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-27 11:04:25.966  1926  2789 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-27 11:04:25.966  1926  2309 W WfdsService: DefaultState - msg [9445378] is not handled
07-27 11:04:25.966  1036  1525 D WifiNative-p2p0: TERMINATE: returned true
07-27 11:04:25.966  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:04:25.966  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:04:25.966  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 11:04:25.968  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-27 11:04:25.970  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:25.970  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global,, returning read-only value.
07-27 11:04:25.970  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,07-27 11:04:25.974  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-27 11:04:25.974  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:04:25.974  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-27 11:04:25.975  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-27 11:04:25.975  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:25.975  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:25.975  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:25.975  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:25.975  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:04:25.975  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:04:25.975  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:25.975  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:25.975  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:04:25.976  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:25.976  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:04:25.977  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:25.977  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:25.977  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:25.977  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:25.977  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:04:25.977  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:04:25.977  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:25.977  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:25.977  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:04:25.978  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:25.978  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:04:25.987  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:25.987  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-27 11:04:25.988  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:25.988  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 11:04:25.989  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:25.989  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:25.990  1036  1531 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-27 11:04:25.990  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:25.990  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:25.990  1036  1531 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:25.990  1036  1531 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-27 11:04:25.990  1036  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:25.991  1036  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:25.991  1036  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-27 11:04:25.991  1588  2047 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-27 11:04:25.991  1036  1531 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-27 11:04:25.991  1036  1531 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-27 11:04:25.991  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 11:04:25.992  1036  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:25.992  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 11:04:25.992  1036  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-27 11:04:25.992  1036  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:25.993  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-27 11:04:25.993  1036  1531 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:25.993  1036  1531 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:25.993  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 11:04:25.993  1036  1525 D WIFI    : new score 0 for ,exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:25.993  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 11:04:25.993  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 11:04:25.993  1036  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:04:25.993  1036  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-27 11:04:25.993  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-27 11:04:25.993  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 11:04:25.993  1036  1531 D NetworkManagementService: Removing idletimer
07-27 11:04:25.993  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 11:04:25.993  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 11:04:25.994  1036  1531 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:25.994  1838  1838 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:25.994  1036  1531 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-27 11:04:25.994  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 11:04:25.995  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:04:26.015  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:04:26.015  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:26.016  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:26.023  1036  1956 I art     : Explicit concurrent mark sweep GC freed 36419(1842KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.513ms total 155.550ms
07-27 11:04:26.026  3871  3871 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,07-27 11:04:26.037  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:04:26.038  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:26.038  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:04:26.045  6964  6964 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 11:04:26.045  6964  6964 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
07-27 11:04:26.046  6964  6964 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:04:26.046  6964  6964 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
07-27 11:04:26.046  1036  2851 D DhcpStateMachine: StoppedState
07-27 11:04:26.046  1036  2851 D DhcpStateMachine: StoppedState{ when=-81ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:26.046  6964  6964 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-27 11:04:26.047  1036  1525 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-27 11:04:26.047  6964  6964 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-27 11:04:26.047  1036  1525 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
07-27 11:04:26.068  2752  2752 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-27 11:04:26.068  2752  2752 I wpa_supplicant: monitor socket send errors count : 1
07-27 11:04:26.068  2752  2752 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1926-2\x00 that cannot receive messages
07-27 11:04:26.069  1036  2772 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-27 11:04:26.069  1036  2772 D WifiMonitor: Dropping event because (p2p0) is stopped
,07-27 11:04:26.094  6941  6941 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-27 11:04:26.094  6941  6941 W LG Account v2.2: No ProfileInfo entries
07-27 11:04:26.094  6941  6941 I LG Account v2.2: isEnabled: false
,07-27 11:04:26.094  6941  6941 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-27 11:04:26.094  6941  6941 I Feature : [Lifetracker]Country: EU
07-27 11:04:26.094  6941  6941 I Feature : [Lifetracker]Operator: OPEN
07-27 11:04:26.094  6941  6941 I Feature : [Lifetracker]Ranking support: false
07-27 11:04:26.094  6941  6941 I Feature : [Lifetracker]Comfort support: false
07-27 11:04:26.094  6941  6941 I Feature : [Lifetracker]Accessory: true
07-27 11:04:26.094  6941  6941 I Feature : [Lifetracker]Health device: true
07-27 11:04:26.094  6941  6941 I Feature : [Lifetracker]Extra Pedometer: false
07-27 11:04:26.094  6941  6941 I Feature : [Lifetracker]Blood glucose device: false
07-27 11:04:26.094  6941  6941 I Feature : [Lifetracker]Device Number: 3
07-27 11:04:26.102  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:26.105  2752  2752 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 11:04:26.106  2752  2752 W wpa_supplicant: USIM:  scard_deinit function
07-27 11:04:26.106  1036  2772 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-27 11:04:26.106  1036  2772 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 11:04:26.106  1036  2772 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 11:04:26.106  1036  2772 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-27 11:04:26.107  1036  2772 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,07-27 11:04:26.107  1036  2772 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:04:26.107  1036  1118 D Tethering: InitialState.processMessage what=4
07-27 11:04:26.107  1036  1525 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=117079
07-27 11:04:26.108  1036  1525 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=117079
07-27 11:04:26.108  1036  1525 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=117080  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-27 11:04:26.108  1036  1525 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=117080  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-27 11:04:26.138  6964  6964 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-27 11:04:26.140  1036  1763 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6984 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 11:04:26.141  1036  1763 I ActivityManager: Killing 6283:com.android.providers.calendar/u0a14 (adj 15): empty #17
07-27 11:04:26.168  2752  2752 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-27 11:04:26.169  1036  2772 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-27 11:04:26.169  1036  2772 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
07-27 11:04:26.169  1036  2772 D WifiMonitor: Disconnecting from the supplicant, no more events
07-27 11:04:26.169  1036  1525 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,07-27 11:04:26.174  3871  3871 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 11:04:26.174  3871  3871 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:26.174  3871  3871 V BluetoothPbapReceiver: ***********state = 13
07-27 11:04:26.175  3871  3871 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-27 11:04:26.176  1036  2017 W libprocessgroup: failed to open /acct/uid_10014/pid_6283/cgroup.procs: No such file or directory
07-27 11:04:26.177  3871  3871 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:26.177  3871  3871 V BluetoothPbapService: state: 13
07-27 11:04:26.177  3871  3871 V BluetoothPbapService: Pbap Service closeService in
07-27 11:04:26.178  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-27 11:04:26.178  1036  1118 D BluetoothManagerService: Message: 20
07-27 11:04:26.180  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ac95462:true
07-27 11:04:26.180  2231  2231 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 11:04:26.181  3871  3871 V BluetoothPbapService: successfully stopped pbap service
07-27 11:04:26.181  3871  3871 V BluetoothPbapService: Pbap Service closeService out
07-27 11:04:26.181  3871  3871 V BluetoothPbapService: Pbap Service onDestroy
07-27 11:04:26.181  3871  3871 V BluetoothPbapService: Pbap Service closeService in
07-27 11:04:26.181  3871  3871 V BluetoothPbapService: Pbap Service closeService out
07-27 11:04:26.181  3871  3871 D LGBluetoothPbapAdapter: [BTUI] cleanup
,07-27 11:04:26.192  1036  1118 D BluetoothManagerService: Message: 30
07-27 11:04:26.196  1036  1118 D BluetoothManagerService: Message: 30
,07-27 11:04:26.199  6964  6964 D LocalBluetoothProfileManager: Adding local MAP profile
07-27 11:04:26.200  6964  6964 D BluetoothMap: Create BluetoothMap proxy object
07-27 11:04:26.201  1036  1118 D BluetoothManagerService: Message: 30
07-27 11:04:26.204  1036  1118 D BluetoothManagerService: Message: 30
07-27 11:04:26.206  6964  6964 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-27 11:04:26.207  6964  6964 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
07-27 11:04:26.222  6964  6964 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,07-27 11:04:26.223  6984  6984 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 11:04:26.225  6964  6964 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
07-27 11:04:26.226  6984  6984 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 11:04:26.228  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:04:26.230  1036  1956 I ActivityManager: Killing 6385:com.android.defcontainer/u0a4 (adj 15): empty #17
07-27 11:04:26.270  1036  1963 W libprocessgroup: failed to open /acct/uid_10004/pid_6385/cgroup.procs: No such file or directory
07-27 11:04:26.270  6964  6964 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:04:26.274  1036  1525 D WifiOffDelayIfNotUsed: stopMonitoring
07-27 11:04:26.274  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:04:26.274  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:04:26.274  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 11:04:26.274  1926  1926 D WfdsService: Supplicant Connection state is changed : false
07-27 11:04:26.274  1926  2309 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-27 11:04:26.274  1926  2309 D WfdsService: Set the WFDS Monitor: false
07-27 11:04:26.274  1926  2309 D WfdsMonitor: WFDS Monitor is stopped
07-27 11:04:26.275  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:26.275  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-27 11:04:26.276  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-27 11:04:26.276  1036  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-27 11:04:26.277  1036  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-27 11:04:26.277  2495  2495 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:26.279  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:26.280  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:26.280  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:26.280  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:26.280  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:04:26.280  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:04:26.280  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:26.280  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:26.280  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:04:26.281  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:26.281  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:26.281  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:26.281  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:26.281  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:04:26.281  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:04:26.281  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:26.281  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:26.281  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:04:26.290  6964  6964 D BluetoothInputDevice: Proxy object connected
07-27 11:04:26.292  6964  6964 D HidProfile: Bluetooth service connected
,07-27 11:04:26.298  6964  6964 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 11:04:26.300  6964  6964 D PanProfile: Bluetooth service connected
07-27 11:04:26.301  6964  6964 D BluetoothMap: Proxy object connected
07-27 11:04:26.303  6964  6964 D MapProfile: Bluetooth service connected
07-27 11:04:26.303  6964  6964 D BluetoothMap: getConnectedDevices()
07-27 11:04:26.304  6964  6964 D BluetoothMap: Bluetooth is Not enabled
,07-27 11:04:26.305  6964  6964 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,07-27 11:04:26.324  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:26.365  6964  6964 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:04:26.365  6964  6964 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:04:26.378  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:26.383  6964  6964 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-27 11:04:26.392  6964  6964 D BluetoothPermissionRequest: onReceive
07-27 11:04:26.395  6964  6964 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-27 11:04:26.406  1036  1051 I ActivityManager: Killing 6586:com.google.android.partnersetup/u0a8 (adj 15): empty #17
07-27 11:04:26.408  6964  6964 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-27 11:04:26.477  1036  1525 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
,07-27 11:04:26.479  1036  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,07-27 11:04:26.500  3871  3871 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-27 11:04:26.501  3871  3871 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-27 11:04:26.503  1036  1929 W libprocessgroup: failed to open /acct/uid_10008/pid_6586/cgroup.procs: No such file or directory
,07-27 11:04:26.503  3871  3871 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-27 11:04:26.532  1036  1362 V AlarmManager: RTC_WAKEUP set : Alarm{37c4596a type 0 when 1469610265109 com.android.vending} when 1469610265109
,07-27 11:04:26.609  1036  1051 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7012 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
07-27 11:04:26.610  3871  3871 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:26.610  3871  3871 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,07-27 11:04:26.615  3871  3871 V BluetoothFtpService: Ftp Service onStartCommand
07-27 11:04:26.615  3871  3871 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:26.616  3871  3871 V BluetoothFtpService: Ftp Service closeService
07-27 11:04:26.616  3871  3871 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-27 11:04:26.617  3871  3871 V BluetoothFtpService: successfully stopped ftp service
07-27 11:04:26.618  3871  3871 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 11:04:26.618  3871  3871 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 11:04:26.618  3871  3871 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 11:04:26.618  3871  3871 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:26.618  3871  3871 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-27 11:04:26.618  3871  3871 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-27 11:04:26.619  3871  3871 V BluetoothFtpService: Ftp Service onDestroy
07-27 11:04:26.619  3871  3871 V BluetoothFtpService: Ftp Service closeService
07-27 11:04:26.630  1036  1963 V SIM_STK : Menu title from STK is T-Mobile
,07-27 11:04:26.663  1036  1052 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7029 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-27 11:04:26.668  3871  3871 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:04:26.668  3871  3871 V BluetoothSapService: state: 13
07-27 11:04:26.668  3871  3871 V BluetoothSapService: Stopping SAP server process
07-27 11:04:26.669  3871  3871 V BluetoothSapService: Sap Service closeSapService in
07-27 11:04:26.669  3871  3871 V BluetoothSapService: Close listen Socket : 
07-27 11:04:26.669  3871  3871 V BluetoothSapService: Close rfcomm Socket : 
07-27 11:04:26.669  3871  3871 V BluetoothSapService: Close sapd  Socket : 
07-27 11:04:26.670  3871  3871 V BluetoothSapService: Sap Service closeSapService out
07-27 11:04:26.670  3871  3871 V BluetoothSapService: Sap Service onDestroy
07-27 11:04:26.670  3871  3871 V BluetoothSapService: Sap Service closeSapService in
07-27 11:04:26.671  3871  3871 V BluetoothSapService: Close listen Socket : 
07-27 11:04:26.671  3871  3871 V BluetoothSapService: Close rfcomm Socket : 
07-27 11:04:26.671  3871  3871 V BluetoothSapService: Close sapd  Socket : 
07-27 11:04:26.671  3871  3871 V BluetoothSapService: Sap Service closeSapService out
07-27 11:04:26.692  7012  7012 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-27 11:04:26.708  7029  7029 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-27 11:04:26.716  7012  7012 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,07-27 11:04:26.740  7012  7012 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
07-27 11:04:26.741  7012  7012 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-27 11:04:26.741  7012  7012 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,07-27 11:04:26.741  7012  7012 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-27 11:04:26.742  7012  7012 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-27 11:04:26.743  7012  7012 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-27 11:04:26.747  7012  7012 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-27 11:04:26.751  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 11:04:26.753  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 11:04:26.766  7012  7012 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 11:04:26.768  7012  7012 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,07-27 11:04:26.770  7012  7012 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-27 11:04:26.770  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:26.772  6984  6984 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 11:04:26.772  6984  6984 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 11:04:26.772  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:04:26.774  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:04:26.779  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 11:04:26.786  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:26.786  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:26.787  7012  7012 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 11:04:26.791  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:04:26.796  6984  6984 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 11:04:26.797  6984  6984 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 11:04:26.797  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:04:26.800  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:26.808  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:26.816  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 11:04:26.817  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:26.820  7012  7012 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 11:04:26.855  6196  6196 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,07-27 11:04:26.861  3871  4088 W bt-btif : ag scb idx 1 not allocated
07-27 11:04:26.861  3871  4088 E bt-btif : BTA AG is already disabled, ignoring ...
07-27 11:04:26.861  3871  3966 D bt_hci_bdroid: cleanup
07-27 11:04:26.861  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:04:26.862  3871  4093 I bt_lpm  : LPM is already off!!!
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:04:26.862  3871  4088 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:04:26.862  3871  4088 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-27 11:04:26.862  3871  4249 I bt_userial_mct: exiting userial_read_thread
07-27 11:04:26.862  3871  4249 D bt_userial_mct: Leaving userial_evt_read_thread()
07-27 11:04:26.863  3871  3966 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-27 11:04:26.863  3871  4093 I bt_vendor: hw_epilog_process
07-27 11:04:26.863  3871  3966 D bt_hci_bdroid: cleanup Finalizing cleanup
07-27 11:04:26.863  3871  3966 D bt_userial_mct: userial_close
07-27 11:04:26.863  3871  3966 E bt_userial_mct: pthread_join() FAILED result:3
07-27 11:04:26.863  3871  3966 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-27 11:04:26.869  1036  1990 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7050 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-27 11:04:26.875  1036  1929 I ActivityManager: Killing 6119:com.lge.appbox.client/u0a11 (adj 15): empty #17
07-27 11:04:26.918  1036  1963 W libprocessgroup: failed to open /acct/uid_10011/pid_6119/cgroup.procs: No such file or directory
,07-27 11:04:26.927  3871  3966 D bt_hci_bdroid: set_power 0
07-27 11:04:26.927  3871  3966 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-27 11:04:26.927  3871  3966 I bt_vendor: bluetooth satus is on
07-27 11:04:26.927  3871  3966 I bt_vendor: bt-vendor : resetting BT status
07-27 11:04:26.927  3871  3966 I bt_vendor: Starting hciattach daemon
07-27 11:04:26.927  3871  3966 I bt_vendor: try to set false
07-27 11:04:26.928  3871  3966 I bt_vendor: Starting hciattach daemon
07-27 11:04:26.928  3871  3966 I bt_vendor: try to set false
07-27 11:04:26.929  3871  3966 I bt_vendor: cleanup
07-27 11:04:26.930  3871  4088 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-27 11:04:26.930  3871  3966 I GKI_LINUX: GKI_exit_task 0 done
07-27 11:04:26.930  3871  3966 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-27 11:04:26.932  3871  3959 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,07-27 11:04:26.938  3871  3871 D HeadsetService: Received stop request...Stopping profile...
07-27 11:04:26.939  3871  3871 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-27 11:04:26.940  3871  3871 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 11:04:26.940  3871  3995 D HeadsetStateMachine: Exit Disconnected: -1
07-27 11:04:26.940  3871  3871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a7edf0e
07-27 11:04:26.941  1036  1036 D BluetoothHeadset: Proxy object disconnected
07-27 11:04:26.941  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-27 11:04:26.941  1838  1838 D BluetoothHeadset: Proxy object disconnected
07-27 11:04:26.941  1838  1838 D BluetoothHeadset: Proxy object disconnected
07-27 11:04:26.942  1838  1838 D BluetoothHeadset: Proxy object disconnected
07-27 11:04:26.943  3871  3871 D A2dpService: Received stop request...Stopping profile...
07-27 11:04:26.944  3871  3871 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-27 11:04:26.944  3871  4050 D A2dpStateMachine: Exit Disconnected: -1
07-27 11:04:26.948  3871  3959 D BluetoothAdapterState: Stopping profile services that were post enabled
07-27 11:04:26.948  3871  3871 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-27 11:04:26.948  3871  3871 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 11:04:26.948  3871  3871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a7edf0e
07-27 11:04:26.949  1036  1036 D BluetoothA2dp: Proxy object disconnected
07-27 11:04:26.949  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,07-27 11:04:26.950  3871  3871 D HidService: Received stop request...Stopping profile...
07-27 11:04:26.950  3871  3871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a7edf0e
07-27 11:04:26.952  3871  3871 D HeadsetStateMachine: Unbinding service...
07-27 11:04:26.952  6964  6964 D BluetoothInputDevice: Proxy object disconnected
07-27 11:04:26.952  6964  6964 D HidProfile: Bluetooth service disconnected
07-27 11:04:26.953  3871  3871 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 11:04:26.953  3871  3871 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 11:04:26.953  3871  3871 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 11:04:26.953  3871  3871 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 11:04:26.953  3871  3871 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-27 11:04:26.953  3871  3871 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 11:04:26.953  3871  3871 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-27 11:04:26.955  3871  3871 D HealthService: Received stop request...Stopping profile...
07-27 11:04:26.955  3871  3871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a7edf0e
07-27 11:04:26.956  3871  3871 D PanService: Received stop request...Stopping profile...
07-27 11:04:26.957  3871  3871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a7edf0e
07-27 11:04:26.958  6964  6964 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-27 11:04:26.958  6964  6964 D PanProfile: Bluetooth service disconnected
07-27 11:04:26.958  3871  3871 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 11:04:26.959  3871  3871 D BtGatt.GattService: Received stop request...Stopping profile...
07-27 11:04:26.959  3871  3871 D BtGatt.GattService: stop()
07-27 11:04:26.960  3871  3871 D BtGatt.AdvertiseManager: advertise clients cleared
07-27 11:04:26.960  3871  3871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a7edf0e
07-27 11:04:26.962  3871  3871 D BluetoothMapService: Received stop request...Stopping profile...
07-27 11:04:26.962  3871  3871 D BluetoothMapService: stop()
,07-27 11:04:26.962  3871  3871 D BluetoothMapEmailAppObserver: deinitObservers()
07-27 11:04:26.963  3871  3871 D BluetoothMapEmailAppObserver: removeReceiver()
07-27 11:04:26.963  3871  3871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a7edf0e
07-27 11:04:26.964  3871  3871 I BluetoothA2dpServiceJni: cleanupNative
07-27 11:04:26.964  3871  4052 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-27 11:04:26.965  3871  3871 I GKI_LINUX: GKI_exit_task 2 done
07-27 11:04:26.965  3871  3871 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-27 11:04:26.965  3871  3871 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-27 11:04:26.965  3871  3871 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-27 11:04:26.966  3871  3871 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-27 11:04:26.966  3871  3871 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 11:04:26.966  3871  3871 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 11:04:26.966  3871  3871 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-27 11:04:26.966  3871  3871 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-27 11:04:26.967  6964  6964 D BluetoothMap: Proxy object disconnected
07-27 11:04:26.967  6964  6964 D MapProfile: Bluetooth service disconnected
07-27 11:04:26.968  3871  3871 V BluetoothMapService: Handler(): got msg=4
07-27 11:04:26.968  3871  3871 D BluetoothMapService: MAP Service closeService in
07-27 11:04:26.968  3871  3871 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 11:04:26.968  3871  3871 V BluetoothMapService: MAP Service closeService out
07-27 11:04:26.968  3871  3959 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-27 11:04:26.968  3871  3959 D BluetoothAdapterProperties: Setting state to 10
07-27 11:04:26.968  3871  3959 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-27 11:04:26.969  3871  3871 D BluetoothMapService: cleanup()
07-27 11:04:26.969  3871  3871 D BluetoothMapService: MAP Service closeService in
07-27 11:04:26.969  3871  3871 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 11:04:26.969  3871  3871 V BluetoothMapService: MAP Service closeService out
07-27 11:04:26.969  1036  1118 D BluetoothManagerService: Message: 60
07-27 11:04:26.969  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-27 11:04:26.969  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
07-27 11:04:26.969  3871  3959 I BluetoothAdapterState: Entering OffState
07-27 11:04:26.970  6964  6981 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-27 11:04:26.970  1838  2456 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:04:26.971  6964  6980 D BluetoothMap: onBluetoothStateChange: up=false
07-27 11:04:26.972  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 11:04:26.972  6964  6981 D BluetoothPan: onBluetoothStateChange on: false
07-27 11:04:26.973  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:04:26.973  1838  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:04:26.973  1838  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:04:26.974  6964  6980 D BluetoothPbap: onBluetoothStateChange: up=false
07-27 11:04:26.975  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-27 11:04:26.975  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,07-27 11:04:26.978  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-27 11:04:26.978  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-27 11:04:26.978  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1b1cdc98 mBinding = false
07-27 11:04:26.979  1036  1118 D BluetoothManagerService: Sending unbind request.
07-27 11:04:26.980  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-27 11:04:26.981  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:26.982  1926  2110 D LGBluetoothAPIService: Message: 2
07-27 11:04:26.982  1926  2110 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@ad1b19 mBinding = false
07-27 11:04:26.982  1926  2110 D LGBluetoothAPIService: Sending unbind request.
07-27 11:04:26.983  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 11:04:26.985  6964  6964 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 11:04:26.986  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:26.987  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:26.990  6964  6964 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-27 11:04:26.990  6964  6964 D LGBluetoothEventManager: [BTUI] clear device connection state
07-27 11:04:26.990  3871  3966 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-27 11:04:26.991  3871  3871 I GKI_LINUX: GKI_exit_task 1 done
07-27 11:04:26.991  3871  3871 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-27 11:04:26.991  3871  3871 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-27 11:04:26.992  3871  3871 I art     : --- WEIRD: removing null entry 246
,07-27 11:04:26.992  3871  3871 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
07-27 11:04:26.992  3871  3871 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-27 11:04:26.992  3871  3871 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-27 11:04:26.992  1588  1588 D BluetoothAdapter: 775230054: getState() :  mService = null. Returning STATE_OFF
07-27 11:04:26.992  1588  1588 D BluetoothAdapter: 775230054: getState() :  mService = null. Returning STATE_OFF
07-27 11:04:26.994  6964  6964 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-27 11:04:26.996  3871  3871 I art     : System.exit called, status: 0
07-27 11:04:26.996  3871  3871 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-27 11:04:27.002  6964  6964 D DockEventReceiver: finishStartingService: stopping service
07-27 11:04:27.011  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 11:04:27.014  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:04:27.018   317  2135 V AudioFlinger: 3871 died, releasing its sessions
07-27 11:04:27.018   317  2135 V AudioFlinger:  pid 1838 @ 0
07-27 11:04:27.018   317  2135 V AudioFlinger:  pid 3467 @ 1
07-27 11:04:27.018   317  2135 V AudioFlinger:  pid 3467 @ 2
07-27 11:04:27.021  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:27.022  6964  6964 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-27 11:04:27.037  1036  1757 I ActivityManager: Process com.android.bluetooth (pid 3871) has died
07-27 11:04:27.037  1036  1757 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,07-27 11:04:27.046  2231  2231 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 11:04:27.053  7050  7072 W FormManager: Network not available. Please check & try again.
,07-27 11:04:27.066  6964  6964 D BluetoothPermissionRequest: onReceive
,07-27 11:04:27.073  6964  6964 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-27 11:04:27.073  6964  6964 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-27 11:04:27.079  6964  6964 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-27 11:04:27.155  1036  1366 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7075 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-27 11:04:27.163  7050  7073 V FormManager: Network unavailable.
07-27 11:04:27.166  7050  7073 V FormManager: Network unavailable.
07-27 11:04:27.180  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 11:04:27.180  6964  6964 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 11:04:27.180  6964  6964 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 11:04:27.180  6964  6964 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 11:04:27.181  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-27 11:04:27.193  6964  6964 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 11:04:27.193  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-27 11:04:27.193  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,07-27 11:04:27.193  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,07-27 11:04:27.193  6964  6964 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 11:04:27.194  6964  6964 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 11:04:27.195  1036  1963 I ActivityManager: Killing 6144:com.android.contacts/u0a19 (adj 15): empty #17
07-27 11:04:27.229  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,07-27 11:04:27.229  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:04:27.231  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:04:27.236  1036  1956 W libprocessgroup: failed to open /acct/uid_10019/pid_6144/cgroup.procs: No such file or directory
07-27 11:04:27.245  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 11:04:27.254  7075  7075 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-27 11:04:27.255  7075  7075 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:04:27.255  7075  7075 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-27 11:04:27.256  7075  7075 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-27 11:04:27.256  4297  7093 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 11:04:27.259  4297  7094 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 11:04:27.260  4297  7094 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-27 11:04:27.265  6984  6984 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-27 11:04:27.265  6984  6984 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 11:04:27.265  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:04:27.274  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:04:27.278  7050  7096 W FormManager: Network not available. Please check & try again.
07-27 11:04:27.282  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:27.292  7075  7075 D BluetoothAdapterApp: Loading JNI Library
,07-27 11:04:27.295  7050  7097 V FormManager: Network unavailable.
07-27 11:04:27.299  7050  7097 V FormManager: Network unavailable.
07-27 11:04:27.305  7012  7012 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,07-27 11:04:27.306  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,07-27 11:04:27.307  7012  7012 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
07-27 11:04:27.335  7075  7075 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@12d6ee37 Instance Count = 1
,07-27 11:04:27.340  7075  7075 D BluetoothAdapterApp: onCreate
07-27 11:04:27.354  7012  7012 D LgDataFeature: LgDataFeature() Constructor: none
,07-27 11:04:27.355  7012  7012 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 11:04:27.362  7075  7075 D ProfileConfigQcom: [BTUI] HeadsetService is supported
07-27 11:04:27.362  7075  7075 D ProfileConfigQcom: Adding HeadsetService
07-27 11:04:27.362  7075  7075 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-27 11:04:27.363  7075  7075 D ProfileConfigQcom: Adding A2dpService
07-27 11:04:27.363  7075  7075 D ProfileConfigQcom: [BTUI] HidService is supported
07-27 11:04:27.363  7075  7075 D ProfileConfigQcom: Adding HidService
07-27 11:04:27.363  7075  7075 D ProfileConfigQcom: [BTUI] HealthService is supported
,07-27 11:04:27.363  7012  7012 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-27 11:04:27.364  7075  7075 D ProfileConfigQcom: Adding HealthService
07-27 11:04:27.364  7075  7075 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-27 11:04:27.364  7012  7012 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-27 11:04:27.364  7012  7012 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-27 11:04:27.365  7012  7012 V SoundPool: doLoad: loading sample sampleID=1
07-27 11:04:27.365  7075  7075 D ProfileConfigQcom: [BTUI] PanService is supported
07-27 11:04:27.365  7075  7075 D ProfileConfigQcom: Adding PanService
07-27 11:04:27.365  7012  7012 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-27 11:04:27.365  7075  7075 D ProfileConfigQcom: [BTUI] GattService is supported
07-27 11:04:27.365  7075  7075 D ProfileConfigQcom: Adding GattService
07-27 11:04:27.366  7075  7075 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-27 11:04:27.366  7075  7075 D ProfileConfigQcom: Adding BluetoothMapService
07-27 11:04:27.366  7075  7075 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,07-27 11:04:27.368  7012  7101 V SoundPool: Start decode
07-27 11:04:27.368  7012  7101 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-27 11:04:27.368  7075  7075 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-27 11:04:27.372  7012  7012 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-27 11:04:27.372   317   317 V MediaPlayerService: decode(23, 10857164, 17813)
07-27 11:04:27.372   317   317 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-27 11:04:27.372   317   317 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-27 11:04:27.372   317   317 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-27 11:04:27.373  6859  6859 D UEI.SmartControl: QS Service created
07-27 11:04:27.373   317   317 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-27 11:04:27.373   317   317 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-27 11:04:27.373   317   317 V MediaPlayerService: player type = 3
07-27 11:04:27.373   317   317 V AwesomePlayer: AwesomePlayer create()
07-27 11:04:27.373  6964  6964 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-27 11:04:27.374   317   317 V AwesomePlayer: reset_l() 
07-27 11:04:27.374   317   317 V AwesomePlayer: cancelPlayerEvents
07-27 11:04:27.374   317   317 V AwesomePlayer: setAudioSink() 
07-27 11:04:27.374   317   317 V AwesomePlayer: reset_l() 
07-27 11:04:27.374   317   317 V AudioCache: notify(0xb16a6780, 8, 0, 0)
07-27 11:04:27.374   317   317 V AudioCache: ignored
07-27 11:04:27.374   317   317 V AwesomePlayer: cancelPlayerEvents
07-27 11:04:27.374   317   317 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
07-27 11:04:27.374   317   317 V AwesomePlayer: setDataSource_l dataSource
07-27 11:04:27.374   317   317 V LGParserOSAL: SniffLGParser start
07-27 11:04:27.374   317   317 V LGParserOSAL: MainType:5, SubType=0
07-27 11:04:27.374   317   317 V LGParserOSAL: #### check Mime : application/ogg
07-27 11:04:27.374   317   317 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-27 11:04:27.374   317   317 E MediaExtractor: Use LGExtractor :application/ogg 
07-27 11:04:27.375  7075  7075 V LGMDMManagerInternal: Create singleton instance
07-27 11:04:27.377  7012  7012 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-27 11:04:27.379  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,07-27 11:04:27.395  6859  6859 I UEI.SmartControl: Service initServices...
07-27 11:04:27.396  6859  6859 D UEI.SmartControl: QS start get config
07-27 11:04:27.406  7012  7012 V LGMDMManager: Create singleton instance
07-27 11:04:27.409   317   317 V LGParserOSAL: supported mime: application/ogg
07-27 11:04:27.409   317   317 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-27 11:04:27.409   317   317 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-27 11:04:27.409   317   317 V AwesomePlayer: mBitrate = -1 bits/sec
07-27 11:04:27.409   317   317 V AwesomePlayer: AudioTrack Setting
07-27 11:04:27.409   317   317 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-27 11:04:27.409   317   317 V AwesomePlayer: setAudioSource() 
07-27 11:04:27.409   317   317 V MediaPlayerService: prepare
07-27 11:04:27.409   317   317 V AwesomePlayer: prepareAsync_l() 
07-27 11:04:27.409   317   317 V MediaPlayerService: wait for prepare
07-27 11:04:27.410   317  7102 V AwesomePlayer: onPrepareAsyncEvent() 
07-27 11:04:27.410   317  7102 V AwesomePlayer: initAudioDecoder() 
07-27 11:04:27.410   317  7102 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 11:04:27.410   317  7102 V AudioSystem: isOffloadSupported()
07-27 11:04:27.410   317  7102 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-27 11:04:27.410   317  7102 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 11:04:27.410   317  7102 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 11:04:27.410   317  7102 V AwesomePlayer: getUseOffload() = 0 
07-27 11:04:27.410   317  7102 V OMXCodec: OMXCodec::Create
07-27 11:04:27.410   317  7102 V OMXCodec: findMatchingCodecs()
07-27 11:04:27.410   317  7102 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-27 11:04:27.410   317  7102 V OMXCodec: matchingCodecs.size()=1
07-27 11:04:27.410   317  7102 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,07-27 11:04:27.411   317  7102 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-27 11:04:27.411   317  7102 V LGCodecAdapter: LG Codec Adapter start
07-27 11:04:27.412   317  7102 V OMXCodec: OMXCodec Createtor
07-27 11:04:27.412   317  7102 V OMXCodec: setComponentRole
07-27 11:04:27.412   317  7102 V OMXCodec: configureCodec protected=0
07-27 11:04:27.412   317  7102 V LGCodecAdapter: called getLGCodecSpecificData
07-27 11:04:27.412   317  7102 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-27 11:04:27.412   317  7102 V LGCodecOSAL: Called LGconfigureCodecMETA
07-27 11:04:27.412   317  7102 V LGCodecOSAL: Called LGconfigureCodecMSG
07-27 11:04:27.412   317  7102 V LGCodecOSAL: Not support LGCodec
07-27 11:04:27.412   317  7102 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 11:04:27.412   317  7102 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-27 11:04:27.412   317  7102 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-27 11:04:27.412   317  7102 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-27 11:04:27.412   317  7102 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 11:04:27.412   317  7102 V AudioSystem: isOffloadSupported()
07-27 11:04:27.412   317  7102 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-27 11:04:27.412   317  7102 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 11:04:27.413   317  7102 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-27 11:04:27.413   317  7102 V OMXCodec: init()
07-27 11:04:27.413   317  7102 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-27 11:04:27.413   317  7102 V OMXCodec: allocateBuffers
07-27 11:04:27.413   317  7102 V OMXCodec: allocateBuffersOnPort portIndex=0
07-27 11:04:27.413   317  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-27 11:04:27.413   317  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
07-27 11:04:27.414   317  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
07-27 11:04:27.414   317  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
07-27 11:04:27.414   317  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
07-27 11:04:27.414   317  7102 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 11:04:27.414   317  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 11:04:27.414   317  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
07-27 11:04:27.414   317  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
07-27 11:04:27.414   317  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd150 on output port
07-27 11:04:27.414   317  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd600 on output port
07-27 11:04:27.414   317  7102 V OMXCodec: init() mAsyncCompletion wait!!! 
07-27 11:04:27.414   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 11:04:27.414   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 11:04:27.414   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-27 11:04:27.414   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-27 11:04:27.414   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-27 11:04:27.414   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
07-27 11:04:27.417   317  7102 V OMXCodec: init() mAsyncCompletion wait free! 
07-27 11:04:27.417   317  7102 V AwesomePlayer: finishAsyncPrepare_l() 
07-27 11:04:27.417   317  7102 V AudioCache: notify(0xb16a6780, 5, 0, 0)
07-27 11:04:27.417   317  7102 V AudioCache: ignored
07-27 11:04:27.417   317  7102 V AudioCache: notify(0xb16a6780, 1, 0, 0)
07-27 11:04:27.417   317  7102 V AudioCache: prepared
07-27 11:04:27.417   317   317 V AudioCache: wait - success
07-27 11:04:27.417   317   317 V MediaPlayerService: start
07-27 11:04:27.417   317   317 V AwesomePlayer: play_l() 
07-27 11:04:27.417   317   317 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-27 11:04:27.417   317   317 V AwesomePlayer: createAudioPlayer_l
07-27 11:04:27.417   317   317 V AwesomePlayer: seekAudioIfNecessary_l() 
07-27 11:04:27.417   317   317 V AwesomePlayer: startAudioPlayer_l() 
07-27 11:04:27.417   317   317 D AudioPlayer: start of Playback, useOffload 0
07-27 11:04:27.417   317   317 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 11:04:27.417   317   317 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044790608
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044791808
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-27 11:04:27.419   317  7104 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 11:04:27.419   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd150 on output port
07-27 11:04:27.420   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
07-27 11:04:27.420   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
07-27 11:04:27.420   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on output port
07-27 11:04:27.420   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-27 11:04:27.420   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-27 11:04:2,7.420   317   317 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-27 11:04:27.421   317   317 V AudioCache: notify(0xb16a6780, 6, 0, 0)
07-27 11:04:27.421   317   317 V AudioCache: ignored
07-27 11:04:27.421   317   317 V MediaPlayerService: wait for playback complete
07-27 11:04:27.422   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.422   317  7105 V AudioCache: memcpy(0xaf004000, 0xb16f5000, 4096)
07-27 11:04:27.423   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.423   317  7105 V AudioCache: memcpy(0xaf005000, 0xb16f5000, 4096)
07-27 11:04:27.423   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.423   317  7105 V AudioCache: memcpy(0xaf006000, 0xb16f5000, 4096)
07-27 11:04:27.424   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.424   317  7105 V AudioCache: memcpy(0xaf007000, 0xb16f5000, 4096)
07-27 11:04:27.424   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.424   317  7105 V AudioCache: memcpy(0xaf008000, 0xb16f5000, 4096)
07-27 11:04:27.425   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.425   317  7105 V AudioCache: memcpy(0xaf009000, 0xb16f5000, 4096)
07-27 11:04:27.425   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.425   317  7105 V AudioCache: memcpy(0xaf00a000, 0xb16f5000, 4096)
07-27 11:04:27.425   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.425   317  7105 V AudioCache: memcpy(0xaf00b000, 0xb16f5000, 4096)
07-27 11:04:27.426   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.426   317  7105 V AudioCache: memcpy(0xaf00c000, 0xb16f5000, 4096)
07-27 11:04:27.426   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.426   317  7105 V AudioCache: memcpy(0xaf00d000, 0xb16f5000, 4096)
07-27 11:04:27.427   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.427   317  7105 V AudioCache: memcpy(0xaf00e000, 0xb16f5000, 4096)
07-27 11:04:27.427   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.427   317  7105 V AudioCache: memcpy(0xaf00f000, 0xb16f5000, 4096)
07-27 11:04:27.427   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.427   317  7105 V AudioCache: memcpy(0xaf010000, 0xb16f5000, 4096)
07-27 11:04:27.428   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.428   317  7105 V AudioCache: memcpy(0xaf011000, 0xb16f5000, 4096)
07-27 11:04:27.428   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.428   317  7105 V AudioCache: memcpy(0xaf012000, 0xb16f5000, 4096)
07-27 11:04:27.429   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.429   317  7105 V AudioCache: memcpy(0xaf013000, 0xb16f5000, 4096)
07-27 11:04:27.429   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.429   317  7105 V AudioCache: memcpy(0xaf014000, 0xb16f5000, 4096)
07-27 11:04:27.430   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.430   317  7105 V AudioCache: memcpy(0xaf015000, 0xb16f5000, 4096)
07-27 11:04:27.430   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.430   317  7105 V AudioCache: memcpy(0xaf016000, 0xb16f5000, 4096)
07-27 11:04:27.431   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.431   317  7105 V AudioCache: memcpy(0xaf017000, 0xb16f5000, 4096)
07-27 11:04:27.431   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.431   317  7105 V AudioCache: memcpy(0xaf018000, 0xb16f5000, 4096)
07-27 11:04:27.431   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.431   317  7105 V AudioCache: memcpy(0xaf019000, 0xb16f5000, 4096)
07-27 11:04:27.432   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.432   317  7105 V AudioCache: memcpy(0xaf01a000, 0xb16f5000, 4096)
07-27 11:04:27.433   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.433   317  7105 V AudioCache: memcpy(0xaf01b000, 0xb16f5000, 4096)
07-27 11:04:27.433   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.433   317  7105 V AudioCache: memcpy(0xaf01c000, 0xb16f5000, 4096)
07-27 11:04:27.433   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.433   317  7105 V AudioCache: memcpy(0xaf01d000, 0xb16f5000, 4096)
07-27 11:04:27.434   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.434   317  7105 V AudioCache: memcpy(0xaf01e000, 0xb16f5000, 4096)
07-27 11:04:27.434   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.434   317  7105 V AudioCache: memcpy(0xaf01f000, 0xb16f5000, 4096)
07-27 11:04:27.435   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.435   317  7105 V AudioCache: memcpy(0xaf020000, 0xb16f5000, 4096)
07-27 11:04:27.435   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.435   317  7105 V AudioCache: memcpy(0xaf021000, 0xb16f5000, 4096)
07-27 11:04:27.436   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.436   317  7105 V AudioCache: memcpy(0xaf022000, 0xb16f5000, 4096)
07-27 11:04:27.436   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.436   317  7105 V AudioCache: memcpy(0xaf023000, 0xb16f5000, 4096)
07-27 11:04:27.437   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.437   317  7105 V AudioCache: memcpy(0xaf024000, 0xb16f5000, 4096)
07-27 11:04:27.437   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.437   317  7105 V AudioCache: memcpy(0xaf025000, 0xb16f5000, 4096)
07-27 11:04:27.438   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.438   317  7105 V AudioCache: memcpy(0xaf026000, 0xb16f5000, 4096)
07-27 11:04:27.438   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.438   317  7105 V AudioCache: memcpy(0xaf027000, 0xb16f5000, 4096)
07-27 11:04:27.439   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.439   317  7105 V AudioCache: memcpy(0xaf028000, 0xb16f5000, 4096)
07-27 11:04:27.439   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.439   317  7105 V AudioCache: memcpy(0xaf029000, 0xb16f5000, 4096)
07-27 11:04:27.440   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.440   317  7105 V AudioCache: memcpy(0xaf02a000, 0xb16f5000, 4096)
07-27 11:04:27.440   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.440   317  7105 V AudioCache: memcpy(0xaf02b000, 0xb16f5000, 4096)
07-27 11:04:27.441   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.441   317  7105 V AudioCache: memcpy(0xaf02c000, 0xb16f5000, 4096)
07-27 11:04:27.441   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.441   317  7105 V AudioCache: memcpy(0xaf02d000, 0xb16f5000, 4096)
07-27 11:04:27.442   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.442   317  7105 V AudioCache: memcpy(0xaf02e000, 0xb16f5000, 4096)
07-27 11:04:27.442   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.442   317  7105 V AudioCache: memcpy(0xaf02f000, 0xb16f5000, 4096)
07-27 11:04:27.442   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.442   317  7105 V AudioCache: memcpy(0xaf030000, 0xb16f5000, 4096)
07-27 11:04:27.443   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.443   317  7105 V AudioCache: memcpy(0xaf031000, 0xb16f5000, 4096)
07-27 11:04:27.443   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.443   317  7105 V AudioCache: memcpy(0xaf032000, 0xb16f5000, 4096)
07-27 11:04:27.443   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-27 11:04:27.444   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.444   317  7105 V AudioCache: memcpy(0xaf033000, 0xb16f5000, 4096)
07-27 11:04:27.444   317  7105 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-27 11:04:27.444   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.444   317  7105 V AudioCache: memcpy(0xaf034000, 0xb16f5000, 4096)
07-27 11:04:27.444   317  7105 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-27 11:04:27.444   317  7105 V AudioCache: write(0xb16f5000, 4096)
07-27 11:04:27.444   317  7105 V AudioCache: memcpy(0xaf035000, 0xb16f5000, 4096)
07-27 11:04:27.444   317  7105 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-27 11:04:27.444   317  7105 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-27 11:04:27.444   317  7105 V AwesomePlayer: postAudioEOS() 
07-27 11:04:27.444   317  7105 V AudioCache: write(0xb16f5000, 280)
07-27 11:04:27.444   317  7105 V AudioCache: memcpy(0xaf036000, 0xb16f5000, 280)
07-27 11:04:27.445   317  7102 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-27 11:04:27.445   317  7102 V AwesomePlayer: onStreamDone
07-27 11:04:27.445   317  7102 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-27 11:04:27.445   317  7102 V AudioCache: notify(0xb16a6780, 2, 0, 0)
07-27 11:04:27.445   317  7102 V AudioCache: playback complete
07-27 11:04:27.445   317  7102 V AwesomePlayer: pause_l() 
07-27 11:04:27.445   317  7102 V AudioCache: notify(0xb16a6780, 7, 0, 0)
07-27 11:04:27.445   317   317 V AudioCache: wait - success
07-27 11:04:27.445   317  7102 V AudioCache: ignored
07-27 11:04:27.445   317   317 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-27 11:04:27.445   317  7102 V AwesomePlayer: cancelPlayerEvents
07-27 11:04:27.446   317  7102 D AudioPlayer: Pause Playback at 1068125
07-27 11:04:27.446   317   317 V AwesomePlayer: reset_l() 
07-27 11:04:27.446   317   317 V AudioCache: notify(0xb16a6780, 8, 0, 0)
07-27 11:04:27.446   317   317 V AudioCache: ignored
07-27 11:04:27.446   317   317 V AwesomePlayer: cancelPlayerEvents
07-27 11:04:27.446   317   317 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-27 11:04:27.446   317   317 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-27 11:04:27.446   317   317 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-27 11:04:27.446   317   317 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-27 11:04:27.446   317   317 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 1
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd150 on port 1
07-27 11:04:27.447   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 11:04:27.448   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-27 11:04:27.448   317   317 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-27 11:04:27.448   317   317 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-27 11:04:27.448   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-27 11:04:27.448   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-27 11:04:27.448   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-27 11:04:27.448   317   317 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-27 11:04:27.448   317   317 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-27 11:04:27.448   317   317 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-27 11:04:27.449   317   317 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-27 11:04:27.449   317   317 D AudioPlayer: AudioPlayer releasing audio source
07-27 11:04:27.449   317   317 D AudioPlayer: AudioPlayer done releasing audio source
07-27 11:04:27.450   317   317 V AwesomePlayer: reset_l() 
07-27 11:04:27.450   317   317 V AwesomePlayer: cancelPlayerEvents
07-27 11:04:27.450   317   317 V AwesomePlayer: ~AwesomePlayer call
07-27 11:04:27.450   317   317 V AwesomePlayer: reset_l() 
07-27 11:04:27.450   317   317 V AwesomePlayer: cancelPlayerEvents
07-27 11:04:27.450  7012  7101 V SoundPool: close(31)
07-27 11:04:27.450  7012  7101 V SoundPool: pointer = 0x9fe97000, size = 205080, sampleRate = 48000, numChannels = 2
,07-27 11:04:27.451  7075  7075 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:27.454  7075  7075 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 11:04:27.454  7075  7075 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 11:04:27.455  7075  7075 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 11:04:27.456  7075  7075 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:27.456  7075  7075 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-27 11:04:27.461  7029  7029 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
07-27 11:04:27.473  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,07-27 11:04:27.473  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,07-27 11:04:27.474  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7948
07-27 11:04:27.677  6859  6859 I UEI.SmartControl: Supports setup maps: true
,07-27 11:04:27.680  6859  6859 D UEI.SmartControl: QS start statue = true Error code = 0
07-27 11:04:27.680  6859  6859 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-27 11:04:27.680  6859  6859 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-27 11:04:27.680  6859  6859 I UEI.SmartControl: ### init IR Blaster...
07-27 11:04:27.683  6859  6859 D serial_port: Configuring serial port
07-27 11:04:27.683  6859  6859 E UEI.SmartControl: UEIBLaster setting for 616
07-27 11:04:27.683  6859  6859 I UEI.SmartControl: Setting serial record hearder size = 2
07-27 11:04:27.683  6859  6859 I UEI.SmartControl: configuring settings for MAXQ616
07-27 11:04:27.683  6859  6859 I UEI.SmartControl: Get version...
07-27 11:04:27.701  6859  7107 D UEI.SmartControl: serial port data available: 21
,07-27 11:04:27.728  6859  6859 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-27 11:04:27.728  6859  6859 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-27 11:04:27.728  6859  6859 I UEI.SmartControl: QS saving settings...
,07-27 11:04:27.731  6859  6859 D UEI.SmartControl: IR Blaster version: 25672567
07-27 11:04:27.748  6859  7107 D UEI.SmartControl: serial port data available: 4
,07-27 11:04:27.783  6859  6859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-27 11:04:27.792  6859  7116 I UEI.SmartControl: Device manager: loading config....
07-27 11:04:27.793  6859  6859 E UEI.SmartControl: Services init done
07-27 11:04:27.793  6859  6859 D UEI.SmartControl: QS Service init finished
07-27 11:04:27.794  6859  7116 D UEI.SmartControl: ----------- loading internal config...
07-27 11:04:27.795  6859  6859 D UEI.SmartControl: QS Service version name: 2.1.91
07-27 11:04:27.795  6859  6859 D UEI.SmartControl: QS Service version code: 201091
07-27 11:04:27.798  6859  6859 D UEI.SmartControl: Service requested: Control
07-27 11:04:27.802  6859  7116 E UEI.SmartControl: Loading SETTINGS...
,07-27 11:04:27.804  6859  6859 D UEI.SmartControl: Request IControl service: devices are loaded...
07-27 11:04:27.809  6859  7116 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-27 11:04:27.810  7012  7012 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-27 11:04:27.811  6859  6875 I UEI.SmartControl: ------ IControl API: 11
07-27 11:04:27.811  6859  6875 D UEI.SmartControl: File observer start...
07-27 11:04:27.812  6859  6875 E UEI.SmartControl: IR Port is disabled: false
07-27 11:04:27.812  6859  6859 D UEI.SmartControl: Internal service binding...
07-27 11:04:27.812  6859  6875 D UEI.SmartControl: Starting file observer...
07-27 11:04:27.812  6859  6875 I UEI.SmartControl: Registering callback...
07-27 11:04:27.814  6859  6874 I UEI.SmartControl: ------ IControl API: 19
07-27 11:04:27.816  6859  6874 I UEI.SmartControl: Registering Services Ready callback...
,07-27 11:04:27.834  6859  7115 I UEI.SmartControl: Notify AllClients services are ready: 0
07-27 11:04:27.834  6859  7115 D UEI.SmartControl: -----service ready thread exits
,07-27 11:04:27.835  7012  7028 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-27 11:04:27.835  7012  7099 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-27 11:04:27.836  7012  7099 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-27 11:04:27.837  7012  7012 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-27 11:04:27.837  7012  7012 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-27 11:04:27.838  6859  6875 I UEI.SmartControl: ------ IControl API: 8
07-27 11:04:27.839  7012  7012 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-27 11:04:27.840  7012  7012 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-27 11:04:27.840  7012  7012 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-27 11:04:27.841  7012  7012 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-27 11:04:27.841  7012  7012 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-27 11:04:27.842  7012  7012 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-27 11:04:27.843  7012  7012 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
07-27 11:04:27.845  7012  7012 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-27 11:04:27.846  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,07-27 11:04:27.847  7012  7012 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-27 11:04:27.848  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-27 11:04:27.849  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-27 11:04:27.851  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
07-27 11:04:27.851  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
07-27 11:04:27.853  7012  7012 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1469610267852]
07-27 11:04:27.855  7012  7012 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
07-27 11:04:27.857  1036  1929 I ActivityManager: Killing 6168:com.android.gallery3d/u0a27 (adj 15): empty #17
07-27 11:04:27.891  7012  7118 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,07-27 11:04:27.931  1036  1929 I ActivityManager: Killing 6633:com.lge.email/u0a23 (adj 15): empty #18
,07-27 11:04:28.046  1036  1990 W libprocessgroup: failed to open /acct/uid_10027/pid_6168/cgroup.procs: No such file or directory
,07-27 11:04:28.056  1036  2017 W libprocessgroup: failed to open /acct/uid_10023/pid_6633/cgroup.procs: No such file or directory
07-27 11:04:28.069  7012  7012 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,07-27 11:04:28.070  7012  7012 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-27 11:04:28.070  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-27 11:04:28.071  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
07-27 11:04:28.071  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
07-27 11:04:28.071  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
07-27 11:04:28.072  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
07-27 11:04:28.083  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,07-27 11:04:28.860  1036  1922 D WifiServiceImplEx: setWifiEnabled: true pid=6733, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,07-27 11:04:28.862  1036  1922 D WifiService: setWifiEnabled: true pid=6733, uid=10118
,07-27 11:04:28.862  1036  1922 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 11:04:28.888  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,07-27 11:04:28.889  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,07-27 11:04:28.889  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,07-27 11:04:28.890  1036  1525 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-27 11:04:28.890  1036  1525 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-27 11:04:28.893  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-27 11:04:28.893  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,07-27 11:04:28.893  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-27 11:04:28.893  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-27 11:04:28.893  1036  1525 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-27 11:04:28.893  1036  1525 E WifiHW  : unknown target_country: EU , set to default
07-27 11:04:28.893  1036  1525 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,07-27 11:04:28.893  1036  1525 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-27 11:04:28.893  1036  1525 I WifiUtil: gEnableBmps=1
07-27 11:04:28.994  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:04:29.023  1036  1118 D Tethering: MasterInitialState.processMessage what=3
07-27 11:04:29.029  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:29.036  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:29.043  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:29.045  1036  1118 D Tethering: MasterInitialState.processMessage what=3
07-27 11:04:29.054  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:29.058  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:29.059  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:29.061  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-27 11:04:29.064  6535  6567 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-27 11:04:29.075  5764  5764 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-27 11:04:29.090  5764  5764 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-27 11:04:29.112  2231  2231 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:04:29.163  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:04:29.193  1036  1366 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7146 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
07-27 11:04:29.196  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:29.196  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:04:29.268  7146  7146 I AppUp4:AppBoxCP: onCreate
07-27 11:04:29.269  7146  7146 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,07-27 11:04:29.280  7146  7146 I AppUp4:DB:  setFingerPrint start
07-27 11:04:29.280  7146  7146 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
07-27 11:04:29.289  7146  7146 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
07-27 11:04:29.289  7146  7146 I AppUp4:DB:  SDK version = 21
07-27 11:04:29.289  7146  7146 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-27 11:04:29.291  7146  7146 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,07-27 11:04:29.292  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 11:04:29.292  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:04:29.294  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 11:04:29.295  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-27 11:04:29.304  7146  7146 I AppUp4:CustModeStarterReceiver: onReceive
,07-27 11:04:29.349  7146  7146 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:04:29.349  7146  7146 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:04:29.357  7146  7146 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2c658109
,07-27 11:04:29.357  7146  7146 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 11:04:29.357  7146  7146 D AppUp4:CustFacade: isPhone : true
07-27 11:04:29.358  7146  7146 D AppUp4:CustModeStarterReceiver: begin check event
07-27 11:04:29.358  7146  7146 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-27 11:04:29.358  7146  7146 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-27 11:04:29.359  7146  7166 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-27 11:04:29.360  7146  7166 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-27 11:04:29.360  7146  7166 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-27 11:04:29.364  1036  1639 I ActivityManager: Killing 6239:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,07-27 11:04:29.452  1036  1922 W libprocessgroup: failed to open /acct/uid_10080/pid_6239/cgroup.procs: No such file or directory
,07-27 11:04:29.454  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:29.455  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:04:29.464  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:04:29.473  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 11:04:29.486  4297  7178 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 11:04:29.487  4297  7179 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:04:29.487  4297  7179 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 11:04:29.522  1036  1366 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7180 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-27 11:04:29.611  7180  7180 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 11:04:29.612  7180  7180 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:04:29.613  7180  7180 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-27 11:04:29.614  7180  7180 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-27 11:04:29.615  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-27 11:04:29.615  1036  1118 D Tethering: InitialState.processMessage what=4
,07-27 11:04:29.615  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-27 11:04:29.620   313   891 D SoftapController: Softap fwReload - Ok
07-27 11:04:29.628  1036  1525 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (731ms)
07-27 11:04:29.630   313   891 D CommandListener: Setting iface cfg
07-27 11:04:29.630   313   891 D CommandListener: Trying to bring down wlan0
07-27 11:04:29.631   313   891 D CommandListener: Clearing all IP addresses on wlan0
,07-27 11:04:29.635  1036  1525 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-27 11:04:29.637  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:04:29.637  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:04:29.637  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 11:04:29.639  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-27 11:04:29.636  7198  7198 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:29.636  7198  7198 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:29.648  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:04:29.649  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:29.650  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-27 11:04:29.650  1036  1525 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-27 11:04:29.650  1036  1525 D WifiMonitor: connecting to supplicant
07-27 11:04:29.650  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:29.672  7198  7198 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-27 11:04:29.707  7198  7198 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 11:04:29.707  7198  7198 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-27 11:04:29.712  1036  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{6240d79 type 2 when 120684 com.google.android.gms} when 120684
07-27 11:04:29.739  7180  7180 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-27 11:04:29.756  7180  7180 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,07-27 11:04:29.793  7198  7198 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 11:04:29.805  7180  7180 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 11:04:29.831  7180  7180 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:04:29.831  7180  7180 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:04:29.846  7198  7198 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,07-27 11:04:29.865  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-27 11:04:29.865  7198  7198 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-27 11:04:29.866  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-27 11:04:29.866  7198  7198 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-27 11:04:29.867  1036  7208 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-27 11:04:29.867  1036  7208 D WifiMonitor: Dropping event because (p2p0) is stopped
07-27 11:04:29.867  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-27 11:04:29.867  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-27 11:04:29.867  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-27 11:04:29.868  1036  1525 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-27 11:04:29.868  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:29.869  1036  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:29.869  1036  1525 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-27 11:04:29.869  1036  1525 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-27 11:04:29.870  1036  7208 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-27 11:04:29.870  1036  7208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-27 11:04:29.870  1036  1525 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,07-27 11:04:29.871  1036  1525 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-27 11:04:29.871  1036  1525 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-27 11:04:29.872  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:29.872  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 11:04:29.872  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:29.872  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:29.872  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 11:04:29.872  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:04:29.872  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:04:29.872  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 11:04:29.874  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,07-27 11:04:29.875  1036  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-27 11:04:29.875  1036  1525 D WifiNative-wlan0: doBoolean: SET update_config 1
07-27 11:04:29.876  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:29.877  1926  1926 D WfdService: Waiting for WifiP2p enabling
07-27 11:04:29.879  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:29.879  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:29.879  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:29.879  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:29.879  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:29.879  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:04:29.879  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:29.879  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:29.879  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:04:29.879  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:29.879  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:04:29.880  1036  1525 D WifiNative-wlan0: SET update_config 1: returned true
07-27 11:04:29.880  1036  1525 D WifiConfigStore: Loading config and enabling all networks 
07-27 11:04:29.880  1036  1525 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-27 11:04:29.881  1036  1525 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-27 11:04:29.881  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:29.881  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:29.881  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:29.881  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:29.881  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:29.881  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:04:29.881  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:29.881  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:29.881  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:04:29.881  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:29.881  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:04:29.886  1036  1525 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,07-27 11:04:29.894  1036  1525 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-27 11:04:29.895  1036  1525 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-27 11:04:29.895  1036  1525 D WifiStateMachine: enableVerboseLogging : level 2
07-27 11:04:29.896  1036  1525 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-27 11:04:29.896  1036  1525 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-27 11:04:29.896  1036  1525 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-27 11:04:29.897  1036  1525 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-27 11:04:29.897  1036  1525 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-27 11:04:29.897  1036  1525 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-27 11:04:29.897  1036  1525 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-27 11:04:29.898  1036  1525 D WifiNative-wlan0: SET model_number LG-D855: returned true
,07-27 11:04:29.898  1036  1525 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-27 11:04:29.898  1036  1525 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-27 11:04:29.898  1036  1525 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-27 11:04:29.899  1036  1525 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-27 11:04:29.899  1036  1525 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-27 11:04:29.899  1036  1525 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-27 11:04:29.900  1926  1926 D WfdsService: Supplicant Connection state is changed : true
07-27 11:04:29.900  1926  2309 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-27 11:04:29.900  1926  2309 D WfdsService: Set the WFDS Monitor: true
07-27 11:04:29.900  1926  2309 D WfdsMonitor: WfdsMonitorThread create
07-27 11:04:29.900  1926  2309 D WfdsMonitor: WFDS Monitor is created and started
07-27 11:04:29.900  1926  2309 D WfdsService: WiFi: Supplicant connection re-established
07-27 11:04:29.900  1036  1525 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 11:04:29.900  1036  1525 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-27 11:04:29.901  1036  1525 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-27 11:04:29.901  1036  1525 D WifiNative-HAL: Setting external_sim to 1
07-27 11:04:29.901  1036  1525 D WifiNative-wlan0: doBoolean: SET external_sim 1
,07-27 11:04:29.901  1036  1525 D WifiNative-wlan0: SET external_sim 1: returned true
07-27 11:04:29.901  1036  1525 I WifiNative-HAL: startHal
07-27 11:04:29.901  1036  1525 D wifi    : setting scan oui 0x9d2527a0
07-27 11:04:29.902  1036  1525 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 11:04:29.902  1036  1525 I WifiNative-HAL: startHal
07-27 11:04:29.902  1036  1525 D wifi    : setting scan oui 0x9d2527a0
07-27 11:04:29.902  1036  1525 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-27 11:04:29.903  1036  1525 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-27 11:04:29.903  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-27 11:04:29.903  7198  7198 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-27 11:04:29.903  1926  7210 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-27 11:04:29.903  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-27 11:04:29.903  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-27 11:04:29.904  7198  7198 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-27 11:04:29.904  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-27 11:04:29.904  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-27 11:04:29.904  7198  7198 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-27 11:04:29.904  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-27 11:04:29.904  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-27 11:04:29.904  7198  7198 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-27 11:04:29.905  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-27 11:04:29.905  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,07-27 11:04:29.905  7198  7198 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-27 11:04:29.905  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,07-27 11:04:29.905  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-27 11:04:29.905  7198  7198 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-27 11:04:29.905  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-27 11:04:29.905  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-27 11:04:29.905  7198  7198 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-27 11:04:29.906  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-27 11:04:29.906  1036  1525 E WifiNative: : [120,878,077 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-27 11:04:29.906  1036  1525 D WifiNative-wlan0: doBoolean: RECONNECT
07-27 11:04:29.906  1926  7210 E CtrlSupplicant: Succeed to open control connection
,07-27 11:04:29.907  1036  1525 D WifiNative-wlan0: RECONNECT: returned true
07-27 11:04:29.907  1036  1525 D WifiNative-wlan0: doString: [STATUS]
07-27 11:04:29.907  1926  7210 E CtrlSupplicant: Succeed to open monitor connection
07-27 11:04:29.907  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-27 11:04:29.907  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-27 11:04:29.908  1036  1525 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-27 11:04:29.908  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 11:04:29.908  1926  7210 D WfdsMonitor: Supplicant connection established
07-27 11:04:29.908  1926  2309 D WfdsService: Connected to the supplicant for wfds
07-27 11:04:29.908  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
07-27 11:04:29.908  1036  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.909  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
07-27 11:04:29.909  1036  1036 D RttService: SCAN_AVAILABLE : 3
07-27 11:04:29.910  1036  1543 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.910  1036  1543 I WifiNative-HAL: startHal
07-27 11:04:29.910  1036  1543 D wifi    : getting scan capabilities on interface[1] = 0x9d2527a0
07-27 11:04:29.910  1036  1543 D wifi    : failed to get capabilities : -3
07-27 11:04:29.910  1036  1543 E WifiScanningService: could not get scan capabilities
07-27 11:04:29.910  1036  1544 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.910   313   891 D CommandListener: Setting iface cfg
07-27 11:04:29.910   313   891 D CommandListener: Trying to bring up p2p0
07-27 11:04:29.911  1036  1524 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-27 11:04:29.911  1036  1524 D LGWifiP2pService: P2pEnablingState
07-27 11:04:29.911  1036  1524 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.911  1036  1525 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-27 11:04:29.911  1036  1524 D LGWifiP2pService: P2p socket connection successful
07-27 11:04:29.911  1036  1524 D LGWifiP2pService: P2pEnabledState
07-27 11:04:29.911  1036  1525 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-27 11:04:29.911  1036  1524 D LGWifiP2pService: sending p2p connection changed broadcast
07-27 11:04:29.911  1036  1525 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-27 11:04:29.911  1036  1524 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-27 11:04:29.911  1036  1525 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-27 11:04:29.912  1036  1525 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-27 11:04:29.912  1036  1525 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-27 11:04:29.912  1036  1525 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-27 11:04:29.912  1036  1525 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-27 11:04:29.912  7198  7198 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-27 11:04:29.913  1036  1525 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-27 11:04:29.913  1036  1525 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-27 11:04:29.913  1036  1525 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-27 11:04:29.913  1036  1525 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-27 11:04:29.913  7198  7198 E wpa_supplicant: disconnect_rssi_lvl: -100
07-27 11:04:29.914  1036  1525 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
07-27 11:04:29.914  1036  1525 E WifiStat,eMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
07-27 11:04:29.914  1036  1525 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
07-27 11:04:29.914  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-27 11:04:29.914  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-27 11:04:29.915  1926  1926 D WfdsService: WifiP2pState is changed : true
07-27 11:04:29.915  1926  1926 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-27 11:04:29.915  1036  1524 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-27 11:04:29.915  1036  1524 D WifiNative-p2p0: doBoolean: SET device_name G3
07-27 11:04:29.915  1926  2309 D WfdsService: Receive the WFDS_ENABLE Method
07-27 11:04:29.915  1926  2309 D WfdsService: Set the WFDS Monitor: true
07-27 11:04:29.915  1926  2309 D WfdsService: Connected to the supplicant for wfds
07-27 11:04:29.915  1036  1524 D WifiNative-p2p0: SET device_name G3: returned true
07-27 11:04:29.915  1926  2309 D WfdsJNI : doCommand: WFDS_SET TRUE
07-27 11:04:29.915  1036  1524 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
,07-27 11:04:29.915  1036  1524 D LGWifiP2pService: before postfix = G3
07-27 11:04:29.915  7198  7198 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-27 11:04:29.915  1036  1524 D WifiServerServiceExt: postfix byte check : 2
07-27 11:04:29.915  1036  1524 D LGWifiP2pService: after postfix = G3
07-27 11:04:29.915  1036  1524 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-27 11:04:29.916  1036  1524 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-27 11:04:29.916  1036  1524 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-27 11:04:29.916  1926  2309 D WfdsService: selectPreferredScanChannel [36]
,07-27 11:04:29.916  1926  2309 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-27 11:04:29.915  1926  1926 D WfdsService: isConnected: false
07-27 11:04:29.916  1036  1524 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-27 11:04:29.916  1036  1524 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-27 11:04:29.916  1036  1524 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-27 11:04:29.916  1036  1524 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-27 11:04:29.917  7198  7198 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-27 11:04:29.917  7198  7198 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:29.917  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 11:04:29.917  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:29.917  1036  7208 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:29.917  1036  7208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:29.918  7198  7198 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-27 11:04:29.918  7198  7198 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.918  1036  7208 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:04:29.918  1036  7208 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.918  1036  7208 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.918  1036  7208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.918  7198  7198 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.918  1036  7208 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:04:29.918  1036  7208 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.918  1036  7208 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.918  1036  7208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.919  1926  7210 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:04:29.919  1926  7210 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:04:29.919  1036  1525 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-27 11:04:29.919  1036  1525 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-27 11:04:29.919  1036  1524 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-27 11:04:29.919  1036  1524 D WifiNative-HAL: p2pGetDeviceAddress
07-27 11:04:29.919  1036  1525 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-27 11:04:29.920  1036  1525 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-27 11:04:29.920  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-27 11:04:29.920  7198  7198 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-27 11:04:29.920  7198  7198 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:04:29.920  1036  1524 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-27 11:04:29.921  1036  1524 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-27 11:04:29.921  1036  1524 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-27 11:04:29.921  1036  1525 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-27 11:04:29.921  1036  1525 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-27 11:04:29.921  1036  1524 D Wif,iNative-p2p0: P2P_FLUSH: returned true
07-27 11:04:29.921  1036  1524 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-27 11:04:29.921  1036  1524 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-27 11:04:29.921  1036  1524 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-27 11:04:29.922  1036  1524 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-27 11:04:29.922  1036  1524 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-27 11:04:29.923  1926  1926 I WfdStateTracker: handleP2pThisDeviceChanged
07-27 11:04:29.923  1926  1926 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-27 11:04:29.923  1926  1926 D WfdsService: Update P2p Interface State: 3
07-27 11:04:29.923  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-27 11:04:29.923  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:04:29.923  1036  7208 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:04:29.924  1036  7208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:04:29.928  1036  1524 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-27 11:04:29.928  1036  1524 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-27 11:04:29.928  1036  1524 D LGWifiP2pService: InactiveState
07-27 11:04:29.928  1036  1524 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.928  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.928  1036  1524 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-27 11:04:29.928  1036  1525 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-27 11:04:29.928  1036  1525 D WifiNative-wlan0: doBoolean: SCAN
07-27 11:04:29.929  7198  7198 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-27 11:04:29.929  7198  7198 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:29.929  1036  7208 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 11:04:29.929  1036  7208 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:29.929  1036  7208 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:29.929  7198  7198 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-27 11:04:29.929  1036  7208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:29.929  7198  7198 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.930  1926  7210 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 11:04:29.930  1926  7210 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:04:29.930  1036  1524 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-27 11:04:29.930  1036  1524 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.930  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.930  1036  1524 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.930  7198  7198 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.930  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.930  1036  1524 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.930  1036  1524 D LGWifiP2pServi,ce: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.930  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.930  1036  1524 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.930  1926  7210 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:04:29.931  1036  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.931  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.931  1036  1525 D WifiNative-wlan0: SCAN: returned false
07-27 11:04:29.931  1036  1524 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.931  1036  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.931  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.931  1036  1524 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:29.931  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=120903  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 11:04:29.931  1036  1036 E WifiServerServiceExt: No p2p device connected
07-27 11:04:29.932  1036  7208 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:04:29.932  1036  7208 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.932  1036  7208 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.933  1036  7208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.933  1036  7208 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:04:29.933  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=120904  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 11:04:29.933  1036  7208 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.933  1036  7208 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.933  1036  1525 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:04:29.933  1036  7208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:29.933  1036  1525 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:04:29.934  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:29.934  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:29.935  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:29.935  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:29.935  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-27 11:04:29.936  1926  2309 W WfdsService: DefaultState - msg [9441285] is not handled
07-27 11:04:29.936  1036  1525 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:04:29.936  1036  1525 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:04:29.936  1036  1525 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:04:29.937  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:29.937  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:04:29.937  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
07-27 11:04:29.954  7180  7180 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-27 11:04:29.971  7180  7180 I HubEmail: JNI_OnLoad()
07-27 11:04:29.971  7180  7180 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-27 11:04:29.971  7180  7180 I HubEmail: registerNatives()
07-27 11:04:29.971  7180  7180 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-27 11:04:29.971  7180  7180 I HubEmail: registerNativeMethods()
07-27 11:04:29.971  7180  7180 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,07-27 11:04:29.971  7180  7180 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
07-27 11:04:29.975  3467  3467 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-27 11:04:29.975  3467  3467 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:29.975  3467  3467 I LgeMiscReceiver: networkInfo.isConnected() = false
,07-27 11:04:30.037  1036  1639 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7216 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,07-27 11:04:30.046  7180  7213 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:30.053  7050  7214 W FormManager: Network not available. Please check & try again.
,07-27 11:04:30.061  7050  7215 V FormManager: Network unavailable.
07-27 11:04:30.067  7050  7215 V FormManager: Network unavailable.
,07-27 11:04:30.080  1036  1052 I ActivityManager: Killing 6671:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,07-27 11:04:30.133  1036  1990 W libprocessgroup: failed to open /acct/uid_10061/pid_6671/cgroup.procs: No such file or directory
07-27 11:04:30.230  7216  7216 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:04:30.230  7216  7216 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:04:30.234  7216  7216 D PhoneMonitor: Register our PhoneStateListener
,07-27 11:04:30.264  7216  7216 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-27 11:04:30.269  7216  7216 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,07-27 11:04:30.308  7216  7216 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,07-27 11:04:30.310  7216  7216 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,07-27 11:04:30.311  7216  7216 D TelephonyAutoProfiling: [parse] Load xml
07-27 11:04:30.319  7216  7216 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-27 11:04:30.319  7216  7216 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,07-27 11:04:30.319  7216  7216 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
07-27 11:04:30.319  7216  7216 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
07-27 11:04:30.320  7216  7216 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
07-27 11:04:30.320  7216  7216 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
07-27 11:04:30.320  7216  7216 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
07-27 11:04:30.320  7216  7216 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
07-27 11:04:30.320  7216  7216 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
07-27 11:04:30.320  7216  7216 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
07-27 11:04:30.320  7216  7216 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
07-27 11:04:30.320  7216  7216 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
07-27 11:04:30.321  7216  7216 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
07-27 11:04:30.321  7216  7216 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
07-27 11:04:30.321  7216  7216 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
07-27 11:04:30.321  7216  7216 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
07-27 11:04:30.321  7216  7216 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,07-27 11:04:30.350  1036  1998 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7238 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 11:04:30.351  7216  7216 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-27 11:04:30.352  1036  1998 I ActivityManager: Killing 6002:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,07-27 11:04:30.398  1036  1922 W libprocessgroup: failed to open /acct/uid_10097/pid_6002/cgroup.procs: No such file or directory
,07-27 11:04:30.538  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,07-27 11:04:30.538  1036  7208 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,07-27 11:04:30.538  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,07-27 11:04:30.538  7198  7198 E wpa_supplicant: USIM:  scard_init function
,07-27 11:04:30.539  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
07-27 11:04:30.539  1036  7208 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-27 11:04:30.539  7198  7198 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-27 11:04:30.546  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-27 11:04:30.546  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,07-27 11:04:30.549  1036  1525 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 11:04:30.550  1036  1525 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 11:04:30.552  1036  1525 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 11:04:30.553  1036  1525 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 11:04:30.553  1036  1525 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-27 11:04:30.618  1036  1922 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7256 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
07-27 11:04:30.623  1036  1922 I ActivityManager: Killing 6807:com.lge.eula/1000 (adj 15): empty #17
,07-27 11:04:30.638   351   351 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 467us total 25.136ms
07-27 11:04:30.652  7198  7198 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-27 11:04:30.655  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-27 11:04:30.655  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-27 11:04:30.655  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-27 11:04:30.655  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-27 11:04:30.655  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:04:30.655  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:04:30.660  7198  7198 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 11:04:30.660  7198  7198 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 11:04:30.660  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:04:30.661  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:04:30.661  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-27 11:04:30.662  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 11:04:30.662  1036  7208 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 11:04:30.662  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-27 11:04:30.662  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 11:04:30.662  1036  7208 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 11:04:30.662  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:04:30.662  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:04:30.664   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 724us total 24.588ms
,07-27 11:04:30.685   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 20.581ms
,07-27 11:04:30.687  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=121658  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-27 11:04:30.688  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-27 11:04:30.688  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=121660  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-27 11:04:30.689  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=121661  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-27 11:04:30.690  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=121661  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-27 11:04:30.690  1036  1525 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121662
07-27 11:04:30.691  1036  1525 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121663
07-27 11:04:30.691  1036  1525 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121663
07-27 11:04:30.692  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121663
07-27 11:04:30.692  1036  1525 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121664
07-27 11:04:30.692  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:30.692  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:30.693  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=121664  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-27 11:04:30.693  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:30.693  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:30.693  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-27 11:04:30.694  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:30.694  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:30.694  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-27 11:04:30.694  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:30.696  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:04:30.696  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-27 11:04:30.698  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:30.704  1036  1956 W libprocessgroup: failed to open /acct/uid_1000/pid_6807/cgroup.procs: No such file or directory
07-27 11:04:30.711  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=121683  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-27 11:04:30.712  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=121684  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-27 11:04:30.713  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=121685  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-27 11:04:30.713  1036  1525 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121685
07-27 11:04:30.714  1036  1525 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121686
07-27 11:04:30.714  1036  1525 D WifiNative-wlan0: doString: [STATUS]
07-27 11:04:30.715  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:04:30.715  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:04:30.715  1036  1525 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,07-27 11:04:30.719  1036  1525 I WifiServiceExtension: setVHTCapabilityType  : false
07-27 11:04:30.720  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:30.720  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:30.720  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-27 11:04:30.721  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:30.721  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:30.721  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-27 11:04:30.725  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:30.725  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:30.726  1036  1525 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-27 11:04:30.726  1036  1525 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
07-27 11:04:30.737  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 11:04:30.737  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 11:04:30.738  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-27 11:04:30.739  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:30.740  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:30.740  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:30.740  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,07-27 11:04:30.741  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:30.741  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:30.742  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:30.742  1036  1525 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-27 11:04:30.742  1036  1531 D ConnectivityService: Got NetworkAgent Messenger
07-27 11:04:30.742  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-27 11:04:30.742  1036  1531 D ConnectivityService: NetworkAgent connected
07-27 11:04:30.743  1036  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:04:30.743  1036  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 11:04:30.743  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:30.743  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:30.743  1036  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 11:04:30.743  1036  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 11:04:30.745  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:30.748  1036  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 11:04:30.748  1036  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:04:30.748  1036  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 11:04:30.748  1036  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 11:04:30.748  1036  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,07-27 11:04:30.753  1036  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 11:04:30.754   313   891 D CommandListener: Setting iface cfg
07-27 11:04:30.758  1036  1525 E WifiStateMachine: Start Dhcp Watchdog 2
07-27 11:04:30.759  1036  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=121731  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:04:30.759  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:30.759  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:30.760  1036  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=121732  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:04:30.760  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=121732  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:04:30.760  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:30.761  1036  7274 D DhcpStateMachine: StoppedState
07-27 11:04:30.761  1036  7274 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:30.761  1036  7274 D DhcpStateMachine: WaitBeforeStartState
07-27 11:04:30.762  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:04:30.762  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-27 11:04:30.762  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
,07-27 11:04:30.762  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
,07-27 11:04:30.763  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:04:30.763  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-27 11:04:30.763  1036  1525 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:30.763  1036  1525 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:30.764  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:30.764  1036  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:30.765  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:04:30.765  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-27 11:04:30.767  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:04:30.767  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-27 11:04:30.768  1036  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121739  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:04:30.768  1036  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121740  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:04:30.769  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121741  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:04:30.770  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:75756] from screen [on:0 period:731455538] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 11:04:30.771  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:731455539] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 11:04:30.771  1036  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 11:04:30.831  1036  1990 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7280 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 11:04:30.832  1036  1990 I ActivityManager: Killing 6826:com.lge.bnr/1000 (adj 15): empty #17
,07-27 11:04:30.941  1036  1887 W libprocessgroup: failed to open /acct/uid_1000/pid_6826/cgroup.procs: No such file or directory
,07-27 11:04:30.942  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,07-27 11:04:30.943  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:30.943  1036  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:30.943  1036  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:30.944  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:30.944  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:30.945  1036  1531 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
07-27 11:04:30.945  1036  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,07-27 11:04:30.952  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=151,0,0
07-27 11:04:30.953  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=151,0,0
07-27 11:04:30.953  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-27 11:04:30.953  7198  7198 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-27 11:04:30.954  1036  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-27 11:04:30.954  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 0
07-27 11:04:30.954  1036  1525 D WifiNative-wlan0: SET ps 0: returned true
07-27 11:04:30.954  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-27 11:04:30.955  7198  7198 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-27 11:04:30.955  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-27 11:04:30.957  1036  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1207a6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:30.957  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1207a6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:30.958  1036  7274 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:30.958  1036  7274 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-27 11:04:30.958  1036  1525 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-27 11:04:30.958  1036  1525 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-27 11:04:30.959  1036  1525 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 11:04:30.961   313   891 D CommandListener: Setting iface cfg
07-27 11:04:30.962   313   891 D CommandListener: Trying to bring up wlan0
,07-27 11:04:30.963  1036  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:30.963  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:30.963  1036  1524 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:30.966  1036  1525 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,07-27 11:04:30.968  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:30.968  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:30.969  1036  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:30.969  1036  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:30.970  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:30.970  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:30.971  1036  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-27 11:04:30.971  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-27 11:04:30.972  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-27 11:04:30.973  1036  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:30.973  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:30.973  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 11:04:30.973  7198  7198 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 11:04:30.974  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 11:04:30.974  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-27 11:04:30.974  7198  7198 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-27 11:04:30.975  1036  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-27 11:04:30.975  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
,07-27 11:04:30.992  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
07-27 11:04:30.992  1036  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-27 11:04:30.993  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 11:04:30.993  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 11:04:30.994  1036  1525 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
,07-27 11:04:30.994  7280  7280 I art     : Almond Protected OAT
07-27 11:04:30.994  1036  1525 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 11:04:30.994  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 11:04:30.995  1036  1525 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 11:04:30.995  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-27 11:04:30.996  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-27 11:04:30.996  1036  1525 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-27 11:04:30.997  1036  1531 D ConnectivityService: ignoring duplicate network state non-change
07-27 11:04:30.998  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-27 11:04:30.999  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:04:30.999  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-27 11:04:30.999  1036  1531 D ConnectivityService: Adding iface wlan0 to network 101
07-27 11:04:31.000  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:31.003  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:31.003  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:31.004  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:04:31.009  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:31.009  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:31.009  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-27 11:04:31.015  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:31.015  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:31.015  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-27 11:04:31.018  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-27 11:04:31.018  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-27 11:04:31.021  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:31.021  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:31.021  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,07-27 11:04:31.022  1036  1525 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-27 11:04:31.023  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-27 11:04:31.026  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:31.026  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:31.026  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-27 11:04:31.028  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:31.028  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:31.029  1036  1531 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-27 11:04:31.030  1036  1531 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-27 11:04:31.031  1036  1531 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
07-27 11:04:31.032   313   891 E Netd    : netlink response contains error (File exists)
07-27 11:04:31.032  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:31.033  1036  1531 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-27 11:04:31.034  1036  1531 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-27 11:04:31.034  1036  1531 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
07-27 11:04:31.034  1036  1531 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
07-27 11:04:31.035  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:31.035  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-27 11:04:31.035  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:31.036  1036  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-27 11:04:31.036  1036  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-27 11:04:31.036  1036  1531 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-27 11:04:31.039  1036  7273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:31.039  1036  7273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-27 11:04:31.039  1036  7273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:31.039  1036  7273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-27 11:04:31.041  1036  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-27 11:04:31.041  1036  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:04:31.041  1036  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:31.041  1036  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 11:04:31.041  1036  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:31.042  1036  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
,07-27 11:04:31.042  1036  1531 D ConnectivityService: currentScore = 0, newScore = 20
07-27 11:04:31.042  1036  1531 D ConnectivityService:    accepting network in place of null
07-27 11:04:31.042   313  7301 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-27 11:04:31.042  1036  1531 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:31.042  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:31.042  1036  1525 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:31.042  1036  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:04:31.042  1838  1838 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:31.043  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 11:04:31.043  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-27 11:04:31.043  1036  1531 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-27 11:04:31.044  1036  1531 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-27 11:04:31.044  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:31.044  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 11:04:31.044  1036  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:31.044  1036  1531 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-27 11:04:31.045  1036  1531 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-27 11:04:31.046  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-27 11:04:31.046  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 11:04:31.046  1036  1531 D ConnectivityService: validation of new default, Network = false
07-27 11:04:31.046  1036  1531 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-27 11:04:31.046  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 11:04:31.046  1036  1531 D DSQN    : enableDataServiceNotify 
07-27 11:04:31.046  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 11:04:31.046  1036  1531 D DSQN    : start dsqn bin
,07-27 11:04:31.054  1036  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-27 11:04:31.054  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:31.054  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:31.046  7302  7302 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:31.046  7302  7302 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:31.057  1036  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:31.060  1588  2047 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 11:04:31.073  7302  7302 E DSQN    : DSQN ssw
,07-27 11:04:31.074  1036  1523 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-27 11:04:31.085  7280  7280 D WeatherApplication: removeAccount
,07-27 11:04:31.090  1803  7306 I CheckinService: active receiver: enabled
,07-27 11:04:31.099  7280  7280 D WeatherApplication: Account.length = 0
07-27 11:04:31.099  7280  7280 E WeatherApplication: OPERATOR:OPEN
07-27 11:04:31.101  1803  7306 I CheckinService: Preparing to send checkin request
07-27 11:04:31.101  1803  7306 I EventLogService: Accumulating logs since 1469610205274
07-27 11:04:31.102   313  7301 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-27 11:04:31.105  7280  7280 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:4:31
07-27 11:04:31.109  7280  7280 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 11:04:31.109  7280  7280 D Weather.Utils: 2 : All the weather widget is gone.
,07-27 11:04:31.111  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:04:31.112  1803  7306 W EventLogAggregator: Unknown tag: snet_gcore
07-27 11:04:31.112  1803  7306 W EventLogAggregator: Unknown tag: snet_launch_service
07-27 11:04:31.112  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:31.113  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:31.115  7280  7280 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 11:04:31.118  7280  7280 D WeatherAncestor: connectivity changed - connection : true
07-27 11:04:31.119  7280  7280 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,07-27 11:04:31.127  7280  7280 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 11:04:31.128  7280  7280 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 11:04:31.128  7280  7280 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
07-27 11:04:31.134   313  7301 D libc-netbsd: res_queryN name = clients3.google.com succeed
,07-27 11:04:31.146  7280  7280 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 11:04:31.146  7280  7280 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:4:31
07-27 11:04:31.162   313   890 D LGDataListener: argv[0]=dsqncommand
,07-27 11:04:31.162   313   890 D LGDataListener: argv[1]=wlan0
07-27 11:04:31.162   313   890 D LGDataListener: argv[2]=1
07-27 11:04:31.162   313   890 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-27 11:04:31.162  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
07-27 11:04:31.162  1036  1116 D DSQN    : start to monitor internet connection
07-27 11:04:31.166  1036  7274 D DhcpStateMachine: DHCPV4 request on wlan0
07-27 11:04:31.166  1036  7274 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-27 11:04:31.166  1036  7274 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-27 11:04:31.166  7311  7311 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:31.166  7311  7311 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:31.177  7311  7311 I dhcpcd  : version 5.5.6 starting
07-27 11:04:31.180  7311  7311 E dhcpcd  : get_duid: m
07-27 11:04:31.180  7311  7311 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-27 11:04:31.180  7311  7311 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,07-27 11:04:31.187  1036  1922 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7312 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 11:04:31.189  1036  1922 I ActivityManager: Killing 2118:com.lge.music/u0a34 (adj 15): empty #17
07-27 11:04:31.189  1036  7273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 09:04:31 GMT], X-Android-Received-Millis=[1469610271189], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469610271161]}
07-27 11:04:31.189  1036  7273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-27 11:04:31.189  1036  7273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-27 11:04:31.189  1036  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
07-27 11:04:31.190  1036  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-27 11:04:31.190  1036  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:04:31.190  1036  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:31.190  1036  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 11:04:31.190  1036  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
07-27 11:04:31.190  1036  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-27 11:04:31.190  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:31.190  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:31.191  1036  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:31.191  1036  1531 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:31.191  1588  2047 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 11:04:31.191  1036  1525 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:31.191  1036  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:04:31.191  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-27 11:04:31.192  1838  1838 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:31.192  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,07-27 11:04:31.213   317  1372 V AudioFlinger: 2118 died, releasing its sessions
07-27 11:04:31.213   317  1372 V AudioFlinger:  pid 1838 @ 0
07-27 11:04:31.213   317  1372 V AudioFlinger:  pid 3467 @ 1
07-27 11:04:31.213   317  1372 V AudioFlinger:  pid 3467 @ 2
,07-27 11:04:31.245  7311  7311 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,07-27 11:04:31.245  7311  7311 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-27 11:04:31.245  7311  7311 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-27 11:04:31.246  7311  7311 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-27 11:04:31.246  7311  7311 D dhcpcd  : wlan0: sending REQUEST (xid 0xf3bf2dc0), next in 4.69 seconds
07-27 11:04:31.251  1036  1757 W libprocessgroup: failed to open /acct/uid_10034/pid_2118/cgroup.procs: No such file or directory
07-27 11:04:31.256  7311  7311 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,07-27 11:04:31.257  1803  7306 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-27 11:04:31.267  7311  7311 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-27 11:04:31.267  7311  7311 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-27 11:04:31.267  7311  7311 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-27 11:04:31.268  7311  7311 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-27 11:04:31.268  7311  7311 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-27 11:04:31.268  7311  7311 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-27 11:04:31.268  7311  7311 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-27 11:04:31.268  7311  7311 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-27 11:04:31.270  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:04:31.270  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:31.271  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:04:31.335   279   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 11:04:31.335   279   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-27 11:04:31.335   279   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 11:04:31.336  7312  7342 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,07-27 11:04:31.350   279   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 11:04:31.350   279   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-27 11:04:31.350   279   364 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 11:04:31.351  7312  7342 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-27 11:04:31.356   279   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 11:04:31.356   279   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-27 11:04:31.356   279   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 11:04:31.357  7312  7348 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-27 11:04:31.359   279   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 11:04:31.359   279   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-27 11:04:31.359   279   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 11:04:31.359  7312  7348 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,07-27 11:04:31.393  1036  1757 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7354 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,07-27 11:04:31.461  7354  7354 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-27 11:04:31.461  7354  7354 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-27 11:04:31.490  7354  7354 I MultiDex: VM with version 2.1.0 has multidex support
07-27 11:04:31.490  7354  7354 I MultiDex: install
07-27 11:04:31.490  7354  7354 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 11:04:31.505  7354  7354 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,07-27 11:04:31.569  1036  7274 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-27 11:04:31.571  1036  7274 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-27 11:04:31.571  1036  7274 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 11:04:31.571  1036  7274 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-27 11:04:31.571  1036  7274 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-27 11:04:31.571  1036  7274 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-27 11:04:31.571  1036  7274 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-27 11:04:31.572  1036  7274 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-27 11:04:31.572  1036  7274 D DhcpStateMachine: RunningState
07-27 11:04:31.634  7312  7312 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-27 11:04:31.642  7312  7312 I LibraryLoader: Loading: webviewchromium
07-27 11:04:31.645  7312  7312 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2624-2628)
07-27 11:04:31.646  7312  7312 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 11:04:31.654  7312  7312 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {12be5658}
07-27 11:04:31.655  7312  7312 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 11:04:31.656  7312  7312 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 11:04:31.665  7312  7312 I BrowserStartupController: Initializing chromium process, renderers=0
07-27 11:04:31.666  7312  7312 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 11:04:31.682  7312  7312 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-27 11:04:31.683  7312  7312 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
07-27 11:04:31.683  7312  7312 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,07-27 11:04:31.706   317  2136 V AudioPolicyService: registerClient() client 0xb558a800, uid 10093
07-27 11:04:31.707  7312  7400 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-27 11:04:31.722  7312  7312 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 11:04:31.722  7312  7312 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 11:04:31.722  7312  7312 I Adreno-EGL: Build Date: 12/12/14 금
07-27 11:04:31.722  7312  7312 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 11:04:31.722  7312  7312 I Adreno-EGL: Remote Branch: 
07-27 11:04:31.722  7312  7312 I Adreno-EGL: Local Patches: 
07-27 11:04:31.722  7312  7312 I Adreno-EGL: Reconstruct Branch: 
,07-27 11:04:31.789  7312  7312 I NSApplication: Starting up...
,07-27 11:04:31.804  7412  7412 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-27 11:04:31.864  7412  7412 I dex2oat : dex2oat took 60.275ms (threads: 4)
,07-27 11:04:31.867  1036  1897 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7419 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-27 11:04:31.869  1036  1897 I ActivityManager: Killing 6196:com.android.vending/u0a44 (adj 15): empty #17
07-27 11:04:31.879  7354  7374 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 11:04:31.879  7354  7374 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 11:04:31.879  7354  7374 I Adreno-EGL: Build Date: 12/12/14 금
07-27 11:04:31.879  7354  7374 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 11:04:31.879  7354  7374 I Adreno-EGL: Remote Branch: 
07-27 11:04:31.879  7354  7374 I Adreno-EGL: Local Patches: 
07-27 11:04:31.879  7354  7374 I Adreno-EGL: Reconstruct Branch: 
,07-27 11:04:31.948  1036  1929 W libprocessgroup: failed to open /acct/uid_10044/pid_6196/cgroup.procs: No such file or directory
,07-27 11:04:31.955  1036  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6733, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,07-27 11:04:31.956  1036  1051 D WifiService: setWifiEnabled: false pid=6733, uid=10118
07-27 11:04:31.956  1036  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-27 11:04:31.966  1036  1525 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,07-27 11:04:31.966  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 11:04:31.966  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-27 11:04:31.967  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 11:04:31.967  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-27 11:04:31.967  1036  1525 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-27 11:04:31.968  1036  1525 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-27 11:04:31.969  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-27 11:04:31.969  1036  1525 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-27 11:04:31.969  1036  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:04:31.969  1036  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 11:04:31.970  1036  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 11:04:31.970  1036  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 11:04:31.976  1036  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 11:04:31.976  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 11:04:31.976  7198  7198 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 11:04:31.977  1036  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:31.977  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:31.977  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 11:04:31.977  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 11:04:31.978  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
07-27 11:04:31.979   313   891 D CommandListener: Clearing all IP addresses on wlan0
,07-27 11:04:31.982  1036  7274 D DhcpStateMachine: RunningState{ when=-4ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:31.990  7419  7419 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 11:04:32.007  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-27 11:04:32.007  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
07-27 11:04:32.011  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-27 11:04:32.011  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:32.011  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:32.011  1036  1525 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-27 11:04:32.012  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 11:04:32.012  1036  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:32.012  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:32.013  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:32.013  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:32.013  1036  1524 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:32.013  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:32.013  1036  1524 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@8708cf
07-27 11:04:32.014  1036  1524 D LGWifiP2pService: P2pDisablingState
07-27 11:04:32.014  1036  1524 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:32.014  1036  1524 D LGWifiP2pService: p2p socket connection lost
07-27 11:04:32.014  1036  1524 D LGWifiP2pService: P2pDisabledState
07-27 11:04:32.015  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:32.015  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-27 11:04:32.022  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 0
,07-27 11:04:32.031  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:32.031  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:32.031  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:32.032  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 11:04:32.032  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
07-27 11:04:32.032  1036  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:32.032  1036  1036 D RttService: SCAN_AVAILABLE : 1
07-27 11:04:32.032  1036  1544 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:32.033  1036  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:32.034  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-27 11:04:32.034  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:32.034  1926  1926 D WfdsService: WifiP2pState is changed : false
07-27 11:04:32.034  1926  2309 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-27 11:04:32.034  1926  2309 D WfdsService: Set the WFDS Monitor: false
07-27 11:04:32.034  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:32.036  1926  7210 D CtrlSupplicant: Received on exit socket, terminate
07-27 11:04:32.036  1036  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-27 11:04:32.036  1926  7210 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-27 11:04:32.036  1926  7210 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-27 11:04:32.036  1926  7210 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-27 11:04:32.036  1926  2309 D WfdsMonitor: WFDS Monitor is stopped
07-27 11:04:32.036  1926  2309 D WfdsService: STATE : WfdsDisabledState - enter
07-27 11:04:32.036  1926  2309 W WfdsService: DefaultState - msg [9445378] is not handled
07-27 11:04:32.036  1926  2311 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-27 11:04:32.037  1036  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:32.037  1036  1524 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:32.037  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 11:04:32.037  7198  7198 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 11:04:32.038  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 11:04:32.038  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 11:04:32.038  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
,07-27 11:04:32.047  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:32.047  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:32.048  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:32.060   313   891 D CommandListener: Clearing all IP addresses on wlan0
,07-27 11:04:32.061  1036  1531 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-27 11:04:32.061  1036  1531 D DSQN    : disableDataServiceNotify
07-27 11:04:32.061  1036  1531 D DSQN    : stop dsqn bin
,07-27 11:04:32.063  1036  1525 D WifiNative-p2p0: doBoolean: TERMINATE
07-27 11:04:32.064  1036  1525 D WifiNative-p2p0: TERMINATE: returned true
07-27 11:04:32.064  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:04:32.064  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:04:32.064  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 11:04:32.064  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-27 11:04:32.064  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:32.064  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:32.064  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 11:04:32.066  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-27 11:04:32.067  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-27 11:04:32.067  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:04:32.067  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-27 11:04:32.067  1036  1531 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
07-27 11:04:32.067  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:32.067  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:32.067  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 11:04:32.067  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:32.068  1036  1531 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:32.068  1036  1531 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-27 11:04:32.068  1588  2047 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-27 11:04:32.068  1036  1531 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-27 11:04:32.068  1036  1531 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-27 11:04:32.068  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 11:04:32.068  1036  7273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:32.068  1036  7273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:32.068  1036  7273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-27 11:04:32.068  1036  1531 D ConnectivityService: sendStickyBroadcastDelay,ed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:32.068  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:32.069  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 11:04:32.069  1036  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:32.069  1036  1531 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:32.069  1036  1531 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:32.069  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:32.069  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:32.069  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:32.069  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:32.069  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:04:32.069  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:04:32.069  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:32.069  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:32.069  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:04:32.069  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:32.069  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:04:32.069  1036  1531 D NetworkManagementService: Removing idletimer
07-27 11:04:32.069  1036  1531 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:32.069  1036  1531 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-27 11:04:32.069  1036  1525 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:32.069  1838  1838 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:32.069  1036  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:04:32.070  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 11:04:32.070  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:32.070  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:32.070  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:32.070  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE ,multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:32.070  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:04:32.070  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:04:32.070  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:32.070  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:32.070  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:04:32.070  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:32.070  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:04:32.071  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:32.071  1036  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-27 11:04:32.071  1036  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-27 11:04:32.071  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-27 11:04:32.073  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-27 11:04:32.074  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 11:04:32.074  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 11:04:32.074  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 11:04:32.074  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 11:04:32.074  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 11:04:32.074  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 11:04:32.079  1036  1531 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
07-27 11:04:32.100  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:04:32.100  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:32.101  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:04:32.114  7354  7374 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 11:04:32.114  7354  7374 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 11:04:32.114  7354  7374 I Adreno-EGL: Build Date: 12/12/14 금
07-27 11:04:32.114  7354  7374 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 11:04:32.114  7354  7374 I Adreno-EGL: Remote Branch: 
07-27 11:04:32.114  7354  7374 I Adreno-EGL: Local Patches: 
07-27 11:04:32.114  7354  7374 I Adreno-EGL: Reconstruct Branch: 
07-27 11:04:32.117  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:04:32.118  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:32.118  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:32.158  7198  7198 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-27 11:04:32.158  7198  7198 I wpa_supplicant: monitor socket send errors count : 1
07-27 11:04:32.158  7198  7198 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1926-4\x00 that cannot receive messages
07-27 11:04:32.159  1036  7208 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,07-27 11:04:32.159  1036  7208 D WifiMonitor: Dropping event because (p2p0) is stopped
,07-27 11:04:32.178  7354  7374 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 11:04:32.178  7354  7374 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 11:04:32.178  7354  7374 I Adreno-EGL: Build Date: 12/12/14 금
07-27 11:04:32.178  7354  7374 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 11:04:32.178  7354  7374 I Adreno-EGL: Remote Branch: 
07-27 11:04:32.178  7354  7374 I Adreno-EGL: Local Patches: 
07-27 11:04:32.178  7354  7374 I Adreno-EGL: Reconstruct Branch: 
,07-27 11:04:32.179  7198  7198 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 11:04:32.180  7198  7198 W wpa_supplicant: USIM:  scard_deinit function
07-27 11:04:32.181  1036  1118 D Tethering: InitialState.processMessage what=4
07-27 11:04:32.182  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-27 11:04:32.183  1036  1525 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:32.184  1036  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:32.186  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-27 11:04:32.186  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 11:04:32.186  1036  7208 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 11:04:32.186  1036  7208 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-27 11:04:32.186  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:04:32.186  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:04:32.186  1036  1525 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=123158
07-27 11:04:32.187  1036  1525 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=123158
07-27 11:04:32.187  1036  1525 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=123159  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-27 11:04:32.187  1036  1525 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=123159  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-27 11:04:32.190  1036  7274 D DhcpStateMachine: StoppedState
07-27 11:04:32.190  1036  7274 D DhcpStateMachine: StoppedState{ when=-151ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:32.190  1036  1525 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-27 11:04:32.191  1036  1525 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
07-27 11:04:32.233  1036  1956 I art     : Explicit concurrent mark sweep GC freed 110147(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 5.512ms total 122.040ms
,07-27 11:04:32.286  7354  7374 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:04:32.286  7354  7374 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:04:32.330  7198  7198 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-27 11:04:32.330  1036  7208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-27 11:04:32.330  1036  7208 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
07-27 11:04:32.330  1036  7208 D WifiMonitor: Disconnecting from the supplicant, no more events
07-27 11:04:32.330  1036  1525 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,07-27 11:04:32.418  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-27 11:04:32.421  6535  6567 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-27 11:04:32.431  1036  1525 D WifiOffDelayIfNotUsed: stopMonitoring
07-27 11:04:32.432  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:04:32.432  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:04:32.432  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,07-27 11:04:32.432  1926  1926 D WfdsService: Supplicant Connection state is changed : false
07-27 11:04:32.433  1926  2309 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-27 11:04:32.433  1926  2309 D WfdsService: Set the WFDS Monitor: false
07-27 11:04:32.433  1926  2309 D WfdsMonitor: WFDS Monitor is stopped
07-27 11:04:32.433  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-27 11:04:32.434  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:32.437  2495  2495 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:32.437  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:32.437  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:32.437  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:32.437  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:32.437  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:04:32.437  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:04:32.437  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:32.437  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:32.437  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:04:32.438  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:32.438  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-27 11:04:32.439  1036  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-27 11:04:32.439  1036  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-27 11:04:32.443  2231  2231 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:32.449  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 11:04:32.449  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:32.450  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 11:04:32.450  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-27 11:04:32.453  7146  7146 I AppUp4:CustModeStarterReceiver: onReceive
07-27 11:04:32.456  7146  7146 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2c658109
07-27 11:04:32.456  7146  7146 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 11:04:32.456  7146  7146 D AppUp4:CustFacade: isPhone : true
07-27 11:04:32.456  7146  7146 D AppUp4:CustModeStarterReceiver: begin check event
07-27 11:04:32.456  7146  7146 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-27 11:04:32.460  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:32.460  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:04:32.461  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:04:32.462  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 11:04:32.466  4297  7452 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 11:04:32.468  7180  7180 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-27 11:04:32.469  4297  7453 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:32.469  4297  7453 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 11:04:32.482  3467  3467 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-27 11:04:32.482  3467  3467 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:32.482  3467  3467 I LgeMiscReceiver: networkInfo.isConnected() = false
,07-27 11:04:32.487  7180  7456 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:32.487  7216  7216 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-27 11:04:32.487  7216  7216 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-27 11:04:32.495  7050  7458 W FormManager: Network not available. Please check & try again.
,07-27 11:04:32.499  7280  7280 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:4:32
07-27 11:04:32.500  7280  7280 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 11:04:32.500  7280  7280 D Weather.Utils: 2 : All the weather widget is gone.
07-27 11:04:32.501  7280  7280 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 11:04:32.501  7280  7280 D WeatherAncestor: connectivity changed - connection : true
07-27 11:04:32.501  7280  7280 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@12cf6d2f
07-27 11:04:32.501  7050  7459 V FormManager: Network unavailable.
07-27 11:04:32.501  7280  7280 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 11:04:32.502  7280  7280 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 11:04:32.502  7280  7280 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-27 11:04:32.502  7280  7280 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 11:04:32.502  7280  7280 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:4:32
07-27 11:04:32.511  7050  7459 V FormManager: Network unavailable.
,07-27 11:04:32.522  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,07-27 11:04:32.522  6964  6964 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 11:04:32.522  6964  6964 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 11:04:32.522  6964  6964 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 11:04:32.523  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-27 11:04:32.525  6964  6964 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 11:04:32.525  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-27 11:04:32.525  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 11:04:32.525  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 11:04:32.525  6964  6964 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 11:04:32.525  6964  6964 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 11:04:32.533  7050  7463 W FormManager: Network not available. Please check & try again.
07-27 11:04:32.534  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:04:32.536  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:04:32.540  7050  7464 V FormManager: Network unavailable.
,07-27 11:04:32.542  7050  7464 V FormManager: Network unavailable.
07-27 11:04:32.545  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:32.556   313  7466 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,07-27 11:04:32.556  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-27 11:04:32.560  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 11:04:32.563  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:04:32.571  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:32.572  7050  7468 W FormManager: Network not available. Please check & try again.
07-27 11:04:32.574   313  7471 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-27 11:04:32.575  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-27 11:04:32.575  1803  7306 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
07-27 11:04:32.577  7050  7469 V FormManager: Network unavailable.
07-27 11:04:32.582  1803  7306 I CheckinService: active receiver: disabled
,07-27 11:04:32.585  7050  7469 V FormManager: Network unavailable.
07-27 11:04:32.591  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 11:04:32.591  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:04:32.593  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 11:04:32.595  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:04:32.599  4297  7472 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 11:04:32.600  4297  7473 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 11:04:32.600  4297  7473 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 11:04:32.651  1036  1052 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7474 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-27 11:04:32.777  7474  7474 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-27 11:04:32.777  7474  7474 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-27 11:04:32.781  6859  7117 D UEI.SmartControl: Internal timer expired: 2
07-27 11:04:32.781  6859  7117 D UEI.SmartControl: unbind internal service
07-27 11:04:32.789  7474  7474 V [BNRBootReceiver]: Boot Receiver Return
07-27 11:04:32.789  7474  7474 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-27 11:04:32.795  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:04:32.805  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:32.812  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 11:04:32.825  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:32.825  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 11:04:32.828  7012  7012 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 11:04:32.835  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
07-27 11:04:32.838  6859  7111 D serial_port: close(fd = 24)
,07-27 11:04:32.839  6964  6964 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,07-27 11:04:32.843  6859  7111 I UEI.SmartControl: Serial port is closed.
07-27 11:04:32.844  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:32.859  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:32.867  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:32.878  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:32.879  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 11:04:32.882  7012  7012 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 11:04:32.888  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:32.901  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:32.911  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:32.923  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:32.924  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:32.925  7012  7012 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-27 11:04:32.932  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:32.949  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:32.957  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 11:04:32.968  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:32.969  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:32.970  7012  7012 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-27 11:04:32.977  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:32.986  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:32.996  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 11:04:33.008  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:33.009  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 11:04:33.010  7012  7012 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:04:33.016  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:04:33.028  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:33.037  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 11:04:33.046  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:33.046  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:33.047  7012  7012 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-27 11:04:33.055  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:04:33.067  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:33.075  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:33.087  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 11:04:33.089  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:33.090  7012  7012 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:04:33.101  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:04:33.123  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:33.137  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:33.153  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:33.154  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 11:04:33.162  7012  7012 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:04:33.171  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:04:33.188  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:33.196  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:33.209  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:33.209  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 11:04:33.214  7012  7012 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:04:33.220  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:33.228  6984  6984 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,07-27 11:04:33.240  1036  1530 D WifiService: New client listening to asynchronous messages
,07-27 11:04:33.241  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:04:33.250  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:33.260  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:33.274  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:33.274  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 11:04:33.277  7012  7012 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-27 11:04:33.280  7012  7012 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-27 11:04:33.282  7012  7012 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-27 11:04:33.292  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:04:33.300  6984  6984 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,07-27 11:04:33.303  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:04:33.312  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:33.322  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:33.337  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 11:04:33.338  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 11:04:33.340  7012  7012 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,07-27 11:04:33.342  7012  7012 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,07-27 11:04:33.343  7012  7012 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-27 11:04:33.350  1036  1366 I ActivityManager: Killing 6941:com.lge.lifetracker/u0a37 (adj 15): empty #17
07-27 11:04:33.446  1036  1051 W libprocessgroup: failed to open /acct/uid_10037/pid_6941/cgroup.procs: No such file or directory
,07-27 11:04:33.458  2231  2231 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
07-27 11:04:33.477  2231  2231 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
07-27 11:04:33.478  2231  2231 D c       : Getting all permits...
07-27 11:04:33.478  2231  2231 D a       : Opening database...
,07-27 11:04:33.485  2231  2231 D a       : Opening database auth.proximity.permit_store...
07-27 11:04:33.486  2231  2231 D a       : Closing database...
07-27 11:04:33.501  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:04:33.505  6984  6984 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 11:04:33.505  6984  6984 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 11:04:33.506  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:04:33.510  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:33.518  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:33.526  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 11:04:33.527  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:33.531  7012  7012 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 11:04:33.535  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:33.541  6984  6984 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 11:04:33.541  6984  6984 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,07-27 11:04:33.541  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:04:33.547  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:33.554  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:33.566  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 11:04:33.567  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 11:04:33.570  7012  7012 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-27 11:04:33.575  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:33.581  6984  6984 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 11:04:33.581  6984  6984 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 11:04:33.581  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 11:04:33.587  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:33.595  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 11:04:33.605  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:33.606  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:33.608  7012  7012 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-27 11:04:33.620  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:04:33.623  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:04:33.635  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:33.636  7050  7500 W FormManager: Network not available. Please check & try again.
07-27 11:04:33.643  7050  7501 V FormManager: Network unavailable.
,07-27 11:04:33.652  7050  7501 V FormManager: Network unavailable.
,07-27 11:04:33.655  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 11:04:33.656  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:04:33.660  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 11:04:33.662  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:04:33.667  4297  7502 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 11:04:33.671  6984  6984 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-27 11:04:33.671  6984  6984 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 11:04:33.671  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:04:33.671  4297  7503 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,07-27 11:04:33.672  4297  7503 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 11:04:33.679  7050  7505 W FormManager: Network not available. Please check & try again.
07-27 11:04:33.680  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:04:33.684  7050  7506 V FormManager: Network unavailable.
07-27 11:04:33.686  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:33.691  7050  7506 V FormManager: Network unavailable.
07-27 11:04:33.704  2231  2231 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-27 11:04:33.945  1036  1525 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:731458713] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-27 11:04:33.953  1036  1525 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:731458721] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-27 11:04:34.046  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:04:34.061  1036  1118 D Tethering: MasterInitialState.processMessage what=3
07-27 11:04:34.073  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:34.078  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:34.082  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:34.084  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-27 11:04:34.086  6535  6567 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-27 11:04:34.099  5764  5764 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-27 11:04:34.117  2231  2231 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:04:34.134  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 11:04:34.135  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:34.135  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 11:04:34.135  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-27 11:04:34.141  7146  7146 I AppUp4:CustModeStarterReceiver: onReceive
07-27 11:04:34.145  7146  7146 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2c658109
07-27 11:04:34.145  7146  7146 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 11:04:34.145  7146  7146 D AppUp4:CustFacade: isPhone : true
07-27 11:04:34.145  7146  7146 D AppUp4:CustModeStarterReceiver: begin check event
07-27 11:04:34.145  7146  7146 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-27 11:04:34.150  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:34.150  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:04:34.152  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 11:04:34.158  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:04:34.165  7180  7180 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-27 11:04:34.196  3467  3467 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-27 11:04:34.196  3467  3467 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:34.196  3467  3467 I LgeMiscReceiver: networkInfo.isConnected() = true
07-27 11:04:34.196  3467  3467 D PhoneState: setPdpRejectCasuse : false
,07-27 11:04:34.202  7216  7216 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-27 11:04:34.202  7216  7216 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-27 11:04:34.214  7280  7280 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:4:34
,07-27 11:04:34.218  7280  7280 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,07-27 11:04:34.218  7280  7280 D Weather.Utils: 2 : All the weather widget is gone.
07-27 11:04:34.219  7280  7280 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 11:04:34.219  7280  7280 D WeatherAncestor: connectivity changed - connection : true
07-27 11:04:34.219  7280  7280 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@12cf6d2f
07-27 11:04:34.220  7280  7280 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 11:04:34.220  7280  7280 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 11:04:34.220  7280  7280 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-27 11:04:34.220  7280  7280 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 11:04:34.220  7280  7280 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:4:34
07-27 11:04:34.239  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:04:34.251  4297  7522 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 11:04:34.254  4297  7538 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:34.254  4297  7538 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 11:04:34.255  7180  7521 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:34.268  7050  7539 W FormManager: Network not available. Please check & try again.
07-27 11:04:34.268  7050  7541 V FormManager: Network unavailable.
,07-27 11:04:34.270  7050  7541 V FormManager: Network unavailable.
,07-27 11:04:34.971  1036  1763 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 11:04:34.972  1036  1763 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-27 11:04:35.000  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 11:04:35.000  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 11:04:35.000  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,07-27 11:04:35.003  1036  1118 D BluetoothManagerService: Message: 1
07-27 11:04:35.003  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-27 11:04:35.030  1036  1118 D BluetoothManagerService: Message: 20
07-27 11:04:35.030  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20771a7:true
,07-27 11:04:35.033  7075  7075 D BluetoothAdapterState: make
07-27 11:04:35.038  7075  7075 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-27 11:04:35.039  7075  7075 I bluedroid-qcom: init
07-27 11:04:35.040  7075  7553 I BluetoothAdapterState: Entering OffState
07-27 11:04:35.040  7075  7075 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-27 11:04:35.041  7075  7075 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-27 11:04:35.041  7075  7075 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 11:04:35.041  7075  7075 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-27 11:04:35.041  7075  7075 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-27 11:04:35.043  7075  7075 I bluedroid-qcom: get_profile_interface socket
07-27 11:04:35.043  7075  7075 I bluedroid-qcom: get_profile_interface map_client
,07-27 11:04:35.047  7075  7557 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-27 11:04:35.050  7075  7557 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-27 11:04:35.046  7556  7556 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:35.046  7556  7556 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:35.060  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-27 11:04:35.060  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,07-27 11:04:35.066  7556  7556 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-27 11:04:35.066  7556  7556 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-27 11:04:35.066  7556  7556 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-27 11:04:35.068  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-27 11:04:35.068  1036  1118 D BluetoothManagerService: Message: 40
07-27 11:04:35.068  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-27 11:04:35.069  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:35.075  7556  7556 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,07-27 11:04:35.081  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:35.081  7556  7556 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-27 11:04:35.081  7556  7556 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-27 11:04:35.084  7075  7091 I bluedroid-qcom: config_hci_snoop_log
07-27 11:04:35.087  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-27 11:04:35.087  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-27 11:04:35.091  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:35.095  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:35.108  7075  7553 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,07-27 11:04:35.110  1036  1118 D Tethering: MasterInitialState.processMessage what=3
07-27 11:04:35.110  1036  1118 D Tethering: MasterInitialState.processMessage what=3
07-27 11:04:35.111  7075  7557 D BluetoothAdapterProperties: Name is: G3
07-27 11:04:35.111  7075  7553 D BluetoothAdapterProperties: Setting state to 11
07-27 11:04:35.111  7075  7553 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-27 11:04:35.112  1036  1118 D BluetoothManagerService: Message: 60
07-27 11:04:35.112  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-27 11:04:35.112  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-27 11:04:35.113  7075  7553 I LGBluetoothServiceJni: classInitNative: succeeds
07-27 11:04:35.119  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:35.123  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:35.126  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:35.130  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 11:04:35.146  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:35.148  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:35.150  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:35.151  6964  6964 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-27 11:04:35.152  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-27 11:04:35.154  6535  6567 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-27 11:04:35.154  7075  7553 D BluetoothBondStateMachine: make
07-27 11:04:35.157  7075  7553 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:35.157  7075  7553 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-27 11:04:35.157  7075  7553 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:35.157  7075  7553 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-27 11:04:35.158  7075  7553 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-27 11:04:35.158  7075  7574 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-27 11:04:35.162  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:35.163  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:35.163  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:35.165  7075  7075 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 11:04:35.166  7075  7075 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:35.166  7075  7075 V BluetoothPbapReceiver: ***********state = 11
07-27 11:04:35.167  5764  5764 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-27 11:04:35.171  7075  7553 E BluetoothAdapterService: File transfer profiles supported!!
,07-27 11:04:35.179  2231  2231 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 11:04:35.182  5764  5764 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-27 11:04:35.184  7075  7553 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:04:35.185  7075  7075 D HeadsetService: Received start request. Starting profile...
07-27 11:04:35.185  7075  7075 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 11:04:35.186  7075  7075 D LGBluetoothHfpAdapter: Version 1.6
,07-27 11:04:35.189  7075  7075 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 11:04:35.190  7075  7075 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 11:04:35.191  7075  7075 D HeadsetStateMachine: make
07-27 11:04:35.232  1036  1757 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7578 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,07-27 11:04:35.239  7075  7075 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:04:35.239  7075  7075 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 11:04:35.245  7075  7553 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:04:35.246  7075  7075 D HeadsetStateMachine: max_hf_connections = 1
07-27 11:04:35.246  7075  7075 I bluedroid-qcom: get_profile_interface handsfree
07-27 11:04:35.248  7075  7075 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,07-27 11:04:35.250   317   317 V AudioPolicyService: registerClient() client 0xb558a6a0, uid 1002
07-27 11:04:35.250   317  1372 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-27 11:04:35.250   317  1372 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 11:04:35.250   317  1372 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 11:04:35.250  7075  7075 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-27 11:04:35.251   317  2136 V AudioFlinger: registerClient() client 0xb1433838, pid 7075
07-27 11:04:35.251   317  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:04:35.251   317  1365 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:04:35.251  7075  7075 V ToneGenerator: Create Track: 0xb4928080
07-27 11:04:35.252  7075  7075 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-27 11:04:35.252  7075  7075 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-27 11:04:35.252  1036  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:04:35.252  1036  1366 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:04:35.252   317  2135 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-27 11:04:35.252   317  2135 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-27 11:04:35.252   317  2135 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 11:04:35.252   317  2135 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 11:04:35.252  1588  2046 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:04:35.252  1588  2046 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:04:35.252   317  1367 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:04:35.252   317  1367 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:04:35.253  7075  7075 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-27 11:04:35.253  7075  7091 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:04:35.253  7075  7091 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-27 11:04:35.253  1838  1853 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:04:35.253  3467  3482 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:04:35.253  1838  1853 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:04:35.253  3467  3482 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:04:35.253   317  1372 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 11:04:35.253  1838  2456 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:04:35.253  1838  2456 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:04:35.253  7075  7091 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:04:35.254  7075  7091 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-27 11:04:35.254  1036  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:04:35.254  1036  1051 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:04:35.254  3467  3483 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:04:35.254  3467  3483 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:04:35.254  1588  1604 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:04:35.254  1588  1604 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:04:35.254   317  2135 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-27 11:04:35.254   317  2135 V AudioPoli,cyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-27 11:04:35.254   317  2135 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 11:04:35.255   317  2135 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 11:04:35.255  7075  7075 V AudioSystem: getLatency() output 2, latency 50
07-27 11:04:35.255  7075  7075 V AudioSystem: getFrameCount() output 2, frameCount 960
07-27 11:04:35.255  7075  7075 V AudioTrack: createTrack_l() output 2 afLatency 50
07-27 11:04:35.256   317  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 11:04:35.256   317  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 11:04:35.256   317  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 11:04:35.256   317  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 11:04:35.256   317  1371 V AudioFlinger: createTrack() lSessionId: 22
07-27 11:04:35.258  7075  7075 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-27 11:04:35.259  7075  7553 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:04:35.259   317  1371 V AudioFlinger: acquiring 22 from 7075, for 7075
07-27 11:04:35.259   317  1371 V AudioFlinger:  added new entry for 22
07-27 11:04:35.260  7075  7075 V ToneGenerator: ToneGenerator INIT OK, time: 126242
07-27 11:04:35.260  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:35.260  2231  2231 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:35.261  7075  7576 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-27 11:04:35.261  7075  7576 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 11:04:35.261  7075  7576 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 11:04:35.261  7075  7576 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-27 11:04:35.262   317  2136 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7075
07-27 11:04:35.263   317  2136 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-27 11:04:35.263   317  2136 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-27 11:04:35.263   317  2136 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-27 11:04:35.263   317  2136 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-27 11:04:35.263   317  2136 V voice   : voice_set_parameters: exit with code(0)
07-27 11:04:35.263   317  2136 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-27 11:04:35.263   317  2136 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-27 11:04:35.263   317  2136 V msm8974_platform: platform_set_parameters: exit with code(0)
07-27 11:04:35.263   317  2136 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-27 11:04:35.263   317  2136 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-27 11:04:35.263   317  2136 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-27 11:04:35.264  7075  7576 V ToneGenerator: ToneGenerator destructor
07-27 11:04:35.264  7075  7576 V ToneGenerator: stopTone
07-27 11:04:35.264  7075  7576 V ToneGenerator: Delete Track: 0xb4928080
07-27 11:04:35.264  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:35.264  7075  7576 V AudioTrack: ~AudioTrack, releasing session id from 7075 on behalf of 7075
07-27 11:04:35.266   317  1372 V AudioFlinger: releasing 22 from 7075 for 7075
07-27 11:04:35.266   317  1372 V AudioFlinger:  decremented refcount to 0
07-27 11:04:35.266   317  1372 V AudioFlinger: purging stale effects
07-27 11:04:35.266   317   317 V AudioPolicyService: AudioCommandThread() adding release output 2
07-27 11:04:35.266   317   317 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-27 11:04:35.266   317  1272 V AudioPolicyService: AudioCommandThread() waking up
07-27 11:04:35.266   317  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
07-27 11:04:35.266   317  1272 V AudioPolicyManager: releaseOutput() 2
07-27 11:04:35.266   317  1272 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 11:04:35.266   317   317 V AudioFlinger: PlaybackThread::Track destructor
07-27 11:04:35.266   317   317 V AudioFlinger: removeClient_l() pid 7075, calling pid 317
07-27 11:04:35.266  1036  1990 W Process : Unable to open /proc/7591/status
07-27 11:04:35.267  7075  7075 D A2dpService: Received start request. Starting profile...
07-27 11:04:35.267  7075  7075 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 11:04:35.268  7075  7075 V Avrcp   : make
07-27 11:04:35.269  7075  7075 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-27 11:04:35.269  7075  7075 I bluedroid-qcom: get_profile_interface avrcp
07-27 11:04:35.273  7075  7553 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:04:35.279  7075  7075 V AudioManager: registerRemoteController: size of Media player list: 0
07-27 11:04:35.280  7075  7075 E AudioManager: No RCC entry present to update
07-27 11:04:35.280  7075  7075 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-27 11:04:35.283  7075  7553 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:04:35.283  7075  7075 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-27 11:04:35.284  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 11:04:35.284  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:35.284  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 11:04:35.284  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-27 11:04:35.284  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-27 11:04:35.284  7075  7075 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-27 11:04:35.288  7146  7146 I AppUp4:CustModeStarterReceiver: onReceive
07-27 11:04:35.289  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,07-27 11:04:35.293  7075  7553 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:04:35.295  7146  7146 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2c658109
07-27 11:04:35.295  7146  7146 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 11:04:35.295  7146  7146 D AppUp4:CustFacade: isPhone : true
07-27 11:04:35.346  7146  7146 D AppUp4:CustModeStarterReceiver: begin check event
,07-27 11:04:35.347  7146  7146 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-27 11:04:35.368  7075  7553 V LGMDMManager: Create singleton instance
,07-27 11:04:35.371  7075  7553 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-27 11:04:35.371  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:35.371  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:04:35.373  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:04:35.376  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:04:35.385  4297  7598 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-27 11:04:35.401  7180  7180 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-27 11:04:35.408  4297  7599 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:35.408  4297  7599 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 11:04:35.427  3467  3467 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-27 11:04:35.427  3467  3467 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:04:35.427  3467  3467 I LgeMiscReceiver: networkInfo.isConnected() = false
07-27 11:04:35.431  7216  7216 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-27 11:04:35.432  7216  7216 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-27 11:04:35.440  7180  7603 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 11:04:35.445  7050  7601 W FormManager: Network not available. Please check & try again.
07-27 11:04:35.448  7050  7604 V FormManager: Network unavailable.
07-27 11:04:35.450  7050  7604 V FormManager: Network unavailable.
07-27 11:04:35.452  7578  7578 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-27 11:04:35.452  7578  7578 W LG Account v2.2: No ProfileInfo entries
07-27 11:04:35.452  7578  7578 I LG Account v2.2: isEnabled: false
,07-27 11:04:35.452  7578  7578 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-27 11:04:35.452  1036  1998 V SIM_STK : Menu title from STK is T-Mobile
07-27 11:04:35.452  7578  7578 I Feature : [Lifetracker]Country: EU
07-27 11:04:35.452  1036  1998 V SIM_STK : Menu title from STK is T-Mobile
07-27 11:04:35.452  7578  7578 I Feature : [Lifetracker]Operator: OPEN
07-27 11:04:35.452  7578  7578 I Feature : [Lifetracker]Ranking support: false
07-27 11:04:35.453  7578  7578 I Feature : [Lifetracker]Comfort support: false
07-27 11:04:35.453  7578  7578 I Feature : [Lifetracker]Accessory: true
07-27 11:04:35.453  7578  7578 I Feature : [Lifetracker]Health device: true
07-27 11:04:35.453  7578  7578 I Feature : [Lifetracker]Extra Pedometer: false
07-27 11:04:35.453  7578  7578 I Feature : [Lifetracker]Blood glucose device: false
07-27 11:04:35.453  7578  7578 I Feature : [Lifetracker]Device Number: 3
,07-27 11:04:35.464  6964  6964 D BluetoothPermissionRequest: onReceive
,07-27 11:04:35.466  6964  6964 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-27 11:04:35.476  7280  7280 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:4:35
07-27 11:04:35.477  7280  7280 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 11:04:35.477  7280  7280 D Weather.Utils: 2 : All the weather widget is gone.
07-27 11:04:35.478  7280  7280 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 11:04:35.478  7280  7280 D WeatherAncestor: connectivity changed - connection : true
07-27 11:04:35.478  7280  7280 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@12cf6d2f
,07-27 11:04:35.480  7280  7280 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,07-27 11:04:35.480  7280  7280 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 11:04:35.480  7280  7280 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-27 11:04:35.480  7280  7280 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 11:04:35.480  7280  7280 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:4:35
07-27 11:04:35.495  6535  6535 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-27 11:04:35.496  6535  6567 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-27 11:04:35.511  2231  2231 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:04:35.520  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 11:04:35.520  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:35.520  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 11:04:35.520  7146  7146 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-27 11:04:35.521  7146  7146 I AppUp4:CustModeStarterReceiver: onReceive
,07-27 11:04:35.525  7146  7146 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2c658109
07-27 11:04:35.525  7146  7146 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 11:04:35.525  7146  7146 D AppUp4:CustFacade: isPhone : true
07-27 11:04:35.525  7146  7146 D AppUp4:CustModeStarterReceiver: begin check event
07-27 11:04:35.525  7146  7146 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-27 11:04:35.528  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:35.529  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:04:35.530  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:04:35.530  1036  1929 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-27 11:04:35.533  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:04:35.536  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,07-27 11:04:35.539  4297  7607 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 11:04:35.540  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-27 11:04:35.540  7180  7180 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-27 11:04:35.540  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-27 11:04:35.540  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-27 11:04:35.540  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-27 11:04:35.540  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 11:04:35.540  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-27 11:04:35.540  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-27 11:04:35.540  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-27 11:04:35.540  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 11:04:35.541  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-27 11:04:35.541  7075  7075 I BluetoothA2dpServiceJni: classInitNative
07-27 11:04:35.541  7075  7075 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 11:04:35.541  7075  7075 D A2dpStateMachine: make
07-27 11:04:35.542  7075  7075 I bluedroid-qcom: get_profile_interface a2dp
07-27 11:04:35.542  7075  7610 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-27 11:04:35.544  7075  7075 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-27 11:04:35.544  7075  7075 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-27 11:04:35.545  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:35.546  7075  7075 D HeadsetStateMachine: Proxy object connected
07-27 11:04:35.546  7075  7609 D A2dpStateMachine: Enter Disconnected: -2
07-27 11:04:35.546  7075  7075 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-27 11:04:35.546  7075  7075 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-27 11:04:35.548  4297  7608 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:35.548  4297  7608 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 11:04:35.548  7075  7075 I BluetoothHidServiceJni: classInitNative: succeeds
,07-27 11:04:35.550  7075  7075 D HidService: Received start request. Starting profile...
07-27 11:04:35.550  7075  7075 I bluedroid-qcom: get_profile_interface hidhost
07-27 11:04:35.550  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:35.554  7075  7075 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:04:35.555  7075  7075 I BluetoothHealthServiceJni: classInitNative: succeeds
07-27 11:04:35.555  7075  7576 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 11:04:35.556  7075  7576 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 11:04:35.556  7075  7576 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-27 11:04:35.557  7075  7075 D HealthService: Received start request. Starting profile...
07-27 11:04:35.559  7075  7075 I bluedroid-qcom: get_profile_interface health
07-27 11:04:35.559  7075  7075 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-27 11:04:35.559  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:35.560  7075  7075 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-27 11:04:35.560  7180  7613 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:35.561  7075  7075 D PanService: Received start request. Starting profile...
07-27 11:04:35.561  7075  7075 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 11:04:35.561  7075  7075 I bluedroid-qcom: get_profile_interface pan
,07-27 11:04:35.565  3467  3467 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-27 11:04:35.565  3467  3467 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:35.565  3467  3467 I LgeMiscReceiver: networkInfo.isConnected() = false
07-27 11:04:35.566  7075  7075 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-27 11:04:35.566  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:35.567  7075  7075 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-27 11:04:35.569  7216  7216 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-27 11:04:35.569  7216  7216 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-27 11:04:35.572  7075  7075 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 11:04:35.572  7075  7075 D BtGatt.GattService: Received start request. Starting profile...
07-27 11:04:35.572  7075  7075 D BtGatt.GattService: start()
07-27 11:04:35.572  7075  7075 I bluedroid-qcom: get_profile_interface gatt
07-27 11:04:35.573  7075  7075 D BtGatt.AdvertiseManager: advertise manager created
07-27 11:04:35.574  7050  7614 W FormManager: Network not available. Please check & try again.
07-27 11:04:35.581  7050  7616 V FormManager: Network unavailable.
,07-27 11:04:35.582  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
,07-27 11:04:35.584  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:35.584  7075  7075 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-27 11:04:35.584  7280  7280 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:4:35
07-27 11:04:35.585  7075  7075 V BluetoothMapService: BluetoothMapBinder()
07-27 11:04:35.586  7280  7280 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 11:04:35.586  7280  7280 D Weather.Utils: 2 : All the weather widget is gone.
07-27 11:04:35.586  7075  7075 D BluetoothMapService: Received start request. Starting profile...
07-27 11:04:35.586  7075  7075 D BluetoothMapService: start()
07-27 11:04:35.586  7280  7280 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 11:04:35.586  7280  7280 D WeatherAncestor: connectivity changed - connection : true
07-27 11:04:35.586  7280  7280 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@12cf6d2f
07-27 11:04:35.587  7050  7616 V FormManager: Network unavailable.
07-27 11:04:35.589  7075  7075 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-27 11:04:35.589  7075  7075 D BluetoothMapEmailAppObserver: createReceiver()
07-27 11:04:35.590  7075  7075 D BluetoothMapEmailAppObserver: initObservers()
07-27 11:04:35.591  7075  7075 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-27 11:04:35.592  7280  7280 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 11:04:35.592  7280  7280 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 11:04:35.592  7280  7280 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-27 11:04:35.592  7280  7280 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 11:04:35.592  7280  7280 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:4:35
07-27 11:04:35.600  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
,07-27 11:04:35.603  7075  7075 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:04:35.606  7075  7075 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:04:35.609  7075  7075 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:04:35.612  7075  7075 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:04:35.612  7075  7075 V PanService: [BTUI] SIM Extra State :ABSENT
,07-27 11:04:35.616  7075  7075 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,07-27 11:04:35.616  7075  7075 V BluetoothMapService: Handler(): got msg=1
07-27 11:04:35.617  7075  7553 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-27 11:04:35.617  7075  7553 I bluedroid-qcom: enable
07-27 11:04:35.617  7075  7622 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-27 11:04:35.618  7075  7622 I bt-btu  : btu_task pending for preload complete event
07-27 11:04:35.618  7075  7553 I bt_hci_bdroid: init
07-27 11:04:35.619  7075  7075 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:35.619  7075  7553 I bt_vendor: bt-vendor : init
07-27 11:04:35.619  7075  7553 I bt_vendor: bt-vendor : get_bt_soc_type
07-27 11:04:35.619  7075  7553 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-27 11:04:35.619  7075  7553 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-27 11:04:35.619  7075  7553 D bt_userial_mct: userial_init
07-27 11:04:35.621  7075  7075 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 11:04:35.621  7075  7553 D bt_hci_bdroid: set_power 1
07-27 11:04:35.621  7075  7075 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 11:04:35.621  7075  7553 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-27 11:04:35.621  7075  7075 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 11:04:35.621  7075  7553 I bt_vendor: Starting hciattach daemon
07-27 11:04:35.621  7075  7553 I bt_vendor: try to set true
07-27 11:04:35.621  7075  7075 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:35.621  7075  7075 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-27 11:04:35.616  7625  7625 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:35.616  7625  7625 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:35.645  7626  7626 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-27 11:04:35.757  7632  7632 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-27 11:04:35.769  7633  7633 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-27 11:04:35.804  7635  7635 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-27 11:04:35.829  7636  7636 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,07-27 11:04:35.848  7641  7641 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-27 11:04:35.859  7643  7643 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-27 11:04:35.881  7645  7645 I libmdmdetect: ESOC framework not supported
,07-27 11:04:35.881  7645  7645 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
07-27 11:04:35.889  7645  7645 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
07-27 11:04:35.889  7645  7645 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-27 11:04:35.890  7645  7645 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-27 11:04:35.890  7645  7645 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-27 11:04:35.890  7645  7645 D bthci_qcomm_common: [BTUI]     LE: Class 2,
07-27 11:04:35.890  7645  7645 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-27 11:04:35.890  7645  7645 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-27 11:04:35.926  7645  7646 E QC-QMI  : qmi_client [7645] 14: failed to locate client data
07-27 11:04:35.928   478   478 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-27 11:04:35.928   478   478 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,07-27 11:04:35.973  7647  7647 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
07-27 11:04:35.985  7648  7648 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-27 11:04:36.011  1036  1099 W ProcessCpuTracker: Skipping unknown process pid 7625
,07-27 11:04:36.012  1036  1099 W ProcessCpuTracker: Skipping unknown process pid 7647
,07-27 11:04:36.024  7075  7553 I bt_vendor: bluetooth satus is on
07-27 11:04:36.024  7075  7553 D bt_hci_bdroid: preload
07-27 11:04:36.024  7075  7624 D bt_userial_mct: userial_open(port:0)
07-27 11:04:36.024  7075  7624 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,07-27 11:04:36.028  7075  7624 I bt_vendor: Done intiailizing UART
07-27 11:04:36.031  7075  7624 I bt_vendor: Done intiailizing UART
07-27 11:04:36.031  7075  7624 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-27 11:04:36.031  7075  7624 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-27 11:04:36.032  7075  7650 D bt_userial_mct: Entering userial_read_thread()
07-27 11:04:36.032  7075  7622 I bt-btu  : btu_task received preload complete event
,07-27 11:04:36.032  7075  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-27 11:04:36.032  7075  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-27 11:04:36.034  7075  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-27 11:04:36.038  7075  7622 I         : BTE_InitTraceLevels -- TRC_HCI
07-27 11:04:36.038  7075  7622 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-27 11:04:36.038  7075  7622 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-27 11:04:36.038  7075  7622 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-27 11:04:36.039  7075  7622 I         : BTE_InitTraceLevels -- TRC_AVRC
07-27 11:04:36.039  7075  7622 I         : BTE_InitTraceLevels -- TRC_A2D
07-27 11:04:36.039  7075  7622 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 11:04:36.039  7075  7622 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 11:04:36.039  7075  7622 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-27 11:04:36.039  7075  7622 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 11:04:36.039  7075  7622 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 11:04:36.043  7075  7622 I         : BTE_InitTraceLevels -- TRC_SDP
07-27 11:04:36.043  7075  7622 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 11:04:36.043  7075  7622 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 11:04:36.043  7075  7622 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-27 11:04:36.043  7075  7622 I         : BTE_InitTraceLevels -- TRC_BTIF
07-27 11:04:36.133  7075  7622 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-27 11:04:36.133  7075  7622 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ad061 
07-27 11:04:36.134  7075  7622 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ad061 
,07-27 11:04:36.183  7075  7557 E bt-btif : Calling BTA_HhEnable
07-27 11:04:36.183  7075  7557 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,07-27 11:04:36.183  7075  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-27 11:04:36.183  7075  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-27 11:04:36.183  7075  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-27 11:04:36.184  7075  7557 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-27 11:04:36.184  7075  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-27 11:04:36.184  7075  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-27 11:04:36.186  7075  7557 D BluetoothAdapterProperties: Name is: G3
07-27 11:04:36.188  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-27 11:04:36.189  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-27 11:04:36.192  7075  7557 D BluetoothAdapterProperties: Scan Mode:20
07-27 11:04:36.193  7075  7557 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 11:04:36.193  7075  7557 D bt_hci_bdroid: postload
07-27 11:04:36.194  7075  7624 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 11:04:36.195  7075  7624 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 11:04:36.195  7075  7557 D bte_conf: Device ID record 1 : primary
07-27 11:04:36.195  7075  7557 D bte_conf:   vendorId            = 00c4
07-27 11:04:36.195  7075  7557 D bte_conf:   vendorIdSource      = 0001
07-27 11:04:36.195  7075  7557 D bte_conf:   product             = 13a1
07-27 11:04:36.195  7075  7557 D bte_conf:   version             = 1000
07-27 11:04:36.195  7075  7557 D bte_conf:   clientExecutableURL = 
07-27 11:04:36.196  7075  7557 D bte_conf:   serviceDescription  = 
07-27 11:04:36.196  7075  7557 D bte_conf:   documentationURL    = 
07-27 11:04:36.196  7075  7557 D bte_conf: bte_load_did_conf no section named DID2.
07-27 11:04:36.199  7075  7624 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 11:04:36.195  7075  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,07-27 11:04:36.202  7075  7557 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-27 11:04:36.196  7652  7652 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-27 11:04:36.209  7075  7622 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:04:36.209  7075  7622 W bt-smp  : Plain text(LSB ~ MSB) = 1b bd 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:04:36.209  7075  7622 W bt-smp  : Encrypted text(LSB ~ MSB) = 4a 13 00 7b c0 17 8a b3 8b 7d 05 4d e8 b0 68 91 
07-27 11:04:36.196  7652  7652 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:36.210  7075  7624 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 11:04:36.210  7075  7622 W bt-btm  : Stopping oneshot timer
07-27 11:04:36.211  7075  7553 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-27 11:04:36.211  7075  7553 D BluetoothAdapterProperties: ScanMode =  20
07-27 11:04:36.212  7075  7553 D BluetoothAdapterProperties: State =  11
07-27 11:04:36.212  7075  7553 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-27 11:04:36.212  7075  7650 E bt_mct  : hci lib postload completed
07-27 11:04:36.213  7075  7553 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-27 11:04:36.213  7075  7553 D BluetoothAdapterProperties: Setting state to 12
07-27 11:04:36.213  7075  7553 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-27 11:04:36.214  7075  7557 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-27 11:04:36.217  1036  1118 D BluetoothManagerService: Message: 60
07-27 11:04:36.217  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,07-27 11:04:36.219  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
07-27 11:04:36.220  7075  7553 I BluetoothAdapterState: Entering On State
07-27 11:04:36.224  6964  7444 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-27 11:04:36.229  1838  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:04:36.232  7075  7553 D LGBluetoothServiceAdapter: [BTUI] OnState
07-27 11:04:36.232  7075  7553 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-27 11:04:36.233  7075  7553 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-27 11:04:36.233  7075  7553 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-27 11:04:36.235  7075  7557 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 11:04:36.235  7075  7557 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,07-27 11:04:36.237  1838  1838 D BluetoothHeadset: Proxy object connected
07-27 11:04:36.238  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:36.238  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:36.238  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:36.238  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:04:36.238  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:36.238  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:36.238  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:36.238  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:04:36.239  6964  6981 D BluetoothMap: onBluetoothStateChange: up=true
07-27 11:04:36.239  6964  6964 D BluetoothInputDevice: Proxy object connected
07-27 11:04:36.239  6964  6964 D HidProfile: Bluetooth service connected
07-27 11:04:36.245  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:04:36.252  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:36.252  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:36.252  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:36.252  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:04:36.252  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:36.252  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:36.252  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:36.252  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:04:36.257  7075  7622 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:04:36.257  7075  7622 W bt-smp  : Plain text(LSB ~ MSB) = 23 f5 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:04:36.257  7075  7622 W bt-smp  : Encrypted text(LSB ~ MSB) = ca 6b 16 f6 e4 d3 e6 40 c7 b5 73 86 50 d2 8e 7a 
07-27 11:04:36.257  7075  7622 W bt-btm  : Stopping oneshot timer
07-27 11:04:36.258  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:04:36.259  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 11:04:36.260  6964  7444 D BluetoothPan: onBluetoothStateChange on: true
07-27 11:04:36.260  6964  7444 D BluetoothPan: onBluetoothStateChange call bindService
07-27 11:04:36.262  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:04:36.263  1838  2456 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:04:36.265  1036  1036 D BluetoothA2dp: Proxy object connected
,07-27 11:04:36.267  1036  1036 D BluetoothHeadset: Proxy object connected
07-27 11:04:36.268  1838  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:04:36.269  1838  1838 D BluetoothHeadset: Proxy object connected
07-27 11:04:36.262  6964  6964 D BluetoothMap: Proxy object connected
07-27 11:04:36.269  6964  6964 D MapProfile: Bluetooth service connected
07-27 11:04:36.269  6964  6964 D BluetoothMap: getConnectedDevices()
07-27 11:04:36.270  7075  7659 V BluetoothMapService: getConnectedDevices()
07-27 11:04:36.271  1838  1838 D BluetoothHeadset: Proxy object connected
07-27 11:04:36.271  7075  7553 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-27 11:04:36.271  6964  7444 D BluetoothPbap: onBluetoothStateChange: up=true
07-27 11:04:36.272  6964  6964 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 11:04:36.272  6964  6964 D PanProfile: Bluetooth service connected
07-27 11:04:36.274  7075  7622 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:04:36.274  7075  7622 W bt-smp  : Plain text(LSB ~ MSB) = b8 c0 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:04:36.274  7075  7622 W bt-smp  : Encrypted text(LSB ~ MSB) = 59 12 8e 40 0f b9 7f a1 78 32 b2 2d 5f 24 10 84 
07-27 11:04:36.274  7075  7622 W bt-btm  : Stopping oneshot timer
07-27 11:04:36.276  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-27 11:04:36.276  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-27 11:04:36.278  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-27 11:04:36.279  1036  1118 D BluetoothManagerService: Message: 40
,07-27 11:04:36.279  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-27 11:04:36.281  7663  7663 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-27 11:04:36.282  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:36.283  1926  2110 D LGBluetoothAPIService: Message: 1
07-27 11:04:36.283  1926  2110 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-27 11:04:36.284  7075  7622 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:04:36.284  7075  7622 W bt-smp  : Plain text(LSB ~ MSB) = dd b4 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:04:36.284  7075  7622 W bt-smp  : Encrypted text(LSB ~ MSB) = eb 74 09 1d 10 55 77 55 96 bd 4e 31 41 92 f5 5e 
07-27 11:04:36.284  7075  7622 W bt-btm  : Stopping oneshot timer
07-27 11:04:36.284  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 11:04:36.287  7075  7075 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:36.288  7075  7075 D BluetoothMapService: STATE_ON
07-27 11:04:36.288  7075  7075 V BluetoothMapService: Handler(): got msg=1
07-27 11:04:36.289  7075  7075 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-27 11:04:36.291  6733  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
07-27 11:04:36.291  7075  7665 D BluetoothMapMasInstance: MAS initSocket()
07-27 11:04:36.291  7075  7665 D BluetoothMapMasInstance:   masId = 00
07-27 11:04:36.291  7075  7665 D BluetoothMapMasInstance:   msgTypes = 0e
07-27 11:04:36.291  7075  7665 D BluetoothMapMasInstance:   masName = SMS/MMS
07-27 11:04:36.291  7075  7665 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,07-27 11:04:36.296  7075  7622 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:04:36.296  7075  7622 W bt-smp  : Plain text(LSB ~ MSB) = 8c 67 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:04:36.296  7075  7622 W bt-smp  : Encrypted text(LSB ~ MSB) = 2c da 34 7b 40 24 02 a1 da b1 d1 ab 9b af c0 5f 
07-27 11:04:36.296  7075  7622 W bt-btm  : Stopping oneshot timer
07-27 11:04:36.297  1926  2110 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-27 11:04:36.297  1036  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:36.298  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:36.298  6964  6964 D LocalBluetoothProfileManager: Adding local A2DP profile
07-27 11:04:36.298  7075  7665 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:04:36.300  7075  7665 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-27 11:04:36.300  1036  1118 D BluetoothManagerService: Message: 30
07-27 11:04:36.301  7075  7665 V BluetoothMapMasInstance: Succeed to create listening socket 
07-27 11:04:36.301  7075  7665 D BluetoothMapMasInstance: Accepting socket connection...
07-27 11:04:36.301  7075  7557 D BluetoothAdapterProperties: Scan Mode:21
07-27 11:04:36.302  7075  7557 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-27 11:04:36.302  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:36.304  6964  6964 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-27 11:04:36.306  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:36.307  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:36.307  7075  7075 V BluetoothPbapService: Pbap Service onCreate
07-27 11:04:36.307  7075  7075 V BluetoothPbapService: Starting PBAP service
07-27 11:04:36.309  1036  1118 D BluetoothManagerService: Message: 30
07-27 11:04:36.309  7075  7075 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-27 11:04:36.310  7075  7075 V BluetoothPbapService: Pbap Service onBind
07-27 11:04:36.311  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:36.312  7075  7075 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:36.312  7075  7075 V BluetoothPbapService: state: 12
07-27 11:04:36.313  7075  7075 D LGBluetoothAPIServer: [BTUI] onCreate()
07-27 11:04:36.313  7075  7075 D LGBluetoothAPIServer: [BTUI] onBind()
07-27 11:04:36.314  7075  7075 V BluetoothPbapService: Handler(): got msg=1
07-27 11:04:36.314  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-27 11:04:36.315  1926  2110 D LGBluetoothAPIService: Message: 100
07-27 11:04:36.315  1926  2110 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-27 11:04:36.315  7075  7075 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-27 11:04:36.316  7075  7666 V BluetoothPbapService: Pbap Service initSocket
07-27 11:04:36.317  6964  6964 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-27 11:04:36.317  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 11:04:36.319  6964  6964 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-27 11:04:36.321  7075  7666 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:04:36.325  6964  6964 D BluetoothA2dp: Proxy object connected
,07-27 11:04:36.325  7075  7666 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-27 11:04:36.325  7075  7666 V BluetoothPbapService: Succeed to create listening socket 
07-27 11:04:36.325  7075  7666 V BluetoothPbapService: Accepting socket connection...
07-27 11:04:36.326  6964  6964 D A2dpProfile: Bluetooth service connected
07-27 11:04:36.327  7075  7075 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 11:04:36.327  7075  7075 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:36.327  7075  7075 V BluetoothPbapReceiver: ***********state = 12
07-27 11:04:36.328  6964  6964 D BluetoothPbap: Proxy object connected
07-27 11:04:36.328  6964  6964 D PbapServerProfile: Bluetooth service connected
07-27 11:04:36.328  6964  6964 D BluetoothHeadset: Proxy object connected
07-27 11:04:36.329  2231  2231 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 11:04:36.330  6964  6964 D HeadsetProfile: Bluetooth service connected
07-27 11:04:36.330  2231  2231 D c       : Getting all permits...
07-27 11:04:36.330  2231  2231 D a       : Opening database...
,07-27 11:04:36.334  2231  2231 D a       : Opening database auth.proximity.permit_store...
07-27 11:04:36.334  6964  6964 D DockEventReceiver: finishStartingService: stopping service
07-27 11:04:36.334  2231  2231 D a       : Closing database...
07-27 11:04:36.346  6964  6964 D BluetoothPermissionRequest: onReceive
,07-27 11:04:36.348  6964  6964 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-27 11:04:36.350  6964  6964 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 11:04:36.350  7312  7345 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
07-27 11:04:36.353  7075  7075 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-27 11:04:36.354  7075  7075 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-27 11:04:36.359  7075  7075 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,07-27 11:04:36.379  7075  7075 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,07-27 11:04:36.380  7075  7075 V BtOppService: onCreate
,07-27 11:04:36.384  7075  7075 V BluetoothOppNotification: send message
07-27 11:04:36.388  7075  7075 V BtOppService: Starting RfcommListener
,07-27 11:04:36.397  7075  7075 D BluetoothOppPreference: Dumping Names:  
07-27 11:04:36.397  7075  7075 D BluetoothOppPreference: {}
07-27 11:04:36.397  7075  7075 D BluetoothOppPreference: Dumping Channels:  
07-27 11:04:36.397  7075  7075 D BluetoothOppPreference: {}
07-27 11:04:36.399  7075  7075 V BtOppService: onStartCommand
,07-27 11:04:36.403  7075  7075 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:36.403  7075  7075 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-27 11:04:36.405  7075  7673 V BtOppService: Deleted complete outbound shares, number =  0
07-27 11:04:36.405  7075  7676 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 11:04:36.406  7075  7676 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 11:04:36.407  7075  7075 V BluetoothOppNotification: new notify threadi!
07-27 11:04:36.408  7075  7673 V BtOppService: Deleted complete inbound failed shares, number = 0
07-27 11:04:36.409  7075  7075 V BluetoothOppNotification: send delay message
07-27 11:04:36.412  7075  7673 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-27 11:04:36.412  7075  7075 V BtOppService: start RfcommListener
07-27 11:04:36.413  7075  7676 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a3e0b8 on behalf of 
07-27 11:04:36.414  7075  7677 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-27 11:04:36.414  7075  7673 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a8eee91 on behalf of 
07-27 11:04:36.415  7075  7676 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,07-27 11:04:36.418  7075  7677 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10b1f1f6 on behalf of 
07-27 11:04:36.418  7075  7075 V BtOppService: RfcommListener started
07-27 11:04:36.419  7075  7075 V BtOppService: ContentObserver received notification
07-27 11:04:36.420  7075  7679 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 11:04:36.421  7075  7679 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 11:04:36.421  7075  7677 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-27 11:04:36.423  7075  7677 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-27 11:04:36.426  7075  7679 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2dc129f7 on behalf of 
07-27 11:04:36.426  7075  7678 V BtOppRfcommListener: Starting RFCOMM listener....
07-27 11:04:36.427  1036  1639 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:36.427  7075  7677 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2125064 on behalf of 
07-27 11:04:36.428  7075  7678 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:04:36.428  7075  7679 V BluetoothOppNotification: update too frequent, put in queue
,07-27 11:04:36.432  7075  7678 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
07-27 11:04:36.432  7075  7679 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-27 11:04:36.433  7075  7677 V BluetoothOppNotification: outbound: succ-0  fail-0
07-27 11:04:36.433  7075  7678 V BtOppRfcommListener: Started RFCOMM listener....
07-27 11:04:36.433  7075  7678 I BtOppRfcommListener: Accept thread started.
07-27 11:04:36.433  7075  7678 V BtOppRfcommListener: Accepting connection...
07-27 11:04:36.434  7075  7677 V BluetoothOppNotification: outbound notification was removed.
07-27 11:04:36.434  7075  7677 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 11:04:36.437  7075  7677 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7a2e2cd on behalf of 
07-27 11:04:36.438  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:36.438  7075  7075 V BluetoothFtpService: Ftp Service onCreate
07-27 11:04:36.438  7075  7075 I BluetoothFtpService: Ftp Service onCreate
07-27 11:04:36.438  7075  7075 V BluetoothFtpService: Ftp Service onStartCommand
07-27 11:04:36.438  7075  7075 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:36.438  7075  7677 V BluetoothOppNotification: inbound: succ-0  fail-0
07-27 11:04:36.438  7075  7075 V BluetoothFtpService: Starting Listening on sockets
07-27 11:04:36.439  7075  7075 V BtOppService: ContentObserver received notification
07-27 11:04:36.439  7075  7075 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 11:04:36.439  7075  7075 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 11:04:36.439  7075  7075 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 11:04:36.439  7075  7075 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:36.439  7075  7075 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-27 11:04:36.439  7075  7075 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-27 11:04:36.440  7075  7680 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 11:04:36.440  7075  7680 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,07-27 11:04:36.441  7075  7680 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11d46e93 on behalf of 
07-27 11:04:36.442  7075  7680 V BluetoothOppNotification: update too frequent, put in queue
07-27 11:04:36.443  7075  7075 V BluetoothFtpService: Handler(): got msg=1
07-27 11:04:36.445  7075  7075 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-27 11:04:36.445  7075  7075 V BluetoothFtpService: Ftp Service initSocket
07-27 11:04:36.445  7075  7680 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-27 11:04:36.446  7075  7677 V BluetoothOppNotification: inbound notification was removed.
07-27 11:04:36.446  7075  7677 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 11:04:36.449  7075  7677 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29d60ed0 on behalf of 
07-27 11:04:36.450  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:36.452  7075  7075 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:04:36.453  7075  7075 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
,07-27 11:04:36.453  7075  7075 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-27 11:04:36.456  7075  7681 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-27 11:04:36.469  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:36.469  7075  7075 V BluetoothSapService: Sap Service onCreate
,07-27 11:04:36.472  7075  7075 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:04:36.472  7075  7075 V BluetoothSapService: state: 12
07-27 11:04:36.472  7075  7075 V BluetoothSapService: Starting SAP server process
07-27 11:04:36.473  7075  7075 V BluetoothSapService: SAP Service startRfcommListenerThread
07-27 11:04:36.475  7075  7683 V BluetoothSapService: Sap Service initRfcommSocket
07-27 11:04:36.475  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:36.466  7682  7682 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:36.476  7075  7683 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:04:36.466  7682  7682 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:36.478  7075  7683 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
07-27 11:04:36.478  7075  7683 V BluetoothSapService: Succeed to create listening socket 
07-27 11:04:36.478  7075  7683 V BluetoothSapService: Accepting socket connection...
07-27 11:04:36.500  7682  7682 V BT_SAP  : Event pipe created
07-27 11:04:36.500  7682  7682 V BT_SAP  : create_server_socket qcom.sap.server
07-27 11:04:36.500  7682  7682 V BT_SAP  : created socket fd 6
,07-27 11:04:37.017  1036  1524 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:37.017  1036  1524 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 11:04:37.068  1036  1525 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-27 11:04:37.070  1036  1525 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-27 11:04:37.414  7075  7075 V BluetoothOppNotification: new notify threadi!
,07-27 11:04:37.422  7075  7075 V BluetoothOppNotification: send delay message
,07-27 11:04:37.436  1036  1757 I ActivityManager: Killing 7474:com.lge.bnr/1000 (adj 15): empty #17
,07-27 11:04:37.451  7075  7693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,07-27 11:04:37.461  7075  7693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7d547fc on behalf of 
07-27 11:04:37.462  7075  7693 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-27 11:04:37.463  7075  7693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,07-27 11:04:37.466  7075  7693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3aa69e85 on behalf of 
07-27 11:04:37.468  7075  7693 V BluetoothOppNotification: outbound: succ-0  fail-0
07-27 11:04:37.470  7075  7693 V BluetoothOppNotification: outbound notification was removed.
07-27 11:04:37.470  7075  7693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 11:04:37.471  7075  7693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d1c34da on behalf of 
07-27 11:04:37.472  7075  7693 V BluetoothOppNotification: inbound: succ-0  fail-0
07-27 11:04:37.473  7075  7693 V BluetoothOppNotification: inbound notification was removed.
07-27 11:04:37.473  7075  7693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 11:04:37.474  7075  7693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37b91d0b on behalf of 
07-27 11:04:37.479  1036  1052 W libprocessgroup: failed to open /acct/uid_1000/pid_7474/cgroup.procs: No such file or directory
,07-27 11:04:37.569  1036  1887 I ActivityManager: Killing 6859:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,07-27 11:04:37.593  7012  7012 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-27 11:04:37.593  7012  7012 W System.err: android.os.DeadObjectException
07-27 11:04:37.593  7012  7012 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 11:04:37.593  7012  7012 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 11:04:37.593  7012  7012 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-27 11:04:37.593  7012  7012 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-27 11:04:37.593  7012  7012 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-27 11:04:37.593  7012  7012 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
,07-27 11:04:37.593  7012  7012 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 11:04:37.597  7012  7012 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 11:04:37.597  7012  7012 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 11:04:37.597  7012  7012 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 11:04:37.598  7012  7012 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:04:37.598  7012  7012 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:04:37.598  7012  7012 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 11:04:37.598  7012  7012 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 11:04:37.598  7012  7012 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-27 11:04:37.598  7012  7012 W System.err: android.os.DeadObjectException
07-27 11:04:37.599  7012  7012 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 11:04:37.599  7012  7012 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 11:04:37.599  7012  7012 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-27 11:04:37.599  7012  7012 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-27 11:04:37.599  7012  7012 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-27 11:04:37.599  7012  7012 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-27 11:04:37.599  7012  7012 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 11:04:37.599  7012  7012 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 11:04:37.599  7012  7012 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 11:04:37.599  7012  7012 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 11:04:37.599  7012  7012 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:04:37.599  7012  7012 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:04:37.599  7012  7012 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 11:04:37.599  7012  7012 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 11:04:37.600  7012  7012 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-27 11:04:37.601  7012  7012 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
07-27 11:04:37.628  1036  1990 W libprocessgroup: failed to open /acct/uid_1000/pid_6859/cgroup.procs: No such file or directory
07-27 11:04:37.628  1036  1990 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,07-27 11:04:37.638  7012  7012 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-27 11:04:37.638  7012  7012 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-27 11:04:37.680  1036  1963 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7694 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 11:04:37.680  7012  7012 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-27 11:04:37.766  7694  7694 D UEI.SmartControl: Quickset Services start...
,07-27 11:04:37.771  7694  7694 I UEI.SmartControl: Manufacture = LGE
,07-27 11:04:37.771  7694  7694 D UEI.SmartControl: Id = LGNevo
07-27 11:04:37.772  7694  7694 D UEI.SmartControl: File observer start...
07-27 11:04:37.773  7694  7694 E UEI.SmartControl: IR Port is disabled: false
07-27 11:04:37.773  7694  7694 D UEI.SmartControl: Starting file observer...
07-27 11:04:37.773  7694  7694 D UEI.SmartControl: Extracting JNI libs...
07-27 11:04:37.774  7694  7694 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-27 11:04:37.862  7694  7694 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-27 11:04:37.862  7694  7694 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-27 11:04:37.862  7694  7694 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-27 11:04:37.904  7694  7694 I UEI.SmartControl: --- Selecting new region: 6
07-27 11:04:37.906  7694  7694 I UEI.SmartControl: Model = LG-D855
,07-27 11:04:37.911  7694  7694 D UEI.SmartControl: QS Service created
07-27 11:04:37.927  7694  7694 I UEI.SmartControl: Service initServices...
,07-27 11:04:37.935  7694  7694 D UEI.SmartControl: QS start get config
,07-27 11:04:37.996  7694  7694 D UEI.SmartControl: Loading JNI Libs...
,07-27 11:04:38.019  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 11:04:38.019  1036  1052 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2526b05e mBinding = false
,07-27 11:04:38.037  1036  1118 D BluetoothManagerService: Message: 2
,07-27 11:04:38.041  1036  1118 D BluetoothManagerService: Sending off request.
07-27 11:04:38.042  7075  7091 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-27 11:04:38.043  7075  7553 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-27 11:04:38.043  7075  7553 D BluetoothAdapterProperties: Setting state to 13
07-27 11:04:38.043  7075  7553 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-27 11:04:38.044  7075  7553 D BluetoothAdapterProperties: onBluetoothDisable()
07-27 11:04:38.044  7075  7553 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-27 11:04:38.045  7075  7557 D BluetoothAdapterProperties: Scan Mode:20
07-27 11:04:38.047  7075  7553 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-27 11:04:38.048  7075  7553 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-27 11:04:38.049  7075  7665 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-27 11:04:38.049  7075  7665 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:04:38.049  7075  7665 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-27 11:04:38.049  7075  7665 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-27 11:04:38.049  7075  7665 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-27 11:04:38.049  7075  7665 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-27 11:04:38.049  7075  7665 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-27 11:04:38.049  7075  7665 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,07-27 11:04:38.051  7075  7666 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:04:38.053  7075  7678 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:04:38.053  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-27 11:04:38.053  7075  7622 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-27 11:04:38.055  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:04:38.055  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:04:38.055  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:04:38.055  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:04:38.055  7075  7622 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:04:38.055  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:04:38.055  7075  7622 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:04:38.055  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:04:38.055  7075  7622 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:04:38.055  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-27 11:04:38.055  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-27 11:04:38.055  7075  7622 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-27 11:04:38.061  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:38.061  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:38.061  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:38.061  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:38.061  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:04:38.061  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:04:38.061  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:38.061  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:38.061  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:04:38.070  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:38.073  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:04:38.078  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 11:04:38.080  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:38.080  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:38.080  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:38.080  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:38.080  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:04:38.080  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:04:38.080  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:38.080  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:38.080  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:04:38.081  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:04:38.081  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:04:38.083  1036  1118 D BluetoothManagerService: Message: 60
07-27 11:04:38.083  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-27 11:04:38.083  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
07-27 11:04:38.085  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,07-27 11:04:38.088  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:38.090  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 11:04:38.090  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-27 11:04:38.094  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:38.097  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:38.099  7075  7075 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:38.099  7075  7075 D BluetoothMapService: STATE_TURNING_OFF
07-27 11:04:38.099  7075  7075 V BluetoothMapService: Handler(): got msg=4
07-27 11:04:38.099  7075  7075 D BluetoothMapService: MAP Service closeService in
07-27 11:04:38.099  7075  7075 D BluetoothMapMasInstance: MAP Service shutdown
07-27 11:04:38.100  7075  7075 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 11:04:38.100  7075  7075 V BluetoothMapService: MAP Service closeService out
07-27 11:04:38.101  7075  7075 V BtOppService: Receiver DISABLED_ACTION 
07-27 11:04:38.101  7075  7075 I BtOppRfcommListener: stopping Accept Thread
07-27 11:04:38.101  7075  7075 V BtOppRfcommListener: close mBtServerSocket
07-27 11:04:38.102  7075  7678 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-27 11:04:38.102  7075  7075 V BtOppRfcommListener: waiting for thread to terminate
07-27 11:04:38.102  7075  7075 V BtOppRfcommListener: done waiting for thread to terminate
07-27 11:04:38.105  6964  6964 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
07-27 11:04:38.120  7075  7681 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-27 11:04:38.128  7075  7683 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:04:38.143  7075  7075 V BtOppService: onDestroy
,07-27 11:04:38.147  7075  7075 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,07-27 11:04:38.269  1036  1639 I art     : Explicit concurrent mark sweep GC freed 70102(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.141ms total 145.202ms
,07-27 11:04:38.271  6964  6964 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-27 11:04:38.283  7075  7075 V BluetoothPbapReceiver: PbapReceiver onReceive 
,07-27 11:04:38.283  7075  7075 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:38.283  7075  7075 V BluetoothPbapReceiver: ***********state = 13
,07-27 11:04:38.286  6964  6964 D DockEventReceiver: finishStartingService: stopping service
07-27 11:04:38.289  7075  7075 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-27 11:04:38.290  7075  7075 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:38.290  7075  7075 V BluetoothPbapService: state: 13
07-27 11:04:38.290  7075  7075 V BluetoothPbapService: Pbap Service closeService in
07-27 11:04:38.294  2231  2231 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 11:04:38.297  7075  7075 V BluetoothPbapService: successfully stopped pbap service
07-27 11:04:38.297  7075  7075 V BluetoothPbapService: Pbap Service closeService out
07-27 11:04:38.297  7075  7075 V BluetoothPbapService: Pbap Service onDestroy
07-27 11:04:38.297  7075  7075 V BluetoothPbapService: Pbap Service closeService in
07-27 11:04:38.297  7075  7075 V BluetoothPbapService: Pbap Service closeService out
07-27 11:04:38.297  7075  7075 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-27 11:04:38.298  6964  6964 D BluetoothPbap: Proxy object disconnected
07-27 11:04:38.298  6964  6964 D PbapServerProfile: Bluetooth service disconnected
07-27 11:04:38.304  6964  6964 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-27 11:04:38.309  6964  6964 D BluetoothPermissionRequest: onReceive
07-27 11:04:38.309  6964  6964 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-27 11:04:38.314  6964  6964 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 11:04:38.317  7075  7075 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-27 11:04:38.317  7075  7075 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,07-27 11:04:38.317  7075  7075 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-27 11:04:38.321  7075  7075 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:38.321  7075  7075 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-27 11:04:38.322  7075  7075 V BluetoothFtpService: Ftp Service onStartCommand
07-27 11:04:38.322  7075  7075 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:38.322  7075  7075 V BluetoothFtpService: Ftp Service closeService
07-27 11:04:38.322  7075  7075 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-27 11:04:38.325  7075  7075 V BluetoothFtpService: successfully stopped ftp service
07-27 11:04:38.326  7075  7075 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 11:04:38.326  7075  7075 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 11:04:38.326  7075  7075 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 11:04:38.326  7075  7075 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:38.326  7075  7075 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-27 11:04:38.326  7075  7075 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-27 11:04:38.327  7075  7075 V BluetoothFtpService: Ftp Service onDestroy
07-27 11:04:38.327  7075  7075 V BluetoothFtpService: Ftp Service closeService
07-27 11:04:38.330  7075  7075 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:38.330  7075  7075 V BluetoothSapService: state: 13
07-27 11:04:38.330  7075  7075 V BluetoothSapService: Stopping SAP server process
07-27 11:04:38.331  7075  7075 V BluetoothSapService: Sap Service closeSapService in
07-27 11:04:38.331  7075  7075 V BluetoothSapService: Close listen Socket : 
07-27 11:04:38.331  7075  7075 V BluetoothSapService: Close rfcomm Socket : 
07-27 11:04:38.331  7075  7075 V BluetoothSapService: Close sapd  Socket : 
07-27 11:04:38.332  7075  7075 V BluetoothSapService: Sap Service closeSapService out
07-27 11:04:38.332  7075  7075 V BluetoothSapService: Sap Service onDestroy
07-27 11:04:38.332  7075  7075 V BluetoothSapService: Sap Service closeSapService in
07-27 11:04:38.332  7075  7075 V BluetoothSapService: Close listen Socket : 
07-27 11:04:38.332  7075  7075 V BluetoothSapService: Close rfcomm Socket : 
07-27 11:04:38.332  7075  7075 V BluetoothSapService: Close sapd  Socket : 
,07-27 11:04:38.333  7075  7075 V BluetoothSapService: Sap Service closeSapService out
,07-27 11:04:38.429  7694  7694 I UEI.SmartControl: Supports setup maps: true
,07-27 11:04:38.432  7694  7694 D UEI.SmartControl: QS start statue = true Error code = 0
,07-27 11:04:38.433  7694  7694 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,07-27 11:04:38.433  7694  7694 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-27 11:04:38.433  7694  7694 I UEI.SmartControl: ### init IR Blaster...
07-27 11:04:38.438  7694  7694 D serial_port: Configuring serial port
07-27 11:04:38.442  7694  7694 E UEI.SmartControl: UEIBLaster setting for 616
,07-27 11:04:38.442  7694  7694 I UEI.SmartControl: Setting serial record hearder size = 2
07-27 11:04:38.442  7694  7694 I UEI.SmartControl: configuring settings for MAXQ616
07-27 11:04:38.442  7694  7694 I UEI.SmartControl: Get version...
07-27 11:04:38.459  7694  7733 D UEI.SmartControl: serial port data available: 21
,07-27 11:04:38.487  7694  7694 D UEI.SmartControl: MAXQ616 A2-X4 software.
,07-27 11:04:38.487  7694  7694 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-27 11:04:38.488  7694  7694 I UEI.SmartControl: QS saving settings...
07-27 11:04:38.489  7694  7694 D UEI.SmartControl: IR Blaster version: 25672567
,07-27 11:04:38.505  7694  7733 D UEI.SmartControl: serial port data available: 4
,07-27 11:04:38.540  7694  7736 I UEI.SmartControl: Device manager: loading config....
07-27 11:04:38.541  7694  7736 D UEI.SmartControl: ----------- loading internal config...
07-27 11:04:38.542  7694  7694 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-27 11:04:38.544  7694  7694 E UEI.SmartControl: Services init done
07-27 11:04:38.545  7694  7694 D UEI.SmartControl: QS Service init finished
07-27 11:04:38.547  7694  7694 D UEI.SmartControl: QS Service version name: 2.1.91
07-27 11:04:38.547  7694  7694 D UEI.SmartControl: QS Service version code: 201091
,07-27 11:04:38.551  7694  7694 D UEI.SmartControl: Service requested: Control
07-27 11:04:38.554  7694  7736 E UEI.SmartControl: Loading SETTINGS...
07-27 11:04:38.557  7694  7694 D UEI.SmartControl: Request IControl service: devices are loaded...
07-27 11:04:38.561  7694  7736 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-27 11:04:38.562  7012  7012 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-27 11:04:38.562  7694  7710 I UEI.SmartControl: ------ IControl API: 11
07-27 11:04:38.563  1036  1998 I ActivityManager: Killing 7012:com.lge.qremote/u0a112 (adj 15): empty #17
,07-27 11:04:38.564  7694  7710 I UEI.SmartControl: Registering callback...
07-27 11:04:38.580  7694  7735 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-27 11:04:38.581  7694  7735 D UEI.SmartControl: -----service ready thread exits
07-27 11:04:38.661  1036  1929 W libprocessgroup: failed to open /acct/uid_10112/pid_7012/cgroup.procs: No such file or directory
07-27 11:04:38.662  7694  7694 D UEI.SmartControl: Internal service binding...
,07-27 11:04:39.046  7075  7557 D bt_hci_bdroid: cleanup
,07-27 11:04:39.054  7075  7624 I bt_lpm  : LPM is already off!!!
07-27 11:04:39.055  7075  7622 W bt-btif : ag scb idx 1 not allocated
07-27 11:04:39.055  7075  7622 E bt-btif : BTA AG is already disabled, ignoring ...
07-27 11:04:39.055  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:04:39.055  7075  7622 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:04:39.055  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:04:39.055  7075  7622 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:04:39.055  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:04:39.055  7075  7622 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:04:39.055  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:04:39.055  7075  7622 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:04:39.056  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:04:39.056  7075  7622 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:04:39.056  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:04:39.056  7075  7622 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:04:39.056  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:04:39.056  7075  7622 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:04:39.056  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:04:39.056  7075  7622 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:04:39.056  7075  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:04:39.056  7075  7622 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:04:39.056  7075  7622 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-27 11:04:39.060  7075  7650 I bt_userial_mct: exiting userial_read_thread
07-27 11:04:39.060  7075  7650 D bt_userial_mct: Leaving userial_evt_read_thread()
07-27 11:04:39.060  7075  7557 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-27 11:04:39.060  7075  7624 I bt_vendor: hw_epilog_process
07-27 11:04:39.061  7075  7557 D bt_hci_bdroid: cleanup Finalizing cleanup
07-27 11:04:39.061  7075  7557 D bt_userial_mct: userial_close
07-27 11:04:39.061  7075  7557 E bt_userial_mct: pthread_join() FAILED result:3
07-27 11:04:39.061  7075  7557 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-27 11:04:39.068  7075  7557 D bt_hci_bdroid: set_power 0
07-27 11:04:39.068  7075  7557 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-27 11:04:39.068  7075  7557 I bt_vendor: bluetooth satus is on
07-27 11:04:39.068  7075  7557 I bt_vendor: bt-vendor : resetting BT status
07-27 11:04:39.068  7075  7557 I bt_vendor: Starting hciattach daemon
07-27 11:04:39.068  7075  7557 I bt_vendor: try to set false
,07-27 11:04:39.075  7075  7557 I bt_vendor: Starting hciattach daemon
07-27 11:04:39.075  7075  7557 I bt_vendor: try to set false
07-27 11:04:39.076  7075  7557 I bt_vendor: cleanup
07-27 11:04:39.077  7075  7622 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-27 11:04:39.077  7075  7557 I GKI_LINUX: GKI_exit_task 0 done
07-27 11:04:39.077  7075  7557 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-27 11:04:39.079  7075  7553 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-27 11:04:39.082  7075  7075 D HeadsetService: Received stop request...Stopping profile...
,07-27 11:04:39.088  7075  7075 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-27 11:04:39.088  7075  7075 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 11:04:39.088  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:39.093  1838  1838 D BluetoothHeadset: Proxy object disconnected
07-27 11:04:39.093  1838  1838 D BluetoothHeadset: Proxy object disconnected
07-27 11:04:39.093  1838  1838 D BluetoothHeadset: Proxy object disconnected
07-27 11:04:39.093  1036  1036 D BluetoothHeadset: Proxy object disconnected
07-27 11:04:39.094  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-27 11:04:39.096  7075  7075 D A2dpService: Received stop request...Stopping profile...
,07-27 11:04:39.099  7075  7609 D A2dpStateMachine: Exit Disconnected: -1
07-27 11:04:39.101  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-27 11:04:39.103  7075  7553 D BluetoothAdapterState: Stopping profile services that were post enabled
07-27 11:04:39.104  7075  7075 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-27 11:04:39.104  7075  7075 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 11:04:39.105  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:39.106  7075  7075 D HidService: Received stop request...Stopping profile...
07-27 11:04:39.106  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:39.108  1036  1036 D BluetoothA2dp: Proxy object disconnected
07-27 11:04:39.108  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,07-27 11:04:39.112  7075  7075 D HealthService: Received stop request...Stopping profile...
07-27 11:04:39.112  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:39.115  7075  7075 D HeadsetStateMachine: Unbinding service...
07-27 11:04:39.117  7075  7075 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 11:04:39.118  7075  7075 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 11:04:39.118  7075  7075 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 11:04:39.118  7075  7075 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 11:04:39.118  7075  7075 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-27 11:04:39.118  7075  7075 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 11:04:39.118  7075  7075 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-27 11:04:39.119  7075  7075 D PanService: Received stop request...Stopping profile...
,07-27 11:04:39.122  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:39.123  7075  7075 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 11:04:39.124  7075  7075 D BtGatt.GattService: Received stop request...Stopping profile...
07-27 11:04:39.124  7075  7075 D BtGatt.GattService: stop()
07-27 11:04:39.124  7075  7075 D BtGatt.AdvertiseManager: advertise clients cleared
07-27 11:04:39.125  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:39.127  7075  7075 D BluetoothMapService: Received stop request...Stopping profile...
07-27 11:04:39.127  7075  7075 D BluetoothMapService: stop()
07-27 11:04:39.129  7075  7075 D BluetoothMapEmailAppObserver: deinitObservers()
07-27 11:04:39.129  7075  7075 D BluetoothMapEmailAppObserver: removeReceiver()
07-27 11:04:39.129  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12cf6d2f
07-27 11:04:39.131  7075  7075 I BluetoothA2dpServiceJni: cleanupNative
,07-27 11:04:39.132  7075  7610 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-27 11:04:39.133  7075  7075 I GKI_LINUX: GKI_exit_task 2 done
07-27 11:04:39.133  7075  7075 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-27 11:04:39.134  7075  7075 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-27 11:04:39.134  7075  7075 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-27 11:04:39.134  7075  7075 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-27 11:04:39.134  7075  7075 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 11:04:39.134  7075  7075 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 11:04:39.135  7075  7075 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-27 11:04:39.135  7075  7075 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-27 11:04:39.138  7075  7075 V BluetoothMapService: Handler(): got msg=4
07-27 11:04:39.138  7075  7075 D BluetoothMapService: MAP Service closeService in
07-27 11:04:39.138  7075  7075 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 11:04:39.138  7075  7075 V BluetoothMapService: MAP Service closeService out
07-27 11:04:39.139  7075  7553 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-27 11:04:39.139  7075  7553 D BluetoothAdapterProperties: Setting state to 10
07-27 11:04:39.139  7075  7553 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-27 11:04:39.140  7075  7075 D BluetoothMapService: cleanup()
07-27 11:04:39.141  7075  7075 D BluetoothMapService: MAP Service closeService in
07-27 11:04:39.141  7075  7075 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 11:04:39.141  7075  7075 V BluetoothMapService: MAP Service closeService out
07-27 11:04:39.142  1036  1118 D BluetoothManagerService: Message: 60
07-27 11:04:39.142  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-27 11:04:39.142  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,07-27 11:04:39.146  7075  7553 I BluetoothAdapterState: Entering OffState
07-27 11:04:39.148  6964  7444 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-27 11:04:39.149  1838  2456 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:04:39.149  6964  7444 D BluetoothMap: onBluetoothStateChange: up=false
07-27 11:04:39.150  7075  7576 D HeadsetStateMachine: Exit Disconnected: -1
07-27 11:04:39.150  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 11:04:39.152  6964  7444 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:04:39.152  6964  7444 D BluetoothPan: onBluetoothStateChange on: false
07-27 11:04:39.153  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:04:39.153  1838  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:04:39.154  1838  2750 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-27 11:04:39.156  6964  7444 D BluetoothPbap: onBluetoothStateChange: up=false
07-27 11:04:39.157  6964  7444 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 11:04:39.158  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-27 11:04:39.158  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-27 11:04:39.160  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-27 11:04:39.160  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-27 11:04:39.160  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2526b05e mBinding = false
07-27 11:04:39.161  1036  1118 D BluetoothManagerService: Sending unbind request.
07-27 11:04:39.166  7075  7557 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,07-27 11:04:39.169  7075  7075 I GKI_LINUX: GKI_exit_task 1 done
07-27 11:04:39.169  7075  7075 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-27 11:04:39.169  7075  7075 I BluetoothServiceJni: cleanupNative: return from cleanup
07-27 11:04:39.169  7075  7075 I art     : --- WEIRD: removing null entry 248
07-27 11:04:39.169  7075  7075 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
07-27 11:04:39.170  7075  7075 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-27 11:04:39.171  7075  7075 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-27 11:04:39.172  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-27 11:04:39.174  7075  7075 I art     : System.exit called, status: 0
07-27 11:04:39.174  7075  7075 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-27 11:04:39.193   317  2135 V AudioFlinger: 7075 died, releasing its sessions
07-27 11:04:39.193   317  2135 V AudioFlinger:  pid 1838 @ 0
07-27 11:04:39.193   317  2135 V AudioFlinger:  pid 3467 @ 1
07-27 11:04:39.193   317  2135 V AudioFlinger:  pid 3467 @ 2
,07-27 11:04:39.200  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
07-27 11:04:39.200  1926  2110 D LGBluetoothAPIService: Message: 101
07-27 11:04:39.201  1926  2110 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
07-27 11:04:39.201  1926  2110 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
07-27 11:04:39.201  1926  2110 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
07-27 11:04:39.203  6964  6964 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-27 11:04:39.299  1036  1763 I ActivityManager: Process com.android.bluetooth (pid 7075) has died
07-27 11:04:39.300  1036  1763 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
07-27 11:04:39.300  1036  1763 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,07-27 11:04:39.311  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 11:04:39.314  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:39.315  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:39.316  6964  6964 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-27 11:04:39.316  6964  6964 D LGBluetoothEventManager: [BTUI] clear device connection state
07-27 11:04:39.318  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:39.319  1926  2110 D LGBluetoothAPIService: Message: 2
07-27 11:04:39.319  1926  2110 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
07-27 11:04:39.322  6964  6964 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-27 11:04:39.332  1588  1588 D BluetoothAdapter: 775230054: getState() :  mService = null. Returning STATE_OFF
,07-27 11:04:39.332  1588  1588 D BluetoothAdapter: 775230054: getState() :  mService = null. Returning STATE_OFF
07-27 11:04:39.369  1036  1990 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7768 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
07-27 11:04:39.371  6964  6964 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:04:39.440  7768  7768 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-27 11:04:39.441  7768  7768 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:04:39.441  7768  7768 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,07-27 11:04:39.442  7768  7768 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-27 11:04:39.463  7768  7768 D BluetoothAdapterApp: Loading JNI Library
,07-27 11:04:39.500  7768  7768 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@12d6ee37 Instance Count = 1
,07-27 11:04:39.516  7768  7768 D BluetoothAdapterApp: onCreate
07-27 11:04:39.543  7768  7768 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,07-27 11:04:39.544  7768  7768 D ProfileConfigQcom: Adding HeadsetService
07-27 11:04:39.544  7768  7768 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-27 11:04:39.544  7768  7768 D ProfileConfigQcom: Adding A2dpService
07-27 11:04:39.544  7768  7768 D ProfileConfigQcom: [BTUI] HidService is supported
07-27 11:04:39.545  7768  7768 D ProfileConfigQcom: Adding HidService
07-27 11:04:39.545  7768  7768 D ProfileConfigQcom: [BTUI] HealthService is supported
07-27 11:04:39.545  7768  7768 D ProfileConfigQcom: Adding HealthService
07-27 11:04:39.545  7768  7768 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-27 11:04:39.547  7768  7768 D ProfileConfigQcom: [BTUI] PanService is supported
07-27 11:04:39.547  7768  7768 D ProfileConfigQcom: Adding PanService
07-27 11:04:39.547  7768  7768 D ProfileConfigQcom: [BTUI] GattService is supported
,07-27 11:04:39.547  7768  7768 D ProfileConfigQcom: Adding GattService
07-27 11:04:39.547  7768  7768 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,07-27 11:04:39.548  7768  7768 D ProfileConfigQcom: Adding BluetoothMapService
07-27 11:04:39.548  7768  7768 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-27 11:04:39.549  7768  7768 V BluetoothPbapReceiver: PbapReceiver onReceive 
,07-27 11:04:39.550  7768  7768 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:04:39.551  7768  7768 V BluetoothPbapReceiver: ***********state = 10
,07-27 11:04:39.553  7768  7768 V LGMDMManagerInternal: Create singleton instance
07-27 11:04:39.651  2231  2231 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 11:04:39.653  7768  7768 D LGBluetoothAPIServer: [BTUI] onCreate()
07-27 11:04:39.653  7768  7768 D LGBluetoothAPIServer: [BTUI] onBind()
07-27 11:04:39.654  6964  6964 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,07-27 11:04:39.664  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-27 11:04:39.665  1926  2110 D LGBluetoothAPIService: Message: 100
07-27 11:04:39.665  1926  2110 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-27 11:04:39.677  6964  6964 D BluetoothPermissionRequest: onReceive
,07-27 11:04:39.680  6964  6964 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-27 11:04:39.680  6964  6964 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-27 11:04:39.683  6964  6964 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 11:04:39.688  7768  7768 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-27 11:04:39.692  7768  7768 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:04:39.696  7768  7768 V BluetoothSapReceiver: [BTUI] checkServiceStart
,07-27 11:04:39.697  7768  7768 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,07-27 11:04:39.697  7768  7768 V BluetoothSapReceiver: SapReceiver onReceive 
,07-27 11:04:39.699  7768  7768 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:04:39.699  7768  7768 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,07-27 11:04:39.703  7029  7029 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,07-27 11:04:41.041  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop,
,07-27 11:04:41.041  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:04:41.157  1588  1588 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,07-27 11:04:41.163  1036  1414 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-27 11:04:41.239  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-27 11:04:41.263  1036  1099 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7796 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-27 11:04:41.276  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,07-27 11:04:41.279  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
07-27 11:04:41.330  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-27 11:04:41.338  1036  1036 D administrator: Handling package changes for user 0
,07-27 11:04:41.368  7796  7796 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-27 11:04:41.458  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
07-27 11:04:41.458  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-27 11:04:41.468  7796  7796 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:04:41.468  7796  7796 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 11:04:41.498  1036  1098 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 11:04:41.506  1036  1098 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,07-27 11:04:41.515  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-27 11:04:41.517  2495  2495 V GmsNetworkLocationProvi: DISABLE
,07-27 11:04:41.546  1036  1098 D LocationProviderProxy: applying state to connected service
,07-27 11:04:41.548  2495  2495 E GCoreFlp: Bound FusedProviderService with LocationManager
,07-27 11:04:41.638  7796  7839 I Babel   : MmsConfig: mnc/mcc: 0/0
07-27 11:04:41.638  7796  7839 I Babel   : MmsConfig.loadMmsSettings
07-27 11:04:41.642  7796  7839 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,07-27 11:04:41.643  7796  7839 I Babel   : MmsConfig.loadFromDatabase
,07-27 11:04:41.665  7796  7839 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-27 11:04:41.666  7796  7839 I Babel   : MmsConfig.loadFromResources
07-27 11:04:41.668  7796  7839 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
07-27 11:04:41.669  7796  7839 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,07-27 11:04:41.691  7796  7796 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:41.694  7796  7838 W AudioCapabilities: Unsupported mime audio/evrc
,07-27 11:04:41.698  7796  7838 W AudioCapabilities: Unsupported mime audio/qcelp
07-27 11:04:41.702  7796  7838 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-27 11:04:41.720  7796  7838 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-27 11:04:41.723  7796  7838 W AudioCapabilities: Unsupported mime audio/qcelp
07-27 11:04:41.724  1803  7842 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-27 11:04:41.724  1803  7842 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
07-27 11:04:41.727  7796  7838 W AudioCapabilities: Unsupported mime audio/evrc
07-27 11:04:41.736  7146  7146 I AppUp4:CustModeStarterReceiver: onReceive
,07-27 11:04:41.742  1803  4768 I Icing   : updateResources: need to parse e{com.google.android.gms}
07-27 11:04:41.748  7146  7146 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2c658109
07-27 11:04:41.748  7146  7146 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 11:04:41.748  7146  7146 D AppUp4:CustFacade: isPhone : true
07-27 11:04:41.749  7146  7146 D AppUp4:CustModeStarterReceiver: begin check event
07-27 11:04:41.749  7146  7146 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,07-27 11:04:41.762  7796  7838 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-27 11:04:41.769  7796  7838 W VideoCapabilities: Unsupported mime video/divx
07-27 11:04:41.771  7796  7838 W VideoCapabilities: Unsupported mime video/divx311
07-27 11:04:41.772  7796  7838 W VideoCapabilities: Unsupported mime video/divx4
07-27 11:04:41.777  7796  7838 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-27 11:04:41.786  1036  1757 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7846 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
07-27 11:04:41.789  1036  1929 I ActivityManager: Killing 6984:com.lge.sync/1000 (adj 15): empty #17
,07-27 11:04:41.800  1036  1530 D WifiService: Client connection lost with reason: 4
07-27 11:04:41.807  7796  7838 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-27 11:04:41.818  7796  7838 W AudioCapabilities: Unsupported mime audio/eac3
07-27 11:04:41.818  7796  7838 W AudioCapabilities: Unsupported mime audio/ac3
07-27 11:04:41.819  7796  7838 W AudioCapabilities: Unsupported mime audio/g726
07-27 11:04:41.820  7796  7838 W AudioCapabilities: Unsupported mime audio/wma-voice
07-27 11:04:41.821  7796  7838 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-27 11:04:41.821  7796  7838 W AudioCapabilities: Unsupported mime audio/adpcm
07-27 11:04:41.823  7796  7838 W VideoCapabilities: Unsupported mime video/theora
07-27 11:04:41.824  7796  7838 W VideoCapabilities: Unsupported mime video/mjpg
,07-27 11:04:41.959  1036  1052 W libprocessgroup: failed to open /acct/uid_1000/pid_6984/cgroup.procs: No such file or directory
07-27 11:04:41.974  7846  7846 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 11:04:41.974  7846  7846 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:04:41.975  7846  7846 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-27 11:04:41.976  7846  7846 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
07-27 11:04:41.976  7846  7846 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,07-27 11:04:42.029  7846  7846 I SystemConfig: BUILD Country: EU
,07-27 11:04:42.029  7846  7846 I SystemConfig: BUILD Operator: OPEN
,07-27 11:04:42.067  1036  1887 I ActivityManager: Killing 7180:com.lge.email/u0a23 (adj 15): empty #17
,07-27 11:04:42.203  1036  1956 W libprocessgroup: failed to open /acct/uid_10023/pid_7180/cgroup.procs: No such file or directory
,07-27 11:04:42.277  1036  1990 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7870 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-27 11:04:42.284  7846  7865 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
07-27 11:04:42.284  7846  7865 I SystemConfig: existFile = false
07-27 11:04:42.284  7846  7865 I SystemConfig: canReadFile = false
07-27 11:04:42.284  7846  7865 I SystemConfig: systemFeature RCS result false
07-27 11:04:42.284  7846  7865 D SystemConfig: refreshRcsSupport() :false
07-27 11:04:42.301   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 387us total 18.983ms
,07-27 11:04:42.318   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 361us total 17.391ms
,07-27 11:04:42.346   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 445us total 25.579ms
,07-27 11:04:42.372  7870  7870 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 11:04:42.372  7870  7870 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-27 11:04:42.372  7870  7870 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-27 11:04:42.373  7870  7870 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-27 11:04:42.489  7870  7870 I AppConfig: Total System Memory = 2995761152
,07-27 11:04:42.502  7870  7870 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
07-27 11:04:42.611  1036  1897 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7892 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 11:04:42.613  1036  1897 I ActivityManager: Killing 7050:com.lge.formmanager/u0a26 (adj 15): empty #17
07-27 11:04:42.678  1036  1887 W libprocessgroup: failed to open /acct/uid_10026/pid_7050/cgroup.procs: No such file or directory
,07-27 11:04:42.898  7892  7892 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-27 11:04:43.020  7892  7892 D LgDataFeature: LgDataFeature() Constructor: none
,07-27 11:04:43.020  7892  7892 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:04:43.086  7892  7892 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,07-27 11:04:43.110  7892  7892 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-27 11:04:43.111  7892  7892 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-27 11:04:43.127  7892  7892 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,07-27 11:04:43.128  7892  7892 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
07-27 11:04:43.145  1036  1052 I ActivityManager: Killing 6535:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,07-27 11:04:43.234  1036  1757 W libprocessgroup: failed to open /acct/uid_1000/pid_6535/cgroup.procs: No such file or directory
,07-27 11:04:43.246  3516  6317 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,07-27 11:04:43.250  3516  6317 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1373f234 on behalf of 7892
,07-27 11:04:43.251  4595  7937 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-27 11:04:43.331  1036  1897 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7938 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-27 11:04:43.385  7892  7892 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
07-27 11:04:43.401  7892  7892 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-27 11:04:43.428  7938  7938 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-27 11:04:43.452  7938  7938 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
07-27 11:04:43.452  7938  7938 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-27 11:04:43.452  7938  7938 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-27 11:04:43.452  7938  7938 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-27 11:04:43.452  7938  7938 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
07-27 11:04:43.452  7938  7938 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,07-27 11:04:43.479  1036  2017 I ActivityManager: Killing 7216:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,07-27 11:04:43.509  1036  1757 W libprocessgroup: failed to open /acct/uid_10046/pid_7216/cgroup.procs: No such file or directory
,07-27 11:04:43.541  7694  7737 D UEI.SmartControl: Internal timer expired: 1
,07-27 11:04:43.541  7694  7737 D UEI.SmartControl: unbind internal service
,07-27 11:04:43.546  7694  7694 D UEI.SmartControl: Service.onUnbind: IControl
,07-27 11:04:43.547  7694  7694 D UEI.SmartControl: Service.onDestroy
07-27 11:04:43.548  7694  7694 D UEI.SmartControl: Lock is in USE false
07-27 11:04:43.548  7694  7694 D UEI.SmartControl: unbind internal service
07-27 11:04:43.550  7694  7694 D serial_port: close(fd = 25)
07-27 11:04:43.554  7694  7694 I UEI.SmartControl: Serial port is closed.
07-27 11:04:43.554  7694  7694 I UEI.SmartControl: Serial port is closed.
07-27 11:04:43.555  7694  7694 D UEI.SmartControl: Blaster closed
07-27 11:04:43.555  7694  7694 D UEI.SmartControl: Shut down QS...
07-27 11:04:43.555  7694  7694 D UEI.SmartControl: Stopping QS lib
07-27 11:04:43.555  7694  7694 D UEI.SmartControl: QS lib stop result = true
07-27 11:04:43.556  7694  7694 D UEI.SmartControl: Stopped QS lib
07-27 11:04:43.556  7694  7694 D UEI.SmartControl: Stopped file observer...
07-27 11:04:43.556  7694  7694 D UEI.SmartControl: QS shutdown complete
,07-27 11:04:43.727  1036  1639 V SIM_STK : Menu title from STK is T-Mobile
,07-27 11:04:43.762  4595  7937 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 509 ms] updated apps [took 509 ms] 
,07-27 11:04:44.064  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 11:04:44.065  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3119f02c added. We now have 6 listener(s)
,07-27 11:04:44.065  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:04:44.079  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:44.079  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d40daf5 added. We now have 7 listener(s)
07-27 11:04:44.079  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:44.080  6733  6802 I System.out: IsBluetoothEnabled
07-27 11:04:44.081  1036  1897 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:44.081  1036  1897 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
07-27 11:04:44.082  1036  1118 D BluetoothManagerService: Message: 2
07-27 11:04:44.086  6733  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:44.089  1036  1990 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:44.089  1036  1990 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-27 11:04:44.103  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 11:04:44.103  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 11:04:44.104  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-27 11:04:44.104  1036  1118 D BluetoothManagerService: Message: 1
07-27 11:04:44.104  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-27 11:04:44.131  1036  1118 D BluetoothManagerService: Message: 20
07-27 11:04:44.131  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aacea8c:true
,07-27 11:04:44.135  7768  7768 D BluetoothAdapterState: make
07-27 11:04:44.140  7768  7768 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-27 11:04:44.140  7768  7768 I bluedroid-qcom: init
07-27 11:04:44.141  7768  7982 I BluetoothAdapterState: Entering OffState
07-27 11:04:44.141  7768  7768 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-27 11:04:44.142  7768  7768 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-27 11:04:44.142  7768  7768 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 11:04:44.142  7768  7768 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-27 11:04:44.142  7768  7768 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-27 11:04:44.144  7768  7768 I bluedroid-qcom: get_profile_interface socket
07-27 11:04:44.144  7768  7768 I bluedroid-qcom: get_profile_interface map_client
,07-27 11:04:44.148  7768  7986 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-27 11:04:44.146  7985  7985 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:44.153  7768  7986 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-27 11:04:44.146  7985  7985 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:44.163  7985  7985 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-27 11:04:44.163  7985  7985 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-27 11:04:44.163  7985  7985 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,07-27 11:04:44.168  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-27 11:04:44.168  1036  1118 D BluetoothManagerService: Message: 40
07-27 11:04:44.168  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-27 11:04:44.170  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-27 11:04:44.173  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-27 11:04:44.173  7768  7784 I bluedroid-qcom: config_hci_snoop_log
07-27 11:04:44.175  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-27 11:04:44.175  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-27 11:04:44.175  7985  7985 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,07-27 11:04:44.189  7768  7982 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,07-27 11:04:44.193  7768  7986 D BluetoothAdapterProperties: Name is: G3
07-27 11:04:44.193  7768  7982 D BluetoothAdapterProperties: Setting state to 11
07-27 11:04:44.193  7768  7982 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-27 11:04:44.194  1036  1118 D BluetoothManagerService: Message: 60
07-27 11:04:44.194  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-27 11:04:44.194  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-27 11:04:44.196  7768  7982 I LGBluetoothServiceJni: classInitNative: succeeds
07-27 11:04:44.201  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,07-27 11:04:44.206  7985  7985 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-27 11:04:44.206  7985  7985 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-27 11:04:44.208  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:44.213  6964  6964 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,07-27 11:04:44.217  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:44.221  7768  7768 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 11:04:44.222  7768  7768 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:44.222  7768  7768 V BluetoothPbapReceiver: ***********state = 11
07-27 11:04:44.225  2231  2231 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 11:04:44.249  7768  7982 D BluetoothBondStateMachine: make
,07-27 11:04:44.253  6964  6964 D BluetoothPermissionRequest: onReceive
,07-27 11:04:44.253  7768  7982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16efff3c
07-27 11:04:44.253  7768  7982 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-27 11:04:44.253  7768  7982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16efff3c
07-27 11:04:44.254  7768  7982 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-27 11:04:44.254  7768  7982 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-27 11:04:44.255  7768  8002 I BluetoothBondStateMachine: StableState(): Entering Off State
07-27 11:04:44.257  6964  6964 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 11:04:44.258  7768  7982 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:04:44.263  7768  7768 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:04:44.266  7768  7768 D HeadsetService: Received start request. Starting profile...
07-27 11:04:44.267  7768  7768 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 11:04:44.267  7768  7768 D LGBluetoothHfpAdapter: Version 1.6
07-27 11:04:44.268  7768  7982 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:04:44.271  7768  7768 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 11:04:44.272  7768  7768 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 11:04:44.272  7768  7768 D HeadsetStateMachine: make
07-27 11:04:44.273  7768  7982 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:04:44.288  7768  7982 E BluetoothAdapterService: File transfer profiles supported!!
,07-27 11:04:44.294  7768  7982 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:04:44.299  7768  7982 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:04:44.304  7768  7982 E BluetoothAdapterService: File transfer profiles supported!!
,07-27 11:04:44.313  7768  7768 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:04:44.314  7768  7768 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:04:44.319  7768  7768 D HeadsetStateMachine: max_hf_connections = 1
07-27 11:04:44.319  7768  7768 I bluedroid-qcom: get_profile_interface handsfree
07-27 11:04:44.322  7768  7768 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-27 11:04:44.322  7768  7982 V LGMDMManager: Create singleton instance
07-27 11:04:44.322   317  1371 V AudioPolicyService: registerClient() client 0xb558a560, uid 1002
07-27 11:04:44.323   317  1372 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,07-27 11:04:44.323   317  1372 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 11:04:44.323   317  1372 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 11:04:44.323  7768  7768 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-27 11:04:44.323   317  2136 V AudioFlinger: registerClient() client 0xb14331c0, pid 7768
07-27 11:04:44.324   317  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:04:44.324   317  1365 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:04:44.324  3467  3482 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:04:44.324  7768  7768 V ToneGenerator: Create Track: 0xb4928a80
07-27 11:04:44.324  3467  3482 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:04:44.324  7768  7768 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-27 11:04:44.324  7768  7768 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-27 11:04:44.324   317  1367 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:04:44.324   317  1367 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:04:44.324  1036  1757 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:04:44.324   317  2135 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-27 11:04:44.324  1036  1757 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:04:44.324   317  2135 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-27 11:04:44.324   317  2135 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 11:04:44.324   317  2135 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 11:04:44.324  1588  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:04:44.324  1588  1607 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:04:44.325  7768  7784 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:04:44.325  7768  7784 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-27 11:04:44.325  7768  7784 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:04:44.325  7768  7784 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-27 11:04:44.325  1838  1854 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:04:44.325  1838  1854 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:04:44.325  1838  1854 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:04:44.325  1838  1854 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:04:44.325  1036  1929 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:04:44.325  1036  1929 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:04:44.325   317  1371 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 11:04:44.325  1588  3117 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:04:44.325  1588  3117 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:04:44.325  3467  3483 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:04:44.325  3467  3483 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:04:44.325   317  1372 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-27 11:04:44.325   317  1372 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-27 11:04:44.325   317  1372 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 11:04:44.325   317  1372 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 11:04:44.325  7768  7982 I BluetoothAdapterState: Entering PendingCom,mandState State: isTurningOn()=true, isTurningOff()=false
07-27 11:04:44.325  7768  7768 V AudioSystem: getLatency() output 2, latency 50
07-27 11:04:44.325  7768  7768 V AudioSystem: getFrameCount() output 2, frameCount 960
07-27 11:04:44.325  7768  7768 V AudioTrack: createTrack_l() output 2 afLatency 50
07-27 11:04:44.326   317  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 11:04:44.326   317  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 11:04:44.326   317  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 11:04:44.326   317  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 11:04:44.326   317  2136 V AudioFlinger: createTrack() lSessionId: 23
07-27 11:04:44.327  7768  7768 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-27 11:04:44.327   317  2136 V AudioFlinger: acquiring 23 from 7768, for 7768
07-27 11:04:44.327   317  2136 V AudioFlinger:  added new entry for 23
07-27 11:04:44.327  7768  7768 V ToneGenerator: ToneGenerator INIT OK, time: 135310
07-27 11:04:44.328  7768  7768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16efff3c
07-27 11:04:44.329  7768  8004 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
,07-27 11:04:44.330  7768  8004 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
,07-27 11:04:44.330  7768  8004 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 11:04:44.330  7768  8004 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-27 11:04:44.330   317   317 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7768
07-27 11:04:44.331   317   317 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-27 11:04:44.331   317   317 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-27 11:04:44.331   317   317 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-27 11:04:44.331   317   317 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-27 11:04:44.331   317   317 V voice   : voice_set_parameters: exit with code(0)
07-27 11:04:44.331   317   317 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-27 11:04:44.331   317   317 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-27 11:04:44.331  7768  7768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16efff3c
07-27 11:04:44.331   317   317 V msm8974_platform: platform_set_parameters: exit with code(0)
07-27 11:04:44.331   317   317 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-27 11:04:44.331   317   317 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-27 11:04:44.331   317   317 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-27 11:04:44.331  7768  7768 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 11:04:44.331  7768  7768 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 11:04:44.331  7768  8004 V ToneGenerator: ToneGenerator destructor
07-27 11:04:44.331  7768  7768 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 11:04:44.331  7768  8004 V ToneGenerator: stopTone
07-27 11:04:44.331  7768  8004 V ToneGenerator: Delete Track: 0xb4928a80
07-27 11:04:44.331  7768  7768 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:44.331  7768  7768 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-27 11:04:44.331  7768  8004 V AudioTrack: ~AudioTrack, releasing session id from 7768 on behalf of 7768
07-27 11:04:44.332   317  2135 V AudioFlinger: releasing 23 from 7768 for 7768
07-27 11:04:44.332   317  2135 V AudioFlinger:  decremented refcount to 0
07-27 11:04:44.332   317  2135 V AudioFlinger: purging stale effects
07-27 11:04:44.332   317  2135 V AudioPolicyService: AudioCommandThread() adding release output 2
07-27 11:04:44.332   317  2135 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-27 11:04:44.332   317  1272 V AudioPolicyService: AudioCommandThread() waking up
07-27 11:04:44.332   317  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
07-27 11:04:44.332   317  1272 V AudioPolicyManager: releaseOutput() 2
07-27 11:04:44.332   317  1272 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 11:04:44.332   317  2135 V AudioFlinger: PlaybackThread::Track destructor
07-27 11:04:44.332   317  2135 V AudioFlinger: removeClient_l() pid 7768, calling pid 317
07-27 11:04:44.333  7768  7768 D A2dpService: Received start request. Starting profile...
07-27 11:04:44.334  7768  7768 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 11:04:44.335  7768  7768 V Avrcp   : make
07-27 11:04:44.335  7768  7768 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-27 11:04:44.335  7768  7768 I bluedroid-qcom: get_profile_interface avrcp
07-27 11:04:44.336  1036  1051 W Process : Unable to open /proc/8006/status
07-27 11:04:44.348  7768  7768 V AudioManager: registerRemoteController: size of Media player list: 0
,07-27 11:04:44.350  7768  7768 E AudioManager: No RCC entry present to update
07-27 11:04:44.350  7768  7768 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-27 11:04:44.353  7768  7768 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-27 11:04:44.355  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-27 11:04:44.355  7768  7768 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-27 11:04:44.359  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-27 11:04:44.466  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
07-27 11:04:44.466  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
,07-27 11:04:44.601  1036  1897 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-27 11:04:44.626  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,07-27 11:04:44.635  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-27 11:04:44.636  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-27 11:04:44.637  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-27 11:04:44.637  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-27 11:04:44.637  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 11:04:44.638  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-27 11:04:44.638  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-27 11:04:44.638  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-27 11:04:44.638  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 11:04:44.638  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-27 11:04:44.639  7768  7768 I BluetoothA2dpServiceJni: classInitNative
,07-27 11:04:44.639  7768  7768 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 11:04:44.639  7768  7768 D A2dpStateMachine: make
07-27 11:04:44.641  7768  7768 I bluedroid-qcom: get_profile_interface a2dp
07-27 11:04:44.642  7768  8016 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-27 11:04:44.645  7768  7768 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-27 11:04:44.645  7768  7768 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-27 11:04:44.647  7768  7768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16efff3c
07-27 11:04:44.647  7768  8015 D A2dpStateMachine: Enter Disconnected: -2
07-27 11:04:44.648  7768  7768 I BluetoothHidServiceJni: classInitNative: succeeds
07-27 11:04:44.651  7768  7768 D HidService: Received start request. Starting profile...
07-27 11:04:44.651  7768  7768 I bluedroid-qcom: get_profile_interface hidhost
07-27 11:04:44.651  7768  7768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16efff3c
07-27 11:04:44.651  7768  7768 I BluetoothHealthServiceJni: classInitNative: succeeds
07-27 11:04:44.653  7768  7768 D HealthService: Received start request. Starting profile...
,07-27 11:04:44.659  7768  7768 I bluedroid-qcom: get_profile_interface health
07-27 11:04:44.659  7768  7768 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-27 11:04:44.659  7768  7768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16efff3c
07-27 11:04:44.660  7768  7768 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-27 11:04:44.662  7768  7768 D PanService: Received start request. Starting profile...
07-27 11:04:44.662  7768  7768 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 11:04:44.662  7768  7768 I bluedroid-qcom: get_profile_interface pan
07-27 11:04:44.671  7768  7768 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-27 11:04:44.671  7768  7768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16efff3c
,07-27 11:04:44.673  7768  7768 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-27 11:04:44.688  7768  7768 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 11:04:44.689  7768  7768 D BtGatt.GattService: Received start request. Starting profile...
07-27 11:04:44.689  7768  7768 D BtGatt.GattService: start()
07-27 11:04:44.689  7768  7768 I bluedroid-qcom: get_profile_interface gatt
07-27 11:04:44.691  7768  7768 D BtGatt.AdvertiseManager: advertise manager created
07-27 11:04:44.700  7768  7768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16efff3c
,07-27 11:04:44.702  7768  7768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16efff3c
,07-27 11:04:44.702  7768  7768 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-27 11:04:44.703  7768  7768 V BluetoothMapService: BluetoothMapBinder()
07-27 11:04:44.704  7768  7768 D BluetoothMapService: Received start request. Starting profile...
,07-27 11:04:44.704  7768  7768 D BluetoothMapService: start()
07-27 11:04:44.708  7768  7768 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-27 11:04:44.708  7768  7768 D BluetoothMapEmailAppObserver: createReceiver()
07-27 11:04:44.709  7768  7768 D BluetoothMapEmailAppObserver: initObservers()
07-27 11:04:44.709  7768  7768 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-27 11:04:44.719  7768  7768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16efff3c
07-27 11:04:44.720  7768  7768 D HeadsetStateMachine: Proxy object connected
07-27 11:04:44.721  7768  7768 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-27 11:04:44.721  7768  7768 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,07-27 11:04:44.724  7768  8004 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 11:04:44.725  7768  8004 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 11:04:44.726  7768  8004 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-27 11:04:44.727  7768  7768 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:04:44.730  7768  7768 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:04:44.733  7768  7768 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-27 11:04:44.737  7768  7768 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:04:44.740  7768  7768 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:04:44.740  7768  7768 V PanService: [BTUI] SIM Extra State :ABSENT
07-27 11:04:44.744  7768  7768 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-27 11:04:44.744  7768  7768 V BluetoothMapService: Handler(): got msg=1
07-27 11:04:44.745  7768  7982 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-27 11:04:44.745  7768  7982 I bluedroid-qcom: enable
07-27 11:04:44.745  7768  8023 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-27 11:04:44.745  7768  8023 I bt-btu  : btu_task pending for preload complete event
07-27 11:04:44.745  7768  7982 I bt_hci_bdroid: init
,07-27 11:04:44.750  7768  7982 I bt_vendor: bt-vendor : init
,07-27 11:04:44.750  7768  7982 I bt_vendor: bt-vendor : get_bt_soc_type
07-27 11:04:44.750  7768  7982 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-27 11:04:44.750  7768  7982 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-27 11:04:44.750  7768  7982 D bt_userial_mct: userial_init
07-27 11:04:44.751  7768  7982 D bt_hci_bdroid: set_power 1
07-27 11:04:44.751  7768  7982 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-27 11:04:44.751  7768  7982 I bt_vendor: Starting hciattach daemon
07-27 11:04:44.751  7768  7982 I bt_vendor: try to set true
07-27 11:04:44.746  8026  8026 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:44.746  8026  8026 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:44.784  8027  8027 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-27 11:04:44.865  8033  8033 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-27 11:04:44.878  8034  8034 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-27 11:04:44.905  8036  8036 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-27 11:04:44.929  8037  8037 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,07-27 11:04:44.941  8038  8038 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-27 11:04:44.953  8039  8039 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-27 11:04:44.982  8041  8041 I libmdmdetect: ESOC framework not supported
07-27 11:04:44.983  8041  8041 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-27 11:04:44.991  8041  8041 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,07-27 11:04:44.991  8041  8041 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-27 11:04:44.991  8041  8041 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-27 11:04:44.991  8041  8041 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-27 11:04:44.991  8041  8041 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-27 11:04:44.991  8041  8041 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-27 11:04:44.991  8041  8041 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-27 11:04:45.032  8041  8042 E QC-QMI  : qmi_client [8041] 15: failed to locate client data
07-27 11:04:45.035   478   478 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-27 11:04:45.036   478   478 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,07-27 11:04:45.078  8043  8043 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-27 11:04:45.093  8044  8044 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-27 11:04:45.108  7768  7982 I bt_vendor: bluetooth satus is on
07-27 11:04:45.108  7768  7982 D bt_hci_bdroid: preload
07-27 11:04:45.108  7768  8025 D bt_userial_mct: userial_open(port:0)
07-27 11:04:45.108  7768  8025 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,07-27 11:04:45.112  7768  8025 I bt_vendor: Done intiailizing UART
07-27 11:04:45.113  7768  8025 I bt_vendor: Done intiailizing UART
07-27 11:04:45.113  7768  8025 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-27 11:04:45.113  7768  8025 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-27 11:04:45.113  7768  8023 I bt-btu  : btu_task received preload complete event
07-27 11:04:45.115  7768  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-27 11:04:45.115  7768  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-27 11:04:45.117  7768  8046 D bt_userial_mct: Entering userial_read_thread()
07-27 11:04:45.120  7768  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-27 11:04:45.127  7768  8023 I         : BTE_InitTraceLevels -- TRC_HCI
07-27 11:04:45.127  7768  8023 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-27 11:04:45.127  7768  8023 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 11:04:45.127  7768  8023 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 11:04:45.127  7768  8023 I         : BTE_InitTraceLevels -- TRC_AVRC
07-27 11:04:45.127  7768  8023 I         : BTE_InitTraceLevels -- TRC_A2D
07-27 11:04:45.127  7768  8023 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 11:04:45.127  7768  8023 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 11:04:45.127  7768  8023 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-27 11:04:45.127  7768  8023 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 11:04:45.127  7768  8023 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 11:04:45.127  7768  8023 I         : BTE_InitTraceLevels -- TRC_SDP
07-27 11:04:45.128  7768  8023 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 11:04:45.128  7768  8023 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 11:04:45.128  7768  8023 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-27 11:04:45.128  7768  8023 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-27 11:04:45.230  7768  8023 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,07-27 11:04:45.230  7768  8023 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ad061 
,07-27 11:04:45.230  7768  8023 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ad061 
,07-27 11:04:45.289  7768  7986 E bt-btif : Calling BTA_HhEnable
,07-27 11:04:45.289  7768  7986 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,07-27 11:04:45.290  7768  7986 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-27 11:04:45.301  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-27 11:04:45.302  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-27 11:04:45.303  7768  7986 D BluetoothAdapterProperties: Name is: G3
07-27 11:04:45.306  7768  7986 D BluetoothAdapterProperties: Scan Mode:20
07-27 11:04:45.307  7768  7986 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 11:04:45.310  7768  7986 D bt_hci_bdroid: postload
,07-27 11:04:45.313  7768  7986 D bte_conf: Device ID record 1 : primary
07-27 11:04:45.313  7768  7986 D bte_conf:   vendorId            = 00c4
07-27 11:04:45.313  7768  7986 D bte_conf:   vendorIdSource      = 0001
07-27 11:04:45.313  7768  7986 D bte_conf:   product             = 13a1
07-27 11:04:45.313  7768  7986 D bte_conf:   version             = 1000
07-27 11:04:45.313  7768  7986 D bte_conf:   clientExecutableURL = 
07-27 11:04:45.313  7768  7986 D bte_conf:   serviceDescription  = 
07-27 11:04:45.313  7768  7986 D bte_conf:   documentationURL    = 
07-27 11:04:45.314  7768  8025 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 11:04:45.314  7768  7986 D bte_conf: bte_load_did_conf no section named DID2.
07-27 11:04:45.316  8051  8051 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:45.320  7768  7982 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-27 11:04:45.320  7768  7982 D BluetoothAdapterProperties: ScanMode =  20
07-27 11:04:45.322  7768  7982 D BluetoothAdapterProperties: State =  11
07-27 11:04:45.322  7768  7982 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-27 11:04:45.322  7768  7982 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-27 11:04:45.322  7768  7982 D BluetoothAdapterProperties: Setting state to 12
07-27 11:04:45.322  7768  7982 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-27 11:04:45.325  7768  7986 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-27 11:04:45.316  8051  8051 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:45.328  1036  1118 D BluetoothManagerService: Message: 60
07-27 11:04:45.328  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-27 11:04:45.328  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
07-27 11:04:45.329  7768  7982 I BluetoothAdapterState: Entering On State
07-27 11:04:45.340  7768  7982 D LGBluetoothServiceAdapter: [BTUI] OnState
07-27 11:04:45.340  7768  7982 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-27 11:04:45.340  7768  7982 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,07-27 11:04:45.347  7768  7982 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-27 11:04:45.366  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:45.366  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:45.366  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:45.366  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:04:45.366  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:45.366  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:45.366  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:45.366  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:04:45.374  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:04:45.377  7768  8025 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 11:04:45.377  7768  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-27 11:04:45.377  7768  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-27 11:04:45.377  7768  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-27 11:04:45.378  7768  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-27 11:04:45.378  7768  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-27 11:04:45.378  7768  8023 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-27 11:04:45.386  7768  7982 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,07-27 11:04:45.390  7768  8025 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 11:04:45.391  6964  6980 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-27 11:04:45.421  8056  8056 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,07-27 11:04:45.426  7768  8046 E bt_mct  : hci lib postload completed
07-27 11:04:45.426  7768  7986 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 11:04:45.427  7768  7986 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-27 11:04:45.427  7768  7986 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-27 11:04:45.431  1838  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:04:45.434  1838  1838 D BluetoothHeadset: Proxy object connected
,07-27 11:04:45.437  7768  8023 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:04:45.437  7768  8023 W bt-smp  : Plain text(LSB ~ MSB) = 5a cf 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:04:45.437  7768  8023 W bt-smp  : Encrypted text(LSB ~ MSB) = 82 5c 34 1c c3 27 e8 94 75 7a 82 e5 44 e8 d8 49 
07-27 11:04:45.437  7768  8023 W bt-btm  : Stopping oneshot timer
07-27 11:04:45.439  6964  6980 D BluetoothMap: onBluetoothStateChange: up=true
07-27 11:04:45.444  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 11:04:45.449  1036  1036 D BluetoothA2dp: Proxy object connected
,07-27 11:04:45.454  6964  7444 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-27 11:04:45.461  6964  6964 D BluetoothInputDevice: Proxy object connected
07-27 11:04:45.461  6964  6964 D HidProfile: Bluetooth service connected
,07-27 11:04:45.465  7768  8023 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:04:45.465  7768  8023 W bt-smp  : Plain text(LSB ~ MSB) = f8 48 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:04:45.465  7768  8023 W bt-smp  : Encrypted text(LSB ~ MSB) = b8 91 29 4e fe ad e5 84 cf f2 05 1f 35 7f f9 a7 
07-27 11:04:45.465  7768  8023 W bt-btm  : Stopping oneshot timer
07-27 11:04:45.466  6964  6980 D BluetoothPan: onBluetoothStateChange on: true
07-27 11:04:45.466  6964  6980 D BluetoothPan: onBluetoothStateChange call bindService
07-27 11:04:45.467  6964  6964 D BluetoothMap: Proxy object connected
07-27 11:04:45.467  6964  6964 D MapProfile: Bluetooth service connected
07-27 11:04:45.467  6964  6964 D BluetoothMap: getConnectedDevices()
07-27 11:04:45.469  7768  7784 V BluetoothMapService: getConnectedDevices()
07-27 11:04:45.470  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:04:45.470  6964  6964 D BluetoothHeadset: Proxy object connected
07-27 11:04:45.470  6964  6964 D HeadsetProfile: Bluetooth service connected
07-27 11:04:45.471  1838  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:04:45.471  1036  1036 D BluetoothHeadset: Proxy object connected
07-27 11:04:45.475  6964  6964 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 11:04:45.476  6964  6964 D PanProfile: Bluetooth service connected
,07-27 11:04:45.478  1838  1838 D BluetoothHeadset: Proxy object connected
07-27 11:04:45.480  1838  2750 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-27 11:04:45.481  7768  8023 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:04:45.481  7768  8023 W bt-smp  : Plain text(LSB ~ MSB) = 5a 09 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:04:45.481  7768  8023 W bt-smp  : Encrypted text(LSB ~ MSB) = 62 bb d2 08 02 85 dc f9 61 10 38 af 45 92 46 ae 
07-27 11:04:45.481  7768  8023 W bt-btm  : Stopping oneshot timer
07-27 11:04:45.484  1838  1838 D BluetoothHeadset: Proxy object connected
07-27 11:04:45.484  6964  7444 D BluetoothPbap: onBluetoothStateChange: up=true
07-27 11:04:45.486  6964  6980 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 11:04:45.489  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-27 11:04:45.489  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,07-27 11:04:45.493  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 11:04:45.493  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:45.494  7768  8023 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:04:45.494  7768  8023 W bt-smp  : Plain text(LSB ~ MSB) = 99 84 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:04:45.494  7768  8023 W bt-smp  : Encrypted text(LSB ~ MSB) = b8 4f 8d 73 7f c1 c6 85 8d 9f bb 6c f8 6b 34 7a 
07-27 11:04:45.494  7768  8023 W bt-btm  : Stopping oneshot timer
07-27 11:04:45.495  1926  2110 D LGBluetoothAPIService: Message: 1
07-27 11:04:45.495  1926  2110 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-27 11:04:45.495  1926  2110 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
07-27 11:04:45.495  1926  2110 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
07-27 11:04:45.498  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-27 11:04:45.499  1036  1118 D BluetoothManagerService: Message: 40
07-27 11:04:45.499  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-27 11:04:45.500  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:45.500  6964  6964 D BluetoothA2dp: Proxy object connected
07-27 11:04:45.500  6964  6964 D A2dpProfile: Bluetooth service connected
07-27 11:04:45.505  7768  7768 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:45.505  7768  7768 D BluetoothMapService: STATE_ON
,07-27 11:04:45.505  7768  8023 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:04:45.505  7768  8023 W bt-smp  : Plain text(LSB ~ MSB) = 87 31 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:04:45.506  7768  8023 W bt-smp  : Encrypted text(LSB ~ MSB) = 8a ee 7f fe 95 4b 1e d7 5e bc 06 e2 f5 26 72 63 
07-27 11:04:45.506  7768  8023 W bt-btm  : Stopping oneshot timer
07-27 11:04:45.511  6964  6964 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-27 11:04:45.512  6964  6964 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-27 11:04:45.521  6964  6964 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:04:45.528  7768  7768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16efff3c
07-27 11:04:45.529  7768  7768 V BluetoothPbapService: Pbap Service onCreate
07-27 11:04:45.529  7768  7768 V BluetoothPbapService: Starting PBAP service
07-27 11:04:45.530  7768  7768 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-27 11:04:45.530  7768  7768 V BluetoothMapService: Handler(): got msg=1
07-27 11:04:45.531  7768  7768 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-27 11:04:45.531  7768  7768 V BluetoothPbapService: Pbap Service onBind
07-27 11:04:45.532  7768  7768 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:04:45.532  7768  7768 V BluetoothPbapService: state: 12
07-27 11:04:45.532  7768  8076 D BluetoothMapMasInstance: MAS initSocket()
07-27 11:04:45.533  7768  7768 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 11:04:45.533  7768  8076 D BluetoothMapMasInstance:   masId = 00
07-27 11:04:45.533  7768  8076 D BluetoothMapMasInstance:   msgTypes = 0e
07-27 11:04:45.533  7768  8076 D BluetoothMapMasInstance:   masName = SMS/MMS
07-27 11:04:45.533  7768  8076 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-27 11:04:45.533  7768  7768 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:45.533  7768  7768 V BluetoothPbapReceiver: ***********state = 12
07-27 11:04:45.535  1036  2017 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:45.536  7768  7768 V BluetoothPbapService: Handler(): got msg=1
07-27 11:04:45.536  6964  6964 D BluetoothPbap: Proxy object connected
07-27 11:04:45.536  6964  6964 D PbapServerProfile: Bluetooth service connected
07-27 11:04:45.537  7768  7768 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-27 11:04:45.537  7768  8076 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:04:45.538  2231  2231 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 11:04:45.538  7768  8077 V BluetoothPbapService: Pbap Service initSocket
07-27 11:04:45.538  2231  2231 D c       : Getting all permits...
07-27 11:04:45.538  2231  2231 D a       : Opening database...
07-27 11:04:45.539  1036  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:45.542  7768  8076 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-27 11:04:45.542  7768  8076 V BluetoothMapMasInstance: Succeed to create listening socket 
07-27 11:04:45.542  7768  8076 D BluetoothMapMasInstance: Accepting socket connection...
07-27 11:04:45.542  2231  2231 D a       : Opening database auth.proximity.permit_store...
07-27 11:04:45.542  7768  7986 D BluetoothAdapterProperties: Scan Mode:21
07-27 11:04:45.543  7768  7986 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-27 11:04:45.543  2231  2231 D a       : Closing database...
07-27 11:04:45.543  7768  8077 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:04:45.547  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:45.550  7768  8077 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-27 11:04:45.551  7768  8077 V BluetoothPbapService: Succeed to create listening socket 
07-27 11:04:45.551  7768  8077 V BluetoothPbapService: Accepting socket connection...
07-27 11:04:45.556  6964  6964 D BluetoothPermissionRequest: onReceive
,07-27 11:04:45.558  6964  6964 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-27 11:04:45.560  6964  6964 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 11:04:45.562  7768  7768 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-27 11:04:45.564  7768  7768 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-27 11:04:45.569  7768  7768 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,07-27 11:04:45.586  7768  7768 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 11:04:45.586  7768  7768 V BtOppService: onCreate
,07-27 11:04:45.590  7768  7768 V BluetoothOppNotification: send message
07-27 11:04:45.593  7768  7768 V BtOppService: Starting RfcommListener
07-27 11:04:45.600  7768  7768 D BluetoothOppPreference: Dumping Names:  
07-27 11:04:45.600  7768  7768 D BluetoothOppPreference: {}
07-27 11:04:45.600  7768  7768 D BluetoothOppPreference: Dumping Channels:  
07-27 11:04:45.600  7768  7768 D BluetoothOppPreference: {}
07-27 11:04:45.601  7768  8080 V BtOppService: Deleted complete outbound shares, number =  0
07-27 11:04:45.601  7768  7768 V BtOppService: onStartCommand
,07-27 11:04:45.602  7768  8083 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 11:04:45.602  7768  8080 V BtOppService: Deleted complete inbound failed shares, number = 0
07-27 11:04:45.604  7768  8080 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-27 11:04:45.604  7768  8083 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 11:04:45.605  7768  7768 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:45.605  7768  7768 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-27 11:04:45.605  7768  8080 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a8eee91 on behalf of 
07-27 11:04:45.605  7768  8083 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a3e0b8 on behalf of 
07-27 11:04:45.608  7768  7768 V BluetoothOppNotification: new notify threadi!
07-27 11:04:45.610  7768  7768 V BluetoothOppNotification: send delay message
07-27 11:04:45.610  7768  8083 V BluetoothOppNotification: update too frequent, put in queue
07-27 11:04:45.610  7768  7768 V BtOppService: start RfcommListener
07-27 11:04:45.611  7768  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-27 11:04:45.611  7768  8083 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 11:04:45.611  7768  8083 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 11:04:45.612  7768  8083 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10b1f1f6 on behalf of 
,07-27 11:04:45.613  7768  7768 V BtOppService: RfcommListener started
,07-27 11:04:45.613  7768  7768 V BtOppService: ContentObserver received notification
07-27 11:04:45.613  7768  7768 V BtOppService: ContentObserver received notification
07-27 11:04:45.613  7768  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2dc129f7 on behalf of 
07-27 11:04:45.614  7768  8085 V BtOppRfcommListener: Starting RFCOMM listener....
07-27 11:04:45.616  1036  2017 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:45.617  7768  8085 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:04:45.618  7768  8084 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-27 11:04:45.618  7768  8085 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
07-27 11:04:45.618  7768  8085 V BtOppRfcommListener: Started RFCOMM listener....
07-27 11:04:45.618  7768  8083 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 11:04:45.618  7768  8085 I BtOppRfcommListener: Accept thread started.
07-27 11:04:45.618  7768  8083 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 11:04:45.618  7768  8085 V BtOppRfcommListener: Accepting connection...
07-27 11:04:45.627  7768  7768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16efff3c
,07-27 11:04:45.627  7768  7768 V BluetoothFtpService: Ftp Service onCreate
07-27 11:04:45.627  7768  7768 I BluetoothFtpService: Ftp Service onCreate
07-27 11:04:45.627  7768  7768 V BluetoothFtpService: Ftp Service onStartCommand
07-27 11:04:45.627  7768  7768 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:45.628  7768  7768 V BluetoothFtpService: Starting Listening on sockets
07-27 11:04:45.628  7768  7768 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 11:04:45.628  7768  7768 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 11:04:45.628  7768  7768 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 11:04:45.628  7768  7768 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:04:45.628  7768  7768 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-27 11:04:45.628  7768  7768 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-27 11:04:45.630  7768  7768 V BluetoothFtpService: Handler(): got msg=1
07-27 11:04:45.631  7768  7768 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-27 11:04:45.631  7768  7768 V BluetoothFtpService: Ftp Service initSocket
07-27 11:04:45.633  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:45.634  7768  7768 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:04:45.638  7768  7768 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=80
07-27 11:04:45.638  7768  7768 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-27 11:04:45.639  7768  8086 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,07-27 11:04:45.655  7768  7768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16efff3c
,07-27 11:04:45.655  7768  7768 V BluetoothSapService: Sap Service onCreate
07-27 11:04:45.658  7768  7768 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:04:45.658  7768  7768 V BluetoothSapService: state: 12
07-27 11:04:45.658  7768  7768 V BluetoothSapService: Starting SAP server process
,07-27 11:04:45.656  8087  8087 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:45.661  7768  7768 V BluetoothSapService: SAP Service startRfcommListenerThread
07-27 11:04:45.656  8087  8087 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:45.663  7768  8088 V BluetoothSapService: Sap Service initRfcommSocket
07-27 11:04:45.667  1036  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:45.668  7768  8088 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:04:45.669  7768  8088 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=81
,07-27 11:04:45.669  7768  8088 V BluetoothSapService: Succeed to create listening socket 
07-27 11:04:45.669  7768  8088 V BluetoothSapService: Accepting socket connection...
,07-27 11:04:45.674  8087  8087 V BT_SAP  : Event pipe created
07-27 11:04:45.674  8087  8087 V BT_SAP  : create_server_socket qcom.sap.server
07-27 11:04:45.674  8087  8087 V BT_SAP  : created socket fd 6
07-27 11:04:45.753  1036  1763 I art     : Explicit concurrent mark sweep GC freed 25316(1240KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.484ms total 133.219ms
,07-27 11:04:45.754  7768  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,07-27 11:04:45.755  7768  8083 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29d60ed0 on behalf of 
,07-27 11:04:45.755  7768  8083 V BluetoothOppNotification: update too frequent, put in queue
07-27 11:04:45.757  7768  8083 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-27 11:04:45.758  7768  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d87dec9 on behalf of 
07-27 11:04:45.760  7768  8084 V BluetoothOppNotification: outbound: succ-0  fail-0
,07-27 11:04:45.762  7768  8084 V BluetoothOppNotification: outbound notification was removed.
07-27 11:04:45.762  7768  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 11:04:45.763  7768  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13149ce on behalf of 
07-27 11:04:45.763  7768  8084 V BluetoothOppNotification: inbound: succ-0  fail-0
,07-27 11:04:45.764  7768  8084 V BluetoothOppNotification: inbound notification was removed.
07-27 11:04:45.765  7768  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 11:04:45.765  7768  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29cd60ef on behalf of 
07-27 11:04:46.143  6733  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
07-27 11:04:46.143  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:46.143  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:46.143  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:04:46.143  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:46.143  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:46.143  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:46.143  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:04:46.155  6733  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:04:46.158  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:46.158  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25d2108a added. We now have 8 listener(s)
07-27 11:04:46.158  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:46.161  1036  2017 D WifiServiceImplEx: setWifiEnabled: false pid=6733, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-27 11:04:46.161  1036  2017 D WifiService: setWifiEnabled: false pid=6733, uid=10118
07-27 11:04:46.161  1036  2017 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-27 11:04:46.168  6733  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:46.171  1036  1763 D WifiServiceImplEx: setWifiEnabled: true pid=6733, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,07-27 11:04:46.172  1036  1763 D WifiService: setWifiEnabled: true pid=6733, uid=10118
07-27 11:04:46.172  1036  1763 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 11:04:46.201  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 11:04:46.202  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 11:04:46.202  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-27 11:04:46.204  1036  1525 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-27 11:04:46.204  1036  1525 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-27 11:04:46.213  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-27 11:04:46.213  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-27 11:04:46.213  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-27 11:04:46.213  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-27 11:04:46.213  1036  1525 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-27 11:04:46.213  1036  1525 E WifiHW  : unknown target_country: EU , set to default
07-27 11:04:46.213  1036  1525 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-27 11:04:46.213  1036  1525 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-27 11:04:46.213  1036  1525 I WifiUtil: gEnableBmps=1
,07-27 11:04:46.611  7768  7768 V BluetoothOppNotification: new notify threadi!
,07-27 11:04:46.611  7768  7768 V BluetoothOppNotification: send delay message
,07-27 11:04:46.616  7768  8102 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-27 11:04:46.618  7768  8102 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7d547fc on behalf of 
07-27 11:04:46.618  7768  8102 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-27 11:04:46.620  7768  8102 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-27 11:04:46.621  7768  8102 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3aa69e85 on behalf of 
07-27 11:04:46.621  7768  8102 V BluetoothOppNotification: outbound: succ-0  fail-0
07-27 11:04:46.623  7768  8102 V BluetoothOppNotification: outbound notification was removed.
07-27 11:04:46.623  7768  8102 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 11:04:46.624  7768  8102 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d1c34da on behalf of 
07-27 11:04:46.624  7768  8102 V BluetoothOppNotification: inbound: succ-0  fail-0
,07-27 11:04:46.629  7768  8102 V BluetoothOppNotification: inbound notification was removed.
,07-27 11:04:46.629  7768  8102 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 11:04:46.631  7768  8102 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37b91d0b on behalf of 
,07-27 11:04:46.920   313   891 D SoftapController: Softap fwReload - Ok
,07-27 11:04:46.929  1036  1525 E NetdConnector: NDC Command {82 softap fwreload wlan0 STA} took too long (690ms)
07-27 11:04:46.937   313   891 D CommandListener: Setting iface cfg
07-27 11:04:46.937   313   891 D CommandListener: Trying to bring down wlan0
,07-27 11:04:46.940   313   891 D CommandListener: Clearing all IP addresses on wlan0
,07-27 11:04:46.955  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-27 11:04:46.967  1036  1525 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,07-27 11:04:46.966  8110  8110 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:46.976  8110  8110 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-27 11:04:46.999  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:04:46.999  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:04:46.999  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 11:04:47.007  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-27 11:04:47.010  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:04:47.018  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-27 11:04:47.033  1036  1525 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-27 11:04:47.034  1036  1525 D WifiMonitor: connecting to supplicant
07-27 11:04:47.041  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:47.048  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 11:04:47.048  6964  6964 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 11:04:47.048  6964  6964 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 11:04:47.048  6964  6964 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 11:04:47.048  8110  8110 I wpa_supplicant: Successfully initialized wpa_supplicant
07-27 11:04:47.049  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-27 11:04:47.052  6964  6964 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 11:04:47.052  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-27 11:04:47.052  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 11:04:47.052  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 11:04:47.052  6964  6964 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 11:04:47.052  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-27 11:04:47.053  6964  6964 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 11:04:47.085  8110  8110 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-27 11:04:47.085  8110  8110 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,07-27 11:04:47.089  1036  1118 D Tethering: InitialState.processMessage what=4
07-27 11:04:47.102  1036  1887 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8127 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-27 11:04:47.104  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-27 11:04:47.148  8110  8110 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 11:04:47.226  8110  8110 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,07-27 11:04:47.238  1036  1897 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8149 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 11:04:47.245  8110  8110 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,07-27 11:04:47.248  8127  8147 W FormManager: Network not available. Please check & try again.
07-27 11:04:47.249  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-27 11:04:47.250  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-27 11:04:47.250  1036  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-27 11:04:47.250  1036  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-27 11:04:47.250  1036  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,07-27 11:04:47.250  1036  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-27 11:04:47.250  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-27 11:04:47.251  1036  1525 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-27 11:04:47.251  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:47.252  1036  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:47.252  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:47.253  1036  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:47.253  1036  1525 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-27 11:04:47.253  1036  1525 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-27 11:04:47.254  1036  1525 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-27 11:04:47.254  1036  1525 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-27 11:04:47.254  1036  1525 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-27 11:04:47.255  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:04:47.255  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:04:47.255  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 11:04:47.255  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:47.255  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:47.255  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:47.255  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:47.255  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 11:04:47.256  1036  1525 D WifiNative-wlan0: doBoolean: SET update_config 1
07-27 11:04:47.257  1036  1525 D WifiNative-wlan0: SET update_config 1: returned true
07-27 11:04:47.257  1036  1525 D WifiConfigStore: Loading config and enabling all networks 
07-27 11:04:47.257  1036  1525 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-27 11:04:47.257  1036  1525 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-27 11:04:47.258  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:47.258  1926  1926 D WfdService: Waiting for WifiP2p enabling
,07-27 11:04:47.261  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-27 11:04:47.262  1036  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-27 11:04:47.265  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:47.265  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:47.265  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:47.265  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:47.265  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:47.265  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:04:47.265  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:04:47.265  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:04:47.266  1036  1525 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
07-27 11:04:47.267  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:04:47.274  8127  8148 V FormManager: Network unavailable.
07-27 11:04:47.276  1036  1525 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-27 11:04:47.276  1036  1525 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-27 11:04:47.277  1036  1525 D WifiStateMachine: enableVerboseLogging : level 2
07-27 11:04:47.277  1036  1525 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-27 11:04:47.277  1036  1525 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-27 11:04:47.277  1036  1525 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-27 11:04:47.278  1036  1525 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-27 11:04:47.278  1036  1525 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-27 11:04:47.278  1036  1525 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-27 11:04:47.278  1036  1525 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-27 11:04:47.279  1036  1525 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-27 11:04:47.279  1036  1525 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,07-27 11:04:47.280  1036  1525 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-27 11:04:47.280  1036  1525 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-27 11:04:47.280  1036  1525 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-27 11:04:47.280  1036  1525 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
,07-27 11:04:47.281  1036  1525 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-27 11:04:47.281  1036  1525 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 11:04:47.281  1036  1525 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-27 11:04:47.281  8127  8148 V FormManager: Network unavailable.
07-27 11:04:47.282  1036  1525 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-27 11:04:47.282  1036  1525 D WifiNative-HAL: Setting external_sim to 1
07-27 11:04:47.282  1036  1525 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-27 11:04:47.282  1926  1926 D WfdsService: Supplicant Connection state is changed : true
07-27 11:04:47.283  1926  2309 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-27 11:04:47.283  1926  2309 D WfdsService: Set the WFDS Monitor: true
07-27 11:04:47.283  1926  2309 D WfdsMonitor: WfdsMonitorThread create
07-27 11:04:47.283  1036  1525 D WifiNative-wlan0: SET external_sim 1: returned true
07-27 11:04:47.283  1036  1525 I WifiNative-HAL: startHal
07-27 11:04:47.283  1036  1525 D wifi    : setting scan oui 0x9d2527a0
07-27 11:04:47.283  1926  2309 D WfdsMonitor: WFDS Monitor is created and started
07-27 11:04:47.283  1926  2309 D WfdsService: WiFi: Supplicant connection re-established
07-27 11:04:47.283  1036  1525 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 11:04:47.283  1036  1525 I WifiNative-HAL: startHal
07-27 11:04:47.283  1036  1525 D wifi    : setting scan oui 0x9d2527a0
07-27 11:04:47.283  1036  1525 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-27 11:04:47.284  1926  8169 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-27 11:04:47.284  1926  8169 E CtrlSupplicant: Succeed to open control connection
07-27 11:04:47.285  1926  8169 E CtrlSupplicant: Succeed to open monitor connection
07-27 11:04:47.285  1036  1525 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-27 11:04:47.286  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-27 11:04:47.286  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-27 11:04:47.286  1926  8169 D WfdsMonitor: Supplicant connection established
07-27 11:04:47.286  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-27 11:04:47.287  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-27 11:04:47.287  7796  7796 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:47.287  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-27 11:04:47.287  1926  2309 D WfdsService: Connected to the supplicant for wfds
07-27 11:04:47.287  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-27 11:04:47.287  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-27 11:04:47.288  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-27 11:04:47.288  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-27 11:04:47.288  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-27 11:04:47.288  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-27 11:04:47.288  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-27 11:04:47.288  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-27 11:04:47.289  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-27 11:04:47.289  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-27 11:04:47.289  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-27 11:04:47.289  8110  8110 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-27 11:04:47.289  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-27 11:04:47.289  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-27 11:04:47.289  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
0,7-27 11:04:47.290  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-27 11:04:47.291  1036  1525 E WifiNative: : [138,262,254 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-27 11:04:47.291  1036  1525 D WifiNative-wlan0: doBoolean: RECONNECT
07-27 11:04:47.291  1036  1525 D WifiNative-wlan0: RECONNECT: returned true
07-27 11:04:47.291  1036  1525 D WifiNative-wlan0: doString: [STATUS]
07-27 11:04:47.292  1036  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-27 11:04:47.292  1036  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,07-27 11:04:47.295  1036  1525 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-27 11:04:47.295  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 11:04:47.296  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
07-27 11:04:47.296  1036  1524 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.297  1036  1525 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-27 11:04:47.297  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
07-27 11:04:47.297  1036  1036 D RttService: SCAN_AVAILABLE : 3
07-27 11:04:47.298  1036  1525 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-27 11:04:47.298  1036  1544 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.298  1036  1543 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.298  1036  1543 I WifiNative-HAL: startHal
07-27 11:04:47.298  1036  1525 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-27 11:04:47.298  1036  1543 D wifi    : getting scan capabilities on interface[1] = 0x9d2527a0
07-27 11:04:47.298  1036  1543 D wifi    : failed to get capabilities : -3
07-27 11:04:47.298  1036  1543 E WifiScanningService: could not get scan capabilities
07-27 11:04:47.298  1036  1525 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
,07-27 11:04:47.299  1036  1525 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-27 11:04:47.299   313   891 D CommandListener: Setting iface cfg
07-27 11:04:47.299   313   891 D CommandListener: Trying to bring up p2p0
07-27 11:04:47.300  1036  1524 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-27 11:04:47.300  1036  1524 D LGWifiP2pService: P2pEnablingState
07-27 11:04:47.300  1036  1524 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.300  1036  1524 D LGWifiP2pService: P2p socket connection successful
07-27 11:04:47.300  1036  1524 D LGWifiP2pService: P2pEnabledState
07-27 11:04:47.300  1036  1525 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-27 11:04:47.300  1036  1525 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-27 11:04:47.300  1036  1525 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-27 11:04:47.301  8110  8110 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-27 11:04:47.302  1036  1525 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-27 11:04:47.302  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-27 11:04:47.302  1036  1525 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-27 11:04:47.302  1926  1926 D WfdsService: WifiP2pState is changed : true
07-27 11:04:47.302  1926  2309 D WfdsService: Receive the WFDS_ENABLE Method
07-27 11:04:47.302  1926  2309 D WfdsService: Set the WFDS Monitor: true
07-27 11:04:47.302  1926  2309 D WfdsService: Connected to the supplicant for wfds
07-27 11:04:47.302  1926  2309 D WfdsJNI : doCommand: WFDS_SET TRUE
07-27 11:04:47.302  1036  1525 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-27 11:04:47.302  1036  1525 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-27 11:04:47.302  8110  8110 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-27 11:04:47.303  8110  8110 E wpa_supplicant: disconnect_rssi_lvl: -100
07-27 11:04:47.303  1926  2309 D WfdsService: selectPreferredScanChannel [36]
07-27 11:04:47.303  1926  2309 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-27 11:04:47.303  1036  1524 D LGWifiP2pService: sending p2p connection changed broadcast
07-27 11:04:47.304  1036  1524 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-27 11:04:47.304  1036  1525 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
07-27 11:04:47.304  1036  1524 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-27 11:04:47.305  1036  1524 D WifiNative-p2p0: doBoolean: SET device_name G3
07-27 11:04:47.305  1036  1524 D WifiNative-p2p0: SET device_name G3: returned true
07-27 11:04:47.305  1036  1524 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-27 11:04:47.305  1036  1524 D LGWifiP2pService: before postfix = G3
07-27 11:04:47.305  1036  1524 D WifiServerServiceExt: postfix byte check : 2
07-27 11:04:47.305  1036  1524 D LGWifiP2pService: after postfix = G3
07-27 11:04:47.305  1926  1926 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-27 11:04:47.305  1036  1524 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-27 11:04:47.305  1036  1524 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-27 11:04:47.305  1036  1524 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-27 11:04:47.306  1926  1926 D WfdsService: isConnected: false
07-27 11:04:47.306  1036  1524 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-27 11:04:47.306  1036  1524 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-27 11:04:47.307  1036  1524 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-27 11:04:47.307  1036  1524 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,07-27 11:04:47.307  1036  1524 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-27 11:04:47.308  1036  1524 D WifiNative-HAL: p2pGetDeviceAddress
07-27 11:04:47.308  1036  1525 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
07-27 11:04:47.308  1036  1524 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-27 11:04:47.308  1036  1525 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
07-27 11:04:47.308  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-27 11:04:47.308  1036  1524 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-27 11:04:47.308  1036  1524 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-27 11:04:47.309  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-27 11:04:47.309  8110  8110 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:47.310  8110  8110 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-27 11:04:47.310  8110  8110 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:47.310  1036  1525 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-27 11:04:47.311  1926  1926 I WfdStateTracker: handleP2pThisDeviceChanged
07-27 11:04:47.311  1926  1926 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-27 11:04:47.311  1926  1926 D WfdsService: Update P2p Interface State: 3
07-27 11:04:47.311  8110  8110 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:47.311  1036  1525 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-27 11:04:47.311  1036  1524 D WifiNative-p2p0: P2P_FLUSH: returned true
07-27 11:04:47.311  1036  1524 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-27 11:04:47.311  1036  1525 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-27 11:04:47.312  1036  1524 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-27 11:04:47.312  1036  1524 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-27 11:04:47.312  1926  8169 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:04:47.312  1926  8169 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:04:47.312  1036  1524 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-27 11:04:47.312  1036  1524 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-27 11:04:47.313  1036  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 11:04:47.313  1036  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:47.313  1036  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:47.313  1036  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:47.313  1036  8164 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:04:47.313  1036  8164 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:47.313  1036  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:47.313  1036  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:47.313  1036  8164 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:04:47.313  1036  8164 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:47.313  1036  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:47.313  1036  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:47.312  1036  1525 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-27 11:04:47.315  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-27 11:04:47.320  1036  1,956 I ActivityManager: Killing 7238:com.android.chrome/u0a57 (adj 15): empty #17
,07-27 11:04:47.326  1036  1524 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-27 11:04:47.326  1036  1524 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-27 11:04:47.327  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-27 11:04:47.327  8110  8110 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:04:47.327  1036  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-27 11:04:47.327  1036  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:04:47.328  1036  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:04:47.328  1036  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:04:47.328  1036  1525 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-27 11:04:47.328  1036  1525 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-27 11:04:47.329  1036  1525 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-27 11:04:47.329  1036  1525 D WifiNative-wlan0: doBoolean: SCAN
07-27 11:04:47.329  1036  1525 D WifiNative-wlan0: SCAN: returned false
07-27 11:04:47.330  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=138302  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 11:04:47.343  8149  8149 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 11:04:47.431  1036  1524 D LGWifiP2pService: InactiveState
,07-27 11:04:47.431  1036  1524 D LGWifiP2pService: InactiveState{ when=-121ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,07-27 11:04:47.431  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-121ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.431  1036  1524 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-27 11:04:47.433  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-27 11:04:47.436  8110  8110 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:47.438  8110  8110 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-27 11:04:47.439  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:47.439  8110  8110 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:47.439  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:47.440  1036  8164 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 11:04:47.440  1036  8164 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:47.441  1036  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:47.441  1036  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:04:47.441  1036  8164 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:04:47.441  1036  8164 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:47.441  8110  8110 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:47.441  1036  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:47.441  1036  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,07-27 11:04:47.441  1036  1524 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-27 11:04:47.442  1036  8164 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,07-27 11:04:47.442  1036  8164 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:04:47.442  1036  1524 D LGWifiP2pService: InactiveState{ when=-129ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler },
07-27 11:04:47.442  1036  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,07-27 11:04:47.442  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-130ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.442  1036  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD,
07-27 11:04:47.442  1926  8169 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 11:04:47.442  1926  8169 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,07-27 11:04:47.443  1926  8169 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:04:47.444  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:04:47.444  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=138416  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 11:04:47.445  1036  1524 D LGWifiP2pService: InactiveState{ when=-12ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.445  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.445  1036  1524 D LGWifiP2pService: DefaultState{ when=-15ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.446  1036  1524 D LGWifiP2pService: InactiveState{ when=-15ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.446  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.446  1036  1524 D LGWifiP2pService: DefaultState{ when=-16ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.448  1036  1525 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:04:47.449  1036  1525 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:04:47.450  1036  1525 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:04:47.450  1036  1525 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:04:47.450  1926  2309 W WfdsService: DefaultState - msg [9441285] is not handled
07-27 11:04:47.450  1036  1525 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:04:47.451  1036  1524 D LGWifiP2pService: InactiveState{ when=-20ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.452  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-20ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.452  1036  1524 D LGWifiP2pService: DefaultState{ when=-22ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.454  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:47.454  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:47.454  1036  1524 D LGWifiP2pService: InactiveState{ when=-23ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.454  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-27 11:04:47.455  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-23ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.455  1036  1524 D LGWifiP2pService: DefaultState{ when=-23ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:47.455  1036  1036 E WifiServerServiceExt: No p2p device connected
07-27 11:04:47.460  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-27 11:04:47.460  1036  1897 W libprocessgroup: failed to open /acct/uid_10057/pid_7238/cgroup.procs: No such file or directory
,07-27 11:04:47.468  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:04:47.468  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
07-27 11:04:47.471  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:47.472  1036  1763 I ActivityManager: Killing 7256:com.lge.drmservice/u0a62 (adj 15): empty #17
07-27 11:04:47.520  1036  1887 W libprocessgroup: failed to open /acct/uid_10062/pid_7256/cgroup.procs: No such file or directory
,07-27 11:04:47.559  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 11:04:47.559  6964  6964 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 11:04:47.559  6964  6964 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 11:04:47.560  6964  6964 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 11:04:47.561  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-27 11:04:47.562  6964  6964 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 11:04:47.562  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-27 11:04:47.562  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 11:04:47.562  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 11:04:47.563  6964  6964 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 11:04:47.563  6964  6964 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 11:04:47.576  8149  8149 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 11:04:47.585  8127  8173 W FormManager: Network not available. Please check & try again.
07-27 11:04:47.590  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:04:47.598  8127  8174 V FormManager: Network unavailable.
07-27 11:04:47.601  8127  8174 V FormManager: Network unavailable.
,07-27 11:04:47.605  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:47.626  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 11:04:47.626  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-27 11:04:47.628  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:04:47.632  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:04:47.638  4297  8175 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-27 11:04:47.643  4297  8176 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 11:04:47.644  4297  8176 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 11:04:47.713  1036  1897 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8177 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-27 11:04:47.822  8177  8177 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-27 11:04:47.822  8177  8177 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-27 11:04:47.831  8177  8177 V [BNRBootReceiver]: Boot Receiver Return
07-27 11:04:47.832  8177  8177 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-27 11:04:47.880  1036  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,07-27 11:04:47.881  8110  8110 E wpa_supplicant: USIM:  scard_init function
07-27 11:04:47.882  8110  8110 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-27 11:04:47.885  1036  8164 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-27 11:04:47.885  1036  8164 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-27 11:04:47.885  1036  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
07-27 11:04:47.885  1036  8164 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-27 11:04:47.885  1036  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-27 11:04:47.885  1036  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
07-27 11:04:47.886  1036  1525 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
07-27 11:04:47.886  1036  1525 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
07-27 11:04:47.887  1036  1525 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
07-27 11:04:47.887  1036  1525 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
07-27 11:04:47.891  1036  1525 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-27 11:04:47.903  1036  2017 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8198 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 11:04:47.904  1036  2017 I ActivityManager: Killing 7280:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,07-27 11:04:47.907  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=138879  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-27 11:04:47.980  1036  1956 W libprocessgroup: failed to open /acct/uid_10085/pid_7280/cgroup.procs: No such file or directory
07-27 11:04:47.989  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:47.989  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:47.991  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:04:47.997  8110  8110 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-27 11:04:48.000  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-27 11:04:48.001  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.001  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.001  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-27 11:04:48.005  1036  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-27 11:04:48.005  1036  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-27 11:04:48.005  1036  8164 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-27 11:04:48.005  1036  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-27 11:04:48.006  1036  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:04:48.006  1036  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:04:48.008  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.008  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.008  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,07-27 11:04:48.009  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=138980  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-27 11:04:48.009  1036  1525 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:48.010  1036  1525 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:48.010  1036  1525 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:48.011  8110  8110 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 11:04:48.011  8110  8110 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 11:04:48.012  1036  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:04:48.012  1036  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:04:48.012  1036  8164 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-27 11:04:48.012  1036  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 11:04:48.012  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:48.012  1036  8164 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 11:04:48.012  1036  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-27 11:04:48.013  1036  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 11:04:48.013  1036  8164 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 11:04:48.013  1036  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:04:48.013  1036  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:04:48.013  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:48.013  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:48.014  1036  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:04:48.014  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:48.015  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138986  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-27 11:04:48.015  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138987  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-27 11:04:48.016  1036  1525 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138988
07-27 11:04:48.016  1036  1525 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138988
07-27 11:04:48.017  1036  1525 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138989
07-27 11:04:48.017  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138989
,07-27 11:04:48.018  1036  1525 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138990
07-27 11:04:48.019  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=138990  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-27 11:04:48.024  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.024  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.024  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,07-27 11:04:48.027  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=138999  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-27 11:04:48.029  8198  8198 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:04:48.030  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.030  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.031  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-27 11:04:48.031  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=139003  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-27 11:04:48.032  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=139004  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-27 11:04:48.032  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:04:48.032  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-27 11:04:48.033  1036  1525 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139004
07-27 11:04:48.033  1036  1525 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139005
07-27 11:04:48.034  1036  1525 D WifiNative-wlan0: doString: [STATUS]
07-27 11:04:48.034  1036  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:04:48.034  1036  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:04:48.034  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:48.035  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:48.035  1036  1525 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-27 11:04:48.036  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:48.037  1036  1525 I WifiServiceExtension: setVHTCapabilityType  : false
07-27 11:04:48.037  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:48.037  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:48.039  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:04:48.046  1036  1525 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-27 11:04:48.046  1036  1525 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
07-27 11:04:48.050  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.051  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.051  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-27 11:04:48.055  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:48.055  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-27 11:04:48.058  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:48.059  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.059  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.059  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-27 11:04:48.060  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:48.060  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:48.061  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:48.063  1036  1525 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-27 11:04:48.063  1036  1531 D ConnectivityService: Got NetworkAgent Messenger
07-27 11:04:48.063  1036  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:04:48.063  1036  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 11:04:48.063  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-27 11:04:48.063  1036  1531 D ConnectivityService: NetworkAgent connected
07-27 11:04:48.064  1036  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 11:04:48.064  1036  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 11:04:48.071  1036  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 11:04:48.071  1036  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 11:04:48.071  1036  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 11:04:48.072  1036  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 11:04:48.072  1036  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 11:04:48.075  8198  8198 D PluginManager: init()
07-27 11:04:48.080  1036  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 11:04:48.082   313   891 D CommandListener: Setting iface cfg
07-27 11:04:48.084  1036  1525 E WifiStateMachine: Start Dhcp Watchdog 3
,07-27 11:04:48.084  1036  8216 D DhcpStateMachine: StoppedState
07-27 11:04:48.084  1036  8216 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:48.084  1036  8216 D DhcpStateMachine: WaitBeforeStartState
07-27 11:04:48.085  1036  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=139056  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:04:48.085  1036  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=139057  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:04:48.087  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=139059  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:04:48.088  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:04:48.088  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-27 11:04:48.089  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:04:48.089  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-27 11:04:48.090  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:04:48.090  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-27 11:04:48.091  1036  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139062  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:04:48.091  1036  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139063  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:04:48.092  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139064  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:04:48.093  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14139] from screen [on:0 period:731472861] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 11:04:48.094  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:731472862] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 11:04:48.094  1036  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 11:04:48.098  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:48.098  1036  1531 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,07-27 11:04:48.099  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:48.099  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:48.100  1036  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:48.100  1036  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:48.101  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:48.101  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:48.101  1036  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-27 11:04:48.102  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=159,0,0
07-27 11:04:48.102  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=159,0,0
07-27 11:04:48.102  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-27 11:04:48.102  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-27 11:04:48.103  1036  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-27 11:04:48.103  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 0
07-27 11:04:48.103  1036  1525 D WifiNative-wlan0: SET ps 0: returned true
07-27 11:04:48.104  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-27 11:04:48.104  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-27 11:04:48.104  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-27 11:04:48.104  1036  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@11f5839d target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:48.105  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@11f5839d target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:48.105  1036  8216 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:48.105  1036  8216 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-27 11:04:48.105  1036  1525 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-27 11:04:48.106  1036  1525 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-27 11:04:48.106  1036  1525 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 11:04:48.107   313   891 D CommandListener: Setting iface cfg
07-27 11:04:48.107   313   891 D CommandListener: Trying to bring up wlan0
07-27 11:04:48.108  1036  1525 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-27 11:04:48.109  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:04:48.109  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-27 11:04:48.110  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,07-27 11:04:48.110  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,07-27 11:04:48.110  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:48.111  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:48.111  1036  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:48.112  1036  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:48.112  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:48.112  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:04:48.113  1036  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-27 11:04:48.113  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-27 11:04:48.114  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-27 11:04:48.114  1036  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:48.114  1036  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:48.114  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 11:04:48.114  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 11:04:48.115  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 11:04:48.115  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-27 11:04:48.115  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-27 11:04:48.115  1036  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-27 11:04:48.115  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 11:04:48.132  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
07-27 11:04:48.133  1036  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-27 11:04:48.134  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,07-27 11:04:48.134  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-27 11:04:48.135  1036  1525 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-27 11:04:48.135  1036  1531 D ConnectivityService: ignoring duplicate network state non-change
07-27 11:04:48.139  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:48.139  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:48.140  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:48.142  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.142  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.142  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-27 11:04:48.142  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-27 11:04:48.143  1036  1531 D ConnectivityService: Adding iface wlan0 to network 102
,07-27 11:04:48.152  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.152  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.152  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-27 11:04:48.154  1036  1525 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-27 11:04:48.157  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-27 11:04:48.160  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 1
,07-27 11:04:48.165  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:48.165  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:04:48.168  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:48.171  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:48.171  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-27 11:04:48.172  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:48.174  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.174  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.174  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-27 11:04:48.174  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-27 11:04:48.174  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.174  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:04:48.174  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-27 11:04:48.175  1036  1531 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-27 11:04:48.175  1036  1531 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,07-27 11:04:48.176  1036  1531 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
07-27 11:04:48.177   313   891 E Netd    : netlink response contains error (File exists)
07-27 11:04:48.177  1036  1531 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
07-27 11:04:48.178  1036  1531 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-27 11:04:48.178  1036  1531 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
07-27 11:04:48.178  1036  1531 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
07-27 11:04:48.179  1036  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-27 11:04:48.179  1036  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-27 11:04:48.179  1036  1531 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
07-27 11:04:48.179  1036  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
07-27 11:04:48.179  1036  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:04:48.179  1036  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:48.180  1036  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 11:04:48.180  1036  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:48.180  1036  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-27 11:04:48.180  1036  1531 D ConnectivityService: currentScore = 0, newScore = 20
07-27 11:04:48.180  1036  1531 D ConnectivityService:    accepting network in place of null
07-27 11:04:48.180  1036  1531 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:48.180  1036  8215 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:48.180  1036  8215 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-27 11:04:48.180  1036  1525 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:48.180  1036  8215 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:04:48.180  1036  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:04:48.180  1036  8215 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-27 11:04:48.182  1838  1838 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:48.183  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 11:04:48.184   313  8226 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-27 11:04:48.185  1036  1531 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnecte,dToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-27 11:04:48.185  1036  1531 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
07-27 11:04:48.185  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 11:04:48.187  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-27 11:04:48.188  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 11:04:48.188  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 11:04:48.188  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,07-27 11:04:48.191  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:04:48.191  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-27 11:04:48.192  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:48.195  1036  1523 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-27 11:04:48.197  1036  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:04:48.197  1036  1531 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-27 11:04:48.198  1036  1531 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-27 11:04:48.199  1036  1531 D ConnectivityService: validation of new default Network = false
07-27 11:04:48.199  1036  1531 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-27 11:04:48.199  1036  1531 D DSQN    : enableDataServiceNotify 
07-27 11:04:48.199  1036  1531 D DSQN    : start dsqn bin
,07-27 11:04:48.212  1036  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
07-27 11:04:48.212  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:48.212  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:48.212  1036  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:48.213  1588  2047 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 11:04:48.206  8227  8227 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:48.214  6733  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:04:48.214  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:48.214  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:48.214  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:48.214  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:48.214  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:48.214  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:04:48.214  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:04:48.206  8227  8227 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:48.215  6733  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:48.218  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:04:48.219  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:48.220  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:48.220  6733  6802 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-27 11:04:48.221  6733  6802 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-27 11:04:48.223  6733  6802 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@20367ac3 Bundle[{}]
07-27 11:04:48.224  6733  6802 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 11:04:48.224  6733  6802 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-27 11:04:48.225  6733  6802 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-27 11:04:48.226  6733  6802 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-27 11:04:48.226  6733  6802 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-27 11:04:48.227  8227  8227 E DSQN    : DSQN ssw
07-27 11:04:48.227  6733  6802 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-27 11:04:48.235  6733  6802 I System.out: Running OutgoingSocketThread
07-27 11:04:48.237  6733  8231 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 866)
,07-27 11:04:48.240  6733  8231 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47638
,07-27 11:04:48.240  6733  8231 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
07-27 11:04:48.242   313  8226 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-27 11:04:48.273   313  8226 D libc-netbsd: res_queryN name = clients3.google.com succeed
,07-27 11:04:48.302   313   890 D LGDataListener: argv[0]=dsqncommand
07-27 11:04:48.302   313   890 D LGDataListener: argv[1]=wlan0
07-27 11:04:48.302   313   890 D LGDataListener: argv[2]=1
07-27 11:04:48.302   313   890 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-27 11:04:48.303  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
,07-27 11:04:48.303  1036  1116 D DSQN    : start to monitor internet connection
07-27 11:04:48.307  1036  8216 D DhcpStateMachine: DHCPV4 request on wlan0
07-27 11:04:48.309  1036  8216 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-27 11:04:48.309  1036  8216 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-27 11:04:48.306  8234  8234 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:04:48.316  8234  8234 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-27 11:04:48.331  1036  8215 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 09:04:48 GMT], X-Android-Received-Millis=[1469610288330], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469610288301]}
07-27 11:04:48.331  1036  8215 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-27 11:04:48.332  1036  8215 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-27 11:04:48.332  1036  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
07-27 11:04:48.332  1036  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
07-27 11:04:48.332  1036  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:04:48.332  1036  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 11:04:48.332  1036  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 11:04:48.332  1036  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
07-27 11:04:48.332  1036  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
07-27 11:04:48.332  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:48.332  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:48.332  1036  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:48.333  1036  1531 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:48.333  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-27 11:04:48.333  1036  1525 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:48.333  1036  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:04:48.334  1588  2047 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 11:04:48.335  1838  1838 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:48.335  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 11:04:48.339  8234  8234 I dhcpcd  : version 5.5.6 starting
07-27 11:04:48.344  8234  8234 E dhcpcd  : get_duid: m
07-27 11:04:48.344  8234  8234 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-27 11:04:48.344  8234  8234 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,07-27 11:04:48.353  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:04:48.355  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:48.355  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:04:48.416  8234  8234 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-27 11:04:48.416  8234  8234 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-27 11:04:48.416  8234  8234 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-27 11:04:48.416  8234  8234 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-27 11:04:48.416  8234  8234 D dhcpcd  : wlan0: sending REQUEST (xid 0x6b7fe2f7), next in 3.95 seconds
,07-27 11:04:48.506  8234  8234 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,07-27 11:04:48.527  8198  8198 W ExternalStrings: load override strings
07-27 11:04:48.527  8198  8198 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 11:04:48.527  8198  8198 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,07-27 11:04:48.530  8198  8198 D StatusProvider: onCreate
,07-27 11:04:48.547  8234  8234 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,07-27 11:04:48.547  8234  8234 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-27 11:04:48.548  8234  8234 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-27 11:04:48.548  8234  8234 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-27 11:04:48.549  8234  8234 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-27 11:04:48.550  8234  8234 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-27 11:04:48.550  8234  8234 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-27 11:04:48.550  8234  8234 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,07-27 11:04:48.612  8198  8198 V Signer  : override build config not found
07-27 11:04:48.612  8198  8198 D Signer  : value of property debug is false
,07-27 11:04:48.650  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
07-27 11:04:48.651  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
07-27 11:04:48.651  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
07-27 11:04:48.651  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
07-27 11:04:48.651  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
07-27 11:04:48.651  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
07-27 11:04:48.652  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
07-27 11:04:48.652  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
07-27 11:04:48.652  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
07-27 11:04:48.652  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
07-27 11:04:48.652  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
07-27 11:04:48.652  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
07-27 11:04:48.653  8198  8198 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,07-27 11:04:48.663  8198  8198 V LGMDMManager: Create singleton instance
,07-27 11:04:48.716  8198  8198 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,07-27 11:04:48.776  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:04:48.778  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:04:48.785  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:48.791  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 11:04:48.826  1036  1963 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8268 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
07-27 11:04:48.827  1036  1963 I ActivityManager: Killing 7312:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,07-27 11:04:48.915  1036  8216 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-27 11:04:48.917  1036  8216 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-27 11:04:48.917  1036  8216 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 11:04:48.917  1036  8216 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-27 11:04:48.917  1036  8216 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-27 11:04:48.917  1036  8216 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-27 11:04:48.917  1036  8216 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-27 11:04:48.917  1036  8216 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-27 11:04:48.918  1036  8216 D DhcpStateMachine: RunningState
07-27 11:04:48.976  8198  8259 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-27 11:04:49.070  1036  1956 W libprocessgroup: failed to open /acct/uid_10093/pid_7312/cgroup.procs: No such file or directory
,07-27 11:04:49.128  8268  8268 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-27 11:04:49.160  8268  8268 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
07-27 11:04:49.202  8268  8268 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
07-27 11:04:49.203  8268  8268 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,07-27 11:04:49.203  8268  8268 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-27 11:04:49.204  8268  8268 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-27 11:04:49.204  8268  8268 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-27 11:04:49.206  8268  8268 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-27 11:04:49.211  8268  8268 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-27 11:04:49.218  8268  8268 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:49.220  8268  8268 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 11:04:49.234  8268  8268 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-27 11:04:49.236  8268  8268 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-27 11:04:49.238  6733  6802 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 867)
07-27 11:04:49.238  6733  6802 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 867)
07-27 11:04:49.238  6733  6802 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 867)
07-27 11:04:49.238  6733  6802 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 867)
07-27 11:04:49.240  8268  8268 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-27 11:04:49.240  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
07-27 11:04:49.243  6733  6802 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 872)
,07-27 11:04:49.243  6733  6802 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 872)
07-27 11:04:49.243  6733  6802 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 872)
,07-27 11:04:49.244  6964  6964 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-27 11:04:49.244  6733  6802 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 873)
07-27 11:04:49.246  6733  6802 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 875)
07-27 11:04:49.248  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:04:49.248  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:49.249  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:04:49.249  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@303746fb added. We now have 2 listener(s)
07-27 11:04:49.249  1036  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:49.253  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:04:49.253  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:04:49.253  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:04:49.253  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:49.253  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4be318 added. We now have 9 listener(s)
07-27 11:04:49.254  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:49.254  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:04:49.256  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:04:49.257  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:04:49.263  6733  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:04:49.263  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:49.263  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:49.263  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:49.263  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:49.263  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:49.263  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:04:49.263  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 11:04:49.265  6733  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:49.265  6733  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:04:49.265  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:04:49.265  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ec8ab56 added. We now have 3 listener(s)
07-27 11:04:49.266  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:49.266  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:49.268  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:49.269  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:04:49.269  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:04:49.269  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:04:49.270  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:49.270  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2957d7 added. We now have 10 listener(s)
07-27 11:04:49.270  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:49.270  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:49.270  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:49.270  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:49.270  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:49.270  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.270  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:04:49.270  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:04:49.270  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@303746fb removed from the list
07-27 11:04:49.270  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:49.270  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4be318 removed from the list
07-27 11:04:49.271  8268  8268 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:49.272  8268  8268 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:49.273  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:04:49.273  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:49.274  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.274  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.274  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.275  8268  8268 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 11:04:49.276  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:49.276  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:49.276  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:49.276  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4be318 not in the list
07-27 11:04:49.276  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.276  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.278  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:04:49.278  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:49.278  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:49.278  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2957d7 removed from the list
07-27 11:04:49.278  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:49.278  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.278  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.278  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:04:49.278  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ec8ab56 removed from the list
07-27 11:04:49.278  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 11:04:49.278  6964  6964 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 11:04:49.279  6964  6964 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 11:04:49.279  6964  6964 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 11:04:49.279  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:04:49.279  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23a818c4 added. We now have 2 listener(s)
07-27 11:04:49.279  1036  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:49.280  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-27 11:04:49.280  6964  6964 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 11:04:49.281  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-27 11:04:49.281  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 11:04:49.281  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 11:04:49.281  6964  6964 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 11:04:49.281  6964  6964 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-27 11:04:49.281  6964  6964 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 11:04:49.281  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:04:49.281  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:04:49.281  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:04:49.281  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:49.281  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11b673ad added. We now have 9 listener(s)
07-27 11:04:49.281  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:49.282  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 11:04:49.284  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:49.285  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:04:49.284  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:04:49.292  6733  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:04:49.292  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:49.292  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:49.292  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:49.292  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:49.292  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:49.292  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:04:49.292  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:04:49.294  6733  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:49.294  6733  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:04:49.295  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:04:49.295  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26c19a73 added. We now have 3 listener(s)
07-27 11:04:49.295  1036  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:49.296  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:49.297  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:49.298  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:49.300  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:04:49.300  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:04:49.300  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:04:49.301  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:49.301  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@256ffd30 added. We now have 10 listener(s)
07-27 11:04:49.301  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:49.301  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:04:49.301  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:04:49.301  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:04:49.301  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:04:49.304  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 11:04:49.304  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:49.309  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 11:04:49.310  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-27 11:04:49.312  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:04:49.312  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:04:49.314  6733  6802 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:04:49.315  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:49.315  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:49.317  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:49.317  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:49.317  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:49.317  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:49.318  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:49.318  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.318  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:04:49.318  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:04:49.318  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23a818c4 removed from the list
07-27 11:04:49.318  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:49.318  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11b673ad removed from the list
07-27 11:04:49.318  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:49.318  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.319  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.319  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.320  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-27 11:04:49.320  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:49.320  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:49.320  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11b673ad not in the list
07-27 11:04:49.320  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.320  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.321  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:04:49.321  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:49.321  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:49.321  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-27 11:04:49.321  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:49.321  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@256ffd30 removed from the list
07-27 11:04:49.321  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:49.321  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.322  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.322  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:04:49.322  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26c19a73 removed from the list
07-27 11:04:49.322  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:04:49.322  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d916acf added. We now have 2 listener(s)
07-27 11:04:49.322  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:49.324  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:04:49.324  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:04:49.324  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:04:49.325  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:49.325  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@308fbc5c added. We now have 9 listener(s)
07-27 11:04:49.325  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:49.325  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:04:49.327  8198  8259 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:04:49.327  8198  8259 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 11:04:49.327  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:04:49.333  8268  8268 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:49.333  8268  8268 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:49.333  8268  8268 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:04:49.333  6733  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:04:49.333  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:49.333  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:49.333  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:49.333  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:49.333  6733  6802 V io.jxcore.node.Conne,ctivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:49.333  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:04:49.333  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 11:04:49.336  6733  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:49.336  6733  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:04:49.337  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:49.338  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:04:49.338  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2057b03a added. We now have 3 listener(s)
07-27 11:04:49.338  1036  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:49.338  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:04:49.339  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:49.340  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:49.344  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:04:49.345  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:04:49.345  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 11:04:49.345  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:49.345  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e3e4eb added. We now have 10 listener(s)
07-27 11:04:49.345  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:49.345  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:04:49.347  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:04:49.347  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:04:49.347  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:04:49.347  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:04:49.353  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 11:04:49.353  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:04:49.353  1036  1897 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 11:04:49.359  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 11:04:49.360  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 11:04:49.362  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:04:49.362  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:04:49.364  6733  6802 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:04:49.364  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:49.364  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:49.364  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:49.364  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:49.364  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:49.364  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.364  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:04:49.364  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:04:49.365  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d916acf removed from the list
07-27 11:04:49.365  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:49.365  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@308fbc5c removed from the list
07-27 11:04:49.365  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:49.365  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.365  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.366  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.366  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:49.366  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:49.366  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:49.366  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@308fbc5c not in the list
07-27 11:04:49.366  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.366  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.367  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:49.368  8268  8268 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:49,.369  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:49.369  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:49.369  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:49.369  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:49.369  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e3e4eb removed from the list
07-27 11:04:49.369  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:49.369  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.369  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.369  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:04:49.369  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2057b03a removed from the list
07-27 11:04:49.370  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:04:49.370  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a009606 added. We now have 2 listener(s)
07-27 11:04:49.370  1036  1763 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:49.370  8268  8268 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:49.371  8268  8268 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:04:49.372  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:04:49.373  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:04:49.374  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:04:49.374  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:04:49.374  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:04:49.374  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:49.374  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e99e4c7 added. We now have 9 listener(s)
07-27 11:04:49.374  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:49.375  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:04:49.377  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:04:49.380  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:04:49.380  6733  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:04:49.380  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:49.380  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:49.380  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:49.380  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:49.380  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:49.380  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:04:49.380  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:04:49.382  6733  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:49.382  6733  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:04:49.382  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:04:49.382  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2888a21d added. We now have 3 listener(s)
07-27 11:04:49.382  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:49.384  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:49.385  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,07-27 11:04:49.385  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:04:49.385  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:04:49.385  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:49.385  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23000c92 added. We now have 10 listener(s)
07-27 11:04:49.385  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:49.385  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:49.385  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:04:49.385  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:04:49.385  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:04:49.385  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:04:49.387  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:49.388  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 11:04:49.389  1036  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:49.391  8268  8268 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:49.391  8268  8268 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:49.392  8268  8268 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:04:49.394  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:49.395  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 11:04:49.395  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:04:49.395  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 11:04:49.397  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-27 11:04:49.399  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:04:49.400  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:04:49.402  6733  6802 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:04:49.403  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:49.403  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:49.403  6733  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:49.403  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:49.403  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.403  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:04:49.403  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:04:49.404  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a009606 removed from the list
07-27 11:04:49.404  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:49.404  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e99e4c7 removed from the list
07-27 11:04:49.404  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:49.404  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.404  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.404  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.405  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:49.405  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:49.405  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:49.405  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e99e4c7 not in the list
07-27 11:04:49.405  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.405  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.405  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:49.406  6733  6802 D BluetoothLeScanner: could not find callback wrapper
07-27 11:04:49.406  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:04:49.406  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:49.406  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:49.406  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23000c92 removed from the list
07-27 11:04:49.406  6733  6802 I org.thali,project.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:49.406  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.406  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.406  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:04:49.406  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2888a21d removed from the list
07-27 11:04:49.407  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:04:49.407  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12924319 added. We now have 2 listener(s)
07-27 11:04:49.407  1036  1639 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:49.408  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:49.409  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:04:49.409  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:04:49.409  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:04:49.409  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:49.409  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@370e5fde added. We now have 9 listener(s)
07-27 11:04:49.409  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:49.410  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:04:49.411  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:04:49.415  8268  8268 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:49.415  6733  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:04:49.415  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:04:49.415  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:04:49.415  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:04:49.415  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:04:49.415  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:49.415  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:04:49.415  6733  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:04:49.415  8268  8268 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:49.416  8268  8268 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:04:49.416  6733  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:04:49.416  6733  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:04:49.417  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:04:49.417  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34e8f48c added. We now have 3 listener(s)
07-27 11:04:49.417  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:04:49.418  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:49.418  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:04:49.419  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:49.420  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:04:49.420  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:04:49.420  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:04:49.420  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:04:49.420  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31faf7d5 added. We now have 10 listener(s)
07-27 11:04:49.420  6733  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:04:49.420  6733  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:04:49.420  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:49.421  67,33  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:04:49.421  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:04:49.421  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:49.421  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.421  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:04:49.421  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:04:49.421  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12924319 removed from the list
07-27 11:04:49.421  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:49.421  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@370e5fde removed from the list
07-27 11:04:49.422  6733  6802 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:04:49.422  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:04:49.424  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.424  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.425  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:04:49.425  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:49.425  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:49.425  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:49.425  6733  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@370e5fde not in the list
07-27 11:04:49.425  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.425  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.426  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:04:49.426  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:04:49.426  6733  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:04:49.426  6733  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31faf7d5 removed from the list
07-27 11:04:49.426  6733  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:04:49.426  6733  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:04:49.426  6733  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:04:49.426  6733  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:04:49.427  6733  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34e8f48c removed from the list
07-27 11:04:49.428  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-27 11:04:49.428  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-27 11:04:49.428  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-27 11:04:49.428  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-27 11:04:49.428  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-27 11:04:49.428  6733  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-27 11:04:49.429  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:49.434  8268  8268 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.,STATE_CHANGE
07-27 11:04:49.434  8268  8268 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:49.434  8268  8268 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-27 11:04:49.440  6733  8311 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 881, name: My test thread name)
07-27 11:04:49.441  6733  8311 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 881, thread name: My test thread name)
07-27 11:04:49.441  6733  8311 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 881, name: My test thread name)
07-27 11:04:49.441  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:04:49.442  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:49.446  6733  8312 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 883, name: My test thread name)
07-27 11:04:49.446  6733  8312 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 883, thread name: My test thread name)
07-27 11:04:49.446  6733  8312 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 883, name: My test thread name)
,07-27 11:04:49.448  6733  6802 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 84
07-27 11:04:49.448  6733  6802 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 84
07-27 11:04:49.448  6733  6802 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-27 11:04:49.448  6733  6802 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-27 11:04:49.449  6733  6802 D com.test.thalitest.ThaliTestRunner: Total duration: 23885 ms
07-27 11:04:49.450  6733  6802 I jxcore-log: Total number of executed tests:  84
07-27 11:04:49.450  6733  6802 I jxcore-log: 
07-27 11:04:49.450  6733  6802 I jxcore-log: Number of passed tests:  84
07-27 11:04:49.450  6733  6802 I jxcore-log: 
07-27 11:04:49.450  6733  6802 I jxcore-log: Number of failed tests:  0
07-27 11:04:49.450  6733  6802 I jxcore-log: 
07-27 11:04:49.450  6733  6802 I jxcore-log: Number of ignored tests:  0
07-27 11:04:49.450  6733  6802 I jxcore-log: 
07-27 11:04:49.450  6733  6802 I jxcore-log: Total duration:  23885
07-27 11:04:49.450  6733  6802 I jxcore-log: 
07-27 11:04:49.451  6733  6802 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-27 11:04:49.451  6733  6802 I jxcore-log: 
07-27 11:04:49.451  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:04:49.453  6733  6802 I jxcore-log: Unit Test app is loaded
07-27 11:04:49.453  6733  6802 I jxcore-log: 
07-27 11:04:49.458  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:49.461  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:04:49.461  6733  6802 I jxcore-log: 
,07-27 11:04:49.465  8268  8268 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:49.466  8268  8268 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:49.466  6733  6733 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-27 11:04:49.467  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:04:49.467  6733  6802 I jxcore-log: 
07-27 11:04:49.468  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:04:49.468  6733  6802 I jxcore-log: 
07-27 11:04:49.469  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:04:49.469  6733  6802 I jxcore-log: 
07-27 11:04:49.470  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:04:49.470  6733  6802 I jxcore-log: 
07-27 11:04:49.470  8268  8268 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:04:49.471  8198  8259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
07-27 11:04:49.471  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-27 11:04:49.471  6733  6802 I jxcore-log: 
,07-27 11:04:49.474  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 11:04:49.474  6733  6802 I jxcore-log: 
07-27 11:04:49.475  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:49.475  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:04:49.476  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:04:49.476  6733  6802 I jxcore-log: 
07-27 11:04:49.477  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:04:49.477  6733  6802 I jxcore-log: 
07-27 11:04:49.478  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:04:49.478  6733  6802 I jxcore-log: 
07-27 11:04:49.479  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:04:49.479  6733  6802 I jxcore-log: 
07-27 11:04:49.480  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 11:04:49.480  6733  6802 I jxcore-log: 
07-27 11:04:49.481  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 11:04:49.481  6733  6802 I jxcore-log: 
07-27 11:04:49.481  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:04:49.482  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:04:49.482  6733  6802 I jxcore-log: 
07-27 11:04:49.482  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:04:49.482  6733  6802 I jxcore-log: 
07-27 11:04:49.483  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:04:49.483  6733  6802 I jxcore-log: 
,07-27 11:04:49.484  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:04:49.484  6733  6802 I jxcore-log: 
07-27 11:04:49.484  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:04:49.484  6733  6802 I jxcore-log: 
07-27 11:04:49.485  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:04:49.485  6733  6802 I jxcore-log: 
07-27 11:04:49.485  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:49.485  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:04:49.485  6733  6802 I jxcore-log: 
07-27 11:04:49.486  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:04:49.486  6733  6802 I jxcore-log: 
07-27 11:04:49.487  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:04:49.487  6733  6802 I jxcore-log: 
07-27 11:04:49.487  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:04:49.487  6733  6802 I jxcore-log: 
07-27 11:04:49.489  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:04:49.489  6733  6802 I jxcore-log: 
07-27 11:04:49.490  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:04:49.490  6733  6802 I jxcore-log: 
07-27 11:04:49.490  8268  8268 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:49.490  8268  8268 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:49.490  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:04:49.490  6733  6802 I jxcore-log: 
07-27 11:04:49.491  8268  8268 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:04:49.491  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:04:49.491  6733  6802 I jxcore-log: 
,07-27 11:04:49.491  6733  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:04:49.491  6733  6802 I jxcore-log: 
07-27 11:04:49.493  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:49.493  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:04:49.495  6733  6802 I jxcore-log: My device name is: LGE-LG-D855
07-27 11:04:49.495  6733  6802 I jxcore-log: 
07-27 11:04:49.496  8198  8259 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
07-27 11:04:49.496  8149  8149 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-27 11:04:49.499  8149  8149 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:04:49.500  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:49.504  8198  8259 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
07-27 11:04:49.504  8198  8259 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-27 11:04:49.505  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:49.505  8198  8259 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-27 11:04:49.505  8198  8259 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
07-27 11:04:49.506  8198  8259 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
07-27 11:04:49.509  8268  8268 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:49.509  8268  8268 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:49.510  8268  8268 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-27 11:04:49.511  8268  8268 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-27 11:04:49.511  8268  8268 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-27 11:04:49.514  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:04:49.514  8198  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:04:49.518  8198  8259 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
07-27 11:04:49.519  8149  8149 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-27 11:04:49.519  8149  8149 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 11:04:49.520  8198  8259 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
07-27 11:04:49.524  6964  6964 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:04:49.530  6964  6964 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:04:49.542  8268  8268 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:04:49.542  8268  8268 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:04:49.543  8268  8268 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-27 11:04:49.543  8268  8268 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-27 11:04:49.543  8268  8268 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-27 11:04:49.545  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,07-27 11:04:49.548  8268  8268 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-27 11:04:49.549  8268  8268 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-27 11:04:49.549  8268  8268 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,07-27 11:04:49.580  8268  8268 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:04:49.580  8268  8268 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 11:04:49.584  8268  8268 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-27 11:04:49.584  8268  8268 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-27 11:04:49.584  8268  8268 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-27 11:04:49.584  8268  8268 V SoundPool: doLoad: loading sample sampleID=1
07-27 11:04:49.585  8268  8268 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-27 11:04:49.587  7694  7694 D UEI.SmartControl: QS Service created
,07-27 11:04:49.596  7694  7694 I UEI.SmartControl: Service initServices...
07-27 11:04:49.596  7694  7694 D UEI.SmartControl: QS start get config
07-27 11:04:49.597  8268  8268 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-27 11:04:49.598  8268  8268 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-27 11:04:49.598  8268  8268 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-27 11:04:49.606  8268  8268 V LGMDMManager: Create singleton instance
,07-27 11:04:49.608  8268  8320 V SoundPool: Start decode
07-27 11:04:49.608  8268  8320 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-27 11:04:49.609   317  1371 V MediaPlayerService: decode(23, 10857164, 17813)
07-27 11:04:49.609   317  1371 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-27 11:04:49.609   317  1371 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-27 11:04:49.609   317  1371 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-27 11:04:49.609   317  1371 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-27 11:04:49.609   317  1371 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-27 11:04:49.609   317  1371 V MediaPlayerService: player type = 3
07-27 11:04:49.609   317  1371 V AwesomePlayer: AwesomePlayer create()
07-27 11:04:49.609   317  1371 V AwesomePlayer: reset_l() 
07-27 11:04:49.609   317  1371 V AwesomePlayer: cancelPlayerEvents
07-27 11:04:49.609   317  1371 V AwesomePlayer: setAudioSink() 
07-27 11:04:49.609   317  1371 V AwesomePlayer: reset_l() 
07-27 11:04:49.609   317  1371 V AudioCache: notify(0xb14323c0, 8, 0, 0)
07-27 11:04:49.609   317  1371 V AudioCache: ignored
07-27 11:04:49.609   317  1371 V AwesomePlayer: cancelPlayerEvents
07-27 11:04:49.609   317  1371 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
07-27 11:04:49.609   317  1371 V AwesomePlayer: setDataSource_l dataSource
07-27 11:04:49.609   317  1371 V LGParserOSAL: SniffLGParser start
07-27 11:04:49.609   317  1371 V LGParserOSAL: MainType:5, SubType=0
07-27 11:04:49.609   317  1371 V LGParserOSAL: #### check Mime : application/ogg
07-27 11:04:49.609   317  1371 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-27 11:04:49.609   317  1371 E MediaExtractor: Use LGExtractor :application/ogg 
07-27 11:04:49.638  1036  1525 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 11:04:49.639  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 11:04:49.639  1036  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 11:04:49.640  1036  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 11:04:49.640  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 11:04:49.640  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 11:04:49.641  1036  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
07-27 11:04:49.641  1036  1531 D ConnectivityService: identical MTU - not setting
07-27 11:04:49.641  1036  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-27 11:04:49.641  1036  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-27 11:04:49.641  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:04:49.641  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:04:49.642  1036  1531 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 11:04:49.643  1588  2047 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-27 11:04:49.649   317  1371 V LGParserOSAL: supported mime: application/ogg
07-27 11:04:49.649   317  1371 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-27 11:04:49.649   317  1371 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-27 11:04:49.649   317  1371 V AwesomePlayer: mBitrate = -1 bits/sec
07-27 11:04:49.649   317  1371 V AwesomePlayer: AudioTrack Setting
07-27 11:04:49.649   317  1371 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-27 11:04:49.649   317  1371 V AwesomePlayer: setAudioSource() 
07-27 11:04:49.649   317  1371 V MediaPlayerService: prepare
07-27 11:04:49.649   317  1371 V AwesomePlayer: prepareAsync_l() 
07-27 11:04:49.649   317  1371 V MediaPlayerService: wait for prepare
07-27 11:04:49.657   317  8323 V AwesomePlayer: onPrepareAsyncEvent() 
07-27 11:04:49.657   317  8323 V AwesomePlayer: initAudioDecoder() 
07-27 11:04:49.657   317  8323 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 11:04:49.657   317  8323 V AudioSystem: isOffloadSupported()
07-27 11:04:49.657   317  8323 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-27 11:04:49.657   317  8323 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 11:04:49.657   317  8323 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 11:04:49.657   317  8323 V AwesomePlayer: getUseOffload() = 0 
07-27 11:04:49.657   317  8323 V OMXCodec: OMXCodec::Create
07-27 11:04:49.657   317  8323 V OMXCodec: findMatchingCodecs()
07-27 11:04:49.657   317  8323 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-27 11:04:49.657   317  8323 V OMXCodec: matchingCodecs.size()=1
07-27 11:04:49.657   317  8323 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
07-27 11:04:49.658   317  8323 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-27 11:04:49.658   317  8323 V LGCodecAdapter: LG Codec Adapter start
07-27 11:04:49.658   317  8323 V OMXCodec: OMXCodec Createtor
07-27 11:04:49.658   317  8323 V OMXCodec: setComponentRole
07-27 11:04:49.658   317  8323 V OMXCodec: configureCodec protected=0
07-27 11:04:49.658   317  8323 V LGCodecAdapter: called getLGCodecSpecificData
07-27 11:04:49.658   317  8323 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-27 11:04:49.658   317  8323 V LGCodecOSAL: Called LGconfigureCodecMETA
07-27 11:04:49.658   317  8323 V LGCodecOSAL: Called LGconfigureCodecMSG
07-27 11:04:49.658   317  8323 V LGCodecOSAL: Not support LGCodec
07-27 11:04:49.658   317  8323 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 11:04:49.658   317  8323 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-27 11:04:49.658   317  8323 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-27 11:04:49.658   317  8323 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-27 11:04:49.658   317  8323 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 11:04:49.658   317  8323 V AudioSystem: isOffloadSupported()
07-27 11:04:49.659   317  8323 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-27 11:04:49.659   317  8323 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 11:04:49.659   317  8323 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-27 11:04:49.659 ,  317  8323 V OMXCodec: init()
07-27 11:04:49.659   317  8323 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-27 11:04:49.659   317  8323 V OMXCodec: allocateBuffers
07-27 11:04:49.659   317  8323 V OMXCodec: allocateBuffersOnPort portIndex=0
07-27 11:04:49.659   317  8323 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-27 11:04:49.659   317  8323 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
07-27 11:04:49.659   317  8323 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
07-27 11:04:49.659   317  8323 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
07-27 11:04:49.659   317  8323 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
07-27 11:04:49.659   317  8323 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 11:04:49.659   317  8323 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 11:04:49.659   317  8323 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
07-27 11:04:49.659   317  8323 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
07-27 11:04:49.659   317  8323 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
07-27 11:04:49.659   317  8323 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
07-27 11:04:49.659   317  8323 V OMXCodec: init() mAsyncCompletion wait!!! 
07-27 11:04:49.667   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 11:04:49.667   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 11:04:49.667   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-27 11:04:49.667   317  8323 V OMXCodec: init() mAsyncCompletion wait!!! 
,07-27 11:04:49.677   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-27 11:04:49.677   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-27 11:04:49.677   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-27 11:04:49.677   317  8323 V OMXCodec: init() mAsyncCompletion wait free! 
07-27 11:04:49.677   317  8323 V AwesomePlayer: finishAsyncPrepare_l() 
07-27 11:04:49.677   317  8323 V AudioCache: notify(0xb14323c0, 5, 0, 0)
07-27 11:04:49.677   317  8323 V AudioCache: ignored
07-27 11:04:49.677   317  8323 V AudioCache: notify(0xb14323c0, 1, 0, 0)
07-27 11:04:49.677   317  8323 V AudioCache: prepared
07-27 11:04:49.677   317  1371 V AudioCache: wait - success
07-27 11:04:49.677   317  1371 V MediaPlayerService: start
07-27 11:04:49.677   317  1371 V AwesomePlayer: play_l() 
07-27 11:04:49.677   317  1371 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-27 11:04:49.677   317  1371 V AwesomePlayer: createAudioPlayer_l
07-27 11:04:49.677   317  1371 V AwesomePlayer: seekAudioIfNecessary_l() 
07-27 11:04:49.677   317  1371 V AwesomePlayer: startAudioPlayer_l() 
07-27 11:04:49.677   317  1371 D AudioPlayer: start of Playback, useOffload 0
07-27 11:04:49.677   317  1371 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 11:04:49.677   317  1371 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 11:04:49.678   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-27 11:04:49.678   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-27 11:04:49.678   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-27 11:04:49.679   317  8325 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 11:04:49.679   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 11:04:49.680   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
07-27 11:04:49.680   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
07-27 11:04:49.680   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
07-27 11:04:49.680   317  8325 V OMXCodec: [,OMX.google.vorbis.decoder] allocated buffer 0xb57bd380 on output port
07-27 11:04:49.680   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-27 11:04:49.680   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-27 11:04:49.680   317  1371 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-27 11:04:49.689  8316  8316 D AndroidRuntime: 
07-27 11:04:49.689  8316  8316 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 11:04:49.691  8316  8316 D AndroidRuntime: CheckJNI is OFF
,07-27 11:04:49.707   317  1371 V AudioCache: notify(0xb14323c0, 6, 0, 0)
07-27 11:04:49.707   317  1371 V AudioCache: ignored
07-27 11:04:49.707   317  1371 V MediaPlayerService: wait for playback complete
07-27 11:04:49.708   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.708   317  8326 V AudioCache: memcpy(0xabf08000, 0xb16f3000, 4096)
07-27 11:04:49.708   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.708   317  8326 V AudioCache: memcpy(0xabf09000, 0xb16f3000, 4096)
07-27 11:04:49.708   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.708   317  8326 V AudioCache: memcpy(0xabf0a000, 0xb16f3000, 4096)
07-27 11:04:49.709   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.709   317  8326 V AudioCache: memcpy(0xabf0b000, 0xb16f3000, 4096)
07-27 11:04:49.709   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.709   317  8326 V AudioCache: memcpy(0xabf0c000, 0xb16f3000, 4096)
07-27 11:04:49.709   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.709   317  8326 V AudioCache: memcpy(0xabf0d000, 0xb16f3000, 4096)
07-27 11:04:49.709   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.709   317  8326 V AudioCache: memcpy(0xabf0e000, 0xb16f3000, 4096)
07-27 11:04:49.710   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.710   317  8326 V AudioCache: memcpy(0xabf0f000, 0xb16f3000, 4096)
,07-27 11:04:49.712   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.712   317  8326 V AudioCache: memcpy(0xabf10000, 0xb16f3000, 4096)
07-27 11:04:49.713   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.713   317  8326 V AudioCache: memcpy(0xabf11000, 0xb16f3000, 4096)
07-27 11:04:49.713   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.713   317  8326 V AudioCache: memcpy(0xabf12000, 0xb16f3000, 4096)
07-27 11:04:49.713   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.713   317  8326 V AudioCache: memcpy(0xabf13000, 0xb16f3000, 4096)
07-27 11:04:49.713   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.713   317  8326 V AudioCache: memcpy(0xabf14000, 0xb16f3000, 4096)
07-27 11:04:49.713   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.714   317  8326 V AudioCache: memcpy(0xabf15000, 0xb16f3000, 4096)
07-27 11:04:49.714   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.714   317  8326 V AudioCache: memcpy(0xabf16000, 0xb16f3000, 4096)
07-27 11:04:49.714   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.714   317  8326 V AudioCache: memcpy(0xabf17000, 0xb16f3000, 4096)
07-27 11:04:49.714   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.714   317  8326 V AudioCache: memcpy(0xabf18000, 0xb16f3000, 4096)
07-27 11:04:49.714   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.714   317  8326 V AudioCache: memcpy(0xabf19000, 0xb16f3000, 4096)
07-27 11:04:49.714   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.714   317  8326 V AudioCache: memcpy(0xabf1a000, 0xb16f3000, 4096)
07-27 11:04:49.715   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.715   317  8326 V AudioCache: memcpy(0xabf1b000, 0xb16f3000, 4096)
07-27 11:04:49.715   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.715   317  8326 V AudioCache: memcpy(0xabf1c000, 0xb16f3000, 4096)
07-27 11:04:49.715   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.715   317  8326 V AudioCache: memcpy(0xabf1d000, 0xb16f3000, 4096)
07-27 11:04:49.715   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.715   317  8326 V AudioCache: memcpy(0xabf1e000, 0xb16f3000, 4096)
07-27 11:04:49.716   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.716   317  8326 V AudioCache: memcpy(0xabf1f000, 0xb16f3000, 4096)
07-27 11:04:49.716   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.716   317  8326 V AudioCache: memcpy(0xabf20000, 0xb16f3000, 4096)
07-27 11:04:49.716   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.716   317  8326 V AudioCache: memcpy(0xabf21000, 0xb16f3000, 4096)
07-27 11:04:49.716   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.716   317  8326 V AudioCache: memcpy(0xabf22000, 0xb16f3000, 4096)
07-27 11:04:49.717   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.717   317  8326 V AudioCache: memcpy(0xabf23000, 0xb16f3000, 4096)
,07-27 11:04:49.717   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.717   317  8326 V AudioCache: memcpy(0xabf24000, 0xb16f3000, 4096)
07-27 11:04:49.717   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.717   317  8326 V AudioCache: memcpy(0xabf25000, 0xb16f3000, 4096)
07-27 11:04:49.717   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.717   317  8326 V AudioCache: memcpy(0xabf26000, 0xb16f3000, 4096)
07-27 11:04:49.718   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.718   317  8326 V AudioCache: memcpy(0xabf27000, 0xb16f3000, 4096)
07-27 11:04:49.718   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.718   317  8326 V AudioCache: memcpy(0xabf28000, 0xb16f3000, 4096)
07-27 11:04:49.718   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.718   317  8326 V AudioCache: memcpy(0xabf29000, 0xb16f3000, 4096)
07-27 11:04:49.719   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.719   317  8326 V AudioCache: memcpy(0xabf2a000, 0xb16f3000, 4096)
07-27 11:04:49.719   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.719   317  8326 V AudioCache: memcpy(0xabf2b000, 0xb16f3000, 4096)
07-27 11:04:49.719   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.719   317  8326 V AudioCache: memcpy(0xabf2c000, 0xb16f3000, 4096)
07-27 11:04:49.720   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.720   317  8326 V AudioCache: memcpy(0xabf2d000, 0xb16f3000, 4096)
07-27 11:04:49.720   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.720   317  8326 V AudioCache: memcpy(0xabf2e000, 0xb16f3000, 4096)
07-27 11:04:49.720   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.720   317  8326 V AudioCache: memcpy(0xabf2f000, 0xb16f3000, 4096)
07-27 11:04:49.720   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.721   317  8326 V AudioCache: memcpy(0xabf30000, 0xb16f3000, 4096)
07-27 11:04:49.721   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.721   317  8326 V AudioCache: memcpy(0xabf31000, 0xb16f3000, 4096)
07-27 11:04:49.721   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.721   317  8326 V AudioCache: memcpy(0xabf32000, 0xb16f3000, 4096)
07-27 11:04:49.721   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.721   317  8326 V AudioCache: memcpy(0xabf33000, 0xb16f3000, 4096)
07-27 11:04:49.722   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.722   317  8326 V AudioCache: memcpy(0xabf34000, 0xb16f3000, 4096)
07-27 11:04:49.722   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.722   317  8326 V AudioCache: memcpy(0xabf35000, 0xb16f3000, 4096)
07-27 11:04:49.722   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.722   317  8326 V AudioCache: memcpy(0xabf36000, 0xb16f3000, 4096)
07-27 11:04:49.723   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.723   317  8326 V AudioCache: memcpy(0xabf37000, 0xb16f3000, 4096)
07-27 11:04:49.723   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.723   317  8326 V AudioCache: memcpy(0xabf38000, 0xb16f3000, 4096)
07-27 11:04:49.723   317  8326 V AudioCache: write(0xb16f3000, 4096)
07-27 11:04:49.723   317  8326 V AudioCache: memcpy(0xabf39000, 0xb16f3000, 4096)
07-27 11:04:49.723   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-27 11:04:49.724   317  8326 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-27 11:04:49.724   317  8326 V AwesomePlayer: postAudioEOS() 
07-27 11:04:49.724   317  8326 V AudioCache: write(0xb16f3000, 280)
07-27 11:04:49.724   317  8326 V AudioCache: memcpy(0xabf3a000, 0xb16f3000, 280)
07-27 11:04:49.725   317  8323 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-27 11:04:49.725   317  8323 V AwesomePlayer: onStreamDone
07-27 11:04:49.725   317  8323 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-27 11:04:49.725   317  8323 V AudioCache: notify(0xb,14323c0, 2, 0, 0)
07-27 11:04:49.725   317  8323 V AudioCache: playback complete
07-27 11:04:49.725   317  8323 V AwesomePlayer: pause_l() 
07-27 11:04:49.725   317  8323 V AudioCache: notify(0xb14323c0, 7, 0, 0)
07-27 11:04:49.725   317  8323 V AudioCache: ignored
07-27 11:04:49.725   317  8323 V AwesomePlayer: cancelPlayerEvents
07-27 11:04:49.725   317  1371 V AudioCache: wait - success
07-27 11:04:49.725   317  1371 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-27 11:04:49.725   317  8323 D AudioPlayer: Pause Playback at 1068125
07-27 11:04:49.725   317  1371 V AwesomePlayer: reset_l() 
07-27 11:04:49.725   317  1371 V AudioCache: notify(0xb14323c0, 8, 0, 0)
07-27 11:04:49.725   317  1371 V AudioCache: ignored
07-27 11:04:49.725   317  1371 V AwesomePlayer: cancelPlayerEvents
07-27 11:04:49.726   317  1371 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-27 11:04:49.726   317  1371 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-27 11:04:49.726   317  1371 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-27 11:04:49.726   317  1371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-27 11:04:49.726   317  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd380 on port 1
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-27 11:04:49.726   317  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-27 11:04:49.726   317  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-27 11:04:49.726   317  8325 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-27 11:04:49.726   317  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!,!
07-27 11:04:49.726   317  1371 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-27 11:04:49.726   317  1371 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-27 11:04:49.727   317  1371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-27 11:04:49.727   317  1371 D AudioPlayer: AudioPlayer releasing audio source
07-27 11:04:49.727   317  1371 D AudioPlayer: AudioPlayer done releasing audio source
07-27 11:04:49.727   317  1371 V AwesomePlayer: reset_l() 
07-27 11:04:49.727   317  1371 V AwesomePlayer: cancelPlayerEvents
07-27 11:04:49.727   317  1371 V AwesomePlayer: ~AwesomePlayer call
07-27 11:04:49.727   317  1371 V AwesomePlayer: reset_l() 
07-27 11:04:49.727   317  1371 V AwesomePlayer: cancelPlayerEvents
07-27 11:04:49.727  8268  8320 V SoundPool: close(31)
07-27 11:04:49.727  8268  8320 V SoundPool: pointer = 0x9fea1000, size = 205080, sampleRate = 48000, numChannels = 2
07-27 11:04:49.765  8268  8268 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-27 11:04:49.773  8268  8268 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
07-27 11:04:49.775  8268  8268 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4979
07-27 11:04:49.778  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:49.792  8316  8316 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-27 11:04:49.804  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:04:49.807  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:49.808  1036  1099 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
07-27 11:04:49.808  1036  1099 I ActivityManager: Killing 6733:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
07-27 11:04:49.837  1036  1366 I WindowState: WIN DEATH: Window{a94a708 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 11:04:49.837  1036  1530 D WifiService: Client connection lost with reason: 4
,07-27 11:04:49.843  1036  1366 D InputDispatcher: Window went away: Window{a94a708 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-27 11:04:50.004  7694  7694 I UEI.SmartControl: Supports setup maps: true
,07-27 11:04:50.007  7694  7694 D UEI.SmartControl: QS start statue = true Error code = 0
07-27 11:04:50.007  7694  7694 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-27 11:04:50.007  7694  7694 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-27 11:04:50.007  7694  7694 I UEI.SmartControl: ### init IR Blaster...
07-27 11:04:50.010  7694  7694 D serial_port: Configuring serial port
07-27 11:04:50.010  7694  7694 E UEI.SmartControl: UEIBLaster setting for 616
07-27 11:04:50.010  7694  7694 I UEI.SmartControl: Setting serial record hearder size = 2
07-27 11:04:50.010  7694  7694 I UEI.SmartControl: configuring settings for MAXQ616
07-27 11:04:50.010  7694  7694 I UEI.SmartControl: Get version...
07-27 11:04:50.020  1036  1099 I ActivityManager:   Force finishing activity ActivityRecord{ec9e2fd u0 com.test.thalitest/.MainActivity t40}
,07-27 11:04:50.030  7694  8340 D UEI.SmartControl: serial port data available: 21
,07-27 11:04:50.057  7694  7694 D UEI.SmartControl: MAXQ616 A2-X4 software.
,07-27 11:04:50.057  7694  7694 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-27 11:04:50.058  7694  7694 I UEI.SmartControl: QS saving settings...
,07-27 11:04:50.061  7694  7694 D UEI.SmartControl: IR Blaster version: 25672567
07-27 11:04:50.067   340   353 E GBMv2   : DFP En is all cleared set to be enabled
07-27 11:04:50.078  7694  8340 D UEI.SmartControl: serial port data available: 4
07-27 11:04:50.079  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:50.079  1036  1051 W ActivityManager: Spurious death for ProcessRecord{1295f917 6733:com.test.thalitest/u0a118}, curProc for 6733: null
,07-27 11:04:50.080  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
07-27 11:04:50.082  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{ec9e2fd u0 com.test.thalitest/.MainActivity t40 f}
07-27 11:04:50.082  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{ec9e2fd u0 com.test.thalitest/.MainActivity t40 f}
07-27 11:04:50.109  7694  8343 I UEI.SmartControl: Device manager: loading config....
07-27 11:04:50.110  7694  7694 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-27 11:04:50.112  7694  8343 D UEI.SmartControl: ----------- loading internal config...
07-27 11:04:50.114  7694  7694 E UEI.SmartControl: Services init done
07-27 11:04:50.114  7694  7694 D UEI.SmartControl: QS Service init finished
07-27 11:04:50.114  2018  2018 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
07-27 11:04:50.115  7694  7694 D UEI.SmartControl: QS Service version name: 2.1.91
07-27 11:04:50.115  7694  7694 D UEI.SmartControl: QS Service version code: 201091
07-27 11:04:50.115  1926  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
07-27 11:04:50.115  7694  7694 D UEI.SmartControl: Service requested: Control
07-27 11:04:50.116  1926  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3c83ac8c co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-27 11:04:50.116  2018  2018 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,07-27 11:04:50.118  1926  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
07-27 11:04:50.118  1926  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{22eb4fd5 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-27 11:04:50.121  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
07-27 11:04:50.124  2728  2728 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,07-27 11:04:50.128  2495  2652 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-27 11:04:50.131  7768  7768 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
07-27 11:04:50.131  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-27 11:04:50.131  4482  4482 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-27 11:04:50.131  4482  4482 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-27 11:04:50.131  4482  4482 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
07-27 11:04:50.131  4482  4482 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
07-27 11:04:50.131  4482  4482 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,07-27 11:04:50.131  4482  4482 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 11:04:50.131  4482  4482 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 11:04:50.131  4482  4482 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 11:04:50.131  4482  4482 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:04:50.132  4482  4482 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:04:50.132  4482  4482 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 11:04:50.132  4482  4482 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 11:04:50.132  1980  1980 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
07-27 11:04:50.133  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
07-27 11:04:50.134  2018  2112 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
07-27 11:04:50.139  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:04:50.145  7694  8343 E UEI.SmartControl: Loading SETTINGS...
07-27 11:04:50.149  7694  7694 D UEI.SmartControl: Request IControl service: devices are loaded...
07-27 11:04:50.150  7694  8343 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-27 11:04:50.156  1036  1414 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-27 11:04:50.167  4595  4595 I art     : Explicit concurrent mark sweep GC freed 8371(476KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 586us total 77.007ms
07-27 11:04:50.176  7694  8342 I UEI.SmartControl: Notify AllClients services are ready: 0
07-27 11:04:50.176  7694  8342 D UEI.SmartControl: -----service ready thread exits
,07-27 11:04:50.185  1036  1998 V SIM_STK : Menu title from STK is T-Mobile
07-27 11:04:50.192  1036  1098 W InputMethodInfo: Duplicated subtype definition found: , voice
,07-27 11:04:50.196  1036  1036 D administrator: Handling package changes for user 0
07-27 11:04:50.203  1890  1890 D ActionManagerService: notifyUserLog: 1000003
07-27 11:04:50.204  2728  4504 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
07-27 11:04:50.204  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
07-27 11:04:50.205  8268  8268 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,07-27 11:04:50.206  7694  7709 I UEI.SmartControl: ------ IControl API: 11
07-27 11:04:50.206  7694  7709 D UEI.SmartControl: File observer start...
07-27 11:04:50.206  7694  7709 E UEI.SmartControl: IR Port is disabled: false
07-27 11:04:50.206  7694  7709 D UEI.SmartControl: Starting file observer...
07-27 11:04:50.207  7694  7709 I UEI.SmartControl: Registering callback...
07-27 11:04:50.207  7694  7710 I UEI.SmartControl: ------ IControl API: 19
07-27 11:04:50.208  7694  7710 I UEI.SmartControl: Registering Services Ready callback...
07-27 11:04:50.208  7694  7710 I UEI.SmartControl: Notify client services are ready...
07-27 11:04:50.209  8268  8284 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-27 11:04:50.209  8268  8318 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
,07-27 11:04:50.209  8268  8318 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-27 11:04:50.210  8268  8268 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-27 11:04:50.210  7694  7694 D UEI.SmartControl: Internal service binding...
07-27 11:04:50.210  8268  8268 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-27 11:04:50.210  7694  7738 I UEI.SmartControl: ------ IControl API: 8
07-27 11:04:50.211  8268  8268 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-27 11:04:50.211  8268  8268 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-27 11:04:50.212  8268  8268 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-27 11:04:50.212  8268  8268 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-27 11:04:50.224  8268  8268 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
,07-27 11:04:50.226  8268  8268 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-27 11:04:50.230  2018  2018 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
07-27 11:04:50.231  2018  2018 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
07-27 11:04:50.232  2018  2018 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
07-27 11:04:50.234  1588  1635 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-27 11:04:50.234  1588  1635 D KeyguardModel: createShortcutInfo...
07-27 11:04:50.234  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
07-27 11:04:50.235  1890  1890 D ActionManagerService: notifyUserLog: 1000004
07-27 11:04:50.236  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,07-27 11:04:50.239  2728  4504 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
07-27 11:04:50.240  2728  2747 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-27 11:04:50.241  1588  1635 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-27 11:04:50.241  1588  1635 D KeyguardModel: createShortcutInfo...
07-27 11:04:50.245  1588  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 11:04:50.245  1588  1635 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262123
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , expire_time: 0
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , display: false
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , animation: false }
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262287
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , expire_time: 0
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , display: false
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , animation: false }
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469186101390
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , create_time: 1469186101943
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , expire_time: 0
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , display: false
07-27 11:04:50.247  2018  2018 I GBoardWebViewUtils: , animation: false }
07-27 11:04:50.252  2018  8345 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,07-27 11:04:50.254  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:50.256  1588  1635 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,07-27 11:04:50.256  8268  8268 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
07-27 11:04:50.256  1588  1635 D KeyguardModel: createShortcutInfo...
07-27 11:04:50.258  8268  8268 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
07-27 11:04:50.259  1588  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 11:04:50.259  1588  1635 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-27 11:04:50.261  1588  1635 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-27 11:04:50.261  1588  1635 D KeyguardModel: createShortcutInfo...
07-27 11:04:50.262  1588  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 11:04:50.263  1588  1635 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-27 11:04:50.264  1588  1635 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-27 11:04:50.264  1588  1635 D KeyguardModel: createShortcutInfo...
07-27 11:04:50.265  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,07-27 11:04:50.268  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:50.273  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
07-27 11:04:50.276  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:50.276  1588  1588 D KeyguardModel: handleShortcutListChanged...
07-27 11:04:50.276  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,07-27 11:04:50.278  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-27 11:04:50.278  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
07-27 11:04:50.293  1036  1956 V SIM_STK : Menu title from STK is T-Mobile
07-27 11:04:50.293  1036  1956 V SIM_STK : Menu title from STK is T-Mobile
07-27 11:04:50.317  1855  1855 D SplitUIManager: split_name #11 / not available #0
07-27 11:04:50.318  1855  1855 D SplitUIService: removed split : 
,07-27 11:04:50.334  1855  1855 D SplitUIManager: split_name #11 / not available #0
07-27 11:04:50.334  1855  1855 I SplitUIService: split app #11
07-27 11:04:50.345  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
,07-27 11:04:50.346  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:50.362  1588  1635 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-27 11:04:50.362  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:04:50.362  1588  1635 D KeyguardModel: createShortcutInfo...
07-27 11:04:50.364  2018  2018 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
07-27 11:04:50.365  1588  1635 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-27 11:04:50.365  1588  1635 D KeyguardModel: createShortcutInfo...
07-27 11:04:50.366  1588  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 11:04:50.366  1588  1635 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-27 11:04:50.366  1588  1635 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-27 11:04:50.366  1588  1635 D KeyguardModel: createShortcutInfo...
,07-27 11:04:50.368  1588  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 11:04:50.368  1588  1635 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-27 11:04:50.370  1588  1635 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-27 11:04:50.370  1588  1635 D KeyguardModel: createShortcutInfo...
07-27 11:04:50.371  1588  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 11:04:50.371  1588  1635 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-27 11:04:50.372  1588  1635 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-27 11:04:50.372  1588  1635 D KeyguardModel: createShortcutInfo...
07-27 11:04:50.387  1036  1887 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-27 11:04:50.388  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-27 11:04:50.388  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-27 11:04:50.388  1588  1588 D KeyguardModel: handleShortcutListChanged...
07-27 11:04:50.388  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-27 11:04:50.388  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-27 11:04:50.388  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-27 11:04:50.388  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-27 11:04:50.388  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 11:04:50.389  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-27 11:04:50.389  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-27 11:04:50.389  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-27 11:04:50.389  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 11:04:50.389  7768  7768 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-27 11:04:50.394  8198  8198 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
07-27 11:04:50.407  1036  1639 I ActivityManager: Killing 7354:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,07-27 11:04:50.442  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
07-27 11:04:50.442  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-27 11:04:50.442  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-27 11:04:50.478  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,07-27 11:04:50.483  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 11:04:50.484  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
07-27 11:04:50.485  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
07-27 11:04:50.486  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
07-27 11:04:50.487  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
07-27 11:04:50.502  1036  2017 W libprocessgroup: failed to open /acct/uid_10005/pid_7354/cgroup.procs: No such file or directory
,07-27 11:04:50.503  1803  1803 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
07-27 11:04:50.507  1036  1563 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
07-27 11:04:50.508  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3fa06ca7 u0 com.lge.launcher2/.Launcher t39} time:141491
07-27 11:04:50.511  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
07-27 11:04:50.511  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 11:04:50.514  2231  2231 I ConfigService: onCreate
07-27 11:04:50.514  2231  2231 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-27 11:04:50.515  2018  2174 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
07-27 11:04:50.515  2018  2174 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,07-27 11:04:50.517  1803  1803 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-27 11:04:50.523  2231  2231 I ConfigService: onBind returning update interface
07-27 11:04:50.523  2231  2231 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-27 11:04:50.523  2231  2231 I ConfigService: onBind returning config service
07-27 11:04:50.528  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,07-27 11:04:50.529  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-27 11:04:50.529  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 11:04:50.530  1036  1124 I art     : Explicit concurrent mark sweep GC freed 83641(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.803ms total 177.519ms
07-27 11:04:50.536  2018  2018 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
07-27 11:04:50.538  2564  2564 D [Concierge]Service: onStartCommand(). Type : 8
07-27 11:04:50.538  2564  2564 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
07-27 11:04:50.539  2564  2564 D [Concierge]Service: Update widget ID : 11
,07-27 11:04:50.540  2018  2018 D [Concierge]WidgetView: change position of spinner
07-27 11:04:50.543  2018  2018 I [Concierge]WidgetView: initWebView(). Time : 1469610290543
07-27 11:04:50.543  2564  2564 D [Concierge]Service: onStartCommand(). Type : 0
07-27 11:04:50.548  2231  2231 I ConfigService: onDestroy
07-27 11:04:50.549  1803  8351 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-27 11:04:50.575  8316  8316 D AndroidRuntime: Shutting down VM
,07-27 11:04:50.578  7146  7146 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
07-27 11:04:50.619  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8355 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,07-27 11:04:50.636  1036  1098 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 11:04:50.639  6052  8372 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
07-27 11:04:50.641  2346  8375 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-27 11:04:50.648  1803  8376 I PeopleContactsSync: CP2 sync disabled
,07-27 11:04:50.653  1036  1098 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-27 11:04:50.681  1036  1052 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8377 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-27 11:04:50.689  2018  2018 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 249209508
07-27 11:04:50.689  2018  2018 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
07-27 11:04:50.690  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
07-27 11:04:50.692  1803  4768 I Icing   : doRemovePackageData com.test.thalitest
07-27 11:04:50.692  2018  2018 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@24ee94b7
07-27 11:04:50.692  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
07-27 11:04:50.694  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-27 11:04:50.694  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-27 11:04:50.699  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
07-27 11:04:50.700  2018  2018 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
07-27 11:04:50.700  2018  2018 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-27 11:04:50.700  2018  2018 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1469610176559, New one : 1469610290543
07-27 11:04:50.700  2018  2018 D [Concierge]WidgetView: Unregister all receivers
07-27 11:04:50.700  2018  2018 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-27 11:04:50.700  1803  8365 W GmsApplication: Using Auth Proxy for data requests.
07-27 11:04:50.701  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-27 11:04:50.702  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 11:04:50.703  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
07-27 11:04:50.704  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
07-27 11:04:50.706  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
07-27 11:04:50.707  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
07-27 11:04:50.708  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
07-27 11:04:50.712  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 11:04:50.712  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-27 11:04:50.727  2231  2257 I art     : Explicit concurrent mark sweep GC freed 8277(494KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 643us total 17.620ms
,07-27 11:04:50.740  1036  2017 I ActivityManager: Killing 7796:com.google.android.talk/u0a72 (adj 15): empty #17
07-27 11:04:50.744  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,07-27 11:04:50.753  2018  2018 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
07-27 11:04:50.753  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
07-27 11:04:50.754  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 11:04:50.772  8377  8377 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 11:04:50.772  8377  8377 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:04:50.773  8377  8377 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,07-27 11:04:50.773  8377  8377 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-27 11:04:50.776  2018  2018 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1dc90c39 time:141759
07-27 11:04:50.839  1036  1963 W libprocessgroup: failed to open /acct/uid_10072/pid_7796/cgroup.procs: No such file or directory
,07-27 11:04:50.846  1803  8365 W GmsApplication: Using Auth Proxy for data requests.
07-27 11:04:50.852  8377  8377 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-27 11:04:50.876  8377  8377 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
07-27 11:04:50.898  1803  8353 I art     : Explicit concurrent mark sweep GC freed 24741(1678KB) AllocSpace objects, 18(288KB) LOS objects, 51% free, 30MB/62MB, paused 862us total 28.184ms
,07-27 11:04:50.899  1803  1815 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
07-27 11:04:50.901  1803  1815 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
07-27 11:04:50.902  1803  1815 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
07-27 11:04:50.923  1803  8353 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-27 11:04:50.924  8377  8377 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 11:04:50.924  1803  8353 E DriveAsyncService: disk I/O error (code 3850)
07-27 11:04:50.924  1803  8353 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 11:04:50.924  1803  8353 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-27 11:04:50.924  1803  8353 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
07-27 11:04:50.924  1803  8353 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-27 11:04:50.924  1803  8353 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-27 11:04:50.924  1803  8353 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
07-27 11:04:50.924  1803  8353 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
07-27 11:04:50.924  1803  8353 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
07-27 11:04:50.924  1803  8353 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
07-27 11:04:50.924  1803  8353 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
07-27 11:04:50.924  1803  8353 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
07-27 11:04:50.924  1803  8353 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 11:04:50.924  1803  8353 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:04:50.924  1803  8353 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
07-27 11:04:50.924  1803  8353 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 11:04:50.944  8377  8377 D LgDataFeature: LgDataFeature() Constructor: none
,07-27 11:04:50.944  8377  8377 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:04:50.997   280   792 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
